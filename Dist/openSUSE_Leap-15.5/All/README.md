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

Total: 571

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [60a56dbd2a](https://linux-hardware.org/?probe=60a56dbd2a) | Dec 30, 2025 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [5e836caa12](https://linux-hardware.org/?probe=5e836caa12) | Dec 26, 2025 |
| Sony          | VPCCW1S1R                   | Notebook    | [f71d59a1a5](https://linux-hardware.org/?probe=f71d59a1a5) | Dec 19, 2025 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [0063113a90](https://linux-hardware.org/?probe=0063113a90) | Sep 12, 2025 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [369bd41c30](https://linux-hardware.org/?probe=369bd41c30) | Aug 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [06190e5180](https://linux-hardware.org/?probe=06190e5180) | Jul 26, 2025 |
| Acer          | Aspire X1900                | Desktop     | [f6ecb29a33](https://linux-hardware.org/?probe=f6ecb29a33) | Jul 15, 2025 |
| HP            | 18E7                        | Desktop     | [23177af3cc](https://linux-hardware.org/?probe=23177af3cc) | Jul 03, 2025 |
| HP            | 3033h                       | Desktop     | [be66226e3c](https://linux-hardware.org/?probe=be66226e3c) | Jun 25, 2025 |
| HP            | 3033h                       | Desktop     | [1bd612ad75](https://linux-hardware.org/?probe=1bd612ad75) | Jun 25, 2025 |
| Gigabyte      | Q77M-D2H                    | Desktop     | [7b44c17fc8](https://linux-hardware.org/?probe=7b44c17fc8) | Jun 20, 2025 |
| HP            | G62                         | Notebook    | [6a0322a5ab](https://linux-hardware.org/?probe=6a0322a5ab) | May 30, 2025 |
| Acer          | Aspire 7741                 | Notebook    | [2af5d6fd28](https://linux-hardware.org/?probe=2af5d6fd28) | Apr 23, 2025 |
| Supermicro    | X11SSA-F                    | Server      | [f5ffac5798](https://linux-hardware.org/?probe=f5ffac5798) | Apr 07, 2025 |
| Dell          | System Inspiron N7110       | Notebook    | [b02db47dad](https://linux-hardware.org/?probe=b02db47dad) | Apr 07, 2025 |
| Supermicro    | X11SSA-F                    | Server      | [8e0effb213](https://linux-hardware.org/?probe=8e0effb213) | Mar 31, 2025 |
| VALE          | Notebook Classic C150       | Notebook    | [7fff17ecdd](https://linux-hardware.org/?probe=7fff17ecdd) | Mar 23, 2025 |
| VALE          | Notebook Classic C150       | Notebook    | [52703c9457](https://linux-hardware.org/?probe=52703c9457) | Mar 22, 2025 |
| Lenovo        | ThinkPad W520 4282A34       | Notebook    | [ff2833eb02](https://linux-hardware.org/?probe=ff2833eb02) | Mar 17, 2025 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [37433501ff](https://linux-hardware.org/?probe=37433501ff) | Mar 11, 2025 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [e4b77dd143](https://linux-hardware.org/?probe=e4b77dd143) | Mar 10, 2025 |
| HP            | 3033h                       | Desktop     | [1711bd8fe8](https://linux-hardware.org/?probe=1711bd8fe8) | Mar 07, 2025 |
| HP            | 3033h                       | Desktop     | [9a18f4fb45](https://linux-hardware.org/?probe=9a18f4fb45) | Mar 06, 2025 |
| Gigabyte      | Q77M-D2H                    | Desktop     | [7b93063347](https://linux-hardware.org/?probe=7b93063347) | Feb 24, 2025 |
| Acer          | Aspire E1-522               | Notebook    | [58bf5cc684](https://linux-hardware.org/?probe=58bf5cc684) | Feb 15, 2025 |
| Acer          | Nitro AN517-51              | Notebook    | [ea998b937e](https://linux-hardware.org/?probe=ea998b937e) | Jan 30, 2025 |
| HP            | 2AF7                        | Desktop     | [b8c3e68123](https://linux-hardware.org/?probe=b8c3e68123) | Jan 28, 2025 |
| HP            | 2AF7                        | Desktop     | [9182779a6f](https://linux-hardware.org/?probe=9182779a6f) | Jan 28, 2025 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [f67c294a33](https://linux-hardware.org/?probe=f67c294a33) | Jan 19, 2025 |
| Chatreey      | AC1-DP                      | Desktop     | [68a2c044bd](https://linux-hardware.org/?probe=68a2c044bd) | Jan 11, 2025 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [5ea80e9289](https://linux-hardware.org/?probe=5ea80e9289) | Jan 07, 2025 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.21-150500.53-default      | 71        | 16.47%  |
| 5.14.21-150500.55.52-default   | 45        | 10.44%  |
| 5.14.21-150500.55.19-default   | 41        | 9.51%   |
| 5.14.21-150500.55.39-default   | 33        | 7.66%   |
| 5.14.21-150500.55.36-default   | 33        | 7.66%   |
| 5.14.21-150500.55.49-default   | 23        | 5.34%   |
| 5.14.21-150500.55.65-default   | 22        | 5.1%    |
| 5.14.21-150500.55.31-default   | 20        | 4.64%   |
| 5.14.21-150500.55.7-default    | 16        | 3.71%   |
| 5.14.21-150500.55.59-default   | 16        | 3.71%   |
| 5.14.21-150500.55.88-default   | 15        | 3.48%   |
| 5.14.21-150500.55.68-default   | 14        | 3.25%   |
| 5.14.21-150500.55.12-default   | 12        | 2.78%   |
| 5.14.21-150500.55.28-default   | 11        | 2.55%   |
| 5.14.21-150500.55.44-default   | 10        | 2.32%   |
| 5.14.21-150500.55.83-default   | 9         | 2.09%   |
| 5.14.21-150500.55.73-default   | 9         | 2.09%   |
| 5.14.21-150500.52-default      | 9         | 2.09%   |
| 5.14.21-150500.55.62-default   | 5         | 1.16%   |
| 6.5.9-lp155.2-default          | 2         | 0.46%   |
| 5.14.21-150500.43-default      | 2         | 0.46%   |
| 5.14.21-150400.24.18-default   | 2         | 0.46%   |
| 6.8.9-1-default                | 1         | 0.23%   |
| 6.6.3-1-default                | 1         | 0.23%   |
| 6.6.11-lp155.3-default         | 1         | 0.23%   |
| 6.5.9-lp154.6-default          | 1         | 0.23%   |
| 6.5.4-1-default                | 1         | 0.23%   |
| 6.4.4-lp154.2.g919c802-default | 1         | 0.23%   |
| 5.14.21-150500.50-default      | 1         | 0.23%   |
| 5.14.21-150500.49-default      | 1         | 0.23%   |
| 5.14.21-150500.37-default      | 1         | 0.23%   |
| 5.14.21-150400.24.55-default   | 1         | 0.23%   |
| 5.14.21-150400.24.46-default   | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.21 | 377       | 97.92%  |
| 6.5.9   | 3         | 0.78%   |
| 6.8.9   | 1         | 0.26%   |
| 6.6.3   | 1         | 0.26%   |
| 6.6.11  | 1         | 0.26%   |
| 6.5.4   | 1         | 0.26%   |
| 6.4.4   | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 377       | 97.92%  |
| 6.5     | 4         | 1.04%   |
| 6.6     | 2         | 0.52%   |
| 6.8     | 1         | 0.26%   |
| 6.4     | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 382       | 99.74%  |
| aarch64 | 1         | 0.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 299       | 77.46%  |
| GNOME    | 55        | 14.25%  |
| XFCE     | 12        | 3.11%   |
| Unknown  | 6         | 1.55%   |
| Cinnamon | 3         | 0.78%   |
| MATE     | 2         | 0.52%   |
| ICEWM    | 2         | 0.52%   |
| Deepin   | 2         | 0.52%   |
| Trinity  | 1         | 0.26%   |
| LXQt     | 1         | 0.26%   |
| LXDE     | 1         | 0.26%   |
| KDE      | 1         | 0.26%   |
| Budgie   | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 325       | 83.33%  |
| Wayland | 50        | 12.82%  |
| Tty     | 13        | 3.33%   |
| Unknown | 2         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 246       | 63.73%  |
| SDDM    | 108       | 27.98%  |
| LightDM | 18        | 4.66%   |
| GDM     | 8         | 2.07%   |
| XDM     | 6         | 1.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 137       | 35.58%  |
| de_DE           | 101       | 26.23%  |
| POSIX           | 38        | 9.87%   |
| pt_BR           | 19        | 4.94%   |
| ru_RU           | 15        | 3.9%    |
| es_ES           | 13        | 3.38%   |
| fr_FR           | 9         | 2.34%   |
| nl_NL           | 8         | 2.08%   |
| pl_PL           | 7         | 1.82%   |
| it_IT           | 7         | 1.82%   |
| en_GB           | 7         | 1.82%   |
| hu_HU           | 3         | 0.78%   |
| C               | 3         | 0.78%   |
| zh_CN           | 2         | 0.52%   |
| sk_SK           | 2         | 0.52%   |
| en_DK           | 2         | 0.52%   |
| cs_CZ           | 2         | 0.52%   |
| pt_PT           | 1         | 0.26%   |
| ja_JP           | 1         | 0.26%   |
| fi_FI           | 1         | 0.26%   |
| es_DO           | 1         | 0.26%   |
| en_ZA           | 1         | 0.26%   |
| en_US.ISO8859-1 | 1         | 0.26%   |
| el_GR           | 1         | 0.26%   |
| da_DK           | 1         | 0.26%   |
| ar_AE           | 1         | 0.26%   |
| Unknown         | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 272       | 70.47%  |
| EFI  | 114       | 29.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 298       | 77.4%   |
| Ext4  | 73        | 18.96%  |
| Xfs   | 10        | 2.6%    |
| Tmpfs | 3         | 0.78%   |
| Zfs   | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 238       | 61.66%  |
| GPT     | 132       | 34.2%   |
| MBR     | 16        | 4.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 349       | 90.41%  |
| Yes       | 37        | 9.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 318       | 82.81%  |
| Yes       | 66        | 17.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 63        | 16.45%  |
| ASUSTek Computer        | 60        | 15.67%  |
| Lenovo                  | 52        | 13.58%  |
| Dell                    | 39        | 10.18%  |
| Gigabyte Technology     | 32        | 8.36%   |
| ASRock                  | 23        | 6.01%   |
| Acer                    | 23        | 6.01%   |
| MSI                     | 20        | 5.22%   |
| Intel                   | 6         | 1.57%   |
| Fujitsu                 | 6         | 1.57%   |
| Toshiba                 | 4         | 1.04%   |
| Sony                    | 4         | 1.04%   |
| Biostar                 | 4         | 1.04%   |
| Apple                   | 4         | 1.04%   |
| TUXEDO                  | 3         | 0.78%   |
| Medion                  | 3         | 0.78%   |
| Wortmann AG             | 2         | 0.52%   |
| System76                | 2         | 0.52%   |
| Samsung Electronics     | 2         | 0.52%   |
| Notebook                | 2         | 0.52%   |
| HUAWEI                  | 2         | 0.52%   |
| HC Technology.          | 2         | 0.52%   |
| Fujitsu Siemens         | 2         | 0.52%   |
| AZW                     | 2         | 0.52%   |
| Unknown                 | 2         | 0.52%   |
| VALE                    | 1         | 0.26%   |
| Supermicro              | 1         | 0.26%   |
| Schenker                | 1         | 0.26%   |
| Raspberry Pi Foundation | 1         | 0.26%   |
| Pegatron                | 1         | 0.26%   |
| Panasonic               | 1         | 0.26%   |
| OEM                     | 1         | 0.26%   |
| LG Electronics          | 1         | 0.26%   |
| ILLEGEAR                | 1         | 0.26%   |
| Google                  | 1         | 0.26%   |
| GEEKOM                  | 1         | 0.26%   |
| Framework               | 1         | 0.26%   |
| Foxconn                 | 1         | 0.26%   |
| Dynabook                | 1         | 0.26%   |
| Digibras                | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASUS M5A97 R2.0                                                                          | 3         | 0.78%   |
| Unknown                                                                                  | 3         | 0.78%   |
| TUXEDO Aura 15 Gen2                                                                      | 2         | 0.52%   |
| MSI MS-7A33                                                                              | 2         | 0.52%   |
| HP Z420 Workstation                                                                      | 2         | 0.52%   |
| HP Victus by Gaming Laptop 15-fb0xxx                                                     | 2         | 0.52%   |
| HP Notebook                                                                              | 2         | 0.52%   |
| HC Technology. HCAR5000-MI                                                               | 2         | 0.52%   |
| Gigabyte GA-MA770-UD3                                                                    | 2         | 0.52%   |
| Gigabyte B550M DS3H                                                                      | 2         | 0.52%   |
| AZW SER                                                                                  | 2         | 0.52%   |
| ASUS ROG STRIX X570-E GAMING                                                             | 2         | 0.52%   |
| ASUS H110M-A/M.2                                                                         | 2         | 0.52%   |
| Wortmann AG TERRA_MOBILE_1749                                                            | 1         | 0.26%   |
| Wortmann AG TERRA_MOBILE_1512/1712                                                       | 1         | 0.26%   |
| VALE Notebook Classic C150                                                               | 1         | 0.26%   |
| TUXEDO Pulse 15 Gen2                                                                     | 1         | 0.26%   |
| Toshiba Satellite R945                                                                   | 1         | 0.26%   |
| Toshiba Satellite Pro C70-A                                                              | 1         | 0.26%   |
| Toshiba Satellite C55D-A                                                                 | 1         | 0.26%   |
| Toshiba dynabook Satellite B552/H                                                        | 1         | 0.26%   |
| System76 Lemur Pro                                                                       | 1         | 0.26%   |
| System76 Bonobo WS                                                                       | 1         | 0.26%   |
| Supermicro Super Server                                                                  | 1         | 0.26%   |
| Sony VPCEH11FX                                                                           | 1         | 0.26%   |
| Sony VPCCW1S1R                                                                           | 1         | 0.26%   |
| Sony SVF1521A7EB                                                                         | 1         | 0.26%   |
| Schenker KEY (E23)                                                                       | 1         | 0.26%   |
| Samsung 730QFG                                                                           | 1         | 0.26%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.26%   |
| RPi rpi                                                                                  | 1         | 0.26%   |
| Pegatron NY603AA-ABA 300-1007                                                            | 1         | 0.26%   |
| Panasonic CF-C2CUGZXKM                                                                   | 1         | 0.26%   |
| OEM B75                                                                                  | 1         | 0.26%   |
| Notebook NS50_70MU                                                                       | 1         | 0.26%   |
| Notebook NLx0MU                                                                          | 1         | 0.26%   |
| MSI Summit E13FlipEvo A11MT                                                              | 1         | 0.26%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8)                                                           | 1         | 0.26%   |
| MSI MS-7D74                                                                              | 1         | 0.26%   |
| MSI MS-7D54                                                                              | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 23        | 6.01%   |
| Acer Aspire                | 16        | 4.18%   |
| Lenovo IdeaPad             | 9         | 2.35%   |
| Dell Precision             | 9         | 2.35%   |
| HP EliteBook               | 8         | 2.09%   |
| Dell Latitude              | 8         | 2.09%   |
| ASUS PRIME                 | 8         | 2.09%   |
| HP ENVY                    | 7         | 1.83%   |
| Dell OptiPlex              | 7         | 1.83%   |
| ASUS ROG                   | 7         | 1.83%   |
| HP Laptop                  | 6         | 1.57%   |
| Dell Inspiron              | 6         | 1.57%   |
| ASUS VivoBook              | 6         | 1.57%   |
| Lenovo ThinkCentre         | 5         | 1.31%   |
| Lenovo Legion              | 5         | 1.31%   |
| HP ProLiant                | 5         | 1.31%   |
| HP Pavilion                | 5         | 1.31%   |
| HP Compaq                  | 5         | 1.31%   |
| HP Victus                  | 4         | 1.04%   |
| Toshiba Satellite          | 3         | 0.78%   |
| Dell XPS                   | 3         | 0.78%   |
| Dell Vostro                | 3         | 0.78%   |
| ASUS M5A97                 | 3         | 0.78%   |
| Acer Nitro                 | 3         | 0.78%   |
| Unknown                    | 3         | 0.78%   |
| Wortmann AG TERRA          | 2         | 0.52%   |
| TUXEDO Aura                | 2         | 0.52%   |
| MSI MS-7A33                | 2         | 0.52%   |
| HP Z420                    | 2         | 0.52%   |
| HP ProDesk                 | 2         | 0.52%   |
| HP ProBook                 | 2         | 0.52%   |
| HP OMEN                    | 2         | 0.52%   |
| HP Notebook                | 2         | 0.52%   |
| HP EliteDesk               | 2         | 0.52%   |
| HC Technology. HCAR5000-MI | 2         | 0.52%   |
| Gigabyte GA-MA770-UD3      | 2         | 0.52%   |
| Gigabyte B550M             | 2         | 0.52%   |
| Gigabyte B450M             | 2         | 0.52%   |
| Fujitsu ESPRIMO            | 2         | 0.52%   |
| Dell System                | 2         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 38        | 9.92%   |
| 2020 | 35        | 9.14%   |
| 2022 | 28        | 7.31%   |
| 2019 | 27        | 7.05%   |
| 2013 | 27        | 7.05%   |
| 2012 | 27        | 7.05%   |
| 2015 | 25        | 6.53%   |
| 2018 | 24        | 6.27%   |
| 2010 | 24        | 6.27%   |
| 2023 | 23        | 6.01%   |
| 2011 | 21        | 5.48%   |
| 2017 | 18        | 4.7%    |
| 2016 | 16        | 4.18%   |
| 2014 | 14        | 3.66%   |
| 2009 | 13        | 3.39%   |
| 2008 | 12        | 3.13%   |
| 2007 | 6         | 1.57%   |
| 2006 | 3         | 0.78%   |
| 2024 | 2         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 188       | 49.09%  |
| Desktop        | 173       | 45.17%  |
| Convertible    | 7         | 1.83%   |
| Mini pc        | 5         | 1.31%   |
| Server         | 5         | 1.31%   |
| All in one     | 3         | 0.78%   |
| Other          | 1         | 0.26%   |
| System on chip | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 355       | 92.45%  |
| Enabled  | 29        | 7.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 380       | 99.22%  |
| Yes  | 3         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 90        | 23.32%  |
| 16.01-24.0      | 89        | 23.06%  |
| 8.01-16.0       | 72        | 18.65%  |
| 32.01-64.0      | 58        | 15.03%  |
| 3.01-4.0        | 38        | 9.84%   |
| 64.01-256.0     | 23        | 5.96%   |
| 24.01-32.0      | 7         | 1.81%   |
| 1.01-2.0        | 7         | 1.81%   |
| More than 256.0 | 1         | 0.26%   |
| 2.01-3.0        | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 135       | 32.61%  |
| 1.01-2.0   | 83        | 20.05%  |
| 4.01-8.0   | 80        | 19.32%  |
| 3.01-4.0   | 78        | 18.84%  |
| 8.01-16.0  | 22        | 5.31%   |
| 0.51-1.0   | 12        | 2.9%    |
| 16.01-24.0 | 3         | 0.72%   |
| 24.01-32.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 204       | 52.31%  |
| 2      | 101       | 25.9%   |
| 3      | 46        | 11.79%  |
| 4      | 18        | 4.62%   |
| 5      | 12        | 3.08%   |
| 6      | 6         | 1.54%   |
| 10     | 1         | 0.26%   |
| 8      | 1         | 0.26%   |
| 7      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 55.56%  |
| Yes       | 172       | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 350       | 91.38%  |
| No        | 33        | 8.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 267       | 69.17%  |
| No        | 119       | 30.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 233       | 60.05%  |
| No        | 155       | 39.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| Germany         | 111       | 28.98%  |
| USA             | 72        | 18.8%   |
| Brazil          | 22        | 5.74%   |
| Russia          | 19        | 4.96%   |
| Poland          | 11        | 2.87%   |
| Italy           | 10        | 2.61%   |
| Spain           | 9         | 2.35%   |
| Canada          | 8         | 2.09%   |
| UK              | 7         | 1.83%   |
| Netherlands     | 7         | 1.83%   |
| Switzerland     | 6         | 1.57%   |
| India           | 6         | 1.57%   |
| Greece          | 6         | 1.57%   |
| Mexico          | 5         | 1.31%   |
| France          | 5         | 1.31%   |
| Belgium         | 5         | 1.31%   |
| Australia       | 5         | 1.31%   |
| Sweden          | 4         | 1.04%   |
| Hungary         | 4         | 1.04%   |
| Finland         | 4         | 1.04%   |
| Czechia         | 4         | 1.04%   |
| Ukraine         | 3         | 0.78%   |
| Colombia        | 3         | 0.78%   |
| Argentina       | 3         | 0.78%   |
| South Africa    | 2         | 0.52%   |
| Slovenia        | 2         | 0.52%   |
| Slovakia        | 2         | 0.52%   |
| Serbia          | 2         | 0.52%   |
| Portugal        | 2         | 0.52%   |
| Malaysia        | 2         | 0.52%   |
| Hong Kong       | 2         | 0.52%   |
| China           | 2         | 0.52%   |
| Bulgaria        | 2         | 0.52%   |
| Austria         | 2         | 0.52%   |
| Vietnam         | 1         | 0.26%   |
| Venezuela       | 1         | 0.26%   |
| Türkiye        | 1         | 0.26%   |
| Turkey          | 1         | 0.26%   |
| The Netherlands | 1         | 0.26%   |
| South Korea     | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Munich               | 10        | 2.53%   |
| Berlin               | 7         | 1.77%   |
| Warsaw               | 5         | 1.26%   |
| Leipzig              | 4         | 1.01%   |
| Zurich               | 3         | 0.76%   |
| Vigo                 | 3         | 0.76%   |
| Stuttgart            | 3         | 0.76%   |
| St Petersburg        | 3         | 0.76%   |
| Sao Paulo            | 3         | 0.76%   |
| Milan                | 3         | 0.76%   |
| Kyiv                 | 3         | 0.76%   |
| Hamburg              | 3         | 0.76%   |
| Enschede             | 3         | 0.76%   |
| Budapest             | 3         | 0.76%   |
| Bremen               | 3         | 0.76%   |
| Zetel                | 2         | 0.51%   |
| Sydney               | 2         | 0.51%   |
| Sofia                | 2         | 0.51%   |
| Sao Vicente          | 2         | 0.51%   |
| Sacramento           | 2         | 0.51%   |
| Rüsselsheim am Main | 2         | 0.51%   |
| Rostock              | 2         | 0.51%   |
| Rio de Janeiro       | 2         | 0.51%   |
| Prague               | 2         | 0.51%   |
| Porto                | 2         | 0.51%   |
| Portland             | 2         | 0.51%   |
| Nuremberg            | 2         | 0.51%   |
| Neustadt             | 2         | 0.51%   |
| Mexico City          | 2         | 0.51%   |
| Ljubljana            | 2         | 0.51%   |
| Kuala Lumpur         | 2         | 0.51%   |
| Krakow               | 2         | 0.51%   |
| Kansas City          | 2         | 0.51%   |
| Johannesburg         | 2         | 0.51%   |
| Jacksonville         | 2         | 0.51%   |
| Ithaca               | 2         | 0.51%   |
| Heraklion            | 2         | 0.51%   |
| Hanover              | 2         | 0.51%   |
| Dresden              | 2         | 0.51%   |
| Denver               | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 99        | 147    | 16.45%  |
| Seagate                     | 91        | 155    | 15.12%  |
| WDC                         | 72        | 142    | 11.96%  |
| SanDisk                     | 37        | 50     | 6.15%   |
| Toshiba                     | 31        | 35     | 5.15%   |
| Kingston                    | 30        | 41     | 4.98%   |
| Crucial                     | 22        | 28     | 3.65%   |
| Hitachi                     | 20        | 24     | 3.32%   |
| Micron Technology           | 16        | 17     | 2.66%   |
| Unknown                     | 15        | 17     | 2.49%   |
| SK hynix                    | 15        | 17     | 2.49%   |
| Intel                       | 15        | 16     | 2.49%   |
| HGST                        | 9         | 10     | 1.5%    |
| China                       | 9         | 12     | 1.5%    |
| Silicon Motion              | 8         | 8      | 1.33%   |
| Micron/Crucial Technology   | 7         | 11     | 1.16%   |
| Kingston Technology Company | 7         | 9      | 1.16%   |
| Intenso                     | 7         | 8      | 1.16%   |
| A-DATA Technology           | 7         | 7      | 1.16%   |
| Phison Electronics          | 5         | 7      | 0.83%   |
| KIOXIA                      | 5         | 6      | 0.83%   |
| Apple                       | 5         | 6      | 0.83%   |
| SPCC                        | 4         | 4      | 0.66%   |
| ADATA Technology            | 4         | 4      | 0.66%   |
| XrayDisk                    | 3         | 4      | 0.5%    |
| PNY                         | 3         | 5      | 0.5%    |
| Hewlett-Packard             | 3         | 3      | 0.5%    |
| Fanxiang                    | 3         | 4      | 0.5%    |
| Dogfish                     | 3         | 3      | 0.5%    |
| Unknown                     | 3         | 5      | 0.5%    |
| Verbatim                    | 2         | 2      | 0.33%   |
| SABRENT                     | 2         | 2      | 0.33%   |
| Realtek Semiconductor       | 2         | 2      | 0.33%   |
| Netac                       | 2         | 4      | 0.33%   |
| LITEON                      | 2         | 2      | 0.33%   |
| Leven                       | 2         | 2      | 0.33%   |
| ASMT                        | 2         | 3      | 0.33%   |
| Yangtze Memory Technologies | 1         | 1      | 0.17%   |
| XSTAR                       | 1         | 1      | 0.17%   |
| USB                         | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 17        | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 13        | 1.96%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 7         | 1.06%   |
| Seagate ST500DM002-1BD142 500GB                       | 6         | 0.9%    |
| Samsung SSD 870 EVO 1TB                               | 6         | 0.9%    |
| Samsung SSD 840 EVO 250GB                             | 6         | 0.9%    |
| Kingston SA400S37480G 480GB SSD                       | 6         | 0.9%    |
| Intel SSD 660P Series 512GB                           | 6         | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 5         | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5         | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                        | 5         | 0.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 5         | 0.75%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 5         | 0.75%   |
| Kingston SA400S37120G 120GB SSD                       | 5         | 0.75%   |
| Unknown MMC Card  16GB                                | 4         | 0.6%    |
| Toshiba MQ01ABD100 1TB                                | 4         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 4         | 0.6%    |
| Samsung SSD 850 EVO 250GB                             | 4         | 0.6%    |
| Kingston SV300S37A120G 120GB SSD                      | 4         | 0.6%    |
| Crucial CT275MX300SSD1 275GB                          | 4         | 0.6%    |
| WDC WDS500G2B0A-00SM50 500GB                          | 3         | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3         | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 3         | 0.45%   |
| Toshiba DT01ACA050 500GB                              | 3         | 0.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 3         | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3         | 0.45%   |
| Seagate ST1000LM048-2E7172 1TB                        | 3         | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3         | 0.45%   |
| Seagate Expansion HDD 4TB                             | 3         | 0.45%   |
| Seagate Expansion 2TB                                 | 3         | 0.45%   |
| Samsung SSD 990 PRO 2TB                               | 3         | 0.45%   |
| Samsung SSD 860 EVO 1TB                               | 3         | 0.45%   |
| Samsung SSD 840 EVO 120GB                             | 3         | 0.45%   |
| Kingston Company A2000 NVMe SSD 250GB                 | 3         | 0.45%   |
| Kingston SA400S37240G 240GB SSD                       | 3         | 0.45%   |
| Unknown                                               | 3         | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                      | 2         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 0.3%    |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 2         | 0.3%    |
| WDC WD10EZRX-00A8LB0 1TB                              | 2         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 145    | 38.33%  |
| WDC                 | 61        | 117    | 26.87%  |
| Toshiba             | 23        | 25     | 10.13%  |
| Hitachi             | 20        | 24     | 8.81%   |
| Samsung Electronics | 12        | 14     | 5.29%   |
| HGST                | 9         | 10     | 3.96%   |
| Apple               | 4         | 4      | 1.76%   |
| Unknown             | 2         | 2      | 0.88%   |
| Hewlett-Packard     | 2         | 2      | 0.88%   |
| XrayDisk            | 1         | 1      | 0.44%   |
| Synology            | 1         | 1      | 0.44%   |
| SATAFIRM            | 1         | 1      | 0.44%   |
| Maxtor              | 1         | 2      | 0.44%   |
| Maxone              | 1         | 1      | 0.44%   |
| Fujitsu             | 1         | 2      | 0.44%   |
| ASMT                | 1         | 2      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 70     | 22.84%  |
| Kingston            | 24        | 31     | 12.18%  |
| Crucial             | 22        | 28     | 11.17%  |
| SanDisk             | 14        | 19     | 7.11%   |
| WDC                 | 13        | 24     | 6.6%    |
| China               | 9         | 12     | 4.57%   |
| A-DATA Technology   | 7         | 7      | 3.55%   |
| Intenso             | 6         | 6      | 3.05%   |
| Toshiba             | 4         | 5      | 2.03%   |
| SPCC                | 4         | 4      | 2.03%   |
| Micron Technology   | 4         | 4      | 2.03%   |
| Intel               | 4         | 5      | 2.03%   |
| PNY                 | 3         | 5      | 1.52%   |
| Dogfish             | 3         | 3      | 1.52%   |
| XrayDisk            | 2         | 3      | 1.02%   |
| SK hynix            | 2         | 2      | 1.02%   |
| SABRENT             | 2         | 2      | 1.02%   |
| Netac               | 2         | 4      | 1.02%   |
| LITEON              | 2         | 2      | 1.02%   |
| Leven               | 2         | 2      | 1.02%   |
| Fanxiang            | 2         | 3      | 1.02%   |
| Apple               | 2         | 2      | 1.02%   |
| Unknown             | 2         | 4      | 1.02%   |
| XSTAR               | 1         | 1      | 0.51%   |
| Verbatim            | 1         | 1      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| Team                | 1         | 2      | 0.51%   |
| T-FORCE             | 1         | 1      | 0.51%   |
| StoreJet            | 1         | 1      | 0.51%   |
| RESCUE              | 1         | 1      | 0.51%   |
| Radeon              | 1         | 1      | 0.51%   |
| Patriot             | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| GOODRAM             | 1         | 1      | 0.51%   |
| Gigabyte Technology | 1         | 1      | 0.51%   |
| FIKWOT              | 1         | 1      | 0.51%   |
| BAITITON            | 1         | 1      | 0.51%   |
| ASMT                | 1         | 1      | 0.51%   |
| AMD                 | 1         | 1      | 0.51%   |
| Acer                | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 171       | 353    | 33.4%   |
| SSD     | 166       | 265    | 32.42%  |
| NVMe    | 152       | 210    | 29.69%  |
| MMC     | 12        | 14     | 2.34%   |
| Unknown | 11        | 14     | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 268       | 573    | 57.63%  |
| NVMe | 152       | 207    | 32.69%  |
| SAS  | 33        | 62     | 7.1%    |
| MMC  | 12        | 14     | 2.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 182       | 276    | 48.28%  |
| 0.51-1.0   | 113       | 194    | 29.97%  |
| 1.01-2.0   | 42        | 81     | 11.14%  |
| 3.01-4.0   | 24        | 39     | 6.37%   |
| 4.01-10.0  | 9         | 20     | 2.39%   |
| 2.01-3.0   | 5         | 5      | 1.33%   |
| 10.01-20.0 | 2         | 3      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 141       | 35.7%   |
| 1001-2000      | 82        | 20.76%  |
| 501-1000       | 48        | 12.15%  |
| 2001-3000      | 46        | 11.65%  |
| 251-500        | 38        | 9.62%   |
| 101-250        | 26        | 6.58%   |
| 51-100         | 6         | 1.52%   |
| Unknown        | 4         | 1.01%   |
| 21-50          | 3         | 0.76%   |
| 1-20           | 1         | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 121       | 29.16%  |
| 51-100         | 68        | 16.39%  |
| 251-500        | 63        | 15.18%  |
| 501-1000       | 51        | 12.29%  |
| 1001-2000      | 35        | 8.43%   |
| 1-20           | 24        | 5.78%   |
| More than 3000 | 23        | 5.54%   |
| 21-50          | 19        | 4.58%   |
| 2001-3000      | 7         | 1.69%   |
| Unknown        | 4         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 10%     |
| Kingston SA400S37120G 120GB SSD                  | 2         | 4      | 10%     |
| Hitachi HTS545032B9A300 320GB                    | 2         | 2      | 10%     |
| WDC WD40EZRX-00SPEB0 4TB                         | 1         | 1      | 5%      |
| WDC WD2500BEVT-22A23T0 250GB                     | 1         | 1      | 5%      |
| WDC WD2002FAEX-007BA0 2TB                        | 1         | 1      | 5%      |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 5%      |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 5%      |
| Seagate ST4000NM0035-1V4107 4TB                  | 1         | 1      | 5%      |
| Samsung Electronics SSD 840 EVO 120GB            | 1         | 1      | 5%      |
| Samsung Electronics MZALQ256HBJD-00BL2 256GB     | 1         | 1      | 5%      |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1         | 1      | 5%      |
| Maxtor 6Y120M0 122GB                             | 1         | 2      | 5%      |
| Intel SSD 600P Series 1024GB                     | 1         | 1      | 5%      |
| Hitachi HTS727550A9E364 500GB                    | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 5%      |
| Crucial CT240M500SSD1 240GB                      | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 21.05%  |
| WDC                 | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| Samsung Electronics | 2         | 3      | 10.53%  |
| Kingston            | 2         | 4      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |
| Maxtor              | 1         | 2      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 30.77%  |
| WDC     | 3         | 3      | 23.08%  |
| Hitachi | 3         | 3      | 23.08%  |
| Toshiba | 1         | 1      | 7.69%   |
| Maxtor  | 1         | 2      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 14     | 66.67%  |
| SSD  | 4         | 7      | 22.22%  |
| NVMe | 2         | 2      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 250       | 581    | 61.27%  |
| Works    | 140       | 250    | 34.31%  |
| Malfunc  | 17        | 23     | 4.17%   |
| Failed   | 1         | 2      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 244       | 46.92%  |
| AMD                           | 86        | 16.54%  |
| Samsung Electronics           | 51        | 9.81%   |
| SanDisk                       | 24        | 4.62%   |
| SK hynix                      | 13        | 2.5%    |
| Kingston Technology Company   | 13        | 2.5%    |
| Micron Technology             | 12        | 2.31%   |
| Silicon Motion                | 8         | 1.54%   |
| ASMedia Technology            | 8         | 1.54%   |
| Micron/Crucial Technology     | 7         | 1.35%   |
| Marvell Technology Group      | 6         | 1.15%   |
| JMicron Technology            | 6         | 1.15%   |
| Toshiba America Info Systems  | 5         | 0.96%   |
| Phison Electronics            | 5         | 0.96%   |
| KIOXIA                        | 5         | 0.96%   |
| Seagate Technology            | 4         | 0.77%   |
| Nvidia                        | 4         | 0.77%   |
| Broadcom / LSI                | 4         | 0.77%   |
| ADATA Technology              | 4         | 0.77%   |
| Union Memory (Shenzhen)       | 2         | 0.38%   |
| Realtek Semiconductor         | 2         | 0.38%   |
| Yangtze Memory Technologies   | 1         | 0.19%   |
| VIA Technologies              | 1         | 0.19%   |
| MAXIO Technology (Hangzhou)   | 1         | 0.19%   |
| Integrated Technology Express | 1         | 0.19%   |
| Hewlett-Packard               | 1         | 0.19%   |
| Adaptec                       | 1         | 0.19%   |
| Unknown                       | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 44        | 7.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 2.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 2.45%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 14        | 2.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 13        | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11        | 1.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.8%    |
| AMD 400 Series Chipset SATA Controller                                         | 11        | 1.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.47%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8         | 1.31%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 1.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 0.98%   |
| Intel SSD 660P Series                                                          | 6         | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.98%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 6         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 0.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5         | 0.82%   |
| Intel SATA Controller [RAID Mode]                                              | 5         | 0.82%   |
| Intel RST Volume Management Device Controller                                  | 5         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5         | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.82%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 5         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 289       | 53.52%  |
| NVMe | 152       | 28.15%  |
| IDE  | 53        | 9.81%   |
| RAID | 38        | 7.04%   |
| SAS  | 7         | 1.3%    |
| SCSI | 1         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 271       | 70.76%  |
| AMD    | 111       | 28.98%  |
| ARM    | 1         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 8         | 2.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 7         | 1.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 6         | 1.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 6         | 1.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 6         | 1.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 5         | 1.31%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 5         | 1.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 4         | 1.04%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 4         | 1.04%   |
| AMD Ryzen 5 5600X 6-Core Processor       | 4         | 1.04%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 4         | 1.04%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 3         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 3         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 3         | 0.78%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 3         | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 3         | 0.78%   |
| Intel 13th Gen Core i9-13900HX           | 3         | 0.78%   |
| AMD Ryzen 7 5700G with Radeon Graphics   | 3         | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 3         | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 3         | 0.78%   |
| Intel Xeon CPU X5650 @ 2.67GHz           | 2         | 0.52%   |
| Intel Xeon CPU E5-1603 0 @ 2.80GHz       | 2         | 0.52%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 0.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 2         | 0.52%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 2         | 0.52%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 2         | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz        | 2         | 0.52%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 2         | 0.52%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 2         | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 2         | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 0.52%   |
| Intel Core i3-7100T CPU @ 3.40GHz        | 2         | 0.52%   |
| Intel Core i3 CPU M 380 @ 2.53GHz        | 2         | 0.52%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz    | 2         | 0.52%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 2         | 0.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 2         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 16.97%  |
| Intel Core i7           | 61        | 15.93%  |
| Other                   | 51        | 13.32%  |
| AMD Ryzen 5             | 32        | 8.36%   |
| Intel Core i3           | 25        | 6.53%   |
| Intel Xeon              | 20        | 5.22%   |
| AMD Ryzen 7             | 20        | 5.22%   |
| Intel Celeron           | 13        | 3.39%   |
| Intel Core 2 Duo        | 11        | 2.87%   |
| AMD FX                  | 11        | 2.87%   |
| Intel Pentium           | 10        | 2.61%   |
| AMD Ryzen 9             | 9         | 2.35%   |
| AMD A6                  | 6         | 1.57%   |
| Intel Core 2 Quad       | 5         | 1.31%   |
| AMD Phenom II X6        | 4         | 1.04%   |
| AMD A8                  | 4         | 1.04%   |
| AMD Ryzen 7 PRO         | 3         | 0.78%   |
| AMD Ryzen 3             | 3         | 0.78%   |
| AMD A4                  | 3         | 0.78%   |
| Intel Pentium Silver    | 2         | 0.52%   |
| Intel Pentium Dual-Core | 2         | 0.52%   |
| Intel Pentium Dual      | 2         | 0.52%   |
| Intel Core i9           | 2         | 0.52%   |
| AMD Phenom II X4        | 2         | 0.52%   |
| AMD Phenom              | 2         | 0.52%   |
| AMD Athlon              | 2         | 0.52%   |
| Intel Pentium Gold      | 1         | 0.26%   |
| Intel Core 2 Extreme    | 1         | 0.26%   |
| Intel Core 2            | 1         | 0.26%   |
| AMD Ryzen Threadripper  | 1         | 0.26%   |
| AMD Ryzen 5 PRO         | 1         | 0.26%   |
| AMD Ryzen 3 PRO         | 1         | 0.26%   |
| AMD Opteron             | 1         | 0.26%   |
| AMD Athlon X4           | 1         | 0.26%   |
| AMD Athlon X2           | 1         | 0.26%   |
| AMD Athlon II X4        | 1         | 0.26%   |
| AMD Athlon II X3        | 1         | 0.26%   |
| AMD Athlon II X2        | 1         | 0.26%   |
| AMD Athlon 64 X2        | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 135       | 35.25%  |
| 2       | 111       | 28.98%  |
| 6       | 57        | 14.88%  |
| 8       | 31        | 8.09%   |
| 12      | 15        | 3.92%   |
| 16      | 7         | 1.83%   |
| 10      | 6         | 1.57%   |
| 24      | 4         | 1.04%   |
| 14      | 4         | 1.04%   |
| 1       | 4         | 1.04%   |
| 20      | 3         | 0.78%   |
| 3       | 3         | 0.78%   |
| 64      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 375       | 97.91%  |
| 2       | 6         | 1.57%   |
| 4       | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 275       | 71.8%   |
| 1       | 107       | 27.94%  |
| Unknown | 1         | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 383       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 227       | 58.51%  |
| 0x806c1    | 12        | 3.09%   |
| 0x906ea    | 8         | 2.06%   |
| 0x906e9    | 8         | 2.06%   |
| 0x1067a    | 8         | 2.06%   |
| 0x08608103 | 8         | 2.06%   |
| 0xb0671    | 7         | 1.8%    |
| 0x806ec    | 7         | 1.8%    |
| 0x0a50000d | 6         | 1.55%   |
| 0x506e3    | 5         | 1.29%   |
| 0x306c3    | 5         | 1.29%   |
| 0x306a9    | 5         | 1.29%   |
| 0x406e3    | 4         | 1.03%   |
| 0x206a7    | 4         | 1.03%   |
| 0xb06a2    | 3         | 0.77%   |
| 0xa0671    | 3         | 0.77%   |
| 0x806ea    | 3         | 0.77%   |
| 0x206d7    | 3         | 0.77%   |
| 0x20655    | 3         | 0.77%   |
| 0x0a50000c | 3         | 0.77%   |
| 0x08600106 | 3         | 0.77%   |
| 0x906ed    | 2         | 0.52%   |
| 0x906a3    | 2         | 0.52%   |
| 0x806e9    | 2         | 0.52%   |
| 0x806c2    | 2         | 0.52%   |
| 0x706e5    | 2         | 0.52%   |
| 0x706a8    | 2         | 0.52%   |
| 0x40651    | 2         | 0.52%   |
| 0x106e5    | 2         | 0.52%   |
| 0x0a601203 | 2         | 0.52%   |
| 0x0a20120a | 2         | 0.52%   |
| 0x08701021 | 2         | 0.52%   |
| 0x08608102 | 2         | 0.52%   |
| 0x0800820d | 2         | 0.52%   |
| 0x06001119 | 2         | 0.52%   |
| 0x06000852 | 2         | 0.52%   |
| 0xa0655    | 1         | 0.26%   |
| 0x906a4    | 1         | 0.26%   |
| 0x90675    | 1         | 0.26%   |
| 0x806d1    | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 52        | 13.58%  |
| Unknown          | 37        | 9.66%   |
| Zen 3            | 29        | 7.57%   |
| IvyBridge        | 29        | 7.57%   |
| Haswell          | 26        | 6.79%   |
| SandyBridge      | 25        | 6.53%   |
| TigerLake        | 21        | 5.48%   |
| Skylake          | 20        | 5.22%   |
| Penryn           | 18        | 4.7%    |
| Westmere         | 13        | 3.39%   |
| Alderlake Hybrid | 13        | 3.39%   |
| Piledriver       | 12        | 3.13%   |
| Zen 2            | 11        | 2.87%   |
| K10              | 11        | 2.87%   |
| Nehalem          | 7         | 1.83%   |
| Icelake          | 7         | 1.83%   |
| Core             | 7         | 1.83%   |
| Zen              | 6         | 1.57%   |
| Goldmont plus    | 6         | 1.57%   |
| Zen+             | 5         | 1.31%   |
| Excavator        | 5         | 1.31%   |
| Broadwell        | 5         | 1.31%   |
| CometLake        | 4         | 1.04%   |
| K10 Llano        | 3         | 0.78%   |
| Silvermont       | 2         | 0.52%   |
| Jaguar           | 2         | 0.52%   |
| Bulldozer        | 2         | 0.52%   |
| Steamroller      | 1         | 0.26%   |
| Puma             | 1         | 0.26%   |
| K8 Hammer        | 1         | 0.26%   |
| K8 & K10 hybrid  | 1         | 0.26%   |
| Goldmont         | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 200       | 43.96%  |
| Nvidia                     | 135       | 29.67%  |
| AMD                        | 114       | 25.05%  |
| Matrox Electronics Systems | 4         | 0.88%   |
| ASPEED Technology          | 2         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 19        | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14        | 3%      |
| Intel 3rd Gen Core processor Graphics Controller                            | 13        | 2.79%   |
| AMD Lucienne                                                                | 13        | 2.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11        | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 10        | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                         | 9         | 1.93%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 8         | 1.72%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 8         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 1.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 6         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 1.29%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 6         | 1.29%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 6         | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5         | 1.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 1.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 1.07%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 5         | 1.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5         | 1.07%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 5         | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4         | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 0.86%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                             | 4         | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 0.86%   |
| Intel Raptor Lake-S UHD Graphics                                            | 4         | 0.86%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 4         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 0.86%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 4         | 0.86%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4         | 0.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3         | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 3         | 0.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.64%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| 1 x Intel        | 141       | 36.62%  |
| 1 x AMD          | 83        | 21.56%  |
| 1 x Nvidia       | 79        | 20.52%  |
| Intel + Nvidia   | 43        | 11.17%  |
| Intel + AMD      | 15        | 3.9%    |
| AMD + Nvidia     | 10        | 2.6%    |
| 2 x AMD          | 6         | 1.56%   |
| 1 x Matrox       | 3         | 0.78%   |
| Other            | 1         | 0.26%   |
| Nvidia + Matrox  | 1         | 0.26%   |
| Nvidia + ASPEED  | 1         | 0.26%   |
| 1 x ASPEED       | 1         | 0.26%   |
| AMD + 2 x Nvidia | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 319       | 82.22%  |
| Proprietary | 56        | 14.43%  |
| Unknown     | 13        | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 281       | 71.68%  |
| 1.01-2.0   | 31        | 7.91%   |
| 0.01-0.5   | 26        | 6.63%   |
| 3.01-4.0   | 23        | 5.87%   |
| 7.01-8.0   | 10        | 2.55%   |
| 8.01-16.0  | 7         | 1.79%   |
| 0.51-1.0   | 6         | 1.53%   |
| 5.01-6.0   | 4         | 1.02%   |
| 2.01-3.0   | 2         | 0.51%   |
| 24.01-32.0 | 1         | 0.26%   |
| 16.01-24.0 | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 54        | 12.74%  |
| AU Optronics            | 37        | 8.73%   |
| LG Display              | 36        | 8.49%   |
| BOE                     | 35        | 8.25%   |
| Chimei Innolux          | 34        | 8.02%   |
| Goldstar                | 29        | 6.84%   |
| Dell                    | 19        | 4.48%   |
| BenQ                    | 18        | 4.25%   |
| Hewlett-Packard         | 17        | 4.01%   |
| AOC                     | 16        | 3.77%   |
| Acer                    | 12        | 2.83%   |
| Philips                 | 11        | 2.59%   |
| Lenovo                  | 9         | 2.12%   |
| Sony                    | 7         | 1.65%   |
| Sharp                   | 7         | 1.65%   |
| Ancor Communications    | 7         | 1.65%   |
| Fujitsu Siemens         | 6         | 1.42%   |
| Chi Mei Optoelectronics | 6         | 1.42%   |
| ViewSonic               | 5         | 1.18%   |
| Iiyama                  | 5         | 1.18%   |
| ASUSTek Computer        | 5         | 1.18%   |
| Unknown                 | 4         | 0.94%   |
| Apple                   | 4         | 0.94%   |
| PANDA                   | 3         | 0.71%   |
| Panasonic               | 3         | 0.71%   |
| Eizo                    | 3         | 0.71%   |
| CSO                     | 3         | 0.71%   |
| HKC                     | 2         | 0.47%   |
| Hitachi                 | 2         | 0.47%   |
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

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.69%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.69%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                       | 3         | 0.69%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 3         | 0.69%   |
| Sony TV *00 SNY4904 3840x2160                                            | 2         | 0.46%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch        | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 2         | 0.46%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.46%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                        | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.46%   |
| BOE LCD Monitor BOE0BB7 3840x2160 381x214mm 17.2-inch                    | 2         | 0.46%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                       | 2         | 0.46%   |
| AU Optronics LCD Monitor AUOFA9B 1920x1200 301x188mm 14.0-inch           | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.46%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 2         | 0.46%   |
| AOC 2236 AOC2236 1920x1080 477x268mm 21.5-inch                           | 2         | 0.46%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.46%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch         | 2         | 0.46%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                        | 2         | 0.46%   |
| ___ LCD TV ___9000 1360x768                                              | 1         | 0.23%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch            | 1         | 0.23%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch            | 1         | 0.23%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch             | 1         | 0.23%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch            | 1         | 0.23%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.23%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                     | 1         | 0.23%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.23%   |
| Unknown LCD Monitor KON TV_MONITOR 1920x1080                             | 1         | 0.23%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 0.23%   |
| TTK CCL250i TTK8541 1600x1200 408x306mm 20.1-inch                        | 1         | 0.23%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 190       | 46.8%   |
| 1366x768 (WXGA)    | 51        | 12.56%  |
| 3840x2160 (4K)     | 37        | 9.11%   |
| 1920x1200 (WUXGA)  | 19        | 4.68%   |
| 1600x900 (HD+)     | 17        | 4.19%   |
| 1280x1024 (SXGA)   | 17        | 4.19%   |
| 2560x1440 (QHD)    | 16        | 3.94%   |
| 1440x900 (WXGA+)   | 11        | 2.71%   |
| 1680x1050 (WSXGA+) | 7         | 1.72%   |
| 2560x1600          | 6         | 1.48%   |
| 2560x1080          | 4         | 0.99%   |
| 1280x800 (WXGA)    | 4         | 0.99%   |
| 1024x768 (XGA)     | 4         | 0.99%   |
| 3840x1080          | 3         | 0.74%   |
| 1920x540           | 3         | 0.74%   |
| 1600x1200          | 3         | 0.74%   |
| Unknown            | 3         | 0.74%   |
| 3440x1440          | 2         | 0.49%   |
| 2880x1800          | 2         | 0.49%   |
| 1360x768           | 2         | 0.49%   |
| 2520x1680          | 1         | 0.25%   |
| 2288x1287          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 2160x1440          | 1         | 0.25%   |
| 2048x1152          | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 103       | 24.58%  |
| 24      | 42        | 10.02%  |
| 17      | 36        | 8.59%   |
| 27      | 32        | 7.64%   |
| 23      | 27        | 6.44%   |
| 21      | 22        | 5.25%   |
| 14      | 22        | 5.25%   |
| 19      | 17        | 4.06%   |
| 13      | 16        | 3.82%   |
| Unknown | 15        | 3.58%   |
| 31      | 14        | 3.34%   |
| 16      | 13        | 3.1%    |
| 72      | 5         | 1.19%   |
| 22      | 5         | 1.19%   |
| 18      | 5         | 1.19%   |
| 12      | 5         | 1.19%   |
| 84      | 3         | 0.72%   |
| 54      | 3         | 0.72%   |
| 36      | 3         | 0.72%   |
| 34      | 3         | 0.72%   |
| 20      | 3         | 0.72%   |
| 65      | 2         | 0.48%   |
| 63      | 2         | 0.48%   |
| 52      | 2         | 0.48%   |
| 43      | 2         | 0.48%   |
| 40      | 2         | 0.48%   |
| 32      | 2         | 0.48%   |
| 28      | 2         | 0.48%   |
| 25      | 2         | 0.48%   |
| 142     | 1         | 0.24%   |
| 86      | 1         | 0.24%   |
| 75      | 1         | 0.24%   |
| 50      | 1         | 0.24%   |
| 48      | 1         | 0.24%   |
| 38      | 1         | 0.24%   |
| 35      | 1         | 0.24%   |
| 33      | 1         | 0.24%   |
| 11      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 143       | 34.62%  |
| 501-600        | 93        | 22.52%  |
| 351-400        | 46        | 11.14%  |
| 401-500        | 41        | 9.93%   |
| 601-700        | 22        | 5.33%   |
| 201-300        | 16        | 3.87%   |
| Unknown        | 15        | 3.63%   |
| 1001-1500      | 12        | 2.91%   |
| 701-800        | 9         | 2.18%   |
| 1501-2000      | 9         | 2.18%   |
| 801-900        | 4         | 0.97%   |
| 901-1000       | 2         | 0.48%   |
| More than 2000 | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 284       | 75.53%  |
| 16/10   | 51        | 13.56%  |
| 5/4     | 13        | 3.46%   |
| Unknown | 9         | 2.39%   |
| 4/3     | 7         | 1.86%   |
| 21/9    | 4         | 1.06%   |
| 3/2     | 3         | 0.8%    |
| 6/5     | 2         | 0.53%   |
| 32/9    | 1         | 0.27%   |
| 1.00    | 1         | 0.27%   |
| 0.56    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 105       | 25.49%  |
| 201-250        | 68        | 16.5%   |
| 301-350        | 32        | 7.77%   |
| 81-90          | 31        | 7.52%   |
| 151-200        | 26        | 6.31%   |
| 121-130        | 25        | 6.07%   |
| 351-500        | 23        | 5.58%   |
| More than 1000 | 22        | 5.34%   |
| 251-300        | 18        | 4.37%   |
| Unknown        | 15        | 3.64%   |
| 141-150        | 10        | 2.43%   |
| 111-120        | 10        | 2.43%   |
| 501-1000       | 8         | 1.94%   |
| 71-80          | 7         | 1.7%    |
| 61-70          | 5         | 1.21%   |
| 131-140        | 5         | 1.21%   |
| 51-60          | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 155       | 38.27%  |
| 121-160       | 108       | 26.67%  |
| 101-120       | 80        | 19.75%  |
| 161-240       | 24        | 5.93%   |
| 1-50          | 16        | 3.95%   |
| Unknown       | 15        | 3.7%    |
| More than 240 | 7         | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 299       | 77.46%  |
| 2     | 66        | 17.1%   |
| 0     | 17        | 4.4%    |
| 3     | 4         | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 226       | 38.5%   |
| Intel                             | 194       | 33.05%  |
| Qualcomm Atheros                  | 43        | 7.33%   |
| Broadcom                          | 31        | 5.28%   |
| MediaTek                          | 12        | 2.04%   |
| Broadcom Limited                  | 6         | 1.02%   |
| ASIX Electronics                  | 5         | 0.85%   |
| TP-Link                           | 4         | 0.68%   |
| Ralink Technology                 | 4         | 0.68%   |
| Ralink                            | 4         | 0.68%   |
| Marvell Technology Group          | 4         | 0.68%   |
| ASUSTek Computer                  | 4         | 0.68%   |
| Samsung Electronics               | 3         | 0.51%   |
| Nvidia                            | 3         | 0.51%   |
| D-Link System                     | 3         | 0.51%   |
| Aquantia                          | 3         | 0.51%   |
| Xiaomi                            | 2         | 0.34%   |
| Sierra Wireless                   | 2         | 0.34%   |
| Shenzhen Goodix Technology        | 2         | 0.34%   |
| QLogic                            | 2         | 0.34%   |
| OPPO Electronics                  | 2         | 0.34%   |
| Lenovo                            | 2         | 0.34%   |
| Edimax Technology                 | 2         | 0.34%   |
| DisplayLink                       | 2         | 0.34%   |
| Dell                              | 2         | 0.34%   |
| D-Link                            | 2         | 0.34%   |
| Belkin Components                 | 2         | 0.34%   |
| AVM                               | 2         | 0.34%   |
| Wilocity                          | 1         | 0.17%   |
| U-Blox                            | 1         | 0.17%   |
| Sitecom Europe                    | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| Mellanox Technologies             | 1         | 0.17%   |
| LSI                               | 1         | 0.17%   |
| Linksys                           | 1         | 0.17%   |
| ICS Advent                        | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| ELATEC                            | 1         | 0.17%   |
| Atmel                             | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 162       | 23.41%  |
| Intel Wi-Fi 6 AX200                                                    | 22        | 3.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 1.88%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 1.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 8         | 1.16%   |
| Intel Wireless 8260                                                    | 8         | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 0.87%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.72%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 5         | 0.72%   |
| Intel Wireless 7260                                                    | 5         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 5         | 0.72%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 5         | 0.72%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.72%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.72%   |
| Realtek 802.11ac NIC                                                   | 4         | 0.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.58%   |
| Intel Wireless 7265                                                    | 4         | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.58%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.58%   |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 134       | 46.69%  |
| Realtek Semiconductor | 51        | 17.77%  |
| Qualcomm Atheros      | 36        | 12.54%  |
| Broadcom              | 15        | 5.23%   |
| MediaTek              | 11        | 3.83%   |
| Broadcom Limited      | 5         | 1.74%   |
| TP-Link               | 4         | 1.39%   |
| Ralink Technology     | 4         | 1.39%   |
| Ralink                | 4         | 1.39%   |
| ASUSTek Computer      | 4         | 1.39%   |
| D-Link System         | 3         | 1.05%   |
| Sierra Wireless       | 2         | 0.7%    |
| Edimax Technology     | 2         | 0.7%    |
| Dell                  | 2         | 0.7%    |
| D-Link                | 2         | 0.7%    |
| Belkin Components     | 2         | 0.7%    |
| AVM                   | 2         | 0.7%    |
| Wilocity              | 1         | 0.35%   |
| Sitecom Europe        | 1         | 0.35%   |
| Qualcomm              | 1         | 0.35%   |
| Linksys               | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 22        | 7.64%   |
| Intel Wi-Fi 6 AX201                                                  | 13        | 4.51%   |
| Intel Wireless 8260                                                  | 8         | 2.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 8         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 7         | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 2.43%   |
| Broadcom BCM43142 802.11b/g/n                                        | 7         | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 6         | 2.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 6         | 2.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 5         | 1.74%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 5         | 1.74%   |
| Intel Wireless 7260                                                  | 5         | 1.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 5         | 1.74%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 5         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 1.74%   |
| Realtek 802.11ac NIC                                                 | 4         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 1.39%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.39%   |
| Intel Wireless 7265                                                  | 4         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 1.04%   |
| Intel Wireless 8265 / 8275                                           | 3         | 1.04%   |
| Intel Wireless 3165                                                  | 3         | 1.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 1.04%   |
| Intel Centrino Advanced-N 6200                                       | 3         | 1.04%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 3         | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 2         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 207       | 54.62%  |
| Intel                    | 107       | 28.23%  |
| Broadcom                 | 20        | 5.28%   |
| Qualcomm Atheros         | 11        | 2.9%    |
| ASIX Electronics         | 5         | 1.32%   |
| Marvell Technology Group | 4         | 1.06%   |
| Samsung Electronics      | 3         | 0.79%   |
| Nvidia                   | 3         | 0.79%   |
| Aquantia                 | 3         | 0.79%   |
| Xiaomi                   | 2         | 0.53%   |
| OPPO Electronics         | 2         | 0.53%   |
| Lenovo                   | 2         | 0.53%   |
| DisplayLink              | 2         | 0.53%   |
| QLogic                   | 1         | 0.26%   |
| MediaTek                 | 1         | 0.26%   |
| LSI                      | 1         | 0.26%   |
| ICS Advent               | 1         | 0.26%   |
| Huawei Technologies      | 1         | 0.26%   |
| Broadcom Limited         | 1         | 0.26%   |
| American Megatrends      | 1         | 0.26%   |
| 3Com                     | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 162       | 41.01%  |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 3.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 3.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 2.53%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.77%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.52%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.27%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.27%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 1.01%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.01%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 1.01%   |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.76%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.76%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.76%   |
| Intel Ethernet Connection (14) I219-V                                  | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2         | 0.51%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 0.51%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2         | 0.51%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.51%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.51%   |
| Intel 82567LF Gigabit Network Connection                               | 2         | 0.51%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 2         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 0.51%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 352       | 56.14%  |
| WiFi     | 266       | 42.42%  |
| Modem    | 6         | 0.96%   |
| Unknown  | 3         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 229       | 57.11%  |
| WiFi     | 172       | 42.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 203       | 52.86%  |
| 1     | 161       | 41.93%  |
| 3     | 11        | 2.86%   |
| 0     | 3         | 0.78%   |
| 5     | 2         | 0.52%   |
| 4     | 2         | 0.52%   |
| 8     | 1         | 0.26%   |
| 6     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 235       | 60.57%  |
| Yes  | 153       | 39.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 46.64%  |
| Realtek Semiconductor           | 33        | 13.87%  |
| Cambridge Silicon Radio         | 20        | 8.4%    |
| Foxconn / Hon Hai               | 10        | 4.2%    |
| IMC Networks                    | 9         | 3.78%   |
| Broadcom                        | 9         | 3.78%   |
| Qualcomm Atheros Communications | 8         | 3.36%   |
| Lite-On Technology              | 6         | 2.52%   |
| Hewlett-Packard                 | 5         | 2.1%    |
| Dell                            | 5         | 2.1%    |
| TP-Link                         | 4         | 1.68%   |
| Apple                           | 4         | 1.68%   |
| ASUSTek Computer                | 3         | 1.26%   |
| MediaTek                        | 2         | 0.84%   |
| Foxconn International           | 2         | 0.84%   |
| USI                             | 1         | 0.42%   |
| Realtek                         | 1         | 0.42%   |
| Ralink Technology               | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Integrated System Solution      | 1         | 0.42%   |
| Fujitsu                         | 1         | 0.42%   |
| Alps Electric                   | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 25        | 10.5%   |
| Intel Bluetooth wireless interface                  | 24        | 10.08%  |
| Intel AX201 Bluetooth                               | 23        | 9.66%   |
| Intel AX200 Bluetooth                               | 21        | 8.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 8.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 6.72%   |
| Intel Bluetooth Device                              | 10        | 4.2%    |
| Intel AX210 Bluetooth                               | 8         | 3.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.1%    |
| IMC Networks Wireless_Device                        | 5         | 2.1%    |
| TP-Link TP-T@- UB500 Adapter                        | 4         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.26%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.26%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.26%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 0.84%   |
| MediaTek Wireless_Device                            | 2         | 0.84%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.84%   |
| IMC Networks Bluetooth Device                       | 2         | 0.84%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.84%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.84%   |
| USI Bluetooth Device                                | 1         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.42%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.42%   |
| Realtek Bluetooth Radio                             | 1         | 0.42%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.42%   |
| Lite-On Wireless_Device                             | 1         | 0.42%   |
| Lite-On Bluetooth Device                            | 1         | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 258       | 47.96%  |
| AMD                                  | 133       | 24.72%  |
| Nvidia                               | 94        | 17.47%  |
| C-Media Electronics                  | 10        | 1.86%   |
| GN Netcom                            | 4         | 0.74%   |
| Creative Labs                        | 4         | 0.74%   |
| Logitech                             | 3         | 0.56%   |
| DSEA A/S                             | 3         | 0.56%   |
| ASUSTek Computer                     | 3         | 0.56%   |
| Texas Instruments                    | 2         | 0.37%   |
| Plantronics                          | 2         | 0.37%   |
| Lenovo                               | 2         | 0.37%   |
| Yamaha                               | 1         | 0.19%   |
| Walmart                              | 1         | 0.19%   |
| VIA Technologies                     | 1         | 0.19%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.19%   |
| Sony                                 | 1         | 0.19%   |
| Schiit Audio                         | 1         | 0.19%   |
| RODE Microphones                     | 1         | 0.19%   |
| Realtek Semiconductor                | 1         | 0.19%   |
| ONN                                  | 1         | 0.19%   |
| Micro Star International             | 1         | 0.19%   |
| Kingston Technology                  | 1         | 0.19%   |
| Jieli Technology                     | 1         | 0.19%   |
| HiBy                                 | 1         | 0.19%   |
| Generalplus Technology               | 1         | 0.19%   |
| FiiO Electronics Technology          | 1         | 0.19%   |
| Elgato Systems                       | 1         | 0.19%   |
| Cambridge Audio                      | 1         | 0.19%   |
| ASRock                               | 1         | 0.19%   |
| Arturia                              | 1         | 0.19%   |
| Unknown                              | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 48        | 7.58%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 33        | 5.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28        | 4.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 3.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19        | 3%      |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 2.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 2.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 2.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.9%    |
| Intel 200 Series PCH HD Audio                                              | 11        | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 1.58%   |
| AMD FCH Azalia Controller                                                  | 10        | 1.58%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.11%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 7         | 1.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.95%   |
| Intel Raptor Lake High Definition Audio Controller                         | 6         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 0.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5         | 0.79%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 0.79%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 0.79%   |
| AMD Radeon High Definition Audio Controller                                | 5         | 0.79%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 5         | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 23.12%  |
| SK hynix            | 24        | 13.87%  |
| Micron Technology   | 23        | 13.29%  |
| Kingston            | 23        | 13.29%  |
| Corsair             | 14        | 8.09%   |
| Unknown             | 11        | 6.36%   |
| Crucial             | 9         | 5.2%    |
| G.Skill             | 5         | 2.89%   |
| Nanya Technology    | 4         | 2.31%   |
| Unknown (ABCD)      | 2         | 1.16%   |
| Team                | 2         | 1.16%   |
| Smart               | 2         | 1.16%   |
| Hewlett-Packard     | 2         | 1.16%   |
| Elpida              | 2         | 1.16%   |
| A-DATA Technology   | 2         | 1.16%   |
| Unknown             | 2         | 1.16%   |
| Unknown (0x0B45)    | 1         | 0.58%   |
| Silicon Power       | 1         | 0.58%   |
| Ramaxel Technology  | 1         | 0.58%   |
| Patriot             | 1         | 0.58%   |
| Lexar               | 1         | 0.58%   |
| GOODRAM             | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 1.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 2         | 1.08%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.08%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 2         | 1.08%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1600MT/s             | 2         | 1.08%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s            | 2         | 1.08%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.08%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.08%   |
| Unknown                                                          | 2         | 1.08%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.54%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.54%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.54%   |
| Unknown (0x0B45) RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s              | 1         | 0.54%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.54%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 0.54%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.54%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 58.17%  |
| DDR3    | 33        | 21.57%  |
| DDR5    | 8         | 5.23%   |
| LPDDR4  | 7         | 4.58%   |
| LPDDR5  | 5         | 3.27%   |
| DDR2    | 4         | 2.61%   |
| SDRAM   | 3         | 1.96%   |
| Unknown | 2         | 1.31%   |
| LPDDR3  | 1         | 0.65%   |
| DDR     | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 53.9%   |
| DIMM         | 58        | 37.66%  |
| Row Of Chips | 13        | 8.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 72        | 44.17%  |
| 16384 | 35        | 21.47%  |
| 4096  | 26        | 15.95%  |
| 2048  | 19        | 11.66%  |
| 32768 | 9         | 5.52%   |
| 49152 | 1         | 0.61%   |
| 512   | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 46        | 27.54%  |
| 2667    | 23        | 13.77%  |
| 1600    | 18        | 10.78%  |
| 2400    | 13        | 7.78%   |
| 1333    | 8         | 4.79%   |
| 5600    | 6         | 3.59%   |
| 3600    | 6         | 3.59%   |
| 2133    | 5         | 2.99%   |
| 1334    | 5         | 2.99%   |
| 6400    | 4         | 2.4%    |
| 4267    | 3         | 1.8%    |
| 800     | 3         | 1.8%    |
| Unknown | 3         | 1.8%    |
| 8400    | 2         | 1.2%    |
| 4000    | 2         | 1.2%    |
| 3066    | 2         | 1.2%    |
| 2933    | 2         | 1.2%    |
| 2666    | 2         | 1.2%    |
| 1867    | 2         | 1.2%    |
| 7500    | 1         | 0.6%    |
| 6000    | 1         | 0.6%    |
| 4800    | 1         | 0.6%    |
| 3800    | 1         | 0.6%    |
| 3266    | 1         | 0.6%    |
| 2134    | 1         | 0.6%    |
| 2048    | 1         | 0.6%    |
| 1866    | 1         | 0.6%    |
| 1648    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |
| 975     | 1         | 0.6%    |
| 533     | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 27.27%  |
| Seiko Epson           | 5         | 22.73%  |
| Brother Industries    | 5         | 22.73%  |
| Xerox                 | 1         | 4.55%   |
| Samsung Electronics   | 1         | 4.55%   |
| Pantum                | 1         | 4.55%   |
| Lexmark International | 1         | 4.55%   |
| Dell                  | 1         | 4.55%   |
| Canon                 | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Xerox WorkCentre 3220            | 1         | 4.55%   |
| Seiko Epson XP-4200 Series       | 1         | 4.55%   |
| Seiko Epson XP-4100 Series       | 1         | 4.55%   |
| Seiko Epson WF-4830 Series       | 1         | 4.55%   |
| Seiko Epson ET-2820 Series       | 1         | 4.55%   |
| Seiko Epson EPSON L300 Series    | 1         | 4.55%   |
| Samsung Phaser 3121              | 1         | 4.55%   |
| Pantum P2200-series              | 1         | 4.55%   |
| Lexmark International MC3224dwe  | 1         | 4.55%   |
| HP OfficeJet Pro 7720 series     | 1         | 4.55%   |
| HP OfficeJet 6950                | 1         | 4.55%   |
| HP LaserJet 1200                 | 1         | 4.55%   |
| HP LaserJet 1018                 | 1         | 4.55%   |
| HP Ink Tank 310 series           | 1         | 4.55%   |
| HP DeskJet 4100 series           | 1         | 4.55%   |
| Dell Laser Printer 1720          | 1         | 4.55%   |
| Canon LiDE 400                   | 1         | 4.55%   |
| Brother Printer                  | 1         | 4.55%   |
| Brother MFC-7360N                | 1         | 4.55%   |
| Brother HL-L3230CDW series       | 1         | 4.55%   |
| Brother DCP-L2520DW              | 1         | 4.55%   |
| Brother DCP-7057 scanner/printer | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 220                       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 44        | 21.46%  |
| IMC Networks                           | 19        | 9.27%   |
| Logitech                               | 16        | 7.8%    |
| Realtek Semiconductor                  | 14        | 6.83%   |
| Bison Electronics                      | 14        | 6.83%   |
| Microdia                               | 13        | 6.34%   |
| Luxvisions Innotech Limited            | 10        | 4.88%   |
| Sunplus Innovation Technology          | 9         | 4.39%   |
| Quanta                                 | 9         | 4.39%   |
| Syntek                                 | 8         | 3.9%    |
| Suyin                                  | 7         | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.44%   |
| Primax Electronics                     | 4         | 1.95%   |
| Apple                                  | 4         | 1.95%   |
| Sonix Technology                       | 3         | 1.46%   |
| Importek                               | 3         | 1.46%   |
| Generalplus Technology                 | 3         | 1.46%   |
| Z-Star Microelectronics                | 2         | 0.98%   |
| Ricoh                                  | 2         | 0.98%   |
| Microsoft                              | 2         | 0.98%   |
| USB CAMERA                             | 1         | 0.49%   |
| Trust                                  | 1         | 0.49%   |
| SunplusIT                              | 1         | 0.49%   |
| Sunplus Technology                     | 1         | 0.49%   |
| Samsung Electronics                    | 1         | 0.49%   |
| Lite-On Technology                     | 1         | 0.49%   |
| Lenovo                                 | 1         | 0.49%   |
| Jieli Technology                       | 1         | 0.49%   |
| Hewlett-Packard                        | 1         | 0.49%   |
| Genesys Logic                          | 1         | 0.49%   |
| Creative Technology                    | 1         | 0.49%   |
| ALi                                    | 1         | 0.49%   |
| Acer                                   | 1         | 0.49%   |
| Unknown                                | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 4.88%   |
| Syntek Integrated Camera                                | 7         | 3.41%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 6         | 2.93%   |
| IMC Networks Integrated Camera                          | 6         | 2.93%   |
| Realtek Integrated_Webcam_HD                            | 5         | 2.44%   |
| Microdia Integrated_Webcam_HD                           | 5         | 2.44%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 1.95%   |
| Logitech Webcam C270                                    | 4         | 1.95%   |
| Chicony HD WebCam                                       | 4         | 1.95%   |
| Chicony HD User Facing                                  | 4         | 1.95%   |
| Bison BisonCam,NB Pro                                   | 4         | 1.95%   |
| Primax HP HD Webcam [Fixed]                             | 3         | 1.46%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera    | 3         | 1.46%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 3         | 1.46%   |
| Generalplus GENERAL WEBCAM                              | 3         | 1.46%   |
| Bison Integrated Camera                                 | 3         | 1.46%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 2         | 0.98%   |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 0.98%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.98%   |
| Quanta VGA WebCam                                       | 2         | 0.98%   |
| Quanta HP TrueVision HD Camera                          | 2         | 0.98%   |
| Quanta HD User Facing                                   | 2         | 0.98%   |
| Microsoft LifeCam HD-3000                               | 2         | 0.98%   |
| Microdia USB 2.0 Camera                                 | 2         | 0.98%   |
| Microdia Integrated Webcam                              | 2         | 0.98%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 0.98%   |
| Logitech HD Webcam C525                                 | 2         | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 0.98%   |
| Chicony HP HD Camera                                    | 2         | 0.98%   |
| Chicony Chicony USB2.0 Camera                           | 2         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 0.98%   |
| Bison Lenovo Integrated Webcam                          | 2         | 0.98%   |
| Bison HD Webcam                                         | 2         | 0.98%   |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 0.98%   |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 0.49%   |
| Z-Star Integrated Camera                                | 1         | 0.49%   |
| USB CAMERA USB CAMERA                                   | 1         | 0.49%   |
| Trust WB-6250X Webcam                                   | 1         | 0.49%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.49%   |
| Suyin USB 2.0 UVC 1.3M WebCam                           | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 11        | 47.83%  |
| Alcor Micro      | 6         | 26.09%  |
| O2 Micro         | 2         | 8.7%    |
| Upek             | 1         | 4.35%   |
| SCM Microsystems | 1         | 4.35%   |
| Lenovo           | 1         | 4.35%   |
| Cherry           | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 26.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 17.39%  |
| Broadcom 58200                                                               | 3         | 13.04%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.35%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.35%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 4.35%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 4.35%   |
| Broadcom 5880                                                                | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 257       | 65.9%   |
| 1     | 100       | 25.64%  |
| 2     | 28        | 7.18%   |
| 3     | 4         | 1.03%   |
| 4     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 39        | 24.07%  |
| Net/wireless             | 30        | 18.52%  |
| Fingerprint reader       | 29        | 17.9%   |
| Chipcard                 | 21        | 12.96%  |
| Sound                    | 11        | 6.79%   |
| Multimedia controller    | 9         | 5.56%   |
| Camera                   | 6         | 3.7%    |
| Card reader              | 4         | 2.47%   |
| Communication controller | 3         | 1.85%   |
| Unassigned class         | 2         | 1.23%   |
| Net/ethernet             | 2         | 1.23%   |
| Bluetooth                | 2         | 1.23%   |
| Network                  | 1         | 0.62%   |
| Modem                    | 1         | 0.62%   |
| Firewire controller      | 1         | 0.62%   |
| Dvb card                 | 1         | 0.62%   |

