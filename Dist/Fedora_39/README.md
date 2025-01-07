Fedora 39 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 39.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_39/Desktop/README.md) and [notebooks](/Dist/Fedora_39/Notebook/README.md).

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

Total: 4306

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z97N-WIFI                   | Notebook    | [94525b433d](https://linux-hardware.org/?probe=94525b433d) | Jan 04, 2025 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [f453563b1e](https://linux-hardware.org/?probe=f453563b1e) | Jan 02, 2025 |
| Dell          | Latitude E6430              | Notebook    | [3bbd75ec42](https://linux-hardware.org/?probe=3bbd75ec42) | Dec 28, 2024 |
| Pegatron      | Benicia                     | Desktop     | [e061c1cadc](https://linux-hardware.org/?probe=e061c1cadc) | Dec 28, 2024 |
| HP            | ENVY m6                     | Notebook    | [4060abf5de](https://linux-hardware.org/?probe=4060abf5de) | Dec 18, 2024 |
| Dell          | 0Y9655                      | Desktop     | [02dddf8f3b](https://linux-hardware.org/?probe=02dddf8f3b) | Dec 10, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [4dba947354](https://linux-hardware.org/?probe=4dba947354) | Dec 06, 2024 |
| ASRock        | B360M Pro4                  | Desktop     | [110b5c92b3](https://linux-hardware.org/?probe=110b5c92b3) | Dec 05, 2024 |
| ASRock        | B360M Pro4                  | Desktop     | [51ed30ad3f](https://linux-hardware.org/?probe=51ed30ad3f) | Dec 05, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | Notebook    | [453f972762](https://linux-hardware.org/?probe=453f972762) | Nov 26, 2024 |
| TUXEDO        | InfinityBook Pro Intel G... | Notebook    | [dd0ea1fc00](https://linux-hardware.org/?probe=dd0ea1fc00) | Nov 24, 2024 |
| Dell          | 09KPNV A00                  | Desktop     | [3071efb367](https://linux-hardware.org/?probe=3071efb367) | Nov 23, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6ff921cfe0](https://linux-hardware.org/?probe=6ff921cfe0) | Nov 23, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [0ad9b505c5](https://linux-hardware.org/?probe=0ad9b505c5) | Nov 22, 2024 |
| HP            | ProBook 430 G5              | Notebook    | [1dd8b2a540](https://linux-hardware.org/?probe=1dd8b2a540) | Nov 18, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [e18f89ceee](https://linux-hardware.org/?probe=e18f89ceee) | Nov 14, 2024 |
| ASUSTek       | Leonite2                    | Desktop     | [0811b000fc](https://linux-hardware.org/?probe=0811b000fc) | Nov 12, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [55c68fb44b](https://linux-hardware.org/?probe=55c68fb44b) | Nov 11, 2024 |
| ASUSTek       | Leonite2                    | Desktop     | [1eccc2d680](https://linux-hardware.org/?probe=1eccc2d680) | Nov 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [9fe7b0c308](https://linux-hardware.org/?probe=9fe7b0c308) | Nov 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [7a1de5717e](https://linux-hardware.org/?probe=7a1de5717e) | Nov 09, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0ee75416e7](https://linux-hardware.org/?probe=0ee75416e7) | Nov 08, 2024 |
| Dell          | 09KPNV A00                  | Desktop     | [c93191fdb6](https://linux-hardware.org/?probe=c93191fdb6) | Nov 08, 2024 |
| ASRock        | B650 LiveMixer              | Desktop     | [644424949e](https://linux-hardware.org/?probe=644424949e) | Nov 05, 2024 |
| ASUSTek       | P5Q SE/R                    | Desktop     | [e2902f3cdb](https://linux-hardware.org/?probe=e2902f3cdb) | Nov 04, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [260459f303](https://linux-hardware.org/?probe=260459f303) | Nov 02, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [08f5e3b392](https://linux-hardware.org/?probe=08f5e3b392) | Oct 31, 2024 |
| ASRock        | 990FX Killer                | Desktop     | [f8fbe6083a](https://linux-hardware.org/?probe=f8fbe6083a) | Oct 25, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [2c354565cb](https://linux-hardware.org/?probe=2c354565cb) | Oct 20, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [a2e03265d9](https://linux-hardware.org/?probe=a2e03265d9) | Oct 19, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [6862f6eee9](https://linux-hardware.org/?probe=6862f6eee9) | Oct 18, 2024 |
| MSI           | Creator 17 A10SE            | Notebook    | [e5802f03e9](https://linux-hardware.org/?probe=e5802f03e9) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [ebed367b62](https://linux-hardware.org/?probe=ebed367b62) | Oct 16, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [facae97aa8](https://linux-hardware.org/?probe=facae97aa8) | Oct 16, 2024 |
| Dell          | Latitude 5510               | Notebook    | [c97d14c219](https://linux-hardware.org/?probe=c97d14c219) | Oct 14, 2024 |
| Lenovo        | ThinkPad E14 20RAS0D800     | Notebook    | [11927afbf6](https://linux-hardware.org/?probe=11927afbf6) | Oct 14, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [5372e4c323](https://linux-hardware.org/?probe=5372e4c323) | Oct 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [48cb304978](https://linux-hardware.org/?probe=48cb304978) | Oct 11, 2024 |
| Dell          | Latitude E6500              | Notebook    | [79b47fa7fc](https://linux-hardware.org/?probe=79b47fa7fc) | Oct 10, 2024 |
| Framework     | Laptop                      | Notebook    | [806d098add](https://linux-hardware.org/?probe=806d098add) | Oct 10, 2024 |
| Positivo      | J14GL11                     | Notebook    | [8978098dbf](https://linux-hardware.org/?probe=8978098dbf) | Oct 10, 2024 |
| HP            | EliteBook 2740p             | Notebook    | [8eaeff2eea](https://linux-hardware.org/?probe=8eaeff2eea) | Oct 09, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7e908345aa](https://linux-hardware.org/?probe=7e908345aa) | Oct 07, 2024 |
| Dell          | Precision M4400             | Notebook    | [a1b83717fb](https://linux-hardware.org/?probe=a1b83717fb) | Oct 06, 2024 |
| Dell          | Latitude 5490               | Notebook    | [a36413cf8d](https://linux-hardware.org/?probe=a36413cf8d) | Oct 01, 2024 |
| Dell          | Latitude 5490               | Notebook    | [9ae5fc5d61](https://linux-hardware.org/?probe=9ae5fc5d61) | Oct 01, 2024 |
| Dell          | G5 5587                     | Notebook    | [4d3bbb7799](https://linux-hardware.org/?probe=4d3bbb7799) | Oct 01, 2024 |
| Dell          | G5 5587                     | Notebook    | [4d6949b64f](https://linux-hardware.org/?probe=4d6949b64f) | Oct 01, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [55d1e16a84](https://linux-hardware.org/?probe=55d1e16a84) | Sep 28, 2024 |
| Dell          | Latitude 3520               | Notebook    | [d28f3e3298](https://linux-hardware.org/?probe=d28f3e3298) | Sep 28, 2024 |
| MSI           | 880GM-E41                   | Desktop     | [337e4c377f](https://linux-hardware.org/?probe=337e4c377f) | Sep 27, 2024 |
| BESSTAR Te... | UM350                       | Desktop     | [57738b8c5e](https://linux-hardware.org/?probe=57738b8c5e) | Sep 25, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [27fbea506b](https://linux-hardware.org/?probe=27fbea506b) | Sep 18, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [910ba58d42](https://linux-hardware.org/?probe=910ba58d42) | Sep 18, 2024 |
| Dell          | Precision 7550              | Notebook    | [2a28845245](https://linux-hardware.org/?probe=2a28845245) | Sep 17, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [38e00d68ca](https://linux-hardware.org/?probe=38e00d68ca) | Sep 15, 2024 |
| Fujitsu       | UH-X                        | Notebook    | [981737896a](https://linux-hardware.org/?probe=981737896a) | Sep 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [bf0a437c11](https://linux-hardware.org/?probe=bf0a437c11) | Sep 14, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [ede9d3b2eb](https://linux-hardware.org/?probe=ede9d3b2eb) | Sep 13, 2024 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [e53f27a41d](https://linux-hardware.org/?probe=e53f27a41d) | Sep 10, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [569f106b52](https://linux-hardware.org/?probe=569f106b52) | Sep 04, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [4c19a63fee](https://linux-hardware.org/?probe=4c19a63fee) | Sep 02, 2024 |
| Dell          | Latitude 5511               | Notebook    | [337579e62a](https://linux-hardware.org/?probe=337579e62a) | Sep 01, 2024 |
| MSI           | 880GM-E41                   | Desktop     | [6644af397b](https://linux-hardware.org/?probe=6644af397b) | Sep 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [11715ce070](https://linux-hardware.org/?probe=11715ce070) | Sep 01, 2024 |
| ASRock        | 760GM-HDV                   | Desktop     | [5f7ac7c626](https://linux-hardware.org/?probe=5f7ac7c626) | Aug 31, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [9ed7c06816](https://linux-hardware.org/?probe=9ed7c06816) | Aug 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [24df3aeea1](https://linux-hardware.org/?probe=24df3aeea1) | Aug 30, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [cdc5ac1794](https://linux-hardware.org/?probe=cdc5ac1794) | Aug 30, 2024 |
| Maibenben     | MaiBook X series            | Notebook    | [0bbba9b117](https://linux-hardware.org/?probe=0bbba9b117) | Aug 30, 2024 |
| Dell          | G5 5587                     | Notebook    | [07255cca6b](https://linux-hardware.org/?probe=07255cca6b) | Aug 29, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [530d4ccb8b](https://linux-hardware.org/?probe=530d4ccb8b) | Aug 29, 2024 |
| Dell          | G5 5587                     | Notebook    | [ff625fce04](https://linux-hardware.org/?probe=ff625fce04) | Aug 28, 2024 |
| Dell          | Precision 3550              | Notebook    | [a95dae2362](https://linux-hardware.org/?probe=a95dae2362) | Aug 28, 2024 |
| Dell          | Precision 3550              | Notebook    | [e1f44712bd](https://linux-hardware.org/?probe=e1f44712bd) | Aug 26, 2024 |
| Dell          | Precision 3581              | Notebook    | [4812e53bbd](https://linux-hardware.org/?probe=4812e53bbd) | Aug 22, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [c88853eed3](https://linux-hardware.org/?probe=c88853eed3) | Aug 21, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [ad3c00e8f4](https://linux-hardware.org/?probe=ad3c00e8f4) | Aug 21, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5d5650815f](https://linux-hardware.org/?probe=5d5650815f) | Aug 18, 2024 |
| HP            | Pavilion 15                 | Notebook    | [a0741415f2](https://linux-hardware.org/?probe=a0741415f2) | Aug 18, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [0b9a036c20](https://linux-hardware.org/?probe=0b9a036c20) | Aug 17, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [f8e212a6a6](https://linux-hardware.org/?probe=f8e212a6a6) | Aug 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [15d1dd3590](https://linux-hardware.org/?probe=15d1dd3590) | Aug 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [cb5166ed3f](https://linux-hardware.org/?probe=cb5166ed3f) | Aug 17, 2024 |
| Acer          | Aspire A515-51G             | Notebook    | [4ed4d6408d](https://linux-hardware.org/?probe=4ed4d6408d) | Aug 16, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [5e665a9269](https://linux-hardware.org/?probe=5e665a9269) | Aug 15, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [b53667784c](https://linux-hardware.org/?probe=b53667784c) | Aug 14, 2024 |
| Dell          | Latitude E5570              | Notebook    | [bffba2f618](https://linux-hardware.org/?probe=bffba2f618) | Aug 13, 2024 |
| Dell          | 0215PR A03                  | Desktop     | [4709910f60](https://linux-hardware.org/?probe=4709910f60) | Aug 12, 2024 |
| Dell          | 0215PR A03                  | Desktop     | [ba8b885367](https://linux-hardware.org/?probe=ba8b885367) | Aug 12, 2024 |
| ASRock        | Z170 Extreme7+              | Desktop     | [64c270cc1d](https://linux-hardware.org/?probe=64c270cc1d) | Aug 12, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [cf835ce8d2](https://linux-hardware.org/?probe=cf835ce8d2) | Aug 11, 2024 |
| HP            | 2129                        | Desktop     | [d2ae5dc64d](https://linux-hardware.org/?probe=d2ae5dc64d) | Aug 11, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [a6f4b3ba0b](https://linux-hardware.org/?probe=a6f4b3ba0b) | Aug 10, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [52ca97fd84](https://linux-hardware.org/?probe=52ca97fd84) | Aug 10, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [36eb66b720](https://linux-hardware.org/?probe=36eb66b720) | Aug 07, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [e7c6b20b64](https://linux-hardware.org/?probe=e7c6b20b64) | Aug 06, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [4468e82d99](https://linux-hardware.org/?probe=4468e82d99) | Aug 05, 2024 |
| HP            | Pavilion 15                 | Notebook    | [f237100ca6](https://linux-hardware.org/?probe=f237100ca6) | Aug 05, 2024 |
| HP            | Pavilion 15                 | Notebook    | [f1f40fc065](https://linux-hardware.org/?probe=f1f40fc065) | Aug 04, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [8805319545](https://linux-hardware.org/?probe=8805319545) | Aug 04, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0a09eb534e](https://linux-hardware.org/?probe=0a09eb534e) | Aug 02, 2024 |
| HP            | ProBook 4720s               | Notebook    | [051178bbab](https://linux-hardware.org/?probe=051178bbab) | Aug 02, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | Notebook    | [3e723d09c8](https://linux-hardware.org/?probe=3e723d09c8) | Aug 02, 2024 |
| HP            | 8056                        | Desktop     | [2e64830df3](https://linux-hardware.org/?probe=2e64830df3) | Aug 01, 2024 |
| HP            | 8056                        | Desktop     | [d38465aac1](https://linux-hardware.org/?probe=d38465aac1) | Aug 01, 2024 |
| HP            | ProBook 4720s               | Notebook    | [d8c638a8fc](https://linux-hardware.org/?probe=d8c638a8fc) | Aug 01, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [c59904f021](https://linux-hardware.org/?probe=c59904f021) | Aug 01, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [775c5ab4cb](https://linux-hardware.org/?probe=775c5ab4cb) | Jul 30, 2024 |
| ASUSTek       | X580VD                      | Notebook    | [8338f52205](https://linux-hardware.org/?probe=8338f52205) | Jul 30, 2024 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [bb161d55df](https://linux-hardware.org/?probe=bb161d55df) | Jul 29, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [7243635706](https://linux-hardware.org/?probe=7243635706) | Jul 26, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [7858b227f7](https://linux-hardware.org/?probe=7858b227f7) | Jul 23, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [987e2409a2](https://linux-hardware.org/?probe=987e2409a2) | Jul 23, 2024 |
| ASUSTek       | ROG Strix G834JY_G834JY     | Notebook    | [7fd40ce962](https://linux-hardware.org/?probe=7fd40ce962) | Jul 22, 2024 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [82f8235d1f](https://linux-hardware.org/?probe=82f8235d1f) | Jul 19, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [fa917601f3](https://linux-hardware.org/?probe=fa917601f3) | Jul 19, 2024 |
| Lenovo        | 1038 SDK0Q40104 WIN 3305... | Server      | [f600e260e9](https://linux-hardware.org/?probe=f600e260e9) | Jul 17, 2024 |
| Lenovo        | ThinkPad T460 20FNXXXXXX    | Notebook    | [89461ad3f5](https://linux-hardware.org/?probe=89461ad3f5) | Jul 17, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [0f1d9f1114](https://linux-hardware.org/?probe=0f1d9f1114) | Jul 17, 2024 |
| ASRock        | Z170 Extreme7+              | Desktop     | [09c4b3a35e](https://linux-hardware.org/?probe=09c4b3a35e) | Jul 17, 2024 |
| HP            | 2ADC                        | Desktop     | [bbb526fb8b](https://linux-hardware.org/?probe=bbb526fb8b) | Jul 17, 2024 |
| Lenovo        | 1038 SDK0Q40104 WIN 3305... | Server      | [0c87261c99](https://linux-hardware.org/?probe=0c87261c99) | Jul 17, 2024 |
| ASRock        | N100DC-ITX                  | Desktop     | [c94f86230a](https://linux-hardware.org/?probe=c94f86230a) | Jul 16, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e6b145c630](https://linux-hardware.org/?probe=e6b145c630) | Jul 16, 2024 |
| HP            | 3048h                       | Desktop     | [4e0b68d2c5](https://linux-hardware.org/?probe=4e0b68d2c5) | Jul 15, 2024 |
| Dell          | Precision 3581              | Notebook    | [3d98230cf1](https://linux-hardware.org/?probe=3d98230cf1) | Jul 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [d82aef88f6](https://linux-hardware.org/?probe=d82aef88f6) | Jul 11, 2024 |
| Intel         | AB2L .A001                  | Mini pc     | [d4dd02c34d](https://linux-hardware.org/?probe=d4dd02c34d) | Jul 09, 2024 |
| Alienware     | M17xR4                      | Notebook    | [32183f94dc](https://linux-hardware.org/?probe=32183f94dc) | Jul 08, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [efea3f1526](https://linux-hardware.org/?probe=efea3f1526) | Jul 06, 2024 |
| ASUSTek       | Z170-A                      | Desktop     | [448a362678](https://linux-hardware.org/?probe=448a362678) | Jul 05, 2024 |
| Acer          | Swift SFG14-42              | Notebook    | [3623aaf512](https://linux-hardware.org/?probe=3623aaf512) | Jul 05, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [b2a92269b5](https://linux-hardware.org/?probe=b2a92269b5) | Jul 05, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [69f46fe2a1](https://linux-hardware.org/?probe=69f46fe2a1) | Jul 04, 2024 |
| Intel         | NUC5i7RYB H73774-105        | Mini pc     | [abe9d3d679](https://linux-hardware.org/?probe=abe9d3d679) | Jul 04, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [732e2a0bab](https://linux-hardware.org/?probe=732e2a0bab) | Jul 03, 2024 |
| ASUSTek       | Z97-DELUXE/USB              | Desktop     | [493d6359d2](https://linux-hardware.org/?probe=493d6359d2) | Jul 03, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [05a3087fd1](https://linux-hardware.org/?probe=05a3087fd1) | Jul 02, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [250703f607](https://linux-hardware.org/?probe=250703f607) | Jul 01, 2024 |
| Intel         | SandyBridge Platform        | Notebook    | [2c314cd985](https://linux-hardware.org/?probe=2c314cd985) | Jul 01, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [9b564a9f2f](https://linux-hardware.org/?probe=9b564a9f2f) | Jun 29, 2024 |
| HP            | Laptop 14-bp0xx             | Notebook    | [2c410dd7fe](https://linux-hardware.org/?probe=2c410dd7fe) | Jun 29, 2024 |
| MSI           | Prestige 15 A10SC           | Notebook    | [70cdd930fc](https://linux-hardware.org/?probe=70cdd930fc) | Jun 29, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [e94ec7fe9f](https://linux-hardware.org/?probe=e94ec7fe9f) | Jun 29, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [c6c2ff5a0a](https://linux-hardware.org/?probe=c6c2ff5a0a) | Jun 29, 2024 |
| Dell          | Latitude 5420               | Notebook    | [3fa5be31e1](https://linux-hardware.org/?probe=3fa5be31e1) | Jun 28, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [a9bc21a345](https://linux-hardware.org/?probe=a9bc21a345) | Jun 28, 2024 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [6aaf1f5ee3](https://linux-hardware.org/?probe=6aaf1f5ee3) | Jun 26, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1b0549fd0b](https://linux-hardware.org/?probe=1b0549fd0b) | Jun 26, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b37aa6322d](https://linux-hardware.org/?probe=b37aa6322d) | Jun 24, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [43bdcb8bff](https://linux-hardware.org/?probe=43bdcb8bff) | Jun 23, 2024 |
| AMD           | A520                        | Desktop     | [4cf100d9b8](https://linux-hardware.org/?probe=4cf100d9b8) | Jun 23, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [a20ee9e228](https://linux-hardware.org/?probe=a20ee9e228) | Jun 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d1321209ae](https://linux-hardware.org/?probe=d1321209ae) | Jun 20, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [b0c89c790e](https://linux-hardware.org/?probe=b0c89c790e) | Jun 19, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [6e268a171b](https://linux-hardware.org/?probe=6e268a171b) | Jun 19, 2024 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [c6a3ecc9f1](https://linux-hardware.org/?probe=c6a3ecc9f1) | Jun 18, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [12bef8e1b7](https://linux-hardware.org/?probe=12bef8e1b7) | Jun 17, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [bd4f65c637](https://linux-hardware.org/?probe=bd4f65c637) | Jun 15, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [8d755f7cf7](https://linux-hardware.org/?probe=8d755f7cf7) | Jun 15, 2024 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [1962d278f9](https://linux-hardware.org/?probe=1962d278f9) | Jun 15, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [61aa75d0c5](https://linux-hardware.org/?probe=61aa75d0c5) | Jun 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cf4e34380f](https://linux-hardware.org/?probe=cf4e34380f) | Jun 14, 2024 |
| Notebook      | PCx0Dx                      | Notebook    | [a4312875de](https://linux-hardware.org/?probe=a4312875de) | Jun 14, 2024 |
| ASUSTek       | P8Z77-M                     | Notebook    | [f98288d257](https://linux-hardware.org/?probe=f98288d257) | Jun 11, 2024 |
| Dell          | Precision M4800             | Notebook    | [24cd1eb79e](https://linux-hardware.org/?probe=24cd1eb79e) | Jun 11, 2024 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [6f371f483d](https://linux-hardware.org/?probe=6f371f483d) | Jun 11, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [c0e41508e0](https://linux-hardware.org/?probe=c0e41508e0) | Jun 11, 2024 |
| System76      | Thelio Major thelio-majo... | Desktop     | [4e35bc3849](https://linux-hardware.org/?probe=4e35bc3849) | Jun 10, 2024 |
| System76      | Thelio Major thelio-majo... | Desktop     | [f8c8acc689](https://linux-hardware.org/?probe=f8c8acc689) | Jun 10, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [be7539d177](https://linux-hardware.org/?probe=be7539d177) | Jun 10, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9e5813c818](https://linux-hardware.org/?probe=9e5813c818) | Jun 10, 2024 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [482f64e89f](https://linux-hardware.org/?probe=482f64e89f) | Jun 10, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [f673ab8e59](https://linux-hardware.org/?probe=f673ab8e59) | Jun 09, 2024 |
| HP            | 8917                        | Desktop     | [051b3cf905](https://linux-hardware.org/?probe=051b3cf905) | Jun 08, 2024 |
| Dell          | Latitude 3420               | Notebook    | [356a53eef2](https://linux-hardware.org/?probe=356a53eef2) | Jun 08, 2024 |
| Dell          | Latitude 3420               | Notebook    | [0b6a5b6ad8](https://linux-hardware.org/?probe=0b6a5b6ad8) | Jun 08, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9baa52a13a](https://linux-hardware.org/?probe=9baa52a13a) | Jun 07, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | Desktop     | [7b4a89be4f](https://linux-hardware.org/?probe=7b4a89be4f) | Jun 05, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | Desktop     | [58135f78e5](https://linux-hardware.org/?probe=58135f78e5) | Jun 05, 2024 |
| Dell          | Latitude E5550              | Notebook    | [ed6db64146](https://linux-hardware.org/?probe=ed6db64146) | Jun 05, 2024 |
| Dell          | Latitude E5550              | Notebook    | [15f86e228b](https://linux-hardware.org/?probe=15f86e228b) | Jun 05, 2024 |
| Dell          | Latitude E7440              | Notebook    | [263c956b64](https://linux-hardware.org/?probe=263c956b64) | Jun 05, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31b9558caf](https://linux-hardware.org/?probe=31b9558caf) | Jun 05, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [e46cc0b4af](https://linux-hardware.org/?probe=e46cc0b4af) | Jun 04, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [d7ef7b9c36](https://linux-hardware.org/?probe=d7ef7b9c36) | Jun 04, 2024 |
| Fujitsu       | LIFEBOOK U7512              | Notebook    | [f38e471977](https://linux-hardware.org/?probe=f38e471977) | Jun 04, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | Notebook    | [8ffa5bb807](https://linux-hardware.org/?probe=8ffa5bb807) | Jun 04, 2024 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [623a5e2894](https://linux-hardware.org/?probe=623a5e2894) | Jun 04, 2024 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [68dd5c57ca](https://linux-hardware.org/?probe=68dd5c57ca) | Jun 04, 2024 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [9a2accbb82](https://linux-hardware.org/?probe=9a2accbb82) | Jun 04, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [208fd714ad](https://linux-hardware.org/?probe=208fd714ad) | Jun 04, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | Notebook    | [695c57972e](https://linux-hardware.org/?probe=695c57972e) | Jun 03, 2024 |
| HP            | 82C0                        | Mini pc     | [a7cb603be4](https://linux-hardware.org/?probe=a7cb603be4) | Jun 02, 2024 |
| ASUSTek       | ROG Strix G713QC_G713QC     | Notebook    | [9e18cd2da0](https://linux-hardware.org/?probe=9e18cd2da0) | Jun 01, 2024 |
| HP            | 1495                        | Desktop     | [c7979accd3](https://linux-hardware.org/?probe=c7979accd3) | May 31, 2024 |
| HP            | 1495                        | Desktop     | [088f6c2bc6](https://linux-hardware.org/?probe=088f6c2bc6) | May 31, 2024 |
| Dell          | Precision 5530              | Notebook    | [338bd4ade5](https://linux-hardware.org/?probe=338bd4ade5) | May 30, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [1cbdc6d75a](https://linux-hardware.org/?probe=1cbdc6d75a) | May 29, 2024 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [3c54f52a2e](https://linux-hardware.org/?probe=3c54f52a2e) | May 29, 2024 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [e696e99eeb](https://linux-hardware.org/?probe=e696e99eeb) | May 28, 2024 |
| ASUSTek       | Maximus IX EXTREME          | Desktop     | [1bb674726e](https://linux-hardware.org/?probe=1bb674726e) | May 28, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [8144ad4580](https://linux-hardware.org/?probe=8144ad4580) | May 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8b30e5083a](https://linux-hardware.org/?probe=8b30e5083a) | May 26, 2024 |
| ASRock        | B650 LiveMixer              | Desktop     | [e80e27799c](https://linux-hardware.org/?probe=e80e27799c) | May 25, 2024 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [5676eb00c8](https://linux-hardware.org/?probe=5676eb00c8) | May 25, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [992d9c19d9](https://linux-hardware.org/?probe=992d9c19d9) | May 24, 2024 |
| Dell          | Latitude 7490               | Notebook    | [dc8c6d63c4](https://linux-hardware.org/?probe=dc8c6d63c4) | May 24, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [999f88f47b](https://linux-hardware.org/?probe=999f88f47b) | May 23, 2024 |
| HP            | EliteBook 840 G5 NOTEBOO... | Notebook    | [eb52e3154b](https://linux-hardware.org/?probe=eb52e3154b) | May 23, 2024 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ef99542c79](https://linux-hardware.org/?probe=ef99542c79) | May 23, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [d3f04d564b](https://linux-hardware.org/?probe=d3f04d564b) | May 23, 2024 |
| HP            | EliteBook 840 G5 NOTEBOO... | Notebook    | [6f77b13646](https://linux-hardware.org/?probe=6f77b13646) | May 22, 2024 |
| Biostar       | A320MH                      | Notebook    | [23e9b549bf](https://linux-hardware.org/?probe=23e9b549bf) | May 22, 2024 |
| Positivo      | C4128G-15                   | Notebook    | [3a626484f8](https://linux-hardware.org/?probe=3a626484f8) | May 22, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1eec079f69](https://linux-hardware.org/?probe=1eec079f69) | May 21, 2024 |
| Dell          | Precision 5530              | Notebook    | [8762044e9b](https://linux-hardware.org/?probe=8762044e9b) | May 21, 2024 |
| Google        | Kohaku                      | Notebook    | [cb6bc17115](https://linux-hardware.org/?probe=cb6bc17115) | May 21, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0d3b74e4c6](https://linux-hardware.org/?probe=0d3b74e4c6) | May 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [d24473f51e](https://linux-hardware.org/?probe=d24473f51e) | May 20, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [71a450cd04](https://linux-hardware.org/?probe=71a450cd04) | May 20, 2024 |
| Dell          | Vostro 7620                 | Notebook    | [cf9fa662a8](https://linux-hardware.org/?probe=cf9fa662a8) | May 20, 2024 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [7ccc346dd5](https://linux-hardware.org/?probe=7ccc346dd5) | May 19, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [414b05c91f](https://linux-hardware.org/?probe=414b05c91f) | May 19, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [b68d9ac21d](https://linux-hardware.org/?probe=b68d9ac21d) | May 18, 2024 |
| Dell          | Latitude E6400              | Notebook    | [47b3359fb9](https://linux-hardware.org/?probe=47b3359fb9) | May 18, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d949bd1fbc](https://linux-hardware.org/?probe=d949bd1fbc) | May 18, 2024 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [6dd9c07f0b](https://linux-hardware.org/?probe=6dd9c07f0b) | May 18, 2024 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [f37d97c956](https://linux-hardware.org/?probe=f37d97c956) | May 18, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a759c66b0d](https://linux-hardware.org/?probe=a759c66b0d) | May 18, 2024 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [28fc9d064e](https://linux-hardware.org/?probe=28fc9d064e) | May 18, 2024 |
| Lenovo        | ThinkStation D20 4155CTO    | Desktop     | [c9d30be181](https://linux-hardware.org/?probe=c9d30be181) | May 18, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [4301eba9f0](https://linux-hardware.org/?probe=4301eba9f0) | May 17, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [4179b24509](https://linux-hardware.org/?probe=4179b24509) | May 17, 2024 |
| HP            | Pavilion 15                 | Notebook    | [20c16d020a](https://linux-hardware.org/?probe=20c16d020a) | May 17, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | Notebook    | [5312f02fde](https://linux-hardware.org/?probe=5312f02fde) | May 17, 2024 |
| Lenovo        | Unknown                     | Notebook    | [d427cb3b64](https://linux-hardware.org/?probe=d427cb3b64) | May 17, 2024 |
| Sony          | VPCYB45JB                   | Notebook    | [747ffc4d2a](https://linux-hardware.org/?probe=747ffc4d2a) | May 16, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [472ce85160](https://linux-hardware.org/?probe=472ce85160) | May 16, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [a2cb0cc623](https://linux-hardware.org/?probe=a2cb0cc623) | May 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [540f2a33ee](https://linux-hardware.org/?probe=540f2a33ee) | May 15, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [ae8bcfd05d](https://linux-hardware.org/?probe=ae8bcfd05d) | May 14, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [448f5f4b26](https://linux-hardware.org/?probe=448f5f4b26) | May 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ab6a57393a](https://linux-hardware.org/?probe=ab6a57393a) | May 13, 2024 |
| Chuwi         | UBook X                     | Convertible | [aebcfca3cd](https://linux-hardware.org/?probe=aebcfca3cd) | May 13, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [8f9768a181](https://linux-hardware.org/?probe=8f9768a181) | May 13, 2024 |
| Gigabyte      | B660M GAMING X AX DDR4      | Desktop     | [76e26350ae](https://linux-hardware.org/?probe=76e26350ae) | May 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [7ec91a9d57](https://linux-hardware.org/?probe=7ec91a9d57) | May 12, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [aa1981e8c1](https://linux-hardware.org/?probe=aa1981e8c1) | May 12, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [06d9ebaf2d](https://linux-hardware.org/?probe=06d9ebaf2d) | May 11, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [97cf40bd89](https://linux-hardware.org/?probe=97cf40bd89) | May 11, 2024 |
| MSI           | Modern 14 C5M               | Notebook    | [b6a9ef050c](https://linux-hardware.org/?probe=b6a9ef050c) | May 11, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [e49a302862](https://linux-hardware.org/?probe=e49a302862) | May 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [da2ad0241c](https://linux-hardware.org/?probe=da2ad0241c) | May 11, 2024 |
| Erying        | tgl                         | Desktop     | [f16c3082ce](https://linux-hardware.org/?probe=f16c3082ce) | May 11, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [68e3c2e111](https://linux-hardware.org/?probe=68e3c2e111) | May 10, 2024 |
| ASUSTek       | K95VJ                       | Notebook    | [5a2ea253cd](https://linux-hardware.org/?probe=5a2ea253cd) | May 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cc2aa8c7b7](https://linux-hardware.org/?probe=cc2aa8c7b7) | May 10, 2024 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [8b42c49814](https://linux-hardware.org/?probe=8b42c49814) | May 10, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [28e810ba0f](https://linux-hardware.org/?probe=28e810ba0f) | May 10, 2024 |
| HP            | ENVY m6                     | Notebook    | [73cac9c76c](https://linux-hardware.org/?probe=73cac9c76c) | May 10, 2024 |
| HP            | ENVY m6                     | Notebook    | [2a3b768042](https://linux-hardware.org/?probe=2a3b768042) | May 10, 2024 |
| Dell          | Latitude E7440              | Notebook    | [618401e8ee](https://linux-hardware.org/?probe=618401e8ee) | May 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | Notebook    | [7e269a1574](https://linux-hardware.org/?probe=7e269a1574) | May 09, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [6da57784a6](https://linux-hardware.org/?probe=6da57784a6) | May 09, 2024 |
| Sony          | VPCYB45JB                   | Notebook    | [6f70d22391](https://linux-hardware.org/?probe=6f70d22391) | May 09, 2024 |
| Avell High... | A70 MOB                     | Notebook    | [2be654083e](https://linux-hardware.org/?probe=2be654083e) | May 08, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [48be6a2dbb](https://linux-hardware.org/?probe=48be6a2dbb) | May 07, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [70022231bd](https://linux-hardware.org/?probe=70022231bd) | May 07, 2024 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [7d6b757088](https://linux-hardware.org/?probe=7d6b757088) | May 07, 2024 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [a9d1c1234c](https://linux-hardware.org/?probe=a9d1c1234c) | May 07, 2024 |
| Star Labs     | StarBook                    | Notebook    | [7e37692a50](https://linux-hardware.org/?probe=7e37692a50) | May 06, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [5038e329fc](https://linux-hardware.org/?probe=5038e329fc) | May 06, 2024 |
| ASUSTek       | ROG Strix G731GV_G731GV     | Notebook    | [00ceb2ea16](https://linux-hardware.org/?probe=00ceb2ea16) | May 06, 2024 |
| Positivo      | J14GL11                     | Notebook    | [71f761fa87](https://linux-hardware.org/?probe=71f761fa87) | May 05, 2024 |
| ASUSTek       | X510UAR                     | Notebook    | [3317acbe53](https://linux-hardware.org/?probe=3317acbe53) | May 05, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [6794452c3b](https://linux-hardware.org/?probe=6794452c3b) | May 05, 2024 |
| HP            | 240 G8                      | Notebook    | [8b7c23e6cb](https://linux-hardware.org/?probe=8b7c23e6cb) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [b7866b963f](https://linux-hardware.org/?probe=b7866b963f) | May 04, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [b7c53048d5](https://linux-hardware.org/?probe=b7c53048d5) | May 04, 2024 |
| MSI           | Raider GE68HX 13VG          | Notebook    | [b3f866a8e6](https://linux-hardware.org/?probe=b3f866a8e6) | May 04, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | Notebook    | [eac9faa98c](https://linux-hardware.org/?probe=eac9faa98c) | May 03, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [44e9f4946e](https://linux-hardware.org/?probe=44e9f4946e) | May 03, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [02a14960a9](https://linux-hardware.org/?probe=02a14960a9) | May 03, 2024 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [41468a4e5c](https://linux-hardware.org/?probe=41468a4e5c) | May 03, 2024 |
| Schenker      | XMG CORE 15(M20, RTX 206... | Notebook    | [e22a67c560](https://linux-hardware.org/?probe=e22a67c560) | May 02, 2024 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [f7e35750cd](https://linux-hardware.org/?probe=f7e35750cd) | May 02, 2024 |
| LG Electro... | 16Z90P-G.AA76G              | Notebook    | [f9bdc22f6f](https://linux-hardware.org/?probe=f9bdc22f6f) | May 01, 2024 |
| Dell          | Inspiron 7537               | Notebook    | [d27f9ad169](https://linux-hardware.org/?probe=d27f9ad169) | May 01, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [7faebd43a1](https://linux-hardware.org/?probe=7faebd43a1) | May 01, 2024 |
| Lenovo        | ThinkPad SL510 2847Q7G      | Notebook    | [c2f435ff58](https://linux-hardware.org/?probe=c2f435ff58) | May 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [badf656eaf](https://linux-hardware.org/?probe=badf656eaf) | May 01, 2024 |
| Apple         | MacBookPro15,2              | Notebook    | [5d0cceea3e](https://linux-hardware.org/?probe=5d0cceea3e) | Apr 30, 2024 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [1c4e390f2d](https://linux-hardware.org/?probe=1c4e390f2d) | Apr 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [3c551032a7](https://linux-hardware.org/?probe=3c551032a7) | Apr 30, 2024 |
| ASUSTek       | CG8480                      | Desktop     | [7567b12c01](https://linux-hardware.org/?probe=7567b12c01) | Apr 30, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [86a58844a8](https://linux-hardware.org/?probe=86a58844a8) | Apr 30, 2024 |
| Dell          | 0H8GYJ A02                  | Server      | [26c6662d67](https://linux-hardware.org/?probe=26c6662d67) | Apr 29, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [d4e717f7b6](https://linux-hardware.org/?probe=d4e717f7b6) | Apr 29, 2024 |
| Dell          | Latitude 5420               | Notebook    | [0a95f2013b](https://linux-hardware.org/?probe=0a95f2013b) | Apr 28, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e2a9d44509](https://linux-hardware.org/?probe=e2a9d44509) | Apr 28, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [6da1776d42](https://linux-hardware.org/?probe=6da1776d42) | Apr 28, 2024 |
| Star Labs     | StarBook                    | Notebook    | [99017e5822](https://linux-hardware.org/?probe=99017e5822) | Apr 28, 2024 |
| HP            | Notebook                    | Notebook    | [6252c3e002](https://linux-hardware.org/?probe=6252c3e002) | Apr 28, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [d314388bb1](https://linux-hardware.org/?probe=d314388bb1) | Apr 28, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ffc336849d](https://linux-hardware.org/?probe=ffc336849d) | Apr 28, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cd0143ba78](https://linux-hardware.org/?probe=cd0143ba78) | Apr 28, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [1af94235a9](https://linux-hardware.org/?probe=1af94235a9) | Apr 28, 2024 |
| Biostar       | Hi-Fi Z87X 3D               | Desktop     | [09d7331f2b](https://linux-hardware.org/?probe=09d7331f2b) | Apr 27, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [29c763baa8](https://linux-hardware.org/?probe=29c763baa8) | Apr 27, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [6b74d2c1b5](https://linux-hardware.org/?probe=6b74d2c1b5) | Apr 27, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [5192e9d32b](https://linux-hardware.org/?probe=5192e9d32b) | Apr 27, 2024 |
| Lenovo        | ThinkStation D20 4155CTO    | Desktop     | [54cae1f375](https://linux-hardware.org/?probe=54cae1f375) | Apr 27, 2024 |
| Acer          | Aspire A314-35              | Notebook    | [b81c267e1b](https://linux-hardware.org/?probe=b81c267e1b) | Apr 27, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [e8f25e02cb](https://linux-hardware.org/?probe=e8f25e02cb) | Apr 27, 2024 |
| HP            | Elite x2 G8 Tablet          | Tablet      | [ce51f2c1ab](https://linux-hardware.org/?probe=ce51f2c1ab) | Apr 26, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [46e559a9de](https://linux-hardware.org/?probe=46e559a9de) | Apr 26, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [14dee832b2](https://linux-hardware.org/?probe=14dee832b2) | Apr 26, 2024 |
| Acer          | Aspire A315-53G             | Notebook    | [2a3e224f63](https://linux-hardware.org/?probe=2a3e224f63) | Apr 26, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ae5dddd784](https://linux-hardware.org/?probe=ae5dddd784) | Apr 25, 2024 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [ae667fce92](https://linux-hardware.org/?probe=ae667fce92) | Apr 25, 2024 |
| ASUSTek       | N751JK                      | Notebook    | [f49afec710](https://linux-hardware.org/?probe=f49afec710) | Apr 25, 2024 |
| Alienware     | M18xR1                      | Notebook    | [d6f3028e98](https://linux-hardware.org/?probe=d6f3028e98) | Apr 25, 2024 |
| HP            | ZBook 15                    | Notebook    | [b5181afe2b](https://linux-hardware.org/?probe=b5181afe2b) | Apr 25, 2024 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [b1502b6440](https://linux-hardware.org/?probe=b1502b6440) | Apr 25, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [e4237a07f0](https://linux-hardware.org/?probe=e4237a07f0) | Apr 24, 2024 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [e74da3b338](https://linux-hardware.org/?probe=e74da3b338) | Apr 24, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8d2850aa6b](https://linux-hardware.org/?probe=8d2850aa6b) | Apr 24, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [a43f744651](https://linux-hardware.org/?probe=a43f744651) | Apr 24, 2024 |
| Lenovo        | G500s 20245                 | Notebook    | [9742cd9e94](https://linux-hardware.org/?probe=9742cd9e94) | Apr 24, 2024 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [758736ef94](https://linux-hardware.org/?probe=758736ef94) | Apr 24, 2024 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [cc1a7f7fef](https://linux-hardware.org/?probe=cc1a7f7fef) | Apr 24, 2024 |
| HP            | 15                          | Notebook    | [4ecce71b7d](https://linux-hardware.org/?probe=4ecce71b7d) | Apr 24, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [719891e7c2](https://linux-hardware.org/?probe=719891e7c2) | Apr 24, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [7e76ea0f76](https://linux-hardware.org/?probe=7e76ea0f76) | Apr 24, 2024 |
| Dell          | Precision M6700             | Notebook    | [cc8f317f9d](https://linux-hardware.org/?probe=cc8f317f9d) | Apr 24, 2024 |
| Toshiba       | STI NI 1401                 | Notebook    | [caed126d9e](https://linux-hardware.org/?probe=caed126d9e) | Apr 24, 2024 |
| Digiboard     | MPxx                        | Desktop     | [e277b1a1d5](https://linux-hardware.org/?probe=e277b1a1d5) | Apr 24, 2024 |
| HP            | 21D0                        | Desktop     | [fe5b1a679c](https://linux-hardware.org/?probe=fe5b1a679c) | Apr 24, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [cf1ac0276a](https://linux-hardware.org/?probe=cf1ac0276a) | Apr 24, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [e25a1d0676](https://linux-hardware.org/?probe=e25a1d0676) | Apr 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2bc3bf2f34](https://linux-hardware.org/?probe=2bc3bf2f34) | Apr 23, 2024 |
| Dell          | 0VNGWR A01                  | All in one  | [b95fa4f6b0](https://linux-hardware.org/?probe=b95fa4f6b0) | Apr 23, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [0a90ca1966](https://linux-hardware.org/?probe=0a90ca1966) | Apr 23, 2024 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [7fc49ffc5f](https://linux-hardware.org/?probe=7fc49ffc5f) | Apr 23, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [6f01a069fa](https://linux-hardware.org/?probe=6f01a069fa) | Apr 23, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [83ab8ba33c](https://linux-hardware.org/?probe=83ab8ba33c) | Apr 23, 2024 |
| Dell          | 0YGYJY A01                  | Desktop     | [c922a511fd](https://linux-hardware.org/?probe=c922a511fd) | Apr 23, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [95453a6898](https://linux-hardware.org/?probe=95453a6898) | Apr 23, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [328456d99c](https://linux-hardware.org/?probe=328456d99c) | Apr 23, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [dbe31bb448](https://linux-hardware.org/?probe=dbe31bb448) | Apr 23, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [72b47f3d18](https://linux-hardware.org/?probe=72b47f3d18) | Apr 23, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [06c04ebd74](https://linux-hardware.org/?probe=06c04ebd74) | Apr 23, 2024 |
| HP            | 8299                        | Desktop     | [e2ee3223fd](https://linux-hardware.org/?probe=e2ee3223fd) | Apr 23, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [894feb1a4d](https://linux-hardware.org/?probe=894feb1a4d) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a7180ee8da](https://linux-hardware.org/?probe=a7180ee8da) | Apr 23, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e79a07e085](https://linux-hardware.org/?probe=e79a07e085) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [cda9b90e74](https://linux-hardware.org/?probe=cda9b90e74) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [922e4ea114](https://linux-hardware.org/?probe=922e4ea114) | Apr 23, 2024 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [864cdaee54](https://linux-hardware.org/?probe=864cdaee54) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a06e5411c0](https://linux-hardware.org/?probe=a06e5411c0) | Apr 23, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [4626c1b15a](https://linux-hardware.org/?probe=4626c1b15a) | Apr 23, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [ab2310f0d6](https://linux-hardware.org/?probe=ab2310f0d6) | Apr 22, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [90e696166f](https://linux-hardware.org/?probe=90e696166f) | Apr 22, 2024 |
| MSI           | CSM-H81M-P32                | Desktop     | [056face9de](https://linux-hardware.org/?probe=056face9de) | Apr 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [a671f5391b](https://linux-hardware.org/?probe=a671f5391b) | Apr 22, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [da3cb2d356](https://linux-hardware.org/?probe=da3cb2d356) | Apr 22, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [92fb8268cc](https://linux-hardware.org/?probe=92fb8268cc) | Apr 22, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [f1d18ed809](https://linux-hardware.org/?probe=f1d18ed809) | Apr 22, 2024 |
| Intel         | X99H                        | Desktop     | [cca155cf13](https://linux-hardware.org/?probe=cca155cf13) | Apr 22, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [68d6575b15](https://linux-hardware.org/?probe=68d6575b15) | Apr 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [4ffd3e632b](https://linux-hardware.org/?probe=4ffd3e632b) | Apr 22, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [ec24097ebe](https://linux-hardware.org/?probe=ec24097ebe) | Apr 22, 2024 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [a3f2909959](https://linux-hardware.org/?probe=a3f2909959) | Apr 22, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a8d83edd62](https://linux-hardware.org/?probe=a8d83edd62) | Apr 22, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [3685be6a35](https://linux-hardware.org/?probe=3685be6a35) | Apr 22, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [0cac32bd87](https://linux-hardware.org/?probe=0cac32bd87) | Apr 22, 2024 |
| AZW           | SER V10                     | Mini pc     | [f8795eab03](https://linux-hardware.org/?probe=f8795eab03) | Apr 22, 2024 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [d7a06f7d8d](https://linux-hardware.org/?probe=d7a06f7d8d) | Apr 22, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [e36ba9916d](https://linux-hardware.org/?probe=e36ba9916d) | Apr 22, 2024 |
| Biostar       | Hi-Fi Z87X 3D               | Desktop     | [8c77d98a43](https://linux-hardware.org/?probe=8c77d98a43) | Apr 21, 2024 |
| Positivo      | S14SL01                     | Notebook    | [4840897917](https://linux-hardware.org/?probe=4840897917) | Apr 21, 2024 |
| Microsoft     | Surface Go                  | Tablet      | [7bc00f9635](https://linux-hardware.org/?probe=7bc00f9635) | Apr 21, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [6c6b1a2edd](https://linux-hardware.org/?probe=6c6b1a2edd) | Apr 21, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [7f5ce15d32](https://linux-hardware.org/?probe=7f5ce15d32) | Apr 21, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [e0c405894c](https://linux-hardware.org/?probe=e0c405894c) | Apr 21, 2024 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [458a4bd2b2](https://linux-hardware.org/?probe=458a4bd2b2) | Apr 21, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c5eedce567](https://linux-hardware.org/?probe=c5eedce567) | Apr 21, 2024 |
| Acer          | RS780DV                     | Desktop     | [2fd4cf8e84](https://linux-hardware.org/?probe=2fd4cf8e84) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2c617e212d](https://linux-hardware.org/?probe=2c617e212d) | Apr 21, 2024 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [6e6ef1d063](https://linux-hardware.org/?probe=6e6ef1d063) | Apr 21, 2024 |
| HP            | ProBook 4530s               | Notebook    | [11f3df5775](https://linux-hardware.org/?probe=11f3df5775) | Apr 21, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9287fd48fd](https://linux-hardware.org/?probe=9287fd48fd) | Apr 21, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [40c04cd535](https://linux-hardware.org/?probe=40c04cd535) | Apr 21, 2024 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [fa784dad84](https://linux-hardware.org/?probe=fa784dad84) | Apr 21, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [b06b4f2ac7](https://linux-hardware.org/?probe=b06b4f2ac7) | Apr 21, 2024 |
| Dell          | Latitude 5440               | Notebook    | [58cc268fb3](https://linux-hardware.org/?probe=58cc268fb3) | Apr 21, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a4e68832be](https://linux-hardware.org/?probe=a4e68832be) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [ceca4cef9c](https://linux-hardware.org/?probe=ceca4cef9c) | Apr 21, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [7b75dbd834](https://linux-hardware.org/?probe=7b75dbd834) | Apr 21, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [dc0120c1ae](https://linux-hardware.org/?probe=dc0120c1ae) | Apr 21, 2024 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | Desktop     | [34da91dacf](https://linux-hardware.org/?probe=34da91dacf) | Apr 21, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9eff554fa4](https://linux-hardware.org/?probe=9eff554fa4) | Apr 21, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [1853702bed](https://linux-hardware.org/?probe=1853702bed) | Apr 21, 2024 |
| Alienware     | x15 R1                      | Notebook    | [63bd9e4e5b](https://linux-hardware.org/?probe=63bd9e4e5b) | Apr 21, 2024 |
| Alienware     | x15 R1                      | Notebook    | [adfa8b3aea](https://linux-hardware.org/?probe=adfa8b3aea) | Apr 21, 2024 |
| HP            | 805B                        | Desktop     | [06e17f3461](https://linux-hardware.org/?probe=06e17f3461) | Apr 21, 2024 |
| HP            | 87D6 SMVB                   | Desktop     | [b3862648a1](https://linux-hardware.org/?probe=b3862648a1) | Apr 21, 2024 |
| ASUSTek       | P6T                         | Desktop     | [d2206947bb](https://linux-hardware.org/?probe=d2206947bb) | Apr 21, 2024 |
| HP            | ProBook 470 G5              | Notebook    | [0c1225132c](https://linux-hardware.org/?probe=0c1225132c) | Apr 21, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [0b3321dc98](https://linux-hardware.org/?probe=0b3321dc98) | Apr 21, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [fdae0762c0](https://linux-hardware.org/?probe=fdae0762c0) | Apr 20, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fea13a098d](https://linux-hardware.org/?probe=fea13a098d) | Apr 20, 2024 |
| Colorful T... | CVN Z690 GAMING FROZEN V... | Desktop     | [09cbde09ca](https://linux-hardware.org/?probe=09cbde09ca) | Apr 20, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [802dfe39ec](https://linux-hardware.org/?probe=802dfe39ec) | Apr 20, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a343ca7f17](https://linux-hardware.org/?probe=a343ca7f17) | Apr 20, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [9836019d80](https://linux-hardware.org/?probe=9836019d80) | Apr 20, 2024 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [98eba50e5b](https://linux-hardware.org/?probe=98eba50e5b) | Apr 20, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [6636df5576](https://linux-hardware.org/?probe=6636df5576) | Apr 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [35685d6f90](https://linux-hardware.org/?probe=35685d6f90) | Apr 20, 2024 |
| Samsung       | 750QFG                      | Convertible | [19c7a1d90b](https://linux-hardware.org/?probe=19c7a1d90b) | Apr 20, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [5b3e452e53](https://linux-hardware.org/?probe=5b3e452e53) | Apr 20, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [94fe70153d](https://linux-hardware.org/?probe=94fe70153d) | Apr 20, 2024 |
| Samsung       | 750QFG                      | Convertible | [958ad1cbf7](https://linux-hardware.org/?probe=958ad1cbf7) | Apr 20, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [0f62918ed2](https://linux-hardware.org/?probe=0f62918ed2) | Apr 20, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e090d79256](https://linux-hardware.org/?probe=e090d79256) | Apr 20, 2024 |
| Valve         | Jupiter                     | Notebook    | [da44a88ec3](https://linux-hardware.org/?probe=da44a88ec3) | Apr 19, 2024 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [bc958fb0e5](https://linux-hardware.org/?probe=bc958fb0e5) | Apr 19, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RW    | Notebook    | [8d5622069d](https://linux-hardware.org/?probe=8d5622069d) | Apr 19, 2024 |
| Lenovo        | ThinkPad T450s 20BWS00V0... | Notebook    | [8d933e8d9e](https://linux-hardware.org/?probe=8d933e8d9e) | Apr 19, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [dad92afe76](https://linux-hardware.org/?probe=dad92afe76) | Apr 19, 2024 |
| Dell          | G15 5530                    | Notebook    | [c1f49dc2d9](https://linux-hardware.org/?probe=c1f49dc2d9) | Apr 19, 2024 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [1f6b5be9dc](https://linux-hardware.org/?probe=1f6b5be9dc) | Apr 19, 2024 |
| Dell          | Latitude E6400              | Notebook    | [d084b4b030](https://linux-hardware.org/?probe=d084b4b030) | Apr 19, 2024 |
| Google        | Shyvana                     | Notebook    | [a0d110b275](https://linux-hardware.org/?probe=a0d110b275) | Apr 19, 2024 |
| Acer          | Aspire A715-43G             | Notebook    | [737b4f2bfb](https://linux-hardware.org/?probe=737b4f2bfb) | Apr 19, 2024 |
| Acer          | Aspire A715-43G             | Notebook    | [b1605729ff](https://linux-hardware.org/?probe=b1605729ff) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [a2fb569143](https://linux-hardware.org/?probe=a2fb569143) | Apr 19, 2024 |
| HP            | Elite x2 G8 Tablet          | Tablet      | [eded3eb6dd](https://linux-hardware.org/?probe=eded3eb6dd) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [b70a3e9c9f](https://linux-hardware.org/?probe=b70a3e9c9f) | Apr 19, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [6b0dd29862](https://linux-hardware.org/?probe=6b0dd29862) | Apr 19, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [6abe6d21fc](https://linux-hardware.org/?probe=6abe6d21fc) | Apr 19, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5de5267a1a](https://linux-hardware.org/?probe=5de5267a1a) | Apr 19, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a813962065](https://linux-hardware.org/?probe=a813962065) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d173c3e7d7](https://linux-hardware.org/?probe=d173c3e7d7) | Apr 18, 2024 |
| Pegatron      | 2AB5                        | Desktop     | [36f9f1b443](https://linux-hardware.org/?probe=36f9f1b443) | Apr 18, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [7e7a28ef89](https://linux-hardware.org/?probe=7e7a28ef89) | Apr 18, 2024 |
| Unknown       | T100                        | Desktop     | [cbe8f3e9af](https://linux-hardware.org/?probe=cbe8f3e9af) | Apr 18, 2024 |
| Unknown       | T100                        | Desktop     | [03f07534d1](https://linux-hardware.org/?probe=03f07534d1) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [43a3e3b36d](https://linux-hardware.org/?probe=43a3e3b36d) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8c079004f7](https://linux-hardware.org/?probe=8c079004f7) | Apr 18, 2024 |
| Dell          | Precision M4800             | Notebook    | [e1bbe5bf56](https://linux-hardware.org/?probe=e1bbe5bf56) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [aaef73d221](https://linux-hardware.org/?probe=aaef73d221) | Apr 18, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [c0cb351a9c](https://linux-hardware.org/?probe=c0cb351a9c) | Apr 18, 2024 |
| MSI           | B450 GAMING PLUS            | Desktop     | [7f84bae081](https://linux-hardware.org/?probe=7f84bae081) | Apr 18, 2024 |
| HP            | EliteBook x360 1030 G4      | Convertible | [019a0a3f80](https://linux-hardware.org/?probe=019a0a3f80) | Apr 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [011644727b](https://linux-hardware.org/?probe=011644727b) | Apr 18, 2024 |
| Samsung       | 730QED                      | Convertible | [c4f2b15449](https://linux-hardware.org/?probe=c4f2b15449) | Apr 18, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [9748a3188e](https://linux-hardware.org/?probe=9748a3188e) | Apr 18, 2024 |
| Acer          | V5-131                      | Notebook    | [5ca622b910](https://linux-hardware.org/?probe=5ca622b910) | Apr 18, 2024 |
| Acer          | V5-131                      | Notebook    | [984da3beb5](https://linux-hardware.org/?probe=984da3beb5) | Apr 18, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59aceeb367](https://linux-hardware.org/?probe=59aceeb367) | Apr 18, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [a344875df9](https://linux-hardware.org/?probe=a344875df9) | Apr 18, 2024 |
| Dell          | Inspiron 15-7568            | Notebook    | [cf77d5e408](https://linux-hardware.org/?probe=cf77d5e408) | Apr 18, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [f225a565f5](https://linux-hardware.org/?probe=f225a565f5) | Apr 18, 2024 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [4e997cc9d3](https://linux-hardware.org/?probe=4e997cc9d3) | Apr 18, 2024 |
| Dell          | Latitude 5310               | Notebook    | [e46914e458](https://linux-hardware.org/?probe=e46914e458) | Apr 17, 2024 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [1b1bec34e3](https://linux-hardware.org/?probe=1b1bec34e3) | Apr 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0eb26f6fcc](https://linux-hardware.org/?probe=0eb26f6fcc) | Apr 17, 2024 |
| ASUSTek       | K53BE                       | Notebook    | [26673bc3d5](https://linux-hardware.org/?probe=26673bc3d5) | Apr 17, 2024 |
| ASRock        | B550 Extreme4               | Desktop     | [6ee8d62842](https://linux-hardware.org/?probe=6ee8d62842) | Apr 17, 2024 |
| Dell          | XPS 9320                    | Notebook    | [572e9a9030](https://linux-hardware.org/?probe=572e9a9030) | Apr 17, 2024 |
| Dell          | XPS 9320                    | Notebook    | [ba5e5d3733](https://linux-hardware.org/?probe=ba5e5d3733) | Apr 17, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [0e9bf013da](https://linux-hardware.org/?probe=0e9bf013da) | Apr 17, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [344e87c2a8](https://linux-hardware.org/?probe=344e87c2a8) | Apr 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [32d8be9f50](https://linux-hardware.org/?probe=32d8be9f50) | Apr 17, 2024 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [a72554e3cd](https://linux-hardware.org/?probe=a72554e3cd) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a776a9677a](https://linux-hardware.org/?probe=a776a9677a) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [4f7d67acb4](https://linux-hardware.org/?probe=4f7d67acb4) | Apr 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [0ce853dae6](https://linux-hardware.org/?probe=0ce853dae6) | Apr 17, 2024 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [47a3594e98](https://linux-hardware.org/?probe=47a3594e98) | Apr 17, 2024 |
| Sony          | VPCEH25EN                   | Notebook    | [3bf6f9edaa](https://linux-hardware.org/?probe=3bf6f9edaa) | Apr 17, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [eb6c0896d5](https://linux-hardware.org/?probe=eb6c0896d5) | Apr 17, 2024 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [ddf96b058d](https://linux-hardware.org/?probe=ddf96b058d) | Apr 17, 2024 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [eea2672841](https://linux-hardware.org/?probe=eea2672841) | Apr 17, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [2a69ec7381](https://linux-hardware.org/?probe=2a69ec7381) | Apr 17, 2024 |
| Dell          | 0P99M4 A01                  | Desktop     | [77e4450298](https://linux-hardware.org/?probe=77e4450298) | Apr 16, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [4ca70a3152](https://linux-hardware.org/?probe=4ca70a3152) | Apr 16, 2024 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [f77a3ef205](https://linux-hardware.org/?probe=f77a3ef205) | Apr 16, 2024 |
| Dell          | 0MWYPT A01                  | Desktop     | [1dcea45437](https://linux-hardware.org/?probe=1dcea45437) | Apr 16, 2024 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [4bc71ebee3](https://linux-hardware.org/?probe=4bc71ebee3) | Apr 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7809a3250e](https://linux-hardware.org/?probe=7809a3250e) | Apr 16, 2024 |
| HP            | 8617                        | Desktop     | [4f55f454d0](https://linux-hardware.org/?probe=4f55f454d0) | Apr 16, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [6877dcd901](https://linux-hardware.org/?probe=6877dcd901) | Apr 16, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4767337e78](https://linux-hardware.org/?probe=4767337e78) | Apr 16, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6110ef887b](https://linux-hardware.org/?probe=6110ef887b) | Apr 16, 2024 |
| Lenovo        | ThinkPad T450s 20BWS00V0... | Notebook    | [763289fa74](https://linux-hardware.org/?probe=763289fa74) | Apr 16, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [a810237e8f](https://linux-hardware.org/?probe=a810237e8f) | Apr 16, 2024 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [a0b18d9fe1](https://linux-hardware.org/?probe=a0b18d9fe1) | Apr 16, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [2e79d9d11e](https://linux-hardware.org/?probe=2e79d9d11e) | Apr 16, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [693ad9a009](https://linux-hardware.org/?probe=693ad9a009) | Apr 16, 2024 |
| ASUSTek       | UX305CA                     | Notebook    | [e25d8c8e00](https://linux-hardware.org/?probe=e25d8c8e00) | Apr 16, 2024 |
| Lenovo        | 1030 SBB0J05441 WIN 3305... | Desktop     | [3370e4360d](https://linux-hardware.org/?probe=3370e4360d) | Apr 16, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [a596d334bf](https://linux-hardware.org/?probe=a596d334bf) | Apr 16, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [13b11b28fc](https://linux-hardware.org/?probe=13b11b28fc) | Apr 16, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [5be1a4715b](https://linux-hardware.org/?probe=5be1a4715b) | Apr 16, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [9ef43fd0f2](https://linux-hardware.org/?probe=9ef43fd0f2) | Apr 16, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [862eca9c16](https://linux-hardware.org/?probe=862eca9c16) | Apr 16, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [5e92237577](https://linux-hardware.org/?probe=5e92237577) | Apr 16, 2024 |
| ASUSTek       | H87-PLUS                    | Desktop     | [7da05aaadf](https://linux-hardware.org/?probe=7da05aaadf) | Apr 16, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [eb9f0768cf](https://linux-hardware.org/?probe=eb9f0768cf) | Apr 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [54ea7f1e25](https://linux-hardware.org/?probe=54ea7f1e25) | Apr 16, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [d74cf44500](https://linux-hardware.org/?probe=d74cf44500) | Apr 16, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [461426c098](https://linux-hardware.org/?probe=461426c098) | Apr 16, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [163f3a262e](https://linux-hardware.org/?probe=163f3a262e) | Apr 15, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [7c4f1e45c9](https://linux-hardware.org/?probe=7c4f1e45c9) | Apr 15, 2024 |
| ASUSTek       | H110M-A                     | Desktop     | [fcc681df4b](https://linux-hardware.org/?probe=fcc681df4b) | Apr 15, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [9e42a69ea4](https://linux-hardware.org/?probe=9e42a69ea4) | Apr 15, 2024 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [ffc28a2270](https://linux-hardware.org/?probe=ffc28a2270) | Apr 15, 2024 |
| Lenovo        | ThinkPad E460 20EUS00000    | Notebook    | [aa85d58506](https://linux-hardware.org/?probe=aa85d58506) | Apr 15, 2024 |
| ASUSTek       | H110M-A                     | Desktop     | [d46d720322](https://linux-hardware.org/?probe=d46d720322) | Apr 15, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [7ff3e868b5](https://linux-hardware.org/?probe=7ff3e868b5) | Apr 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [5378d5a780](https://linux-hardware.org/?probe=5378d5a780) | Apr 15, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CMA... | Notebook    | [9820ac9335](https://linux-hardware.org/?probe=9820ac9335) | Apr 15, 2024 |
| Dell          | 0KJCC5 A00                  | Desktop     | [688001e950](https://linux-hardware.org/?probe=688001e950) | Apr 15, 2024 |
| LG Electro... | 17Z90R-G.AA77G              | Notebook    | [c3c12d00f2](https://linux-hardware.org/?probe=c3c12d00f2) | Apr 15, 2024 |
| HP            | ZBook 15                    | Notebook    | [f581a351ed](https://linux-hardware.org/?probe=f581a351ed) | Apr 15, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [60e642d93c](https://linux-hardware.org/?probe=60e642d93c) | Apr 15, 2024 |
| MSI           | Z270M MORTAR                | Desktop     | [2d81483fa4](https://linux-hardware.org/?probe=2d81483fa4) | Apr 15, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c249f10628](https://linux-hardware.org/?probe=c249f10628) | Apr 15, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [583357f85f](https://linux-hardware.org/?probe=583357f85f) | Apr 15, 2024 |
| LG Electro... | 17Z90R-G.AA77G              | Notebook    | [9adb0d4728](https://linux-hardware.org/?probe=9adb0d4728) | Apr 15, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [8ae1401a90](https://linux-hardware.org/?probe=8ae1401a90) | Apr 14, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [b2bcb4464b](https://linux-hardware.org/?probe=b2bcb4464b) | Apr 14, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [4114d5cfe4](https://linux-hardware.org/?probe=4114d5cfe4) | Apr 14, 2024 |
| Dell          | Precision 5520              | Notebook    | [6a85a306b8](https://linux-hardware.org/?probe=6a85a306b8) | Apr 14, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [c7a6c2d6ed](https://linux-hardware.org/?probe=c7a6c2d6ed) | Apr 14, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [ca106270ee](https://linux-hardware.org/?probe=ca106270ee) | Apr 14, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [aaed2b7478](https://linux-hardware.org/?probe=aaed2b7478) | Apr 14, 2024 |
| ASUSTek       | P10S-I Series               | Desktop     | [c0afefe9bc](https://linux-hardware.org/?probe=c0afefe9bc) | Apr 14, 2024 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [5de5178742](https://linux-hardware.org/?probe=5de5178742) | Apr 14, 2024 |
| HP            | 255 15.6 inch G10           | Notebook    | [b72fb5d156](https://linux-hardware.org/?probe=b72fb5d156) | Apr 14, 2024 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [8ed3523f0a](https://linux-hardware.org/?probe=8ed3523f0a) | Apr 14, 2024 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [e96012759d](https://linux-hardware.org/?probe=e96012759d) | Apr 14, 2024 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [89fbde8b2d](https://linux-hardware.org/?probe=89fbde8b2d) | Apr 14, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [38168a41b4](https://linux-hardware.org/?probe=38168a41b4) | Apr 14, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [4a91844828](https://linux-hardware.org/?probe=4a91844828) | Apr 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [476daae154](https://linux-hardware.org/?probe=476daae154) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5bb8884eee](https://linux-hardware.org/?probe=5bb8884eee) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [841b3d5f2e](https://linux-hardware.org/?probe=841b3d5f2e) | Apr 14, 2024 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [5e533a401e](https://linux-hardware.org/?probe=5e533a401e) | Apr 14, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [776d567b36](https://linux-hardware.org/?probe=776d567b36) | Apr 14, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [31da76530e](https://linux-hardware.org/?probe=31da76530e) | Apr 13, 2024 |
| Dell          | Latitude E6420              | Notebook    | [713c9b9514](https://linux-hardware.org/?probe=713c9b9514) | Apr 13, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [7af65eace4](https://linux-hardware.org/?probe=7af65eace4) | Apr 13, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [2bb2f2f042](https://linux-hardware.org/?probe=2bb2f2f042) | Apr 13, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [702273a412](https://linux-hardware.org/?probe=702273a412) | Apr 13, 2024 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [cf8e423d4c](https://linux-hardware.org/?probe=cf8e423d4c) | Apr 13, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [abbfebcf21](https://linux-hardware.org/?probe=abbfebcf21) | Apr 13, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [75ef2f2d7a](https://linux-hardware.org/?probe=75ef2f2d7a) | Apr 13, 2024 |
| HP            | ProBook 450 G0              | Notebook    | [686202a739](https://linux-hardware.org/?probe=686202a739) | Apr 13, 2024 |
| HP            | 1905                        | Desktop     | [85c5b91f0d](https://linux-hardware.org/?probe=85c5b91f0d) | Apr 13, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8ac09a4b58](https://linux-hardware.org/?probe=8ac09a4b58) | Apr 13, 2024 |
| Acer          | Spin SP513-55N              | Convertible | [7592d772c2](https://linux-hardware.org/?probe=7592d772c2) | Apr 13, 2024 |
| MSI           | B450 GAMING PLUS            | Desktop     | [fe95b1e7e7](https://linux-hardware.org/?probe=fe95b1e7e7) | Apr 13, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c5720fd484](https://linux-hardware.org/?probe=c5720fd484) | Apr 13, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [bebccc0dd1](https://linux-hardware.org/?probe=bebccc0dd1) | Apr 13, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [1015688c75](https://linux-hardware.org/?probe=1015688c75) | Apr 13, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [c4c0c27585](https://linux-hardware.org/?probe=c4c0c27585) | Apr 13, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [84a01ab668](https://linux-hardware.org/?probe=84a01ab668) | Apr 13, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [df30810cbe](https://linux-hardware.org/?probe=df30810cbe) | Apr 13, 2024 |
| Gigabyte      | H81M-DS2                    | Desktop     | [b8407eb44d](https://linux-hardware.org/?probe=b8407eb44d) | Apr 13, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [02b8d8e933](https://linux-hardware.org/?probe=02b8d8e933) | Apr 12, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [b93bba8226](https://linux-hardware.org/?probe=b93bba8226) | Apr 12, 2024 |
| HP            | ProBook 6570b               | Notebook    | [d17831e754](https://linux-hardware.org/?probe=d17831e754) | Apr 12, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [8b8b4193c8](https://linux-hardware.org/?probe=8b8b4193c8) | Apr 12, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [aa96253b80](https://linux-hardware.org/?probe=aa96253b80) | Apr 12, 2024 |
| ASUSTek       | K52Je                       | Notebook    | [7cfd3a8614](https://linux-hardware.org/?probe=7cfd3a8614) | Apr 12, 2024 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [f0de46fc9a](https://linux-hardware.org/?probe=f0de46fc9a) | Apr 12, 2024 |
| HP            | ProBook 450 G0              | Notebook    | [becdc6cf99](https://linux-hardware.org/?probe=becdc6cf99) | Apr 12, 2024 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [4f51073d9c](https://linux-hardware.org/?probe=4f51073d9c) | Apr 12, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [16f0af2047](https://linux-hardware.org/?probe=16f0af2047) | Apr 12, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [2ee7ec3b1f](https://linux-hardware.org/?probe=2ee7ec3b1f) | Apr 12, 2024 |
| Dell          | G15 5510                    | Notebook    | [9820798256](https://linux-hardware.org/?probe=9820798256) | Apr 12, 2024 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [dcabc6c4f7](https://linux-hardware.org/?probe=dcabc6c4f7) | Apr 12, 2024 |
| Pegatron      | H81-M1                      | Desktop     | [ad6b67560b](https://linux-hardware.org/?probe=ad6b67560b) | Apr 12, 2024 |
| HP            | Split 13 x2 Detachable P... | Notebook    | [17c8956856](https://linux-hardware.org/?probe=17c8956856) | Apr 12, 2024 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [533488aa1d](https://linux-hardware.org/?probe=533488aa1d) | Apr 12, 2024 |
| Dell          | XPS 9315                    | Notebook    | [a034dc4942](https://linux-hardware.org/?probe=a034dc4942) | Apr 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [77db3dff9e](https://linux-hardware.org/?probe=77db3dff9e) | Apr 12, 2024 |
| Dell          | Inspiron 15-7568            | Notebook    | [939c6125de](https://linux-hardware.org/?probe=939c6125de) | Apr 12, 2024 |
| MSI           | B350M GAMING PRO            | Desktop     | [448a1d81fb](https://linux-hardware.org/?probe=448a1d81fb) | Apr 12, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [6a4269d6d1](https://linux-hardware.org/?probe=6a4269d6d1) | Apr 12, 2024 |
| ASUSTek       | K52Je                       | Notebook    | [e825e3871d](https://linux-hardware.org/?probe=e825e3871d) | Apr 12, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [5f48d3ede1](https://linux-hardware.org/?probe=5f48d3ede1) | Apr 12, 2024 |
| MSI           | B350M GAMING PRO            | Desktop     | [25ed2372d0](https://linux-hardware.org/?probe=25ed2372d0) | Apr 12, 2024 |
| Juana Mans... | SF20GM7                     | Notebook    | [2a01eeac36](https://linux-hardware.org/?probe=2a01eeac36) | Apr 12, 2024 |
| Lenovo        | ThinkPad T580 20L9001EUS    | Notebook    | [95d21ed0f1](https://linux-hardware.org/?probe=95d21ed0f1) | Apr 12, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | Notebook    | [fd2fc14275](https://linux-hardware.org/?probe=fd2fc14275) | Apr 12, 2024 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [d81a8d46ed](https://linux-hardware.org/?probe=d81a8d46ed) | Apr 12, 2024 |
| Acer          | Nitro ANV15-51              | Notebook    | [b78fb4e0df](https://linux-hardware.org/?probe=b78fb4e0df) | Apr 12, 2024 |
| Dell          | Precision 5750              | Notebook    | [f59c1fa6c6](https://linux-hardware.org/?probe=f59c1fa6c6) | Apr 12, 2024 |
| Lenovo        | ThinkPad T580 20L9001EUS    | Notebook    | [9f0cfb04b0](https://linux-hardware.org/?probe=9f0cfb04b0) | Apr 12, 2024 |
| Toshiba       | Satellite C70-B             | Notebook    | [305c87ae5d](https://linux-hardware.org/?probe=305c87ae5d) | Apr 12, 2024 |
| Timi          | TM1701                      | Notebook    | [0af4854c82](https://linux-hardware.org/?probe=0af4854c82) | Apr 12, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [f6720efacd](https://linux-hardware.org/?probe=f6720efacd) | Apr 11, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [c614d887b6](https://linux-hardware.org/?probe=c614d887b6) | Apr 11, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f7ab9249b4](https://linux-hardware.org/?probe=f7ab9249b4) | Apr 11, 2024 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [8efe50aabf](https://linux-hardware.org/?probe=8efe50aabf) | Apr 11, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [6fd7de9ca4](https://linux-hardware.org/?probe=6fd7de9ca4) | Apr 11, 2024 |
| ASRock        | H77 Pro4-M                  | Desktop     | [7b10a71ade](https://linux-hardware.org/?probe=7b10a71ade) | Apr 11, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [1234bcb2a4](https://linux-hardware.org/?probe=1234bcb2a4) | Apr 11, 2024 |
| SZQFTX        | MI2-SC                      | Desktop     | [be8172007e](https://linux-hardware.org/?probe=be8172007e) | Apr 11, 2024 |
| Intel         | B365                        | Desktop     | [7abeea79f6](https://linux-hardware.org/?probe=7abeea79f6) | Apr 11, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [988ea47737](https://linux-hardware.org/?probe=988ea47737) | Apr 11, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [a02fa9c7cf](https://linux-hardware.org/?probe=a02fa9c7cf) | Apr 11, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [3d83075443](https://linux-hardware.org/?probe=3d83075443) | Apr 11, 2024 |
| Dell          | Inspiron 5566               | Notebook    | [bd5c43f6c8](https://linux-hardware.org/?probe=bd5c43f6c8) | Apr 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S29D0W    | Notebook    | [7d55e2a84d](https://linux-hardware.org/?probe=7d55e2a84d) | Apr 11, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | Notebook    | [52de364ea7](https://linux-hardware.org/?probe=52de364ea7) | Apr 11, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [2294836c34](https://linux-hardware.org/?probe=2294836c34) | Apr 11, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [1d9ef42930](https://linux-hardware.org/?probe=1d9ef42930) | Apr 11, 2024 |
| Dell          | Studio 1558                 | Notebook    | [195acc75cf](https://linux-hardware.org/?probe=195acc75cf) | Apr 10, 2024 |
| Dell          | Studio 1558                 | Notebook    | [92678a06a0](https://linux-hardware.org/?probe=92678a06a0) | Apr 10, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | Notebook    | [38d04908c1](https://linux-hardware.org/?probe=38d04908c1) | Apr 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S5QH00    | Notebook    | [5068f44f3b](https://linux-hardware.org/?probe=5068f44f3b) | Apr 10, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [301474cde1](https://linux-hardware.org/?probe=301474cde1) | Apr 10, 2024 |
| Dell          | Precision 3571              | Notebook    | [6bef26b856](https://linux-hardware.org/?probe=6bef26b856) | Apr 10, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [ef8d387984](https://linux-hardware.org/?probe=ef8d387984) | Apr 10, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [4ec86b2e5d](https://linux-hardware.org/?probe=4ec86b2e5d) | Apr 10, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9a15677135](https://linux-hardware.org/?probe=9a15677135) | Apr 10, 2024 |
| Gigabyte      | B550M GAMING                | Desktop     | [d85fa6cbe3](https://linux-hardware.org/?probe=d85fa6cbe3) | Apr 10, 2024 |
| Dell          | Precision M6800             | Notebook    | [fbdc7e53c6](https://linux-hardware.org/?probe=fbdc7e53c6) | Apr 10, 2024 |
| Lenovo        | 3306 SDK0T76528 WIN 3556... | All in one  | [06b63083c7](https://linux-hardware.org/?probe=06b63083c7) | Apr 10, 2024 |
| Alienware     | m15 R7 AMD                  | Notebook    | [effd96032c](https://linux-hardware.org/?probe=effd96032c) | Apr 10, 2024 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [afbcbc9b57](https://linux-hardware.org/?probe=afbcbc9b57) | Apr 10, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [eadf15884b](https://linux-hardware.org/?probe=eadf15884b) | Apr 10, 2024 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [e86ef24429](https://linux-hardware.org/?probe=e86ef24429) | Apr 10, 2024 |
| MSI           | Raider GE66 12UGS           | Notebook    | [e45ec711e7](https://linux-hardware.org/?probe=e45ec711e7) | Apr 10, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [184f279e1e](https://linux-hardware.org/?probe=184f279e1e) | Apr 10, 2024 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [a8283e57e1](https://linux-hardware.org/?probe=a8283e57e1) | Apr 10, 2024 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [63c063feab](https://linux-hardware.org/?probe=63c063feab) | Apr 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0a7b693def](https://linux-hardware.org/?probe=0a7b693def) | Apr 10, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | Notebook    | [f892422654](https://linux-hardware.org/?probe=f892422654) | Apr 10, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [4d6466d304](https://linux-hardware.org/?probe=4d6466d304) | Apr 10, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [73ef8a88c7](https://linux-hardware.org/?probe=73ef8a88c7) | Apr 10, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [5b99de1b59](https://linux-hardware.org/?probe=5b99de1b59) | Apr 10, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [be0f54854d](https://linux-hardware.org/?probe=be0f54854d) | Apr 10, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [716e9907f4](https://linux-hardware.org/?probe=716e9907f4) | Apr 10, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [41bec233fb](https://linux-hardware.org/?probe=41bec233fb) | Apr 10, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [1761f221f8](https://linux-hardware.org/?probe=1761f221f8) | Apr 09, 2024 |
| Dell          | 030VXY A01                  | Desktop     | [793be088c2](https://linux-hardware.org/?probe=793be088c2) | Apr 09, 2024 |
| Dell          | 030VXY A01                  | Desktop     | [64ed2bb4d3](https://linux-hardware.org/?probe=64ed2bb4d3) | Apr 09, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [84b8f6128b](https://linux-hardware.org/?probe=84b8f6128b) | Apr 09, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [752982118a](https://linux-hardware.org/?probe=752982118a) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1c025781a3](https://linux-hardware.org/?probe=1c025781a3) | Apr 09, 2024 |
| Digiboard     | MPxx                        | Desktop     | [fe1ed8d822](https://linux-hardware.org/?probe=fe1ed8d822) | Apr 09, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [e033d32271](https://linux-hardware.org/?probe=e033d32271) | Apr 09, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d712921459](https://linux-hardware.org/?probe=d712921459) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d21570a024](https://linux-hardware.org/?probe=d21570a024) | Apr 09, 2024 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cb1ab91477](https://linux-hardware.org/?probe=cb1ab91477) | Apr 09, 2024 |
| Dell          | Latitude 7420               | Notebook    | [8dc657f9e2](https://linux-hardware.org/?probe=8dc657f9e2) | Apr 09, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [2c7e501a12](https://linux-hardware.org/?probe=2c7e501a12) | Apr 09, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [717e8590bb](https://linux-hardware.org/?probe=717e8590bb) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3ed13a3d8a](https://linux-hardware.org/?probe=3ed13a3d8a) | Apr 09, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | Notebook    | [c08adc1120](https://linux-hardware.org/?probe=c08adc1120) | Apr 09, 2024 |
| Foxconn       | H55MX-S Series              | Desktop     | [e659b4546f](https://linux-hardware.org/?probe=e659b4546f) | Apr 09, 2024 |
| Alienware     | 0XJKKD A01                  | Desktop     | [891952c62d](https://linux-hardware.org/?probe=891952c62d) | Apr 09, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [7e40bc4b0a](https://linux-hardware.org/?probe=7e40bc4b0a) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [32842b7d56](https://linux-hardware.org/?probe=32842b7d56) | Apr 09, 2024 |
| Foxconn       | H55MX-S Series              | Desktop     | [93deba6ce5](https://linux-hardware.org/?probe=93deba6ce5) | Apr 09, 2024 |
| ASRock        | B550M-C                     | Desktop     | [dd5090a053](https://linux-hardware.org/?probe=dd5090a053) | Apr 09, 2024 |
| Toshiba       | Satellite L750              | Notebook    | [296a0d80a0](https://linux-hardware.org/?probe=296a0d80a0) | Apr 09, 2024 |
| Alienware     | 07HV66 A01                  | Desktop     | [5557c9197d](https://linux-hardware.org/?probe=5557c9197d) | Apr 09, 2024 |
| Itautec       | ST 4265                     | Desktop     | [256c04b1e3](https://linux-hardware.org/?probe=256c04b1e3) | Apr 09, 2024 |
| Alienware     | m18 R1 AMD                  | Notebook    | [8031bfa7f7](https://linux-hardware.org/?probe=8031bfa7f7) | Apr 08, 2024 |
| Itautec       | ST 4265                     | Desktop     | [052c74a17d](https://linux-hardware.org/?probe=052c74a17d) | Apr 08, 2024 |
| Acer          | Aspire 5750ZG               | Notebook    | [b80881ad3d](https://linux-hardware.org/?probe=b80881ad3d) | Apr 08, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [f27647e9bb](https://linux-hardware.org/?probe=f27647e9bb) | Apr 08, 2024 |
| Dell          | Precision M4800             | Notebook    | [3ec884f458](https://linux-hardware.org/?probe=3ec884f458) | Apr 08, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [cc080ae6d6](https://linux-hardware.org/?probe=cc080ae6d6) | Apr 08, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [9d9dacedb7](https://linux-hardware.org/?probe=9d9dacedb7) | Apr 08, 2024 |
| Timi          | Mi NoteBook Pro             | Notebook    | [ab28993dd3](https://linux-hardware.org/?probe=ab28993dd3) | Apr 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [97879c1052](https://linux-hardware.org/?probe=97879c1052) | Apr 08, 2024 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [e9cd6d780b](https://linux-hardware.org/?probe=e9cd6d780b) | Apr 08, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [3e60ae1de4](https://linux-hardware.org/?probe=3e60ae1de4) | Apr 08, 2024 |
| AYANEO        | GEEK 1S                     | Tablet      | [2b4664da0c](https://linux-hardware.org/?probe=2b4664da0c) | Apr 08, 2024 |
| Dell          | Latitude 3410               | Notebook    | [0922287873](https://linux-hardware.org/?probe=0922287873) | Apr 08, 2024 |
| HP            | 8595                        | Desktop     | [75999844ff](https://linux-hardware.org/?probe=75999844ff) | Apr 08, 2024 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [67cdf98b8b](https://linux-hardware.org/?probe=67cdf98b8b) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3c71179d12](https://linux-hardware.org/?probe=3c71179d12) | Apr 08, 2024 |
| HP            | 8595                        | Desktop     | [78e64097d4](https://linux-hardware.org/?probe=78e64097d4) | Apr 08, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [62d0c49e82](https://linux-hardware.org/?probe=62d0c49e82) | Apr 08, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [96e5d2941a](https://linux-hardware.org/?probe=96e5d2941a) | Apr 08, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [abc57ed409](https://linux-hardware.org/?probe=abc57ed409) | Apr 08, 2024 |
| HP            | 2000                        | Notebook    | [1dd10f95ab](https://linux-hardware.org/?probe=1dd10f95ab) | Apr 08, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [8ebbe74fff](https://linux-hardware.org/?probe=8ebbe74fff) | Apr 08, 2024 |
| HP            | 2000                        | Notebook    | [023731233e](https://linux-hardware.org/?probe=023731233e) | Apr 08, 2024 |
| HP            | 2B38                        | Desktop     | [db7129fcde](https://linux-hardware.org/?probe=db7129fcde) | Apr 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [0553161eac](https://linux-hardware.org/?probe=0553161eac) | Apr 07, 2024 |
| Toshiba       | dynabook T554/45LB          | Notebook    | [da72e21681](https://linux-hardware.org/?probe=da72e21681) | Apr 07, 2024 |
| HP            | 2B38                        | Desktop     | [44386f0027](https://linux-hardware.org/?probe=44386f0027) | Apr 07, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7d61a78399](https://linux-hardware.org/?probe=7d61a78399) | Apr 07, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4461108096](https://linux-hardware.org/?probe=4461108096) | Apr 07, 2024 |
| Dell          | Precision 3571              | Notebook    | [fdab7d40f5](https://linux-hardware.org/?probe=fdab7d40f5) | Apr 07, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [57145c3161](https://linux-hardware.org/?probe=57145c3161) | Apr 07, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [5a07da097a](https://linux-hardware.org/?probe=5a07da097a) | Apr 07, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [bbdb88ab07](https://linux-hardware.org/?probe=bbdb88ab07) | Apr 07, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [ac1e80470e](https://linux-hardware.org/?probe=ac1e80470e) | Apr 07, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [0d3fb54918](https://linux-hardware.org/?probe=0d3fb54918) | Apr 07, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [daefa26759](https://linux-hardware.org/?probe=daefa26759) | Apr 07, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [87286d8d57](https://linux-hardware.org/?probe=87286d8d57) | Apr 07, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9d2377e611](https://linux-hardware.org/?probe=9d2377e611) | Apr 07, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [e499150ab3](https://linux-hardware.org/?probe=e499150ab3) | Apr 07, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [a06329df00](https://linux-hardware.org/?probe=a06329df00) | Apr 07, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [b35623df85](https://linux-hardware.org/?probe=b35623df85) | Apr 07, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [67dad6a68c](https://linux-hardware.org/?probe=67dad6a68c) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5d346ffec7](https://linux-hardware.org/?probe=5d346ffec7) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f40831832](https://linux-hardware.org/?probe=3f40831832) | Apr 07, 2024 |
| Intel         | X99                         | Desktop     | [7dca188f3d](https://linux-hardware.org/?probe=7dca188f3d) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [46543ad5d6](https://linux-hardware.org/?probe=46543ad5d6) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5368ebb47](https://linux-hardware.org/?probe=b5368ebb47) | Apr 07, 2024 |
| Intel         | X99                         | Desktop     | [8821705436](https://linux-hardware.org/?probe=8821705436) | Apr 07, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [d0dc207772](https://linux-hardware.org/?probe=d0dc207772) | Apr 07, 2024 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [782d5db9e2](https://linux-hardware.org/?probe=782d5db9e2) | Apr 06, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4a15d1a355](https://linux-hardware.org/?probe=4a15d1a355) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [5d0259d7a1](https://linux-hardware.org/?probe=5d0259d7a1) | Apr 06, 2024 |
| Timi          | Mi NoteBook Pro             | Notebook    | [96fefe11d7](https://linux-hardware.org/?probe=96fefe11d7) | Apr 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [278e4869ad](https://linux-hardware.org/?probe=278e4869ad) | Apr 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [65816fc70b](https://linux-hardware.org/?probe=65816fc70b) | Apr 06, 2024 |
| HP            | 870C                        | Desktop     | [eb08ffa35d](https://linux-hardware.org/?probe=eb08ffa35d) | Apr 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [595c1e3d71](https://linux-hardware.org/?probe=595c1e3d71) | Apr 06, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ed719f8ced](https://linux-hardware.org/?probe=ed719f8ced) | Apr 06, 2024 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [0bb98b6d5d](https://linux-hardware.org/?probe=0bb98b6d5d) | Apr 06, 2024 |
| SCHNEIDER     | SCL141CTP                   | Notebook    | [33e14fe576](https://linux-hardware.org/?probe=33e14fe576) | Apr 06, 2024 |
| HUAWEI        | KLVF-XX                     | Notebook    | [775f139f3b](https://linux-hardware.org/?probe=775f139f3b) | Apr 06, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [da60008a10](https://linux-hardware.org/?probe=da60008a10) | Apr 06, 2024 |
| Lenovo        | ThinkPad T480s 20L7001NG... | Notebook    | [ec916e14d1](https://linux-hardware.org/?probe=ec916e14d1) | Apr 06, 2024 |
| HUAWEI        | KLVF-XX                     | Notebook    | [6d24eb8f58](https://linux-hardware.org/?probe=6d24eb8f58) | Apr 06, 2024 |
| Apple         | Mac-F2238AC8                | All in one  | [62598c6d50](https://linux-hardware.org/?probe=62598c6d50) | Apr 06, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [f675a67959](https://linux-hardware.org/?probe=f675a67959) | Apr 06, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [6fd20472e0](https://linux-hardware.org/?probe=6fd20472e0) | Apr 06, 2024 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [4c0e6e4b31](https://linux-hardware.org/?probe=4c0e6e4b31) | Apr 06, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [abf1d82267](https://linux-hardware.org/?probe=abf1d82267) | Apr 06, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [e4ace3a2df](https://linux-hardware.org/?probe=e4ace3a2df) | Apr 06, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [bae1a9abd7](https://linux-hardware.org/?probe=bae1a9abd7) | Apr 06, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [b99319c775](https://linux-hardware.org/?probe=b99319c775) | Apr 06, 2024 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [971729512a](https://linux-hardware.org/?probe=971729512a) | Apr 06, 2024 |
| Google        | Voxel                       | Notebook    | [7c1c455196](https://linux-hardware.org/?probe=7c1c455196) | Apr 06, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [62cd5c6263](https://linux-hardware.org/?probe=62cd5c6263) | Apr 06, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [9f2cc7f5dc](https://linux-hardware.org/?probe=9f2cc7f5dc) | Apr 06, 2024 |
| Foxconn       | H55MX-S Series              | Desktop     | [57dab83b95](https://linux-hardware.org/?probe=57dab83b95) | Apr 06, 2024 |
| Foxconn       | H55MX-S Series              | Desktop     | [111eb94f46](https://linux-hardware.org/?probe=111eb94f46) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [5bc8966967](https://linux-hardware.org/?probe=5bc8966967) | Apr 06, 2024 |
| Lenovo        | ThinkPad P52 20MAS1DM00     | Notebook    | [c83b503bb6](https://linux-hardware.org/?probe=c83b503bb6) | Apr 06, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [ae8d66a693](https://linux-hardware.org/?probe=ae8d66a693) | Apr 06, 2024 |
| Google        | Bluebird                    | Notebook    | [a41a0e7278](https://linux-hardware.org/?probe=a41a0e7278) | Apr 06, 2024 |
| Lenovo        | 3307 NOK                    | Mini pc     | [06b644930d](https://linux-hardware.org/?probe=06b644930d) | Apr 05, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [bae97d2c1c](https://linux-hardware.org/?probe=bae97d2c1c) | Apr 05, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [68d2448180](https://linux-hardware.org/?probe=68d2448180) | Apr 05, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [47c56bd4ee](https://linux-hardware.org/?probe=47c56bd4ee) | Apr 05, 2024 |
| HUAWEI        | MRGF-XX                     | Notebook    | [aeccfe5e22](https://linux-hardware.org/?probe=aeccfe5e22) | Apr 05, 2024 |
| Win elemen... | M600                        | Desktop     | [9f4d0b35c6](https://linux-hardware.org/?probe=9f4d0b35c6) | Apr 05, 2024 |
| Win elemen... | M600                        | Desktop     | [bed5926e13](https://linux-hardware.org/?probe=bed5926e13) | Apr 05, 2024 |
| Framework     | Laptop                      | Notebook    | [3349129590](https://linux-hardware.org/?probe=3349129590) | Apr 05, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6496d4176b](https://linux-hardware.org/?probe=6496d4176b) | Apr 05, 2024 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [a7245399da](https://linux-hardware.org/?probe=a7245399da) | Apr 05, 2024 |
| Haier         | Y11C                        | Notebook    | [412c266aec](https://linux-hardware.org/?probe=412c266aec) | Apr 05, 2024 |
| MSI           | PRO B760-VC WIFI            | Desktop     | [f6466041c0](https://linux-hardware.org/?probe=f6466041c0) | Apr 05, 2024 |
| Lenovo        | ThinkPad E580 20KS003LCA    | Notebook    | [a6320acff1](https://linux-hardware.org/?probe=a6320acff1) | Apr 05, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [490811d61a](https://linux-hardware.org/?probe=490811d61a) | Apr 05, 2024 |
| OEM           | X99-Turbo                   | Desktop     | [ad20e3f989](https://linux-hardware.org/?probe=ad20e3f989) | Apr 05, 2024 |
| MSI           | PRO B760-VC WIFI            | Desktop     | [2847b39ae3](https://linux-hardware.org/?probe=2847b39ae3) | Apr 05, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [912bbd56b1](https://linux-hardware.org/?probe=912bbd56b1) | Apr 05, 2024 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [943c2e486a](https://linux-hardware.org/?probe=943c2e486a) | Apr 05, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [fb9702f65e](https://linux-hardware.org/?probe=fb9702f65e) | Apr 05, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FF... | Notebook    | [9cceb657f4](https://linux-hardware.org/?probe=9cceb657f4) | Apr 05, 2024 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [15b41ef5b3](https://linux-hardware.org/?probe=15b41ef5b3) | Apr 04, 2024 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [2edfed7d6c](https://linux-hardware.org/?probe=2edfed7d6c) | Apr 04, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [77e3ddbb44](https://linux-hardware.org/?probe=77e3ddbb44) | Apr 04, 2024 |
| Dell          | 07N90W A02                  | Desktop     | [4d11f26d4c](https://linux-hardware.org/?probe=4d11f26d4c) | Apr 04, 2024 |
| ASRock        | B550M-C                     | Desktop     | [7601b80b80](https://linux-hardware.org/?probe=7601b80b80) | Apr 04, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [5179c6e5f3](https://linux-hardware.org/?probe=5179c6e5f3) | Apr 04, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [a9490d11d7](https://linux-hardware.org/?probe=a9490d11d7) | Apr 04, 2024 |
| Chuwi         | UBook XPro                  | Notebook    | [f7f05e8aa2](https://linux-hardware.org/?probe=f7f05e8aa2) | Apr 04, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [b8436b6a3c](https://linux-hardware.org/?probe=b8436b6a3c) | Apr 04, 2024 |
| Acer          | Aspire V5-572G              | Notebook    | [ca5e1f767e](https://linux-hardware.org/?probe=ca5e1f767e) | Apr 04, 2024 |
| Dell          | Inspiron 5566               | Notebook    | [a22633719c](https://linux-hardware.org/?probe=a22633719c) | Apr 04, 2024 |
| MSI           | GX780R/GT780R/GT780DXR      | Notebook    | [c4e752d06c](https://linux-hardware.org/?probe=c4e752d06c) | Apr 04, 2024 |
| MSI           | GX780R/GT780R/GT780DXR      | Notebook    | [100d6d2fcd](https://linux-hardware.org/?probe=100d6d2fcd) | Apr 04, 2024 |
| Dell          | 0P99M4 A01                  | Desktop     | [7a869aaf6e](https://linux-hardware.org/?probe=7a869aaf6e) | Apr 04, 2024 |
| HP            | 2175                        | Desktop     | [d21c1aaf46](https://linux-hardware.org/?probe=d21c1aaf46) | Apr 04, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [6ea19c4f02](https://linux-hardware.org/?probe=6ea19c4f02) | Apr 04, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [ba3e37736d](https://linux-hardware.org/?probe=ba3e37736d) | Apr 04, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582HS_... | Notebook    | [ab6e09c508](https://linux-hardware.org/?probe=ab6e09c508) | Apr 04, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1dd4bee031](https://linux-hardware.org/?probe=1dd4bee031) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [323bf9fa10](https://linux-hardware.org/?probe=323bf9fa10) | Apr 04, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [d52b8f5295](https://linux-hardware.org/?probe=d52b8f5295) | Apr 04, 2024 |
| HP            | 8590                        | Notebook    | [2d3f6d27a2](https://linux-hardware.org/?probe=2d3f6d27a2) | Apr 04, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [c7e57e0c0b](https://linux-hardware.org/?probe=c7e57e0c0b) | Apr 04, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [8856db4940](https://linux-hardware.org/?probe=8856db4940) | Apr 04, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [38feac2aaa](https://linux-hardware.org/?probe=38feac2aaa) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [c41823fc76](https://linux-hardware.org/?probe=c41823fc76) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [09a8421999](https://linux-hardware.org/?probe=09a8421999) | Apr 04, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c5ce1039fa](https://linux-hardware.org/?probe=c5ce1039fa) | Apr 04, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [bf0d1ddab3](https://linux-hardware.org/?probe=bf0d1ddab3) | Apr 04, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [86c8aec82f](https://linux-hardware.org/?probe=86c8aec82f) | Apr 04, 2024 |
| Intel         | B75 V124A                   | Desktop     | [df800a1252](https://linux-hardware.org/?probe=df800a1252) | Apr 04, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [071d177bf5](https://linux-hardware.org/?probe=071d177bf5) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU605MI... | Notebook    | [4581288732](https://linux-hardware.org/?probe=4581288732) | Apr 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8946117fdf](https://linux-hardware.org/?probe=8946117fdf) | Apr 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [c38ed1feec](https://linux-hardware.org/?probe=c38ed1feec) | Apr 03, 2024 |
| HP            | Pro Tablet 10 EE G1         | Notebook    | [364cf44bfa](https://linux-hardware.org/?probe=364cf44bfa) | Apr 03, 2024 |
| HP            | Pro Tablet 10 EE G1         | Notebook    | [a76cafaf48](https://linux-hardware.org/?probe=a76cafaf48) | Apr 03, 2024 |
| Dell          | Latitude 9440 2-in-1        | Convertible | [705dbea40c](https://linux-hardware.org/?probe=705dbea40c) | Apr 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2768c4333f](https://linux-hardware.org/?probe=2768c4333f) | Apr 03, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21BN0... | Notebook    | [91168e1623](https://linux-hardware.org/?probe=91168e1623) | Apr 03, 2024 |
| HP            | 1497                        | Desktop     | [86bbef8ff3](https://linux-hardware.org/?probe=86bbef8ff3) | Apr 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4eb39c2cf0](https://linux-hardware.org/?probe=4eb39c2cf0) | Apr 03, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [10a4a26f0e](https://linux-hardware.org/?probe=10a4a26f0e) | Apr 03, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [3c05445a49](https://linux-hardware.org/?probe=3c05445a49) | Apr 03, 2024 |
| ASUSTek       | Zenbook UX8402VU_UX8402V... | Notebook    | [2cea574673](https://linux-hardware.org/?probe=2cea574673) | Apr 03, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [e0b3cba959](https://linux-hardware.org/?probe=e0b3cba959) | Apr 03, 2024 |
| HP            | 8434 11                     | Desktop     | [a1a62e20a4](https://linux-hardware.org/?probe=a1a62e20a4) | Apr 03, 2024 |
| HP            | 1495                        | Desktop     | [7bb71cc6c8](https://linux-hardware.org/?probe=7bb71cc6c8) | Apr 03, 2024 |
| HP            | 1495                        | Desktop     | [369904b953](https://linux-hardware.org/?probe=369904b953) | Apr 03, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [bdff9c20d1](https://linux-hardware.org/?probe=bdff9c20d1) | Apr 03, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [60c648fc52](https://linux-hardware.org/?probe=60c648fc52) | Apr 03, 2024 |
| Dell          | Latitude E6400              | Notebook    | [bb95390cc4](https://linux-hardware.org/?probe=bb95390cc4) | Apr 03, 2024 |
| Dell          | Latitude E6400              | Notebook    | [39d6e5102c](https://linux-hardware.org/?probe=39d6e5102c) | Apr 03, 2024 |
| Lenovo        | 3709 SDK0J40700 WIN 3258... | Desktop     | [1e11e401a4](https://linux-hardware.org/?probe=1e11e401a4) | Apr 03, 2024 |
| Dell          | Inspiron 15 3525            | Notebook    | [76e8934737](https://linux-hardware.org/?probe=76e8934737) | Apr 03, 2024 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [dd2a60e142](https://linux-hardware.org/?probe=dd2a60e142) | Apr 03, 2024 |
| ASRock        | B650M-H/M.2+                | Desktop     | [2e3ed0f79c](https://linux-hardware.org/?probe=2e3ed0f79c) | Apr 02, 2024 |
| Lenovo        | ThinkPad L530 24793J2       | Notebook    | [1e4c7768c1](https://linux-hardware.org/?probe=1e4c7768c1) | Apr 02, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [c44e1a4b30](https://linux-hardware.org/?probe=c44e1a4b30) | Apr 02, 2024 |
| Lenovo        | ThinkPad L530 24793J2       | Notebook    | [9f6aec0751](https://linux-hardware.org/?probe=9f6aec0751) | Apr 02, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78a7a3ff32](https://linux-hardware.org/?probe=78a7a3ff32) | Apr 02, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [faec4d68cd](https://linux-hardware.org/?probe=faec4d68cd) | Apr 02, 2024 |
| Dell          | Latitude 3540               | Notebook    | [452a3babe4](https://linux-hardware.org/?probe=452a3babe4) | Apr 02, 2024 |
| Avell High... | B.ON                        | Notebook    | [27a4a2ab6d](https://linux-hardware.org/?probe=27a4a2ab6d) | Apr 02, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [5f3337af59](https://linux-hardware.org/?probe=5f3337af59) | Apr 02, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [48ed166001](https://linux-hardware.org/?probe=48ed166001) | Apr 02, 2024 |
| Gigabyte      | H510M S2H V3                | Desktop     | [860e8667e1](https://linux-hardware.org/?probe=860e8667e1) | Apr 02, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0004... | Notebook    | [2dd77820c8](https://linux-hardware.org/?probe=2dd77820c8) | Apr 02, 2024 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [ae35aaa6fe](https://linux-hardware.org/?probe=ae35aaa6fe) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7f542aae1b](https://linux-hardware.org/?probe=7f542aae1b) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0474c0e2a0](https://linux-hardware.org/?probe=0474c0e2a0) | Apr 02, 2024 |
| Lenovo        | Mullins-LarneML             | Notebook    | [07f3f21f7f](https://linux-hardware.org/?probe=07f3f21f7f) | Apr 02, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [aedfa9ff53](https://linux-hardware.org/?probe=aedfa9ff53) | Apr 02, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [3a49180fbf](https://linux-hardware.org/?probe=3a49180fbf) | Apr 02, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [4bc1c20e34](https://linux-hardware.org/?probe=4bc1c20e34) | Apr 02, 2024 |
| Avell High... | A62 LIV                     | Notebook    | [a7d1ceac6e](https://linux-hardware.org/?probe=a7d1ceac6e) | Apr 02, 2024 |
| MSI           | B365M PRO-VH                | Desktop     | [3b94bbe5fe](https://linux-hardware.org/?probe=3b94bbe5fe) | Apr 02, 2024 |
| Lenovo        | ThinkPad X240 20AMS1PT06    | Notebook    | [fb2384d93e](https://linux-hardware.org/?probe=fb2384d93e) | Apr 02, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [3bf4dbf87e](https://linux-hardware.org/?probe=3bf4dbf87e) | Apr 02, 2024 |
| Dell          | Precision 5560              | Notebook    | [2a88b33a32](https://linux-hardware.org/?probe=2a88b33a32) | Apr 02, 2024 |
| Dell          | Precision 5560              | Notebook    | [e9dfd89a49](https://linux-hardware.org/?probe=e9dfd89a49) | Apr 01, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9c151ab347](https://linux-hardware.org/?probe=9c151ab347) | Apr 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d21f6d3fe4](https://linux-hardware.org/?probe=d21f6d3fe4) | Apr 01, 2024 |
| Dell          | Inspiron 5770               | Notebook    | [3a6a7880c9](https://linux-hardware.org/?probe=3a6a7880c9) | Apr 01, 2024 |
| HP            | 8ACF 0100                   | All in one  | [0fd2395383](https://linux-hardware.org/?probe=0fd2395383) | Apr 01, 2024 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [4b4bfa93ee](https://linux-hardware.org/?probe=4b4bfa93ee) | Apr 01, 2024 |
| Dell          | Latitude 3540               | Notebook    | [11fa6df76e](https://linux-hardware.org/?probe=11fa6df76e) | Apr 01, 2024 |
| HP            | 1632                        | Desktop     | [09e29cc1bb](https://linux-hardware.org/?probe=09e29cc1bb) | Apr 01, 2024 |
| HP            | 1632                        | Desktop     | [746200a8d4](https://linux-hardware.org/?probe=746200a8d4) | Apr 01, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [eb4d7e2521](https://linux-hardware.org/?probe=eb4d7e2521) | Apr 01, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [1e27980b1d](https://linux-hardware.org/?probe=1e27980b1d) | Apr 01, 2024 |
| Dell          | Latitude 7430               | Notebook    | [d8fb269186](https://linux-hardware.org/?probe=d8fb269186) | Apr 01, 2024 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [1fd384a408](https://linux-hardware.org/?probe=1fd384a408) | Apr 01, 2024 |
| Apple         | MacBook10,1                 | Notebook    | [2da6005f10](https://linux-hardware.org/?probe=2da6005f10) | Apr 01, 2024 |
| Apple         | MacBook10,1                 | Notebook    | [36d6f74236](https://linux-hardware.org/?probe=36d6f74236) | Apr 01, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f0329002c8](https://linux-hardware.org/?probe=f0329002c8) | Apr 01, 2024 |
| HP            | ProBook 4720s               | Notebook    | [978eb70871](https://linux-hardware.org/?probe=978eb70871) | Apr 01, 2024 |
| Timi          | Mi NoteBook Pro             | Notebook    | [79e676b7a6](https://linux-hardware.org/?probe=79e676b7a6) | Apr 01, 2024 |
| Lenovo        | 3769 NO DPK                 | Desktop     | [c532b6c4ed](https://linux-hardware.org/?probe=c532b6c4ed) | Apr 01, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e9b930b832](https://linux-hardware.org/?probe=e9b930b832) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [900e722a10](https://linux-hardware.org/?probe=900e722a10) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [48dfdf4137](https://linux-hardware.org/?probe=48dfdf4137) | Apr 01, 2024 |
| Apple         | MacBookAir2,1               | Notebook    | [a80e8486df](https://linux-hardware.org/?probe=a80e8486df) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d209d00332](https://linux-hardware.org/?probe=d209d00332) | Apr 01, 2024 |
| Apple         | MacBookAir2,1               | Notebook    | [72fee9e6ec](https://linux-hardware.org/?probe=72fee9e6ec) | Apr 01, 2024 |
| Acer          | Aspire ES1-111              | Notebook    | [5135f2fbd2](https://linux-hardware.org/?probe=5135f2fbd2) | Apr 01, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [b5f8522b51](https://linux-hardware.org/?probe=b5f8522b51) | Apr 01, 2024 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [fc9cd1b4e0](https://linux-hardware.org/?probe=fc9cd1b4e0) | Apr 01, 2024 |
| Huanan        | X79 V2.47                   | Desktop     | [46ef932a9f](https://linux-hardware.org/?probe=46ef932a9f) | Mar 31, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1d2d3e6e05](https://linux-hardware.org/?probe=1d2d3e6e05) | Mar 31, 2024 |
| Gigabyte      | H81M-S                      | Desktop     | [d18c354852](https://linux-hardware.org/?probe=d18c354852) | Mar 31, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e3f1b781a2](https://linux-hardware.org/?probe=e3f1b781a2) | Mar 31, 2024 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [a7615a9986](https://linux-hardware.org/?probe=a7615a9986) | Mar 31, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [7ccfbb7054](https://linux-hardware.org/?probe=7ccfbb7054) | Mar 31, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [145a13951d](https://linux-hardware.org/?probe=145a13951d) | Mar 31, 2024 |
| HMT           | W042-67A                    | Notebook    | [957c1d9647](https://linux-hardware.org/?probe=957c1d9647) | Mar 31, 2024 |
| HMT           | W042-67A                    | Notebook    | [1d219ca2d5](https://linux-hardware.org/?probe=1d219ca2d5) | Mar 31, 2024 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [00de19b7af](https://linux-hardware.org/?probe=00de19b7af) | Mar 31, 2024 |
| ASUSTek       | H87-PLUS                    | Desktop     | [a32a6e5814](https://linux-hardware.org/?probe=a32a6e5814) | Mar 31, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [4c759cffbe](https://linux-hardware.org/?probe=4c759cffbe) | Mar 31, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [bd45787501](https://linux-hardware.org/?probe=bd45787501) | Mar 31, 2024 |
| GEEKOM        | A5                          | Desktop     | [da516126ba](https://linux-hardware.org/?probe=da516126ba) | Mar 31, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [eaa846245d](https://linux-hardware.org/?probe=eaa846245d) | Mar 31, 2024 |
| MSI           | B560M-A PRO                 | Desktop     | [e365e673d0](https://linux-hardware.org/?probe=e365e673d0) | Mar 31, 2024 |
| Apple         | MacBookPro13,3              | Notebook    | [df99c64127](https://linux-hardware.org/?probe=df99c64127) | Mar 31, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [bbd24ce2a1](https://linux-hardware.org/?probe=bbd24ce2a1) | Mar 31, 2024 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [5cefaeeb6a](https://linux-hardware.org/?probe=5cefaeeb6a) | Mar 31, 2024 |
| Lenovo        | Yoga Slim 6 14IRH8 83E0     | Notebook    | [31ba9b687a](https://linux-hardware.org/?probe=31ba9b687a) | Mar 31, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfb77127c6](https://linux-hardware.org/?probe=bfb77127c6) | Mar 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [17f9e8a736](https://linux-hardware.org/?probe=17f9e8a736) | Mar 31, 2024 |
| Dell          | Latitude E6440              | Notebook    | [a13e07b860](https://linux-hardware.org/?probe=a13e07b860) | Mar 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [f6171acc29](https://linux-hardware.org/?probe=f6171acc29) | Mar 31, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [e49bbb6862](https://linux-hardware.org/?probe=e49bbb6862) | Mar 30, 2024 |
| ASUSTek       | X542UR                      | Notebook    | [4710a67397](https://linux-hardware.org/?probe=4710a67397) | Mar 30, 2024 |
| Radxa         | ROCK 5 Model B              | Soc         | [c251818c1a](https://linux-hardware.org/?probe=c251818c1a) | Mar 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8a68f21257](https://linux-hardware.org/?probe=8a68f21257) | Mar 30, 2024 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [791d0e46d7](https://linux-hardware.org/?probe=791d0e46d7) | Mar 30, 2024 |
| Lenovo        | ThinkPad E580 20KS006FMZ    | Notebook    | [94d109d91e](https://linux-hardware.org/?probe=94d109d91e) | Mar 30, 2024 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [48e1b75074](https://linux-hardware.org/?probe=48e1b75074) | Mar 30, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7f3b57dade](https://linux-hardware.org/?probe=7f3b57dade) | Mar 30, 2024 |
| Foxconn       | H61MXL-K                    | Desktop     | [967587e883](https://linux-hardware.org/?probe=967587e883) | Mar 30, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | Notebook    | [818d4cdfe2](https://linux-hardware.org/?probe=818d4cdfe2) | Mar 30, 2024 |
| ASRock        | B365M IB-R                  | Desktop     | [870917e4e8](https://linux-hardware.org/?probe=870917e4e8) | Mar 30, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [e28e296839](https://linux-hardware.org/?probe=e28e296839) | Mar 30, 2024 |
| MSI           | MS-B9181                    | Desktop     | [1ae3e9b8ba](https://linux-hardware.org/?probe=1ae3e9b8ba) | Mar 30, 2024 |
| HP            | EliteBook 865 16 inch G1... | Notebook    | [cda1c99c4d](https://linux-hardware.org/?probe=cda1c99c4d) | Mar 30, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [1753d19bc6](https://linux-hardware.org/?probe=1753d19bc6) | Mar 30, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3aeea5fae7](https://linux-hardware.org/?probe=3aeea5fae7) | Mar 30, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [922723cbd4](https://linux-hardware.org/?probe=922723cbd4) | Mar 30, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3932e020fb](https://linux-hardware.org/?probe=3932e020fb) | Mar 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [e49cbff800](https://linux-hardware.org/?probe=e49cbff800) | Mar 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [c8e50aef4c](https://linux-hardware.org/?probe=c8e50aef4c) | Mar 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [dc808b758c](https://linux-hardware.org/?probe=dc808b758c) | Mar 30, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [b56fd43be2](https://linux-hardware.org/?probe=b56fd43be2) | Mar 30, 2024 |
| HP            | 886C                        | Desktop     | [c36efe4b45](https://linux-hardware.org/?probe=c36efe4b45) | Mar 30, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [6edb48c733](https://linux-hardware.org/?probe=6edb48c733) | Mar 29, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ba62c18a47](https://linux-hardware.org/?probe=ba62c18a47) | Mar 29, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d58ea5ec2c](https://linux-hardware.org/?probe=d58ea5ec2c) | Mar 29, 2024 |
| Alienware     | 15 R2                       | Notebook    | [2b6cb8a942](https://linux-hardware.org/?probe=2b6cb8a942) | Mar 29, 2024 |
| Acer          | Aspire A715-43G             | Notebook    | [d75576fddc](https://linux-hardware.org/?probe=d75576fddc) | Mar 29, 2024 |
| Dell          | Latitude 5289               | Convertible | [b1101aa5b9](https://linux-hardware.org/?probe=b1101aa5b9) | Mar 29, 2024 |
| Alienware     | 15 R2                       | Notebook    | [de21034f41](https://linux-hardware.org/?probe=de21034f41) | Mar 29, 2024 |
| Acer          | Aspire A715-43G             | Notebook    | [dd44e47f72](https://linux-hardware.org/?probe=dd44e47f72) | Mar 29, 2024 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [3a7607450d](https://linux-hardware.org/?probe=3a7607450d) | Mar 29, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9d668bab07](https://linux-hardware.org/?probe=9d668bab07) | Mar 29, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3ccfef4564](https://linux-hardware.org/?probe=3ccfef4564) | Mar 29, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [b8f102aaac](https://linux-hardware.org/?probe=b8f102aaac) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [21ef6a026f](https://linux-hardware.org/?probe=21ef6a026f) | Mar 29, 2024 |
| HP            | EliteBook 850 G1            | Notebook    | [3448f4cb60](https://linux-hardware.org/?probe=3448f4cb60) | Mar 29, 2024 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [75a6f1b690](https://linux-hardware.org/?probe=75a6f1b690) | Mar 29, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [4190d386b3](https://linux-hardware.org/?probe=4190d386b3) | Mar 29, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dbd9faa279](https://linux-hardware.org/?probe=dbd9faa279) | Mar 29, 2024 |
| ASUSTek       | GA35DX                      | Desktop     | [9f86bc906c](https://linux-hardware.org/?probe=9f86bc906c) | Mar 29, 2024 |
| ASRock        | AD2700-ITX                  | Desktop     | [52eb0a99d1](https://linux-hardware.org/?probe=52eb0a99d1) | Mar 29, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [57667ea730](https://linux-hardware.org/?probe=57667ea730) | Mar 29, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [eadd458a1d](https://linux-hardware.org/?probe=eadd458a1d) | Mar 29, 2024 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [ef8f367c13](https://linux-hardware.org/?probe=ef8f367c13) | Mar 29, 2024 |
| Lenovo        | ThinkPad T490s 20NYS41L0... | Notebook    | [2fcbfc4400](https://linux-hardware.org/?probe=2fcbfc4400) | Mar 29, 2024 |
| Dell          | 0K837J A02                  | Desktop     | [d4e979b93a](https://linux-hardware.org/?probe=d4e979b93a) | Mar 29, 2024 |
| Dell          | 0K837J A02                  | Desktop     | [86c44e64e6](https://linux-hardware.org/?probe=86c44e64e6) | Mar 29, 2024 |
| Intel         | X99                         | Desktop     | [f0dc0b1cf7](https://linux-hardware.org/?probe=f0dc0b1cf7) | Mar 28, 2024 |
| Gigabyte      | AORUS 5 KE                  | Notebook    | [aee8f4658d](https://linux-hardware.org/?probe=aee8f4658d) | Mar 28, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [612a0c054e](https://linux-hardware.org/?probe=612a0c054e) | Mar 28, 2024 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [208d350948](https://linux-hardware.org/?probe=208d350948) | Mar 28, 2024 |
| Lenovo        | 1066 NOK                    | Desktop     | [43b1e20967](https://linux-hardware.org/?probe=43b1e20967) | Mar 28, 2024 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [39e3f850a3](https://linux-hardware.org/?probe=39e3f850a3) | Mar 28, 2024 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [ec561b98c0](https://linux-hardware.org/?probe=ec561b98c0) | Mar 28, 2024 |
| Intel         | X99                         | Desktop     | [9770a63f27](https://linux-hardware.org/?probe=9770a63f27) | Mar 28, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [9f48c2854c](https://linux-hardware.org/?probe=9f48c2854c) | Mar 28, 2024 |
| Dell          | Precision 7710              | Notebook    | [02cc10dc57](https://linux-hardware.org/?probe=02cc10dc57) | Mar 28, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3eb36392bc](https://linux-hardware.org/?probe=3eb36392bc) | Mar 28, 2024 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [2854efe003](https://linux-hardware.org/?probe=2854efe003) | Mar 28, 2024 |
| Notebook      | PCx0Dx                      | Notebook    | [b1ca622c4a](https://linux-hardware.org/?probe=b1ca622c4a) | Mar 28, 2024 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4ee87d5c77](https://linux-hardware.org/?probe=4ee87d5c77) | Mar 28, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [2fc457195f](https://linux-hardware.org/?probe=2fc457195f) | Mar 28, 2024 |
| Insyde        | i101c                       | Notebook    | [fd15a3a81f](https://linux-hardware.org/?probe=fd15a3a81f) | Mar 28, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [ef4427b153](https://linux-hardware.org/?probe=ef4427b153) | Mar 28, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1248f2ac01](https://linux-hardware.org/?probe=1248f2ac01) | Mar 27, 2024 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [bf4d3d25ce](https://linux-hardware.org/?probe=bf4d3d25ce) | Mar 27, 2024 |
| Dell          | Latitude 7200 2-in-1        | Tablet      | [5720c32c5f](https://linux-hardware.org/?probe=5720c32c5f) | Mar 27, 2024 |
| Dell          | Latitude 7200 2-in-1        | Tablet      | [90e07f5656](https://linux-hardware.org/?probe=90e07f5656) | Mar 27, 2024 |
| HP            | EliteBook 865 16 inch G1... | Notebook    | [b0de881978](https://linux-hardware.org/?probe=b0de881978) | Mar 27, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [483f5486da](https://linux-hardware.org/?probe=483f5486da) | Mar 27, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [6d24bca5f3](https://linux-hardware.org/?probe=6d24bca5f3) | Mar 27, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [56d77f445e](https://linux-hardware.org/?probe=56d77f445e) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | Notebook    | [25985cf7e8](https://linux-hardware.org/?probe=25985cf7e8) | Mar 27, 2024 |
| HP            | 18E7                        | Desktop     | [ff6a9328f3](https://linux-hardware.org/?probe=ff6a9328f3) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | Notebook    | [433914ac7c](https://linux-hardware.org/?probe=433914ac7c) | Mar 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e11313b626](https://linux-hardware.org/?probe=e11313b626) | Mar 27, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b46c9ec4ab](https://linux-hardware.org/?probe=b46c9ec4ab) | Mar 27, 2024 |
| Lenovo        | Mullins-LarneML             | Notebook    | [5f1162baa1](https://linux-hardware.org/?probe=5f1162baa1) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [e23a935b8e](https://linux-hardware.org/?probe=e23a935b8e) | Mar 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S4G713    | Notebook    | [00b299696d](https://linux-hardware.org/?probe=00b299696d) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [650cc5973f](https://linux-hardware.org/?probe=650cc5973f) | Mar 27, 2024 |
| Apple         | MacBookPro14,2              | Notebook    | [8af3aa3110](https://linux-hardware.org/?probe=8af3aa3110) | Mar 27, 2024 |
| Lenovo        | ThinkPad T490s 20NYS42N0... | Notebook    | [5c7d81f9a4](https://linux-hardware.org/?probe=5c7d81f9a4) | Mar 27, 2024 |
| Timi          | TM1701                      | Notebook    | [63336e0c6c](https://linux-hardware.org/?probe=63336e0c6c) | Mar 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [e4c56c90e5](https://linux-hardware.org/?probe=e4c56c90e5) | Mar 26, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [d8557bf301](https://linux-hardware.org/?probe=d8557bf301) | Mar 26, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [18b1b5d0e9](https://linux-hardware.org/?probe=18b1b5d0e9) | Mar 26, 2024 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [a089051410](https://linux-hardware.org/?probe=a089051410) | Mar 26, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_39/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 6.5.6-300.fc39.x86_64       | 386       | 11.09%  |
| 6.7.9-200.fc39.x86_64       | 226       | 6.49%   |
| 6.5.11-300.fc39.x86_64      | 209       | 6%      |
| 6.6.9-200.fc39.x86_64       | 205       | 5.89%   |
| 6.7.4-200.fc39.x86_64       | 194       | 5.57%   |
| 6.6.8-200.fc39.x86_64       | 171       | 4.91%   |
| 6.7.7-200.fc39.x86_64       | 145       | 4.16%   |
| 6.6.13-200.fc39.x86_64      | 114       | 3.27%   |
| 6.5.12-300.fc39.x86_64      | 109       | 3.13%   |
| 6.6.11-200.fc39.x86_64      | 102       | 2.93%   |
| 6.6.4-200.fc39.x86_64       | 96        | 2.76%   |
| 6.6.6-200.fc39.x86_64       | 95        | 2.73%   |
| 6.8.4-200.fc39.x86_64       | 93        | 2.67%   |
| 6.7.5-200.fc39.x86_64       | 89        | 2.56%   |
| 6.6.7-200.fc39.x86_64       | 88        | 2.53%   |
| 6.7.10-200.fc39.x86_64      | 87        | 2.5%    |
| 6.8.6-200.fc39.x86_64       | 83        | 2.38%   |
| 6.6.2-201.fc39.x86_64       | 81        | 2.33%   |
| 6.7.6-200.fc39.x86_64       | 78        | 2.24%   |
| 6.7.11-200.fc39.x86_64      | 75        | 2.15%   |
| 6.7.3-200.fc39.x86_64       | 70        | 2.01%   |
| 6.8.5-201.fc39.x86_64       | 61        | 1.75%   |
| 6.6.14-200.fc39.x86_64      | 53        | 1.52%   |
| 6.8.7-200.fc39.x86_64       | 51        | 1.46%   |
| 6.6.12-200.fc39.x86_64      | 46        | 1.32%   |
| 6.5.10-300.fc39.x86_64      | 42        | 1.21%   |
| 6.6.3-200.fc39.x86_64       | 37        | 1.06%   |
| 6.8.9-200.fc39.x86_64       | 32        | 0.92%   |
| 6.8.11-200.fc39.x86_64      | 24        | 0.69%   |
| 6.5.9-300.fc39.x86_64       | 19        | 0.55%   |
| 6.5.5-300.fc39.x86_64       | 16        | 0.46%   |
| 6.8.8-200.fc39.x86_64       | 13        | 0.37%   |
| 6.9.7-100.fc39.x86_64       | 12        | 0.34%   |
| 6.7.9-207.fsync.fc39.x86_64 | 10        | 0.29%   |
| 6.8.10-200.fc39.x86_64      | 9         | 0.26%   |
| 6.7.9-204.fsync.fc39.x86_64 | 9         | 0.26%   |
| 6.5.2-301.fc39.x86_64       | 7         | 0.2%    |
| 6.10.6-100.fc39.x86_64      | 7         | 0.2%    |
| 6.10.3-100.fc39.x86_64      | 7         | 0.2%    |
| 6.9.12-100.fc39.x86_64      | 6         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.6   | 386       | 11.1%   |
| 6.7.9   | 250       | 7.19%   |
| 6.5.11  | 210       | 6.04%   |
| 6.6.9   | 206       | 5.92%   |
| 6.7.4   | 197       | 5.66%   |
| 6.6.8   | 175       | 5.03%   |
| 6.7.7   | 152       | 4.37%   |
| 6.6.13  | 115       | 3.31%   |
| 6.5.12  | 109       | 3.13%   |
| 6.6.11  | 103       | 2.96%   |
| 6.6.4   | 98        | 2.82%   |
| 6.8.4   | 96        | 2.76%   |
| 6.6.6   | 96        | 2.76%   |
| 6.7.5   | 93        | 2.67%   |
| 6.6.7   | 93        | 2.67%   |
| 6.7.10  | 87        | 2.5%    |
| 6.8.6   | 84        | 2.41%   |
| 6.7.6   | 83        | 2.39%   |
| 6.6.2   | 81        | 2.33%   |
| 6.7.11  | 77        | 2.21%   |
| 6.7.3   | 72        | 2.07%   |
| 6.8.5   | 61        | 1.75%   |
| 6.6.14  | 55        | 1.58%   |
| 6.8.7   | 52        | 1.49%   |
| 6.6.12  | 51        | 1.47%   |
| 6.5.10  | 46        | 1.32%   |
| 6.6.3   | 39        | 1.12%   |
| 6.8.9   | 32        | 0.92%   |
| 6.8.11  | 24        | 0.69%   |
| 6.5.9   | 19        | 0.55%   |
| 6.5.5   | 16        | 0.46%   |
| 6.8.8   | 14        | 0.4%    |
| 6.9.7   | 13        | 0.37%   |
| 6.7.0   | 11        | 0.32%   |
| 6.8.10  | 9         | 0.26%   |
| 6.8.0   | 7         | 0.2%    |
| 6.5.2   | 7         | 0.2%    |
| 6.4.0   | 7         | 0.2%    |
| 6.10.6  | 7         | 0.2%    |
| 6.10.3  | 7         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 1060      | 31.63%  |
| 6.7     | 992       | 29.6%   |
| 6.5     | 810       | 24.17%  |
| 6.8     | 375       | 11.19%  |
| 6.9     | 45        | 1.34%   |
| 6.10    | 30        | 0.9%    |
| 6.11    | 15        | 0.45%   |
| 6.4     | 10        | 0.3%    |
| 6.3     | 6         | 0.18%   |
| 6.2     | 5         | 0.15%   |
| 6.0     | 2         | 0.06%   |
| 5.0     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3145      | 99.78%  |
| aarch64 | 7         | 0.22%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| GNOME          | 2433      | 76.87%  |
| KDE5           | 444       | 14.03%  |
| Unknown        | 55        | 1.74%   |
| X-Cinnamon     | 43        | 1.36%   |
| XFCE           | 39        | 1.23%   |
| Cinnamon       | 30        | 0.95%   |
| Budgie         | 26        | 0.82%   |
| GNOME Classic  | 24        | 0.76%   |
| MATE           | 20        | 0.63%   |
| sway           | 11        | 0.35%   |
| Hyprland       | 8         | 0.25%   |
| KDE6           | 6         | 0.19%   |
| i3             | 5         | 0.16%   |
| LXQt           | 4         | 0.13%   |
| KDE            | 4         | 0.13%   |
| GNOME-Classic  | 3         | 0.09%   |
| Deepin         | 3         | 0.09%   |
| LXDE           | 2         | 0.06%   |
| wlroots        | 1         | 0.03%   |
| WindowMaker    | 1         | 0.03%   |
| river          | 1         | 0.03%   |
| i3-with-shmlog | 1         | 0.03%   |
| bspwm          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 2583      | 81.07%  |
| X11     | 517       | 16.23%  |
| Tty     | 56        | 1.76%   |
| Unknown | 29        | 0.91%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2104      | 66.35%  |
| GDM     | 695       | 21.92%  |
| SDDM    | 226       | 7.13%   |
| LightDM | 144       | 4.54%   |
| LXDM    | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1594      | 50.44%  |
| en_GB   | 236       | 7.47%   |
| ru_RU   | 185       | 5.85%   |
| de_DE   | 157       | 4.97%   |
| pt_BR   | 155       | 4.91%   |
| fr_FR   | 90        | 2.85%   |
| it_IT   | 89        | 2.82%   |
| en_AU   | 71        | 2.25%   |
| en_CA   | 69        | 2.18%   |
| pl_PL   | 55        | 1.74%   |
| es_ES   | 45        | 1.42%   |
| en_IN   | 39        | 1.23%   |
| es_MX   | 38        | 1.2%    |
| tr_TR   | 24        | 0.76%   |
| cs_CZ   | 22        | 0.7%    |
| de_AT   | 17        | 0.54%   |
| de_CH   | 16        | 0.51%   |
| zh_CN   | 15        | 0.47%   |
| hu_HU   | 15        | 0.47%   |
| es_AR   | 15        | 0.47%   |
| es_CL   | 12        | 0.38%   |
| en_NZ   | 12        | 0.38%   |
| es_CO   | 10        | 0.32%   |
| pt_PT   | 9         | 0.28%   |
| fr_CA   | 9         | 0.28%   |
| en_DK   | 9         | 0.28%   |
| Unknown | 9         | 0.28%   |
| nl_NL   | 8         | 0.25%   |
| en_ZA   | 8         | 0.25%   |
| ru_UA   | 7         | 0.22%   |
| fr_CH   | 7         | 0.22%   |
| fr_BE   | 7         | 0.22%   |
| nb_NO   | 6         | 0.19%   |
| ko_KR   | 6         | 0.19%   |
| en_IE   | 6         | 0.19%   |
| ja_JP   | 5         | 0.16%   |
| da_DK   | 5         | 0.16%   |
| sv_SE   | 4         | 0.13%   |
| ro_RO   | 4         | 0.13%   |
| fi_FI   | 4         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1888      | 58.63%  |
| BIOS | 1332      | 41.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 2644      | 83.64%  |
| Ext4    | 419       | 13.26%  |
| Xfs     | 66        | 2.09%   |
| Tmpfs   | 24        | 0.76%   |
| Overlay | 5         | 0.16%   |
| Unknown | 2         | 0.06%   |
| XXXXX   | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2048      | 64.54%  |
| GPT     | 1077      | 33.94%  |
| MBR     | 48        | 1.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2938      | 92.92%  |
| Yes       | 224       | 7.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2699      | 85.44%  |
| Yes       | 460       | 14.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 579       | 18.37%  |
| ASUSTek Computer                     | 550       | 17.45%  |
| Hewlett-Packard                      | 403       | 12.79%  |
| Dell                                 | 368       | 11.68%  |
| MSI                                  | 204       | 6.47%   |
| Gigabyte Technology                  | 170       | 5.39%   |
| Apple                                | 164       | 5.2%    |
| Acer                                 | 131       | 4.16%   |
| ASRock                               | 93        | 2.95%   |
| HUAWEI                               | 48        | 1.52%   |
| Intel                                | 35        | 1.11%   |
| Framework                            | 27        | 0.86%   |
| Samsung Electronics                  | 24        | 0.76%   |
| Fujitsu                              | 22        | 0.7%    |
| Unknown                              | 18        | 0.57%   |
| Toshiba                              | 15        | 0.48%   |
| Google                               | 15        | 0.48%   |
| Alienware                            | 14        | 0.44%   |
| Timi                                 | 13        | 0.41%   |
| AZW                                  | 13        | 0.41%   |
| Microsoft                            | 12        | 0.38%   |
| Chuwi                                | 11        | 0.35%   |
| Shenzhen Meigao Electronic Equipment | 9         | 0.29%   |
| Pegatron                             | 9         | 0.29%   |
| TUXEDO                               | 8         | 0.25%   |
| Positivo                             | 8         | 0.25%   |
| Notebook                             | 8         | 0.25%   |
| Sony                                 | 7         | 0.22%   |
| LG Electronics                       | 7         | 0.22%   |
| Biostar                              | 7         | 0.22%   |
| HONOR                                | 6         | 0.19%   |
| Medion                               | 5         | 0.16%   |
| Foxconn                              | 5         | 0.16%   |
| AMI                                  | 5         | 0.16%   |
| SLIMBOOK                             | 4         | 0.13%   |
| Razer                                | 4         | 0.13%   |
| Panasonic                            | 4         | 0.13%   |
| BESSTAR Tech                         | 4         | 0.13%   |
| Avell High Performance               | 4         | 0.13%   |
| XIAOMI                               | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 25        | 0.79%   |
| ASUS All Series                            | 16        | 0.51%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 14        | 0.44%   |
| Apple MacBookPro14,1                       | 12        | 0.38%   |
| Apple MacBookAir7,2                        | 9         | 0.29%   |
| MSI MS-7C95                                | 8         | 0.25%   |
| MSI MS-7C37                                | 7         | 0.22%   |
| HP Notebook                                | 7         | 0.22%   |
| AZW SER                                    | 7         | 0.22%   |
| ASUS ROG STRIX B550-F GAMING               | 7         | 0.22%   |
| Apple MacPro5,1                            | 7         | 0.22%   |
| Apple MacBookPro9,2                        | 7         | 0.22%   |
| Apple MacBookPro8,1                        | 7         | 0.22%   |
| MSI MS-7B89                                | 6         | 0.19%   |
| HUAWEI RLEF-XX                             | 6         | 0.19%   |
| HUAWEI BOM-WXX9                            | 6         | 0.19%   |
| Framework Laptop (12th Gen Intel Core)     | 6         | 0.19%   |
| Dell Precision M4800                       | 6         | 0.19%   |
| ASUS TUF Gaming X570-PLUS                  | 6         | 0.19%   |
| ASUS ROG STRIX X570-E GAMING               | 6         | 0.19%   |
| ASUS PRIME A320M-K                         | 6         | 0.19%   |
| Apple MacBookPro11,3                       | 6         | 0.19%   |
| Apple MacBookPro11,1                       | 6         | 0.19%   |
| MSI MS-7C56                                | 5         | 0.16%   |
| MSI MS-7C02                                | 5         | 0.16%   |
| MSI MS-7B86                                | 5         | 0.16%   |
| Microsoft Surface Pro 4                    | 5         | 0.16%   |
| Lenovo ThinkBook 16 G6 IRL 21KH            | 5         | 0.16%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 5         | 0.16%   |
| Intel X99                                  | 5         | 0.16%   |
| HP OMEN by Laptop 16-c0xxx                 | 5         | 0.16%   |
| HP EliteBook 840 G5                        | 5         | 0.16%   |
| Gigabyte X570 I AORUS PRO WIFI             | 5         | 0.16%   |
| Dell OptiPlex 9020                         | 5         | 0.16%   |
| Dell Latitude 5290 2-in-1                  | 5         | 0.16%   |
| Dell Inspiron 15-3567                      | 5         | 0.16%   |
| ASUS Zenbook UM3402YAR_UM3402YA            | 5         | 0.16%   |
| ASUS TUF Gaming X570-PRO                   | 5         | 0.16%   |
| ASUS TUF Gaming B550-PLUS                  | 5         | 0.16%   |
| Apple Macmini6,1                           | 5         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 274       | 8.69%   |
| ASUS ROG            | 114       | 3.62%   |
| Dell Latitude       | 106       | 3.36%   |
| Lenovo IdeaPad      | 95        | 3.01%   |
| ASUS PRIME          | 82        | 2.6%    |
| Dell Inspiron       | 79        | 2.51%   |
| ASUS VivoBook       | 77        | 2.44%   |
| Acer Aspire         | 77        | 2.44%   |
| HP EliteBook        | 70        | 2.22%   |
| HP Laptop           | 55        | 1.74%   |
| Dell XPS            | 52        | 1.65%   |
| ASUS TUF            | 52        | 1.65%   |
| HP Pavilion         | 50        | 1.59%   |
| Dell Precision      | 50        | 1.59%   |
| HP ENVY             | 44        | 1.4%    |
| Lenovo Legion       | 41        | 1.3%    |
| Dell OptiPlex       | 41        | 1.3%    |
| Lenovo Yoga         | 40        | 1.27%   |
| ASUS ASUS           | 39        | 1.24%   |
| HP ProBook          | 33        | 1.05%   |
| ASUS Zenbook        | 31        | 0.98%   |
| Framework Laptop    | 27        | 0.86%   |
| Unknown             | 25        | 0.79%   |
| Acer Nitro          | 23        | 0.73%   |
| Apple MacBookPro11  | 21        | 0.67%   |
| Lenovo ThinkCentre  | 19        | 0.6%    |
| Lenovo ThinkBook    | 17        | 0.54%   |
| HP EliteDesk        | 17        | 0.54%   |
| HP OMEN             | 16        | 0.51%   |
| Dell Vostro         | 16        | 0.51%   |
| ASUS All            | 16        | 0.51%   |
| Gigabyte X570       | 15        | 0.48%   |
| Gigabyte B550M      | 14        | 0.44%   |
| Apple MacBookPro14  | 14        | 0.44%   |
| Toshiba Satellite   | 12        | 0.38%   |
| Microsoft Surface   | 12        | 0.38%   |
| Lenovo ThinkStation | 12        | 0.38%   |
| Fujitsu LIFEBOOK    | 12        | 0.38%   |
| Lenovo IdeaPadFlex  | 11        | 0.35%   |
| HP ZBook            | 11        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 397       | 12.6%   |
| 2021    | 391       | 12.4%   |
| 2023    | 367       | 11.64%  |
| 2020    | 342       | 10.85%  |
| 2019    | 261       | 8.28%   |
| 2018    | 249       | 7.9%    |
| 2017    | 193       | 6.12%   |
| 2013    | 139       | 4.41%   |
| 2012    | 136       | 4.31%   |
| 2014    | 134       | 4.25%   |
| 2015    | 120       | 3.81%   |
| 2016    | 111       | 3.52%   |
| 2011    | 98        | 3.11%   |
| 2010    | 78        | 2.47%   |
| 2008    | 42        | 1.33%   |
| 2009    | 41        | 1.3%    |
| 2007    | 23        | 0.73%   |
| 2024    | 22        | 0.7%    |
| 2006    | 4         | 0.13%   |
| 2005    | 2         | 0.06%   |
| Unknown | 2         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1842      | 58.44%  |
| Desktop        | 979       | 31.06%  |
| Convertible    | 156       | 4.95%   |
| Mini pc        | 62        | 1.97%   |
| Tablet         | 54        | 1.71%   |
| All in one     | 45        | 1.43%   |
| Server         | 8         | 0.25%   |
| System on chip | 5         | 0.16%   |
| Other          | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2663      | 83.9%   |
| Enabled  | 511       | 16.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3133      | 99.4%   |
| Yes  | 19        | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 740       | 23.35%  |
| 4.01-8.0        | 686       | 21.65%  |
| 8.01-16.0       | 603       | 19.03%  |
| 32.01-64.0      | 567       | 17.89%  |
| 3.01-4.0        | 203       | 6.41%   |
| 64.01-256.0     | 183       | 5.77%   |
| 24.01-32.0      | 151       | 4.76%   |
| 1.01-2.0        | 23        | 0.73%   |
| 2.01-3.0        | 10        | 0.32%   |
| More than 256.0 | 3         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1096      | 32.74%  |
| 2.01-3.0    | 807       | 24.1%   |
| 3.01-4.0    | 779       | 23.27%  |
| 1.01-2.0    | 325       | 9.71%   |
| 8.01-16.0   | 246       | 7.35%   |
| 16.01-24.0  | 47        | 1.4%    |
| 0.51-1.0    | 30        | 0.9%    |
| 24.01-32.0  | 10        | 0.3%    |
| 32.01-64.0  | 6         | 0.18%   |
| 64.01-256.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1990      | 62.34%  |
| 2      | 710       | 22.24%  |
| 3      | 269       | 8.43%   |
| 4      | 108       | 3.38%   |
| 5      | 57        | 1.79%   |
| 6      | 28        | 0.88%   |
| 8      | 9         | 0.28%   |
| 7      | 6         | 0.19%   |
| 0      | 5         | 0.16%   |
| 9      | 3         | 0.09%   |
| 12     | 2         | 0.06%   |
| 10     | 2         | 0.06%   |
| 22     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2579      | 81.61%  |
| Yes       | 581       | 18.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2416      | 76.48%  |
| No        | 743       | 23.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2654      | 83.99%  |
| No        | 506       | 16.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2449      | 77.35%  |
| No        | 717       | 22.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 638       | 20.17%  |
| Germany     | 256       | 8.09%   |
| Russia      | 210       | 6.64%   |
| Brazil      | 203       | 6.42%   |
| Italy       | 147       | 4.65%   |
| UK          | 135       | 4.27%   |
| France      | 122       | 3.86%   |
| Canada      | 115       | 3.64%   |
| Poland      | 99        | 3.13%   |
| India       | 90        | 2.85%   |
| Australia   | 81        | 2.56%   |
| Spain       | 72        | 2.28%   |
| Netherlands | 59        | 1.87%   |
| Mexico      | 55        | 1.74%   |
| Switzerland | 50        | 1.58%   |
| Austria     | 45        | 1.42%   |
| Turkey      | 43        | 1.36%   |
| Czechia     | 42        | 1.33%   |
| Romania     | 39        | 1.23%   |
| Portugal    | 33        | 1.04%   |
| Sweden      | 32        | 1.01%   |
| Argentina   | 30        | 0.95%   |
| Hungary     | 28        | 0.89%   |
| Belgium     | 26        | 0.82%   |
| Finland     | 22        | 0.7%    |
| Bulgaria    | 21        | 0.66%   |
| Norway      | 19        | 0.6%    |
| Colombia    | 19        | 0.6%    |
| Chile       | 17        | 0.54%   |
| Belarus     | 17        | 0.54%   |
| Egypt       | 16        | 0.51%   |
| Japan       | 15        | 0.47%   |
| Denmark     | 15        | 0.47%   |
| China       | 15        | 0.47%   |
| Indonesia   | 13        | 0.41%   |
| Morocco     | 12        | 0.38%   |
| Greece      | 12        | 0.38%   |
| Serbia      | 11        | 0.35%   |
| Philippines | 11        | 0.35%   |
| New Zealand | 11        | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 53        | 1.64%   |
| Sydney         | 32        | 0.99%   |
| St Petersburg  | 31        | 0.96%   |
| Vienna         | 26        | 0.81%   |
| Berlin         | 26        | 0.81%   |
| Warsaw         | 21        | 0.65%   |
| Seattle        | 21        | 0.65%   |
| Paris          | 21        | 0.65%   |
| Toronto        | 18        | 0.56%   |
| Sao Paulo      | 17        | 0.53%   |
| Munich         | 17        | 0.53%   |
| Milan          | 17        | 0.53%   |
| Bengaluru      | 15        | 0.46%   |
| Montreal       | 14        | 0.43%   |
| Yekaterinburg  | 13        | 0.4%    |
| Prague         | 13        | 0.4%    |
| Minsk          | 13        | 0.4%    |
| Istanbul       | 13        | 0.4%    |
| Zurich         | 12        | 0.37%   |
| Stuttgart      | 12        | 0.37%   |
| Rome           | 12        | 0.37%   |
| Melbourne      | 12        | 0.37%   |
| Los Angeles    | 12        | 0.37%   |
| Helsinki       | 12        | 0.37%   |
| Rio de Janeiro | 11        | 0.34%   |
| Mexico City    | 11        | 0.34%   |
| Hamburg        | 11        | 0.34%   |
| Ankara         | 11        | 0.34%   |
| Sofia          | 10        | 0.31%   |
| Santiago       | 10        | 0.31%   |
| London         | 10        | 0.31%   |
| Delhi          | 10        | 0.31%   |
| Chicago        | 10        | 0.31%   |
| Budapest       | 10        | 0.31%   |
| Bucharest      | 10        | 0.31%   |
| Brisbane       | 10        | 0.31%   |
| Amsterdam      | 10        | 0.31%   |
| Tashkent       | 9         | 0.28%   |
| Poznan         | 9         | 0.28%   |
| Porto Alegre   | 9         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 866       | 1215   | 18.79%  |
| Sandisk                      | 439       | 517    | 9.52%   |
| WDC                          | 398       | 593    | 8.63%   |
| Seagate                      | 365       | 517    | 7.92%   |
| Kingston                     | 219       | 271    | 4.75%   |
| SK hynix                     | 204       | 226    | 4.43%   |
| Toshiba                      | 168       | 200    | 3.64%   |
| Micron Technology            | 160       | 172    | 3.47%   |
| Intel                        | 159       | 202    | 3.45%   |
| Unknown                      | 141       | 168    | 3.06%   |
| Crucial                      | 141       | 173    | 3.06%   |
| Micron/Crucial Technology    | 120       | 156    | 2.6%    |
| Phison Electronics           | 105       | 127    | 2.28%   |
| Apple                        | 90        | 123    | 1.95%   |
| KIOXIA                       | 71        | 80     | 1.54%   |
| Kingston Technology Company  | 59        | 64     | 1.28%   |
| MAXIO Technology (Hangzhou)  | 58        | 66     | 1.26%   |
| Hitachi                      | 55        | 66     | 1.19%   |
| A-DATA Technology            | 54        | 59     | 1.17%   |
| Silicon Motion               | 52        | 67     | 1.13%   |
| ADATA Technology             | 50        | 64     | 1.08%   |
| HGST                         | 49        | 62     | 1.06%   |
| China                        | 42        | 49     | 0.91%   |
| Realtek Semiconductor        | 23        | 25     | 0.5%    |
| PNY                          | 23        | 28     | 0.5%    |
| SPCC                         | 22        | 27     | 0.48%   |
| Shenzhen Longsys Electronics | 22        | 28     | 0.48%   |
| Unknown                      | 17        | 19     | 0.37%   |
| Patriot                      | 16        | 21     | 0.35%   |
| Intenso                      | 16        | 18     | 0.35%   |
| Netac                        | 15        | 21     | 0.33%   |
| JMicron Technology           | 15        | 24     | 0.33%   |
| Transcend                    | 13        | 16     | 0.28%   |
| GOODRAM                      | 12        | 15     | 0.26%   |
| Apacer                       | 12        | 15     | 0.26%   |
| Team                         | 11        | 13     | 0.24%   |
| LITEON                       | 11        | 15     | 0.24%   |
| Lexar                        | 11        | 14     | 0.24%   |
| Union Memory (Shenzhen)      | 10        | 10     | 0.22%   |
| Hewlett-Packard              | 10        | 30     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 223       | 4.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 149       | 2.97%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 83        | 1.66%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 59        | 1.18%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 48        | 0.96%   |
| Kingston SA400S37240G 240GB SSD                       | 46        | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 43        | 0.86%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 42        | 0.84%   |
| Phison E12 NVMe Controller 480GB                      | 39        | 0.78%   |
| Samsung SSD 860 EVO 500GB                             | 38        | 0.76%   |
| Intel SSDPEKNU512GZ 512GB                             | 38        | 0.76%   |
| Kingston SA400S37480G 480GB SSD                       | 37        | 0.74%   |
| Intel SSD 660P Series 1024GB                          | 34        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 32        | 0.64%   |
| Unknown MMC Card  32GB                                | 30        | 0.6%    |
| Unknown MMC Card  128GB                               | 29        | 0.58%   |
| Samsung SSD 980 1TB                                   | 26        | 0.52%   |
| Samsung SSD 850 EVO 250GB                             | 26        | 0.52%   |
| Samsung SSD 860 EVO 1TB                               | 25        | 0.5%    |
| Samsung SSD 850 EVO 500GB                             | 25        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                        | 24        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                           | 24        | 0.48%   |
| Unknown MMC Card  64GB                                | 23        | 0.46%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 23        | 0.46%   |
| Kingston Company SNV2S1000G 1TB                       | 23        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB                        | 22        | 0.44%   |
| Sandisk WD Black SN850 2TB                            | 22        | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                        | 21        | 0.42%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 20        | 0.4%    |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 20        | 0.4%    |
| Samsung SSD 990 PRO 2TB                               | 20        | 0.4%    |
| Sandisk WD_BLACK SN770 1TB                            | 19        | 0.38%   |
| Samsung SSD 870 EVO 1TB                               | 19        | 0.38%   |
| Crucial CT500MX500SSD1 500GB                          | 19        | 0.38%   |
| Sandisk WD_BLACK SN850X 1000GB                        | 18        | 0.36%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 18        | 0.36%   |
| Seagate ST500DM002-1BD142 500GB                       | 17        | 0.34%   |
| HGST HTS721010A9E630 1TB                              | 17        | 0.34%   |
| Crucial CT480BX500SSD1 480GB                          | 17        | 0.34%   |
| Unknown                                               | 17        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 351       | 494    | 35.6%   |
| WDC                 | 325       | 486    | 32.96%  |
| Toshiba             | 102       | 127    | 10.34%  |
| Hitachi             | 55        | 66     | 5.58%   |
| HGST                | 48        | 61     | 4.87%   |
| Samsung Electronics | 30        | 46     | 3.04%   |
| Apple               | 15        | 17     | 1.52%   |
| Unknown             | 13        | 13     | 1.32%   |
| JMicron Technology  | 10        | 19     | 1.01%   |
| External            | 6         | 10     | 0.61%   |
| Maxtor              | 4         | 4      | 0.41%   |
| Fujitsu             | 4         | 5      | 0.41%   |
| SABRENT             | 3         | 3      | 0.3%    |
| ASMT                | 3         | 8      | 0.3%    |
| USB                 | 2         | 2      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 2      | 0.1%    |
| SAGE                | 1         | 1      | 0.1%    |
| ORICO               | 1         | 1      | 0.1%    |
| Lenovo              | 1         | 1      | 0.1%    |
| KINGWIN             | 1         | 1      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| Inateck             | 1         | 2      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| IB-377U3            | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 20     | 0.1%    |
| FC-1307             | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |
| Asm                 | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 301       | 422    | 22.25%  |
| Kingston            | 162       | 194    | 11.97%  |
| Crucial             | 141       | 173    | 10.42%  |
| SanDisk             | 95        | 112    | 7.02%   |
| WDC                 | 86        | 103    | 6.36%   |
| Apple               | 52        | 54     | 3.84%   |
| A-DATA Technology   | 44        | 48     | 3.25%   |
| China               | 42        | 49     | 3.1%    |
| Intel               | 38        | 58     | 2.81%   |
| SK hynix            | 35        | 37     | 2.59%   |
| Micron Technology   | 26        | 28     | 1.92%   |
| PNY                 | 23        | 28     | 1.7%    |
| SPCC                | 21        | 26     | 1.55%   |
| Toshiba             | 17        | 18     | 1.26%   |
| Patriot             | 15        | 20     | 1.11%   |
| Intenso             | 14        | 16     | 1.03%   |
| GOODRAM             | 12        | 15     | 0.89%   |
| Apacer              | 12        | 15     | 0.89%   |
| Transcend           | 11        | 13     | 0.81%   |
| Team                | 11        | 13     | 0.81%   |
| Netac               | 11        | 15     | 0.81%   |
| LITEON              | 11        | 15     | 0.81%   |
| Lexar               | 10        | 13     | 0.74%   |
| OCZ                 | 9         | 13     | 0.67%   |
| LITEONIT            | 9         | 11     | 0.67%   |
| KingSpec            | 9         | 11     | 0.67%   |
| Unknown             | 8         | 10     | 0.59%   |
| Hewlett-Packard     | 7         | 8      | 0.52%   |
| Gigabyte Technology | 7         | 7      | 0.52%   |
| Fanxiang            | 6         | 8      | 0.44%   |
| Corsair             | 5         | 6      | 0.37%   |
| Smartbuy            | 4         | 5      | 0.3%    |
| Seagate             | 4         | 4      | 0.3%    |
| Plextor             | 4         | 8      | 0.3%    |
| USB3.0              | 3         | 3      | 0.22%   |
| FORESEE             | 3         | 4      | 0.22%   |
| Emtec               | 3         | 3      | 0.22%   |
| AirDisk             | 3         | 3      | 0.22%   |
| XrayDisk            | 2         | 2      | 0.15%   |
| StoreJet            | 2         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1978      | 2628   | 47.49%  |
| SSD     | 1171      | 1678   | 28.12%  |
| HDD     | 836       | 1397   | 20.07%  |
| MMC     | 104       | 126    | 2.5%    |
| Unknown | 76        | 93     | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1973      | 2607   | 51.35%  |
| SATA | 1588      | 2944   | 41.33%  |
| SAS  | 177       | 245    | 4.61%   |
| MMC  | 104       | 126    | 2.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1078      | 1595   | 50.95%  |
| 0.51-1.0   | 660       | 905    | 31.19%  |
| 1.01-2.0   | 199       | 275    | 9.4%    |
| 3.01-4.0   | 77        | 119    | 3.64%   |
| 4.01-10.0  | 58        | 116    | 2.74%   |
| 2.01-3.0   | 25        | 37     | 1.18%   |
| 10.01-20.0 | 19        | 28     | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 719       | 22.3%   |
| 251-500        | 566       | 17.56%  |
| 1001-2000      | 563       | 17.46%  |
| 101-250        | 377       | 11.69%  |
| More than 3000 | 262       | 8.13%   |
| Unknown        | 254       | 7.88%   |
| 1-20           | 226       | 7.01%   |
| 2001-3000      | 124       | 3.85%   |
| 51-100         | 97        | 3.01%   |
| 21-50          | 36        | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 959       | 29.14%  |
| 21-50          | 603       | 18.32%  |
| 101-250        | 411       | 12.49%  |
| 51-100         | 341       | 10.36%  |
| 251-500        | 278       | 8.45%   |
| Unknown        | 254       | 7.72%   |
| 501-1000       | 198       | 6.02%   |
| 1001-2000      | 130       | 3.95%   |
| More than 3000 | 74        | 2.25%   |
| 2001-3000      | 43        | 1.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68N32N0 4TB                                        | 4         | 4      | 4%      |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 4      | 3%      |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2         | 2      | 2%      |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD                        | 2         | 2      | 2%      |
| Seagate ST9500325AS 500GB                                       | 2         | 2      | 2%      |
| Seagate ST2000DM001-1ER164 2TB                                  | 2         | 2      | 2%      |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB       | 2         | 2      | 2%      |
| Intel SSDSC2CT120A3 120GB                                       | 2         | 8      | 2%      |
| Crucial CT128MX100SSD1 128GB                                    | 2         | 2      | 2%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 1         | 1      | 1%      |
| WDC WD7500BPKX-00HPJT0 752GB                                    | 1         | 1      | 1%      |
| WDC WD6400AAKS-65A7B2 640GB                                     | 1         | 1      | 1%      |
| WDC WD5000LPVX-22V0TT0 500GB                                    | 1         | 1      | 1%      |
| WDC WD5000BPVT-22HXZT1 500GB                                    | 1         | 1      | 1%      |
| WDC WD5000AVDS-63U7B1 500GB                                     | 1         | 2      | 1%      |
| WDC WD5000AVCS-632DY1 500GB                                     | 1         | 3      | 1%      |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 1         | 2      | 1%      |
| WDC WD5000AAKS-00UU3A0 500GB                                    | 1         | 1      | 1%      |
| WDC WD40EFRX-68WT0N0 4TB                                        | 1         | 1      | 1%      |
| WDC WD3200AAKS-22B3A0 320GB                                     | 1         | 1      | 1%      |
| WDC WD30 EZRX-00SPEB0 3TB                                       | 1         | 1      | 1%      |
| WDC WD20EADS-00S2B0 2TB                                         | 1         | 1      | 1%      |
| WDC WD2003FZEX-00SRLA0 2TB                                      | 1         | 1      | 1%      |
| WDC WD20 EZRX-00D8PB0 2TB                                       | 1         | 1      | 1%      |
| WDC WD1600AVVS-63L2B0 160GB                                     | 1         | 1      | 1%      |
| WDC WD15EARS-00MVWB0 1TB                                        | 1         | 1      | 1%      |
| WDC WD10JPVT-75A1YT0 1TB                                        | 1         | 1      | 1%      |
| WDC WD10EZEX-08WN4A0 1TB                                        | 1         | 1      | 1%      |
| WDC WD10EARS-22Y5B1 1TB                                         | 1         | 1      | 1%      |
| WDC WD10EADS-11M2B2 1TB                                         | 1         | 1      | 1%      |
| WDC WD10EADS-00L5B1 1TB                                         | 1         | 1      | 1%      |
| WDC WD Green 2.5 480GB SSD                                      | 1         | 1      | 1%      |
| WDC WD Blue SA510 2.5 500GB                                     | 1         | 1      | 1%      |
| Toshiba MQ01ABF050 500GB                                        | 1         | 1      | 1%      |
| Toshiba MQ01ABD050 500GB                                        | 1         | 4      | 1%      |
| Toshiba MK5056GSYF 500GB                                        | 1         | 1      | 1%      |
| Toshiba DT01ACA100 1TB                                          | 1         | 1      | 1%      |
| Toshiba BG3 NVMe SSD Controller 128GB                           | 1         | 1      | 1%      |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 1         | 1      | 1%      |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 1%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 27        | 34     | 28.13%  |
| Seagate               | 19        | 24     | 19.79%  |
| Samsung Electronics   | 8         | 19     | 8.33%   |
| Toshiba               | 7         | 10     | 7.29%   |
| Hitachi               | 7         | 7      | 7.29%   |
| Crucial               | 5         | 8      | 5.21%   |
| SanDisk               | 4         | 4      | 4.17%   |
| Intel                 | 3         | 9      | 3.13%   |
| HGST                  | 3         | 3      | 3.13%   |
| Realtek Semiconductor | 2         | 2      | 2.08%   |
| Micron Technology     | 2         | 2      | 2.08%   |
| Apple                 | 2         | 2      | 2.08%   |
| SK hynix              | 1         | 1      | 1.04%   |
| Neo                   | 1         | 1      | 1.04%   |
| Mushkin               | 1         | 1      | 1.04%   |
| Maxtor                | 1         | 1      | 1.04%   |
| Kingston              | 1         | 1      | 1.04%   |
| Fujitsu               | 1         | 1      | 1.04%   |
| China                 | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 29     | 37.7%   |
| Seagate             | 19        | 24     | 31.15%  |
| Hitachi             | 7         | 7      | 11.48%  |
| Toshiba             | 4         | 7      | 6.56%   |
| HGST                | 3         | 3      | 4.92%   |
| Samsung Electronics | 2         | 12     | 3.28%   |
| Maxtor              | 1         | 1      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |
| Apple               | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 85     | 60.87%  |
| SSD  | 27        | 36     | 29.35%  |
| NVMe | 9         | 10     | 9.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD30 EZRS-00J99B0 3TB       | 1         | 1      | 33.33%  |
| Sandisk PC SN520 NVMe SSD 256GB | 1         | 1      | 33.33%  |
| Hitachi HDS721010DLE630 1TB     | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Sandisk | 1         | 1      | 33.33%  |
| Hitachi | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2202      | 4065   | 66.97%  |
| Works    | 996       | 1722   | 30.29%  |
| Malfunc  | 87        | 131    | 2.65%   |
| Failed   | 3         | 4      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1617      | 35.93%  |
| AMD                                     | 631       | 14.02%  |
| Samsung Electronics                     | 630       | 14%     |
| SanDisk                                 | 347       | 7.71%   |
| SK hynix                                | 169       | 3.76%   |
| Micron Technology                       | 134       | 2.98%   |
| Kingston Technology Company             | 121       | 2.69%   |
| Micron/Crucial Technology               | 120       | 2.67%   |
| Phison Electronics                      | 108       | 2.4%    |
| ASMedia Technology                      | 76        | 1.69%   |
| KIOXIA                                  | 71        | 1.58%   |
| ADATA Technology                        | 60        | 1.33%   |
| MAXIO Technology (Hangzhou)             | 59        | 1.31%   |
| Silicon Motion                          | 52        | 1.16%   |
| Toshiba America Info Systems            | 51        | 1.13%   |
| Marvell Technology Group                | 27        | 0.6%    |
| Realtek Semiconductor                   | 23        | 0.51%   |
| JMicron Technology                      | 23        | 0.51%   |
| Apple                                   | 23        | 0.51%   |
| Shenzhen Longsys Electronics            | 22        | 0.49%   |
| Nvidia                                  | 22        | 0.49%   |
| Solidigm                                | 15        | 0.33%   |
| Solid State Storage Technology          | 14        | 0.31%   |
| Union Memory (Shenzhen)                 | 11        | 0.24%   |
| Shenzhen Unionmemory Information System | 8         | 0.18%   |
| INNOGRIT                                | 8         | 0.18%   |
| Broadcom / LSI                          | 8         | 0.18%   |
| Seagate Technology                      | 7         | 0.16%   |
| Lenovo                                  | 6         | 0.13%   |
| Yangtze Memory Technologies             | 5         | 0.11%   |
| Netac Technology                        | 4         | 0.09%   |
| Lite-On Technology                      | 4         | 0.09%   |
| Transcend                               | 3         | 0.07%   |
| Biwin Storage Technology                | 3         | 0.07%   |
| VIA Technologies                        | 2         | 0.04%   |
| LSI Logic / Symbios Logic               | 2         | 0.04%   |
| Hosin Global Electronics                | 2         | 0.04%   |
| Adaptec                                 | 2         | 0.04%   |
| ULi Electronics                         | 1         | 0.02%   |
| TenaFe                                  | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 333       | 6.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 224       | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 175       | 3.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 152       | 3.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 148       | 3.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 121       | 2.46%   |
| AMD 500 Series Chipset SATA Controller                                         | 113       | 2.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 102       | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 91        | 1.85%   |
| AMD 600 Series Chipset SATA Controller                                         | 84        | 1.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 83        | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 78        | 1.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 77        | 1.57%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 65        | 1.32%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 65        | 1.32%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 59        | 1.2%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 59        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 59        | 1.2%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 58        | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 58        | 1.18%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 52        | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 49        | 1%      |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 47        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 44        | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 43        | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 43        | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 43        | 0.87%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 42        | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 40        | 0.81%   |
| Intel SATA Controller [RAID mode]                                              | 40        | 0.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 40        | 0.81%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 39        | 0.79%   |
| Phison E12 NVMe Controller                                                     | 39        | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 39        | 0.79%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 38        | 0.77%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 38        | 0.77%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 37        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 37        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 35        | 0.71%   |
| Intel SSD 660P Series                                                          | 34        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 1966      | 44.76%  |
| SATA | 1898      | 43.21%  |
| RAID | 376       | 8.56%   |
| IDE  | 142       | 3.23%   |
| SAS  | 8         | 0.18%   |
| SCSI | 2         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 2142      | 67.96%  |
| AMD     | 1003      | 31.82%  |
| ARM     | 5         | 0.16%   |
| Unknown | 2         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 51        | 1.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 42        | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 36        | 1.14%   |
| AMD Ryzen 5 3600 6-Core Processor          | 33        | 1.05%   |
| Intel 12th Gen Core i7-12700H              | 30        | 0.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 30        | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 27        | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 27        | 0.86%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 27        | 0.86%   |
| AMD Ryzen 5 5500U with Radeon Graphics     | 26        | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 23        | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 22        | 0.7%    |
| Intel 12th Gen Core i5-1235U               | 22        | 0.7%    |
| AMD Ryzen 7 5800X 8-Core Processor         | 21        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 20        | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 20        | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 20        | 0.63%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 20        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 19        | 0.6%    |
| Intel 12th Gen Core i5-12450H              | 19        | 0.6%    |
| AMD Ryzen 7 5700G with Radeon Graphics     | 19        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz         | 18        | 0.57%   |
| Intel 13th Gen Core i7-1355U               | 18        | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 17        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 17        | 0.54%   |
| Intel 13th Gen Core i7-13700H              | 17        | 0.54%   |
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics | 17        | 0.54%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 17        | 0.54%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 17        | 0.54%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 17        | 0.54%   |
| AMD Ryzen 5 5600H with Radeon Graphics     | 17        | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 16        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 16        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 16        | 0.51%   |
| Intel 12th Gen Core i7-1255U               | 16        | 0.51%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 16        | 0.51%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 16        | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 15        | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 15        | 0.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 15        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 606       | 19.2%   |
| Intel Core i5           | 591       | 18.73%  |
| Intel Core i7           | 500       | 15.84%  |
| AMD Ryzen 7             | 333       | 10.55%  |
| AMD Ryzen 5             | 295       | 9.35%   |
| Intel Core i3           | 146       | 4.63%   |
| AMD Ryzen 9             | 133       | 4.21%   |
| Intel Celeron           | 76        | 2.41%   |
| Intel Xeon              | 68        | 2.15%   |
| Intel Core 2 Duo        | 49        | 1.55%   |
| AMD Ryzen 3             | 45        | 1.43%   |
| AMD Ryzen 7 PRO         | 40        | 1.27%   |
| Intel Pentium           | 30        | 0.95%   |
| AMD Ryzen 5 PRO         | 21        | 0.67%   |
| AMD FX                  | 21        | 0.67%   |
| Intel Atom              | 20        | 0.63%   |
| Intel Core i9           | 19        | 0.6%    |
| Intel Core 2 Quad       | 16        | 0.51%   |
| AMD A6                  | 14        | 0.44%   |
| AMD Ryzen Threadripper  | 13        | 0.41%   |
| AMD A8                  | 10        | 0.32%   |
| AMD A10                 | 8         | 0.25%   |
| Intel Core m3           | 7         | 0.22%   |
| Intel Core              | 7         | 0.22%   |
| AMD Phenom II X6        | 7         | 0.22%   |
| AMD A4                  | 7         | 0.22%   |
| Intel Pentium Silver    | 5         | 0.16%   |
| AMD Phenom II X4        | 5         | 0.16%   |
| AMD Athlon 64 X2        | 5         | 0.16%   |
| Intel Pentium Dual-Core | 4         | 0.13%   |
| Intel Genuine           | 4         | 0.13%   |
| Intel Core m5           | 4         | 0.13%   |
| AMD E                   | 4         | 0.13%   |
| AMD Athlon              | 4         | 0.13%   |
| AMD Ryzen 3 PRO         | 3         | 0.1%    |
| AMD Athlon II           | 3         | 0.1%    |
| Intel Xeon Gold         | 2         | 0.06%   |
| Intel Pentium Dual      | 2         | 0.06%   |
| Intel Core M            | 2         | 0.06%   |
| Intel Core 2 Extreme    | 2         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 986       | 31.24%  |
| 2       | 721       | 22.85%  |
| 8       | 513       | 16.25%  |
| 6       | 451       | 14.29%  |
| 12      | 149       | 4.72%   |
| 10      | 112       | 3.55%   |
| 14      | 92        | 2.92%   |
| 16      | 65        | 2.06%   |
| 24      | 31        | 0.98%   |
| 1       | 9         | 0.29%   |
| 3       | 6         | 0.19%   |
| 32      | 4         | 0.13%   |
| 28      | 4         | 0.13%   |
| 20      | 3         | 0.1%    |
| 18      | 3         | 0.1%    |
| Unknown | 3         | 0.1%    |
| 64      | 1         | 0.03%   |
| 40      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3131      | 99.33%  |
| 2       | 18        | 0.57%   |
| Unknown | 3         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2623      | 83.14%  |
| 1       | 529       | 16.77%  |
| Unknown | 3         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3148      | 99.87%  |
| 64-bit         | 4         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2633      | 82.36%  |
| 0x0a50000d | 57        | 1.78%   |
| 0x0a704103 | 35        | 1.09%   |
| 0x0a404102 | 34        | 1.06%   |
| 0x0a50000c | 29        | 0.91%   |
| 0x08701021 | 28        | 0.88%   |
| 0x08608103 | 26        | 0.81%   |
| 0x0a601206 | 25        | 0.78%   |
| 0x0a601203 | 23        | 0.72%   |
| 0x08600106 | 23        | 0.72%   |
| 0x0a20120a | 21        | 0.66%   |
| 0x08108109 | 19        | 0.59%   |
| 0x08701030 | 17        | 0.53%   |
| 0x0a201016 | 14        | 0.44%   |
| 0x08600109 | 11        | 0.34%   |
| 0x010000c8 | 11        | 0.34%   |
| 0x0a50000f | 10        | 0.31%   |
| 0x08101016 | 10        | 0.31%   |
| 0x0800820d | 10        | 0.31%   |
| 0x0a20120e | 9         | 0.28%   |
| 0x08701013 | 7         | 0.22%   |
| 0x0a704104 | 6         | 0.19%   |
| 0x08608104 | 6         | 0.19%   |
| 0x08608102 | 6         | 0.19%   |
| 0x08600104 | 6         | 0.19%   |
| 0x08600103 | 6         | 0.19%   |
| 0x06006705 | 6         | 0.19%   |
| 0x06000852 | 6         | 0.19%   |
| 0x0a404101 | 5         | 0.16%   |
| 0x08001138 | 5         | 0.16%   |
| 0x08001137 | 5         | 0.16%   |
| 0x06001119 | 5         | 0.16%   |
| 0x0a704101 | 4         | 0.13%   |
| 0x08a00008 | 4         | 0.13%   |
| 0x0a50000b | 3         | 0.09%   |
| 0x0a20102b | 3         | 0.09%   |
| 0x08a00006 | 3         | 0.09%   |
| 0x08108102 | 3         | 0.09%   |
| 0x0810100b | 3         | 0.09%   |
| 0x07030105 | 3         | 0.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 509       | 16.06%  |
| Unknown           | 455       | 14.36%  |
| Zen 3             | 297       | 9.37%   |
| Alderlake Hybrid  | 279       | 8.8%    |
| Haswell           | 208       | 6.56%   |
| TigerLake         | 163       | 5.14%   |
| Zen 2             | 162       | 5.11%   |
| Skylake           | 142       | 4.48%   |
| IvyBridge         | 130       | 4.1%    |
| SandyBridge       | 107       | 3.38%   |
| CometLake         | 78        | 2.46%   |
| Broadwell         | 77        | 2.43%   |
| Zen+              | 72        | 2.27%   |
| Icelake           | 68        | 2.15%   |
| Penryn            | 62        | 1.96%   |
| Westmere          | 52        | 1.64%   |
| Zen               | 50        | 1.58%   |
| Silvermont        | 44        | 1.39%   |
| Goldmont plus     | 34        | 1.07%   |
| Piledriver        | 29        | 0.92%   |
| K10               | 25        | 0.79%   |
| Nehalem           | 22        | 0.69%   |
| Core              | 18        | 0.57%   |
| Excavator         | 17        | 0.54%   |
| K8 Hammer         | 9         | 0.28%   |
| Gracemont         | 9         | 0.28%   |
| Steamroller       | 8         | 0.25%   |
| Puma              | 8         | 0.25%   |
| Tremont           | 6         | 0.19%   |
| Jaguar            | 6         | 0.19%   |
| Goldmont          | 6         | 0.19%   |
| Bobcat            | 6         | 0.19%   |
| Meteorlake Hybrid | 5         | 0.16%   |
| Bonnell           | 3         | 0.09%   |
| K10 Llano         | 2         | 0.06%   |
| NetBurst          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1772      | 46.06%  |
| Nvidia                     | 1054      | 27.4%   |
| AMD                        | 1014      | 26.36%  |
| Matrox Electronics Systems | 3         | 0.08%   |
| ASPEED Technology          | 2         | 0.05%   |
| VIA Technologies           | 1         | 0.03%   |
| Silicon Motion             | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 143       | 3.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 113       | 2.86%   |
| Intel UHD Graphics 620                                                      | 107       | 2.71%   |
| AMD Phoenix1                                                                | 86        | 2.18%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 85        | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 79        | 2%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 78        | 1.98%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 75        | 1.9%    |
| Intel HD Graphics 620                                                       | 75        | 1.9%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 71        | 1.8%    |
| AMD Raphael                                                                 | 68        | 1.72%   |
| AMD Rembrandt [Radeon 680M]                                                 | 66        | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 63        | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 60        | 1.52%   |
| AMD Lucienne                                                                | 57        | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 56        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 52        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 50        | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 46        | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 42        | 1.06%   |
| AMD Barcelo                                                                 | 42        | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 41        | 1.04%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 41        | 1.04%   |
| Intel HD Graphics 5500                                                      | 41        | 1.04%   |
| Intel HD Graphics 530                                                       | 41        | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 41        | 1.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 40        | 1.01%   |
| Intel HD Graphics 630                                                       | 37        | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 36        | 0.91%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 36        | 0.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 33        | 0.84%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 33        | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 32        | 0.81%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 32        | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 31        | 0.79%   |
| Intel Core Processor Integrated Graphics Controller                         | 31        | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 30        | 0.76%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 27        | 0.68%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 26        | 0.66%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 26        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1210      | 38.24%  |
| 1 x AMD            | 729       | 23.04%  |
| 1 x Nvidia         | 458       | 14.48%  |
| Intel + Nvidia     | 449       | 14.19%  |
| AMD + Nvidia       | 138       | 4.36%   |
| 2 x AMD            | 73        | 2.31%   |
| Intel + AMD        | 72        | 2.28%   |
| Other              | 12        | 0.38%   |
| 2 x Intel          | 9         | 0.28%   |
| 2 x Nvidia         | 6         | 0.19%   |
| 1 x Matrox         | 3         | 0.09%   |
| 1 x ASPEED         | 2         | 0.06%   |
| 1 x VIA            | 1         | 0.03%   |
| 1 x Silicon Motion | 1         | 0.03%   |
| AMD + 2 x Nvidia   | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2598      | 81.85%  |
| Proprietary | 436       | 13.74%  |
| Unknown     | 140       | 4.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2098      | 65.34%  |
| 0.01-0.5   | 270       | 8.41%   |
| 1.01-2.0   | 199       | 6.2%    |
| 3.01-4.0   | 172       | 5.36%   |
| 7.01-8.0   | 147       | 4.58%   |
| 0.51-1.0   | 126       | 3.92%   |
| 8.01-16.0  | 102       | 3.18%   |
| 5.01-6.0   | 56        | 1.74%   |
| 16.01-24.0 | 24        | 0.75%   |
| 2.01-3.0   | 16        | 0.5%    |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 426       | 11.83%  |
| Samsung Electronics     | 405       | 11.24%  |
| AU Optronics            | 383       | 10.63%  |
| Chimei Innolux          | 322       | 8.94%   |
| LG Display              | 242       | 6.72%   |
| Dell                    | 235       | 6.52%   |
| Goldstar                | 212       | 5.89%   |
| Apple                   | 141       | 3.91%   |
| Acer                    | 100       | 2.78%   |
| Hewlett-Packard         | 96        | 2.67%   |
| Lenovo                  | 83        | 2.3%    |
| AOC                     | 79        | 2.19%   |
| Philips                 | 77        | 2.14%   |
| Sharp                   | 76        | 2.11%   |
| CSO                     | 56        | 1.55%   |
| ASUSTek Computer        | 56        | 1.55%   |
| Ancor Communications    | 51        | 1.42%   |
| BenQ                    | 48        | 1.33%   |
| PANDA                   | 39        | 1.08%   |
| InfoVision              | 35        | 0.97%   |
| MSI                     | 33        | 0.92%   |
| Iiyama                  | 31        | 0.86%   |
| ViewSonic               | 27        | 0.75%   |
| Gigabyte Technology     | 25        | 0.69%   |
| Sony                    | 20        | 0.56%   |
| TMX                     | 19        | 0.53%   |
| Chi Mei Optoelectronics | 17        | 0.47%   |
| Mi                      | 11        | 0.31%   |
| HKC                     | 10        | 0.28%   |
| Sceptre Tech            | 9         | 0.25%   |
| Panasonic               | 9         | 0.25%   |
| NEC Computers           | 9         | 0.25%   |
| Unknown                 | 8         | 0.22%   |
| Insignia                | 8         | 0.22%   |
| Vizio                   | 7         | 0.19%   |
| Fujitsu Siemens         | 7         | 0.19%   |
| Eizo                    | 7         | 0.19%   |
| HUAWEI                  | 6         | 0.17%   |
| TMA                     | 5         | 0.14%   |
| Gateway                 | 5         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 16        | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 15        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 14        | 0.38%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 14        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 13        | 0.35%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 13        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 13        | 0.35%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 13        | 0.35%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                 | 12        | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 10        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 10        | 0.27%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 10        | 0.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 10        | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 9         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 9         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 8         | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 7         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 7         | 0.19%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 7         | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 7         | 0.19%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 7         | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 7         | 0.19%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 7         | 0.19%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 7         | 0.19%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                      | 7         | 0.19%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 7         | 0.19%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 7         | 0.19%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 6         | 0.16%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 6         | 0.16%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 6         | 0.16%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1538      | 44.74%  |
| 1366x768 (WXGA)    | 360       | 10.47%  |
| 3840x2160 (4K)     | 305       | 8.87%   |
| 2560x1440 (QHD)    | 272       | 7.91%   |
| 1920x1200 (WUXGA)  | 168       | 4.89%   |
| 2880x1800          | 96        | 2.79%   |
| 2560x1600          | 94        | 2.73%   |
| 1600x900 (HD+)     | 77        | 2.24%   |
| 3440x1440          | 59        | 1.72%   |
| 1440x900 (WXGA+)   | 56        | 1.63%   |
| 1680x1050 (WSXGA+) | 48        | 1.4%    |
| 1280x1024 (SXGA)   | 46        | 1.34%   |
| 2560x1080          | 38        | 1.11%   |
| 1280x800 (WXGA)    | 34        | 0.99%   |
| 2256x1504          | 27        | 0.79%   |
| 2160x1440          | 21        | 0.61%   |
| 1920x1280          | 17        | 0.49%   |
| 3840x2400          | 16        | 0.47%   |
| 3840x1080          | 15        | 0.44%   |
| 3200x2000          | 12        | 0.35%   |
| 2880x1620          | 10        | 0.29%   |
| Unknown            | 10        | 0.29%   |
| 3456x2160          | 9         | 0.26%   |
| 1920x540           | 9         | 0.26%   |
| 3072x1920          | 8         | 0.23%   |
| 1360x768           | 8         | 0.23%   |
| 2736x1824          | 7         | 0.2%    |
| 2288x1287          | 7         | 0.2%    |
| 1600x1200          | 7         | 0.2%    |
| 3000x2000          | 6         | 0.17%   |
| 3200x1800 (QHD+)   | 5         | 0.15%   |
| 2240x1400          | 5         | 0.15%   |
| 3840x1600          | 4         | 0.12%   |
| 2520x1680          | 4         | 0.12%   |
| 800x1280           | 3         | 0.09%   |
| 3120x2080          | 3         | 0.09%   |
| 2880x1920          | 3         | 0.09%   |
| 2304x1440          | 3         | 0.09%   |
| 1280x720 (HD)      | 3         | 0.09%   |
| 640x480            | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 850       | 23.55%  |
| 13      | 402       | 11.14%  |
| 27      | 394       | 10.91%  |
| 14      | 359       | 9.94%   |
| 24      | 258       | 7.15%   |
| 23      | 194       | 5.37%   |
| 21      | 148       | 4.1%    |
| 16      | 142       | 3.93%   |
| 31      | 137       | 3.8%    |
| 17      | 115       | 3.19%   |
| 34      | 91        | 2.52%   |
| 12      | 70        | 1.94%   |
| 19      | 52        | 1.44%   |
| 20      | 41        | 1.14%   |
| 18      | 40        | 1.11%   |
| Unknown | 40        | 1.11%   |
| 22      | 29        | 0.8%    |
| 84      | 26        | 0.72%   |
| 11      | 25        | 0.69%   |
| 54      | 19        | 0.53%   |
| 26      | 19        | 0.53%   |
| 32      | 18        | 0.5%    |
| 48      | 14        | 0.39%   |
| 40      | 14        | 0.39%   |
| 72      | 13        | 0.36%   |
| 28      | 8         | 0.22%   |
| 142     | 7         | 0.19%   |
| 25      | 7         | 0.19%   |
| 42      | 6         | 0.17%   |
| 37      | 6         | 0.17%   |
| 33      | 6         | 0.17%   |
| 29      | 6         | 0.17%   |
| 39      | 4         | 0.11%   |
| 36      | 4         | 0.11%   |
| 10      | 4         | 0.11%   |
| 47      | 3         | 0.08%   |
| 46      | 3         | 0.08%   |
| 38      | 3         | 0.08%   |
| 7       | 3         | 0.08%   |
| 86      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1472      | 41.62%  |
| 501-600        | 765       | 21.63%  |
| 201-300        | 353       | 9.98%   |
| 401-500        | 273       | 7.72%   |
| 601-700        | 192       | 5.43%   |
| 351-400        | 171       | 4.83%   |
| 701-800        | 120       | 3.39%   |
| 1001-1500      | 54        | 1.53%   |
| 1501-2000      | 43        | 1.22%   |
| Unknown        | 40        | 1.13%   |
| 801-900        | 28        | 0.79%   |
| 901-1000       | 14        | 0.4%    |
| More than 2000 | 7         | 0.2%    |
| 101-200        | 3         | 0.08%   |
| 1-100          | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2322      | 72.36%  |
| 16/10   | 568       | 17.7%   |
| 21/9    | 102       | 3.18%   |
| 3/2     | 95        | 2.96%   |
| 5/4     | 42        | 1.31%   |
| Unknown | 22        | 0.69%   |
| 32/9    | 15        | 0.47%   |
| 4/3     | 14        | 0.44%   |
| 1.00    | 7         | 0.22%   |
| 6/5     | 6         | 0.19%   |
| 0.56    | 3         | 0.09%   |
| 3.40    | 2         | 0.06%   |
| 1.96    | 2         | 0.06%   |
| 0.67    | 2         | 0.06%   |
| 0.62    | 2         | 0.06%   |
| 3.73    | 1         | 0.03%   |
| 3.33    | 1         | 0.03%   |
| 2.12    | 1         | 0.03%   |
| 2.00    | 1         | 0.03%   |
| 0.89    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 864       | 24.12%  |
| 81-90          | 593       | 16.55%  |
| 201-250        | 489       | 13.65%  |
| 301-350        | 408       | 11.39%  |
| 351-500        | 262       | 7.31%   |
| 71-80          | 156       | 4.36%   |
| 151-200        | 139       | 3.88%   |
| 111-120        | 124       | 3.46%   |
| 251-300        | 96        | 2.68%   |
| 121-130        | 92        | 2.57%   |
| More than 1000 | 83        | 2.32%   |
| 501-1000       | 67        | 1.87%   |
| 61-70          | 60        | 1.68%   |
| 141-150        | 40        | 1.12%   |
| Unknown        | 40        | 1.12%   |
| 51-60          | 28        | 0.78%   |
| 91-100         | 23        | 0.64%   |
| 131-140        | 10        | 0.28%   |
| 1-40           | 5         | 0.14%   |
| 41-50          | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1097      | 31.62%  |
| 51-100        | 929       | 26.78%  |
| 101-120       | 687       | 19.8%   |
| 161-240       | 484       | 13.95%  |
| More than 240 | 171       | 4.93%   |
| 1-50          | 61        | 1.76%   |
| Unknown       | 40        | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2424      | 75.99%  |
| 2     | 560       | 17.55%  |
| 0     | 124       | 3.89%   |
| 3     | 66        | 2.07%   |
| 4     | 14        | 0.44%   |
| 6     | 2         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1692      | 35.83%  |
| Realtek Semiconductor             | 1654      | 35.03%  |
| MediaTek                          | 272       | 5.76%   |
| Broadcom                          | 266       | 5.63%   |
| Qualcomm Atheros                  | 262       | 5.55%   |
| ASIX Electronics                  | 59        | 1.25%   |
| Broadcom Limited                  | 49        | 1.04%   |
| TP-Link                           | 46        | 0.97%   |
| Qualcomm                          | 39        | 0.83%   |
| Ralink Technology                 | 29        | 0.61%   |
| Marvell Technology Group          | 25        | 0.53%   |
| Ralink                            | 23        | 0.49%   |
| Microsoft                         | 23        | 0.49%   |
| Lenovo                            | 17        | 0.36%   |
| Nvidia                            | 16        | 0.34%   |
| Samsung Electronics               | 15        | 0.32%   |
| Dell                              | 15        | 0.32%   |
| Aquantia                          | 15        | 0.32%   |
| Sierra Wireless                   | 14        | 0.3%    |
| DisplayLink                       | 12        | 0.25%   |
| Xiaomi                            | 11        | 0.23%   |
| Qualcomm Atheros Communications   | 11        | 0.23%   |
| NetGear                           | 11        | 0.23%   |
| D-Link                            | 10        | 0.21%   |
| ASUSTek Computer                  | 10        | 0.21%   |
| Motorola PCS                      | 9         | 0.19%   |
| Hewlett-Packard                   | 8         | 0.17%   |
| Google                            | 8         | 0.17%   |
| OPPO Electronics                  | 7         | 0.15%   |
| Apple                             | 6         | 0.13%   |
| Qualcomm Technologies             | 5         | 0.11%   |
| Fibocom                           | 5         | 0.11%   |
| U-Blox                            | 4         | 0.08%   |
| Huawei Technologies               | 4         | 0.08%   |
| Mellanox Technologies             | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| JMicron Technology                | 3         | 0.06%   |
| Ericsson Business Mobile Networks | 3         | 0.06%   |
| D-Link System                     | 3         | 0.06%   |
| AVM                               | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 983       | 17.68%  |
| Realtek RTL8125 2.5GbE Controller                                      | 195       | 3.51%   |
| Intel Wi-Fi 6 AX200                                                    | 190       | 3.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 141       | 2.54%   |
| Intel Wireless 8265 / 8275                                             | 125       | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 124       | 2.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 118       | 2.12%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 118       | 2.12%   |
| Intel Wi-Fi 6 AX201                                                    | 117       | 2.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 101       | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 95        | 1.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 93        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 84        | 1.51%   |
| Intel I211 Gigabit Network Connection                                  | 74        | 1.33%   |
| Intel Ethernet Controller I225-V                                       | 73        | 1.31%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 67        | 1.2%    |
| Intel Wireless 7265                                                    | 63        | 1.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 53        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 51        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 50        | 0.9%    |
| Intel Wireless 8260                                                    | 50        | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 50        | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 49        | 0.88%   |
| Intel Wireless 7260                                                    | 47        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 44        | 0.79%   |
| Intel Ethernet Connection I217-LM                                      | 41        | 0.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 41        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 40        | 0.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 39        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 37        | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 37        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 37        | 0.67%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 35        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                   | 35        | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 33        | 0.59%   |
| Intel Wireless 3165                                                    | 32        | 0.58%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 31        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                          | 30        | 0.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 29        | 0.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 28        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1410      | 50.47%  |
| Realtek Semiconductor                 | 436       | 15.6%   |
| MediaTek                              | 232       | 8.3%    |
| Broadcom                              | 214       | 7.66%   |
| Qualcomm Atheros                      | 206       | 7.37%   |
| Broadcom Limited                      | 46        | 1.65%   |
| TP-Link                               | 42        | 1.5%    |
| Qualcomm                              | 35        | 1.25%   |
| Ralink Technology                     | 29        | 1.04%   |
| Ralink                                | 23        | 0.82%   |
| Microsoft                             | 18        | 0.64%   |
| Sierra Wireless                       | 14        | 0.5%    |
| Dell                                  | 12        | 0.43%   |
| Qualcomm Atheros Communications       | 11        | 0.39%   |
| NetGear                               | 11        | 0.39%   |
| ASUSTek Computer                      | 10        | 0.36%   |
| Marvell Technology Group              | 8         | 0.29%   |
| D-Link                                | 8         | 0.29%   |
| Qualcomm Technologies                 | 5         | 0.18%   |
| Fibocom                               | 5         | 0.18%   |
| Linksys                               | 3         | 0.11%   |
| AVM                                   | 3         | 0.11%   |
| ZyDAS                                 | 2         | 0.07%   |
| Mercucys                              | 2         | 0.07%   |
| Hewlett-Packard                       | 2         | 0.07%   |
| Edimax Technology                     | 2         | 0.07%   |
| Wacom                                 | 1         | 0.04%   |
| Sagem                                 | 1         | 0.04%   |
| D-Link System                         | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 190       | 6.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 140       | 4.99%   |
| Intel Wireless 8265 / 8275                                           | 125       | 4.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 118       | 4.21%   |
| Intel Wi-Fi 6 AX201                                                  | 117       | 4.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 101       | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 95        | 3.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 84        | 2.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 82        | 2.92%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 67        | 2.39%   |
| Intel Wireless 7265                                                  | 63        | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 51        | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 50        | 1.78%   |
| Intel Wireless 8260                                                  | 50        | 1.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 47        | 1.67%   |
| Intel Wireless 7260                                                  | 47        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 44        | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 40        | 1.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 39        | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 37        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 37        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 37        | 1.32%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 35        | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 33        | 1.18%   |
| Intel Wireless 3165                                                  | 32        | 1.14%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 31        | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                        | 30        | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 29        | 1.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 28        | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 27        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 27        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 23        | 0.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 23        | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 23        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 22        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 22        | 0.78%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 21        | 0.75%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller          | 19        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 19        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 19        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1434      | 54.59%  |
| Intel                                  | 733       | 27.9%   |
| Broadcom                               | 117       | 4.45%   |
| Qualcomm Atheros                       | 72        | 2.74%   |
| ASIX Electronics                       | 59        | 2.25%   |
| MediaTek                               | 38        | 1.45%   |
| Marvell Technology Group               | 17        | 0.65%   |
| Lenovo                                 | 17        | 0.65%   |
| Nvidia                                 | 16        | 0.61%   |
| Aquantia                               | 15        | 0.57%   |
| DisplayLink                            | 12        | 0.46%   |
| Xiaomi                                 | 11        | 0.42%   |
| Samsung Electronics                    | 11        | 0.42%   |
| Motorola PCS                           | 9         | 0.34%   |
| OPPO Electronics                       | 7         | 0.27%   |
| Google                                 | 7         | 0.27%   |
| Apple                                  | 6         | 0.23%   |
| TP-Link                                | 4         | 0.15%   |
| Qualcomm                               | 4         | 0.15%   |
| Hewlett-Packard                        | 4         | 0.15%   |
| Microsoft                              | 3         | 0.11%   |
| Mellanox Technologies                  | 3         | 0.11%   |
| JMicron Technology                     | 3         | 0.11%   |
| Huawei Technologies                    | 3         | 0.11%   |
| Broadcom Limited                       | 3         | 0.11%   |
| D-Link System                          | 2         | 0.08%   |
| D-Link                                 | 2         | 0.08%   |
| Unknown                                | 2         | 0.08%   |
| ZyXEL Communications                   | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| VIA Technologies                       | 1         | 0.04%   |
| Tehuti Networks                        | 1         | 0.04%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Solarflare Communications              | 1         | 0.04%   |
| Sharp                                  | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| American Megatrends                    | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 983       | 36.37%  |
| Realtek RTL8125 2.5GbE Controller                                      | 195       | 7.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 124       | 4.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 93        | 3.44%   |
| Intel I211 Gigabit Network Connection                                  | 74        | 2.74%   |
| Intel Ethernet Controller I225-V                                       | 73        | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 50        | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                          | 49        | 1.81%   |
| Intel Ethernet Connection I217-LM                                      | 41        | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 41        | 1.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 36        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 35        | 1.29%   |
| Intel Ethernet Connection (4) I219-V                                   | 27        | 1%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 27        | 1%      |
| Intel Ethernet Connection (2) I219-LM                                  | 26        | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 25        | 0.92%   |
| Realtek Killer E2600 GbE Controller                                    | 23        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                   | 21        | 0.78%   |
| Intel 82574L Gigabit Network Connection                                | 18        | 0.67%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 17        | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 17        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                  | 17        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                  | 16        | 0.59%   |
| Intel I210 Gigabit Network Connection                                  | 15        | 0.55%   |
| Intel Ethernet Connection (16) I219-V                                  | 15        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                  | 14        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 0.52%   |
| Intel Ethernet Connection I218-LM                                      | 13        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                   | 13        | 0.48%   |
| Intel Ethernet Connection (13) I219-V                                  | 13        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 12        | 0.44%   |
| Intel Ethernet Connection I219-V                                       | 12        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 11        | 0.41%   |
| Intel Ethernet Connection (17) I219-V                                  | 11        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                | 11        | 0.41%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 11        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 10        | 0.37%   |
| Intel Ethernet Controller I226-V                                       | 10        | 0.37%   |
| Realtek PCIe GbE Family Controller                                     | 9         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2658      | 51.96%  |
| Ethernet | 2406      | 47.04%  |
| Modem    | 38        | 0.74%   |
| Unknown  | 13        | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2113      | 63.99%  |
| Ethernet | 1188      | 35.98%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1666      | 52.75%  |
| 1     | 1350      | 42.75%  |
| 3     | 91        | 2.88%   |
| 0     | 34        | 1.08%   |
| 4     | 11        | 0.35%   |
| 5     | 3         | 0.09%   |
| 6     | 2         | 0.06%   |
| 11    | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2150      | 67.57%  |
| Yes  | 1032      | 32.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1272      | 51.41%  |
| Realtek Semiconductor           | 285       | 11.52%  |
| IMC Networks                    | 148       | 5.98%   |
| Apple                           | 134       | 5.42%   |
| Foxconn / Hon Hai               | 108       | 4.37%   |
| Qualcomm Atheros Communications | 99        | 4%      |
| MediaTek                        | 75        | 3.03%   |
| Cambridge Silicon Radio         | 65        | 2.63%   |
| Lite-On Technology              | 59        | 2.38%   |
| Broadcom                        | 59        | 2.38%   |
| ASUSTek Computer                | 31        | 1.25%   |
| Realtek                         | 26        | 1.05%   |
| TP-Link                         | 24        | 0.97%   |
| USI                             | 21        | 0.85%   |
| Hewlett-Packard                 | 9         | 0.36%   |
| Dell                            | 8         | 0.32%   |
| Marvell Semiconductor           | 7         | 0.28%   |
| Foxconn International           | 7         | 0.28%   |
| Ralink                          | 6         | 0.24%   |
| Actions                         | 5         | 0.2%    |
| Ralink Technology               | 4         | 0.16%   |
| Toshiba                         | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| Edimax Technology               | 3         | 0.12%   |
| Dynex                           | 2         | 0.08%   |
| Belkin Components               | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| Alps Electric                   | 2         | 0.08%   |
| Unknown                         | 2         | 0.08%   |
| Smart Modular Technologies      | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 319       | 12.89%  |
| Intel AX201 Bluetooth                               | 271       | 10.95%  |
| Intel AX211 Bluetooth                               | 203       | 8.2%    |
| Realtek Bluetooth Radio                             | 197       | 7.96%   |
| Intel AX200 Bluetooth                               | 176       | 7.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 115       | 4.65%   |
| Intel AX210 Bluetooth                               | 113       | 4.57%   |
| IMC Networks Wireless_Device                        | 90        | 3.64%   |
| MediaTek Wireless_Device                            | 75        | 3.03%   |
| Apple Bluetooth Host Controller                     | 69        | 2.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 65        | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 53        | 2.14%   |
| Foxconn / Hon Hai Wireless_Device                   | 53        | 2.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 1.78%   |
| Apple Bluetooth USB Host Controller                 | 40        | 1.62%   |
| IMC Networks Bluetooth Radio                        | 39        | 1.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.49%   |
| Realtek Bluetooth Radio                             | 26        | 1.05%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 26        | 1.05%   |
| Realtek 802.11ac WLAN Adapter                       | 25        | 1.01%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 24        | 0.97%   |
| USI Bluetooth Device                                | 21        | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 0.77%   |
| Lite-On Wireless_Device                             | 18        | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 15        | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.53%   |
| Lite-On Bluetooth Device                            | 12        | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.44%   |
| IMC Networks Bluetooth Device                       | 11        | 0.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.44%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.4%    |
| ASUS ASUS USB-BT500                                 | 10        | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.28%   |
| Lite-On Bluetooth Radio                             | 7         | 0.28%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.28%   |
| Foxconn International BCM43142A0 Bluetooth module   | 7         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2099      | 45.06%  |
| AMD                                  | 1131      | 24.28%  |
| Nvidia                               | 813       | 17.45%  |
| C-Media Electronics                  | 65        | 1.4%    |
| Logitech                             | 44        | 0.94%   |
| JMTek                                | 28        | 0.6%    |
| ASUSTek Computer                     | 27        | 0.58%   |
| Micro Star International             | 22        | 0.47%   |
| GN Netcom                            | 22        | 0.47%   |
| Generalplus Technology               | 22        | 0.47%   |
| Hewlett-Packard                      | 21        | 0.45%   |
| SteelSeries ApS                      | 20        | 0.43%   |
| Realtek Semiconductor                | 19        | 0.41%   |
| Lenovo                               | 19        | 0.41%   |
| Texas Instruments                    | 18        | 0.39%   |
| Razer USA                            | 18        | 0.39%   |
| Creative Labs                        | 17        | 0.36%   |
| Kingston Technology                  | 14        | 0.3%    |
| Apple                                | 14        | 0.3%    |
| Sony                                 | 11        | 0.24%   |
| Plantronics                          | 10        | 0.21%   |
| Focusrite-Novation                   | 10        | 0.21%   |
| Corsair                              | 10        | 0.21%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.17%   |
| Jieli Technology                     | 7         | 0.15%   |
| RODE Microphones                     | 6         | 0.13%   |
| BEHRINGER International              | 6         | 0.13%   |
| Samson Technologies                  | 5         | 0.11%   |
| KTMicro                              | 5         | 0.11%   |
| FiiO Electronics Technology          | 5         | 0.11%   |
| FIFINE Microphones                   | 5         | 0.11%   |
| Blue Microphones                     | 5         | 0.11%   |
| DSEA A/S                             | 4         | 0.09%   |
| Creative Technology                  | 4         | 0.09%   |
| Conexant Systems                     | 4         | 0.09%   |
| ASRock                               | 4         | 0.09%   |
| Arturia                              | 4         | 0.09%   |
| VIA Technologies                     | 3         | 0.06%   |
| TTGK Technology                      | 3         | 0.06%   |
| Trust                                | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 608       | 10.67%  |
| Intel Sunrise Point-LP HD Audio                                            | 288       | 5.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 285       | 5%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 225       | 3.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 193       | 3.39%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 171       | 3%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 163       | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 121       | 2.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 120       | 2.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 112       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 107       | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 103       | 1.81%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 88        | 1.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 80        | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 76        | 1.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 72        | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 70        | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 68        | 1.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 65        | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 64        | 1.12%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 64        | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 63        | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 61        | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 60        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 59        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 58        | 1.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 56        | 0.98%   |
| Intel Alder Lake-S HD Audio Controller                                     | 52        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 48        | 0.84%   |
| Intel 200 Series PCH HD Audio                                              | 46        | 0.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 46        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 45        | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 45        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 44        | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 42        | 0.74%   |
| Intel Raptor Lake High Definition Audio Controller                         | 42        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 39        | 0.68%   |
| Nvidia GA107 High Definition Audio Controller                              | 38        | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 38        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 289       | 22.81%  |
| SK hynix            | 231       | 18.23%  |
| Micron Technology   | 181       | 14.29%  |
| Kingston            | 133       | 10.5%   |
| Crucial             | 84        | 6.63%   |
| Corsair             | 72        | 5.68%   |
| G.Skill             | 59        | 4.66%   |
| Unknown             | 52        | 4.1%    |
| A-DATA Technology   | 23        | 1.82%   |
| Unknown             | 22        | 1.74%   |
| Ramaxel Technology  | 18        | 1.42%   |
| Team                | 13        | 1.03%   |
| Nanya Technology    | 10        | 0.79%   |
| Elpida              | 7         | 0.55%   |
| Patriot             | 6         | 0.47%   |
| Unknown (ABCD)      | 5         | 0.39%   |
| Smart               | 5         | 0.39%   |
| Transcend           | 4         | 0.32%   |
| Timetec             | 4         | 0.32%   |
| Lexar               | 4         | 0.32%   |
| AMD                 | 3         | 0.24%   |
| Patriot Memory      | 2         | 0.16%   |
| Kllisre             | 2         | 0.16%   |
| Hikvision           | 2         | 0.16%   |
| ChangXin Memory     | 2         | 0.16%   |
| Atermiter           | 2         | 0.16%   |
| Apacer              | 2         | 0.16%   |
| Wodposit            | 1         | 0.08%   |
| Wilk                | 1         | 0.08%   |
| V-GeN               | 1         | 0.08%   |
| Unknown (8A5D)      | 1         | 0.08%   |
| Unknown (83DA)      | 1         | 0.08%   |
| Unknown (130B)      | 1         | 0.08%   |
| Unknown (0x8A02)    | 1         | 0.08%   |
| Unknown (0x7FFF)    | 1         | 0.08%   |
| Unknown (0x0B5E)    | 1         | 0.08%   |
| Unknown (09D5)      | 1         | 0.08%   |
| Teikon              | 1         | 0.08%   |
| TBD                 | 1         | 0.08%   |
| TakeMS              | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 22        | 1.64%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 1.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.67%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 8         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 8         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.6%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 7         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 7         | 0.52%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 7         | 0.52%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 6         | 0.45%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 6         | 0.45%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.45%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 6         | 0.45%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                     | 6         | 0.45%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 5         | 0.37%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 5         | 0.37%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.37%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.37%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 0.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.37%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 5         | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.37%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s          | 5         | 0.37%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.3%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 0.3%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 4         | 0.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.3%    |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s            | 4         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 591       | 52.63%  |
| DDR3    | 187       | 16.65%  |
| DDR5    | 125       | 11.13%  |
| LPDDR5  | 90        | 8.01%   |
| LPDDR4  | 54        | 4.81%   |
| LPDDR3  | 44        | 3.92%   |
| DDR2    | 11        | 0.98%   |
| Unknown | 10        | 0.89%   |
| SDRAM   | 8         | 0.71%   |
| DDR     | 2         | 0.18%   |
| DRAM    | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 673       | 59.19%  |
| DIMM         | 291       | 25.59%  |
| Row Of Chips | 160       | 14.07%  |
| Chip         | 8         | 0.7%    |
| Unknown      | 3         | 0.26%   |
| RIMM         | 2         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 500       | 41.84%  |
| 16384 | 289       | 24.18%  |
| 4096  | 227       | 19%     |
| 32768 | 102       | 8.54%   |
| 2048  | 63        | 5.27%   |
| 1024  | 7         | 0.59%   |
| 49152 | 3         | 0.25%   |
| 65536 | 2         | 0.17%   |
| 3072  | 2         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 294       | 24.89%  |
| 2667    | 135       | 11.43%  |
| 1600    | 131       | 11.09%  |
| 6400    | 70        | 5.93%   |
| 2133    | 69        | 5.84%   |
| 2400    | 60        | 5.08%   |
| 4800    | 51        | 4.32%   |
| 5600    | 43        | 3.64%   |
| 3600    | 36        | 3.05%   |
| 1333    | 34        | 2.88%   |
| 4267    | 27        | 2.29%   |
| 1867    | 27        | 2.29%   |
| 7500    | 24        | 2.03%   |
| 1334    | 18        | 1.52%   |
| 6000    | 17        | 1.44%   |
| 3733    | 16        | 1.35%   |
| 4266    | 14        | 1.19%   |
| 3800    | 9         | 0.76%   |
| 3400    | 7         | 0.59%   |
| 3000    | 7         | 0.59%   |
| 800     | 7         | 0.59%   |
| Unknown | 7         | 0.59%   |
| 5200    | 6         | 0.51%   |
| 3466    | 6         | 0.51%   |
| 1066    | 6         | 0.51%   |
| 667     | 6         | 0.51%   |
| 4000    | 5         | 0.42%   |
| 3266    | 5         | 0.42%   |
| 2666    | 4         | 0.34%   |
| 1866    | 4         | 0.34%   |
| 3866    | 3         | 0.25%   |
| 2933    | 3         | 0.25%   |
| 1067    | 3         | 0.25%   |
| 5800    | 2         | 0.17%   |
| 3534    | 2         | 0.17%   |
| 3467    | 2         | 0.17%   |
| 3066    | 2         | 0.17%   |
| 400     | 2         | 0.17%   |
| 12800   | 1         | 0.08%   |
| 8400    | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 38.89%  |
| Brother Industries  | 12        | 22.22%  |
| Canon               | 7         | 12.96%  |
| Seiko Epson         | 4         | 7.41%   |
| Dymo-CoStar         | 4         | 7.41%   |
| Samsung Electronics | 2         | 3.7%    |
| QinHeng Electronics | 1         | 1.85%   |
| Minolta             | 1         | 1.85%   |
| iDPRT               | 1         | 1.85%   |
| Dell                | 1         | 1.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450            | 2         | 3.7%    |
| Brother Printer                        | 2         | 3.7%    |
| Brother MFC-L2710DW series             | 2         | 3.7%    |
| Seiko Epson XP-4100 Series             | 1         | 1.85%   |
| Seiko Epson L3150 Series               | 1         | 1.85%   |
| Seiko Epson L300 Series                | 1         | 1.85%   |
| Seiko Epson AL-M310DN                  | 1         | 1.85%   |
| Samsung ML-216x Series Laser Printer   | 1         | 1.85%   |
| Samsung M203x Series                   | 1         | 1.85%   |
| QinHeng CH340S                         | 1         | 1.85%   |
| Minolta PagePro 1300W                  | 1         | 1.85%   |
| iDPRT SP410                            | 1         | 1.85%   |
| HP Smart Tank 7300 series              | 1         | 1.85%   |
| HP Smart Tank 510 series               | 1         | 1.85%   |
| HP PSC-1315/PSC-1317                   | 1         | 1.85%   |
| HP LaserJet P2015 series               | 1         | 1.85%   |
| HP LaserJet P1102                      | 1         | 1.85%   |
| HP LaserJet P1006                      | 1         | 1.85%   |
| HP LaserJet P1005                      | 1         | 1.85%   |
| HP LaserJet 400 color M451dn           | 1         | 1.85%   |
| HP LaserJet 2200                       | 1         | 1.85%   |
| HP LaserJet 1020                       | 1         | 1.85%   |
| HP LaserJet 1010                       | 1         | 1.85%   |
| HP HP LaserJet Pro M404-M405           | 1         | 1.85%   |
| HP HP LaserJet M14-M17                 | 1         | 1.85%   |
| HP ENVY Photo 7800 series              | 1         | 1.85%   |
| HP ENVY Photo 6200 series              | 1         | 1.85%   |
| HP ENVY 5000 series                    | 1         | 1.85%   |
| HP ENVY 4500 series                    | 1         | 1.85%   |
| HP DeskJet 4100 series                 | 1         | 1.85%   |
| HP DeskJet 3940                        | 1         | 1.85%   |
| HP DeskJet 2700 series                 | 1         | 1.85%   |
| HP DeskJet 2620 All-in-One Printer     | 1         | 1.85%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 1.85%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO   | 1         | 1.85%   |
| Dell C1660w Color Printer              | 1         | 1.85%   |
| Canon TS5300 series                    | 1         | 1.85%   |
| Canon TS3100 series                    | 1         | 1.85%   |
| Canon TR4700 series                    | 1         | 1.85%   |
| Canon PIXMA MX470 Series               | 1         | 1.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 6         | 60%     |
| Seiko Epson        | 3         | 30%     |
| Ultima Electronics | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Ultima Artec E+ Pro                         | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |
| Canon CanoScan LiDE 110                     | 1         | 10%     |
| Canon CanoScan 8800F                        | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 381       | 18.38%  |
| IMC Networks                           | 227       | 10.95%  |
| Microdia                               | 174       | 8.39%   |
| Bison Electronics                      | 147       | 7.09%   |
| Quanta                                 | 136       | 6.56%   |
| Realtek Semiconductor                  | 130       | 6.27%   |
| Logitech                               | 118       | 5.69%   |
| Apple                                  | 95        | 4.58%   |
| Sunplus Innovation Technology          | 93        | 4.49%   |
| Luxvisions Innotech Limited            | 92        | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 59        | 2.85%   |
| Sonix Technology                       | 53        | 2.56%   |
| Syntek                                 | 52        | 2.51%   |
| Acer                                   | 38        | 1.83%   |
| Lite-On Technology                     | 34        | 1.64%   |
| Suyin                                  | 22        | 1.06%   |
| Microsoft                              | 16        | 0.77%   |
| SunplusIT                              | 15        | 0.72%   |
| ShineTech                              | 15        | 0.72%   |
| Samsung Electronics                    | 15        | 0.72%   |
| Silicon Motion                         | 14        | 0.68%   |
| Alcor Micro                            | 14        | 0.68%   |
| Lenovo                                 | 7         | 0.34%   |
| Generalplus Technology                 | 7         | 0.34%   |
| ARC International                      | 6         | 0.29%   |
| Ricoh                                  | 5         | 0.24%   |
| Razer USA                              | 5         | 0.24%   |
| Trust                                  | 4         | 0.19%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.19%   |
| icSpring                               | 4         | 0.19%   |
| AVerMedia Technologies                 | 4         | 0.19%   |
| Alpha Imaging Technology               | 4         | 0.19%   |
| 2M UVC CAMERA                          | 4         | 0.19%   |
| Z-Star Microelectronics                | 3         | 0.14%   |
| Qtech                                  | 3         | 0.14%   |
| Primax Electronics                     | 3         | 0.14%   |
| MacroSilicon                           | 3         | 0.14%   |
| KYE Systems (Mouse Systems)            | 3         | 0.14%   |
| kingcome                               | 3         | 0.14%   |
| GEMBIRD                                | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 123       | 5.87%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 89        | 4.25%   |
| Microdia Integrated_Webcam_HD                       | 72        | 3.44%   |
| IMC Networks Integrated Camera                      | 70        | 3.34%   |
| Realtek Integrated_Webcam_HD                        | 56        | 2.67%   |
| Bison Integrated Camera                             | 55        | 2.63%   |
| Syntek Integrated Camera                            | 41        | 1.96%   |
| Sunplus Integrated_Webcam_HD                        | 31        | 1.48%   |
| Apple FaceTime HD Camera (Built-in)                 | 30        | 1.43%   |
| Sonix USB2.0 HD UVC WebCam                          | 28        | 1.34%   |
| Quanta HD User Facing                               | 26        | 1.24%   |
| Logitech HD Pro Webcam C920                         | 25        | 1.19%   |
| Luxvisions Innotech Limited Integrated Camera       | 23        | 1.1%    |
| Chicony HP HD Camera                                | 22        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 21        | 1%      |
| Apple FaceTime HD Camera                            | 21        | 1%      |
| Chicony HD Webcam                                   | 20        | 0.95%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 19        | 0.91%   |
| Apple Built-in iSight                               | 19        | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 18        | 0.86%   |
| Chicony HP Truevision HD camera                     | 18        | 0.86%   |
| Logitech Webcam C270                                | 17        | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 17        | 0.81%   |
| Chicony Integrated Camera (1280x720@30)             | 17        | 0.81%   |
| Quanta ACER HD User Facing                          | 16        | 0.76%   |
| Microdia USB 2.0 Camera                             | 16        | 0.76%   |
| IMC Networks HD Camera                              | 16        | 0.76%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)             | 15        | 0.72%   |
| Bison HD Webcam                                     | 15        | 0.72%   |
| Quanta HP Wide Vision HD Camera                     | 14        | 0.67%   |
| Quanta HP TrueVision HD Camera                      | 14        | 0.67%   |
| Microdia Webcam Vitade AF                           | 14        | 0.67%   |
| Microdia Integrated_Webcam_FHD                      | 14        | 0.67%   |
| Chicony HP Wide Vision HD Camera                    | 14        | 0.67%   |
| Chicony HD User Facing                              | 14        | 0.67%   |
| Acer Integrated Camera                              | 14        | 0.67%   |
| Sonix USB2.0 FHD UVC WebCam                         | 13        | 0.62%   |
| Microdia Integrated Webcam                          | 13        | 0.62%   |
| Chicony HP TrueVision HD                            | 13        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 162       | 40.81%  |
| Validity Sensors                   | 97        | 24.43%  |
| Shenzhen Goodix Technology         | 69        | 17.38%  |
| Elan Microelectronics              | 31        | 7.81%   |
| Upek                               | 13        | 3.27%   |
| Realtek USB2.0 Finger Print Bridge | 9         | 2.27%   |
| LighTuning Technology              | 9         | 2.27%   |
| Samsung Electronics                | 2         | 0.5%    |
| AuthenTec                          | 2         | 0.5%    |
| FocalTech                          | 1         | 0.25%   |
| Focal-systems.Corp                 | 1         | 0.25%   |
| Dell                               | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 10.33%  |
| Shenzhen Goodix  FingerPrint Device                                        | 39        | 9.82%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 8.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 5.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 5.79%   |
| Synaptics Prometheus Fingerprint Reader                                    | 16        | 4.03%   |
| Elan ELAN:Fingerprint                                                      | 16        | 4.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 3.78%   |
| Elan ELAN:ARM-M4                                                           | 15        | 3.78%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 3.53%   |
| Synaptics UWP WBDI Device                                                  | 14        | 3.53%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 2.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.27%   |
| Synaptics UWP WBDI                                                         | 9         | 2.27%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 9         | 2.27%   |
| Synaptics WBDI                                                             | 8         | 2.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.76%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 1.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.26%   |
| Validity Sensors VFS491                                                    | 4         | 1.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.01%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.76%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.76%   |
| Synaptics  WBDI                                                            | 3         | 0.76%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.76%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.5%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.5%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.25%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.25%   |
| Upek TCS1C EIM/STM32 Fingerprint sensor                                    | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 82        | 49.7%   |
| Alcor Micro               | 59        | 35.76%  |
| Upek                      | 4         | 2.42%   |
| Lenovo                    | 3         | 1.82%   |
| Advanced Card Systems     | 3         | 1.82%   |
| Yubico.com                | 2         | 1.21%   |
| OmniKey                   | 2         | 1.21%   |
| CHERRY                    | 2         | 1.21%   |
| Reiner SCT Kartensysteme  | 1         | 0.61%   |
| Realtek Semiconductor     | 1         | 0.61%   |
| O2 Micro                  | 1         | 0.61%   |
| NXP Semiconductors        | 1         | 0.61%   |
| Gemalto (was Gemplus)     | 1         | 0.61%   |
| Chicony Electronics       | 1         | 0.61%   |
| Aladdin Knowledge Systems | 1         | 0.61%   |
| Aktiv                     | 1         | 0.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 59        | 35.76%  |
| Broadcom 58200                                                               | 27        | 16.36%  |
| Broadcom BCM5880 Secure Applications Processor                               | 23        | 13.94%  |
| Broadcom 5880                                                                | 22        | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.42%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 1.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.21%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 1.21%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.61%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.61%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.61%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.61%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.61%   |
| NXP Semiconductors PR533                                                     | 1         | 0.61%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.61%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.61%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.61%   |
| Aktiv Rutoken lite                                                           | 1         | 0.61%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.61%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.61%   |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 0.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2122      | 66.9%   |
| 1     | 883       | 27.84%  |
| 2     | 143       | 4.51%   |
| 3     | 14        | 0.44%   |
| 4     | 5         | 0.16%   |
| 7     | 2         | 0.06%   |
| 5     | 2         | 0.06%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 391       | 32.1%   |
| Graphics card            | 357       | 29.31%  |
| Multimedia controller    | 196       | 16.09%  |
| Net/wireless             | 117       | 9.61%   |
| Unassigned class         | 27        | 2.22%   |
| Chipcard                 | 25        | 2.05%   |
| Sound                    | 24        | 1.97%   |
| Camera                   | 19        | 1.56%   |
| Bluetooth                | 15        | 1.23%   |
| Net/ethernet             | 12        | 0.99%   |
| Communication controller | 7         | 0.57%   |
| Network                  | 6         | 0.49%   |
| Storage/raid             | 5         | 0.41%   |
| Storage                  | 5         | 0.41%   |
| Card reader              | 5         | 0.41%   |
| Modem                    | 4         | 0.33%   |
| Storage/ide              | 2         | 0.16%   |
| Storage/nvme             | 1         | 0.08%   |

