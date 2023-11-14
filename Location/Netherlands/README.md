Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 6373

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | MS-7708                     | Desktop     | [9170f4dd42](https://linux-hardware.org/?probe=9170f4dd42) | Nov 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [b42102e397](https://linux-hardware.org/?probe=b42102e397) | Nov 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [17dda27251](https://linux-hardware.org/?probe=17dda27251) | Nov 06, 2023 |
| Dell          | Latitude 5590               | Notebook    | [913308d97b](https://linux-hardware.org/?probe=913308d97b) | Nov 05, 2023 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [27923cd021](https://linux-hardware.org/?probe=27923cd021) | Nov 05, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [1c86a5a6de](https://linux-hardware.org/?probe=1c86a5a6de) | Nov 05, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4601ae11d9](https://linux-hardware.org/?probe=4601ae11d9) | Nov 05, 2023 |
| HP            | Compaq 6710b                | Notebook    | [7a0b2fd29b](https://linux-hardware.org/?probe=7a0b2fd29b) | Nov 05, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [45e65903ff](https://linux-hardware.org/?probe=45e65903ff) | Nov 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [a8bb556bfe](https://linux-hardware.org/?probe=a8bb556bfe) | Nov 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [03f4055831](https://linux-hardware.org/?probe=03f4055831) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [aba7da7a37](https://linux-hardware.org/?probe=aba7da7a37) | Nov 04, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ea9a865ed2](https://linux-hardware.org/?probe=ea9a865ed2) | Nov 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [1f2c5ea57b](https://linux-hardware.org/?probe=1f2c5ea57b) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a0c7507d6d](https://linux-hardware.org/?probe=a0c7507d6d) | Nov 03, 2023 |
| Medion        | ERAZER X7855 MD60892        | Notebook    | [b34c69b29d](https://linux-hardware.org/?probe=b34c69b29d) | Nov 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [49ec48adb9](https://linux-hardware.org/?probe=49ec48adb9) | Nov 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3c4533c5a9](https://linux-hardware.org/?probe=3c4533c5a9) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| Lenovo        | 31A7 SDK0K17763 WIN 1801... | Mini pc     | [4291eb9ffb](https://linux-hardware.org/?probe=4291eb9ffb) | Nov 02, 2023 |
| Lenovo        | 31A7 SDK0K17763 WIN 1801... | Mini pc     | [b616f22a15](https://linux-hardware.org/?probe=b616f22a15) | Nov 02, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5c4a8fa3ed](https://linux-hardware.org/?probe=5c4a8fa3ed) | Nov 02, 2023 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [849d24e533](https://linux-hardware.org/?probe=849d24e533) | Nov 02, 2023 |
| HP            | 8924 0101                   | All in one  | [2a4ccfce66](https://linux-hardware.org/?probe=2a4ccfce66) | Nov 02, 2023 |
| MSI           | Titan GT77HX 13VI           | Notebook    | [1fb8b0ccb3](https://linux-hardware.org/?probe=1fb8b0ccb3) | Nov 01, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [9893d57e1b](https://linux-hardware.org/?probe=9893d57e1b) | Nov 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [317aadad91](https://linux-hardware.org/?probe=317aadad91) | Nov 01, 2023 |
| HP            | EliteBook 8470w             | Notebook    | [d4b6365e3f](https://linux-hardware.org/?probe=d4b6365e3f) | Nov 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6af2aaed4e](https://linux-hardware.org/?probe=6af2aaed4e) | Nov 01, 2023 |
| Medion        | MS-7800                     | Desktop     | [8ebfbd5941](https://linux-hardware.org/?probe=8ebfbd5941) | Nov 01, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [2abdc4603a](https://linux-hardware.org/?probe=2abdc4603a) | Nov 01, 2023 |
| Lenovo        | 31A7 SDK0K17763 WIN 1801... | Mini pc     | [cba0718bc1](https://linux-hardware.org/?probe=cba0718bc1) | Oct 31, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aef5a9f17c](https://linux-hardware.org/?probe=aef5a9f17c) | Oct 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [53e53337bb](https://linux-hardware.org/?probe=53e53337bb) | Oct 30, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [48f8f53d3e](https://linux-hardware.org/?probe=48f8f53d3e) | Oct 30, 2023 |
| Dell          | Latitude 7430               | Notebook    | [b72f3f4264](https://linux-hardware.org/?probe=b72f3f4264) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [1267d6df00](https://linux-hardware.org/?probe=1267d6df00) | Oct 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H10... | Notebook    | [0a7d468516](https://linux-hardware.org/?probe=0a7d468516) | Oct 29, 2023 |
| HP            | 1998                        | Desktop     | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [af4673599a](https://linux-hardware.org/?probe=af4673599a) | Oct 29, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [751a447386](https://linux-hardware.org/?probe=751a447386) | Oct 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [91f7b242b9](https://linux-hardware.org/?probe=91f7b242b9) | Oct 28, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [aaf303e411](https://linux-hardware.org/?probe=aaf303e411) | Oct 28, 2023 |
| Intel         | NUC12WSBi3 M36953-304       | Mini pc     | [c976a3e607](https://linux-hardware.org/?probe=c976a3e607) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9a6fdf5543](https://linux-hardware.org/?probe=9a6fdf5543) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [85b2c39c93](https://linux-hardware.org/?probe=85b2c39c93) | Oct 28, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [8b0a272a4e](https://linux-hardware.org/?probe=8b0a272a4e) | Oct 28, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [291bf42f9d](https://linux-hardware.org/?probe=291bf42f9d) | Oct 27, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [39e2fb6be6](https://linux-hardware.org/?probe=39e2fb6be6) | Oct 27, 2023 |
| Dell          | Latitude 5440               | Notebook    | [e7d56ee207](https://linux-hardware.org/?probe=e7d56ee207) | Oct 26, 2023 |
| Dell          | Latitude 7490               | Notebook    | [58324a8dfd](https://linux-hardware.org/?probe=58324a8dfd) | Oct 26, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [d7ffb73521](https://linux-hardware.org/?probe=d7ffb73521) | Oct 26, 2023 |
| ASUSTek       | P5E-VM HDMI                 | Desktop     | [4491bc9ec0](https://linux-hardware.org/?probe=4491bc9ec0) | Oct 26, 2023 |
| Acer          | Aspire SW5-171              | Notebook    | [3b2a04a910](https://linux-hardware.org/?probe=3b2a04a910) | Oct 26, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3a1039b4b6](https://linux-hardware.org/?probe=3a1039b4b6) | Oct 26, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [da8b82a004](https://linux-hardware.org/?probe=da8b82a004) | Oct 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4b51bd3321](https://linux-hardware.org/?probe=4b51bd3321) | Oct 25, 2023 |
| MSI           | 2A9C                        | Desktop     | [d87ee22b95](https://linux-hardware.org/?probe=d87ee22b95) | Oct 24, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [b8ac729343](https://linux-hardware.org/?probe=b8ac729343) | Oct 24, 2023 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [0206625e43](https://linux-hardware.org/?probe=0206625e43) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | Desktop     | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [f1e5521102](https://linux-hardware.org/?probe=f1e5521102) | Oct 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [d71e04d478](https://linux-hardware.org/?probe=d71e04d478) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [c03a4ad29d](https://linux-hardware.org/?probe=c03a4ad29d) | Oct 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [d4d7110981](https://linux-hardware.org/?probe=d4d7110981) | Oct 23, 2023 |
| Medion        | P6613                       | Notebook    | [c36f8ad846](https://linux-hardware.org/?probe=c36f8ad846) | Oct 23, 2023 |
| MSI           | X58 Pro SLI                 | Desktop     | [e127c69a3f](https://linux-hardware.org/?probe=e127c69a3f) | Oct 23, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [f48b2b4e3c](https://linux-hardware.org/?probe=f48b2b4e3c) | Oct 23, 2023 |
| Medion        | P6613                       | Notebook    | [18975f3ee4](https://linux-hardware.org/?probe=18975f3ee4) | Oct 23, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60926fccde](https://linux-hardware.org/?probe=60926fccde) | Oct 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [93043f297f](https://linux-hardware.org/?probe=93043f297f) | Oct 22, 2023 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [817e15f7e6](https://linux-hardware.org/?probe=817e15f7e6) | Oct 22, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [ed30fdba07](https://linux-hardware.org/?probe=ed30fdba07) | Oct 22, 2023 |
| HP            | ProBook 6550b               | Notebook    | [da6e693794](https://linux-hardware.org/?probe=da6e693794) | Oct 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [d38a6fb326](https://linux-hardware.org/?probe=d38a6fb326) | Oct 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ec48996f11](https://linux-hardware.org/?probe=ec48996f11) | Oct 21, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [dcef0a70af](https://linux-hardware.org/?probe=dcef0a70af) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [a149fbf417](https://linux-hardware.org/?probe=a149fbf417) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [f4f7d19069](https://linux-hardware.org/?probe=f4f7d19069) | Oct 20, 2023 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [53a5331f12](https://linux-hardware.org/?probe=53a5331f12) | Oct 20, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [5cea3b7124](https://linux-hardware.org/?probe=5cea3b7124) | Oct 18, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [0df63f5012](https://linux-hardware.org/?probe=0df63f5012) | Oct 17, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [0bb3061070](https://linux-hardware.org/?probe=0bb3061070) | Oct 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [96f3c530df](https://linux-hardware.org/?probe=96f3c530df) | Oct 17, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [d4a36e5a56](https://linux-hardware.org/?probe=d4a36e5a56) | Oct 17, 2023 |
| Gigabyte      | AORUS 15G XB                | Notebook    | [9e4c6d48d4](https://linux-hardware.org/?probe=9e4c6d48d4) | Oct 16, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [04ff7db18a](https://linux-hardware.org/?probe=04ff7db18a) | Oct 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [07b407d18a](https://linux-hardware.org/?probe=07b407d18a) | Oct 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [37983381b0](https://linux-hardware.org/?probe=37983381b0) | Oct 15, 2023 |
| HP            | 8055                        | Desktop     | [5fe9038a50](https://linux-hardware.org/?probe=5fe9038a50) | Oct 15, 2023 |
| HP            | 8055                        | Desktop     | [8a74853b61](https://linux-hardware.org/?probe=8a74853b61) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8bbdd141fe](https://linux-hardware.org/?probe=8bbdd141fe) | Oct 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c3e8cf453e](https://linux-hardware.org/?probe=c3e8cf453e) | Oct 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [46cc5e4c0a](https://linux-hardware.org/?probe=46cc5e4c0a) | Oct 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [398445f93d](https://linux-hardware.org/?probe=398445f93d) | Oct 14, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [bdd8aeaf43](https://linux-hardware.org/?probe=bdd8aeaf43) | Oct 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [729234c285](https://linux-hardware.org/?probe=729234c285) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [e9bee28805](https://linux-hardware.org/?probe=e9bee28805) | Oct 14, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [ef66b70c6f](https://linux-hardware.org/?probe=ef66b70c6f) | Oct 12, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [ab55bb1001](https://linux-hardware.org/?probe=ab55bb1001) | Oct 12, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [2dbab85ec9](https://linux-hardware.org/?probe=2dbab85ec9) | Oct 12, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [ec7d122a78](https://linux-hardware.org/?probe=ec7d122a78) | Oct 12, 2023 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [e7252be8a1](https://linux-hardware.org/?probe=e7252be8a1) | Oct 12, 2023 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [1328071174](https://linux-hardware.org/?probe=1328071174) | Oct 12, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [f33ca79691](https://linux-hardware.org/?probe=f33ca79691) | Oct 12, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [6edb73b1b7](https://linux-hardware.org/?probe=6edb73b1b7) | Oct 11, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b506ceb439](https://linux-hardware.org/?probe=b506ceb439) | Oct 11, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [5e8749954f](https://linux-hardware.org/?probe=5e8749954f) | Oct 11, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [3df74e5b96](https://linux-hardware.org/?probe=3df74e5b96) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [875dd4eedb](https://linux-hardware.org/?probe=875dd4eedb) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [d9c5086891](https://linux-hardware.org/?probe=d9c5086891) | Oct 09, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [33dc949dff](https://linux-hardware.org/?probe=33dc949dff) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [5cc0f3a697](https://linux-hardware.org/?probe=5cc0f3a697) | Oct 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [b3f3a17f8c](https://linux-hardware.org/?probe=b3f3a17f8c) | Oct 08, 2023 |
| ASUSTek       | G551JW                      | Notebook    | [7f805877ed](https://linux-hardware.org/?probe=7f805877ed) | Oct 08, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [c975944c8e](https://linux-hardware.org/?probe=c975944c8e) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [84ff0a9a08](https://linux-hardware.org/?probe=84ff0a9a08) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1505f63948](https://linux-hardware.org/?probe=1505f63948) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7d321bffa1](https://linux-hardware.org/?probe=7d321bffa1) | Oct 07, 2023 |
| Samsung       | 950QED                      | Convertible | [739568d199](https://linux-hardware.org/?probe=739568d199) | Oct 07, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [00fa623097](https://linux-hardware.org/?probe=00fa623097) | Oct 07, 2023 |
| Unknown       | Unknown                     | Soc         | [d0bfdb9730](https://linux-hardware.org/?probe=d0bfdb9730) | Oct 06, 2023 |
| Unknown       | Unknown                     | Soc         | [bc57962bed](https://linux-hardware.org/?probe=bc57962bed) | Oct 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [1c741fc115](https://linux-hardware.org/?probe=1c741fc115) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16098f839a](https://linux-hardware.org/?probe=16098f839a) | Oct 06, 2023 |
| Gigabyte      | GA-A75M-S2V                 | Desktop     | [3da2ab0f79](https://linux-hardware.org/?probe=3da2ab0f79) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [47a1dadfc2](https://linux-hardware.org/?probe=47a1dadfc2) | Oct 05, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [cef2fbcb68](https://linux-hardware.org/?probe=cef2fbcb68) | Oct 05, 2023 |
| OrangePi      | Zero3                       | Soc         | [a97205648a](https://linux-hardware.org/?probe=a97205648a) | Oct 05, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [7849b5efb5](https://linux-hardware.org/?probe=7849b5efb5) | Oct 05, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1a05adb467](https://linux-hardware.org/?probe=1a05adb467) | Oct 04, 2023 |
| ASUSTek       | E402BA                      | Notebook    | [ff16ab19fd](https://linux-hardware.org/?probe=ff16ab19fd) | Oct 04, 2023 |
| ASRock        | Z790 PG Riptide             | Desktop     | [82630a534f](https://linux-hardware.org/?probe=82630a534f) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [85af984a69](https://linux-hardware.org/?probe=85af984a69) | Oct 03, 2023 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [a9fd86c33d](https://linux-hardware.org/?probe=a9fd86c33d) | Oct 03, 2023 |
| ECS           | H67H2-EM                    | Desktop     | [15b851571b](https://linux-hardware.org/?probe=15b851571b) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [0516711124](https://linux-hardware.org/?probe=0516711124) | Oct 02, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [8c7e1a3205](https://linux-hardware.org/?probe=8c7e1a3205) | Oct 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [aeb0b469c8](https://linux-hardware.org/?probe=aeb0b469c8) | Oct 01, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bc2e88dd9c](https://linux-hardware.org/?probe=bc2e88dd9c) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | Desktop     | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Medion        | MS-7667                     | Desktop     | [a91527e825](https://linux-hardware.org/?probe=a91527e825) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [a3af35a207](https://linux-hardware.org/?probe=a3af35a207) | Sep 29, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3859ed5445](https://linux-hardware.org/?probe=3859ed5445) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| SKIKK         | Sindri 14                   | Notebook    | [9766c80aa9](https://linux-hardware.org/?probe=9766c80aa9) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5828bffdb6](https://linux-hardware.org/?probe=5828bffdb6) | Sep 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [76c2234d3e](https://linux-hardware.org/?probe=76c2234d3e) | Sep 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [6bb37fb224](https://linux-hardware.org/?probe=6bb37fb224) | Sep 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [50e5cd4da6](https://linux-hardware.org/?probe=50e5cd4da6) | Sep 28, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [6e4c4376c5](https://linux-hardware.org/?probe=6e4c4376c5) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Acer          | FX58M                       | Desktop     | [e24f36e0bd](https://linux-hardware.org/?probe=e24f36e0bd) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| HP            | 2ADE                        | Desktop     | [ec7d683b49](https://linux-hardware.org/?probe=ec7d683b49) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [2e717c304e](https://linux-hardware.org/?probe=2e717c304e) | Sep 25, 2023 |
| MSI           | Katana 15 B12VGK            | Notebook    | [9a6d33a191](https://linux-hardware.org/?probe=9a6d33a191) | Sep 24, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [7a121f2a9e](https://linux-hardware.org/?probe=7a121f2a9e) | Sep 24, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [888c822527](https://linux-hardware.org/?probe=888c822527) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [42309ddc8c](https://linux-hardware.org/?probe=42309ddc8c) | Sep 23, 2023 |
| System76      | Gazelle                     | Notebook    | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [40380b4dce](https://linux-hardware.org/?probe=40380b4dce) | Sep 22, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [4e3033c305](https://linux-hardware.org/?probe=4e3033c305) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [6c9da4e4fa](https://linux-hardware.org/?probe=6c9da4e4fa) | Sep 21, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [4b581786a8](https://linux-hardware.org/?probe=4b581786a8) | Sep 21, 2023 |
| Acer          | Aspire 7520                 | Notebook    | [5e16126a55](https://linux-hardware.org/?probe=5e16126a55) | Sep 21, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [ff8d00073e](https://linux-hardware.org/?probe=ff8d00073e) | Sep 21, 2023 |
| Lenovo        | ThinkPad L540 20AU006CRI    | Notebook    | [e8885911a0](https://linux-hardware.org/?probe=e8885911a0) | Sep 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [4ab55a6c83](https://linux-hardware.org/?probe=4ab55a6c83) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | Notebook    | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [a41b85a029](https://linux-hardware.org/?probe=a41b85a029) | Sep 21, 2023 |
| HP            | 0B40h                       | Desktop     | [b9c00a29ab](https://linux-hardware.org/?probe=b9c00a29ab) | Sep 21, 2023 |
| Chuwi         | MiniBook X                  | Notebook    | [50d0819b3b](https://linux-hardware.org/?probe=50d0819b3b) | Sep 20, 2023 |
| Clevo         | E7130                       | Notebook    | [38de5c7699](https://linux-hardware.org/?probe=38de5c7699) | Sep 20, 2023 |
| Acer          | Aspire 7520                 | Notebook    | [bbba1d5ea4](https://linux-hardware.org/?probe=bbba1d5ea4) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [dde4d0b10f](https://linux-hardware.org/?probe=dde4d0b10f) | Sep 20, 2023 |
| Medion        | Akoya E7416                 | Notebook    | [f820e8515d](https://linux-hardware.org/?probe=f820e8515d) | Sep 19, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [d90f46756b](https://linux-hardware.org/?probe=d90f46756b) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [acd1c47b9d](https://linux-hardware.org/?probe=acd1c47b9d) | Sep 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9e9652809d](https://linux-hardware.org/?probe=9e9652809d) | Sep 18, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [cf0fa1658a](https://linux-hardware.org/?probe=cf0fa1658a) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [ebfe5ca0b0](https://linux-hardware.org/?probe=ebfe5ca0b0) | Sep 18, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a7f191e99f](https://linux-hardware.org/?probe=a7f191e99f) | Sep 18, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [50a48f1548](https://linux-hardware.org/?probe=50a48f1548) | Sep 18, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [5f99185bbb](https://linux-hardware.org/?probe=5f99185bbb) | Sep 17, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [675cec7d95](https://linux-hardware.org/?probe=675cec7d95) | Sep 17, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [c47a157971](https://linux-hardware.org/?probe=c47a157971) | Sep 16, 2023 |
| HP            | 2ADE                        | Desktop     | [5b1bf011de](https://linux-hardware.org/?probe=5b1bf011de) | Sep 16, 2023 |
| ASUSTek       | K54L                        | Notebook    | [4b62e4c882](https://linux-hardware.org/?probe=4b62e4c882) | Sep 15, 2023 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [960947648b](https://linux-hardware.org/?probe=960947648b) | Sep 15, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [623cd3e438](https://linux-hardware.org/?probe=623cd3e438) | Sep 14, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [3d3f930e69](https://linux-hardware.org/?probe=3d3f930e69) | Sep 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [d0e8034434](https://linux-hardware.org/?probe=d0e8034434) | Sep 14, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [2a695cf7f9](https://linux-hardware.org/?probe=2a695cf7f9) | Sep 13, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [06b4774756](https://linux-hardware.org/?probe=06b4774756) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [0c8393b2d4](https://linux-hardware.org/?probe=0c8393b2d4) | Sep 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [775b7ba530](https://linux-hardware.org/?probe=775b7ba530) | Sep 13, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [caa54219cf](https://linux-hardware.org/?probe=caa54219cf) | Sep 13, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [97909e20b1](https://linux-hardware.org/?probe=97909e20b1) | Sep 12, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [923e3060e8](https://linux-hardware.org/?probe=923e3060e8) | Sep 10, 2023 |
| Medion        | E11201                      | Notebook    | [c62ac67427](https://linux-hardware.org/?probe=c62ac67427) | Sep 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f39fbfabcc](https://linux-hardware.org/?probe=f39fbfabcc) | Sep 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [e82f904ef8](https://linux-hardware.org/?probe=e82f904ef8) | Sep 10, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6ed0b47516](https://linux-hardware.org/?probe=6ed0b47516) | Sep 08, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [e64c5d24b0](https://linux-hardware.org/?probe=e64c5d24b0) | Sep 08, 2023 |
| HP            | 339A                        | Desktop     | [4ba272aaf9](https://linux-hardware.org/?probe=4ba272aaf9) | Sep 08, 2023 |
| MSI           | MS-B1711                    | Desktop     | [4c68221aae](https://linux-hardware.org/?probe=4c68221aae) | Sep 08, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [16e39e16a0](https://linux-hardware.org/?probe=16e39e16a0) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ecef237a9c](https://linux-hardware.org/?probe=ecef237a9c) | Sep 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [85a4fe79c2](https://linux-hardware.org/?probe=85a4fe79c2) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a738df6114](https://linux-hardware.org/?probe=a738df6114) | Sep 06, 2023 |
| HP            | 21F5                        | Desktop     | [af9bc6bde6](https://linux-hardware.org/?probe=af9bc6bde6) | Sep 06, 2023 |
| ASUSTek       | B150M-PLUS                  | Desktop     | [a5a6f0acfb](https://linux-hardware.org/?probe=a5a6f0acfb) | Sep 06, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [dccf0aaf61](https://linux-hardware.org/?probe=dccf0aaf61) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | Desktop     | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [51e417460a](https://linux-hardware.org/?probe=51e417460a) | Sep 05, 2023 |
| Framework     | Laptop                      | Notebook    | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [312d4a06dc](https://linux-hardware.org/?probe=312d4a06dc) | Sep 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [a26939af7b](https://linux-hardware.org/?probe=a26939af7b) | Sep 05, 2023 |
| HP            | ProBook 6550b               | Notebook    | [5881531377](https://linux-hardware.org/?probe=5881531377) | Sep 05, 2023 |
| Medion        | H110H4-EM                   | Desktop     | [e4752c330e](https://linux-hardware.org/?probe=e4752c330e) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9accfe317a](https://linux-hardware.org/?probe=9accfe317a) | Sep 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [945acb9ea2](https://linux-hardware.org/?probe=945acb9ea2) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [d7b4b0f2f1](https://linux-hardware.org/?probe=d7b4b0f2f1) | Sep 04, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [12894bacfb](https://linux-hardware.org/?probe=12894bacfb) | Sep 03, 2023 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [5656c8fd0b](https://linux-hardware.org/?probe=5656c8fd0b) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b44e37eec5](https://linux-hardware.org/?probe=b44e37eec5) | Sep 03, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [9e80502e5d](https://linux-hardware.org/?probe=9e80502e5d) | Sep 03, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [ad65335e8d](https://linux-hardware.org/?probe=ad65335e8d) | Sep 02, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [efd67d7c17](https://linux-hardware.org/?probe=efd67d7c17) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [c4c911d725](https://linux-hardware.org/?probe=c4c911d725) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [bc7e99e576](https://linux-hardware.org/?probe=bc7e99e576) | Sep 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7907301c2f](https://linux-hardware.org/?probe=7907301c2f) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2acb1da32c](https://linux-hardware.org/?probe=2acb1da32c) | Sep 02, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f592e65a04](https://linux-hardware.org/?probe=f592e65a04) | Sep 02, 2023 |
| Lenovo        | 14w Gen 2 82N9              | Notebook    | [87c8a118b5](https://linux-hardware.org/?probe=87c8a118b5) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [07a44c323f](https://linux-hardware.org/?probe=07a44c323f) | Sep 01, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [0f9de0fdf4](https://linux-hardware.org/?probe=0f9de0fdf4) | Sep 01, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [3b02e0db71](https://linux-hardware.org/?probe=3b02e0db71) | Sep 01, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5cb3aa2368](https://linux-hardware.org/?probe=5cb3aa2368) | Aug 31, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [8ad8098315](https://linux-hardware.org/?probe=8ad8098315) | Aug 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 1495                        | Desktop     | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [56e3937602](https://linux-hardware.org/?probe=56e3937602) | Aug 31, 2023 |
| ASUSTek       | P6T6 WS REVOLUTION          | Desktop     | [cff4daa814](https://linux-hardware.org/?probe=cff4daa814) | Aug 30, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [2e1b103708](https://linux-hardware.org/?probe=2e1b103708) | Aug 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [5e3be336db](https://linux-hardware.org/?probe=5e3be336db) | Aug 30, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [047f752404](https://linux-hardware.org/?probe=047f752404) | Aug 30, 2023 |
| MSI           | Katana GF76 11UC            | Notebook    | [dd25d90357](https://linux-hardware.org/?probe=dd25d90357) | Aug 30, 2023 |
| HP            | 885F A                      | Desktop     | [d665bb8939](https://linux-hardware.org/?probe=d665bb8939) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [338a8026f3](https://linux-hardware.org/?probe=338a8026f3) | Aug 29, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [23712e9380](https://linux-hardware.org/?probe=23712e9380) | Aug 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [87b94b4ea0](https://linux-hardware.org/?probe=87b94b4ea0) | Aug 28, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [409ccc747c](https://linux-hardware.org/?probe=409ccc747c) | Aug 28, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [8c0be85e0e](https://linux-hardware.org/?probe=8c0be85e0e) | Aug 28, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [47b9d876af](https://linux-hardware.org/?probe=47b9d876af) | Aug 27, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [3d8f7e9e00](https://linux-hardware.org/?probe=3d8f7e9e00) | Aug 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [4d894addd1](https://linux-hardware.org/?probe=4d894addd1) | Aug 27, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [40802d54a7](https://linux-hardware.org/?probe=40802d54a7) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [5ef3048a11](https://linux-hardware.org/?probe=5ef3048a11) | Aug 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [25b5ca25b8](https://linux-hardware.org/?probe=25b5ca25b8) | Aug 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [14605463c1](https://linux-hardware.org/?probe=14605463c1) | Aug 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [738c091241](https://linux-hardware.org/?probe=738c091241) | Aug 26, 2023 |
| HP            | Notebook                    | Notebook    | [b27d20b450](https://linux-hardware.org/?probe=b27d20b450) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7425d71f52](https://linux-hardware.org/?probe=7425d71f52) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [fc86b0463f](https://linux-hardware.org/?probe=fc86b0463f) | Aug 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6496a666d7](https://linux-hardware.org/?probe=6496a666d7) | Aug 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [adb5d31da7](https://linux-hardware.org/?probe=adb5d31da7) | Aug 25, 2023 |
| Google        | Rammus                      | Notebook    | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [de1d12ec95](https://linux-hardware.org/?probe=de1d12ec95) | Aug 24, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [6788c79a8b](https://linux-hardware.org/?probe=6788c79a8b) | Aug 24, 2023 |
| Google        | Rammus                      | Notebook    | [57b3596f63](https://linux-hardware.org/?probe=57b3596f63) | Aug 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3746b277b6](https://linux-hardware.org/?probe=3746b277b6) | Aug 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3e241db8f7](https://linux-hardware.org/?probe=3e241db8f7) | Aug 24, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [845b1d4d76](https://linux-hardware.org/?probe=845b1d4d76) | Aug 22, 2023 |
| Positivo      | Mobile                      | Notebook    | [e39dbd02a9](https://linux-hardware.org/?probe=e39dbd02a9) | Aug 22, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [23474c1faa](https://linux-hardware.org/?probe=23474c1faa) | Aug 22, 2023 |
| Unknown       | Unknown                     | Soc         | [a89fb0968e](https://linux-hardware.org/?probe=a89fb0968e) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | Notebook    | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b59f9b2f6a](https://linux-hardware.org/?probe=b59f9b2f6a) | Aug 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b1aa1b9853](https://linux-hardware.org/?probe=b1aa1b9853) | Aug 21, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [81bc5661ca](https://linux-hardware.org/?probe=81bc5661ca) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23243VG       | Notebook    | [be77bad24e](https://linux-hardware.org/?probe=be77bad24e) | Aug 21, 2023 |
| HP            | Presario CQ42               | Notebook    | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [31861c8357](https://linux-hardware.org/?probe=31861c8357) | Aug 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [dc150253e5](https://linux-hardware.org/?probe=dc150253e5) | Aug 18, 2023 |
| HP            | 0B40h                       | Desktop     | [27ee0e32c4](https://linux-hardware.org/?probe=27ee0e32c4) | Aug 17, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [24a295f95b](https://linux-hardware.org/?probe=24a295f95b) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dd8d164747](https://linux-hardware.org/?probe=dd8d164747) | Aug 17, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [2d38a6554a](https://linux-hardware.org/?probe=2d38a6554a) | Aug 16, 2023 |
| HP            | 1998                        | Desktop     | [b44d5aaf94](https://linux-hardware.org/?probe=b44d5aaf94) | Aug 16, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [56759a6a05](https://linux-hardware.org/?probe=56759a6a05) | Aug 16, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [bbf606d6e8](https://linux-hardware.org/?probe=bbf606d6e8) | Aug 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3da24e6a41](https://linux-hardware.org/?probe=3da24e6a41) | Aug 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [12c4ed323e](https://linux-hardware.org/?probe=12c4ed323e) | Aug 15, 2023 |
| Gigabyte      | H61M-DS2V                   | Desktop     | [a1dccbbd3f](https://linux-hardware.org/?probe=a1dccbbd3f) | Aug 15, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [7aac45ad2d](https://linux-hardware.org/?probe=7aac45ad2d) | Aug 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [2c2aca991d](https://linux-hardware.org/?probe=2c2aca991d) | Aug 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [ed10f1ef39](https://linux-hardware.org/?probe=ed10f1ef39) | Aug 13, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ef08441bc9](https://linux-hardware.org/?probe=ef08441bc9) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| AMI           | Unknown                     | Notebook    | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| Lenovo        | ThinkPad T490 20N3S8FN0F    | Notebook    | [cff61d75ae](https://linux-hardware.org/?probe=cff61d75ae) | Aug 12, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [0eb433075b](https://linux-hardware.org/?probe=0eb433075b) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [6fdc79e1c7](https://linux-hardware.org/?probe=6fdc79e1c7) | Aug 12, 2023 |
| HP            | ProBook 6560b               | Notebook    | [01c0e5d78c](https://linux-hardware.org/?probe=01c0e5d78c) | Aug 12, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4fe5238f21](https://linux-hardware.org/?probe=4fe5238f21) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [b4a67f9e6d](https://linux-hardware.org/?probe=b4a67f9e6d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7d1e95601c](https://linux-hardware.org/?probe=7d1e95601c) | Aug 09, 2023 |
| HP            | ProBook 4310s               | Notebook    | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [2a02492c01](https://linux-hardware.org/?probe=2a02492c01) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [509b979b88](https://linux-hardware.org/?probe=509b979b88) | Aug 09, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [8a6ead436f](https://linux-hardware.org/?probe=8a6ead436f) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [60a28c22c7](https://linux-hardware.org/?probe=60a28c22c7) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [9f044dbe9e](https://linux-hardware.org/?probe=9f044dbe9e) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [c1062b9705](https://linux-hardware.org/?probe=c1062b9705) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [46a7513850](https://linux-hardware.org/?probe=46a7513850) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [309b546405](https://linux-hardware.org/?probe=309b546405) | Aug 07, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7c6e6aaaea](https://linux-hardware.org/?probe=7c6e6aaaea) | Aug 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8ee3625d12](https://linux-hardware.org/?probe=8ee3625d12) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [eeb7f6e8fe](https://linux-hardware.org/?probe=eeb7f6e8fe) | Aug 06, 2023 |
| HP            | 829A                        | Mini pc     | [8d7ea68ded](https://linux-hardware.org/?probe=8d7ea68ded) | Aug 05, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [c157382bd3](https://linux-hardware.org/?probe=c157382bd3) | Aug 05, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [4a2c7a9f15](https://linux-hardware.org/?probe=4a2c7a9f15) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [32fd45f163](https://linux-hardware.org/?probe=32fd45f163) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [5636598221](https://linux-hardware.org/?probe=5636598221) | Aug 03, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [1318f4d842](https://linux-hardware.org/?probe=1318f4d842) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [79d26043a0](https://linux-hardware.org/?probe=79d26043a0) | Aug 03, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [deb7c70ef0](https://linux-hardware.org/?probe=deb7c70ef0) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [d5bb32f2de](https://linux-hardware.org/?probe=d5bb32f2de) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| Gigabyte      | P35-DS4                     | Desktop     | [9116e4042c](https://linux-hardware.org/?probe=9116e4042c) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fd9503645f](https://linux-hardware.org/?probe=fd9503645f) | Aug 01, 2023 |
| Dell          | Latitude E6440              | Notebook    | [57ce920c06](https://linux-hardware.org/?probe=57ce920c06) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [22e8927934](https://linux-hardware.org/?probe=22e8927934) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [046b3ffe68](https://linux-hardware.org/?probe=046b3ffe68) | Aug 01, 2023 |
| Dell          | OptiPlex 980                | Desktop     | [7ec85c3865](https://linux-hardware.org/?probe=7ec85c3865) | Aug 01, 2023 |
| HP            | 8924 0101                   | All in one  | [e2fa4d7d10](https://linux-hardware.org/?probe=e2fa4d7d10) | Jul 31, 2023 |
| Intel         | NUC7i7DNB J83500-207        | Mini pc     | [e18855dc59](https://linux-hardware.org/?probe=e18855dc59) | Jul 30, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f94bdf300](https://linux-hardware.org/?probe=4f94bdf300) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4d875892d6](https://linux-hardware.org/?probe=4d875892d6) | Jul 30, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4ff0e84129](https://linux-hardware.org/?probe=4ff0e84129) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [02383fb507](https://linux-hardware.org/?probe=02383fb507) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [ca01eab0e3](https://linux-hardware.org/?probe=ca01eab0e3) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [b322ef8e74](https://linux-hardware.org/?probe=b322ef8e74) | Jul 28, 2023 |
| HP            | 829D                        | Desktop     | [35b5c3a375](https://linux-hardware.org/?probe=35b5c3a375) | Jul 28, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d6855eabe2](https://linux-hardware.org/?probe=d6855eabe2) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Minix         | NEO Z83-4A                  | Notebook    | [3a884d55d3](https://linux-hardware.org/?probe=3a884d55d3) | Jul 26, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [864fcc639d](https://linux-hardware.org/?probe=864fcc639d) | Jul 25, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| Intel         | NUC5i5MYBE H47797-206       | Mini pc     | [393855b913](https://linux-hardware.org/?probe=393855b913) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7970e46266](https://linux-hardware.org/?probe=7970e46266) | Jul 25, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [12c8f156b9](https://linux-hardware.org/?probe=12c8f156b9) | Jul 25, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [52d2901ce2](https://linux-hardware.org/?probe=52d2901ce2) | Jul 25, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b30f6c221b](https://linux-hardware.org/?probe=b30f6c221b) | Jul 25, 2023 |
| ASUSTek       | T303UA                      | Tablet      | [19f4fde1e4](https://linux-hardware.org/?probe=19f4fde1e4) | Jul 24, 2023 |
| ASUSTek       | T303UA                      | Tablet      | [8e189305b3](https://linux-hardware.org/?probe=8e189305b3) | Jul 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [67585d0d00](https://linux-hardware.org/?probe=67585d0d00) | Jul 24, 2023 |
| HP            | 212B                        | Desktop     | [3e033bf376](https://linux-hardware.org/?probe=3e033bf376) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [02cae62d32](https://linux-hardware.org/?probe=02cae62d32) | Jul 24, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [684aa3a397](https://linux-hardware.org/?probe=684aa3a397) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [de58b924e1](https://linux-hardware.org/?probe=de58b924e1) | Jul 23, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [5215522010](https://linux-hardware.org/?probe=5215522010) | Jul 23, 2023 |
| AMI           | Intel                       | Desktop     | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Standard      | Unknown                     | Notebook    | [74acf0f707](https://linux-hardware.org/?probe=74acf0f707) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [f7218e4043](https://linux-hardware.org/?probe=f7218e4043) | Jul 20, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a55acd567e](https://linux-hardware.org/?probe=a55acd567e) | Jul 19, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [73bad4fbb8](https://linux-hardware.org/?probe=73bad4fbb8) | Jul 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [92efeaeef7](https://linux-hardware.org/?probe=92efeaeef7) | Jul 18, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [49a085a451](https://linux-hardware.org/?probe=49a085a451) | Jul 18, 2023 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| HP            | Notebook                    | Notebook    | [4498c757a7](https://linux-hardware.org/?probe=4498c757a7) | Jul 18, 2023 |
| Dell          | Latitude E5510              | Notebook    | [3b006db4ec](https://linux-hardware.org/?probe=3b006db4ec) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [19b0d02a1e](https://linux-hardware.org/?probe=19b0d02a1e) | Jul 17, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e22c4ba5ee](https://linux-hardware.org/?probe=e22c4ba5ee) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| ASRock        | H370 Performance            | Desktop     | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | Notebook    | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d553e03b18](https://linux-hardware.org/?probe=d553e03b18) | Jul 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a230ea3a4d](https://linux-hardware.org/?probe=a230ea3a4d) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [038a62a49f](https://linux-hardware.org/?probe=038a62a49f) | Jul 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4de092adb7](https://linux-hardware.org/?probe=4de092adb7) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| Dell          | Precision 7540              | Notebook    | [c862752535](https://linux-hardware.org/?probe=c862752535) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4dc6731c7a](https://linux-hardware.org/?probe=4dc6731c7a) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e32b594990](https://linux-hardware.org/?probe=e32b594990) | Jul 14, 2023 |
| MSI           | H170M PRO-VDH               | Desktop     | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [74ef14c05b](https://linux-hardware.org/?probe=74ef14c05b) | Jul 13, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [b937fd31a8](https://linux-hardware.org/?probe=b937fd31a8) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| HP            | ProBook 6570b               | Notebook    | [0c933d2dd8](https://linux-hardware.org/?probe=0c933d2dd8) | Jul 12, 2023 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [e160b642b4](https://linux-hardware.org/?probe=e160b642b4) | Jul 12, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ea5b457e85](https://linux-hardware.org/?probe=ea5b457e85) | Jul 11, 2023 |
| Acer          | Extensa 7630G               | Notebook    | [47c7ddbf85](https://linux-hardware.org/?probe=47c7ddbf85) | Jul 11, 2023 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [f7305d0265](https://linux-hardware.org/?probe=f7305d0265) | Jul 11, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [8ec23e64db](https://linux-hardware.org/?probe=8ec23e64db) | Jul 10, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [f60d21d84f](https://linux-hardware.org/?probe=f60d21d84f) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Acer          | TravelMate P2510-G2-M       | Notebook    | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| ECS           | P43T-AD3                    | Desktop     | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a3fd5e4b9d](https://linux-hardware.org/?probe=a3fd5e4b9d) | Jul 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3401b425ae](https://linux-hardware.org/?probe=3401b425ae) | Jul 07, 2023 |
| ASUSTek       | G73Jw                       | Notebook    | [79053de50e](https://linux-hardware.org/?probe=79053de50e) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | Notebook    | [b482f282a5](https://linux-hardware.org/?probe=b482f282a5) | Jul 06, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [55d33d8a40](https://linux-hardware.org/?probe=55d33d8a40) | Jul 06, 2023 |
| Notebook      | NJx0PU                      | Notebook    | [29ebf426d1](https://linux-hardware.org/?probe=29ebf426d1) | Jul 06, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [d759c2c726](https://linux-hardware.org/?probe=d759c2c726) | Jul 06, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4e88e96d9f](https://linux-hardware.org/?probe=4e88e96d9f) | Jul 06, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [d988a440f0](https://linux-hardware.org/?probe=d988a440f0) | Jul 05, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [4397540a82](https://linux-hardware.org/?probe=4397540a82) | Jul 05, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [a40b38a093](https://linux-hardware.org/?probe=a40b38a093) | Jul 05, 2023 |
| Dell          | 0WG261                      | Desktop     | [8ef0f126d5](https://linux-hardware.org/?probe=8ef0f126d5) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | 212B                        | Desktop     | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [2296d2e846](https://linux-hardware.org/?probe=2296d2e846) | Jul 03, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9330835392](https://linux-hardware.org/?probe=9330835392) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [6a51948293](https://linux-hardware.org/?probe=6a51948293) | Jul 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [5af51ee197](https://linux-hardware.org/?probe=5af51ee197) | Jul 03, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [e578144ebb](https://linux-hardware.org/?probe=e578144ebb) | Jul 02, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [83fd2dc626](https://linux-hardware.org/?probe=83fd2dc626) | Jul 02, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [e0810c9450](https://linux-hardware.org/?probe=e0810c9450) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| Packard Be... | EasyNote TJ67               | Notebook    | [92be4d3a56](https://linux-hardware.org/?probe=92be4d3a56) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| Dell          | 09T7VV A02                  | Server      | [a63b9c6851](https://linux-hardware.org/?probe=a63b9c6851) | Jul 01, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [e33c7b943c](https://linux-hardware.org/?probe=e33c7b943c) | Jul 01, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | Notebook    | [88b4565c0b](https://linux-hardware.org/?probe=88b4565c0b) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | Notebook    | [7e1b98b585](https://linux-hardware.org/?probe=7e1b98b585) | Jul 01, 2023 |
| HP            | 1998                        | Desktop     | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| Acer          | FRS780M                     | Desktop     | [3066c1772f](https://linux-hardware.org/?probe=3066c1772f) | Jul 01, 2023 |
| Acer          | FRS780M                     | Desktop     | [4f8ad26557](https://linux-hardware.org/?probe=4f8ad26557) | Jul 01, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [7b546735a4](https://linux-hardware.org/?probe=7b546735a4) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [64e81a22a5](https://linux-hardware.org/?probe=64e81a22a5) | Jun 29, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [b36ca5687c](https://linux-hardware.org/?probe=b36ca5687c) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | Notebook    | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Dell          | Latitude 7370               | Notebook    | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3ef19cf418](https://linux-hardware.org/?probe=3ef19cf418) | Jun 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [e39c7f5f6f](https://linux-hardware.org/?probe=e39c7f5f6f) | Jun 28, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [771e2e233a](https://linux-hardware.org/?probe=771e2e233a) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | Notebook    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [e1b714fdf1](https://linux-hardware.org/?probe=e1b714fdf1) | Jun 27, 2023 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [c73458700f](https://linux-hardware.org/?probe=c73458700f) | Jun 27, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f5e04da161](https://linux-hardware.org/?probe=f5e04da161) | Jun 26, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [554a954c22](https://linux-hardware.org/?probe=554a954c22) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [9c925666a5](https://linux-hardware.org/?probe=9c925666a5) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ea814b3f7b](https://linux-hardware.org/?probe=ea814b3f7b) | Jun 26, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [23c2fe2245](https://linux-hardware.org/?probe=23c2fe2245) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7e8503e88](https://linux-hardware.org/?probe=d7e8503e88) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [b33e52fa0a](https://linux-hardware.org/?probe=b33e52fa0a) | Jun 22, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [c63cf5f434](https://linux-hardware.org/?probe=c63cf5f434) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [7782ddf809](https://linux-hardware.org/?probe=7782ddf809) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| HP            | 0B40h                       | Desktop     | [ac50670d44](https://linux-hardware.org/?probe=ac50670d44) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [b34442d8c3](https://linux-hardware.org/?probe=b34442d8c3) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [f9bf8920f7](https://linux-hardware.org/?probe=f9bf8920f7) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [c436287876](https://linux-hardware.org/?probe=c436287876) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [bcd39f0607](https://linux-hardware.org/?probe=bcd39f0607) | Jun 19, 2023 |
| HP            | HDX18                       | Notebook    | [dec8492b2f](https://linux-hardware.org/?probe=dec8492b2f) | Jun 19, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [2fa7c42c59](https://linux-hardware.org/?probe=2fa7c42c59) | Jun 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7a4e69498](https://linux-hardware.org/?probe=b7a4e69498) | Jun 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [cb097e3c83](https://linux-hardware.org/?probe=cb097e3c83) | Jun 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [8b9ddcc1d8](https://linux-hardware.org/?probe=8b9ddcc1d8) | Jun 18, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [8f7aac560c](https://linux-hardware.org/?probe=8f7aac560c) | Jun 18, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [3f18a24757](https://linux-hardware.org/?probe=3f18a24757) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Dell          | Latitude 3189               | Notebook    | [c7f2d1b100](https://linux-hardware.org/?probe=c7f2d1b100) | Jun 17, 2023 |
| HP            | 3397                        | Desktop     | [b9fa9f9e43](https://linux-hardware.org/?probe=b9fa9f9e43) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [93bd9e7b0b](https://linux-hardware.org/?probe=93bd9e7b0b) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [36b0b1204f](https://linux-hardware.org/?probe=36b0b1204f) | Jun 17, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [a62dc4b2ed](https://linux-hardware.org/?probe=a62dc4b2ed) | Jun 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6e0568f0df](https://linux-hardware.org/?probe=6e0568f0df) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [d5d7c6ec90](https://linux-hardware.org/?probe=d5d7c6ec90) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| HP            | HDX18                       | Notebook    | [9a49d14af9](https://linux-hardware.org/?probe=9a49d14af9) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [6b73cb1d75](https://linux-hardware.org/?probe=6b73cb1d75) | Jun 15, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [a8cc966bac](https://linux-hardware.org/?probe=a8cc966bac) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [cc3d8c4659](https://linux-hardware.org/?probe=cc3d8c4659) | Jun 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [1f5318c2b4](https://linux-hardware.org/?probe=1f5318c2b4) | Jun 14, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| Samsung       | 750XED                      | Notebook    | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [39d97bb85b](https://linux-hardware.org/?probe=39d97bb85b) | Jun 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [aca09b2a54](https://linux-hardware.org/?probe=aca09b2a54) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [b815ac19d4](https://linux-hardware.org/?probe=b815ac19d4) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d2cb2b5360](https://linux-hardware.org/?probe=d2cb2b5360) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Dell          | Latitude 9420               | Convertible | [354adf0653](https://linux-hardware.org/?probe=354adf0653) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| Dell          | 0PU052                      | Desktop     | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | Latitude 9420               | Convertible | [593403cb67](https://linux-hardware.org/?probe=593403cb67) | Jun 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [7a36bdb92a](https://linux-hardware.org/?probe=7a36bdb92a) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Dell          | Precision 7540              | Notebook    | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | Notebook    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4895fe7746](https://linux-hardware.org/?probe=4895fe7746) | Jun 05, 2023 |
| Dell          | Precision 7540              | Notebook    | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [5e1bb16065](https://linux-hardware.org/?probe=5e1bb16065) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | Notebook    | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| HP            | 1906                        | Desktop     | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | Desktop     | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [06000e9b0e](https://linux-hardware.org/?probe=06000e9b0e) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [fa8eeaabff](https://linux-hardware.org/?probe=fa8eeaabff) | May 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [bf0674c0f0](https://linux-hardware.org/?probe=bf0674c0f0) | May 28, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| MSI           | CX700                       | Notebook    | [ecb1aaf9c1](https://linux-hardware.org/?probe=ecb1aaf9c1) | May 26, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Dell          | Latitude 5290               | Notebook    | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| AAEON         | UP-CHCR1 V0.4               | Desktop     | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | Precision 7540              | Notebook    | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [52b95d45ca](https://linux-hardware.org/?probe=52b95d45ca) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [b021476220](https://linux-hardware.org/?probe=b021476220) | May 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69f5bff4c0](https://linux-hardware.org/?probe=69f5bff4c0) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Dell          | Precision 7540              | Notebook    | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [50b46e4d8c](https://linux-hardware.org/?probe=50b46e4d8c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| AMI           | Intel                       | Desktop     | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [a655c52b88](https://linux-hardware.org/?probe=a655c52b88) | May 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | Desktop     | [0d2426a070](https://linux-hardware.org/?probe=0d2426a070) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Lenovo        | ThinkPad T410 2537V32       | Notebook    | [cece14e931](https://linux-hardware.org/?probe=cece14e931) | May 21, 2023 |
| HP            | 0A08h                       | Desktop     | [9d159d2637](https://linux-hardware.org/?probe=9d159d2637) | May 21, 2023 |
| AMI           | Intel                       | Desktop     | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b344b7ea03](https://linux-hardware.org/?probe=b344b7ea03) | May 21, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [1f2563578e](https://linux-hardware.org/?probe=1f2563578e) | May 20, 2023 |
| Dell          | Latitude 3120               | Convertible | [ac4bbe967d](https://linux-hardware.org/?probe=ac4bbe967d) | May 19, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [41342ea0f6](https://linux-hardware.org/?probe=41342ea0f6) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [97149ea35b](https://linux-hardware.org/?probe=97149ea35b) | May 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Acer          | Aspire 7535                 | Notebook    | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [215d88c8b6](https://linux-hardware.org/?probe=215d88c8b6) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [d452669f4a](https://linux-hardware.org/?probe=d452669f4a) | May 18, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [beacb75b2c](https://linux-hardware.org/?probe=beacb75b2c) | May 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Dell          | Latitude E5510              | Notebook    | [74ecc09f16](https://linux-hardware.org/?probe=74ecc09f16) | May 17, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [228fa2798d](https://linux-hardware.org/?probe=228fa2798d) | May 16, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32d4567b37](https://linux-hardware.org/?probe=32d4567b37) | May 16, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [de2456eae8](https://linux-hardware.org/?probe=de2456eae8) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3ca79ab5f8](https://linux-hardware.org/?probe=3ca79ab5f8) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [858590e655](https://linux-hardware.org/?probe=858590e655) | May 15, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1efefa9214](https://linux-hardware.org/?probe=1efefa9214) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| HP            | 829D                        | Desktop     | [a9358c228a](https://linux-hardware.org/?probe=a9358c228a) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Xiaomi        | Mipad2                      | Tablet      | [c3c41b0bae](https://linux-hardware.org/?probe=c3c41b0bae) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | Notebook    | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| HP            | EliteBook 720 G2            | Notebook    | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| Dell          | Latitude E7450              | Notebook    | [9dbbae1356](https://linux-hardware.org/?probe=9dbbae1356) | May 12, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [4318c51164](https://linux-hardware.org/?probe=4318c51164) | May 12, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [341a5673f2](https://linux-hardware.org/?probe=341a5673f2) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | 829A                        | Mini pc     | [e51b2da826](https://linux-hardware.org/?probe=e51b2da826) | May 12, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [eefa55009a](https://linux-hardware.org/?probe=eefa55009a) | May 11, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [1e8359a02c](https://linux-hardware.org/?probe=1e8359a02c) | May 11, 2023 |
| Notebook      | N14xWU                      | Notebook    | [0e4f386b46](https://linux-hardware.org/?probe=0e4f386b46) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [99af0c1e17](https://linux-hardware.org/?probe=99af0c1e17) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| Acer          | TravelMate P653-M           | Notebook    | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Dell          | XPS 9315                    | Notebook    | [291a190f04](https://linux-hardware.org/?probe=291a190f04) | May 10, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| Acer          | Aspire M1930                | Desktop     | [712a246ce4](https://linux-hardware.org/?probe=712a246ce4) | May 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [8e4cbc4837](https://linux-hardware.org/?probe=8e4cbc4837) | May 08, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [ec45ea6206](https://linux-hardware.org/?probe=ec45ea6206) | May 08, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| PC Special... | NP5x_NP6x_NP7xPNP           | Notebook    | [72d9dac16b](https://linux-hardware.org/?probe=72d9dac16b) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [148433c97e](https://linux-hardware.org/?probe=148433c97e) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dce7e41a72](https://linux-hardware.org/?probe=dce7e41a72) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [64db3d70f1](https://linux-hardware.org/?probe=64db3d70f1) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0d6a9b046a](https://linux-hardware.org/?probe=0d6a9b046a) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [bdafbe06aa](https://linux-hardware.org/?probe=bdafbe06aa) | May 07, 2023 |
| HP            | 829A                        | Mini pc     | [eba2b6ce4e](https://linux-hardware.org/?probe=eba2b6ce4e) | May 06, 2023 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [01e1d2ef02](https://linux-hardware.org/?probe=01e1d2ef02) | May 05, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| Unknown       | Cherry Trail CR             | Notebook    | [9569a530e8](https://linux-hardware.org/?probe=9569a530e8) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| Intel         | JSL MRD                     | Desktop     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Acer          | TravelMate P214-53          | Notebook    | [8e78c8d139](https://linux-hardware.org/?probe=8e78c8d139) | May 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [f839b22217](https://linux-hardware.org/?probe=f839b22217) | May 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a6a9a6675](https://linux-hardware.org/?probe=0a6a9a6675) | May 03, 2023 |
| Dell          | Latitude 7420               | Notebook    | [7986f6779d](https://linux-hardware.org/?probe=7986f6779d) | May 03, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [dfbf38e06f](https://linux-hardware.org/?probe=dfbf38e06f) | May 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f3b0efc277](https://linux-hardware.org/?probe=f3b0efc277) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| VIOS          | LTH17                       | Notebook    | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [3316360d7a](https://linux-hardware.org/?probe=3316360d7a) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Insyde        | M890BAP                     | Notebook    | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [bd3dba564e](https://linux-hardware.org/?probe=bd3dba564e) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [cab1aa59e0](https://linux-hardware.org/?probe=cab1aa59e0) | Apr 28, 2023 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [36175223a5](https://linux-hardware.org/?probe=36175223a5) | Apr 28, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [fa82c3b6ba](https://linux-hardware.org/?probe=fa82c3b6ba) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c416a3f44a](https://linux-hardware.org/?probe=c416a3f44a) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [589810ee4b](https://linux-hardware.org/?probe=589810ee4b) | Apr 28, 2023 |
| Dell          | Latitude 3301               | Notebook    | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [6b17eb81f8](https://linux-hardware.org/?probe=6b17eb81f8) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Acer          | Aspire X3995                | Desktop     | [877c9deb7a](https://linux-hardware.org/?probe=877c9deb7a) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [37cd92a7f0](https://linux-hardware.org/?probe=37cd92a7f0) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [0b966e7b88](https://linux-hardware.org/?probe=0b966e7b88) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [06fbe4d0b6](https://linux-hardware.org/?probe=06fbe4d0b6) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [2337ae230f](https://linux-hardware.org/?probe=2337ae230f) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [90db0063b0](https://linux-hardware.org/?probe=90db0063b0) | Apr 24, 2023 |
| BTO           | 17X1183                     | Notebook    | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | Notebook    | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | Notebook    | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b906572f4b](https://linux-hardware.org/?probe=b906572f4b) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [65ba6571a2](https://linux-hardware.org/?probe=65ba6571a2) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [2e828158e5](https://linux-hardware.org/?probe=2e828158e5) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | Notebook    | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | Notebook    | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| EVERCOM NE... | Unknown                     | Desktop     | [d36803f05d](https://linux-hardware.org/?probe=d36803f05d) | Apr 21, 2023 |
| HP            | 1494                        | Desktop     | [625373a1de](https://linux-hardware.org/?probe=625373a1de) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [e8332849a1](https://linux-hardware.org/?probe=e8332849a1) | Apr 20, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [bca816c594](https://linux-hardware.org/?probe=bca816c594) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [4e45f9c51f](https://linux-hardware.org/?probe=4e45f9c51f) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [abcb6ed7e8](https://linux-hardware.org/?probe=abcb6ed7e8) | Apr 19, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [213cd129cd](https://linux-hardware.org/?probe=213cd129cd) | Apr 18, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [ae7ea68877](https://linux-hardware.org/?probe=ae7ea68877) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Acer          | Iconia                      | Notebook    | [1ebc88d3ab](https://linux-hardware.org/?probe=1ebc88d3ab) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [6c08e40387](https://linux-hardware.org/?probe=6c08e40387) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [6c62f23970](https://linux-hardware.org/?probe=6c62f23970) | Apr 16, 2023 |
| HP            | 18E7                        | Desktop     | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [5994a04ee0](https://linux-hardware.org/?probe=5994a04ee0) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [ca89b451bd](https://linux-hardware.org/?probe=ca89b451bd) | Apr 15, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [df2e4c0c56](https://linux-hardware.org/?probe=df2e4c0c56) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2c7e1238eb](https://linux-hardware.org/?probe=2c7e1238eb) | Apr 15, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [fcf729207a](https://linux-hardware.org/?probe=fcf729207a) | Apr 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Medion        | MS-7857                     | Desktop     | [5d04997966](https://linux-hardware.org/?probe=5d04997966) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [7f4d0d2d91](https://linux-hardware.org/?probe=7f4d0d2d91) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [f3114cd0d7](https://linux-hardware.org/?probe=f3114cd0d7) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Wortmann      | TERRA_MOBILE_1160           | Notebook    | [d40eed27fd](https://linux-hardware.org/?probe=d40eed27fd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | Desktop     | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d2fbfe344c](https://linux-hardware.org/?probe=d2fbfe344c) | Apr 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3d0ccace69](https://linux-hardware.org/?probe=3d0ccace69) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | Notebook    | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [5a903505c7](https://linux-hardware.org/?probe=5a903505c7) | Apr 10, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Acer          | Aspire M1930                | Desktop     | [2bc158bf57](https://linux-hardware.org/?probe=2bc158bf57) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| Acer          | Spin SP314-51               | Convertible | [4b3e9e100d](https://linux-hardware.org/?probe=4b3e9e100d) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [10213d8aa1](https://linux-hardware.org/?probe=10213d8aa1) | Apr 05, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [b34f7e7ea6](https://linux-hardware.org/?probe=b34f7e7ea6) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [e8a69f8de9](https://linux-hardware.org/?probe=e8a69f8de9) | Apr 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [f211babaa5](https://linux-hardware.org/?probe=f211babaa5) | Apr 04, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ec3a161d36](https://linux-hardware.org/?probe=ec3a161d36) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [316e31eae5](https://linux-hardware.org/?probe=316e31eae5) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [088a09317e](https://linux-hardware.org/?probe=088a09317e) | Apr 04, 2023 |
| HP            | 3032h                       | Desktop     | [75792234b4](https://linux-hardware.org/?probe=75792234b4) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | Notebook    | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| Intel         | VALLEYVIEW C0 PLATFORM      | Tablet      | [3dcf212c95](https://linux-hardware.org/?probe=3dcf212c95) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [c1f349f579](https://linux-hardware.org/?probe=c1f349f579) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ca8ae50d80](https://linux-hardware.org/?probe=ca8ae50d80) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e18d9530c1](https://linux-hardware.org/?probe=e18d9530c1) | Mar 31, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [c3065ba2b6](https://linux-hardware.org/?probe=c3065ba2b6) | Mar 31, 2023 |
| Medion        | Iron238G                    | All in one  | [55cab5c7fa](https://linux-hardware.org/?probe=55cab5c7fa) | Mar 31, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [96107a824d](https://linux-hardware.org/?probe=96107a824d) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | 843F                        | Desktop     | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7edc7c9f47](https://linux-hardware.org/?probe=7edc7c9f47) | Mar 30, 2023 |
| Foxconn       | ETON                        | Desktop     | [52e92b5803](https://linux-hardware.org/?probe=52e92b5803) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39d6f86500](https://linux-hardware.org/?probe=39d6f86500) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | Desktop     | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ZOTAC         | AMD M1                      | Desktop     | [2b2c8fd4fa](https://linux-hardware.org/?probe=2b2c8fd4fa) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5fff36a878](https://linux-hardware.org/?probe=5fff36a878) | Mar 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [55f0bb1013](https://linux-hardware.org/?probe=55f0bb1013) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1ee3769d23](https://linux-hardware.org/?probe=1ee3769d23) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Acer          | Aspire M1930                | Desktop     | [228747d646](https://linux-hardware.org/?probe=228747d646) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | 1494                        | Desktop     | [e682c9975e](https://linux-hardware.org/?probe=e682c9975e) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Medion        | MS-7797                     | Desktop     | [180b0242e8](https://linux-hardware.org/?probe=180b0242e8) | Mar 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 583       | 12.72%  |
| Ubuntu 18.04                 | 305       | 6.65%   |
| Ubuntu 22.04                 | 282       | 6.15%   |
| OpenMandriva 4.3             | 199       | 4.34%   |
| Debian 11                    | 110       | 2.4%    |
| Zorin 16                     | 107       | 2.33%   |
| Linux Mint 20.3              | 78        | 1.7%    |
| Arch Rolling                 | 71        | 1.55%   |
| Pop!_OS 22.04                | 70        | 1.53%   |
| Fedora 38                    | 67        | 1.46%   |
| Ubuntu 20.10                 | 66        | 1.44%   |
| Arch                         | 66        | 1.44%   |
| Manjaro                      | 64        | 1.4%    |
| Linux Mint 21.1              | 62        | 1.35%   |
| Xubuntu 20.04                | 56        | 1.22%   |
| openSUSE Tumbleweed-XXXXXXXX | 55        | 1.2%    |
| OpenMandriva 4.2             | 55        | 1.2%    |
| KDE neon 20.04               | 54        | 1.18%   |
| Fedora 36                    | 53        | 1.16%   |
| Fedora 34                    | 53        | 1.16%   |
| Linux Mint 20.2              | 52        | 1.13%   |
| Ubuntu 21.10                 | 51        | 1.11%   |
| Fedora 37                    | 50        | 1.09%   |
| Linux Mint 19.3              | 47        | 1.03%   |
| Ubuntu 21.04                 | 46        | 1%      |
| Linux Mint 20.1              | 46        | 1%      |
| Fedora 35                    | 44        | 0.96%   |
| ArcoLinux Rolling            | 44        | 0.96%   |
| Ubuntu 19.10                 | 43        | 0.94%   |
| Pop!_OS 20.10                | 41        | 0.89%   |
| Fedora 33                    | 41        | 0.89%   |
| Pop!_OS 20.04                | 40        | 0.87%   |
| Zorin 15                     | 39        | 0.85%   |
| Pop!_OS 21.04                | 39        | 0.85%   |
| Ubuntu 22.10                 | 38        | 0.83%   |
| Linux Mint 20                | 38        | 0.83%   |
| Kubuntu 20.04                | 38        | 0.83%   |
| Fedora 31                    | 38        | 0.83%   |
| Ubuntu 19.04                 | 35        | 0.76%   |
| Pop!_OS 21.10                | 35        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1453      | 33.47%  |
| Linux Mint    | 398       | 9.17%   |
| OpenMandriva  | 351       | 8.09%   |
| Fedora        | 349       | 8.04%   |
| Pop!_OS       | 216       | 4.98%   |
| Debian        | 197       | 4.54%   |
| Manjaro       | 164       | 3.78%   |
| Zorin         | 155       | 3.57%   |
| Arch          | 138       | 3.18%   |
| Xubuntu       | 101       | 2.33%   |
| Kubuntu       | 99        | 2.28%   |
| KDE neon      | 81        | 1.87%   |
| openSUSE      | 72        | 1.66%   |
| ArcoLinux     | 47        | 1.08%   |
| Kali          | 33        | 0.76%   |
| EndeavourOS   | 33        | 0.76%   |
| Gentoo        | 32        | 0.74%   |
| Elementary    | 30        | 0.69%   |
| ROSA          | 28        | 0.65%   |
| Lubuntu       | 28        | 0.65%   |
| SteamOS       | 24        | 0.55%   |
| Ubuntu Unity  | 23        | 0.53%   |
| Ubuntu MATE   | 21        | 0.48%   |
| Clear Linux   | 20        | 0.46%   |
| Parrot        | 16        | 0.37%   |
| LMDE          | 16        | 0.37%   |
| Endless       | 16        | 0.37%   |
| Ubuntu Budgie | 15        | 0.35%   |
| MX            | 14        | 0.32%   |
| Nobara        | 13        | 0.3%    |
| Garuda Linux  | 12        | 0.28%   |
| Raspbian      | 11        | 0.25%   |
| Solus         | 10        | 0.23%   |
| Peppermint    | 10        | 0.23%   |
| CentOS        | 10        | 0.23%   |
| BlackPanther  | 6         | 0.14%   |
| Xero          | 5         | 0.12%   |
| Rocky Linux   | 5         | 0.12%   |
| RHEL          | 5         | 0.12%   |
| Reborn OS     | 5         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 197       | 3.86%   |
| 5.4.0-42-generic         | 69        | 1.35%   |
| 5.10.14-desktop-1omv4002 | 54        | 1.06%   |
| 5.4.0-58-generic         | 43        | 0.84%   |
| 5.8.0-50-generic         | 42        | 0.82%   |
| 5.15.0-56-generic        | 39        | 0.77%   |
| 5.15.0-58-generic        | 37        | 0.73%   |
| 5.4.0-52-generic         | 36        | 0.71%   |
| 5.4.0-48-generic         | 35        | 0.69%   |
| 5.11.0-38-generic        | 33        | 0.65%   |
| 5.15.0-46-generic        | 30        | 0.59%   |
| 6.2.6-desktop-1omv2390   | 28        | 0.55%   |
| 6.1.1-desktop-1omv2290   | 28        | 0.55%   |
| 5.8.0-43-generic         | 26        | 0.51%   |
| 5.4.0-26-generic         | 26        | 0.51%   |
| 5.13.0-28-generic        | 26        | 0.51%   |
| 5.11.0-27-generic        | 26        | 0.51%   |
| 5.4.0-77-generic         | 25        | 0.49%   |
| 5.15.0-52-generic        | 25        | 0.49%   |
| 5.4.0-40-generic         | 24        | 0.47%   |
| 5.15.0-43-generic        | 24        | 0.47%   |
| 5.19.0-35-generic        | 23        | 0.45%   |
| 5.4.0-37-generic         | 22        | 0.43%   |
| 5.15.0-76-generic        | 22        | 0.43%   |
| 5.15.0-67-generic        | 22        | 0.43%   |
| 5.15.0-48-generic        | 22        | 0.43%   |
| 5.8.0-53-generic         | 21        | 0.41%   |
| 5.4.0-65-generic         | 21        | 0.41%   |
| 5.15.0-60-generic        | 21        | 0.41%   |
| 5.13.0-39-generic        | 21        | 0.41%   |
| 5.11.0-7620-generic      | 21        | 0.41%   |
| 5.8.0-7630-generic       | 20        | 0.39%   |
| 5.4.0-56-generic         | 20        | 0.39%   |
| 5.4.0-33-generic         | 20        | 0.39%   |
| 5.4.0-29-generic         | 20        | 0.39%   |
| 5.3.0-46-generic         | 19        | 0.37%   |
| 5.11.0-43-generic        | 19        | 0.37%   |
| 5.8.0-48-generic         | 18        | 0.35%   |
| 5.4.0-54-generic         | 18        | 0.35%   |
| 5.4.0-47-generic         | 18        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 723       | 15.13%  |
| 5.15.0  | 442       | 9.25%   |
| 5.8.0   | 285       | 5.96%   |
| 4.15.0  | 243       | 5.09%   |
| 5.11.0  | 236       | 4.94%   |
| 5.13.0  | 205       | 4.29%   |
| 5.16.7  | 200       | 4.19%   |
| 5.19.0  | 156       | 3.26%   |
| 5.3.0   | 141       | 2.95%   |
| 5.10.0  | 128       | 2.68%   |
| 5.0.0   | 107       | 2.24%   |
| 6.2.0   | 99        | 2.07%   |
| 4.18.0  | 73        | 1.53%   |
| 5.10.14 | 57        | 1.19%   |
| 6.1.0   | 47        | 0.98%   |
| 6.2.6   | 44        | 0.92%   |
| 4.19.0  | 37        | 0.77%   |
| 6.1.1   | 33        | 0.69%   |
| 5.14.0  | 26        | 0.54%   |
| 6.4.11  | 20        | 0.42%   |
| 4.4.0   | 18        | 0.38%   |
| 6.4.6   | 16        | 0.33%   |
| 5.6.0   | 16        | 0.33%   |
| 5.16.11 | 16        | 0.33%   |
| 5.17.5  | 15        | 0.31%   |
| 6.3.0   | 14        | 0.29%   |
| 6.2.9   | 14        | 0.29%   |
| 6.0.6   | 14        | 0.29%   |
| 5.9.16  | 14        | 0.29%   |
| 6.5.0   | 12        | 0.25%   |
| 6.3.8   | 12        | 0.25%   |
| 6.0.0   | 12        | 0.25%   |
| 6.0.12  | 11        | 0.23%   |
| 5.3.18  | 11        | 0.23%   |
| 5.18.0  | 11        | 0.23%   |
| 5.17.1  | 11        | 0.23%   |
| 5.17.0  | 10        | 0.21%   |
| 5.16.0  | 10        | 0.21%   |
| 6.2.8   | 9         | 0.19%   |
| 5.9.8   | 9         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 787       | 16.66%  |
| 5.15    | 555       | 11.75%  |
| 5.8     | 336       | 7.11%   |
| 5.11    | 283       | 5.99%   |
| 5.16    | 268       | 5.67%   |
| 5.10    | 251       | 5.31%   |
| 5.13    | 247       | 5.23%   |
| 4.15    | 244       | 5.17%   |
| 6.2     | 202       | 4.28%   |
| 5.19    | 194       | 4.11%   |
| 5.3     | 173       | 3.66%   |
| 6.1     | 160       | 3.39%   |
| 5.0     | 111       | 2.35%   |
| 4.18    | 87        | 1.84%   |
| 6.0     | 85        | 1.8%    |
| 6.4     | 75        | 1.59%   |
| 6.3     | 73        | 1.55%   |
| 5.17    | 69        | 1.46%   |
| 5.14    | 66        | 1.4%    |
| 5.18    | 61        | 1.29%   |
| 5.9     | 56        | 1.19%   |
| 6.5     | 51        | 1.08%   |
| 5.6     | 51        | 1.08%   |
| 4.19    | 50        | 1.06%   |
| 5.12    | 36        | 0.76%   |
| 5.7     | 32        | 0.68%   |
| 5.5     | 28        | 0.59%   |
| 4.9     | 26        | 0.55%   |
| 4.4     | 20        | 0.42%   |
| 5.2     | 9         | 0.19%   |
| 4.16    | 5         | 0.11%   |
| 4.10    | 5         | 0.11%   |
| 4.20    | 4         | 0.08%   |
| 4.14    | 4         | 0.08%   |
| 4.12    | 4         | 0.08%   |
| 6.6     | 3         | 0.06%   |
| 3.10    | 3         | 0.06%   |
| 4.1     | 2         | 0.04%   |
| 3.16    | 2         | 0.04%   |
| 96.5    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4054      | 96.2%   |
| i686    | 104       | 2.47%   |
| aarch64 | 47        | 1.12%   |
| armv7l  | 7         | 0.17%   |
| armv8l  | 1         | 0.02%   |
| armv6l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1944      | 44.39%  |
| KDE5             | 786       | 17.95%  |
| Unknown          | 547       | 12.49%  |
| X-Cinnamon       | 310       | 7.08%   |
| XFCE             | 304       | 6.94%   |
| MATE             | 101       | 2.31%   |
| KDE              | 93        | 2.12%   |
| Cinnamon         | 39        | 0.89%   |
| LXQt             | 31        | 0.71%   |
| Pantheon         | 30        | 0.69%   |
| LXDE             | 29        | 0.66%   |
| Budgie           | 27        | 0.62%   |
| i3               | 26        | 0.59%   |
| Unity            | 23        | 0.53%   |
| KDE4             | 17        | 0.39%   |
| GNOME Flashback  | 14        | 0.32%   |
| Deepin           | 8         | 0.18%   |
| sway             | 7         | 0.16%   |
| openbox          | 7         | 0.16%   |
| icewm            | 5         | 0.11%   |
| Enlightenment    | 5         | 0.11%   |
| qtile            | 4         | 0.09%   |
| awesome          | 4         | 0.09%   |
| lightdm-xsession | 3         | 0.07%   |
| Trinity          | 2         | 0.05%   |
| Hyprland         | 2         | 0.05%   |
| GNOME Classic    | 2         | 0.05%   |
| xmonad           | 1         | 0.02%   |
| LeftWM           | 1         | 0.02%   |
| jwm              | 1         | 0.02%   |
| herbstluftwm     | 1         | 0.02%   |
| fluxbox          | 1         | 0.02%   |
| DWM              | 1         | 0.02%   |
| dusk             | 1         | 0.02%   |
| Core             | 1         | 0.02%   |
| bspwm            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3189      | 73.65%  |
| Wayland | 778       | 17.97%  |
| Unknown | 265       | 6.12%   |
| Tty     | 96        | 2.22%   |
| Web     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2160      | 49.51%  |
| SDDM    | 653       | 14.97%  |
| GDM3    | 522       | 11.96%  |
| GDM     | 491       | 11.25%  |
| LightDM | 404       | 9.26%   |
| TDM     | 94        | 2.15%   |
| KDM     | 16        | 0.37%   |
| XDM     | 8         | 0.18%   |
| SLiM    | 4         | 0.09%   |
| Ly      | 4         | 0.09%   |
| GREETD  | 3         | 0.07%   |
| LXDM    | 2         | 0.05%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 2096      | 48.52%  |
| nl_NL       | 1230      | 28.47%  |
| Unknown     | 434       | 10.05%  |
| en_GB       | 181       | 4.19%   |
| C           | 72        | 1.67%   |
| de_DE       | 47        | 1.09%   |
| pl_PL       | 38        | 0.88%   |
| ru_RU       | 32        | 0.74%   |
| fr_FR       | 16        | 0.37%   |
| en_NL       | 14        | 0.32%   |
| en_IE       | 14        | 0.32%   |
| POSIX       | 13        | 0.3%    |
| it_IT       | 10        | 0.23%   |
| es_ES       | 9         | 0.21%   |
| nl_BE       | 7         | 0.16%   |
| en_IN       | 7         | 0.16%   |
| en_CA       | 7         | 0.16%   |
| fr_BE       | 5         | 0.12%   |
| en_DK       | 5         | 0.12%   |
| en_AG       | 5         | 0.12%   |
| C.UTF8      | 5         | 0.12%   |
| sv_SE       | 4         | 0.09%   |
| sk_SK       | 4         | 0.09%   |
| ru_UA       | 4         | 0.09%   |
| pt_PT       | 4         | 0.09%   |
| es_MX       | 4         | 0.09%   |
| de_AT       | 4         | 0.09%   |
| cs_CZ       | 4         | 0.09%   |
| pt_BR       | 3         | 0.07%   |
| nb_NO       | 3         | 0.07%   |
| hu_HU       | 3         | 0.07%   |
| en_ZA       | 3         | 0.07%   |
| en_US.utf-8 | 3         | 0.07%   |
| en_AU       | 3         | 0.07%   |
| zh_CN       | 2         | 0.05%   |
| uk_UA       | 2         | 0.05%   |
| tr_TR       | 2         | 0.05%   |
| nl_AW       | 2         | 0.05%   |
| en_SG       | 2         | 0.05%   |
| ca_ES       | 2         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2246      | 52.18%  |
| BIOS | 2058      | 47.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3170      | 73.31%  |
| Btrfs   | 416       | 9.62%   |
| Overlay | 375       | 8.67%   |
| Unknown | 126       | 2.91%   |
| Tmpfs   | 112       | 2.59%   |
| Xfs     | 54        | 1.25%   |
| Zfs     | 43        | 0.99%   |
| Ext2    | 10        | 0.23%   |
| F2fs    | 9         | 0.21%   |
| Ext3    | 5         | 0.12%   |
| Aufs    | 3         | 0.07%   |
| Jfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2279      | 52.99%  |
| GPT     | 1662      | 38.64%  |
| MBR     | 360       | 8.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3656      | 85.32%  |
| Yes       | 629       | 14.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3035      | 71.08%  |
| Yes       | 1235      | 28.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 659       | 15.66%  |
| Dell                    | 659       | 15.66%  |
| ASUSTek Computer        | 596       | 14.17%  |
| Lenovo                  | 490       | 11.65%  |
| Acer                    | 255       | 6.06%   |
| Gigabyte Technology     | 238       | 5.66%   |
| MSI                     | 237       | 5.63%   |
| ASRock                  | 170       | 4.04%   |
| Apple                   | 132       | 3.14%   |
| Intel                   | 92        | 2.19%   |
| Medion                  | 68        | 1.62%   |
| Toshiba                 | 58        | 1.38%   |
| Notebook                | 57        | 1.35%   |
| Raspberry Pi Foundation | 45        | 1.07%   |
| Unknown                 | 32        | 0.76%   |
| Packard Bell            | 29        | 0.69%   |
| Samsung Electronics     | 27        | 0.64%   |
| Fujitsu                 | 24        | 0.57%   |
| Valve                   | 21        | 0.5%    |
| Google                  | 20        | 0.48%   |
| Sony                    | 17        | 0.4%    |
| Microsoft               | 16        | 0.38%   |
| HUAWEI                  | 16        | 0.38%   |
| Fujitsu Siemens         | 13        | 0.31%   |
| Foxconn                 | 13        | 0.31%   |
| Alienware               | 10        | 0.24%   |
| Supermicro              | 9         | 0.21%   |
| Pegatron                | 9         | 0.21%   |
| BESSTAR Tech            | 8         | 0.19%   |
| AMI                     | 8         | 0.19%   |
| Biostar                 | 7         | 0.17%   |
| TUXEDO                  | 6         | 0.14%   |
| Timi                    | 6         | 0.14%   |
| Shuttle                 | 6         | 0.14%   |
| Insyde                  | 6         | 0.14%   |
| Chuwi                   | 6         | 0.14%   |
| ZOTAC                   | 5         | 0.12%   |
| System76                | 5         | 0.12%   |
| PC Specialist           | 5         | 0.12%   |
| SLIMBOOK                | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Dell Latitude 3120                    | 56        | 1.33%   |
| Unknown                               | 45        | 1.07%   |
| Dell Latitude 3190 2-in-1             | 41        | 0.97%   |
| Dell Latitude 3310                    | 32        | 0.76%   |
| ASUS All Series                       | 30        | 0.71%   |
| Valve Jupiter                         | 21        | 0.5%    |
| RPi Raspberry Pi                      | 17        | 0.4%    |
| Dell OptiPlex 7010                    | 14        | 0.33%   |
| Dell XPS 15 7590                      | 13        | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.4    | 11        | 0.26%   |
| MSI MS-7C02                           | 11        | 0.26%   |
| HP Notebook                           | 11        | 0.26%   |
| Apple MacBookPro9,2                   | 10        | 0.24%   |
| HP Pavilion dv7                       | 9         | 0.21%   |
| Dell XPS 15 9560                      | 9         | 0.21%   |
| Dell XPS 15 9500                      | 9         | 0.21%   |
| MSI MS-7C37                           | 8         | 0.19%   |
| HP ZBook Studio G5                    | 8         | 0.19%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 8         | 0.19%   |
| HP Pavilion g7                        | 8         | 0.19%   |
| HP Pavilion g6                        | 8         | 0.19%   |
| Dell XPS 13 9310                      | 8         | 0.19%   |
| Dell OptiPlex 3020                    | 8         | 0.19%   |
| Dell Latitude E6410                   | 8         | 0.19%   |
| Dell Latitude 3300                    | 8         | 0.19%   |
| ASRock B450M Pro4                     | 8         | 0.19%   |
| MSI MS-7B86                           | 7         | 0.17%   |
| MSI MS-7817                           | 7         | 0.17%   |
| HP ProBook 6570b                      | 7         | 0.17%   |
| HP Pavilion Laptop 15-cw1xxx          | 7         | 0.17%   |
| HP Pavilion dv6                       | 7         | 0.17%   |
| HP EliteBook 8570w                    | 7         | 0.17%   |
| Dell Latitude 3189                    | 7         | 0.17%   |
| Apple iMac8,1                         | 7         | 0.17%   |
| MSI MS-7B98                           | 6         | 0.14%   |
| MSI MS-7721                           | 6         | 0.14%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 6         | 0.14%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 6         | 0.14%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 6         | 0.14%   |
| Intel NUC8i3BEH                       | 6         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 330       | 7.84%   |
| Lenovo ThinkPad       | 238       | 5.66%   |
| Acer Aspire           | 174       | 4.14%   |
| HP EliteBook          | 113       | 2.69%   |
| Dell XPS              | 110       | 2.61%   |
| HP Pavilion           | 109       | 2.59%   |
| HP Compaq             | 108       | 2.57%   |
| Lenovo IdeaPad        | 85        | 2.02%   |
| HP ProBook            | 75        | 1.78%   |
| Dell OptiPlex         | 69        | 1.64%   |
| ASUS PRIME            | 65        | 1.55%   |
| ASUS ROG              | 59        | 1.4%    |
| Toshiba Satellite     | 53        | 1.26%   |
| Dell Inspiron         | 53        | 1.26%   |
| RPi Raspberry         | 45        | 1.07%   |
| Unknown               | 45        | 1.07%   |
| Dell Precision        | 38        | 0.9%    |
| Lenovo Yoga           | 37        | 0.88%   |
| HP ZBook              | 37        | 0.88%   |
| Lenovo Legion         | 32        | 0.76%   |
| HP ENVY               | 30        | 0.71%   |
| ASUS VivoBook         | 30        | 0.71%   |
| ASUS All              | 30        | 0.71%   |
| HP Laptop             | 24        | 0.57%   |
| Gigabyte X570         | 24        | 0.57%   |
| ASUS TUF              | 24        | 0.57%   |
| Packard Bell EasyNote | 22        | 0.52%   |
| Valve Jupiter         | 21        | 0.5%    |
| Lenovo ThinkCentre    | 18        | 0.43%   |
| Lenovo ThinkBook      | 18        | 0.43%   |
| ASUS ZenBook          | 17        | 0.4%    |
| Microsoft Surface     | 16        | 0.38%   |
| HP ProDesk            | 16        | 0.38%   |
| Acer TravelMate       | 16        | 0.38%   |
| HP EliteDesk          | 15        | 0.36%   |
| Acer Swift            | 15        | 0.36%   |
| HP Spectre            | 14        | 0.33%   |
| Fujitsu LIFEBOOK      | 14        | 0.33%   |
| ASRock B450M          | 13        | 0.31%   |
| Gigabyte B550         | 12        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 474       | 11.27%  |
| 2018    | 365       | 8.68%   |
| 2020    | 339       | 8.06%   |
| 2021    | 322       | 7.65%   |
| 2012    | 314       | 7.46%   |
| 2011    | 273       | 6.49%   |
| 2013    | 271       | 6.44%   |
| 2017    | 253       | 6.01%   |
| 2014    | 229       | 5.44%   |
| 2010    | 212       | 5.04%   |
| 2015    | 205       | 4.87%   |
| 2016    | 195       | 4.64%   |
| 2022    | 161       | 3.83%   |
| 2009    | 160       | 3.8%    |
| 2008    | 160       | 3.8%    |
| 2007    | 119       | 2.83%   |
| 2006    | 50        | 1.19%   |
| Unknown | 50        | 1.19%   |
| 2023    | 31        | 0.74%   |
| 2005    | 13        | 0.31%   |
| 2004    | 7         | 0.17%   |
| 2003    | 3         | 0.07%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2235      | 53.13%  |
| Desktop        | 1477      | 35.11%  |
| Convertible    | 210       | 4.99%   |
| Mini pc        | 103       | 2.45%   |
| All in one     | 58        | 1.38%   |
| System on chip | 52        | 1.24%   |
| Tablet         | 43        | 1.02%   |
| Server         | 27        | 0.64%   |
| Phone          | 2         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3893      | 91.84%  |
| Enabled  | 346       | 8.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4180      | 99.36%  |
| Yes  | 27        | 0.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 964       | 22.54%  |
| 16.01-24.0      | 888       | 20.76%  |
| 3.01-4.0        | 764       | 17.86%  |
| 8.01-16.0       | 738       | 17.26%  |
| 32.01-64.0      | 452       | 10.57%  |
| 1.01-2.0        | 154       | 3.6%    |
| 64.01-256.0     | 119       | 2.78%   |
| 24.01-32.0      | 84        | 1.96%   |
| 2.01-3.0        | 75        | 1.75%   |
| 0.51-1.0        | 36        | 0.84%   |
| More than 256.0 | 2         | 0.05%   |
| 0.01-0.5        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1654      | 35.56%  |
| 2.01-3.0    | 1100      | 23.65%  |
| 4.01-8.0    | 667       | 14.34%  |
| 3.01-4.0    | 603       | 12.96%  |
| 0.51-1.0    | 288       | 6.19%   |
| 8.01-16.0   | 235       | 5.05%   |
| 16.01-24.0  | 43        | 0.92%   |
| 0.01-0.5    | 43        | 0.92%   |
| 32.01-64.0  | 13        | 0.28%   |
| 24.01-32.0  | 4         | 0.09%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2545      | 58.98%  |
| 2       | 1058      | 24.52%  |
| 3       | 331       | 7.67%   |
| 4       | 164       | 3.8%    |
| 5       | 86        | 1.99%   |
| 0       | 54        | 1.25%   |
| 6       | 34        | 0.79%   |
| 7       | 25        | 0.58%   |
| 8       | 7         | 0.16%   |
| 9       | 4         | 0.09%   |
| Unknown | 4         | 0.09%   |
| 28      | 1         | 0.02%   |
| 27      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2708      | 63.85%  |
| Yes       | 1533      | 36.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3505      | 83.06%  |
| No        | 715       | 16.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3132      | 74.11%  |
| No        | 1094      | 25.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2567      | 60.02%  |
| No        | 1710      | 39.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 4207      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 793       | 17.67%  |
| The Hague              | 217       | 4.84%   |
| Rotterdam              | 156       | 3.48%   |
| Schagen                | 142       | 3.16%   |
| Utrecht                | 111       | 2.47%   |
| Delft                  | 96        | 2.14%   |
| Haarlem                | 85        | 1.89%   |
| Groningen              | 75        | 1.67%   |
| Almere Stad            | 69        | 1.54%   |
| Naaldwijk              | 67        | 1.49%   |
| Eindhoven              | 64        | 1.43%   |
| Amersfoort             | 50        | 1.11%   |
| Enschede               | 49        | 1.09%   |
| Tilburg                | 48        | 1.07%   |
| Leiden                 | 44        | 0.98%   |
| Nijmegen               | 37        | 0.82%   |
| Zoetermeer             | 35        | 0.78%   |
| Arnhem                 | 35        | 0.78%   |
| Apeldoorn              | 33        | 0.74%   |
| Almelo                 | 32        | 0.71%   |
| Breda                  | 31        | 0.69%   |
| Roosendaal             | 26        | 0.58%   |
| Zwolle                 | 25        | 0.56%   |
| Zeist                  | 25        | 0.56%   |
| Hilversum              | 25        | 0.56%   |
| Capelle aan den IJssel | 25        | 0.56%   |
| Maastricht             | 24        | 0.53%   |
| Lelystad               | 24        | 0.53%   |
| Assen                  | 24        | 0.53%   |
| Amstelveen             | 24        | 0.53%   |
| Heerlen                | 23        | 0.51%   |
| Dordrecht              | 23        | 0.51%   |
| Purmerend              | 21        | 0.47%   |
| Gouda                  | 21        | 0.47%   |
| Alkmaar                | 21        | 0.47%   |
| 's-Hertogenbosch       | 21        | 0.47%   |
| Schiedam               | 19        | 0.42%   |
| Leeuwarden             | 19        | 0.42%   |
| Hoofddorp              | 19        | 0.42%   |
| Meppel                 | 17        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1396      | 2265   | 22.98%  |
| WDC                         | 778       | 1207   | 12.81%  |
| Seagate                     | 714       | 1126   | 11.75%  |
| Kingston                    | 370       | 487    | 6.09%   |
| Toshiba                     | 327       | 452    | 5.38%   |
| SanDisk                     | 287       | 381    | 4.72%   |
| Crucial                     | 264       | 347    | 4.35%   |
| Unknown                     | 262       | 327    | 4.31%   |
| SK hynix                    | 218       | 261    | 3.59%   |
| Intel                       | 190       | 250    | 3.13%   |
| Hitachi                     | 175       | 225    | 2.88%   |
| HGST                        | 100       | 124    | 1.65%   |
| Micron Technology           | 84        | 102    | 1.38%   |
| A-DATA Technology           | 67        | 74     | 1.1%    |
| KIOXIA                      | 57        | 71     | 0.94%   |
| Apple                       | 56        | 79     | 0.92%   |
| LITEON                      | 43        | 54     | 0.71%   |
| Maxtor                      | 33        | 45     | 0.54%   |
| OCZ                         | 32        | 40     | 0.53%   |
| China                       | 32        | 45     | 0.53%   |
| Phison                      | 28        | 42     | 0.46%   |
| Corsair                     | 27        | 36     | 0.44%   |
| PNY                         | 26        | 32     | 0.43%   |
| LITEONIT                    | 26        | 29     | 0.43%   |
| Transcend                   | 23        | 28     | 0.38%   |
| Kingston Technology Company | 23        | 26     | 0.38%   |
| Fujitsu                     | 23        | 26     | 0.38%   |
| Intenso                     | 22        | 22     | 0.36%   |
| Micron/Crucial Technology   | 21        | 26     | 0.35%   |
| SSSTC                       | 20        | 22     | 0.33%   |
| Gigabyte Technology         | 18        | 23     | 0.3%    |
| Unknown                     | 18        | 21     | 0.3%    |
| JMicron Technology          | 17        | 24     | 0.28%   |
| GOODRAM                     | 17        | 19     | 0.28%   |
| ASMT                        | 17        | 20     | 0.28%   |
| SPCC                        | 16        | 19     | 0.26%   |
| Phison Electronics          | 16        | 22     | 0.26%   |
| Patriot                     | 14        | 18     | 0.23%   |
| KingFast                    | 14        | 18     | 0.23%   |
| Silicon Motion              | 10        | 11     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                          | 99        | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 74        | 1.08%   |
| Samsung SSD 850 EVO 500GB                          | 71        | 1.04%   |
| Samsung SSD 860 EVO 500GB                          | 69        | 1.01%   |
| Kingston SA400S37240G 240GB SSD                    | 52        | 0.76%   |
| Samsung NVMe SSD Drive 500GB                       | 47        | 0.69%   |
| Samsung NVMe SSD Drive 1TB                         | 46        | 0.67%   |
| Unknown MMC Card  32GB                             | 45        | 0.66%   |
| Samsung SSD 840 EVO 250GB                          | 43        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 43        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                    | 42        | 0.62%   |
| Samsung SSD 860 EVO 1TB                            | 39        | 0.57%   |
| Unknown MMC Card  64GB                             | 38        | 0.56%   |
| Samsung SSD 980 1TB                                | 37        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                       | 37        | 0.54%   |
| Kingston SV300S37A120G 120GB SSD                   | 36        | 0.53%   |
| Samsung SSD 840 EVO 120GB                          | 35        | 0.51%   |
| Seagate Expansion 1TB                              | 34        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                    | 32        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                     | 31        | 0.45%   |
| Samsung SSD 970 EVO 1TB                            | 31        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB                     | 28        | 0.41%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 28        | 0.41%   |
| HGST HTS721010A9E630 1TB                           | 28        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                        | 27        | 0.4%    |
| Toshiba DT01ACA100 1TB                             | 26        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                       | 26        | 0.38%   |
| Samsung NVMe SSD Drive 512GB                       | 25        | 0.37%   |
| Samsung SSD 860 QVO 1TB                            | 24        | 0.35%   |
| Toshiba MQ01ABF050 500GB                           | 23        | 0.34%   |
| Samsung SSD 870 QVO 1TB                            | 23        | 0.34%   |
| SK hynix BC711 NVMe 128GB                          | 22        | 0.32%   |
| Seagate ST9500325AS 500GB                          | 22        | 0.32%   |
| Samsung NVMe SSD Drive 1024GB                      | 22        | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB                       | 21        | 0.31%   |
| Toshiba MQ01ABD100 1TB                             | 20        | 0.29%   |
| Seagate ST1000DM010-2EP102 1TB                     | 20        | 0.29%   |
| SanDisk NVMe SSD Drive 512GB                       | 20        | 0.29%   |
| Samsung SSD 860 EVO 250GB                          | 20        | 0.29%   |
| Kingston SA400S37480G 480GB SSD                    | 20        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 700       | 1102   | 33.62%  |
| WDC                 | 631       | 989    | 30.31%  |
| Toshiba             | 221       | 316    | 10.61%  |
| Hitachi             | 175       | 225    | 8.41%   |
| Samsung Electronics | 143       | 226    | 6.87%   |
| HGST                | 100       | 124    | 4.8%    |
| Maxtor              | 33        | 45     | 1.59%   |
| Fujitsu             | 23        | 26     | 1.1%    |
| Unknown             | 12        | 19     | 0.58%   |
| Apple               | 12        | 16     | 0.58%   |
| Intenso             | 4         | 4      | 0.19%   |
| JMicron Technology  | 3         | 6      | 0.14%   |
| HGST HTS            | 3         | 4      | 0.14%   |
| ASMT                | 3         | 6      | 0.14%   |
| SAGE                | 2         | 2      | 0.1%    |
| IBM/Hitachi         | 2         | 2      | 0.1%    |
| Hewlett-Packard     | 2         | 2      | 0.1%    |
| External            | 2         | 4      | 0.1%    |
| ExcelStor           | 2         | 2      | 0.1%    |
| Synology            | 1         | 1      | 0.05%   |
| SSK                 | 1         | 1      | 0.05%   |
| QNAP                | 1         | 1      | 0.05%   |
| NAS                 | 1         | 10     | 0.05%   |
| Maxtor 6            | 1         | 2      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LIO-ORG             | 1         | 4      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 727       | 1089   | 33.6%   |
| Kingston            | 275       | 353    | 12.71%  |
| Crucial             | 252       | 335    | 11.65%  |
| SanDisk             | 169       | 211    | 7.81%   |
| WDC                 | 81        | 117    | 3.74%   |
| Intel               | 75        | 92     | 3.47%   |
| SK hynix            | 54        | 70     | 2.5%    |
| A-DATA Technology   | 54        | 61     | 2.5%    |
| Micron Technology   | 39        | 51     | 1.8%    |
| LITEON              | 35        | 46     | 1.62%   |
| OCZ                 | 32        | 40     | 1.48%   |
| China               | 32        | 45     | 1.48%   |
| Apple               | 32        | 41     | 1.48%   |
| Toshiba             | 28        | 36     | 1.29%   |
| PNY                 | 26        | 32     | 1.2%    |
| LITEONIT            | 26        | 29     | 1.2%    |
| Corsair             | 20        | 28     | 0.92%   |
| Transcend           | 19        | 24     | 0.88%   |
| GOODRAM             | 17        | 19     | 0.79%   |
| SPCC                | 16        | 19     | 0.74%   |
| Patriot             | 14        | 18     | 0.65%   |
| Intenso             | 14        | 14     | 0.65%   |
| ASMT                | 13        | 13     | 0.6%    |
| KingSpec            | 7         | 9      | 0.32%   |
| Gigabyte Technology | 6         | 10     | 0.28%   |
| Netac               | 5         | 5      | 0.23%   |
| Mushkin             | 5         | 7      | 0.23%   |
| KingFast            | 5         | 6      | 0.23%   |
| Apacer              | 5         | 5      | 0.23%   |
| Unknown             | 5         | 8      | 0.23%   |
| ACASIS              | 4         | 4      | 0.18%   |
| Unknown             | 3         | 3      | 0.14%   |
| Team                | 3         | 5      | 0.14%   |
| SSSTC               | 3         | 3      | 0.14%   |
| Plextor             | 3         | 4      | 0.14%   |
| Phison              | 3         | 7      | 0.14%   |
| Leven               | 3         | 3      | 0.14%   |
| KingDian            | 3         | 4      | 0.14%   |
| ASMedia             | 3         | 5      | 0.14%   |
| Vaseky              | 2         | 2      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1898      | 2925   | 34.58%  |
| HDD     | 1720      | 3142   | 31.34%  |
| NVMe    | 1545      | 2216   | 28.15%  |
| MMC     | 259       | 312    | 4.72%   |
| Unknown | 67        | 85     | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2893      | 5769   | 58.53%  |
| NVMe | 1539      | 2203   | 31.13%  |
| MMC  | 259       | 312    | 5.24%   |
| SAS  | 252       | 396    | 5.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2339      | 3688   | 61.34%  |
| 0.51-1.0   | 949       | 1429   | 24.89%  |
| 1.01-2.0   | 285       | 469    | 7.47%   |
| 3.01-4.0   | 90        | 194    | 2.36%   |
| 2.01-3.0   | 80        | 121    | 2.1%    |
| 4.01-10.0  | 63        | 147    | 1.65%   |
| 10.01-20.0 | 6         | 18     | 0.16%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1162      | 26.05%  |
| 251-500        | 874       | 19.59%  |
| 501-1000       | 591       | 13.25%  |
| 1-20           | 450       | 10.09%  |
| 1001-2000      | 388       | 8.7%    |
| 51-100         | 290       | 6.5%    |
| More than 3000 | 256       | 5.74%   |
| 21-50          | 190       | 4.26%   |
| 2001-3000      | 134       | 3%      |
| Unknown        | 126       | 2.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1810      | 39.25%  |
| 21-50          | 712       | 15.44%  |
| 101-250        | 542       | 11.75%  |
| 51-100         | 488       | 10.58%  |
| 251-500        | 344       | 7.46%   |
| 501-1000       | 280       | 6.07%   |
| 1001-2000      | 146       | 3.17%   |
| Unknown        | 126       | 2.73%   |
| More than 3000 | 106       | 2.3%    |
| 2001-3000      | 55        | 1.19%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD      | 5         | 6      | 1.84%   |
| HGST HTS721010A9E630 1TB              | 5         | 6      | 1.84%   |
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.47%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 1.47%   |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.1%    |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.1%    |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.1%    |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 1.1%    |
| Kingston SA400S37120G 120GB SSD       | 3         | 4      | 1.1%    |
| Intel SSDSC2BW120A4 120GB             | 3         | 4      | 1.1%    |
| Intel SSDSA2M080G2GC 80GB             | 3         | 4      | 1.1%    |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.1%    |
| Crucial CT128MX100SSD1 128GB          | 3         | 3      | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.74%   |
| WDC WD60EFRX-68MYMN1 6TB              | 2         | 2      | 0.74%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2         | 2      | 0.74%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 3      | 0.74%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 2         | 2      | 0.74%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.74%   |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 0.74%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.74%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.74%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.74%   |
| Seagate ST380011A 80GB                | 2         | 2      | 0.74%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.74%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 0.74%   |
| Seagate ST1000DM003-1ER162 1TB        | 2         | 2      | 0.74%   |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 0.74%   |
| Samsung Electronics HD753LJ 752GB     | 2         | 2      | 0.74%   |
| Samsung Electronics HD103UJ 1TB       | 2         | 2      | 0.74%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.74%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 0.74%   |
| Intel SSDMAEXC024G3H 24GB             | 2         | 2      | 0.74%   |
| Hitachi HTS725050A7E630 500GB         | 2         | 3      | 0.74%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 3      | 0.74%   |
| Fujitsu MHZ2320BH G2 320GB            | 2         | 2      | 0.74%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.74%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.37%   |
| WDC WD800JD-00HKA0 80GB               | 1         | 1      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 63        | 77     | 23.51%  |
| Seagate                     | 49        | 64     | 18.28%  |
| Samsung Electronics         | 19        | 23     | 7.09%   |
| Intel                       | 19        | 24     | 7.09%   |
| Kingston                    | 17        | 19     | 6.34%   |
| Hitachi                     | 16        | 18     | 5.97%   |
| Toshiba                     | 13        | 14     | 4.85%   |
| HGST                        | 12        | 14     | 4.48%   |
| Crucial                     | 12        | 21     | 4.48%   |
| SanDisk                     | 8         | 8      | 2.99%   |
| SK hynix                    | 7         | 7      | 2.61%   |
| Micron Technology           | 4         | 4      | 1.49%   |
| Maxtor                      | 4         | 6      | 1.49%   |
| Fujitsu                     | 4         | 4      | 1.49%   |
| LITEON                      | 3         | 6      | 1.12%   |
| A-DATA Technology           | 3         | 3      | 1.12%   |
| OCZ                         | 2         | 2      | 0.75%   |
| LITEONIT                    | 2         | 2      | 0.75%   |
| Corsair                     | 2         | 4      | 0.75%   |
| Realtek                     | 1         | 1      | 0.37%   |
| PNY                         | 1         | 1      | 0.37%   |
| Patriot                     | 1         | 1      | 0.37%   |
| Kingston Technology Company | 1         | 1      | 0.37%   |
| Intenso                     | 1         | 1      | 0.37%   |
| GOODRAM                     | 1         | 1      | 0.37%   |
| C-Series                    | 1         | 1      | 0.37%   |
| Apple                       | 1         | 1      | 0.37%   |
| Anobit                      | 1         | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 60        | 74     | 35.93%  |
| Seagate             | 49        | 64     | 29.34%  |
| Hitachi             | 16        | 18     | 9.58%   |
| Toshiba             | 12        | 13     | 7.19%   |
| HGST                | 12        | 14     | 7.19%   |
| Samsung Electronics | 9         | 9      | 5.39%   |
| Maxtor              | 4         | 6      | 2.4%    |
| Fujitsu             | 4         | 4      | 2.4%    |
| Apple               | 1         | 1      | 0.6%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 157       | 203    | 61.09%  |
| SSD  | 88        | 108    | 34.24%  |
| NVMe | 12        | 18     | 4.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 11.11%  |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 11.11%  |
| Toshiba HDWG180 8TB               | 1         | 4      | 11.11%  |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 11.11%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 11.11%  |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 11.11%  |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 11.11%  |
| Apple SSD TS256C 256GB            | 1         | 1      | 11.11%  |
| Apple HDD HTS541010A9E662 1TB     | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| Apple               | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Seagate             | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2670      | 5618   | 59.4%   |
| Works    | 1570      | 2721   | 34.93%  |
| Malfunc  | 246       | 329    | 5.47%   |
| Failed   | 9         | 12     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2730      | 51.39%  |
| Samsung Electronics                     | 684       | 12.88%  |
| AMD                                     | 673       | 12.67%  |
| SanDisk                                 | 190       | 3.58%   |
| SK hynix                                | 162       | 3.05%   |
| Kingston Technology Company             | 116       | 2.18%   |
| Toshiba America Info Systems            | 90        | 1.69%   |
| ASMedia Technology                      | 83        | 1.56%   |
| JMicron Technology                      | 67        | 1.26%   |
| Nvidia                                  | 61        | 1.15%   |
| Phison Electronics                      | 60        | 1.13%   |
| Marvell Technology Group                | 58        | 1.09%   |
| KIOXIA                                  | 57        | 1.07%   |
| Micron Technology                       | 46        | 0.87%   |
| Micron/Crucial Technology               | 31        | 0.58%   |
| Solid State Storage Technology          | 20        | 0.38%   |
| Silicon Motion                          | 17        | 0.32%   |
| ADATA Technology                        | 17        | 0.32%   |
| VIA Technologies                        | 15        | 0.28%   |
| Silicon Integrated Systems [SiS]        | 15        | 0.28%   |
| Seagate Technology                      | 13        | 0.24%   |
| Apple                                   | 13        | 0.24%   |
| Lite-On Technology                      | 11        | 0.21%   |
| Broadcom / LSI                          | 11        | 0.21%   |
| LSI Logic / Symbios Logic               | 9         | 0.17%   |
| Silicon Image                           | 8         | 0.15%   |
| Realtek Semiconductor                   | 8         | 0.15%   |
| Union Memory (Shenzhen)                 | 7         | 0.13%   |
| O2 Micro                                | 6         | 0.11%   |
| Hewlett-Packard                         | 5         | 0.09%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.08%   |
| Adaptec                                 | 4         | 0.08%   |
| Integrated Technology Express           | 3         | 0.06%   |
| ULi Electronics                         | 2         | 0.04%   |
| Transcend                               | 2         | 0.04%   |
| Shenzhen Unionmemory Information System | 2         | 0.04%   |
| Shenzhen Longsys Electronics            | 2         | 0.04%   |
| Promise Technology                      | 2         | 0.04%   |
| INNOGRIT                                | 2         | 0.04%   |
| HighPoint Technologies                  | 2         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 436       | 7.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 333       | 5.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 189       | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 188       | 3.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 181       | 2.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 159       | 2.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 158       | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 116       | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 105       | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 96        | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 93        | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 87        | 1.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 85        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 81        | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 80        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 79        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 77        | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 75        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 74        | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 73        | 1.19%   |
| Intel SATA Controller [RAID mode]                                              | 71        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 69        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 69        | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 69        | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 66        | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 65        | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 62        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 62        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 60        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 59        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 58        | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 55        | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 53        | 0.87%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 52        | 0.85%   |
| Intel SSD 660P Series                                                          | 52        | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 50        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 49        | 0.8%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 47        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 46        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 45        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2822      | 52.64%  |
| NVMe | 1547      | 28.86%  |
| IDE  | 594       | 11.08%  |
| RAID | 380       | 7.09%   |
| SAS  | 11        | 0.21%   |
| SCSI | 7         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3275      | 77.85%  |
| AMD          | 874       | 20.77%  |
| ARM          | 55        | 1.31%   |
| CentaurHauls | 2         | 0.05%   |
| QUALCOMM     | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 58        | 1.38%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 48        | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 45        | 1.07%   |
| ARM Processor                                 | 43        | 1.02%   |
| AMD Ryzen 5 3600 6-Core Processor             | 42        | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 40        | 0.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 38        | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 36        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 35        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 33        | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 33        | 0.78%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 30        | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 28        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 28        | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 28        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 0.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 25        | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 25        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 23        | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 22        | 0.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 21        | 0.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 21        | 0.5%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 21        | 0.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 21        | 0.5%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.5%    |
| AMD Custom APU 0405                           | 21        | 0.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 20        | 0.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 20        | 0.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 20        | 0.47%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 19        | 0.45%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 19        | 0.45%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 19        | 0.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 18        | 0.43%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 18        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 904       | 21.46%  |
| Intel Core i7           | 825       | 19.59%  |
| Other                   | 327       | 7.76%   |
| Intel Core i3           | 306       | 7.26%   |
| AMD Ryzen 5             | 211       | 5.01%   |
| AMD Ryzen 7             | 207       | 4.91%   |
| Intel Core 2 Duo        | 177       | 4.2%    |
| Intel Celeron           | 153       | 3.63%   |
| Intel Pentium Silver    | 107       | 2.54%   |
| Intel Atom              | 96        | 2.28%   |
| Intel Pentium           | 92        | 2.18%   |
| Intel Xeon              | 89        | 2.11%   |
| AMD Ryzen 9             | 70        | 1.66%   |
| Intel Pentium Dual-Core | 59        | 1.4%    |
| Intel Core 2 Quad       | 46        | 1.09%   |
| AMD FX                  | 41        | 0.97%   |
| Intel Core i9           | 37        | 0.88%   |
| Intel Core 2            | 29        | 0.69%   |
| AMD Ryzen 7 PRO         | 28        | 0.66%   |
| AMD A6                  | 28        | 0.66%   |
| Intel Pentium Dual      | 26        | 0.62%   |
| Intel Genuine           | 23        | 0.55%   |
| AMD A8                  | 22        | 0.52%   |
| AMD Ryzen 5 PRO         | 20        | 0.47%   |
| AMD Athlon 64 X2        | 20        | 0.47%   |
| AMD Ryzen 3             | 19        | 0.45%   |
| AMD Phenom II X4        | 17        | 0.4%    |
| AMD A4                  | 16        | 0.38%   |
| AMD A10                 | 16        | 0.38%   |
| Intel Pentium 4         | 15        | 0.36%   |
| Intel Pentium D         | 13        | 0.31%   |
| AMD E                   | 13        | 0.31%   |
| AMD Athlon II X2        | 13        | 0.31%   |
| ARM BCM                 | 11        | 0.26%   |
| AMD E1                  | 10        | 0.24%   |
| AMD Ryzen Threadripper  | 8         | 0.19%   |
| AMD Athlon II X4        | 8         | 0.19%   |
| AMD Athlon              | 8         | 0.19%   |
| Intel Core m3           | 7         | 0.17%   |
| AMD Phenom II X6        | 7         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1653      | 39.22%  |
| 2       | 1519      | 36.04%  |
| 6       | 412       | 9.77%   |
| 8       | 324       | 7.69%   |
| 1       | 94        | 2.23%   |
| 12      | 77        | 1.83%   |
| 10      | 45        | 1.07%   |
| 16      | 29        | 0.69%   |
| 14      | 26        | 0.62%   |
| 24      | 11        | 0.26%   |
| 3       | 11        | 0.26%   |
| Unknown | 10        | 0.24%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 32      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4167      | 99.05%  |
| 2       | 30        | 0.71%   |
| Unknown | 8         | 0.19%   |
| 4       | 1         | 0.02%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2735      | 64.95%  |
| 1       | 1463      | 34.74%  |
| Unknown | 10        | 0.24%   |
| 16      | 1         | 0.02%   |
| 8       | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4086      | 96.89%  |
| Unknown        | 95        | 2.25%   |
| 32-bit         | 31        | 0.74%   |
| 64-bit         | 5         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1236      | 28.28%  |
| 0x306a9    | 215       | 4.92%   |
| 0x206a7    | 205       | 4.69%   |
| 0x306c3    | 171       | 3.91%   |
| 0x1067a    | 143       | 3.27%   |
| 0x806ec    | 125       | 2.86%   |
| 0x906ea    | 115       | 2.63%   |
| 0x806c1    | 81        | 1.85%   |
| 0x806ea    | 79        | 1.81%   |
| 0x406e3    | 78        | 1.78%   |
| 0x506e3    | 75        | 1.72%   |
| 0x40651    | 72        | 1.65%   |
| 0x20655    | 71        | 1.62%   |
| 0x806e9    | 68        | 1.56%   |
| 0x906e9    | 65        | 1.49%   |
| 0x906c0    | 59        | 1.35%   |
| 0x6fd      | 59        | 1.35%   |
| 0x08701021 | 58        | 1.33%   |
| 0x306d4    | 50        | 1.14%   |
| 0x0a50000c | 44        | 1.01%   |
| 0x08600106 | 42        | 0.96%   |
| 0x706a8    | 41        | 0.94%   |
| 0x30678    | 41        | 0.94%   |
| 0x6fb      | 35        | 0.8%    |
| 0x08701013 | 34        | 0.78%   |
| 0x010000c8 | 33        | 0.76%   |
| 0x806eb    | 32        | 0.73%   |
| 0x10676    | 29        | 0.66%   |
| 0xa0652    | 28        | 0.64%   |
| 0x0800820d | 28        | 0.64%   |
| 0x906ed    | 27        | 0.62%   |
| 0x706e5    | 27        | 0.62%   |
| 0x706a1    | 27        | 0.62%   |
| 0x106e5    | 27        | 0.62%   |
| 0x406c4    | 26        | 0.59%   |
| 0x20652    | 26        | 0.59%   |
| 0x08108109 | 25        | 0.57%   |
| 0x08108102 | 24        | 0.55%   |
| 0x06001119 | 24        | 0.55%   |
| 0x06000852 | 24        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 717       | 17%     |
| Haswell          | 354       | 8.39%   |
| IvyBridge        | 297       | 7.04%   |
| SandyBridge      | 279       | 6.62%   |
| Skylake          | 223       | 5.29%   |
| Penryn           | 220       | 5.22%   |
| Zen 2            | 212       | 5.03%   |
| Unknown          | 196       | 4.65%   |
| Core             | 154       | 3.65%   |
| Zen 3            | 142       | 3.37%   |
| Westmere         | 142       | 3.37%   |
| Silvermont       | 135       | 3.2%    |
| TigerLake        | 119       | 2.82%   |
| Zen+             | 101       | 2.4%    |
| Broadwell        | 84        | 1.99%   |
| Goldmont plus    | 77        | 1.83%   |
| CometLake        | 75        | 1.78%   |
| Alderlake Hybrid | 72        | 1.71%   |
| Piledriver       | 64        | 1.52%   |
| Nehalem          | 64        | 1.52%   |
| K10              | 61        | 1.45%   |
| Zen              | 58        | 1.38%   |
| IceLake          | 54        | 1.28%   |
| Tremont          | 53        | 1.26%   |
| K8 Hammer        | 37        | 0.88%   |
| Goldmont         | 35        | 0.83%   |
| NetBurst         | 32        | 0.76%   |
| Excavator        | 26        | 0.62%   |
| Bonnell          | 21        | 0.5%    |
| Bobcat           | 21        | 0.5%    |
| K10 Llano        | 18        | 0.43%   |
| P6               | 17        | 0.4%    |
| Jaguar           | 16        | 0.38%   |
| Steamroller      | 13        | 0.31%   |
| Puma             | 10        | 0.24%   |
| K8 & K10 hybrid  | 9         | 0.21%   |
| Bulldozer        | 7         | 0.17%   |
| Gracemont        | 1         | 0.02%   |
| CannonLake       | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2472      | 50.51%  |
| Nvidia                           | 1358      | 27.75%  |
| AMD                              | 1020      | 20.84%  |
| Matrox Electronics Systems       | 17        | 0.35%   |
| ASPEED Technology                | 11        | 0.22%   |
| Silicon Integrated Systems [SiS] | 8         | 0.16%   |
| VIA Technologies                 | 7         | 0.14%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 202       | 4.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 171       | 3.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 127       | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 118       | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 110       | 2.19%   |
| Intel UHD Graphics 620                                                                   | 94        | 1.87%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 84        | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 83        | 1.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 82        | 1.63%   |
| Intel HD Graphics 620                                                                    | 77        | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 77        | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 76        | 1.51%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 71        | 1.41%   |
| Intel HD Graphics 630                                                                    | 68        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 67        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 67        | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 66        | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 1.31%   |
| Intel JasperLake [UHD Graphics]                                                          | 65        | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 64        | 1.27%   |
| Intel HD Graphics 530                                                                    | 61        | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 60        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 54        | 1.07%   |
| Intel HD Graphics 5500                                                                   | 50        | 1%      |
| Intel GeminiLake [UHD Graphics 605]                                                      | 49        | 0.98%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 48        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 47        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 42        | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 41        | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 41        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 36        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 33        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 31        | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 31        | 0.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 31        | 0.62%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 31        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 30        | 0.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 26        | 0.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 25        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1808      | 42.63%  |
| 1 x AMD                  | 837       | 19.74%  |
| 1 x Nvidia               | 762       | 17.97%  |
| Intel + Nvidia           | 525       | 12.38%  |
| Intel + AMD              | 75        | 1.77%   |
| Other                    | 62        | 1.46%   |
| AMD + Nvidia             | 56        | 1.32%   |
| 2 x AMD                  | 50        | 1.18%   |
| 1 x Matrox               | 14        | 0.33%   |
| 2 x Nvidia               | 12        | 0.28%   |
| 2 x Intel                | 8         | 0.19%   |
| 1 x SiS                  | 8         | 0.19%   |
| 1 x VIA                  | 7         | 0.17%   |
| 1 x ASPEED               | 6         | 0.14%   |
| Nvidia + ASPEED          | 4         | 0.09%   |
| Nvidia + Matrox          | 2         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.05%   |
| Intel + 2 x AMD          | 1         | 0.02%   |
| AMD + Matrox             | 1         | 0.02%   |
| AMD + ASPEED             | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3354      | 78.33%  |
| Proprietary | 733       | 17.12%  |
| Unknown     | 195       | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2545      | 58.82%  |
| 1.01-2.0   | 445       | 10.28%  |
| 0.01-0.5   | 418       | 9.66%   |
| 0.51-1.0   | 301       | 6.96%   |
| 3.01-4.0   | 274       | 6.33%   |
| 7.01-8.0   | 182       | 4.21%   |
| 5.01-6.0   | 84        | 1.94%   |
| 8.01-16.0  | 43        | 0.99%   |
| 2.01-3.0   | 27        | 0.62%   |
| 16.01-24.0 | 8         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 596       | 12.9%   |
| Samsung Electronics     | 576       | 12.46%  |
| LG Display              | 379       | 8.2%    |
| BOE                     | 357       | 7.73%   |
| Chimei Innolux          | 314       | 6.8%    |
| Dell                    | 254       | 5.5%    |
| Goldstar                | 214       | 4.63%   |
| Iiyama                  | 207       | 4.48%   |
| Philips                 | 200       | 4.33%   |
| Hewlett-Packard         | 163       | 3.53%   |
| Acer                    | 145       | 3.14%   |
| Apple                   | 117       | 2.53%   |
| Sharp                   | 105       | 2.27%   |
| AOC                     | 103       | 2.23%   |
| BenQ                    | 88        | 1.9%    |
| Chi Mei Optoelectronics | 60        | 1.3%    |
| Ancor Communications    | 60        | 1.3%    |
| Lenovo                  | 54        | 1.17%   |
| LG Philips              | 36        | 0.78%   |
| Sony                    | 35        | 0.76%   |
| Medion                  | 32        | 0.69%   |
| InfoVision              | 31        | 0.67%   |
| Idek Iiyama             | 29        | 0.63%   |
| Eizo                    | 23        | 0.5%    |
| PANDA                   | 22        | 0.48%   |
| LG Electronics          | 22        | 0.48%   |
| ASUSTek Computer        | 22        | 0.48%   |
| CSO                     | 21        | 0.45%   |
| MSI                     | 20        | 0.43%   |
| Valve                   | 17        | 0.37%   |
| Unknown                 | 17        | 0.37%   |
| Panasonic               | 15        | 0.32%   |
| Gigabyte Technology     | 14        | 0.3%    |
| Fujitsu Siemens         | 13        | 0.28%   |
| ViewSonic               | 12        | 0.26%   |
| Vestel Elektronik       | 11        | 0.24%   |
| Packard Bell            | 11        | 0.24%   |
| NEC Computers           | 11        | 0.24%   |
| Toshiba                 | 10        | 0.22%   |
| HannStar                | 10        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 33        | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 26        | 0.54%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 23        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 20        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 18        | 0.37%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch               | 18        | 0.37%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 18        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 18        | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 18        | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 16        | 0.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 14        | 0.29%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 13        | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 12        | 0.25%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 11        | 0.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 11        | 0.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 10        | 0.21%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 10        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 10        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 9         | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 9         | 0.19%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.19%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 9         | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.19%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                          | 9         | 0.19%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.17%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                      | 8         | 0.17%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch          | 8         | 0.17%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                      | 8         | 0.17%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.17%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 8         | 0.17%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 8         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1886      | 42.28%  |
| 1366x768 (WXGA)    | 600       | 13.45%  |
| 3840x2160 (4K)     | 311       | 6.97%   |
| 2560x1440 (QHD)    | 271       | 6.07%   |
| 1600x900 (HD+)     | 187       | 4.19%   |
| 1280x1024 (SXGA)   | 151       | 3.38%   |
| 1680x1050 (WSXGA+) | 150       | 3.36%   |
| 1920x1200 (WUXGA)  | 127       | 2.85%   |
| 1280x800 (WXGA)    | 117       | 2.62%   |
| 1440x900 (WXGA+)   | 108       | 2.42%   |
| 3440x1440          | 75        | 1.68%   |
| Unknown            | 58        | 1.3%    |
| 2560x1600          | 50        | 1.12%   |
| 2560x1080          | 49        | 1.1%    |
| 1360x768           | 34        | 0.76%   |
| 3840x2400          | 33        | 0.74%   |
| 2880x1800          | 31        | 0.69%   |
| 3840x1080          | 20        | 0.45%   |
| 1024x768 (XGA)     | 18        | 0.4%    |
| 800x1280           | 17        | 0.38%   |
| 1920x540           | 13        | 0.29%   |
| 2736x1824          | 9         | 0.2%    |
| 2160x1440          | 9         | 0.2%    |
| 1600x1200          | 9         | 0.2%    |
| 1280x720 (HD)      | 9         | 0.2%    |
| 3840x1600          | 7         | 0.16%   |
| 3456x2160          | 7         | 0.16%   |
| 3840x1200          | 6         | 0.13%   |
| 3200x1800 (QHD+)   | 6         | 0.13%   |
| 1400x1050          | 6         | 0.13%   |
| 3600x1080          | 5         | 0.11%   |
| 3000x2000          | 5         | 0.11%   |
| 2048x1152          | 5         | 0.11%   |
| 1024x600           | 5         | 0.11%   |
| 7680x2160          | 4         | 0.09%   |
| 5760x1080          | 4         | 0.09%   |
| 3072x1920          | 4         | 0.09%   |
| 2256x1504          | 4         | 0.09%   |
| 1280x960           | 4         | 0.09%   |
| 2288x1287          | 3         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 993       | 21.48%  |
| 13      | 398       | 8.61%   |
| 17      | 360       | 7.79%   |
| 27      | 346       | 7.49%   |
| 24      | 341       | 7.38%   |
| 14      | 292       | 6.32%   |
| 23      | 280       | 6.06%   |
| Unknown | 248       | 5.37%   |
| 21      | 218       | 4.72%   |
| 11      | 153       | 3.31%   |
| 19      | 118       | 2.55%   |
| 34      | 100       | 2.16%   |
| 12      | 97        | 2.1%    |
| 22      | 96        | 2.08%   |
| 31      | 87        | 1.88%   |
| 20      | 59        | 1.28%   |
| 18      | 48        | 1.04%   |
| 16      | 47        | 1.02%   |
| 84      | 36        | 0.78%   |
| 25      | 34        | 0.74%   |
| 40      | 30        | 0.65%   |
| 72      | 27        | 0.58%   |
| 54      | 18        | 0.39%   |
| 65      | 16        | 0.35%   |
| 28      | 16        | 0.35%   |
| 10      | 16        | 0.35%   |
| 7       | 14        | 0.3%    |
| 32      | 11        | 0.24%   |
| 26      | 11        | 0.24%   |
| 33      | 10        | 0.22%   |
| 29      | 10        | 0.22%   |
| 37      | 9         | 0.19%   |
| 52      | 8         | 0.17%   |
| 35      | 8         | 0.17%   |
| 46      | 6         | 0.13%   |
| 36      | 6         | 0.13%   |
| 58      | 5         | 0.11%   |
| 42      | 5         | 0.11%   |
| 39      | 5         | 0.11%   |
| 86      | 4         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1504      | 33.11%  |
| 501-600        | 918       | 20.21%  |
| 201-300        | 524       | 11.54%  |
| 401-500        | 449       | 9.89%   |
| 351-400        | 403       | 8.87%   |
| Unknown        | 248       | 5.46%   |
| 601-700        | 146       | 3.21%   |
| 701-800        | 124       | 2.73%   |
| 1001-1500      | 72        | 1.59%   |
| 1501-2000      | 66        | 1.45%   |
| 801-900        | 55        | 1.21%   |
| 1-100          | 17        | 0.37%   |
| 901-1000       | 12        | 0.26%   |
| More than 2000 | 2         | 0.04%   |
| 101-200        | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2965      | 70.7%   |
| 16/10   | 627       | 14.95%  |
| Unknown | 206       | 4.91%   |
| 5/4     | 145       | 3.46%   |
| 21/9    | 123       | 2.93%   |
| 3/2     | 46        | 1.1%    |
| 4/3     | 40        | 0.95%   |
| 0.67    | 14        | 0.33%   |
| 6/5     | 11        | 0.26%   |
| 32/9    | 7         | 0.17%   |
| 0.56    | 3         | 0.07%   |
| 1.00    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 0.80    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 979       | 21.35%  |
| 201-250        | 735       | 16.03%  |
| 81-90          | 480       | 10.47%  |
| 301-350        | 356       | 7.76%   |
| Unknown        | 248       | 5.41%   |
| 151-200        | 247       | 5.39%   |
| 121-130        | 241       | 5.26%   |
| 351-500        | 240       | 5.23%   |
| 71-80          | 218       | 4.75%   |
| 51-60          | 155       | 3.38%   |
| 251-300        | 152       | 3.32%   |
| More than 1000 | 128       | 2.79%   |
| 141-150        | 107       | 2.33%   |
| 61-70          | 84        | 1.83%   |
| 501-1000       | 72        | 1.57%   |
| 111-120        | 54        | 1.18%   |
| 131-140        | 48        | 1.05%   |
| 1-40           | 19        | 0.41%   |
| 41-50          | 15        | 0.33%   |
| 91-100         | 7         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1410      | 31.56%  |
| 121-160       | 1276      | 28.57%  |
| 101-120       | 957       | 21.42%  |
| 161-240       | 306       | 6.85%   |
| Unknown       | 248       | 5.55%   |
| More than 240 | 163       | 3.65%   |
| 1-50          | 107       | 2.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3324      | 77.11%  |
| 2     | 697       | 16.17%  |
| 0     | 205       | 4.76%   |
| 3     | 79        | 1.83%   |
| 4     | 5         | 0.12%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2232      | 36.14%  |
| Realtek Semiconductor                 | 2034      | 32.93%  |
| Qualcomm Atheros                      | 573       | 9.28%   |
| Broadcom                              | 382       | 6.19%   |
| Broadcom Limited                      | 89        | 1.44%   |
| TP-Link                               | 77        | 1.25%   |
| Marvell Technology Group              | 76        | 1.23%   |
| Ralink Technology                     | 74        | 1.2%    |
| MediaTek                              | 74        | 1.2%    |
| Ralink                                | 61        | 0.99%   |
| Nvidia                                | 48        | 0.78%   |
| ASIX Electronics                      | 42        | 0.68%   |
| DisplayLink                           | 34        | 0.55%   |
| Dell                                  | 30        | 0.49%   |
| Hewlett-Packard                       | 26        | 0.42%   |
| Microsoft                             | 16        | 0.26%   |
| Sitecom Europe                        | 15        | 0.24%   |
| Samsung Electronics                   | 15        | 0.24%   |
| NetGear                               | 15        | 0.24%   |
| JMicron Technology                    | 14        | 0.23%   |
| Sierra Wireless                       | 13        | 0.21%   |
| Lenovo                                | 13        | 0.21%   |
| IMC Networks                          | 13        | 0.21%   |
| Huawei Technologies                   | 13        | 0.21%   |
| Silicon Integrated Systems [SiS]      | 12        | 0.19%   |
| Qualcomm                              | 12        | 0.19%   |
| Ericsson Business Mobile Networks     | 12        | 0.19%   |
| ASUSTek Computer                      | 11        | 0.18%   |
| Aquantia                              | 11        | 0.18%   |
| VIA Technologies                      | 6         | 0.1%    |
| Gemtek                                | 6         | 0.1%    |
| D-Link                                | 6         | 0.1%    |
| Xiaomi                                | 5         | 0.08%   |
| Qualcomm Atheros Communications       | 5         | 0.08%   |
| Mellanox Technologies                 | 5         | 0.08%   |
| Fibocom                               | 5         | 0.08%   |
| Edimax Technology                     | 5         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.08%   |
| U-Blox                                | 4         | 0.06%   |
| Sigma Designs                         | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1449      | 20.05%  |
| Intel Wi-Fi 6 AX200                                               | 223       | 3.09%   |
| Intel Wireless 8265 / 8275                                        | 171       | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 169       | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 167       | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 151       | 2.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 121       | 1.67%   |
| Intel Wireless 7265                                               | 105       | 1.45%   |
| Intel I211 Gigabit Network Connection                             | 101       | 1.4%    |
| Intel Wi-Fi 6 AX201                                               | 94        | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 88        | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 77        | 1.07%   |
| Intel Wireless 7260                                               | 77        | 1.07%   |
| Intel Wireless 8260                                               | 68        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 68        | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 64        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 64        | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 61        | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 60        | 0.83%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 60        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 60        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 58        | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 56        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 54        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 51        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 0.69%   |
| Intel Wireless 3165                                               | 49        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 49        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 47        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 47        | 0.65%   |
| Intel Wireless-AC 9260                                            | 46        | 0.64%   |
| Intel Ethernet Controller I225-V                                  | 41        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 40        | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 39        | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 38        | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 37        | 0.51%   |
| Intel Centrino Ultimate-N 6300                                    | 37        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 36        | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 36        | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 36        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1717      | 52.03%  |
| Qualcomm Atheros                      | 456       | 13.82%  |
| Realtek Semiconductor                 | 394       | 11.94%  |
| Broadcom                              | 238       | 7.21%   |
| Ralink Technology                     | 74        | 2.24%   |
| MediaTek                              | 72        | 2.18%   |
| TP-Link                               | 68        | 2.06%   |
| Ralink                                | 61        | 1.85%   |
| Broadcom Limited                      | 45        | 1.36%   |
| Sitecom Europe                        | 15        | 0.45%   |
| NetGear                               | 15        | 0.45%   |
| Microsoft                             | 14        | 0.42%   |
| Sierra Wireless                       | 13        | 0.39%   |
| Marvell Technology Group              | 13        | 0.39%   |
| IMC Networks                          | 13        | 0.39%   |
| Dell                                  | 13        | 0.39%   |
| ASUSTek Computer                      | 11        | 0.33%   |
| Qualcomm                              | 9         | 0.27%   |
| Hewlett-Packard                       | 6         | 0.18%   |
| Gemtek                                | 6         | 0.18%   |
| D-Link                                | 6         | 0.18%   |
| Qualcomm Atheros Communications       | 5         | 0.15%   |
| Fibocom                               | 5         | 0.15%   |
| Edimax Technology                     | 5         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.15%   |
| Linksys                               | 4         | 0.12%   |
| Belkin Components                     | 4         | 0.12%   |
| Senao                                 | 2         | 0.06%   |
| Sagem                                 | 2         | 0.06%   |
| CyberTAN Technology                   | 2         | 0.06%   |
| Wilocity                              | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Cinterion                             | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 223       | 6.72%   |
| Intel Wireless 8265 / 8275                                              | 171       | 5.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 121       | 3.65%   |
| Intel Wireless 7265                                                     | 105       | 3.17%   |
| Intel Wi-Fi 6 AX201                                                     | 94        | 2.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 77        | 2.32%   |
| Intel Wireless 7260                                                     | 77        | 2.32%   |
| Intel Wireless 8260                                                     | 68        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 68        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 64        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 61        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 60        | 1.81%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 60        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 60        | 1.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 58        | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 56        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 54        | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 51        | 1.54%   |
| Intel Wireless 3165                                                     | 49        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 49        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 47        | 1.42%   |
| Intel Wireless-AC 9260                                                  | 46        | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 40        | 1.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 38        | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 37        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 37        | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 36        | 1.09%   |
| Intel Wireless 3160                                                     | 33        | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1%      |
| Intel Centrino Advanced-N 6200                                          | 32        | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 31        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 26        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 23        | 0.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 23        | 0.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 23        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 23        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1871      | 50.24%  |
| Intel                                  | 1093      | 29.35%  |
| Broadcom                               | 202       | 5.42%   |
| Qualcomm Atheros                       | 182       | 4.89%   |
| Marvell Technology Group               | 63        | 1.69%   |
| Nvidia                                 | 47        | 1.26%   |
| Broadcom Limited                       | 44        | 1.18%   |
| ASIX Electronics                       | 42        | 1.13%   |
| DisplayLink                            | 34        | 0.91%   |
| Samsung Electronics                    | 14        | 0.38%   |
| JMicron Technology                     | 14        | 0.38%   |
| Lenovo                                 | 13        | 0.35%   |
| Silicon Integrated Systems [SiS]       | 11        | 0.3%    |
| Aquantia                               | 11        | 0.3%    |
| TP-Link                                | 9         | 0.24%   |
| Huawei Technologies                    | 9         | 0.24%   |
| VIA Technologies                       | 6         | 0.16%   |
| Hewlett-Packard                        | 6         | 0.16%   |
| Xiaomi                                 | 5         | 0.13%   |
| Mellanox Technologies                  | 4         | 0.11%   |
| ICS Advent                             | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.08%   |
| Standard Microsystems                  | 3         | 0.08%   |
| Qualcomm                               | 3         | 0.08%   |
| 3Com                                   | 3         | 0.08%   |
| ULi Electronics                        | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.05%   |
| Motorola PCS                           | 2         | 0.05%   |
| MosChip Semiconductor                  | 2         | 0.05%   |
| Microsoft                              | 2         | 0.05%   |
| Microchip Technology                   | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| Jolla Oy                               | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1449      | 37.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 169       | 4.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 167       | 4.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 151       | 3.95%   |
| Intel I211 Gigabit Network Connection                             | 101       | 2.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 88        | 2.3%    |
| Intel Ethernet Connection (2) I219-V                              | 64        | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 47        | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 41        | 1.07%   |
| Intel Ethernet Connection I219-LM                                 | 36        | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 36        | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 35        | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 34        | 0.89%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32        | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 32        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 25        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 20        | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 19        | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 18        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 17        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 16        | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.39%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15        | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3505      | 52.17%  |
| WiFi     | 3129      | 46.57%  |
| Modem    | 76        | 1.13%   |
| Unknown  | 9         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2377      | 53.94%  |
| Ethernet | 2029      | 46.04%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2173      | 51.51%  |
| 1     | 1815      | 43.02%  |
| 0     | 113       | 2.68%   |
| 3     | 88        | 2.09%   |
| 4     | 19        | 0.45%   |
| 5     | 4         | 0.09%   |
| 7     | 3         | 0.07%   |
| 6     | 3         | 0.07%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3348      | 77.75%  |
| Yes  | 958       | 22.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1387      | 53.45%  |
| Cambridge Silicon Radio         | 204       | 7.86%   |
| Realtek Semiconductor           | 177       | 6.82%   |
| Qualcomm Atheros Communications | 132       | 5.09%   |
| Apple                           | 119       | 4.59%   |
| Broadcom                        | 109       | 4.2%    |
| IMC Networks                    | 95        | 3.66%   |
| Foxconn / Hon Hai               | 76        | 2.93%   |
| Lite-On Technology              | 69        | 2.66%   |
| ASUSTek Computer                | 47        | 1.81%   |
| Hewlett-Packard                 | 44        | 1.7%    |
| Dell                            | 37        | 1.43%   |
| Toshiba                         | 20        | 0.77%   |
| MediaTek                        | 16        | 0.62%   |
| Marvell Semiconductor           | 13        | 0.5%    |
| Ralink                          | 10        | 0.39%   |
| TP-Link                         | 8         | 0.31%   |
| Realtek                         | 6         | 0.23%   |
| Alps Electric                   | 4         | 0.15%   |
| USI                             | 3         | 0.12%   |
| Ralink Technology               | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| Sitecom Europe                  | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Foxconn International           | 2         | 0.08%   |
| Roper                           | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 476       | 18.32%  |
| Intel AX201 Bluetooth                               | 256       | 9.85%   |
| Intel AX200 Bluetooth                               | 213       | 8.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 204       | 7.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 204       | 7.85%   |
| Realtek Bluetooth Radio                             | 112       | 4.31%   |
| Intel Bluetooth Device                              | 79        | 3.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 50        | 1.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 47        | 1.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 47        | 1.81%   |
| Apple Bluetooth Host Controller                     | 46        | 1.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.69%   |
| IMC Networks Bluetooth Radio                        | 39        | 1.5%    |
| Intel AX210 Bluetooth                               | 35        | 1.35%   |
| Apple Bluetooth USB Host Controller                 | 33        | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 32        | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                   | 31        | 1.19%   |
| Lite-On Bluetooth Device                            | 29        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 27        | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 27        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 26        | 1%      |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.89%   |
| IMC Networks Bluetooth Device                       | 22        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.77%   |
| Broadcom HP Portable SoftSailing                    | 20        | 0.77%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 18        | 0.69%   |
| IMC Networks Wireless_Device                        | 17        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 16        | 0.62%   |
| MediaTek Wireless_Device                            | 15        | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.5%    |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.5%    |
| Apple Bluetooth HCI                                 | 13        | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.42%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.38%   |
| Broadcom HP Portable Bumble Bee                     | 10        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3074      | 52.92%  |
| AMD                              | 1107      | 19.06%  |
| Nvidia                           | 976       | 16.8%   |
| C-Media Electronics              | 86        | 1.48%   |
| Logitech                         | 50        | 0.86%   |
| Realtek Semiconductor            | 39        | 0.67%   |
| GN Netcom                        | 35        | 0.6%    |
| Creative Labs                    | 34        | 0.59%   |
| Texas Instruments                | 26        | 0.45%   |
| Focusrite-Novation               | 21        | 0.36%   |
| Hewlett-Packard                  | 16        | 0.28%   |
| Creative Technology              | 16        | 0.28%   |
| SteelSeries ApS                  | 15        | 0.26%   |
| Silicon Integrated Systems [SiS] | 14        | 0.24%   |
| JMTek                            | 13        | 0.22%   |
| BEHRINGER International          | 13        | 0.22%   |
| Plantronics                      | 12        | 0.21%   |
| Kingston Technology              | 12        | 0.21%   |
| VIA Technologies                 | 11        | 0.19%   |
| Corsair                          | 11        | 0.19%   |
| ASUSTek Computer                 | 11        | 0.19%   |
| Generalplus Technology           | 9         | 0.15%   |
| Apple                            | 9         | 0.15%   |
| Sony                             | 8         | 0.14%   |
| Sennheiser Communications        | 8         | 0.14%   |
| Razer USA                        | 8         | 0.14%   |
| Lenovo                           | 8         | 0.14%   |
| GYROCOM C&C                      | 8         | 0.14%   |
| RODE Microphones                 | 7         | 0.12%   |
| Micro Star International         | 7         | 0.12%   |
| Yamaha                           | 5         | 0.09%   |
| Native Instruments               | 5         | 0.09%   |
| Cambridge Silicon Radio          | 5         | 0.09%   |
| Blue Microphones                 | 5         | 0.09%   |
| XMOS                             | 4         | 0.07%   |
| Schiit Audio                     | 4         | 0.07%   |
| SAVITECH                         | 4         | 0.07%   |
| Samson Technologies              | 4         | 0.07%   |
| Jieli Technology                 | 4         | 0.07%   |
| AKAI Professional M.I.           | 4         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 306       | 4.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 297       | 4.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 290       | 4.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 252       | 3.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 209       | 3.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 179       | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 176       | 2.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 168       | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 160       | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 147       | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 146       | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 130       | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 122       | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 119       | 1.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 110       | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 101       | 1.49%   |
| AMD FCH Azalia Controller                                                  | 92        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 91        | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 85        | 1.25%   |
| Intel 8 Series HD Audio Controller                                         | 85        | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 79        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 78        | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 77        | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 76        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 74        | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 73        | 1.08%   |
| Nvidia High Definition Audio Controller                                    | 72        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 72        | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 71        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 69        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 69        | 1.02%   |
| Intel Jasper Lake HD Audio                                                 | 65        | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 60        | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 58        | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 57        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 57        | 0.84%   |
| Intel CM238 HD Audio Controller                                            | 57        | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 55        | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 52        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 50        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 538       | 22.35%  |
| Samsung Electronics | 470       | 19.53%  |
| Kingston            | 263       | 10.93%  |
| Micron Technology   | 255       | 10.59%  |
| Corsair             | 200       | 8.31%   |
| Unknown             | 176       | 7.31%   |
| Crucial             | 161       | 6.69%   |
| G.Skill             | 84        | 3.49%   |
| Ramaxel Technology  | 34        | 1.41%   |
| Nanya Technology    | 33        | 1.37%   |
| A-DATA Technology   | 33        | 1.37%   |
| Elpida              | 25        | 1.04%   |
| Unknown             | 17        | 0.71%   |
| Transcend           | 12        | 0.5%    |
| Unknown (ABCD)      | 10        | 0.42%   |
| Team                | 8         | 0.33%   |
| GOODRAM             | 8         | 0.33%   |
| Qimonda             | 7         | 0.29%   |
| ASint Technology    | 5         | 0.21%   |
| Patriot             | 4         | 0.17%   |
| 48spaces            | 4         | 0.17%   |
| Wilk                | 3         | 0.12%   |
| GeIL                | 3         | 0.12%   |
| Axiom               | 3         | 0.12%   |
| A Force             | 3         | 0.12%   |
| Toshiba             | 2         | 0.08%   |
| TakeMS              | 2         | 0.08%   |
| PNY                 | 2         | 0.08%   |
| Lexar               | 2         | 0.08%   |
| Hewlett-Packard     | 2         | 0.08%   |
| Goldkey             | 2         | 0.08%   |
| Avant               | 2         | 0.08%   |
| Atermiter           | 2         | 0.08%   |
| AMD                 | 2         | 0.08%   |
| A-DA                | 2         | 0.08%   |
| ZIFEI               | 1         | 0.04%   |
| zApacer             | 1         | 0.04%   |
| Unknown (AD8A)      | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x873E)    | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 43        | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 31        | 1.21%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 27        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 22        | 0.86%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 19        | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 18        | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 17        | 0.66%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s         | 17        | 0.66%   |
| Unknown                                                        | 17        | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 14        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 14        | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 14        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 14        | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 13        | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 13        | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 13        | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 12        | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 12        | 0.47%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 12        | 0.47%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 11        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 11        | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 11        | 0.43%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 11        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 10        | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 9         | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 9         | 0.35%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 9         | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 9         | 0.35%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 8         | 0.31%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 8         | 0.31%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 8         | 0.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 8         | 0.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8         | 0.31%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 8         | 0.31%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 8         | 0.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 8         | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s     | 8         | 0.31%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 8         | 0.31%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 8         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1022      | 48.28%  |
| DDR3    | 634       | 29.95%  |
| LPDDR4  | 130       | 6.14%   |
| DDR2    | 86        | 4.06%   |
| LPDDR3  | 67        | 3.16%   |
| SDRAM   | 60        | 2.83%   |
| DDR5    | 44        | 2.08%   |
| Unknown | 32        | 1.51%   |
| LPDDR5  | 22        | 1.04%   |
| DDR     | 15        | 0.71%   |
| DRAM    | 4         | 0.19%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1212      | 57.25%  |
| DIMM         | 660       | 31.18%  |
| Row Of Chips | 222       | 10.49%  |
| Unknown      | 10        | 0.47%   |
| Chip         | 9         | 0.43%   |
| FB-DIMM      | 2         | 0.09%   |
| RIMM         | 1         | 0.05%   |
| DIP          | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 903       | 39.33%  |
| 4096  | 573       | 24.96%  |
| 16384 | 364       | 15.85%  |
| 2048  | 288       | 12.54%  |
| 1024  | 80        | 3.48%   |
| 32768 | 73        | 3.18%   |
| 512   | 11        | 0.48%   |
| 3072  | 1         | 0.04%   |
| 256   | 1         | 0.04%   |
| 64    | 1         | 0.04%   |
| 1     | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 382       | 16.9%   |
| 3200    | 347       | 15.35%  |
| 2667    | 329       | 14.55%  |
| 2400    | 165       | 7.3%    |
| 1333    | 143       | 6.32%   |
| 2133    | 118       | 5.22%   |
| 4267    | 95        | 4.2%    |
| 3600    | 65        | 2.87%   |
| 1334    | 64        | 2.83%   |
| 1867    | 52        | 2.3%    |
| 800     | 49        | 2.17%   |
| 667     | 47        | 2.08%   |
| Unknown | 35        | 1.55%   |
| 4800    | 30        | 1.33%   |
| 1066    | 24        | 1.06%   |
| 6400    | 21        | 0.93%   |
| 2933    | 17        | 0.75%   |
| 1067    | 17        | 0.75%   |
| 3266    | 16        | 0.71%   |
| 3400    | 15        | 0.66%   |
| 3733    | 14        | 0.62%   |
| 1866    | 14        | 0.62%   |
| 1800    | 14        | 0.62%   |
| 3000    | 13        | 0.57%   |
| 8400    | 12        | 0.53%   |
| 3533    | 12        | 0.53%   |
| 3866    | 10        | 0.44%   |
| 2048    | 10        | 0.44%   |
| 4199    | 9         | 0.4%    |
| 3800    | 9         | 0.4%    |
| 2666    | 9         | 0.4%    |
| 4266    | 8         | 0.35%   |
| 3466    | 8         | 0.35%   |
| 1639    | 8         | 0.35%   |
| 400     | 8         | 0.35%   |
| 6000    | 7         | 0.31%   |
| 533     | 7         | 0.31%   |
| 2800    | 5         | 0.22%   |
| 3666    | 4         | 0.18%   |
| 1648    | 4         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 30        | 30%     |
| Brother Industries    | 19        | 19%     |
| Canon                 | 17        | 17%     |
| Samsung Electronics   | 11        | 11%     |
| Seiko Epson           | 7         | 7%      |
| Dymo-CoStar           | 7         | 7%      |
| Citizen               | 4         | 4%      |
| Zebra                 | 1         | 1%      |
| STMicroelectronics    | 1         | 1%      |
| Ricoh                 | 1         | 1%      |
| Prolific Technology   | 1         | 1%      |
| Lexmark International | 1         | 1%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                                    | 4         | 4%      |
| Dymo-CoStar LabelWriter 450                               | 4         | 4%      |
| Citizen Thermal Receipt Printer [CT-E351]                 | 4         | 4%      |
| HP ENVY 5000 series                                       | 3         | 3%      |
| HP Deskjet 2540 series                                    | 3         | 3%      |
| Seiko Epson ET-2820 Series                                | 2         | 2%      |
| Samsung SCX-4600 Series                                   | 2         | 2%      |
| Samsung ML-216x Series Laser Printer                      | 2         | 2%      |
| Samsung ML-1640 Series Laser Printer                      | 2         | 2%      |
| HP DeskJet 2700 series                                    | 2         | 2%      |
| Canon TS3100 series                                       | 2         | 2%      |
| Canon PIXMA MX920 Series                                  | 2         | 2%      |
| Canon PIXMA MG5600 Series                                 | 2         | 2%      |
| Canon PIXMA MG2500 Series                                 | 2         | 2%      |
| Brother Printer                                           | 2         | 2%      |
| Brother HL-2030 Laser Printer                             | 2         | 2%      |
| Zebra Printer                                             | 1         | 1%      |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1%      |
| Seiko Epson XP-4200 Series                                | 1         | 1%      |
| Seiko Epson XP-200 Series                                 | 1         | 1%      |
| Seiko Epson Thermal Receipt Printer [TM-T20]              | 1         | 1%      |
| Seiko Epson Printer                                       | 1         | 1%      |
| Seiko Epson ET-2720 Series                                | 1         | 1%      |
| Samsung SCX-4300 Series                                   | 1         | 1%      |
| Samsung ML-2240 Series                                    | 1         | 1%      |
| Samsung CLX-3180 Series                                   | 1         | 1%      |
| Samsung C48x Series                                       | 1         | 1%      |
| Samsung C43x Series                                       | 1         | 1%      |
| Ricoh Aficio SP 3510DN                                    | 1         | 1%      |
| Prolific PL2305 Parallel Port                             | 1         | 1%      |
| Lexmark International MC3326adwe                          | 1         | 1%      |
| HP Printing Support                                       | 1         | 1%      |
| HP OfficeJet Pro 8020 series                              | 1         | 1%      |
| HP OfficeJet 8010 series                                  | 1         | 1%      |
| HP OfficeJet 6950                                         | 1         | 1%      |
| HP OfficeJet 3830 series                                  | 1         | 1%      |
| HP LaserJet Professional P1102w                           | 1         | 1%      |
| HP LaserJet P1005                                         | 1         | 1%      |
| HP LaserJet 1320                                          | 1         | 1%      |
| HP LaserJet 1018                                          | 1         | 1%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 62.16%  |
| Seiko Epson     | 7         | 18.92%  |
| Mustek Systems  | 4         | 10.81%  |
| Hewlett-Packard | 2         | 5.41%   |
| Plustek         | 1         | 2.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 10.53%  |
| Canon CanoScan LiDE 210                       | 4         | 10.53%  |
| Mustek Systems ScanExpress 1200 UB            | 3         | 7.89%   |
| Seiko Epson Scanner                           | 2         | 5.26%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 5.26%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 5.26%   |
| Canon CanoScan N650U/N656U                    | 2         | 5.26%   |
| Canon CanoScan LiDE 200                       | 2         | 5.26%   |
| Canon CanoScan LiDE 120                       | 2         | 5.26%   |
| Canon CanoScan LiDE 110                       | 2         | 5.26%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 2.63%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 2.63%   |
| Plustek 600dpi USB Scanner                    | 1         | 2.63%   |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 2.63%   |
| HP ScanJet 5590                               | 1         | 2.63%   |
| HP ScanJet 3300c                              | 1         | 2.63%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 2.63%   |
| Canon CanoScan LiDE 60                        | 1         | 2.63%   |
| Canon CanoScan FB630U                         | 1         | 2.63%   |
| Canon CanoScan 9000F Mark II                  | 1         | 2.63%   |
| Canon CanoScan 5600F                          | 1         | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 536       | 20.92%  |
| Microdia                               | 287       | 11.2%   |
| Realtek Semiconductor                  | 243       | 9.48%   |
| IMC Networks                           | 210       | 8.2%    |
| Logitech                               | 170       | 6.64%   |
| Sunplus Innovation Technology          | 168       | 6.56%   |
| Bison Electronics                      | 132       | 5.15%   |
| Cheng Uei Precision Industry (Foxlink) | 107       | 4.18%   |
| Apple                                  | 104       | 4.06%   |
| Quanta                                 | 85        | 3.32%   |
| Suyin                                  | 77        | 3.01%   |
| Lite-On Technology                     | 50        | 1.95%   |
| Acer                                   | 39        | 1.52%   |
| Syntek                                 | 36        | 1.41%   |
| Luxvisions Innotech Limited            | 29        | 1.13%   |
| Samsung Electronics                    | 24        | 0.94%   |
| Silicon Motion                         | 21        | 0.82%   |
| Microsoft                              | 20        | 0.78%   |
| Ricoh                                  | 18        | 0.7%    |
| Alcor Micro                            | 17        | 0.66%   |
| Lenovo                                 | 16        | 0.62%   |
| Primax Electronics                     | 14        | 0.55%   |
| Sonix Technology                       | 12        | 0.47%   |
| Trust                                  | 10        | 0.39%   |
| MacroSilicon                           | 8         | 0.31%   |
| Jieli Technology                       | 8         | 0.31%   |
| Importek                               | 8         | 0.31%   |
| SunplusIT                              | 6         | 0.23%   |
| Generalplus Technology                 | 6         | 0.23%   |
| ARC International                      | 6         | 0.23%   |
| ALi                                    | 5         | 0.2%    |
| Z-Star Microelectronics                | 4         | 0.16%   |
| Sweex                                  | 4         | 0.16%   |
| Creative Technology                    | 4         | 0.16%   |
| Y Media                                | 3         | 0.12%   |
| Valve Software                         | 3         | 0.12%   |
| Ruision                                | 3         | 0.12%   |
| OmniVision Technologies                | 3         | 0.12%   |
| LG Electronics                         | 3         | 0.12%   |
| Genesys Logic                          | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 172       | 6.58%   |
| Realtek Integrated_Webcam_HD                                               | 92        | 3.52%   |
| Chicony integrated camera                                                  | 89        | 3.4%    |
| IMC Networks Integrated Camera                                             | 75        | 2.87%   |
| Sunplus Integrated_Webcam_HD                                               | 70        | 2.68%   |
| Realtek Integrated_Webcam_5M                                               | 68        | 2.6%    |
| Chicony HD WebCam                                                          | 68        | 2.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 50        | 1.91%   |
| Bison Integrated Camera                                                    | 37        | 1.42%   |
| Chicony HP HD Camera                                                       | 36        | 1.38%   |
| Logitech Webcam C270                                                       | 32        | 1.22%   |
| Apple Built-in iSight                                                      | 32        | 1.22%   |
| Chicony USB2.0 Camera                                                      | 28        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 25        | 0.96%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 24        | 0.92%   |
| Logitech HD Pro Webcam C920                                                | 24        | 0.92%   |
| Chicony HP Wide Vision HD Camera                                           | 23        | 0.88%   |
| Syntek Integrated Camera                                                   | 22        | 0.84%   |
| Bison BisonCam,NB Pro                                                      | 22        | 0.84%   |
| Apple FaceTime HD Camera (Built-in)                                        | 21        | 0.8%    |
| Apple FaceTime HD Camera                                                   | 21        | 0.8%    |
| Sunplus HD WebCam                                                          | 20        | 0.77%   |
| Microdia Integrated_Webcam_5M                                              | 20        | 0.77%   |
| Chicony TOSHIBA Web Camera - HD                                            | 18        | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 17        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 17        | 0.65%   |
| Logitech Webcam C310                                                       | 16        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 16        | 0.61%   |
| Quanta HD User Facing                                                      | 15        | 0.57%   |
| Logitech C922 Pro Stream Webcam                                            | 15        | 0.57%   |
| Chicony Integrated HP HD Webcam                                            | 15        | 0.57%   |
| Realtek USB Camera                                                         | 14        | 0.54%   |
| Microdia Integrated Webcam                                                 | 14        | 0.54%   |
| Lite-On Integrated Camera                                                  | 14        | 0.54%   |
| Lite-On HP HD Camera                                                       | 14        | 0.54%   |
| Acer Integrated Camera                                                     | 14        | 0.54%   |
| Quanta HP Wide Vision HD Camera                                            | 13        | 0.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.5%    |
| Chicony USB2.0 HD UVC WebCam                                               | 13        | 0.5%    |
| Quanta HP HD Camera                                                        | 12        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 166       | 32.87%  |
| Synaptics                          | 165       | 32.67%  |
| Shenzhen Goodix Technology         | 67        | 13.27%  |
| AuthenTec                          | 34        | 6.73%   |
| Elan Microelectronics              | 25        | 4.95%   |
| LighTuning Technology              | 23        | 4.55%   |
| Upek                               | 20        | 3.96%   |
| STMicroelectronics                 | 3         | 0.59%   |
| Samsung Electronics                | 1         | 0.2%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 57        | 11.29%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 8.51%   |
| Shenzhen Goodix  Fingerprint Device                                        | 27        | 5.35%   |
| Validity Sensors VFS491                                                    | 21        | 4.16%   |
| Shenzhen Goodix FingerPrint                                                | 21        | 4.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 3.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 2.97%   |
| Synaptics UWP WBDI                                                         | 15        | 2.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 2.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.77%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.57%   |
| Synaptics  WBDI                                                            | 13        | 2.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 2.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 13        | 2.57%   |
| Elan ELAN:ARM-M4                                                           | 13        | 2.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 2.57%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 2.18%   |
| Synaptics WBDI                                                             | 11        | 2.18%   |
| AuthenTec AES2810                                                          | 9         | 1.78%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.39%   |
| Synaptics TouchPad                                                         | 7         | 1.39%   |
| AuthenTec AES1600                                                          | 7         | 1.39%   |
| Unknown                                                                    | 7         | 1.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.19%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.19%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.99%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.99%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.99%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 0.99%   |
| Synaptics WBDI Device                                                      | 4         | 0.79%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.59%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.59%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 122       | 52.59%  |
| Alcor Micro                       | 63        | 27.16%  |
| O2 Micro                          | 23        | 9.91%   |
| Upek                              | 8         | 3.45%   |
| Lenovo                            | 6         | 2.59%   |
| Gemalto (was Gemplus)             | 2         | 0.86%   |
| Yubico.com                        | 1         | 0.43%   |
| VASCO Data Security International | 1         | 0.43%   |
| SCM Microsystems                  | 1         | 0.43%   |
| OmniKey                           | 1         | 0.43%   |
| Fujitsu Siemens Computers         | 1         | 0.43%   |
| Clay Logic                        | 1         | 0.43%   |
| Chicony Electronics               | 1         | 0.43%   |
| Advanced Card Systems             | 1         | 0.43%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 63        | 27.16%  |
| Broadcom BCM5880 Secure Applications Processor                               | 38        | 16.38%  |
| Broadcom 58200                                                               | 35        | 15.09%  |
| Broadcom 5880                                                                | 27        | 11.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 9.48%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 9.05%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 2.59%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.86%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.43%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.43%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.43%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.43%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.43%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.43%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.43%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.43%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.43%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.43%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2931      | 67.89%  |
| 1     | 1086      | 25.16%  |
| 2     | 244       | 5.65%   |
| 3     | 37        | 0.86%   |
| 4     | 11        | 0.25%   |
| 5     | 4         | 0.09%   |
| 6     | 3         | 0.07%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 500       | 29.52%  |
| Graphics card            | 353       | 20.84%  |
| Chipcard                 | 200       | 11.81%  |
| Net/wireless             | 169       | 9.98%   |
| Multimedia controller    | 165       | 9.74%   |
| Communication controller | 64        | 3.78%   |
| Camera                   | 54        | 3.19%   |
| Bluetooth                | 32        | 1.89%   |
| Unassigned class         | 30        | 1.77%   |
| Sound                    | 26        | 1.53%   |
| Storage                  | 22        | 1.3%    |
| Card reader              | 18        | 1.06%   |
| Network                  | 16        | 0.94%   |
| Net/ethernet             | 13        | 0.77%   |
| Flash memory             | 8         | 0.47%   |
| Storage/ide              | 5         | 0.3%    |
| Storage/ata              | 5         | 0.3%    |
| Storage/raid             | 4         | 0.24%   |
| Tv card                  | 3         | 0.18%   |
| Modem                    | 3         | 0.18%   |
| Storage/nvme             | 2         | 0.12%   |
| Firewire controller      | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

