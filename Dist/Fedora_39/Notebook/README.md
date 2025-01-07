Fedora 39 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 39.

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

Total: 2448

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z97N-WIFI                   | [94525b433d](https://linux-hardware.org/?probe=94525b433d) | Jan 04, 2025 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [f453563b1e](https://linux-hardware.org/?probe=f453563b1e) | Jan 02, 2025 |
| Dell          | Latitude E6430              | [3bbd75ec42](https://linux-hardware.org/?probe=3bbd75ec42) | Dec 28, 2024 |
| HP            | ENVY m6                     | [4060abf5de](https://linux-hardware.org/?probe=4060abf5de) | Dec 18, 2024 |
| Apple         | MacBookPro4,1               | [4dba947354](https://linux-hardware.org/?probe=4dba947354) | Dec 06, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | [453f972762](https://linux-hardware.org/?probe=453f972762) | Nov 26, 2024 |
| TUXEDO        | InfinityBook Pro Intel G... | [dd0ea1fc00](https://linux-hardware.org/?probe=dd0ea1fc00) | Nov 24, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6ff921cfe0](https://linux-hardware.org/?probe=6ff921cfe0) | Nov 23, 2024 |
| Dell          | Latitude 5290 2-in-1        | [0ad9b505c5](https://linux-hardware.org/?probe=0ad9b505c5) | Nov 22, 2024 |
| HP            | ProBook 430 G5              | [1dd8b2a540](https://linux-hardware.org/?probe=1dd8b2a540) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [9fe7b0c308](https://linux-hardware.org/?probe=9fe7b0c308) | Nov 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [7a1de5717e](https://linux-hardware.org/?probe=7a1de5717e) | Nov 09, 2024 |
| Apple         | MacBookAir7,2               | [260459f303](https://linux-hardware.org/?probe=260459f303) | Nov 02, 2024 |
| HP            | ProBook 450 G3              | [2c354565cb](https://linux-hardware.org/?probe=2c354565cb) | Oct 20, 2024 |
| MSI           | Creator 17 A10SE            | [e5802f03e9](https://linux-hardware.org/?probe=e5802f03e9) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [ebed367b62](https://linux-hardware.org/?probe=ebed367b62) | Oct 16, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [facae97aa8](https://linux-hardware.org/?probe=facae97aa8) | Oct 16, 2024 |
| Dell          | Latitude 5510               | [c97d14c219](https://linux-hardware.org/?probe=c97d14c219) | Oct 14, 2024 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [11927afbf6](https://linux-hardware.org/?probe=11927afbf6) | Oct 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [48cb304978](https://linux-hardware.org/?probe=48cb304978) | Oct 11, 2024 |
| Dell          | Latitude E6500              | [79b47fa7fc](https://linux-hardware.org/?probe=79b47fa7fc) | Oct 10, 2024 |
| Framework     | Laptop                      | [806d098add](https://linux-hardware.org/?probe=806d098add) | Oct 10, 2024 |
| Positivo      | J14GL11                     | [8978098dbf](https://linux-hardware.org/?probe=8978098dbf) | Oct 10, 2024 |
| HP            | EliteBook 2740p             | [8eaeff2eea](https://linux-hardware.org/?probe=8eaeff2eea) | Oct 09, 2024 |
| Dell          | Precision M4400             | [a1b83717fb](https://linux-hardware.org/?probe=a1b83717fb) | Oct 06, 2024 |
| Dell          | Latitude 5490               | [a36413cf8d](https://linux-hardware.org/?probe=a36413cf8d) | Oct 01, 2024 |
| Dell          | Latitude 5490               | [9ae5fc5d61](https://linux-hardware.org/?probe=9ae5fc5d61) | Oct 01, 2024 |
| Dell          | G5 5587                     | [4d3bbb7799](https://linux-hardware.org/?probe=4d3bbb7799) | Oct 01, 2024 |
| Dell          | G5 5587                     | [4d6949b64f](https://linux-hardware.org/?probe=4d6949b64f) | Oct 01, 2024 |
| Dell          | Latitude 3520               | [d28f3e3298](https://linux-hardware.org/?probe=d28f3e3298) | Sep 28, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [27fbea506b](https://linux-hardware.org/?probe=27fbea506b) | Sep 18, 2024 |
| Dell          | Precision 7550              | [2a28845245](https://linux-hardware.org/?probe=2a28845245) | Sep 17, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [38e00d68ca](https://linux-hardware.org/?probe=38e00d68ca) | Sep 15, 2024 |
| Fujitsu       | UH-X                        | [981737896a](https://linux-hardware.org/?probe=981737896a) | Sep 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [bf0a437c11](https://linux-hardware.org/?probe=bf0a437c11) | Sep 14, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [4c19a63fee](https://linux-hardware.org/?probe=4c19a63fee) | Sep 02, 2024 |
| Dell          | Latitude 5511               | [337579e62a](https://linux-hardware.org/?probe=337579e62a) | Sep 01, 2024 |
| Acer          | Aspire A315-51              | [9ed7c06816](https://linux-hardware.org/?probe=9ed7c06816) | Aug 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [24df3aeea1](https://linux-hardware.org/?probe=24df3aeea1) | Aug 30, 2024 |
| HP            | ProBook 440 G2              | [cdc5ac1794](https://linux-hardware.org/?probe=cdc5ac1794) | Aug 30, 2024 |
| Maibenben     | MaiBook X series            | [0bbba9b117](https://linux-hardware.org/?probe=0bbba9b117) | Aug 30, 2024 |
| Dell          | G5 5587                     | [07255cca6b](https://linux-hardware.org/?probe=07255cca6b) | Aug 29, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [530d4ccb8b](https://linux-hardware.org/?probe=530d4ccb8b) | Aug 29, 2024 |
| Dell          | G5 5587                     | [ff625fce04](https://linux-hardware.org/?probe=ff625fce04) | Aug 28, 2024 |
| Dell          | Precision 3550              | [a95dae2362](https://linux-hardware.org/?probe=a95dae2362) | Aug 28, 2024 |
| Dell          | Precision 3550              | [e1f44712bd](https://linux-hardware.org/?probe=e1f44712bd) | Aug 26, 2024 |
| Dell          | Precision 3581              | [4812e53bbd](https://linux-hardware.org/?probe=4812e53bbd) | Aug 22, 2024 |
| Acer          | Nitro AN515-54              | [ad3c00e8f4](https://linux-hardware.org/?probe=ad3c00e8f4) | Aug 21, 2024 |
| HP            | Pavilion 15                 | [a0741415f2](https://linux-hardware.org/?probe=a0741415f2) | Aug 18, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [15d1dd3590](https://linux-hardware.org/?probe=15d1dd3590) | Aug 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [cb5166ed3f](https://linux-hardware.org/?probe=cb5166ed3f) | Aug 17, 2024 |
| Acer          | Aspire A515-51G             | [4ed4d6408d](https://linux-hardware.org/?probe=4ed4d6408d) | Aug 16, 2024 |
| Acer          | Nitro AN515-54              | [5e665a9269](https://linux-hardware.org/?probe=5e665a9269) | Aug 15, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [b53667784c](https://linux-hardware.org/?probe=b53667784c) | Aug 14, 2024 |
| Dell          | Latitude E5570              | [bffba2f618](https://linux-hardware.org/?probe=bffba2f618) | Aug 13, 2024 |
| HP            | Laptop 15-gw0xxx            | [cf835ce8d2](https://linux-hardware.org/?probe=cf835ce8d2) | Aug 11, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [e7c6b20b64](https://linux-hardware.org/?probe=e7c6b20b64) | Aug 06, 2024 |
| HP            | Pavilion 15                 | [f237100ca6](https://linux-hardware.org/?probe=f237100ca6) | Aug 05, 2024 |
| HP            | Pavilion 15                 | [f1f40fc065](https://linux-hardware.org/?probe=f1f40fc065) | Aug 04, 2024 |
| TUXEDO        | Pulse 14 Gen1               | [0a09eb534e](https://linux-hardware.org/?probe=0a09eb534e) | Aug 02, 2024 |
| HP            | ProBook 4720s               | [051178bbab](https://linux-hardware.org/?probe=051178bbab) | Aug 02, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | [3e723d09c8](https://linux-hardware.org/?probe=3e723d09c8) | Aug 02, 2024 |
| HP            | ProBook 4720s               | [d8c638a8fc](https://linux-hardware.org/?probe=d8c638a8fc) | Aug 01, 2024 |
| Apple         | MacBookPro6,2               | [775c5ab4cb](https://linux-hardware.org/?probe=775c5ab4cb) | Jul 30, 2024 |
| ASUSTek       | X580VD                      | [8338f52205](https://linux-hardware.org/?probe=8338f52205) | Jul 30, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [7243635706](https://linux-hardware.org/?probe=7243635706) | Jul 26, 2024 |
| Dell          | XPS 15 7590                 | [987e2409a2](https://linux-hardware.org/?probe=987e2409a2) | Jul 23, 2024 |
| ASUSTek       | ROG Strix G834JY_G834JY     | [7fd40ce962](https://linux-hardware.org/?probe=7fd40ce962) | Jul 22, 2024 |
| HP            | ProBook 450 15.6 inch G1... | [82f8235d1f](https://linux-hardware.org/?probe=82f8235d1f) | Jul 19, 2024 |
| Apple         | MacBookPro11,1              | [fa917601f3](https://linux-hardware.org/?probe=fa917601f3) | Jul 19, 2024 |
| Lenovo        | ThinkPad T460 20FNXXXXXX    | [89461ad3f5](https://linux-hardware.org/?probe=89461ad3f5) | Jul 17, 2024 |
| HP            | ProBook 650 G2              | [0f1d9f1114](https://linux-hardware.org/?probe=0f1d9f1114) | Jul 17, 2024 |
| Dell          | Precision 3581              | [3d98230cf1](https://linux-hardware.org/?probe=3d98230cf1) | Jul 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d82aef88f6](https://linux-hardware.org/?probe=d82aef88f6) | Jul 11, 2024 |
| Alienware     | M17xR4                      | [32183f94dc](https://linux-hardware.org/?probe=32183f94dc) | Jul 08, 2024 |
| Dell          | XPS 13 9310                 | [efea3f1526](https://linux-hardware.org/?probe=efea3f1526) | Jul 06, 2024 |
| Acer          | Swift SFG14-42              | [3623aaf512](https://linux-hardware.org/?probe=3623aaf512) | Jul 05, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [250703f607](https://linux-hardware.org/?probe=250703f607) | Jul 01, 2024 |
| Intel         | SandyBridge Platform        | [2c314cd985](https://linux-hardware.org/?probe=2c314cd985) | Jul 01, 2024 |
| HP            | Laptop 14-bp0xx             | [2c410dd7fe](https://linux-hardware.org/?probe=2c410dd7fe) | Jun 29, 2024 |
| MSI           | Prestige 15 A10SC           | [70cdd930fc](https://linux-hardware.org/?probe=70cdd930fc) | Jun 29, 2024 |
| ASUSTek       | K53SJ                       | [e94ec7fe9f](https://linux-hardware.org/?probe=e94ec7fe9f) | Jun 29, 2024 |
| Dell          | Latitude 5420               | [3fa5be31e1](https://linux-hardware.org/?probe=3fa5be31e1) | Jun 28, 2024 |
| ASUSTek       | K53SJ                       | [a9bc21a345](https://linux-hardware.org/?probe=a9bc21a345) | Jun 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d1321209ae](https://linux-hardware.org/?probe=d1321209ae) | Jun 20, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [b0c89c790e](https://linux-hardware.org/?probe=b0c89c790e) | Jun 19, 2024 |
| Acer          | Aspire A515-51              | [12bef8e1b7](https://linux-hardware.org/?probe=12bef8e1b7) | Jun 17, 2024 |
| Dell          | Vostro 3550                 | [bd4f65c637](https://linux-hardware.org/?probe=bd4f65c637) | Jun 15, 2024 |
| Dell          | Inspiron 5570               | [8d755f7cf7](https://linux-hardware.org/?probe=8d755f7cf7) | Jun 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cf4e34380f](https://linux-hardware.org/?probe=cf4e34380f) | Jun 14, 2024 |
| Notebook      | PCx0Dx                      | [a4312875de](https://linux-hardware.org/?probe=a4312875de) | Jun 14, 2024 |
| ASUSTek       | P8Z77-M                     | [f98288d257](https://linux-hardware.org/?probe=f98288d257) | Jun 11, 2024 |
| Dell          | Precision M4800             | [24cd1eb79e](https://linux-hardware.org/?probe=24cd1eb79e) | Jun 11, 2024 |
| Acer          | Aspire A515-51              | [be7539d177](https://linux-hardware.org/?probe=be7539d177) | Jun 10, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [9e5813c818](https://linux-hardware.org/?probe=9e5813c818) | Jun 10, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [f673ab8e59](https://linux-hardware.org/?probe=f673ab8e59) | Jun 09, 2024 |
| Dell          | Latitude 3420               | [356a53eef2](https://linux-hardware.org/?probe=356a53eef2) | Jun 08, 2024 |
| Dell          | Latitude 3420               | [0b6a5b6ad8](https://linux-hardware.org/?probe=0b6a5b6ad8) | Jun 08, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [9baa52a13a](https://linux-hardware.org/?probe=9baa52a13a) | Jun 07, 2024 |
| Dell          | Latitude E5550              | [ed6db64146](https://linux-hardware.org/?probe=ed6db64146) | Jun 05, 2024 |
| Dell          | Latitude E5550              | [15f86e228b](https://linux-hardware.org/?probe=15f86e228b) | Jun 05, 2024 |
| Dell          | Latitude E7440              | [263c956b64](https://linux-hardware.org/?probe=263c956b64) | Jun 05, 2024 |
| HP            | EliteBook 840 G5            | [e46cc0b4af](https://linux-hardware.org/?probe=e46cc0b4af) | Jun 04, 2024 |
| Fujitsu       | LIFEBOOK U7512              | [f38e471977](https://linux-hardware.org/?probe=f38e471977) | Jun 04, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | [8ffa5bb807](https://linux-hardware.org/?probe=8ffa5bb807) | Jun 04, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | [695c57972e](https://linux-hardware.org/?probe=695c57972e) | Jun 03, 2024 |
| ASUSTek       | ROG Strix G713QC_G713QC     | [9e18cd2da0](https://linux-hardware.org/?probe=9e18cd2da0) | Jun 01, 2024 |
| Dell          | Precision 5530              | [338bd4ade5](https://linux-hardware.org/?probe=338bd4ade5) | May 30, 2024 |
| Apple         | MacBookPro8,1               | [1cbdc6d75a](https://linux-hardware.org/?probe=1cbdc6d75a) | May 29, 2024 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [3c54f52a2e](https://linux-hardware.org/?probe=3c54f52a2e) | May 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8b30e5083a](https://linux-hardware.org/?probe=8b30e5083a) | May 26, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [992d9c19d9](https://linux-hardware.org/?probe=992d9c19d9) | May 24, 2024 |
| Dell          | Latitude 7490               | [dc8c6d63c4](https://linux-hardware.org/?probe=dc8c6d63c4) | May 24, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [999f88f47b](https://linux-hardware.org/?probe=999f88f47b) | May 23, 2024 |
| HP            | EliteBook 840 G5 NOTEBOO... | [eb52e3154b](https://linux-hardware.org/?probe=eb52e3154b) | May 23, 2024 |
| HP            | ProBook 455 G8 Notebook ... | [ef99542c79](https://linux-hardware.org/?probe=ef99542c79) | May 23, 2024 |
| Dell          | Inspiron 15-3567            | [d3f04d564b](https://linux-hardware.org/?probe=d3f04d564b) | May 23, 2024 |
| HP            | EliteBook 840 G5 NOTEBOO... | [6f77b13646](https://linux-hardware.org/?probe=6f77b13646) | May 22, 2024 |
| Biostar       | A320MH                      | [23e9b549bf](https://linux-hardware.org/?probe=23e9b549bf) | May 22, 2024 |
| Positivo      | C4128G-15                   | [3a626484f8](https://linux-hardware.org/?probe=3a626484f8) | May 22, 2024 |
| HUAWEI        | KLVL-WXXW                   | [1eec079f69](https://linux-hardware.org/?probe=1eec079f69) | May 21, 2024 |
| Dell          | Precision 5530              | [8762044e9b](https://linux-hardware.org/?probe=8762044e9b) | May 21, 2024 |
| Google        | Kohaku                      | [cb6bc17115](https://linux-hardware.org/?probe=cb6bc17115) | May 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d24473f51e](https://linux-hardware.org/?probe=d24473f51e) | May 20, 2024 |
| Dell          | Vostro 7620                 | [cf9fa662a8](https://linux-hardware.org/?probe=cf9fa662a8) | May 20, 2024 |
| HP            | EliteBook 840 14 inch G9... | [7ccc346dd5](https://linux-hardware.org/?probe=7ccc346dd5) | May 19, 2024 |
| Dell          | Latitude E6400              | [47b3359fb9](https://linux-hardware.org/?probe=47b3359fb9) | May 18, 2024 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6dd9c07f0b](https://linux-hardware.org/?probe=6dd9c07f0b) | May 18, 2024 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [f37d97c956](https://linux-hardware.org/?probe=f37d97c956) | May 18, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a759c66b0d](https://linux-hardware.org/?probe=a759c66b0d) | May 18, 2024 |
| HP            | Pavilion Gaming Laptop      | [28fc9d064e](https://linux-hardware.org/?probe=28fc9d064e) | May 18, 2024 |
| MSI           | Cyborg 15 A12VF             | [4301eba9f0](https://linux-hardware.org/?probe=4301eba9f0) | May 17, 2024 |
| Toshiba       | Satellite L50-B             | [4179b24509](https://linux-hardware.org/?probe=4179b24509) | May 17, 2024 |
| HP            | Pavilion 15                 | [20c16d020a](https://linux-hardware.org/?probe=20c16d020a) | May 17, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [5312f02fde](https://linux-hardware.org/?probe=5312f02fde) | May 17, 2024 |
| Lenovo        | Unknown                     | [d427cb3b64](https://linux-hardware.org/?probe=d427cb3b64) | May 17, 2024 |
| Sony          | VPCYB45JB                   | [747ffc4d2a](https://linux-hardware.org/?probe=747ffc4d2a) | May 16, 2024 |
| Dell          | Latitude 5290 2-in-1        | [a2cb0cc623](https://linux-hardware.org/?probe=a2cb0cc623) | May 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [540f2a33ee](https://linux-hardware.org/?probe=540f2a33ee) | May 15, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [448f5f4b26](https://linux-hardware.org/?probe=448f5f4b26) | May 14, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [8f9768a181](https://linux-hardware.org/?probe=8f9768a181) | May 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [7ec91a9d57](https://linux-hardware.org/?probe=7ec91a9d57) | May 12, 2024 |
| MSI           | Modern 14 C5M               | [b6a9ef050c](https://linux-hardware.org/?probe=b6a9ef050c) | May 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [da2ad0241c](https://linux-hardware.org/?probe=da2ad0241c) | May 11, 2024 |
| HP            | Laptop 14-cf2xxx            | [68e3c2e111](https://linux-hardware.org/?probe=68e3c2e111) | May 10, 2024 |
| ASUSTek       | K95VJ                       | [5a2ea253cd](https://linux-hardware.org/?probe=5a2ea253cd) | May 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cc2aa8c7b7](https://linux-hardware.org/?probe=cc2aa8c7b7) | May 10, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [28e810ba0f](https://linux-hardware.org/?probe=28e810ba0f) | May 10, 2024 |
| HP            | ENVY m6                     | [73cac9c76c](https://linux-hardware.org/?probe=73cac9c76c) | May 10, 2024 |
| HP            | ENVY m6                     | [2a3b768042](https://linux-hardware.org/?probe=2a3b768042) | May 10, 2024 |
| Dell          | Latitude E7440              | [618401e8ee](https://linux-hardware.org/?probe=618401e8ee) | May 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | [7e269a1574](https://linux-hardware.org/?probe=7e269a1574) | May 09, 2024 |
| HP            | EliteBook 840 G5            | [6da57784a6](https://linux-hardware.org/?probe=6da57784a6) | May 09, 2024 |
| Sony          | VPCYB45JB                   | [6f70d22391](https://linux-hardware.org/?probe=6f70d22391) | May 09, 2024 |
| Avell High... | A70 MOB                     | [2be654083e](https://linux-hardware.org/?probe=2be654083e) | May 08, 2024 |
| HP            | EliteBook 840 G6            | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| Dell          | XPS 15 9520                 | [70022231bd](https://linux-hardware.org/?probe=70022231bd) | May 07, 2024 |
| HP            | ENVY Notebook 13-ab0XX      | [7d6b757088](https://linux-hardware.org/?probe=7d6b757088) | May 07, 2024 |
| HP            | ENVY Notebook 13-ab0XX      | [a9d1c1234c](https://linux-hardware.org/?probe=a9d1c1234c) | May 07, 2024 |
| Star Labs     | StarBook                    | [7e37692a50](https://linux-hardware.org/?probe=7e37692a50) | May 06, 2024 |
| ASUSTek       | X550CA                      | [5038e329fc](https://linux-hardware.org/?probe=5038e329fc) | May 06, 2024 |
| ASUSTek       | ROG Strix G731GV_G731GV     | [00ceb2ea16](https://linux-hardware.org/?probe=00ceb2ea16) | May 06, 2024 |
| Positivo      | J14GL11                     | [71f761fa87](https://linux-hardware.org/?probe=71f761fa87) | May 05, 2024 |
| ASUSTek       | X510UAR                     | [3317acbe53](https://linux-hardware.org/?probe=3317acbe53) | May 05, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [6794452c3b](https://linux-hardware.org/?probe=6794452c3b) | May 05, 2024 |
| HP            | 240 G8                      | [8b7c23e6cb](https://linux-hardware.org/?probe=8b7c23e6cb) | May 05, 2024 |
| Unknown       | Unknown                     | [b7866b963f](https://linux-hardware.org/?probe=b7866b963f) | May 04, 2024 |
| MSI           | Raider GE68HX 13VG          | [b3f866a8e6](https://linux-hardware.org/?probe=b3f866a8e6) | May 04, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | [eac9faa98c](https://linux-hardware.org/?probe=eac9faa98c) | May 03, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [44e9f4946e](https://linux-hardware.org/?probe=44e9f4946e) | May 03, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [02a14960a9](https://linux-hardware.org/?probe=02a14960a9) | May 03, 2024 |
| Lenovo        | IdeaPad Z500 20202          | [41468a4e5c](https://linux-hardware.org/?probe=41468a4e5c) | May 03, 2024 |
| Schenker      | XMG CORE 15(M20, RTX 206... | [e22a67c560](https://linux-hardware.org/?probe=e22a67c560) | May 02, 2024 |
| Lenovo        | IdeaPad Z500 20202          | [f7e35750cd](https://linux-hardware.org/?probe=f7e35750cd) | May 02, 2024 |
| LG Electro... | 16Z90P-G.AA76G              | [f9bdc22f6f](https://linux-hardware.org/?probe=f9bdc22f6f) | May 01, 2024 |
| Dell          | Inspiron 7537               | [d27f9ad169](https://linux-hardware.org/?probe=d27f9ad169) | May 01, 2024 |
| Lenovo        | ThinkPad SL510 2847Q7G      | [c2f435ff58](https://linux-hardware.org/?probe=c2f435ff58) | May 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [badf656eaf](https://linux-hardware.org/?probe=badf656eaf) | May 01, 2024 |
| Apple         | MacBookPro15,2              | [5d0cceea3e](https://linux-hardware.org/?probe=5d0cceea3e) | Apr 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [3c551032a7](https://linux-hardware.org/?probe=3c551032a7) | Apr 30, 2024 |
| HP            | EliteBook 840 G4            | [86a58844a8](https://linux-hardware.org/?probe=86a58844a8) | Apr 30, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d4e717f7b6](https://linux-hardware.org/?probe=d4e717f7b6) | Apr 29, 2024 |
| Dell          | Latitude 5420               | [0a95f2013b](https://linux-hardware.org/?probe=0a95f2013b) | Apr 28, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e2a9d44509](https://linux-hardware.org/?probe=e2a9d44509) | Apr 28, 2024 |
| HP            | Pavilion Notebook           | [6da1776d42](https://linux-hardware.org/?probe=6da1776d42) | Apr 28, 2024 |
| Star Labs     | StarBook                    | [99017e5822](https://linux-hardware.org/?probe=99017e5822) | Apr 28, 2024 |
| HP            | Notebook                    | [6252c3e002](https://linux-hardware.org/?probe=6252c3e002) | Apr 28, 2024 |
| HP            | EliteBook 830 G6            | [6b74d2c1b5](https://linux-hardware.org/?probe=6b74d2c1b5) | Apr 27, 2024 |
| Acer          | Nitro AN515-58              | [5192e9d32b](https://linux-hardware.org/?probe=5192e9d32b) | Apr 27, 2024 |
| Acer          | Aspire A314-35              | [b81c267e1b](https://linux-hardware.org/?probe=b81c267e1b) | Apr 27, 2024 |
| Dell          | Inspiron 15 3520            | [e8f25e02cb](https://linux-hardware.org/?probe=e8f25e02cb) | Apr 27, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [46e559a9de](https://linux-hardware.org/?probe=46e559a9de) | Apr 26, 2024 |
| Acer          | Aspire A315-53G             | [2a3e224f63](https://linux-hardware.org/?probe=2a3e224f63) | Apr 26, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae5dddd784](https://linux-hardware.org/?probe=ae5dddd784) | Apr 25, 2024 |
| ASUSTek       | N751JK                      | [f49afec710](https://linux-hardware.org/?probe=f49afec710) | Apr 25, 2024 |
| Alienware     | M18xR1                      | [d6f3028e98](https://linux-hardware.org/?probe=d6f3028e98) | Apr 25, 2024 |
| HP            | ZBook 15                    | [b5181afe2b](https://linux-hardware.org/?probe=b5181afe2b) | Apr 25, 2024 |
| HP            | Laptop 15s-du1xxx           | [b1502b6440](https://linux-hardware.org/?probe=b1502b6440) | Apr 25, 2024 |
| HP            | Victus by Gaming Laptop ... | [8d2850aa6b](https://linux-hardware.org/?probe=8d2850aa6b) | Apr 24, 2024 |
| Lenovo        | G500s 20245                 | [9742cd9e94](https://linux-hardware.org/?probe=9742cd9e94) | Apr 24, 2024 |
| HP            | 15                          | [4ecce71b7d](https://linux-hardware.org/?probe=4ecce71b7d) | Apr 24, 2024 |
| Dell          | Precision M6700             | [cc8f317f9d](https://linux-hardware.org/?probe=cc8f317f9d) | Apr 24, 2024 |
| Toshiba       | STI NI 1401                 | [caed126d9e](https://linux-hardware.org/?probe=caed126d9e) | Apr 24, 2024 |
| Apple         | MacBookPro8,1               | [cf1ac0276a](https://linux-hardware.org/?probe=cf1ac0276a) | Apr 24, 2024 |
| Acer          | Aspire A315-24P             | [e25a1d0676](https://linux-hardware.org/?probe=e25a1d0676) | Apr 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2bc3bf2f34](https://linux-hardware.org/?probe=2bc3bf2f34) | Apr 23, 2024 |
| Acer          | Nitro AN515-46              | [0a90ca1966](https://linux-hardware.org/?probe=0a90ca1966) | Apr 23, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [6f01a069fa](https://linux-hardware.org/?probe=6f01a069fa) | Apr 23, 2024 |
| Apple         | MacBook5,1                  | [83ab8ba33c](https://linux-hardware.org/?probe=83ab8ba33c) | Apr 23, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [95453a6898](https://linux-hardware.org/?probe=95453a6898) | Apr 23, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [72b47f3d18](https://linux-hardware.org/?probe=72b47f3d18) | Apr 23, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [894feb1a4d](https://linux-hardware.org/?probe=894feb1a4d) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [a7180ee8da](https://linux-hardware.org/?probe=a7180ee8da) | Apr 23, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [e79a07e085](https://linux-hardware.org/?probe=e79a07e085) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cda9b90e74](https://linux-hardware.org/?probe=cda9b90e74) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [922e4ea114](https://linux-hardware.org/?probe=922e4ea114) | Apr 23, 2024 |
| Apple         | MacBookPro9,2               | [da3cb2d356](https://linux-hardware.org/?probe=da3cb2d356) | Apr 22, 2024 |
| Acer          | Aspire A315-56              | [92fb8268cc](https://linux-hardware.org/?probe=92fb8268cc) | Apr 22, 2024 |
| HP            | Victus by Gaming Laptop ... | [4ffd3e632b](https://linux-hardware.org/?probe=4ffd3e632b) | Apr 22, 2024 |
| Lenovo        | Legion R7000P APH8 82Y9     | [a3f2909959](https://linux-hardware.org/?probe=a3f2909959) | Apr 22, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a8d83edd62](https://linux-hardware.org/?probe=a8d83edd62) | Apr 22, 2024 |
| Acer          | Aspire A514-54              | [3685be6a35](https://linux-hardware.org/?probe=3685be6a35) | Apr 22, 2024 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [d7a06f7d8d](https://linux-hardware.org/?probe=d7a06f7d8d) | Apr 22, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [e36ba9916d](https://linux-hardware.org/?probe=e36ba9916d) | Apr 22, 2024 |
| Positivo      | S14SL01                     | [4840897917](https://linux-hardware.org/?probe=4840897917) | Apr 21, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [e0c405894c](https://linux-hardware.org/?probe=e0c405894c) | Apr 21, 2024 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [458a4bd2b2](https://linux-hardware.org/?probe=458a4bd2b2) | Apr 21, 2024 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [6e6ef1d063](https://linux-hardware.org/?probe=6e6ef1d063) | Apr 21, 2024 |
| HP            | ProBook 4530s               | [11f3df5775](https://linux-hardware.org/?probe=11f3df5775) | Apr 21, 2024 |
| Acer          | Aspire A514-54              | [b06b4f2ac7](https://linux-hardware.org/?probe=b06b4f2ac7) | Apr 21, 2024 |
| Dell          | Latitude 5440               | [58cc268fb3](https://linux-hardware.org/?probe=58cc268fb3) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [ceca4cef9c](https://linux-hardware.org/?probe=ceca4cef9c) | Apr 21, 2024 |
| HP            | Laptop 17-cp0xxx            | [9eff554fa4](https://linux-hardware.org/?probe=9eff554fa4) | Apr 21, 2024 |
| ASUSTek       | G75VW                       | [1853702bed](https://linux-hardware.org/?probe=1853702bed) | Apr 21, 2024 |
| Alienware     | x15 R1                      | [63bd9e4e5b](https://linux-hardware.org/?probe=63bd9e4e5b) | Apr 21, 2024 |
| Alienware     | x15 R1                      | [adfa8b3aea](https://linux-hardware.org/?probe=adfa8b3aea) | Apr 21, 2024 |
| HP            | ProBook 470 G5              | [0c1225132c](https://linux-hardware.org/?probe=0c1225132c) | Apr 21, 2024 |
| HP            | Laptop 17-cp0xxx            | [fea13a098d](https://linux-hardware.org/?probe=fea13a098d) | Apr 20, 2024 |
| Apple         | MacBookPro11,2              | [802dfe39ec](https://linux-hardware.org/?probe=802dfe39ec) | Apr 20, 2024 |
| Acer          | Aspire A315-44P             | [6636df5576](https://linux-hardware.org/?probe=6636df5576) | Apr 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [35685d6f90](https://linux-hardware.org/?probe=35685d6f90) | Apr 20, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [5b3e452e53](https://linux-hardware.org/?probe=5b3e452e53) | Apr 20, 2024 |
| Dell          | Inspiron 3501               | [0f62918ed2](https://linux-hardware.org/?probe=0f62918ed2) | Apr 20, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [e090d79256](https://linux-hardware.org/?probe=e090d79256) | Apr 20, 2024 |
| Valve         | Jupiter                     | [da44a88ec3](https://linux-hardware.org/?probe=da44a88ec3) | Apr 19, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RW    | [8d5622069d](https://linux-hardware.org/?probe=8d5622069d) | Apr 19, 2024 |
| Lenovo        | ThinkPad T450s 20BWS00V0... | [8d933e8d9e](https://linux-hardware.org/?probe=8d933e8d9e) | Apr 19, 2024 |
| Dell          | G15 5530                    | [c1f49dc2d9](https://linux-hardware.org/?probe=c1f49dc2d9) | Apr 19, 2024 |
| Fujitsu       | LIFEBOOK T902               | [1f6b5be9dc](https://linux-hardware.org/?probe=1f6b5be9dc) | Apr 19, 2024 |
| Dell          | Latitude E6400              | [d084b4b030](https://linux-hardware.org/?probe=d084b4b030) | Apr 19, 2024 |
| Google        | Shyvana                     | [a0d110b275](https://linux-hardware.org/?probe=a0d110b275) | Apr 19, 2024 |
| Acer          | Aspire A715-43G             | [737b4f2bfb](https://linux-hardware.org/?probe=737b4f2bfb) | Apr 19, 2024 |
| Acer          | Aspire A715-43G             | [b1605729ff](https://linux-hardware.org/?probe=b1605729ff) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [a2fb569143](https://linux-hardware.org/?probe=a2fb569143) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [b70a3e9c9f](https://linux-hardware.org/?probe=b70a3e9c9f) | Apr 19, 2024 |
| Lenovo        | G50-80 80E5                 | [5de5267a1a](https://linux-hardware.org/?probe=5de5267a1a) | Apr 19, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d173c3e7d7](https://linux-hardware.org/?probe=d173c3e7d7) | Apr 18, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [7e7a28ef89](https://linux-hardware.org/?probe=7e7a28ef89) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [43a3e3b36d](https://linux-hardware.org/?probe=43a3e3b36d) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8c079004f7](https://linux-hardware.org/?probe=8c079004f7) | Apr 18, 2024 |
| Dell          | Precision M4800             | [e1bbe5bf56](https://linux-hardware.org/?probe=e1bbe5bf56) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aaef73d221](https://linux-hardware.org/?probe=aaef73d221) | Apr 18, 2024 |
| Acer          | Aspire E5-571G              | [c0cb351a9c](https://linux-hardware.org/?probe=c0cb351a9c) | Apr 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [011644727b](https://linux-hardware.org/?probe=011644727b) | Apr 18, 2024 |
| HP            | EliteBook 2540p             | [9748a3188e](https://linux-hardware.org/?probe=9748a3188e) | Apr 18, 2024 |
| Acer          | V5-131                      | [5ca622b910](https://linux-hardware.org/?probe=5ca622b910) | Apr 18, 2024 |
| Acer          | V5-131                      | [984da3beb5](https://linux-hardware.org/?probe=984da3beb5) | Apr 18, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [59aceeb367](https://linux-hardware.org/?probe=59aceeb367) | Apr 18, 2024 |
| Dell          | Inspiron 15-7568            | [cf77d5e408](https://linux-hardware.org/?probe=cf77d5e408) | Apr 18, 2024 |
| Acer          | Aspire E5-571G              | [f225a565f5](https://linux-hardware.org/?probe=f225a565f5) | Apr 18, 2024 |
| Dell          | Latitude 5310               | [e46914e458](https://linux-hardware.org/?probe=e46914e458) | Apr 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0eb26f6fcc](https://linux-hardware.org/?probe=0eb26f6fcc) | Apr 17, 2024 |
| ASUSTek       | K53BE                       | [26673bc3d5](https://linux-hardware.org/?probe=26673bc3d5) | Apr 17, 2024 |
| Dell          | XPS 9320                    | [572e9a9030](https://linux-hardware.org/?probe=572e9a9030) | Apr 17, 2024 |
| Dell          | XPS 9320                    | [ba5e5d3733](https://linux-hardware.org/?probe=ba5e5d3733) | Apr 17, 2024 |
| HP            | Laptop 15-dy2xxx            | [0e9bf013da](https://linux-hardware.org/?probe=0e9bf013da) | Apr 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [32d8be9f50](https://linux-hardware.org/?probe=32d8be9f50) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [a776a9677a](https://linux-hardware.org/?probe=a776a9677a) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4f7d67acb4](https://linux-hardware.org/?probe=4f7d67acb4) | Apr 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [0ce853dae6](https://linux-hardware.org/?probe=0ce853dae6) | Apr 17, 2024 |
| Sony          | VPCEH25EN                   | [3bf6f9edaa](https://linux-hardware.org/?probe=3bf6f9edaa) | Apr 17, 2024 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [eea2672841](https://linux-hardware.org/?probe=eea2672841) | Apr 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7809a3250e](https://linux-hardware.org/?probe=7809a3250e) | Apr 16, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | [6877dcd901](https://linux-hardware.org/?probe=6877dcd901) | Apr 16, 2024 |
| Lenovo        | ThinkPad T450s 20BWS00V0... | [763289fa74](https://linux-hardware.org/?probe=763289fa74) | Apr 16, 2024 |
| HP            | EliteBook 840 G1            | [a810237e8f](https://linux-hardware.org/?probe=a810237e8f) | Apr 16, 2024 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [a0b18d9fe1](https://linux-hardware.org/?probe=a0b18d9fe1) | Apr 16, 2024 |
| Apple         | MacBookPro8,2               | [2e79d9d11e](https://linux-hardware.org/?probe=2e79d9d11e) | Apr 16, 2024 |
| ASUSTek       | UX305CA                     | [e25d8c8e00](https://linux-hardware.org/?probe=e25d8c8e00) | Apr 16, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [a596d334bf](https://linux-hardware.org/?probe=a596d334bf) | Apr 16, 2024 |
| ASUSTek       | X551MA                      | [9ef43fd0f2](https://linux-hardware.org/?probe=9ef43fd0f2) | Apr 16, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [862eca9c16](https://linux-hardware.org/?probe=862eca9c16) | Apr 16, 2024 |
| Dell          | XPS 15 9560                 | [5e92237577](https://linux-hardware.org/?probe=5e92237577) | Apr 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [54ea7f1e25](https://linux-hardware.org/?probe=54ea7f1e25) | Apr 16, 2024 |
| HUAWEI        | RLEF-XX                     | [461426c098](https://linux-hardware.org/?probe=461426c098) | Apr 16, 2024 |
| Apple         | MacBookAir7,2               | [163f3a262e](https://linux-hardware.org/?probe=163f3a262e) | Apr 15, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [7c4f1e45c9](https://linux-hardware.org/?probe=7c4f1e45c9) | Apr 15, 2024 |
| Lenovo        | ThinkPad E460 20EUS00000    | [aa85d58506](https://linux-hardware.org/?probe=aa85d58506) | Apr 15, 2024 |
| Acer          | Aspire A515-51              | [7ff3e868b5](https://linux-hardware.org/?probe=7ff3e868b5) | Apr 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5378d5a780](https://linux-hardware.org/?probe=5378d5a780) | Apr 15, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CMA... | [9820ac9335](https://linux-hardware.org/?probe=9820ac9335) | Apr 15, 2024 |
| LG Electro... | 17Z90R-G.AA77G              | [c3c12d00f2](https://linux-hardware.org/?probe=c3c12d00f2) | Apr 15, 2024 |
| HP            | ZBook 15                    | [f581a351ed](https://linux-hardware.org/?probe=f581a351ed) | Apr 15, 2024 |
| Apple         | MacBookPro9,2               | [60e642d93c](https://linux-hardware.org/?probe=60e642d93c) | Apr 15, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [c249f10628](https://linux-hardware.org/?probe=c249f10628) | Apr 15, 2024 |
| LG Electro... | 17Z90R-G.AA77G              | [9adb0d4728](https://linux-hardware.org/?probe=9adb0d4728) | Apr 15, 2024 |
| Dell          | Precision 5520              | [6a85a306b8](https://linux-hardware.org/?probe=6a85a306b8) | Apr 14, 2024 |
| HP            | 255 15.6 inch G10           | [b72fb5d156](https://linux-hardware.org/?probe=b72fb5d156) | Apr 14, 2024 |
| TUXEDO        | Gemini Gen2                 | [89fbde8b2d](https://linux-hardware.org/?probe=89fbde8b2d) | Apr 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [476daae154](https://linux-hardware.org/?probe=476daae154) | Apr 14, 2024 |
| Dell          | Latitude E6420              | [713c9b9514](https://linux-hardware.org/?probe=713c9b9514) | Apr 13, 2024 |
| Apple         | MacBookPro11,3              | [abbfebcf21](https://linux-hardware.org/?probe=abbfebcf21) | Apr 13, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [75ef2f2d7a](https://linux-hardware.org/?probe=75ef2f2d7a) | Apr 13, 2024 |
| HP            | ProBook 450 G0              | [686202a739](https://linux-hardware.org/?probe=686202a739) | Apr 13, 2024 |
| HUAWEI        | BOM-WXX9                    | [c5720fd484](https://linux-hardware.org/?probe=c5720fd484) | Apr 13, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [c4c0c27585](https://linux-hardware.org/?probe=c4c0c27585) | Apr 13, 2024 |
| Acer          | Aspire A315-41              | [df30810cbe](https://linux-hardware.org/?probe=df30810cbe) | Apr 13, 2024 |
| Apple         | MacBookPro14,1              | [02b8d8e933](https://linux-hardware.org/?probe=02b8d8e933) | Apr 12, 2024 |
| HP            | Laptop 15-dy2xxx            | [b93bba8226](https://linux-hardware.org/?probe=b93bba8226) | Apr 12, 2024 |
| HP            | ProBook 6570b               | [d17831e754](https://linux-hardware.org/?probe=d17831e754) | Apr 12, 2024 |
| Acer          | Nitro AN515-44              | [8b8b4193c8](https://linux-hardware.org/?probe=8b8b4193c8) | Apr 12, 2024 |
| ASUSTek       | K52Je                       | [7cfd3a8614](https://linux-hardware.org/?probe=7cfd3a8614) | Apr 12, 2024 |
| HP            | ProBook 450 G0              | [becdc6cf99](https://linux-hardware.org/?probe=becdc6cf99) | Apr 12, 2024 |
| Dell          | G15 5510                    | [9820798256](https://linux-hardware.org/?probe=9820798256) | Apr 12, 2024 |
| HP            | Split 13 x2 Detachable P... | [17c8956856](https://linux-hardware.org/?probe=17c8956856) | Apr 12, 2024 |
| Dell          | XPS 9315                    | [a034dc4942](https://linux-hardware.org/?probe=a034dc4942) | Apr 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | [77db3dff9e](https://linux-hardware.org/?probe=77db3dff9e) | Apr 12, 2024 |
| Dell          | Inspiron 15-7568            | [939c6125de](https://linux-hardware.org/?probe=939c6125de) | Apr 12, 2024 |
| ASUSTek       | K52Je                       | [e825e3871d](https://linux-hardware.org/?probe=e825e3871d) | Apr 12, 2024 |
| HP            | ZBook 15 G3                 | [5f48d3ede1](https://linux-hardware.org/?probe=5f48d3ede1) | Apr 12, 2024 |
| Juana Mans... | SF20GM7                     | [2a01eeac36](https://linux-hardware.org/?probe=2a01eeac36) | Apr 12, 2024 |
| Lenovo        | ThinkPad T580 20L9001EUS    | [95d21ed0f1](https://linux-hardware.org/?probe=95d21ed0f1) | Apr 12, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | [fd2fc14275](https://linux-hardware.org/?probe=fd2fc14275) | Apr 12, 2024 |
| Acer          | Nitro ANV15-51              | [b78fb4e0df](https://linux-hardware.org/?probe=b78fb4e0df) | Apr 12, 2024 |
| Dell          | Precision 5750              | [f59c1fa6c6](https://linux-hardware.org/?probe=f59c1fa6c6) | Apr 12, 2024 |
| Lenovo        | ThinkPad T580 20L9001EUS    | [9f0cfb04b0](https://linux-hardware.org/?probe=9f0cfb04b0) | Apr 12, 2024 |
| Toshiba       | Satellite C70-B             | [305c87ae5d](https://linux-hardware.org/?probe=305c87ae5d) | Apr 12, 2024 |
| Timi          | TM1701                      | [0af4854c82](https://linux-hardware.org/?probe=0af4854c82) | Apr 12, 2024 |
| Apple         | MacBookPro14,1              | [f6720efacd](https://linux-hardware.org/?probe=f6720efacd) | Apr 11, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f7ab9249b4](https://linux-hardware.org/?probe=f7ab9249b4) | Apr 11, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [988ea47737](https://linux-hardware.org/?probe=988ea47737) | Apr 11, 2024 |
| Acer          | Swift SF314-43              | [a02fa9c7cf](https://linux-hardware.org/?probe=a02fa9c7cf) | Apr 11, 2024 |
| Dell          | Inspiron 5566               | [bd5c43f6c8](https://linux-hardware.org/?probe=bd5c43f6c8) | Apr 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S29D0W    | [7d55e2a84d](https://linux-hardware.org/?probe=7d55e2a84d) | Apr 11, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | [52de364ea7](https://linux-hardware.org/?probe=52de364ea7) | Apr 11, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [1d9ef42930](https://linux-hardware.org/?probe=1d9ef42930) | Apr 11, 2024 |
| Dell          | Studio 1558                 | [195acc75cf](https://linux-hardware.org/?probe=195acc75cf) | Apr 10, 2024 |
| Dell          | Studio 1558                 | [92678a06a0](https://linux-hardware.org/?probe=92678a06a0) | Apr 10, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [38d04908c1](https://linux-hardware.org/?probe=38d04908c1) | Apr 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S5QH00    | [5068f44f3b](https://linux-hardware.org/?probe=5068f44f3b) | Apr 10, 2024 |
| Dell          | Precision 3571              | [6bef26b856](https://linux-hardware.org/?probe=6bef26b856) | Apr 10, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9a15677135](https://linux-hardware.org/?probe=9a15677135) | Apr 10, 2024 |
| Dell          | Precision M6800             | [fbdc7e53c6](https://linux-hardware.org/?probe=fbdc7e53c6) | Apr 10, 2024 |
| Alienware     | m15 R7 AMD                  | [effd96032c](https://linux-hardware.org/?probe=effd96032c) | Apr 10, 2024 |
| Lenovo        | ThinkPad P50 20EN0013US     | [afbcbc9b57](https://linux-hardware.org/?probe=afbcbc9b57) | Apr 10, 2024 |
| MSI           | Raider GE66 12UGS           | [e45ec711e7](https://linux-hardware.org/?probe=e45ec711e7) | Apr 10, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [184f279e1e](https://linux-hardware.org/?probe=184f279e1e) | Apr 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0a7b693def](https://linux-hardware.org/?probe=0a7b693def) | Apr 10, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [f892422654](https://linux-hardware.org/?probe=f892422654) | Apr 10, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [4d6466d304](https://linux-hardware.org/?probe=4d6466d304) | Apr 10, 2024 |
| HP            | 250 G8 Notebook PC          | [73ef8a88c7](https://linux-hardware.org/?probe=73ef8a88c7) | Apr 10, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [5b99de1b59](https://linux-hardware.org/?probe=5b99de1b59) | Apr 10, 2024 |
| HP            | Laptop 15-dy5xxx            | [716e9907f4](https://linux-hardware.org/?probe=716e9907f4) | Apr 10, 2024 |
| HP            | Laptop 15-dy5xxx            | [41bec233fb](https://linux-hardware.org/?probe=41bec233fb) | Apr 10, 2024 |
| HP            | ProBook 440 G2              | [1761f221f8](https://linux-hardware.org/?probe=1761f221f8) | Apr 09, 2024 |
| HP            | ProBook 440 G2              | [84b8f6128b](https://linux-hardware.org/?probe=84b8f6128b) | Apr 09, 2024 |
| Acer          | Aspire E5-771G              | [752982118a](https://linux-hardware.org/?probe=752982118a) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1c025781a3](https://linux-hardware.org/?probe=1c025781a3) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d21570a024](https://linux-hardware.org/?probe=d21570a024) | Apr 09, 2024 |
| Dell          | Latitude 7420               | [8dc657f9e2](https://linux-hardware.org/?probe=8dc657f9e2) | Apr 09, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [717e8590bb](https://linux-hardware.org/?probe=717e8590bb) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3ed13a3d8a](https://linux-hardware.org/?probe=3ed13a3d8a) | Apr 09, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | [c08adc1120](https://linux-hardware.org/?probe=c08adc1120) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [32842b7d56](https://linux-hardware.org/?probe=32842b7d56) | Apr 09, 2024 |
| Toshiba       | Satellite L750              | [296a0d80a0](https://linux-hardware.org/?probe=296a0d80a0) | Apr 09, 2024 |
| Alienware     | m18 R1 AMD                  | [8031bfa7f7](https://linux-hardware.org/?probe=8031bfa7f7) | Apr 08, 2024 |
| Acer          | Aspire 5750ZG               | [b80881ad3d](https://linux-hardware.org/?probe=b80881ad3d) | Apr 08, 2024 |
| Infinix       | ZERO BOOK 13                | [f27647e9bb](https://linux-hardware.org/?probe=f27647e9bb) | Apr 08, 2024 |
| Dell          | Precision M4800             | [3ec884f458](https://linux-hardware.org/?probe=3ec884f458) | Apr 08, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [9d9dacedb7](https://linux-hardware.org/?probe=9d9dacedb7) | Apr 08, 2024 |
| Timi          | Mi NoteBook Pro             | [ab28993dd3](https://linux-hardware.org/?probe=ab28993dd3) | Apr 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [97879c1052](https://linux-hardware.org/?probe=97879c1052) | Apr 08, 2024 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [e9cd6d780b](https://linux-hardware.org/?probe=e9cd6d780b) | Apr 08, 2024 |
| ASUSTek       | X553MA                      | [3e60ae1de4](https://linux-hardware.org/?probe=3e60ae1de4) | Apr 08, 2024 |
| Dell          | Latitude 3410               | [0922287873](https://linux-hardware.org/?probe=0922287873) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3c71179d12](https://linux-hardware.org/?probe=3c71179d12) | Apr 08, 2024 |
| Apple         | MacBookPro10,1              | [62d0c49e82](https://linux-hardware.org/?probe=62d0c49e82) | Apr 08, 2024 |
| Apple         | MacBookPro10,1              | [96e5d2941a](https://linux-hardware.org/?probe=96e5d2941a) | Apr 08, 2024 |
| HP            | 2000                        | [1dd10f95ab](https://linux-hardware.org/?probe=1dd10f95ab) | Apr 08, 2024 |
| HP            | 2000                        | [023731233e](https://linux-hardware.org/?probe=023731233e) | Apr 08, 2024 |
| Toshiba       | dynabook T554/45LB          | [da72e21681](https://linux-hardware.org/?probe=da72e21681) | Apr 07, 2024 |
| Dell          | Precision 3571              | [fdab7d40f5](https://linux-hardware.org/?probe=fdab7d40f5) | Apr 07, 2024 |
| HP            | EliteBook 745 G3            | [ac1e80470e](https://linux-hardware.org/?probe=ac1e80470e) | Apr 07, 2024 |
| Acer          | Aspire A715-51G             | [0d3fb54918](https://linux-hardware.org/?probe=0d3fb54918) | Apr 07, 2024 |
| HP            | EliteBook 840 G5            | [daefa26759](https://linux-hardware.org/?probe=daefa26759) | Apr 07, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [87286d8d57](https://linux-hardware.org/?probe=87286d8d57) | Apr 07, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9d2377e611](https://linux-hardware.org/?probe=9d2377e611) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [5d346ffec7](https://linux-hardware.org/?probe=5d346ffec7) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3f40831832](https://linux-hardware.org/?probe=3f40831832) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [46543ad5d6](https://linux-hardware.org/?probe=46543ad5d6) | Apr 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [b5368ebb47](https://linux-hardware.org/?probe=b5368ebb47) | Apr 07, 2024 |
| Notebook      | NS5x_NS7xAU                 | [782d5db9e2](https://linux-hardware.org/?probe=782d5db9e2) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [5d0259d7a1](https://linux-hardware.org/?probe=5d0259d7a1) | Apr 06, 2024 |
| Timi          | Mi NoteBook Pro             | [96fefe11d7](https://linux-hardware.org/?probe=96fefe11d7) | Apr 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [278e4869ad](https://linux-hardware.org/?probe=278e4869ad) | Apr 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [65816fc70b](https://linux-hardware.org/?probe=65816fc70b) | Apr 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [595c1e3d71](https://linux-hardware.org/?probe=595c1e3d71) | Apr 06, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ed719f8ced](https://linux-hardware.org/?probe=ed719f8ced) | Apr 06, 2024 |
| SCHNEIDER     | SCL141CTP                   | [33e14fe576](https://linux-hardware.org/?probe=33e14fe576) | Apr 06, 2024 |
| HUAWEI        | KLVF-XX                     | [775f139f3b](https://linux-hardware.org/?probe=775f139f3b) | Apr 06, 2024 |
| Acer          | Aspire E5-573G              | [da60008a10](https://linux-hardware.org/?probe=da60008a10) | Apr 06, 2024 |
| Lenovo        | ThinkPad T480s 20L7001NG... | [ec916e14d1](https://linux-hardware.org/?probe=ec916e14d1) | Apr 06, 2024 |
| HUAWEI        | KLVF-XX                     | [6d24eb8f58](https://linux-hardware.org/?probe=6d24eb8f58) | Apr 06, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [6fd20472e0](https://linux-hardware.org/?probe=6fd20472e0) | Apr 06, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [abf1d82267](https://linux-hardware.org/?probe=abf1d82267) | Apr 06, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [e4ace3a2df](https://linux-hardware.org/?probe=e4ace3a2df) | Apr 06, 2024 |
| Google        | Voxel                       | [7c1c455196](https://linux-hardware.org/?probe=7c1c455196) | Apr 06, 2024 |
| HP            | 250 G8 Notebook PC          | [62cd5c6263](https://linux-hardware.org/?probe=62cd5c6263) | Apr 06, 2024 |
| Lenovo        | ThinkPad P52 20MAS1DM00     | [c83b503bb6](https://linux-hardware.org/?probe=c83b503bb6) | Apr 06, 2024 |
| Google        | Bluebird                    | [a41a0e7278](https://linux-hardware.org/?probe=a41a0e7278) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [47c56bd4ee](https://linux-hardware.org/?probe=47c56bd4ee) | Apr 05, 2024 |
| HUAWEI        | MRGF-XX                     | [aeccfe5e22](https://linux-hardware.org/?probe=aeccfe5e22) | Apr 05, 2024 |
| Framework     | Laptop                      | [3349129590](https://linux-hardware.org/?probe=3349129590) | Apr 05, 2024 |
| Haier         | Y11C                        | [412c266aec](https://linux-hardware.org/?probe=412c266aec) | Apr 05, 2024 |
| Lenovo        | ThinkPad E580 20KS003LCA    | [a6320acff1](https://linux-hardware.org/?probe=a6320acff1) | Apr 05, 2024 |
| HUAWEI        | RLEF-XX                     | [912bbd56b1](https://linux-hardware.org/?probe=912bbd56b1) | Apr 05, 2024 |
| Dell          | Inspiron 5459               | [fb9702f65e](https://linux-hardware.org/?probe=fb9702f65e) | Apr 05, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FF... | [9cceb657f4](https://linux-hardware.org/?probe=9cceb657f4) | Apr 05, 2024 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [2edfed7d6c](https://linux-hardware.org/?probe=2edfed7d6c) | Apr 04, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [77e3ddbb44](https://linux-hardware.org/?probe=77e3ddbb44) | Apr 04, 2024 |
| HP            | EliteBook 820 G3            | [5179c6e5f3](https://linux-hardware.org/?probe=5179c6e5f3) | Apr 04, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [a9490d11d7](https://linux-hardware.org/?probe=a9490d11d7) | Apr 04, 2024 |
| Chuwi         | UBook XPro                  | [f7f05e8aa2](https://linux-hardware.org/?probe=f7f05e8aa2) | Apr 04, 2024 |
| Apple         | MacBookPro9,1               | [b8436b6a3c](https://linux-hardware.org/?probe=b8436b6a3c) | Apr 04, 2024 |
| Acer          | Aspire V5-572G              | [ca5e1f767e](https://linux-hardware.org/?probe=ca5e1f767e) | Apr 04, 2024 |
| Dell          | Inspiron 5566               | [a22633719c](https://linux-hardware.org/?probe=a22633719c) | Apr 04, 2024 |
| MSI           | GX780R/GT780R/GT780DXR      | [c4e752d06c](https://linux-hardware.org/?probe=c4e752d06c) | Apr 04, 2024 |
| MSI           | GX780R/GT780R/GT780DXR      | [100d6d2fcd](https://linux-hardware.org/?probe=100d6d2fcd) | Apr 04, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [6ea19c4f02](https://linux-hardware.org/?probe=6ea19c4f02) | Apr 04, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [ba3e37736d](https://linux-hardware.org/?probe=ba3e37736d) | Apr 04, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582HS_... | [ab6e09c508](https://linux-hardware.org/?probe=ab6e09c508) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [323bf9fa10](https://linux-hardware.org/?probe=323bf9fa10) | Apr 04, 2024 |
| HP            | Laptop 15-bs1xx             | [d52b8f5295](https://linux-hardware.org/?probe=d52b8f5295) | Apr 04, 2024 |
| HP            | 8590                        | [2d3f6d27a2](https://linux-hardware.org/?probe=2d3f6d27a2) | Apr 04, 2024 |
| HP            | EliteBook 840 G6            | [c7e57e0c0b](https://linux-hardware.org/?probe=c7e57e0c0b) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [c41823fc76](https://linux-hardware.org/?probe=c41823fc76) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [09a8421999](https://linux-hardware.org/?probe=09a8421999) | Apr 04, 2024 |
| Apple         | MacBookAir7,2               | [c5ce1039fa](https://linux-hardware.org/?probe=c5ce1039fa) | Apr 04, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [bf0d1ddab3](https://linux-hardware.org/?probe=bf0d1ddab3) | Apr 04, 2024 |
| Apple         | MacBookAir7,2               | [86c8aec82f](https://linux-hardware.org/?probe=86c8aec82f) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU605MI... | [4581288732](https://linux-hardware.org/?probe=4581288732) | Apr 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [c38ed1feec](https://linux-hardware.org/?probe=c38ed1feec) | Apr 03, 2024 |
| HP            | Pro Tablet 10 EE G1         | [364cf44bfa](https://linux-hardware.org/?probe=364cf44bfa) | Apr 03, 2024 |
| HP            | Pro Tablet 10 EE G1         | [a76cafaf48](https://linux-hardware.org/?probe=a76cafaf48) | Apr 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2768c4333f](https://linux-hardware.org/?probe=2768c4333f) | Apr 03, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21BN0... | [91168e1623](https://linux-hardware.org/?probe=91168e1623) | Apr 03, 2024 |
| Apple         | MacBookAir5,2               | [3c05445a49](https://linux-hardware.org/?probe=3c05445a49) | Apr 03, 2024 |
| ASUSTek       | Zenbook UX8402VU_UX8402V... | [2cea574673](https://linux-hardware.org/?probe=2cea574673) | Apr 03, 2024 |
| Dell          | Latitude E6400              | [bb95390cc4](https://linux-hardware.org/?probe=bb95390cc4) | Apr 03, 2024 |
| Dell          | Latitude E6400              | [39d6e5102c](https://linux-hardware.org/?probe=39d6e5102c) | Apr 03, 2024 |
| Dell          | Inspiron 15 3525            | [76e8934737](https://linux-hardware.org/?probe=76e8934737) | Apr 03, 2024 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [dd2a60e142](https://linux-hardware.org/?probe=dd2a60e142) | Apr 03, 2024 |
| Lenovo        | ThinkPad L530 24793J2       | [1e4c7768c1](https://linux-hardware.org/?probe=1e4c7768c1) | Apr 02, 2024 |
| Acer          | Aspire A315-56              | [c44e1a4b30](https://linux-hardware.org/?probe=c44e1a4b30) | Apr 02, 2024 |
| Lenovo        | ThinkPad L530 24793J2       | [9f6aec0751](https://linux-hardware.org/?probe=9f6aec0751) | Apr 02, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [78a7a3ff32](https://linux-hardware.org/?probe=78a7a3ff32) | Apr 02, 2024 |
| Dell          | Latitude 3540               | [452a3babe4](https://linux-hardware.org/?probe=452a3babe4) | Apr 02, 2024 |
| Avell High... | B.ON                        | [27a4a2ab6d](https://linux-hardware.org/?probe=27a4a2ab6d) | Apr 02, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0004... | [2dd77820c8](https://linux-hardware.org/?probe=2dd77820c8) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [7f542aae1b](https://linux-hardware.org/?probe=7f542aae1b) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [0474c0e2a0](https://linux-hardware.org/?probe=0474c0e2a0) | Apr 02, 2024 |
| Lenovo        | Mullins-LarneML             | [07f3f21f7f](https://linux-hardware.org/?probe=07f3f21f7f) | Apr 02, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [3a49180fbf](https://linux-hardware.org/?probe=3a49180fbf) | Apr 02, 2024 |
| Apple         | MacBookPro9,2               | [4bc1c20e34](https://linux-hardware.org/?probe=4bc1c20e34) | Apr 02, 2024 |
| Avell High... | A62 LIV                     | [a7d1ceac6e](https://linux-hardware.org/?probe=a7d1ceac6e) | Apr 02, 2024 |
| Lenovo        | ThinkPad X240 20AMS1PT06    | [fb2384d93e](https://linux-hardware.org/?probe=fb2384d93e) | Apr 02, 2024 |
| Dell          | Precision 5560              | [2a88b33a32](https://linux-hardware.org/?probe=2a88b33a32) | Apr 02, 2024 |
| Dell          | Precision 5560              | [e9dfd89a49](https://linux-hardware.org/?probe=e9dfd89a49) | Apr 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d21f6d3fe4](https://linux-hardware.org/?probe=d21f6d3fe4) | Apr 01, 2024 |
| Dell          | Inspiron 5770               | [3a6a7880c9](https://linux-hardware.org/?probe=3a6a7880c9) | Apr 01, 2024 |
| HP            | ENVY Laptop 13-ba1xxx       | [4b4bfa93ee](https://linux-hardware.org/?probe=4b4bfa93ee) | Apr 01, 2024 |
| Dell          | Latitude 3540               | [11fa6df76e](https://linux-hardware.org/?probe=11fa6df76e) | Apr 01, 2024 |
| HP            | EliteBook 850 G6            | [eb4d7e2521](https://linux-hardware.org/?probe=eb4d7e2521) | Apr 01, 2024 |
| Lenovo        | G460 20041                  | [1e27980b1d](https://linux-hardware.org/?probe=1e27980b1d) | Apr 01, 2024 |
| Dell          | Latitude 7430               | [d8fb269186](https://linux-hardware.org/?probe=d8fb269186) | Apr 01, 2024 |
| Apple         | MacBook10,1                 | [2da6005f10](https://linux-hardware.org/?probe=2da6005f10) | Apr 01, 2024 |
| Apple         | MacBook10,1                 | [36d6f74236](https://linux-hardware.org/?probe=36d6f74236) | Apr 01, 2024 |
| HP            | ProBook 4720s               | [978eb70871](https://linux-hardware.org/?probe=978eb70871) | Apr 01, 2024 |
| Timi          | Mi NoteBook Pro             | [79e676b7a6](https://linux-hardware.org/?probe=79e676b7a6) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [900e722a10](https://linux-hardware.org/?probe=900e722a10) | Apr 01, 2024 |
| Apple         | MacBookAir2,1               | [a80e8486df](https://linux-hardware.org/?probe=a80e8486df) | Apr 01, 2024 |
| Apple         | MacBookAir2,1               | [72fee9e6ec](https://linux-hardware.org/?probe=72fee9e6ec) | Apr 01, 2024 |
| Acer          | Aspire ES1-111              | [5135f2fbd2](https://linux-hardware.org/?probe=5135f2fbd2) | Apr 01, 2024 |
| Timi          | Mi Laptop Pro 15            | [fc9cd1b4e0](https://linux-hardware.org/?probe=fc9cd1b4e0) | Apr 01, 2024 |
| Apple         | MacBookPro11,2              | [7ccfbb7054](https://linux-hardware.org/?probe=7ccfbb7054) | Mar 31, 2024 |
| HMT           | W042-67A                    | [957c1d9647](https://linux-hardware.org/?probe=957c1d9647) | Mar 31, 2024 |
| HMT           | W042-67A                    | [1d219ca2d5](https://linux-hardware.org/?probe=1d219ca2d5) | Mar 31, 2024 |
| ASUSTek       | GL552VW                     | [4c759cffbe](https://linux-hardware.org/?probe=4c759cffbe) | Mar 31, 2024 |
| HP            | ProBook 450 G5              | [eaa846245d](https://linux-hardware.org/?probe=eaa846245d) | Mar 31, 2024 |
| Apple         | MacBookPro13,3              | [df99c64127](https://linux-hardware.org/?probe=df99c64127) | Mar 31, 2024 |
| Lenovo        | Yoga Slim 6 14IRH8 83E0     | [31ba9b687a](https://linux-hardware.org/?probe=31ba9b687a) | Mar 31, 2024 |
| Chuwi         | GemiBook Pro                | [bfb77127c6](https://linux-hardware.org/?probe=bfb77127c6) | Mar 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [17f9e8a736](https://linux-hardware.org/?probe=17f9e8a736) | Mar 31, 2024 |
| Dell          | Latitude E6440              | [a13e07b860](https://linux-hardware.org/?probe=a13e07b860) | Mar 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [f6171acc29](https://linux-hardware.org/?probe=f6171acc29) | Mar 31, 2024 |
| Dell          | XPS 15 9560                 | [e49bbb6862](https://linux-hardware.org/?probe=e49bbb6862) | Mar 30, 2024 |
| ASUSTek       | X542UR                      | [4710a67397](https://linux-hardware.org/?probe=4710a67397) | Mar 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8a68f21257](https://linux-hardware.org/?probe=8a68f21257) | Mar 30, 2024 |
| Fujitsu       | LIFEBOOK T902               | [791d0e46d7](https://linux-hardware.org/?probe=791d0e46d7) | Mar 30, 2024 |
| Lenovo        | ThinkPad E580 20KS006FMZ    | [94d109d91e](https://linux-hardware.org/?probe=94d109d91e) | Mar 30, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [818d4cdfe2](https://linux-hardware.org/?probe=818d4cdfe2) | Mar 30, 2024 |
| HP            | Laptop 15-dw1xxx            | [e28e296839](https://linux-hardware.org/?probe=e28e296839) | Mar 30, 2024 |
| HP            | EliteBook 865 16 inch G1... | [cda1c99c4d](https://linux-hardware.org/?probe=cda1c99c4d) | Mar 30, 2024 |
| HP            | ProBook 450 G2              | [1753d19bc6](https://linux-hardware.org/?probe=1753d19bc6) | Mar 30, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3aeea5fae7](https://linux-hardware.org/?probe=3aeea5fae7) | Mar 30, 2024 |
| HP            | Laptop 15-bs0xx             | [922723cbd4](https://linux-hardware.org/?probe=922723cbd4) | Mar 30, 2024 |
| HP            | Laptop 15-bs0xx             | [3932e020fb](https://linux-hardware.org/?probe=3932e020fb) | Mar 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [e49cbff800](https://linux-hardware.org/?probe=e49cbff800) | Mar 30, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [b56fd43be2](https://linux-hardware.org/?probe=b56fd43be2) | Mar 30, 2024 |
| Alienware     | 15 R2                       | [2b6cb8a942](https://linux-hardware.org/?probe=2b6cb8a942) | Mar 29, 2024 |
| Acer          | Aspire A715-43G             | [d75576fddc](https://linux-hardware.org/?probe=d75576fddc) | Mar 29, 2024 |
| Alienware     | 15 R2                       | [de21034f41](https://linux-hardware.org/?probe=de21034f41) | Mar 29, 2024 |
| Acer          | Aspire A715-43G             | [dd44e47f72](https://linux-hardware.org/?probe=dd44e47f72) | Mar 29, 2024 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [3a7607450d](https://linux-hardware.org/?probe=3a7607450d) | Mar 29, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9d668bab07](https://linux-hardware.org/?probe=9d668bab07) | Mar 29, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [3ccfef4564](https://linux-hardware.org/?probe=3ccfef4564) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [21ef6a026f](https://linux-hardware.org/?probe=21ef6a026f) | Mar 29, 2024 |
| HP            | EliteBook 850 G1            | [3448f4cb60](https://linux-hardware.org/?probe=3448f4cb60) | Mar 29, 2024 |
| Dell          | Inspiron 5570               | [57667ea730](https://linux-hardware.org/?probe=57667ea730) | Mar 29, 2024 |
| Lenovo        | ThinkPad T490s 20NYS41L0... | [2fcbfc4400](https://linux-hardware.org/?probe=2fcbfc4400) | Mar 29, 2024 |
| Gigabyte      | AORUS 5 KE                  | [aee8f4658d](https://linux-hardware.org/?probe=aee8f4658d) | Mar 28, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [612a0c054e](https://linux-hardware.org/?probe=612a0c054e) | Mar 28, 2024 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [39e3f850a3](https://linux-hardware.org/?probe=39e3f850a3) | Mar 28, 2024 |
| Dell          | Inspiron 1545               | [9f48c2854c](https://linux-hardware.org/?probe=9f48c2854c) | Mar 28, 2024 |
| Dell          | Precision 7710              | [02cc10dc57](https://linux-hardware.org/?probe=02cc10dc57) | Mar 28, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [3eb36392bc](https://linux-hardware.org/?probe=3eb36392bc) | Mar 28, 2024 |
| Notebook      | PCx0Dx                      | [b1ca622c4a](https://linux-hardware.org/?probe=b1ca622c4a) | Mar 28, 2024 |
| HP            | Laptop 15-fd0xxx            | [2fc457195f](https://linux-hardware.org/?probe=2fc457195f) | Mar 28, 2024 |
| Insyde        | i101c                       | [fd15a3a81f](https://linux-hardware.org/?probe=fd15a3a81f) | Mar 28, 2024 |
| Fujitsu       | LIFEBOOK T902               | [bf4d3d25ce](https://linux-hardware.org/?probe=bf4d3d25ce) | Mar 27, 2024 |
| HP            | EliteBook 865 16 inch G1... | [b0de881978](https://linux-hardware.org/?probe=b0de881978) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | [25985cf7e8](https://linux-hardware.org/?probe=25985cf7e8) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | [433914ac7c](https://linux-hardware.org/?probe=433914ac7c) | Mar 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e11313b626](https://linux-hardware.org/?probe=e11313b626) | Mar 27, 2024 |
| Lenovo        | Mullins-LarneML             | [5f1162baa1](https://linux-hardware.org/?probe=5f1162baa1) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [e23a935b8e](https://linux-hardware.org/?probe=e23a935b8e) | Mar 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S4G713    | [00b299696d](https://linux-hardware.org/?probe=00b299696d) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [650cc5973f](https://linux-hardware.org/?probe=650cc5973f) | Mar 27, 2024 |
| Apple         | MacBookPro14,2              | [8af3aa3110](https://linux-hardware.org/?probe=8af3aa3110) | Mar 27, 2024 |
| Lenovo        | ThinkPad T490s 20NYS42N0... | [5c7d81f9a4](https://linux-hardware.org/?probe=5c7d81f9a4) | Mar 27, 2024 |
| Timi          | TM1701                      | [63336e0c6c](https://linux-hardware.org/?probe=63336e0c6c) | Mar 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [e4c56c90e5](https://linux-hardware.org/?probe=e4c56c90e5) | Mar 26, 2024 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [a089051410](https://linux-hardware.org/?probe=a089051410) | Mar 26, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [66a18f2732](https://linux-hardware.org/?probe=66a18f2732) | Mar 26, 2024 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [1f9d8fad3e](https://linux-hardware.org/?probe=1f9d8fad3e) | Mar 26, 2024 |
| HP            | Laptop 15s-dr0xxx           | [a41db03c5b](https://linux-hardware.org/?probe=a41db03c5b) | Mar 26, 2024 |
| Lenovo        | G500 20236                  | [8709768753](https://linux-hardware.org/?probe=8709768753) | Mar 26, 2024 |
| Star Labs     | StarBook                    | [91ff4c71fc](https://linux-hardware.org/?probe=91ff4c71fc) | Mar 26, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [529873e41c](https://linux-hardware.org/?probe=529873e41c) | Mar 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [2f1729ec9e](https://linux-hardware.org/?probe=2f1729ec9e) | Mar 26, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [bddc045346](https://linux-hardware.org/?probe=bddc045346) | Mar 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [ec5f9e5af3](https://linux-hardware.org/?probe=ec5f9e5af3) | Mar 26, 2024 |
| HP            | EliteBook 860 16 inch G9... | [687163bf58](https://linux-hardware.org/?probe=687163bf58) | Mar 26, 2024 |
| Apple         | MacBookPro16,1              | [82901b0cb6](https://linux-hardware.org/?probe=82901b0cb6) | Mar 26, 2024 |
| Dell          | Inspiron 1545               | [8a3260b7d8](https://linux-hardware.org/?probe=8a3260b7d8) | Mar 26, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | [68220addb3](https://linux-hardware.org/?probe=68220addb3) | Mar 26, 2024 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | [4e53b595db](https://linux-hardware.org/?probe=4e53b595db) | Mar 26, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [97fd197cc6](https://linux-hardware.org/?probe=97fd197cc6) | Mar 26, 2024 |
| MSI           | GS65 Stealth Thin 8RE       | [4b3fce45c9](https://linux-hardware.org/?probe=4b3fce45c9) | Mar 26, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d15637af96](https://linux-hardware.org/?probe=d15637af96) | Mar 25, 2024 |
| Apple         | MacBook4,1                  | [2a77e891e5](https://linux-hardware.org/?probe=2a77e891e5) | Mar 25, 2024 |
| HP            | EliteBook 2540p             | [99983f8fbf](https://linux-hardware.org/?probe=99983f8fbf) | Mar 25, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [b81f5867ef](https://linux-hardware.org/?probe=b81f5867ef) | Mar 25, 2024 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [0bbd95d6e5](https://linux-hardware.org/?probe=0bbd95d6e5) | Mar 25, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d09473d0ee](https://linux-hardware.org/?probe=d09473d0ee) | Mar 25, 2024 |
| HP            | ProBook 450 G5              | [e256bda48f](https://linux-hardware.org/?probe=e256bda48f) | Mar 25, 2024 |
| System76      | Lemur                       | [a5fb83b20e](https://linux-hardware.org/?probe=a5fb83b20e) | Mar 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e5e4d98f62](https://linux-hardware.org/?probe=e5e4d98f62) | Mar 25, 2024 |
| Dell          | Vostro 5490                 | [8f0042ce48](https://linux-hardware.org/?probe=8f0042ce48) | Mar 25, 2024 |
| Acer          | Nitro AN515-57              | [c455ccf61a](https://linux-hardware.org/?probe=c455ccf61a) | Mar 25, 2024 |
| Juana Mans... | SF20GM7                     | [96b7025093](https://linux-hardware.org/?probe=96b7025093) | Mar 25, 2024 |
| Dell          | G15 5525                    | [504ff7b25b](https://linux-hardware.org/?probe=504ff7b25b) | Mar 25, 2024 |
| Apple         | MacBookPro9,1               | [b0266d88c6](https://linux-hardware.org/?probe=b0266d88c6) | Mar 25, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5e09efbd44](https://linux-hardware.org/?probe=5e09efbd44) | Mar 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e2f8f7ac57](https://linux-hardware.org/?probe=e2f8f7ac57) | Mar 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [4788b61821](https://linux-hardware.org/?probe=4788b61821) | Mar 24, 2024 |
| HP            | ProBook 645 G1              | [62db4c657a](https://linux-hardware.org/?probe=62db4c657a) | Mar 24, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4f98b7fda2](https://linux-hardware.org/?probe=4f98b7fda2) | Mar 24, 2024 |
| Lenovo        | 330S-15ARR 81FB             | [664ff42149](https://linux-hardware.org/?probe=664ff42149) | Mar 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [843460ad8c](https://linux-hardware.org/?probe=843460ad8c) | Mar 24, 2024 |
| Jumper        | EZbook                      | [0aab28b972](https://linux-hardware.org/?probe=0aab28b972) | Mar 24, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [2cf44c6715](https://linux-hardware.org/?probe=2cf44c6715) | Mar 24, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [1120862001](https://linux-hardware.org/?probe=1120862001) | Mar 24, 2024 |
| Lenovo        | G50-45 80E3                 | [f3d66b5b1b](https://linux-hardware.org/?probe=f3d66b5b1b) | Mar 24, 2024 |
| Lenovo        | Yoga S740-15IRH 81NX        | [d6b26c4897](https://linux-hardware.org/?probe=d6b26c4897) | Mar 24, 2024 |
| HP            | EliteBook 840 G4            | [c29d13bf92](https://linux-hardware.org/?probe=c29d13bf92) | Mar 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [433fee63bc](https://linux-hardware.org/?probe=433fee63bc) | Mar 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bbb4a23341](https://linux-hardware.org/?probe=bbb4a23341) | Mar 24, 2024 |
| MSI           | GT62VR 7RE                  | [5a46a7a194](https://linux-hardware.org/?probe=5a46a7a194) | Mar 24, 2024 |
| Apple         | MacBookPro8,1               | [55f07fcb9e](https://linux-hardware.org/?probe=55f07fcb9e) | Mar 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [95ba85ab58](https://linux-hardware.org/?probe=95ba85ab58) | Mar 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [67fc1bc6d4](https://linux-hardware.org/?probe=67fc1bc6d4) | Mar 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8ee75a3460](https://linux-hardware.org/?probe=8ee75a3460) | Mar 23, 2024 |
| Dell          | Precision M4500             | [64b323b223](https://linux-hardware.org/?probe=64b323b223) | Mar 23, 2024 |
| Lenovo        | ThinkPad X280 20KES0301F    | [4f2119ccf5](https://linux-hardware.org/?probe=4f2119ccf5) | Mar 23, 2024 |
| Dell          | Precision 3550              | [94674b699c](https://linux-hardware.org/?probe=94674b699c) | Mar 23, 2024 |
| Lenovo        | ThinkPad X220 4289A92       | [419b67eb72](https://linux-hardware.org/?probe=419b67eb72) | Mar 23, 2024 |
| HP            | EliteBook 8560w             | [1bf5084448](https://linux-hardware.org/?probe=1bf5084448) | Mar 23, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [ffe8ceea5a](https://linux-hardware.org/?probe=ffe8ceea5a) | Mar 23, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b97398e770](https://linux-hardware.org/?probe=b97398e770) | Mar 23, 2024 |
| Apple         | MacBookPro8,1               | [44bf0e419e](https://linux-hardware.org/?probe=44bf0e419e) | Mar 23, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [815151eddd](https://linux-hardware.org/?probe=815151eddd) | Mar 23, 2024 |
| Dell          | Precision 5510              | [da71f8326d](https://linux-hardware.org/?probe=da71f8326d) | Mar 22, 2024 |
| Lenovo        | 330S-15ARR 81FB             | [b825f202f8](https://linux-hardware.org/?probe=b825f202f8) | Mar 22, 2024 |
| HP            | Pavilion dv9700             | [6851f7a21a](https://linux-hardware.org/?probe=6851f7a21a) | Mar 22, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | [bea5a82b81](https://linux-hardware.org/?probe=bea5a82b81) | Mar 22, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | [5768f6b7e4](https://linux-hardware.org/?probe=5768f6b7e4) | Mar 22, 2024 |
| Dell          | Latitude 5480               | [ff785a4ce1](https://linux-hardware.org/?probe=ff785a4ce1) | Mar 22, 2024 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [88d382ec33](https://linux-hardware.org/?probe=88d382ec33) | Mar 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [3f2b9d56d7](https://linux-hardware.org/?probe=3f2b9d56d7) | Mar 22, 2024 |
| Dell          | Latitude E6230              | [78a94f507a](https://linux-hardware.org/?probe=78a94f507a) | Mar 21, 2024 |
| Apple         | MacBookPro9,1               | [4197088580](https://linux-hardware.org/?probe=4197088580) | Mar 21, 2024 |
| Dell          | Precision M4800             | [b5e30ec426](https://linux-hardware.org/?probe=b5e30ec426) | Mar 21, 2024 |
| Apple         | MacBookPro15,2              | [4f4b3cdccb](https://linux-hardware.org/?probe=4f4b3cdccb) | Mar 21, 2024 |
| Apple         | MacBookAir7,2               | [b013bb39fe](https://linux-hardware.org/?probe=b013bb39fe) | Mar 21, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [b2e638abe8](https://linux-hardware.org/?probe=b2e638abe8) | Mar 21, 2024 |
| Apple         | MacBook4,1                  | [bf0e5c50ea](https://linux-hardware.org/?probe=bf0e5c50ea) | Mar 21, 2024 |
| SLIMBOOK      | TITAN                       | [a0b40ac666](https://linux-hardware.org/?probe=a0b40ac666) | Mar 21, 2024 |
| Fujitsu       | LIFEBOOK E734               | [840661dcba](https://linux-hardware.org/?probe=840661dcba) | Mar 21, 2024 |
| Dell          | Inspiron N4010              | [b0bf69df9a](https://linux-hardware.org/?probe=b0bf69df9a) | Mar 21, 2024 |
| Lenovo        | G770 20089                  | [806788c3e5](https://linux-hardware.org/?probe=806788c3e5) | Mar 21, 2024 |
| Lenovo        | G770 20089                  | [4cb900586e](https://linux-hardware.org/?probe=4cb900586e) | Mar 21, 2024 |
| Alienware     | 17 R2                       | [eb210f842b](https://linux-hardware.org/?probe=eb210f842b) | Mar 21, 2024 |
| HONOR         | HLYL-WXX9                   | [62fe7bdcd7](https://linux-hardware.org/?probe=62fe7bdcd7) | Mar 21, 2024 |
| Dell          | Inspiron N4010              | [df814c37dd](https://linux-hardware.org/?probe=df814c37dd) | Mar 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [c369a7c1ed](https://linux-hardware.org/?probe=c369a7c1ed) | Mar 20, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [8b103ba076](https://linux-hardware.org/?probe=8b103ba076) | Mar 20, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [65d705c744](https://linux-hardware.org/?probe=65d705c744) | Mar 20, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | [04e9ad11ab](https://linux-hardware.org/?probe=04e9ad11ab) | Mar 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [abd25548fc](https://linux-hardware.org/?probe=abd25548fc) | Mar 20, 2024 |
| ASUSTek       | P552LA                      | [1e7c8ea0f7](https://linux-hardware.org/?probe=1e7c8ea0f7) | Mar 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fd5a3402a1](https://linux-hardware.org/?probe=fd5a3402a1) | Mar 20, 2024 |
| HUAWEI        | CREM-WXX9                   | [38269c9b67](https://linux-hardware.org/?probe=38269c9b67) | Mar 20, 2024 |
| Acer          | Aspire A514-54              | [fbe957e40f](https://linux-hardware.org/?probe=fbe957e40f) | Mar 20, 2024 |
| ASUSTek       | UX31E                       | [bb8b9596e5](https://linux-hardware.org/?probe=bb8b9596e5) | Mar 20, 2024 |
| Dell          | Latitude E7470              | [ab8a5e8ce5](https://linux-hardware.org/?probe=ab8a5e8ce5) | Mar 20, 2024 |
| HP            | EliteBook 2560p             | [a67fc46555](https://linux-hardware.org/?probe=a67fc46555) | Mar 19, 2024 |
| HP            | EliteBook 2560p             | [93c91024ea](https://linux-hardware.org/?probe=93c91024ea) | Mar 19, 2024 |
| Lenovo        | ThinkPad P53s 20N6001GGE    | [c4bc693f1f](https://linux-hardware.org/?probe=c4bc693f1f) | Mar 19, 2024 |
| Acer          | Aspire A314-23P             | [f7b12c681f](https://linux-hardware.org/?probe=f7b12c681f) | Mar 19, 2024 |
| Acer          | Aspire E5-771G              | [3b5d0f6921](https://linux-hardware.org/?probe=3b5d0f6921) | Mar 19, 2024 |
| HP            | Notebook                    | [90535a0e4b](https://linux-hardware.org/?probe=90535a0e4b) | Mar 19, 2024 |
| HP            | Notebook                    | [97043bd58f](https://linux-hardware.org/?probe=97043bd58f) | Mar 19, 2024 |
| Dell          | XPS 13 9360                 | [75bac9573b](https://linux-hardware.org/?probe=75bac9573b) | Mar 19, 2024 |
| LTD Delovo... | 15U                         | [86fd7e6d4a](https://linux-hardware.org/?probe=86fd7e6d4a) | Mar 19, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [0fa9c73550](https://linux-hardware.org/?probe=0fa9c73550) | Mar 19, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0004... | [62154aaa67](https://linux-hardware.org/?probe=62154aaa67) | Mar 19, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [74a0af3ace](https://linux-hardware.org/?probe=74a0af3ace) | Mar 19, 2024 |
| Razer         | Blade 14 - RZ09-0482        | [44a58b94b5](https://linux-hardware.org/?probe=44a58b94b5) | Mar 19, 2024 |
| HP            | Laptop 15-bs1xx             | [f341009f68](https://linux-hardware.org/?probe=f341009f68) | Mar 19, 2024 |
| Dell          | Inspiron 5570               | [12eb329aea](https://linux-hardware.org/?probe=12eb329aea) | Mar 19, 2024 |
| ASUSTek       | UX31E                       | [569f3ba982](https://linux-hardware.org/?probe=569f3ba982) | Mar 19, 2024 |
| Apple         | MacBookPro8,2               | [2a946685c1](https://linux-hardware.org/?probe=2a946685c1) | Mar 18, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f7da71747e](https://linux-hardware.org/?probe=f7da71747e) | Mar 18, 2024 |
| Razer         | Blade 14 - RZ09-0482        | [11880dc6e0](https://linux-hardware.org/?probe=11880dc6e0) | Mar 18, 2024 |
| Dell          | Inspiron 15-3567            | [4c1a37011d](https://linux-hardware.org/?probe=4c1a37011d) | Mar 18, 2024 |
| Dell          | Inspiron 15-3567            | [b322a7f7ff](https://linux-hardware.org/?probe=b322a7f7ff) | Mar 18, 2024 |
| Dell          | XPS 13 7390                 | [bd22d0e0ca](https://linux-hardware.org/?probe=bd22d0e0ca) | Mar 18, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [01f3900ba8](https://linux-hardware.org/?probe=01f3900ba8) | Mar 18, 2024 |
| Dell          | Latitude E6500              | [b094579770](https://linux-hardware.org/?probe=b094579770) | Mar 18, 2024 |
| Unknown       | Unknown                     | [f2d92ae386](https://linux-hardware.org/?probe=f2d92ae386) | Mar 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5d767c4912](https://linux-hardware.org/?probe=5d767c4912) | Mar 18, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [313c63108b](https://linux-hardware.org/?probe=313c63108b) | Mar 18, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | [dff417deef](https://linux-hardware.org/?probe=dff417deef) | Mar 18, 2024 |
| Alienware     | M17x                        | [fbdbfea7d8](https://linux-hardware.org/?probe=fbdbfea7d8) | Mar 18, 2024 |
| HP            | Laptop 15-bs1xx             | [eac08b7374](https://linux-hardware.org/?probe=eac08b7374) | Mar 18, 2024 |
| Packard Be... | EasyNote TJ65               | [00b7925953](https://linux-hardware.org/?probe=00b7925953) | Mar 18, 2024 |
| HP            | EliteBook 840 Aero G8 No... | [ad05f2ffb7](https://linux-hardware.org/?probe=ad05f2ffb7) | Mar 18, 2024 |
| Dell          | Latitude E6230              | [67bc6aae53](https://linux-hardware.org/?probe=67bc6aae53) | Mar 18, 2024 |
| Dell          | Latitude E6500              | [610674fdb6](https://linux-hardware.org/?probe=610674fdb6) | Mar 17, 2024 |
| Lenovo        | G505 20240                  | [15a2296a5e](https://linux-hardware.org/?probe=15a2296a5e) | Mar 17, 2024 |
| Apple         | MacBookPro8,1               | [d4f946dccd](https://linux-hardware.org/?probe=d4f946dccd) | Mar 17, 2024 |
| Apple         | MacBookPro8,1               | [b291ca03c0](https://linux-hardware.org/?probe=b291ca03c0) | Mar 17, 2024 |
| Dell          | Latitude E5440              | [4dfea625ba](https://linux-hardware.org/?probe=4dfea625ba) | Mar 17, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [1ce88ca0ff](https://linux-hardware.org/?probe=1ce88ca0ff) | Mar 17, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [e7b96ba325](https://linux-hardware.org/?probe=e7b96ba325) | Mar 17, 2024 |
| ASUSTek       | Strix 17 GL703GE            | [78fc7bc120](https://linux-hardware.org/?probe=78fc7bc120) | Mar 17, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [8dcb3c6e6e](https://linux-hardware.org/?probe=8dcb3c6e6e) | Mar 17, 2024 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [6cf8b6dfbb](https://linux-hardware.org/?probe=6cf8b6dfbb) | Mar 17, 2024 |
| HP            | Pavilion g6                 | [19c3a7e428](https://linux-hardware.org/?probe=19c3a7e428) | Mar 17, 2024 |
| Apple         | MacBookPro8,1               | [ffea228279](https://linux-hardware.org/?probe=ffea228279) | Mar 16, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [ca665b8165](https://linux-hardware.org/?probe=ca665b8165) | Mar 16, 2024 |
| Lenovo        | ThinkPad T490 20N3S3FX00    | [819d84d41f](https://linux-hardware.org/?probe=819d84d41f) | Mar 16, 2024 |
| Acer          | Predator PH16-71            | [e45e64cb9d](https://linux-hardware.org/?probe=e45e64cb9d) | Mar 16, 2024 |
| Dell          | XPS 15 9510                 | [3eb0629810](https://linux-hardware.org/?probe=3eb0629810) | Mar 16, 2024 |
| Fujitsu       | UH-X                        | [570594b1b8](https://linux-hardware.org/?probe=570594b1b8) | Mar 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3f171c561b](https://linux-hardware.org/?probe=3f171c561b) | Mar 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6b70347aa7](https://linux-hardware.org/?probe=6b70347aa7) | Mar 16, 2024 |
| HUAWEI        | BOM-WXX9                    | [4523fc3b5b](https://linux-hardware.org/?probe=4523fc3b5b) | Mar 16, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [abac559576](https://linux-hardware.org/?probe=abac559576) | Mar 16, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3693213bee](https://linux-hardware.org/?probe=3693213bee) | Mar 15, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [2da687baba](https://linux-hardware.org/?probe=2da687baba) | Mar 15, 2024 |
| HUAWEI        | MACHC-WAX9                  | [b312700336](https://linux-hardware.org/?probe=b312700336) | Mar 15, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [7f4a2b0418](https://linux-hardware.org/?probe=7f4a2b0418) | Mar 15, 2024 |
| MSI           | Bravo 15 C7UDX              | [4441dff3bf](https://linux-hardware.org/?probe=4441dff3bf) | Mar 15, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [637324dc21](https://linux-hardware.org/?probe=637324dc21) | Mar 15, 2024 |
| Fujitsu       | LIFEBOOK E5512A             | [a4027e3386](https://linux-hardware.org/?probe=a4027e3386) | Mar 15, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [e6003cf319](https://linux-hardware.org/?probe=e6003cf319) | Mar 15, 2024 |
| Acer          | Aspire A515-54G             | [7a1b6dfb64](https://linux-hardware.org/?probe=7a1b6dfb64) | Mar 15, 2024 |
| Acer          | Aspire A515-54G             | [9bf4d26fde](https://linux-hardware.org/?probe=9bf4d26fde) | Mar 15, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [20d2994e24](https://linux-hardware.org/?probe=20d2994e24) | Mar 15, 2024 |
| PC Special... | Lafite Pro III 15           | [41257b8ee3](https://linux-hardware.org/?probe=41257b8ee3) | Mar 15, 2024 |
| ARCELIK       | GNB 1150 B1 N2              | [ebe974790a](https://linux-hardware.org/?probe=ebe974790a) | Mar 14, 2024 |
| ARCELIK       | GNB 1150 B1 N2              | [abb3de4578](https://linux-hardware.org/?probe=abb3de4578) | Mar 14, 2024 |
| HP            | EliteBook 860 16 inch G9... | [229bc29a68](https://linux-hardware.org/?probe=229bc29a68) | Mar 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [67558b8124](https://linux-hardware.org/?probe=67558b8124) | Mar 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [afda13b5c3](https://linux-hardware.org/?probe=afda13b5c3) | Mar 14, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [aaab952c4c](https://linux-hardware.org/?probe=aaab952c4c) | Mar 14, 2024 |
| Lenovo        | ThinkPad S430 336457G       | [4e64dcc89e](https://linux-hardware.org/?probe=4e64dcc89e) | Mar 14, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | [5b53873162](https://linux-hardware.org/?probe=5b53873162) | Mar 14, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [6c43f0d8df](https://linux-hardware.org/?probe=6c43f0d8df) | Mar 14, 2024 |
| LG Electro... | 17Z90P-K.AA75A1             | [654e886aea](https://linux-hardware.org/?probe=654e886aea) | Mar 14, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [a17c2cb5e6](https://linux-hardware.org/?probe=a17c2cb5e6) | Mar 13, 2024 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [2509390925](https://linux-hardware.org/?probe=2509390925) | Mar 13, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [b33165a798](https://linux-hardware.org/?probe=b33165a798) | Mar 13, 2024 |
| Acer          | Aspire A515-44              | [5ada3f6f2b](https://linux-hardware.org/?probe=5ada3f6f2b) | Mar 13, 2024 |
| Apple         | MacBookPro14,1              | [957aa361c1](https://linux-hardware.org/?probe=957aa361c1) | Mar 13, 2024 |
| HP            | Pavilion dm3                | [2ae7a34348](https://linux-hardware.org/?probe=2ae7a34348) | Mar 13, 2024 |
| Acer          | NG-G3-572-75Y3              | [23a29d65ee](https://linux-hardware.org/?probe=23a29d65ee) | Mar 13, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [82bda69ec0](https://linux-hardware.org/?probe=82bda69ec0) | Mar 13, 2024 |
| Acer          | Predator PT515-51           | [be5eec8386](https://linux-hardware.org/?probe=be5eec8386) | Mar 13, 2024 |
| HP            | EliteBook 850 G1            | [65c6d3f39e](https://linux-hardware.org/?probe=65c6d3f39e) | Mar 13, 2024 |
| Dell          | Inspiron 3543               | [a160c09d29](https://linux-hardware.org/?probe=a160c09d29) | Mar 13, 2024 |
| Acer          | Aspire A715-51G             | [64a6a1066d](https://linux-hardware.org/?probe=64a6a1066d) | Mar 13, 2024 |
| Sony          | SVF14N13CXB                 | [e8ca8b6334](https://linux-hardware.org/?probe=e8ca8b6334) | Mar 13, 2024 |
| Apple         | MacBookPro14,1              | [7e02170101](https://linux-hardware.org/?probe=7e02170101) | Mar 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [f80fc50a95](https://linux-hardware.org/?probe=f80fc50a95) | Mar 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3c4326af6a](https://linux-hardware.org/?probe=3c4326af6a) | Mar 13, 2024 |
| Dell          | G7 7588                     | [956adb435e](https://linux-hardware.org/?probe=956adb435e) | Mar 12, 2024 |
| HP            | ENVY Laptop 17-cr1xxx       | [d09ef5488c](https://linux-hardware.org/?probe=d09ef5488c) | Mar 12, 2024 |
| Apple         | MacBookPro12,1              | [ab9c7984ab](https://linux-hardware.org/?probe=ab9c7984ab) | Mar 12, 2024 |
| Apple         | MacBookPro14,1              | [0dd49e19ad](https://linux-hardware.org/?probe=0dd49e19ad) | Mar 12, 2024 |
| Apple         | MacBookPro14,1              | [46c28ab6f4](https://linux-hardware.org/?probe=46c28ab6f4) | Mar 12, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [253a5cace0](https://linux-hardware.org/?probe=253a5cace0) | Mar 12, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9d22ecd7c0](https://linux-hardware.org/?probe=9d22ecd7c0) | Mar 12, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [0fc00c2837](https://linux-hardware.org/?probe=0fc00c2837) | Mar 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [2605d2fe75](https://linux-hardware.org/?probe=2605d2fe75) | Mar 12, 2024 |
| CRX           | N95                         | [472d8b11b7](https://linux-hardware.org/?probe=472d8b11b7) | Mar 12, 2024 |
| Dell          | Latitude 5420               | [225e5abd98](https://linux-hardware.org/?probe=225e5abd98) | Mar 12, 2024 |
| Google        | Cyan                        | [0cc944571a](https://linux-hardware.org/?probe=0cc944571a) | Mar 12, 2024 |
| Acer          | Aspire 5750                 | [57cb2f13a9](https://linux-hardware.org/?probe=57cb2f13a9) | Mar 11, 2024 |
| Dell          | XPS 15 7590                 | [dbcb29fc4e](https://linux-hardware.org/?probe=dbcb29fc4e) | Mar 11, 2024 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [47a991e51d](https://linux-hardware.org/?probe=47a991e51d) | Mar 11, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [944358baac](https://linux-hardware.org/?probe=944358baac) | Mar 11, 2024 |
| HP            | Pavilion 17                 | [3ec0291877](https://linux-hardware.org/?probe=3ec0291877) | Mar 11, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [d2695ebfb6](https://linux-hardware.org/?probe=d2695ebfb6) | Mar 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b7c41acc81](https://linux-hardware.org/?probe=b7c41acc81) | Mar 11, 2024 |
| Acer          | Aspire A315-59              | [edf84e43ee](https://linux-hardware.org/?probe=edf84e43ee) | Mar 11, 2024 |
| Dell          | Precision 5520              | [438d4fcd8b](https://linux-hardware.org/?probe=438d4fcd8b) | Mar 11, 2024 |
| Dell          | Precision 5520              | [c6b4d698c9](https://linux-hardware.org/?probe=c6b4d698c9) | Mar 11, 2024 |
| SLIMBOOK      | TITAN                       | [551179f7cd](https://linux-hardware.org/?probe=551179f7cd) | Mar 11, 2024 |
| Gigabyte      | B550M DS3H AC               | [1550ac647f](https://linux-hardware.org/?probe=1550ac647f) | Mar 10, 2024 |
| MSI           | Modern 15 A11MU             | [147c498235](https://linux-hardware.org/?probe=147c498235) | Mar 10, 2024 |
| Lenovo        | Flex 2-14 20404             | [5da900fb67](https://linux-hardware.org/?probe=5da900fb67) | Mar 10, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e430a077ba](https://linux-hardware.org/?probe=e430a077ba) | Mar 10, 2024 |
| Fujitsu       | UH-X                        | [fee081fe33](https://linux-hardware.org/?probe=fee081fe33) | Mar 10, 2024 |
| Lenovo        | Legion R7000P APH8 82Y9     | [42b7066b10](https://linux-hardware.org/?probe=42b7066b10) | Mar 10, 2024 |
| Alienware     | m15 R7 AMD                  | [e6f85671a4](https://linux-hardware.org/?probe=e6f85671a4) | Mar 10, 2024 |
| HP            | ENVY Laptop 17-cr1xxx       | [8381e30586](https://linux-hardware.org/?probe=8381e30586) | Mar 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4bb97e8868](https://linux-hardware.org/?probe=4bb97e8868) | Mar 10, 2024 |
| HP            | Laptop 14s-dq2xxx           | [9edb1b8e80](https://linux-hardware.org/?probe=9edb1b8e80) | Mar 10, 2024 |
| Lenovo        | V110-15ISK 80TL             | [2341d20d26](https://linux-hardware.org/?probe=2341d20d26) | Mar 10, 2024 |
| Dell          | Latitude E6440              | [7991b019ef](https://linux-hardware.org/?probe=7991b019ef) | Mar 10, 2024 |
| Dell          | Latitude E6440              | [1729bd7da3](https://linux-hardware.org/?probe=1729bd7da3) | Mar 10, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [1729eda52e](https://linux-hardware.org/?probe=1729eda52e) | Mar 10, 2024 |
| Lenovo        | V15 G4 ABP 82YY             | [a1d9dbb33e](https://linux-hardware.org/?probe=a1d9dbb33e) | Mar 10, 2024 |
| Apple         | MacBook5,1                  | [ec5813091b](https://linux-hardware.org/?probe=ec5813091b) | Mar 10, 2024 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | [6ca07ca433](https://linux-hardware.org/?probe=6ca07ca433) | Mar 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c4fae5c89](https://linux-hardware.org/?probe=3c4fae5c89) | Mar 10, 2024 |
| HONOR         | BOHK-WAX9X                  | [d7892c8c29](https://linux-hardware.org/?probe=d7892c8c29) | Mar 10, 2024 |
| Apple         | MacBook5,1                  | [25f0708b52](https://linux-hardware.org/?probe=25f0708b52) | Mar 10, 2024 |
| Lenovo        | Z50-70 20354                | [ba1a54631e](https://linux-hardware.org/?probe=ba1a54631e) | Mar 09, 2024 |
| Acer          | NG-G3-572-75Y3              | [b1da1a8b09](https://linux-hardware.org/?probe=b1da1a8b09) | Mar 09, 2024 |
| Acer          | Aspire A515-43              | [054ae2a4a5](https://linux-hardware.org/?probe=054ae2a4a5) | Mar 09, 2024 |
| ASUSTek       | TP301UA                     | [1f8c7b7644](https://linux-hardware.org/?probe=1f8c7b7644) | Mar 09, 2024 |
| ASUSTek       | TP301UA                     | [90f550ea4c](https://linux-hardware.org/?probe=90f550ea4c) | Mar 09, 2024 |
| MSI           | GF63 Thin 8SC               | [bbc6edbc2d](https://linux-hardware.org/?probe=bbc6edbc2d) | Mar 09, 2024 |
| HUAWEI        | BOM-WXX9                    | [c3b38c2e5c](https://linux-hardware.org/?probe=c3b38c2e5c) | Mar 09, 2024 |
| Lenovo        | IdeaPad U410                | [01389d9b94](https://linux-hardware.org/?probe=01389d9b94) | Mar 09, 2024 |
| Dell          | Latitude 5289               | [fe338e3231](https://linux-hardware.org/?probe=fe338e3231) | Mar 09, 2024 |
| Dell          | Inspiron 7548               | [4447047ecb](https://linux-hardware.org/?probe=4447047ecb) | Mar 09, 2024 |
| Lenovo        | ThinkPad T560 20FH001RUS    | [dc1169ec25](https://linux-hardware.org/?probe=dc1169ec25) | Mar 09, 2024 |
| Lenovo        | ThinkPad T495 20NKS1RQ01    | [5c00b6631a](https://linux-hardware.org/?probe=5c00b6631a) | Mar 09, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [fe32daee85](https://linux-hardware.org/?probe=fe32daee85) | Mar 09, 2024 |
| HUAWEI        | MACHC-WAX9                  | [9a80e12c77](https://linux-hardware.org/?probe=9a80e12c77) | Mar 09, 2024 |
| Acer          | Aspire E5-574G              | [e2b9eeaf50](https://linux-hardware.org/?probe=e2b9eeaf50) | Mar 08, 2024 |
| ECT           | ONE GAMING Laptop Agent ... | [5de8ec763e](https://linux-hardware.org/?probe=5de8ec763e) | Mar 08, 2024 |
| ASUSTek       | Zenbook UX8402VU_UX8402V... | [11541992d2](https://linux-hardware.org/?probe=11541992d2) | Mar 08, 2024 |
| Acer          | Nitro AN515-44              | [0371716016](https://linux-hardware.org/?probe=0371716016) | Mar 08, 2024 |
| Acer          | Nitro AN515-44              | [d1ff7df797](https://linux-hardware.org/?probe=d1ff7df797) | Mar 08, 2024 |
| HP            | ZBook 14 G2                 | [7136267ed7](https://linux-hardware.org/?probe=7136267ed7) | Mar 08, 2024 |
| Acer          | Aspire A515-57              | [4767e446b4](https://linux-hardware.org/?probe=4767e446b4) | Mar 08, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [3a321a169b](https://linux-hardware.org/?probe=3a321a169b) | Mar 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [10c46496a2](https://linux-hardware.org/?probe=10c46496a2) | Mar 08, 2024 |
| Dell          | Inspiron 5593               | [f80a3758f4](https://linux-hardware.org/?probe=f80a3758f4) | Mar 08, 2024 |
| Unknown       | Unknown                     | [3d2ee78848](https://linux-hardware.org/?probe=3d2ee78848) | Mar 08, 2024 |
| HP            | Pavilion Notebook           | [6c1a3e7d24](https://linux-hardware.org/?probe=6c1a3e7d24) | Mar 08, 2024 |
| HP            | Pavilion Notebook           | [71fa9b9d2e](https://linux-hardware.org/?probe=71fa9b9d2e) | Mar 08, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | [605efa5d0e](https://linux-hardware.org/?probe=605efa5d0e) | Mar 08, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | [e0459cc79f](https://linux-hardware.org/?probe=e0459cc79f) | Mar 08, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7700a7a168](https://linux-hardware.org/?probe=7700a7a168) | Mar 08, 2024 |
| Dell          | XPS 15 9530                 | [2f06508328](https://linux-hardware.org/?probe=2f06508328) | Mar 08, 2024 |
| HUAWEI        | HLYL-WXX9                   | [1268e9c989](https://linux-hardware.org/?probe=1268e9c989) | Mar 08, 2024 |
| Dell          | Latitude 5480               | [45ac0c15f6](https://linux-hardware.org/?probe=45ac0c15f6) | Mar 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [00e022702a](https://linux-hardware.org/?probe=00e022702a) | Mar 08, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [524c41a601](https://linux-hardware.org/?probe=524c41a601) | Mar 07, 2024 |
| Dell          | XPS 13 9370                 | [96e1e8d964](https://linux-hardware.org/?probe=96e1e8d964) | Mar 07, 2024 |
| Acer          | Aspire A514-52G             | [e272a833a9](https://linux-hardware.org/?probe=e272a833a9) | Mar 07, 2024 |
| Apple         | MacBookPro8,1               | [f1f560a5d9](https://linux-hardware.org/?probe=f1f560a5d9) | Mar 07, 2024 |
| Dell          | Precision M4800             | [8c3ccdefdf](https://linux-hardware.org/?probe=8c3ccdefdf) | Mar 07, 2024 |
| Apple         | MacBookPro14,1              | [cfac4d0bf1](https://linux-hardware.org/?probe=cfac4d0bf1) | Mar 07, 2024 |
| Dell          | Precision M4800             | [ee670169c3](https://linux-hardware.org/?probe=ee670169c3) | Mar 07, 2024 |
| Dell          | Inspiron 11-3168            | [fb161333d5](https://linux-hardware.org/?probe=fb161333d5) | Mar 07, 2024 |
| Dell          | Inspiron 15-5578            | [1989ba3a95](https://linux-hardware.org/?probe=1989ba3a95) | Mar 07, 2024 |
| Apple         | MacBookPro14,1              | [2cffa130aa](https://linux-hardware.org/?probe=2cffa130aa) | Mar 07, 2024 |
| Lenovo        | ThinkPad T480s 20L8A04HU... | [c0b7940b94](https://linux-hardware.org/?probe=c0b7940b94) | Mar 07, 2024 |
| HP            | Pavilion Laptop 14-ce2xx... | [a41d273411](https://linux-hardware.org/?probe=a41d273411) | Mar 07, 2024 |
| Framework     | Laptop                      | [61f57ff8e6](https://linux-hardware.org/?probe=61f57ff8e6) | Mar 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [d8a1f42773](https://linux-hardware.org/?probe=d8a1f42773) | Mar 07, 2024 |
| Acer          | Aspire A515-54              | [d4f875966c](https://linux-hardware.org/?probe=d4f875966c) | Mar 06, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [316b6d3fd6](https://linux-hardware.org/?probe=316b6d3fd6) | Mar 06, 2024 |
| HUAWEI        | NBM-WXX9                    | [2e1dca9bf1](https://linux-hardware.org/?probe=2e1dca9bf1) | Mar 06, 2024 |
| Dell          | Latitude 7480               | [5de3625fd8](https://linux-hardware.org/?probe=5de3625fd8) | Mar 06, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a57603903a](https://linux-hardware.org/?probe=a57603903a) | Mar 06, 2024 |
| PC Special... | Standard                    | [09db510396](https://linux-hardware.org/?probe=09db510396) | Mar 06, 2024 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b1f55d2745](https://linux-hardware.org/?probe=b1f55d2745) | Mar 06, 2024 |
| Dell          | Precision 7550              | [01d42b6548](https://linux-hardware.org/?probe=01d42b6548) | Mar 06, 2024 |
| Unknown       | Unknown                     | [23114923e2](https://linux-hardware.org/?probe=23114923e2) | Mar 06, 2024 |
| HP            | ProBook 4720s               | [134f6993e2](https://linux-hardware.org/?probe=134f6993e2) | Mar 06, 2024 |
| ASUSTek       | X453MA                      | [e1e03429e2](https://linux-hardware.org/?probe=e1e03429e2) | Mar 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [a3cdcfa3c5](https://linux-hardware.org/?probe=a3cdcfa3c5) | Mar 05, 2024 |
| MSI           | Modern 14 B11MOU            | [0e93128c3f](https://linux-hardware.org/?probe=0e93128c3f) | Mar 05, 2024 |
| ASUSTek       | F80Q                        | [613ffc9f22](https://linux-hardware.org/?probe=613ffc9f22) | Mar 05, 2024 |
| HUAWEI        | HVY-WXX9                    | [cfd713e6d5](https://linux-hardware.org/?probe=cfd713e6d5) | Mar 05, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [23b7d5bdae](https://linux-hardware.org/?probe=23b7d5bdae) | Mar 05, 2024 |
| Dell          | XPS 15 9560                 | [898154cbf9](https://linux-hardware.org/?probe=898154cbf9) | Mar 05, 2024 |
| HP            | EliteBook 840 G6            | [8ad6d87c2e](https://linux-hardware.org/?probe=8ad6d87c2e) | Mar 05, 2024 |
| Chuwi         | GemiBook Pro                | [3318fa4906](https://linux-hardware.org/?probe=3318fa4906) | Mar 05, 2024 |
| Chuwi         | GemiBook Pro                | [971e3ba533](https://linux-hardware.org/?probe=971e3ba533) | Mar 05, 2024 |
| Lenovo        | Unknown                     | [821c1ffdbe](https://linux-hardware.org/?probe=821c1ffdbe) | Mar 04, 2024 |
| HP            | ZBook Studio G5             | [208ce1e5fd](https://linux-hardware.org/?probe=208ce1e5fd) | Mar 04, 2024 |
| Compaq        | PRESARIOCQ18                | [8077da8d33](https://linux-hardware.org/?probe=8077da8d33) | Mar 04, 2024 |
| Apple         | MacBookPro8,1               | [b5d292fc18](https://linux-hardware.org/?probe=b5d292fc18) | Mar 04, 2024 |
| Maibenben     | MaiBook M                   | [b589598404](https://linux-hardware.org/?probe=b589598404) | Mar 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b75f098f59](https://linux-hardware.org/?probe=b75f098f59) | Mar 04, 2024 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [c2297db77f](https://linux-hardware.org/?probe=c2297db77f) | Mar 04, 2024 |
| CSL-Comput... | T14 v2                      | [9353bbc0cb](https://linux-hardware.org/?probe=9353bbc0cb) | Mar 04, 2024 |
| Dell          | XPS 13 9310                 | [f788059abd](https://linux-hardware.org/?probe=f788059abd) | Mar 04, 2024 |
| Apple         | MacBookPro11,2              | [3c91f66fcd](https://linux-hardware.org/?probe=3c91f66fcd) | Mar 04, 2024 |
| Acer          | Nitro AN515-54              | [b1cac18eb5](https://linux-hardware.org/?probe=b1cac18eb5) | Mar 04, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6e670eec25](https://linux-hardware.org/?probe=6e670eec25) | Mar 04, 2024 |
| Dell          | XPS 9320                    | [cb10809a8f](https://linux-hardware.org/?probe=cb10809a8f) | Mar 04, 2024 |
| Toshiba       | QOSMIO X70-A                | [2d2a35d8df](https://linux-hardware.org/?probe=2d2a35d8df) | Mar 03, 2024 |
| Toshiba       | QOSMIO X70-A                | [1d948103cf](https://linux-hardware.org/?probe=1d948103cf) | Mar 03, 2024 |
| THUNDEROBO... | 911S                        | [71618e3421](https://linux-hardware.org/?probe=71618e3421) | Mar 03, 2024 |
| THUNDEROBO... | 911S                        | [77d46f40ce](https://linux-hardware.org/?probe=77d46f40ce) | Mar 03, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6662caaaad](https://linux-hardware.org/?probe=6662caaaad) | Mar 03, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [a0f65ca405](https://linux-hardware.org/?probe=a0f65ca405) | Mar 03, 2024 |
| Acer          | Aspire A515-55G             | [9d2dde6d8c](https://linux-hardware.org/?probe=9d2dde6d8c) | Mar 03, 2024 |
| Dell          | Latitude E6230              | [49f05d7c23](https://linux-hardware.org/?probe=49f05d7c23) | Mar 03, 2024 |
| Apple         | MacBook10,1                 | [55ec44d9b3](https://linux-hardware.org/?probe=55ec44d9b3) | Mar 03, 2024 |
| Apple         | MacBook10,1                 | [ba5be41b6e](https://linux-hardware.org/?probe=ba5be41b6e) | Mar 03, 2024 |
| Google        | Kled                        | [31628d29e1](https://linux-hardware.org/?probe=31628d29e1) | Mar 03, 2024 |
| TECNO Mobi... | MEGABOOK T1 TGL             | [b55c18be6e](https://linux-hardware.org/?probe=b55c18be6e) | Mar 03, 2024 |
| Dell          | Inspiron 15-3567            | [ae4cdbb501](https://linux-hardware.org/?probe=ae4cdbb501) | Mar 03, 2024 |
| ASUSTek       | Zenbook UX425QA_UM425QA     | [21975edff4](https://linux-hardware.org/?probe=21975edff4) | Mar 03, 2024 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [24dd3cbd21](https://linux-hardware.org/?probe=24dd3cbd21) | Mar 03, 2024 |
| Linx          | LINX1010B                   | [185483454f](https://linux-hardware.org/?probe=185483454f) | Mar 03, 2024 |
| Apple         | MacBookPro14,1              | [69f0e32aa7](https://linux-hardware.org/?probe=69f0e32aa7) | Mar 02, 2024 |
| Apple         | MacBookPro14,1              | [d96fbfaa4d](https://linux-hardware.org/?probe=d96fbfaa4d) | Mar 02, 2024 |
| Lenovo        | ThinkPad L480 20LTS4Y600    | [e28b6be6f7](https://linux-hardware.org/?probe=e28b6be6f7) | Mar 02, 2024 |
| Google        | Cyan                        | [e74753d72c](https://linux-hardware.org/?probe=e74753d72c) | Mar 02, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [231c4ecf3b](https://linux-hardware.org/?probe=231c4ecf3b) | Mar 02, 2024 |
| HUAWEI        | BOM-WXX9                    | [3a7fd5ff3f](https://linux-hardware.org/?probe=3a7fd5ff3f) | Mar 02, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [c9a57d1573](https://linux-hardware.org/?probe=c9a57d1573) | Mar 02, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | [b85a5f54e0](https://linux-hardware.org/?probe=b85a5f54e0) | Mar 02, 2024 |
| ASUSTek       | K501LB                      | [d40732a5f1](https://linux-hardware.org/?probe=d40732a5f1) | Mar 02, 2024 |
| Acer          | Nitro AN515-46              | [968c22dfbb](https://linux-hardware.org/?probe=968c22dfbb) | Mar 02, 2024 |
| HP            | EliteBook 840 G3            | [3c120a627d](https://linux-hardware.org/?probe=3c120a627d) | Mar 02, 2024 |
| Lenovo        | ThinkPad L380 20M6A00800    | [b85a1da621](https://linux-hardware.org/?probe=b85a1da621) | Mar 02, 2024 |
| Lenovo        | ThinkPad T450 20BUS0QT03    | [40e1c764cc](https://linux-hardware.org/?probe=40e1c764cc) | Mar 01, 2024 |
| SLIMBOOK      | PROX15-AMD                  | [b50ca64146](https://linux-hardware.org/?probe=b50ca64146) | Mar 01, 2024 |
| HP            | EliteBook 840 G3            | [6067e37980](https://linux-hardware.org/?probe=6067e37980) | Mar 01, 2024 |
| HP            | Laptop 17-bs0xx             | [019d8a8d68](https://linux-hardware.org/?probe=019d8a8d68) | Mar 01, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [204971811b](https://linux-hardware.org/?probe=204971811b) | Mar 01, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edcd356d73](https://linux-hardware.org/?probe=edcd356d73) | Mar 01, 2024 |
| AMI           | Intel                       | [e9dc6ddc46](https://linux-hardware.org/?probe=e9dc6ddc46) | Mar 01, 2024 |
| Dell          | Precision 7760              | [e032c1878e](https://linux-hardware.org/?probe=e032c1878e) | Mar 01, 2024 |
| HP            | Pavilion g6                 | [f6ef470081](https://linux-hardware.org/?probe=f6ef470081) | Mar 01, 2024 |
| Chuwi         | Hi10 Go                     | [8f143f6874](https://linux-hardware.org/?probe=8f143f6874) | Mar 01, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [fe3f707bbb](https://linux-hardware.org/?probe=fe3f707bbb) | Mar 01, 2024 |
| Acer          | Aspire A514-52G             | [bbb24a24fa](https://linux-hardware.org/?probe=bbb24a24fa) | Feb 29, 2024 |
| Dell          | Latitude 5430               | [7898f47001](https://linux-hardware.org/?probe=7898f47001) | Feb 29, 2024 |
| Unknown       | WY133A                      | [ac6776d5fc](https://linux-hardware.org/?probe=ac6776d5fc) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [88e7a5c628](https://linux-hardware.org/?probe=88e7a5c628) | Feb 29, 2024 |
| Positivo      | C4240AI-15                  | [9c0dc5edf3](https://linux-hardware.org/?probe=9c0dc5edf3) | Feb 29, 2024 |
| Acer          | Extensa 2511                | [0f4bcc7a0f](https://linux-hardware.org/?probe=0f4bcc7a0f) | Feb 29, 2024 |
| MSI           | Modern 14 B11SBU            | [5a5e7d82d7](https://linux-hardware.org/?probe=5a5e7d82d7) | Feb 29, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [935b64ed30](https://linux-hardware.org/?probe=935b64ed30) | Feb 29, 2024 |
| Acer          | Nitro AN515-57              | [7e202b0bf0](https://linux-hardware.org/?probe=7e202b0bf0) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a387b3439f](https://linux-hardware.org/?probe=a387b3439f) | Feb 29, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [a89a6188f3](https://linux-hardware.org/?probe=a89a6188f3) | Feb 29, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | [3226e99762](https://linux-hardware.org/?probe=3226e99762) | Feb 28, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4032a951c0](https://linux-hardware.org/?probe=4032a951c0) | Feb 28, 2024 |
| Google        | Fleex                       | [8e0e838293](https://linux-hardware.org/?probe=8e0e838293) | Feb 28, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a33280c60d](https://linux-hardware.org/?probe=a33280c60d) | Feb 28, 2024 |
| Dell          | Precision 7720              | [51cdb8ec52](https://linux-hardware.org/?probe=51cdb8ec52) | Feb 28, 2024 |
| Lenovo        | ThinkPad T470 20HD000EHV    | [e398f98431](https://linux-hardware.org/?probe=e398f98431) | Feb 28, 2024 |
| Toshiba       | Satellite L875              | [a10c5ac721](https://linux-hardware.org/?probe=a10c5ac721) | Feb 28, 2024 |
| HP            | EliteBook Folio 1040 G3     | [74e42de463](https://linux-hardware.org/?probe=74e42de463) | Feb 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a599204e74](https://linux-hardware.org/?probe=a599204e74) | Feb 28, 2024 |
| ASUSTek       | M80TA                       | [5f355dcdbe](https://linux-hardware.org/?probe=5f355dcdbe) | Feb 28, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [48f5d48f4f](https://linux-hardware.org/?probe=48f5d48f4f) | Feb 28, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [1eb393358b](https://linux-hardware.org/?probe=1eb393358b) | Feb 28, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [80e87858cf](https://linux-hardware.org/?probe=80e87858cf) | Feb 27, 2024 |
| HP            | EliteBook Folio 1040 G3     | [f8ca8ffa74](https://linux-hardware.org/?probe=f8ca8ffa74) | Feb 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fb716bf15a](https://linux-hardware.org/?probe=fb716bf15a) | Feb 27, 2024 |
| Timi          | Redmi Book Pro 14 2022      | [b2c8fa2bd5](https://linux-hardware.org/?probe=b2c8fa2bd5) | Feb 27, 2024 |
| Dell          | Precision 3530              | [e0f9df42ca](https://linux-hardware.org/?probe=e0f9df42ca) | Feb 27, 2024 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [dc511ffd5f](https://linux-hardware.org/?probe=dc511ffd5f) | Feb 27, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [44cc34fb38](https://linux-hardware.org/?probe=44cc34fb38) | Feb 27, 2024 |
| Dell          | Latitude 5590               | [9c7d2af833](https://linux-hardware.org/?probe=9c7d2af833) | Feb 27, 2024 |
| Timi          | Mi NoteBook Ultra           | [be15da34bb](https://linux-hardware.org/?probe=be15da34bb) | Feb 27, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [354d18fbcc](https://linux-hardware.org/?probe=354d18fbcc) | Feb 27, 2024 |
| Apple         | MacBookPro14,3              | [c0ebb71a0b](https://linux-hardware.org/?probe=c0ebb71a0b) | Feb 27, 2024 |
| Intel         | intibook                    | [7668db4bcd](https://linux-hardware.org/?probe=7668db4bcd) | Feb 27, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ce35471f83](https://linux-hardware.org/?probe=ce35471f83) | Feb 27, 2024 |
| Dell          | Latitude E6430              | [1121d113bf](https://linux-hardware.org/?probe=1121d113bf) | Feb 26, 2024 |
| Dell          | Latitude E6430              | [860bbdc112](https://linux-hardware.org/?probe=860bbdc112) | Feb 26, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0fa9131028](https://linux-hardware.org/?probe=0fa9131028) | Feb 26, 2024 |
| Clevo         | D900C                       | [4f01daad16](https://linux-hardware.org/?probe=4f01daad16) | Feb 26, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7441889f1](https://linux-hardware.org/?probe=c7441889f1) | Feb 26, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [34a532791a](https://linux-hardware.org/?probe=34a532791a) | Feb 26, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [339c1aaeb1](https://linux-hardware.org/?probe=339c1aaeb1) | Feb 26, 2024 |
| HUAWEI        | HKD-WXX                     | [f13b90ff35](https://linux-hardware.org/?probe=f13b90ff35) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [fd7cecbb27](https://linux-hardware.org/?probe=fd7cecbb27) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [42410484b6](https://linux-hardware.org/?probe=42410484b6) | Feb 26, 2024 |
| ASUSTek       | X202EP                      | [0500d514e8](https://linux-hardware.org/?probe=0500d514e8) | Feb 26, 2024 |
| Apple         | MacBookPro12,1              | [3e204ee57c](https://linux-hardware.org/?probe=3e204ee57c) | Feb 25, 2024 |
| Apple         | MacBookPro11,5              | [e079325d3f](https://linux-hardware.org/?probe=e079325d3f) | Feb 25, 2024 |
| Toshiba       | PORTEGE Z20T-B              | [5c0becae45](https://linux-hardware.org/?probe=5c0becae45) | Feb 25, 2024 |
| Acer          | Aspire 5733                 | [3f1c51c526](https://linux-hardware.org/?probe=3f1c51c526) | Feb 25, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [d3f9302555](https://linux-hardware.org/?probe=d3f9302555) | Feb 25, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0abb317a3d](https://linux-hardware.org/?probe=0abb317a3d) | Feb 25, 2024 |
| Lenovo        | ThinkPad X200 Tablet 745... | [7d1fbbf6ed](https://linux-hardware.org/?probe=7d1fbbf6ed) | Feb 25, 2024 |
| Samsung       | RV411/RV511/E3511/S3511     | [5af12a1d29](https://linux-hardware.org/?probe=5af12a1d29) | Feb 25, 2024 |
| HP            | OMEN by Laptop              | [f5d826478a](https://linux-hardware.org/?probe=f5d826478a) | Feb 25, 2024 |
| Lenovo        | ThinkPad L380 20M6A00800    | [b65e205358](https://linux-hardware.org/?probe=b65e205358) | Feb 25, 2024 |
| HP            | Laptop 14-fq0xxx            | [30277355f3](https://linux-hardware.org/?probe=30277355f3) | Feb 25, 2024 |
| Dell          | XPS 15 9530                 | [a04353dfd1](https://linux-hardware.org/?probe=a04353dfd1) | Feb 25, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d2703786e9](https://linux-hardware.org/?probe=d2703786e9) | Feb 25, 2024 |
| Lenovo        | ThinkPad L480 20LTS7T800    | [522229ee6f](https://linux-hardware.org/?probe=522229ee6f) | Feb 24, 2024 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [474d7d9a50](https://linux-hardware.org/?probe=474d7d9a50) | Feb 24, 2024 |
| Apple         | MacBookPro12,1              | [6fa1f75e39](https://linux-hardware.org/?probe=6fa1f75e39) | Feb 24, 2024 |
| Medion        | E14304                      | [364518962e](https://linux-hardware.org/?probe=364518962e) | Feb 24, 2024 |
| HP            | Laptop 14s-fq1xxx           | [6bb2788890](https://linux-hardware.org/?probe=6bb2788890) | Feb 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [296f52bf01](https://linux-hardware.org/?probe=296f52bf01) | Feb 24, 2024 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | [e21ac7c0a0](https://linux-hardware.org/?probe=e21ac7c0a0) | Feb 24, 2024 |
| Dell          | Latitude E6430              | [efb55db7dd](https://linux-hardware.org/?probe=efb55db7dd) | Feb 24, 2024 |
| Lenovo        | ThinkPad T480s 20L8S70N0... | [e22e9c6b98](https://linux-hardware.org/?probe=e22e9c6b98) | Feb 24, 2024 |
| Medion        | E14304                      | [ca85dce24e](https://linux-hardware.org/?probe=ca85dce24e) | Feb 24, 2024 |
| HP            | Laptop 14s-fq1xxx           | [db0b93e1b9](https://linux-hardware.org/?probe=db0b93e1b9) | Feb 24, 2024 |
| Acer          | Aspire A315-55G             | [f5b7121a08](https://linux-hardware.org/?probe=f5b7121a08) | Feb 24, 2024 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [18d49fdf41](https://linux-hardware.org/?probe=18d49fdf41) | Feb 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [3cac5a9fac](https://linux-hardware.org/?probe=3cac5a9fac) | Feb 24, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [c651e72886](https://linux-hardware.org/?probe=c651e72886) | Feb 24, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | [19f5064a8e](https://linux-hardware.org/?probe=19f5064a8e) | Feb 24, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | [d6e9ae9de6](https://linux-hardware.org/?probe=d6e9ae9de6) | Feb 24, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [125a06b18a](https://linux-hardware.org/?probe=125a06b18a) | Feb 24, 2024 |
| TUXEDO        | Pulse 14 Gen3               | [f63d2faf13](https://linux-hardware.org/?probe=f63d2faf13) | Feb 24, 2024 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | [136a52a9df](https://linux-hardware.org/?probe=136a52a9df) | Feb 23, 2024 |
| Lenovo        | ThinkPad T490 20N3SC8T00    | [9c2ae2e6d2](https://linux-hardware.org/?probe=9c2ae2e6d2) | Feb 23, 2024 |
| Acer          | Aspire A515-55G             | [46ccc39ce8](https://linux-hardware.org/?probe=46ccc39ce8) | Feb 23, 2024 |
| Lenovo        | ThinkPad X280 20KES0301F    | [1f22e2a01a](https://linux-hardware.org/?probe=1f22e2a01a) | Feb 23, 2024 |
| Medion        | ERAZER P6705 MD61409        | [1acf80df5e](https://linux-hardware.org/?probe=1acf80df5e) | Feb 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4725f6700e](https://linux-hardware.org/?probe=4725f6700e) | Feb 23, 2024 |
| Medion        | ERAZER P6705 MD61409        | [7ae2637aad](https://linux-hardware.org/?probe=7ae2637aad) | Feb 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [854b480d0e](https://linux-hardware.org/?probe=854b480d0e) | Feb 23, 2024 |
| HP            | Victus by Gaming Laptop ... | [46e3558e2c](https://linux-hardware.org/?probe=46e3558e2c) | Feb 23, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6a88d5ebaf](https://linux-hardware.org/?probe=6a88d5ebaf) | Feb 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [31008e9ce3](https://linux-hardware.org/?probe=31008e9ce3) | Feb 23, 2024 |
| HP            | Victus by Gaming Laptop ... | [32aa95befd](https://linux-hardware.org/?probe=32aa95befd) | Feb 23, 2024 |
| Positivo      | C4128E-S                    | [ef50210dea](https://linux-hardware.org/?probe=ef50210dea) | Feb 23, 2024 |
| Apple         | MacBookPro8,2               | [274dd5ae51](https://linux-hardware.org/?probe=274dd5ae51) | Feb 23, 2024 |
| HP            | EliteBook 850 G3            | [bf5310d274](https://linux-hardware.org/?probe=bf5310d274) | Feb 23, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [d3b0041d5d](https://linux-hardware.org/?probe=d3b0041d5d) | Feb 22, 2024 |
| Dell          | Vostro 3700                 | [17fd185a72](https://linux-hardware.org/?probe=17fd185a72) | Feb 22, 2024 |
| Dell          | Precision 5520              | [ef95414cdd](https://linux-hardware.org/?probe=ef95414cdd) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [1736ebc6c2](https://linux-hardware.org/?probe=1736ebc6c2) | Feb 22, 2024 |
| HP            | ENVY m7 Notebook            | [e16748a252](https://linux-hardware.org/?probe=e16748a252) | Feb 22, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_39/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.5.6-300.fc39.x86_64  | 237       | 11.85%  |
| 6.5.11-300.fc39.x86_64 | 137       | 6.85%   |
| 6.7.9-200.fc39.x86_64  | 124       | 6.2%    |
| 6.6.9-200.fc39.x86_64  | 110       | 5.5%    |
| 6.7.4-200.fc39.x86_64  | 108       | 5.4%    |
| 6.6.8-200.fc39.x86_64  | 105       | 5.25%   |
| 6.7.7-200.fc39.x86_64  | 87        | 4.35%   |
| 6.6.13-200.fc39.x86_64 | 68        | 3.4%    |
| 6.5.12-300.fc39.x86_64 | 61        | 3.05%   |
| 6.8.4-200.fc39.x86_64  | 57        | 2.85%   |
| 6.6.4-200.fc39.x86_64  | 57        | 2.85%   |
| 6.7.5-200.fc39.x86_64  | 55        | 2.75%   |
| 6.6.6-200.fc39.x86_64  | 55        | 2.75%   |
| 6.6.11-200.fc39.x86_64 | 52        | 2.6%    |
| 6.6.7-200.fc39.x86_64  | 49        | 2.45%   |
| 6.8.6-200.fc39.x86_64  | 47        | 2.35%   |
| 6.7.6-200.fc39.x86_64  | 47        | 2.35%   |
| 6.7.10-200.fc39.x86_64 | 47        | 2.35%   |
| 6.7.3-200.fc39.x86_64  | 41        | 2.05%   |
| 6.6.2-201.fc39.x86_64  | 41        | 2.05%   |
| 6.7.11-200.fc39.x86_64 | 39        | 1.95%   |
| 6.8.7-200.fc39.x86_64  | 31        | 1.55%   |
| 6.6.14-200.fc39.x86_64 | 30        | 1.5%    |
| 6.8.5-201.fc39.x86_64  | 29        | 1.45%   |
| 6.8.9-200.fc39.x86_64  | 23        | 1.15%   |
| 6.6.3-200.fc39.x86_64  | 23        | 1.15%   |
| 6.6.12-200.fc39.x86_64 | 23        | 1.15%   |
| 6.5.10-300.fc39.x86_64 | 19        | 0.95%   |
| 6.8.8-200.fc39.x86_64  | 12        | 0.6%    |
| 6.5.9-300.fc39.x86_64  | 12        | 0.6%    |
| 6.8.11-200.fc39.x86_64 | 10        | 0.5%    |
| 6.5.5-300.fc39.x86_64  | 10        | 0.5%    |
| 6.10.6-100.fc39.x86_64 | 7         | 0.35%   |
| 6.9.7-100.fc39.x86_64  | 5         | 0.25%   |
| 6.5.8-300.fc39.x86_64  | 4         | 0.2%    |
| 6.5.4-300.fc39.x86_64  | 4         | 0.2%    |
| 6.5.2-301.fc39.x86_64  | 4         | 0.2%    |
| 6.9.9-100.fc39.x86_64  | 3         | 0.15%   |
| 6.9.6-100.fc39.x86_64  | 3         | 0.15%   |
| 6.9.12-100.fc39.x86_64 | 3         | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.6   | 237       | 11.86%  |
| 6.5.11  | 137       | 6.85%   |
| 6.7.9   | 129       | 6.45%   |
| 6.7.4   | 111       | 5.55%   |
| 6.6.9   | 111       | 5.55%   |
| 6.6.8   | 109       | 5.45%   |
| 6.7.7   | 92        | 4.6%    |
| 6.6.13  | 68        | 3.4%    |
| 6.5.12  | 61        | 3.05%   |
| 6.6.4   | 59        | 2.95%   |
| 6.8.4   | 57        | 2.85%   |
| 6.7.5   | 57        | 2.85%   |
| 6.6.6   | 55        | 2.75%   |
| 6.6.7   | 52        | 2.6%    |
| 6.6.11  | 52        | 2.6%    |
| 6.7.6   | 49        | 2.45%   |
| 6.8.6   | 47        | 2.35%   |
| 6.7.10  | 47        | 2.35%   |
| 6.7.3   | 42        | 2.1%    |
| 6.6.2   | 41        | 2.05%   |
| 6.7.11  | 40        | 2%      |
| 6.8.7   | 32        | 1.6%    |
| 6.6.14  | 30        | 1.5%    |
| 6.8.5   | 29        | 1.45%   |
| 6.6.3   | 25        | 1.25%   |
| 6.6.12  | 24        | 1.2%    |
| 6.8.9   | 23        | 1.15%   |
| 6.5.10  | 20        | 1%      |
| 6.8.8   | 13        | 0.65%   |
| 6.5.9   | 12        | 0.6%    |
| 6.8.11  | 10        | 0.5%    |
| 6.5.5   | 10        | 0.5%    |
| 6.7.0   | 7         | 0.35%   |
| 6.10.6  | 7         | 0.35%   |
| 6.9.7   | 5         | 0.25%   |
| 6.8.0   | 4         | 0.2%    |
| 6.7.1   | 4         | 0.2%    |
| 6.5.8   | 4         | 0.2%    |
| 6.5.4   | 4         | 0.2%    |
| 6.5.2   | 4         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 608       | 31.32%  |
| 6.7     | 562       | 28.95%  |
| 6.5     | 489       | 25.19%  |
| 6.8     | 217       | 11.18%  |
| 6.9     | 23        | 1.18%   |
| 6.10    | 20        | 1.03%   |
| 6.11    | 7         | 0.36%   |
| 6.4     | 5         | 0.26%   |
| 6.2     | 4         | 0.21%   |
| 6.3     | 3         | 0.15%   |
| 6.0     | 2         | 0.1%    |
| 5.0     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1840      | 99.89%  |
| aarch64 | 2         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 1460      | 78.88%  |
| KDE5           | 243       | 13.13%  |
| Unknown        | 26        | 1.4%    |
| XFCE           | 24        | 1.3%    |
| X-Cinnamon     | 18        | 0.97%   |
| GNOME Classic  | 15        | 0.81%   |
| MATE           | 13        | 0.7%    |
| Cinnamon       | 11        | 0.59%   |
| Budgie         | 11        | 0.59%   |
| sway           | 9         | 0.49%   |
| Hyprland       | 5         | 0.27%   |
| i3             | 4         | 0.22%   |
| LXQt           | 3         | 0.16%   |
| KDE6           | 2         | 0.11%   |
| GNOME-Classic  | 2         | 0.11%   |
| river          | 1         | 0.05%   |
| LXDE           | 1         | 0.05%   |
| KDE            | 1         | 0.05%   |
| i3-with-shmlog | 1         | 0.05%   |
| Deepin         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 1576      | 84.82%  |
| X11     | 249       | 13.4%   |
| Tty     | 18        | 0.97%   |
| Unknown | 15        | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1191      | 64.24%  |
| GDM     | 451       | 24.33%  |
| SDDM    | 130       | 7.01%   |
| LightDM | 82        | 4.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 931       | 50.43%  |
| en_GB   | 142       | 7.69%   |
| ru_RU   | 115       | 6.23%   |
| de_DE   | 92        | 4.98%   |
| pt_BR   | 80        | 4.33%   |
| it_IT   | 57        | 3.09%   |
| fr_FR   | 50        | 2.71%   |
| pl_PL   | 41        | 2.22%   |
| en_IN   | 35        | 1.9%    |
| en_CA   | 32        | 1.73%   |
| en_AU   | 27        | 1.46%   |
| es_ES   | 24        | 1.3%    |
| es_MX   | 22        | 1.19%   |
| tr_TR   | 18        | 0.98%   |
| es_CL   | 12        | 0.65%   |
| es_AR   | 11        | 0.6%    |
| de_CH   | 10        | 0.54%   |
| zh_CN   | 9         | 0.49%   |
| es_CO   | 9         | 0.49%   |
| cs_CZ   | 8         | 0.43%   |
| de_AT   | 7         | 0.38%   |
| Unknown | 7         | 0.38%   |
| hu_HU   | 6         | 0.33%   |
| en_ZA   | 6         | 0.33%   |
| en_DK   | 6         | 0.33%   |
| ru_UA   | 5         | 0.27%   |
| pt_PT   | 5         | 0.27%   |
| nb_NO   | 5         | 0.27%   |
| fr_CH   | 4         | 0.22%   |
| en_NZ   | 4         | 0.22%   |
| uk_UA   | 3         | 0.16%   |
| fr_CA   | 3         | 0.16%   |
| fi_FI   | 3         | 0.16%   |
| es_PE   | 3         | 0.16%   |
| en_PH   | 3         | 0.16%   |
| en_IL   | 3         | 0.16%   |
| en_IE   | 3         | 0.16%   |
| el_GR   | 3         | 0.16%   |
| da_DK   | 3         | 0.16%   |
| zh_TW   | 2         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1184      | 63.05%  |
| BIOS | 694       | 36.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 1565      | 84.78%  |
| Ext4    | 237       | 12.84%  |
| Xfs     | 27        | 1.46%   |
| Tmpfs   | 14        | 0.76%   |
| Overlay | 2         | 0.11%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1165      | 62.77%  |
| GPT     | 667       | 35.94%  |
| MBR     | 24        | 1.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1736      | 93.99%  |
| Yes       | 111       | 6.01%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1578      | 85.44%  |
| Yes       | 269       | 14.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 470       | 25.52%  |
| Hewlett-Packard        | 274       | 14.88%  |
| Dell                   | 268       | 14.55%  |
| ASUSTek Computer       | 232       | 12.6%   |
| Acer                   | 124       | 6.73%   |
| Apple                  | 110       | 5.97%   |
| HUAWEI                 | 47        | 2.55%   |
| MSI                    | 44        | 2.39%   |
| Framework              | 27        | 1.47%   |
| Samsung Electronics    | 16        | 0.87%   |
| Toshiba                | 15        | 0.81%   |
| Google                 | 14        | 0.76%   |
| Timi                   | 13        | 0.71%   |
| Gigabyte Technology    | 13        | 0.71%   |
| Fujitsu                | 12        | 0.65%   |
| Alienware              | 11        | 0.6%    |
| Unknown                | 11        | 0.6%    |
| TUXEDO                 | 8         | 0.43%   |
| Notebook               | 8         | 0.43%   |
| Sony                   | 7         | 0.38%   |
| Positivo               | 6         | 0.33%   |
| LG Electronics         | 6         | 0.33%   |
| HONOR                  | 6         | 0.33%   |
| Chuwi                  | 6         | 0.33%   |
| SLIMBOOK               | 4         | 0.22%   |
| Razer                  | 4         | 0.22%   |
| Medion                 | 4         | 0.22%   |
| Avell High Performance | 4         | 0.22%   |
| XIAOMI                 | 3         | 0.16%   |
| Star Labs              | 3         | 0.16%   |
| Schenker               | 3         | 0.16%   |
| Packard Bell           | 3         | 0.16%   |
| Juana Manso            | 3         | 0.16%   |
| GPD                    | 3         | 0.16%   |
| Valve                  | 2         | 0.11%   |
| Semp Toshiba           | 2         | 0.11%   |
| PC Specialist          | 2         | 0.11%   |
| Panasonic              | 2         | 0.11%   |
| Maibenben              | 2         | 0.11%   |
| MACHENIKE              | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 18        | 0.98%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 14        | 0.76%   |
| Apple MacBookPro14,1                       | 12        | 0.65%   |
| Apple MacBookAir7,2                        | 9         | 0.49%   |
| HP Notebook                                | 7         | 0.38%   |
| Apple MacBookPro9,2                        | 7         | 0.38%   |
| Apple MacBookPro8,1                        | 7         | 0.38%   |
| HUAWEI RLEF-XX                             | 6         | 0.33%   |
| HUAWEI BOM-WXX9                            | 6         | 0.33%   |
| Framework Laptop (12th Gen Intel Core)     | 6         | 0.33%   |
| Dell Precision M4800                       | 6         | 0.33%   |
| Apple MacBookPro11,3                       | 6         | 0.33%   |
| Apple MacBookPro11,1                       | 6         | 0.33%   |
| Lenovo ThinkBook 16 G6 IRL 21KH            | 5         | 0.27%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 5         | 0.27%   |
| HP OMEN by Laptop 16-c0xxx                 | 5         | 0.27%   |
| HP EliteBook 840 G5                        | 5         | 0.27%   |
| Dell Inspiron 15-3567                      | 5         | 0.27%   |
| ASUS Zenbook UM3402YAR_UM3402YA            | 5         | 0.27%   |
| Apple MacBookPro12,1                       | 5         | 0.27%   |
| Apple MacBookPro10,1                       | 5         | 0.27%   |
| Acer Aspire A515-57                        | 5         | 0.27%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 4         | 0.22%   |
| HUAWEI HVY-WXX9                            | 4         | 0.22%   |
| HP Pavilion Notebook                       | 4         | 0.22%   |
| HP EliteBook 840 G6                        | 4         | 0.22%   |
| HP EliteBook 840 G4                        | 4         | 0.22%   |
| Framework Laptop                           | 4         | 0.22%   |
| Dell XPS 9320                              | 4         | 0.22%   |
| Dell XPS 15 9570                           | 4         | 0.22%   |
| Dell XPS 15 9560                           | 4         | 0.22%   |
| Dell XPS 15 9530                           | 4         | 0.22%   |
| Dell XPS 13 9310                           | 4         | 0.22%   |
| Dell Latitude E6430                        | 4         | 0.22%   |
| Dell Latitude E6400                        | 4         | 0.22%   |
| Dell Inspiron 5570                         | 4         | 0.22%   |
| Apple MacBookPro8,2                        | 4         | 0.22%   |
| Apple MacBookPro11,5                       | 4         | 0.22%   |
| Apple MacBookPro11,2                       | 4         | 0.22%   |
| Apple MacBookAir6,2                        | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 249       | 13.52%  |
| Lenovo IdeaPad     | 92        | 4.99%   |
| Dell Latitude      | 92        | 4.99%   |
| Acer Aspire        | 74        | 4.02%   |
| ASUS VivoBook      | 73        | 3.96%   |
| Dell Inspiron      | 66        | 3.58%   |
| HP EliteBook       | 63        | 3.42%   |
| HP Laptop          | 55        | 2.99%   |
| Dell XPS           | 42        | 2.28%   |
| ASUS ROG           | 40        | 2.17%   |
| HP Pavilion        | 38        | 2.06%   |
| Dell Precision     | 37        | 2.01%   |
| Lenovo Legion      | 36        | 1.95%   |
| ASUS ASUS          | 36        | 1.95%   |
| HP ProBook         | 33        | 1.79%   |
| Framework Laptop   | 27        | 1.47%   |
| ASUS Zenbook       | 26        | 1.41%   |
| Acer Nitro         | 23        | 1.25%   |
| Apple MacBookPro11 | 21        | 1.14%   |
| Lenovo Yoga        | 20        | 1.09%   |
| Unknown            | 18        | 0.98%   |
| Lenovo ThinkBook   | 16        | 0.87%   |
| HP ENVY            | 14        | 0.76%   |
| Apple MacBookPro14 | 14        | 0.76%   |
| HP OMEN            | 13        | 0.71%   |
| Dell Vostro        | 13        | 0.71%   |
| Toshiba Satellite  | 12        | 0.65%   |
| HP ZBook           | 11        | 0.6%    |
| Fujitsu LIFEBOOK   | 11        | 0.6%    |
| Apple MacBookPro8  | 11        | 0.6%    |
| Acer Swift         | 11        | 0.6%    |
| Apple MacBookAir7  | 10        | 0.54%   |
| MSI Modern         | 9         | 0.49%   |
| Dell G15           | 9         | 0.49%   |
| Apple MacBookPro9  | 9         | 0.49%   |
| Lenovo V15         | 8         | 0.43%   |
| MSI Prestige       | 7         | 0.38%   |
| HP Notebook        | 7         | 0.38%   |
| HP 250             | 7         | 0.38%   |
| Lenovo LOQ         | 6         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 271       | 14.71%  |
| 2023    | 232       | 12.6%   |
| 2022    | 223       | 12.11%  |
| 2020    | 185       | 10.04%  |
| 2018    | 131       | 7.11%   |
| 2019    | 130       | 7.06%   |
| 2017    | 118       | 6.41%   |
| 2013    | 91        | 4.94%   |
| 2014    | 87        | 4.72%   |
| 2012    | 77        | 4.18%   |
| 2015    | 70        | 3.8%    |
| 2011    | 63        | 3.42%   |
| 2016    | 62        | 3.37%   |
| 2010    | 35        | 1.9%    |
| 2009    | 20        | 1.09%   |
| 2008    | 20        | 1.09%   |
| 2024    | 13        | 0.71%   |
| 2007    | 12        | 0.65%   |
| Unknown | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1842      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1513      | 81.43%  |
| Enabled  | 345       | 18.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1825      | 99.08%  |
| Yes  | 17        | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 502       | 27.18%  |
| 16.01-24.0  | 415       | 22.47%  |
| 8.01-16.0   | 401       | 21.71%  |
| 32.01-64.0  | 254       | 13.75%  |
| 3.01-4.0    | 139       | 7.53%   |
| 24.01-32.0  | 72        | 3.9%    |
| 64.01-256.0 | 43        | 2.33%   |
| 1.01-2.0    | 13        | 0.7%    |
| 2.01-3.0    | 8         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 633       | 32.63%  |
| 2.01-3.0   | 500       | 25.77%  |
| 3.01-4.0   | 459       | 23.66%  |
| 1.01-2.0   | 187       | 9.64%   |
| 8.01-16.0  | 133       | 6.86%   |
| 16.01-24.0 | 14        | 0.72%   |
| 0.51-1.0   | 7         | 0.36%   |
| 24.01-32.0 | 5         | 0.26%   |
| 32.01-64.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1411      | 76.11%  |
| 2      | 384       | 20.71%  |
| 3      | 44        | 2.37%   |
| 4      | 10        | 0.54%   |
| 0      | 2         | 0.11%   |
| 7      | 1         | 0.05%   |
| 6      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1563      | 84.81%  |
| Yes       | 280       | 15.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1276      | 69.12%  |
| No        | 570       | 30.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1786      | 96.91%  |
| No        | 57        | 3.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1614      | 87.24%  |
| No        | 236       | 12.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 297       | 16.05%  |
| Germany      | 157       | 8.49%   |
| Russia       | 133       | 7.19%   |
| Brazil       | 113       | 6.11%   |
| Italy        | 100       | 5.41%   |
| India        | 76        | 4.11%   |
| UK           | 74        | 4%      |
| Poland       | 74        | 4%      |
| France       | 65        | 3.51%   |
| Canada       | 60        | 3.24%   |
| Spain        | 44        | 2.38%   |
| Netherlands  | 33        | 1.78%   |
| Mexico       | 33        | 1.78%   |
| Turkey       | 32        | 1.73%   |
| Australia    | 31        | 1.68%   |
| Romania      | 30        | 1.62%   |
| Switzerland  | 29        | 1.57%   |
| Austria      | 22        | 1.19%   |
| Czechia      | 21        | 1.14%   |
| Portugal     | 17        | 0.92%   |
| Argentina    | 17        | 0.92%   |
| Chile        | 16        | 0.86%   |
| Sweden       | 15        | 0.81%   |
| Hungary      | 15        | 0.81%   |
| Bulgaria     | 15        | 0.81%   |
| Finland      | 14        | 0.76%   |
| Colombia     | 14        | 0.76%   |
| Belgium      | 13        | 0.7%    |
| Belarus      | 12        | 0.65%   |
| Norway       | 11        | 0.59%   |
| Denmark      | 11        | 0.59%   |
| Philippines  | 10        | 0.54%   |
| Morocco      | 10        | 0.54%   |
| Greece       | 9         | 0.49%   |
| China        | 9         | 0.49%   |
| South Africa | 8         | 0.43%   |
| Slovakia     | 8         | 0.43%   |
| Indonesia    | 8         | 0.43%   |
| Croatia      | 8         | 0.43%   |
| Uzbekistan   | 7         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 33        | 1.74%   |
| St Petersburg | 25        | 1.32%   |
| Berlin        | 17        | 0.9%    |
| Vienna        | 15        | 0.79%   |
| Paris         | 14        | 0.74%   |
| Warsaw        | 13        | 0.69%   |
| Milan         | 13        | 0.69%   |
| Munich        | 12        | 0.63%   |
| Istanbul      | 12        | 0.63%   |
| Bengaluru     | 12        | 0.63%   |
| Helsinki      | 11        | 0.58%   |
| Seattle       | 10        | 0.53%   |
| Montreal      | 10        | 0.53%   |
| Zurich        | 9         | 0.48%   |
| Yekaterinburg | 9         | 0.48%   |
| Toronto       | 9         | 0.48%   |
| Sydney        | 9         | 0.48%   |
| Sao Paulo     | 9         | 0.48%   |
| Santiago      | 9         | 0.48%   |
| Minsk         | 9         | 0.48%   |
| Bucharest     | 9         | 0.48%   |
| Madrid        | 8         | 0.42%   |
| Los Angeles   | 8         | 0.42%   |
| Delhi         | 8         | 0.42%   |
| Chennai       | 8         | 0.42%   |
| Amsterdam     | 8         | 0.42%   |
| Tashkent      | 7         | 0.37%   |
| Stuttgart     | 7         | 0.37%   |
| Sofia         | 7         | 0.37%   |
| Perm          | 7         | 0.37%   |
| London        | 7         | 0.37%   |
| Budapest      | 7         | 0.37%   |
| Prague        | 6         | 0.32%   |
| Poznan        | 6         | 0.32%   |
| Nuremberg     | 6         | 0.32%   |
| Hamburg       | 6         | 0.32%   |
| Barcelona     | 6         | 0.32%   |
| Wroclaw       | 5         | 0.26%   |
| Sanford       | 5         | 0.26%   |
| Rome          | 5         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 430       | 513    | 19.25%  |
| Sandisk                      | 254       | 278    | 11.37%  |
| SK hynix                     | 148       | 163    | 6.62%   |
| Micron Technology            | 129       | 136    | 5.77%   |
| WDC                          | 109       | 119    | 4.88%   |
| Seagate                      | 107       | 121    | 4.79%   |
| Unknown                      | 97        | 116    | 4.34%   |
| Intel                        | 96        | 118    | 4.3%    |
| Kingston                     | 95        | 104    | 4.25%   |
| Toshiba                      | 75        | 83     | 3.36%   |
| Apple                        | 67        | 93     | 3%      |
| KIOXIA                       | 53        | 60     | 2.37%   |
| Micron/Crucial Technology    | 47        | 54     | 2.1%    |
| Phison Electronics           | 46        | 52     | 2.06%   |
| Crucial                      | 44        | 48     | 1.97%   |
| Kingston Technology Company  | 31        | 33     | 1.39%   |
| A-DATA Technology            | 31        | 32     | 1.39%   |
| Silicon Motion               | 27        | 29     | 1.21%   |
| HGST                         | 26        | 28     | 1.16%   |
| MAXIO Technology (Hangzhou)  | 19        | 22     | 0.85%   |
| China                        | 17        | 17     | 0.76%   |
| ADATA Technology             | 17        | 18     | 0.76%   |
| Hitachi                      | 14        | 15     | 0.63%   |
| SPCC                         | 10        | 12     | 0.45%   |
| Shenzhen Longsys Electronics | 9         | 10     | 0.4%    |
| PNY                          | 9         | 11     | 0.4%    |
| Union Memory (Shenzhen)      | 8         | 8      | 0.36%   |
| Solid State Storage          | 8         | 9      | 0.36%   |
| LITEONIT                     | 8         | 8      | 0.36%   |
| LITEON                       | 8         | 9      | 0.36%   |
| Lexar                        | 8         | 9      | 0.36%   |
| Gigabyte Technology          | 8         | 8      | 0.36%   |
| Union Memory                 | 7         | 9      | 0.31%   |
| Transcend                    | 7         | 8      | 0.31%   |
| Realtek Semiconductor        | 7         | 7      | 0.31%   |
| Netac                        | 7         | 10     | 0.31%   |
| Lenovo                       | 7         | 9      | 0.31%   |
| GOODRAM                      | 7         | 8      | 0.31%   |
| Unknown                      | 7         | 7      | 0.31%   |
| Patriot                      | 6         | 6      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 102       | 4.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 84        | 3.66%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 39        | 1.7%    |
| Intel SSDPEKNU512GZ 512GB                             | 34        | 1.48%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 33        | 1.44%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 31        | 1.35%   |
| Unknown MMC Card  32GB                                | 25        | 1.09%   |
| Kingston SA400S37240G 240GB SSD                       | 25        | 1.09%   |
| Unknown MMC Card  128GB                               | 20        | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                        | 18        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 17        | 0.74%   |
| Intel SSD 660P Series 1024GB                          | 16        | 0.7%    |
| Unknown MMC Card  64GB                                | 15        | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 15        | 0.65%   |
| Phison E12 NVMe Controller 480GB                      | 15        | 0.65%   |
| Samsung SSD 860 EVO 500GB                             | 14        | 0.61%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 14        | 0.61%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 14        | 0.61%   |
| Apple S3X NVMe Controller 500GB                       | 14        | 0.61%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 13        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 12        | 0.52%   |
| Sandisk WD Black SN850 2TB                            | 12        | 0.52%   |
| Sandisk WD_BLACK SN770 1TB                            | 11        | 0.48%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 11        | 0.48%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 11        | 0.48%   |
| HGST HTS721010A9E630 1TB                              | 11        | 0.48%   |
| Toshiba MQ04ABF100 1TB                                | 10        | 0.44%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB       | 10        | 0.44%   |
| Unknown NVMe SSD Drive 512GB                          | 9         | 0.39%   |
| SK hynix HFM512GD3JX013N 512GB                        | 9         | 0.39%   |
| SK hynix BC511 512GB                                  | 9         | 0.39%   |
| Samsung SSD 980 1TB                                   | 9         | 0.39%   |
| Samsung MZALQ512HBLU-00BL2 512GB                      | 9         | 0.39%   |
| Micron 2400_MTFDKBA1T0QFM 1TB                         | 9         | 0.39%   |
| Kingston SA400S37480G 480GB SSD                       | 9         | 0.39%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 512GB         | 9         | 0.39%   |
| Unknown MMC Card  16GB                                | 8         | 0.35%   |
| SK hynix SKHynix_HFS001TEJ9X162N 1TB                  | 8         | 0.35%   |
| Silicon Motion PCIe-8 SSD 512GB                       | 8         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB                       | 8         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 97        | 108    | 34.77%  |
| WDC                 | 80        | 84     | 28.67%  |
| Toshiba             | 37        | 41     | 13.26%  |
| HGST                | 26        | 28     | 9.32%   |
| Hitachi             | 14        | 15     | 5.02%   |
| Unknown             | 5         | 5      | 1.79%   |
| Samsung Electronics | 4         | 5      | 1.43%   |
| JMicron Technology  | 3         | 5      | 1.08%   |
| Fujitsu             | 2         | 2      | 0.72%   |
| External            | 2         | 3      | 0.72%   |
| Apple               | 2         | 2      | 0.72%   |
| USB3.0              | 1         | 1      | 0.36%   |
| USB                 | 1         | 1      | 0.36%   |
| SABRENT             | 1         | 1      | 0.36%   |
| HGST HTS            | 1         | 1      | 0.36%   |
| ASMT                | 1         | 2      | 0.36%   |
| ASMedia             | 1         | 1      | 0.36%   |
| Asm                 | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 115       | 132    | 19.69%  |
| Kingston            | 65        | 70     | 11.13%  |
| SanDisk             | 47        | 53     | 8.05%   |
| Crucial             | 44        | 48     | 7.53%   |
| Apple               | 42        | 43     | 7.19%   |
| WDC                 | 30        | 34     | 5.14%   |
| A-DATA Technology   | 21        | 21     | 3.6%    |
| Micron Technology   | 19        | 20     | 3.25%   |
| SK hynix            | 17        | 18     | 2.91%   |
| China               | 17        | 17     | 2.91%   |
| Intel               | 15        | 20     | 2.57%   |
| SPCC                | 10        | 12     | 1.71%   |
| Toshiba             | 9         | 9      | 1.54%   |
| PNY                 | 9         | 11     | 1.54%   |
| LITEONIT            | 8         | 8      | 1.37%   |
| LITEON              | 8         | 9      | 1.37%   |
| Lexar               | 8         | 9      | 1.37%   |
| GOODRAM             | 7         | 8      | 1.2%    |
| Gigabyte Technology | 7         | 7      | 1.2%    |
| Transcend           | 6         | 7      | 1.03%   |
| Netac               | 6         | 9      | 1.03%   |
| Patriot             | 5         | 5      | 0.86%   |
| KingSpec            | 4         | 5      | 0.68%   |
| Intenso             | 4         | 5      | 0.68%   |
| Hewlett-Packard     | 4         | 4      | 0.68%   |
| Team                | 3         | 3      | 0.51%   |
| Plextor             | 3         | 7      | 0.51%   |
| Unknown             | 3         | 3      | 0.51%   |
| Seagate             | 2         | 2      | 0.34%   |
| OCZ                 | 2         | 5      | 0.34%   |
| Lenovo              | 2         | 2      | 0.34%   |
| KingFast            | 2         | 2      | 0.34%   |
| KingDian            | 2         | 2      | 0.34%   |
| HS-SSD-E100         | 2         | 2      | 0.34%   |
| BIWIN               | 2         | 2      | 0.34%   |
| Apacer              | 2         | 2      | 0.34%   |
| AMD                 | 2         | 2      | 0.34%   |
| XrayDisk            | 1         | 1      | 0.17%   |
| Win Memory          | 1         | 1      | 0.17%   |
| Wdxsky              | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1180      | 1459   | 55.92%  |
| SSD     | 552       | 655    | 26.16%  |
| HDD     | 270       | 306    | 12.8%   |
| MMC     | 76        | 93     | 3.6%    |
| Unknown | 32        | 38     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1179      | 1452   | 57.32%  |
| SATA | 724       | 913    | 35.2%   |
| SAS  | 78        | 93     | 3.79%   |
| MMC  | 76        | 93     | 3.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 518       | 620    | 63.95%  |
| 0.51-1.0   | 259       | 305    | 31.98%  |
| 1.01-2.0   | 25        | 27     | 3.09%   |
| 4.01-10.0  | 4         | 4      | 0.49%   |
| 3.01-4.0   | 3         | 4      | 0.37%   |
| 10.01-20.0 | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 455       | 24.32%  |
| 251-500        | 390       | 20.84%  |
| 1001-2000      | 277       | 14.8%   |
| 101-250        | 243       | 12.99%  |
| Unknown        | 169       | 9.03%   |
| 1-20           | 163       | 8.71%   |
| 51-100         | 58        | 3.1%    |
| More than 3000 | 51        | 2.73%   |
| 2001-3000      | 44        | 2.35%   |
| 21-50          | 21        | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 632       | 33.11%  |
| 21-50          | 358       | 18.75%  |
| 101-250        | 246       | 12.89%  |
| 51-100         | 194       | 10.16%  |
| Unknown        | 169       | 8.85%   |
| 251-500        | 165       | 8.64%   |
| 501-1000       | 94        | 4.92%   |
| 1001-2000      | 38        | 1.99%   |
| 2001-3000      | 7         | 0.37%   |
| More than 3000 | 6         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 2         | 2      | 7.14%   |
| Crucial CT128MX100SSD1 128GB                   | 2         | 2      | 7.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 3.57%   |
| WDC WD5000BPVT-22HXZT1 500GB                   | 1         | 1      | 3.57%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 1      | 3.57%   |
| WDC WD Green 2.5 480GB SSD                     | 1         | 1      | 3.57%   |
| WDC WD Blue SA510 2.5 500GB                    | 1         | 1      | 3.57%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD       | 1         | 1      | 3.57%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.57%   |
| Toshiba MK5056GSYF 500GB                       | 1         | 1      | 3.57%   |
| SK hynix BC711 HFM512GD3JX013N 512GB           | 1         | 1      | 3.57%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 3.57%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 1         | 1      | 3.57%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 3.57%   |
| Seagate ST1000LM049-2GH172 1TB                 | 1         | 1      | 3.57%   |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 840 EVO 250GB          | 1         | 1      | 3.57%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 3.57%   |
| Intel SSD 600P Series 256GB                    | 1         | 1      | 3.57%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 3.57%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 3.57%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 3.57%   |
| Fujitsu MHZ2080BJ FFS G2 80GB                  | 1         | 1      | 3.57%   |
| Crucial CT1000MX500SSD1 1TB                    | 1         | 1      | 3.57%   |
| China G521N256GB                               | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| WDC                 | 5         | 5      | 17.86%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Crucial             | 3         | 3      | 10.71%  |
| HGST                | 2         | 2      | 7.14%   |
| SK hynix            | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 50%     |
| WDC     | 2         | 2      | 12.5%   |
| Toshiba | 2         | 2      | 12.5%   |
| HGST    | 2         | 2      | 12.5%   |
| Hitachi | 1         | 1      | 6.25%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 57.14%  |
| SSD  | 10        | 10     | 35.71%  |
| NVMe | 2         | 2      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Sandisk PC SN520 NVMe SSD 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Sandisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1249      | 1746   | 66.22%  |
| Works    | 608       | 776    | 32.24%  |
| Malfunc  | 28        | 28     | 1.48%   |
| Failed   | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 981       | 41.62%  |
| Samsung Electronics                     | 344       | 14.59%  |
| SanDisk                                 | 207       | 8.78%   |
| AMD                                     | 146       | 6.19%   |
| SK hynix                                | 131       | 5.56%   |
| Micron Technology                       | 110       | 4.67%   |
| Kingston Technology Company             | 61        | 2.59%   |
| KIOXIA                                  | 53        | 2.25%   |
| Phison Electronics                      | 48        | 2.04%   |
| Micron/Crucial Technology               | 47        | 1.99%   |
| Toshiba America Info Systems            | 30        | 1.27%   |
| Silicon Motion                          | 27        | 1.15%   |
| ADATA Technology                        | 27        | 1.15%   |
| Apple                                   | 21        | 0.89%   |
| MAXIO Technology (Hangzhou)             | 20        | 0.85%   |
| Solid State Storage Technology          | 13        | 0.55%   |
| Solidigm                                | 10        | 0.42%   |
| Union Memory (Shenzhen)                 | 9         | 0.38%   |
| Shenzhen Longsys Electronics            | 9         | 0.38%   |
| Nvidia                                  | 9         | 0.38%   |
| Seagate Technology                      | 7         | 0.3%    |
| Realtek Semiconductor                   | 7         | 0.3%    |
| Shenzhen Unionmemory Information System | 6         | 0.25%   |
| Marvell Technology Group                | 6         | 0.25%   |
| INNOGRIT                                | 6         | 0.25%   |
| Lenovo                                  | 5         | 0.21%   |
| Yangtze Memory Technologies             | 4         | 0.17%   |
| Transcend                               | 2         | 0.08%   |
| Lite-On Technology                      | 2         | 0.08%   |
| Hosin Global Electronics                | 2         | 0.08%   |
| ASMedia Technology                      | 2         | 0.08%   |
| Netac Technology                        | 1         | 0.04%   |
| JMicron Technology                      | 1         | 0.04%   |
| Biwin Storage Technology                | 1         | 0.04%   |
| Beijing Starblaze Technology            | 1         | 0.04%   |
| Unknown                                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 134       | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 134       | 5.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 125       | 5.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 104       | 4.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 97        | 3.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 84        | 3.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 77        | 3.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 68        | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 58        | 2.34%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 48        | 1.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 45        | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 45        | 1.82%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 43        | 1.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 42        | 1.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 42        | 1.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 39        | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 35        | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 34        | 1.37%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 33        | 1.33%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 33        | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 32        | 1.29%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 31        | 1.25%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 29        | 1.17%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 29        | 1.17%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 27        | 1.09%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 23        | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.93%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 22        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 22        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 21        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.85%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 19        | 0.77%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 18        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 17        | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 17        | 0.69%   |
| Intel SSD 660P Series                                                          | 16        | 0.65%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 15        | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 15        | 0.61%   |
| Phison E12 NVMe Controller                                                     | 15        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 1174      | 49.85%  |
| SATA | 890       | 37.79%  |
| RAID | 267       | 11.34%  |
| IDE  | 24        | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1399      | 75.95%  |
| AMD     | 441       | 23.94%  |
| Unknown | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 29        | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 1.52%   |
| Intel 12th Gen Core i7-12700H                 | 26        | 1.41%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 25        | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 1.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 1.25%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 22        | 1.19%   |
| Intel 12th Gen Core i5-1235U                  | 19        | 1.03%   |
| Intel 12th Gen Core i5-12450H                 | 18        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 17        | 0.92%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 16        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.87%   |
| Intel 13th Gen Core i7-13700H                 | 16        | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 16        | 0.87%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 16        | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 16        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 15        | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 0.81%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 14        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.76%   |
| Intel 12th Gen Core i7-1260P                  | 14        | 0.76%   |
| AMD Ryzen 7 PRO 7840U w/ Radeon 780M Graphics | 14        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 13        | 0.71%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 13        | 0.71%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics    | 13        | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.65%   |
| Intel 13th Gen Core i7-1355U                  | 12        | 0.65%   |
| Intel 12th Gen Core i5-1240P                  | 12        | 0.65%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics     | 12        | 0.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 0.65%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 11        | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 428       | 23.24%  |
| Intel Core i5           | 378       | 20.52%  |
| Intel Core i7           | 351       | 19.06%  |
| AMD Ryzen 7             | 159       | 8.63%   |
| AMD Ryzen 5             | 123       | 6.68%   |
| Intel Core i3           | 94        | 5.1%    |
| Intel Celeron           | 56        | 3.04%   |
| AMD Ryzen 7 PRO         | 39        | 2.12%   |
| AMD Ryzen 9             | 37        | 2.01%   |
| Intel Core 2 Duo        | 30        | 1.63%   |
| AMD Ryzen 3             | 25        | 1.36%   |
| Intel Pentium           | 19        | 1.03%   |
| AMD Ryzen 5 PRO         | 16        | 0.87%   |
| Intel Atom              | 12        | 0.65%   |
| AMD A6                  | 10        | 0.54%   |
| Intel Xeon              | 8         | 0.43%   |
| Intel Core i9           | 7         | 0.38%   |
| Intel Core              | 6         | 0.33%   |
| Intel Core m3           | 5         | 0.27%   |
| AMD A8                  | 5         | 0.27%   |
| Intel Pentium Silver    | 4         | 0.22%   |
| Intel Pentium Dual-Core | 3         | 0.16%   |
| Intel Core m5           | 3         | 0.16%   |
| AMD E                   | 3         | 0.16%   |
| AMD Athlon II           | 3         | 0.16%   |
| AMD Athlon              | 3         | 0.16%   |
| AMD A4                  | 3         | 0.16%   |
| Intel Pentium Dual      | 2         | 0.11%   |
| Intel Core M            | 2         | 0.11%   |
| AMD A10                 | 2         | 0.11%   |
| Intel Core m7           | 1         | 0.05%   |
| AMD Turion 64 X2 Mobile | 1         | 0.05%   |
| AMD Ryzen 3 PRO         | 1         | 0.05%   |
| AMD E2                  | 1         | 0.05%   |
| AMD E1                  | 1         | 0.05%   |
| AMD Athlon II Neo       | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 575       | 31.22%  |
| 2      | 558       | 30.29%  |
| 8      | 279       | 15.15%  |
| 6      | 195       | 10.59%  |
| 14     | 76        | 4.13%   |
| 10     | 74        | 4.02%   |
| 12     | 60        | 3.26%   |
| 24     | 16        | 0.87%   |
| 16     | 7         | 0.38%   |
| 20     | 1         | 0.05%   |
| 1      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1842      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1641      | 89.09%  |
| 1      | 201       | 10.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1840      | 99.89%  |
| 64-bit         | 2         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1613      | 86.77%  |
| 0x0a704103 | 29        | 1.56%   |
| 0x0a50000d | 28        | 1.51%   |
| 0x0a404102 | 27        | 1.45%   |
| 0x08608103 | 22        | 1.18%   |
| 0x0a50000c | 21        | 1.13%   |
| 0x08600106 | 19        | 1.02%   |
| 0x08108109 | 13        | 0.7%    |
| 0x08608102 | 6         | 0.32%   |
| 0x08600109 | 6         | 0.32%   |
| 0x08600103 | 6         | 0.32%   |
| 0x08608104 | 5         | 0.27%   |
| 0x08600104 | 5         | 0.27%   |
| 0x06006705 | 5         | 0.27%   |
| 0x0a704104 | 4         | 0.22%   |
| 0x0a704101 | 4         | 0.22%   |
| 0x0a404101 | 4         | 0.22%   |
| 0x08a00008 | 4         | 0.22%   |
| 0x0a50000f | 3         | 0.16%   |
| 0x08a00006 | 3         | 0.16%   |
| 0x08108102 | 3         | 0.16%   |
| 0x0810100b | 3         | 0.16%   |
| 0x07030105 | 3         | 0.16%   |
| 0x0700010f | 3         | 0.16%   |
| 0x06006704 | 3         | 0.16%   |
| 0x010000c8 | 3         | 0.16%   |
| 0x0a601203 | 2         | 0.11%   |
| 0x0a20120a | 2         | 0.11%   |
| 0x08200103 | 2         | 0.11%   |
| 0x08101016 | 2         | 0.11%   |
| 0x206a7    | 1         | 0.05%   |
| 0x0a50000b | 1         | 0.05%   |
| 0x08900201 | 1         | 0.05%   |
| 0x06006110 | 1         | 0.05%   |
| 0x05000119 | 1         | 0.05%   |
| 0x03000027 | 1         | 0.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 342       | 18.48%  |
| Unknown           | 271       | 14.64%  |
| Alderlake Hybrid  | 197       | 10.64%  |
| TigerLake         | 132       | 7.13%   |
| Haswell           | 117       | 6.32%   |
| Zen 3             | 111       | 6%      |
| Skylake           | 83        | 4.48%   |
| IvyBridge         | 75        | 4.05%   |
| SandyBridge       | 68        | 3.67%   |
| Zen 2             | 61        | 3.3%    |
| Broadwell         | 60        | 3.24%   |
| IceLake           | 53        | 2.86%   |
| CometLake         | 48        | 2.59%   |
| Zen+              | 38        | 2.05%   |
| Westmere          | 37        | 2%      |
| Silvermont        | 31        | 1.67%   |
| Penryn            | 30        | 1.62%   |
| Goldmont plus     | 27        | 1.46%   |
| Zen               | 12        | 0.65%   |
| Excavator         | 10        | 0.54%   |
| Puma              | 7         | 0.38%   |
| Nehalem           | 5         | 0.27%   |
| Jaguar            | 5         | 0.27%   |
| Core              | 5         | 0.27%   |
| Meteorlake Hybrid | 4         | 0.22%   |
| K10               | 4         | 0.22%   |
| Gracemont         | 4         | 0.22%   |
| Goldmont          | 4         | 0.22%   |
| Bobcat            | 4         | 0.22%   |
| Tremont           | 2         | 0.11%   |
| Piledriver        | 2         | 0.11%   |
| K8 Hammer         | 1         | 0.05%   |
| K10 Llano         | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 1325      | 54.89%  |
| Nvidia         | 584       | 24.19%  |
| AMD            | 504       | 20.88%  |
| Silicon Motion | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 115       | 4.7%    |
| Intel UHD Graphics 620                                                                | 84        | 3.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 77        | 3.15%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 73        | 2.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 71        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 63        | 2.57%   |
| AMD Phoenix1                                                                          | 63        | 2.57%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 59        | 2.41%   |
| Intel HD Graphics 620                                                                 | 59        | 2.41%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 59        | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 58        | 2.37%   |
| AMD Rembrandt [Radeon 680M]                                                           | 53        | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 52        | 2.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 50        | 2.04%   |
| AMD Lucienne                                                                          | 48        | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 44        | 1.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 41        | 1.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 41        | 1.67%   |
| Intel HD Graphics 5500                                                                | 41        | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 41        | 1.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 41        | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 40        | 1.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 40        | 1.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 35        | 1.43%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 29        | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                                   | 29        | 1.18%   |
| AMD Barcelo                                                                           | 29        | 1.18%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 27        | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 24        | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 24        | 0.98%   |
| Intel HD Graphics 630                                                                 | 23        | 0.94%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                 | 23        | 0.94%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 21        | 0.86%   |
| Intel Raptor Lake-S UHD Graphics                                                      | 18        | 0.74%   |
| Intel HD Graphics 530                                                                 | 18        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 18        | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 17        | 0.69%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 16        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 0.61%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                       | 15        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 850       | 46.05%  |
| Intel + Nvidia     | 411       | 22.26%  |
| 1 x AMD            | 323       | 17.5%   |
| AMD + Nvidia       | 102       | 5.53%   |
| 1 x Nvidia         | 68        | 3.68%   |
| Intel + AMD        | 57        | 3.09%   |
| 2 x AMD            | 24        | 1.3%    |
| Other              | 5         | 0.27%   |
| 2 x Intel          | 3         | 0.16%   |
| 2 x Nvidia         | 2         | 0.11%   |
| 1 x Silicon Motion | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1560      | 84.19%  |
| Proprietary | 231       | 12.47%  |
| Unknown     | 62        | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1319      | 70.5%   |
| 0.01-0.5   | 187       | 9.99%   |
| 1.01-2.0   | 125       | 6.68%   |
| 3.01-4.0   | 94        | 5.02%   |
| 0.51-1.0   | 70        | 3.74%   |
| 7.01-8.0   | 34        | 1.82%   |
| 5.01-6.0   | 24        | 1.28%   |
| 8.01-16.0  | 10        | 0.53%   |
| 2.01-3.0   | 7         | 0.37%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 386       | 17.9%   |
| AU Optronics            | 357       | 16.56%  |
| Chimei Innolux          | 290       | 13.45%  |
| LG Display              | 223       | 10.34%  |
| Samsung Electronics     | 202       | 9.37%   |
| Apple                   | 106       | 4.92%   |
| Dell                    | 64        | 2.97%   |
| Sharp                   | 57        | 2.64%   |
| CSO                     | 55        | 2.55%   |
| Goldstar                | 49        | 2.27%   |
| Lenovo                  | 43        | 1.99%   |
| PANDA                   | 39        | 1.81%   |
| Hewlett-Packard         | 27        | 1.25%   |
| InfoVision              | 22        | 1.02%   |
| Philips                 | 21        | 0.97%   |
| AOC                     | 21        | 0.97%   |
| Acer                    | 18        | 0.83%   |
| TMX                     | 17        | 0.79%   |
| Chi Mei Optoelectronics | 17        | 0.79%   |
| Iiyama                  | 12        | 0.56%   |
| ASUSTek Computer        | 12        | 0.56%   |
| ViewSonic               | 9         | 0.42%   |
| Sony                    | 9         | 0.42%   |
| BenQ                    | 8         | 0.37%   |
| Gigabyte Technology     | 7         | 0.32%   |
| MSI                     | 6         | 0.28%   |
| HKC                     | 5         | 0.23%   |
| Ancor Communications    | 5         | 0.23%   |
| KDB                     | 4         | 0.19%   |
| CTO                     | 4         | 0.19%   |
| TMA                     | 3         | 0.14%   |
| STA                     | 3         | 0.14%   |
| Mi                      | 3         | 0.14%   |
| KDC                     | 3         | 0.14%   |
| Valve                   | 2         | 0.09%   |
| NEC Computers           | 2         | 0.09%   |
| LG Philips              | 2         | 0.09%   |
| JDI                     | 2         | 0.09%   |
| InnoLux Display         | 2         | 0.09%   |
| HUAWEI                  | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 16        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 14        | 0.64%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 14        | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 13        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 13        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 13        | 0.6%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 12        | 0.55%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                 | 12        | 0.55%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 10        | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 10        | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 10        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 9         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 9         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 9         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 8         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 7         | 0.32%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 7         | 0.32%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 7         | 0.32%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 6         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 6         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 6         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 6         | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 6         | 0.28%   |
| BOE LCD Monitor BOE0A74 1920x1200 345x215mm 16.0-inch                 | 6         | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 6         | 0.28%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                 | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.28%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 6         | 0.28%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 5         | 0.23%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 5         | 0.23%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 5         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 5         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 930       | 45.7%   |
| 1366x768 (WXGA)    | 328       | 16.12%  |
| 1920x1200 (WUXGA)  | 112       | 5.5%    |
| 3840x2160 (4K)     | 104       | 5.11%   |
| 2560x1440 (QHD)    | 100       | 4.91%   |
| 2880x1800          | 86        | 4.23%   |
| 2560x1600          | 81        | 3.98%   |
| 1600x900 (HD+)     | 53        | 2.6%    |
| 1440x900 (WXGA+)   | 34        | 1.67%   |
| 1280x800 (WXGA)    | 33        | 1.62%   |
| 2256x1504          | 26        | 1.28%   |
| 3440x1440          | 16        | 0.79%   |
| 3840x2400          | 15        | 0.74%   |
| 2560x1080          | 14        | 0.69%   |
| 3200x2000          | 12        | 0.59%   |
| 2160x1440          | 12        | 0.59%   |
| 3456x2160          | 9         | 0.44%   |
| 2880x1620          | 8         | 0.39%   |
| 1680x1050 (WSXGA+) | 8         | 0.39%   |
| 3072x1920          | 7         | 0.34%   |
| 3200x1800 (QHD+)   | 4         | 0.2%    |
| 2520x1680          | 4         | 0.2%    |
| 2240x1400          | 4         | 0.2%    |
| 3120x2080          | 3         | 0.15%   |
| 2304x1440          | 3         | 0.15%   |
| 1920x1280          | 3         | 0.15%   |
| 1280x1024 (SXGA)   | 3         | 0.15%   |
| 800x1280           | 2         | 0.1%    |
| 3840x1100          | 2         | 0.1%    |
| 3840x1080          | 2         | 0.1%    |
| 3000x2000          | 2         | 0.1%    |
| 2160x1350          | 2         | 0.1%    |
| 1400x1050          | 2         | 0.1%    |
| Unknown            | 2         | 0.1%    |
| 3840x1600          | 1         | 0.05%   |
| 2880x864           | 1         | 0.05%   |
| 2160x1200          | 1         | 0.05%   |
| 2048x1152          | 1         | 0.05%   |
| 1920x540           | 1         | 0.05%   |
| 1920x515           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 807       | 37.38%  |
| 13      | 331       | 15.33%  |
| 14      | 317       | 14.68%  |
| 16      | 130       | 6.02%   |
| 27      | 101       | 4.68%   |
| 17      | 100       | 4.63%   |
| 24      | 75        | 3.47%   |
| 23      | 50        | 2.32%   |
| 12      | 41        | 1.9%    |
| 21      | 31        | 1.44%   |
| 34      | 29        | 1.34%   |
| 31      | 26        | 1.2%    |
| 11      | 22        | 1.02%   |
| 18      | 10        | 0.46%   |
| 26      | 9         | 0.42%   |
| 84      | 8         | 0.37%   |
| Unknown | 8         | 0.37%   |
| 40      | 7         | 0.32%   |
| 20      | 7         | 0.32%   |
| 22      | 6         | 0.28%   |
| 19      | 6         | 0.28%   |
| 72      | 4         | 0.19%   |
| 54      | 4         | 0.19%   |
| 32      | 4         | 0.19%   |
| 38      | 2         | 0.09%   |
| 33      | 2         | 0.09%   |
| 29      | 2         | 0.09%   |
| 7       | 2         | 0.09%   |
| 85      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 47      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 44      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1356      | 63.6%   |
| 201-300     | 258       | 12.1%   |
| 501-600     | 204       | 9.57%   |
| 351-400     | 134       | 6.29%   |
| 401-500     | 56        | 2.63%   |
| 601-700     | 39        | 1.83%   |
| 701-800     | 35        | 1.64%   |
| 1501-2000   | 13        | 0.61%   |
| 1001-1500   | 13        | 0.61%   |
| 801-900     | 9         | 0.42%   |
| Unknown     | 8         | 0.38%   |
| 901-1000    | 3         | 0.14%   |
| 101-200     | 2         | 0.09%   |
| 1-100       | 2         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1391      | 73.17%  |
| 16/10   | 403       | 21.2%   |
| 3/2     | 54        | 2.84%   |
| 21/9    | 31        | 1.63%   |
| 4/3     | 5         | 0.26%   |
| Unknown | 4         | 0.21%   |
| 5/4     | 3         | 0.16%   |
| 32/9    | 3         | 0.16%   |
| 3.40    | 2         | 0.11%   |
| 0.67    | 2         | 0.11%   |
| 3.73    | 1         | 0.05%   |
| 3.33    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 819       | 38.08%  |
| 81-90          | 529       | 24.59%  |
| 201-250        | 131       | 6.09%   |
| 111-120        | 115       | 5.35%   |
| 301-350        | 109       | 5.07%   |
| 71-80          | 101       | 4.7%    |
| 121-130        | 90        | 4.18%   |
| 351-500        | 62        | 2.88%   |
| 61-70          | 38        | 1.77%   |
| 51-60          | 24        | 1.12%   |
| 251-300        | 22        | 1.02%   |
| 91-100         | 22        | 1.02%   |
| More than 1000 | 21        | 0.98%   |
| 151-200        | 18        | 0.84%   |
| 501-1000       | 18        | 0.84%   |
| 141-150        | 10        | 0.46%   |
| 131-140        | 9         | 0.42%   |
| Unknown        | 8         | 0.37%   |
| 1-40           | 4         | 0.19%   |
| 41-50          | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 956       | 45.09%  |
| 101-120       | 412       | 19.43%  |
| 161-240       | 339       | 15.99%  |
| 51-100        | 253       | 11.93%  |
| More than 240 | 138       | 6.51%   |
| 1-50          | 14        | 0.66%   |
| Unknown       | 8         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1461      | 78.46%  |
| 2     | 306       | 16.43%  |
| 0     | 49        | 2.63%   |
| 3     | 38        | 2.04%   |
| 4     | 8         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1003      | 36.07%  |
| Realtek Semiconductor             | 923       | 33.19%  |
| Qualcomm Atheros                  | 200       | 7.19%   |
| MediaTek                          | 173       | 6.22%   |
| Broadcom                          | 170       | 6.11%   |
| Broadcom Limited                  | 43        | 1.55%   |
| ASIX Electronics                  | 39        | 1.4%    |
| Qualcomm                          | 38        | 1.37%   |
| TP-Link                           | 18        | 0.65%   |
| Lenovo                            | 14        | 0.5%    |
| Ralink Technology                 | 13        | 0.47%   |
| Dell                              | 13        | 0.47%   |
| Ralink                            | 11        | 0.4%    |
| Sierra Wireless                   | 10        | 0.36%   |
| Samsung Electronics               | 8         | 0.29%   |
| Marvell Technology Group          | 8         | 0.29%   |
| Xiaomi                            | 7         | 0.25%   |
| Nvidia                            | 7         | 0.25%   |
| DisplayLink                       | 7         | 0.25%   |
| OPPO Electronics                  | 6         | 0.22%   |
| Hewlett-Packard                   | 6         | 0.22%   |
| Motorola PCS                      | 5         | 0.18%   |
| Fibocom                           | 4         | 0.14%   |
| D-Link                            | 4         | 0.14%   |
| ASUSTek Computer                  | 4         | 0.14%   |
| Apple                             | 4         | 0.14%   |
| Qualcomm Technologies             | 3         | 0.11%   |
| NetGear                           | 3         | 0.11%   |
| Google                            | 3         | 0.11%   |
| Ericsson Business Mobile Networks | 3         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.07%   |
| QinHeng Electronics               | 2         | 0.07%   |
| JMicron Technology                | 2         | 0.07%   |
| Huawei Technologies               | 2         | 0.07%   |
| Edimax Technology                 | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Bose                              | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| Unknown                           | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 530       | 16.1%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 115       | 3.49%   |
| Intel Wi-Fi 6 AX201                                                    | 92        | 2.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 89        | 2.7%    |
| Intel Wireless 8265 / 8275                                             | 89        | 2.7%    |
| Intel Wi-Fi 6 AX200                                                    | 87        | 2.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 85        | 2.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 85        | 2.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 79        | 2.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 67        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 63        | 1.91%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 52        | 1.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 51        | 1.55%   |
| Intel Wireless 7265                                                    | 47        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 46        | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                                  | 44        | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 41        | 1.25%   |
| Intel Wireless 8260                                                    | 41        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 38        | 1.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 37        | 1.12%   |
| Intel Wireless 7260                                                    | 37        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                      | 33        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 33        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                          | 33        | 1%      |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 31        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 31        | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 30        | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 29        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                          | 29        | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 0.82%   |
| Intel Wireless 3165                                                    | 24        | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                   | 23        | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 22        | 0.67%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 22        | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 22        | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 22        | 0.67%   |
| Realtek Killer E2600 GbE Controller                                    | 21        | 0.64%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 21        | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 20        | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 19        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 962       | 51.2%   |
| Realtek Semiconductor                 | 286       | 15.22%  |
| Qualcomm Atheros                      | 168       | 8.94%   |
| MediaTek                              | 152       | 8.09%   |
| Broadcom                              | 147       | 7.82%   |
| Broadcom Limited                      | 42        | 2.24%   |
| Qualcomm                              | 35        | 1.86%   |
| TP-Link                               | 14        | 0.75%   |
| Ralink Technology                     | 13        | 0.69%   |
| Ralink                                | 11        | 0.59%   |
| Sierra Wireless                       | 10        | 0.53%   |
| Dell                                  | 10        | 0.53%   |
| Fibocom                               | 4         | 0.21%   |
| D-Link                                | 4         | 0.21%   |
| ASUSTek Computer                      | 4         | 0.21%   |
| Qualcomm Technologies                 | 3         | 0.16%   |
| NetGear                               | 3         | 0.16%   |
| Qualcomm Atheros Communications       | 2         | 0.11%   |
| Edimax Technology                     | 2         | 0.11%   |
| Wacom                                 | 1         | 0.05%   |
| Microsoft                             | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| D-Link System                         | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                     | 114       | 6.04%   |
| Intel Wi-Fi 6 AX201                                                  | 92        | 4.88%   |
| Intel Wireless 8265 / 8275                                           | 89        | 4.72%   |
| Intel Wi-Fi 6 AX200                                                  | 87        | 4.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 85        | 4.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 79        | 4.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 63        | 3.34%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 52        | 2.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 51        | 2.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 47        | 2.49%   |
| Intel Wireless 7265                                                  | 47        | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 46        | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 41        | 2.17%   |
| Intel Wireless 8260                                                  | 41        | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 38        | 2.01%   |
| Intel Wireless 7260                                                  | 37        | 1.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 34        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 33        | 1.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 31        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 31        | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 30        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 29        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                        | 29        | 1.54%   |
| Intel Wireless 3165                                                  | 24        | 1.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 22        | 1.17%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 22        | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 22        | 1.17%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 22        | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 21        | 1.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 19        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 18        | 0.95%   |
| Intel Wireless 3160                                                  | 18        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 17        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 16        | 0.85%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                   | 16        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 14        | 0.74%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 14        | 0.74%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 14        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 14        | 0.74%   |
| Intel Centrino Advanced-N 6200                                       | 13        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 772       | 56.81%  |
| Intel                                  | 336       | 24.72%  |
| Broadcom                               | 54        | 3.97%   |
| Qualcomm Atheros                       | 48        | 3.53%   |
| ASIX Electronics                       | 39        | 2.87%   |
| MediaTek                               | 21        | 1.55%   |
| Lenovo                                 | 14        | 1.03%   |
| Marvell Technology Group               | 8         | 0.59%   |
| Xiaomi                                 | 7         | 0.52%   |
| Nvidia                                 | 7         | 0.52%   |
| DisplayLink                            | 7         | 0.52%   |
| OPPO Electronics                       | 6         | 0.44%   |
| Samsung Electronics                    | 5         | 0.37%   |
| Motorola PCS                           | 5         | 0.37%   |
| TP-Link                                | 4         | 0.29%   |
| Apple                                  | 4         | 0.29%   |
| Qualcomm                               | 3         | 0.22%   |
| Hewlett-Packard                        | 3         | 0.22%   |
| Google                                 | 3         | 0.22%   |
| JMicron Technology                     | 2         | 0.15%   |
| Huawei Technologies                    | 2         | 0.15%   |
| Unknown                                | 2         | 0.15%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.07%   |
| Spreadtrum Communications              | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |
| D-Link System                          | 1         | 0.07%   |
| Broadcom Limited                       | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 530       | 38.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 89        | 6.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 85        | 6.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 44        | 3.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 33        | 2.39%   |
| ASIX AX88179 Gigabit Ethernet                                          | 33        | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 1.95%   |
| Intel Ethernet Connection (4) I219-V                                   | 23        | 1.66%   |
| Realtek Killer E2600 GbE Controller                                    | 21        | 1.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 20        | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 20        | 1.45%   |
| Intel Ethernet Connection I219-LM                                      | 17        | 1.23%   |
| Intel Ethernet Connection I217-LM                                      | 17        | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                  | 16        | 1.16%   |
| Intel Ethernet Connection (6) I219-LM                                  | 15        | 1.09%   |
| Intel Ethernet Connection (16) I219-V                                  | 14        | 1.01%   |
| Intel Ethernet Connection I218-LM                                      | 13        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 13        | 0.94%   |
| Intel Ethernet Connection I219-V                                       | 12        | 0.87%   |
| Intel Ethernet Connection (13) I219-V                                  | 11        | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                   | 10        | 0.72%   |
| Realtek PCIe GbE Family Controller                                     | 9         | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 9         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 9         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 8         | 0.58%   |
| Intel Ethernet Connection (16) I219-LM                                 | 8         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 7         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 0.43%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.43%   |
| Intel Ethernet Connection (23) I219-V                                  | 6         | 0.43%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 6         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.36%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 5         | 0.36%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5         | 0.36%   |
| Intel Ethernet Connection (23) I219-LM                                 | 5         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1788      | 58.07%  |
| Ethernet | 1268      | 41.18%  |
| Modem    | 19        | 0.62%   |
| Unknown  | 4         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1538      | 80.44%  |
| Ethernet | 373       | 19.51%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1111      | 60.28%  |
| 1     | 698       | 37.87%  |
| 0     | 18        | 0.98%   |
| 3     | 15        | 0.81%   |
| 4     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1271      | 68.37%  |
| Yes  | 588       | 31.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 841       | 51.88%  |
| Realtek Semiconductor           | 198       | 12.21%  |
| IMC Networks                    | 107       | 6.6%    |
| Qualcomm Atheros Communications | 85        | 5.24%   |
| Apple                           | 83        | 5.12%   |
| Foxconn / Hon Hai               | 82        | 5.06%   |
| Lite-On Technology              | 58        | 3.58%   |
| Broadcom                        | 47        | 2.9%    |
| MediaTek                        | 26        | 1.6%    |
| USI                             | 21        | 1.3%    |
| Realtek                         | 20        | 1.23%   |
| Hewlett-Packard                 | 8         | 0.49%   |
| Dell                            | 8         | 0.49%   |
| Foxconn International           | 7         | 0.43%   |
| Cambridge Silicon Radio         | 6         | 0.37%   |
| Ralink                          | 5         | 0.31%   |
| Ralink Technology               | 4         | 0.25%   |
| Toshiba                         | 3         | 0.19%   |
| ASUSTek Computer                | 2         | 0.12%   |
| Askey Computer                  | 2         | 0.12%   |
| Alps Electric                   | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Smart Modular Technologies      | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| Actions                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 237       | 14.62%  |
| Intel AX201 Bluetooth                               | 210       | 12.95%  |
| Intel AX211 Bluetooth                               | 139       | 8.57%   |
| Realtek Bluetooth Radio                             | 133       | 8.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 93        | 5.74%   |
| Intel AX200 Bluetooth                               | 83        | 5.12%   |
| IMC Networks Wireless_Device                        | 69        | 4.26%   |
| Intel AX210 Bluetooth                               | 50        | 3.08%   |
| Apple Bluetooth Host Controller                     | 50        | 3.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 45        | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 34        | 2.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 32        | 1.97%   |
| MediaTek Wireless_Device                            | 26        | 1.6%    |
| Apple Bluetooth USB Host Controller                 | 26        | 1.6%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 24        | 1.48%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.42%   |
| USI Bluetooth Device                                | 21        | 1.3%    |
| Realtek 802.11ac WLAN Adapter                       | 21        | 1.3%    |
| Realtek Bluetooth Radio                             | 20        | 1.23%   |
| Lite-On Wireless_Device                             | 18        | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 0.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.86%   |
| Lite-On Bluetooth Device                            | 12        | 0.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.49%   |
| IMC Networks Bluetooth Device                       | 8         | 0.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module   | 7         | 0.43%   |
| Lite-On Bluetooth Radio                             | 6         | 0.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 6         | 0.37%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.31%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.31%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 0.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.31%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 5         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1378      | 58.27%  |
| AMD                                             | 468       | 19.79%  |
| Nvidia                                          | 363       | 15.35%  |
| Lenovo                                          | 16        | 0.68%   |
| C-Media Electronics                             | 15        | 0.63%   |
| GN Netcom                                       | 13        | 0.55%   |
| Sony                                            | 9         | 0.38%   |
| Realtek Semiconductor                           | 9         | 0.38%   |
| Hewlett-Packard                                 | 9         | 0.38%   |
| Apple                                           | 9         | 0.38%   |
| Logitech                                        | 6         | 0.25%   |
| JMTek                                           | 5         | 0.21%   |
| Generalplus Technology                          | 5         | 0.21%   |
| ASUSTek Computer                                | 5         | 0.21%   |
| Plantronics                                     | 4         | 0.17%   |
| Texas Instruments                               | 3         | 0.13%   |
| Focusrite-Novation                              | 3         | 0.13%   |
| DSEA A/S                                        | 3         | 0.13%   |
| SteelSeries ApS                                 | 2         | 0.08%   |
| Samson Technologies                             | 2         | 0.08%   |
| Razer USA                                       | 2         | 0.08%   |
| KTMicro                                         | 2         | 0.08%   |
| Jieli Technology                                | 2         | 0.08%   |
| FiiO Electronics Technology                     | 2         | 0.08%   |
| Creative Technology                             | 2         | 0.08%   |
| BEHRINGER International                         | 2         | 0.08%   |
| Unknown                                         | 2         | 0.08%   |
| Yealink Network Technology                      | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.04%   |
| Tenx Technology                                 | 1         | 0.04%   |
| Silicon Motion                                  | 1         | 0.04%   |
| RODE Microphones                                | 1         | 0.04%   |
| RME                                             | 1         | 0.04%   |
| Panasonic (Matsushita)                          | 1         | 0.04%   |
| Nordic Semiconductor ASA                        | 1         | 0.04%   |
| Microchip Technology                            | 1         | 0.04%   |
| M-Audio                                         | 1         | 0.04%   |
| Lotoo                                           | 1         | 0.04%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.04%   |
| Kingston Technology                             | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 386       | 13.23%  |
| Intel Sunrise Point-LP HD Audio                                            | 227       | 7.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 187       | 6.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 148       | 5.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 132       | 4.53%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 126       | 4.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 82        | 2.81%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 71        | 2.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 60        | 2.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 60        | 2.06%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 60        | 2.06%   |
| Intel 8 Series HD Audio Controller                                         | 58        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 57        | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 56        | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 47        | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 47        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 45        | 1.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 42        | 1.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 42        | 1.44%   |
| Nvidia GA106 High Definition Audio Controller                              | 38        | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 38        | 1.3%    |
| Nvidia GA107 High Definition Audio Controller                              | 37        | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 34        | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 32        | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 28        | 0.96%   |
| Nvidia AD107 High Definition Audio Controller                              | 28        | 0.96%   |
| Intel CM238 HD Audio Controller                                            | 28        | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 27        | 0.93%   |
| Intel Raptor Lake High Definition Audio Controller                         | 22        | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 20        | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 19        | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 18        | 0.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 0.62%   |
| AMD FCH Azalia Controller                                                  | 17        | 0.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15        | 0.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.48%   |
| Nvidia AD106M High Definition Audio Controller                             | 14        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 229       | 28.2%   |
| SK hynix            | 188       | 23.15%  |
| Micron Technology   | 146       | 17.98%  |
| Kingston            | 75        | 9.24%   |
| Crucial             | 51        | 6.28%   |
| Unknown             | 20        | 2.46%   |
| Ramaxel Technology  | 16        | 1.97%   |
| A-DATA Technology   | 14        | 1.72%   |
| Unknown             | 11        | 1.35%   |
| Corsair             | 8         | 0.99%   |
| Nanya Technology    | 7         | 0.86%   |
| G.Skill             | 6         | 0.74%   |
| Team                | 5         | 0.62%   |
| Elpida              | 5         | 0.62%   |
| Timetec             | 4         | 0.49%   |
| Transcend           | 3         | 0.37%   |
| Patriot             | 2         | 0.25%   |
| ChangXin Memory     | 2         | 0.25%   |
| Wilk                | 1         | 0.12%   |
| Unknown (ABCD)      | 1         | 0.12%   |
| Unknown (8A5D)      | 1         | 0.12%   |
| Unknown (83DA)      | 1         | 0.12%   |
| Unknown (0x7FFF)    | 1         | 0.12%   |
| Unknown (0x0B5E)    | 1         | 0.12%   |
| Teikon              | 1         | 0.12%   |
| Spectek             | 1         | 0.12%   |
| Smart Brazil        | 1         | 0.12%   |
| Smart               | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| Neo Forza           | 1         | 0.12%   |
| Lexar               | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| King Tiger          | 1         | 0.12%   |
| Innodisk            | 1         | 0.12%   |
| Hikvision           | 1         | 0.12%   |
| ASint Technology    | 1         | 0.12%   |
| Apacer              | 1         | 0.12%   |
| AMD                 | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.87%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.41%   |
| Unknown                                                          | 11        | 1.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.17%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 9         | 1.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 8         | 0.94%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.94%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 7         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.82%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 7         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.82%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 7         | 0.82%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 6         | 0.7%    |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 6         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 6         | 0.7%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.7%    |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                     | 6         | 0.7%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.59%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.59%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.59%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.59%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 5         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.59%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.47%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 4         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 4         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s            | 4         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.47%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 371       | 53.54%  |
| DDR3   | 117       | 16.88%  |
| LPDDR5 | 74        | 10.68%  |
| DDR5   | 65        | 9.38%   |
| LPDDR3 | 33        | 4.76%   |
| LPDDR4 | 28        | 4.04%   |
| DDR2   | 3         | 0.43%   |
| SDRAM  | 2         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 585       | 82.63%  |
| Row Of Chips | 115       | 16.24%  |
| Chip         | 6         | 0.85%   |
| DIMM         | 1         | 0.14%   |
| Unknown      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 327       | 43.95%  |
| 16384 | 172       | 23.12%  |
| 4096  | 158       | 21.24%  |
| 32768 | 48        | 6.45%   |
| 2048  | 33        | 4.44%   |
| 1024  | 4         | 0.54%   |
| 3072  | 2         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 228       | 31.23%  |
| 2667    | 115       | 15.75%  |
| 1600    | 90        | 12.33%  |
| 6400    | 51        | 6.99%   |
| 2133    | 39        | 5.34%   |
| 4800    | 33        | 4.52%   |
| 2400    | 32        | 4.38%   |
| 5600    | 30        | 4.11%   |
| 7500    | 22        | 3.01%   |
| 1334    | 17        | 2.33%   |
| 1867    | 14        | 1.92%   |
| 1333    | 14        | 1.92%   |
| 4267    | 11        | 1.51%   |
| 4266    | 10        | 1.37%   |
| 3266    | 4         | 0.55%   |
| 3733    | 3         | 0.41%   |
| 1066    | 3         | 0.41%   |
| 667     | 3         | 0.41%   |
| 5200    | 2         | 0.27%   |
| 8400    | 1         | 0.14%   |
| 7467    | 1         | 0.14%   |
| 4199    | 1         | 0.14%   |
| 2933    | 1         | 0.14%   |
| 2666    | 1         | 0.14%   |
| 2048    | 1         | 0.14%   |
| 1776    | 1         | 0.14%   |
| 1067    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 28.57%  |
| QinHeng Electronics | 1         | 14.29%  |
| Minolta             | 1         | 14.29%  |
| Dymo-CoStar         | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| QinHeng CH340S              | 1         | 14.29%  |
| Minolta PagePro 1300W       | 1         | 14.29%  |
| HP Smart Tank 510 series    | 1         | 14.29%  |
| HP LaserJet P1102           | 1         | 14.29%  |
| Dymo-CoStar LabelWriter 450 | 1         | 14.29%  |
| Canon PIXMA MG3500 Series   | 1         | 14.29%  |
| Brother HL-2240D series     | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 8800F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 349       | 21.41%  |
| IMC Networks                           | 206       | 12.64%  |
| Microdia                               | 141       | 8.65%   |
| Bison Electronics                      | 124       | 7.61%   |
| Quanta                                 | 121       | 7.42%   |
| Realtek Semiconductor                  | 112       | 6.87%   |
| Luxvisions Innotech Limited            | 77        | 4.72%   |
| Sunplus Innovation Technology          | 71        | 4.36%   |
| Apple                                  | 56        | 3.44%   |
| Cheng Uei Precision Industry (Foxlink) | 53        | 3.25%   |
| Sonix Technology                       | 49        | 3.01%   |
| Syntek                                 | 46        | 2.82%   |
| Acer                                   | 35        | 2.15%   |
| Lite-On Technology                     | 29        | 1.78%   |
| Logitech                               | 23        | 1.41%   |
| Suyin                                  | 19        | 1.17%   |
| ShineTech                              | 15        | 0.92%   |
| Silicon Motion                         | 14        | 0.86%   |
| Alcor Micro                            | 13        | 0.8%    |
| SunplusIT                              | 10        | 0.61%   |
| Samsung Electronics                    | 10        | 0.61%   |
| Lenovo                                 | 7         | 0.43%   |
| Ricoh                                  | 5         | 0.31%   |
| Microsoft                              | 4         | 0.25%   |
| icSpring                               | 4         | 0.25%   |
| Qtech                                  | 3         | 0.18%   |
| Primax Electronics                     | 3         | 0.18%   |
| Shine-optics                           | 2         | 0.12%   |
| kingcome                               | 2         | 0.12%   |
| Intel                                  | 2         | 0.12%   |
| Importek                               | 2         | 0.12%   |
| Goodong Industry                       | 2         | 0.12%   |
| Creative Technology                    | 2         | 0.12%   |
| Alpha Imaging Technology               | 2         | 0.12%   |
| Unknown                                | 2         | 0.12%   |
| Y Media                                | 1         | 0.06%   |
| Tripath Technology                     | 1         | 0.06%   |
| Tobii Technology AB                    | 1         | 0.06%   |
| Sunplus Technology                     | 1         | 0.06%   |
| Sunplus IT                             | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 111       | 6.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 76        | 4.63%   |
| Microdia Integrated_Webcam_HD                       | 68        | 4.14%   |
| IMC Networks Integrated Camera                      | 64        | 3.9%    |
| Realtek Integrated_Webcam_HD                        | 52        | 3.17%   |
| Bison Integrated Camera                             | 39        | 2.38%   |
| Syntek Integrated Camera                            | 37        | 2.25%   |
| Sunplus Integrated_Webcam_HD                        | 28        | 1.71%   |
| Sonix USB2.0 HD UVC WebCam                          | 28        | 1.71%   |
| Quanta HD User Facing                               | 26        | 1.58%   |
| Luxvisions Innotech Limited Integrated Camera       | 21        | 1.28%   |
| Chicony HP HD Camera                                | 21        | 1.28%   |
| Apple FaceTime HD Camera                            | 21        | 1.28%   |
| Chicony HD Webcam                                   | 19        | 1.16%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 18        | 1.1%    |
| Chicony HP Truevision HD camera                     | 18        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 17        | 1.04%   |
| Quanta ACER HD User Facing                          | 16        | 0.98%   |
| IMC Networks HD Camera                              | 16        | 0.98%   |
| Chicony Integrated Camera (1280x720@30)             | 16        | 0.98%   |
| Bison HD Webcam                                     | 15        | 0.91%   |
| Quanta HP TrueVision HD Camera                      | 14        | 0.85%   |
| Chicony HD User Facing                              | 14        | 0.85%   |
| Bison SunplusIT Integrated Camera                   | 14        | 0.85%   |
| Sonix USB2.0 FHD UVC WebCam                         | 13        | 0.79%   |
| Chicony HP TrueVision HD                            | 13        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 13        | 0.79%   |
| Acer Integrated Camera                              | 13        | 0.79%   |
| Microdia Webcam Vitade AF                           | 12        | 0.73%   |
| Microdia Integrated Webcam                          | 12        | 0.73%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 12        | 0.73%   |
| Realtek Laptop Camera                               | 11        | 0.67%   |
| Microdia Integrated_Webcam_FHD                      | 11        | 0.67%   |
| Luxvisions Innotech Limited HP HD Camera            | 11        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)             | 10        | 0.61%   |
| Quanta ov9734_techfront_camera                      | 10        | 0.61%   |
| Quanta HP Wide Vision HD Camera                     | 10        | 0.61%   |
| Lite-On HP HD Camera                                | 10        | 0.61%   |
| Bison Integrated RGB Camera                         | 10        | 0.61%   |
| Apple Built-in iSight                               | 10        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 132       | 40.37%  |
| Validity Sensors                   | 86        | 26.3%   |
| Shenzhen Goodix Technology         | 53        | 16.21%  |
| Elan Microelectronics              | 24        | 7.34%   |
| Upek                               | 12        | 3.67%   |
| Realtek USB2.0 Finger Print Bridge | 9         | 2.75%   |
| LighTuning Technology              | 6         | 1.83%   |
| AuthenTec                          | 2         | 0.61%   |
| Samsung Electronics                | 1         | 0.31%   |
| FocalTech                          | 1         | 0.31%   |
| Focal-systems.Corp                 | 1         | 0.31%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 11.62%  |
| Shenzhen Goodix  FingerPrint Device                                        | 37        | 11.31%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 9.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 6.73%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 14        | 4.28%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 3.67%   |
| Synaptics UWP WBDI Device                                                  | 12        | 3.67%   |
| Elan ELAN:Fingerprint                                                      | 12        | 3.67%   |
| Elan ELAN:ARM-M4                                                           | 12        | 3.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 3.36%   |
| Synaptics Prometheus Fingerprint Reader                                    | 11        | 3.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.06%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.75%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 9         | 2.75%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.14%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.83%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.53%   |
| Validity Sensors VFS491                                                    | 4         | 1.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.22%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.92%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.92%   |
| Synaptics WBDI                                                             | 3         | 0.92%   |
| Synaptics UWP WBDI                                                         | 3         | 0.92%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.92%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.61%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.31%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.31%   |
| Synaptics TouchPad                                                         | 1         | 0.31%   |
| Synaptics  WBDI                                                            | 1         | 0.31%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.31%   |
| FocalTech FocalTech Fingerprint Device                                     | 1         | 0.31%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 75        | 51.02%  |
| Alcor Micro              | 54        | 36.73%  |
| Upek                     | 4         | 2.72%   |
| Lenovo                   | 3         | 2.04%   |
| Yubico.com               | 2         | 1.36%   |
| OmniKey                  | 2         | 1.36%   |
| CHERRY                   | 2         | 1.36%   |
| Reiner SCT Kartensysteme | 1         | 0.68%   |
| O2 Micro                 | 1         | 0.68%   |
| Gemalto (was Gemplus)    | 1         | 0.68%   |
| Chicony Electronics      | 1         | 0.68%   |
| Aktiv                    | 1         | 0.68%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 54        | 36.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 23        | 15.65%  |
| Broadcom 58200                                                               | 22        | 14.97%  |
| Broadcom 5880                                                                | 20        | 13.61%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 6.12%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.72%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.04%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.36%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 1.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.68%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.68%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.68%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.68%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.68%   |
| Aktiv Rutoken lite                                                           | 1         | 0.68%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1099      | 59.34%  |
| 1     | 637       | 34.4%   |
| 2     | 107       | 5.78%   |
| 3     | 7         | 0.38%   |
| 6     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 323       | 37.47%  |
| Graphics card            | 247       | 28.65%  |
| Multimedia controller    | 152       | 17.63%  |
| Net/wireless             | 64        | 7.42%   |
| Chipcard                 | 20        | 2.32%   |
| Camera                   | 15        | 1.74%   |
| Sound                    | 9         | 1.04%   |
| Net/ethernet             | 8         | 0.93%   |
| Bluetooth                | 8         | 0.93%   |
| Card reader              | 5         | 0.58%   |
| Modem                    | 4         | 0.46%   |
| Storage                  | 3         | 0.35%   |
| Network                  | 2         | 0.23%   |
| Communication controller | 2         | 0.23%   |

