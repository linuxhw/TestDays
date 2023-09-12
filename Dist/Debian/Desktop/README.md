Debian - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 5970

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z790 UD                     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRock        | Z97M OC Formula             | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [f20b630cf8](https://linux-hardware.org/?probe=f20b630cf8) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [2b9d42ccc9](https://linux-hardware.org/?probe=2b9d42ccc9) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| MSI           | Z370-A PRO                  | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | [a97cdf671b](https://linux-hardware.org/?probe=a97cdf671b) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [5a4f7a4641](https://linux-hardware.org/?probe=5a4f7a4641) | Sep 05, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | [6c90c83d67](https://linux-hardware.org/?probe=6c90c83d67) | Sep 04, 2023 |
| Dell          | 0Y2MRG A00                  | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| MSI           | Z370-A PRO                  | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| MSI           | PRO X670-P WIFI             | [326596a962](https://linux-hardware.org/?probe=326596a962) | Sep 04, 2023 |
| Dell          | 0CU409                      | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| Gigabyte      | B85M-D3H                    | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| HP            | 1825                        | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9259a8f3f3](https://linux-hardware.org/?probe=9259a8f3f3) | Sep 02, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [91d7a53a1b](https://linux-hardware.org/?probe=91d7a53a1b) | Sep 01, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| Unknown       | Unknown                     | [3e3433226b](https://linux-hardware.org/?probe=3e3433226b) | Sep 01, 2023 |
| Dell          | 0GM819                      | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| Dell          | 0GM819                      | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| HP            | 1495                        | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| Gigabyte      | X570S AERO G                | [f367356391](https://linux-hardware.org/?probe=f367356391) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| Intel         | DG41TY AAE47335-301         | [1f8897e1a2](https://linux-hardware.org/?probe=1f8897e1a2) | Aug 29, 2023 |
| Lenovo        | 102F SDK0Q40081 WIN 3305... | [b6478eb429](https://linux-hardware.org/?probe=b6478eb429) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 82A2                        | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| BESSTAR Te... | TH50                        | [816347743d](https://linux-hardware.org/?probe=816347743d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [89e3ba3d7d](https://linux-hardware.org/?probe=89e3ba3d7d) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0150e826ac](https://linux-hardware.org/?probe=0150e826ac) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eef69bf730](https://linux-hardware.org/?probe=eef69bf730) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| ASUSTek       | Z170-A                      | [eadbc95dc7](https://linux-hardware.org/?probe=eadbc95dc7) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| HP            | 1495                        | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [3add2f8945](https://linux-hardware.org/?probe=3add2f8945) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Unknown       | Unknown                     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| HP            | 158A                        | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [815a77392c](https://linux-hardware.org/?probe=815a77392c) | Aug 25, 2023 |
| HP            | 18E4                        | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Unknown       | Unknown                     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| Intel         | DN2820FYK H24582-201        | [bb1402894c](https://linux-hardware.org/?probe=bb1402894c) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| MSI           | MAG B560 TORPEDO            | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acc3f87d28](https://linux-hardware.org/?probe=acc3f87d28) | Aug 23, 2023 |
| ASRock        | FM2A68M-HD+                 | [6811a2231b](https://linux-hardware.org/?probe=6811a2231b) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| HP            | 8835                        | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [5663c30e5e](https://linux-hardware.org/?probe=5663c30e5e) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [78bfc9060d](https://linux-hardware.org/?probe=78bfc9060d) | Aug 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [5a9553b9a2](https://linux-hardware.org/?probe=5a9553b9a2) | Aug 22, 2023 |
| Supermicro    | H12SSL-i                    | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| ASRock        | J4125B-ITX                  | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
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
| Medion        | MS-7728                     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
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
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [780b9a9e3a](https://linux-hardware.org/?probe=780b9a9e3a) | Aug 15, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [48ae062db8](https://linux-hardware.org/?probe=48ae062db8) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS            | [5297d177b4](https://linux-hardware.org/?probe=5297d177b4) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| Dell          | 0CT017                      | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| ASRock        | B550M PG Riptide            | [642c45af5d](https://linux-hardware.org/?probe=642c45af5d) | Aug 13, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| MSI           | G33M                        | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| Unknown       | AB07H                       | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| ASUSTek       | P5LD2-SE                    | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Unknown       | Unknown                     | [14114ca4aa](https://linux-hardware.org/?probe=14114ca4aa) | Aug 07, 2023 |
| Gigabyte      | H81M-S2H                    | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Unknown       | Unknown                     | [946d81eb9d](https://linux-hardware.org/?probe=946d81eb9d) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Foxconn       | 2ADA                        | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| Biostar       | B365MHC                     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| ASRock        | FM2A68M-DG3+                | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Lenovo        | 1036 NO DPK                 | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Intel         | H61                         | [7b2774c1a1](https://linux-hardware.org/?probe=7b2774c1a1) | Aug 03, 2023 |
| Intel         | H61                         | [8d450f7e6e](https://linux-hardware.org/?probe=8d450f7e6e) | Aug 03, 2023 |
| Gigabyte      | H510M H                     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H V2               | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [e0c07e2d0c](https://linux-hardware.org/?probe=e0c07e2d0c) | Aug 02, 2023 |
| ASUSTek       | Z170-A                      | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| ASRock        | X300-ITX                    | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [54462345a7](https://linux-hardware.org/?probe=54462345a7) | Jul 31, 2023 |
| Unknown       | Unknown                     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | H97M-PLUS                   | [940e14c90d](https://linux-hardware.org/?probe=940e14c90d) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 0K240Y A01                  | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| Unknown       | Unknown                     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [37e282ff80](https://linux-hardware.org/?probe=37e282ff80) | Jul 30, 2023 |
| ASRockRack    | X470D4U                     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Unknown       | Unknown                     | [d9c029afa4](https://linux-hardware.org/?probe=d9c029afa4) | Jul 28, 2023 |
| Dell          | 06X1TJ A00                  | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Intel         | X99H                        | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
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
| ASRock        | N68C-GS FX                  | [6b35cdc0ae](https://linux-hardware.org/?probe=6b35cdc0ae) | Jul 26, 2023 |
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
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Gigabyte      | Z77X-UD3H                   | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| MSI           | Z77A-GD65                   | [4df7cd69af](https://linux-hardware.org/?probe=4df7cd69af) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| MSI           | H110M PRO-VD                | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| ASUSTek       | P5Q-PRO                     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| Dell          | 0KWVT8 A03                  | [77fd7def41](https://linux-hardware.org/?probe=77fd7def41) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| ASRock        | B550M Steel Legend          | [6e0eb8c7f5](https://linux-hardware.org/?probe=6e0eb8c7f5) | Jul 19, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Unknown       | Unknown                     | [32816fb789](https://linux-hardware.org/?probe=32816fb789) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| Unknown       | Unknown                     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| HP            | 805A                        | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | H81M-C                      | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| MSI           | 2A9C                        | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| MSI           | H81M-P33                    | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| Biostar       | B450MH                      | [22909715b3](https://linux-hardware.org/?probe=22909715b3) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Unknown       | Unknown                     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Unknown       | Unknown                     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| MSI           | MAG B550M MORTAR            | [74239bf89d](https://linux-hardware.org/?probe=74239bf89d) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Google        | Guado                       | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| ASRock        | B550M Steel Legend          | [c353f8ceea](https://linux-hardware.org/?probe=c353f8ceea) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [7e1752f29c](https://linux-hardware.org/?probe=7e1752f29c) | Jul 14, 2023 |
| ASUSTek       | H110M-R                     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| MSI           | H170M PRO-VDH               | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Dell          | 0D28YY A00                  | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| MSI           | MAG B550M MORTAR            | [b9ff94a143](https://linux-hardware.org/?probe=b9ff94a143) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Apple         | Mac-F221BEC8                | [83e08e8aca](https://linux-hardware.org/?probe=83e08e8aca) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| Foxconn       | G33M03                      | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [eda9b7d2e8](https://linux-hardware.org/?probe=eda9b7d2e8) | Jul 10, 2023 |
| ASUSTek       | PRIME Z590-P                | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 09KPNV A01                  | [596389ea27](https://linux-hardware.org/?probe=596389ea27) | Jul 10, 2023 |
| HP            | 2B38                        | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| Dell          | 0V8WGR A00                  | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| AZW           | U59                         | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| AZW           | MINI S                      | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| ASRock        | B550 Taichi Razer Editio... | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e177e22bff](https://linux-hardware.org/?probe=e177e22bff) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| HP            | 8860 A                      | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| Gigabyte      | H61M-DS2                    | [b0c1a875c3](https://linux-hardware.org/?probe=b0c1a875c3) | Jul 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [d58bb46843](https://linux-hardware.org/?probe=d58bb46843) | Jul 05, 2023 |
| HP            | 895C                        | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| MSI           | MAG B560 TORPEDO            | [1327fb98ac](https://linux-hardware.org/?probe=1327fb98ac) | Jul 04, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| Lenovo        | 3706 SDK0J40697 WIN 3305... | [35e0dd6624](https://linux-hardware.org/?probe=35e0dd6624) | Jul 03, 2023 |
| HP            | 0AECh D                     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| ASUSTek       | Z87-A                       | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Unknown       | AB07H                       | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| ASRock        | B450 Pro4                   | [304cab93f1](https://linux-hardware.org/?probe=304cab93f1) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | 1036 NO DPK                 | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [ed171ca808](https://linux-hardware.org/?probe=ed171ca808) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| Gigabyte      | B365M D3H-CF                | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Shuttle       | FS61                        | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| OEM           | Unknown                     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| AMI           | Cherry Trail CR             | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| Dell          | 0PU052                      | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| Biostar       | X370GTN                     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Biostar       | TH55B HD                    | [5fbef8b11a](https://linux-hardware.org/?probe=5fbef8b11a) | Jun 25, 2023 |
| Gigabyte      | EP45C-DS3R                  | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASUSTek       | K30BF_M32BF                 | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| HP            | 3397                        | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| Acer          | Aspire X1700                | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| HP            | 1998                        | [efcccef24e](https://linux-hardware.org/?probe=efcccef24e) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1998                        | [71bee9f013](https://linux-hardware.org/?probe=71bee9f013) | Jun 21, 2023 |
| HP            | 1588h                       | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| ASRock        | X570 Extreme4               | [3ff2c9e4cc](https://linux-hardware.org/?probe=3ff2c9e4cc) | Jun 21, 2023 |
| ASRock        | B760 Pro RS/D4              | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| MSI           | H81M-P33                    | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0RW203                      | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| Dell          | 0PU052                      | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| ASUSTek       | P8H67-M                     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| MSI           | B350M MORTAR                | [dde719cb99](https://linux-hardware.org/?probe=dde719cb99) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Intel         | H81                         | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| AZW           | U59                         | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | 2B38                        | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| ASRock        | B760 Pro RS/D4              | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [d10c160695](https://linux-hardware.org/?probe=d10c160695) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| HP            | 1589                        | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [5fe5f59145](https://linux-hardware.org/?probe=5fe5f59145) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [7974c3961d](https://linux-hardware.org/?probe=7974c3961d) | Jun 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| HP            | 2820h                       | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d704e4a5d3](https://linux-hardware.org/?probe=d704e4a5d3) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
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
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [365eeba4c9](https://linux-hardware.org/?probe=365eeba4c9) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [df7c4a738e](https://linux-hardware.org/?probe=df7c4a738e) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASRock        | H110M-HDV R3.0              | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ECS           | G31T-M9                     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| ASRock        | H310CM-HDV                  | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| MSI           | Z390-A PRO                  | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Unknown       | Unknown                     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Intel         | X99                         | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Gigabyte      | Z690 AERO G                 | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| AZW           | MINI S                      | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| Biostar       | A10N-8800E                  | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
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
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| MSI           | H110M PRO-VD                | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | Berkeley                    | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| ASUSTek       | E35M1-M                     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Gigabyte      | M61PME-S2                   | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | F2A85-M                     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| HP            | 2B38                        | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| Dell          | 09KPNV A00                  | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| ASRock        | H470M-HVS                   | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| ASRock        | X370 Taichi                 | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| MSI           | 760GM-P23                   | [05c4685974](https://linux-hardware.org/?probe=05c4685974) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| HP            | 8076                        | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| ASUSTek       | P5B-VM SE                   | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| AMI           | Cherry Trail CR             | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Dell          | 0782GW A00                  | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Gigabyte      | H61M-DS2                    | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| ASRock        | H470M-HVS                   | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| HP            | 339A                        | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| HP            | 1632                        | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| ASUSTek       | Rampage IV FORMULA          | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| AZW           | Green G3                    | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| HP            | 1998                        | [42824285c0](https://linux-hardware.org/?probe=42824285c0) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASRock        | H470M-HVS                   | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| ECS           | G31T-M9                     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| ASRock        | H470M-HVS                   | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| Dell          | 0C1R19 A01                  | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| HP            | 1589                        | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Unknown       | Unknown                     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| Dell          | 0RN474                      | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| Unknown       | Unknown                     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| BESSTAR Te... | DMAF5                       | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| HP            | 2B38                        | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Medion        | MS-7708                     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| MSI           | MS-B0A21                    | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| HP            | 8309                        | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| HP            | 1632                        | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| HP            | 8056                        | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Shuttle       | FS81                        | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| ASUSTek       | P8B75-V                     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| HP            | 18E7                        | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [2ab6f2745c](https://linux-hardware.org/?probe=2ab6f2745c) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [55f8d9f172](https://linux-hardware.org/?probe=55f8d9f172) | Apr 14, 2023 |
| Unknown       | Unknown                     | [6925c48705](https://linux-hardware.org/?probe=6925c48705) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Unknown       | Unknown                     | [158dacc1ce](https://linux-hardware.org/?probe=158dacc1ce) | Apr 13, 2023 |
| Unknown       | Unknown                     | [52aeca6f98](https://linux-hardware.org/?probe=52aeca6f98) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| Dell          | 03V7GF A02                  | [cb72d83566](https://linux-hardware.org/?probe=cb72d83566) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Gigabyte      | H61M-DS2                    | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| Lenovo        | 32E6 NOK                    | [c1d51dba1d](https://linux-hardware.org/?probe=c1d51dba1d) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| HP            | 1589                        | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| HP            | 2B29                        | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| ASUSTek       | P7H55                       | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | MS-7253                     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Debian 11               | 2466     | 57.1%   |
| Debian 10               | 750      | 17.37%  |
| Debian 12               | 460      | 10.65%  |
| Debian Testing          | 231      | 5.35%   |
| Debian 9                | 147      | 3.4%    |
| Debian Unstable         | 116      | 2.69%   |
| Debian                  | 98       | 2.27%   |
| Debian 8                | 25       | 0.58%   |
| Debian 11-updates       | 16       | 0.37%   |
| Debian 7                | 5        | 0.12%   |
| Debian Testing/unstable | 2        | 0.05%   |
| Debian Sid              | 1        | 0.02%   |
| Debian 6                | 1        | 0.02%   |
| Debian 23               | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Debian | 4111     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-7-amd64        | 513      | 10.92%  |
| 5.10.0-8-amd64        | 240      | 5.11%   |
| 5.10.0-21-amd64       | 180      | 3.83%   |
| 6.1.0-4-amd64         | 135      | 2.87%   |
| 5.10.0-9-amd64        | 123      | 2.62%   |
| 5.10.0-2-amd64        | 118      | 2.51%   |
| 5.10.0-20-amd64       | 103      | 2.19%   |
| 5.10.0-19-amd64       | 102      | 2.17%   |
| 6.1.0-9-amd64         | 93       | 1.98%   |
| 5.10.0-23-amd64       | 89       | 1.9%    |
| 5.10.0-13-amd64       | 87       | 1.85%   |
| 5.10.0-18-amd64       | 83       | 1.77%   |
| 6.1.0-10-amd64        | 77       | 1.64%   |
| 5.10.0-10-amd64       | 74       | 1.58%   |
| 5.10.0-11-amd64       | 73       | 1.55%   |
| 5.10.0-16-amd64       | 69       | 1.47%   |
| 4.19.0-6-amd64        | 56       | 1.19%   |
| 4.19.0-16-amd64       | 52       | 1.11%   |
| 4.19.0-14-amd64       | 52       | 1.11%   |
| 5.10.0-14-amd64       | 50       | 1.06%   |
| 4.19.0-13-amd64       | 50       | 1.06%   |
| 4.19.0-9-amd64        | 48       | 1.02%   |
| 4.19.0-17-amd64       | 48       | 1.02%   |
| 4.19.0-8-amd64        | 47       | 1%      |
| 6.1.0-11-amd64        | 46       | 0.98%   |
| 5.10.0-17-amd64       | 43       | 0.92%   |
| 5.10.0-15-amd64       | 43       | 0.92%   |
| 5.10.0-22-amd64       | 41       | 0.87%   |
| 4.19.0-12-amd64       | 38       | 0.81%   |
| 5.15.0-2-amd64        | 37       | 0.79%   |
| 4.19.0-10-amd64       | 34       | 0.72%   |
| 4.9.0-8-amd64         | 31       | 0.66%   |
| 6.1.0-7-amd64         | 30       | 0.64%   |
| 5.10.0-12-amd64       | 29       | 0.62%   |
| 5.6.0-2-amd64         | 28       | 0.6%    |
| 6.0.0-6-amd64         | 20       | 0.43%   |
| 5.18.0-2-amd64        | 20       | 0.43%   |
| 5.16.0-0.bpo.4-amd64  | 20       | 0.43%   |
| 6.0.0-0.deb11.6-amd64 | 19       | 0.4%    |
| 5.7.0-1-amd64         | 19       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2111     | 47.09%  |
| 4.19.0   | 520      | 11.6%   |
| 6.1.0    | 455      | 10.15%  |
| 4.9.0    | 110      | 2.45%   |
| 6.0.0    | 93       | 2.07%   |
| 5.18.0   | 79       | 1.76%   |
| 5.9.0    | 59       | 1.32%   |
| 5.16.0   | 59       | 1.32%   |
| 5.15.0   | 57       | 1.27%   |
| 5.8.0    | 55       | 1.23%   |
| 5.7.0    | 54       | 1.2%    |
| 5.6.0    | 48       | 1.07%   |
| 5.4.0    | 45       | 1%      |
| 5.13.19  | 44       | 0.98%   |
| 5.19.0   | 41       | 0.91%   |
| 5.14.0   | 33       | 0.74%   |
| 5.17.0   | 25       | 0.56%   |
| 5.15.107 | 19       | 0.42%   |
| 5.15.102 | 19       | 0.42%   |
| 5.11.22  | 19       | 0.42%   |
| 5.3.0    | 18       | 0.4%    |
| 6.3.0    | 17       | 0.38%   |
| 6.4.0    | 16       | 0.36%   |
| 6.2.16   | 15       | 0.33%   |
| 5.5.0    | 14       | 0.31%   |
| 5.15.83  | 14       | 0.31%   |
| 5.15.74  | 14       | 0.31%   |
| 5.15.39  | 13       | 0.29%   |
| 5.15.35  | 13       | 0.29%   |
| 5.15.85  | 12       | 0.27%   |
| 5.15.30  | 11       | 0.25%   |
| 5.15.53  | 10       | 0.22%   |
| 3.16.0   | 10       | 0.22%   |
| 5.4.106  | 9        | 0.2%    |
| 4.18.0   | 9        | 0.2%    |
| 5.2.0    | 8        | 0.18%   |
| 5.15.104 | 8        | 0.18%   |
| 5.4.44   | 7        | 0.16%   |
| 5.15.108 | 7        | 0.16%   |
| 4.15.18  | 7        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10     | 2143     | 48.11%  |
| 4.19     | 531      | 11.92%  |
| 6.1      | 469      | 10.53%  |
| 5.15     | 203      | 4.56%   |
| 4.9      | 116      | 2.6%    |
| 6.0      | 104      | 2.33%   |
| 5.4      | 98       | 2.2%    |
| 5.18     | 84       | 1.89%   |
| 5.16     | 64       | 1.44%   |
| 5.9      | 62       | 1.39%   |
| 5.8      | 61       | 1.37%   |
| 5.7      | 58       | 1.3%    |
| 5.13     | 54       | 1.21%   |
| 5.6      | 52       | 1.17%   |
| 5.19     | 49       | 1.1%    |
| 5.14     | 36       | 0.81%   |
| 6.2      | 33       | 0.74%   |
| 5.11     | 31       | 0.7%    |
| 5.3      | 30       | 0.67%   |
| 5.17     | 29       | 0.65%   |
| 6.4      | 23       | 0.52%   |
| 6.3      | 21       | 0.47%   |
| 5.5      | 17       | 0.38%   |
| 4.15     | 11       | 0.25%   |
| 4.18     | 10       | 0.22%   |
| 3.16     | 10       | 0.22%   |
| 5.2      | 8        | 0.18%   |
| 5.0      | 8        | 0.18%   |
| 4.1      | 7        | 0.16%   |
| 4.17     | 5        | 0.11%   |
| 5.12     | 3        | 0.07%   |
| 5.1      | 3        | 0.07%   |
| 4.16     | 3        | 0.07%   |
| 6.5      | 2        | 0.04%   |
| 4.20     | 2        | 0.04%   |
| 4.14     | 2        | 0.04%   |
| 4.13     | 2        | 0.04%   |
| 2.6      | 2        | 0.04%   |
| 5.10.164 | 1        | 0.02%   |
| 4.6      | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 3985     | 96.91%  |
| i686        | 96       | 2.33%   |
| ppc64       | 7        | 0.17%   |
| riscv64     | 6        | 0.15%   |
| armv7l      | 6        | 0.15%   |
| ppc64le     | 2        | 0.05%   |
| mips64      | 2        | 0.05%   |
| i586        | 2        | 0.05%   |
| aarch64     | 2        | 0.05%   |
| sparc64     | 1        | 0.02%   |
| sh4a        | 1        | 0.02%   |
| loongarch64 | 1        | 0.02%   |
| armv6l      | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1507     | 35.83%  |
| GNOME             | 806      | 19.16%  |
| XFCE              | 501      | 11.91%  |
| KDE5              | 500      | 11.89%  |
| MATE              | 199      | 4.73%   |
| X-Cinnamon        | 154      | 3.66%   |
| Cinnamon          | 110      | 2.62%   |
| LXDE              | 106      | 2.52%   |
| KDE               | 78       | 1.85%   |
| LXQt              | 67       | 1.59%   |
| i3                | 36       | 0.86%   |
| Openbox           | 33       | 0.78%   |
| GNOME Flashback   | 20       | 0.48%   |
| lightdm-xsession  | 18       | 0.43%   |
| trinity           | 14       | 0.33%   |
| GNOME Classic     | 14       | 0.33%   |
| Budgie            | 14       | 0.33%   |
| awesome           | 5        | 0.12%   |
| KDE4              | 4        | 0.1%    |
| fluxbox           | 4        | 0.1%    |
| sway              | 3        | 0.07%   |
| Enlightenment     | 2        | 0.05%   |
| dwm               | 2        | 0.05%   |
| xmonad            | 1        | 0.02%   |
| UKUI              | 1        | 0.02%   |
| i3-with-shmlog    | 1        | 0.02%   |
| GNUstep           | 1        | 0.02%   |
| gnome-xorg        | 1        | 0.02%   |
| e16-session       | 1        | 0.02%   |
| default           | 1        | 0.02%   |
| Cutefish          | 1        | 0.02%   |
| /etc/X11/Xsession | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 2195     | 52.46%  |
| Unknown     | 905      | 21.63%  |
| Tty         | 628      | 15.01%  |
| Wayland     | 453      | 10.83%  |
| Web         | 2        | 0.05%   |
| Unspecified | 1        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2124     | 50.64%  |
| LightDM | 655      | 15.62%  |
| GDM     | 488      | 11.64%  |
| SDDM    | 458      | 10.92%  |
| TDM     | 250      | 5.96%   |
| GDM3    | 163      | 3.89%   |
| SLiM    | 17       | 0.41%   |
| XDM     | 16       | 0.38%   |
| NODM    | 9        | 0.21%   |
| KDM     | 5        | 0.12%   |
| WDM     | 3        | 0.07%   |
| LXDM    | 3        | 0.07%   |
| Ly      | 2        | 0.05%   |
| SU      | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1422     | 34.15%  |
| ru_RU   | 839      | 20.15%  |
| Unknown | 298      | 7.16%   |
| de_DE   | 255      | 6.12%   |
| fr_FR   | 201      | 4.83%   |
| en_GB   | 195      | 4.68%   |
| pt_BR   | 127      | 3.05%   |
| es_ES   | 118      | 2.83%   |
| it_IT   | 79       | 1.9%    |
| en_CA   | 66       | 1.59%   |
| C       | 60       | 1.44%   |
| en_AU   | 57       | 1.37%   |
| pl_PL   | 39       | 0.94%   |
| es_AR   | 24       | 0.58%   |
| zh_CN   | 22       | 0.53%   |
| en_IN   | 22       | 0.53%   |
| en_IE   | 20       | 0.48%   |
| hu_HU   | 18       | 0.43%   |
| es_VE   | 18       | 0.43%   |
| ja_JP   | 17       | 0.41%   |
| es_MX   | 17       | 0.41%   |
| de_AT   | 16       | 0.38%   |
| en_ZA   | 13       | 0.31%   |
| nl_BE   | 12       | 0.29%   |
| pt_PT   | 11       | 0.26%   |
| nl_NL   | 10       | 0.24%   |
| de_CH   | 10       | 0.24%   |
| cs_CZ   | 10       | 0.24%   |
| en_NZ   | 9        | 0.22%   |
| es_CL   | 8        | 0.19%   |
| sv_SE   | 7        | 0.17%   |
| en_DK   | 7        | 0.17%   |
| ru_UA   | 6        | 0.14%   |
| fi_FI   | 6        | 0.14%   |
| en_HK   | 6        | 0.14%   |
| el_GR   | 6        | 0.14%   |
| ca_ES   | 6        | 0.14%   |
| uk_UA   | 5        | 0.12%   |
| fr_BE   | 5        | 0.12%   |
| es_PE   | 5        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2588     | 62.05%  |
| EFI  | 1583     | 37.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 2881     | 69.3%   |
| Overlay    | 787      | 18.93%  |
| Btrfs      | 171      | 4.11%   |
| Zfs        | 101      | 2.43%   |
| Unknown    | 81       | 1.95%   |
| Xfs        | 68       | 1.64%   |
| Ext3       | 24       | 0.58%   |
| Tmpfs      | 15       | 0.36%   |
| Ext2       | 10       | 0.24%   |
| Rootfs     | 8        | 0.19%   |
| Aufs       | 4        | 0.1%    |
| XXXXXXX    | 2        | 0.05%   |
| Jfs        | 2        | 0.05%   |
| F2fs       | 2        | 0.05%   |
| Fuse.sshfs | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1998     | 47.62%  |
| MBR     | 1383     | 32.96%  |
| Unknown | 815      | 19.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3347     | 80.32%  |
| Yes       | 820      | 19.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2585     | 62.18%  |
| Yes       | 1572     | 37.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1109     | 26.98%  |
| Gigabyte Technology                  | 685      | 16.66%  |
| MSI                                  | 431      | 10.48%  |
| ASRock                               | 407      | 9.9%    |
| Dell                                 | 272      | 6.62%   |
| Hewlett-Packard                      | 249      | 6.06%   |
| Lenovo                               | 135      | 3.28%   |
| Intel                                | 132      | 3.21%   |
| Unknown                              | 93       | 2.26%   |
| ECS                                  | 57       | 1.39%   |
| Fujitsu                              | 45       | 1.09%   |
| Foxconn                              | 42       | 1.02%   |
| AZW                                  | 37       | 0.9%    |
| ASRockRack                           | 35       | 0.85%   |
| Supermicro                           | 34       | 0.83%   |
| Acer                                 | 34       | 0.83%   |
| Biostar                              | 26       | 0.63%   |
| Pegatron                             | 22       | 0.54%   |
| Huanan                               | 14       | 0.34%   |
| Shuttle                              | 13       | 0.32%   |
| Inventec                             | 12       | 0.29%   |
| Apple                                | 12       | 0.29%   |
| Fujitsu Siemens                      | 11       | 0.27%   |
| BESSTAR Tech                         | 11       | 0.27%   |
| Positivo                             | 10       | 0.24%   |
| Medion                               | 10       | 0.24%   |
| Google                               | 9        | 0.22%   |
| Shenzhen Meigao Electronic Equipment | 6        | 0.15%   |
| IceWhale Technology                  | 6        | 0.15%   |
| Hardkernel                           | 5        | 0.12%   |
| AMI                                  | 5        | 0.12%   |
| Techvision                           | 4        | 0.1%    |
| PCWare                               | 4        | 0.1%    |
| Packard Bell                         | 4        | 0.1%    |
| Gateway                              | 4        | 0.1%    |
| Alienware                            | 4        | 0.1%    |
| Wistron                              | 3        | 0.07%   |
| PC Engines                           | 3        | 0.07%   |
| OEM                                  | 3        | 0.07%   |
| Itautec                              | 3        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 135      | 3.28%   |
| Unknown                         | 100      | 2.43%   |
| ASUS S20 K29                    | 55       | 1.34%   |
| MSI MS-7996                     | 44       | 1.07%   |
| MSI MS-7817                     | 26       | 0.63%   |
| ECS G31T-M9                     | 25       | 0.61%   |
| Gigabyte H81M-S2V               | 24       | 0.58%   |
| Dell OptiPlex 7010              | 20       | 0.49%   |
| ASRock H470M-HVS                | 20       | 0.49%   |
| ASUS PRIME H510M-A              | 19       | 0.46%   |
| Gigabyte B450M DS3H             | 17       | 0.41%   |
| Gigabyte H410M S2H              | 16       | 0.39%   |
| ECS H61H2-M13                   | 16       | 0.39%   |
| ASUS TUF Gaming X570-PLUS       | 16       | 0.39%   |
| ASUS PRIME A320M-K              | 16       | 0.39%   |
| ASUS P8H61-M LX3 R2.0           | 15       | 0.36%   |
| Lenovo ThinkCentre M55p 8808D8U | 14       | 0.34%   |
| ASUS PRIME B450M-A              | 14       | 0.34%   |
| ASRock B450M Pro4               | 14       | 0.34%   |
| MSI MS-7C56                     | 13       | 0.32%   |
| MSI MS-7C02                     | 12       | 0.29%   |
| MSI MS-7B79                     | 12       | 0.29%   |
| ASUS PRIME B450M-K              | 12       | 0.29%   |
| MSI MS-7C91                     | 11       | 0.27%   |
| HP Z420 Workstation             | 11       | 0.27%   |
| Gigabyte B450M S2H              | 11       | 0.27%   |
| AZW U59                         | 11       | 0.27%   |
| AZW MINI S                      | 11       | 0.27%   |
| ASUS PRIME B450-PLUS            | 11       | 0.27%   |
| ASUS P8H67-M                    | 11       | 0.27%   |
| ASUS H110M-R                    | 11       | 0.27%   |
| ASRock B450 Pro4                | 11       | 0.27%   |
| MSI MS-7A34                     | 10       | 0.24%   |
| HP ProLiant MicroServer Gen8    | 10       | 0.24%   |
| HP Compaq Elite 8300 SFF        | 10       | 0.24%   |
| ASUS PRIME X370-PRO             | 10       | 0.24%   |
| ASRock H61M-VG4                 | 10       | 0.24%   |
| HP ProLiant MicroServer         | 9        | 0.22%   |
| Gigabyte H61M-S2PV              | 9        | 0.22%   |
| Gigabyte GA-78LMT-USB3          | 9        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 237      | 5.77%   |
| Dell OptiPlex          | 147      | 3.58%   |
| ASUS All               | 135      | 3.28%   |
| Unknown                | 100      | 2.43%   |
| ASUS ROG               | 95       | 2.31%   |
| Lenovo ThinkCentre     | 78       | 1.9%    |
| HP Compaq              | 67       | 1.63%   |
| ASUS TUF               | 67       | 1.63%   |
| Dell Precision         | 55       | 1.34%   |
| ASUS S20               | 55       | 1.34%   |
| MSI MS-7996            | 44       | 1.07%   |
| Gigabyte B450M         | 39       | 0.95%   |
| ASUS P8H61-M           | 35       | 0.85%   |
| HP EliteDesk           | 34       | 0.83%   |
| HP ProLiant            | 29       | 0.71%   |
| Gigabyte X570          | 29       | 0.71%   |
| MSI MS-7817            | 26       | 0.63%   |
| ASUS PRO               | 26       | 0.63%   |
| ECS G31T-M9            | 25       | 0.61%   |
| Gigabyte H81M-S2V      | 24       | 0.58%   |
| ASRock B450M           | 24       | 0.58%   |
| Lenovo ThinkStation    | 23       | 0.56%   |
| Fujitsu ESPRIMO        | 23       | 0.56%   |
| Acer Aspire            | 22       | 0.54%   |
| Gigabyte H410M         | 21       | 0.51%   |
| Gigabyte B550          | 21       | 0.51%   |
| HP ProDesk             | 20       | 0.49%   |
| ASRock H470M-HVS       | 20       | 0.49%   |
| ASRock B450            | 20       | 0.49%   |
| ASUS M5A78L-M          | 18       | 0.44%   |
| Gigabyte GA-78LMT-USB3 | 17       | 0.41%   |
| Gigabyte B450          | 17       | 0.41%   |
| Gigabyte A320M-S2H     | 17       | 0.41%   |
| Dell XPS               | 17       | 0.41%   |
| Dell Vostro            | 17       | 0.41%   |
| ASUS P5G41T-M          | 17       | 0.41%   |
| Gigabyte B550M         | 16       | 0.39%   |
| ECS H61H2-M13          | 16       | 0.39%   |
| Dell Inspiron          | 15       | 0.36%   |
| ASUS P8H67-M           | 15       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 399      | 9.71%   |
| 2020    | 383      | 9.32%   |
| 2012    | 366      | 8.9%    |
| 2013    | 328      | 7.98%   |
| 2019    | 290      | 7.05%   |
| 2021    | 275      | 6.69%   |
| 2011    | 264      | 6.42%   |
| 2014    | 238      | 5.79%   |
| 2017    | 213      | 5.18%   |
| 2009    | 208      | 5.06%   |
| 2015    | 194      | 4.72%   |
| 2010    | 188      | 4.57%   |
| 2022    | 174      | 4.23%   |
| 2016    | 169      | 4.11%   |
| 2008    | 148      | 3.6%    |
| 2007    | 117      | 2.85%   |
| 2006    | 47       | 1.14%   |
| 2023    | 33       | 0.8%    |
| Unknown | 29       | 0.71%   |
| 2005    | 25       | 0.61%   |
| 2004    | 10       | 0.24%   |
| 2003    | 6        | 0.15%   |
| 2001    | 3        | 0.07%   |
| 2002    | 2        | 0.05%   |
| 2000    | 2        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4111     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4044     | 98.16%  |
| Enabled  | 76       | 1.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4093     | 99.56%  |
| Yes  | 18       | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 824      | 19.72%  |
| 4.01-8.0        | 664      | 15.89%  |
| 8.01-16.0       | 651      | 15.58%  |
| 3.01-4.0        | 628      | 15.03%  |
| 32.01-64.0      | 625      | 14.96%  |
| 64.01-256.0     | 357      | 8.54%   |
| 1.01-2.0        | 166      | 3.97%   |
| 24.01-32.0      | 115      | 2.75%   |
| 2.01-3.0        | 68       | 1.63%   |
| 0.51-1.0        | 31       | 0.74%   |
| More than 256.0 | 19       | 0.45%   |
| Unknown         | 15       | 0.36%   |
| 0.01-0.5        | 14       | 0.34%   |
| 0               | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 967      | 21.63%  |
| 1.01-2.0        | 923      | 20.64%  |
| 2.01-3.0        | 742      | 16.6%   |
| 4.01-8.0        | 693      | 15.5%   |
| 3.01-4.0        | 439      | 9.82%   |
| 8.01-16.0       | 285      | 6.37%   |
| 0.01-0.5        | 175      | 3.91%   |
| 16.01-24.0      | 111      | 2.48%   |
| 32.01-64.0      | 56       | 1.25%   |
| 24.01-32.0      | 43       | 0.96%   |
| 64.01-256.0     | 18       | 0.4%    |
| Unknown         | 18       | 0.4%    |
| More than 256.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1846     | 43.52%  |
| 2       | 976      | 23.01%  |
| 3       | 566      | 13.34%  |
| 4       | 370      | 8.72%   |
| 5       | 175      | 4.13%   |
| 6       | 110      | 2.59%   |
| 7       | 56       | 1.32%   |
| 8       | 44       | 1.04%   |
| 0       | 26       | 0.61%   |
| 9       | 20       | 0.47%   |
| 10      | 15       | 0.35%   |
| 11      | 8        | 0.19%   |
| 13      | 6        | 0.14%   |
| 12      | 6        | 0.14%   |
| 29      | 2        | 0.05%   |
| 27      | 2        | 0.05%   |
| 19      | 2        | 0.05%   |
| 14      | 2        | 0.05%   |
| Unknown | 2        | 0.05%   |
| 46      | 1        | 0.02%   |
| 32      | 1        | 0.02%   |
| 28      | 1        | 0.02%   |
| 22      | 1        | 0.02%   |
| 21      | 1        | 0.02%   |
| 18      | 1        | 0.02%   |
| 17      | 1        | 0.02%   |
| 16      | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2674     | 64.43%  |
| Yes       | 1476     | 35.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4076     | 99.15%  |
| No        | 35       | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2826     | 68.23%  |
| Yes       | 1316     | 31.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3099     | 74.55%  |
| Yes       | 1058     | 25.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 933      | 22.65%  |
| USA          | 616      | 14.96%  |
| Germany      | 422      | 10.25%  |
| France       | 255      | 6.19%   |
| Brazil       | 198      | 4.81%   |
| Spain        | 169      | 4.1%    |
| UK           | 137      | 3.33%   |
| Italy        | 129      | 3.13%   |
| Canada       | 109      | 2.65%   |
| Australia    | 82       | 1.99%   |
| Poland       | 70       | 1.7%    |
| Netherlands  | 62       | 1.51%   |
| China        | 50       | 1.21%   |
| Switzerland  | 45       | 1.09%   |
| Austria      | 43       | 1.04%   |
| Argentina    | 40       | 0.97%   |
| Ukraine      | 37       | 0.9%    |
| Hungary      | 37       | 0.9%    |
| Finland      | 35       | 0.85%   |
| Belgium      | 35       | 0.85%   |
| Sweden       | 34       | 0.83%   |
| Mexico       | 31       | 0.75%   |
| India        | 28       | 0.68%   |
| Czechia      | 26       | 0.63%   |
| Norway       | 25       | 0.61%   |
| Portugal     | 24       | 0.58%   |
| Venezuela    | 23       | 0.56%   |
| Romania      | 22       | 0.53%   |
| Bulgaria     | 22       | 0.53%   |
| Japan        | 21       | 0.51%   |
| Turkey       | 17       | 0.41%   |
| Denmark      | 17       | 0.41%   |
| South Africa | 16       | 0.39%   |
| Belarus      | 15       | 0.36%   |
| Taiwan       | 13       | 0.32%   |
| Slovakia     | 13       | 0.32%   |
| Malaysia     | 13       | 0.32%   |
| New Zealand  | 12       | 0.29%   |
| Ireland      | 12       | 0.29%   |
| Greece       | 12       | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 652      | 15.28%  |
| Moscow            | 72       | 1.69%   |
| St Petersburg     | 49       | 1.15%   |
| Paris             | 34       | 0.8%    |
| Vienna            | 33       | 0.77%   |
| Sao Paulo         | 29       | 0.68%   |
| Berlin            | 29       | 0.68%   |
| Falkenstein       | 26       | 0.61%   |
| Bangor            | 26       | 0.61%   |
| Madrid            | 23       | 0.54%   |
| Seville           | 21       | 0.49%   |
| Rio de Janeiro    | 21       | 0.49%   |
| Barcelona         | 21       | 0.49%   |
| Toronto           | 18       | 0.42%   |
| Melbourne         | 18       | 0.42%   |
| Amsterdam         | 18       | 0.42%   |
| Sydney            | 17       | 0.4%    |
| Milan             | 16       | 0.37%   |
| Frankfurt am Main | 16       | 0.37%   |
| Yekaterinburg     | 15       | 0.35%   |
| Brisbane          | 15       | 0.35%   |
| Munich            | 14       | 0.33%   |
| Hamburg           | 14       | 0.33%   |
| Zurich            | 13       | 0.3%    |
| Budapest          | 13       | 0.3%    |
| Warsaw            | 12       | 0.28%   |
| Kyiv              | 12       | 0.28%   |
| Cologne           | 12       | 0.28%   |
| Chicago           | 12       | 0.28%   |
| Perm              | 11       | 0.26%   |
| Nuremberg         | 11       | 0.26%   |
| New York          | 11       | 0.26%   |
| London            | 11       | 0.26%   |
| Helsinki          | 11       | 0.26%   |
| Dallas            | 11       | 0.26%   |
| Buenos Aires      | 11       | 0.26%   |
| Beijing           | 11       | 0.26%   |
| Valencia          | 10       | 0.23%   |
| Stockholm         | 10       | 0.23%   |
| Sofia             | 10       | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 1363     | 2588   | 18.58%  |
| Seagate                     | 1297     | 2374   | 17.68%  |
| Samsung Electronics         | 1064     | 1715   | 14.51%  |
| Kingston                    | 503      | 656    | 6.86%   |
| Toshiba                     | 464      | 859    | 6.33%   |
| Crucial                     | 425      | 580    | 5.79%   |
| SanDisk                     | 258      | 352    | 3.52%   |
| Hitachi                     | 256      | 368    | 3.49%   |
| Intel                       | 138      | 194    | 1.88%   |
| A-DATA Technology           | 111      | 150    | 1.51%   |
| HGST                        | 109      | 228    | 1.49%   |
| China                       | 98       | 115    | 1.34%   |
| Unknown                     | 91       | 136    | 1.24%   |
| SPCC                        | 62       | 69     | 0.85%   |
| Transcend                   | 53       | 60     | 0.72%   |
| Phison                      | 52       | 73     | 0.71%   |
| PNY                         | 49       | 88     | 0.67%   |
| Maxtor                      | 49       | 57     | 0.67%   |
| Corsair                     | 49       | 68     | 0.67%   |
| OCZ                         | 47       | 58     | 0.64%   |
| Hewlett-Packard             | 41       | 73     | 0.56%   |
| Patriot                     | 34       | 45     | 0.46%   |
| Micron Technology           | 34       | 43     | 0.46%   |
| Netac                       | 31       | 110    | 0.42%   |
| Intenso                     | 30       | 42     | 0.41%   |
| SK hynix                    | 29       | 48     | 0.4%    |
| Gigabyte Technology         | 28       | 32     | 0.38%   |
| GOODRAM                     | 25       | 43     | 0.34%   |
| Unknown                     | 23       | 24     | 0.31%   |
| Kingston Technology Company | 19       | 26     | 0.26%   |
| Plextor                     | 18       | 24     | 0.25%   |
| XPG                         | 17       | 30     | 0.23%   |
| Silicon Motion              | 16       | 21     | 0.22%   |
| JMicron Technology          | 16       | 18     | 0.22%   |
| Apacer                      | 16       | 18     | 0.22%   |
| Micron/Crucial Technology   | 15       | 20     | 0.2%    |
| LITEON                      | 15       | 19     | 0.2%    |
| Phison Electronics          | 14       | 25     | 0.19%   |
| Team                        | 13       | 19     | 0.18%   |
| KingDian                    | 12       | 13     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 124      | 1.42%   |
| Seagate ST500DM002-1BD142 500GB  | 109      | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB   | 89       | 1.02%   |
| Crucial CT480BX500SSD1 480GB     | 85       | 0.97%   |
| Toshiba DT01ACA050 500GB         | 77       | 0.88%   |
| Kingston SV300S37A120G 120GB SSD | 64       | 0.73%   |
| Kingston SA400S37480G 480GB SSD  | 62       | 0.71%   |
| Toshiba DT01ACA100 1TB           | 58       | 0.66%   |
| Samsung SSD 860 EVO 500GB        | 58       | 0.66%   |
| Samsung SSD 860 EVO 1TB          | 58       | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB         | 54       | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB   | 54       | 0.62%   |
| Samsung SSD 860 EVO 250GB        | 54       | 0.62%   |
| Samsung SSD 850 EVO 250GB        | 54       | 0.62%   |
| Kingston SA400S37120G 120GB SSD  | 54       | 0.62%   |
| Crucial CT500MX500SSD1 500GB     | 53       | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB   | 51       | 0.58%   |
| Samsung SSD 970 EVO Plus 500GB   | 51       | 0.58%   |
| Samsung SSD 850 EVO 500GB        | 51       | 0.58%   |
| Crucial CT240BX500SSD1 240GB     | 51       | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB     | 48       | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB   | 47       | 0.54%   |
| Toshiba HDWD110 1TB              | 46       | 0.53%   |
| Crucial CT1000MX500SSD1 1TB      | 46       | 0.53%   |
| Seagate ST1000DM003-1CH162 1TB   | 43       | 0.49%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 40       | 0.46%   |
| Hitachi HDS721050CLA362 500GB    | 40       | 0.46%   |
| Samsung SSD 980 PRO 1TB          | 35       | 0.4%    |
| Samsung SSD 870 EVO 500GB        | 33       | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB   | 32       | 0.37%   |
| Toshiba DT01ACA200 2TB           | 31       | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB   | 31       | 0.35%   |
| Seagate ST3500418AS 500GB        | 30       | 0.34%   |
| WDC WD20EFRX-68EUZN0 2TB         | 29       | 0.33%   |
| SanDisk NVMe SSD Drive 1TB       | 29       | 0.33%   |
| Crucial CT250MX500SSD1 250GB     | 28       | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB         | 27       | 0.31%   |
| WDC WD30EFRX-68EUZN0 3TB         | 27       | 0.31%   |
| WDC WD10EZEX-00BN5A0 1TB         | 27       | 0.31%   |
| Toshiba DT01ACA300 3TB           | 27       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1273     | 2314   | 35.7%   |
| WDC                 | 1191     | 2275   | 33.4%   |
| Toshiba             | 424      | 791    | 11.89%  |
| Hitachi             | 256      | 368    | 7.18%   |
| Samsung Electronics | 158      | 214    | 4.43%   |
| HGST                | 109      | 228    | 3.06%   |
| Maxtor              | 48       | 56     | 1.35%   |
| Unknown             | 21       | 28     | 0.59%   |
| Hewlett-Packard     | 10       | 26     | 0.28%   |
| SABRENT             | 9        | 10     | 0.25%   |
| Fujitsu             | 6        | 7      | 0.17%   |
| ASMT                | 6        | 9      | 0.17%   |
| Intenso             | 4        | 5      | 0.11%   |
| HPE                 | 4        | 9      | 0.11%   |
| External            | 4        | 6      | 0.11%   |
| Apple               | 4        | 5      | 0.11%   |
| ASMedia             | 3        | 3      | 0.08%   |
| QNAP                | 2        | 3      | 0.06%   |
| Inateck             | 2        | 2      | 0.06%   |
| WD MediaMax         | 1        | 6      | 0.03%   |
| USB 3.0             | 1        | 2      | 0.03%   |
| USB                 | 1        | 1      | 0.03%   |
| Synology            | 1        | 1      | 0.03%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SSK                 | 1        | 1      | 0.03%   |
| SD                  | 1        | 1      | 0.03%   |
| RSH-319             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| pqi                 | 1        | 1      | 0.03%   |
| Pear 2TB            | 1        | 1      | 0.03%   |
| NAS                 | 1        | 10     | 0.03%   |
| MaxDigital          | 1        | 4      | 0.03%   |
| MARSHAL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| LIO-ORG             | 1        | 8      | 0.03%   |
| LaCie               | 1        | 1      | 0.03%   |
| JMicron Technology  | 1        | 2      | 0.03%   |
| Innodisk            | 1        | 1      | 0.03%   |
| IBM/Hitachi         | 1        | 1      | 0.03%   |
| IBM H0              | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 592      | 869    | 22.05%  |
| Kingston            | 449      | 578    | 16.72%  |
| Crucial             | 378      | 510    | 14.08%  |
| SanDisk             | 173      | 235    | 6.44%   |
| WDC                 | 154      | 200    | 5.74%   |
| China               | 96       | 113    | 3.58%   |
| A-DATA Technology   | 82       | 108    | 3.05%   |
| Intel               | 76       | 102    | 2.83%   |
| SPCC                | 53       | 57     | 1.97%   |
| Transcend           | 47       | 53     | 1.75%   |
| OCZ                 | 47       | 58     | 1.75%   |
| PNY                 | 37       | 73     | 1.38%   |
| Toshiba             | 33       | 42     | 1.23%   |
| Netac               | 29       | 108    | 1.08%   |
| Patriot             | 26       | 31     | 0.97%   |
| Intenso             | 24       | 32     | 0.89%   |
| GOODRAM             | 22       | 31     | 0.82%   |
| Micron Technology   | 20       | 25     | 0.74%   |
| Corsair             | 18       | 23     | 0.67%   |
| Gigabyte Technology | 15       | 17     | 0.56%   |
| Plextor             | 14       | 20     | 0.52%   |
| Hewlett-Packard     | 14       | 20     | 0.52%   |
| Apacer              | 12       | 12     | 0.45%   |
| Team                | 11       | 14     | 0.41%   |
| LITEON              | 11       | 15     | 0.41%   |
| KingDian            | 11       | 12     | 0.41%   |
| SK hynix            | 10       | 12     | 0.37%   |
| Seagate             | 10       | 12     | 0.37%   |
| JMicron Technology  | 10       | 11     | 0.37%   |
| Unknown             | 10       | 11     | 0.37%   |
| Unknown             | 8        | 11     | 0.3%    |
| Mushkin             | 8        | 9      | 0.3%    |
| Hajaan              | 8        | 11     | 0.3%    |
| LITEONIT            | 7        | 12     | 0.26%   |
| Xinhaike            | 5        | 8      | 0.19%   |
| T-FORCE             | 5        | 7      | 0.19%   |
| NGFF                | 5        | 5      | 0.19%   |
| Hoodisk             | 5        | 5      | 0.19%   |
| TO Exter            | 4        | 4      | 0.15%   |
| Smartbuy            | 4        | 4      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2731     | 6422   | 44.6%   |
| SSD     | 2225     | 3650   | 36.33%  |
| NVMe    | 1046     | 1673   | 17.08%  |
| Unknown | 76       | 144    | 1.24%   |
| MMC     | 46       | 55     | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3708     | 9629   | 73.28%  |
| NVMe | 1043     | 1665   | 20.61%  |
| SAS  | 263      | 595    | 5.2%    |
| MMC  | 46       | 55     | 0.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives  | Percent |
|------------|----------|---------|---------|
| 0.01-0.5   | 2849     | 4821    | 50.97%  |
| 0.51-1.0   | 1347     | 2254    | 24.1%   |
| 1.01-2.0   | 609      | 1080    | 10.89%  |
| 3.01-4.0   | 306      | 663     | 5.47%   |
| 4.01-10.0  | 228      | 651     | 4.08%   |
| 2.01-3.0   | 186      | 351     | 3.33%   |
| 10.01-20.0 | 63       | 251     | 1.13%   |
| 20.01-50.0 | 1        | 1       | 0.02%   |
| 0          | 1        | Unknown | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 872      | 20.43%  |
| 101-250        | 679      | 15.91%  |
| 251-500        | 568      | 13.31%  |
| 501-1000       | 547      | 12.82%  |
| More than 3000 | 503      | 11.79%  |
| 1001-2000      | 379      | 8.88%   |
| 51-100         | 229      | 5.37%   |
| 2001-3000      | 207      | 4.85%   |
| 1-20           | 155      | 3.63%   |
| 21-50          | 129      | 3.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1113     | 25.5%   |
| Unknown        | 872      | 19.98%  |
| 101-250        | 436      | 9.99%   |
| 21-50          | 370      | 8.48%   |
| 251-500        | 335      | 7.67%   |
| 501-1000       | 317      | 7.26%   |
| 51-100         | 317      | 7.26%   |
| 1001-2000      | 255      | 5.84%   |
| More than 3000 | 226      | 5.18%   |
| 2001-3000      | 115      | 2.63%   |
| 0              | 9        | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 27       | 41     | 2.77%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 36     | 2.05%   |
| Kingston SV300S37A120G 120GB SSD | 20       | 21     | 2.05%   |
| Hitachi HDS721050CLA362 500GB    | 12       | 13     | 1.23%   |
| Seagate ST1000DM003-9YN162 1TB   | 10       | 11     | 1.03%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 9        | 9      | 0.92%   |
| Seagate ST3500418AS 500GB        | 9        | 14     | 0.92%   |
| Seagate ST31000528AS 1TB         | 9        | 11     | 0.92%   |
| Seagate ST3250318AS 250GB        | 8        | 9      | 0.82%   |
| Seagate ST31500341AS 1TB         | 8        | 14     | 0.82%   |
| Toshiba DT01ACA100 1TB           | 7        | 9      | 0.72%   |
| Toshiba DT01ACA050 500GB         | 7        | 8      | 0.72%   |
| Seagate ST3160815AS 160GB        | 7        | 9      | 0.72%   |
| Seagate ST250DM000-1BD141 250GB  | 7        | 7      | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB   | 7        | 7      | 0.72%   |
| WDC WD5000AAKX-001CA0 500GB      | 6        | 8      | 0.62%   |
| WDC WD3200AAJS-00L7A0 320GB      | 6        | 6      | 0.62%   |
| WDC WD20EARX-00PASB0 2TB         | 6        | 8      | 0.62%   |
| Seagate ST3320613AS 320GB        | 6        | 6      | 0.62%   |
| Seagate ST3250410AS 250GB        | 6        | 7      | 0.62%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 5      | 0.51%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 5        | 6      | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB         | 5        | 16     | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB         | 5        | 5      | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 5      | 0.51%   |
| WDC WD10EARS-00Y5B1 1TB          | 5        | 5      | 0.51%   |
| WDC WD10EADS-00M2B0 1TB          | 5        | 5      | 0.51%   |
| Seagate ST3500413AS 500GB        | 5        | 6      | 0.51%   |
| Seagate ST31000524AS 1TB         | 5        | 5      | 0.51%   |
| Seagate ST2000DM001-1CH164 2TB   | 5        | 6      | 0.51%   |
| Samsung Electronics HD103UJ 1TB  | 5        | 6      | 0.51%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.41%   |
| WDC WD40EFRX-68WT0N0 4TB         | 4        | 13     | 0.41%   |
| WDC WD30EFRX-68EUZN0 3TB         | 4        | 4      | 0.41%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 4        | 4      | 0.41%   |
| WDC WD2002FAEX-007BA0 2TB        | 4        | 5      | 0.41%   |
| WDC WD10EALX-009BA0 1TB          | 4        | 5      | 0.41%   |
| Seagate ST9500325AS 500GB        | 4        | 6      | 0.41%   |
| Seagate ST380815AS 80GB          | 4        | 5      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 276      | 391    | 29.84%  |
| WDC                 | 264      | 378    | 28.54%  |
| Samsung Electronics | 83       | 94     | 8.97%   |
| Hitachi             | 64       | 87     | 6.92%   |
| Toshiba             | 42       | 53     | 4.54%   |
| Kingston            | 41       | 48     | 4.43%   |
| Intel               | 24       | 30     | 2.59%   |
| Crucial             | 20       | 26     | 2.16%   |
| Maxtor              | 18       | 20     | 1.95%   |
| A-DATA Technology   | 18       | 25     | 1.95%   |
| SanDisk             | 12       | 15     | 1.3%    |
| HGST                | 9        | 10     | 0.97%   |
| OCZ                 | 7        | 8      | 0.76%   |
| SK hynix            | 4        | 8      | 0.43%   |
| KingDian            | 4        | 4      | 0.43%   |
| China               | 4        | 4      | 0.43%   |
| Micron Technology   | 3        | 3      | 0.32%   |
| Transcend           | 2        | 2      | 0.22%   |
| SPCC                | 2        | 2      | 0.22%   |
| LITEONIT            | 2        | 2      | 0.22%   |
| LITEON              | 2        | 2      | 0.22%   |
| Hewlett-Packard     | 2        | 3      | 0.22%   |
| Corsair             | 2        | 2      | 0.22%   |
| Apacer              | 2        | 2      | 0.22%   |
| ZHITAI              | 1        | 1      | 0.11%   |
| Western Digital     | 1        | 2      | 0.11%   |
| Unknown             | 1        | 1      | 0.11%   |
| Teclast             | 1        | 1      | 0.11%   |
| SSSTC               | 1        | 1      | 0.11%   |
| ShiJi               | 1        | 1      | 0.11%   |
| PNY                 | 1        | 1      | 0.11%   |
| Plextor             | 1        | 2      | 0.11%   |
| Patriot             | 1        | 1      | 0.11%   |
| Mushkin             | 1        | 1      | 0.11%   |
| KingSpec            | 1        | 1      | 0.11%   |
| Intenso             | 1        | 1      | 0.11%   |
| IBM                 | 1        | 1      | 0.11%   |
| Hypertec            | 1        | 1      | 0.11%   |
| HP Phison           | 1        | 1      | 0.11%   |
| Fujitsu             | 1        | 2      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 276      | 391    | 38.66%  |
| WDC                 | 252      | 364    | 35.29%  |
| Hitachi             | 64       | 87     | 8.96%   |
| Samsung Electronics | 49       | 55     | 6.86%   |
| Toshiba             | 40       | 51     | 5.6%    |
| Maxtor              | 18       | 20     | 2.52%   |
| HGST                | 9        | 10     | 1.26%   |
| Hewlett-Packard     | 2        | 3      | 0.28%   |
| Unknown             | 1        | 1      | 0.14%   |
| IBM                 | 1        | 1      | 0.14%   |
| Fujitsu             | 1        | 2      | 0.14%   |
| ASMT                | 1        | 2      | 0.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 644      | 987    | 75.5%   |
| SSD  | 182      | 218    | 21.34%  |
| NVMe | 27       | 36     | 3.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 3      | 10%     |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1        | 1      | 5%      |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 5%      |
| Seagate ST500DM005 HD502HJ 500GB                 | 1        | 1      | 5%      |
| Seagate ST3500830AS 500GB                        | 1        | 1      | 5%      |
| Seagate ST3500630A 500GB                         | 1        | 1      | 5%      |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 5%      |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1        | 1      | 5%      |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 5%      |
| Samsung Electronics SP0802N 80GB                 | 1        | 1      | 5%      |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 5%      |
| Samsung Electronics HD253GJ 250GB                | 1        | 1      | 5%      |
| Samsung Electronics HD103SJ 1TB                  | 1        | 2      | 5%      |
| Intel SSDSC2KW256G8 256GB                        | 1        | 1      | 5%      |
| Inland SATA SSD 128GB                            | 1        | 1      | 5%      |
| HGST HUH728080ALN600 8TB                         | 1        | 1      | 5%      |
| HGST HDN724040ALE640 4TB                         | 1        | 1      | 5%      |
| Hewlett-Packard SSD S700 500GB                   | 1        | 2      | 5%      |
| Crucial CT1000P1SSD8 1TB                         | 1        | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 30%     |
| Samsung Electronics | 6        | 8      | 30%     |
| WDC                 | 2        | 2      | 10%     |
| HGST                | 2        | 2      | 10%     |
| Intel               | 1        | 1      | 5%      |
| Inland              | 1        | 1      | 5%      |
| Hewlett-Packard     | 1        | 2      | 5%      |
| Crucial             | 1        | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 2959     | 7594   | 60.67%  |
| Detected | 1081     | 3083   | 22.17%  |
| Malfunc  | 815      | 1241   | 16.71%  |
| Failed   | 20       | 24     | 0.41%   |
| Limited  | 2        | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2729     | 46.59%  |
| AMD                              | 1211     | 20.67%  |
| Samsung Electronics              | 440      | 7.51%   |
| ASMedia Technology               | 224      | 3.82%   |
| SanDisk                          | 169      | 2.88%   |
| Marvell Technology Group         | 150      | 2.56%   |
| Phison Electronics               | 139      | 2.37%   |
| JMicron Technology               | 117      | 2%      |
| Nvidia                           | 95       | 1.62%   |
| Kingston Technology Company      | 82       | 1.4%    |
| Micron/Crucial Technology        | 70       | 1.19%   |
| LSI Logic / Symbios Logic        | 48       | 0.82%   |
| VIA Technologies                 | 47       | 0.8%    |
| Silicon Motion                   | 47       | 0.8%    |
| ADATA Technology                 | 45       | 0.77%   |
| Broadcom / LSI                   | 40       | 0.68%   |
| Silicon Image                    | 23       | 0.39%   |
| Toshiba America Info Systems     | 18       | 0.31%   |
| SK hynix                         | 17       | 0.29%   |
| Adaptec                          | 17       | 0.29%   |
| Micron Technology                | 15       | 0.26%   |
| Realtek Semiconductor            | 14       | 0.24%   |
| KIOXIA                           | 14       | 0.24%   |
| MAXIO Technology (Hangzhou)      | 12       | 0.2%    |
| Seagate Technology               | 11       | 0.19%   |
| Lite-On Technology               | 9        | 0.15%   |
| Silicon Integrated Systems [SiS] | 5        | 0.09%   |
| IBM                              | 5        | 0.09%   |
| Hewlett-Packard                  | 5        | 0.09%   |
| Integrated Technology Express    | 4        | 0.07%   |
| INNOGRIT                         | 4        | 0.07%   |
| Biwin Storage Technology         | 4        | 0.07%   |
| HighPoint Technologies           | 3        | 0.05%   |
| Yangtze Memory Technologies      | 2        | 0.03%   |
| Transcend                        | 2        | 0.03%   |
| Shenzhen Longsys Electronics     | 2        | 0.03%   |
| Netac Technology                 | 2        | 0.03%   |
| Mylex                            | 2        | 0.03%   |
| Loongson Technology              | 2        | 0.03%   |
| 3ware                            | 2        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 721      | 9.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 336      | 4.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 268      | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 249      | 3.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 216      | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 208      | 2.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 204      | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 202      | 2.75%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 199      | 2.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 160      | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 157      | 2.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 153      | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 151      | 2.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 131      | 1.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 101      | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 96       | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 96       | 1.31%   |
| Intel SATA Controller [RAID mode]                                                       | 95       | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 95       | 1.29%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 92       | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 90       | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 71       | 0.97%   |
| Phison E12 NVMe Controller                                                              | 70       | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 70       | 0.95%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 61       | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 61       | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 60       | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                                  | 59       | 0.8%    |
| AMD FCH SATA Controller D                                                               | 58       | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 55       | 0.75%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 54       | 0.74%   |
| Samsung NVMe SSD Controller 980                                                         | 51       | 0.69%   |
| Nvidia MCP61 SATA Controller                                                            | 50       | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 45       | 0.61%   |
| Nvidia MCP61 IDE                                                                        | 44       | 0.6%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 43       | 0.59%   |
| AMD X370 Series Chipset SATA Controller                                                 | 43       | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 42       | 0.57%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.57%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 40       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3325     | 57.81%  |
| NVMe | 1047     | 18.2%   |
| IDE  | 1008     | 17.52%  |
| RAID | 252      | 4.38%   |
| SAS  | 88       | 1.53%   |
| SCSI | 32       | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2757     | 67.06%  |
| AMD                   | 1318     | 32.06%  |
| CentaurHauls          | 7        | 0.17%   |
| Unknown               | 7        | 0.17%   |
| CHRP IBM,8233-E8B     | 5        | 0.12%   |
| ARM                   | 5        | 0.12%   |
| sifive,bullet0        | 3        | 0.07%   |
| sifive,u74-mc         | 2        | 0.05%   |
| Marvell Semiconductor | 2        | 0.05%   |
| CHRP IBM,9131-52A     | 2        | 0.05%   |
| PowerNV FP5466G2      | 1        | 0.02%   |
| PowerNV C829UAG3      | 1        | 0.02%   |
| Loongson              | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 68       | 1.65%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 67       | 1.62%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 47       | 1.14%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 42       | 1.02%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 41       | 0.99%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 39       | 0.95%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 38       | 0.92%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 38       | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 37       | 0.9%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 37       | 0.9%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 35       | 0.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 35       | 0.85%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 34       | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 33       | 0.8%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 33       | 0.8%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 32       | 0.78%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 32       | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 31       | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 31       | 0.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 30       | 0.73%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 29       | 0.7%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 29       | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 29       | 0.7%    |
| Intel Core i3-10100 CPU @ 3.60GHz           | 28       | 0.68%   |
| AMD FX-8350 Eight-Core Processor            | 28       | 0.68%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 27       | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 27       | 0.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 27       | 0.65%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 26       | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 26       | 0.63%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 25       | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 25       | 0.61%   |
| Intel Celeron N5105 @ 2.00GHz               | 25       | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.58%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 24       | 0.58%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 23       | 0.56%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 23       | 0.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 23       | 0.56%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 22       | 0.53%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 22       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 634      | 15.39%  |
| Intel Core i7           | 407      | 9.88%   |
| Intel Core i3           | 342      | 8.3%    |
| AMD Ryzen 5             | 295      | 7.16%   |
| Intel Xeon              | 268      | 6.5%    |
| AMD Ryzen 7             | 245      | 5.95%   |
| Intel Celeron           | 223      | 5.41%   |
| Intel Pentium           | 214      | 5.19%   |
| Other                   | 187      | 4.54%   |
| Intel Core 2 Duo        | 156      | 3.79%   |
| AMD Ryzen 9             | 147      | 3.57%   |
| AMD FX                  | 123      | 2.99%   |
| Intel Pentium Dual-Core | 79       | 1.92%   |
| Intel Core 2 Quad       | 69       | 1.67%   |
| AMD Ryzen 3             | 68       | 1.65%   |
| Intel Atom              | 41       | 1%      |
| Intel Core 2            | 38       | 0.92%   |
| AMD Ryzen Threadripper  | 38       | 0.92%   |
| Intel Core i9           | 35       | 0.85%   |
| AMD Phenom II X4        | 35       | 0.85%   |
| AMD Athlon 64 X2        | 35       | 0.85%   |
| AMD Athlon II X2        | 33       | 0.8%    |
| AMD Athlon              | 32       | 0.78%   |
| AMD A10                 | 31       | 0.75%   |
| Intel Pentium 4         | 28       | 0.68%   |
| Intel Pentium Gold      | 26       | 0.63%   |
| AMD A8                  | 26       | 0.63%   |
| AMD Ryzen 5 PRO         | 20       | 0.49%   |
| AMD GX                  | 19       | 0.46%   |
| AMD Phenom II X6        | 17       | 0.41%   |
| Intel Pentium Dual      | 15       | 0.36%   |
| AMD Athlon II X4        | 15       | 0.36%   |
| AMD Sempron             | 13       | 0.32%   |
| Intel Pentium D         | 12       | 0.29%   |
| AMD A4                  | 12       | 0.29%   |
| Intel Pentium Silver    | 11       | 0.27%   |
| AMD Phenom              | 11       | 0.27%   |
| AMD A6                  | 11       | 0.27%   |
| AMD E                   | 10       | 0.24%   |
| AMD Athlon 64           | 10       | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1403     | 34.03%  |
| 2       | 1199     | 29.08%  |
| 6       | 586      | 14.21%  |
| 8       | 406      | 9.85%   |
| 1       | 138      | 3.35%   |
| 12      | 129      | 3.13%   |
| 16      | 117      | 2.84%   |
| 3       | 45       | 1.09%   |
| 10      | 33       | 0.8%    |
| 24      | 20       | 0.49%   |
| 32      | 14       | 0.34%   |
| Unknown | 8        | 0.19%   |
| 14      | 6        | 0.15%   |
| 18      | 5        | 0.12%   |
| 64      | 3        | 0.07%   |
| 44      | 3        | 0.07%   |
| 22      | 3        | 0.07%   |
| 20      | 3        | 0.07%   |
| 36      | 1        | 0.02%   |
| 28      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4029     | 97.96%  |
| 2       | 74       | 1.8%    |
| Unknown | 8        | 0.19%   |
| 16      | 1        | 0.02%   |
| 0       | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2227     | 54.11%  |
| 1       | 1874     | 45.53%  |
| Unknown | 8        | 0.19%   |
| 4       | 6        | 0.15%   |
| 8       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3993     | 96.99%  |
| Unknown        | 81       | 1.97%   |
| 32-bit         | 43       | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 959      | 22.64%  |
| 0x306c3    | 341      | 8.05%   |
| 0x206a7    | 201      | 4.75%   |
| 0x1067a    | 195      | 4.6%    |
| 0x306a9    | 190      | 4.49%   |
| 0x506e3    | 156      | 3.68%   |
| 0x906ea    | 135      | 3.19%   |
| 0x08701021 | 128      | 3.02%   |
| 0xa0653    | 87       | 2.05%   |
| 0x906e9    | 81       | 1.91%   |
| 0x0800820d | 67       | 1.58%   |
| 0x08108109 | 65       | 1.53%   |
| 0x0a201016 | 59       | 1.39%   |
| 0xa0655    | 53       | 1.25%   |
| 0xa0671    | 45       | 1.06%   |
| 0x906c0    | 44       | 1.04%   |
| 0x90672    | 42       | 0.99%   |
| 0x010000c8 | 42       | 0.99%   |
| 0x08701013 | 40       | 0.94%   |
| 0x906ed    | 36       | 0.85%   |
| 0x08101016 | 34       | 0.8%    |
| 0x06000852 | 32       | 0.76%   |
| 0x306f2    | 31       | 0.73%   |
| 0x6fd      | 30       | 0.71%   |
| 0x206d7    | 30       | 0.71%   |
| 0x0a50000d | 30       | 0.71%   |
| 0x6fb      | 29       | 0.68%   |
| 0x08001137 | 29       | 0.68%   |
| 0x06003106 | 29       | 0.68%   |
| 0x306e4    | 28       | 0.66%   |
| 0x0a601203 | 27       | 0.64%   |
| 0x0a20120a | 27       | 0.64%   |
| 0x906eb    | 26       | 0.61%   |
| 0x08001138 | 24       | 0.57%   |
| 0x6f2      | 22       | 0.52%   |
| 0x106a5    | 22       | 0.52%   |
| 0x10676    | 22       | 0.52%   |
| 0x0a201009 | 22       | 0.52%   |
| 0x08600106 | 22       | 0.52%   |
| 0x206c2    | 21       | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 485      | 11.75%  |
| KabyLake         | 365      | 8.85%   |
| SandyBridge      | 289      | 7%      |
| Penryn           | 271      | 6.57%   |
| IvyBridge        | 268      | 6.5%    |
| Zen 2            | 261      | 6.33%   |
| Zen 3            | 219      | 5.31%   |
| Skylake          | 219      | 5.31%   |
| Zen+             | 196      | 4.75%   |
| CometLake        | 164      | 3.97%   |
| Unknown          | 157      | 3.81%   |
| Zen              | 141      | 3.42%   |
| K10              | 140      | 3.39%   |
| Core             | 131      | 3.17%   |
| Piledriver       | 123      | 2.98%   |
| Westmere         | 69       | 1.67%   |
| Silvermont       | 59       | 1.43%   |
| K8 Hammer        | 58       | 1.41%   |
| Nehalem          | 55       | 1.33%   |
| Tremont          | 52       | 1.26%   |
| NetBurst         | 50       | 1.21%   |
| Alderlake Hybrid | 50       | 1.21%   |
| Steamroller      | 37       | 0.9%    |
| Goldmont plus    | 37       | 0.9%    |
| Bulldozer        | 30       | 0.73%   |
| Bonnell          | 29       | 0.7%    |
| Broadwell        | 28       | 0.68%   |
| Goldmont         | 27       | 0.65%   |
| Excavator        | 21       | 0.51%   |
| Jaguar           | 20       | 0.48%   |
| Bobcat           | 19       | 0.46%   |
| Icelake          | 17       | 0.41%   |
| Puma             | 10       | 0.24%   |
| TigerLake        | 8        | 0.19%   |
| K6               | 7        | 0.17%   |
| P6               | 6        | 0.15%   |
| K10 Llano        | 5        | 0.12%   |
| Gracemont        | 2        | 0.05%   |
| Geode            | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1659     | 38.15%  |
| Nvidia                           | 1416     | 32.56%  |
| AMD                              | 1129     | 25.96%  |
| ASPEED Technology                | 80       | 1.84%   |
| Matrox Electronics Systems       | 45       | 1.03%   |
| VIA Technologies                 | 11       | 0.25%   |
| Silicon Integrated Systems [SiS] | 3        | 0.07%   |
| Loongson Technology              | 2        | 0.05%   |
| Silicon Motion                   | 1        | 0.02%   |
| Cirrus Logic                     | 1        | 0.02%   |
| ATI Technologies                 | 1        | 0.02%   |
| 3DLabs                           | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 232      | 5.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 151      | 3.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 150      | 3.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 131      | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 103      | 2.31%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 95       | 2.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 92       | 2.06%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 85       | 1.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 80       | 1.79%   |
| Intel HD Graphics 530                                                                    | 80       | 1.79%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 80       | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 76       | 1.71%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 75       | 1.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 68       | 1.53%   |
| Intel HD Graphics 630                                                                    | 58       | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 55       | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 54       | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 51       | 1.14%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 51       | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 50       | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                               | 47       | 1.05%   |
| Intel JasperLake [UHD Graphics]                                                          | 46       | 1.03%   |
| Intel HD Graphics 510                                                                    | 43       | 0.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 39       | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 35       | 0.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 35       | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 35       | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 35       | 0.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 35       | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 34       | 0.76%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 33       | 0.74%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 32       | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 32       | 0.72%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 32       | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 31       | 0.7%    |
| Intel AlderLake-S GT1                                                                    | 30       | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28       | 0.63%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 27       | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27       | 0.61%   |
| AMD Renoir                                                                               | 27       | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1486     | 35.71%  |
| 1 x Nvidia                        | 1281     | 30.79%  |
| 1 x AMD                           | 1005     | 24.15%  |
| Intel + Nvidia                    | 69       | 1.66%   |
| 1 x ASPEED                        | 62       | 1.49%   |
| 2 x AMD                           | 52       | 1.25%   |
| 1 x Matrox                        | 43       | 1.03%   |
| Other                             | 41       | 0.99%   |
| AMD + Nvidia                      | 34       | 0.82%   |
| Intel + AMD                       | 22       | 0.53%   |
| 2 x Nvidia                        | 15       | 0.36%   |
| 1 x VIA                           | 11       | 0.26%   |
| Nvidia + ASPEED                   | 11       | 0.26%   |
| AMD + ASPEED                      | 6        | 0.14%   |
| 2 x Intel                         | 5        | 0.12%   |
| AMD + Matrox                      | 4        | 0.1%    |
| 1 x SiS                           | 3        | 0.07%   |
| Intel + 2 x Nvidia                | 3        | 0.07%   |
| 3 x AMD                           | 1        | 0.02%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.02%   |
| 2 x Loongson Technology           | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.02%   |
| 1 x Silicon Motion                | 1        | 0.02%   |
| 1 x Loongson Technology           | 1        | 0.02%   |
| 1 x Cirrus Logic                  | 1        | 0.02%   |
| AMD + 3DLabs                      | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2392     | 57.49%  |
| Unknown     | 1060     | 25.47%  |
| Proprietary | 709      | 17.04%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2533     | 60.27%  |
| 1.01-2.0   | 379      | 9.02%   |
| 0.51-1.0   | 288      | 6.85%   |
| 0.01-0.5   | 266      | 6.33%   |
| 3.01-4.0   | 251      | 5.97%   |
| 7.01-8.0   | 237      | 5.64%   |
| 5.01-6.0   | 110      | 2.62%   |
| 8.01-16.0  | 72       | 1.71%   |
| 2.01-3.0   | 42       | 1%      |
| 16.01-24.0 | 17       | 0.4%    |
| 4.01-5.0   | 6        | 0.14%   |
| 32.01-64.0 | 1        | 0.02%   |
| 24.01-32.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 518      | 15.68%  |
| Dell                 | 383      | 11.6%   |
| Goldstar             | 326      | 9.87%   |
| Hewlett-Packard      | 209      | 6.33%   |
| Acer                 | 205      | 6.21%   |
| BenQ                 | 199      | 6.02%   |
| Philips              | 165      | 5%      |
| AOC                  | 161      | 4.87%   |
| Ancor Communications | 149      | 4.51%   |
| Iiyama               | 81       | 2.45%   |
| ViewSonic            | 73       | 2.21%   |
| Unknown              | 72       | 2.18%   |
| Lenovo               | 54       | 1.63%   |
| ASUSTek Computer     | 53       | 1.6%    |
| LG Electronics       | 49       | 1.48%   |
| Eizo                 | 37       | 1.12%   |
| Sony                 | 31       | 0.94%   |
| NEC Computers        | 27       | 0.82%   |
| Fujitsu Siemens      | 21       | 0.64%   |
| Unknown              | 19       | 0.58%   |
| Medion               | 18       | 0.54%   |
| Vizio                | 15       | 0.45%   |
| Vestel Elektronik    | 13       | 0.39%   |
| HannStar             | 13       | 0.39%   |
| Sceptre Tech         | 12       | 0.36%   |
| MSI                  | 12       | 0.36%   |
| Belinea              | 10       | 0.3%    |
| Panasonic            | 9        | 0.27%   |
| Idek Iiyama          | 9        | 0.27%   |
| HPN                  | 9        | 0.27%   |
| Hitachi              | 9        | 0.27%   |
| Toshiba              | 8        | 0.24%   |
| RTK                  | 8        | 0.24%   |
| HKC                  | 8        | 0.24%   |
| CHR                  | 8        | 0.24%   |
| Apple                | 8        | 0.24%   |
| Packard Bell         | 6        | 0.18%   |
| ONN                  | 6        | 0.18%   |
| MStar                | 6        | 0.18%   |
| Mi                   | 6        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 34       | 0.96%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 29       | 0.82%   |
| Unknown                                                               | 19       | 0.54%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 15       | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 14       | 0.4%    |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                         | 12       | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 12       | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 11       | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 11       | 0.31%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 10       | 0.28%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 9        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 9        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9        | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 9        | 0.25%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.25%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 8        | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 8        | 0.23%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 8        | 0.23%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                     | 8        | 0.23%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                        | 8        | 0.23%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 8        | 0.23%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 8        | 0.23%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 7        | 0.2%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch  | 7        | 0.2%    |
| Philips 190SW PHL086D 1440x900 400x250mm 18.6-inch                    | 7        | 0.2%    |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 7        | 0.2%    |
| CHR CH7511B CHR7511 1024x768 430x290mm 20.4-inch                      | 7        | 0.2%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 7        | 0.2%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 7        | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6        | 0.17%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 6        | 0.17%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 6        | 0.17%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 6        | 0.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6        | 0.17%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 6        | 0.17%   |
| Dell E178FP DELA027 1280x1024 338x270mm 17.0-inch                     | 6        | 0.17%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 6        | 0.17%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 6        | 0.17%   |
| AOC 2460X AOC2460 1920x1200 518x324mm 24.1-inch                       | 6        | 0.17%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 6        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1350     | 41.32%  |
| 3840x2160 (4K)     | 310      | 9.49%   |
| 1280x1024 (SXGA)   | 270      | 8.26%   |
| 2560x1440 (QHD)    | 240      | 7.35%   |
| 1680x1050 (WSXGA+) | 163      | 4.99%   |
| 1920x1200 (WUXGA)  | 121      | 3.7%    |
| Unknown            | 119      | 3.64%   |
| 1366x768 (WXGA)    | 110      | 3.37%   |
| 1440x900 (WXGA+)   | 88       | 2.69%   |
| 1600x900 (HD+)     | 87       | 2.66%   |
| 2560x1080          | 56       | 1.71%   |
| 3440x1440          | 51       | 1.56%   |
| 3840x1080          | 37       | 1.13%   |
| 1360x768           | 37       | 1.13%   |
| 2288x1287          | 36       | 1.1%    |
| 1024x768 (XGA)     | 33       | 1.01%   |
| 1600x1200          | 28       | 0.86%   |
| 1920x540           | 16       | 0.49%   |
| 4480x1440          | 12       | 0.37%   |
| 2560x1600          | 10       | 0.31%   |
| 3200x1080          | 7        | 0.21%   |
| 5760x2160          | 6        | 0.18%   |
| 5760x1080          | 6        | 0.18%   |
| 3840x1600          | 6        | 0.18%   |
| 1280x720 (HD)      | 6        | 0.18%   |
| 7680x2160          | 5        | 0.15%   |
| 3840x1200          | 4        | 0.12%   |
| 3360x1050          | 3        | 0.09%   |
| 2048x1152          | 3        | 0.09%   |
| 1400x1050          | 3        | 0.09%   |
| 6400x2160          | 2        | 0.06%   |
| 5760x1200          | 2        | 0.06%   |
| 5360x1440          | 2        | 0.06%   |
| 3600x1080          | 2        | 0.06%   |
| 2560x1024          | 2        | 0.06%   |
| 2048x1536          | 2        | 0.06%   |
| 1280x800 (WXGA)    | 2        | 0.06%   |
| 7680x4320          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |
| 7280x2160          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 458      | 14.06%  |
| 27      | 426      | 13.08%  |
| 23      | 386      | 11.85%  |
| Unknown | 345      | 10.59%  |
| 21      | 329      | 10.1%   |
| 19      | 207      | 6.35%   |
| 17      | 135      | 4.14%   |
| 18      | 127      | 3.9%    |
| 31      | 112      | 3.44%   |
| 22      | 107      | 3.28%   |
| 20      | 100      | 3.07%   |
| 34      | 80       | 2.46%   |
| 15      | 67       | 2.06%   |
| 84      | 47       | 1.44%   |
| 142     | 34       | 1.04%   |
| 25      | 32       | 0.98%   |
| 72      | 28       | 0.86%   |
| 32      | 26       | 0.8%    |
| 54      | 24       | 0.74%   |
| 40      | 21       | 0.64%   |
| 26      | 19       | 0.58%   |
| 28      | 16       | 0.49%   |
| 52      | 13       | 0.4%    |
| 29      | 10       | 0.31%   |
| 48      | 9        | 0.28%   |
| 35      | 8        | 0.25%   |
| 13      | 8        | 0.25%   |
| 39      | 7        | 0.21%   |
| 16      | 7        | 0.21%   |
| 65      | 6        | 0.18%   |
| 43      | 6        | 0.18%   |
| 42      | 6        | 0.18%   |
| 37      | 5        | 0.15%   |
| 12      | 5        | 0.15%   |
| 46      | 4        | 0.12%   |
| 38      | 4        | 0.12%   |
| 36      | 4        | 0.12%   |
| 33      | 4        | 0.12%   |
| 75      | 3        | 0.09%   |
| 49      | 3        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1174     | 37.19%  |
| 401-500        | 732      | 23.19%  |
| Unknown        | 345      | 10.93%  |
| 601-700        | 194      | 6.15%   |
| 301-350        | 192      | 6.08%   |
| 351-400        | 150      | 4.75%   |
| 701-800        | 112      | 3.55%   |
| 1501-2000      | 80       | 2.53%   |
| 1001-1500      | 67       | 2.12%   |
| 801-900        | 44       | 1.39%   |
| More than 2000 | 35       | 1.11%   |
| 201-300        | 17       | 0.54%   |
| 901-1000       | 13       | 0.41%   |
| 101-200        | 2        | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1833     | 60.38%  |
| 16/10   | 374      | 12.32%  |
| Unknown | 305      | 10.05%  |
| 5/4     | 251      | 8.27%   |
| 21/9    | 101      | 3.33%   |
| 4/3     | 82       | 2.7%    |
| 1.00    | 36       | 1.19%   |
| 3/2     | 25       | 0.82%   |
| 6/5     | 13       | 0.43%   |
| 32/9    | 9        | 0.3%    |
| 2.00    | 2        | 0.07%   |
| 1.96    | 2        | 0.07%   |
| 2.65    | 1        | 0.03%   |
| 11/10   | 1        | 0.03%   |
| 0.56    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1029     | 32.19%  |
| 301-350        | 437      | 13.67%  |
| 151-200        | 396      | 12.39%  |
| Unknown        | 345      | 10.79%  |
| 351-500        | 251      | 7.85%   |
| 141-150        | 215      | 6.73%   |
| 251-300        | 186      | 5.82%   |
| More than 1000 | 172      | 5.38%   |
| 501-1000       | 61       | 1.91%   |
| 101-110        | 58       | 1.81%   |
| 131-140        | 13       | 0.41%   |
| 111-120        | 10       | 0.31%   |
| 71-80          | 9        | 0.28%   |
| 121-130        | 7        | 0.22%   |
| 81-90          | 4        | 0.13%   |
| 1-40           | 2        | 0.06%   |
| 41-50          | 1        | 0.03%   |
| 91-100         | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1819     | 59.66%  |
| 101-120       | 536      | 17.58%  |
| Unknown       | 346      | 11.35%  |
| 121-160       | 150      | 4.92%   |
| 1-50          | 126      | 4.13%   |
| 161-240       | 69       | 2.26%   |
| More than 240 | 3        | 0.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2322     | 55.58%  |
| 0     | 1247     | 29.85%  |
| 2     | 542      | 12.97%  |
| 3     | 62       | 1.48%   |
| 4     | 5        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2533     | 45.38%  |
| Intel                             | 1685     | 30.19%  |
| Qualcomm Atheros                  | 309      | 5.54%   |
| Broadcom                          | 154      | 2.76%   |
| Ralink Technology                 | 95       | 1.7%    |
| Nvidia                            | 79       | 1.42%   |
| TP-Link                           | 63       | 1.13%   |
| MediaTek                          | 59       | 1.06%   |
| Ralink                            | 44       | 0.79%   |
| Broadcom Limited                  | 39       | 0.7%    |
| Marvell Technology Group          | 38       | 0.68%   |
| Aquantia                          | 37       | 0.66%   |
| Mellanox Technologies             | 24       | 0.43%   |
| ASIX Electronics                  | 24       | 0.43%   |
| D-Link System                     | 23       | 0.41%   |
| Samsung Electronics               | 22       | 0.39%   |
| Qualcomm Atheros Communications   | 22       | 0.39%   |
| Microsoft                         | 18       | 0.32%   |
| VIA Technologies                  | 17       | 0.3%    |
| ASUSTek Computer                  | 17       | 0.3%    |
| Huawei Technologies               | 16       | 0.29%   |
| D-Link                            | 16       | 0.29%   |
| American Megatrends               | 15       | 0.27%   |
| Edimax Technology                 | 13       | 0.23%   |
| NetGear                           | 12       | 0.21%   |
| 3Com                              | 11       | 0.2%    |
| Xiaomi                            | 8        | 0.14%   |
| Gemtek                            | 8        | 0.14%   |
| Belkin Components                 | 8        | 0.14%   |
| Sigma Designs                     | 7        | 0.13%   |
| Texas Instruments                 | 5        | 0.09%   |
| Sundance Technology Inc / IC Plus | 5        | 0.09%   |
| QinHeng Electronics               | 5        | 0.09%   |
| Linksys                           | 5        | 0.09%   |
| IMC Networks                      | 5        | 0.09%   |
| IBM                               | 5        | 0.09%   |
| Emulex                            | 5        | 0.09%   |
| DisplayLink                       | 5        | 0.09%   |
| ZTE WCDMA Technologies MSM        | 4        | 0.07%   |
| Wilocity                          | 4        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2033     | 32.51%  |
| Intel I211 Gigabit Network Connection                             | 213      | 3.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 209      | 3.34%   |
| Intel Wi-Fi 6 AX200                                               | 143      | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 128      | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 120      | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 115      | 1.84%   |
| Intel Ethernet Controller I225-V                                  | 109      | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 84       | 1.34%   |
| Intel I210 Gigabit Network Connection                             | 79       | 1.26%   |
| Intel 82579V Gigabit Network Connection                           | 73       | 1.17%   |
| Intel 82574L Gigabit Network Connection                           | 65       | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 55       | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 52       | 0.83%   |
| Nvidia MCP61 Ethernet                                             | 46       | 0.74%   |
| Intel Wireless 3165                                               | 46       | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 44       | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 43       | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 43       | 0.69%   |
| Intel Ethernet Connection (14) I219-V                             | 42       | 0.67%   |
| Intel Wireless-AC 9260                                            | 41       | 0.66%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 38       | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.59%   |
| Ralink MT7601U Wireless Adapter                                   | 37       | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37       | 0.59%   |
| Intel I350 Gigabit Network Connection                             | 34       | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32       | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 31       | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 30       | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 30       | 0.48%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 30       | 0.48%   |
| Realtek 802.11ac NIC                                              | 28       | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26       | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 26       | 0.42%   |
| Intel Wireless 7260                                               | 26       | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 24       | 0.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 24       | 0.38%   |
| Ralink RT5370 Wireless Adapter                                    | 22       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 515      | 36.71%  |
| Realtek Semiconductor                 | 276      | 19.67%  |
| Qualcomm Atheros                      | 154      | 10.98%  |
| Ralink Technology                     | 95       | 6.77%   |
| TP-Link                               | 58       | 4.13%   |
| MediaTek                              | 54       | 3.85%   |
| Broadcom                              | 47       | 3.35%   |
| Ralink                                | 44       | 3.14%   |
| Qualcomm Atheros Communications       | 22       | 1.57%   |
| ASUSTek Computer                      | 17       | 1.21%   |
| D-Link                                | 16       | 1.14%   |
| Microsoft                             | 15       | 1.07%   |
| Edimax Technology                     | 13       | 0.93%   |
| NetGear                               | 12       | 0.86%   |
| D-Link System                         | 12       | 0.86%   |
| Belkin Components                     | 8        | 0.57%   |
| Broadcom Limited                      | 7        | 0.5%    |
| Gemtek                                | 6        | 0.43%   |
| Linksys                               | 5        | 0.36%   |
| IMC Networks                          | 5        | 0.36%   |
| Wilocity                              | 4        | 0.29%   |
| Marvell Technology Group              | 3        | 0.21%   |
| AVM                                   | 3        | 0.21%   |
| ZyDAS                                 | 1        | 0.07%   |
| Xiaomi                                | 1        | 0.07%   |
| TRENDnet                              | 1        | 0.07%   |
| Tenda                                 | 1        | 0.07%   |
| Sitecom Europe                        | 1        | 0.07%   |
| PLANEX                                | 1        | 0.07%   |
| Micro Star International              | 1        | 0.07%   |
| Fiberline                             | 1        | 0.07%   |
| Encore Electronics                    | 1        | 0.07%   |
| CyberTAN Technology                   | 1        | 0.07%   |
| BUFFALO                               | 1        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 143      | 10.11%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 55       | 3.89%   |
| Intel Wireless 3165                                            | 46       | 3.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 44       | 3.11%   |
| Intel Wireless-AC 9260                                         | 41       | 2.9%    |
| Ralink MT7601U Wireless Adapter                                | 37       | 2.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 31       | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 30       | 2.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 30       | 2.12%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 30       | 2.12%   |
| Realtek 802.11ac NIC                                           | 28       | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 26       | 1.84%   |
| Intel Wireless 7260                                            | 26       | 1.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 24       | 1.7%    |
| Ralink RT5370 Wireless Adapter                                 | 22       | 1.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 21       | 1.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 19       | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                | 19       | 1.34%   |
| Intel Wireless 7265                                            | 18       | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 17       | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 17       | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16       | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 16       | 1.13%   |
| Intel Wireless 8260                                            | 16       | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15       | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 14       | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 14       | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14       | 0.99%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 13       | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 12       | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12       | 0.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 12       | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 11       | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 10       | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10       | 0.71%   |
| Intel Wireless 8265 / 8275                                     | 10       | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10       | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 9        | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 9        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2435     | 53.65%  |
| Intel                                  | 1411     | 31.09%  |
| Qualcomm Atheros                       | 168      | 3.7%    |
| Broadcom                               | 111      | 2.45%   |
| Nvidia                                 | 79       | 1.74%   |
| Aquantia                               | 37       | 0.82%   |
| Marvell Technology Group               | 36       | 0.79%   |
| Broadcom Limited                       | 32       | 0.71%   |
| ASIX Electronics                       | 24       | 0.53%   |
| Samsung Electronics                    | 22       | 0.48%   |
| Mellanox Technologies                  | 22       | 0.48%   |
| VIA Technologies                       | 17       | 0.37%   |
| American Megatrends                    | 15       | 0.33%   |
| Huawei Technologies                    | 11       | 0.24%   |
| D-Link System                          | 11       | 0.24%   |
| 3Com                                   | 11       | 0.24%   |
| Xiaomi                                 | 7        | 0.15%   |
| TP-Link                                | 5        | 0.11%   |
| Sundance Technology Inc / IC Plus      | 5        | 0.11%   |
| IBM                                    | 5        | 0.11%   |
| Emulex                                 | 5        | 0.11%   |
| DisplayLink                            | 5        | 0.11%   |
| Silicon Integrated Systems [SiS]       | 4        | 0.09%   |
| Qualcomm                               | 4        | 0.09%   |
| QLogic                                 | 4        | 0.09%   |
| Motorola PCS                           | 4        | 0.09%   |
| MediaTek                               | 4        | 0.09%   |
| OPPO Electronics                       | 3        | 0.07%   |
| Microsoft                              | 3        | 0.07%   |
| Insyde Software                        | 3        | 0.07%   |
| ICS Advent                             | 3        | 0.07%   |
| Google                                 | 3        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.04%   |
| SysKonnect                             | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| Solarflare Communications              | 2        | 0.04%   |
| Lenovo                                 | 2        | 0.04%   |
| JMicron Technology                     | 2        | 0.04%   |
| Gemtek                                 | 2        | 0.04%   |
| ADMtek                                 | 2        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2033     | 42.73%  |
| Intel I211 Gigabit Network Connection                             | 213      | 4.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 209      | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 128      | 2.69%   |
| Intel Ethernet Connection (2) I219-V                              | 120      | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 115      | 2.42%   |
| Intel Ethernet Controller I225-V                                  | 109      | 2.29%   |
| Intel Ethernet Connection I217-LM                                 | 84       | 1.77%   |
| Intel I210 Gigabit Network Connection                             | 79       | 1.66%   |
| Intel 82579V Gigabit Network Connection                           | 73       | 1.53%   |
| Intel 82574L Gigabit Network Connection                           | 65       | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 52       | 1.09%   |
| Nvidia MCP61 Ethernet                                             | 46       | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 43       | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 43       | 0.9%    |
| Intel Ethernet Connection (14) I219-V                             | 42       | 0.88%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 0.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 38       | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37       | 0.78%   |
| Intel I350 Gigabit Network Connection                             | 34       | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32       | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26       | 0.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 24       | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 22       | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 22       | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21       | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 21       | 0.44%   |
| Intel Ethernet Controller X550                                    | 19       | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 19       | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 19       | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18       | 0.38%   |
| Intel Ethernet Controller I226-V                                  | 18       | 0.38%   |
| Intel 82566DM Gigabit Network Connection                          | 18       | 0.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17       | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16       | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15       | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 15       | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4076     | 74.58%  |
| WiFi     | 1312     | 24.01%  |
| Modem    | 67       | 1.23%   |
| Unknown  | 10       | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3563     | 86.35%  |
| WiFi     | 563      | 13.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2626     | 63.41%  |
| 2     | 1115     | 26.93%  |
| 3     | 234      | 5.65%   |
| 4     | 64       | 1.55%   |
| 0     | 32       | 0.77%   |
| 6     | 26       | 0.63%   |
| 5     | 21       | 0.51%   |
| 7     | 7        | 0.17%   |
| 8     | 6        | 0.14%   |
| 9     | 4        | 0.1%    |
| 12    | 2        | 0.05%   |
| 33    | 1        | 0.02%   |
| 21    | 1        | 0.02%   |
| 17    | 1        | 0.02%   |
| 13    | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3493     | 83.87%  |
| Yes     | 671      | 16.11%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 480      | 43.8%   |
| Cambridge Silicon Radio         | 230      | 20.99%  |
| Realtek Semiconductor           | 85       | 7.76%   |
| ASUSTek Computer                | 77       | 7.03%   |
| Broadcom                        | 59       | 5.38%   |
| Qualcomm Atheros Communications | 41       | 3.74%   |
| MediaTek                        | 38       | 3.47%   |
| IMC Networks                    | 24       | 2.19%   |
| Apple                           | 12       | 1.09%   |
| TP-Link                         | 11       | 1%      |
| Foxconn / Hon Hai               | 9        | 0.82%   |
| Lite-On Technology              | 4        | 0.36%   |
| Belkin Components               | 4        | 0.36%   |
| Integrated System Solution      | 3        | 0.27%   |
| Edimax Technology               | 3        | 0.27%   |
| Realtek                         | 2        | 0.18%   |
| Micro Star International        | 2        | 0.18%   |
| Dynex                           | 2        | 0.18%   |
| Toshiba                         | 1        | 0.09%   |
| Sitecom Europe                  | 1        | 0.09%   |
| SINO WEALTH                     | 1        | 0.09%   |
| Qcom                            | 1        | 0.09%   |
| Microsoft                       | 1        | 0.09%   |
| Kensington                      | 1        | 0.09%   |
| HTC (High Tech Computer)        | 1        | 0.09%   |
| Hewlett-Packard                 | 1        | 0.09%   |
| Com One                         | 1        | 0.09%   |
| Unknown                         | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 230      | 20.97%  |
| Intel AX200 Bluetooth                                 | 138      | 12.58%  |
| Intel Bluetooth wireless interface                    | 115      | 10.48%  |
| Intel Bluetooth Device                                | 75       | 6.84%   |
| Realtek Bluetooth Radio                               | 72       | 6.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 42       | 3.83%   |
| Intel AX201 Bluetooth                                 | 41       | 3.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 39       | 3.56%   |
| MediaTek Wireless_Device                              | 38       | 3.46%   |
| Intel AX210 Bluetooth                                 | 37       | 3.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 26       | 2.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 25       | 2.28%   |
| Qualcomm Atheros  Bluetooth Device                    | 16       | 1.46%   |
| IMC Networks Bluetooth Radio                          | 14       | 1.28%   |
| TP-Link UB5A Adapter                                  | 11       | 1%      |
| ASUS Bluetooth Adapter                                | 11       | 1%      |
| ASUS ASUS USB-BT500                                   | 11       | 1%      |
| ASUS Bluetooth Radio                                  | 10       | 0.91%   |
| Realtek  Bluetooth 4.2 Adapter                        | 9        | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 7        | 0.64%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 6        | 0.55%   |
| IMC Networks Bluetooth Device                         | 6        | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                     | 6        | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.46%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)       | 5        | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 5        | 0.46%   |
| ASUS BCM20702A0                                       | 5        | 0.46%   |
| Apple Bluetooth Host Controller                       | 5        | 0.46%   |
| ASUS Qualcomm Bluetooth 4.1                           | 4        | 0.36%   |
| ASUS Bluetooth Device                                 | 4        | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 4        | 0.36%   |
| Realtek RTL8821A Bluetooth                            | 3        | 0.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3        | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3        | 0.27%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.27%   |
| Lite-On Bluetooth Device                              | 3        | 0.27%   |
| Broadcom Bluetooth 3.0 USB Dongle                     | 3        | 0.27%   |
| Realtek Bluetooth Radio                               | 2        | 0.18%   |
| Integrated System Solution Bluetooth Device           | 2        | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2518     | 40.76%  |
| AMD                                          | 1496     | 24.22%  |
| Nvidia                                       | 1328     | 21.5%   |
| C-Media Electronics                          | 140      | 2.27%   |
| Creative Labs                                | 68       | 1.1%    |
| Logitech                                     | 65       | 1.05%   |
| ASUSTek Computer                             | 39       | 0.63%   |
| Texas Instruments                            | 27       | 0.44%   |
| Micro Star International                     | 26       | 0.42%   |
| Generalplus Technology                       | 25       | 0.4%    |
| KTMicro                                      | 23       | 0.37%   |
| GN Netcom                                    | 23       | 0.37%   |
| Focusrite-Novation                           | 22       | 0.36%   |
| VIA Technologies                             | 20       | 0.32%   |
| JMTek                                        | 20       | 0.32%   |
| Creative Technology                          | 20       | 0.32%   |
| Kingston Technology                          | 18       | 0.29%   |
| Plantronics                                  | 15       | 0.24%   |
| SteelSeries ApS                              | 12       | 0.19%   |
| Dell                                         | 12       | 0.19%   |
| Realtek Semiconductor                        | 11       | 0.18%   |
| BEHRINGER International                      | 11       | 0.18%   |
| Razer USA                                    | 10       | 0.16%   |
| Corsair                                      | 10       | 0.16%   |
| Blue Microphones                             | 10       | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 9        | 0.15%   |
| GYROCOM C&C                                  | 9        | 0.15%   |
| RODE Microphones                             | 8        | 0.13%   |
| Yamaha                                       | 7        | 0.11%   |
| Giga-Byte Technology                         | 7        | 0.11%   |
| Samson Technologies                          | 6        | 0.1%    |
| M-Audio                                      | 6        | 0.1%    |
| Tenx Technology                              | 5        | 0.08%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.08%   |
| Microsoft                                    | 5        | 0.08%   |
| Cambridge Silicon Radio                      | 5        | 0.08%   |
| Sennheiser Communications                    | 4        | 0.06%   |
| Samsung Electronics                          | 4        | 0.06%   |
| Musical Fidelity                             | 4        | 0.06%   |
| XMOS                                         | 3        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 356      | 4.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 352      | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 289      | 3.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 272      | 3.75%   |
| AMD Family 17h/19h HD Audio Controller                                            | 261      | 3.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 234      | 3.23%   |
| Intel 200 Series PCH HD Audio                                                     | 220      | 3.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 207      | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 193      | 2.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 183      | 2.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 159      | 2.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 155      | 2.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 125      | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 120      | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 113      | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                     | 112      | 1.55%   |
| AMD FCH Azalia Controller                                                         | 105      | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                        | 98       | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 92       | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 89       | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                                     | 88       | 1.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 84       | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 79       | 1.09%   |
| Nvidia High Definition Audio Controller                                           | 77       | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 69       | 0.95%   |
| Intel Comet Lake PCH cAVS                                                         | 68       | 0.94%   |
| Intel Alder Lake-S HD Audio Controller                                            | 65       | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 63       | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                                     | 62       | 0.86%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 62       | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 61       | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                     | 60       | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 58       | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                     | 56       | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                                     | 55       | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 52       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 51       | 0.7%    |
| AMD Navi 10 HDMI Audio                                                            | 50       | 0.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 50       | 0.69%   |
| Nvidia MCP61 High Definition Audio                                                | 48       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 723      | 19.02%  |
| Unknown                      | 603      | 15.86%  |
| Crucial                      | 422      | 11.1%   |
| Samsung Electronics          | 386      | 10.16%  |
| Corsair                      | 339      | 8.92%   |
| SK hynix                     | 312      | 8.21%   |
| G.Skill                      | 259      | 6.81%   |
| Micron Technology            | 145      | 3.81%   |
| Patriot                      | 87       | 2.29%   |
| A-DATA Technology            | 69       | 1.82%   |
| Unknown                      | 42       | 1.1%    |
| Team                         | 34       | 0.89%   |
| Unknown (ABCD)               | 27       | 0.71%   |
| AMD                          | 27       | 0.71%   |
| Ramaxel Technology           | 26       | 0.68%   |
| Nanya Technology             | 25       | 0.66%   |
| Hikvision                    | 21       | 0.55%   |
| Elpida                       | 21       | 0.55%   |
| Transcend                    | 19       | 0.5%    |
| Smart                        | 15       | 0.39%   |
| Apacer                       | 11       | 0.29%   |
| GOODRAM                      | 10       | 0.26%   |
| Hewlett-Packard              | 9        | 0.24%   |
| GeIL                         | 9        | 0.24%   |
| Timetec                      | 8        | 0.21%   |
| Micro Memory Bank            | 8        | 0.21%   |
| Qimonda                      | 7        | 0.18%   |
| Avant                        | 7        | 0.18%   |
| Unknown (0x5846)             | 5        | 0.13%   |
| Toshiba                      | 5        | 0.13%   |
| Unknown (AB)                 | 4        | 0.11%   |
| PNY                          | 4        | 0.11%   |
| Patriot Memory (PDP Systems) | 4        | 0.11%   |
| Kingmax                      | 4        | 0.11%   |
| 48spaces                     | 4        | 0.11%   |
| V-Color                      | 3        | 0.08%   |
| Unknown (0x0B45)             | 3        | 0.08%   |
| Unifosa                      | 3        | 0.08%   |
| Silicon Power                | 3        | 0.08%   |
| OCZ                          | 3        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 52       | 1.24%   |
| Unknown                                                        | 42       | 1%      |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s          | 37       | 0.88%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s         | 35       | 0.83%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 33       | 0.79%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s          | 31       | 0.74%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 29       | 0.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 28       | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 27       | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 26       | 0.62%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s           | 24       | 0.57%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 23       | 0.55%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 23       | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s            | 21       | 0.5%    |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s        | 21       | 0.5%    |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s        | 20       | 0.48%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 19       | 0.45%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 18       | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 17       | 0.41%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s            | 16       | 0.38%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                | 16       | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 15       | 0.36%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 15       | 0.36%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                 | 15       | 0.36%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s        | 15       | 0.36%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 15       | 0.36%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 15       | 0.36%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 15       | 0.36%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 15       | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 14       | 0.33%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s           | 14       | 0.33%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 14       | 0.33%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 14       | 0.33%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 13       | 0.31%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 13       | 0.31%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 13       | 0.31%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 13       | 0.31%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s         | 13       | 0.31%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 12       | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 12       | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1539     | 45.13%  |
| DDR3         | 1114     | 32.67%  |
| Unknown      | 241      | 7.07%   |
| DDR2         | 192      | 5.63%   |
| SDRAM        | 182      | 5.34%   |
| DDR5         | 53       | 1.55%   |
| LPDDR4       | 40       | 1.17%   |
| DDR          | 39       | 1.14%   |
| DRAM         | 8        | 0.23%   |
| LPDDR3       | 1        | 0.03%   |
| DDR2 FB-DIMM | 1        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 3035     | 90.3%   |
| SODIMM       | 287      | 8.54%   |
| Row Of Chips | 13       | 0.39%   |
| RIMM         | 12       | 0.36%   |
| FB-DIMM      | 9        | 0.27%   |
| Unknown      | 4        | 0.12%   |
| Chip         | 1        | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 1189     | 32.01%  |
| 4096    | 835      | 22.48%  |
| 16384   | 617      | 16.61%  |
| 2048    | 589      | 15.86%  |
| 32768   | 246      | 6.62%   |
| 1024    | 180      | 4.85%   |
| 512     | 42       | 1.13%   |
| 256     | 6        | 0.16%   |
| 65536   | 5        | 0.13%   |
| 128     | 2        | 0.05%   |
| 1536    | 1        | 0.03%   |
| 64      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 649      | 17.47%  |
| 1333    | 394      | 10.61%  |
| 3200    | 327      | 8.8%    |
| 2667    | 265      | 7.13%   |
| 2400    | 226      | 6.08%   |
| 3600    | 208      | 5.6%    |
| 2133    | 200      | 5.38%   |
| 800     | 162      | 4.36%   |
| Unknown | 131      | 3.53%   |
| 667     | 108      | 2.91%   |
| 1866    | 92       | 2.48%   |
| 2666    | 82       | 2.21%   |
| 1867    | 58       | 1.56%   |
| 3000    | 55       | 1.48%   |
| 3400    | 52       | 1.4%    |
| 1066    | 49       | 1.32%   |
| 1800    | 48       | 1.29%   |
| 2933    | 47       | 1.27%   |
| 3733    | 38       | 1.02%   |
| 4800    | 32       | 0.86%   |
| 1067    | 31       | 0.83%   |
| 3800    | 28       | 0.75%   |
| 2866    | 27       | 0.73%   |
| 3266    | 25       | 0.67%   |
| 3466    | 23       | 0.62%   |
| 3533    | 20       | 0.54%   |
| 533     | 19       | 0.51%   |
| 400     | 19       | 0.51%   |
| 1334    | 18       | 0.48%   |
| 4333    | 16       | 0.43%   |
| 3866    | 14       | 0.38%   |
| 6000    | 13       | 0.35%   |
| 3933    | 13       | 0.35%   |
| 3100    | 13       | 0.35%   |
| 2800    | 13       | 0.35%   |
| 2048    | 13       | 0.35%   |
| 3666    | 12       | 0.32%   |
| 3534    | 12       | 0.32%   |
| 3500    | 10       | 0.27%   |
| 1648    | 10       | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 52       | 30.41%  |
| Brother Industries    | 37       | 21.64%  |
| Canon                 | 22       | 12.87%  |
| Samsung Electronics   | 14       | 8.19%   |
| Seiko Epson           | 8        | 4.68%   |
| Dymo-CoStar           | 6        | 3.51%   |
| Zebra                 | 4        | 2.34%   |
| Xerox                 | 4        | 2.34%   |
| Prolific Technology   | 4        | 2.34%   |
| Lexmark International | 4        | 2.34%   |
| Pantum                | 3        | 1.75%   |
| QinHeng Electronics   | 2        | 1.17%   |
| Kyocera               | 2        | 1.17%   |
| STMicroelectronics    | 1        | 0.58%   |
| Ricoh                 | 1        | 0.58%   |
| Printer               | 1        | 0.58%   |
| Oki Data              | 1        | 0.58%   |
| Konica Minolta        | 1        | 0.58%   |
| GODEX INTERNATIONAL   | 1        | 0.58%   |
| Dell                  | 1        | 0.58%   |
| Datamax-O'Neil        | 1        | 0.58%   |
| Apple                 | 1        | 0.58%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                          | 6        | 3.51%   |
| HP LaserJet 1200                                          | 5        | 2.92%   |
| Prolific PL2305 Parallel Port                             | 4        | 2.34%   |
| Xerox B205                                                | 3        | 1.75%   |
| Samsung ML-1660 Series                                    | 3        | 1.75%   |
| HP LaserJet M101-M106                                     | 3        | 1.75%   |
| Brother HL-52x0 series                                    | 3        | 1.75%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.17%   |
| Samsung M2020 Series                                      | 2        | 1.17%   |
| QinHeng CH340S                                            | 2        | 1.17%   |
| Pantum P2500W series                                      | 2        | 1.17%   |
| Lexmark International CS417dn                             | 2        | 1.17%   |
| HP LaserJet Pro M404-M405                                 | 2        | 1.17%   |
| HP LaserJet P1005                                         | 2        | 1.17%   |
| HP LaserJet M14-M17                                       | 2        | 1.17%   |
| HP LaserJet 400 M401a                                     | 2        | 1.17%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.17%   |
| HP ENVY 4520 series                                       | 2        | 1.17%   |
| HP DeskJet 2700 series                                    | 2        | 1.17%   |
| HP DeskJet 2130 series                                    | 2        | 1.17%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.17%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2        | 1.17%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.17%   |
| Canon MF4410                                              | 2        | 1.17%   |
| Canon MF3010                                              | 2        | 1.17%   |
| Canon LiDE 400                                            | 2        | 1.17%   |
| Brother MFC-7460DN                                        | 2        | 1.17%   |
| Brother HL-3040CN series                                  | 2        | 1.17%   |
| Brother HL-1110 series                                    | 2        | 1.17%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.58%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.58%   |
| Zebra ZTC S4M-200dpi ZPL                                  | 1        | 0.58%   |
| Zebra Printer                                             | 1        | 0.58%   |
| Xerox Phaser 3260                                         | 1        | 0.58%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.58%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.58%   |
| Seiko Epson XP-15000 Series                               | 1        | 0.58%   |
| Seiko Epson Printer                                       | 1        | 0.58%   |
| Seiko Epson M105 Series                                   | 1        | 0.58%   |
| Seiko Epson L396 Series                                   | 1        | 0.58%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 29       | 61.7%   |
| Seiko Epson        | 9        | 19.15%  |
| Hewlett-Packard    | 4        | 8.51%   |
| AGFA-Gevaert NV    | 2        | 4.26%   |
| Ultima Electronics | 1        | 2.13%   |
| Plustek            | 1        | 2.13%   |
| Mustek Systems     | 1        | 2.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 14.89%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6        | 12.77%  |
| Canon CanoScan LiDE 210                                                               | 4        | 8.51%   |
| Canon CanoScan LiDE 220                                                               | 3        | 6.38%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 2        | 4.26%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 4.26%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2        | 4.26%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 2.13%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 2.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 2.13%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 2.13%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 2.13%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 2.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 2.13%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 2.13%   |
| Plustek 1200dpi USB Scanner                                                           | 1        | 2.13%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 2.13%   |
| HP ScanJet Pro 2500 f1                                                                | 1        | 2.13%   |
| HP ScanJet 82x0C                                                                      | 1        | 2.13%   |
| HP ScanJet 3970c                                                                      | 1        | 2.13%   |
| HP Scanjet 300                                                                        | 1        | 2.13%   |
| Canon CanoScan LiDE 60                                                                | 1        | 2.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1        | 2.13%   |
| Canon CanoScan LIDE 25                                                                | 1        | 2.13%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 2.13%   |
| Canon CanoScan 8800F                                                                  | 1        | 2.13%   |
| Canon CanoScan 5600F                                                                  | 1        | 2.13%   |
| Canon CanoScan 4400F                                                                  | 1        | 2.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 267      | 43.56%  |
| Microdia                               | 44       | 7.18%   |
| Microsoft                              | 36       | 5.87%   |
| Samsung Electronics                    | 24       | 3.92%   |
| Generalplus Technology                 | 24       | 3.92%   |
| Sunplus Innovation Technology          | 23       | 3.75%   |
| Creative Technology                    | 16       | 2.61%   |
| Apple                                  | 15       | 2.45%   |
| Jieli Technology                       | 13       | 2.12%   |
| Z-Star Microelectronics                | 12       | 1.96%   |
| KYE Systems (Mouse Systems)            | 12       | 1.96%   |
| GEMBIRD                                | 10       | 1.63%   |
| ARC International                      | 10       | 1.63%   |
| Chicony Electronics                    | 8        | 1.31%   |
| Realtek Semiconductor                  | 5        | 0.82%   |
| Huawei Technologies                    | 5        | 0.82%   |
| MacroSilicon                           | 4        | 0.65%   |
| Hewlett-Packard                        | 4        | 0.65%   |
| Genesys Logic                          | 4        | 0.65%   |
| Cubeternet                             | 4        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.65%   |
| Quanta                                 | 3        | 0.49%   |
| Novatek Microelectronics               | 3        | 0.49%   |
| Google                                 | 3        | 0.49%   |
| AVerMedia Technologies                 | 3        | 0.49%   |
| Xiongmai                               | 2        | 0.33%   |
| Valve Software                         | 2        | 0.33%   |
| ValueHD                                | 2        | 0.33%   |
| Trust                                  | 2        | 0.33%   |
| Tobii Technology AB                    | 2        | 0.33%   |
| Syntek                                 | 2        | 0.33%   |
| Sunplus IT                             | 2        | 0.33%   |
| Ruision                                | 2        | 0.33%   |
| Razer USA                              | 2        | 0.33%   |
| Nintendo                               | 2        | 0.33%   |
| IMC Networks                           | 2        | 0.33%   |
| Aveo Technology                        | 2        | 0.33%   |
| Arkmicro Technologies                  | 2        | 0.33%   |
| 2M UVC CAMERA                          | 2        | 0.33%   |
| Xiaomi                                 | 1        | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 72       | 11.67%  |
| Logitech HD Pro Webcam C920                       | 47       | 7.62%   |
| Logitech C922 Pro Stream Webcam                   | 27       | 4.38%   |
| Samsung Galaxy series, misc. (MTP mode)           | 23       | 3.73%   |
| Microsoft LifeCam HD-3000                         | 20       | 3.24%   |
| Logitech Webcam C170                              | 16       | 2.59%   |
| Logitech HD Webcam C525                           | 15       | 2.43%   |
| Generalplus CAMERA - UVC                          | 15       | 2.43%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 14       | 2.27%   |
| Jieli USB PHY 2.0                                 | 13       | 2.11%   |
| Logitech Webcam C310                              | 12       | 1.94%   |
| Microdia Webcam Vitade AF                         | 11       | 1.78%   |
| KYE Systems (Mouse Systems) Genius Webcam         | 11       | 1.78%   |
| Microdia GC02M2                                   | 9        | 1.46%   |
| Logitech HD Webcam C910                           | 9        | 1.46%   |
| Z-Star Venus USB2.0 Camera                        | 7        | 1.13%   |
| Logitech HD Webcam C615                           | 7        | 1.13%   |
| ARC International Camera                          | 7        | 1.13%   |
| Sunplus FHD Camera Microphone                     | 6        | 0.97%   |
| Logitech BRIO Ultra HD Webcam                     | 6        | 0.97%   |
| Generalplus 808 Camera                            | 6        | 0.97%   |
| GEMBIRD USB2.0 PC CAMERA                          | 6        | 0.97%   |
| Sunplus papalook AF 925                           | 5        | 0.81%   |
| Microdia USB 2.0 Camera                           | 5        | 0.81%   |
| Microdia Integrated Camera                        | 5        | 0.81%   |
| Huawei HiCamera                                   | 5        | 0.81%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 0.65%   |
| Microdia Camera                                   | 4        | 0.65%   |
| Logitech Webcam C925e                             | 4        | 0.65%   |
| Logitech Webcam C210                              | 4        | 0.65%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 4        | 0.65%   |
| Creative Live! Cam Chat HD [VF0700]               | 4        | 0.65%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 4        | 0.65%   |
| Novatek HP High Definition 2MP Webcam             | 3        | 0.49%   |
| Microsoft LifeCam VX-500 [1357]                   | 3        | 0.49%   |
| Microsoft LifeCam HD-5000                         | 3        | 0.49%   |
| MacroSilicon USB Video                            | 3        | 0.49%   |
| Logitech Webcam Pro 9000                          | 3        | 0.49%   |
| Logitech Webcam C930e                             | 3        | 0.49%   |
| Logitech StreamCam                                | 3        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 33.33%  |
| Synaptics             | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 33.33%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 6        | 15.38%  |
| Alcor Micro                | 5        | 12.82%  |
| Realtek Semiconductor      | 4        | 10.26%  |
| Gemalto (was Gemplus)      | 4        | 10.26%  |
| Cherry                     | 4        | 10.26%  |
| Clay Logic                 | 3        | 7.69%   |
| Yubico.com                 | 2        | 5.13%   |
| Reiner SCT Kartensysteme   | 2        | 5.13%   |
| Chicony Electronics        | 2        | 5.13%   |
| Aladdin Knowledge Systems  | 2        | 5.13%   |
| Advanced Card Systems      | 2        | 5.13%   |
| Lenovo                     | 1        | 2.56%   |
| Feitian Technologies       | 1        | 2.56%   |
| Athena Smartcard Solutions | 1        | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 10.26%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 10.26%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 7.69%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 5.13%   |
| Clay Logic Nitrokey Pro                                                    | 2        | 5.13%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 5.13%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 2        | 5.13%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 5.13%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 2.56%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.56%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 2.56%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.56%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 2.56%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 2.56%   |
| Feitian Technologies SCR301                                                | 1        | 2.56%   |
| Clay Logic Nitrokey Start                                                  | 1        | 2.56%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 2.56%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                 | 1        | 2.56%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 1        | 2.56%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.56%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2709     | 64.86%  |
| 1     | 1259     | 30.14%  |
| 2     | 179      | 4.29%   |
| 3     | 21       | 0.5%    |
| 5     | 3        | 0.07%   |
| 4     | 3        | 0.07%   |
| 6     | 2        | 0.05%   |
| 7     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1121     | 69.63%  |
| Net/wireless             | 148      | 9.19%   |
| Communication controller | 81       | 5.03%   |
| Unassigned class         | 72       | 4.47%   |
| Sound                    | 34       | 2.11%   |
| Multimedia controller    | 31       | 1.93%   |
| Bluetooth                | 23       | 1.43%   |
| Chipcard                 | 18       | 1.12%   |
| Net/ethernet             | 17       | 1.06%   |
| Camera                   | 15       | 0.93%   |
| Card reader              | 11       | 0.68%   |
| Storage/raid             | 9        | 0.56%   |
| Storage/ide              | 6        | 0.37%   |
| Network                  | 6        | 0.37%   |
| Modem                    | 4        | 0.25%   |
| Dvb card                 | 4        | 0.25%   |
| Tv card                  | 3        | 0.19%   |
| Fingerprint reader       | 3        | 0.19%   |
| Storage                  | 2        | 0.12%   |
| Wireless                 | 1        | 0.06%   |
| Storage/nvme             | 1        | 0.06%   |

