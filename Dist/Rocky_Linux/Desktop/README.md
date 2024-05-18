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

Total: 131

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Google        | Tricky                      | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
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


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Rocky Linux 9.1 | 18       | 18.18%  |
| Rocky Linux 9.3 | 14       | 14.14%  |
| Rocky Linux 8.5 | 12       | 12.12%  |
| Rocky Linux 9.2 | 10       | 10.1%   |
| Rocky Linux 8.8 | 9        | 9.09%   |
| Rocky Linux 8.4 | 9        | 9.09%   |
| Rocky Linux 8.7 | 8        | 8.08%   |
| Rocky Linux 8.6 | 8        | 8.08%   |
| Rocky Linux 9.0 | 7        | 7.07%   |
| Rocky Linux 8.9 | 3        | 3.03%   |
| Rocky Linux 8.3 | 1        | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 97       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                               | Desktops | Percent |
|---------------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64       | 6        | 5.77%   |
| 4.18.0-348.12.2.el8_5.x86_64          | 6        | 5.77%   |
| 4.18.0-477.27.1.el8_8.x86_64          | 5        | 4.81%   |
| 5.14.0-362.18.1.el9_3.0.1.x86_64      | 4        | 3.85%   |
| 5.14.0-362.13.1.el9_3.x86_64          | 4        | 3.85%   |
| 5.14.0-284.30.1.el9_2.x86_64          | 4        | 3.85%   |
| 5.14.0-284.11.1.el9_2.x86_64          | 4        | 3.85%   |
| 5.14.0-162.18.1.el9_1.x86_64          | 4        | 3.85%   |
| 4.18.0-425.19.2.el8_7.x86_64          | 4        | 3.85%   |
| 5.14.0-70.30.1.el9_0.x86_64           | 3        | 2.88%   |
| 5.14.0-70.26.1.el9_0.x86_64           | 3        | 2.88%   |
| 5.14.0-362.8.1.el9_3.x86_64           | 3        | 2.88%   |
| 5.14.0-162.23.1.el9_1.x86_64          | 3        | 2.88%   |
| 4.18.0-348.7.1.el8_5.x86_64           | 3        | 2.88%   |
| 4.18.0-305.10.2.el8_4.x86_64          | 3        | 2.88%   |
| 5.14.0-362.24.1.el9_3.x86_64          | 2        | 1.92%   |
| 5.14.0-162.6.1.el9_1.x86_64           | 2        | 1.92%   |
| 4.18.0-513.18.1.el8_9.x86_64          | 2        | 1.92%   |
| 4.18.0-477.21.1.el8_8.x86_64          | 2        | 1.92%   |
| 4.18.0-477.15.1.el8_8.x86_64          | 2        | 1.92%   |
| 4.18.0-425.13.1.el8_7.x86_64          | 2        | 1.92%   |
| 4.18.0-425.10.1.el8_7.x86_64          | 2        | 1.92%   |
| 4.18.0-372.32.1.el8_6.x86_64          | 2        | 1.92%   |
| 4.18.0-372.26.1.el8_6.x86_64          | 2        | 1.92%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64      | 2        | 1.92%   |
| 4.18.0-348.20.1.el8_5.x86_64          | 2        | 1.92%   |
| 4.18.0-305.19.1.el8_4.x86_64          | 2        | 1.92%   |
| 4.18.0-305.12.1.el8_4.x86_64          | 2        | 1.92%   |
| 6.6.11-1.el9.elrepo.x86_64            | 1        | 0.96%   |
| 6.1.8-1.el9.elrepo.x86_64             | 1        | 0.96%   |
| 6.1.6-1.el8.elrepo.x86_64             | 1        | 0.96%   |
| 6.0.10_tkg_bmq                        | 1        | 0.96%   |
| 6.0.10-1.el9.elrepo.x86_64            | 1        | 0.96%   |
| 5.14.1-1.el8.elrepo.x86_64            | 1        | 0.96%   |
| 5.14.0-70.22.1.el9_0.x86_64           | 1        | 0.96%   |
| 5.14.0-70.17.1.el9_0.x86_64           | 1        | 0.96%   |
| 5.14.0-284.30.1.rt14.315.el9_2.x86_64 | 1        | 0.96%   |
| 5.14.0-284.25.1.el9_2.x86_64          | 1        | 0.96%   |
| 5.14.0-284.18.1.el9_2.x86_64          | 1        | 0.96%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64      | 1        | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 47       | 47.96%  |
| 5.14.0  | 45       | 45.92%  |
| 6.0.10  | 2        | 2.04%   |
| 6.6.11  | 1        | 1.02%   |
| 6.1.8   | 1        | 1.02%   |
| 6.1.6   | 1        | 1.02%   |
| 5.14.1  | 1        | 1.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 47       | 47.96%  |
| 5.14    | 46       | 46.94%  |
| 6.1     | 2        | 2.04%   |
| 6.0     | 2        | 2.04%   |
| 6.6     | 1        | 1.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 97       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 62       | 62.63%  |
| Unknown       | 19       | 19.19%  |
| KDE5          | 8        | 8.08%   |
| XFCE          | 4        | 4.04%   |
| GNOME Classic | 4        | 4.04%   |
| MATE          | 2        | 2.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 46       | 44.66%  |
| X11     | 37       | 35.92%  |
| Tty     | 10       | 9.71%   |
| Unknown | 8        | 7.77%   |
| Web     | 2        | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 47       | 47.96%  |
| GDM     | 42       | 42.86%  |
| SDDM    | 6        | 6.12%   |
| LightDM | 3        | 3.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 63       | 64.29%  |
| ru_RU   | 4        | 4.08%   |
| en_GB   | 4        | 4.08%   |
| en_CA   | 4        | 4.08%   |
| en_IL   | 3        | 3.06%   |
| ko_KR   | 2        | 2.04%   |
| en_SG   | 2        | 2.04%   |
| en_AU   | 2        | 2.04%   |
| C       | 2        | 2.04%   |
| Unknown | 2        | 2.04%   |
| zh_CN   | 1        | 1.02%   |
| pt_BR   | 1        | 1.02%   |
| pl_PL   | 1        | 1.02%   |
| ja_JP   | 1        | 1.02%   |
| es_CO   | 1        | 1.02%   |
| es_AR   | 1        | 1.02%   |
| en_ZA   | 1        | 1.02%   |
| en_IN   | 1        | 1.02%   |
| de_DE   | 1        | 1.02%   |
| af_ZA   | 1        | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 56       | 57.14%  |
| BIOS | 42       | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 78       | 80.41%  |
| Ext4 | 18       | 18.56%  |
| Ext2 | 1        | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 56       | 57.73%  |
| Unknown | 25       | 25.77%  |
| MBR     | 16       | 16.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 79.38%  |
| Yes       | 20       | 20.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 84.54%  |
| Yes       | 15       | 15.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 24       | 24.74%  |
| Dell                | 14       | 14.43%  |
| Gigabyte Technology | 13       | 13.4%   |
| Hewlett-Packard     | 11       | 11.34%  |
| MSI                 | 8        | 8.25%   |
| ASRock              | 5        | 5.15%   |
| Lenovo              | 4        | 4.12%   |
| AZW                 | 3        | 3.09%   |
| Unknown             | 3        | 3.09%   |
| Intel               | 2        | 2.06%   |
| BESSTAR Tech        | 2        | 2.06%   |
| Techvision          | 1        | 1.03%   |
| System76            | 1        | 1.03%   |
| Sapphire            | 1        | 1.03%   |
| Pegatron            | 1        | 1.03%   |
| NCR                 | 1        | 1.03%   |
| Machenike           | 1        | 1.03%   |
| HPE                 | 1        | 1.03%   |
| Google              | 1        | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 3        | 3.09%   |
| HP Z210 Workstation                 | 2        | 2.06%   |
| Gigabyte 970A-DS3P                  | 2        | 2.06%   |
| Dell OptiPlex 9020                  | 2        | 2.06%   |
| Techvision TVI7309X                 | 1        | 1.03%   |
| System76 Thelio Mira                | 1        | 1.03%   |
| Sapphire PE-AM2RS690V2              | 1        | 1.03%   |
| Pegatron IPMIP-GS                   | 1        | 1.03%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 1.03%   |
| MSI MS-7D78                         | 1        | 1.03%   |
| MSI MS-7D46                         | 1        | 1.03%   |
| MSI MS-7D25                         | 1        | 1.03%   |
| MSI MS-7B89                         | 1        | 1.03%   |
| MSI MS-7B78                         | 1        | 1.03%   |
| MSI MS-7A94                         | 1        | 1.03%   |
| MSI MS-7917                         | 1        | 1.03%   |
| MSI H510M PRO-E                     | 1        | 1.03%   |
| Machenike DT                        | 1        | 1.03%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 1.03%   |
| Lenovo ThinkStation P340 30DK000CUS | 1        | 1.03%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 1.03%   |
| Lenovo H535 10117                   | 1        | 1.03%   |
| Intel X99                           | 1        | 1.03%   |
| Intel PRO412081                     | 1        | 1.03%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 1.03%   |
| HP Z820 Workstation                 | 1        | 1.03%   |
| HP Z800 Workstation                 | 1        | 1.03%   |
| HP Z600 Workstation                 | 1        | 1.03%   |
| HP Z1 G8 Tower Desktop PC           | 1        | 1.03%   |
| HP ProDesk 600 G2 SFF               | 1        | 1.03%   |
| HP Pavilion Desktop TP01-0xxx       | 1        | 1.03%   |
| HP ENVY TE01-0xxx                   | 1        | 1.03%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.03%   |
| HP 700-074                          | 1        | 1.03%   |
| Google Tricky                       | 1        | 1.03%   |
| Gigabyte Z97P-D3                    | 1        | 1.03%   |
| Gigabyte X670 GAMING X AX           | 1        | 1.03%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 1.03%   |
| Gigabyte X399 AORUS PRO             | 1        | 1.03%   |
| Gigabyte H87-D3H                    | 1        | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 12       | 12.37%  |
| Dell OptiPlex          | 7        | 7.22%   |
| Dell Precision         | 4        | 4.12%   |
| ASUS ROG               | 3        | 3.09%   |
| Unknown                | 3        | 3.09%   |
| Lenovo ThinkStation    | 2        | 2.06%   |
| HP Z210                | 2        | 2.06%   |
| Gigabyte 970A-DS3P     | 2        | 2.06%   |
| Dell Vostro            | 2        | 2.06%   |
| ASUS Pro               | 2        | 2.06%   |
| Techvision TVI7309X    | 1        | 1.03%   |
| System76 Thelio        | 1        | 1.03%   |
| Sapphire PE-AM2RS690V2 | 1        | 1.03%   |
| Pegatron IPMIP-GS      | 1        | 1.03%   |
| NCR xxxx-xxxx-xxxx     | 1        | 1.03%   |
| MSI MS-7D78            | 1        | 1.03%   |
| MSI MS-7D46            | 1        | 1.03%   |
| MSI MS-7D25            | 1        | 1.03%   |
| MSI MS-7B89            | 1        | 1.03%   |
| MSI MS-7B78            | 1        | 1.03%   |
| MSI MS-7A94            | 1        | 1.03%   |
| MSI MS-7917            | 1        | 1.03%   |
| MSI H510M              | 1        | 1.03%   |
| Machenike DT           | 1        | 1.03%   |
| Lenovo ThinkCentre     | 1        | 1.03%   |
| Lenovo H535            | 1        | 1.03%   |
| Intel X99              | 1        | 1.03%   |
| Intel PRO412081        | 1        | 1.03%   |
| HPE ProLiant           | 1        | 1.03%   |
| HP Z820                | 1        | 1.03%   |
| HP Z800                | 1        | 1.03%   |
| HP Z600                | 1        | 1.03%   |
| HP Z1                  | 1        | 1.03%   |
| HP ProDesk             | 1        | 1.03%   |
| HP Pavilion            | 1        | 1.03%   |
| HP ENVY                | 1        | 1.03%   |
| HP EliteDesk           | 1        | 1.03%   |
| HP 700-074             | 1        | 1.03%   |
| Google Tricky          | 1        | 1.03%   |
| Gigabyte Z97P-D3       | 1        | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 11       | 11.34%  |
| 2022 | 10       | 10.31%  |
| 2020 | 10       | 10.31%  |
| 2013 | 10       | 10.31%  |
| 2011 | 10       | 10.31%  |
| 2019 | 7        | 7.22%   |
| 2018 | 7        | 7.22%   |
| 2014 | 6        | 6.19%   |
| 2015 | 5        | 5.15%   |
| 2012 | 5        | 5.15%   |
| 2023 | 4        | 4.12%   |
| 2017 | 3        | 3.09%   |
| 2010 | 3        | 3.09%   |
| 2008 | 3        | 3.09%   |
| 2016 | 2        | 2.06%   |
| 2009 | 1        | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 97       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 92       | 94.85%  |
| Enabled  | 5        | 5.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 98.97%  |
| Yes  | 1        | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 19       | 19.39%  |
| 64.01-256.0     | 18       | 18.37%  |
| 8.01-16.0       | 16       | 16.33%  |
| 4.01-8.0        | 15       | 15.31%  |
| 16.01-24.0      | 14       | 14.29%  |
| 24.01-32.0      | 5        | 5.1%    |
| 3.01-4.0        | 4        | 4.08%   |
| 1.01-2.0        | 3        | 3.06%   |
| More than 256.0 | 2        | 2.04%   |
| 2.01-3.0        | 2        | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 28       | 27.72%  |
| 4.01-8.0    | 22       | 21.78%  |
| 3.01-4.0    | 19       | 18.81%  |
| 1.01-2.0    | 12       | 11.88%  |
| 0.51-1.0    | 6        | 5.94%   |
| 8.01-16.0   | 5        | 4.95%   |
| 16.01-24.0  | 3        | 2.97%   |
| 32.01-64.0  | 2        | 1.98%   |
| 0.01-0.5    | 2        | 1.98%   |
| 24.01-32.0  | 1        | 0.99%   |
| 64.01-256.0 | 1        | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 42%     |
| 2      | 25       | 25%     |
| 3      | 12       | 12%     |
| 4      | 11       | 11%     |
| 6      | 4        | 4%      |
| 5      | 4        | 4%      |
| 9      | 1        | 1%      |
| 8      | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 65.98%  |
| Yes       | 33       | 34.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 98.97%  |
| No        | 1        | 1.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 60%     |
| Yes       | 40       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 67.35%  |
| Yes       | 32       | 32.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 31       | 31.96%  |
| Germany                | 7        | 7.22%   |
| Russia                 | 6        | 6.19%   |
| Canada                 | 6        | 6.19%   |
| Singapore              | 4        | 4.12%   |
| Italy                  | 4        | 4.12%   |
| UK                     | 3        | 3.09%   |
| South Korea            | 3        | 3.09%   |
| Israel                 | 3        | 3.09%   |
| Australia              | 3        | 3.09%   |
| South Africa           | 2        | 2.06%   |
| Netherlands            | 2        | 2.06%   |
| Indonesia              | 2        | 2.06%   |
| India                  | 2        | 2.06%   |
| France                 | 2        | 2.06%   |
| Sweden                 | 1        | 1.03%   |
| Portugal               | 1        | 1.03%   |
| Poland                 | 1        | 1.03%   |
| Norway                 | 1        | 1.03%   |
| Mexico                 | 1        | 1.03%   |
| Malaysia               | 1        | 1.03%   |
| Japan                  | 1        | 1.03%   |
| Iran                   | 1        | 1.03%   |
| Hong Kong              | 1        | 1.03%   |
| Finland                | 1        | 1.03%   |
| Czechia                | 1        | 1.03%   |
| Colombia               | 1        | 1.03%   |
| China                  | 1        | 1.03%   |
| Brazil                 | 1        | 1.03%   |
| Bosnia and Herzegovina | 1        | 1.03%   |
| Austria                | 1        | 1.03%   |
| Argentina              | 1        | 1.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 4        | 4.04%   |
| Düsseldorf            | 3        | 3.03%   |
| Toronto                | 2        | 2.02%   |
| St Petersburg          | 2        | 2.02%   |
| Melbourne              | 2        | 2.02%   |
| Haifa                  | 2        | 2.02%   |
| Chicago                | 2        | 2.02%   |
| Buckley                | 2        | 2.02%   |
| Berlin                 | 2        | 2.02%   |
| Yogyakarta             | 1        | 1.01%   |
| Yekaterinburg          | 1        | 1.01%   |
| Willowbrook            | 1        | 1.01%   |
| Wells                  | 1        | 1.01%   |
| Washington             | 1        | 1.01%   |
| Waltham                | 1        | 1.01%   |
| Voronezh               | 1        | 1.01%   |
| Vienna                 | 1        | 1.01%   |
| Vero Beach             | 1        | 1.01%   |
| Vashon                 | 1        | 1.01%   |
| Vancouver              | 1        | 1.01%   |
| Tlaxcala City          | 1        | 1.01%   |
| Thoothukudi            | 1        | 1.01%   |
| Tehran                 | 1        | 1.01%   |
| St. John's             | 1        | 1.01%   |
| Springfield            | 1        | 1.01%   |
| Sobral de Monte Agraco | 1        | 1.01%   |
| Siroki Brijeg          | 1        | 1.01%   |
| Simi Valley            | 1        | 1.01%   |
| Semarang               | 1        | 1.01%   |
| Sao Jose do Rio Claro  | 1        | 1.01%   |
| Rotterdam              | 1        | 1.01%   |
| Rome                   | 1        | 1.01%   |
| Rochester              | 1        | 1.01%   |
| Rehovot                | 1        | 1.01%   |
| Prague                 | 1        | 1.01%   |
| Paris                  | 1        | 1.01%   |
| Ōtsu                  | 1        | 1.01%   |
| Oslo                   | 1        | 1.01%   |
| Ormond Beach           | 1        | 1.01%   |
| Newmarket              | 1        | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 26       | 44     | 16.15%  |
| Samsung Electronics         | 26       | 43     | 16.15%  |
| Seagate                     | 25       | 53     | 15.53%  |
| Toshiba                     | 10       | 14     | 6.21%   |
| Hitachi                     | 8        | 13     | 4.97%   |
| Crucial                     | 7        | 8      | 4.35%   |
| SanDisk                     | 6        | 6      | 3.73%   |
| Kingston                    | 5        | 5      | 3.11%   |
| Intel                       | 5        | 8      | 3.11%   |
| SK hynix                    | 4        | 4      | 2.48%   |
| Unknown                     | 3        | 6      | 1.86%   |
| MAXIO Technology (Hangzhou) | 3        | 4      | 1.86%   |
| HGST                        | 3        | 3      | 1.86%   |
| China                       | 3        | 3      | 1.86%   |
| Kingston Technology Company | 2        | 2      | 1.24%   |
| Gigabyte Technology         | 2        | 2      | 1.24%   |
| Transcend                   | 1        | 1      | 0.62%   |
| Teclast                     | 1        | 1      | 0.62%   |
| Team                        | 1        | 1      | 0.62%   |
| SPCC                        | 1        | 1      | 0.62%   |
| SABRENT                     | 1        | 1      | 0.62%   |
| Realtek Semiconductor       | 1        | 1      | 0.62%   |
| PNY                         | 1        | 1      | 0.62%   |
| Phison                      | 1        | 1      | 0.62%   |
| MyDigitalSSD                | 1        | 1      | 0.62%   |
| Mobius                      | 1        | 2      | 0.62%   |
| Micron/Crucial Technology   | 1        | 2      | 0.62%   |
| Micron Technology           | 1        | 1      | 0.62%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.62%   |
| KIOXIA                      | 1        | 1      | 0.62%   |
| GOODRAM                     | 1        | 1      | 0.62%   |
| G-DRIVE                     | 1        | 1      | 0.62%   |
| DUEX-120GB                  | 1        | 1      | 0.62%   |
| Digma                       | 1        | 1      | 0.62%   |
| Corsair                     | 1        | 1      | 0.62%   |
| Apacer                      | 1        | 1      | 0.62%   |
| AMD                         | 1        | 5      | 0.62%   |
| ADATA SU                    | 1        | 1      | 0.62%   |
| A-DATA Technology           | 1        | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 6        | 3.17%   |
| Seagate ST500DM002-1BD142 500GB                    | 4        | 2.12%   |
| WDC WD2002FAEX-007BA0 2TB                          | 2        | 1.06%   |
| Seagate ST4000DM004-2CV104 4TB                     | 2        | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2        | 1.06%   |
| Samsung SSD 980 1TB                                | 2        | 1.06%   |
| Samsung SSD 860 EVO 1TB                            | 2        | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2        | 1.06%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 2        | 1.06%   |
| Kingston Company SNV2S250G 250GB                   | 2        | 1.06%   |
| Kingston SA400S37960G 960GB SSD                    | 2        | 1.06%   |
| Gigabyte GP-GSTFS31240GNTD 240GB                   | 2        | 1.06%   |
| Crucial CT240BX500SSD1 240GB                       | 2        | 1.06%   |
| WDC WDS500G1R0A-68A4W0 500GB                       | 1        | 0.53%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                   | 1        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1        | 0.53%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 1        | 0.53%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                     | 1        | 0.53%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 1        | 0.53%   |
| WDC WD5000AUDX-63WNHY0 500GB                       | 1        | 0.53%   |
| WDC WD5000AAKX-75U6AA0 500GB                       | 1        | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB                        | 1        | 0.53%   |
| WDC WD40PURZ-85AKKY0 4TB                           | 1        | 0.53%   |
| WDC WD40EZRZ-00WN9B0 4TB                           | 1        | 0.53%   |
| WDC WD40EZAX-00C8UB0 4TB                           | 1        | 0.53%   |
| WDC WD4003FRYZ-01F0DB0 4TB                         | 1        | 0.53%   |
| WDC WD30EZRX-00D8PB0 3TB                           | 1        | 0.53%   |
| WDC WD2500AAJS-22VTA0 250GB                        | 1        | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1        | 0.53%   |
| WDC WD20EZRX-00DC0B0 2TB                           | 1        | 0.53%   |
| WDC WD20EZBX-00AYRA0 2TB                           | 1        | 0.53%   |
| WDC WD20EFZX-68AWUN0 2TB                           | 1        | 0.53%   |
| WDC WD2003FZEX-00SRLA0 2TB                         | 1        | 0.53%   |
| WDC WD10EZEX-75M2NA0 1TB                           | 1        | 0.53%   |
| WDC WD10EZEX-60WN4A1 1TB                           | 1        | 0.53%   |
| WDC WD10EZEX-21WN4A0 1TB                           | 1        | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1        | 0.53%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1        | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 25       | 53     | 35.21%  |
| WDC                 | 21       | 34     | 29.58%  |
| Toshiba             | 9        | 13     | 12.68%  |
| Hitachi             | 8        | 13     | 11.27%  |
| Samsung Electronics | 3        | 5      | 4.23%   |
| HGST                | 2        | 2      | 2.82%   |
| Unknown             | 1        | 1      | 1.41%   |
| SABRENT             | 1        | 1      | 1.41%   |
| Mobius              | 1        | 2      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 13     | 18.37%  |
| WDC                 | 6        | 9      | 12.24%  |
| Crucial             | 6        | 7      | 12.24%  |
| SanDisk             | 4        | 4      | 8.16%   |
| Kingston            | 4        | 4      | 8.16%   |
| China               | 3        | 3      | 6.12%   |
| Gigabyte Technology | 2        | 2      | 4.08%   |
| Toshiba             | 1        | 1      | 2.04%   |
| Teclast             | 1        | 1      | 2.04%   |
| Team                | 1        | 1      | 2.04%   |
| SPCC                | 1        | 1      | 2.04%   |
| SK hynix            | 1        | 1      | 2.04%   |
| PNY                 | 1        | 1      | 2.04%   |
| MyDigitalSSD        | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| GOODRAM             | 1        | 1      | 2.04%   |
| G-DRIVE             | 1        | 1      | 2.04%   |
| DUEX-120GB          | 1        | 1      | 2.04%   |
| Digma               | 1        | 1      | 2.04%   |
| Corsair             | 1        | 1      | 2.04%   |
| Apacer              | 1        | 1      | 2.04%   |
| ADATA SU            | 1        | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 52       | 124    | 36.88%  |
| SSD     | 45       | 57     | 31.91%  |
| NVMe    | 41       | 60     | 29.08%  |
| Unknown | 2        | 5      | 1.42%   |
| MMC     | 1        | 1      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 80       | 171    | 62.5%   |
| NVMe | 41       | 60     | 32.03%  |
| SAS  | 6        | 15     | 4.69%   |
| MMC  | 1        | 1      | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 73     | 45.28%  |
| 0.51-1.0   | 28       | 50     | 26.42%  |
| 1.01-2.0   | 14       | 26     | 13.21%  |
| 3.01-4.0   | 10       | 25     | 9.43%   |
| 2.01-3.0   | 2        | 2      | 1.89%   |
| 4.01-10.0  | 2        | 2      | 1.89%   |
| 20.01-50.0 | 1        | 2      | 0.94%   |
| 10.01-20.0 | 1        | 1      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 23%     |
| 501-1000       | 19       | 19%     |
| 1001-2000      | 18       | 18%     |
| 251-500        | 14       | 14%     |
| More than 3000 | 13       | 13%     |
| 2001-3000      | 5        | 5%      |
| Unknown        | 3        | 3%      |
| 1-20           | 2        | 2%      |
| 51-100         | 2        | 2%      |
| 21-50          | 1        | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 31       | 29.81%  |
| 21-50          | 19       | 18.27%  |
| 51-100         | 15       | 14.42%  |
| 501-1000       | 9        | 8.65%   |
| 251-500        | 8        | 7.69%   |
| 101-250        | 8        | 7.69%   |
| More than 3000 | 7        | 6.73%   |
| 1001-2000      | 3        | 2.88%   |
| Unknown        | 3        | 2.88%   |
| 2001-3000      | 1        | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD40EZRZ-00WN9B0 4TB       | 1        | 1      | 7.69%   |
| WDC WD1001FALS-00J7B1 1TB      | 1        | 2      | 7.69%   |
| WDC WD1001FALS-00J7B0 1TB      | 1        | 4      | 7.69%   |
| Toshiba MK1059GSM 1TB          | 1        | 1      | 7.69%   |
| Seagate ST9500325AS 500GB      | 1        | 1      | 7.69%   |
| Seagate ST9320325AS 320GB      | 1        | 1      | 7.69%   |
| Seagate ST31000528AS 1TB       | 1        | 2      | 7.69%   |
| Intel SSD 600P Series 256GB    | 1        | 2      | 7.69%   |
| Hitachi HTS727575A9E364 752GB  | 1        | 1      | 7.69%   |
| Hitachi HDS725050KLA360 500GB  | 1        | 1      | 7.69%   |
| Hitachi HDS721010CLA632 1TB    | 1        | 1      | 7.69%   |
| Crucial CT1050MX300SSD1 1050GB | 1        | 1      | 7.69%   |
| Corsair Neutron SSD 64GB       | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 7      | 23.08%  |
| Seagate | 3        | 4      | 23.08%  |
| Hitachi | 3        | 3      | 23.08%  |
| Toshiba | 1        | 1      | 7.69%   |
| Intel   | 1        | 2      | 7.69%   |
| Crucial | 1        | 1      | 7.69%   |
| Corsair | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 7      | 30%     |
| Seagate | 3        | 4      | 30%     |
| Hitachi | 3        | 3      | 30%     |
| Toshiba | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 15     | 72.73%  |
| SSD  | 2        | 2      | 18.18%  |
| NVMe | 1        | 2      | 9.09%   |

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
| Works    | 68       | 154    | 61.26%  |
| Detected | 32       | 73     | 28.83%  |
| Malfunc  | 10       | 19     | 9.01%   |
| Failed   | 1        | 1      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 64       | 42.11%  |
| AMD                         | 34       | 22.37%  |
| Samsung Electronics         | 17       | 11.18%  |
| ASMedia Technology          | 5        | 3.29%   |
| Broadcom / LSI              | 4        | 2.63%   |
| SK hynix                    | 3        | 1.97%   |
| SanDisk                     | 3        | 1.97%   |
| MAXIO Technology (Hangzhou) | 3        | 1.97%   |
| Kingston Technology Company | 3        | 1.97%   |
| Realtek Semiconductor       | 2        | 1.32%   |
| Micron/Crucial Technology   | 2        | 1.32%   |
| LSI Logic / Symbios Logic   | 2        | 1.32%   |
| KIOXIA                      | 2        | 1.32%   |
| VIA Technologies            | 1        | 0.66%   |
| Transcend                   | 1        | 0.66%   |
| Silicon Image               | 1        | 0.66%   |
| Phison Electronics          | 1        | 0.66%   |
| Micron Technology           | 1        | 0.66%   |
| Marvell Technology Group    | 1        | 0.66%   |
| JMicron Technology          | 1        | 0.66%   |
| Adaptec                     | 1        | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 9.73%   |
| Intel SATA Controller [RAID Mode]                                                       | 9        | 4.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8        | 4.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 2.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 2.16%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.16%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 4        | 2.16%   |
| AMD 600 Series Chipset SATA Controller                                                  | 4        | 2.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.62%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.62%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 3        | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.62%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 1.08%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 1.08%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 2        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.08%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 1.08%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 1.08%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 1.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.08%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.08%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 1.08%   |
| AMD FCH SATA Controller [RAID Bottom]                                                   | 2        | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.08%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.54%   |
| Transcend NVMe PCIe SSD 240S/MTE710T                                                    | 1        | 0.54%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 0.54%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 77       | 49.04%  |
| NVMe | 41       | 26.11%  |
| IDE  | 18       | 11.46%  |
| RAID | 14       | 8.92%   |
| SAS  | 5        | 3.18%   |
| SCSI | 2        | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 62       | 63.92%  |
| AMD    | 35       | 36.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 4.12%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.06%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 2.06%   |
| Intel 12th Gen Core i5-12400F               | 2        | 2.06%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 2.06%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.06%   |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1        | 1.03%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 1.03%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 1.03%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz         | 1        | 1.03%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 1.03%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 1.03%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 1.03%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 1.03%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 1.03%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 1.03%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 1.03%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.03%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.03%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1        | 1.03%   |
| Intel Core i9-10900KF CPU @ 3.70GHz         | 1        | 1.03%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.03%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.03%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1        | 1.03%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.03%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.03%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.03%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.03%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.03%   |
| Intel Core i5-8269U CPU @ 2.60GHz           | 1        | 1.03%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 1.03%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.03%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.03%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.03%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.03%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 16       | 16.49%  |
| Intel Core i5           | 14       | 14.43%  |
| Intel Xeon              | 10       | 10.31%  |
| Other                   | 9        | 9.28%   |
| AMD Ryzen 7             | 8        | 8.25%   |
| AMD Ryzen 9             | 6        | 6.19%   |
| AMD Ryzen Threadripper  | 5        | 5.15%   |
| Intel Core i3           | 4        | 4.12%   |
| Intel Celeron           | 4        | 4.12%   |
| AMD FX                  | 4        | 4.12%   |
| AMD Ryzen 5             | 3        | 3.09%   |
| Intel Core i9           | 2        | 2.06%   |
| Intel Pentium Gold      | 1        | 1.03%   |
| Intel Pentium Dual-Core | 1        | 1.03%   |
| Intel Pentium Dual      | 1        | 1.03%   |
| Intel Core 2 Quad       | 1        | 1.03%   |
| AMD Sempron             | 1        | 1.03%   |
| AMD Ryzen Embedded      | 1        | 1.03%   |
| AMD Ryzen 7 PRO         | 1        | 1.03%   |
| AMD Ryzen 3             | 1        | 1.03%   |
| AMD Phenom II X6        | 1        | 1.03%   |
| AMD Athlon II X2        | 1        | 1.03%   |
| AMD A8                  | 1        | 1.03%   |
| AMD A4                  | 1        | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 33       | 34.02%  |
| 6      | 16       | 16.49%  |
| 8      | 15       | 15.46%  |
| 2      | 15       | 15.46%  |
| 12     | 7        | 7.22%   |
| 24     | 4        | 4.12%   |
| 16     | 4        | 4.12%   |
| 10     | 2        | 2.06%   |
| 3      | 1        | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 95.88%  |
| 2      | 4        | 4.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 72       | 74.23%  |
| 1      | 25       | 25.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 97       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 16.33%  |
| 0x206a7    | 8        | 8.16%   |
| 0x306c3    | 5        | 5.1%    |
| 0x506e3    | 3        | 3.06%   |
| 0x306a9    | 3        | 3.06%   |
| 0x0a601203 | 3        | 3.06%   |
| 0x06000852 | 3        | 3.06%   |
| 0xa0671    | 2        | 2.04%   |
| 0xa0655    | 2        | 2.04%   |
| 0xa0653    | 2        | 2.04%   |
| 0x906ea    | 2        | 2.04%   |
| 0x906c0    | 2        | 2.04%   |
| 0x90672    | 2        | 2.04%   |
| 0x306e4    | 2        | 2.04%   |
| 0x206c2    | 2        | 2.04%   |
| 0x0a404102 | 2        | 2.04%   |
| 0x08600106 | 2        | 2.04%   |
| 0x08108109 | 2        | 2.04%   |
| 0x0800820d | 2        | 2.04%   |
| 0xb0671    | 1        | 1.02%   |
| 0x906ed    | 1        | 1.02%   |
| 0x90675    | 1        | 1.02%   |
| 0x706a8    | 1        | 1.02%   |
| 0x6fd      | 1        | 1.02%   |
| 0x50654    | 1        | 1.02%   |
| 0x406f1    | 1        | 1.02%   |
| 0x40651    | 1        | 1.02%   |
| 0x306f2    | 1        | 1.02%   |
| 0x206d7    | 1        | 1.02%   |
| 0x106e5    | 1        | 1.02%   |
| 0x10677    | 1        | 1.02%   |
| 0x10676    | 1        | 1.02%   |
| 0x0a601201 | 1        | 1.02%   |
| 0x0a50000c | 1        | 1.02%   |
| 0x0a20120a | 1        | 1.02%   |
| 0x0a201016 | 1        | 1.02%   |
| 0x0a201009 | 1        | 1.02%   |
| 0x0a008205 | 1        | 1.02%   |
| 0x08701021 | 1        | 1.02%   |
| 0x0870100a | 1        | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 11       | 11.34%  |
| SandyBridge      | 10       | 10.31%  |
| KabyLake         | 7        | 7.22%   |
| Unknown          | 7        | 7.22%   |
| Zen 2            | 6        | 6.19%   |
| Skylake          | 5        | 5.15%   |
| Piledriver       | 5        | 5.15%   |
| IvyBridge        | 5        | 5.15%   |
| CometLake        | 5        | 5.15%   |
| Alderlake Hybrid | 5        | 5.15%   |
| Zen+             | 4        | 4.12%   |
| Zen 3            | 4        | 4.12%   |
| Zen              | 4        | 4.12%   |
| Westmere         | 3        | 3.09%   |
| K10              | 3        | 3.09%   |
| Icelake          | 3        | 3.09%   |
| Tremont          | 2        | 2.06%   |
| Penryn           | 2        | 2.06%   |
| Nehalem          | 1        | 1.03%   |
| K10 Llano        | 1        | 1.03%   |
| Jaguar           | 1        | 1.03%   |
| Goldmont plus    | 1        | 1.03%   |
| Core             | 1        | 1.03%   |
| Broadwell        | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 44       | 41.12%  |
| Intel             | 35       | 32.71%  |
| AMD               | 27       | 25.23%  |
| ASPEED Technology | 1        | 0.93%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 4.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 3.67%   |
| Intel HD Graphics 530                                                       | 4        | 3.67%   |
| AMD Raphael                                                                 | 4        | 3.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.83%   |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 1.83%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.83%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.83%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 1.83%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 1.83%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.83%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 1.83%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2        | 1.83%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2        | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.83%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.83%   |
| Nvidia TU117GL [T600]                                                       | 1        | 0.92%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.92%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.92%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.92%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.92%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.92%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.92%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.92%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 0.92%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.92%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.92%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.92%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 35       | 36.08%  |
| 1 x Intel       | 31       | 31.96%  |
| 1 x AMD         | 21       | 21.65%  |
| AMD + Nvidia    | 4        | 4.12%   |
| Intel + Nvidia  | 3        | 3.09%   |
| 2 x AMD         | 2        | 2.06%   |
| Nvidia + ASPEED | 1        | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 72.45%  |
| Proprietary | 21       | 21.43%  |
| Unknown     | 6        | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 40.82%  |
| 1.01-2.0   | 14       | 14.29%  |
| 0.01-0.5   | 12       | 12.24%  |
| 0.51-1.0   | 11       | 11.22%  |
| 8.01-16.0  | 5        | 5.1%    |
| 7.01-8.0   | 4        | 4.08%   |
| 16.01-24.0 | 4        | 4.08%   |
| 3.01-4.0   | 3        | 3.06%   |
| 2.01-3.0   | 3        | 3.06%   |
| 32.01-64.0 | 1        | 1.02%   |
| 5.01-6.0   | 1        | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 13.83%  |
| Dell                 | 13       | 13.83%  |
| Goldstar             | 9        | 9.57%   |
| Acer                 | 7        | 7.45%   |
| Hewlett-Packard      | 6        | 6.38%   |
| BenQ                 | 6        | 6.38%   |
| Philips              | 5        | 5.32%   |
| Ancor Communications | 5        | 5.32%   |
| Eizo                 | 4        | 4.26%   |
| AOC                  | 4        | 4.26%   |
| Iiyama               | 3        | 3.19%   |
| ViewSonic            | 2        | 2.13%   |
| Unknown              | 2        | 2.13%   |
| Xiaomi               | 1        | 1.06%   |
| Sony                 | 1        | 1.06%   |
| SGT                  | 1        | 1.06%   |
| Sceptre Tech         | 1        | 1.06%   |
| Plain Tree Systems   | 1        | 1.06%   |
| OEM                  | 1        | 1.06%   |
| NEC Computers        | 1        | 1.06%   |
| LLM                  | 1        | 1.06%   |
| LG Electronics       | 1        | 1.06%   |
| Lenovo               | 1        | 1.06%   |
| HUAWEI               | 1        | 1.06%   |
| HCL                  | 1        | 1.06%   |
| EDI                  | 1        | 1.06%   |
| ASUSTek Computer     | 1        | 1.06%   |
| Apple                | 1        | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2        | 2.02%   |
| BenQ GW2283 BNQ78E9 1920x1080 480x270mm 21.7-inch                     | 2        | 2.02%   |
| Unknown                                                               | 2        | 2.02%   |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                    | 1        | 1.01%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch            | 1        | 1.01%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1        | 1.01%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1        | 1.01%   |
| SGT HX156U SGT1560 3840x2160 345x194mm 15.6-inch                      | 1        | 1.01%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch        | 1        | 1.01%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1        | 1.01%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM062E 1280x1024 376x301mm 19.0-inch  | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1        | 1.01%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch  | 1        | 1.01%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1        | 1.01%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1        | 1.01%   |
| Samsung Electronics LF27T35 SAM7080 1920x1080 598x337mm 27.0-inch     | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 1        | 1.01%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 1.01%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.01%   |
| Plain Tree Systems PS-576 PTS1599 1280x800 332x207mm 15.4-inch        | 1        | 1.01%   |
| Philips PHL 279P1 PHL0948 3840x2160 597x336mm 27.0-inch               | 1        | 1.01%   |
| Philips PHL 275E2F PHLC23A 2560x1440 600x340mm 27.2-inch              | 1        | 1.01%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 1.01%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 1.01%   |
| Philips LCD Monitor PHL4650 1280x768 710x400mm 32.1-inch              | 1        | 1.01%   |
| OEM 26W_LCD_TV OEM3700 1920x540                                       | 1        | 1.01%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1        | 1.01%   |
| LLM HDMI EDID LLM0401 3840x2160 477x268mm 21.5-inch                   | 1        | 1.01%   |
| LG Electronics LCD Monitor LG HDR 4K 7680x2160                        | 1        | 1.01%   |
| LG Electronics LCD Monitor LG HDR 4K                                  | 1        | 1.01%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                   | 1        | 1.01%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1        | 1.01%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                  | 1        | 1.01%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1        | 1.01%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 1        | 1.01%   |
| Hewlett-Packard V27e HPN36AF 1920x1080 598x336mm 27.0-inch            | 1        | 1.01%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch            | 1        | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 32.29%  |
| 3840x2160 (4K)     | 14       | 14.58%  |
| 1280x1024 (SXGA)   | 8        | 8.33%   |
| 2560x1440 (QHD)    | 7        | 7.29%   |
| 1920x1200 (WUXGA)  | 5        | 5.21%   |
| 3440x1440          | 4        | 4.17%   |
| 1600x900 (HD+)     | 4        | 4.17%   |
| 3840x1080          | 3        | 3.13%   |
| 1920x540           | 3        | 3.13%   |
| 1366x768 (WXGA)    | 3        | 3.13%   |
| Unknown            | 3        | 3.13%   |
| 2560x1080          | 2        | 2.08%   |
| 1680x1050 (WSXGA+) | 2        | 2.08%   |
| 1440x900 (WXGA+)   | 2        | 2.08%   |
| 1024x768 (XGA)     | 2        | 2.08%   |
| 7680x2160          | 1        | 1.04%   |
| 1280x800 (WXGA)    | 1        | 1.04%   |
| 1280x768           | 1        | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 15       | 15.79%  |
| 24      | 14       | 14.74%  |
| 23      | 10       | 10.53%  |
| 19      | 7        | 7.37%   |
| Unknown | 7        | 7.37%   |
| 34      | 6        | 6.32%   |
| 31      | 5        | 5.26%   |
| 21      | 4        | 4.21%   |
| 20      | 4        | 4.21%   |
| 17      | 4        | 4.21%   |
| 18      | 3        | 3.16%   |
| 65      | 2        | 2.11%   |
| 40      | 2        | 2.11%   |
| 22      | 2        | 2.11%   |
| 15      | 2        | 2.11%   |
| 84      | 1        | 1.05%   |
| 54      | 1        | 1.05%   |
| 48      | 1        | 1.05%   |
| 36      | 1        | 1.05%   |
| 32      | 1        | 1.05%   |
| 28      | 1        | 1.05%   |
| 25      | 1        | 1.05%   |
| 14      | 1        | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 38       | 40.43%  |
| 401-500     | 17       | 18.09%  |
| 701-800     | 8        | 8.51%   |
| Unknown     | 7        | 7.45%   |
| 601-700     | 6        | 6.38%   |
| 301-350     | 6        | 6.38%   |
| 351-400     | 4        | 4.26%   |
| 1001-1500   | 4        | 4.26%   |
| 801-900     | 2        | 2.13%   |
| 201-300     | 1        | 1.06%   |
| 1501-2000   | 1        | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 56       | 62.92%  |
| 16/10   | 9        | 10.11%  |
| 5/4     | 8        | 8.99%   |
| Unknown | 6        | 6.74%   |
| 21/9    | 5        | 5.62%   |
| 4/3     | 2        | 2.25%   |
| 32/9    | 2        | 2.25%   |
| 3/2     | 1        | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 24.73%  |
| 301-350        | 15       | 16.13%  |
| 351-500        | 12       | 12.9%   |
| 151-200        | 12       | 12.9%   |
| 141-150        | 7        | 7.53%   |
| Unknown        | 7        | 7.53%   |
| 251-300        | 5        | 5.38%   |
| 501-1000       | 5        | 5.38%   |
| More than 1000 | 4        | 4.3%    |
| 101-110        | 2        | 2.15%   |
| 111-120        | 1        | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 64       | 69.57%  |
| 101-120 | 9        | 9.78%   |
| Unknown | 7        | 7.61%   |
| 121-160 | 5        | 5.43%   |
| 161-240 | 4        | 4.35%   |
| 1-50    | 3        | 3.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 71       | 73.2%   |
| 2     | 13       | 13.4%   |
| 0     | 13       | 13.4%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 58       | 39.73%  |
| Realtek Semiconductor     | 54       | 36.99%  |
| MediaTek                  | 7        | 4.79%   |
| Ralink Technology         | 4        | 2.74%   |
| Broadcom                  | 4        | 2.74%   |
| Linksys                   | 3        | 2.05%   |
| Aquantia                  | 3        | 2.05%   |
| Qualcomm Atheros          | 2        | 1.37%   |
| Marvell Technology Group  | 2        | 1.37%   |
| TP-Link                   | 1        | 0.68%   |
| Spreadtrum Communications | 1        | 0.68%   |
| Solarflare Communications | 1        | 0.68%   |
| Ralink                    | 1        | 0.68%   |
| Microsoft                 | 1        | 0.68%   |
| Mellanox Technologies     | 1        | 0.68%   |
| InterBiometrics           | 1        | 0.68%   |
| Davicom Semiconductor     | 1        | 0.68%   |
| BUFFALO                   | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 40       | 23.53%  |
| Realtek RTL8125 2.5GbE Controller                                              | 8        | 4.71%   |
| Intel I211 Gigabit Network Connection                                          | 8        | 4.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8        | 4.71%   |
| Intel Ethernet Controller I225-V                                               | 6        | 3.53%   |
| Intel Wi-Fi 6 AX200                                                            | 4        | 2.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 3        | 1.76%   |
| Intel Wireless 3165                                                            | 3        | 1.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 3        | 1.76%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 1.76%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.76%   |
| Intel Ethernet Connection (17) I219-V                                          | 3        | 1.76%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 1.76%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 1.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2        | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.18%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2        | 1.18%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 2        | 1.18%   |
| Intel Ethernet Controller X550                                                 | 2        | 1.18%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 1.18%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 1.18%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                            | 1        | 0.59%   |
| Spreadtrum Unisoc Phone                                                        | 1        | 0.59%   |
| Solarflare SFC9020 10G Ethernet Controller                                     | 1        | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1        | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.59%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1        | 0.59%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                         | 1        | 0.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.59%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.59%   |
| Realtek 802.11ac NIC                                                           | 1        | 0.59%   |
| Ralink RT5370 Wireless Adapter                                                 | 1        | 0.59%   |
| Ralink RT3071 Wireless Adapter                                                 | 1        | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1        | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1        | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1        | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 35.56%  |
| Realtek Semiconductor | 8        | 17.78%  |
| MediaTek              | 7        | 15.56%  |
| Ralink Technology     | 4        | 8.89%   |
| Linksys               | 3        | 6.67%   |
| Qualcomm Atheros      | 2        | 4.44%   |
| TP-Link               | 1        | 2.22%   |
| Ralink                | 1        | 2.22%   |
| Microsoft             | 1        | 2.22%   |
| BUFFALO               | 1        | 2.22%   |
| Broadcom              | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 4        | 8.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3        | 6.38%   |
| Intel Wireless 3165                                                    | 3        | 6.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 6.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 4.26%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 4.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 4.26%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 2.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 2.13%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                 | 1        | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 2.13%   |
| Realtek 802.11ac NIC                                                   | 1        | 2.13%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 2.13%   |
| Ralink RT3071 Wireless Adapter                                         | 1        | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 2.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 2.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 2.13%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 1        | 2.13%   |
| MediaTek WiFi                                                          | 1        | 2.13%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                     | 1        | 2.13%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 2.13%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 2.13%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]         | 1        | 2.13%   |
| Intel Wireless 7265                                                    | 1        | 2.13%   |
| Intel Wireless 7260                                                    | 1        | 2.13%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 2.13%   |
| Intel Centrino Wireless-N 2230                                         | 1        | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1        | 2.13%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                   | 1        | 2.13%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]               | 1        | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 52       | 45.22%  |
| Intel                     | 50       | 43.48%  |
| Broadcom                  | 4        | 3.48%   |
| Aquantia                  | 3        | 2.61%   |
| Marvell Technology Group  | 2        | 1.74%   |
| Spreadtrum Communications | 1        | 0.87%   |
| Solarflare Communications | 1        | 0.87%   |
| Mellanox Technologies     | 1        | 0.87%   |
| Davicom Semiconductor     | 1        | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 40       | 32.79%  |
| Realtek RTL8125 2.5GbE Controller                                              | 8        | 6.56%   |
| Intel I211 Gigabit Network Connection                                          | 8        | 6.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8        | 6.56%   |
| Intel Ethernet Controller I225-V                                               | 6        | 4.92%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 2.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 2.46%   |
| Intel Ethernet Connection (17) I219-V                                          | 3        | 2.46%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 2.46%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 2.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.64%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2        | 1.64%   |
| Intel Ethernet Controller X550                                                 | 2        | 1.64%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 1.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 1.64%   |
| Spreadtrum Unisoc Phone                                                        | 1        | 0.82%   |
| Solarflare SFC9020 10G Ethernet Controller                                     | 1        | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.82%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.82%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1        | 0.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.82%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1        | 0.82%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.82%   |
| Intel WiMAX Connection 2400m                                                   | 1        | 0.82%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.82%   |
| Intel I210 Gigabit Network Connection                                          | 1        | 0.82%   |
| Intel Ethernet Controller I226-V                                               | 1        | 0.82%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.82%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.82%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 0.82%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.82%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.82%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.82%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1        | 0.82%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 0.82%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.82%   |
| Intel 82578DC Gigabit Network Connection                                       | 1        | 0.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 1        | 0.82%   |
| Davicom DM9102 Fast Ethernet Controller                                        | 1        | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 70.07%  |
| WiFi     | 40       | 29.2%   |
| Modem    | 1        | 0.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 83.67%  |
| WiFi     | 16       | 16.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 51.02%  |
| 2     | 32       | 32.65%  |
| 3     | 11       | 11.22%  |
| 4     | 3        | 3.06%   |
| 5     | 2        | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 78.35%  |
| Yes  | 21       | 21.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 14       | 42.42%  |
| MediaTek                   | 5        | 15.15%  |
| Cambridge Silicon Radio    | 5        | 15.15%  |
| Realtek Semiconductor      | 2        | 6.06%   |
| Broadcom                   | 2        | 6.06%   |
| Ralink                     | 1        | 3.03%   |
| Integrated System Solution | 1        | 3.03%   |
| IMC Networks               | 1        | 3.03%   |
| Foxconn / Hon Hai          | 1        | 3.03%   |
| ASUSTek Computer           | 1        | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                              | 5        | 15.15%  |
| Intel Bluetooth wireless interface                    | 5        | 15.15%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 15.15%  |
| Intel AX200 Bluetooth                                 | 4        | 12.12%  |
| Intel AX210 Bluetooth                                 | 3        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 6.06%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 3.03%   |
| Realtek 802.11ac WLAN Adapter                         | 1        | 3.03%   |
| Ralink RT3290 Bluetooth                               | 1        | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 3.03%   |
| Intel AX211 Bluetooth                                 | 1        | 3.03%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 3.03%   |
| IMC Networks Bluetooth Device                         | 1        | 3.03%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 3.03%   |
| ASUS Bluetooth Radio                                  | 1        | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 60       | 37.27%  |
| Nvidia                | 42       | 26.09%  |
| AMD                   | 39       | 24.22%  |
| C-Media Electronics   | 4        | 2.48%   |
| Logitech              | 3        | 1.86%   |
| ASUSTek Computer      | 3        | 1.86%   |
| Texas Instruments     | 1        | 0.62%   |
| TEAC                  | 1        | 0.62%   |
| Setek Elektronik      | 1        | 0.62%   |
| Realtek Semiconductor | 1        | 0.62%   |
| Nektar                | 1        | 0.62%   |
| KTMicro               | 1        | 0.62%   |
| GYROCOM C&C           | 1        | 0.62%   |
| Creative Technology   | 1        | 0.62%   |
| Creative Labs         | 1        | 0.62%   |
| ASRock                | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 11       | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9        | 4.89%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 3.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 3.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 6        | 3.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5        | 2.72%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 2.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 2.72%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 2.17%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 2.17%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.63%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 1.63%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 1.63%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 1.63%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 1.63%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3        | 1.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 1.63%   |
| ASUSTek Computer USB Audio                                                        | 3        | 1.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.63%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2        | 1.09%   |
| Nvidia AD102 High Definition Audio Controller                                     | 2        | 1.09%   |
| Intel Raptor Lake High Definition Audio Controller                                | 2        | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 1.09%   |
| Intel Jasper Lake HD Audio                                                        | 2        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.09%   |
| C-Media Electronics USB PnP Audio Device                                          | 2        | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 1.09%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.09%   |
| AMD FCH Azalia Controller                                                         | 2        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 12       | 14.81%  |
| Corsair             | 12       | 14.81%  |
| Kingston            | 11       | 13.58%  |
| Unknown             | 8        | 9.88%   |
| Micron Technology   | 8        | 9.88%   |
| G.Skill             | 8        | 9.88%   |
| SK hynix            | 5        | 6.17%   |
| Crucial             | 4        | 4.94%   |
| Unknown             | 2        | 2.47%   |
| Team                | 1        | 1.23%   |
| PNY                 | 1        | 1.23%   |
| Patriot             | 1        | 1.23%   |
| Nanya Technology    | 1        | 1.23%   |
| Lexar               | 1        | 1.23%   |
| HPE                 | 1        | 1.23%   |
| Gold Key            | 1        | 1.23%   |
| Elpida              | 1        | 1.23%   |
| CUSO                | 1        | 1.23%   |
| Apacer              | 1        | 1.23%   |
| A-DATA Technology   | 1        | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s    | 2        | 2.38%   |
| Unknown                                                  | 2        | 2.38%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                | 1        | 1.19%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.19%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 1.19%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 1.19%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s           | 1        | 1.19%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 1.19%   |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 1.19%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s               | 1        | 1.19%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s     | 1        | 1.19%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s      | 1        | 1.19%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.19%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s              | 1        | 1.19%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.19%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s     | 1        | 1.19%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 1.19%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s   | 1        | 1.19%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s   | 1        | 1.19%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s | 1        | 1.19%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 1.19%   |
| Samsung RAM M386A4G40EM2-CRC 32GB DIMM DDR4 2400MT/s     | 1        | 1.19%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 1.19%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s    | 1        | 1.19%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 1        | 1.19%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 1.19%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3200MT/s     | 1        | 1.19%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s     | 1        | 1.19%   |
| Samsung RAM M323R4GA3BB0-CQKOD 32GB DIMM DDR5 3600MT/s   | 1        | 1.19%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s     | 1        | 1.19%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s         | 1        | 1.19%   |
| Nanya RAM NT8GC72B4NB1NK-CG 8GB DIMM DDR3 1333MT/s       | 1        | 1.19%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 1.19%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                 | 1        | 1.19%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s      | 1        | 1.19%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s       | 1        | 1.19%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s    | 1        | 1.19%   |
| Micron RAM 36KSZF1G72PZ-1G4D1 8GB DIMM DDR3 1333MT/s     | 1        | 1.19%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s     | 1        | 1.19%   |
| Micron RAM 16ATF4G64AZ-2G6E1 32GB DIMM DDR4 2667MT/s     | 1        | 1.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 56.52%  |
| DDR3    | 21       | 30.43%  |
| DDR5    | 6        | 8.7%    |
| DDR2    | 2        | 2.9%    |
| Unknown | 1        | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 57       | 82.61%  |
| SODIMM | 11       | 15.94%  |
| RIMM   | 1        | 1.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 21       | 28.38%  |
| 8192  | 19       | 25.68%  |
| 32768 | 14       | 18.92%  |
| 4096  | 13       | 17.57%  |
| 2048  | 4        | 5.41%   |
| 1024  | 3        | 4.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 12       | 15.38%  |
| 2667  | 11       | 14.1%   |
| 1600  | 8        | 10.26%  |
| 2133  | 7        | 8.97%   |
| 1333  | 7        | 8.97%   |
| 4800  | 4        | 5.13%   |
| 3600  | 4        | 5.13%   |
| 2400  | 4        | 5.13%   |
| 2666  | 3        | 3.85%   |
| 3933  | 2        | 2.56%   |
| 3534  | 2        | 2.56%   |
| 1800  | 2        | 2.56%   |
| 667   | 2        | 2.56%   |
| 5600  | 1        | 1.28%   |
| 3733  | 1        | 1.28%   |
| 3666  | 1        | 1.28%   |
| 3333  | 1        | 1.28%   |
| 3100  | 1        | 1.28%   |
| 3000  | 1        | 1.28%   |
| 2800  | 1        | 1.28%   |
| 2200  | 1        | 1.28%   |
| 2048  | 1        | 1.28%   |
| 1866  | 1        | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 50%     |
| Brother Industries | 2        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson XP-4100 Series    | 1        | 25%     |
| Seiko Epson Printer           | 1        | 25%     |
| Brother MFC-J435W             | 1        | 25%     |
| Brother HL-2030 Laser Printer | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP ScanJet 82x0C  | 1        | 50%     |
| HP OfficeJet 6110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 2        | 16.67%  |
| Logitech                      | 2        | 16.67%  |
| 2M UVC CAMERA                 | 2        | 16.67%  |
| Microdia                      | 1        | 8.33%   |
| MacroSilicon                  | 1        | 8.33%   |
| KYE Systems (Mouse Systems)   | 1        | 8.33%   |
| Huawei Technologies           | 1        | 8.33%   |
| Generalplus Technology        | 1        | 8.33%   |
| Elgato Systems                | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| 2M UVC CAMERA NexiGo N60 FHD Webcam       | 2        | 16.67%  |
| Sunplus Full HD webcam                    | 1        | 8.33%   |
| Sunplus FHD Camera                        | 1        | 8.33%   |
| Microdia Sonix USB 2.0 Camera             | 1        | 8.33%   |
| MacroSilicon MiraBox Capture              | 1        | 8.33%   |
| Logitech Webcam C270                      | 1        | 8.33%   |
| Logitech HD Pro Webcam C920               | 1        | 8.33%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 8.33%   |
| Huawei HiCamera                           | 1        | 8.33%   |
| Generalplus CAMERA - UVC                  | 1        | 8.33%   |
| Elgato Systems Elgato Facecam             | 1        | 8.33%   |

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
| 0     | 64       | 64.65%  |
| 1     | 24       | 24.24%  |
| 2     | 10       | 10.1%   |
| 3     | 1        | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 9        | 21.43%  |
| Graphics card            | 8        | 19.05%  |
| Unassigned class         | 4        | 9.52%   |
| Firewire controller      | 3        | 7.14%   |
| Storage/raid             | 2        | 4.76%   |
| Storage/ide              | 2        | 4.76%   |
| Sound                    | 2        | 4.76%   |
| Net/ethernet             | 2        | 4.76%   |
| Communication controller | 2        | 4.76%   |
| Storage/ata              | 1        | 2.38%   |
| Storage                  | 1        | 2.38%   |
| Network                  | 1        | 2.38%   |
| Multimedia controller    | 1        | 2.38%   |
| Modem                    | 1        | 2.38%   |
| Fingerprint reader       | 1        | 2.38%   |
| Dvb card                 | 1        | 2.38%   |
| Bluetooth                | 1        | 2.38%   |

