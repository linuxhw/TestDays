openSUSE Leap-15.5 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.5/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.5/Notebook/README.md).

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

Total: 540

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [4690fd028c](https://linux-hardware.org/?probe=4690fd028c) | Jan 01, 2025 |
| ASUSTek       | X751SA                      | Notebook    | [11d8d9b891](https://linux-hardware.org/?probe=11d8d9b891) | Dec 30, 2024 |
| ASUSTek       | X751SA                      | Notebook    | [2f216406f5](https://linux-hardware.org/?probe=2f216406f5) | Dec 28, 2024 |
| HP            | 2AF7                        | Desktop     | [86175be1e4](https://linux-hardware.org/?probe=86175be1e4) | Dec 25, 2024 |
| Dell          | Latitude 7400               | Notebook    | [79148dd5e2](https://linux-hardware.org/?probe=79148dd5e2) | Dec 14, 2024 |
| HP            | 2AF7                        | Desktop     | [7779a1d0a0](https://linux-hardware.org/?probe=7779a1d0a0) | Dec 11, 2024 |
| Dell          | Latitude 7400               | Notebook    | [77befeb4ea](https://linux-hardware.org/?probe=77befeb4ea) | Dec 09, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [cf504cfd50](https://linux-hardware.org/?probe=cf504cfd50) | Dec 05, 2024 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [170159c12d](https://linux-hardware.org/?probe=170159c12d) | Nov 22, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [775a4e3d49](https://linux-hardware.org/?probe=775a4e3d49) | Nov 17, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [cd9cf7bf34](https://linux-hardware.org/?probe=cd9cf7bf34) | Nov 17, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [37416e4e8a](https://linux-hardware.org/?probe=37416e4e8a) | Nov 12, 2024 |
| Medion        | E15433                      | Notebook    | [05ec29cd01](https://linux-hardware.org/?probe=05ec29cd01) | Nov 11, 2024 |
| Toshiba       | Satellite C55D-A            | Notebook    | [aa4ba3a227](https://linux-hardware.org/?probe=aa4ba3a227) | Nov 04, 2024 |
| Lenovo        | ThinkPad W520 4282A34       | Notebook    | [9c2a644e93](https://linux-hardware.org/?probe=9c2a644e93) | Nov 01, 2024 |
| Google        | Candy                       | Notebook    | [2ee49236e0](https://linux-hardware.org/?probe=2ee49236e0) | Oct 23, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [36aa1c57ca](https://linux-hardware.org/?probe=36aa1c57ca) | Oct 06, 2024 |
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [34c10e27fb](https://linux-hardware.org/?probe=34c10e27fb) | Oct 03, 2024 |
| HP            | 843B                        | Desktop     | [78e41c4cf2](https://linux-hardware.org/?probe=78e41c4cf2) | Oct 01, 2024 |
| Google        | Candy                       | Notebook    | [1fd06c93d2](https://linux-hardware.org/?probe=1fd06c93d2) | Sep 26, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [0767b12df1](https://linux-hardware.org/?probe=0767b12df1) | Sep 20, 2024 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [d012125c09](https://linux-hardware.org/?probe=d012125c09) | Sep 19, 2024 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [26254c11a6](https://linux-hardware.org/?probe=26254c11a6) | Sep 18, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [d4b48bd314](https://linux-hardware.org/?probe=d4b48bd314) | Sep 12, 2024 |
| Sony          | VPCEH11FX                   | Notebook    | [76b181ca5c](https://linux-hardware.org/?probe=76b181ca5c) | Sep 03, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [bdaf9d87ea](https://linux-hardware.org/?probe=bdaf9d87ea) | Sep 01, 2024 |
| Acer          | Nitro AN517-51              | Notebook    | [33ffbac3ac](https://linux-hardware.org/?probe=33ffbac3ac) | Aug 29, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ad8d4cea54](https://linux-hardware.org/?probe=ad8d4cea54) | Aug 26, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d11387efbf](https://linux-hardware.org/?probe=d11387efbf) | Aug 25, 2024 |
| Dell          | Precision 3541              | Notebook    | [1c2a5e45f3](https://linux-hardware.org/?probe=1c2a5e45f3) | Aug 21, 2024 |
| Toshiba       | Satellite R945              | Notebook    | [4e4ca76ccf](https://linux-hardware.org/?probe=4e4ca76ccf) | Aug 19, 2024 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [06658f76e8](https://linux-hardware.org/?probe=06658f76e8) | Aug 17, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [f414f9fb5b](https://linux-hardware.org/?probe=f414f9fb5b) | Aug 17, 2024 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [b0f6c21ecc](https://linux-hardware.org/?probe=b0f6c21ecc) | Aug 17, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [e91aed8d91](https://linux-hardware.org/?probe=e91aed8d91) | Aug 16, 2024 |
| Dell          | Precision 3541              | Notebook    | [c5f2dba49c](https://linux-hardware.org/?probe=c5f2dba49c) | Aug 13, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c670222db7](https://linux-hardware.org/?probe=c670222db7) | Aug 12, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [05d992d68b](https://linux-hardware.org/?probe=05d992d68b) | Aug 11, 2024 |
| Panasonic     | FZ40-1                      | Notebook    | [a8cf31fa9e](https://linux-hardware.org/?probe=a8cf31fa9e) | Aug 05, 2024 |
| Dell          | Latitude 7400               | Notebook    | [830e4194f2](https://linux-hardware.org/?probe=830e4194f2) | Aug 02, 2024 |
| MSI           | 760GM-P23                   | Desktop     | [a30c04cd45](https://linux-hardware.org/?probe=a30c04cd45) | Jul 28, 2024 |
| MSI           | X370 GAMING PLUS            | Desktop     | [d17fbd5101](https://linux-hardware.org/?probe=d17fbd5101) | Jul 28, 2024 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [83394cc331](https://linux-hardware.org/?probe=83394cc331) | Jul 24, 2024 |
| Dell          | Latitude 5320               | Notebook    | [937747e0cd](https://linux-hardware.org/?probe=937747e0cd) | Jul 24, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [d32f73f43c](https://linux-hardware.org/?probe=d32f73f43c) | Jul 24, 2024 |
| Dell          | Latitude E6510              | Notebook    | [7bdf8e1d08](https://linux-hardware.org/?probe=7bdf8e1d08) | Jul 18, 2024 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [c61e819173](https://linux-hardware.org/?probe=c61e819173) | Jul 16, 2024 |
| Acer          | WG43M                       | Desktop     | [0a5383935d](https://linux-hardware.org/?probe=0a5383935d) | Jul 07, 2024 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [bf21f420fb](https://linux-hardware.org/?probe=bf21f420fb) | Jul 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [cc7fb9a2cc](https://linux-hardware.org/?probe=cc7fb9a2cc) | Jun 28, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [5e5b324a08](https://linux-hardware.org/?probe=5e5b324a08) | Jun 27, 2024 |
| Acer          | Aspire E1-571               | Notebook    | [554884bafe](https://linux-hardware.org/?probe=554884bafe) | Jun 23, 2024 |
| HP            | ENVY 14                     | Notebook    | [c0be266fe2](https://linux-hardware.org/?probe=c0be266fe2) | Jun 18, 2024 |
| HP            | ENVY 14                     | Notebook    | [0838fecf0e](https://linux-hardware.org/?probe=0838fecf0e) | Jun 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [9c9c84de42](https://linux-hardware.org/?probe=9c9c84de42) | Jun 17, 2024 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [f57172b283](https://linux-hardware.org/?probe=f57172b283) | Jun 16, 2024 |
| Dell          | 0HMF7C A01                  | Desktop     | [fbb14e1d17](https://linux-hardware.org/?probe=fbb14e1d17) | Jun 16, 2024 |
| Raspberry ... | rpi                         | Soc         | [8319138d81](https://linux-hardware.org/?probe=8319138d81) | Jun 15, 2024 |
| HP            | ENVY Laptop 17-ae1xx        | Notebook    | [e3e68fbf69](https://linux-hardware.org/?probe=e3e68fbf69) | Jun 15, 2024 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [c9edb14972](https://linux-hardware.org/?probe=c9edb14972) | Jun 13, 2024 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [920d747441](https://linux-hardware.org/?probe=920d747441) | Jun 13, 2024 |
| Gigabyte      | G31M-S2L                    | Desktop     | [c73c94191f](https://linux-hardware.org/?probe=c73c94191f) | Jun 13, 2024 |
| HP            | 212A                        | Desktop     | [3372b6a1ed](https://linux-hardware.org/?probe=3372b6a1ed) | Jun 13, 2024 |
| Wortmann      | TERRA_MOBILE_1512/1712      | Notebook    | [925af4ca04](https://linux-hardware.org/?probe=925af4ca04) | Jun 11, 2024 |
| Wortmann      | TERRA_MOBILE_1512/1712      | Notebook    | [b80c7ef54c](https://linux-hardware.org/?probe=b80c7ef54c) | Jun 11, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c9b9a5f54b](https://linux-hardware.org/?probe=c9b9a5f54b) | Jun 10, 2024 |
| ASRock        | Z270M Pro4                  | Desktop     | [5e30fab9b5](https://linux-hardware.org/?probe=5e30fab9b5) | Jun 10, 2024 |
| Acer          | WG43M                       | Desktop     | [1b1aaf3187](https://linux-hardware.org/?probe=1b1aaf3187) | Jun 08, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [39216d7b67](https://linux-hardware.org/?probe=39216d7b67) | Jun 06, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [bd8df104f0](https://linux-hardware.org/?probe=bd8df104f0) | Jun 06, 2024 |
| ASRock        | EP2C602-2L+/D16             | Desktop     | [71b56e0c28](https://linux-hardware.org/?probe=71b56e0c28) | Jun 05, 2024 |
| Dell          | 0JP3NX A00                  | Desktop     | [db67c945b8](https://linux-hardware.org/?probe=db67c945b8) | Jun 05, 2024 |
| MSI           | MS-B0A81                    | Desktop     | [fd136a4700](https://linux-hardware.org/?probe=fd136a4700) | Jun 05, 2024 |
| ASRock        | H270 Pro4                   | Desktop     | [c180147c81](https://linux-hardware.org/?probe=c180147c81) | Jun 03, 2024 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [7fa8ee163f](https://linux-hardware.org/?probe=7fa8ee163f) | Jun 03, 2024 |
| LG Electro... | P1-J331P                    | Notebook    | [a24862e047](https://linux-hardware.org/?probe=a24862e047) | Jun 02, 2024 |
| LG Electro... | P1-J331P                    | Notebook    | [948cbb9a59](https://linux-hardware.org/?probe=948cbb9a59) | Jun 02, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [d18a7ae343](https://linux-hardware.org/?probe=d18a7ae343) | May 31, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [ed38e31a5a](https://linux-hardware.org/?probe=ed38e31a5a) | May 31, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ce453ef020](https://linux-hardware.org/?probe=ce453ef020) | May 30, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [54446d7877](https://linux-hardware.org/?probe=54446d7877) | May 28, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [14a14a76f1](https://linux-hardware.org/?probe=14a14a76f1) | May 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [aa9d0999c0](https://linux-hardware.org/?probe=aa9d0999c0) | May 26, 2024 |
| Dell          | Precision 7510              | Notebook    | [2732302a98](https://linux-hardware.org/?probe=2732302a98) | May 23, 2024 |
| Dell          | Precision 7510              | Notebook    | [f1f16c7457](https://linux-hardware.org/?probe=f1f16c7457) | May 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [68262266cc](https://linux-hardware.org/?probe=68262266cc) | May 23, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [a2e639d9d5](https://linux-hardware.org/?probe=a2e639d9d5) | May 23, 2024 |
| Biostar       | TA970                       | Desktop     | [80334f21f5](https://linux-hardware.org/?probe=80334f21f5) | May 21, 2024 |
| Intel         | H61                         | Desktop     | [82eb95baf1](https://linux-hardware.org/?probe=82eb95baf1) | May 19, 2024 |
| Acer          | WG43M                       | Desktop     | [47875247e5](https://linux-hardware.org/?probe=47875247e5) | May 19, 2024 |
| HP            | 8054                        | Desktop     | [8a38a141d6](https://linux-hardware.org/?probe=8a38a141d6) | May 17, 2024 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [e1d78ae74f](https://linux-hardware.org/?probe=e1d78ae74f) | May 17, 2024 |
| Intel         | H61                         | Desktop     | [7e84e54543](https://linux-hardware.org/?probe=7e84e54543) | May 17, 2024 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [faac458723](https://linux-hardware.org/?probe=faac458723) | May 15, 2024 |
| ASRock        | 890GX Pro3                  | Desktop     | [24eb48fe3d](https://linux-hardware.org/?probe=24eb48fe3d) | May 15, 2024 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [97f3382524](https://linux-hardware.org/?probe=97f3382524) | May 14, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [5fd4014ac6](https://linux-hardware.org/?probe=5fd4014ac6) | May 14, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [1cb4d4b3d8](https://linux-hardware.org/?probe=1cb4d4b3d8) | May 13, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0dd0acc11c](https://linux-hardware.org/?probe=0dd0acc11c) | May 13, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [33cbfbce5d](https://linux-hardware.org/?probe=33cbfbce5d) | May 13, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [18aa30f5dc](https://linux-hardware.org/?probe=18aa30f5dc) | May 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [fce74afc84](https://linux-hardware.org/?probe=fce74afc84) | May 09, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [85dee8d963](https://linux-hardware.org/?probe=85dee8d963) | May 07, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [42a7c6fb23](https://linux-hardware.org/?probe=42a7c6fb23) | May 06, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [3fafaee792](https://linux-hardware.org/?probe=3fafaee792) | May 05, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ed934b8b61](https://linux-hardware.org/?probe=ed934b8b61) | May 05, 2024 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a1541c5122](https://linux-hardware.org/?probe=a1541c5122) | May 02, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [9c08740bb5](https://linux-hardware.org/?probe=9c08740bb5) | May 02, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [8a00241444](https://linux-hardware.org/?probe=8a00241444) | May 01, 2024 |
| Medion        | P662X                       | Notebook    | [3689ca2476](https://linux-hardware.org/?probe=3689ca2476) | May 01, 2024 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [cdfcbe795b](https://linux-hardware.org/?probe=cdfcbe795b) | May 01, 2024 |
| Dell          | Inspiron 5748               | Notebook    | [43d176db3e](https://linux-hardware.org/?probe=43d176db3e) | Apr 29, 2024 |
| Acer          | Aspire 7741                 | Notebook    | [69f109864f](https://linux-hardware.org/?probe=69f109864f) | Apr 28, 2024 |
| Lenovo        | ThinkPad L520 786035U       | Notebook    | [711272241a](https://linux-hardware.org/?probe=711272241a) | Apr 28, 2024 |
| ASUSTek       | N751JK                      | Notebook    | [1d2d8c3d7a](https://linux-hardware.org/?probe=1d2d8c3d7a) | Apr 25, 2024 |
| Lenovo        | U31-70 80M5                 | Notebook    | [2a4ad09169](https://linux-hardware.org/?probe=2a4ad09169) | Apr 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [ec99c46757](https://linux-hardware.org/?probe=ec99c46757) | Apr 25, 2024 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [8f95604689](https://linux-hardware.org/?probe=8f95604689) | Apr 24, 2024 |
| HP            | 158B                        | Desktop     | [38acb31ca9](https://linux-hardware.org/?probe=38acb31ca9) | Apr 24, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [a35bd4ad42](https://linux-hardware.org/?probe=a35bd4ad42) | Apr 23, 2024 |
| Biostar       | A960D+V2                    | Desktop     | [e6d3b07d8e](https://linux-hardware.org/?probe=e6d3b07d8e) | Apr 23, 2024 |
| ASRock        | Z790 PG SONIC               | Desktop     | [6426fb59eb](https://linux-hardware.org/?probe=6426fb59eb) | Apr 22, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [8b5161f4ab](https://linux-hardware.org/?probe=8b5161f4ab) | Apr 22, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0247606ff3](https://linux-hardware.org/?probe=0247606ff3) | Apr 21, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [cf7eac1515](https://linux-hardware.org/?probe=cf7eac1515) | Apr 21, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [542fb126b0](https://linux-hardware.org/?probe=542fb126b0) | Apr 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8cff3fe858](https://linux-hardware.org/?probe=8cff3fe858) | Apr 20, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [8a42c0cd30](https://linux-hardware.org/?probe=8a42c0cd30) | Apr 18, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e7bc6ac35e](https://linux-hardware.org/?probe=e7bc6ac35e) | Apr 17, 2024 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [f14f8b8b13](https://linux-hardware.org/?probe=f14f8b8b13) | Apr 17, 2024 |
| ASUSTek       | N751JK                      | Notebook    | [39bb3da888](https://linux-hardware.org/?probe=39bb3da888) | Apr 16, 2024 |
| Gigabyte      | P55-UD5                     | Desktop     | [736814c1df](https://linux-hardware.org/?probe=736814c1df) | Apr 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [b29f521f01](https://linux-hardware.org/?probe=b29f521f01) | Apr 12, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME      | Desktop     | [fb483fb3bc](https://linux-hardware.org/?probe=fb483fb3bc) | Apr 10, 2024 |
| HP            | EliteBook 2730p             | Notebook    | [843cd11924](https://linux-hardware.org/?probe=843cd11924) | Apr 10, 2024 |
| Fujitsu       | CELSIUS H780                | Notebook    | [f5dc0c7623](https://linux-hardware.org/?probe=f5dc0c7623) | Apr 10, 2024 |
| Dell          | Precision M4800             | Notebook    | [e0cd62ded2](https://linux-hardware.org/?probe=e0cd62ded2) | Apr 10, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [75b15c6330](https://linux-hardware.org/?probe=75b15c6330) | Apr 09, 2024 |
| Dell          | Precision 3561              | Notebook    | [6bc6a2a9d9](https://linux-hardware.org/?probe=6bc6a2a9d9) | Apr 09, 2024 |
| Dell          | Latitude E7240              | Notebook    | [08dd3e8b44](https://linux-hardware.org/?probe=08dd3e8b44) | Apr 09, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME      | Desktop     | [0de5191161](https://linux-hardware.org/?probe=0de5191161) | Apr 08, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ea4485f45b](https://linux-hardware.org/?probe=ea4485f45b) | Apr 08, 2024 |
| HP            | ProLiant ML350 G6           | Desktop     | [3a9aaf0732](https://linux-hardware.org/?probe=3a9aaf0732) | Apr 07, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [92dd5d1690](https://linux-hardware.org/?probe=92dd5d1690) | Apr 07, 2024 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [3c1bd6247c](https://linux-hardware.org/?probe=3c1bd6247c) | Apr 06, 2024 |
| HP            | 3048h                       | Desktop     | [98a7ae878b](https://linux-hardware.org/?probe=98a7ae878b) | Apr 06, 2024 |
| HP            | ProLiant ML350 G6           | Desktop     | [d70516fc56](https://linux-hardware.org/?probe=d70516fc56) | Apr 06, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e009d9dd56](https://linux-hardware.org/?probe=e009d9dd56) | Apr 05, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [05643228c4](https://linux-hardware.org/?probe=05643228c4) | Apr 02, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bb4170e7fc](https://linux-hardware.org/?probe=bb4170e7fc) | Apr 01, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9dc48f27f9](https://linux-hardware.org/?probe=9dc48f27f9) | Apr 01, 2024 |
| Gigabyte      | EP35-DS3                    | Desktop     | [3d93a78c1b](https://linux-hardware.org/?probe=3d93a78c1b) | Mar 31, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [cf27d76a8a](https://linux-hardware.org/?probe=cf27d76a8a) | Mar 29, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [21456be41e](https://linux-hardware.org/?probe=21456be41e) | Mar 26, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [b9faafe90e](https://linux-hardware.org/?probe=b9faafe90e) | Mar 25, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [233178d530](https://linux-hardware.org/?probe=233178d530) | Mar 25, 2024 |
| GEEKOM        | Mini IT11                   | Desktop     | [959133190b](https://linux-hardware.org/?probe=959133190b) | Mar 24, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [8fa61ae34a](https://linux-hardware.org/?probe=8fa61ae34a) | Mar 24, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [d3e9088b43](https://linux-hardware.org/?probe=d3e9088b43) | Mar 23, 2024 |
| Dell          | 0272WF A00                  | Server      | [ecb7c501fd](https://linux-hardware.org/?probe=ecb7c501fd) | Mar 23, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [36c66318b0](https://linux-hardware.org/?probe=36c66318b0) | Mar 22, 2024 |
| Dell          | 0M9KCM A02                  | Desktop     | [e612c937ca](https://linux-hardware.org/?probe=e612c937ca) | Mar 22, 2024 |
| ASRock        | Z790 Riptide WiFi           | Desktop     | [a03071be8b](https://linux-hardware.org/?probe=a03071be8b) | Mar 21, 2024 |
| ASRock        | Z790 Riptide WiFi           | Desktop     | [b8d5bc7323](https://linux-hardware.org/?probe=b8d5bc7323) | Mar 21, 2024 |
| ASRock        | B560 Pro4                   | Desktop     | [a34877f66c](https://linux-hardware.org/?probe=a34877f66c) | Mar 21, 2024 |
| Dell          | Precision 5520              | Notebook    | [8d942977e2](https://linux-hardware.org/?probe=8d942977e2) | Mar 20, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4d9cfcc0fb](https://linux-hardware.org/?probe=4d9cfcc0fb) | Mar 19, 2024 |
| ASUSTek       | Pro WS W680-ACE             | Desktop     | [c1ef51d3b0](https://linux-hardware.org/?probe=c1ef51d3b0) | Mar 19, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [153f16ac8d](https://linux-hardware.org/?probe=153f16ac8d) | Mar 18, 2024 |
| Acer          | Aspire 5745                 | Notebook    | [512b58fc90](https://linux-hardware.org/?probe=512b58fc90) | Mar 16, 2024 |
| Dell          | 0272WF A00                  | Server      | [5399f81241](https://linux-hardware.org/?probe=5399f81241) | Mar 15, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [174ace72e6](https://linux-hardware.org/?probe=174ace72e6) | Mar 15, 2024 |
| HP            | 2B29                        | Desktop     | [0db8d7c93c](https://linux-hardware.org/?probe=0db8d7c93c) | Mar 13, 2024 |
| Schenker      | KEY (E23)                   | Notebook    | [f555bec75a](https://linux-hardware.org/?probe=f555bec75a) | Mar 12, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [1e7f921f12](https://linux-hardware.org/?probe=1e7f921f12) | Mar 12, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [21d3f26046](https://linux-hardware.org/?probe=21d3f26046) | Mar 12, 2024 |
| Acer          | TravelMate P215-54          | Notebook    | [a8e5c041ef](https://linux-hardware.org/?probe=a8e5c041ef) | Mar 11, 2024 |
| ASUSTek       | P8B75-V                     | Desktop     | [6529cfcd8e](https://linux-hardware.org/?probe=6529cfcd8e) | Mar 11, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [4b83d77529](https://linux-hardware.org/?probe=4b83d77529) | Mar 10, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9793665868](https://linux-hardware.org/?probe=9793665868) | Mar 08, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [66f2f3a361](https://linux-hardware.org/?probe=66f2f3a361) | Mar 04, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [3ab9b49b3e](https://linux-hardware.org/?probe=3ab9b49b3e) | Mar 04, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [97c41f0fd8](https://linux-hardware.org/?probe=97c41f0fd8) | Mar 04, 2024 |
| MSI           | Katana GF66 11UE            | Notebook    | [95b3dd2821](https://linux-hardware.org/?probe=95b3dd2821) | Mar 03, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [548005c028](https://linux-hardware.org/?probe=548005c028) | Mar 02, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [146b43cf79](https://linux-hardware.org/?probe=146b43cf79) | Mar 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [8464bee9a7](https://linux-hardware.org/?probe=8464bee9a7) | Feb 29, 2024 |
| HP            | 3031h                       | Desktop     | [7f8ca0e8e8](https://linux-hardware.org/?probe=7f8ca0e8e8) | Feb 29, 2024 |
| Acer          | Aspire 5742Z                | Notebook    | [22ba0ca014](https://linux-hardware.org/?probe=22ba0ca014) | Feb 29, 2024 |
| HP            | Pavilion dv9500             | Notebook    | [233bd911e6](https://linux-hardware.org/?probe=233bd911e6) | Feb 28, 2024 |
| Lenovo        | ThinkPad L530 24814YG       | Notebook    | [41599a23c0](https://linux-hardware.org/?probe=41599a23c0) | Feb 28, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2934279a7d](https://linux-hardware.org/?probe=2934279a7d) | Feb 28, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cc59cfab4f](https://linux-hardware.org/?probe=cc59cfab4f) | Feb 27, 2024 |
| HP            | Pavilion dv9500             | Notebook    | [8c5ec97398](https://linux-hardware.org/?probe=8c5ec97398) | Feb 27, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [cded833645](https://linux-hardware.org/?probe=cded833645) | Feb 25, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [85f840ba85](https://linux-hardware.org/?probe=85f840ba85) | Feb 24, 2024 |
| ASUSTek       | X751LX                      | Notebook    | [702ddba05b](https://linux-hardware.org/?probe=702ddba05b) | Feb 24, 2024 |
| Dell          | 0J3C2F A02                  | Desktop     | [e757c4ef0c](https://linux-hardware.org/?probe=e757c4ef0c) | Feb 21, 2024 |
| HP            | Laptop 17z-ca200            | Notebook    | [1dbf9d63d5](https://linux-hardware.org/?probe=1dbf9d63d5) | Feb 21, 2024 |
| ASUSTek       | A68HM-K                     | Desktop     | [5ba603ce75](https://linux-hardware.org/?probe=5ba603ce75) | Feb 21, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [3e89cd8ab4](https://linux-hardware.org/?probe=3e89cd8ab4) | Feb 19, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [aa4c2879d1](https://linux-hardware.org/?probe=aa4c2879d1) | Feb 13, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [748b126968](https://linux-hardware.org/?probe=748b126968) | Feb 12, 2024 |
| Dell          | 0C522T A01                  | Desktop     | [aa4b8ca306](https://linux-hardware.org/?probe=aa4b8ca306) | Feb 12, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [f72f15f296](https://linux-hardware.org/?probe=f72f15f296) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d916f30fdc](https://linux-hardware.org/?probe=d916f30fdc) | Feb 10, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [f4930d0549](https://linux-hardware.org/?probe=f4930d0549) | Feb 09, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c8567d0dcc](https://linux-hardware.org/?probe=c8567d0dcc) | Feb 06, 2024 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [8d65745585](https://linux-hardware.org/?probe=8d65745585) | Feb 05, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [91197e4fa0](https://linux-hardware.org/?probe=91197e4fa0) | Feb 05, 2024 |
| ASRock        | B75 Pro3                    | Desktop     | [d15b9f0cc9](https://linux-hardware.org/?probe=d15b9f0cc9) | Feb 04, 2024 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [7955c56c67](https://linux-hardware.org/?probe=7955c56c67) | Jan 29, 2024 |
| HP            | ProLiant ML10 v2            | Desktop     | [b16f323611](https://linux-hardware.org/?probe=b16f323611) | Jan 28, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [d41cb5632c](https://linux-hardware.org/?probe=d41cb5632c) | Jan 28, 2024 |
| Acer          | Aspire A317-32              | Notebook    | [9baf9646df](https://linux-hardware.org/?probe=9baf9646df) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 20RAS1S600     | Notebook    | [8544584b30](https://linux-hardware.org/?probe=8544584b30) | Jan 27, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [af91485fb2](https://linux-hardware.org/?probe=af91485fb2) | Jan 25, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [343af19ed9](https://linux-hardware.org/?probe=343af19ed9) | Jan 24, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6dd363b754](https://linux-hardware.org/?probe=6dd363b754) | Jan 22, 2024 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [f3a19638cd](https://linux-hardware.org/?probe=f3a19638cd) | Jan 21, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [195dbfe0e7](https://linux-hardware.org/?probe=195dbfe0e7) | Jan 20, 2024 |
| Dell          | Latitude E6400              | Notebook    | [b2765b0e50](https://linux-hardware.org/?probe=b2765b0e50) | Jan 19, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9bed697ae6](https://linux-hardware.org/?probe=9bed697ae6) | Jan 18, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d0f45c11a7](https://linux-hardware.org/?probe=d0f45c11a7) | Jan 18, 2024 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [28a227c7d1](https://linux-hardware.org/?probe=28a227c7d1) | Jan 16, 2024 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [1ec6103b31](https://linux-hardware.org/?probe=1ec6103b31) | Jan 16, 2024 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [96e3e7f937](https://linux-hardware.org/?probe=96e3e7f937) | Jan 16, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c2c3082933](https://linux-hardware.org/?probe=c2c3082933) | Jan 16, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [b082a9bd9f](https://linux-hardware.org/?probe=b082a9bd9f) | Jan 14, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [4dc1a2b98c](https://linux-hardware.org/?probe=4dc1a2b98c) | Jan 11, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [088dbf4c2f](https://linux-hardware.org/?probe=088dbf4c2f) | Jan 10, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [6cf5d66e62](https://linux-hardware.org/?probe=6cf5d66e62) | Jan 10, 2024 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [0dff2ac4a3](https://linux-hardware.org/?probe=0dff2ac4a3) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2e0223d4eb](https://linux-hardware.org/?probe=2e0223d4eb) | Jan 09, 2024 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [dc1999f5b3](https://linux-hardware.org/?probe=dc1999f5b3) | Jan 09, 2024 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5d90ffe9df](https://linux-hardware.org/?probe=5d90ffe9df) | Jan 09, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [0e9f707dea](https://linux-hardware.org/?probe=0e9f707dea) | Jan 06, 2024 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [a304de1339](https://linux-hardware.org/?probe=a304de1339) | Jan 06, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e340939ad8](https://linux-hardware.org/?probe=e340939ad8) | Jan 06, 2024 |
| Acer          | Aspire A317-32              | Notebook    | [806a8b59fb](https://linux-hardware.org/?probe=806a8b59fb) | Jan 05, 2024 |
| HP            | 8AB6 SMVB                   | Desktop     | [b846966b99](https://linux-hardware.org/?probe=b846966b99) | Jan 04, 2024 |
| ASUSTek       | UX510UXK                    | Notebook    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [1504d9c050](https://linux-hardware.org/?probe=1504d9c050) | Jan 03, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [b7d97486fb](https://linux-hardware.org/?probe=b7d97486fb) | Jan 01, 2024 |
| Samsung       | 730QFG                      | Convertible | [3cb8ce6daf](https://linux-hardware.org/?probe=3cb8ce6daf) | Dec 30, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [0c56a0465b](https://linux-hardware.org/?probe=0c56a0465b) | Dec 29, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [7b5d790450](https://linux-hardware.org/?probe=7b5d790450) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [16a5247446](https://linux-hardware.org/?probe=16a5247446) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [82f94ea967](https://linux-hardware.org/?probe=82f94ea967) | Dec 28, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [cb215ce5f6](https://linux-hardware.org/?probe=cb215ce5f6) | Dec 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [2b312f609c](https://linux-hardware.org/?probe=2b312f609c) | Dec 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [626b056720](https://linux-hardware.org/?probe=626b056720) | Dec 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [a271d8355d](https://linux-hardware.org/?probe=a271d8355d) | Dec 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d12d3a2f21](https://linux-hardware.org/?probe=d12d3a2f21) | Dec 23, 2023 |
| Dell          | System XPS L322X            | Notebook    | [6b050ff1c8](https://linux-hardware.org/?probe=6b050ff1c8) | Dec 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [51cee07e16](https://linux-hardware.org/?probe=51cee07e16) | Dec 22, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [f8215b7e03](https://linux-hardware.org/?probe=f8215b7e03) | Dec 21, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [476ef9075c](https://linux-hardware.org/?probe=476ef9075c) | Dec 21, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [e0b9ef0f5e](https://linux-hardware.org/?probe=e0b9ef0f5e) | Dec 18, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [e83b933182](https://linux-hardware.org/?probe=e83b933182) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [7e2afccdd6](https://linux-hardware.org/?probe=7e2afccdd6) | Dec 18, 2023 |
| System76      | Bonobo WS                   | Notebook    | [22f5ef6fce](https://linux-hardware.org/?probe=22f5ef6fce) | Dec 16, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b949261978](https://linux-hardware.org/?probe=b949261978) | Dec 13, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [d2c14973f1](https://linux-hardware.org/?probe=d2c14973f1) | Dec 10, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1e3585333b](https://linux-hardware.org/?probe=1e3585333b) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| HP            | Compaq 515                  | Notebook    | [025d4116ed](https://linux-hardware.org/?probe=025d4116ed) | Dec 09, 2023 |
| HP            | 3397                        | Desktop     | [f840ce3d4e](https://linux-hardware.org/?probe=f840ce3d4e) | Dec 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3cdaec0eab](https://linux-hardware.org/?probe=3cdaec0eab) | Dec 07, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9d717185fb](https://linux-hardware.org/?probe=9d717185fb) | Dec 07, 2023 |
| Dell          | 0GM819                      | Desktop     | [8ff7ec90b2](https://linux-hardware.org/?probe=8ff7ec90b2) | Dec 05, 2023 |
| Intel         | S1200RP G62254-407          | Server      | [7db1ebe060](https://linux-hardware.org/?probe=7db1ebe060) | Dec 05, 2023 |
| AMI           | Intel                       | Desktop     | [7fdef1f7fc](https://linux-hardware.org/?probe=7fdef1f7fc) | Dec 04, 2023 |
| HP            | Notebook                    | Notebook    | [0a554c91b1](https://linux-hardware.org/?probe=0a554c91b1) | Dec 01, 2023 |
| ASUSTek       | M4A88T-M LE                 | Desktop     | [a2f1655886](https://linux-hardware.org/?probe=a2f1655886) | Dec 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [4ba2fc285f](https://linux-hardware.org/?probe=4ba2fc285f) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [0f9a06cc9f](https://linux-hardware.org/?probe=0f9a06cc9f) | Nov 30, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9accd13cb5](https://linux-hardware.org/?probe=9accd13cb5) | Nov 30, 2023 |
| HP            | Notebook                    | Notebook    | [93464a0904](https://linux-hardware.org/?probe=93464a0904) | Nov 30, 2023 |
| ASUSTek       | M4A88T-M LE                 | Desktop     | [1e982d5ac9](https://linux-hardware.org/?probe=1e982d5ac9) | Nov 30, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [f6e7c5e8a3](https://linux-hardware.org/?probe=f6e7c5e8a3) | Nov 29, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [02b205724a](https://linux-hardware.org/?probe=02b205724a) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [1eda316922](https://linux-hardware.org/?probe=1eda316922) | Nov 28, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b46ec04a69](https://linux-hardware.org/?probe=b46ec04a69) | Nov 27, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d3122d678f](https://linux-hardware.org/?probe=d3122d678f) | Nov 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [84e4d06443](https://linux-hardware.org/?probe=84e4d06443) | Nov 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [312776837c](https://linux-hardware.org/?probe=312776837c) | Nov 26, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [8104fc2789](https://linux-hardware.org/?probe=8104fc2789) | Nov 26, 2023 |
| HP            | 212B                        | Desktop     | [90bc0d4d2d](https://linux-hardware.org/?probe=90bc0d4d2d) | Nov 25, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [c4895d59da](https://linux-hardware.org/?probe=c4895d59da) | Nov 23, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [50eb6f63d8](https://linux-hardware.org/?probe=50eb6f63d8) | Nov 23, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [052c9cc626](https://linux-hardware.org/?probe=052c9cc626) | Nov 23, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [1ec9d0635f](https://linux-hardware.org/?probe=1ec9d0635f) | Nov 23, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [718e30ca5e](https://linux-hardware.org/?probe=718e30ca5e) | Nov 22, 2023 |
| System76      | Lemur Pro                   | Notebook    | [45a6298cb5](https://linux-hardware.org/?probe=45a6298cb5) | Nov 22, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [1d8de35042](https://linux-hardware.org/?probe=1d8de35042) | Nov 21, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [4949cbc96a](https://linux-hardware.org/?probe=4949cbc96a) | Nov 19, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [36ce4210e3](https://linux-hardware.org/?probe=36ce4210e3) | Nov 19, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [a6392d3aae](https://linux-hardware.org/?probe=a6392d3aae) | Nov 19, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [5cdf728f08](https://linux-hardware.org/?probe=5cdf728f08) | Nov 15, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9fc66b4436](https://linux-hardware.org/?probe=9fc66b4436) | Nov 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [d169a02b18](https://linux-hardware.org/?probe=d169a02b18) | Nov 14, 2023 |
| Dell          | Latitude E6410              | Notebook    | [1e9606e755](https://linux-hardware.org/?probe=1e9606e755) | Nov 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [383553241b](https://linux-hardware.org/?probe=383553241b) | Nov 14, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [474f3dea0b](https://linux-hardware.org/?probe=474f3dea0b) | Nov 13, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6406ede8d4](https://linux-hardware.org/?probe=6406ede8d4) | Nov 11, 2023 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [161674ce4a](https://linux-hardware.org/?probe=161674ce4a) | Nov 10, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9222374410](https://linux-hardware.org/?probe=9222374410) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [e736653169](https://linux-hardware.org/?probe=e736653169) | Nov 08, 2023 |
| Lenovo        | ThinkPad W541 20EGS1LB00    | Notebook    | [7a31e185b9](https://linux-hardware.org/?probe=7a31e185b9) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [1c86a5a6de](https://linux-hardware.org/?probe=1c86a5a6de) | Nov 05, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [1a9eef3748](https://linux-hardware.org/?probe=1a9eef3748) | Nov 02, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [9893d57e1b](https://linux-hardware.org/?probe=9893d57e1b) | Nov 01, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [b254c30981](https://linux-hardware.org/?probe=b254c30981) | Nov 01, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [c8ba0de51d](https://linux-hardware.org/?probe=c8ba0de51d) | Oct 31, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [fa410ee23c](https://linux-hardware.org/?probe=fa410ee23c) | Oct 29, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [16417bdac2](https://linux-hardware.org/?probe=16417bdac2) | Oct 29, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [33d021b931](https://linux-hardware.org/?probe=33d021b931) | Oct 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [ae8894002e](https://linux-hardware.org/?probe=ae8894002e) | Oct 27, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [0990fc4382](https://linux-hardware.org/?probe=0990fc4382) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434FL             | Notebook    | [139d1a74ed](https://linux-hardware.org/?probe=139d1a74ed) | Oct 25, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [b615345fa6](https://linux-hardware.org/?probe=b615345fa6) | Oct 21, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [75f2f0b411](https://linux-hardware.org/?probe=75f2f0b411) | Oct 21, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [572daeb059](https://linux-hardware.org/?probe=572daeb059) | Oct 19, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [398445f93d](https://linux-hardware.org/?probe=398445f93d) | Oct 14, 2023 |
| HP            | ProBook 4535s               | Notebook    | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | Desktop     | [e550587c85](https://linux-hardware.org/?probe=e550587c85) | Oct 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [729234c285](https://linux-hardware.org/?probe=729234c285) | Oct 14, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [56b055ab70](https://linux-hardware.org/?probe=56b055ab70) | Oct 12, 2023 |
| HP            | 3048h                       | Desktop     | [79350e657a](https://linux-hardware.org/?probe=79350e657a) | Oct 12, 2023 |
| Lenovo        | ThinkPad T400 27658JG       | Notebook    | [3b3b7832c9](https://linux-hardware.org/?probe=3b3b7832c9) | Oct 11, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [5e8749954f](https://linux-hardware.org/?probe=5e8749954f) | Oct 11, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [8b9a5127c0](https://linux-hardware.org/?probe=8b9a5127c0) | Oct 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [9ff3f35842](https://linux-hardware.org/?probe=9ff3f35842) | Oct 11, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4c0b8f71c3](https://linux-hardware.org/?probe=4c0b8f71c3) | Oct 10, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [541d9a0542](https://linux-hardware.org/?probe=541d9a0542) | Oct 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [c98952b2ee](https://linux-hardware.org/?probe=c98952b2ee) | Oct 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [5d51aca6b2](https://linux-hardware.org/?probe=5d51aca6b2) | Oct 08, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [9beb6f3b26](https://linux-hardware.org/?probe=9beb6f3b26) | Oct 08, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [4f2f37c5ba](https://linux-hardware.org/?probe=4f2f37c5ba) | Oct 08, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [f6fc0aee5b](https://linux-hardware.org/?probe=f6fc0aee5b) | Oct 07, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [c0c10b1767](https://linux-hardware.org/?probe=c0c10b1767) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7d321bffa1](https://linux-hardware.org/?probe=7d321bffa1) | Oct 07, 2023 |
| Dell          | Precision M6500             | Notebook    | [18605f38d4](https://linux-hardware.org/?probe=18605f38d4) | Oct 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ab02b2a3e7](https://linux-hardware.org/?probe=ab02b2a3e7) | Oct 04, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | Notebook    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [d6c281a706](https://linux-hardware.org/?probe=d6c281a706) | Oct 01, 2023 |
| HP            | 198E                        | Desktop     | [a311728a5f](https://linux-hardware.org/?probe=a311728a5f) | Sep 29, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [013801fc61](https://linux-hardware.org/?probe=013801fc61) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6fc52a277a](https://linux-hardware.org/?probe=6fc52a277a) | Sep 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [c09e747a85](https://linux-hardware.org/?probe=c09e747a85) | Sep 27, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [01109ec772](https://linux-hardware.org/?probe=01109ec772) | Sep 24, 2023 |
| Intel         | S1200RP G62254-407          | Server      | [1d003db534](https://linux-hardware.org/?probe=1d003db534) | Sep 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f5ed151e3e](https://linux-hardware.org/?probe=f5ed151e3e) | Sep 24, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [f94566dde6](https://linux-hardware.org/?probe=f94566dde6) | Sep 23, 2023 |
| HP            | ENVY 17                     | Notebook    | [4f6463148f](https://linux-hardware.org/?probe=4f6463148f) | Sep 22, 2023 |
| Lenovo        | ThinkPad W500 40624DG       | Notebook    | [9bdd448e89](https://linux-hardware.org/?probe=9bdd448e89) | Sep 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [b962cd9626](https://linux-hardware.org/?probe=b962cd9626) | Sep 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [1bd2a17c99](https://linux-hardware.org/?probe=1bd2a17c99) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d63be526d2](https://linux-hardware.org/?probe=d63be526d2) | Sep 18, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [8e044378bd](https://linux-hardware.org/?probe=8e044378bd) | Sep 15, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [6cc800f5dc](https://linux-hardware.org/?probe=6cc800f5dc) | Sep 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [de53daa0f8](https://linux-hardware.org/?probe=de53daa0f8) | Sep 12, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Dell          | Precision 7540              | Notebook    | [ced1086a24](https://linux-hardware.org/?probe=ced1086a24) | Sep 09, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [d6a8fc3557](https://linux-hardware.org/?probe=d6a8fc3557) | Sep 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [394dd17b98](https://linux-hardware.org/?probe=394dd17b98) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [d34f211b22](https://linux-hardware.org/?probe=d34f211b22) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [098294fb47](https://linux-hardware.org/?probe=098294fb47) | Sep 07, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [1e743d0b2d](https://linux-hardware.org/?probe=1e743d0b2d) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | Notebook    | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [12ed8aee3f](https://linux-hardware.org/?probe=12ed8aee3f) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [fdcab89946](https://linux-hardware.org/?probe=fdcab89946) | Sep 05, 2023 |
| ASRock        | Z490 Phantom Gaming 4/ac    | Desktop     | [5fa23571c9](https://linux-hardware.org/?probe=5fa23571c9) | Sep 04, 2023 |
| Medion        | S15449                      | Notebook    | [7e8cd1a434](https://linux-hardware.org/?probe=7e8cd1a434) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [315510322c](https://linux-hardware.org/?probe=315510322c) | Sep 02, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [0a46c781fc](https://linux-hardware.org/?probe=0a46c781fc) | Sep 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [e7c4150ded](https://linux-hardware.org/?probe=e7c4150ded) | Sep 01, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [75acf7c3bf](https://linux-hardware.org/?probe=75acf7c3bf) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [616c88aa53](https://linux-hardware.org/?probe=616c88aa53) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Gigabyte      | B75M-D3P                    | Desktop     | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [c5b6554c6b](https://linux-hardware.org/?probe=c5b6554c6b) | Aug 26, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [58d50740e7](https://linux-hardware.org/?probe=58d50740e7) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6b9175d89e](https://linux-hardware.org/?probe=6b9175d89e) | Aug 22, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2e8b5e3b34](https://linux-hardware.org/?probe=2e8b5e3b34) | Aug 20, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5a62fd8541](https://linux-hardware.org/?probe=5a62fd8541) | Aug 17, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [4c36ef643e](https://linux-hardware.org/?probe=4c36ef643e) | Aug 17, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| Toshiba       | Satellite Pro C70-A         | Notebook    | [dbb00fe95b](https://linux-hardware.org/?probe=dbb00fe95b) | Aug 15, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [f523831970](https://linux-hardware.org/?probe=f523831970) | Aug 14, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [b0e10f6505](https://linux-hardware.org/?probe=b0e10f6505) | Aug 13, 2023 |
| Intel         | DX58OG AAG10926-205         | Desktop     | [cb3a9289f9](https://linux-hardware.org/?probe=cb3a9289f9) | Aug 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [66bcc74be2](https://linux-hardware.org/?probe=66bcc74be2) | Aug 13, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e374cc3341](https://linux-hardware.org/?probe=e374cc3341) | Aug 12, 2023 |
| HP            | 1589                        | Desktop     | [1a38154020](https://linux-hardware.org/?probe=1a38154020) | Aug 12, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8193c225e5](https://linux-hardware.org/?probe=8193c225e5) | Aug 11, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c2b7b4e760](https://linux-hardware.org/?probe=c2b7b4e760) | Aug 10, 2023 |
| Dell          | 0272WF A00                  | Server      | [39abbc5ab8](https://linux-hardware.org/?probe=39abbc5ab8) | Aug 09, 2023 |
| Dell          | Precision 7740              | Notebook    | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| ASUSTek       | Z97-PRO/USB                 | Desktop     | [edd74878c3](https://linux-hardware.org/?probe=edd74878c3) | Aug 05, 2023 |
| HP            | 470 G7 Notebook PC          | Notebook    | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Dell          | 082WXT A03                  | Desktop     | [27a50c4491](https://linux-hardware.org/?probe=27a50c4491) | Aug 03, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [b684b97e44](https://linux-hardware.org/?probe=b684b97e44) | Aug 02, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [356dae8360](https://linux-hardware.org/?probe=356dae8360) | Jul 30, 2023 |
| Dell          | 0272WF A00                  | Server      | [ab789b12e1](https://linux-hardware.org/?probe=ab789b12e1) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [3a81b2b0d9](https://linux-hardware.org/?probe=3a81b2b0d9) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [4d6a620df3](https://linux-hardware.org/?probe=4d6a620df3) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| Sony          | Unknown                     | Notebook    | [80613731cb](https://linux-hardware.org/?probe=80613731cb) | Jul 28, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [7e89496549](https://linux-hardware.org/?probe=7e89496549) | Jul 27, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9d891afae0](https://linux-hardware.org/?probe=9d891afae0) | Jul 26, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [1568ba2843](https://linux-hardware.org/?probe=1568ba2843) | Jul 25, 2023 |
| HP            | 1589                        | Desktop     | [5c0bd1ec07](https://linux-hardware.org/?probe=5c0bd1ec07) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [b7c7b058b7](https://linux-hardware.org/?probe=b7c7b058b7) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [c741f10f18](https://linux-hardware.org/?probe=c741f10f18) | Jul 23, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [01f822dec1](https://linux-hardware.org/?probe=01f822dec1) | Jul 22, 2023 |
| Medion        | E6224                       | Notebook    | [c33b8a1fb1](https://linux-hardware.org/?probe=c33b8a1fb1) | Jul 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7b6300dfc7](https://linux-hardware.org/?probe=7b6300dfc7) | Jul 20, 2023 |
| Sony          | Unknown                     | Notebook    | [427e52d6a6](https://linux-hardware.org/?probe=427e52d6a6) | Jul 20, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [65da6837ae](https://linux-hardware.org/?probe=65da6837ae) | Jul 20, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [a2779c6ac8](https://linux-hardware.org/?probe=a2779c6ac8) | Jul 19, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [fe065234a9](https://linux-hardware.org/?probe=fe065234a9) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| Medion        | E6224                       | Notebook    | [4ffae87044](https://linux-hardware.org/?probe=4ffae87044) | Jul 17, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [874f8b41a7](https://linux-hardware.org/?probe=874f8b41a7) | Jul 14, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [78f620581b](https://linux-hardware.org/?probe=78f620581b) | Jul 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [9b03d78d55](https://linux-hardware.org/?probe=9b03d78d55) | Jul 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [7aac135bc0](https://linux-hardware.org/?probe=7aac135bc0) | Jul 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a52e535dcb](https://linux-hardware.org/?probe=a52e535dcb) | Jul 11, 2023 |
| Dell          | Latitude E5410              | Notebook    | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [c00debe968](https://linux-hardware.org/?probe=c00debe968) | Jul 08, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [a72d3eff75](https://linux-hardware.org/?probe=a72d3eff75) | Jul 08, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [8a5cbee239](https://linux-hardware.org/?probe=8a5cbee239) | Jul 08, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| HP            | 8B3B A                      | Desktop     | [b003988978](https://linux-hardware.org/?probe=b003988978) | Jul 05, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [40b7950cb2](https://linux-hardware.org/?probe=40b7950cb2) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [73435e5646](https://linux-hardware.org/?probe=73435e5646) | Jul 05, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [427fc931a0](https://linux-hardware.org/?probe=427fc931a0) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [a1fc2e0020](https://linux-hardware.org/?probe=a1fc2e0020) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [47536e2cde](https://linux-hardware.org/?probe=47536e2cde) | Jun 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2dd6be0ddc](https://linux-hardware.org/?probe=2dd6be0ddc) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | Notebook    | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| HP            | 1589                        | Desktop     | [dcb3289360](https://linux-hardware.org/?probe=dcb3289360) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| Gigabyte      | EG45M-DS2H                  | Desktop     | [b9b25df5a3](https://linux-hardware.org/?probe=b9b25df5a3) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [17c221fa68](https://linux-hardware.org/?probe=17c221fa68) | Jun 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6c015f633b](https://linux-hardware.org/?probe=6c015f633b) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Pegatron      | JESSE                       | Desktop     | [fa09a247a7](https://linux-hardware.org/?probe=fa09a247a7) | Jun 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [ed8bd3839f](https://linux-hardware.org/?probe=ed8bd3839f) | Jun 12, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [02f6d0b74b](https://linux-hardware.org/?probe=02f6d0b74b) | May 29, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [eb9ee9f38e](https://linux-hardware.org/?probe=eb9ee9f38e) | May 27, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e0920f015d](https://linux-hardware.org/?probe=e0920f015d) | May 25, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [7087600ab6](https://linux-hardware.org/?probe=7087600ab6) | May 17, 2023 |
| Dell          | Inspiron 7573               | Convertible | [8f57130549](https://linux-hardware.org/?probe=8f57130549) | May 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| Dell          | Inspiron 7573               | Convertible | [6f1d226305](https://linux-hardware.org/?probe=6f1d226305) | May 16, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [443ee2bf3a](https://linux-hardware.org/?probe=443ee2bf3a) | May 16, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| Dell          | Latitude D530               | Notebook    | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9b0a8de7a1](https://linux-hardware.org/?probe=9b0a8de7a1) | Feb 02, 2023 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE_Leap-15.5/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.21-150500.53-default      | 70        | 17.07%  |
| 5.14.21-150500.55.52-default   | 45        | 10.98%  |
| 5.14.21-150500.55.19-default   | 41        | 10%     |
| 5.14.21-150500.55.39-default   | 33        | 8.05%   |
| 5.14.21-150500.55.36-default   | 32        | 7.8%    |
| 5.14.21-150500.55.49-default   | 23        | 5.61%   |
| 5.14.21-150500.55.65-default   | 21        | 5.12%   |
| 5.14.21-150500.55.31-default   | 20        | 4.88%   |
| 5.14.21-150500.55.7-default    | 16        | 3.9%    |
| 5.14.21-150500.55.59-default   | 16        | 3.9%    |
| 5.14.21-150500.55.68-default   | 12        | 2.93%   |
| 5.14.21-150500.55.12-default   | 12        | 2.93%   |
| 5.14.21-150500.55.28-default   | 11        | 2.68%   |
| 5.14.21-150500.55.44-default   | 10        | 2.44%   |
| 5.14.21-150500.55.73-default   | 9         | 2.2%    |
| 5.14.21-150500.52-default      | 9         | 2.2%    |
| 5.14.21-150500.55.83-default   | 8         | 1.95%   |
| 5.14.21-150500.55.62-default   | 5         | 1.22%   |
| 5.14.21-150500.43-default      | 2         | 0.49%   |
| 5.14.21-150400.24.18-default   | 2         | 0.49%   |
| 6.8.9-1-default                | 1         | 0.24%   |
| 6.6.3-1-default                | 1         | 0.24%   |
| 6.6.11-lp155.3-default         | 1         | 0.24%   |
| 6.5.9-lp155.2-default          | 1         | 0.24%   |
| 6.5.9-lp154.6-default          | 1         | 0.24%   |
| 6.5.4-1-default                | 1         | 0.24%   |
| 6.4.4-lp154.2.g919c802-default | 1         | 0.24%   |
| 5.14.21-150500.55.88-default   | 1         | 0.24%   |
| 5.14.21-150500.50-default      | 1         | 0.24%   |
| 5.14.21-150500.49-default      | 1         | 0.24%   |
| 5.14.21-150500.37-default      | 1         | 0.24%   |
| 5.14.21-150400.24.55-default   | 1         | 0.24%   |
| 5.14.21-150400.24.46-default   | 1         | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.21 | 364       | 98.11%  |
| 6.5.9   | 2         | 0.54%   |
| 6.8.9   | 1         | 0.27%   |
| 6.6.3   | 1         | 0.27%   |
| 6.6.11  | 1         | 0.27%   |
| 6.5.4   | 1         | 0.27%   |
| 6.4.4   | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 364       | 98.11%  |
| 6.5     | 3         | 0.81%   |
| 6.6     | 2         | 0.54%   |
| 6.8     | 1         | 0.27%   |
| 6.4     | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 369       | 99.73%  |
| aarch64 | 1         | 0.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 286       | 76.88%  |
| GNOME    | 55        | 14.78%  |
| XFCE     | 12        | 3.23%   |
| Unknown  | 6         | 1.61%   |
| MATE     | 2         | 0.54%   |
| ICEWM    | 2         | 0.54%   |
| Deepin   | 2         | 0.54%   |
| Cinnamon | 2         | 0.54%   |
| Trinity  | 1         | 0.27%   |
| LXQt     | 1         | 0.27%   |
| LXDE     | 1         | 0.27%   |
| KDE      | 1         | 0.27%   |
| Budgie   | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 312       | 82.98%  |
| Wayland | 49        | 13.03%  |
| Tty     | 13        | 3.46%   |
| Unknown | 2         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 237       | 63.54%  |
| SDDM    | 105       | 28.15%  |
| LightDM | 17        | 4.56%   |
| GDM     | 8         | 2.14%   |
| XDM     | 6         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 133       | 35.75%  |
| de_DE           | 98        | 26.34%  |
| POSIX           | 36        | 9.68%   |
| pt_BR           | 18        | 4.84%   |
| ru_RU           | 14        | 3.76%   |
| es_ES           | 12        | 3.23%   |
| fr_FR           | 9         | 2.42%   |
| nl_NL           | 8         | 2.15%   |
| pl_PL           | 7         | 1.88%   |
| it_IT           | 7         | 1.88%   |
| en_GB           | 7         | 1.88%   |
| hu_HU           | 3         | 0.81%   |
| C               | 3         | 0.81%   |
| zh_CN           | 2         | 0.54%   |
| sk_SK           | 2         | 0.54%   |
| en_DK           | 2         | 0.54%   |
| pt_PT           | 1         | 0.27%   |
| ja_JP           | 1         | 0.27%   |
| fi_FI           | 1         | 0.27%   |
| es_DO           | 1         | 0.27%   |
| en_ZA           | 1         | 0.27%   |
| en_US.ISO8859-1 | 1         | 0.27%   |
| el_GR           | 1         | 0.27%   |
| da_DK           | 1         | 0.27%   |
| cs_CZ           | 1         | 0.27%   |
| ar_AE           | 1         | 0.27%   |
| Unknown         | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 260       | 69.71%  |
| EFI  | 113       | 30.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 288       | 77.42%  |
| Ext4  | 70        | 18.82%  |
| Xfs   | 10        | 2.69%   |
| Tmpfs | 3         | 0.81%   |
| Zfs   | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 229       | 61.39%  |
| GPT     | 130       | 34.85%  |
| MBR     | 14        | 3.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 336       | 90.32%  |
| Yes       | 36        | 9.68%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 307       | 82.75%  |
| Yes       | 64        | 17.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 60        | 16.22%  |
| ASUSTek Computer        | 58        | 15.68%  |
| Lenovo                  | 51        | 13.78%  |
| Dell                    | 38        | 10.27%  |
| Gigabyte Technology     | 31        | 8.38%   |
| ASRock                  | 23        | 6.22%   |
| Acer                    | 21        | 5.68%   |
| MSI                     | 20        | 5.41%   |
| Intel                   | 6         | 1.62%   |
| Fujitsu                 | 6         | 1.62%   |
| Toshiba                 | 4         | 1.08%   |
| Biostar                 | 4         | 1.08%   |
| Apple                   | 4         | 1.08%   |
| TUXEDO                  | 3         | 0.81%   |
| Sony                    | 3         | 0.81%   |
| Medion                  | 3         | 0.81%   |
| Wortmann AG             | 2         | 0.54%   |
| System76                | 2         | 0.54%   |
| Samsung Electronics     | 2         | 0.54%   |
| Notebook                | 2         | 0.54%   |
| HUAWEI                  | 2         | 0.54%   |
| HC Technology.          | 2         | 0.54%   |
| Fujitsu Siemens         | 2         | 0.54%   |
| AZW                     | 2         | 0.54%   |
| Unknown                 | 2         | 0.54%   |
| Schenker                | 1         | 0.27%   |
| Raspberry Pi Foundation | 1         | 0.27%   |
| Pegatron                | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| OEM                     | 1         | 0.27%   |
| LG Electronics          | 1         | 0.27%   |
| ILLEGEAR                | 1         | 0.27%   |
| Google                  | 1         | 0.27%   |
| GEEKOM                  | 1         | 0.27%   |
| Framework               | 1         | 0.27%   |
| Foxconn                 | 1         | 0.27%   |
| Dynabook                | 1         | 0.27%   |
| Digibras                | 1         | 0.27%   |
| Colorful Technology     | 1         | 0.27%   |
| BESSTAR Tech            | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASUS M5A97 R2.0                                                                          | 3         | 0.81%   |
| Unknown                                                                                  | 3         | 0.81%   |
| TUXEDO Aura 15 Gen2                                                                      | 2         | 0.54%   |
| MSI MS-7A33                                                                              | 2         | 0.54%   |
| HP Z420 Workstation                                                                      | 2         | 0.54%   |
| HP Victus by Gaming Laptop 15-fb0xxx                                                     | 2         | 0.54%   |
| HP Notebook                                                                              | 2         | 0.54%   |
| HC Technology. HCAR5000-MI                                                               | 2         | 0.54%   |
| Gigabyte GA-MA770-UD3                                                                    | 2         | 0.54%   |
| Gigabyte B550M DS3H                                                                      | 2         | 0.54%   |
| AZW SER                                                                                  | 2         | 0.54%   |
| ASUS ROG STRIX X570-E GAMING                                                             | 2         | 0.54%   |
| Wortmann AG TERRA_MOBILE_1749                                                            | 1         | 0.27%   |
| Wortmann AG TERRA_MOBILE_1512/1712                                                       | 1         | 0.27%   |
| TUXEDO Pulse 15 Gen2                                                                     | 1         | 0.27%   |
| Toshiba Satellite R945                                                                   | 1         | 0.27%   |
| Toshiba Satellite Pro C70-A                                                              | 1         | 0.27%   |
| Toshiba Satellite C55D-A                                                                 | 1         | 0.27%   |
| Toshiba dynabook Satellite B552/H                                                        | 1         | 0.27%   |
| System76 Lemur Pro                                                                       | 1         | 0.27%   |
| System76 Bonobo WS                                                                       | 1         | 0.27%   |
| Sony VPCEH11FX                                                                           | 1         | 0.27%   |
| Sony SVF1521A7EB                                                                         | 1         | 0.27%   |
| Schenker KEY (E23)                                                                       | 1         | 0.27%   |
| Samsung 730QFG                                                                           | 1         | 0.27%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.27%   |
| RPi rpi                                                                                  | 1         | 0.27%   |
| Pegatron NY603AA-ABA 300-1007                                                            | 1         | 0.27%   |
| Panasonic CF-C2CUGZXKM                                                                   | 1         | 0.27%   |
| OEM B75                                                                                  | 1         | 0.27%   |
| Notebook NS50_70MU                                                                       | 1         | 0.27%   |
| Notebook NLx0MU                                                                          | 1         | 0.27%   |
| MSI Summit E13FlipEvo A11MT                                                              | 1         | 0.27%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8)                                                           | 1         | 0.27%   |
| MSI MS-7D74                                                                              | 1         | 0.27%   |
| MSI MS-7D54                                                                              | 1         | 0.27%   |
| MSI MS-7C95                                                                              | 1         | 0.27%   |
| MSI MS-7C91                                                                              | 1         | 0.27%   |
| MSI MS-7C80                                                                              | 1         | 0.27%   |
| MSI MS-7C52                                                                              | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 23        | 6.22%   |
| Acer Aspire                | 14        | 3.78%   |
| Dell Precision             | 9         | 2.43%   |
| Lenovo IdeaPad             | 8         | 2.16%   |
| HP EliteBook               | 8         | 2.16%   |
| Dell Latitude              | 8         | 2.16%   |
| ASUS PRIME                 | 8         | 2.16%   |
| HP ENVY                    | 7         | 1.89%   |
| Dell OptiPlex              | 7         | 1.89%   |
| ASUS ROG                   | 7         | 1.89%   |
| HP Laptop                  | 6         | 1.62%   |
| Dell Inspiron              | 6         | 1.62%   |
| Lenovo ThinkCentre         | 5         | 1.35%   |
| Lenovo Legion              | 5         | 1.35%   |
| HP ProLiant                | 5         | 1.35%   |
| HP Pavilion                | 5         | 1.35%   |
| ASUS VivoBook              | 5         | 1.35%   |
| HP Victus                  | 4         | 1.08%   |
| HP Compaq                  | 4         | 1.08%   |
| Toshiba Satellite          | 3         | 0.81%   |
| Dell XPS                   | 3         | 0.81%   |
| Dell Vostro                | 3         | 0.81%   |
| ASUS M5A97                 | 3         | 0.81%   |
| Acer Nitro                 | 3         | 0.81%   |
| Unknown                    | 3         | 0.81%   |
| Wortmann AG TERRA          | 2         | 0.54%   |
| TUXEDO Aura                | 2         | 0.54%   |
| MSI MS-7A33                | 2         | 0.54%   |
| HP Z420                    | 2         | 0.54%   |
| HP ProBook                 | 2         | 0.54%   |
| HP OMEN                    | 2         | 0.54%   |
| HP Notebook                | 2         | 0.54%   |
| HP EliteDesk               | 2         | 0.54%   |
| HC Technology. HCAR5000-MI | 2         | 0.54%   |
| Gigabyte GA-MA770-UD3      | 2         | 0.54%   |
| Gigabyte B550M             | 2         | 0.54%   |
| Gigabyte B450M             | 2         | 0.54%   |
| Fujitsu ESPRIMO            | 2         | 0.54%   |
| AZW SER                    | 2         | 0.54%   |
| ASUS ZenBook               | 2         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 37        | 10%     |
| 2020 | 34        | 9.19%   |
| 2022 | 29        | 7.84%   |
| 2019 | 28        | 7.57%   |
| 2013 | 25        | 6.76%   |
| 2012 | 25        | 6.76%   |
| 2018 | 24        | 6.49%   |
| 2010 | 24        | 6.49%   |
| 2023 | 23        | 6.22%   |
| 2015 | 23        | 6.22%   |
| 2017 | 20        | 5.41%   |
| 2011 | 20        | 5.41%   |
| 2016 | 14        | 3.78%   |
| 2014 | 13        | 3.51%   |
| 2008 | 11        | 2.97%   |
| 2009 | 9         | 2.43%   |
| 2007 | 6         | 1.62%   |
| 2006 | 3         | 0.81%   |
| 2024 | 2         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 181       | 48.92%  |
| Desktop        | 168       | 45.41%  |
| Convertible    | 7         | 1.89%   |
| Mini pc        | 5         | 1.35%   |
| Server         | 4         | 1.08%   |
| All in one     | 3         | 0.81%   |
| Other          | 1         | 0.27%   |
| System on chip | 1         | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 343       | 92.45%  |
| Enabled  | 28        | 7.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 367       | 99.19%  |
| Yes  | 3         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 86        | 23.12%  |
| 16.01-24.0      | 86        | 23.12%  |
| 8.01-16.0       | 71        | 19.09%  |
| 32.01-64.0      | 57        | 15.32%  |
| 3.01-4.0        | 35        | 9.41%   |
| 64.01-256.0     | 23        | 6.18%   |
| 24.01-32.0      | 6         | 1.61%   |
| 1.01-2.0        | 6         | 1.61%   |
| More than 256.0 | 1         | 0.27%   |
| 2.01-3.0        | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 131       | 33.16%  |
| 1.01-2.0   | 81        | 20.51%  |
| 4.01-8.0   | 74        | 18.73%  |
| 3.01-4.0   | 73        | 18.48%  |
| 8.01-16.0  | 21        | 5.32%   |
| 0.51-1.0   | 11        | 2.78%   |
| 16.01-24.0 | 3         | 0.76%   |
| 24.01-32.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 198       | 52.8%   |
| 2      | 97        | 25.87%  |
| 3      | 45        | 12%     |
| 4      | 18        | 4.8%    |
| 5      | 9         | 2.4%    |
| 6      | 5         | 1.33%   |
| 10     | 1         | 0.27%   |
| 8      | 1         | 0.27%   |
| 7      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 56.18%  |
| Yes       | 163       | 43.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 339       | 91.62%  |
| No        | 31        | 8.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 257       | 69.09%  |
| No        | 115       | 30.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 60%     |
| No        | 150       | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| Germany         | 108       | 29.19%  |
| USA             | 69        | 18.65%  |
| Brazil          | 21        | 5.68%   |
| Russia          | 17        | 4.59%   |
| Poland          | 11        | 2.97%   |
| Italy           | 10        | 2.7%    |
| Spain           | 9         | 2.43%   |
| UK              | 7         | 1.89%   |
| Netherlands     | 7         | 1.89%   |
| Canada          | 7         | 1.89%   |
| Switzerland     | 6         | 1.62%   |
| India           | 6         | 1.62%   |
| Greece          | 6         | 1.62%   |
| France          | 5         | 1.35%   |
| Belgium         | 5         | 1.35%   |
| Australia       | 5         | 1.35%   |
| Mexico          | 4         | 1.08%   |
| Hungary         | 4         | 1.08%   |
| Finland         | 4         | 1.08%   |
| Ukraine         | 3         | 0.81%   |
| Sweden          | 3         | 0.81%   |
| Czechia         | 3         | 0.81%   |
| Colombia        | 3         | 0.81%   |
| Argentina       | 3         | 0.81%   |
| South Africa    | 2         | 0.54%   |
| Slovenia        | 2         | 0.54%   |
| Slovakia        | 2         | 0.54%   |
| Serbia          | 2         | 0.54%   |
| Portugal        | 2         | 0.54%   |
| Malaysia        | 2         | 0.54%   |
| Hong Kong       | 2         | 0.54%   |
| China           | 2         | 0.54%   |
| Bulgaria        | 2         | 0.54%   |
| Austria         | 2         | 0.54%   |
| Vietnam         | 1         | 0.27%   |
| Venezuela       | 1         | 0.27%   |
| Türkiye        | 1         | 0.27%   |
| Turkey          | 1         | 0.27%   |
| The Netherlands | 1         | 0.27%   |
| South Korea     | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Munich               | 10        | 2.62%   |
| Berlin               | 7         | 1.84%   |
| Warsaw               | 5         | 1.31%   |
| Zurich               | 3         | 0.79%   |
| Vigo                 | 3         | 0.79%   |
| Stuttgart            | 3         | 0.79%   |
| St Petersburg        | 3         | 0.79%   |
| Sao Paulo            | 3         | 0.79%   |
| Milan                | 3         | 0.79%   |
| Leipzig              | 3         | 0.79%   |
| Kyiv                 | 3         | 0.79%   |
| Hamburg              | 3         | 0.79%   |
| Enschede             | 3         | 0.79%   |
| Budapest             | 3         | 0.79%   |
| Bremen               | 3         | 0.79%   |
| Zetel                | 2         | 0.52%   |
| Sydney               | 2         | 0.52%   |
| Sofia                | 2         | 0.52%   |
| Sao Vicente          | 2         | 0.52%   |
| Sacramento           | 2         | 0.52%   |
| Rüsselsheim am Main | 2         | 0.52%   |
| Rostock              | 2         | 0.52%   |
| Rio de Janeiro       | 2         | 0.52%   |
| Prague               | 2         | 0.52%   |
| Porto                | 2         | 0.52%   |
| Portland             | 2         | 0.52%   |
| Nuremberg            | 2         | 0.52%   |
| Neustadt             | 2         | 0.52%   |
| Ljubljana            | 2         | 0.52%   |
| Kuala Lumpur         | 2         | 0.52%   |
| Krakow               | 2         | 0.52%   |
| Kansas City          | 2         | 0.52%   |
| Johannesburg         | 2         | 0.52%   |
| Ithaca               | 2         | 0.52%   |
| Heraklion            | 2         | 0.52%   |
| Hanover              | 2         | 0.52%   |
| Dresden              | 2         | 0.52%   |
| Denver               | 2         | 0.52%   |
| Cherry Hill          | 2         | 0.52%   |
| Central              | 2         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 98        | 142    | 16.96%  |
| Seagate                     | 87        | 143    | 15.05%  |
| WDC                         | 68        | 134    | 11.76%  |
| Sandisk                     | 35        | 48     | 6.06%   |
| Kingston                    | 30        | 41     | 5.19%   |
| Toshiba                     | 28        | 32     | 4.84%   |
| Crucial                     | 22        | 25     | 3.81%   |
| Hitachi                     | 17        | 20     | 2.94%   |
| Micron Technology           | 16        | 17     | 2.77%   |
| Unknown                     | 15        | 17     | 2.6%    |
| SK hynix                    | 15        | 17     | 2.6%    |
| Intel                       | 15        | 16     | 2.6%    |
| HGST                        | 9         | 10     | 1.56%   |
| Silicon Motion              | 8         | 8      | 1.38%   |
| Micron/Crucial Technology   | 7         | 9      | 1.21%   |
| Kingston Technology Company | 7         | 9      | 1.21%   |
| Intenso                     | 7         | 8      | 1.21%   |
| A-DATA Technology           | 7         | 7      | 1.21%   |
| China                       | 6         | 7      | 1.04%   |
| Phison Electronics          | 5         | 7      | 0.87%   |
| Apple                       | 5         | 6      | 0.87%   |
| SPCC                        | 4         | 4      | 0.69%   |
| KIOXIA                      | 4         | 5      | 0.69%   |
| ADATA Technology            | 4         | 4      | 0.69%   |
| PNY                         | 3         | 5      | 0.52%   |
| Hewlett-Packard             | 3         | 3      | 0.52%   |
| Fanxiang                    | 3         | 4      | 0.52%   |
| Dogfish                     | 3         | 3      | 0.52%   |
| XrayDisk                    | 2         | 2      | 0.35%   |
| Verbatim                    | 2         | 2      | 0.35%   |
| SABRENT                     | 2         | 2      | 0.35%   |
| Realtek Semiconductor       | 2         | 2      | 0.35%   |
| Netac                       | 2         | 4      | 0.35%   |
| Leven                       | 2         | 2      | 0.35%   |
| ASMT                        | 2         | 3      | 0.35%   |
| Unknown                     | 2         | 2      | 0.35%   |
| Yangtze Memory Technologies | 1         | 1      | 0.17%   |
| XSTAR                       | 1         | 1      | 0.17%   |
| USB                         | 1         | 1      | 0.17%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 17        | 2.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 13        | 2.05%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 7         | 1.1%    |
| Seagate ST500DM002-1BD142 500GB                       | 6         | 0.94%   |
| Samsung SSD 870 EVO 1TB                               | 6         | 0.94%   |
| Samsung SSD 840 EVO 250GB                             | 6         | 0.94%   |
| Kingston SA400S37480G 480GB SSD                       | 6         | 0.94%   |
| Intel SSD 660P Series 1024GB                          | 6         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 5         | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5         | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB                        | 5         | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 5         | 0.79%   |
| Kingston SA400S37120G 120GB SSD                       | 5         | 0.79%   |
| Unknown MMC Card  16GB                                | 4         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 4         | 0.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 4         | 0.63%   |
| Kingston SV300S37A120G 120GB SSD                      | 4         | 0.63%   |
| Crucial CT275MX300SSD1 275GB                          | 4         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3         | 0.47%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 3         | 0.47%   |
| Toshiba MQ01ABD100 1TB                                | 3         | 0.47%   |
| Toshiba DT01ACA050 500GB                              | 3         | 0.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 3         | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3         | 0.47%   |
| Seagate ST1000LM048-2E7172 1TB                        | 3         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3         | 0.47%   |
| Seagate Expansion HDD 14TB                            | 3         | 0.47%   |
| Samsung SSD 990 PRO 2TB                               | 3         | 0.47%   |
| Samsung SSD 860 EVO 1TB                               | 3         | 0.47%   |
| Samsung SSD 850 EVO 250GB                             | 3         | 0.47%   |
| Samsung SSD 840 EVO 120GB                             | 3         | 0.47%   |
| Kingston Company A2000 NVMe SSD 500GB                 | 3         | 0.47%   |
| Kingston SA400S37240G 240GB SSD                       | 3         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 2         | 0.31%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                      | 2         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 0.31%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 2         | 0.31%   |
| WDC WD10EZRX-00A8LB0 1TB                              | 2         | 0.31%   |
| WDC WD1003FZEX-00K3CA0 1TB                            | 2         | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB                           | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 83        | 134    | 38.43%  |
| WDC                 | 58        | 111    | 26.85%  |
| Toshiba             | 20        | 22     | 9.26%   |
| Hitachi             | 17        | 20     | 7.87%   |
| Samsung Electronics | 12        | 14     | 5.56%   |
| HGST                | 9         | 10     | 4.17%   |
| Apple               | 4         | 4      | 1.85%   |
| Unknown             | 2         | 2      | 0.93%   |
| SABRENT             | 2         | 2      | 0.93%   |
| Hewlett-Packard     | 2         | 2      | 0.93%   |
| ASMT                | 2         | 3      | 0.93%   |
| XrayDisk            | 1         | 1      | 0.46%   |
| Synology            | 1         | 1      | 0.46%   |
| Maxtor              | 1         | 2      | 0.46%   |
| Maxone              | 1         | 1      | 0.46%   |
| Fujitsu             | 1         | 2      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 66     | 23.66%  |
| Kingston            | 24        | 31     | 12.9%   |
| Crucial             | 22        | 25     | 11.83%  |
| SanDisk             | 13        | 18     | 6.99%   |
| WDC                 | 12        | 22     | 6.45%   |
| A-DATA Technology   | 7         | 7      | 3.76%   |
| Intenso             | 6         | 6      | 3.23%   |
| China               | 6         | 7      | 3.23%   |
| Toshiba             | 4         | 5      | 2.15%   |
| SPCC                | 4         | 4      | 2.15%   |
| Micron Technology   | 4         | 4      | 2.15%   |
| Intel               | 4         | 5      | 2.15%   |
| PNY                 | 3         | 5      | 1.61%   |
| Dogfish             | 3         | 3      | 1.61%   |
| SK hynix            | 2         | 2      | 1.08%   |
| Netac               | 2         | 4      | 1.08%   |
| Leven               | 2         | 2      | 1.08%   |
| Fanxiang            | 2         | 3      | 1.08%   |
| Apple               | 2         | 2      | 1.08%   |
| XSTAR               | 1         | 1      | 0.54%   |
| XrayDisk            | 1         | 1      | 0.54%   |
| Verbatim            | 1         | 1      | 0.54%   |
| Transcend           | 1         | 1      | 0.54%   |
| Team                | 1         | 2      | 0.54%   |
| T-FORCE             | 1         | 1      | 0.54%   |
| StoreJet            | 1         | 1      | 0.54%   |
| SATAFIRM            | 1         | 1      | 0.54%   |
| RESCUE              | 1         | 1      | 0.54%   |
| Radeon              | 1         | 1      | 0.54%   |
| Patriot             | 1         | 1      | 0.54%   |
| LITEON              | 1         | 1      | 0.54%   |
| Hewlett-Packard     | 1         | 1      | 0.54%   |
| GOODRAM             | 1         | 1      | 0.54%   |
| Gigabyte Technology | 1         | 1      | 0.54%   |
| FIKWOT              | 1         | 1      | 0.54%   |
| BAITITON            | 1         | 1      | 0.54%   |
| AMD                 | 1         | 1      | 0.54%   |
| Acer                | 1         | 1      | 0.54%   |
| Unknown             | 1         | 1      | 0.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 166       | 331    | 33.4%   |
| SSD     | 159       | 242    | 31.99%  |
| NVMe    | 149       | 204    | 29.98%  |
| MMC     | 12        | 14     | 2.41%   |
| Unknown | 11        | 14     | 2.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 256       | 536    | 57.27%  |
| NVMe | 149       | 202    | 33.33%  |
| SAS  | 30        | 53     | 6.71%   |
| MMC  | 12        | 14     | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 173       | 260    | 48.87%  |
| 0.51-1.0   | 108       | 179    | 30.51%  |
| 1.01-2.0   | 36        | 73     | 10.17%  |
| 3.01-4.0   | 18        | 33     | 5.08%   |
| 4.01-10.0  | 9         | 15     | 2.54%   |
| 2.01-3.0   | 5         | 5      | 1.41%   |
| 10.01-20.0 | 5         | 8      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 136       | 35.88%  |
| 1001-2000      | 80        | 21.11%  |
| 501-1000       | 45        | 11.87%  |
| 2001-3000      | 43        | 11.35%  |
| 251-500        | 35        | 9.23%   |
| 101-250        | 26        | 6.86%   |
| 51-100         | 6         | 1.58%   |
| Unknown        | 4         | 1.06%   |
| 21-50          | 3         | 0.79%   |
| 1-20           | 1         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 115       | 29.11%  |
| 51-100         | 67        | 16.96%  |
| 251-500        | 60        | 15.19%  |
| 501-1000       | 46        | 11.65%  |
| 1001-2000      | 33        | 8.35%   |
| 1-20           | 24        | 6.08%   |
| More than 3000 | 20        | 5.06%   |
| 21-50          | 19        | 4.81%   |
| 2001-3000      | 7         | 1.77%   |
| Unknown        | 4         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 13.33%  |
| Kingston SA400S37120G 120GB SSD                  | 2         | 4      | 13.33%  |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 6.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 6.67%   |
| Seagate ST4000NM0035-1V4107 4TB                  | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 840 EVO 120GB            | 1         | 1      | 6.67%   |
| Samsung Electronics MZALQ256HBJD-00BL2 256GB     | 1         | 1      | 6.67%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1         | 1      | 6.67%   |
| Maxtor 6Y120M0 128GB                             | 1         | 2      | 6.67%   |
| Intel SSD 600P Series 256GB                      | 1         | 1      | 6.67%   |
| Hitachi HTS727550A9E364 500GB                    | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 6.67%   |
| Crucial CT240M500SSD1 240GB                      | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 28.57%  |
| Samsung Electronics | 2         | 3      | 14.29%  |
| Kingston            | 2         | 4      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Maxtor              | 1         | 2      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| Toshiba | 1         | 1      | 12.5%   |
| Maxtor  | 1         | 2      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 57.14%  |
| SSD  | 4         | 7      | 28.57%  |
| NVMe | 2         | 2      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 240       | 541    | 61.22%  |
| Works    | 138       | 244    | 35.2%   |
| Malfunc  | 13        | 18     | 3.32%   |
| Failed   | 1         | 2      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 232       | 46.03%  |
| AMD                           | 85        | 16.87%  |
| Samsung Electronics           | 50        | 9.92%   |
| SanDisk                       | 23        | 4.56%   |
| SK hynix                      | 13        | 2.58%   |
| Kingston Technology Company   | 13        | 2.58%   |
| Micron Technology             | 12        | 2.38%   |
| Silicon Motion                | 8         | 1.59%   |
| ASMedia Technology            | 8         | 1.59%   |
| Micron/Crucial Technology     | 7         | 1.39%   |
| Marvell Technology Group      | 6         | 1.19%   |
| JMicron Technology            | 6         | 1.19%   |
| Toshiba America Info Systems  | 5         | 0.99%   |
| Phison Electronics            | 5         | 0.99%   |
| Seagate Technology            | 4         | 0.79%   |
| Nvidia                        | 4         | 0.79%   |
| KIOXIA                        | 4         | 0.79%   |
| Broadcom / LSI                | 4         | 0.79%   |
| ADATA Technology              | 4         | 0.79%   |
| Union Memory (Shenzhen)       | 2         | 0.4%    |
| Realtek Semiconductor         | 2         | 0.4%    |
| Yangtze Memory Technologies   | 1         | 0.2%    |
| VIA Technologies              | 1         | 0.2%    |
| MAXIO Technology (Hangzhou)   | 1         | 0.2%    |
| Integrated Technology Express | 1         | 0.2%    |
| Hewlett-Packard               | 1         | 0.2%    |
| Adaptec                       | 1         | 0.2%    |
| Unknown                       | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 43        | 7.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 2.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 2.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 2.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 2.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 14        | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 13        | 2.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11        | 1.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 11        | 1.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.52%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8         | 1.35%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 1.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 1.02%   |
| Intel SSD 660P Series                                                          | 6         | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.02%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 6         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 5         | 0.85%   |
| Intel SATA Controller [RAID Mode]                                              | 5         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5         | 0.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.85%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 5         | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.68%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 4         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 277       | 53.07%  |
| NVMe | 149       | 28.54%  |
| IDE  | 51        | 9.77%   |
| RAID | 37        | 7.09%   |
| SAS  | 7         | 1.34%   |
| SCSI | 1         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 259       | 70%     |
| AMD    | 110       | 29.73%  |
| ARM    | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 1.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 6         | 1.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 1.62%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 6         | 1.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 5         | 1.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 5         | 1.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 1.08%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4         | 1.08%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 4         | 1.08%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 4         | 1.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 3         | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.81%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 0.81%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 0.81%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 0.81%   |
| Intel 13th Gen Core i9-13900HX          | 3         | 0.81%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 3         | 0.81%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 0.81%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 3         | 0.81%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 2         | 0.54%   |
| Intel Xeon CPU E5-1603 0 @ 2.80GHz      | 2         | 0.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.54%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 0.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 0.54%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 2         | 0.54%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.54%   |
| Intel Core i3-7100T CPU @ 3.40GHz       | 2         | 0.54%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 0.54%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz   | 2         | 0.54%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 2         | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.54%   |
| Intel 13th Gen Core i9-13900H           | 2         | 0.54%   |
| Intel 12th Gen Core i5-1235U            | 2         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 63        | 17.03%  |
| Intel Core i7           | 60        | 16.22%  |
| Other                   | 50        | 13.51%  |
| AMD Ryzen 5             | 32        | 8.65%   |
| Intel Core i3           | 23        | 6.22%   |
| AMD Ryzen 7             | 20        | 5.41%   |
| Intel Xeon              | 18        | 4.86%   |
| Intel Celeron           | 12        | 3.24%   |
| AMD FX                  | 11        | 2.97%   |
| Intel Pentium           | 10        | 2.7%    |
| Intel Core 2 Duo        | 10        | 2.7%    |
| AMD Ryzen 9             | 9         | 2.43%   |
| Intel Core 2 Quad       | 5         | 1.35%   |
| AMD A6                  | 5         | 1.35%   |
| AMD Phenom II X6        | 4         | 1.08%   |
| AMD A8                  | 4         | 1.08%   |
| AMD Ryzen 7 PRO         | 3         | 0.81%   |
| AMD Ryzen 3             | 3         | 0.81%   |
| AMD A4                  | 3         | 0.81%   |
| Intel Pentium Dual-Core | 2         | 0.54%   |
| Intel Core i9           | 2         | 0.54%   |
| AMD Phenom II X4        | 2         | 0.54%   |
| AMD Phenom              | 2         | 0.54%   |
| AMD Athlon              | 2         | 0.54%   |
| Intel Pentium Silver    | 1         | 0.27%   |
| Intel Pentium Gold      | 1         | 0.27%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Core 2 Extreme    | 1         | 0.27%   |
| Intel Core 2            | 1         | 0.27%   |
| AMD Ryzen Threadripper  | 1         | 0.27%   |
| AMD Ryzen 5 PRO         | 1         | 0.27%   |
| AMD Ryzen 3 PRO         | 1         | 0.27%   |
| AMD Opteron             | 1         | 0.27%   |
| AMD Athlon X4           | 1         | 0.27%   |
| AMD Athlon X2           | 1         | 0.27%   |
| AMD Athlon II X4        | 1         | 0.27%   |
| AMD Athlon II X3        | 1         | 0.27%   |
| AMD Athlon II X2        | 1         | 0.27%   |
| AMD Athlon 64 X2        | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 129       | 34.86%  |
| 2       | 104       | 28.11%  |
| 6       | 57        | 15.41%  |
| 8       | 31        | 8.38%   |
| 12      | 15        | 4.05%   |
| 16      | 7         | 1.89%   |
| 10      | 6         | 1.62%   |
| 24      | 4         | 1.08%   |
| 14      | 4         | 1.08%   |
| 1       | 4         | 1.08%   |
| 20      | 3         | 0.81%   |
| 3       | 3         | 0.81%   |
| 64      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 362       | 97.84%  |
| 2       | 6         | 1.62%   |
| 4       | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 267       | 72.16%  |
| 1       | 102       | 27.57%  |
| Unknown | 1         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 370       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 220       | 58.67%  |
| 0x806c1    | 12        | 3.2%    |
| 0x906ea    | 8         | 2.13%   |
| 0x906e9    | 8         | 2.13%   |
| 0x08608103 | 8         | 2.13%   |
| 0xb0671    | 7         | 1.87%   |
| 0x806ec    | 7         | 1.87%   |
| 0x1067a    | 7         | 1.87%   |
| 0x0a50000d | 6         | 1.6%    |
| 0x306a9    | 5         | 1.33%   |
| 0x506e3    | 4         | 1.07%   |
| 0x406e3    | 4         | 1.07%   |
| 0x306c3    | 4         | 1.07%   |
| 0xb06a2    | 3         | 0.8%    |
| 0xa0671    | 3         | 0.8%    |
| 0x806ea    | 3         | 0.8%    |
| 0x206d7    | 3         | 0.8%    |
| 0x206a7    | 3         | 0.8%    |
| 0x0a50000c | 3         | 0.8%    |
| 0x08600106 | 3         | 0.8%    |
| 0x906ed    | 2         | 0.53%   |
| 0x906a3    | 2         | 0.53%   |
| 0x806e9    | 2         | 0.53%   |
| 0x806c2    | 2         | 0.53%   |
| 0x706a8    | 2         | 0.53%   |
| 0x40651    | 2         | 0.53%   |
| 0x20655    | 2         | 0.53%   |
| 0x106e5    | 2         | 0.53%   |
| 0x0a601203 | 2         | 0.53%   |
| 0x0a20120a | 2         | 0.53%   |
| 0x08701021 | 2         | 0.53%   |
| 0x08608102 | 2         | 0.53%   |
| 0x0800820d | 2         | 0.53%   |
| 0x06001119 | 2         | 0.53%   |
| 0x06000852 | 2         | 0.53%   |
| 0xa0655    | 1         | 0.27%   |
| 0x906a4    | 1         | 0.27%   |
| 0x90675    | 1         | 0.27%   |
| 0x806d1    | 1         | 0.27%   |
| 0x706e5    | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 13.78%  |
| Unknown          | 37        | 10%     |
| Zen 3            | 29        | 7.84%   |
| IvyBridge        | 28        | 7.57%   |
| Haswell          | 25        | 6.76%   |
| SandyBridge      | 24        | 6.49%   |
| TigerLake        | 20        | 5.41%   |
| Skylake          | 19        | 5.14%   |
| Penryn           | 16        | 4.32%   |
| Alderlake Hybrid | 13        | 3.51%   |
| Westmere         | 12        | 3.24%   |
| Piledriver       | 12        | 3.24%   |
| Zen 2            | 11        | 2.97%   |
| K10              | 11        | 2.97%   |
| Nehalem          | 7         | 1.89%   |
| Zen              | 6         | 1.62%   |
| Icelake          | 6         | 1.62%   |
| Core             | 6         | 1.62%   |
| Zen+             | 5         | 1.35%   |
| Goldmont plus    | 5         | 1.35%   |
| Excavator        | 5         | 1.35%   |
| Broadwell        | 5         | 1.35%   |
| CometLake        | 4         | 1.08%   |
| K10 Llano        | 3         | 0.81%   |
| Silvermont       | 2         | 0.54%   |
| Bulldozer        | 2         | 0.54%   |
| Steamroller      | 1         | 0.27%   |
| Puma             | 1         | 0.27%   |
| K8 Hammer        | 1         | 0.27%   |
| K8 & K10 hybrid  | 1         | 0.27%   |
| Jaguar           | 1         | 0.27%   |
| Goldmont         | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 192       | 43.64%  |
| Nvidia                     | 132       | 30%     |
| AMD                        | 111       | 25.23%  |
| Matrox Electronics Systems | 4         | 0.91%   |
| ASPEED Technology          | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 18        | 3.99%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 13        | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 13        | 2.88%   |
| AMD Lucienne                                                                | 13        | 2.88%   |
| Intel HD Graphics 630                                                       | 11        | 2.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11        | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 10        | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 8         | 1.77%   |
| Intel Core Processor Integrated Graphics Controller                         | 8         | 1.77%   |
| Intel HD Graphics 530                                                       | 7         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 1.33%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 6         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.11%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5         | 1.11%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5         | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 1.11%   |
| Intel UHD Graphics 620                                                      | 5         | 1.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 1.11%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 5         | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 0.89%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                             | 4         | 0.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 0.89%   |
| Intel Raptor Lake-S UHD Graphics                                            | 4         | 0.89%   |
| Intel HD Graphics 620                                                       | 4         | 0.89%   |
| Intel HD Graphics 5500                                                      | 4         | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 0.89%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4         | 0.89%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3         | 0.67%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 3         | 0.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.67%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 0.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| 1 x Intel        | 134       | 36.02%  |
| 1 x AMD          | 81        | 21.77%  |
| 1 x Nvidia       | 77        | 20.7%   |
| Intel + Nvidia   | 43        | 11.56%  |
| Intel + AMD      | 14        | 3.76%   |
| AMD + Nvidia     | 10        | 2.69%   |
| 2 x AMD          | 6         | 1.61%   |
| 1 x Matrox       | 3         | 0.81%   |
| Other            | 1         | 0.27%   |
| Nvidia + Matrox  | 1         | 0.27%   |
| 1 x ASPEED       | 1         | 0.27%   |
| AMD + 2 x Nvidia | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 296       | 79.14%  |
| Proprietary | 65        | 17.38%  |
| Unknown     | 13        | 3.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 271       | 71.5%   |
| 1.01-2.0   | 30        | 7.92%   |
| 0.01-0.5   | 25        | 6.6%    |
| 3.01-4.0   | 23        | 6.07%   |
| 7.01-8.0   | 10        | 2.64%   |
| 8.01-16.0  | 7         | 1.85%   |
| 0.51-1.0   | 5         | 1.32%   |
| 5.01-6.0   | 4         | 1.06%   |
| 2.01-3.0   | 2         | 0.53%   |
| 24.01-32.0 | 1         | 0.26%   |
| 16.01-24.0 | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 52        | 12.65%  |
| AU Optronics            | 37        | 9%      |
| LG Display              | 34        | 8.27%   |
| Chimei Innolux          | 34        | 8.27%   |
| BOE                     | 33        | 8.03%   |
| Goldstar                | 28        | 6.81%   |
| Dell                    | 19        | 4.62%   |
| BenQ                    | 17        | 4.14%   |
| Hewlett-Packard         | 16        | 3.89%   |
| AOC                     | 16        | 3.89%   |
| Philips                 | 11        | 2.68%   |
| Acer                    | 11        | 2.68%   |
| Lenovo                  | 9         | 2.19%   |
| Sharp                   | 7         | 1.7%    |
| Sony                    | 6         | 1.46%   |
| Fujitsu Siemens         | 6         | 1.46%   |
| Ancor Communications    | 6         | 1.46%   |
| ViewSonic               | 5         | 1.22%   |
| Iiyama                  | 5         | 1.22%   |
| Chi Mei Optoelectronics | 5         | 1.22%   |
| ASUSTek Computer        | 5         | 1.22%   |
| Unknown                 | 4         | 0.97%   |
| Apple                   | 4         | 0.97%   |
| PANDA                   | 3         | 0.73%   |
| Panasonic               | 3         | 0.73%   |
| Eizo                    | 3         | 0.73%   |
| CSO                     | 3         | 0.73%   |
| HKC                     | 2         | 0.49%   |
| Hitachi                 | 2         | 0.49%   |
| ___                     | 1         | 0.24%   |
| TTK                     | 1         | 0.24%   |
| Toshiba                 | 1         | 0.24%   |
| Sun                     | 1         | 0.24%   |
| SANYO                   | 1         | 0.24%   |
| RTK                     | 1         | 0.24%   |
| PXO                     | 1         | 0.24%   |
| Plain Tree Systems      | 1         | 0.24%   |
| Neso                    | 1         | 0.24%   |
| MStar                   | 1         | 0.24%   |
| MSI                     | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.71%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                       | 3         | 0.71%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                       | 3         | 0.71%   |
| Sony TV *00 SNY4904 3840x2160                                            | 2         | 0.48%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch        | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 2         | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.48%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.48%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                        | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.48%   |
| BOE LCD Monitor BOE0BB7 3840x2160 381x214mm 17.2-inch                    | 2         | 0.48%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.48%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 0.48%   |
| AU Optronics LCD Monitor AUOFA9B 1920x1200 301x188mm 14.0-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.48%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 2         | 0.48%   |
| AOC 2236 AOC2236 1920x1080 477x268mm 21.5-inch                           | 2         | 0.48%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.48%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                        | 2         | 0.48%   |
| ___ LCD TV ___9000 1360x768                                              | 1         | 0.24%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch            | 1         | 0.24%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch            | 1         | 0.24%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch             | 1         | 0.24%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch            | 1         | 0.24%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.24%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                     | 1         | 0.24%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.24%   |
| Unknown LCD Monitor KON TV_MONITOR 1920x1080                             | 1         | 0.24%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 0.24%   |
| TTK CCL250i TTK8541 1600x1200 408x306mm 20.1-inch                        | 1         | 0.24%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.24%   |
| Sun X7149A SUN058A 1600x1200 400x300mm 19.7-inch                         | 1         | 0.24%   |
| Sony TV SNYEE01 1920x1080                                                | 1         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 184       | 46.7%   |
| 1366x768 (WXGA)    | 48        | 12.18%  |
| 3840x2160 (4K)     | 36        | 9.14%   |
| 1920x1200 (WUXGA)  | 19        | 4.82%   |
| 1280x1024 (SXGA)   | 17        | 4.31%   |
| 2560x1440 (QHD)    | 16        | 4.06%   |
| 1600x900 (HD+)     | 16        | 4.06%   |
| 1440x900 (WXGA+)   | 10        | 2.54%   |
| 1680x1050 (WSXGA+) | 7         | 1.78%   |
| 2560x1600          | 6         | 1.52%   |
| 2560x1080          | 4         | 1.02%   |
| 1280x800 (WXGA)    | 4         | 1.02%   |
| 1024x768 (XGA)     | 4         | 1.02%   |
| 3840x1080          | 3         | 0.76%   |
| 1920x540           | 3         | 0.76%   |
| 1600x1200          | 3         | 0.76%   |
| Unknown            | 3         | 0.76%   |
| 3440x1440          | 2         | 0.51%   |
| 2880x1800          | 2         | 0.51%   |
| 1360x768           | 2         | 0.51%   |
| 2520x1680          | 1         | 0.25%   |
| 2288x1287          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 2160x1440          | 1         | 0.25%   |
| 2048x1152          | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 99        | 24.38%  |
| 24      | 41        | 10.1%   |
| 17      | 34        | 8.37%   |
| 27      | 32        | 7.88%   |
| 23      | 25        | 6.16%   |
| 14      | 22        | 5.42%   |
| 21      | 21        | 5.17%   |
| 19      | 16        | 3.94%   |
| 13      | 16        | 3.94%   |
| Unknown | 15        | 3.69%   |
| 31      | 14        | 3.45%   |
| 16      | 13        | 3.2%    |
| 72      | 5         | 1.23%   |
| 34      | 5         | 1.23%   |
| 22      | 5         | 1.23%   |
| 18      | 5         | 1.23%   |
| 12      | 5         | 1.23%   |
| 84      | 3         | 0.74%   |
| 54      | 3         | 0.74%   |
| 36      | 3         | 0.74%   |
| 20      | 3         | 0.74%   |
| 52      | 2         | 0.49%   |
| 40      | 2         | 0.49%   |
| 32      | 2         | 0.49%   |
| 28      | 2         | 0.49%   |
| 25      | 2         | 0.49%   |
| 142     | 1         | 0.25%   |
| 86      | 1         | 0.25%   |
| 75      | 1         | 0.25%   |
| 65      | 1         | 0.25%   |
| 50      | 1         | 0.25%   |
| 48      | 1         | 0.25%   |
| 43      | 1         | 0.25%   |
| 38      | 1         | 0.25%   |
| 35      | 1         | 0.25%   |
| 33      | 1         | 0.25%   |
| 11      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 139       | 34.66%  |
| 501-600        | 92        | 22.94%  |
| 351-400        | 44        | 10.97%  |
| 401-500        | 39        | 9.73%   |
| 601-700        | 21        | 5.24%   |
| 201-300        | 16        | 3.99%   |
| Unknown        | 15        | 3.74%   |
| 701-800        | 11        | 2.74%   |
| 1501-2000      | 9         | 2.24%   |
| 1001-1500      | 9         | 2.24%   |
| 801-900        | 4         | 1%      |
| More than 2000 | 1         | 0.25%   |
| 901-1000       | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 271       | 74.25%  |
| 16/10   | 50        | 13.7%   |
| 5/4     | 13        | 3.56%   |
| Unknown | 9         | 2.47%   |
| 4/3     | 8         | 2.19%   |
| 21/9    | 6         | 1.64%   |
| 3/2     | 3         | 0.82%   |
| 6/5     | 2         | 0.55%   |
| 32/9    | 1         | 0.27%   |
| 1.00    | 1         | 0.27%   |
| 0.56    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 25.5%   |
| 201-250        | 65        | 16.25%  |
| 81-90          | 31        | 7.75%   |
| 301-350        | 31        | 7.75%   |
| 351-500        | 26        | 6.5%    |
| 151-200        | 25        | 6.25%   |
| 121-130        | 23        | 5.75%   |
| More than 1000 | 19        | 4.75%   |
| 251-300        | 18        | 4.5%    |
| Unknown        | 15        | 3.75%   |
| 141-150        | 10        | 2.5%    |
| 111-120        | 10        | 2.5%    |
| 71-80          | 7         | 1.75%   |
| 501-1000       | 7         | 1.75%   |
| 61-70          | 5         | 1.25%   |
| 131-140        | 5         | 1.25%   |
| 51-60          | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 152       | 38.58%  |
| 121-160       | 105       | 26.65%  |
| 101-120       | 78        | 19.8%   |
| 161-240       | 24        | 6.09%   |
| Unknown       | 15        | 3.81%   |
| 1-50          | 13        | 3.3%    |
| More than 240 | 7         | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 287       | 76.94%  |
| 2     | 65        | 17.43%  |
| 0     | 17        | 4.56%   |
| 3     | 4         | 1.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 222       | 39.5%   |
| Intel                             | 184       | 32.74%  |
| Qualcomm Atheros                  | 41        | 7.3%    |
| Broadcom                          | 31        | 5.52%   |
| MediaTek                          | 12        | 2.14%   |
| Broadcom Limited                  | 6         | 1.07%   |
| ASIX Electronics                  | 5         | 0.89%   |
| TP-Link                           | 3         | 0.53%   |
| Samsung Electronics               | 3         | 0.53%   |
| Ralink Technology                 | 3         | 0.53%   |
| Ralink                            | 3         | 0.53%   |
| Nvidia                            | 3         | 0.53%   |
| Marvell Technology Group          | 3         | 0.53%   |
| ASUSTek Computer                  | 3         | 0.53%   |
| Aquantia                          | 3         | 0.53%   |
| Xiaomi                            | 2         | 0.36%   |
| Sierra Wireless                   | 2         | 0.36%   |
| QLogic                            | 2         | 0.36%   |
| OPPO Electronics                  | 2         | 0.36%   |
| Lenovo                            | 2         | 0.36%   |
| Edimax Technology                 | 2         | 0.36%   |
| DisplayLink                       | 2         | 0.36%   |
| Dell                              | 2         | 0.36%   |
| D-Link System                     | 2         | 0.36%   |
| Belkin Components                 | 2         | 0.36%   |
| AVM                               | 2         | 0.36%   |
| Wilocity                          | 1         | 0.18%   |
| U-Blox                            | 1         | 0.18%   |
| Sitecom Europe                    | 1         | 0.18%   |
| Qualcomm                          | 1         | 0.18%   |
| Mellanox Technologies             | 1         | 0.18%   |
| LSI                               | 1         | 0.18%   |
| Linksys                           | 1         | 0.18%   |
| ICS Advent                        | 1         | 0.18%   |
| Huawei Technologies               | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| ELATEC                            | 1         | 0.18%   |
| D-Link                            | 1         | 0.18%   |
| Atmel                             | 1         | 0.18%   |
| American Megatrends               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 161       | 24.17%  |
| Intel Wi-Fi 6 AX200                                                    | 22        | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 2.1%    |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 8         | 1.2%    |
| Intel Wireless 8260                                                    | 8         | 1.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.9%    |
| Intel I211 Gigabit Network Connection                                  | 6         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.75%   |
| Intel Wireless 7260                                                    | 5         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 5         | 0.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 5         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.75%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.75%   |
| Realtek 802.11ac NIC                                                   | 4         | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.6%    |
| Intel Wireless 7265                                                    | 4         | 0.6%    |
| Intel I210 Gigabit Network Connection                                  | 4         | 0.6%    |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.6%    |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.45%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 128       | 46.55%  |
| Realtek Semiconductor | 53        | 19.27%  |
| Qualcomm Atheros      | 34        | 12.36%  |
| Broadcom              | 15        | 5.45%   |
| MediaTek              | 11        | 4%      |
| Broadcom Limited      | 5         | 1.82%   |
| TP-Link               | 3         | 1.09%   |
| Ralink Technology     | 3         | 1.09%   |
| Ralink                | 3         | 1.09%   |
| ASUSTek Computer      | 3         | 1.09%   |
| Sierra Wireless       | 2         | 0.73%   |
| Edimax Technology     | 2         | 0.73%   |
| Dell                  | 2         | 0.73%   |
| D-Link System         | 2         | 0.73%   |
| Belkin Components     | 2         | 0.73%   |
| AVM                   | 2         | 0.73%   |
| Wilocity              | 1         | 0.36%   |
| Sitecom Europe        | 1         | 0.36%   |
| Qualcomm              | 1         | 0.36%   |
| Linksys               | 1         | 0.36%   |
| D-Link                | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 22        | 7.97%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 4.35%   |
| Intel Wireless 8260                                            | 8         | 2.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 8         | 2.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.54%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 2.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.81%   |
| Intel Wireless 7260                                            | 5         | 1.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 1.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 5         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.81%   |
| Realtek 802.11ac NIC                                           | 4         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.45%   |
| Intel Wireless 7265                                            | 4         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 1.09%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3         | 1.09%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 3         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.09%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.72%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 202       | 55.19%  |
| Intel                    | 102       | 27.87%  |
| Broadcom                 | 20        | 5.46%   |
| Qualcomm Atheros         | 10        | 2.73%   |
| ASIX Electronics         | 5         | 1.37%   |
| Nvidia                   | 3         | 0.82%   |
| Marvell Technology Group | 3         | 0.82%   |
| Aquantia                 | 3         | 0.82%   |
| Xiaomi                   | 2         | 0.55%   |
| Samsung Electronics      | 2         | 0.55%   |
| OPPO Electronics         | 2         | 0.55%   |
| Lenovo                   | 2         | 0.55%   |
| DisplayLink              | 2         | 0.55%   |
| QLogic                   | 1         | 0.27%   |
| MediaTek                 | 1         | 0.27%   |
| LSI                      | 1         | 0.27%   |
| ICS Advent               | 1         | 0.27%   |
| Huawei Technologies      | 1         | 0.27%   |
| Broadcom Limited         | 1         | 0.27%   |
| American Megatrends      | 1         | 0.27%   |
| 3Com                     | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 161       | 42.15%  |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 3.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 2.88%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 2.36%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.83%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.31%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 1.31%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.31%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 1.05%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 1.05%   |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 1.05%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.79%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.79%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.79%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.79%   |
| Intel Ethernet Connection (14) I219-V                                  | 3         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.52%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 0.52%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.52%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2         | 0.52%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.52%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.52%   |
| Intel 82567LF Gigabit Network Connection                               | 2         | 0.52%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 2         | 0.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 0.52%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 341       | 56.46%  |
| WiFi     | 255       | 42.22%  |
| Modem    | 5         | 0.83%   |
| Unknown  | 3         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 226       | 58.25%  |
| WiFi     | 162       | 41.75%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 197       | 53.24%  |
| 1     | 153       | 41.35%  |
| 3     | 11        | 2.97%   |
| 0     | 3         | 0.81%   |
| 5     | 2         | 0.54%   |
| 4     | 2         | 0.54%   |
| 8     | 1         | 0.27%   |
| 6     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 225       | 60.16%  |
| Yes  | 149       | 39.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 46.72%  |
| Realtek Semiconductor           | 33        | 14.41%  |
| Cambridge Silicon Radio         | 18        | 7.86%   |
| IMC Networks                    | 9         | 3.93%   |
| Foxconn / Hon Hai               | 9         | 3.93%   |
| Broadcom                        | 9         | 3.93%   |
| Qualcomm Atheros Communications | 8         | 3.49%   |
| Lite-On Technology              | 6         | 2.62%   |
| Hewlett-Packard                 | 5         | 2.18%   |
| Dell                            | 5         | 2.18%   |
| TP-Link                         | 4         | 1.75%   |
| Apple                           | 4         | 1.75%   |
| ASUSTek Computer                | 3         | 1.31%   |
| MediaTek                        | 2         | 0.87%   |
| Foxconn International           | 2         | 0.87%   |
| USI                             | 1         | 0.44%   |
| Realtek                         | 1         | 0.44%   |
| Ralink                          | 1         | 0.44%   |
| Integrated System Solution      | 1         | 0.44%   |
| Fujitsu                         | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 23        | 10.04%  |
| Intel Bluetooth wireless interface                  | 23        | 10.04%  |
| Intel AX201 Bluetooth                               | 22        | 9.61%   |
| Intel AX200 Bluetooth                               | 21        | 9.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 7.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 6.55%   |
| Intel AX211 Bluetooth                               | 9         | 3.93%   |
| Intel AX210 Bluetooth                               | 8         | 3.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.18%   |
| IMC Networks Wireless_Device                        | 5         | 2.18%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 4         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.31%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.31%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.31%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.31%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 0.87%   |
| MediaTek Wireless_Device                            | 2         | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.87%   |
| IMC Networks Bluetooth Device                       | 2         | 0.87%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.87%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.87%   |
| USI Bluetooth Device                                | 1         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.44%   |
| Realtek Bluetooth Radio                             | 1         | 0.44%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.44%   |
| Lite-On Wireless_Device                             | 1         | 0.44%   |
| Lite-On Bluetooth Device                            | 1         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 247       | 47.5%   |
| AMD                                  | 130       | 25%     |
| Nvidia                               | 91        | 17.5%   |
| C-Media Electronics                  | 10        | 1.92%   |
| GN Netcom                            | 4         | 0.77%   |
| Logitech                             | 3         | 0.58%   |
| DSEA A/S                             | 3         | 0.58%   |
| Creative Labs                        | 3         | 0.58%   |
| ASUSTek Computer                     | 3         | 0.58%   |
| Texas Instruments                    | 2         | 0.38%   |
| Plantronics                          | 2         | 0.38%   |
| Lenovo                               | 2         | 0.38%   |
| Yamaha                               | 1         | 0.19%   |
| Walmart                              | 1         | 0.19%   |
| VIA Technologies                     | 1         | 0.19%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.19%   |
| Sony                                 | 1         | 0.19%   |
| Schiit Audio                         | 1         | 0.19%   |
| RODE Microphones                     | 1         | 0.19%   |
| Realtek Semiconductor                | 1         | 0.19%   |
| Micro Star International             | 1         | 0.19%   |
| Kingston Technology                  | 1         | 0.19%   |
| Jieli Technology                     | 1         | 0.19%   |
| HiBy                                 | 1         | 0.19%   |
| Generalplus Technology               | 1         | 0.19%   |
| FiiO Electronics Technology          | 1         | 0.19%   |
| Elgato Systems                       | 1         | 0.19%   |
| Cambridge Audio                      | 1         | 0.19%   |
| Best Buy                             | 1         | 0.19%   |
| ASRock                               | 1         | 0.19%   |
| Arturia                              | 1         | 0.19%   |
| Unknown                              | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 48        | 7.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 33        | 5.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 27        | 4.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 3.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19        | 3.1%    |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 2.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 2.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 1.79%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9         | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 1.47%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.14%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 7         | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.98%   |
| Intel Raptor Lake High Definition Audio Controller                         | 6         | 0.98%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5         | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 0.82%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 0.82%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 0.82%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 5         | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 23.08%  |
| SK hynix            | 24        | 14.2%   |
| Micron Technology   | 23        | 13.61%  |
| Kingston            | 23        | 13.61%  |
| Corsair             | 14        | 8.28%   |
| Unknown             | 10        | 5.92%   |
| Crucial             | 9         | 5.33%   |
| G.Skill             | 5         | 2.96%   |
| Nanya Technology    | 4         | 2.37%   |
| Unknown (ABCD)      | 2         | 1.18%   |
| Team                | 2         | 1.18%   |
| Smart               | 2         | 1.18%   |
| Hewlett-Packard     | 2         | 1.18%   |
| Elpida              | 2         | 1.18%   |
| A-DATA Technology   | 2         | 1.18%   |
| Unknown             | 2         | 1.18%   |
| Unknown (0x0B45)    | 1         | 0.59%   |
| Silicon Power       | 1         | 0.59%   |
| Lexar               | 1         | 0.59%   |
| GOODRAM             | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 1.12%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 2         | 1.12%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 1.12%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.12%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.12%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.12%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.12%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.12%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s            | 2         | 1.12%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.12%   |
| Unknown                                                          | 2         | 1.12%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.56%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.56%   |
| Unknown (0x0B45) RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s | 1         | 0.56%   |
| Team RAM TEAMGROUP-UD4-2666 4GB DIMM DDR4                        | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.56%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 0.56%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.56%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.56%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 88        | 59.06%  |
| DDR3    | 30        | 20.13%  |
| DDR5    | 8         | 5.37%   |
| LPDDR4  | 7         | 4.7%    |
| LPDDR5  | 5         | 3.36%   |
| DDR2    | 4         | 2.68%   |
| SDRAM   | 3         | 2.01%   |
| Unknown | 2         | 1.34%   |
| LPDDR3  | 1         | 0.67%   |
| DDR     | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 80        | 53.69%  |
| DIMM         | 57        | 38.26%  |
| Row Of Chips | 12        | 8.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 69        | 43.95%  |
| 16384 | 34        | 21.66%  |
| 4096  | 26        | 16.56%  |
| 2048  | 17        | 10.83%  |
| 32768 | 9         | 5.73%   |
| 49152 | 1         | 0.64%   |
| 512   | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 45        | 27.95%  |
| 2667    | 23        | 14.29%  |
| 1600    | 17        | 10.56%  |
| 2400    | 13        | 8.07%   |
| 1333    | 8         | 4.97%   |
| 5600    | 6         | 3.73%   |
| 1334    | 6         | 3.73%   |
| 2133    | 5         | 3.11%   |
| 6400    | 4         | 2.48%   |
| 4267    | 3         | 1.86%   |
| 3600    | 3         | 1.86%   |
| 2933    | 3         | 1.86%   |
| 1867    | 3         | 1.86%   |
| 800     | 3         | 1.86%   |
| 2666    | 2         | 1.24%   |
| Unknown | 2         | 1.24%   |
| 7500    | 1         | 0.62%   |
| 6000    | 1         | 0.62%   |
| 4800    | 1         | 0.62%   |
| 4000    | 1         | 0.62%   |
| 3800    | 1         | 0.62%   |
| 3666    | 1         | 0.62%   |
| 3534    | 1         | 0.62%   |
| 3266    | 1         | 0.62%   |
| 3066    | 1         | 0.62%   |
| 3000    | 1         | 0.62%   |
| 2134    | 1         | 0.62%   |
| 2048    | 1         | 0.62%   |
| 1067    | 1         | 0.62%   |
| 975     | 1         | 0.62%   |
| 533     | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 28.57%  |
| Seiko Epson           | 5         | 23.81%  |
| Brother Industries    | 5         | 23.81%  |
| Xerox                 | 1         | 4.76%   |
| Samsung Electronics   | 1         | 4.76%   |
| Pantum                | 1         | 4.76%   |
| Lexmark International | 1         | 4.76%   |
| Dell                  | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Xerox WorkCentre 3220            | 1         | 4.76%   |
| Seiko Epson XP-4200 Series       | 1         | 4.76%   |
| Seiko Epson XP-4100 Series       | 1         | 4.76%   |
| Seiko Epson WF-4830 Series       | 1         | 4.76%   |
| Seiko Epson L300 Series          | 1         | 4.76%   |
| Seiko Epson ET-2820 Series       | 1         | 4.76%   |
| Samsung Phaser 3121              | 1         | 4.76%   |
| Pantum P2200-series              | 1         | 4.76%   |
| Lexmark International MC3224dwe  | 1         | 4.76%   |
| HP OfficeJet Pro 7720 series     | 1         | 4.76%   |
| HP OfficeJet 6950                | 1         | 4.76%   |
| HP LaserJet 1200                 | 1         | 4.76%   |
| HP LaserJet 1018                 | 1         | 4.76%   |
| HP Ink Tank 310 series           | 1         | 4.76%   |
| HP DeskJet 4100 series           | 1         | 4.76%   |
| Dell Laser Printer 1720          | 1         | 4.76%   |
| Brother Printer                  | 1         | 4.76%   |
| Brother MFC-7360N                | 1         | 4.76%   |
| Brother HL-L3230CDW series       | 1         | 4.76%   |
| Brother DCP-L2520DW              | 1         | 4.76%   |
| Brother DCP-7057 scanner/printer | 1         | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 220                       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 42        | 21.32%  |
| IMC Networks                           | 18        | 9.14%   |
| Logitech                               | 16        | 8.12%   |
| Realtek Semiconductor                  | 14        | 7.11%   |
| Microdia                               | 13        | 6.6%    |
| Bison Electronics                      | 11        | 5.58%   |
| Luxvisions Innotech Limited            | 10        | 5.08%   |
| Quanta                                 | 9         | 4.57%   |
| Syntek                                 | 8         | 4.06%   |
| Sunplus Innovation Technology          | 8         | 4.06%   |
| Suyin                                  | 7         | 3.55%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.54%   |
| Apple                                  | 4         | 2.03%   |
| Acer                                   | 4         | 2.03%   |
| Sonix Technology                       | 3         | 1.52%   |
| Primax Electronics                     | 3         | 1.52%   |
| Importek                               | 3         | 1.52%   |
| Generalplus Technology                 | 3         | 1.52%   |
| Z-Star Microelectronics                | 2         | 1.02%   |
| Microsoft                              | 2         | 1.02%   |
| Trust                                  | 1         | 0.51%   |
| SunplusIT                              | 1         | 0.51%   |
| Sunplus Technology                     | 1         | 0.51%   |
| Samsung Electronics                    | 1         | 0.51%   |
| Ricoh                                  | 1         | 0.51%   |
| Lite-On Technology                     | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| Jieli Technology                       | 1         | 0.51%   |
| icSpring                               | 1         | 0.51%   |
| Hewlett-Packard                        | 1         | 0.51%   |
| Creative Technology                    | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 9         | 4.57%   |
| Syntek Integrated Camera                                | 7         | 3.55%   |
| IMC Networks Integrated Camera                          | 6         | 3.05%   |
| Realtek Integrated_Webcam_HD                            | 5         | 2.54%   |
| Microdia Integrated_Webcam_HD                           | 5         | 2.54%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 2.54%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 2.03%   |
| Logitech Webcam C270                                    | 4         | 2.03%   |
| Chicony HD User Facing                                  | 4         | 2.03%   |
| Primax HP HD Webcam [Fixed]                             | 3         | 1.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera    | 3         | 1.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 3         | 1.52%   |
| Generalplus GENERAL WEBCAM                              | 3         | 1.52%   |
| Chicony HD Webcam                                       | 3         | 1.52%   |
| Bison Integrated Camera                                 | 3         | 1.52%   |
| Acer BisonCam,NB Pro                                    | 3         | 1.52%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.02%   |
| Quanta VGA WebCam                                       | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                          | 2         | 1.02%   |
| Quanta HD User Facing                                   | 2         | 1.02%   |
| Microsoft LifeCam HD-3000                               | 2         | 1.02%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.02%   |
| Microdia Integrated Webcam                              | 2         | 1.02%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 1.02%   |
| Logitech HD Webcam C525                                 | 2         | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 1.02%   |
| Chicony USB2.0 Camera                                   | 2         | 1.02%   |
| Chicony HP HD Camera                                    | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.02%   |
| Bison Lenovo Integrated Webcam                          | 2         | 1.02%   |
| Bison HD Webcam                                         | 2         | 1.02%   |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 1.02%   |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 0.51%   |
| Z-Star Integrated Camera                                | 1         | 0.51%   |
| Trust WB-6250X Webcam                                   | 1         | 0.51%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.51%   |
| Suyin USB 2.0 UVC 1.3M WebCam                           | 1         | 0.51%   |
| Suyin Sony Visual Communication Camera                  | 1         | 0.51%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.51%   |
| Suyin Integrated Webcam                                 | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 34.48%  |
| Validity Sensors           | 7         | 24.14%  |
| Shenzhen Goodix Technology | 5         | 17.24%  |
| Upek                       | 3         | 10.34%  |
| AuthenTec                  | 3         | 10.34%  |
| Next Biometrics            | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 13.79%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 10.34%  |
| Shenzhen Goodix  FingerPrint Device                      | 3         | 10.34%  |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 6.9%    |
| Validity Sensors Synaptics WBDI                          | 2         | 6.9%    |
| Synaptics UWP WBDI Device                                | 2         | 6.9%    |
| AuthenTec AES2810                                        | 2         | 6.9%    |
| Validity Sensors VFS491                                  | 1         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 3.45%   |
| Synaptics UWP WBDI                                       | 1         | 3.45%   |
| Synaptics  WBDI                                          | 1         | 3.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Synaptics Fingerprint scanner                            | 1         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 3.45%   |
| Shenzhen Goodix FingerPrint                              | 1         | 3.45%   |
| Next Biometrics NB-2020-U Fingerprint Reader             | 1         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 11        | 47.83%  |
| Alcor Micro      | 6         | 26.09%  |
| O2 Micro         | 2         | 8.7%    |
| Upek             | 1         | 4.35%   |
| SCM Microsystems | 1         | 4.35%   |
| Lenovo           | 1         | 4.35%   |
| CHERRY           | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 26.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 17.39%  |
| Broadcom 58200                                                               | 4         | 17.39%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.35%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.35%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 4.35%   |
| Broadcom 5880                                                                | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 247       | 65.69%  |
| 1     | 98        | 26.06%  |
| 2     | 27        | 7.18%   |
| 3     | 3         | 0.8%    |
| 4     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 38        | 24.2%   |
| Net/wireless             | 29        | 18.47%  |
| Fingerprint reader       | 29        | 18.47%  |
| Chipcard                 | 21        | 13.38%  |
| Sound                    | 10        | 6.37%   |
| Multimedia controller    | 9         | 5.73%   |
| Camera                   | 6         | 3.82%   |
| Card reader              | 4         | 2.55%   |
| Unassigned class         | 2         | 1.27%   |
| Net/ethernet             | 2         | 1.27%   |
| Communication controller | 2         | 1.27%   |
| Bluetooth                | 2         | 1.27%   |
| Network                  | 1         | 0.64%   |
| Modem                    | 1         | 0.64%   |
| Firewire controller      | 1         | 0.64%   |

