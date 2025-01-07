Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 172

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | H110M PRO-VD PLUS           | [6b9f134647](https://linux-hardware.org/?probe=6b9f134647) | Jan 05, 2025 |
| MSI           | PRO X870-P WIFI             | [c9a82e8bd9](https://linux-hardware.org/?probe=c9a82e8bd9) | Dec 13, 2024 |
| Shenzhen M... | AHWSA                       | [2bc5597511](https://linux-hardware.org/?probe=2bc5597511) | Dec 05, 2024 |
| Gigabyte      | Z690 UD DDR4                | [367385929b](https://linux-hardware.org/?probe=367385929b) | Nov 28, 2024 |
| ASUSTek       | Z170-P                      | [814a4954e8](https://linux-hardware.org/?probe=814a4954e8) | Nov 22, 2024 |
| MSI           | B450-A PRO MAX              | [74b369c302](https://linux-hardware.org/?probe=74b369c302) | Nov 21, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [777759441c](https://linux-hardware.org/?probe=777759441c) | Nov 20, 2024 |
| Gigabyte      | H61M-S1                     | [afe93e20da](https://linux-hardware.org/?probe=afe93e20da) | Nov 16, 2024 |
| ASRock        | B650 LiveMixer              | [1cae9e87fc](https://linux-hardware.org/?probe=1cae9e87fc) | Oct 25, 2024 |
| ASRock        | Z77 Performance             | [01cb85dde8](https://linux-hardware.org/?probe=01cb85dde8) | Oct 22, 2024 |
| Dell          | 0NK70N A03                  | [33c83f5d6f](https://linux-hardware.org/?probe=33c83f5d6f) | Oct 14, 2024 |
| HP            | 81B4                        | [6b0bb4a74e](https://linux-hardware.org/?probe=6b0bb4a74e) | Oct 10, 2024 |
| Unknown       | YL-J1900-V2                 | [c095fc1d28](https://linux-hardware.org/?probe=c095fc1d28) | Oct 08, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d167dbf12f](https://linux-hardware.org/?probe=d167dbf12f) | Sep 18, 2024 |
| ASRock        | B660M Pro RS                | [15cb87a4a4](https://linux-hardware.org/?probe=15cb87a4a4) | Sep 01, 2024 |
| HP            | 1791                        | [73deeb4fdb](https://linux-hardware.org/?probe=73deeb4fdb) | Sep 01, 2024 |
| ASRock        | Z690 Pro RS                 | [ab1e0d0b70](https://linux-hardware.org/?probe=ab1e0d0b70) | Sep 01, 2024 |
| ASRock        | B660 Pro RS                 | [d51849c1f3](https://linux-hardware.org/?probe=d51849c1f3) | Sep 01, 2024 |
| HP            | 1589                        | [f3d101d67d](https://linux-hardware.org/?probe=f3d101d67d) | Sep 01, 2024 |
| ASRock        | B660 Pro RS                 | [31ffd0c8cd](https://linux-hardware.org/?probe=31ffd0c8cd) | Sep 01, 2024 |
| MSI           | Z370 GAMING M5              | [3a36128c03](https://linux-hardware.org/?probe=3a36128c03) | Aug 27, 2024 |
| ASRock        | Z790 PG Lightning/D4        | [7e3b3247ae](https://linux-hardware.org/?probe=7e3b3247ae) | Aug 23, 2024 |
| ASRock        | B650 LiveMixer              | [5570dc6d1f](https://linux-hardware.org/?probe=5570dc6d1f) | Aug 13, 2024 |
| Dell          | 06CV2N A01                  | [4c5c7fedbc](https://linux-hardware.org/?probe=4c5c7fedbc) | Aug 04, 2024 |
| Dell          | 06XMFM A02                  | [c9ed30c21c](https://linux-hardware.org/?probe=c9ed30c21c) | Jul 26, 2024 |
| ASRock        | Z77 Performance             | [3235e7c866](https://linux-hardware.org/?probe=3235e7c866) | Jul 25, 2024 |
| Pegatron      | 2AB5                        | [c94576fefd](https://linux-hardware.org/?probe=c94576fefd) | Jul 24, 2024 |
| ASRockRack    | X470D4U                     | [b3953ac4ba](https://linux-hardware.org/?probe=b3953ac4ba) | Jul 06, 2024 |
| Dell          | 0VTKY7 A00                  | [c4e7ae2b86](https://linux-hardware.org/?probe=c4e7ae2b86) | Jul 02, 2024 |
| Dell          | 0C4H12 A00                  | [5c1c566f58](https://linux-hardware.org/?probe=5c1c566f58) | Jun 30, 2024 |
| HP            | 8876 11                     | [bbb34882c8](https://linux-hardware.org/?probe=bbb34882c8) | Jun 26, 2024 |
| Dell          | 0VTKY7 A00                  | [61f6792355](https://linux-hardware.org/?probe=61f6792355) | Jun 25, 2024 |
| Dell          | 0VTKY7 A00                  | [be09b39701](https://linux-hardware.org/?probe=be09b39701) | Jun 25, 2024 |
| HP            | 8876 11                     | [9bc16b89e7](https://linux-hardware.org/?probe=9bc16b89e7) | Jun 24, 2024 |
| ASRock        | Z77 Performance             | [772cecb8ab](https://linux-hardware.org/?probe=772cecb8ab) | Jun 22, 2024 |
| ASRock        | G31M-S                      | [6ed3e35541](https://linux-hardware.org/?probe=6ed3e35541) | Jun 21, 2024 |
| Gigabyte      | TRX50 AERO D                | [bd0ceaa990](https://linux-hardware.org/?probe=bd0ceaa990) | Jun 13, 2024 |
| Supermicro    | X10DAI                      | [006e94afd4](https://linux-hardware.org/?probe=006e94afd4) | Jun 11, 2024 |
| Supermicro    | X10DAI                      | [b308552347](https://linux-hardware.org/?probe=b308552347) | Jun 07, 2024 |
| ASRock        | G31M-S                      | [53b9eebd24](https://linux-hardware.org/?probe=53b9eebd24) | May 18, 2024 |
| ASRock        | Z77 Performance             | [7bef6fd4d3](https://linux-hardware.org/?probe=7bef6fd4d3) | May 16, 2024 |
| Gigabyte      | 970A-DS3P                   | [e9c41c2a25](https://linux-hardware.org/?probe=e9c41c2a25) | Apr 07, 2024 |
| Gigabyte      | H310 D3 x.x                 | [d524f96da0](https://linux-hardware.org/?probe=d524f96da0) | Apr 04, 2024 |
| Gigabyte      | Z97P-D3                     | [4b656f9e6d](https://linux-hardware.org/?probe=4b656f9e6d) | Mar 25, 2024 |
| HP            | 889C                        | [395bdd06d9](https://linux-hardware.org/?probe=395bdd06d9) | Mar 19, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [7c2336be5e](https://linux-hardware.org/?probe=7c2336be5e) | Mar 18, 2024 |
| Gigabyte      | 970A-DS3P                   | [f1a78a6388](https://linux-hardware.org/?probe=f1a78a6388) | Mar 15, 2024 |
| Gigabyte      | X399 AORUS PRO-CF           | [c60aa1b735](https://linux-hardware.org/?probe=c60aa1b735) | Mar 06, 2024 |
| ASUSTek       | PRIME Z790-P D4             | [eb0b332d22](https://linux-hardware.org/?probe=eb0b332d22) | Mar 06, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a4836fd9a9](https://linux-hardware.org/?probe=a4836fd9a9) | Mar 06, 2024 |
| ASUSTek       | PRIME B250-PLUS             | [41dbc538ba](https://linux-hardware.org/?probe=41dbc538ba) | Feb 26, 2024 |
| BESSTAR Te... | UM700                       | [521bf7584c](https://linux-hardware.org/?probe=521bf7584c) | Feb 21, 2024 |
| Dell          | 096JG8 A01                  | [d775aa1202](https://linux-hardware.org/?probe=d775aa1202) | Feb 19, 2024 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [7837a817bf](https://linux-hardware.org/?probe=7837a817bf) | Feb 13, 2024 |
| Unknown       | T3 MRD                      | [e3b3bc071f](https://linux-hardware.org/?probe=e3b3bc071f) | Jan 31, 2024 |
| HP            | 8653 A                      | [64cfa9a25f](https://linux-hardware.org/?probe=64cfa9a25f) | Jan 30, 2024 |
| Machenike     | ARB19                       | [3002916884](https://linux-hardware.org/?probe=3002916884) | Jan 28, 2024 |
| Machenike     | ARB19                       | [4f289b9a02](https://linux-hardware.org/?probe=4f289b9a02) | Jan 28, 2024 |
| Dell          | 0D735T A00                  | [4f4fe7da0b](https://linux-hardware.org/?probe=4f4fe7da0b) | Jan 06, 2024 |
| Intel         | X99                         | [ed34568c2b](https://linux-hardware.org/?probe=ed34568c2b) | Jan 05, 2024 |
| Unknown       | Unknown                     | [3faf86bf2b](https://linux-hardware.org/?probe=3faf86bf2b) | Jan 04, 2024 |
| ASUSTek       | PRIME Z490-P                | [61724f27e7](https://linux-hardware.org/?probe=61724f27e7) | Dec 23, 2023 |
| ASRock        | Z790 Taichi                 | [3bc8305321](https://linux-hardware.org/?probe=3bc8305321) | Dec 22, 2023 |
| ASRock        | Z790 Taichi                 | [bffb0cadbe](https://linux-hardware.org/?probe=bffb0cadbe) | Dec 17, 2023 |
| Gigabyte      | X670 GAMING X AX            | [18d321d9d6](https://linux-hardware.org/?probe=18d321d9d6) | Dec 06, 2023 |
| HP            | 2AF3                        | [fd3b043741](https://linux-hardware.org/?probe=fd3b043741) | Nov 25, 2023 |
| Pegatron      | IPMIP-GS                    | [fb0f45f5b0](https://linux-hardware.org/?probe=fb0f45f5b0) | Nov 24, 2023 |
| HP            | 158B                        | [bd8928c0a2](https://linux-hardware.org/?probe=bd8928c0a2) | Nov 22, 2023 |
| System76      | Thelio Mira thelio-mira-... | [a6d3f50714](https://linux-hardware.org/?probe=a6d3f50714) | Nov 18, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [bdbde84396](https://linux-hardware.org/?probe=bdbde84396) | Nov 18, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [3734293144](https://linux-hardware.org/?probe=3734293144) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [72bedff7a6](https://linux-hardware.org/?probe=72bedff7a6) | Nov 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| HP            | 1587h                       | [ecafcd1843](https://linux-hardware.org/?probe=ecafcd1843) | Oct 30, 2023 |
| HP            | 8653 A                      | [6d84c59a16](https://linux-hardware.org/?probe=6d84c59a16) | Oct 25, 2023 |
| Lenovo        | 31900058 STD                | [b6c589b413](https://linux-hardware.org/?probe=b6c589b413) | Oct 19, 2023 |
| Shenzhen M... | HX90G                       | [a6e9f6c7fc](https://linux-hardware.org/?probe=a6e9f6c7fc) | Oct 01, 2023 |
| Dell          | 0D24M8 A01                  | [214eb681ad](https://linux-hardware.org/?probe=214eb681ad) | Oct 01, 2023 |
| ASUSTek       | F1A55-M LX PLUS             | [a2aebc52bd](https://linux-hardware.org/?probe=a2aebc52bd) | Sep 03, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [e584e6c368](https://linux-hardware.org/?probe=e584e6c368) | Aug 16, 2023 |
| ASRock        | X670E Pro RS                | [baa9e459cc](https://linux-hardware.org/?probe=baa9e459cc) | Aug 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [32fd45f163](https://linux-hardware.org/?probe=32fd45f163) | Aug 04, 2023 |
| MSI           | PRO B650-P WIFI             | [92abff2d6e](https://linux-hardware.org/?probe=92abff2d6e) | Jul 31, 2023 |
| MSI           | PRO B650-P WIFI             | [d1c158eebc](https://linux-hardware.org/?probe=d1c158eebc) | Jul 31, 2023 |
| HP            | 0AECh D                     | [58f6dd1695](https://linux-hardware.org/?probe=58f6dd1695) | Jul 14, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b4b1f263a8](https://linux-hardware.org/?probe=b4b1f263a8) | Jul 08, 2023 |
| Gigabyte      | H61M-DS2                    | [2310257292](https://linux-hardware.org/?probe=2310257292) | Jun 19, 2023 |
| Gigabyte      | H61M-DS2                    | [ee6f9906b5](https://linux-hardware.org/?probe=ee6f9906b5) | Jun 19, 2023 |
| Techvision    | TVI7309X B0                 | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [da8705e5a7](https://linux-hardware.org/?probe=da8705e5a7) | May 31, 2023 |
| HPE           | ProLiant MicroServer Gen... | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| ASRock        | AM1B-ITX                    | [a2e80bffac](https://linux-hardware.org/?probe=a2e80bffac) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | [d0633ac39d](https://linux-hardware.org/?probe=d0633ac39d) | May 19, 2023 |
| AZW           | MINI S                      | [d7ee12a01b](https://linux-hardware.org/?probe=d7ee12a01b) | May 08, 2023 |
| Dell          | 0D735T A00                  | [3070f4e7da](https://linux-hardware.org/?probe=3070f4e7da) | May 02, 2023 |
| Dell          | 06D7TR A00                  | [6fe7179a50](https://linux-hardware.org/?probe=6fe7179a50) | May 01, 2023 |
| Dell          | 0Y2MRG A00                  | [5f765d4d9c](https://linux-hardware.org/?probe=5f765d4d9c) | Apr 29, 2023 |
| Dell          | 0Y2MRG A00                  | [62a4a8b0b5](https://linux-hardware.org/?probe=62a4a8b0b5) | Apr 29, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [fd875a6058](https://linux-hardware.org/?probe=fd875a6058) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| AZW           | GTR V02                     | [fcd41fbe77](https://linux-hardware.org/?probe=fcd41fbe77) | Mar 10, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| HP            | 1587h                       | [312effb7b7](https://linux-hardware.org/?probe=312effb7b7) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| Dell          | 08HPGT A01                  | [bf2c6ebd43](https://linux-hardware.org/?probe=bf2c6ebd43) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| ASRock        | H610M-HDV/M.2               | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| Lenovo        | NOK                         | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Dell          | 0Y2MRG A00                  | [784e2db087](https://linux-hardware.org/?probe=784e2db087) | Jan 25, 2023 |
| MSI           | H510M PRO-E                 | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| Unknown       | Unknown                     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Dell          | 0VRWRC A00                  | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | 805D                        | [cf88e571df](https://linux-hardware.org/?probe=cf88e571df) | Dec 28, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| ASUSTek       | X99-WS/IPMI                 | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Intel         | D33217GKE G69901-202        | [f10d00e42a](https://linux-hardware.org/?probe=f10d00e42a) | Nov 12, 2022 |
| HP            | 8054                        | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASUSTek       | Crosshair V Formula         | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV                   | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| BESSTAR Te... | HM90                        | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME H570-PLUS             | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| ASUSTek       | PRIME B550M-K               | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| ASUSTek       | P8B WS                      | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK                 | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Gigabyte      | 970A-UD3P                   | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| Unknown       | X31_ICH7                    | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01                  | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 06CV2N A00                  | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3                  | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1             | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Dell          | 0NK70N A03                  | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Dell          | 0WN7Y6 A01                  | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02                  | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| ASRock        | B450M Pro4                  | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6               | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| AZW           | Gemini M                    | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                    | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Panther                     | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF                  | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Dell          | 0N4YC8 A00                  | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A II            | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | NOK                         | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Dell          | 0M5DCD A00                  | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| HP            | 0B54h D                     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Rocky Linux 9.1  | 18       | 13.85%  |
| Rocky Linux 9.3  | 15       | 11.54%  |
| Rocky Linux 8.5  | 12       | 9.23%   |
| Rocky Linux 9.2  | 11       | 8.46%   |
| Rocky Linux 9.4  | 10       | 7.69%   |
| Rocky Linux 8.8  | 9        | 6.92%   |
| Rocky Linux 8.7  | 9        | 6.92%   |
| Rocky Linux 8.4  | 9        | 6.92%   |
| Rocky Linux 8.10 | 9        | 6.92%   |
| Rocky Linux 8.6  | 8        | 6.15%   |
| Rocky Linux 9.5  | 7        | 5.38%   |
| Rocky Linux 9.0  | 7        | 5.38%   |
| Rocky Linux 8.9  | 5        | 3.85%   |
| Rocky Linux 8.3  | 1        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 126      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 6        | 4.32%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 4.32%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 5        | 3.6%    |
| 5.14.0-362.18.1.el9_3.0.1.x86_64 | 4        | 2.88%   |
| 5.14.0-362.13.1.el9_3.x86_64     | 4        | 2.88%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 4        | 2.88%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 4        | 2.88%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 4        | 2.88%   |
| 4.18.0-553.5.1.el8_10.x86_64     | 4        | 2.88%   |
| 4.18.0-425.19.2.el8_7.x86_64     | 4        | 2.88%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 3        | 2.16%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 3        | 2.16%   |
| 5.14.0-503.15.1.el9_5.x86_64     | 3        | 2.16%   |
| 5.14.0-427.35.1.el9_4.x86_64     | 3        | 2.16%   |
| 5.14.0-362.8.1.el9_3.x86_64      | 3        | 2.16%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 3        | 2.16%   |
| 4.18.0-553.16.1.el8_10.x86_64    | 3        | 2.16%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 2.16%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 2.16%   |
| 5.14.0-503.14.1.el9_5.x86_64     | 2        | 1.44%   |
| 5.14.0-427.42.1.el9_4.x86_64     | 2        | 1.44%   |
| 5.14.0-427.24.1.el9_4.x86_64     | 2        | 1.44%   |
| 5.14.0-427.20.1.el9_4.x86_64     | 2        | 1.44%   |
| 5.14.0-362.24.1.el9_3.x86_64     | 2        | 1.44%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 2        | 1.44%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2        | 1.44%   |
| 4.18.0-553.22.1.el8_10.x86_64    | 2        | 1.44%   |
| 4.18.0-513.18.1.el8_9.x86_64     | 2        | 1.44%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 2        | 1.44%   |
| 4.18.0-477.15.1.el8_8.x86_64     | 2        | 1.44%   |
| 4.18.0-425.3.1.el8.x86_64        | 2        | 1.44%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 2        | 1.44%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 2        | 1.44%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 2        | 1.44%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2        | 1.44%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 1.44%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 1.44%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 1.44%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 1.44%   |
| 6.6.11-1.el9.elrepo.x86_64       | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 63       | 49.61%  |
| 4.18.0  | 58       | 45.67%  |
| 6.0.10  | 2        | 1.57%   |
| 6.6.11  | 1        | 0.79%   |
| 6.1.8   | 1        | 0.79%   |
| 6.1.6   | 1        | 0.79%   |
| 5.14.1  | 1        | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 64       | 50.39%  |
| 4.18    | 58       | 45.67%  |
| 6.1     | 2        | 1.57%   |
| 6.0     | 2        | 1.57%   |
| 6.6     | 1        | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 126      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 76       | 59.38%  |
| Unknown       | 26       | 20.31%  |
| KDE5          | 10       | 7.81%   |
| GNOME Classic | 6        | 4.69%   |
| XFCE          | 5        | 3.91%   |
| MATE          | 5        | 3.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 57       | 43.18%  |
| X11     | 50       | 37.88%  |
| Tty     | 11       | 8.33%   |
| Unknown | 9        | 6.82%   |
| Web     | 5        | 3.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 68       | 53.54%  |
| GDM     | 49       | 38.58%  |
| SDDM    | 6        | 4.72%   |
| LightDM | 4        | 3.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 78       | 60.47%  |
| en_GB   | 6        | 4.65%   |
| C       | 5        | 3.88%   |
| ru_RU   | 4        | 3.1%    |
| en_CA   | 4        | 3.1%    |
| ko_KR   | 3        | 2.33%   |
| fr_CA   | 3        | 2.33%   |
| en_IL   | 3        | 2.33%   |
| Unknown | 3        | 2.33%   |
| ja_JP   | 2        | 1.55%   |
| it_IT   | 2        | 1.55%   |
| en_SG   | 2        | 1.55%   |
| en_AU   | 2        | 1.55%   |
| zh_CN   | 1        | 0.78%   |
| ro_RO   | 1        | 0.78%   |
| pt_BR   | 1        | 0.78%   |
| pl_PL   | 1        | 0.78%   |
| es_CO   | 1        | 0.78%   |
| es_AR   | 1        | 0.78%   |
| en_ZA   | 1        | 0.78%   |
| en_NZ   | 1        | 0.78%   |
| en_IN   | 1        | 0.78%   |
| de_DE   | 1        | 0.78%   |
| Default | 1        | 0.78%   |
| af_ZA   | 1        | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 81       | 63.28%  |
| BIOS | 47       | 36.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 104      | 82.54%  |
| Ext4 | 21       | 16.67%  |
| Ext2 | 1        | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 70       | 55.56%  |
| Unknown | 38       | 30.16%  |
| MBR     | 18       | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 80.95%  |
| Yes       | 24       | 19.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 87.3%   |
| Yes       | 16       | 12.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 26       | 20.63%  |
| Dell                                 | 20       | 15.87%  |
| Gigabyte Technology                  | 16       | 12.7%   |
| Hewlett-Packard                      | 13       | 10.32%  |
| MSI                                  | 12       | 9.52%   |
| ASRock                               | 12       | 9.52%   |
| Lenovo                               | 4        | 3.17%   |
| Unknown                              | 4        | 3.17%   |
| AZW                                  | 3        | 2.38%   |
| Pegatron                             | 2        | 1.59%   |
| Intel                                | 2        | 1.59%   |
| BESSTAR Tech                         | 2        | 1.59%   |
| Techvision                           | 1        | 0.79%   |
| System76                             | 1        | 0.79%   |
| Supermicro                           | 1        | 0.79%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.79%   |
| Sapphire                             | 1        | 0.79%   |
| NCR                                  | 1        | 0.79%   |
| Machenike                            | 1        | 0.79%   |
| HPE                                  | 1        | 0.79%   |
| Google                               | 1        | 0.79%   |
| ASRockRack                           | 1        | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 4        | 3.17%   |
| HP Z210 Workstation                               | 2        | 1.59%   |
| Gigabyte 970A-DS3P                                | 2        | 1.59%   |
| Dell Vostro 3681                                  | 2        | 1.59%   |
| Dell Precision T7610                              | 2        | 1.59%   |
| Dell Precision 3680                               | 2        | 1.59%   |
| Dell OptiPlex 9020                                | 2        | 1.59%   |
| Techvision TVI7309X                               | 1        | 0.79%   |
| System76 Thelio Mira                              | 1        | 0.79%   |
| Supermicro X10DAi                                 | 1        | 0.79%   |
| Shenzhen Meigao Electronic Equipment Venus Series | 1        | 0.79%   |
| Sapphire PE-AM2RS690V2                            | 1        | 0.79%   |
| Pegatron IPMIP-GS                                 | 1        | 0.79%   |
| Pegatron h8-1130a                                 | 1        | 0.79%   |
| NCR xxxx-xxxx-xxxx                                | 1        | 0.79%   |
| MSI MS-7E47                                       | 1        | 0.79%   |
| MSI MS-7D78                                       | 1        | 0.79%   |
| MSI MS-7D46                                       | 1        | 0.79%   |
| MSI MS-7D25                                       | 1        | 0.79%   |
| MSI MS-7B89                                       | 1        | 0.79%   |
| MSI MS-7B86                                       | 1        | 0.79%   |
| MSI MS-7B78                                       | 1        | 0.79%   |
| MSI MS-7B58                                       | 1        | 0.79%   |
| MSI MS-7A94                                       | 1        | 0.79%   |
| MSI MS-7A15                                       | 1        | 0.79%   |
| MSI MS-7917                                       | 1        | 0.79%   |
| MSI H510M PRO-E                                   | 1        | 0.79%   |
| Machenike DT                                      | 1        | 0.79%   |
| Lenovo ThinkStation P620 30E0S0PR00               | 1        | 0.79%   |
| Lenovo ThinkStation P340 30DK000CUS               | 1        | 0.79%   |
| Lenovo ThinkCentre M72e 36601Y8                   | 1        | 0.79%   |
| Lenovo H535 10117                                 | 1        | 0.79%   |
| Intel X99                                         | 1        | 0.79%   |
| Intel PRO412081                                   | 1        | 0.79%   |
| HPE ProLiant MicroServer Gen10 Plus               | 1        | 0.79%   |
| HP Z820 Workstation                               | 1        | 0.79%   |
| HP Z800 Workstation                               | 1        | 0.79%   |
| HP Z600 Workstation                               | 1        | 0.79%   |
| HP Z1 G8 Tower Desktop PC                         | 1        | 0.79%   |
| HP ProDesk 600 G2 SFF                             | 1        | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 12       | 9.52%   |
| Dell OptiPlex                              | 8        | 6.35%   |
| Dell Precision                             | 7        | 5.56%   |
| Unknown                                    | 4        | 3.17%   |
| Dell Vostro                                | 3        | 2.38%   |
| ASUS ROG                                   | 3        | 2.38%   |
| Lenovo ThinkStation                        | 2        | 1.59%   |
| HP Z210                                    | 2        | 1.59%   |
| Gigabyte 970A-DS3P                         | 2        | 1.59%   |
| ASUS Pro                                   | 2        | 1.59%   |
| Techvision TVI7309X                        | 1        | 0.79%   |
| System76 Thelio                            | 1        | 0.79%   |
| Supermicro X10DAi                          | 1        | 0.79%   |
| Shenzhen Meigao Electronic Equipment Venus | 1        | 0.79%   |
| Sapphire PE-AM2RS690V2                     | 1        | 0.79%   |
| Pegatron IPMIP-GS                          | 1        | 0.79%   |
| Pegatron h8-1130a                          | 1        | 0.79%   |
| NCR xxxx-xxxx-xxxx                         | 1        | 0.79%   |
| MSI MS-7E47                                | 1        | 0.79%   |
| MSI MS-7D78                                | 1        | 0.79%   |
| MSI MS-7D46                                | 1        | 0.79%   |
| MSI MS-7D25                                | 1        | 0.79%   |
| MSI MS-7B89                                | 1        | 0.79%   |
| MSI MS-7B86                                | 1        | 0.79%   |
| MSI MS-7B78                                | 1        | 0.79%   |
| MSI MS-7B58                                | 1        | 0.79%   |
| MSI MS-7A94                                | 1        | 0.79%   |
| MSI MS-7A15                                | 1        | 0.79%   |
| MSI MS-7917                                | 1        | 0.79%   |
| MSI H510M                                  | 1        | 0.79%   |
| Machenike DT                               | 1        | 0.79%   |
| Lenovo ThinkCentre                         | 1        | 0.79%   |
| Lenovo H535                                | 1        | 0.79%   |
| Intel X99                                  | 1        | 0.79%   |
| Intel PRO412081                            | 1        | 0.79%   |
| HPE ProLiant                               | 1        | 0.79%   |
| HP Z820                                    | 1        | 0.79%   |
| HP Z800                                    | 1        | 0.79%   |
| HP Z600                                    | 1        | 0.79%   |
| HP Z1                                      | 1        | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 13       | 10.32%  |
| 2022 | 12       | 9.52%   |
| 2019 | 12       | 9.52%   |
| 2013 | 12       | 9.52%   |
| 2020 | 11       | 8.73%   |
| 2011 | 11       | 8.73%   |
| 2018 | 9        | 7.14%   |
| 2014 | 7        | 5.56%   |
| 2024 | 6        | 4.76%   |
| 2012 | 6        | 4.76%   |
| 2023 | 5        | 3.97%   |
| 2015 | 5        | 3.97%   |
| 2017 | 4        | 3.17%   |
| 2016 | 4        | 3.17%   |
| 2008 | 4        | 3.17%   |
| 2010 | 3        | 2.38%   |
| 2009 | 2        | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 126      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 115      | 91.27%  |
| Enabled  | 11       | 8.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 125      | 99.21%  |
| Yes  | 1        | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 28       | 22.05%  |
| 32.01-64.0      | 23       | 18.11%  |
| 8.01-16.0       | 20       | 15.75%  |
| 4.01-8.0        | 19       | 14.96%  |
| 16.01-24.0      | 18       | 14.17%  |
| 3.01-4.0        | 6        | 4.72%   |
| 24.01-32.0      | 5        | 3.94%   |
| More than 256.0 | 3        | 2.36%   |
| 1.01-2.0        | 3        | 2.36%   |
| 2.01-3.0        | 2        | 1.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 36       | 27.07%  |
| 4.01-8.0    | 31       | 23.31%  |
| 3.01-4.0    | 24       | 18.05%  |
| 1.01-2.0    | 18       | 13.53%  |
| 0.51-1.0    | 8        | 6.02%   |
| 8.01-16.0   | 7        | 5.26%   |
| 16.01-24.0  | 3        | 2.26%   |
| 32.01-64.0  | 2        | 1.5%    |
| 0.01-0.5    | 2        | 1.5%    |
| 24.01-32.0  | 1        | 0.75%   |
| 64.01-256.0 | 1        | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 41.09%  |
| 2      | 35       | 27.13%  |
| 3      | 17       | 13.18%  |
| 4      | 13       | 10.08%  |
| 6      | 5        | 3.88%   |
| 5      | 4        | 3.1%    |
| 9      | 1        | 0.78%   |
| 8      | 1        | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 65.35%  |
| Yes       | 44       | 34.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 125      | 99.21%  |
| No        | 1        | 0.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 58.91%  |
| Yes       | 53       | 41.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 66.41%  |
| Yes       | 43       | 33.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 37       | 29.37%  |
| Canada                 | 10       | 7.94%   |
| Germany                | 9        | 7.14%   |
| Russia                 | 8        | 6.35%   |
| Italy                  | 7        | 5.56%   |
| UK                     | 5        | 3.97%   |
| South Korea            | 4        | 3.17%   |
| Singapore              | 4        | 3.17%   |
| France                 | 4        | 3.17%   |
| Israel                 | 3        | 2.38%   |
| India                  | 3        | 2.38%   |
| Brazil                 | 3        | 2.38%   |
| Australia              | 3        | 2.38%   |
| South Africa           | 2        | 1.59%   |
| Netherlands            | 2        | 1.59%   |
| Japan                  | 2        | 1.59%   |
| Indonesia              | 2        | 1.59%   |
| Sweden                 | 1        | 0.79%   |
| Romania                | 1        | 0.79%   |
| Portugal               | 1        | 0.79%   |
| Poland                 | 1        | 0.79%   |
| Norway                 | 1        | 0.79%   |
| New Zealand            | 1        | 0.79%   |
| Mexico                 | 1        | 0.79%   |
| Malaysia               | 1        | 0.79%   |
| Iran                   | 1        | 0.79%   |
| Hong Kong              | 1        | 0.79%   |
| Finland                | 1        | 0.79%   |
| Czechia                | 1        | 0.79%   |
| Colombia               | 1        | 0.79%   |
| China                  | 1        | 0.79%   |
| Bulgaria               | 1        | 0.79%   |
| Bosnia and Herzegovina | 1        | 0.79%   |
| Austria                | 1        | 0.79%   |
| Argentina              | 1        | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 4        | 3.01%   |
| Sorel-Tracy            | 3        | 2.26%   |
| Düsseldorf            | 3        | 2.26%   |
| Berlin                 | 3        | 2.26%   |
| Voronezh               | 2        | 1.5%    |
| Turin                  | 2        | 1.5%    |
| Toronto                | 2        | 1.5%    |
| St Petersburg          | 2        | 1.5%    |
| Rennes                 | 2        | 1.5%    |
| Melbourne              | 2        | 1.5%    |
| Haifa                  | 2        | 1.5%    |
| Chicago                | 2        | 1.5%    |
| Buckley                | 2        | 1.5%    |
| Barzanò               | 2        | 1.5%    |
| Yuba City              | 1        | 0.75%   |
| Yogyakarta             | 1        | 0.75%   |
| Yekaterinburg          | 1        | 0.75%   |
| Willowbrook            | 1        | 0.75%   |
| Wells                  | 1        | 0.75%   |
| Washington             | 1        | 0.75%   |
| Waltham                | 1        | 0.75%   |
| Vienna                 | 1        | 0.75%   |
| Verona                 | 1        | 0.75%   |
| Vero Beach             | 1        | 0.75%   |
| Vashon                 | 1        | 0.75%   |
| Vancouver              | 1        | 0.75%   |
| Tlaxcala City          | 1        | 0.75%   |
| Timișoara             | 1        | 0.75%   |
| Thoothukudi            | 1        | 0.75%   |
| Tehran                 | 1        | 0.75%   |
| St. John's             | 1        | 0.75%   |
| Springfield            | 1        | 0.75%   |
| Sofia                  | 1        | 0.75%   |
| Sobral de Monte Agraco | 1        | 0.75%   |
| Siroki Brijeg          | 1        | 0.75%   |
| Simi Valley            | 1        | 0.75%   |
| Semarang               | 1        | 0.75%   |
| Sao Paulo              | 1        | 0.75%   |
| Sao Jose do Rio Claro  | 1        | 0.75%   |
| Rotterdam              | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 33       | 59     | 15.94%  |
| WDC                         | 31       | 50     | 14.98%  |
| Seagate                     | 31       | 64     | 14.98%  |
| Toshiba                     | 11       | 16     | 5.31%   |
| Crucial                     | 10       | 15     | 4.83%   |
| Kingston                    | 9        | 11     | 4.35%   |
| SanDisk                     | 8        | 8      | 3.86%   |
| Hitachi                     | 8        | 13     | 3.86%   |
| SK hynix                    | 5        | 6      | 2.42%   |
| Intel                       | 5        | 8      | 2.42%   |
| HGST                        | 5        | 5      | 2.42%   |
| Unknown                     | 4        | 7      | 1.93%   |
| Micron/Crucial Technology   | 4        | 6      | 1.93%   |
| MAXIO Technology (Hangzhou) | 4        | 7      | 1.93%   |
| Phison Electronics          | 3        | 5      | 1.45%   |
| Micron Technology           | 3        | 3      | 1.45%   |
| China                       | 3        | 3      | 1.45%   |
| PNY                         | 2        | 2      | 0.97%   |
| KIOXIA                      | 2        | 2      | 0.97%   |
| Kingston Technology Company | 2        | 2      | 0.97%   |
| Gigabyte Technology         | 2        | 2      | 0.97%   |
| Transcend                   | 1        | 1      | 0.48%   |
| Teclast                     | 1        | 1      | 0.48%   |
| Team                        | 1        | 1      | 0.48%   |
| SPCC                        | 1        | 1      | 0.48%   |
| Silicon Motion              | 1        | 2      | 0.48%   |
| SABRENT                     | 1        | 1      | 0.48%   |
| Realtek Semiconductor       | 1        | 1      | 0.48%   |
| Phison                      | 1        | 1      | 0.48%   |
| MyDigitalSSD                | 1        | 1      | 0.48%   |
| Mobius                      | 1        | 2      | 0.48%   |
| LITEON                      | 1        | 1      | 0.48%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.48%   |
| GOODRAM                     | 1        | 1      | 0.48%   |
| G-DRIVE                     | 1        | 1      | 0.48%   |
| DUEX-120GB                  | 1        | 1      | 0.48%   |
| Digma                       | 1        | 1      | 0.48%   |
| Corsair                     | 1        | 1      | 0.48%   |
| BR                          | 1        | 1      | 0.48%   |
| Apacer                      | 1        | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 8        | 3.32%   |
| Seagate ST500DM002-1BD142 500GB                      | 4        | 1.66%   |
| Phison E12 NVMe Controller 480GB                     | 3        | 1.24%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 3        | 1.24%   |
| WDC WD20EZBX-00AYRA0 2TB                             | 2        | 0.83%   |
| WDC WD2002FAEX-007BA0 2TB                            | 2        | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 2        | 0.83%   |
| WDC WD10EZEX-00BBHA0 1TB                             | 2        | 0.83%   |
| WDC WD1001FALS-00J7B0 1TB                            | 2        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB                       | 2        | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB                       | 2        | 0.83%   |
| Samsung SSD 980 500GB                                | 2        | 0.83%   |
| Samsung SSD 980 1TB                                  | 2        | 0.83%   |
| Samsung SSD 860 EVO 1TB                              | 2        | 0.83%   |
| Samsung SSD 850 EVO 500GB                            | 2        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 2        | 0.83%   |
| PNY CS900 120GB SSD                                  | 2        | 0.83%   |
| Micron CT1000P3SSD8 1TB                              | 2        | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 2        | 0.83%   |
| Kingston Company SNV2S250G 250GB                     | 2        | 0.83%   |
| Kingston SA400S37960G 960GB SSD                      | 2        | 0.83%   |
| Gigabyte GP-GSTFS31240GNTD 240GB                     | 2        | 0.83%   |
| Crucial CT240BX500SSD1 240GB                         | 2        | 0.83%   |
| WDC WDS500G1R0A-68A4W0 500GB                         | 1        | 0.41%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                     | 1        | 0.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1        | 0.41%   |
| WDC WDS100T1X0E-00AFY0 1TB                           | 1        | 0.41%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                       | 1        | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB                         | 1        | 0.41%   |
| WDC WD5000AUDX-63WNHY0 500GB                         | 1        | 0.41%   |
| WDC WD5000AAKX-75U6AA0 500GB                         | 1        | 0.41%   |
| WDC WD5000AAKX-001CA0 500GB                          | 1        | 0.41%   |
| WDC WD40PURZ-85AKKY0 4TB                             | 1        | 0.41%   |
| WDC WD40EZRZ-00WN9B0 4TB                             | 1        | 0.41%   |
| WDC WD40EZAX-00C8UB0 4TB                             | 1        | 0.41%   |
| WDC WD4003FRYZ-01F0DB0 4TB                           | 1        | 0.41%   |
| WDC WD30EZRX-00D8PB0 3TB                             | 1        | 0.41%   |
| WDC WD2500AAJS-22VTA0 250GB                          | 1        | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 64     | 36.05%  |
| WDC                 | 26       | 40     | 30.23%  |
| Toshiba             | 10       | 15     | 11.63%  |
| Hitachi             | 8        | 13     | 9.3%    |
| HGST                | 4        | 4      | 4.65%   |
| Samsung Electronics | 3        | 5      | 3.49%   |
| Unknown             | 2        | 2      | 2.33%   |
| SABRENT             | 1        | 1      | 1.16%   |
| Mobius              | 1        | 2      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 22     | 20.97%  |
| Crucial             | 9        | 14     | 14.52%  |
| Kingston            | 7        | 7      | 11.29%  |
| WDC                 | 6        | 9      | 9.68%   |
| SanDisk             | 4        | 4      | 6.45%   |
| China               | 3        | 3      | 4.84%   |
| PNY                 | 2        | 2      | 3.23%   |
| Gigabyte Technology | 2        | 2      | 3.23%   |
| Toshiba             | 1        | 1      | 1.61%   |
| Teclast             | 1        | 1      | 1.61%   |
| Team                | 1        | 1      | 1.61%   |
| SPCC                | 1        | 1      | 1.61%   |
| SK hynix            | 1        | 1      | 1.61%   |
| MyDigitalSSD        | 1        | 1      | 1.61%   |
| LITEON              | 1        | 1      | 1.61%   |
| Intel               | 1        | 1      | 1.61%   |
| GOODRAM             | 1        | 1      | 1.61%   |
| G-DRIVE             | 1        | 1      | 1.61%   |
| DUEX-120GB          | 1        | 1      | 1.61%   |
| Digma               | 1        | 1      | 1.61%   |
| Corsair             | 1        | 1      | 1.61%   |
| BR                  | 1        | 1      | 1.61%   |
| Apacer              | 1        | 1      | 1.61%   |
| ADATA SU            | 1        | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 65       | 146    | 35.71%  |
| NVMe    | 58       | 91     | 31.87%  |
| SSD     | 56       | 79     | 30.77%  |
| Unknown | 2        | 5      | 1.1%    |
| MMC     | 1        | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 100      | 213    | 59.88%  |
| NVMe | 58       | 91     | 34.73%  |
| SAS  | 8        | 17     | 4.79%   |
| MMC  | 1        | 1      | 0.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 61       | 95     | 45.19%  |
| 0.51-1.0   | 38       | 64     | 28.15%  |
| 1.01-2.0   | 18       | 31     | 13.33%  |
| 3.01-4.0   | 10       | 25     | 7.41%   |
| 4.01-10.0  | 3        | 3      | 2.22%   |
| 2.01-3.0   | 2        | 2      | 1.48%   |
| 10.01-20.0 | 2        | 3      | 1.48%   |
| 20.01-50.0 | 1        | 2      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 22.48%  |
| 501-1000       | 29       | 22.48%  |
| 251-500        | 20       | 15.5%   |
| 1001-2000      | 20       | 15.5%   |
| More than 3000 | 16       | 12.4%   |
| 2001-3000      | 5        | 3.88%   |
| Unknown        | 4        | 3.1%    |
| 51-100         | 3        | 2.33%   |
| 1-20           | 2        | 1.55%   |
| 21-50          | 1        | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 40       | 29.41%  |
| 21-50          | 23       | 16.91%  |
| 51-100         | 22       | 16.18%  |
| 101-250        | 13       | 9.56%   |
| 251-500        | 12       | 8.82%   |
| 501-1000       | 10       | 7.35%   |
| More than 3000 | 8        | 5.88%   |
| Unknown        | 4        | 2.94%   |
| 1001-2000      | 3        | 2.21%   |
| 2001-3000      | 1        | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD40EZRZ-00WN9B0 4TB        | 1        | 1      | 6.67%   |
| WDC WD1001FALS-00J7B1 1TB       | 1        | 2      | 6.67%   |
| WDC WD1001FALS-00J7B0 1TB       | 1        | 4      | 6.67%   |
| Toshiba MK1059GSM 1TB           | 1        | 1      | 6.67%   |
| Seagate ST9500325AS 500GB       | 1        | 1      | 6.67%   |
| Seagate ST9320325AS 320GB       | 1        | 1      | 6.67%   |
| Seagate ST500LM021-1KJ152 500GB | 1        | 1      | 6.67%   |
| Seagate ST31000528AS 1TB        | 1        | 2      | 6.67%   |
| Kingston SE50S3100G 100GB SSD   | 1        | 1      | 6.67%   |
| Intel SSD 600P Series 256GB     | 1        | 2      | 6.67%   |
| Hitachi HTS727575A9E364 752GB   | 1        | 1      | 6.67%   |
| Hitachi HDS725050KLA360 500GB   | 1        | 1      | 6.67%   |
| Hitachi HDS721010CLA632 1TB     | 1        | 1      | 6.67%   |
| Crucial CT1050MX300SSD1 1050GB  | 1        | 1      | 6.67%   |
| Corsair Neutron SSD 64GB        | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 4        | 5      | 26.67%  |
| WDC      | 3        | 7      | 20%     |
| Hitachi  | 3        | 3      | 20%     |
| Toshiba  | 1        | 1      | 6.67%   |
| Kingston | 1        | 1      | 6.67%   |
| Intel    | 1        | 2      | 6.67%   |
| Crucial  | 1        | 1      | 6.67%   |
| Corsair  | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 36.36%  |
| WDC     | 3        | 7      | 27.27%  |
| Hitachi | 3        | 3      | 27.27%  |
| Toshiba | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 16     | 69.23%  |
| SSD  | 3        | 3      | 23.08%  |
| NVMe | 1        | 2      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST9500420AS 500GB | 1        | 1      | 100%    |

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
| Works    | 83       | 181    | 58.04%  |
| Detected | 47       | 119    | 32.87%  |
| Malfunc  | 12       | 21     | 8.39%   |
| Failed   | 1        | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 85       | 41.87%  |
| AMD                         | 41       | 20.2%   |
| Samsung Electronics         | 21       | 10.34%  |
| ASMedia Technology          | 7        | 3.45%   |
| SanDisk                     | 5        | 2.46%   |
| Micron/Crucial Technology   | 5        | 2.46%   |
| Broadcom / LSI              | 5        | 2.46%   |
| SK hynix                    | 4        | 1.97%   |
| Phison Electronics          | 4        | 1.97%   |
| MAXIO Technology (Hangzhou) | 4        | 1.97%   |
| Kingston Technology Company | 4        | 1.97%   |
| Micron Technology           | 3        | 1.48%   |
| LSI Logic / Symbios Logic   | 3        | 1.48%   |
| KIOXIA                      | 3        | 1.48%   |
| Realtek Semiconductor       | 2        | 0.99%   |
| VIA Technologies            | 1        | 0.49%   |
| Transcend                   | 1        | 0.49%   |
| Silicon Motion              | 1        | 0.49%   |
| Silicon Image               | 1        | 0.49%   |
| Marvell Technology Group    | 1        | 0.49%   |
| JMicron Technology          | 1        | 0.49%   |
| Adaptec                     | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21       | 8.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 4.03%   |
| Intel SATA Controller [RAID Mode]                                                       | 9        | 3.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 3.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 3.23%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 2.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 2.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 2.02%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.02%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 4        | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.61%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 1.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.61%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 4        | 1.61%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 3        | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.21%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.21%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                        | 2        | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 2        | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 0.81%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 2        | 0.81%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.81%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.81%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.81%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 102      | 49.28%  |
| NVMe | 58       | 28.02%  |
| IDE  | 21       | 10.14%  |
| RAID | 18       | 8.7%    |
| SAS  | 6        | 2.9%    |
| SCSI | 2        | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 84       | 66.67%  |
| AMD    | 42       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 5        | 3.97%   |
| Intel 12th Gen Core i5-12400F               | 4        | 3.17%   |
| Intel Core i9-14900                         | 2        | 1.59%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.59%   |
| Intel 13th Gen Core i9-13900K               | 2        | 1.59%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 1.59%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.59%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.59%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.59%   |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1        | 0.79%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.79%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.79%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.79%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 0.79%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.79%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 0.79%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1        | 0.79%   |
| Intel Pentium Gold G7400                    | 1        | 0.79%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.79%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.79%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.79%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1        | 0.79%   |
| Intel Core i9-10900KF CPU @ 3.70GHz         | 1        | 0.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.79%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.79%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.79%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1        | 0.79%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 0.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.79%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.79%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 21       | 16.67%  |
| Intel Core i5           | 17       | 13.49%  |
| Other                   | 14       | 11.11%  |
| Intel Xeon              | 13       | 10.32%  |
| AMD Ryzen 7             | 10       | 7.94%   |
| AMD Ryzen 9             | 7        | 5.56%   |
| AMD Ryzen Threadripper  | 6        | 4.76%   |
| AMD Ryzen 5             | 6        | 4.76%   |
| Intel Core i3           | 5        | 3.97%   |
| Intel Celeron           | 5        | 3.97%   |
| Intel Core i9           | 4        | 3.17%   |
| AMD FX                  | 4        | 3.17%   |
| Intel Pentium Gold      | 2        | 1.59%   |
| Intel Core 2 Quad       | 2        | 1.59%   |
| Intel Pentium Dual-Core | 1        | 0.79%   |
| Intel Pentium Dual      | 1        | 0.79%   |
| AMD Sempron             | 1        | 0.79%   |
| AMD Ryzen Embedded      | 1        | 0.79%   |
| AMD Ryzen 7 PRO         | 1        | 0.79%   |
| AMD Ryzen 3             | 1        | 0.79%   |
| AMD Phenom II X6        | 1        | 0.79%   |
| AMD Athlon II X2        | 1        | 0.79%   |
| AMD A8                  | 1        | 0.79%   |
| AMD A4                  | 1        | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 33.33%  |
| 6      | 23       | 18.25%  |
| 8      | 17       | 13.49%  |
| 2      | 17       | 13.49%  |
| 12     | 10       | 7.94%   |
| 24     | 7        | 5.56%   |
| 16     | 5        | 3.97%   |
| 10     | 2        | 1.59%   |
| 64     | 1        | 0.79%   |
| 14     | 1        | 0.79%   |
| 3      | 1        | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 120      | 95.24%  |
| 2      | 6        | 4.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 93       | 73.81%  |
| 1      | 33       | 26.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 126      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 29.69%  |
| 0x206a7    | 8        | 6.25%   |
| 0x306c3    | 5        | 3.91%   |
| 0x506e3    | 3        | 2.34%   |
| 0x306a9    | 3        | 2.34%   |
| 0x0a601203 | 3        | 2.34%   |
| 0x0800820d | 3        | 2.34%   |
| 0x06000852 | 3        | 2.34%   |
| 0xb0671    | 2        | 1.56%   |
| 0xa0671    | 2        | 1.56%   |
| 0xa0655    | 2        | 1.56%   |
| 0xa0653    | 2        | 1.56%   |
| 0x906ea    | 2        | 1.56%   |
| 0x906c0    | 2        | 1.56%   |
| 0x90672    | 2        | 1.56%   |
| 0x306f2    | 2        | 1.56%   |
| 0x306e4    | 2        | 1.56%   |
| 0x206c2    | 2        | 1.56%   |
| 0x0a404102 | 2        | 1.56%   |
| 0x08600106 | 2        | 1.56%   |
| 0x08108109 | 2        | 1.56%   |
| 0x906ed    | 1        | 0.78%   |
| 0x90675    | 1        | 0.78%   |
| 0x706a8    | 1        | 0.78%   |
| 0x6fd      | 1        | 0.78%   |
| 0x50654    | 1        | 0.78%   |
| 0x406f1    | 1        | 0.78%   |
| 0x40651    | 1        | 0.78%   |
| 0x206d7    | 1        | 0.78%   |
| 0x106e5    | 1        | 0.78%   |
| 0x10677    | 1        | 0.78%   |
| 0x10676    | 1        | 0.78%   |
| 0x0a601206 | 1        | 0.78%   |
| 0x0a601201 | 1        | 0.78%   |
| 0x0a50000c | 1        | 0.78%   |
| 0x0a50000b | 1        | 0.78%   |
| 0x0a20120a | 1        | 0.78%   |
| 0x0a201205 | 1        | 0.78%   |
| 0x0a20102b | 1        | 0.78%   |
| 0x0a201016 | 1        | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 12       | 9.52%   |
| Haswell          | 12       | 9.52%   |
| Alderlake Hybrid | 12       | 9.52%   |
| Unknown          | 11       | 8.73%   |
| KabyLake         | 10       | 7.94%   |
| Zen 3            | 7        | 5.56%   |
| Skylake          | 7        | 5.56%   |
| IvyBridge        | 7        | 5.56%   |
| Zen 2            | 6        | 4.76%   |
| CometLake        | 6        | 4.76%   |
| Zen+             | 5        | 3.97%   |
| Piledriver       | 5        | 3.97%   |
| Zen              | 4        | 3.17%   |
| Westmere         | 3        | 2.38%   |
| Penryn           | 3        | 2.38%   |
| K10              | 3        | 2.38%   |
| Icelake          | 3        | 2.38%   |
| Tremont          | 2        | 1.59%   |
| Core             | 2        | 1.59%   |
| Silvermont       | 1        | 0.79%   |
| Nehalem          | 1        | 0.79%   |
| K10 Llano        | 1        | 0.79%   |
| Jaguar           | 1        | 0.79%   |
| Goldmont plus    | 1        | 0.79%   |
| Broadwell        | 1        | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 57       | 40.71%  |
| Intel             | 46       | 32.86%  |
| AMD               | 35       | 25%     |
| ASPEED Technology | 2        | 1.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.5%    |
| Intel HD Graphics 530                                                       | 5        | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 2.8%    |
| Nvidia AD102 [GeForce RTX 4090]                                             | 4        | 2.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.8%    |
| AMD Raphael                                                                 | 4        | 2.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.4%    |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.4%    |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.4%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.4%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.4%    |
| Nvidia AD103 [GeForce RTX 4080]                                             | 2        | 1.4%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 1.4%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.4%    |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.4%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.4%    |
| Intel HD Graphics 630                                                       | 2        | 1.4%    |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 1.4%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 1.4%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 2        | 1.4%    |
| AMD Rembrandt [Radeon 680M]                                                 | 2        | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 1.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.4%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.4%    |
| Nvidia TU117GL [T600]                                                       | 1        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.7%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.7%    |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.7%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.7%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 48       | 38.1%   |
| 1 x Intel       | 39       | 30.95%  |
| 1 x AMD         | 27       | 21.43%  |
| AMD + Nvidia    | 4        | 3.17%   |
| 2 x AMD         | 3        | 2.38%   |
| Intel + Nvidia  | 3        | 2.38%   |
| Nvidia + ASPEED | 1        | 0.79%   |
| AMD + ASPEED    | 1        | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 92       | 72.44%  |
| Proprietary | 29       | 22.83%  |
| Unknown     | 6        | 4.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 54       | 42.52%  |
| 1.01-2.0   | 17       | 13.39%  |
| 0.01-0.5   | 14       | 11.02%  |
| 0.51-1.0   | 12       | 9.45%   |
| 7.01-8.0   | 6        | 4.72%   |
| 16.01-24.0 | 6        | 4.72%   |
| 8.01-16.0  | 6        | 4.72%   |
| 3.01-4.0   | 4        | 3.15%   |
| 2.01-3.0   | 4        | 3.15%   |
| 5.01-6.0   | 3        | 2.36%   |
| 32.01-64.0 | 1        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 19       | 15.83%  |
| Goldstar             | 16       | 13.33%  |
| Samsung Electronics  | 13       | 10.83%  |
| Acer                 | 11       | 9.17%   |
| Philips              | 6        | 5%      |
| Hewlett-Packard      | 6        | 5%      |
| BenQ                 | 6        | 5%      |
| Ancor Communications | 6        | 5%      |
| Eizo                 | 5        | 4.17%   |
| AOC                  | 4        | 3.33%   |
| Iiyama               | 3        | 2.5%    |
| ViewSonic            | 2        | 1.67%   |
| LG Electronics       | 2        | 1.67%   |
| Unknown              | 2        | 1.67%   |
| ZTL                  | 1        | 0.83%   |
| Xiaomi               | 1        | 0.83%   |
| Sony                 | 1        | 0.83%   |
| SKG                  | 1        | 0.83%   |
| SGT                  | 1        | 0.83%   |
| Sceptre Tech         | 1        | 0.83%   |
| SANYO                | 1        | 0.83%   |
| Plain Tree Systems   | 1        | 0.83%   |
| Panasonic            | 1        | 0.83%   |
| OEM                  | 1        | 0.83%   |
| NEC Computers        | 1        | 0.83%   |
| LLM                  | 1        | 0.83%   |
| Lenovo               | 1        | 0.83%   |
| HUAWEI               | 1        | 0.83%   |
| HCL                  | 1        | 0.83%   |
| EDI                  | 1        | 0.83%   |
| Denver               | 1        | 0.83%   |
| ASUSTek Computer     | 1        | 0.83%   |
| Apple                | 1        | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 3.2%    |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch               | 3        | 2.4%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 2        | 1.6%    |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                      | 2        | 1.6%    |
| Acer V193W ACR0053 1440x900 408x255mm 18.9-inch                        | 2        | 1.6%    |
| Unknown                                                                | 2        | 1.6%    |
| ZTL ZM29W1 ZTL1506 2560x1080 1600x1000mm 74.3-inch                     | 1        | 0.8%    |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                     | 1        | 0.8%    |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch             | 1        | 0.8%    |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                 | 1        | 0.8%    |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                     | 1        | 0.8%    |
| SKG H24T27 SKG2410 2560x1440 530x300mm 24.0-inch                       | 1        | 0.8%    |
| SGT F156P1 SGT1560 1920x1080 345x194mm 15.6-inch                       | 1        | 0.8%    |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch         | 1        | 0.8%    |
| SANYO LED MONITOR SAN952D 1920x1080 443x249mm 20.0-inch                | 1        | 0.8%    |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch      | 1        | 0.8%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM062E 1280x1024 376x301mm 19.0-inch   | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch   | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch   | 1        | 0.8%    |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch   | 1        | 0.8%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.8%    |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch    | 1        | 0.8%    |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1110x620mm 50.1-inch | 1        | 0.8%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch  | 1        | 0.8%    |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 700x400mm 31.7-inch     | 1        | 0.8%    |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 1        | 0.8%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 0.8%    |
| Plain Tree Systems PS-576 PTS1599 1280x800 332x207mm 15.4-inch         | 1        | 0.8%    |
| Philips PHL 279P1 PHL0948 3840x2160 597x336mm 27.0-inch                | 1        | 0.8%    |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch               | 1        | 0.8%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.8%    |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch               | 1        | 0.8%    |
| Panasonic TV MEIA0A7 1920x1080 698x392mm 31.5-inch                     | 1        | 0.8%    |
| OEM 215_LCD_TV OEM3700 1920x1080                                       | 1        | 0.8%    |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch          | 1        | 0.8%    |
| LLM HDMI EDID LLM0401 3840x2160 477x268mm 21.5-inch                    | 1        | 0.8%    |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                       | 1        | 0.8%    |
| LG Electronics LCD Monitor LG HDR 4K 7680x2160                         | 1        | 0.8%    |
| LG Electronics LCD Monitor LG HDR 4K                                   | 1        | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 41       | 34.17%  |
| 3840x2160 (4K)     | 19       | 15.83%  |
| 1280x1024 (SXGA)   | 10       | 8.33%   |
| 2560x1440 (QHD)    | 9        | 7.5%    |
| 1920x1200 (WUXGA)  | 6        | 5%      |
| 3440x1440          | 5        | 4.17%   |
| 1600x900 (HD+)     | 4        | 3.33%   |
| 1440x900 (WXGA+)   | 4        | 3.33%   |
| 3840x1080          | 3        | 2.5%    |
| 2560x1080          | 3        | 2.5%    |
| 1920x540           | 3        | 2.5%    |
| 1366x768 (WXGA)    | 3        | 2.5%    |
| Unknown            | 3        | 2.5%    |
| 1680x1050 (WSXGA+) | 2        | 1.67%   |
| 1024x768 (XGA)     | 2        | 1.67%   |
| 7680x2160          | 1        | 0.83%   |
| 1280x800 (WXGA)    | 1        | 0.83%   |
| 1280x768           | 1        | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 18       | 14.88%  |
| 27      | 17       | 14.05%  |
| 23      | 12       | 9.92%   |
| 31      | 11       | 9.09%   |
| 19      | 9        | 7.44%   |
| Unknown | 9        | 7.44%   |
| 34      | 6        | 4.96%   |
| 21      | 6        | 4.96%   |
| 17      | 6        | 4.96%   |
| 20      | 5        | 4.13%   |
| 40      | 3        | 2.48%   |
| 18      | 3        | 2.48%   |
| 65      | 2        | 1.65%   |
| 22      | 2        | 1.65%   |
| 15      | 2        | 1.65%   |
| 84      | 1        | 0.83%   |
| 74      | 1        | 0.83%   |
| 54      | 1        | 0.83%   |
| 49      | 1        | 0.83%   |
| 48      | 1        | 0.83%   |
| 36      | 1        | 0.83%   |
| 32      | 1        | 0.83%   |
| 28      | 1        | 0.83%   |
| 25      | 1        | 0.83%   |
| 14      | 1        | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 46       | 38.33%  |
| 401-500     | 22       | 18.33%  |
| 601-700     | 12       | 10%     |
| Unknown     | 9        | 7.5%    |
| 701-800     | 8        | 6.67%   |
| 301-350     | 8        | 6.67%   |
| 1001-1500   | 5        | 4.17%   |
| 351-400     | 4        | 3.33%   |
| 801-900     | 3        | 2.5%    |
| 1501-2000   | 2        | 1.67%   |
| 201-300     | 1        | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 62.83%  |
| 16/10   | 13       | 11.5%   |
| 5/4     | 9        | 7.96%   |
| Unknown | 8        | 7.08%   |
| 21/9    | 5        | 4.42%   |
| 32/9    | 3        | 2.65%   |
| 4/3     | 2        | 1.77%   |
| 6/5     | 1        | 0.88%   |
| 3/2     | 1        | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 23.73%  |
| 351-500        | 18       | 15.25%  |
| 301-350        | 17       | 14.41%  |
| 151-200        | 16       | 13.56%  |
| 141-150        | 9        | 7.63%   |
| Unknown        | 9        | 7.63%   |
| 501-1000       | 7        | 5.93%   |
| 251-300        | 6        | 5.08%   |
| More than 1000 | 5        | 4.24%   |
| 101-110        | 2        | 1.69%   |
| 111-120        | 1        | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 80       | 69.57%  |
| 101-120 | 12       | 10.43%  |
| Unknown | 9        | 7.83%   |
| 121-160 | 6        | 5.22%   |
| 1-50    | 4        | 3.48%   |
| 161-240 | 4        | 3.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 91       | 72.22%  |
| 0     | 18       | 14.29%  |
| 2     | 17       | 13.49%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 73       | 38.02%  |
| Intel                     | 73       | 38.02%  |
| MediaTek                  | 8        | 4.17%   |
| Broadcom                  | 6        | 3.13%   |
| Aquantia                  | 5        | 2.6%    |
| Ralink Technology         | 4        | 2.08%   |
| TP-Link                   | 3        | 1.56%   |
| Qualcomm Atheros          | 3        | 1.56%   |
| Linksys                   | 3        | 1.56%   |
| Ralink                    | 2        | 1.04%   |
| Marvell Technology Group  | 2        | 1.04%   |
| Tehuti Networks           | 1        | 0.52%   |
| Spreadtrum Communications | 1        | 0.52%   |
| Solarflare Communications | 1        | 0.52%   |
| Qualcomm Technologies     | 1        | 0.52%   |
| Microsoft                 | 1        | 0.52%   |
| Mellanox Technologies     | 1        | 0.52%   |
| InterBiometrics           | 1        | 0.52%   |
| Davicom Semiconductor     | 1        | 0.52%   |
| BUFFALO                   | 1        | 0.52%   |
| American Megatrends       | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 51       | 22.67%  |
| Realtek RTL8125 2.5GbE Controller                                              | 12       | 5.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9        | 4%      |
| Intel I211 Gigabit Network Connection                                          | 8        | 3.56%   |
| Intel Ethernet Controller I225-V                                               | 6        | 2.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 5        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                            | 5        | 2.22%   |
| Intel Ethernet Connection (17) I219-V                                          | 5        | 2.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4        | 1.78%   |
| Intel Wireless 3165                                                            | 4        | 1.78%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 1.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3        | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 1.33%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.33%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 1.33%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2        | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.89%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2        | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 2        | 0.89%   |
| Intel Wireless 7265                                                            | 2        | 0.89%   |
| Intel Ethernet Controller X550                                                 | 2        | 0.89%   |
| Intel Ethernet Controller I226-V                                               | 2        | 0.89%   |
| Intel Ethernet Controller I226-LM                                              | 2        | 0.89%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 0.89%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2        | 0.89%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 0.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 0.89%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                            | 1        | 0.44%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                     | 1        | 0.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.44%   |
| Tehuti Networks TN9510 10GBase-T/NBASE-T Ethernet Adapter                      | 1        | 0.44%   |
| Spreadtrum Unisoc Phone                                                        | 1        | 0.44%   |
| Solarflare SFC9020 10G Ethernet Controller                                     | 1        | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1        | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 23       | 38.33%  |
| Realtek Semiconductor | 10       | 16.67%  |
| MediaTek              | 8        | 13.33%  |
| Ralink Technology     | 4        | 6.67%   |
| TP-Link               | 3        | 5%      |
| Qualcomm Atheros      | 3        | 5%      |
| Linksys               | 3        | 5%      |
| Ralink                | 2        | 3.33%   |
| Qualcomm Technologies | 1        | 1.67%   |
| Microsoft             | 1        | 1.67%   |
| BUFFALO               | 1        | 1.67%   |
| Broadcom              | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5        | 8.06%   |
| Intel Wi-Fi 6 AX200                                                    | 5        | 8.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 6.45%   |
| Intel Wireless 3165                                                    | 4        | 6.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 4.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 3.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 3.23%   |
| Intel Wireless 7265                                                    | 2        | 3.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 1.61%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1        | 1.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 1.61%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                 | 1        | 1.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 1.61%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 1.61%   |
| Ralink RT3071 Wireless Adapter                                         | 1        | 1.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 1.61%   |
| Ralink RT5392 PCIe Wireless Network Adapter                            | 1        | 1.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.61%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1        | 1.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 1.61%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 1        | 1.61%   |
| MediaTek WiFi                                                          | 1        | 1.61%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                     | 1        | 1.61%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.61%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.61%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]         | 1        | 1.61%   |
| Intel Wireless 7260                                                    | 1        | 1.61%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.61%   |
| Intel Centrino Wireless-N 2230                                         | 1        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1        | 1.61%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                   | 1        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1        | 1.61%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]               | 1        | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 70       | 46.98%  |
| Intel                     | 60       | 40.27%  |
| Broadcom                  | 6        | 4.03%   |
| Aquantia                  | 5        | 3.36%   |
| Marvell Technology Group  | 2        | 1.34%   |
| Tehuti Networks           | 1        | 0.67%   |
| Spreadtrum Communications | 1        | 0.67%   |
| Solarflare Communications | 1        | 0.67%   |
| Mellanox Technologies     | 1        | 0.67%   |
| Davicom Semiconductor     | 1        | 0.67%   |
| American Megatrends       | 1        | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 51       | 31.48%  |
| Realtek RTL8125 2.5GbE Controller                                              | 12       | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9        | 5.56%   |
| Intel I211 Gigabit Network Connection                                          | 8        | 4.94%   |
| Intel Ethernet Controller I225-V                                               | 6        | 3.7%    |
| Intel Ethernet Connection (17) I219-V                                          | 5        | 3.09%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 1.85%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.85%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 1.85%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 1.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 1.23%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2        | 1.23%   |
| Intel Ethernet Controller X550                                                 | 2        | 1.23%   |
| Intel Ethernet Controller I226-V                                               | 2        | 1.23%   |
| Intel Ethernet Controller I226-LM                                              | 2        | 1.23%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 1.23%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2        | 1.23%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 1.23%   |
| Tehuti Networks TN9510 10GBase-T/NBASE-T Ethernet Adapter                      | 1        | 0.62%   |
| Spreadtrum Unisoc Phone                                                        | 1        | 0.62%   |
| Solarflare SFC9020 10G Ethernet Controller                                     | 1        | 0.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.62%   |
| Realtek RT8126 PCIe Ethernet Controller                                        | 1        | 0.62%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.62%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1        | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.62%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1        | 0.62%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.62%   |
| Intel WiMAX Connection 2400m                                                   | 1        | 0.62%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.62%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.62%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 0.62%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.62%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 125      | 69.83%  |
| WiFi     | 53       | 29.61%  |
| Modem    | 1        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 108      | 83.08%  |
| WiFi     | 22       | 16.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 62       | 48.06%  |
| 2     | 47       | 36.43%  |
| 3     | 13       | 10.08%  |
| 4     | 4        | 3.1%    |
| 5     | 3        | 2.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 79.53%  |
| Yes  | 26       | 20.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 20       | 45.45%  |
| MediaTek                   | 6        | 13.64%  |
| Cambridge Silicon Radio    | 6        | 13.64%  |
| Realtek Semiconductor      | 3        | 6.82%   |
| Foxconn / Hon Hai          | 3        | 6.82%   |
| Broadcom                   | 2        | 4.55%   |
| Ralink                     | 1        | 2.27%   |
| Integrated System Solution | 1        | 2.27%   |
| IMC Networks               | 1        | 2.27%   |
| ASUSTek Computer           | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                              | 6        | 13.64%  |
| Intel Bluetooth wireless interface                    | 6        | 13.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 13.64%  |
| Intel AX210 Bluetooth                                 | 5        | 11.36%  |
| Intel AX200 Bluetooth                                 | 5        | 11.36%  |
| Realtek Bluetooth Radio                               | 2        | 4.55%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 2.27%   |
| Ralink RT3290 Bluetooth                               | 1        | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.27%   |
| Intel AX211 Bluetooth                                 | 1        | 2.27%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.27%   |
| IMC Networks Bluetooth Device                         | 1        | 2.27%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 2.27%   |
| ASUS Bluetooth Radio                                  | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 81       | 37.85%  |
| Nvidia                  | 55       | 25.7%   |
| AMD                     | 50       | 23.36%  |
| Logitech                | 5        | 2.34%   |
| C-Media Electronics     | 5        | 2.34%   |
| ASUSTek Computer        | 3        | 1.4%    |
| Realtek Semiconductor   | 2        | 0.93%   |
| Texas Instruments       | 1        | 0.47%   |
| Tenx Technology         | 1        | 0.47%   |
| TEAC                    | 1        | 0.47%   |
| Setek Elektronik        | 1        | 0.47%   |
| Nektar                  | 1        | 0.47%   |
| KTMicro                 | 1        | 0.47%   |
| GYROCOM C&C             | 1        | 0.47%   |
| GS3                     | 1        | 0.47%   |
| Giga-Byte Technology    | 1        | 0.47%   |
| Creative Technology     | 1        | 0.47%   |
| Creative Labs           | 1        | 0.47%   |
| BEHRINGER International | 1        | 0.47%   |
| ASRock                  | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 14       | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 4.56%   |
| Intel Alder Lake-S HD Audio Controller                                            | 9        | 3.73%   |
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 3.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 7        | 2.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 2.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 2.49%   |
| Intel 200 Series PCH HD Audio                                                     | 6        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 2.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 2.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 2.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5        | 2.07%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.66%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.66%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 1.66%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.66%   |
| Nvidia AD102 High Definition Audio Controller                                     | 4        | 1.66%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4        | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 1.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 1.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 1.24%   |
| Intel Raptor Lake High Definition Audio Controller                                | 3        | 1.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 1.24%   |
| ASUSTek Computer USB Audio                                                        | 3        | 1.24%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 1.24%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.24%   |
| Nvidia High Definition Audio Controller                                           | 2        | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2        | 0.83%   |
| Nvidia Audio device                                                               | 2        | 0.83%   |
| Intel Jasper Lake HD Audio                                                        | 2        | 0.83%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 16       | 16%     |
| Kingston            | 13       | 13%     |
| Corsair             | 13       | 13%     |
| Micron Technology   | 10       | 10%     |
| Unknown             | 8        | 8%      |
| SK hynix            | 8        | 8%      |
| G.Skill             | 8        | 8%      |
| Crucial             | 7        | 7%      |
| Unknown             | 4        | 4%      |
| Nanya Technology    | 2        | 2%      |
| Team                | 1        | 1%      |
| Silicon Power       | 1        | 1%      |
| PNY                 | 1        | 1%      |
| Patriot             | 1        | 1%      |
| Lexar               | 1        | 1%      |
| HPE                 | 1        | 1%      |
| Gold Key            | 1        | 1%      |
| Elpida              | 1        | 1%      |
| CUSO                | 1        | 1%      |
| Apacer              | 1        | 1%      |
| A-DATA Technology   | 1        | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown                                                  | 4        | 3.81%   |
| SK hynix RAM HMCG88AGBUA084N 32GB DIMM DDR5 5600MT/s     | 2        | 1.9%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 2        | 1.9%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s    | 2        | 1.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 1.9%    |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.95%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s           | 1        | 0.95%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 0.95%   |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 0.95%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s               | 1        | 0.95%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s     | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s       | 1        | 0.95%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 0.95%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s              | 1        | 0.95%   |
| SK hynix RAM HMT84GL7MMR4A-H9 32GB DIMM DDR3 1333MT/s    | 1        | 0.95%   |
| SK hynix RAM HMT84GL7BMR4A-H9 32GB DIMM DDR3 1333MT/s    | 1        | 0.95%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s     | 1        | 0.95%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 0.95%   |
| Silicon Power RAM DCLT4GN568S 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| Silicon Power RAM DBLT4GN568S 4GB DIMM DDR3 1333MT/s     | 1        | 0.95%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s   | 1        | 0.95%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s   | 1        | 0.95%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s | 1        | 0.95%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 0.95%   |
| Samsung RAM M386A4G40EM2-CRC 32GB DIMM DDR4 2400MT/s     | 1        | 0.95%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s     | 1        | 0.95%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s   | 1        | 0.95%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s    | 1        | 0.95%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 0.95%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3933MT/s     | 1        | 0.95%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 3000MT/s     | 1        | 0.95%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 2733MT/s      | 1        | 0.95%   |
| Samsung RAM M323R4GA3BB0-CQKOD 32GB DIMM DDR5 4800MT/s   | 1        | 0.95%   |
| Samsung RAM M321R8GA0BB0-CQKZJ 64GB DIMM DDR5 4800MT/s   | 1        | 0.95%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s     | 1        | 0.95%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s         | 1        | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 44       | 51.76%  |
| DDR3    | 25       | 29.41%  |
| DDR5    | 11       | 12.94%  |
| DDR2    | 3        | 3.53%   |
| DRAM    | 1        | 1.18%   |
| Unknown | 1        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 72       | 84.71%  |
| SODIMM | 12       | 14.12%  |
| RIMM   | 1        | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 25.27%  |
| 16384 | 21       | 23.08%  |
| 32768 | 20       | 21.98%  |
| 4096  | 17       | 18.68%  |
| 2048  | 5        | 5.49%   |
| 1024  | 3        | 3.3%    |
| 65536 | 1        | 1.1%    |
| 49152 | 1        | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 13       | 13.54%  |
| 2667  | 12       | 12.5%   |
| 1600  | 10       | 10.42%  |
| 1333  | 9        | 9.38%   |
| 2133  | 8        | 8.33%   |
| 5600  | 5        | 5.21%   |
| 4800  | 5        | 5.21%   |
| 3600  | 4        | 4.17%   |
| 2400  | 4        | 4.17%   |
| 3933  | 3        | 3.13%   |
| 2666  | 3        | 3.13%   |
| 3534  | 2        | 2.08%   |
| 3000  | 2        | 2.08%   |
| 2800  | 2        | 2.08%   |
| 1800  | 2        | 2.08%   |
| 667   | 2        | 2.08%   |
| 6000  | 1        | 1.04%   |
| 3733  | 1        | 1.04%   |
| 3666  | 1        | 1.04%   |
| 3333  | 1        | 1.04%   |
| 3100  | 1        | 1.04%   |
| 2733  | 1        | 1.04%   |
| 2200  | 1        | 1.04%   |
| 2048  | 1        | 1.04%   |
| 1866  | 1        | 1.04%   |
| 800   | 1        | 1.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 2        | 40%     |
| Brother Industries  | 2        | 40%     |
| Samsung Electronics | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson XP-4100 Series           | 1        | 20%     |
| Seiko Epson Printer                  | 1        | 20%     |
| Samsung ML-1640 Series Laser Printer | 1        | 20%     |
| Brother MFC-J435W                    | 1        | 20%     |
| Brother HL-2030 Laser Printer        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| HP ScanJet 82x0C   | 1        | 33.33%  |
| HP ScanJet 3400cse | 1        | 33.33%  |
| HP OfficeJet 6110  | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 31.25%  |
| Sunplus Innovation Technology | 2        | 12.5%   |
| 2M UVC CAMERA                 | 2        | 12.5%   |
| Microdia                      | 1        | 6.25%   |
| MacroSilicon                  | 1        | 6.25%   |
| KYE Systems (Mouse Systems)   | 1        | 6.25%   |
| Huawei Technologies           | 1        | 6.25%   |
| Hewlett-Packard               | 1        | 6.25%   |
| Generalplus Technology        | 1        | 6.25%   |
| Elgato Systems                | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 2        | 12.5%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam        | 2        | 12.5%   |
| Sunplus FULL HD webcam                     | 1        | 6.25%   |
| Sunplus FHD Camera                         | 1        | 6.25%   |
| Microdia Sonix USB 2.0 Camera              | 1        | 6.25%   |
| MacroSilicon USB Video                     | 1        | 6.25%   |
| Logitech Webcam C250                       | 1        | 6.25%   |
| Logitech Webcam C110                       | 1        | 6.25%   |
| Logitech HD Pro Webcam C920                | 1        | 6.25%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 6.25%   |
| Huawei HiCamera                            | 1        | 6.25%   |
| HP Webcam HD 4310                          | 1        | 6.25%   |
| Generalplus GENERAL WEBCAM                 | 1        | 6.25%   |
| Elgato Systems Elgato Facecam              | 1        | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 85       | 65.38%  |
| 1     | 32       | 24.62%  |
| 2     | 11       | 8.46%   |
| 3     | 2        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 24.07%  |
| Graphics card            | 11       | 20.37%  |
| Unassigned class         | 5        | 9.26%   |
| Net/ethernet             | 5        | 9.26%   |
| Firewire controller      | 3        | 5.56%   |
| Communication controller | 3        | 5.56%   |
| Storage/raid             | 2        | 3.7%    |
| Storage/ide              | 2        | 3.7%    |
| Sound                    | 2        | 3.7%    |
| Storage/ata              | 1        | 1.85%   |
| Storage                  | 1        | 1.85%   |
| Network                  | 1        | 1.85%   |
| Multimedia controller    | 1        | 1.85%   |
| Modem                    | 1        | 1.85%   |
| Fingerprint reader       | 1        | 1.85%   |
| Dvb card                 | 1        | 1.85%   |
| Bluetooth                | 1        | 1.85%   |

