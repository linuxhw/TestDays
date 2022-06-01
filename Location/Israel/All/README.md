Linux in Israel - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Israel/Desktop/README.md) and [notebooks](/Location/Israel/Notebook/README.md).

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

Total: 722

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e308c653b2](https://linux-hardware.org/?probe=e308c653b2) | May 30, 2022 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [8a1f2ffc65](https://linux-hardware.org/?probe=8a1f2ffc65) | May 20, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| HP            | 8298                        | Desktop     | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Dell          | 0R4CNN A01                  | Server      | [b12db2e5d7](https://linux-hardware.org/?probe=b12db2e5d7) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | Notebook    | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | Notebook    | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [f51fab0e09](https://linux-hardware.org/?probe=f51fab0e09) | Apr 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Dell          | Latitude 7400               | Notebook    | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Acer          | Aspire V7-482PG             | Notebook    | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| ASUSTek       | D540MA-C                    | Desktop     | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | Notebook    | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f242f094a9](https://linux-hardware.org/?probe=f242f094a9) | Apr 09, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [76ddd6a6bc](https://linux-hardware.org/?probe=76ddd6a6bc) | Apr 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9e98e995e7](https://linux-hardware.org/?probe=9e98e995e7) | Mar 18, 2022 |
| MSI           | H61M-E22                    | Desktop     | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | Notebook    | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [63caa45089](https://linux-hardware.org/?probe=63caa45089) | Mar 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | Notebook    | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte      | H55M-D2H                    | Desktop     | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle       | FH87                        | Desktop     | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518NR8    | Desktop     | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP            | 2B34                        | Desktop     | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [52699a1847](https://linux-hardware.org/?probe=52699a1847) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [46a851b841](https://linux-hardware.org/?probe=46a851b841) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M91p 4524B96    | Desktop     | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Dell          | Latitude 3350               | Notebook    | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [195c9a8567](https://linux-hardware.org/?probe=195c9a8567) | Dec 29, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| AZW           | U59                         | Desktop     | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [d4f31ef495](https://linux-hardware.org/?probe=d4f31ef495) | Dec 01, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | Notebook    | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [8d8d873287](https://linux-hardware.org/?probe=8d8d873287) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [19bfb20536](https://linux-hardware.org/?probe=19bfb20536) | Nov 19, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [ba96dd251c](https://linux-hardware.org/?probe=ba96dd251c) | Nov 17, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | BU403UAV                    | Notebook    | [cb7fcf5c15](https://linux-hardware.org/?probe=cb7fcf5c15) | Nov 15, 2021 |
| Gigabyte      | B560M H                     | Desktop     | [358ab5a9fe](https://linux-hardware.org/?probe=358ab5a9fe) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [78bc4b00c0](https://linux-hardware.org/?probe=78bc4b00c0) | Nov 12, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [55b02178a3](https://linux-hardware.org/?probe=55b02178a3) | Nov 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [b6127e027b](https://linux-hardware.org/?probe=b6127e027b) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Dell          | Latitude 5410               | Notebook    | [35fd3a8949](https://linux-hardware.org/?probe=35fd3a8949) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [c5e111be13](https://linux-hardware.org/?probe=c5e111be13) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [6cc81555db](https://linux-hardware.org/?probe=6cc81555db) | Nov 04, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ed20604458](https://linux-hardware.org/?probe=ed20604458) | Oct 26, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [3f5d6aaab8](https://linux-hardware.org/?probe=3f5d6aaab8) | Oct 26, 2021 |
| Dell          | 0V8F20 A01                  | Desktop     | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| MSI           | G41TM-P33                   | Desktop     | [8216f8bfae](https://linux-hardware.org/?probe=8216f8bfae) | Oct 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b792457755](https://linux-hardware.org/?probe=b792457755) | Oct 21, 2021 |
| Foxconn       | H81MXV FAB A                | Desktop     | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [b39ed56cc9](https://linux-hardware.org/?probe=b39ed56cc9) | Oct 19, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [e3149252a0](https://linux-hardware.org/?probe=e3149252a0) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [b78fec94ab](https://linux-hardware.org/?probe=b78fec94ab) | Oct 16, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [28136dcca0](https://linux-hardware.org/?probe=28136dcca0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f86adc0f8d](https://linux-hardware.org/?probe=f86adc0f8d) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [267712392b](https://linux-hardware.org/?probe=267712392b) | Oct 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| Notebook      | N2x0WU                      | Notebook    | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| HP            | 1497                        | Desktop     | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| Dell          | Latitude 5420               | Notebook    | [a31b3507c4](https://linux-hardware.org/?probe=a31b3507c4) | Sep 26, 2021 |
| Dell          | Latitude 5420               | Notebook    | [a077664ed2](https://linux-hardware.org/?probe=a077664ed2) | Sep 26, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| ASUSTek       | H81M-E R2.0                 | Desktop     | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [e79a9eb09d](https://linux-hardware.org/?probe=e79a9eb09d) | Sep 22, 2021 |
| HP            | EliteBook x360 1040 G6      | Convertible | [7e2118517f](https://linux-hardware.org/?probe=7e2118517f) | Sep 17, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [28ce3a6f8d](https://linux-hardware.org/?probe=28ce3a6f8d) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| Dell          | Vostro 7590                 | Notebook    | [8f4e694845](https://linux-hardware.org/?probe=8f4e694845) | Sep 10, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ProBook 4520s               | Notebook    | [4f947f1b22](https://linux-hardware.org/?probe=4f947f1b22) | Sep 06, 2021 |
| HP            | ProBook 4520s               | Notebook    | [fac0dbdf09](https://linux-hardware.org/?probe=fac0dbdf09) | Sep 06, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP            | 158A                        | Desktop     | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| HP            | Spectre Notebook            | Notebook    | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | Notebook    | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [17afc04962](https://linux-hardware.org/?probe=17afc04962) | Aug 16, 2021 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [0ca5c5faa2](https://linux-hardware.org/?probe=0ca5c5faa2) | Aug 11, 2021 |
| IP3 Tech      | AP1                         | Notebook    | [b27a94c64c](https://linux-hardware.org/?probe=b27a94c64c) | Aug 08, 2021 |
| Dell          | Latitude 5410               | Notebook    | [4f2e0ccb9f](https://linux-hardware.org/?probe=4f2e0ccb9f) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [37cbdcae11](https://linux-hardware.org/?probe=37cbdcae11) | Aug 03, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [cab34266f1](https://linux-hardware.org/?probe=cab34266f1) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| Dell          | Latitude 5410               | Notebook    | [73c46f7a65](https://linux-hardware.org/?probe=73c46f7a65) | Aug 01, 2021 |
| Dell          | Latitude 5410               | Notebook    | [8357a0ce64](https://linux-hardware.org/?probe=8357a0ce64) | Aug 01, 2021 |
| Gigabyte      | X58-USB3                    | Desktop     | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| HP            | Unknown                     | Notebook    | [f048334d4b](https://linux-hardware.org/?probe=f048334d4b) | Jul 21, 2021 |
| Dell          | Latitude E4300              | Notebook    | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell          | 0GMM0G A00                  | Desktop     | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [d479a6fd61](https://linux-hardware.org/?probe=d479a6fd61) | Jun 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [13ed380099](https://linux-hardware.org/?probe=13ed380099) | Jun 24, 2021 |
| HP            | Notebook                    | Notebook    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| HP            | Notebook                    | Notebook    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [ecec039fdb](https://linux-hardware.org/?probe=ecec039fdb) | Jun 13, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [276793666d](https://linux-hardware.org/?probe=276793666d) | Jun 13, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [debb5f4ac5](https://linux-hardware.org/?probe=debb5f4ac5) | Jun 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [38d5c55bd7](https://linux-hardware.org/?probe=38d5c55bd7) | May 31, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e334fad2cc](https://linux-hardware.org/?probe=e334fad2cc) | May 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Acer          | Aspire 4333                 | Notebook    | [9f3738469d](https://linux-hardware.org/?probe=9f3738469d) | May 24, 2021 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [6fe368312c](https://linux-hardware.org/?probe=6fe368312c) | May 15, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [9497cc9d85](https://linux-hardware.org/?probe=9497cc9d85) | May 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7ed9015fd5](https://linux-hardware.org/?probe=7ed9015fd5) | May 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ab559fd00d](https://linux-hardware.org/?probe=ab559fd00d) | May 09, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [c72aec456a](https://linux-hardware.org/?probe=c72aec456a) | May 06, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c8a2e1e897](https://linux-hardware.org/?probe=c8a2e1e897) | May 06, 2021 |
| LG Electro... | 15Z980-A.AAS8U1             | Notebook    | [2a68dcd848](https://linux-hardware.org/?probe=2a68dcd848) | May 03, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e0e3552e96](https://linux-hardware.org/?probe=e0e3552e96) | Apr 28, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f8b00a2f85](https://linux-hardware.org/?probe=f8b00a2f85) | Apr 27, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| HP            | 3397                        | Desktop     | [08ea9bb12b](https://linux-hardware.org/?probe=08ea9bb12b) | Apr 22, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0752e29519](https://linux-hardware.org/?probe=0752e29519) | Apr 21, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [6dd3daccc6](https://linux-hardware.org/?probe=6dd3daccc6) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [95f2d11b2e](https://linux-hardware.org/?probe=95f2d11b2e) | Apr 16, 2021 |
| ASUSTek       | D540MA-C                    | Desktop     | [945b05bee8](https://linux-hardware.org/?probe=945b05bee8) | Apr 16, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [23fd0be92f](https://linux-hardware.org/?probe=23fd0be92f) | Apr 10, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [9881ce611d](https://linux-hardware.org/?probe=9881ce611d) | Apr 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [ca15c642d7](https://linux-hardware.org/?probe=ca15c642d7) | Apr 08, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a5823c243c](https://linux-hardware.org/?probe=a5823c243c) | Apr 02, 2021 |
| Unknown       | Unknown                     | All in one  | [a8185511a2](https://linux-hardware.org/?probe=a8185511a2) | Apr 01, 2021 |
| Unknown       | Unknown                     | All in one  | [f07c298443](https://linux-hardware.org/?probe=f07c298443) | Apr 01, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [fefe0c7d71](https://linux-hardware.org/?probe=fefe0c7d71) | Apr 01, 2021 |
| MSI           | H87-G43 GAMING              | Desktop     | [5bd49fbcea](https://linux-hardware.org/?probe=5bd49fbcea) | Mar 28, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8d84b967f2](https://linux-hardware.org/?probe=8d84b967f2) | Mar 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [91a8d56cfd](https://linux-hardware.org/?probe=91a8d56cfd) | Mar 25, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [4cc755d1c2](https://linux-hardware.org/?probe=4cc755d1c2) | Mar 25, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f71120521c](https://linux-hardware.org/?probe=f71120521c) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [edf6ab636e](https://linux-hardware.org/?probe=edf6ab636e) | Mar 19, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [feb8706c98](https://linux-hardware.org/?probe=feb8706c98) | Mar 18, 2021 |
| ASRock        | H71M-DGS                    | Desktop     | [30424c4317](https://linux-hardware.org/?probe=30424c4317) | Mar 18, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [fa7b8613f2](https://linux-hardware.org/?probe=fa7b8613f2) | Mar 16, 2021 |
| Gigabyte      | Z490M                       | Desktop     | [6eecc1d3cc](https://linux-hardware.org/?probe=6eecc1d3cc) | Mar 15, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | Desktop     | [0fbdab8514](https://linux-hardware.org/?probe=0fbdab8514) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [7140c5ee85](https://linux-hardware.org/?probe=7140c5ee85) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [93a598b2c2](https://linux-hardware.org/?probe=93a598b2c2) | Mar 11, 2021 |
| Intel         | DG43RK AAE78175-403         | Desktop     | [942660dca5](https://linux-hardware.org/?probe=942660dca5) | Mar 11, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2d19cc5e17](https://linux-hardware.org/?probe=2d19cc5e17) | Mar 11, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | Desktop     | [99082a91ac](https://linux-hardware.org/?probe=99082a91ac) | Mar 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a50f9abd26](https://linux-hardware.org/?probe=a50f9abd26) | Mar 11, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [1e4054e9fe](https://linux-hardware.org/?probe=1e4054e9fe) | Mar 09, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| Supermicro    | X8DAL                       | Server      | [ef1b6d7f7e](https://linux-hardware.org/?probe=ef1b6d7f7e) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a55964d5d9](https://linux-hardware.org/?probe=a55964d5d9) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [fb3d2fc3e9](https://linux-hardware.org/?probe=fb3d2fc3e9) | Mar 03, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [061392ad81](https://linux-hardware.org/?probe=061392ad81) | Mar 01, 2021 |
| ASUSTek       | GL503VD                     | Notebook    | [d03b00803b](https://linux-hardware.org/?probe=d03b00803b) | Feb 27, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [618d47c042](https://linux-hardware.org/?probe=618d47c042) | Feb 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [2fff8b3674](https://linux-hardware.org/?probe=2fff8b3674) | Feb 24, 2021 |
| Gigabyte      | H81-D3                      | Desktop     | [d05b1b3efc](https://linux-hardware.org/?probe=d05b1b3efc) | Feb 22, 2021 |
| ASRock        | H77M                        | Desktop     | [eb7af012c2](https://linux-hardware.org/?probe=eb7af012c2) | Feb 19, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [c2bd3800b7](https://linux-hardware.org/?probe=c2bd3800b7) | Feb 18, 2021 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [95fc52db78](https://linux-hardware.org/?probe=95fc52db78) | Feb 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2b4a74a520](https://linux-hardware.org/?probe=2b4a74a520) | Feb 16, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [f4c77fc7dc](https://linux-hardware.org/?probe=f4c77fc7dc) | Feb 16, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [802f6994df](https://linux-hardware.org/?probe=802f6994df) | Feb 16, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [aead87bf38](https://linux-hardware.org/?probe=aead87bf38) | Feb 14, 2021 |
| Lenovo        | 3176 NOK                    | Desktop     | [c5216ce396](https://linux-hardware.org/?probe=c5216ce396) | Feb 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [a2ab510560](https://linux-hardware.org/?probe=a2ab510560) | Feb 14, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [66af036f49](https://linux-hardware.org/?probe=66af036f49) | Feb 13, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [749beaf127](https://linux-hardware.org/?probe=749beaf127) | Feb 13, 2021 |
| Gigabyte      | B460M D3H                   | Desktop     | [8cdafac5a3](https://linux-hardware.org/?probe=8cdafac5a3) | Feb 13, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8711f89b6b](https://linux-hardware.org/?probe=8711f89b6b) | Feb 13, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [351477b72b](https://linux-hardware.org/?probe=351477b72b) | Feb 13, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [3e8ad6be09](https://linux-hardware.org/?probe=3e8ad6be09) | Feb 10, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [655d6c5817](https://linux-hardware.org/?probe=655d6c5817) | Feb 06, 2021 |
| Supermicro    | X10DRD-iNT                  | Server      | [21124e85cc](https://linux-hardware.org/?probe=21124e85cc) | Feb 05, 2021 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [799c676c40](https://linux-hardware.org/?probe=799c676c40) | Feb 04, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [586d4a5a82](https://linux-hardware.org/?probe=586d4a5a82) | Feb 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [017e9abf15](https://linux-hardware.org/?probe=017e9abf15) | Feb 04, 2021 |
| Lenovo        | ThinkPad E550 20DF004RIV    | Notebook    | [23140cf3f9](https://linux-hardware.org/?probe=23140cf3f9) | Jan 29, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [1763668816](https://linux-hardware.org/?probe=1763668816) | Jan 29, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e6be0abafb](https://linux-hardware.org/?probe=e6be0abafb) | Jan 28, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9aa53da922](https://linux-hardware.org/?probe=9aa53da922) | Jan 19, 2021 |
| Dell          | Latitude E6420              | Notebook    | [20a4b3769d](https://linux-hardware.org/?probe=20a4b3769d) | Jan 19, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [4df2203870](https://linux-hardware.org/?probe=4df2203870) | Jan 19, 2021 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [65724a4aa6](https://linux-hardware.org/?probe=65724a4aa6) | Jan 18, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [cc4593764d](https://linux-hardware.org/?probe=cc4593764d) | Jan 18, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [23a9e9c5f6](https://linux-hardware.org/?probe=23a9e9c5f6) | Jan 17, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [750413cc61](https://linux-hardware.org/?probe=750413cc61) | Jan 16, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [725729e04e](https://linux-hardware.org/?probe=725729e04e) | Jan 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [9c40fd9781](https://linux-hardware.org/?probe=9c40fd9781) | Jan 13, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [94b70d7578](https://linux-hardware.org/?probe=94b70d7578) | Jan 12, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [4723903be4](https://linux-hardware.org/?probe=4723903be4) | Jan 11, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [8c6a5c5e60](https://linux-hardware.org/?probe=8c6a5c5e60) | Jan 10, 2021 |
| ASRock        | H97M Anniversary            | Desktop     | [b630702ecc](https://linux-hardware.org/?probe=b630702ecc) | Jan 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [c1eeffc9d8](https://linux-hardware.org/?probe=c1eeffc9d8) | Jan 08, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [2583ebac59](https://linux-hardware.org/?probe=2583ebac59) | Jan 08, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [b7c82c53b6](https://linux-hardware.org/?probe=b7c82c53b6) | Jan 07, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [0d62d918c5](https://linux-hardware.org/?probe=0d62d918c5) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [5a3a67e5c3](https://linux-hardware.org/?probe=5a3a67e5c3) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [f37800ed52](https://linux-hardware.org/?probe=f37800ed52) | Jan 07, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [b8bab31c57](https://linux-hardware.org/?probe=b8bab31c57) | Jan 06, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [d55bf78096](https://linux-hardware.org/?probe=d55bf78096) | Jan 06, 2021 |
| Unknown       | G41 Series                  | Desktop     | [578bc526ef](https://linux-hardware.org/?probe=578bc526ef) | Jan 06, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [0efe5f5a7e](https://linux-hardware.org/?probe=0efe5f5a7e) | Jan 04, 2021 |
| Unknown       | G41 Series                  | Desktop     | [5a6543b6f1](https://linux-hardware.org/?probe=5a6543b6f1) | Jan 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [b364724e53](https://linux-hardware.org/?probe=b364724e53) | Jan 02, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8d338ea73c](https://linux-hardware.org/?probe=8d338ea73c) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ef84edb346](https://linux-hardware.org/?probe=ef84edb346) | Dec 31, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [2ed921327b](https://linux-hardware.org/?probe=2ed921327b) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [9448ec4439](https://linux-hardware.org/?probe=9448ec4439) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [7cd92f4564](https://linux-hardware.org/?probe=7cd92f4564) | Dec 30, 2020 |
| Unknown       | Unknown                     | Notebook    | [749c45e229](https://linux-hardware.org/?probe=749c45e229) | Dec 29, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [01024cf86e](https://linux-hardware.org/?probe=01024cf86e) | Dec 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [66fd37cef4](https://linux-hardware.org/?probe=66fd37cef4) | Dec 27, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c79668f190](https://linux-hardware.org/?probe=c79668f190) | Dec 24, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [56b69fe95e](https://linux-hardware.org/?probe=56b69fe95e) | Dec 23, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [ddc1a4457d](https://linux-hardware.org/?probe=ddc1a4457d) | Dec 22, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [b4ebedb0e2](https://linux-hardware.org/?probe=b4ebedb0e2) | Dec 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [8d41f37972](https://linux-hardware.org/?probe=8d41f37972) | Dec 18, 2020 |
| Nvidia        | Tegra                       | Soc         | [eb55f6a449](https://linux-hardware.org/?probe=eb55f6a449) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e42b0f86e0](https://linux-hardware.org/?probe=e42b0f86e0) | Dec 14, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [5c1982b26c](https://linux-hardware.org/?probe=5c1982b26c) | Dec 08, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [5b58c4ff46](https://linux-hardware.org/?probe=5b58c4ff46) | Dec 08, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [df5f3d5a4d](https://linux-hardware.org/?probe=df5f3d5a4d) | Dec 07, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [4f0b22ee7f](https://linux-hardware.org/?probe=4f0b22ee7f) | Nov 30, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [4cbbe5b21a](https://linux-hardware.org/?probe=4cbbe5b21a) | Nov 26, 2020 |
| Lenovo        | Unknown                     | Notebook    | [40c892a262](https://linux-hardware.org/?probe=40c892a262) | Nov 26, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [f65b9a326b](https://linux-hardware.org/?probe=f65b9a326b) | Nov 21, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [8f674b7608](https://linux-hardware.org/?probe=8f674b7608) | Nov 21, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [c42752eed3](https://linux-hardware.org/?probe=c42752eed3) | Nov 19, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [a6e2af6e5b](https://linux-hardware.org/?probe=a6e2af6e5b) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [1674d3318e](https://linux-hardware.org/?probe=1674d3318e) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [0ae9d90f3f](https://linux-hardware.org/?probe=0ae9d90f3f) | Nov 18, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [375ec8881d](https://linux-hardware.org/?probe=375ec8881d) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2f9457bf32](https://linux-hardware.org/?probe=2f9457bf32) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f2e24821f4](https://linux-hardware.org/?probe=f2e24821f4) | Nov 17, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [accc9c10e5](https://linux-hardware.org/?probe=accc9c10e5) | Nov 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e13999e22a](https://linux-hardware.org/?probe=e13999e22a) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | Notebook    | [e04b97eabe](https://linux-hardware.org/?probe=e04b97eabe) | Nov 11, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [90ef23a01c](https://linux-hardware.org/?probe=90ef23a01c) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | Notebook    | [4572167747](https://linux-hardware.org/?probe=4572167747) | Nov 10, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [22a316e31b](https://linux-hardware.org/?probe=22a316e31b) | Nov 08, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [a1662fff6f](https://linux-hardware.org/?probe=a1662fff6f) | Nov 08, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1c3bd52baa](https://linux-hardware.org/?probe=1c3bd52baa) | Nov 05, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1b6972fae9](https://linux-hardware.org/?probe=1b6972fae9) | Nov 05, 2020 |
| Dell          | 0CU409                      | Desktop     | [6adb83b2e0](https://linux-hardware.org/?probe=6adb83b2e0) | Nov 04, 2020 |
| Lenovo        | Yoga 3 11 80J8              | Notebook    | [b4f083536f](https://linux-hardware.org/?probe=b4f083536f) | Nov 04, 2020 |
| Lenovo        | ThinkCentre A58 751581G     | Desktop     | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [b0a2e83351](https://linux-hardware.org/?probe=b0a2e83351) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [b94cef8d24](https://linux-hardware.org/?probe=b94cef8d24) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [c872f1d76f](https://linux-hardware.org/?probe=c872f1d76f) | Nov 03, 2020 |
| Dell          | 0KWVT8 A02                  | Desktop     | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| Dell          | Latitude E6330              | Notebook    | [f7e530a8c2](https://linux-hardware.org/?probe=f7e530a8c2) | Nov 02, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e8426a064f](https://linux-hardware.org/?probe=e8426a064f) | Nov 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [c59e7b1e56](https://linux-hardware.org/?probe=c59e7b1e56) | Nov 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Dell          | 0KP561                      | Desktop     | [da357993dd](https://linux-hardware.org/?probe=da357993dd) | Oct 31, 2020 |
| Dell          | 0KP561                      | Desktop     | [b14be76868](https://linux-hardware.org/?probe=b14be76868) | Oct 31, 2020 |
| Lenovo        | ThinkPad E480 20KN0062IV    | Notebook    | [fba2fb0e45](https://linux-hardware.org/?probe=fba2fb0e45) | Oct 30, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [1a691f72dc](https://linux-hardware.org/?probe=1a691f72dc) | Oct 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [990f9bb22f](https://linux-hardware.org/?probe=990f9bb22f) | Oct 29, 2020 |
| Dell          | Latitude 7490               | Notebook    | [2d61d426d5](https://linux-hardware.org/?probe=2d61d426d5) | Oct 28, 2020 |
| HP            | 158A                        | Desktop     | [f83412f912](https://linux-hardware.org/?probe=f83412f912) | Oct 27, 2020 |
| Dell          | Latitude 7300               | Notebook    | [ebf99bafc8](https://linux-hardware.org/?probe=ebf99bafc8) | Oct 27, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5bd58e33be](https://linux-hardware.org/?probe=5bd58e33be) | Oct 27, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [156543a1d2](https://linux-hardware.org/?probe=156543a1d2) | Oct 26, 2020 |
| HP            | 82B4                        | Desktop     | [d98d676e9c](https://linux-hardware.org/?probe=d98d676e9c) | Oct 26, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7c9e9b741c](https://linux-hardware.org/?probe=7c9e9b741c) | Oct 25, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d3f4deffa5](https://linux-hardware.org/?probe=d3f4deffa5) | Oct 25, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [36d289ce92](https://linux-hardware.org/?probe=36d289ce92) | Oct 20, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [e360fd1fa2](https://linux-hardware.org/?probe=e360fd1fa2) | Oct 18, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| Dell          | Vostro 14 5401              | Notebook    | [89826d13da](https://linux-hardware.org/?probe=89826d13da) | Oct 13, 2020 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| ASUSTek       | UX430UNR                    | Notebook    | [03dd6f184c](https://linux-hardware.org/?probe=03dd6f184c) | Oct 12, 2020 |
| Dell          | Vostro 14 5401              | Notebook    | [d3f66acd1b](https://linux-hardware.org/?probe=d3f66acd1b) | Oct 12, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [cab83dd9ff](https://linux-hardware.org/?probe=cab83dd9ff) | Oct 12, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [b998e489c5](https://linux-hardware.org/?probe=b998e489c5) | Oct 07, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [ba633c064d](https://linux-hardware.org/?probe=ba633c064d) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [a9d940dd83](https://linux-hardware.org/?probe=a9d940dd83) | Oct 04, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [c7e2a6001a](https://linux-hardware.org/?probe=c7e2a6001a) | Oct 04, 2020 |
| Dell          | Latitude 7400               | Notebook    | [6eac6cfa15](https://linux-hardware.org/?probe=6eac6cfa15) | Oct 04, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI           | G41M-E43                    | Desktop     | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b8c1686e69](https://linux-hardware.org/?probe=b8c1686e69) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [33801ffba1](https://linux-hardware.org/?probe=33801ffba1) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 20RA0036IV     | Notebook    | [d53e57ac10](https://linux-hardware.org/?probe=d53e57ac10) | Sep 25, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [9b2604c2e1](https://linux-hardware.org/?probe=9b2604c2e1) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP            | 339A                        | Desktop     | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [24b00b8ca8](https://linux-hardware.org/?probe=24b00b8ca8) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| Dell          | Latitude E5270              | Notebook    | [745e05ba12](https://linux-hardware.org/?probe=745e05ba12) | Aug 31, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [eee9972fdf](https://linux-hardware.org/?probe=eee9972fdf) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [cb7fda5c3f](https://linux-hardware.org/?probe=cb7fda5c3f) | Aug 27, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [99c5924655](https://linux-hardware.org/?probe=99c5924655) | Aug 23, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| Lenovo        | ThinkPad L390 20NR001LIV    | Notebook    | [9fef5634b2](https://linux-hardware.org/?probe=9fef5634b2) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee5213ce49](https://linux-hardware.org/?probe=ee5213ce49) | Aug 19, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | Notebook    | [5f1ce912be](https://linux-hardware.org/?probe=5f1ce912be) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [635a148f20](https://linux-hardware.org/?probe=635a148f20) | Aug 19, 2020 |
| Toshiba       | Satellite P50t-B-10T        | Notebook    | [0f41a5b6ec](https://linux-hardware.org/?probe=0f41a5b6ec) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | Desktop     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| Lenovo        | ThinkPad T490 20N20073IV    | Notebook    | [3878e27014](https://linux-hardware.org/?probe=3878e27014) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock        | H55M                        | Desktop     | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [6d92297671](https://linux-hardware.org/?probe=6d92297671) | Aug 05, 2020 |
| Nvidia        | Tegra                       | Soc         | [273bc677cd](https://linux-hardware.org/?probe=273bc677cd) | Aug 05, 2020 |
| Supermicro    | X8DAL                       | Server      | [03a282558d](https://linux-hardware.org/?probe=03a282558d) | Aug 05, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Supermicro    | X8DAL                       | Server      | [08cd245e63](https://linux-hardware.org/?probe=08cd245e63) | Aug 03, 2020 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [fb785080a3](https://linux-hardware.org/?probe=fb785080a3) | Aug 02, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e934fab850](https://linux-hardware.org/?probe=e934fab850) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [38feef34d4](https://linux-hardware.org/?probe=38feef34d4) | Aug 01, 2020 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6156b4dec2](https://linux-hardware.org/?probe=6156b4dec2) | Aug 01, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock        | H55M                        | Desktop     | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Dell          | Latitude E6530              | Notebook    | [6e1b2fb388](https://linux-hardware.org/?probe=6e1b2fb388) | Jul 24, 2020 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [3944aa1028](https://linux-hardware.org/?probe=3944aa1028) | Jul 20, 2020 |
| HP            | ProBook 640 G2              | Notebook    | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [6e6f80378d](https://linux-hardware.org/?probe=6e6f80378d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | Notebook    | [d0aacf7693](https://linux-hardware.org/?probe=d0aacf7693) | Jul 09, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | Notebook    | [868953dc99](https://linux-hardware.org/?probe=868953dc99) | Jul 09, 2020 |
| Dell          | Latitude 5400               | Notebook    | [ae1c2d9825](https://linux-hardware.org/?probe=ae1c2d9825) | Jul 08, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASUSTek       | UX461UA                     | Convertible | [a294adac80](https://linux-hardware.org/?probe=a294adac80) | Jul 02, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [52fad4367c](https://linux-hardware.org/?probe=52fad4367c) | Jul 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [39df31f4c6](https://linux-hardware.org/?probe=39df31f4c6) | Jun 27, 2020 |
| Lenovo        | ThinkPad E14 20RA0016IV     | Notebook    | [2878e88064](https://linux-hardware.org/?probe=2878e88064) | Jun 24, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [866c72927a](https://linux-hardware.org/?probe=866c72927a) | Jun 22, 2020 |
| Dell          | Inspiron 5379               | Notebook    | [f7fe8744d9](https://linux-hardware.org/?probe=f7fe8744d9) | Jun 21, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| MSI           | G41M-E43                    | Desktop     | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [1ce6e06069](https://linux-hardware.org/?probe=1ce6e06069) | May 30, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| Dell          | Latitude 5490               | Notebook    | [2afe6adf1b](https://linux-hardware.org/?probe=2afe6adf1b) | May 18, 2020 |
| Dell          | Latitude 5490               | Notebook    | [c2b1c12105](https://linux-hardware.org/?probe=c2b1c12105) | May 17, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| HP            | 339A                        | Desktop     | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| HP            | G42                         | Notebook    | [6d45062a76](https://linux-hardware.org/?probe=6d45062a76) | May 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Lenovo        | ThinkPad X200 74587DU       | Notebook    | [ba354beaa9](https://linux-hardware.org/?probe=ba354beaa9) | May 10, 2020 |
| ASUSTek       | K54C                        | Notebook    | [c2656ceae6](https://linux-hardware.org/?probe=c2656ceae6) | May 07, 2020 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [6f86c55589](https://linux-hardware.org/?probe=6f86c55589) | May 04, 2020 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [e93143c6fd](https://linux-hardware.org/?probe=e93143c6fd) | Apr 27, 2020 |
| Dell          | 097YXY A00                  | Desktop     | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [4cc7a86795](https://linux-hardware.org/?probe=4cc7a86795) | Apr 26, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [d9a55aeca2](https://linux-hardware.org/?probe=d9a55aeca2) | Apr 25, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [1e6ea00cd0](https://linux-hardware.org/?probe=1e6ea00cd0) | Apr 25, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [2516b70573](https://linux-hardware.org/?probe=2516b70573) | Apr 23, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [cdcce3c09c](https://linux-hardware.org/?probe=cdcce3c09c) | Apr 23, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [d99b7f2578](https://linux-hardware.org/?probe=d99b7f2578) | Apr 22, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [434a4a46f9](https://linux-hardware.org/?probe=434a4a46f9) | Apr 19, 2020 |
| Dell          | XPS 13 9350                 | Notebook    | [d718b985ec](https://linux-hardware.org/?probe=d718b985ec) | Apr 18, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [cd641ec5c7](https://linux-hardware.org/?probe=cd641ec5c7) | Apr 17, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [28e6c33fec](https://linux-hardware.org/?probe=28e6c33fec) | Apr 17, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [7e17ce97e9](https://linux-hardware.org/?probe=7e17ce97e9) | Apr 17, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [189e02e90e](https://linux-hardware.org/?probe=189e02e90e) | Apr 12, 2020 |
| ASUSTek       | X550CA                      | Notebook    | [d23cc368bb](https://linux-hardware.org/?probe=d23cc368bb) | Apr 10, 2020 |
| Dell          | Latitude 5490               | Notebook    | [6759b030d2](https://linux-hardware.org/?probe=6759b030d2) | Apr 10, 2020 |
| Dell          | Latitude 7300               | Notebook    | [4c263fc2d0](https://linux-hardware.org/?probe=4c263fc2d0) | Apr 01, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [254c1f48da](https://linux-hardware.org/?probe=254c1f48da) | Mar 31, 2020 |
| Dell          | Latitude 5490               | Notebook    | [03873fa787](https://linux-hardware.org/?probe=03873fa787) | Mar 30, 2020 |
| Dell          | Latitude 5490               | Notebook    | [d71d69d129](https://linux-hardware.org/?probe=d71d69d129) | Mar 30, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2aab729aee](https://linux-hardware.org/?probe=2aab729aee) | Mar 30, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [ade023408c](https://linux-hardware.org/?probe=ade023408c) | Mar 26, 2020 |
| MSI           | B450-A PRO                  | Desktop     | [f9c1a4dd5d](https://linux-hardware.org/?probe=f9c1a4dd5d) | Mar 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9c1238b041](https://linux-hardware.org/?probe=9c1238b041) | Mar 22, 2020 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [e02dd36f39](https://linux-hardware.org/?probe=e02dd36f39) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [5c3ecb2c5b](https://linux-hardware.org/?probe=5c3ecb2c5b) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [1004ffcce5](https://linux-hardware.org/?probe=1004ffcce5) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [e0f2c8f133](https://linux-hardware.org/?probe=e0f2c8f133) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b5765e1a9f](https://linux-hardware.org/?probe=b5765e1a9f) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3c36d4bdc9](https://linux-hardware.org/?probe=3c36d4bdc9) | Mar 21, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [03d86fb8e8](https://linux-hardware.org/?probe=03d86fb8e8) | Mar 21, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a53152418d](https://linux-hardware.org/?probe=a53152418d) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [32428dda92](https://linux-hardware.org/?probe=32428dda92) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5d56415e4c](https://linux-hardware.org/?probe=5d56415e4c) | Mar 14, 2020 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [48afe5fac3](https://linux-hardware.org/?probe=48afe5fac3) | Mar 08, 2020 |
| Lenovo        | ThinkPad T480 20L5A063CD    | Notebook    | [ccd24104da](https://linux-hardware.org/?probe=ccd24104da) | Mar 08, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d13a02aacb](https://linux-hardware.org/?probe=d13a02aacb) | Mar 08, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [08d45d3162](https://linux-hardware.org/?probe=08d45d3162) | Mar 07, 2020 |
| Microsoft     | Surface 3                   | Tablet      | [76a25407de](https://linux-hardware.org/?probe=76a25407de) | Feb 26, 2020 |
| HP            | 1495                        | Desktop     | [ff4447983a](https://linux-hardware.org/?probe=ff4447983a) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | Notebook    | [ebce14c87e](https://linux-hardware.org/?probe=ebce14c87e) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | Notebook    | [d4b3df5729](https://linux-hardware.org/?probe=d4b3df5729) | Feb 22, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [72475e5edb](https://linux-hardware.org/?probe=72475e5edb) | Feb 22, 2020 |
| HP            | 1495                        | Desktop     | [e1d927d5ce](https://linux-hardware.org/?probe=e1d927d5ce) | Feb 16, 2020 |
| HP            | 1495                        | Desktop     | [c9e7f762e4](https://linux-hardware.org/?probe=c9e7f762e4) | Feb 16, 2020 |
| ASUSTek       | X201EP                      | Notebook    | [75d7523e83](https://linux-hardware.org/?probe=75d7523e83) | Feb 13, 2020 |
| Gigabyte      | H110M-DS2 DDR3-CF           | Desktop     | [e2a558c35b](https://linux-hardware.org/?probe=e2a558c35b) | Feb 11, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [239b2eba6d](https://linux-hardware.org/?probe=239b2eba6d) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [a3e9ca6d37](https://linux-hardware.org/?probe=a3e9ca6d37) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [60ba0e3d0f](https://linux-hardware.org/?probe=60ba0e3d0f) | Feb 08, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [30e38a1812](https://linux-hardware.org/?probe=30e38a1812) | Feb 03, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [524089d286](https://linux-hardware.org/?probe=524089d286) | Jan 29, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [b4ef2a52c5](https://linux-hardware.org/?probe=b4ef2a52c5) | Jan 21, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [33d23400b4](https://linux-hardware.org/?probe=33d23400b4) | Jan 20, 2020 |
| Pegatron      | NARRA5                      | Desktop     | [f0bd8ead24](https://linux-hardware.org/?probe=f0bd8ead24) | Jan 17, 2020 |
| LG Electro... | 15Z990-A.AAS7U1             | Notebook    | [afd7d4caf9](https://linux-hardware.org/?probe=afd7d4caf9) | Jan 15, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [7bf153f618](https://linux-hardware.org/?probe=7bf153f618) | Jan 13, 2020 |
| Lenovo        | ThinkPad E595 20NF0018US    | Notebook    | [00d8e5ba33](https://linux-hardware.org/?probe=00d8e5ba33) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [a423e910c6](https://linux-hardware.org/?probe=a423e910c6) | Jan 13, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [221a2cfac8](https://linux-hardware.org/?probe=221a2cfac8) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [84fcfb4be2](https://linux-hardware.org/?probe=84fcfb4be2) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [903ab151c8](https://linux-hardware.org/?probe=903ab151c8) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [495c89d842](https://linux-hardware.org/?probe=495c89d842) | Jan 07, 2020 |
| Dell          | Latitude E7270              | Notebook    | [83f77407ab](https://linux-hardware.org/?probe=83f77407ab) | Jan 06, 2020 |
| Dell          | Latitude E7270              | Notebook    | [dc87d2cdee](https://linux-hardware.org/?probe=dc87d2cdee) | Jan 06, 2020 |
| Dell          | 0GM819                      | Desktop     | [d99391a30c](https://linux-hardware.org/?probe=d99391a30c) | Jan 06, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [3da92e4cab](https://linux-hardware.org/?probe=3da92e4cab) | Jan 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [992e2074ff](https://linux-hardware.org/?probe=992e2074ff) | Dec 25, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f3b22a675a](https://linux-hardware.org/?probe=f3b22a675a) | Dec 20, 2019 |
| ASUSTek       | UL30A                       | Notebook    | [b7f84b8da0](https://linux-hardware.org/?probe=b7f84b8da0) | Dec 20, 2019 |
| ASUSTek       | X501A                       | Notebook    | [ce99670ceb](https://linux-hardware.org/?probe=ce99670ceb) | Dec 20, 2019 |
| ASUSTek       | X501A                       | Notebook    | [f7a367e32c](https://linux-hardware.org/?probe=f7a367e32c) | Dec 20, 2019 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [8f93bf715a](https://linux-hardware.org/?probe=8f93bf715a) | Dec 11, 2019 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [145dff2b67](https://linux-hardware.org/?probe=145dff2b67) | Dec 11, 2019 |
| ASRock        | H97M Anniversary            | Desktop     | [831ff4b7fc](https://linux-hardware.org/?probe=831ff4b7fc) | Dec 10, 2019 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [8fbc16ebfa](https://linux-hardware.org/?probe=8fbc16ebfa) | Dec 03, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| LG Electro... | A310                        | Notebook    | [d2599d1470](https://linux-hardware.org/?probe=d2599d1470) | Nov 26, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [52db21c094](https://linux-hardware.org/?probe=52db21c094) | Nov 24, 2019 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [831c001466](https://linux-hardware.org/?probe=831c001466) | Nov 23, 2019 |
| HP            | G7000                       | Notebook    | [cb550f69f7](https://linux-hardware.org/?probe=cb550f69f7) | Nov 12, 2019 |
| HP            | G7000                       | Notebook    | [97ada3d9cf](https://linux-hardware.org/?probe=97ada3d9cf) | Nov 12, 2019 |
| HP            | G7000                       | Notebook    | [ca985e708a](https://linux-hardware.org/?probe=ca985e708a) | Nov 12, 2019 |
| ASRock        | G41C-GS                     | Desktop     | [920a88f615](https://linux-hardware.org/?probe=920a88f615) | Nov 08, 2019 |
| HP            | 2B38                        | Desktop     | [8a919fff76](https://linux-hardware.org/?probe=8a919fff76) | Oct 26, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [6d5ea39af4](https://linux-hardware.org/?probe=6d5ea39af4) | Oct 26, 2019 |
| Dell          | 0GM819                      | Desktop     | [4468e2e57e](https://linux-hardware.org/?probe=4468e2e57e) | Oct 21, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [39c33a8d85](https://linux-hardware.org/?probe=39c33a8d85) | Oct 21, 2019 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [a5e61f3a1a](https://linux-hardware.org/?probe=a5e61f3a1a) | Oct 18, 2019 |
| Dell          | Latitude E6320              | Notebook    | [276041713d](https://linux-hardware.org/?probe=276041713d) | Oct 18, 2019 |
| Dell          | Latitude E6320              | Notebook    | [a2002798ac](https://linux-hardware.org/?probe=a2002798ac) | Oct 18, 2019 |
| Lenovo        | E31-80 80MX                 | Notebook    | [4f5d1ae105](https://linux-hardware.org/?probe=4f5d1ae105) | Oct 17, 2019 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [8a9e5f7293](https://linux-hardware.org/?probe=8a9e5f7293) | Oct 14, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [cafdeb1b3a](https://linux-hardware.org/?probe=cafdeb1b3a) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6bc1a600ee](https://linux-hardware.org/?probe=6bc1a600ee) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [32944602dd](https://linux-hardware.org/?probe=32944602dd) | Oct 06, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [60e8599708](https://linux-hardware.org/?probe=60e8599708) | Sep 30, 2019 |
| HP            | 2B38                        | Desktop     | [f690313ecf](https://linux-hardware.org/?probe=f690313ecf) | Sep 30, 2019 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2ad6f6b23d](https://linux-hardware.org/?probe=2ad6f6b23d) | Sep 25, 2019 |
| Lenovo        | G560 0679                   | Notebook    | [403cb2c831](https://linux-hardware.org/?probe=403cb2c831) | Sep 19, 2019 |
| Lenovo        | G560 0679                   | Notebook    | [0552d32d91](https://linux-hardware.org/?probe=0552d32d91) | Sep 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [77a3bc0e11](https://linux-hardware.org/?probe=77a3bc0e11) | Sep 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [eeaadaa0a3](https://linux-hardware.org/?probe=eeaadaa0a3) | Sep 17, 2019 |
| AMI           | Cherry Trail CR             | Desktop     | [0398059e29](https://linux-hardware.org/?probe=0398059e29) | Sep 16, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [3bfc472643](https://linux-hardware.org/?probe=3bfc472643) | Sep 15, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [d90225cad7](https://linux-hardware.org/?probe=d90225cad7) | Sep 15, 2019 |
| HP            | EliteBook 840 G6            | Notebook    | [4ada1a54ef](https://linux-hardware.org/?probe=4ada1a54ef) | Sep 13, 2019 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [b4f1b9249a](https://linux-hardware.org/?probe=b4f1b9249a) | Sep 10, 2019 |
| Dell          | Latitude E7450              | Notebook    | [cb374fcaff](https://linux-hardware.org/?probe=cb374fcaff) | Sep 05, 2019 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c090add0c0](https://linux-hardware.org/?probe=c090add0c0) | Sep 04, 2019 |
| Dell          | XPS 13 9343                 | Notebook    | [ecb0cffd7b](https://linux-hardware.org/?probe=ecb0cffd7b) | Sep 04, 2019 |
| Dell          | 0GM819                      | Desktop     | [863ec2a484](https://linux-hardware.org/?probe=863ec2a484) | Sep 02, 2019 |
| Dell          | 0GM819                      | Desktop     | [7bf21b409d](https://linux-hardware.org/?probe=7bf21b409d) | Sep 02, 2019 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [f6c7aa7735](https://linux-hardware.org/?probe=f6c7aa7735) | Sep 02, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [b1fb625f3d](https://linux-hardware.org/?probe=b1fb625f3d) | Aug 26, 2019 |
| ASUSTek       | X302UJ                      | Notebook    | [d467007887](https://linux-hardware.org/?probe=d467007887) | Aug 24, 2019 |
| Dell          | 0CKCXH A04                  | Desktop     | [2679a50fe1](https://linux-hardware.org/?probe=2679a50fe1) | Aug 24, 2019 |
| Gigabyte      | H55M-S2H                    | Desktop     | [2479a0b0c9](https://linux-hardware.org/?probe=2479a0b0c9) | Aug 24, 2019 |
| Acer          | Aspire 5730                 | Notebook    | [6e8c846d9b](https://linux-hardware.org/?probe=6e8c846d9b) | Aug 24, 2019 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [616bb81d97](https://linux-hardware.org/?probe=616bb81d97) | Aug 17, 2019 |
| Dell          | Latitude E5470              | Notebook    | [d01c149d9c](https://linux-hardware.org/?probe=d01c149d9c) | Aug 17, 2019 |
| Dell          | Latitude E5470              | Notebook    | [b0b32067b9](https://linux-hardware.org/?probe=b0b32067b9) | Aug 17, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [afa245a5c3](https://linux-hardware.org/?probe=afa245a5c3) | Aug 13, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [2043a9b3c9](https://linux-hardware.org/?probe=2043a9b3c9) | Jul 18, 2019 |
| Foxconn       | 2A8C                        | Desktop     | [54cbeed66e](https://linux-hardware.org/?probe=54cbeed66e) | Jul 10, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [10a2ff392a](https://linux-hardware.org/?probe=10a2ff392a) | Jul 09, 2019 |
| ASUSTek       | K54C                        | Notebook    | [4a89c5d895](https://linux-hardware.org/?probe=4a89c5d895) | Jul 06, 2019 |
| Gigabyte      | H57M-USB3                   | Desktop     | [10ba468b45](https://linux-hardware.org/?probe=10ba468b45) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [0b6b3550b5](https://linux-hardware.org/?probe=0b6b3550b5) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a920b40c9f](https://linux-hardware.org/?probe=a920b40c9f) | Jul 01, 2019 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4f0fb75146](https://linux-hardware.org/?probe=4f0fb75146) | Jun 20, 2019 |
| ASRock        | H110M-ITX/ac                | Desktop     | [6f2ecbf51c](https://linux-hardware.org/?probe=6f2ecbf51c) | Jun 04, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [93c1102eae](https://linux-hardware.org/?probe=93c1102eae) | May 30, 2019 |
| Gigabyte      | H97-HD3                     | Desktop     | [64e47e9922](https://linux-hardware.org/?probe=64e47e9922) | May 28, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [0e16d3f886](https://linux-hardware.org/?probe=0e16d3f886) | May 23, 2019 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [112dc8e71a](https://linux-hardware.org/?probe=112dc8e71a) | May 23, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [89e100d874](https://linux-hardware.org/?probe=89e100d874) | May 17, 2019 |
| HP            | Pavilion dv6500             | Notebook    | [b185023357](https://linux-hardware.org/?probe=b185023357) | May 13, 2019 |
| ASUSTek       | K54C                        | Notebook    | [653d157e1a](https://linux-hardware.org/?probe=653d157e1a) | May 04, 2019 |
| Lenovo        | 36F4 SDK0R32862 WIN 3258... | All in one  | [6543f3c4af](https://linux-hardware.org/?probe=6543f3c4af) | May 03, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [c736db6599](https://linux-hardware.org/?probe=c736db6599) | May 01, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [109947ebc6](https://linux-hardware.org/?probe=109947ebc6) | May 01, 2019 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [05fcc6199e](https://linux-hardware.org/?probe=05fcc6199e) | Apr 21, 2019 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [0818236221](https://linux-hardware.org/?probe=0818236221) | Apr 16, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | Notebook    | [a803a8593b](https://linux-hardware.org/?probe=a803a8593b) | Apr 11, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | Notebook    | [6be3c466e0](https://linux-hardware.org/?probe=6be3c466e0) | Apr 10, 2019 |
| HP            | 82A5                        | Mini pc     | [2350ea995c](https://linux-hardware.org/?probe=2350ea995c) | Apr 07, 2019 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [f8a69693bc](https://linux-hardware.org/?probe=f8a69693bc) | Mar 30, 2019 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f49f4bf7e3](https://linux-hardware.org/?probe=f49f4bf7e3) | Mar 30, 2019 |
| Biostar       | H61MLV2                     | Desktop     | [19146b787b](https://linux-hardware.org/?probe=19146b787b) | Mar 28, 2019 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [606743f06e](https://linux-hardware.org/?probe=606743f06e) | Mar 22, 2019 |
| Gigabyte      | H97M-HD3                    | Desktop     | [a6818d6761](https://linux-hardware.org/?probe=a6818d6761) | Mar 20, 2019 |
| System76      | Gazelle                     | Notebook    | [03387dc427](https://linux-hardware.org/?probe=03387dc427) | Mar 12, 2019 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [b1e21a522f](https://linux-hardware.org/?probe=b1e21a522f) | Feb 26, 2019 |
| HP            | G70                         | Notebook    | [d4f5ef99c5](https://linux-hardware.org/?probe=d4f5ef99c5) | Feb 14, 2019 |
| ASUSTek       | S551LN                      | Notebook    | [572227fb77](https://linux-hardware.org/?probe=572227fb77) | Jan 19, 2019 |
| ASUSTek       | S551LN                      | Notebook    | [f624b3c2eb](https://linux-hardware.org/?probe=f624b3c2eb) | Jan 18, 2019 |
| ASUSTek       | S551LN                      | Notebook    | [084947886f](https://linux-hardware.org/?probe=084947886f) | Jan 03, 2019 |
| Timi          | TM1701                      | Notebook    | [19f0b77769](https://linux-hardware.org/?probe=19f0b77769) | Dec 21, 2018 |
| Timi          | TM1701                      | Notebook    | [e0c4ee1fcb](https://linux-hardware.org/?probe=e0c4ee1fcb) | Dec 21, 2018 |
| ASUSTek       | S551LN                      | Notebook    | [4fef5b511a](https://linux-hardware.org/?probe=4fef5b511a) | Dec 15, 2018 |
| ASUSTek       | S551LN                      | Notebook    | [735db3cd91](https://linux-hardware.org/?probe=735db3cd91) | Dec 14, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [569fd85150](https://linux-hardware.org/?probe=569fd85150) | Dec 05, 2018 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [01310a1064](https://linux-hardware.org/?probe=01310a1064) | Dec 01, 2018 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [ac7a7dc15b](https://linux-hardware.org/?probe=ac7a7dc15b) | Nov 13, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [120d843ed3](https://linux-hardware.org/?probe=120d843ed3) | Nov 07, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d21daddd24](https://linux-hardware.org/?probe=d21daddd24) | Nov 07, 2018 |
| ASUSTek       | Z87-K                       | Desktop     | [1d8a707c72](https://linux-hardware.org/?probe=1d8a707c72) | Sep 11, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [00e7c9c5fc](https://linux-hardware.org/?probe=00e7c9c5fc) | Aug 18, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [80227a12a8](https://linux-hardware.org/?probe=80227a12a8) | Aug 18, 2018 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [935991dc2b](https://linux-hardware.org/?probe=935991dc2b) | May 04, 2018 |
| Lenovo        | ThinkPad T60 2613CTO        | Notebook    | [35edbff8b9](https://linux-hardware.org/?probe=35edbff8b9) | Feb 25, 2018 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [d147cce967](https://linux-hardware.org/?probe=d147cce967) | Dec 06, 2017 |
| Samsung       | N248P                       | Notebook    | [2b7782d6cb](https://linux-hardware.org/?probe=2b7782d6cb) | Aug 10, 2017 |
| HP            | Unknown                     | Notebook    | [551457fd6d](https://linux-hardware.org/?probe=551457fd6d) | Jul 10, 2017 |
| ASUSTek       | M5A87                       | Desktop     | [242554d0b3](https://linux-hardware.org/?probe=242554d0b3) | Apr 27, 2017 |
| ASRock        | G41C-GS                     | Desktop     | [ff9333f313](https://linux-hardware.org/?probe=ff9333f313) | Apr 13, 2017 |
| ASUSTek       | M5A87                       | Desktop     | [bbe4de9927](https://linux-hardware.org/?probe=bbe4de9927) | Apr 07, 2017 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [10108844b5](https://linux-hardware.org/?probe=10108844b5) | Mar 17, 2017 |
| ASUSTek       | M5A87                       | Desktop     | [653cce33bd](https://linux-hardware.org/?probe=653cce33bd) | Mar 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c869336270](https://linux-hardware.org/?probe=c869336270) | Jan 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c7554e6e05](https://linux-hardware.org/?probe=c7554e6e05) | Jan 14, 2017 |
| MSI           | G41TM-P33                   | Desktop     | [dd04fa411c](https://linux-hardware.org/?probe=dd04fa411c) | Dec 12, 2016 |
| Acer          | Aspire 7520                 | Notebook    | [9132eeefdd](https://linux-hardware.org/?probe=9132eeefdd) | Nov 21, 2016 |
| ASUSTek       | 1001PXD                     | Notebook    | [6de0cbb74c](https://linux-hardware.org/?probe=6de0cbb74c) | Oct 29, 2016 |
| ASUSTek       | 1001PXD                     | Notebook    | [439684c718](https://linux-hardware.org/?probe=439684c718) | Oct 29, 2016 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [0a729a3728](https://linux-hardware.org/?probe=0a729a3728) | Oct 07, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 120       | 22.73%  |
| Ubuntu 18.04                 | 62        | 11.74%  |
| OpenMandriva 4.2             | 16        | 3.03%   |
| ROSA R11                     | 14        | 2.65%   |
| Ubuntu 21.04                 | 11        | 2.08%   |
| Ubuntu 19.04                 | 11        | 2.08%   |
| OpenMandriva 4.3             | 10        | 1.89%   |
| Linux Mint 20.1              | 10        | 1.89%   |
| Fedora 35                    | 10        | 1.89%   |
| Manjaro                      | 9         | 1.7%    |
| Ubuntu 20.10                 | 8         | 1.52%   |
| Ubuntu 19.10                 | 8         | 1.52%   |
| ROSA R11.1                   | 8         | 1.52%   |
| Pop!_OS 21.04                | 8         | 1.52%   |
| ROSA R10                     | 7         | 1.33%   |
| Linux Mint 19.3              | 7         | 1.33%   |
| Fedora 34                    | 7         | 1.33%   |
| Fedora 33                    | 7         | 1.33%   |
| Zorin 15                     | 6         | 1.14%   |
| Pop!_OS 21.10                | 6         | 1.14%   |
| Pop!_OS 20.04                | 6         | 1.14%   |
| Linux Mint 20                | 6         | 1.14%   |
| Kubuntu 20.04                | 6         | 1.14%   |
| Arch                         | 6         | 1.14%   |
| Zorin 16                     | 5         | 0.95%   |
| Ubuntu 22.04                 | 5         | 0.95%   |
| Ubuntu 21.10                 | 5         | 0.95%   |
| Ubuntu 16.04                 | 5         | 0.95%   |
| ROSA R8                      | 5         | 0.95%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.95%   |
| Linux Mint 20.2              | 5         | 0.95%   |
| Fedora 36                    | 5         | 0.95%   |
| ArcoLinux Rolling            | 5         | 0.95%   |
| Linux Mint 20.3              | 4         | 0.76%   |
| KDE neon 20.04               | 4         | 0.76%   |
| Debian 11                    | 4         | 0.76%   |
| Arch Rolling                 | 4         | 0.76%   |
| Xubuntu 18.04                | 3         | 0.57%   |
| ROSA R9                      | 3         | 0.57%   |
| ROSA R8.1                    | 3         | 0.57%   |
| Pop!_OS 20.10                | 3         | 0.57%   |
| Manjaro 20.2                 | 3         | 0.57%   |
| Linux Mint 19.2              | 3         | 0.57%   |
| Fedora 32                    | 3         | 0.57%   |
| Xubuntu 20.10                | 2         | 0.38%   |
| Xubuntu 20.04                | 2         | 0.38%   |
| Ubuntu MATE 18.04            | 2         | 0.38%   |
| Rocky Linux 8.5              | 2         | 0.38%   |
| Manjaro 20.1                 | 2         | 0.38%   |
| Linux Mint 19.1              | 2         | 0.38%   |
| Fedora 31                    | 2         | 0.38%   |
| Endless 3.7.8                | 2         | 0.38%   |
| Debian 10                    | 2         | 0.38%   |
| CentOS 8                     | 2         | 0.38%   |
| CentOS 7                     | 2         | 0.38%   |
| BlackPanther 18.1            | 2         | 0.38%   |
| Zorin 12                     | 1         | 0.19%   |
| Xubuntu 19.10                | 1         | 0.19%   |
| Xubuntu 19.04                | 1         | 0.19%   |
| Xero Rolling                 | 1         | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 229       | 46.45%  |
| Linux Mint    | 34        | 6.9%    |
| ROSA          | 33        | 6.69%   |
| Fedora        | 33        | 6.69%   |
| OpenMandriva  | 26        | 5.27%   |
| Pop!_OS       | 24        | 4.87%   |
| Manjaro       | 18        | 3.65%   |
| Zorin         | 12        | 2.43%   |
| Arch          | 10        | 2.03%   |
| Xubuntu       | 9         | 1.83%   |
| Kubuntu       | 9         | 1.83%   |
| Endless       | 8         | 1.62%   |
| Debian        | 8         | 1.62%   |
| openSUSE      | 5         | 1.01%   |
| ArcoLinux     | 5         | 1.01%   |
| KDE neon      | 4         | 0.81%   |
| CentOS        | 4         | 0.81%   |
| Ubuntu MATE   | 3         | 0.61%   |
| Rocky Linux   | 3         | 0.61%   |
| Clear Linux   | 3         | 0.61%   |
| Devuan        | 2         | 0.41%   |
| BlackPanther  | 2         | 0.41%   |
| Xero          | 1         | 0.2%    |
| UbuntuDDE     | 1         | 0.2%    |
| Ubuntu Budgie | 1         | 0.2%    |
| RHEL          | 1         | 0.2%    |
| Lubuntu       | 1         | 0.2%    |
| Kali          | 1         | 0.2%    |
| Gentoo        | 1         | 0.2%    |
| EndeavourOS   | 1         | 0.2%    |
| Elementary    | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 26        | 4.59%   |
| 5.10.14-desktop-1omv4002            | 15        | 2.65%   |
| 5.4.0-48-generic                    | 12        | 2.12%   |
| 5.4.0-52-generic                    | 10        | 1.77%   |
| 5.16.7-desktop-1omv4003             | 10        | 1.77%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 7         | 1.24%   |
| 5.4.0-72-generic                    | 6         | 1.06%   |
| 5.4.0-65-generic                    | 6         | 1.06%   |
| 5.4.0-26-generic                    | 6         | 1.06%   |
| 5.4.0-58-generic                    | 5         | 0.88%   |
| 5.3.0-46-generic                    | 5         | 0.88%   |
| 5.13.0-30-generic                   | 5         | 0.88%   |
| 5.11.0-40-generic                   | 5         | 0.88%   |
| 5.11.0-37-generic                   | 5         | 0.88%   |
| 5.11.0-27-generic                   | 5         | 0.88%   |
| 5.0.0-23-generic                    | 5         | 0.88%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 5         | 0.88%   |
| 5.4.0-70-generic                    | 4         | 0.71%   |
| 5.4.0-40-generic                    | 4         | 0.71%   |
| 5.4.0-37-generic                    | 4         | 0.71%   |
| 5.3.0-42-generic                    | 4         | 0.71%   |
| 5.3.0-28-generic                    | 4         | 0.71%   |
| 5.13.0-7620-generic                 | 4         | 0.71%   |
| 5.11.0-38-generic                   | 4         | 0.71%   |
| 5.11.0-34-generic                   | 4         | 0.71%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 4         | 0.71%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 4         | 0.71%   |
| 4.15.0-58-generic                   | 4         | 0.71%   |
| 4.15.0-50-generic                   | 4         | 0.71%   |
| 5.8.0-7642-generic                  | 3         | 0.53%   |
| 5.8.0-59-generic                    | 3         | 0.53%   |
| 5.8.0-55-generic                    | 3         | 0.53%   |
| 5.8.0-53-generic                    | 3         | 0.53%   |
| 5.8.0-48-generic                    | 3         | 0.53%   |
| 5.8.0-44-generic                    | 3         | 0.53%   |
| 5.8.0-43-generic                    | 3         | 0.53%   |
| 5.8.0-41-generic                    | 3         | 0.53%   |
| 5.4.0-62-generic                    | 3         | 0.53%   |
| 5.4.0-29-generic                    | 3         | 0.53%   |
| 5.3.0-53-generic                    | 3         | 0.53%   |
| 5.3.0-51-generic                    | 3         | 0.53%   |
| 5.3.0-40-generic                    | 3         | 0.53%   |
| 5.3.0-26-generic                    | 3         | 0.53%   |
| 5.3.0-19-generic                    | 3         | 0.53%   |
| 5.0.0-29-generic                    | 3         | 0.53%   |
| 5.0.0-25-generic                    | 3         | 0.53%   |
| 5.9.16-200.fc33.x86_64              | 2         | 0.35%   |
| 5.8.5-arch1-1                       | 2         | 0.35%   |
| 5.8.16-300.fc33.x86_64              | 2         | 0.35%   |
| 5.8.0-7630-generic                  | 2         | 0.35%   |
| 5.8.0-63-generic                    | 2         | 0.35%   |
| 5.8.0-50-generic                    | 2         | 0.35%   |
| 5.8.0-36-generic                    | 2         | 0.35%   |
| 5.8.0-34-generic                    | 2         | 0.35%   |
| 5.8.0-25-generic                    | 2         | 0.35%   |
| 5.4.2-1-MANJARO                     | 2         | 0.35%   |
| 5.4.0-97-generic                    | 2         | 0.35%   |
| 5.4.0-91-generic                    | 2         | 0.35%   |
| 5.4.0-84-generic                    | 2         | 0.35%   |
| 5.4.0-81-generic                    | 2         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 123       | 23.03%  |
| 4.15.0  | 49        | 9.18%   |
| 5.8.0   | 43        | 8.05%   |
| 5.11.0  | 37        | 6.93%   |
| 5.3.0   | 31        | 5.81%   |
| 5.13.0  | 25        | 4.68%   |
| 5.0.0   | 25        | 4.68%   |
| 5.10.14 | 15        | 2.81%   |
| 4.18.0  | 13        | 2.43%   |
| 5.16.7  | 10        | 1.87%   |
| 5.10.0  | 6         | 1.12%   |
| 4.9.60  | 6         | 1.12%   |
| 5.15.0  | 5         | 0.94%   |
| 5.9.16  | 4         | 0.75%   |
| 4.19.0  | 4         | 0.75%   |
| 4.1.34  | 4         | 0.75%   |
| 5.8.5   | 3         | 0.56%   |
| 5.14.10 | 3         | 0.56%   |
| 4.9.20  | 3         | 0.56%   |
| 5.9.9   | 2         | 0.37%   |
| 5.8.16  | 2         | 0.37%   |
| 5.7.10  | 2         | 0.37%   |
| 5.6.0   | 2         | 0.37%   |
| 5.4.2   | 2         | 0.37%   |
| 5.17.6  | 2         | 0.37%   |
| 5.16.2  | 2         | 0.37%   |
| 5.16.19 | 2         | 0.37%   |
| 5.16.18 | 2         | 0.37%   |
| 5.16.15 | 2         | 0.37%   |
| 5.16.11 | 2         | 0.37%   |
| 5.15.2  | 2         | 0.37%   |
| 5.15.11 | 2         | 0.37%   |
| 5.14.16 | 2         | 0.37%   |
| 5.14.14 | 2         | 0.37%   |
| 5.13.12 | 2         | 0.37%   |
| 5.12.9  | 2         | 0.37%   |
| 5.12.0  | 2         | 0.37%   |
| 5.11.11 | 2         | 0.37%   |
| 5.10.43 | 2         | 0.37%   |
| 4.9.140 | 2         | 0.37%   |
| 4.4.0   | 2         | 0.37%   |
| 4.18.16 | 2         | 0.37%   |
| 4.1.38  | 2         | 0.37%   |
| 5.9.8   | 1         | 0.19%   |
| 5.9.3   | 1         | 0.19%   |
| 5.9.14  | 1         | 0.19%   |
| 5.9.13  | 1         | 0.19%   |
| 5.9.11  | 1         | 0.19%   |
| 5.9.1   | 1         | 0.19%   |
| 5.8.18  | 1         | 0.19%   |
| 5.8.13  | 1         | 0.19%   |
| 5.8.11  | 1         | 0.19%   |
| 5.8.1   | 1         | 0.19%   |
| 5.7.7   | 1         | 0.19%   |
| 5.7.16  | 1         | 0.19%   |
| 5.7.11  | 1         | 0.19%   |
| 5.7.0   | 1         | 0.19%   |
| 5.6.4   | 1         | 0.19%   |
| 5.6.13  | 1         | 0.19%   |
| 5.5.6   | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 128       | 24.47%  |
| 5.8     | 50        | 9.56%   |
| 4.15    | 49        | 9.37%   |
| 5.11    | 44        | 8.41%   |
| 5.10    | 35        | 6.69%   |
| 5.3     | 33        | 6.31%   |
| 5.13    | 29        | 5.54%   |
| 5.0     | 26        | 4.97%   |
| 5.16    | 23        | 4.4%    |
| 5.15    | 15        | 2.87%   |
| 4.18    | 15        | 2.87%   |
| 4.9     | 14        | 2.68%   |
| 5.9     | 11        | 2.1%    |
| 5.14    | 9         | 1.72%   |
| 4.19    | 8         | 1.53%   |
| 5.17    | 6         | 1.15%   |
| 5.12    | 6         | 1.15%   |
| 4.1     | 6         | 1.15%   |
| 5.7     | 5         | 0.96%   |
| 5.6     | 4         | 0.76%   |
| 5.5     | 2         | 0.38%   |
| 4.4     | 2         | 0.38%   |
| 5.18    | 1         | 0.19%   |
| 4.7     | 1         | 0.19%   |
| 3.10    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 471       | 97.11%  |
| i686    | 11        | 2.27%   |
| aarch64 | 3         | 0.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 244       | 48.8%   |
| Unknown    | 74        | 14.8%   |
| KDE5       | 69        | 13.8%   |
| KDE4       | 28        | 5.6%    |
| X-Cinnamon | 26        | 5.2%    |
| XFCE       | 22        | 4.4%    |
| KDE        | 12        | 2.4%    |
| MATE       | 6         | 1.2%    |
| Cinnamon   | 6         | 1.2%    |
| Unity      | 4         | 0.8%    |
| i3         | 3         | 0.6%    |
| Trinity    | 1         | 0.2%    |
| Pantheon   | 1         | 0.2%    |
| LXQt       | 1         | 0.2%    |
| LXDE       | 1         | 0.2%    |
| Deepin     | 1         | 0.2%    |
| Budgie     | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 393       | 79.88%  |
| Wayland | 47        | 9.55%   |
| Unknown | 43        | 8.74%   |
| Tty     | 9         | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 273       | 55.04%  |
| GDM     | 79        | 15.93%  |
| SDDM    | 59        | 11.9%   |
| KDM     | 28        | 5.65%   |
| GDM3    | 25        | 5.04%   |
| TDM     | 18        | 3.63%   |
| LightDM | 13        | 2.62%   |
| XDM     | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_IL      | 184       | 37.25%  |
| en_US      | 147       | 29.76%  |
| Unknown    | 87        | 17.61%  |
| ru_RU      | 27        | 5.47%   |
| he_IL      | 27        | 5.47%   |
| C          | 6         | 1.21%   |
| fr_FR      | 4         | 0.81%   |
| en_GB      | 3         | 0.61%   |
| POSIX      | 2         | 0.4%    |
| it_IT      | 1         | 0.2%    |
| es_ES      | 1         | 0.2%    |
| en_US.UTF8 | 1         | 0.2%    |
| en_NZ      | 1         | 0.2%    |
| en_CA      | 1         | 0.2%    |
| en_AU      | 1         | 0.2%    |
| C.UTF8     | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 249       | 50.2%   |
| EFI  | 247       | 49.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 384       | 78.21%  |
| Btrfs   | 35        | 7.13%   |
| Overlay | 34        | 6.92%   |
| Unknown | 24        | 4.89%   |
| Xfs     | 9         | 1.83%   |
| Zfs     | 1         | 0.2%    |
| Tmpfs   | 1         | 0.2%    |
| F2fs    | 1         | 0.2%    |
| Ext3    | 1         | 0.2%    |
| Ext2    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 287       | 58.33%  |
| GPT     | 148       | 30.08%  |
| MBR     | 57        | 11.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 430       | 87.76%  |
| Yes       | 60        | 12.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 346       | 70.47%  |
| Yes       | 145       | 29.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 112       | 23.14%  |
| Lenovo                  | 89        | 18.39%  |
| Dell                    | 71        | 14.67%  |
| Gigabyte Technology     | 68        | 14.05%  |
| Hewlett-Packard         | 51        | 10.54%  |
| Intel                   | 13        | 2.69%   |
| MSI                     | 10        | 2.07%   |
| ASRock                  | 10        | 2.07%   |
| Acer                    | 8         | 1.65%   |
| Apple                   | 7         | 1.45%   |
| Samsung Electronics     | 6         | 1.24%   |
| Toshiba                 | 4         | 0.83%   |
| Unknown                 | 4         | 0.83%   |
| Supermicro              | 3         | 0.62%   |
| LG Electronics          | 3         | 0.62%   |
| Fujitsu                 | 3         | 0.62%   |
| Pegatron                | 2         | 0.41%   |
| Nvidia                  | 2         | 0.41%   |
| Fujitsu Siemens         | 2         | 0.41%   |
| Foxconn                 | 2         | 0.41%   |
| Timi                    | 1         | 0.21%   |
| System76                | 1         | 0.21%   |
| Shuttle                 | 1         | 0.21%   |
| Raspberry Pi Foundation | 1         | 0.21%   |
| Notebook                | 1         | 0.21%   |
| Neousys Technology      | 1         | 0.21%   |
| Microsoft               | 1         | 0.21%   |
| IP3 Tech                | 1         | 0.21%   |
| HUAWEI                  | 1         | 0.21%   |
| HARDKERNEL              | 1         | 0.21%   |
| Biostar                 | 1         | 0.21%   |
| AZW                     | 1         | 0.21%   |
| AMI                     | 1         | 0.21%   |
| Alienware               | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASUS All Series                                                                          | 9         | 1.86%   |
| Unknown                                                                                  | 7         | 1.45%   |
| MSI MS-7592                                                                              | 3         | 0.62%   |
| HP Compaq Presario CQ61                                                                  | 3         | 0.62%   |
| Gigabyte H61M-S1                                                                         | 3         | 0.62%   |
| ASUS UX331UA                                                                             | 3         | 0.62%   |
| ASUS P8H61-M LX R2.0                                                                     | 3         | 0.62%   |
| ASUS H110M-A/M.2                                                                         | 3         | 0.62%   |
| Nvidia Tegra                                                                             | 2         | 0.41%   |
| Lenovo V14-IIL 82C4                                                                      | 2         | 0.41%   |
| Lenovo IdeaPad Y700-15ISK 80NV                                                           | 2         | 0.41%   |
| Lenovo IdeaPad L340-15IWL 81LG                                                           | 2         | 0.41%   |
| Lenovo IdeaPad 5 14ITL05 82FE                                                            | 2         | 0.41%   |
| Intel NUC8i7BEH                                                                          | 2         | 0.41%   |
| Intel NUC8i3BEH                                                                          | 2         | 0.41%   |
| Intel DH77EB AAG39073-304                                                                | 2         | 0.41%   |
| HP ZBook 15 G3                                                                           | 2         | 0.41%   |
| HP Spectre x360 Convertible 13-aw0xxx                                                    | 2         | 0.41%   |
| HP Pavilion Notebook                                                                     | 2         | 0.41%   |
| HP EliteBook 840 G5                                                                      | 2         | 0.41%   |
| Gigabyte Z390 GAMING X                                                                   | 2         | 0.41%   |
| Gigabyte X570 AORUS ULTRA                                                                | 2         | 0.41%   |
| Gigabyte P55-UD3L                                                                        | 2         | 0.41%   |
| Gigabyte H61M-S2PV                                                                       | 2         | 0.41%   |
| Gigabyte H55M-D2H                                                                        | 2         | 0.41%   |
| Gigabyte B460HD3                                                                         | 2         | 0.41%   |
| Fujitsu LIFEBOOK AH530                                                                   | 2         | 0.41%   |
| Dell OptiPlex 755                                                                        | 2         | 0.41%   |
| Dell OptiPlex 7050                                                                       | 2         | 0.41%   |
| Dell Latitude E6330                                                                      | 2         | 0.41%   |
| Dell Latitude 7400                                                                       | 2         | 0.41%   |
| Dell Latitude 5410                                                                       | 2         | 0.41%   |
| Dell Inspiron 3593                                                                       | 2         | 0.41%   |
| Dell Inspiron 3542                                                                       | 2         | 0.41%   |
| Dell Inspiron 13-5378                                                                    | 2         | 0.41%   |
| ASUS ZenBook UX425EA_UX425EA                                                             | 2         | 0.41%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                                                     | 2         | 0.41%   |
| ASUS TUF Gaming B550-PLUS                                                                | 2         | 0.41%   |
| ASUS ROG STRIX Z390-E GAMING                                                             | 2         | 0.41%   |
| ASUS PRIME Z490-P                                                                        | 2         | 0.41%   |
| ASUS PRIME X470-PRO                                                                      | 2         | 0.41%   |
| ASUS PRIME H310M-E R2.0                                                                  | 2         | 0.41%   |
| ASUS PRIME B560M-K                                                                       | 2         | 0.41%   |
| ASUS N550JV                                                                              | 2         | 0.41%   |
| Toshiba Satellite P50t-B-10T                                                             | 1         | 0.21%   |
| Toshiba Satellite L755                                                                   | 1         | 0.21%   |
| Toshiba Satellite A200                                                                   | 1         | 0.21%   |
| Toshiba PORTEGE R700                                                                     | 1         | 0.21%   |
| Timi TM1701                                                                              | 1         | 0.21%   |
| System76 Gazelle                                                                         | 1         | 0.21%   |
| Supermicro X9DAi                                                                         | 1         | 0.21%   |
| Supermicro X8DAL                                                                         | 1         | 0.21%   |
| Supermicro Super Server                                                                  | 1         | 0.21%   |
| Shuttle SH87R                                                                            | 1         | 0.21%   |
| Samsung N248P                                                                            | 1         | 0.21%   |
| Samsung Galaxy Book 12 LTE                                                               | 1         | 0.21%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV                                                 | 1         | 0.21%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.21%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                                                      | 1         | 0.21%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B                                               | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 32        | 6.61%   |
| Dell Latitude      | 23        | 4.75%   |
| ASUS PRIME         | 21        | 4.34%   |
| Lenovo IdeaPad     | 18        | 3.72%   |
| Dell Inspiron      | 16        | 3.31%   |
| ASUS ROG           | 13        | 2.69%   |
| Dell Vostro        | 11        | 2.27%   |
| Dell OptiPlex      | 10        | 2.07%   |
| ASUS VivoBook      | 9         | 1.86%   |
| ASUS All           | 9         | 1.86%   |
| HP Pavilion        | 8         | 1.65%   |
| Lenovo ThinkCentre | 7         | 1.45%   |
| HP Compaq          | 7         | 1.45%   |
| Acer Aspire        | 7         | 1.45%   |
| Unknown            | 7         | 1.45%   |
| Lenovo Legion      | 6         | 1.24%   |
| HP EliteBook       | 6         | 1.24%   |
| Dell XPS           | 6         | 1.24%   |
| ASUS TUF           | 6         | 1.24%   |
| ASUS ZenBook       | 5         | 1.03%   |
| Lenovo Yoga        | 4         | 0.83%   |
| HP ProBook         | 4         | 0.83%   |
| ASUS H110M-A       | 4         | 0.83%   |
| Toshiba Satellite  | 3         | 0.62%   |
| MSI MS-7592        | 3         | 0.62%   |
| Lenovo V520-15IKL  | 3         | 0.62%   |
| HP ZBook           | 3         | 0.62%   |
| HP Spectre         | 3         | 0.62%   |
| HP ENVY            | 3         | 0.62%   |
| Gigabyte Z390      | 3         | 0.62%   |
| Gigabyte H61M-S1   | 3         | 0.62%   |
| Fujitsu LIFEBOOK   | 3         | 0.62%   |
| ASUS UX331UA       | 3         | 0.62%   |
| ASUS P8H61-M       | 3         | 0.62%   |
| Nvidia Tegra       | 2         | 0.41%   |
| Lenovo V14-IIL     | 2         | 0.41%   |
| Lenovo ThinkBook   | 2         | 0.41%   |
| Lenovo MIIX        | 2         | 0.41%   |
| Lenovo IdeaPadFlex | 2         | 0.41%   |
| Lenovo G50-80      | 2         | 0.41%   |
| Intel NUC8i7BEH    | 2         | 0.41%   |
| Intel NUC8i3BEH    | 2         | 0.41%   |
| Intel DH77EB       | 2         | 0.41%   |
| HP ProDesk         | 2         | 0.41%   |
| HP Laptop          | 2         | 0.41%   |
| Gigabyte X570      | 2         | 0.41%   |
| Gigabyte P55-UD3L  | 2         | 0.41%   |
| Gigabyte H61M-S2PV | 2         | 0.41%   |
| Gigabyte H55M-D2H  | 2         | 0.41%   |
| Gigabyte B560M     | 2         | 0.41%   |
| Gigabyte B460HD3   | 2         | 0.41%   |
| Gigabyte B450M     | 2         | 0.41%   |
| Dell Precision     | 2         | 0.41%   |
| ASUS N550JV        | 2         | 0.41%   |
| ASUS ASUSPRO       | 2         | 0.41%   |
| ASUS ASUS          | 2         | 0.41%   |
| Toshiba PORTEGE    | 1         | 0.21%   |
| Timi TM1701        | 1         | 0.21%   |
| System76 Gazelle   | 1         | 0.21%   |
| Supermicro X9DAi   | 1         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 62        | 12.81%  |
| 2018    | 60        | 12.4%   |
| 2020    | 48        | 9.92%   |
| 2017    | 39        | 8.06%   |
| 2012    | 37        | 7.64%   |
| 2016    | 33        | 6.82%   |
| 2014    | 29        | 5.99%   |
| 2015    | 27        | 5.58%   |
| 2013    | 26        | 5.37%   |
| 2010    | 26        | 5.37%   |
| 2011    | 25        | 5.17%   |
| 2021    | 24        | 4.96%   |
| 2009    | 20        | 4.13%   |
| 2008    | 12        | 2.48%   |
| 2007    | 10        | 2.07%   |
| 2006    | 3         | 0.62%   |
| Unknown | 3         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 234       | 48.35%  |
| Desktop        | 210       | 43.39%  |
| Mini pc        | 12        | 2.48%   |
| Convertible    | 11        | 2.27%   |
| Tablet         | 5         | 1.03%   |
| Server         | 5         | 1.03%   |
| All in one     | 4         | 0.83%   |
| System on chip | 3         | 0.62%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 449       | 92.39%  |
| Enabled  | 37        | 7.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 484       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 124       | 25.41%  |
| 4.01-8.0    | 98        | 20.08%  |
| 8.01-16.0   | 76        | 15.57%  |
| 3.01-4.0    | 71        | 14.55%  |
| 32.01-64.0  | 68        | 13.93%  |
| 1.01-2.0    | 22        | 4.51%   |
| 64.01-256.0 | 18        | 3.69%   |
| 2.01-3.0    | 6         | 1.23%   |
| 24.01-32.0  | 4         | 0.82%   |
| 0.51-1.0    | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 170       | 32.26%  |
| 2.01-3.0   | 118       | 22.39%  |
| 4.01-8.0   | 83        | 15.75%  |
| 3.01-4.0   | 68        | 12.9%   |
| 8.01-16.0  | 40        | 7.59%   |
| 0.51-1.0   | 34        | 6.45%   |
| 0.01-0.5   | 7         | 1.33%   |
| 16.01-24.0 | 6         | 1.14%   |
| 24.01-32.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 311       | 62.96%  |
| 2      | 107       | 21.66%  |
| 3      | 42        | 8.5%    |
| 4      | 14        | 2.83%   |
| 5      | 9         | 1.82%   |
| 6      | 4         | 0.81%   |
| 0      | 3         | 0.61%   |
| 7      | 2         | 0.4%    |
| 10     | 1         | 0.2%    |
| 8      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 329       | 67.28%  |
| Yes       | 160       | 32.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 422       | 87.01%  |
| No        | 63        | 12.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 70.52%  |
| No        | 143       | 29.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 54.19%  |
| No        | 224       | 45.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Israel  | 484       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Tel Aviv              | 211       | 41.37%  |
| Ramat Gan             | 43        | 8.43%   |
| Haifa                 | 30        | 5.88%   |
| Petaẖ Tiqwa         | 20        | 3.92%   |
| Jerusalem             | 20        | 3.92%   |
| Rishon LeZiyyon       | 15        | 2.94%   |
| Herzliya              | 15        | 2.94%   |
| Givatayim             | 10        | 1.96%   |
| Rehovot               | 9         | 1.76%   |
| Netanya               | 9         | 1.76%   |
| Holon                 | 8         | 1.57%   |
| Ramat HaSharon        | 7         | 1.37%   |
| Qiryat Ata            | 6         | 1.18%   |
| Nahariya              | 6         | 1.18%   |
| Kfar Saba             | 6         | 1.18%   |
| Raanana               | 5         | 0.98%   |
| Kiryat Ono            | 5         | 0.98%   |
| Beersheba             | 4         | 0.78%   |
| Ashquelon             | 4         | 0.78%   |
| Ashdod                | 4         | 0.78%   |
| Pardes Hanna Karkur   | 3         | 0.59%   |
| Ness Ziona            | 3         | 0.59%   |
| Hod HaSharon          | 3         | 0.59%   |
| Ganei Tikva           | 3         | 0.59%   |
| Bet Shemesh           | 3         | 0.59%   |
| Yavne                 | 2         | 0.39%   |
| Tiberias              | 2         | 0.39%   |
| Qiryat Moẕqin       | 2         | 0.39%   |
| Lod                   | 2         | 0.39%   |
| Karmi’el            | 2         | 0.39%   |
| Hadera                | 2         | 0.39%   |
| Givat Shmuel          | 2         | 0.39%   |
| Dimona                | 2         | 0.39%   |
| Be'er Ya'aqov         | 2         | 0.39%   |
| Bat Yam               | 2         | 0.39%   |
| Afula                 | 2         | 0.39%   |
| Yehud                 | 1         | 0.2%    |
| Tel Mond              | 1         | 0.2%    |
| Shelomi               | 1         | 0.2%    |
| Sha`ar Ha`Amaqim      | 1         | 0.2%    |
| Sderot                | 1         | 0.2%    |
| Sde Nehemya           | 1         | 0.2%    |
| Rosh HaAyin           | 1         | 0.2%    |
| Ramla                 | 1         | 0.2%    |
| Qiryat Bialik         | 1         | 0.2%    |
| Qazir                 | 1         | 0.2%    |
| Petaбє– Tiqwa     | 1         | 0.2%    |
| Petaáº– Tiqwa     | 1         | 0.2%    |
| Pardesiyya            | 1         | 0.2%    |
| Or Yehuda             | 1         | 0.2%    |
| Ofakim                | 1         | 0.2%    |
| Nazerat 'Illit        | 1         | 0.2%    |
| Modiin Makkabbim Reut | 1         | 0.2%    |
| Meitar                | 1         | 0.2%    |
| Mazkeret Batya        | 1         | 0.2%    |
| Lapid                 | 1         | 0.2%    |
| Kiryat Tiv'on         | 1         | 0.2%    |
| Kiryat Gat            | 1         | 0.2%    |
| Kinneret              | 1         | 0.2%    |
| Kfar Yona             | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 127       | 202    | 17.89%  |
| Samsung Electronics       | 99        | 133    | 13.94%  |
| Seagate                   | 81        | 120    | 11.41%  |
| SanDisk                   | 55        | 65     | 7.75%   |
| Toshiba                   | 44        | 51     | 6.2%    |
| Hitachi                   | 42        | 65     | 5.92%   |
| Kingston                  | 41        | 45     | 5.77%   |
| Intel                     | 29        | 35     | 4.08%   |
| SK Hynix                  | 26        | 37     | 3.66%   |
| Crucial                   | 21        | 40     | 2.96%   |
| HGST                      | 20        | 23     | 2.82%   |
| Transcend                 | 16        | 20     | 2.25%   |
| Micron Technology         | 15        | 18     | 2.11%   |
| Unknown                   | 13        | 14     | 1.83%   |
| Corsair                   | 11        | 16     | 1.55%   |
| A-DATA Technology         | 9         | 11     | 1.27%   |
| XPG                       | 6         | 12     | 0.85%   |
| StoreJet                  | 5         | 5      | 0.7%    |
| Apple                     | 5         | 5      | 0.7%    |
| Phison                    | 4         | 5      | 0.56%   |
| LITEON                    | 4         | 4      | 0.56%   |
| Fujitsu                   | 4         | 5      | 0.56%   |
| Silicon Motion            | 3         | 3      | 0.42%   |
| KIOXIA                    | 3         | 3      | 0.42%   |
| SPCC                      | 2         | 2      | 0.28%   |
| OCZ                       | 2         | 2      | 0.28%   |
| Netac                     | 2         | 2      | 0.28%   |
| Micron/Crucial Technology | 2         | 2      | 0.28%   |
| China                     | 2         | 3      | 0.28%   |
| Apacer                    | 2         | 2      | 0.28%   |
| USB3.0                    | 1         | 1      | 0.14%   |
| TPH01204000GB             | 1         | 1      | 0.14%   |
| PLEXTOR                   | 1         | 1      | 0.14%   |
| Patriot                   | 1         | 1      | 0.14%   |
| OCZ-VERTEX3               | 1         | 1      | 0.14%   |
| NGFF                      | 1         | 1      | 0.14%   |
| Marvell                   | 1         | 2      | 0.14%   |
| LS600                     | 1         | 1      | 0.14%   |
| Lexar                     | 1         | 1      | 0.14%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.14%   |
| KingSpec                  | 1         | 1      | 0.14%   |
| JMicron                   | 1         | 1      | 0.14%   |
| IBM/Hitachi               | 1         | 1      | 0.14%   |
| External                  | 1         | 1      | 0.14%   |
| ADATA Technology          | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| SanDisk SSD PLUS 240GB              | 12        | 1.55%   |
| Kingston SA400S37240G 240GB SSD     | 10        | 1.29%   |
| Hitachi HDS721050CLA362 500GB       | 9         | 1.16%   |
| Samsung SSD 860 EVO 500GB           | 8         | 1.03%   |
| Samsung NVMe SSD Drive 512GB        | 8         | 1.03%   |
| Intel NVMe SSD Drive 512GB          | 7         | 0.9%    |
| Toshiba DT01ACA100 1TB              | 6         | 0.77%   |
| SK Hynix NVMe SSD Drive 256GB       | 6         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 0.77%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 0.77%   |
| Samsung SSD 850 EVO 250GB           | 6         | 0.77%   |
| Samsung NVMe SSD Drive 500GB        | 6         | 0.77%   |
| HGST HTS545050A7E680 500GB          | 6         | 0.77%   |
| WDC WD20PURX-64P6ZY0 2TB            | 5         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB      | 5         | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 0.64%   |
| Crucial CT500MX500SSD1 500GB        | 5         | 0.64%   |
| Unknown MMC Card  64GB              | 4         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB        | 4         | 0.52%   |
| SK Hynix NVMe SSD Drive 512GB       | 4         | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB      | 4         | 0.52%   |
| Sandisk NVMe SSD Drive 512GB        | 4         | 0.52%   |
| SanDisk Extreme SSD 500GB           | 4         | 0.52%   |
| Samsung SSD 850 EVO 500GB           | 4         | 0.52%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 0.52%   |
| Samsung NVMe SSD Drive 250GB        | 4         | 0.52%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 0.52%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 0.52%   |
| Intel SSDPEKNW512G8 512GB           | 4         | 0.52%   |
| HGST HTS721010A9E630 1TB            | 4         | 0.52%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 3         | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB            | 3         | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB             | 3         | 0.39%   |
| WDC WD10EADS-00L5B1 1TB             | 3         | 0.39%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 3         | 0.39%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.39%   |
| Toshiba DT01ACA050 500GB            | 3         | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB      | 3         | 0.39%   |
| Seagate Expansion Desk 10TB         | 3         | 0.39%   |
| Sandisk NVMe SSD Drive 256GB        | 3         | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB      | 3         | 0.39%   |
| Samsung SSD 860 QVO 1TB             | 3         | 0.39%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.39%   |
| Samsung NVMe SSD Drive 1TB          | 3         | 0.39%   |
| Samsung NVMe SSD Drive 1024GB       | 3         | 0.39%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 3         | 0.39%   |
| Kingston SUV400S37120G 120GB SSD    | 3         | 0.39%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.39%   |
| Intel SSDPEKKW256G7 256GB           | 3         | 0.39%   |
| Hitachi HDS721050CLA360 500GB       | 3         | 0.39%   |
| HGST HTS545050A7E380 500GB          | 3         | 0.39%   |
| HGST HTS541010A9E680 1TB            | 3         | 0.39%   |
| XPG NVMe SSD Drive 2TB              | 2         | 0.26%   |
| XPG NVMe SSD Drive 1024GB           | 2         | 0.26%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2         | 0.26%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 2         | 0.26%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 2         | 0.26%   |
| WDC WD5000AZRX-00A8LB0 500GB        | 2         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 103       | 170    | 34.45%  |
| Seagate             | 81        | 119    | 27.09%  |
| Hitachi             | 42        | 65     | 14.05%  |
| Toshiba             | 34        | 39     | 11.37%  |
| HGST                | 20        | 23     | 6.69%   |
| Samsung Electronics | 7         | 13     | 2.34%   |
| Fujitsu             | 4         | 5      | 1.34%   |
| Apple               | 3         | 3      | 1%      |
| USB3.0              | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |
| TPH01204000GB       | 1         | 1      | 0.33%   |
| StoreJet            | 1         | 1      | 0.33%   |
| IBM/Hitachi         | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 54     | 18.86%  |
| SanDisk             | 38        | 47     | 16.67%  |
| Kingston            | 34        | 38     | 14.91%  |
| Crucial             | 16        | 34     | 7.02%   |
| Transcend           | 15        | 19     | 6.58%   |
| Micron Technology   | 11        | 12     | 4.82%   |
| Intel               | 10        | 12     | 4.39%   |
| Corsair             | 10        | 14     | 4.39%   |
| SK Hynix            | 8         | 18     | 3.51%   |
| A-DATA Technology   | 8         | 10     | 3.51%   |
| WDC                 | 7         | 7      | 3.07%   |
| LITEON              | 4         | 4      | 1.75%   |
| StoreJet            | 2         | 2      | 0.88%   |
| OCZ                 | 2         | 2      | 0.88%   |
| Netac               | 2         | 2      | 0.88%   |
| China               | 2         | 3      | 0.88%   |
| Apple               | 2         | 2      | 0.88%   |
| Apacer              | 2         | 2      | 0.88%   |
| Toshiba             | 1         | 1      | 0.44%   |
| SPCC                | 1         | 1      | 0.44%   |
| Seagate             | 1         | 1      | 0.44%   |
| PLEXTOR             | 1         | 1      | 0.44%   |
| Patriot             | 1         | 1      | 0.44%   |
| OCZ-VERTEX3         | 1         | 1      | 0.44%   |
| NGFF                | 1         | 1      | 0.44%   |
| LS600               | 1         | 1      | 0.44%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.44%   |
| KingSpec            | 1         | 1      | 0.44%   |
| JMicron             | 1         | 1      | 0.44%   |
| External            | 1         | 1      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 244       | 442    | 38.92%  |
| SSD     | 200       | 294    | 31.9%   |
| NVMe    | 168       | 212    | 26.79%  |
| MMC     | 12        | 14     | 1.91%   |
| Unknown | 3         | 4      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 348       | 712    | 63.16%  |
| NVMe | 168       | 212    | 30.49%  |
| SAS  | 23        | 28     | 4.17%   |
| MMC  | 12        | 14     | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 270       | 446    | 58.82%  |
| 0.51-1.0   | 116       | 168    | 25.27%  |
| 1.01-2.0   | 47        | 67     | 10.24%  |
| 2.01-3.0   | 10        | 13     | 2.18%   |
| 3.01-4.0   | 9         | 29     | 1.96%   |
| 4.01-10.0  | 6         | 8      | 1.31%   |
| 10.01-20.0 | 1         | 5      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 135       | 27%     |
| 251-500        | 127       | 25.4%   |
| 501-1000       | 72        | 14.4%   |
| 1001-2000      | 31        | 6.2%    |
| 1-20           | 31        | 6.2%    |
| 51-100         | 26        | 5.2%    |
| 2001-3000      | 25        | 5%      |
| More than 3000 | 22        | 4.4%    |
| 21-50          | 20        | 4%      |
| Unknown        | 11        | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 208       | 40%     |
| 21-50          | 99        | 19.04%  |
| 101-250        | 70        | 13.46%  |
| 51-100         | 45        | 8.65%   |
| 251-500        | 30        | 5.77%   |
| 1001-2000      | 22        | 4.23%   |
| 501-1000       | 17        | 3.27%   |
| Unknown        | 11        | 2.12%   |
| 2001-3000      | 10        | 1.92%   |
| More than 3000 | 8         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 5         | 7      | 8.47%   |
| WDC WD10EARS-00Y5B1 1TB               | 2         | 2      | 3.39%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 3.39%   |
| Hitachi HDS721050CLA362 500GB         | 2         | 3      | 3.39%   |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 3.39%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 1.69%   |
| WDC WD5001AALS-00LWTA0 500GB          | 1         | 1      | 1.69%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.69%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 1.69%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 1.69%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 1      | 1.69%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 2      | 1.69%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 1.69%   |
| WDC WD10EZEX-00ZF5A0 1TB              | 1         | 1      | 1.69%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 1.69%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 1      | 1.69%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 1.69%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.69%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 1.69%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 1.69%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 1.69%   |
| SK Hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 1.69%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.69%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 1.69%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.69%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.69%   |
| Seagate ST3750528AS 752GB             | 1         | 1      | 1.69%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.69%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.69%   |
| Seagate ST2000DM001-1ER164 2TB        | 1         | 1      | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 2      | 1.69%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 1.69%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 1.69%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 1.69%   |
| SanDisk SSD PLUS 240GB                | 1         | 1      | 1.69%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 2      | 1.69%   |
| Intel SSDSCKKF256H6 SATA 256GB        | 1         | 1      | 1.69%   |
| Hitachi HUA723020ALA640 2TB           | 1         | 1      | 1.69%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 1.69%   |
| Hitachi HTS545025B9A300 250GB         | 1         | 1      | 1.69%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 1.69%   |
| Hitachi HDS721050CLA360 500GB         | 1         | 1      | 1.69%   |
| Hitachi HDS721032CLA362 320GB         | 1         | 1      | 1.69%   |
| Hitachi HDP725050GLAT80 500GB         | 1         | 1      | 1.69%   |
| Hitachi HDP725050GLA360 500GB         | 1         | 1      | 1.69%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 1.69%   |
| HGST HCC545050A7E380 500GB            | 1         | 1      | 1.69%   |
| Fujitsu MHY2160BH 160GB               | 1         | 1      | 1.69%   |
| Corsair Neutron XT SSD 240GB          | 1         | 1      | 1.69%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 1.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 16     | 24.56%  |
| Seagate             | 10        | 12     | 17.54%  |
| Hitachi             | 10        | 11     | 17.54%  |
| HGST                | 9         | 11     | 15.79%  |
| Toshiba             | 5         | 5      | 8.77%   |
| SK Hynix            | 2         | 6      | 3.51%   |
| SanDisk             | 2         | 2      | 3.51%   |
| Corsair             | 2         | 2      | 3.51%   |
| Samsung Electronics | 1         | 2      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| Fujitsu             | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 16     | 28%     |
| Seagate             | 10        | 12     | 20%     |
| Hitachi             | 10        | 11     | 20%     |
| HGST                | 9         | 11     | 18%     |
| Toshiba             | 5         | 5      | 10%     |
| Samsung Electronics | 1         | 2      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 58     | 85.42%  |
| SSD  | 7         | 11     | 14.58%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK3256GSY 320GB         | 1         | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS547550A9E384 500GB   | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 297       | 617    | 56.9%   |
| Works    | 176       | 276    | 33.72%  |
| Malfunc  | 47        | 69     | 9%      |
| Failed   | 2         | 4      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 385       | 62.7%   |
| Samsung Electronics          | 54        | 8.79%   |
| AMD                          | 43        | 7%      |
| Sandisk                      | 34        | 5.54%   |
| SK Hynix                     | 18        | 2.93%   |
| Toshiba America Info Systems | 9         | 1.47%   |
| JMicron Technology           | 9         | 1.47%   |
| ADATA Technology             | 8         | 1.3%    |
| Micron/Crucial Technology    | 7         | 1.14%   |
| Kingston Technology Company  | 7         | 1.14%   |
| Phison Electronics           | 6         | 0.98%   |
| Nvidia                       | 6         | 0.98%   |
| ASMedia Technology           | 6         | 0.98%   |
| Marvell Technology Group     | 5         | 0.81%   |
| Silicon Motion               | 4         | 0.65%   |
| Micron Technology            | 4         | 0.65%   |
| KIOXIA                       | 4         | 0.65%   |
| VIA Technologies             | 2         | 0.33%   |
| Union Memory (Shenzhen)      | 1         | 0.16%   |
| Shenzhen Longsys Electronics | 1         | 0.16%   |
| LSI Logic / Symbios Logic    | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 41        | 5.87%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 35        | 5.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 33        | 4.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23        | 3.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20        | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 2.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18        | 2.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14        | 2.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 2.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 13        | 1.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13        | 1.86%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 12        | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 12        | 1.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 12        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11        | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10        | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 1.43%   |
| Intel SATA Controller [RAID mode]                                                       | 10        | 1.43%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 1.43%   |
| Intel SSD 660P Series                                                                   | 9         | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 9         | 1.29%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 8         | 1.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 1.15%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1%      |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 1%      |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 6         | 0.86%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6         | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6         | 0.86%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6         | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5         | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 0.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 0.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.57%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 4         | 0.57%   |
| SK Hynix Gold P31 SSD                                                                   | 4         | 0.57%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.57%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 4         | 0.57%   |
| Micron/Crucial Non-Volatile memory controller                                           | 4         | 0.57%   |
| Micron Non-Volatile memory controller                                                   | 4         | 0.57%   |
| KIOXIA Non-Volatile memory controller                                                   | 4         | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                         | 4         | 0.57%   |
| Intel SSD 600P Series                                                                   | 4         | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 0.57%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 3         | 0.43%   |
| SK Hynix Non-Volatile memory controller                                                 | 3         | 0.43%   |
| SK Hynix BC511                                                                          | 3         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 347       | 55.79%  |
| NVMe | 169       | 27.17%  |
| IDE  | 60        | 9.65%   |
| RAID | 44        | 7.07%   |
| SAS  | 2         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 429       | 88.64%  |
| AMD          | 51        | 10.54%  |
| ARM          | 2         | 0.41%   |
| CentaurHauls | 1         | 0.21%   |
| Unknown      | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 17        | 3.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 8         | 1.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8         | 1.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 8         | 1.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7         | 1.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 7         | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 7         | 1.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 6         | 1.23%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 5         | 1.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 5         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 5         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 1.03%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 0.82%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4         | 0.82%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4         | 0.82%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 0.82%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4         | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 4         | 0.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4         | 0.82%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 0.82%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4         | 0.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 0.82%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4         | 0.82%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 4         | 0.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4         | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 0.82%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3         | 0.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.62%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3         | 0.62%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 3         | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.62%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3         | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 0.62%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3         | 0.62%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3         | 0.62%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.62%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 0.62%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.62%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 0.62%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 0.62%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 2         | 0.41%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2         | 0.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2         | 0.41%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 0.41%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 0.41%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 2         | 0.41%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 0.41%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 0.41%   |
| Intel Core i7-8700T CPU @ 2.40GHz           | 2         | 0.41%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 2         | 0.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 153       | 31.55%  |
| Intel Core i5           | 114       | 23.51%  |
| Intel Core i3           | 46        | 9.48%   |
| Other                   | 32        | 6.6%    |
| Intel Pentium Dual-Core | 15        | 3.09%   |
| Intel Core 2 Duo        | 15        | 3.09%   |
| AMD Ryzen 5             | 14        | 2.89%   |
| Intel Pentium           | 12        | 2.47%   |
| Intel Xeon              | 9         | 1.86%   |
| Intel Celeron           | 8         | 1.65%   |
| Intel Atom              | 8         | 1.65%   |
| AMD Ryzen 9             | 8         | 1.65%   |
| AMD Ryzen 7             | 8         | 1.65%   |
| Intel Pentium Dual      | 5         | 1.03%   |
| Intel Genuine           | 4         | 0.82%   |
| Intel Core i9           | 4         | 0.82%   |
| AMD A8                  | 4         | 0.82%   |
| AMD A6                  | 3         | 0.62%   |
| AMD FX                  | 2         | 0.41%   |
| AMD A10                 | 2         | 0.41%   |
| Intel Xeon Gold         | 1         | 0.21%   |
| Intel Pentium Silver    | 1         | 0.21%   |
| Intel Pentium Gold      | 1         | 0.21%   |
| Intel Pentium 4         | 1         | 0.21%   |
| Intel Core M            | 1         | 0.21%   |
| Intel Core 2 Quad       | 1         | 0.21%   |
| Intel Core 2            | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| CentaurHauls VIA C7     | 1         | 0.21%   |
| AMD Turion 64 X2 Mobile | 1         | 0.21%   |
| AMD Ryzen Threadripper  | 1         | 0.21%   |
| AMD Ryzen 7 PRO         | 1         | 0.21%   |
| AMD Ryzen 3 PRO         | 1         | 0.21%   |
| AMD Ryzen 3             | 1         | 0.21%   |
| AMD Phenom II X4        | 1         | 0.21%   |
| AMD Phenom              | 1         | 0.21%   |
| AMD EPYC                | 1         | 0.21%   |
| AMD Athlon II X3        | 1         | 0.21%   |
| AMD Athlon 64 X2        | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 210       | 43.3%   |
| 2       | 169       | 34.85%  |
| 6       | 45        | 9.28%   |
| 8       | 33        | 6.8%    |
| 12      | 9         | 1.86%   |
| 1       | 7         | 1.44%   |
| 16      | 6         | 1.24%   |
| 3       | 2         | 0.41%   |
| 32      | 1         | 0.21%   |
| 14      | 1         | 0.21%   |
| 10      | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 478       | 98.76%  |
| 2       | 4         | 0.83%   |
| 4       | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 350       | 72.02%  |
| 1       | 135       | 27.78%  |
| Unknown | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 472       | 97.52%  |
| Unknown        | 11        | 2.27%   |
| 32-bit         | 1         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 20.44%  |
| 0x806ea    | 27        | 5.36%   |
| 0x306c3    | 27        | 5.36%   |
| 0x306a9    | 25        | 4.96%   |
| 0x206a7    | 25        | 4.96%   |
| 0x1067a    | 23        | 4.56%   |
| 0x906e9    | 19        | 3.77%   |
| 0x906ea    | 18        | 3.57%   |
| 0x506e3    | 18        | 3.57%   |
| 0x806c1    | 16        | 3.17%   |
| 0x806ec    | 15        | 2.98%   |
| 0x806e9    | 12        | 2.38%   |
| 0x406e3    | 12        | 2.38%   |
| 0x706e5    | 11        | 2.18%   |
| 0x306d4    | 11        | 2.18%   |
| 0x906ed    | 8         | 1.59%   |
| 0x20655    | 8         | 1.59%   |
| 0x6fd      | 7         | 1.39%   |
| 0x08108109 | 7         | 1.39%   |
| 0xa0652    | 6         | 1.19%   |
| 0x806eb    | 6         | 1.19%   |
| 0xa0655    | 5         | 0.99%   |
| 0xa0653    | 5         | 0.99%   |
| 0x40651    | 5         | 0.99%   |
| 0x106e5    | 5         | 0.99%   |
| 0xa0671    | 4         | 0.79%   |
| 0x306e4    | 4         | 0.79%   |
| 0x08701021 | 4         | 0.79%   |
| 0x706a1    | 3         | 0.6%    |
| 0x406c4    | 3         | 0.6%    |
| 0x10676    | 3         | 0.6%    |
| 0x08701013 | 3         | 0.6%    |
| 0x0800820d | 3         | 0.6%    |
| 0x06001119 | 3         | 0.6%    |
| 0x90672    | 2         | 0.4%    |
| 0x806d1    | 2         | 0.4%    |
| 0x6fa      | 2         | 0.4%    |
| 0x20652    | 2         | 0.4%    |
| 0x106ca    | 2         | 0.4%    |
| 0x106a5    | 2         | 0.4%    |
| 0x0a50000c | 2         | 0.4%    |
| 0x08600104 | 2         | 0.4%    |
| 0x08108102 | 2         | 0.4%    |
| 0x06003106 | 2         | 0.4%    |
| 0x010000c8 | 2         | 0.4%    |
| 0xa0660    | 1         | 0.2%    |
| 0x906ec    | 1         | 0.2%    |
| 0x906eb    | 1         | 0.2%    |
| 0x906c0    | 1         | 0.2%    |
| 0x906a3    | 1         | 0.2%    |
| 0x6f6      | 1         | 0.2%    |
| 0x6f4      | 1         | 0.2%    |
| 0x506e0    | 1         | 0.2%    |
| 0x506c9    | 1         | 0.2%    |
| 0x406c3    | 1         | 0.2%    |
| 0x40671    | 1         | 0.2%    |
| 0x30673    | 1         | 0.2%    |
| 0x206c2    | 1         | 0.2%    |
| 0x106c2    | 1         | 0.2%    |
| 0x0a201016 | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 133       | 27.42%  |
| Haswell          | 44        | 9.07%   |
| Skylake          | 36        | 7.42%   |
| IvyBridge        | 34        | 7.01%   |
| Penryn           | 31        | 6.39%   |
| SandyBridge      | 28        | 5.77%   |
| CometLake        | 20        | 4.12%   |
| TigerLake        | 18        | 3.71%   |
| IceLake          | 18        | 3.71%   |
| Zen 2            | 13        | 2.68%   |
| Westmere         | 13        | 2.68%   |
| Broadwell        | 13        | 2.68%   |
| Zen+             | 12        | 2.47%   |
| Core             | 11        | 2.27%   |
| Unknown          | 10        | 2.06%   |
| Nehalem          | 9         | 1.86%   |
| Silvermont       | 7         | 1.44%   |
| Zen              | 5         | 1.03%   |
| Piledriver       | 5         | 1.03%   |
| Zen 3            | 4         | 0.82%   |
| Steamroller      | 3         | 0.62%   |
| K10              | 3         | 0.62%   |
| Goldmont plus    | 3         | 0.62%   |
| Puma             | 2         | 0.41%   |
| K8 Hammer        | 2         | 0.41%   |
| Bonnell          | 2         | 0.41%   |
| Alderlake Hybrid | 2         | 0.41%   |
| Tremont          | 1         | 0.21%   |
| NetBurst         | 1         | 0.21%   |
| Goldmont         | 1         | 0.21%   |
| Bulldozer        | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 336       | 57.63%  |
| Nvidia                     | 181       | 31.05%  |
| AMD                        | 63        | 10.81%  |
| VIA Technologies           | 1         | 0.17%   |
| Matrox Electronics Systems | 1         | 0.17%   |
| ASPEED Technology          | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 29        | 4.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 3.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 3.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 2.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 2.54%   |
| Intel HD Graphics 630                                                                    | 14        | 2.37%   |
| Intel HD Graphics 530                                                                    | 14        | 2.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 1.69%   |
| Intel HD Graphics 5500                                                                   | 10        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.35%   |
| Intel Iris Plus Graphics G7                                                              | 8         | 1.35%   |
| Intel HD Graphics 620                                                                    | 8         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 1.18%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.85%   |
| Nvidia GP107GL [Quadro P400]                                                             | 5         | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 5         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.85%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 5         | 0.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 0.85%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4         | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.68%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 4         | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.51%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.51%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3         | 0.51%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.51%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.51%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 3         | 0.51%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.51%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.51%   |
| AMD Renoir                                                                               | 3         | 0.51%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.51%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.51%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 3         | 0.51%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.51%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 0.34%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2         | 0.34%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2         | 0.34%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 244       | 50.21%  |
| 1 x Nvidia     | 99        | 20.37%  |
| Intel + Nvidia | 74        | 15.23%  |
| 1 x AMD        | 45        | 9.26%   |
| Intel + AMD    | 10        | 2.06%   |
| AMD + Nvidia   | 6         | 1.23%   |
| Other          | 3         | 0.62%   |
| 2 x AMD        | 2         | 0.41%   |
| 1 x VIA        | 1         | 0.21%   |
| 1 x Matrox     | 1         | 0.21%   |
| 1 x ASPEED     | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 368       | 74.49%  |
| Proprietary | 103       | 20.85%  |
| Unknown     | 23        | 4.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 292       | 58.87%  |
| 1.01-2.0   | 66        | 13.31%  |
| 3.01-4.0   | 46        | 9.27%   |
| 0.51-1.0   | 29        | 5.85%   |
| 0.01-0.5   | 24        | 4.84%   |
| 7.01-8.0   | 21        | 4.23%   |
| 5.01-6.0   | 10        | 2.02%   |
| 2.01-3.0   | 3         | 0.6%    |
| 8.01-16.0  | 3         | 0.6%    |
| 24.01-32.0 | 1         | 0.2%    |
| 16.01-24.0 | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 90        | 16.89%  |
| AU Optronics            | 63        | 11.82%  |
| Dell                    | 61        | 11.44%  |
| Chimei Innolux          | 41        | 7.69%   |
| LG Display              | 40        | 7.5%    |
| BOE                     | 34        | 6.38%   |
| Philips                 | 23        | 4.32%   |
| Goldstar                | 23        | 4.32%   |
| Lenovo                  | 17        | 3.19%   |
| AOC                     | 13        | 2.44%   |
| Hewlett-Packard         | 12        | 2.25%   |
| Sharp                   | 9         | 1.69%   |
| Ancor Communications    | 9         | 1.69%   |
| ViewSonic               | 7         | 1.31%   |
| ASUSTek Computer        | 7         | 1.31%   |
| InfoVision              | 6         | 1.13%   |
| Unknown                 | 5         | 0.94%   |
| LG Philips              | 5         | 0.94%   |
| Chi Mei Optoelectronics | 5         | 0.94%   |
| BenQ                    | 4         | 0.75%   |
| Apple                   | 4         | 0.75%   |
| Sanyo                   | 3         | 0.56%   |
| Panasonic               | 3         | 0.56%   |
| LG Electronics          | 3         | 0.56%   |
| Lenovo Group Limited    | 3         | 0.56%   |
| Acer                    | 3         | 0.56%   |
| Unknown                 | 3         | 0.56%   |
| Toshiba                 | 2         | 0.38%   |
| Sony                    | 2         | 0.38%   |
| NEX                     | 2         | 0.38%   |
| HKC                     | 2         | 0.38%   |
| Eizo                    | 2         | 0.38%   |
| AUS                     | 2         | 0.38%   |
| ___                     | 1         | 0.19%   |
| VOR                     | 1         | 0.19%   |
| VIE                     | 1         | 0.19%   |
| Unknown (AAA)           | 1         | 0.19%   |
| STD                     | 1         | 0.19%   |
| SSD                     | 1         | 0.19%   |
| Seiko/Epson             | 1         | 0.19%   |
| Sceptre Tech            | 1         | 0.19%   |
| RIS                     | 1         | 0.19%   |
| Plain Tree Systems      | 1         | 0.19%   |
| Pioneer                 | 1         | 0.19%   |
| PANDA                   | 1         | 0.19%   |
| NXG                     | 1         | 0.19%   |
| MStar                   | 1         | 0.19%   |
| LGD                     | 1         | 0.19%   |
| JRY                     | 1         | 0.19%   |
| Iiyama                  | 1         | 0.19%   |
| Hitachi                 | 1         | 0.19%   |
| HannStar Display        | 1         | 0.19%   |
| Fujitsu Siemens         | 1         | 0.19%   |
| CVT                     | 1         | 0.19%   |
| CSO                     | 1         | 0.19%   |
| CPT                     | 1         | 0.19%   |
| BOE Technology Group    | 1         | 0.19%   |
| AGO                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 7         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 1.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 1.08%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                  | 4         | 0.72%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 4         | 0.72%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                  | 4         | 0.72%   |
| Philips LCD Monitor PHLC052 1920x1080 480x270mm 21.7-inch                | 4         | 0.72%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 4         | 0.72%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 4         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.72%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch     | 3         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.54%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch      | 3         | 0.54%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.54%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.54%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                         | 3         | 0.54%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch           | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch           | 3         | 0.54%   |
| Unknown                                                                  | 3         | 0.54%   |
| Sanyo LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch                  | 2         | 0.36%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch     | 2         | 0.36%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch     | 2         | 0.36%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 2         | 0.36%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch        | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                       | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 2         | 0.36%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch       | 2         | 0.36%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch        | 2         | 0.36%   |
| Panasonic TV MEIA296 1360x768                                            | 2         | 0.36%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.36%   |
| Lenovo Group Limited LCD Monitor L24q-10                                 | 2         | 0.36%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch              | 2         | 0.36%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch               | 2         | 0.36%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                     | 2         | 0.36%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                        | 2         | 0.36%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                        | 2         | 0.36%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.36%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 2         | 0.36%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 2         | 0.36%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                        | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.36%   |
| BOE LCD Monitor BOE07BC 1920x1080 309x173mm 13.9-inch                    | 2         | 0.36%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.36%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO633D 1920x1080 309x174mm 14.0-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO453D 1920x1080 309x174mm 14.0-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x173mm 13.9-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 270       | 53.78%  |
| 1366x768 (WXGA)    | 63        | 12.55%  |
| 3840x2160 (4K)     | 37        | 7.37%   |
| 2560x1440 (QHD)    | 19        | 3.78%   |
| 1680x1050 (WSXGA+) | 17        | 3.39%   |
| 1920x1200 (WUXGA)  | 14        | 2.79%   |
| 1280x1024 (SXGA)   | 13        | 2.59%   |
| Unknown            | 11        | 2.19%   |
| 1600x900 (HD+)     | 9         | 1.79%   |
| 1280x800 (WXGA)    | 9         | 1.79%   |
| 1440x900 (WXGA+)   | 8         | 1.59%   |
| 3440x1440          | 4         | 0.8%    |
| 2560x1080          | 4         | 0.8%    |
| 3840x1080          | 3         | 0.6%    |
| 1024x768 (XGA)     | 3         | 0.6%    |
| 3200x1800 (QHD+)   | 2         | 0.4%    |
| 2560x1600          | 2         | 0.4%    |
| 1920x540           | 2         | 0.4%    |
| 1280x768           | 2         | 0.4%    |
| 5360x1440          | 1         | 0.2%    |
| 5120x1440          | 1         | 0.2%    |
| 4480x1440          | 1         | 0.2%    |
| 3520x1080          | 1         | 0.2%    |
| 3456x2160          | 1         | 0.2%    |
| 3200x1200          | 1         | 0.2%    |
| 2880x1800          | 1         | 0.2%    |
| 2304x1024          | 1         | 0.2%    |
| 2160x1440          | 1         | 0.2%    |
| 1360x768           | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 116       | 22.05%  |
| 13      | 62        | 11.79%  |
| 24      | 56        | 10.65%  |
| 21      | 51        | 9.7%    |
| 27      | 39        | 7.41%   |
| 23      | 39        | 7.41%   |
| 14      | 38        | 7.22%   |
| Unknown | 32        | 6.08%   |
| 22      | 16        | 3.04%   |
| 17      | 15        | 2.85%   |
| 19      | 8         | 1.52%   |
| 31      | 6         | 1.14%   |
| 12      | 6         | 1.14%   |
| 34      | 5         | 0.95%   |
| 20      | 5         | 0.95%   |
| 84      | 4         | 0.76%   |
| 72      | 4         | 0.76%   |
| 18      | 3         | 0.57%   |
| 54      | 2         | 0.38%   |
| 33      | 2         | 0.38%   |
| 32      | 2         | 0.38%   |
| 25      | 2         | 0.38%   |
| 11      | 2         | 0.38%   |
| 65      | 1         | 0.19%   |
| 60      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 49      | 1         | 0.19%   |
| 48      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |
| 42      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |
| 16      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 188       | 36.29%  |
| 501-600     | 127       | 24.52%  |
| 401-500     | 75        | 14.48%  |
| 201-300     | 41        | 7.92%   |
| Unknown     | 32        | 6.18%   |
| 351-400     | 16        | 3.09%   |
| 601-700     | 11        | 2.12%   |
| 701-800     | 9         | 1.74%   |
| 1501-2000   | 8         | 1.54%   |
| 1001-1500   | 7         | 1.35%   |
| 901-1000    | 2         | 0.39%   |
| 801-900     | 1         | 0.19%   |
| 101-200     | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 359       | 76.22%  |
| 16/10   | 58        | 12.31%  |
| Unknown | 31        | 6.58%   |
| 5/4     | 9         | 1.91%   |
| 4/3     | 6         | 1.27%   |
| 21/9    | 5         | 1.06%   |
| 3/2     | 2         | 0.42%   |
| 1.96    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 126       | 24.23%  |
| 101-110        | 116       | 22.31%  |
| 81-90          | 69        | 13.27%  |
| 301-350        | 39        | 7.5%    |
| Unknown        | 32        | 6.15%   |
| 71-80          | 30        | 5.77%   |
| 151-200        | 27        | 5.19%   |
| 251-300        | 21        | 4.04%   |
| 351-500        | 16        | 3.08%   |
| More than 1000 | 14        | 2.69%   |
| 141-150        | 7         | 1.35%   |
| 61-70          | 6         | 1.15%   |
| 121-130        | 6         | 1.15%   |
| 501-1000       | 4         | 0.77%   |
| 131-140        | 3         | 0.58%   |
| 51-60          | 2         | 0.38%   |
| 1-40           | 1         | 0.19%   |
| 91-100         | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 172       | 33.73%  |
| 121-160       | 126       | 24.71%  |
| 101-120       | 126       | 24.71%  |
| Unknown       | 32        | 6.27%   |
| 161-240       | 22        | 4.31%   |
| More than 240 | 20        | 3.92%   |
| 1-50          | 12        | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 377       | 76.47%  |
| 2     | 81        | 16.43%  |
| 0     | 25        | 5.07%   |
| 3     | 8         | 1.62%   |
| 4     | 2         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 263       | 36.28%  |
| Intel                           | 253       | 34.9%   |
| Qualcomm Atheros                | 76        | 10.48%  |
| Broadcom                        | 22        | 3.03%   |
| Ralink Technology               | 13        | 1.79%   |
| Broadcom Limited                | 10        | 1.38%   |
| TP-Link                         | 9         | 1.24%   |
| Lenovo                          | 8         | 1.1%    |
| Edimax Technology               | 8         | 1.1%    |
| Nvidia                          | 5         | 0.69%   |
| Marvell Technology Group        | 5         | 0.69%   |
| ASIX Electronics                | 5         | 0.69%   |
| Xiaomi                          | 4         | 0.55%   |
| Qualcomm Atheros Communications | 4         | 0.55%   |
| MEDIATEK                        | 4         | 0.55%   |
| Ralink                          | 3         | 0.41%   |
| DisplayLink                     | 3         | 0.41%   |
| Texas Instruments               | 2         | 0.28%   |
| Samsung Electronics             | 2         | 0.28%   |
| Huawei Technologies             | 2         | 0.28%   |
| D-Link                          | 2         | 0.28%   |
| U.S. Robotics                   | 1         | 0.14%   |
| Toshiba                         | 1         | 0.14%   |
| STMicroelectronics              | 1         | 0.14%   |
| ROCCAT                          | 1         | 0.14%   |
| PEAK-System Technik             | 1         | 0.14%   |
| Nokia Mobile Phones             | 1         | 0.14%   |
| Microsoft                       | 1         | 0.14%   |
| Mellanox Technologies           | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| LG Electronics                  | 1         | 0.14%   |
| HMD Global                      | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |
| Google                          | 1         | 0.14%   |
| GDMicroelectronics              | 1         | 0.14%   |
| Dell                            | 1         | 0.14%   |
| Davicom Semiconductor           | 1         | 0.14%   |
| Comneon                         | 1         | 0.14%   |
| BUFFALO                         | 1         | 0.14%   |
| Attansic Technology             | 1         | 0.14%   |
| ASUSTek Computer                | 1         | 0.14%   |
| Aquantia                        | 1         | 0.14%   |
| Accton Technology               | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 187       | 22.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 30        | 3.55%   |
| Intel Wireless 8265 / 8275                                              | 22        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 19        | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 2.01%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.78%   |
| Intel Ethernet Connection (2) I219-V                                    | 14        | 1.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.42%   |
| Intel I211 Gigabit Network Connection                                   | 12        | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                       | 11        | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.18%   |
| Intel Wireless 3165                                                     | 10        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.07%   |
| Intel Wireless 8260                                                     | 9         | 1.07%   |
| Intel Ethernet Connection (6) I219-V                                    | 9         | 1.07%   |
| Intel Ethernet Connection (7) I219-V                                    | 8         | 0.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 7         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.71%   |
| Intel Wireless 3160                                                     | 6         | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.71%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.59%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.59%   |
| Intel Wireless 7265                                                     | 5         | 0.59%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.47%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 4         | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                                   | 4         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                   | 4         | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                   | 4         | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.47%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 3         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.36%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 3         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.36%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 3         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 175       | 48.61%  |
| Qualcomm Atheros                | 60        | 16.67%  |
| Realtek Semiconductor           | 51        | 14.17%  |
| Broadcom                        | 21        | 5.83%   |
| Ralink Technology               | 13        | 3.61%   |
| TP-Link                         | 8         | 2.22%   |
| Edimax Technology               | 8         | 2.22%   |
| Broadcom Limited                | 6         | 1.67%   |
| Qualcomm Atheros Communications | 4         | 1.11%   |
| MEDIATEK                        | 4         | 1.11%   |
| Ralink                          | 3         | 0.83%   |
| D-Link                          | 2         | 0.56%   |
| Microsoft                       | 1         | 0.28%   |
| Marvell Technology Group        | 1         | 0.28%   |
| Dell                            | 1         | 0.28%   |
| BUFFALO                         | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 22        | 6.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 4.7%    |
| Intel Wi-Fi 6 AX200                                                     | 16        | 4.42%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 4.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 3.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 3.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 2.76%   |
| Intel Wireless 3165                                                     | 10        | 2.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.49%   |
| Intel Wireless 8260                                                     | 9         | 2.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 7         | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 1.66%   |
| Intel Wireless 3160                                                     | 6         | 1.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.38%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.38%   |
| Intel Wireless 7265                                                     | 5         | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.1%    |
| Realtek 802.11ac NIC                                                    | 4         | 1.1%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4         | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.1%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 3         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.83%   |
| Edimax RTL8192S WLAN Adapter                                            | 3         | 0.83%   |
| Edimax AC600 USB                                                        | 3         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.55%   |
| TP-Link Archer T4U ver.3                                                | 2         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 2         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.55%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.55%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 2         | 0.55%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.55%   |
| Intel Wireless 7260                                                     | 2         | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.55%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.55%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.55%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 2         | 0.55%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.55%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.55%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.55%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 244       | 53.04%  |
| Intel                    | 143       | 31.09%  |
| Qualcomm Atheros         | 21        | 4.57%   |
| Lenovo                   | 8         | 1.74%   |
| Broadcom                 | 6         | 1.3%    |
| Nvidia                   | 5         | 1.09%   |
| Broadcom Limited         | 5         | 1.09%   |
| ASIX Electronics         | 5         | 1.09%   |
| Xiaomi                   | 4         | 0.87%   |
| Marvell Technology Group | 4         | 0.87%   |
| DisplayLink              | 3         | 0.65%   |
| Samsung Electronics      | 2         | 0.43%   |
| TP-Link                  | 1         | 0.22%   |
| Mellanox Technologies    | 1         | 0.22%   |
| Linksys                  | 1         | 0.22%   |
| Huawei Technologies      | 1         | 0.22%   |
| HMD Global               | 1         | 0.22%   |
| Google                   | 1         | 0.22%   |
| Davicom Semiconductor    | 1         | 0.22%   |
| Attansic Technology      | 1         | 0.22%   |
| Aquantia                 | 1         | 0.22%   |
| Accton Technology        | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 187       | 39.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 4.04%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 2.98%   |
| Intel I211 Gigabit Network Connection                             | 12        | 2.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 2.34%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 1.91%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 1.7%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.85%   |
| Intel Ethernet Connection (14) I219-V                             | 4         | 0.85%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.64%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 3         | 0.64%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.64%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 3         | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.64%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.43%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.43%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.43%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.43%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.43%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.21%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.21%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.21%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.21%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.21%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.21%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.21%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.21%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 421       | 54.25%  |
| WiFi     | 342       | 44.07%  |
| Modem    | 11        | 1.42%   |
| Unknown  | 2         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 254       | 50.2%   |
| Ethernet | 251       | 49.6%   |
| Modem    | 1         | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 235       | 48.45%  |
| 2     | 234       | 48.25%  |
| 3     | 11        | 2.27%   |
| 0     | 5         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 433       | 88.01%  |
| Yes  | 59        | 11.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 57.3%   |
| Qualcomm Atheros Communications | 24        | 8.99%   |
| Cambridge Silicon Radio         | 20        | 7.49%   |
| Realtek Semiconductor           | 17        | 6.37%   |
| IMC Networks                    | 12        | 4.49%   |
| Broadcom                        | 9         | 3.37%   |
| Apple                           | 7         | 2.62%   |
| Lite-On Technology              | 5         | 1.87%   |
| Foxconn / Hon Hai               | 5         | 1.87%   |
| ASUSTek Computer                | 4         | 1.5%    |
| Dell                            | 3         | 1.12%   |
| Hewlett-Packard                 | 2         | 0.75%   |
| Askey Computer                  | 2         | 0.75%   |
| Toshiba                         | 1         | 0.37%   |
| Realtek                         | 1         | 0.37%   |
| MediaTek                        | 1         | 0.37%   |
| Marvell Semiconductor           | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 60        | 22.47%  |
| Intel AX201 Bluetooth                               | 34        | 12.73%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 10.49%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 7.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 5.62%   |
| Intel AX200 Bluetooth                               | 14        | 5.24%   |
| Realtek Bluetooth Radio                             | 7         | 2.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.87%   |
| IMC Networks Bluetooth Device                       | 5         | 1.87%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 1.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.5%    |
| Lite-On Bluetooth Device                            | 4         | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.5%    |
| Apple Bluetooth USB Host Controller                 | 4         | 1.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.12%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.75%   |
| Intel AX210 Bluetooth                               | 2         | 0.75%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.75%   |
| Foxconn / Hon Hai BT                                | 2         | 0.75%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.75%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.75%   |
| ASUS Bluetooth Adapter                              | 2         | 0.75%   |
| Askey Bluetooth Device                              | 2         | 0.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.75%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.37%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.37%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.37%   |
| Realtek Bluetooth Radio                             | 1         | 0.37%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.37%   |
| MediaTek BT                                         | 1         | 0.37%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.37%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.37%   |
| Intel Bluetooth Device                              | 1         | 0.37%   |
| IMC Networks Wireless_Device                        | 1         | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.37%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.37%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 0.37%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.37%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.37%   |
| Broadcom BCM20702A0                                 | 1         | 0.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.37%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.37%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.37%   |
| Broadcom BCM2045A0                                  | 1         | 0.37%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 0.37%   |
| ASUS BCM20702A0                                     | 1         | 0.37%   |
| Apple Bluetooth Host Controller                     | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 415       | 62.22%  |
| Nvidia                     | 132       | 19.79%  |
| AMD                        | 66        | 9.9%    |
| Lenovo                     | 8         | 1.2%    |
| C-Media Electronics        | 8         | 1.2%    |
| Creative Labs              | 5         | 0.75%   |
| XMOS                       | 4         | 0.6%    |
| Creative Technology        | 4         | 0.6%    |
| Realtek Semiconductor      | 3         | 0.45%   |
| Microsoft                  | 3         | 0.45%   |
| GN Netcom                  | 3         | 0.45%   |
| Focusrite-Novation         | 3         | 0.45%   |
| VIA Technologies           | 2         | 0.3%    |
| Logitech                   | 2         | 0.3%    |
| Texas Instruments          | 1         | 0.15%   |
| Sennheiser Communications  | 1         | 0.15%   |
| Razer USA                  | 1         | 0.15%   |
| PreSonus Audio Electronics | 1         | 0.15%   |
| Meridian                   | 1         | 0.15%   |
| Kingston Technology        | 1         | 0.15%   |
| JMTek                      | 1         | 0.15%   |
| iCreate Technologies       | 1         | 0.15%   |
| EGO SYStems                | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 56        | 7.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 34        | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 26        | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24        | 3.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 3.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24        | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22        | 2.95%   |
| Intel 200 Series PCH HD Audio                                              | 21        | 2.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 2.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 2.28%   |
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 2.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 16        | 2.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 15        | 2.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 1.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 13        | 1.74%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 1.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 11        | 1.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 1.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.34%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.2%    |
| Nvidia High Definition Audio Controller                                    | 8         | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 8         | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 1.07%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.07%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 0.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7         | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 0.8%    |
| Nvidia TU104 HD Audio Controller                                           | 6         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                | 6         | 0.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 5         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5         | 0.67%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 0.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 4         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.54%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.54%   |
| AMD Trinity HDMI Audio Controller                                          | 4         | 0.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.54%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4         | 0.54%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 0.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.54%   |
| Realtek Semiconductor USB Audio                                            | 3         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                         | 3         | 0.4%    |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.4%    |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.4%    |
| Microsoft LifeChat LX-3000 Headset                                         | 3         | 0.4%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 3         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 58        | 19.66%  |
| SK Hynix            | 48        | 16.27%  |
| Kingston            | 40        | 13.56%  |
| Micron Technology   | 35        | 11.86%  |
| Unknown             | 33        | 11.19%  |
| Crucial             | 21        | 7.12%   |
| Corsair             | 15        | 5.08%   |
| G.Skill             | 14        | 4.75%   |
| Ramaxel Technology  | 7         | 2.37%   |
| Transcend           | 5         | 1.69%   |
| Team                | 3         | 1.02%   |
| Nanya Technology    | 3         | 1.02%   |
| Elpida              | 3         | 1.02%   |
| GeIL                | 2         | 0.68%   |
| A-DATA Technology   | 2         | 0.68%   |
| V-Color             | 1         | 0.34%   |
| Unknown (09D5)      | 1         | 0.34%   |
| Patriot             | 1         | 0.34%   |
| KETECH              | 1         | 0.34%   |
| Avant               | 1         | 0.34%   |
| 48spaces            | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s      | 3         | 0.96%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.96%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 0.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.96%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.96%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.96%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 3         | 0.96%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 2         | 0.64%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2         | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 2         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 2         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 2         | 0.64%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s             | 2         | 0.64%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.64%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.64%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 2         | 0.64%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 2         | 0.64%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.64%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 0.64%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 0.64%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 0.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 0.64%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s          | 2         | 0.64%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 0.64%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s       | 2         | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.64%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s  | 2         | 0.64%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s       | 2         | 0.64%   |
| Kingston RAM KHX2400C15D4/4G 4096MB DIMM DDR4 3151MT/s       | 2         | 0.64%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s         | 2         | 0.64%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s        | 2         | 0.64%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s        | 2         | 0.64%   |
| Kingston RAM 9905711-035.A00G 8GB SODIMM DDR4 3200MT/s       | 2         | 0.64%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s         | 2         | 0.64%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s           | 2         | 0.64%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s      | 2         | 0.64%   |
| Crucial RAM CT16G4DFD832A.C16FP 16384MB DIMM DDR4 3200MT/s   | 2         | 0.64%   |
| V-Color RAM TF416G26D819 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.32%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.32%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s               | 1         | 0.32%   |
| Unknown RAM Module 8192MB DIMM 800MT/s                       | 1         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.32%   |
| Unknown RAM Module 4GB DIMM 667MT/s                          | 1         | 0.32%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1         | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1         | 0.32%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 1         | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                    | 1         | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                     | 1         | 0.32%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                     | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 147       | 57.87%  |
| DDR3    | 59        | 23.23%  |
| DDR2    | 15        | 5.91%   |
| Unknown | 14        | 5.51%   |
| LPDDR3  | 9         | 3.54%   |
| SDRAM   | 4         | 1.57%   |
| LPDDR4  | 3         | 1.18%   |
| DDR     | 3         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 127       | 49.8%   |
| DIMM         | 111       | 43.53%  |
| Row Of Chips | 16        | 6.27%   |
| Chip         | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 89        | 32.6%   |
| 4096  | 69        | 25.27%  |
| 16384 | 58        | 21.25%  |
| 2048  | 37        | 13.55%  |
| 1024  | 11        | 4.03%   |
| 32768 | 9         | 3.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 51        | 18.41%  |
| 1600    | 44        | 15.88%  |
| 3200    | 42        | 15.16%  |
| 2133    | 25        | 9.03%   |
| 2400    | 24        | 8.66%   |
| 800     | 13        | 4.69%   |
| 1333    | 11        | 3.97%   |
| 667     | 9         | 3.25%   |
| 3600    | 6         | 2.17%   |
| Unknown | 6         | 2.17%   |
| 1867    | 5         | 1.81%   |
| 1334    | 5         | 1.81%   |
| 4267    | 3         | 1.08%   |
| 3466    | 3         | 1.08%   |
| 3266    | 3         | 1.08%   |
| 2933    | 3         | 1.08%   |
| 3151    | 2         | 0.72%   |
| 2000    | 2         | 0.72%   |
| 1866    | 2         | 0.72%   |
| 1400    | 2         | 0.72%   |
| 1067    | 2         | 0.72%   |
| 49926   | 1         | 0.36%   |
| 4800    | 1         | 0.36%   |
| 4400    | 1         | 0.36%   |
| 3800    | 1         | 0.36%   |
| 3733    | 1         | 0.36%   |
| 3400    | 1         | 0.36%   |
| 3066    | 1         | 0.36%   |
| 3000    | 1         | 0.36%   |
| 2800    | 1         | 0.36%   |
| 2134    | 1         | 0.36%   |
| 1800    | 1         | 0.36%   |
| 1066    | 1         | 0.36%   |
| 533     | 1         | 0.36%   |
| 400     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 40%     |
| Samsung Electronics   | 3         | 20%     |
| Canon                 | 2         | 13.33%  |
| Brother Industries    | 2         | 13.33%  |
| Lexmark International | 1         | 6.67%   |
| GODEX INTERNATIONAL   | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung M2070 Series          | 2         | 13.33%  |
| HP Officejet 4500 G510g-m     | 2         | 13.33%  |
| Samsung M288x Series          | 1         | 6.67%   |
| Lexmark International CS417dn | 1         | 6.67%   |
| HP Printing Support           | 1         | 6.67%   |
| HP LaserJet M14-M17           | 1         | 6.67%   |
| HP DeskJet 4670 series        | 1         | 6.67%   |
| HP Deskjet 4640 series        | 1         | 6.67%   |
| GODEX INTERNATIONAL DT2       | 1         | 6.67%   |
| Canon TR7500 series           | 1         | 6.67%   |
| Canon PIXMA MX490 Series      | 1         | 6.67%   |
| Brother Printer               | 1         | 6.67%   |
| Brother MFC-J497DW            | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 2         | 66.67%  |
| Canon CanoScan LiDE 220 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 44        | 15.17%  |
| Chicony Electronics                    | 43        | 14.83%  |
| Realtek Semiconductor                  | 38        | 13.1%   |
| Logitech                               | 22        | 7.59%   |
| Acer                                   | 22        | 7.59%   |
| Microsoft                              | 19        | 6.55%   |
| Sunplus Innovation Technology          | 18        | 6.21%   |
| Microdia                               | 15        | 5.17%   |
| Apple                                  | 10        | 3.45%   |
| Suyin                                  | 6         | 2.07%   |
| Quanta                                 | 6         | 2.07%   |
| Lite-On Technology                     | 6         | 2.07%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.07%   |
| Syntek                                 | 5         | 1.72%   |
| Samsung Electronics                    | 5         | 1.72%   |
| Generalplus Technology                 | 5         | 1.72%   |
| Silicon Motion                         | 4         | 1.38%   |
| Jieli Technology                       | 2         | 0.69%   |
| ALi                                    | 2         | 0.69%   |
| Alcor Micro                            | 2         | 0.69%   |
| Z-Star Microelectronics                | 1         | 0.34%   |
| Yealink Network Technology             | 1         | 0.34%   |
| Xiaomi                                 | 1         | 0.34%   |
| Primax Electronics                     | 1         | 0.34%   |
| Luxvisions Innotech Limited            | 1         | 0.34%   |
| Lenovo                                 | 1         | 0.34%   |
| Hewlett-Packard                        | 1         | 0.34%   |
| eMPIA Technology                       | 1         | 0.34%   |
| Cubeternet                             | 1         | 0.34%   |
| Aveo Technology                        | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 19        | 6.55%   |
| Microsoft LifeCam HD-3000                | 13        | 4.48%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 12        | 4.14%   |
| Chicony Integrated Camera                | 12        | 4.14%   |
| IMC Networks Integrated Camera           | 11        | 3.79%   |
| IMC Networks USB2.0 HD UVC WebCam        | 10        | 3.45%   |
| Acer Integrated Camera                   | 8         | 2.76%   |
| Microdia Integrated_Webcam_HD            | 6         | 2.07%   |
| Samsung Galaxy A5 (MTP)                  | 5         | 1.72%   |
| Logitech Webcam C270                     | 5         | 1.72%   |
| Apple iPhone 5/5C/5S/6/SE                | 5         | 1.72%   |
| Acer Lenovo EasyCamera                   | 5         | 1.72%   |
| Syntek Integrated Camera                 | 4         | 1.38%   |
| Generalplus CAMERA - UVC                 | 4         | 1.38%   |
| Chicony HP HD Camera                     | 4         | 1.38%   |
| Sunplus Integrated_Webcam_HD             | 3         | 1.03%   |
| Sunplus HK 1080P K20Pro                  | 3         | 1.03%   |
| Realtek Integrated Webcam HD             | 3         | 1.03%   |
| IMC Networks USB2.0 UVC HD Webcam        | 3         | 1.03%   |
| Chicony Lenovo EasyCamera                | 3         | 1.03%   |
| Chicony Integrated Camera (1280x720@30)  | 3         | 1.03%   |
| Chicony EasyCamera                       | 3         | 1.03%   |
| Acer SunplusIT Integrated Camera         | 3         | 1.03%   |
| Realtek USB2.0 HD UVC WebCam             | 2         | 0.69%   |
| Realtek USB Camera                       | 2         | 0.69%   |
| Realtek Lenovo EasyCamera                | 2         | 0.69%   |
| Realtek HP Wide Vision HD Camera         | 2         | 0.69%   |
| Quanta USB Webcam                        | 2         | 0.69%   |
| Microsoft LifeCam NX-6000                | 2         | 0.69%   |
| Microdia Integrated Webcam               | 2         | 0.69%   |
| Microdia Dell Integrated HD Webcam       | 2         | 0.69%   |
| Logitech Webcam C925e                    | 2         | 0.69%   |
| Logitech Webcam C310                     | 2         | 0.69%   |
| Logitech C922 Pro Stream Webcam          | 2         | 0.69%   |
| Logitech BRIO Ultra HD Webcam            | 2         | 0.69%   |
| Lite-On Integrated Camera                | 2         | 0.69%   |
| Lite-On HP HD Camera                     | 2         | 0.69%   |
| Jieli USB PHY 2.0                        | 2         | 0.69%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 2         | 0.69%   |
| IMC Networks Lenovo EasyCamera           | 2         | 0.69%   |
| Chicony HP Webcam                        | 2         | 0.69%   |
| ALi Gateway Webcam                       | 2         | 0.69%   |
| Acer BisonCam, NB Pro                    | 2         | 0.69%   |
| Z-Star WebCam SC-03FFL11739P             | 1         | 0.34%   |
| Yealink Network UVC30                    | 1         | 0.34%   |
| Xiaomi Mi/Redmi series (PTP + ADB)       | 1         | 0.34%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.34%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.34%   |
| Suyin HP webcam [dv6-1190en]             | 1         | 0.34%   |
| Suyin HP Truevision HD                   | 1         | 0.34%   |
| Suyin Asus Integrated Webcam [CN031B]    | 1         | 0.34%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.34%   |
| Suyin Acer CrystalEye Webcam             | 1         | 0.34%   |
| Sunplus Lenovo EasyCamera                | 1         | 0.34%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 0.34%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.34%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 0.34%   |
| Sunplus Integrated_Webcam_FHD            | 1         | 0.34%   |
| Sunplus Integrated Camera                | 1         | 0.34%   |
| Sunplus HD WebCam                        | 1         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 21        | 40.38%  |
| Validity Sensors           | 16        | 30.77%  |
| Shenzhen Goodix Technology | 7         | 13.46%  |
| STMicroelectronics         | 2         | 3.85%   |
| Elan Microelectronics      | 2         | 3.85%   |
| AuthenTec                  | 2         | 3.85%   |
| Upek                       | 1         | 1.92%   |
| LighTuning Technology      | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 15.38%  |
| Unknown                                                                    | 5         | 9.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.77%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 5.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.85%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.85%   |
| Synaptics  WBDI                                                            | 2         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.85%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.85%   |
| Validity Sensors VFS491                                                    | 1         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.92%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 67.74%  |
| Alcor Micro | 10        | 32.26%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 32.26%  |
| Broadcom 58200                                                               | 8         | 25.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 19.35%  |
| Broadcom 5880                                                                | 6         | 19.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 347       | 69.96%  |
| 1     | 116       | 23.39%  |
| 2     | 26        | 5.24%   |
| 3     | 5         | 1.01%   |
| 7     | 1         | 0.2%    |
| 4     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 26.98%  |
| Graphics card            | 49        | 25.93%  |
| Net/wireless             | 30        | 15.87%  |
| Chipcard                 | 28        | 14.81%  |
| Communication controller | 7         | 3.7%    |
| Multimedia controller    | 6         | 3.17%   |
| Camera                   | 6         | 3.17%   |
| Unassigned class         | 3         | 1.59%   |
| Sound                    | 2         | 1.06%   |
| Card reader              | 2         | 1.06%   |
| Bluetooth                | 2         | 1.06%   |
| Storage                  | 1         | 0.53%   |
| Network                  | 1         | 0.53%   |
| Net/ethernet             | 1         | 0.53%   |

