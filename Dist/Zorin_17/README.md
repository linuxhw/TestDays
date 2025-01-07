Zorin 17 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 17.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_17/Desktop/README.md) and [notebooks](/Dist/Zorin_17/Notebook/README.md).

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

Total: 3545

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | FARQ16011                   | Tablet      | [cf0a931bc4](https://linux-hardware.org/?probe=cf0a931bc4) | Jan 06, 2025 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [a56f47a26f](https://linux-hardware.org/?probe=a56f47a26f) | Jan 06, 2025 |
| HP            | ProBook 640 G1              | Notebook    | [d6e43bba74](https://linux-hardware.org/?probe=d6e43bba74) | Jan 06, 2025 |
| HP            | ProBook 640 G1              | Notebook    | [7b033a8375](https://linux-hardware.org/?probe=7b033a8375) | Jan 06, 2025 |
| Intel         | H61M-DS2                    | Desktop     | [2ef34839f4](https://linux-hardware.org/?probe=2ef34839f4) | Jan 06, 2025 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [ad40db7f67](https://linux-hardware.org/?probe=ad40db7f67) | Jan 06, 2025 |
| Positivo      | C464C                       | Convertible | [d7de8bee56](https://linux-hardware.org/?probe=d7de8bee56) | Jan 06, 2025 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [f0c2f6b640](https://linux-hardware.org/?probe=f0c2f6b640) | Jan 06, 2025 |
| Lenovo        | IdeaPad Z400 VIWZ1          | Notebook    | [516947871e](https://linux-hardware.org/?probe=516947871e) | Jan 05, 2025 |
| MSI           | MS-B0A41                    | Desktop     | [72d4614eaf](https://linux-hardware.org/?probe=72d4614eaf) | Jan 05, 2025 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [de52972775](https://linux-hardware.org/?probe=de52972775) | Jan 05, 2025 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [d82c706a63](https://linux-hardware.org/?probe=d82c706a63) | Jan 05, 2025 |
| Dell          | 0HY9JP A00                  | Desktop     | [3047d18f75](https://linux-hardware.org/?probe=3047d18f75) | Jan 05, 2025 |
| ASUSTek       | K93SV                       | Notebook    | [01d0efaf46](https://linux-hardware.org/?probe=01d0efaf46) | Jan 05, 2025 |
| Dell          | Inspiron N4050              | Notebook    | [6da56634e0](https://linux-hardware.org/?probe=6da56634e0) | Jan 05, 2025 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [b2b5aa8eec](https://linux-hardware.org/?probe=b2b5aa8eec) | Jan 05, 2025 |
| Acer          | Aspire 5750G                | Notebook    | [68404201a9](https://linux-hardware.org/?probe=68404201a9) | Jan 05, 2025 |
| Lenovo        | IdeaPad 5 2-in-1 14AHP9 ... | Convertible | [9b54eb722d](https://linux-hardware.org/?probe=9b54eb722d) | Jan 05, 2025 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4a2cbc9a5c](https://linux-hardware.org/?probe=4a2cbc9a5c) | Jan 05, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [38b497d193](https://linux-hardware.org/?probe=38b497d193) | Jan 05, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [394cfdc261](https://linux-hardware.org/?probe=394cfdc261) | Jan 05, 2025 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [381b6fc010](https://linux-hardware.org/?probe=381b6fc010) | Jan 05, 2025 |
| Intel         | H61 V1.6B                   | Desktop     | [eb28b5f6be](https://linux-hardware.org/?probe=eb28b5f6be) | Jan 04, 2025 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [331b79e990](https://linux-hardware.org/?probe=331b79e990) | Jan 04, 2025 |
| Sony          | SVF15213CBW                 | Notebook    | [2a3349eb69](https://linux-hardware.org/?probe=2a3349eb69) | Jan 04, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [69146beeeb](https://linux-hardware.org/?probe=69146beeeb) | Jan 04, 2025 |
| HP            | 805D                        | Desktop     | [269af351cb](https://linux-hardware.org/?probe=269af351cb) | Jan 04, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [989a72852c](https://linux-hardware.org/?probe=989a72852c) | Jan 04, 2025 |
| Dell          | Inspiron 5566               | Notebook    | [9653ac70bc](https://linux-hardware.org/?probe=9653ac70bc) | Jan 04, 2025 |
| Intel         | H61                         | Desktop     | [2a8ff4b81a](https://linux-hardware.org/?probe=2a8ff4b81a) | Jan 03, 2025 |
| Intel         | H61                         | Desktop     | [bb2c7db34e](https://linux-hardware.org/?probe=bb2c7db34e) | Jan 03, 2025 |
| Dell          | Vostro 3420                 | Notebook    | [03772e7414](https://linux-hardware.org/?probe=03772e7414) | Jan 03, 2025 |
| Avell High... | Avell G1513 MUV / A52 MU... | Notebook    | [ca3162cf4a](https://linux-hardware.org/?probe=ca3162cf4a) | Jan 03, 2025 |
| Sony          | VGN-CR21S_W                 | Notebook    | [29a2c1f90e](https://linux-hardware.org/?probe=29a2c1f90e) | Jan 03, 2025 |
| Dell          | 0F65P3 A01                  | All in one  | [0fbde604e6](https://linux-hardware.org/?probe=0fbde604e6) | Jan 03, 2025 |
| HP            | Spectre x360 Convertible    | Convertible | [f3f5de25ba](https://linux-hardware.org/?probe=f3f5de25ba) | Jan 03, 2025 |
| HP            | Notebook                    | Notebook    | [b50d5a2974](https://linux-hardware.org/?probe=b50d5a2974) | Jan 03, 2025 |
| Toshiba       | Satellite C660              | Notebook    | [0767070a44](https://linux-hardware.org/?probe=0767070a44) | Jan 03, 2025 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [afcca700da](https://linux-hardware.org/?probe=afcca700da) | Jan 03, 2025 |
| HP            | ProBook 445 G7              | Notebook    | [8e56333050](https://linux-hardware.org/?probe=8e56333050) | Jan 03, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [bb8d0a325f](https://linux-hardware.org/?probe=bb8d0a325f) | Jan 02, 2025 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b58899eb8b](https://linux-hardware.org/?probe=b58899eb8b) | Jan 02, 2025 |
| Sony          | VGN-CS11Z_T                 | Notebook    | [28f8386e8f](https://linux-hardware.org/?probe=28f8386e8f) | Jan 01, 2025 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [eeb85155e5](https://linux-hardware.org/?probe=eeb85155e5) | Jan 01, 2025 |
| OEM           | B75 Ver:1.41                | Desktop     | [31c5df1f0f](https://linux-hardware.org/?probe=31c5df1f0f) | Jan 01, 2025 |
| HP            | TouchSmart tm2              | Notebook    | [1750c192e9](https://linux-hardware.org/?probe=1750c192e9) | Jan 01, 2025 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [2e3ebfe841](https://linux-hardware.org/?probe=2e3ebfe841) | Jan 01, 2025 |
| Dell          | 04GJJT A00                  | Desktop     | [444d672dcb](https://linux-hardware.org/?probe=444d672dcb) | Jan 01, 2025 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [047af1c88e](https://linux-hardware.org/?probe=047af1c88e) | Jan 01, 2025 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [15b1774620](https://linux-hardware.org/?probe=15b1774620) | Jan 01, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [47b07545df](https://linux-hardware.org/?probe=47b07545df) | Dec 31, 2024 |
| Dell          | Latitude E6410              | Notebook    | [ce431d6def](https://linux-hardware.org/?probe=ce431d6def) | Dec 31, 2024 |
| Dell          | Latitude E6410              | Notebook    | [e5ad6fdba6](https://linux-hardware.org/?probe=e5ad6fdba6) | Dec 31, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [5c2b2c9c8f](https://linux-hardware.org/?probe=5c2b2c9c8f) | Dec 31, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [8b12a21b9a](https://linux-hardware.org/?probe=8b12a21b9a) | Dec 31, 2024 |
| Lenovo        | ThinkPad Edge 0301FFG       | Notebook    | [526994e0a4](https://linux-hardware.org/?probe=526994e0a4) | Dec 31, 2024 |
| Dell          | Inspiron 7520               | Notebook    | [f60d84588c](https://linux-hardware.org/?probe=f60d84588c) | Dec 31, 2024 |
| Samsung       | 950QED                      | Convertible | [fed1e8737a](https://linux-hardware.org/?probe=fed1e8737a) | Dec 31, 2024 |
| HP            | ProBook 4540s               | Notebook    | [9bbe0a3b71](https://linux-hardware.org/?probe=9bbe0a3b71) | Dec 31, 2024 |
| Toshiba       | Satellite C75D-B            | Notebook    | [728de620aa](https://linux-hardware.org/?probe=728de620aa) | Dec 31, 2024 |
| ASRock        | A75 Extreme6                | Desktop     | [86fd341a89](https://linux-hardware.org/?probe=86fd341a89) | Dec 31, 2024 |
| Lenovo        | ThinkPad T500 2241WKY       | Notebook    | [7b16eb5229](https://linux-hardware.org/?probe=7b16eb5229) | Dec 30, 2024 |
| HP            | 470 G8 Notebook PC          | Notebook    | [a14600050a](https://linux-hardware.org/?probe=a14600050a) | Dec 30, 2024 |
| Dell          | Latitude E7270              | Notebook    | [45d3b8797a](https://linux-hardware.org/?probe=45d3b8797a) | Dec 30, 2024 |
| HP            | 198E                        | Desktop     | [039237d3ac](https://linux-hardware.org/?probe=039237d3ac) | Dec 30, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [81eb291a07](https://linux-hardware.org/?probe=81eb291a07) | Dec 30, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [6d09d6c124](https://linux-hardware.org/?probe=6d09d6c124) | Dec 30, 2024 |
| ASUSTek       | N56JK                       | Notebook    | [d1c6ca3f72](https://linux-hardware.org/?probe=d1c6ca3f72) | Dec 29, 2024 |
| ASUSTek       | N56JK                       | Notebook    | [0114b99957](https://linux-hardware.org/?probe=0114b99957) | Dec 29, 2024 |
| AZW           | GK35                        | Desktop     | [ed7df72829](https://linux-hardware.org/?probe=ed7df72829) | Dec 29, 2024 |
| ASUSTek       | PRIME H610M-K ARGB          | Desktop     | [8f2f1603ad](https://linux-hardware.org/?probe=8f2f1603ad) | Dec 29, 2024 |
| Lenovo        | ThinkPad T460 20FN004CMN    | Notebook    | [c918606381](https://linux-hardware.org/?probe=c918606381) | Dec 29, 2024 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [dc533b139f](https://linux-hardware.org/?probe=dc533b139f) | Dec 29, 2024 |
| Dell          | 0XCR8D A03                  | Desktop     | [77abfbec81](https://linux-hardware.org/?probe=77abfbec81) | Dec 29, 2024 |
| HP            | 1497                        | Desktop     | [256c3def88](https://linux-hardware.org/?probe=256c3def88) | Dec 29, 2024 |
| MSI           | GT72 2QD                    | Notebook    | [c8a2b702aa](https://linux-hardware.org/?probe=c8a2b702aa) | Dec 29, 2024 |
| Lenovo        | G585 20137                  | Notebook    | [28c0d1589f](https://linux-hardware.org/?probe=28c0d1589f) | Dec 28, 2024 |
| Lenovo        | G585 20137                  | Notebook    | [77d7e4f41b](https://linux-hardware.org/?probe=77d7e4f41b) | Dec 28, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [daf6ad0471](https://linux-hardware.org/?probe=daf6ad0471) | Dec 28, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [4d428ff2fd](https://linux-hardware.org/?probe=4d428ff2fd) | Dec 28, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [fd2a217520](https://linux-hardware.org/?probe=fd2a217520) | Dec 28, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [089e2c01de](https://linux-hardware.org/?probe=089e2c01de) | Dec 28, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [d5047e58d1](https://linux-hardware.org/?probe=d5047e58d1) | Dec 28, 2024 |
| Dell          | Latitude E4300              | Notebook    | [0c340c7391](https://linux-hardware.org/?probe=0c340c7391) | Dec 28, 2024 |
| GPD           | G1618-04                    | Notebook    | [f9fccc3291](https://linux-hardware.org/?probe=f9fccc3291) | Dec 28, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [39cfeac033](https://linux-hardware.org/?probe=39cfeac033) | Dec 28, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [ffcb19aa37](https://linux-hardware.org/?probe=ffcb19aa37) | Dec 28, 2024 |
| MSI           | FM2-A75IA-E53               | Desktop     | [4736ddfd8c](https://linux-hardware.org/?probe=4736ddfd8c) | Dec 28, 2024 |
| Toshiba       | Satellite P300              | Notebook    | [3174fc3f7e](https://linux-hardware.org/?probe=3174fc3f7e) | Dec 27, 2024 |
| Dell          | Latitude E4300              | Notebook    | [e00b4f8165](https://linux-hardware.org/?probe=e00b4f8165) | Dec 27, 2024 |
| Lenovo        | V15 G2 ITL 82ME             | Notebook    | [4c710eefac](https://linux-hardware.org/?probe=4c710eefac) | Dec 27, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [dcb25941f6](https://linux-hardware.org/?probe=dcb25941f6) | Dec 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6d267dc1e6](https://linux-hardware.org/?probe=6d267dc1e6) | Dec 27, 2024 |
| Medion        | ERAZER X7853 MD60603        | Notebook    | [9c5d2630f6](https://linux-hardware.org/?probe=9c5d2630f6) | Dec 27, 2024 |
| Acer          | Aspire E1-571G              | Notebook    | [6da76de24e](https://linux-hardware.org/?probe=6da76de24e) | Dec 27, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a0df3d57ee](https://linux-hardware.org/?probe=a0df3d57ee) | Dec 27, 2024 |
| Dell          | 05XGC8 A01                  | Desktop     | [59297e30b7](https://linux-hardware.org/?probe=59297e30b7) | Dec 27, 2024 |
| Dell          | 05XGC8 A01                  | Desktop     | [4714a00d4c](https://linux-hardware.org/?probe=4714a00d4c) | Dec 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4bfed8719e](https://linux-hardware.org/?probe=4bfed8719e) | Dec 27, 2024 |
| ASRock        | X870 Pro RS WiFi            | Desktop     | [97eaca87bb](https://linux-hardware.org/?probe=97eaca87bb) | Dec 27, 2024 |
| HP            | 83F2                        | Desktop     | [28232611f8](https://linux-hardware.org/?probe=28232611f8) | Dec 27, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [59a746132a](https://linux-hardware.org/?probe=59a746132a) | Dec 26, 2024 |
| Dell          | 0200DY A02                  | Desktop     | [048527009c](https://linux-hardware.org/?probe=048527009c) | Dec 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | Notebook    | [32b3387f38](https://linux-hardware.org/?probe=32b3387f38) | Dec 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | Notebook    | [ce3b8aa0e6](https://linux-hardware.org/?probe=ce3b8aa0e6) | Dec 26, 2024 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [ff70c71f76](https://linux-hardware.org/?probe=ff70c71f76) | Dec 26, 2024 |
| ASUSTek       | X455LD                      | Notebook    | [0695dcd803](https://linux-hardware.org/?probe=0695dcd803) | Dec 26, 2024 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [783314e5b3](https://linux-hardware.org/?probe=783314e5b3) | Dec 26, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ee9f566833](https://linux-hardware.org/?probe=ee9f566833) | Dec 26, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [03bac79df3](https://linux-hardware.org/?probe=03bac79df3) | Dec 26, 2024 |
| Dell          | Latitude 5480               | Notebook    | [a43c9feb6e](https://linux-hardware.org/?probe=a43c9feb6e) | Dec 26, 2024 |
| Dell          | Latitude 5480               | Notebook    | [b0b2a919ce](https://linux-hardware.org/?probe=b0b2a919ce) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b127afa2e4](https://linux-hardware.org/?probe=b127afa2e4) | Dec 25, 2024 |
| Dell          | Precision M6800             | Notebook    | [7d37225503](https://linux-hardware.org/?probe=7d37225503) | Dec 25, 2024 |
| Packard Be... | TBGM01                      | Desktop     | [68d8628be3](https://linux-hardware.org/?probe=68d8628be3) | Dec 25, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [b0f84564ba](https://linux-hardware.org/?probe=b0f84564ba) | Dec 25, 2024 |
| Dell          | Precision M6800             | Notebook    | [d5733504f6](https://linux-hardware.org/?probe=d5733504f6) | Dec 25, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [3bb45810a1](https://linux-hardware.org/?probe=3bb45810a1) | Dec 25, 2024 |
| Dell          | 06FW8P A02                  | Desktop     | [42c00b7a8a](https://linux-hardware.org/?probe=42c00b7a8a) | Dec 24, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1c4acdd4ee](https://linux-hardware.org/?probe=1c4acdd4ee) | Dec 24, 2024 |
| Fujitsu Si... | D2461-A2 S26361-D2461-A2    | Desktop     | [246c7d0034](https://linux-hardware.org/?probe=246c7d0034) | Dec 24, 2024 |
| Lenovo        | ThinkPad T460s 20F90042G... | Notebook    | [d007cb01ec](https://linux-hardware.org/?probe=d007cb01ec) | Dec 24, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1440d04792](https://linux-hardware.org/?probe=1440d04792) | Dec 24, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [1205a81135](https://linux-hardware.org/?probe=1205a81135) | Dec 23, 2024 |
| Intel         | HM87                        | Notebook    | [06e9957440](https://linux-hardware.org/?probe=06e9957440) | Dec 23, 2024 |
| Teclast       | F6 Plus                     | Notebook    | [143094aa18](https://linux-hardware.org/?probe=143094aa18) | Dec 23, 2024 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [ec6c6385d5](https://linux-hardware.org/?probe=ec6c6385d5) | Dec 23, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [d6756e38c9](https://linux-hardware.org/?probe=d6756e38c9) | Dec 23, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [253b2b9f9f](https://linux-hardware.org/?probe=253b2b9f9f) | Dec 23, 2024 |
| Samsung       | R530/R730/P530              | Notebook    | [2c69e47fef](https://linux-hardware.org/?probe=2c69e47fef) | Dec 23, 2024 |
| Samsung       | R530/R730/P530              | Notebook    | [86fbdd5542](https://linux-hardware.org/?probe=86fbdd5542) | Dec 23, 2024 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | Desktop     | [572d308e92](https://linux-hardware.org/?probe=572d308e92) | Dec 23, 2024 |
| Samsung       | 700G7A                      | Notebook    | [0f56340187](https://linux-hardware.org/?probe=0f56340187) | Dec 23, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c8554294b6](https://linux-hardware.org/?probe=c8554294b6) | Dec 23, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [b5e37804c4](https://linux-hardware.org/?probe=b5e37804c4) | Dec 23, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [29bad5d443](https://linux-hardware.org/?probe=29bad5d443) | Dec 23, 2024 |
| HP            | 83E9                        | Desktop     | [149bf1039e](https://linux-hardware.org/?probe=149bf1039e) | Dec 23, 2024 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [482ce52b8d](https://linux-hardware.org/?probe=482ce52b8d) | Dec 22, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [119c51368a](https://linux-hardware.org/?probe=119c51368a) | Dec 22, 2024 |
| ASUSTek       | PRIME H470-PLUS             | Desktop     | [93ed037f43](https://linux-hardware.org/?probe=93ed037f43) | Dec 22, 2024 |
| Microsoft     | Surface Laptop SE           | Tablet      | [1827ad6649](https://linux-hardware.org/?probe=1827ad6649) | Dec 22, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JH00... | Convertible | [9711be4bfb](https://linux-hardware.org/?probe=9711be4bfb) | Dec 22, 2024 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [188aa532e9](https://linux-hardware.org/?probe=188aa532e9) | Dec 22, 2024 |
| Lenovo        | ThinkPad L540 20AUS02U00    | Notebook    | [b1e76585dc](https://linux-hardware.org/?probe=b1e76585dc) | Dec 21, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [e54906d193](https://linux-hardware.org/?probe=e54906d193) | Dec 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [d1d487fe68](https://linux-hardware.org/?probe=d1d487fe68) | Dec 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8adc47d05f](https://linux-hardware.org/?probe=8adc47d05f) | Dec 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [df6f512e3a](https://linux-hardware.org/?probe=df6f512e3a) | Dec 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [7c430caf94](https://linux-hardware.org/?probe=7c430caf94) | Dec 21, 2024 |
| Intel         | NUC13ANBi3 M89896-203       | Mini pc     | [70fdf813cc](https://linux-hardware.org/?probe=70fdf813cc) | Dec 20, 2024 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [69da2b0a14](https://linux-hardware.org/?probe=69da2b0a14) | Dec 20, 2024 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2b2541ddf3](https://linux-hardware.org/?probe=2b2541ddf3) | Dec 20, 2024 |
| HUAWEI        | HN-WX9X                     | Notebook    | [7749a94f08](https://linux-hardware.org/?probe=7749a94f08) | Dec 20, 2024 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [b08ef8f5a1](https://linux-hardware.org/?probe=b08ef8f5a1) | Dec 20, 2024 |
| Dell          | Latitude 7420               | Notebook    | [754cef3d2f](https://linux-hardware.org/?probe=754cef3d2f) | Dec 20, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [15936c57d6](https://linux-hardware.org/?probe=15936c57d6) | Dec 20, 2024 |
| Acer          | Nitro AN517-52              | Notebook    | [4233b4277f](https://linux-hardware.org/?probe=4233b4277f) | Dec 20, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [1d68c69eaf](https://linux-hardware.org/?probe=1d68c69eaf) | Dec 20, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [5850f01900](https://linux-hardware.org/?probe=5850f01900) | Dec 19, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [7c92813622](https://linux-hardware.org/?probe=7c92813622) | Dec 19, 2024 |
| Google        | Teemo                       | Desktop     | [220fc873b9](https://linux-hardware.org/?probe=220fc873b9) | Dec 19, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [edefe68947](https://linux-hardware.org/?probe=edefe68947) | Dec 19, 2024 |
| RuggedPC      | RuggedPadC15                | Tablet      | [2f439ab25c](https://linux-hardware.org/?probe=2f439ab25c) | Dec 19, 2024 |
| RuggedPC      | RuggedPadC15                | Tablet      | [013204f3b0](https://linux-hardware.org/?probe=013204f3b0) | Dec 19, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [c649082ef1](https://linux-hardware.org/?probe=c649082ef1) | Dec 19, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [61b3ee9f74](https://linux-hardware.org/?probe=61b3ee9f74) | Dec 19, 2024 |
| Packard Be... | TBGM01                      | Desktop     | [8fe4cbb492](https://linux-hardware.org/?probe=8fe4cbb492) | Dec 18, 2024 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [a3dfcce270](https://linux-hardware.org/?probe=a3dfcce270) | Dec 18, 2024 |
| Panasonic     | CF-31WFL52CM                | Notebook    | [566d39243d](https://linux-hardware.org/?probe=566d39243d) | Dec 18, 2024 |
| Proline       | V14664P                     | Notebook    | [3e422abecf](https://linux-hardware.org/?probe=3e422abecf) | Dec 18, 2024 |
| Lenovo        | S10-3                       | Notebook    | [3ba705e8e3](https://linux-hardware.org/?probe=3ba705e8e3) | Dec 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [a1f0651a5b](https://linux-hardware.org/?probe=a1f0651a5b) | Dec 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [f149e767ce](https://linux-hardware.org/?probe=f149e767ce) | Dec 18, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [837d0f44f3](https://linux-hardware.org/?probe=837d0f44f3) | Dec 17, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3f960b1f4e](https://linux-hardware.org/?probe=3f960b1f4e) | Dec 17, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [4f8f97ac4c](https://linux-hardware.org/?probe=4f8f97ac4c) | Dec 17, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3c1c1b71e8](https://linux-hardware.org/?probe=3c1c1b71e8) | Dec 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Notebook    | [db89962085](https://linux-hardware.org/?probe=db89962085) | Dec 17, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b7fa7d97c0](https://linux-hardware.org/?probe=b7fa7d97c0) | Dec 17, 2024 |
| Multilaser    | UB820                       | All in one  | [ec8a440630](https://linux-hardware.org/?probe=ec8a440630) | Dec 16, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [1e479b232e](https://linux-hardware.org/?probe=1e479b232e) | Dec 16, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | Notebook    | [a1ff05a59d](https://linux-hardware.org/?probe=a1ff05a59d) | Dec 16, 2024 |
| Acer          | Predator G3610              | Desktop     | [e1311f0567](https://linux-hardware.org/?probe=e1311f0567) | Dec 16, 2024 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [878a94ca7f](https://linux-hardware.org/?probe=878a94ca7f) | Dec 16, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [74781357e5](https://linux-hardware.org/?probe=74781357e5) | Dec 16, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [6501a529f5](https://linux-hardware.org/?probe=6501a529f5) | Dec 16, 2024 |
| Dell          | Latitude 5490               | Notebook    | [e8d767b8cb](https://linux-hardware.org/?probe=e8d767b8cb) | Dec 16, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [9926e0ee70](https://linux-hardware.org/?probe=9926e0ee70) | Dec 15, 2024 |
| Huanan        | B85                         | Desktop     | [b296e2c8e1](https://linux-hardware.org/?probe=b296e2c8e1) | Dec 15, 2024 |
| Dell          | Inspiron 7586               | Convertible | [ce99c50659](https://linux-hardware.org/?probe=ce99c50659) | Dec 15, 2024 |
| Dell          | Inspiron 7586               | Convertible | [89232ce550](https://linux-hardware.org/?probe=89232ce550) | Dec 15, 2024 |
| Toshiba       | Satellite P55-A             | Notebook    | [d54a3b360d](https://linux-hardware.org/?probe=d54a3b360d) | Dec 15, 2024 |
| MSI           | Eclipse Plus                | Desktop     | [bd3c3d2f09](https://linux-hardware.org/?probe=bd3c3d2f09) | Dec 15, 2024 |
| Acer          | Aspire A315-34              | Notebook    | [6c8d585d0b](https://linux-hardware.org/?probe=6c8d585d0b) | Dec 15, 2024 |
| Lenovo        | 10064                       | Desktop     | [b162e666ea](https://linux-hardware.org/?probe=b162e666ea) | Dec 15, 2024 |
| Acer          | Predator G3610              | Desktop     | [6daec71034](https://linux-hardware.org/?probe=6daec71034) | Dec 15, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [612e52e652](https://linux-hardware.org/?probe=612e52e652) | Dec 14, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [8e8893c238](https://linux-hardware.org/?probe=8e8893c238) | Dec 14, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [87c39f6163](https://linux-hardware.org/?probe=87c39f6163) | Dec 14, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [b839a0b9cf](https://linux-hardware.org/?probe=b839a0b9cf) | Dec 14, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [9d14a14655](https://linux-hardware.org/?probe=9d14a14655) | Dec 14, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e55c65b62](https://linux-hardware.org/?probe=9e55c65b62) | Dec 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [880ae3d999](https://linux-hardware.org/?probe=880ae3d999) | Dec 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [6d4d0b3ad2](https://linux-hardware.org/?probe=6d4d0b3ad2) | Dec 14, 2024 |
| Dell          | 0200DY A02                  | Desktop     | [8cdb0aff4f](https://linux-hardware.org/?probe=8cdb0aff4f) | Dec 14, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5720b04708](https://linux-hardware.org/?probe=5720b04708) | Dec 13, 2024 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [2b25226ef6](https://linux-hardware.org/?probe=2b25226ef6) | Dec 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [99ca8a0388](https://linux-hardware.org/?probe=99ca8a0388) | Dec 13, 2024 |
| Biostar       | A520MH                      | Desktop     | [b62ff2bde3](https://linux-hardware.org/?probe=b62ff2bde3) | Dec 13, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7c957f114c](https://linux-hardware.org/?probe=7c957f114c) | Dec 13, 2024 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [5a6473c245](https://linux-hardware.org/?probe=5a6473c245) | Dec 13, 2024 |
| Acer          | Aspire 5552                 | Notebook    | [1a998c8df4](https://linux-hardware.org/?probe=1a998c8df4) | Dec 13, 2024 |
| Dell          | Latitude E6430              | Notebook    | [200bed6a55](https://linux-hardware.org/?probe=200bed6a55) | Dec 13, 2024 |
| HP            | EliteBook x360 1040 G6      | Convertible | [c490d2f931](https://linux-hardware.org/?probe=c490d2f931) | Dec 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [c22f3c5d77](https://linux-hardware.org/?probe=c22f3c5d77) | Dec 12, 2024 |
| Dell          | Latitude E7440              | Notebook    | [f3ae8893e1](https://linux-hardware.org/?probe=f3ae8893e1) | Dec 12, 2024 |
| Dell          | 09WH54 A00                  | Desktop     | [f1bb8a4c8b](https://linux-hardware.org/?probe=f1bb8a4c8b) | Dec 12, 2024 |
| HP            | 3032h                       | Desktop     | [ca96a21d5f](https://linux-hardware.org/?probe=ca96a21d5f) | Dec 12, 2024 |
| Intel         | X79F1 V2.0                  | Desktop     | [b22f83ab40](https://linux-hardware.org/?probe=b22f83ab40) | Dec 12, 2024 |
| Intel         | H55                         | Desktop     | [9d104d8648](https://linux-hardware.org/?probe=9d104d8648) | Dec 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [209746eb6c](https://linux-hardware.org/?probe=209746eb6c) | Dec 11, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [642094775c](https://linux-hardware.org/?probe=642094775c) | Dec 11, 2024 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [87de375a5f](https://linux-hardware.org/?probe=87de375a5f) | Dec 11, 2024 |
| HP            | 8105                        | Desktop     | [96072984b0](https://linux-hardware.org/?probe=96072984b0) | Dec 11, 2024 |
| wpc           | zrd616                      | Desktop     | [f00be7af29](https://linux-hardware.org/?probe=f00be7af29) | Dec 11, 2024 |
| Lenovo        | ThinkPad T590 20N5S56P00    | Notebook    | [3112d3b106](https://linux-hardware.org/?probe=3112d3b106) | Dec 11, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [496d906ed4](https://linux-hardware.org/?probe=496d906ed4) | Dec 11, 2024 |
| Google        | Caroline                    | Notebook    | [cdad48b614](https://linux-hardware.org/?probe=cdad48b614) | Dec 11, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a331c3b846](https://linux-hardware.org/?probe=a331c3b846) | Dec 10, 2024 |
| Acer          | TravelMate 7740G            | Notebook    | [6a53c529c4](https://linux-hardware.org/?probe=6a53c529c4) | Dec 10, 2024 |
| Fujitsu       | FMVA30DN                    | Notebook    | [b859d288a9](https://linux-hardware.org/?probe=b859d288a9) | Dec 10, 2024 |
| HP            | Pavilion g4                 | Notebook    | [be7deb3d00](https://linux-hardware.org/?probe=be7deb3d00) | Dec 10, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [b632a4d566](https://linux-hardware.org/?probe=b632a4d566) | Dec 10, 2024 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [7bcd9c0153](https://linux-hardware.org/?probe=7bcd9c0153) | Dec 10, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [114c039a04](https://linux-hardware.org/?probe=114c039a04) | Dec 10, 2024 |
| Gigabyte      | B760 AORUS ELITE AX         | Desktop     | [1f88096982](https://linux-hardware.org/?probe=1f88096982) | Dec 09, 2024 |
| HP            | Pavilion g7                 | Notebook    | [3594243010](https://linux-hardware.org/?probe=3594243010) | Dec 09, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [8280df7254](https://linux-hardware.org/?probe=8280df7254) | Dec 09, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [9865d823ab](https://linux-hardware.org/?probe=9865d823ab) | Dec 09, 2024 |
| ASUSTek       | X555UB                      | Notebook    | [48b994930e](https://linux-hardware.org/?probe=48b994930e) | Dec 09, 2024 |
| Dell          | 0CRWCR A01                  | All in one  | [a552eb99ee](https://linux-hardware.org/?probe=a552eb99ee) | Dec 09, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [32b4864422](https://linux-hardware.org/?probe=32b4864422) | Dec 09, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5769fa8214](https://linux-hardware.org/?probe=5769fa8214) | Dec 09, 2024 |
| MSI           | Eclipse Plus                | Desktop     | [c3573619ad](https://linux-hardware.org/?probe=c3573619ad) | Dec 08, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4e75b83008](https://linux-hardware.org/?probe=4e75b83008) | Dec 08, 2024 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [3fb4762109](https://linux-hardware.org/?probe=3fb4762109) | Dec 08, 2024 |
| ASUSTek       | P9D-I Series                | Server      | [236c9198c6](https://linux-hardware.org/?probe=236c9198c6) | Dec 08, 2024 |
| Positivo      | POS-PIH81DL                 | Desktop     | [898e87127f](https://linux-hardware.org/?probe=898e87127f) | Dec 08, 2024 |
| Lenovo        | ThinkPad T430 2342CTO       | Notebook    | [1da6908bf8](https://linux-hardware.org/?probe=1da6908bf8) | Dec 07, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [dd5a713c21](https://linux-hardware.org/?probe=dd5a713c21) | Dec 07, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c9392314ab](https://linux-hardware.org/?probe=c9392314ab) | Dec 07, 2024 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [1a8413b8c1](https://linux-hardware.org/?probe=1a8413b8c1) | Dec 07, 2024 |
| Google        | Caroline                    | Notebook    | [6a386f12ab](https://linux-hardware.org/?probe=6a386f12ab) | Dec 07, 2024 |
| Lenovo        | 100e 2nd Gen 82GJ           | Notebook    | [8171e07097](https://linux-hardware.org/?probe=8171e07097) | Dec 07, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [56d85b7552](https://linux-hardware.org/?probe=56d85b7552) | Dec 07, 2024 |
| Dell          | 0J8H4R A00                  | Desktop     | [762b620190](https://linux-hardware.org/?probe=762b620190) | Dec 07, 2024 |
| Lenovo        | ThinkPad T430s 23539WU      | Notebook    | [3994091726](https://linux-hardware.org/?probe=3994091726) | Dec 07, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [bc0ded78ae](https://linux-hardware.org/?probe=bc0ded78ae) | Dec 07, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [9aef334f00](https://linux-hardware.org/?probe=9aef334f00) | Dec 06, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [95f2f887d0](https://linux-hardware.org/?probe=95f2f887d0) | Dec 06, 2024 |
| PC Special... | Recoil VIII 17              | Notebook    | [bf09f105dc](https://linux-hardware.org/?probe=bf09f105dc) | Dec 06, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [51c09a7ff2](https://linux-hardware.org/?probe=51c09a7ff2) | Dec 06, 2024 |
| Acer          | FIH57                       | All in one  | [aa23301e4b](https://linux-hardware.org/?probe=aa23301e4b) | Dec 06, 2024 |
| Dell          | 0PR1NK A01                  | All in one  | [62f71baabe](https://linux-hardware.org/?probe=62f71baabe) | Dec 06, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e2dc32e766](https://linux-hardware.org/?probe=e2dc32e766) | Dec 06, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [b2ee97d3d8](https://linux-hardware.org/?probe=b2ee97d3d8) | Dec 05, 2024 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [5e962e2194](https://linux-hardware.org/?probe=5e962e2194) | Dec 05, 2024 |
| HP            | Pavilion g4                 | Notebook    | [bb26b30a98](https://linux-hardware.org/?probe=bb26b30a98) | Dec 05, 2024 |
| Acer          | Aspire 8940G                | Notebook    | [e2dceeb6db](https://linux-hardware.org/?probe=e2dceeb6db) | Dec 05, 2024 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [8c3060eca2](https://linux-hardware.org/?probe=8c3060eca2) | Dec 05, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b0ff4ecc5f](https://linux-hardware.org/?probe=b0ff4ecc5f) | Dec 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [cfdba4136a](https://linux-hardware.org/?probe=cfdba4136a) | Dec 04, 2024 |
| Acer          | Aspire 5736Z                | Notebook    | [0ad38979a9](https://linux-hardware.org/?probe=0ad38979a9) | Dec 04, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [2c75ca87d5](https://linux-hardware.org/?probe=2c75ca87d5) | Dec 04, 2024 |
| Lenovo        | G580 2689K9G                | Notebook    | [7ebd98750f](https://linux-hardware.org/?probe=7ebd98750f) | Dec 04, 2024 |
| HP            | 8105                        | Desktop     | [536d499bb8](https://linux-hardware.org/?probe=536d499bb8) | Dec 04, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [8b336590d9](https://linux-hardware.org/?probe=8b336590d9) | Dec 04, 2024 |
| ASUSTek       | K53SC                       | Notebook    | [b7850939a4](https://linux-hardware.org/?probe=b7850939a4) | Dec 04, 2024 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [12e0599060](https://linux-hardware.org/?probe=12e0599060) | Dec 04, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [c3faa55c34](https://linux-hardware.org/?probe=c3faa55c34) | Dec 04, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1b34f91a7e](https://linux-hardware.org/?probe=1b34f91a7e) | Dec 04, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [c8b86d2a3e](https://linux-hardware.org/?probe=c8b86d2a3e) | Dec 04, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [c70be6f167](https://linux-hardware.org/?probe=c70be6f167) | Dec 04, 2024 |
| MSI           | Prestige 16 A13UCX          | Notebook    | [3c4cfbe0c2](https://linux-hardware.org/?probe=3c4cfbe0c2) | Dec 04, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [e292db7a28](https://linux-hardware.org/?probe=e292db7a28) | Dec 04, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7909d61813](https://linux-hardware.org/?probe=7909d61813) | Dec 04, 2024 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [de8e216552](https://linux-hardware.org/?probe=de8e216552) | Dec 04, 2024 |
| Login Info... | LOG-BAT-I                   | Desktop     | [c5ba631810](https://linux-hardware.org/?probe=c5ba631810) | Dec 04, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [7f5a0eea32](https://linux-hardware.org/?probe=7f5a0eea32) | Dec 03, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [959bb88eae](https://linux-hardware.org/?probe=959bb88eae) | Dec 03, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b1af910648](https://linux-hardware.org/?probe=b1af910648) | Dec 03, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [a806223e92](https://linux-hardware.org/?probe=a806223e92) | Dec 03, 2024 |
| Dell          | Inspiron 5759               | Notebook    | [9ca3f31d64](https://linux-hardware.org/?probe=9ca3f31d64) | Dec 03, 2024 |
| Intel Clie... | LAPBC710                    | Notebook    | [e603037ba8](https://linux-hardware.org/?probe=e603037ba8) | Dec 03, 2024 |
| ASUSTek       | X99-A II                    | Desktop     | [53d19a5849](https://linux-hardware.org/?probe=53d19a5849) | Dec 03, 2024 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [bda3d5d09a](https://linux-hardware.org/?probe=bda3d5d09a) | Dec 03, 2024 |
| BANGHO        | Suma 1025                   | Tablet      | [da6ce4b361](https://linux-hardware.org/?probe=da6ce4b361) | Dec 03, 2024 |
| Dell          | 0M9KCM A01                  | Desktop     | [5c2a5074f2](https://linux-hardware.org/?probe=5c2a5074f2) | Dec 02, 2024 |
| Acer          | Aspire 8940G                | Notebook    | [b2a2802135](https://linux-hardware.org/?probe=b2a2802135) | Dec 02, 2024 |
| HP            | Pavilion g4                 | Notebook    | [42bd25b20f](https://linux-hardware.org/?probe=42bd25b20f) | Dec 02, 2024 |
| Acer          | Aspire X3960                | Desktop     | [875985a78d](https://linux-hardware.org/?probe=875985a78d) | Dec 02, 2024 |
| MSI           | B760M GAMING PLUS WIFI      | Desktop     | [8ec6dab60d](https://linux-hardware.org/?probe=8ec6dab60d) | Dec 02, 2024 |
| Dell          | Latitude 3420               | Notebook    | [bfa6a73c30](https://linux-hardware.org/?probe=bfa6a73c30) | Dec 02, 2024 |
| Dell          | 0M9KCM A01                  | Desktop     | [c24a105e90](https://linux-hardware.org/?probe=c24a105e90) | Dec 02, 2024 |
| HP            | 8054                        | Desktop     | [aff3ac8a75](https://linux-hardware.org/?probe=aff3ac8a75) | Dec 02, 2024 |
| Dell          | Inspiron 3421               | Notebook    | [e5ed2eb5d8](https://linux-hardware.org/?probe=e5ed2eb5d8) | Dec 02, 2024 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [d064733dcb](https://linux-hardware.org/?probe=d064733dcb) | Dec 02, 2024 |
| HP            | ENVY dv6                    | Notebook    | [4540e135f3](https://linux-hardware.org/?probe=4540e135f3) | Dec 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [f660d8c779](https://linux-hardware.org/?probe=f660d8c779) | Dec 02, 2024 |
| Unknown       | YEPBOOK PRO                 | Notebook    | [a3393a26e8](https://linux-hardware.org/?probe=a3393a26e8) | Dec 01, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [b618babdf5](https://linux-hardware.org/?probe=b618babdf5) | Dec 01, 2024 |
| Dell          | Inspiron 13-5368            | Notebook    | [5f256e8e33](https://linux-hardware.org/?probe=5f256e8e33) | Dec 01, 2024 |
| Dell          | Latitude 5420               | Notebook    | [5002efd6a5](https://linux-hardware.org/?probe=5002efd6a5) | Dec 01, 2024 |
| Star Labs     | StarLite                    | Tablet      | [b6fe8e3fc9](https://linux-hardware.org/?probe=b6fe8e3fc9) | Dec 01, 2024 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [08b1243826](https://linux-hardware.org/?probe=08b1243826) | Dec 01, 2024 |
| Toshiba       | Satellite M840              | Notebook    | [63307beb47](https://linux-hardware.org/?probe=63307beb47) | Dec 01, 2024 |
| HP            | ProBook 6560b               | Notebook    | [a7224d17ca](https://linux-hardware.org/?probe=a7224d17ca) | Dec 01, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [90456d790c](https://linux-hardware.org/?probe=90456d790c) | Dec 01, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [35b3881cdb](https://linux-hardware.org/?probe=35b3881cdb) | Dec 01, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [95e149cabd](https://linux-hardware.org/?probe=95e149cabd) | Dec 01, 2024 |
| HP            | 821D                        | Desktop     | [20e39b95ab](https://linux-hardware.org/?probe=20e39b95ab) | Dec 01, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [014cfa2104](https://linux-hardware.org/?probe=014cfa2104) | Dec 01, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [734efedbfa](https://linux-hardware.org/?probe=734efedbfa) | Dec 01, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [10e229d327](https://linux-hardware.org/?probe=10e229d327) | Dec 01, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | Notebook    | [9235c47547](https://linux-hardware.org/?probe=9235c47547) | Dec 01, 2024 |
| Alienware     | 17                          | Notebook    | [feba90fb9d](https://linux-hardware.org/?probe=feba90fb9d) | Nov 30, 2024 |
| LG Electro... | 17Z90R-G.AA77G              | Notebook    | [63b72a5f86](https://linux-hardware.org/?probe=63b72a5f86) | Nov 30, 2024 |
| Lenovo        | ThinkPad T460s 20F90042G... | Notebook    | [4b13d3f5ba](https://linux-hardware.org/?probe=4b13d3f5ba) | Nov 30, 2024 |
| Dell          | Vostro 3525                 | Notebook    | [e4ebed04a3](https://linux-hardware.org/?probe=e4ebed04a3) | Nov 30, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [a42179c4b6](https://linux-hardware.org/?probe=a42179c4b6) | Nov 30, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [315f389132](https://linux-hardware.org/?probe=315f389132) | Nov 30, 2024 |
| Dell          | Latitude E5400              | Notebook    | [64f3a906c9](https://linux-hardware.org/?probe=64f3a906c9) | Nov 29, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [7342faf26d](https://linux-hardware.org/?probe=7342faf26d) | Nov 29, 2024 |
| Lenovo        | YB1-X91L                    | Convertible | [a263b9a39c](https://linux-hardware.org/?probe=a263b9a39c) | Nov 29, 2024 |
| Lenovo        | YB1-X91L                    | Convertible | [887954e693](https://linux-hardware.org/?probe=887954e693) | Nov 29, 2024 |
| ASRock        | A520M-HVS                   | Desktop     | [6fc786e56e](https://linux-hardware.org/?probe=6fc786e56e) | Nov 29, 2024 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [3a04adcfd6](https://linux-hardware.org/?probe=3a04adcfd6) | Nov 29, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [f0a42c0331](https://linux-hardware.org/?probe=f0a42c0331) | Nov 29, 2024 |
| Dell          | Latitude 3420               | Notebook    | [d7a23c335f](https://linux-hardware.org/?probe=d7a23c335f) | Nov 29, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [6e168a52c2](https://linux-hardware.org/?probe=6e168a52c2) | Nov 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [9dc04ee643](https://linux-hardware.org/?probe=9dc04ee643) | Nov 28, 2024 |
| Dell          | Latitude E5400              | Notebook    | [9c7aaedec7](https://linux-hardware.org/?probe=9c7aaedec7) | Nov 28, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [dbc43531ce](https://linux-hardware.org/?probe=dbc43531ce) | Nov 28, 2024 |
| Dell          | Precision M4800             | Notebook    | [c97548d58c](https://linux-hardware.org/?probe=c97548d58c) | Nov 28, 2024 |
| Dell          | Precision M4800             | Notebook    | [8cddfc2c38](https://linux-hardware.org/?probe=8cddfc2c38) | Nov 28, 2024 |
| Dell          | Precision M4800             | Notebook    | [932bc22167](https://linux-hardware.org/?probe=932bc22167) | Nov 28, 2024 |
| MSI           | GF615M-P33                  | Desktop     | [df34126457](https://linux-hardware.org/?probe=df34126457) | Nov 28, 2024 |
| Toshiba       | Satellite S55-C             | Notebook    | [f2be068ec4](https://linux-hardware.org/?probe=f2be068ec4) | Nov 28, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [96a747160d](https://linux-hardware.org/?probe=96a747160d) | Nov 28, 2024 |
| MSI           | GF615M-P33                  | Desktop     | [2e1f2c05cd](https://linux-hardware.org/?probe=2e1f2c05cd) | Nov 28, 2024 |
| Acer          | Aspire E5-521G              | Notebook    | [234e21b8b6](https://linux-hardware.org/?probe=234e21b8b6) | Nov 28, 2024 |
| Dell          | 0KWVT8 A00                  | Desktop     | [bd9c6385dd](https://linux-hardware.org/?probe=bd9c6385dd) | Nov 28, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [d8fe08107c](https://linux-hardware.org/?probe=d8fe08107c) | Nov 27, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [97df382c2f](https://linux-hardware.org/?probe=97df382c2f) | Nov 27, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7b8612d136](https://linux-hardware.org/?probe=7b8612d136) | Nov 27, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [70c8b6c941](https://linux-hardware.org/?probe=70c8b6c941) | Nov 27, 2024 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [ed20170ba7](https://linux-hardware.org/?probe=ed20170ba7) | Nov 27, 2024 |
| Samsung       | 750QFG                      | Convertible | [23f1277193](https://linux-hardware.org/?probe=23f1277193) | Nov 27, 2024 |
| Medion        | P7812                       | Notebook    | [19f035bca6](https://linux-hardware.org/?probe=19f035bca6) | Nov 27, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [f5b92bba05](https://linux-hardware.org/?probe=f5b92bba05) | Nov 26, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [a896649890](https://linux-hardware.org/?probe=a896649890) | Nov 26, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [49be531cbb](https://linux-hardware.org/?probe=49be531cbb) | Nov 26, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [819377ad01](https://linux-hardware.org/?probe=819377ad01) | Nov 26, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e3d6b07ecf](https://linux-hardware.org/?probe=e3d6b07ecf) | Nov 26, 2024 |
| Intel         | DX79TO AAG28805-402         | Desktop     | [4b26bc3324](https://linux-hardware.org/?probe=4b26bc3324) | Nov 26, 2024 |
| MSI           | MS-N014                     | Notebook    | [789c4f8e10](https://linux-hardware.org/?probe=789c4f8e10) | Nov 26, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [5dd1a2b1ec](https://linux-hardware.org/?probe=5dd1a2b1ec) | Nov 26, 2024 |
| Lenovo        | ThinkPad T430 2349LPG       | Notebook    | [c9caafc936](https://linux-hardware.org/?probe=c9caafc936) | Nov 26, 2024 |
| Teclast       | F15 Plus                    | Notebook    | [d3115c0e4f](https://linux-hardware.org/?probe=d3115c0e4f) | Nov 26, 2024 |
| MSI           | 2A9C                        | Desktop     | [69c4dafac6](https://linux-hardware.org/?probe=69c4dafac6) | Nov 26, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [e7ffb651be](https://linux-hardware.org/?probe=e7ffb651be) | Nov 26, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [978715d9f7](https://linux-hardware.org/?probe=978715d9f7) | Nov 26, 2024 |
| HP            | Unknown                     | Notebook    | [cf8fe45f43](https://linux-hardware.org/?probe=cf8fe45f43) | Nov 26, 2024 |
| Alienware     | M15x                        | Notebook    | [6a413494a5](https://linux-hardware.org/?probe=6a413494a5) | Nov 26, 2024 |
| HP            | 84FE                        | Desktop     | [e5540a94da](https://linux-hardware.org/?probe=e5540a94da) | Nov 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [2800502e8a](https://linux-hardware.org/?probe=2800502e8a) | Nov 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [e58584102b](https://linux-hardware.org/?probe=e58584102b) | Nov 26, 2024 |
| Dell          | Vostro 1510                 | Notebook    | [b7343f8cb8](https://linux-hardware.org/?probe=b7343f8cb8) | Nov 25, 2024 |
| HP            | Pavilion g6                 | Notebook    | [1e390a1633](https://linux-hardware.org/?probe=1e390a1633) | Nov 25, 2024 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [b575ef56e5](https://linux-hardware.org/?probe=b575ef56e5) | Nov 25, 2024 |
| Gigabyte      | B760 AORUS ELITE AX         | Desktop     | [d3c62f2b89](https://linux-hardware.org/?probe=d3c62f2b89) | Nov 25, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [0bb2743c5f](https://linux-hardware.org/?probe=0bb2743c5f) | Nov 25, 2024 |
| ASUSTek       | X550CL                      | Notebook    | [4da2083b30](https://linux-hardware.org/?probe=4da2083b30) | Nov 25, 2024 |
| ASUSTek       | M11AD                       | Desktop     | [b3222c19f5](https://linux-hardware.org/?probe=b3222c19f5) | Nov 25, 2024 |
| Dell          | Precision 5530              | Notebook    | [f03de6018a](https://linux-hardware.org/?probe=f03de6018a) | Nov 25, 2024 |
| ASUSTek       | M11AD                       | Desktop     | [63ed444411](https://linux-hardware.org/?probe=63ed444411) | Nov 25, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [49fcf4bdc7](https://linux-hardware.org/?probe=49fcf4bdc7) | Nov 25, 2024 |
| Dell          | 0KWVT8 A00                  | Desktop     | [790161652a](https://linux-hardware.org/?probe=790161652a) | Nov 25, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [2681ae7326](https://linux-hardware.org/?probe=2681ae7326) | Nov 25, 2024 |
| Dell          | Latitude E6510              | Notebook    | [68f65df3f5](https://linux-hardware.org/?probe=68f65df3f5) | Nov 25, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [76f9ffcdab](https://linux-hardware.org/?probe=76f9ffcdab) | Nov 25, 2024 |
| Acer          | Aspire E5-521G              | Notebook    | [7a5907751e](https://linux-hardware.org/?probe=7a5907751e) | Nov 25, 2024 |
| Lenovo        | ThinkPad P51 20HJS1AM00     | Notebook    | [e40691b60f](https://linux-hardware.org/?probe=e40691b60f) | Nov 24, 2024 |
| HP            | 2AA2                        | Desktop     | [ad8688b30a](https://linux-hardware.org/?probe=ad8688b30a) | Nov 24, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [7cffac8f5b](https://linux-hardware.org/?probe=7cffac8f5b) | Nov 24, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1755731ed3](https://linux-hardware.org/?probe=1755731ed3) | Nov 24, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [41d8012fc9](https://linux-hardware.org/?probe=41d8012fc9) | Nov 24, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | Notebook    | [d163c30bb6](https://linux-hardware.org/?probe=d163c30bb6) | Nov 24, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [2d282337d2](https://linux-hardware.org/?probe=2d282337d2) | Nov 24, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8d5b062bbb](https://linux-hardware.org/?probe=8d5b062bbb) | Nov 24, 2024 |
| Panasonic     | CF-30KTPJX2B                | Notebook    | [527ecd9958](https://linux-hardware.org/?probe=527ecd9958) | Nov 24, 2024 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [10d9ba5f68](https://linux-hardware.org/?probe=10d9ba5f68) | Nov 24, 2024 |
| Dell          | 0XC837                      | Desktop     | [af2a699551](https://linux-hardware.org/?probe=af2a699551) | Nov 24, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [50c436b911](https://linux-hardware.org/?probe=50c436b911) | Nov 24, 2024 |
| Colorful T... | C.Z77 X5 V20                | Desktop     | [5883b61b95](https://linux-hardware.org/?probe=5883b61b95) | Nov 24, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3f588402aa](https://linux-hardware.org/?probe=3f588402aa) | Nov 23, 2024 |
| HP            | 2ADC                        | Desktop     | [80db44ef55](https://linux-hardware.org/?probe=80db44ef55) | Nov 23, 2024 |
| Jemper        | EZPAD WS_reserve            | Notebook    | [120200526f](https://linux-hardware.org/?probe=120200526f) | Nov 23, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [770555fffb](https://linux-hardware.org/?probe=770555fffb) | Nov 23, 2024 |
| Toshiba       | TECRA M10                   | Notebook    | [f2db588ac1](https://linux-hardware.org/?probe=f2db588ac1) | Nov 23, 2024 |
| HP            | 625                         | Notebook    | [b34c64fa81](https://linux-hardware.org/?probe=b34c64fa81) | Nov 23, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21HL... | Notebook    | [74baa5a8ae](https://linux-hardware.org/?probe=74baa5a8ae) | Nov 23, 2024 |
| Sony          | VAIO                        | All in one  | [a8f1e64b41](https://linux-hardware.org/?probe=a8f1e64b41) | Nov 23, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4ae0ff6bb2](https://linux-hardware.org/?probe=4ae0ff6bb2) | Nov 23, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a297024700](https://linux-hardware.org/?probe=a297024700) | Nov 23, 2024 |
| Exo           | Smart XL4                   | Notebook    | [b9367af1bd](https://linux-hardware.org/?probe=b9367af1bd) | Nov 23, 2024 |
| Exo           | Smart XL4                   | Notebook    | [264ffc04ec](https://linux-hardware.org/?probe=264ffc04ec) | Nov 23, 2024 |
| HP            | 1497                        | Desktop     | [8d58b02962](https://linux-hardware.org/?probe=8d58b02962) | Nov 23, 2024 |
| Toshiba       | Satellite L500              | Notebook    | [e84f351148](https://linux-hardware.org/?probe=e84f351148) | Nov 23, 2024 |
| ASUSTek       | Q550LF                      | Notebook    | [c909346ef8](https://linux-hardware.org/?probe=c909346ef8) | Nov 23, 2024 |
| HP            | 2ADC                        | Desktop     | [eb84d86558](https://linux-hardware.org/?probe=eb84d86558) | Nov 23, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [c2f43e33c0](https://linux-hardware.org/?probe=c2f43e33c0) | Nov 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [168a1bbabd](https://linux-hardware.org/?probe=168a1bbabd) | Nov 23, 2024 |
| MSI           | GF75 Thin 10UE              | Notebook    | [b6764cacc8](https://linux-hardware.org/?probe=b6764cacc8) | Nov 23, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [2ccd8e4d15](https://linux-hardware.org/?probe=2ccd8e4d15) | Nov 23, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [11904bdfcd](https://linux-hardware.org/?probe=11904bdfcd) | Nov 22, 2024 |
| Biostar       | GF8200C M2+                 | Desktop     | [07b481323c](https://linux-hardware.org/?probe=07b481323c) | Nov 22, 2024 |
| Biostar       | GF8200C M2+                 | Desktop     | [8094c6177a](https://linux-hardware.org/?probe=8094c6177a) | Nov 22, 2024 |
| MSI           | GF75 Thin 10UE              | Notebook    | [90559a82e1](https://linux-hardware.org/?probe=90559a82e1) | Nov 22, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [92e0094425](https://linux-hardware.org/?probe=92e0094425) | Nov 22, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [6c4b43e660](https://linux-hardware.org/?probe=6c4b43e660) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [2dc26b3608](https://linux-hardware.org/?probe=2dc26b3608) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [05198e67f4](https://linux-hardware.org/?probe=05198e67f4) | Nov 22, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [4b11bad4e2](https://linux-hardware.org/?probe=4b11bad4e2) | Nov 21, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [8671b7ff77](https://linux-hardware.org/?probe=8671b7ff77) | Nov 21, 2024 |
| JW Technol... | JW-IG41-MKII V1.1           | Desktop     | [e48cac1e60](https://linux-hardware.org/?probe=e48cac1e60) | Nov 21, 2024 |
| Monster       | TULPAR T7 V19.3             | Notebook    | [a1fed284f5](https://linux-hardware.org/?probe=a1fed284f5) | Nov 21, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [64ef50126b](https://linux-hardware.org/?probe=64ef50126b) | Nov 21, 2024 |
| HP            | 8055                        | Desktop     | [593178f988](https://linux-hardware.org/?probe=593178f988) | Nov 21, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [e61aed8e47](https://linux-hardware.org/?probe=e61aed8e47) | Nov 21, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [437866e6de](https://linux-hardware.org/?probe=437866e6de) | Nov 21, 2024 |
| Acer          | Aspire 8940G                | Notebook    | [34cae8ce91](https://linux-hardware.org/?probe=34cae8ce91) | Nov 21, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [bce97e2d1d](https://linux-hardware.org/?probe=bce97e2d1d) | Nov 21, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [5f49362c72](https://linux-hardware.org/?probe=5f49362c72) | Nov 21, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [c7ca315f7b](https://linux-hardware.org/?probe=c7ca315f7b) | Nov 21, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [3fe08ea4ca](https://linux-hardware.org/?probe=3fe08ea4ca) | Nov 21, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [eb7131a7ff](https://linux-hardware.org/?probe=eb7131a7ff) | Nov 20, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [0d9292a695](https://linux-hardware.org/?probe=0d9292a695) | Nov 20, 2024 |
| ASUSTek       | 1215N                       | Notebook    | [b7baad3524](https://linux-hardware.org/?probe=b7baad3524) | Nov 20, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [bec30cdc12](https://linux-hardware.org/?probe=bec30cdc12) | Nov 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d7a91ad89e](https://linux-hardware.org/?probe=d7a91ad89e) | Nov 20, 2024 |
| MSI           | Prestige 16 AI Studio B1... | Notebook    | [fa335a2999](https://linux-hardware.org/?probe=fa335a2999) | Nov 20, 2024 |
| VALE          | Notebook Classic C170       | Notebook    | [d5f2c08e9a](https://linux-hardware.org/?probe=d5f2c08e9a) | Nov 19, 2024 |
| Intel         | D34010WYK H14771-304        | Desktop     | [51e96c807d](https://linux-hardware.org/?probe=51e96c807d) | Nov 19, 2024 |
| ASUSTek       | N752VX                      | Notebook    | [b519a4ac5e](https://linux-hardware.org/?probe=b519a4ac5e) | Nov 19, 2024 |
| Lenovo        | ThinkPad T440 20B6008EUS    | Notebook    | [3e2fc33d80](https://linux-hardware.org/?probe=3e2fc33d80) | Nov 19, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [f32ad3a689](https://linux-hardware.org/?probe=f32ad3a689) | Nov 19, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [9987b49eb1](https://linux-hardware.org/?probe=9987b49eb1) | Nov 19, 2024 |
| Lenovo        | ThinkPad T430 2349LPG       | Notebook    | [dea56417dc](https://linux-hardware.org/?probe=dea56417dc) | Nov 19, 2024 |
| Acer          | Aspire 3810T                | Notebook    | [71d5b52553](https://linux-hardware.org/?probe=71d5b52553) | Nov 18, 2024 |
| Intel         | D34010WYK H14771-304        | Desktop     | [d35a3bd5f8](https://linux-hardware.org/?probe=d35a3bd5f8) | Nov 18, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [ba3ba814ee](https://linux-hardware.org/?probe=ba3ba814ee) | Nov 18, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [d9d23cdc2c](https://linux-hardware.org/?probe=d9d23cdc2c) | Nov 18, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a57440afe](https://linux-hardware.org/?probe=1a57440afe) | Nov 18, 2024 |
| Login Info... | LOG-BAT-I                   | Desktop     | [2c0e29b140](https://linux-hardware.org/?probe=2c0e29b140) | Nov 18, 2024 |
| ASRock        | A320M Pro4                  | Desktop     | [69c029ae2e](https://linux-hardware.org/?probe=69c029ae2e) | Nov 18, 2024 |
| Dell          | Latitude 3430               | Notebook    | [2aa0f80ba7](https://linux-hardware.org/?probe=2aa0f80ba7) | Nov 18, 2024 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [4f40e1382c](https://linux-hardware.org/?probe=4f40e1382c) | Nov 18, 2024 |
| AMD           | A88                         | Desktop     | [9203b9c5a1](https://linux-hardware.org/?probe=9203b9c5a1) | Nov 18, 2024 |
| ASRock        | Z590 Phantom Gaming-ITX/... | Desktop     | [d158bc88f9](https://linux-hardware.org/?probe=d158bc88f9) | Nov 18, 2024 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [586741cd8d](https://linux-hardware.org/?probe=586741cd8d) | Nov 18, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [70aebceb5e](https://linux-hardware.org/?probe=70aebceb5e) | Nov 18, 2024 |
| ASUSTek       | P5K                         | Desktop     | [dfdb2cf6ee](https://linux-hardware.org/?probe=dfdb2cf6ee) | Nov 17, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [9925b08391](https://linux-hardware.org/?probe=9925b08391) | Nov 17, 2024 |
| AMI           | Intel                       | Desktop     | [266b0fb8f5](https://linux-hardware.org/?probe=266b0fb8f5) | Nov 17, 2024 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [dba1d52306](https://linux-hardware.org/?probe=dba1d52306) | Nov 17, 2024 |
| HP            | 805A                        | Desktop     | [4d0512b55a](https://linux-hardware.org/?probe=4d0512b55a) | Nov 16, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [1d7aa20bd7](https://linux-hardware.org/?probe=1d7aa20bd7) | Nov 16, 2024 |
| Compaq        | Presario CQ-23              | Notebook    | [a89bbf6c2d](https://linux-hardware.org/?probe=a89bbf6c2d) | Nov 16, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [c88c8d82af](https://linux-hardware.org/?probe=c88c8d82af) | Nov 16, 2024 |
| HP            | HDX18                       | Notebook    | [5c06e25998](https://linux-hardware.org/?probe=5c06e25998) | Nov 16, 2024 |
| Sony          | VAIO                        | All in one  | [cb7d9be78b](https://linux-hardware.org/?probe=cb7d9be78b) | Nov 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [3ddf105c9b](https://linux-hardware.org/?probe=3ddf105c9b) | Nov 16, 2024 |
| HP            | HDX18                       | Notebook    | [84c4ca9b15](https://linux-hardware.org/?probe=84c4ca9b15) | Nov 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [2f9a6a3df7](https://linux-hardware.org/?probe=2f9a6a3df7) | Nov 16, 2024 |
| HP            | Pavilion dv6                | Notebook    | [3e5c98d0a7](https://linux-hardware.org/?probe=3e5c98d0a7) | Nov 16, 2024 |
| Pegatron      | 2A9A                        | Desktop     | [f28e0b8f3d](https://linux-hardware.org/?probe=f28e0b8f3d) | Nov 16, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [d408ed76f5](https://linux-hardware.org/?probe=d408ed76f5) | Nov 15, 2024 |
| MSI           | MS-6657                     | All in one  | [f7cb25fe9c](https://linux-hardware.org/?probe=f7cb25fe9c) | Nov 15, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21HL... | Notebook    | [053ac6a237](https://linux-hardware.org/?probe=053ac6a237) | Nov 15, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [655fe70c91](https://linux-hardware.org/?probe=655fe70c91) | Nov 15, 2024 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | Desktop     | [7055ac7293](https://linux-hardware.org/?probe=7055ac7293) | Nov 15, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [865f61fac1](https://linux-hardware.org/?probe=865f61fac1) | Nov 15, 2024 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [0c40e6c351](https://linux-hardware.org/?probe=0c40e6c351) | Nov 15, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a7c7d8ba31](https://linux-hardware.org/?probe=a7c7d8ba31) | Nov 14, 2024 |
| Dell          | Latitude 7420               | Notebook    | [38595a466f](https://linux-hardware.org/?probe=38595a466f) | Nov 14, 2024 |
| HP            | Pavilion g7                 | Notebook    | [97d1e7e615](https://linux-hardware.org/?probe=97d1e7e615) | Nov 14, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [84de7f4342](https://linux-hardware.org/?probe=84de7f4342) | Nov 13, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [c9a14a76c9](https://linux-hardware.org/?probe=c9a14a76c9) | Nov 13, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [820c94c4ff](https://linux-hardware.org/?probe=820c94c4ff) | Nov 13, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [14bab473d3](https://linux-hardware.org/?probe=14bab473d3) | Nov 13, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [0c44989ab0](https://linux-hardware.org/?probe=0c44989ab0) | Nov 13, 2024 |
| Dell          | Inspiron 5420               | Notebook    | [00ddbfabc2](https://linux-hardware.org/?probe=00ddbfabc2) | Nov 13, 2024 |
| Intel         | B75                         | Desktop     | [3702d043f1](https://linux-hardware.org/?probe=3702d043f1) | Nov 13, 2024 |
| Intel         | B75                         | Desktop     | [b9f5a481dc](https://linux-hardware.org/?probe=b9f5a481dc) | Nov 13, 2024 |
| Lenovo        | ThinkPad L430 2466DN6       | Notebook    | [4f5a0a5c17](https://linux-hardware.org/?probe=4f5a0a5c17) | Nov 13, 2024 |
| HP            | 2B02                        | Desktop     | [a0b3253900](https://linux-hardware.org/?probe=a0b3253900) | Nov 13, 2024 |
| Lenovo        | ThinkPad W530 244759G       | Notebook    | [6c04928748](https://linux-hardware.org/?probe=6c04928748) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [16f0766161](https://linux-hardware.org/?probe=16f0766161) | Nov 12, 2024 |
| HP            | 2B02                        | Desktop     | [d5120d2bd5](https://linux-hardware.org/?probe=d5120d2bd5) | Nov 12, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4e89ce41d8](https://linux-hardware.org/?probe=4e89ce41d8) | Nov 12, 2024 |
| MSI           | B365M PRO-VDH               | Desktop     | [82d0c85a4c](https://linux-hardware.org/?probe=82d0c85a4c) | Nov 12, 2024 |
| HP            | 1998                        | Desktop     | [369ca1dd47](https://linux-hardware.org/?probe=369ca1dd47) | Nov 12, 2024 |
| ASUSTek       | P5K                         | Desktop     | [909b21807d](https://linux-hardware.org/?probe=909b21807d) | Nov 11, 2024 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [2f352dba44](https://linux-hardware.org/?probe=2f352dba44) | Nov 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [c236922dba](https://linux-hardware.org/?probe=c236922dba) | Nov 11, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [7317bd38b4](https://linux-hardware.org/?probe=7317bd38b4) | Nov 11, 2024 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [b394d3009b](https://linux-hardware.org/?probe=b394d3009b) | Nov 11, 2024 |
| Dell          | Latitude 3420               | Notebook    | [f2a0eac267](https://linux-hardware.org/?probe=f2a0eac267) | Nov 11, 2024 |
| ASUSTek       | GL503VD                     | Notebook    | [d395d04c9f](https://linux-hardware.org/?probe=d395d04c9f) | Nov 11, 2024 |
| OEM           | Unknown                     | Notebook    | [da6c715062](https://linux-hardware.org/?probe=da6c715062) | Nov 11, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [971fc4620d](https://linux-hardware.org/?probe=971fc4620d) | Nov 11, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [9e6cca17b9](https://linux-hardware.org/?probe=9e6cca17b9) | Nov 10, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [748450069e](https://linux-hardware.org/?probe=748450069e) | Nov 10, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [3b2b10209b](https://linux-hardware.org/?probe=3b2b10209b) | Nov 10, 2024 |
| RuggedPC      | RuggedBookR15               | Notebook    | [aa3abb03d5](https://linux-hardware.org/?probe=aa3abb03d5) | Nov 10, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [df8fc5ffa1](https://linux-hardware.org/?probe=df8fc5ffa1) | Nov 10, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [cc3c38e859](https://linux-hardware.org/?probe=cc3c38e859) | Nov 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7bba50e3f8](https://linux-hardware.org/?probe=7bba50e3f8) | Nov 10, 2024 |
| HP            | ProBook 4720s               | Notebook    | [e65d783c0d](https://linux-hardware.org/?probe=e65d783c0d) | Nov 10, 2024 |
| HP            | ProBook 4720s               | Notebook    | [4e2933c1be](https://linux-hardware.org/?probe=4e2933c1be) | Nov 10, 2024 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [bfaec6f29f](https://linux-hardware.org/?probe=bfaec6f29f) | Nov 10, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [4a59573437](https://linux-hardware.org/?probe=4a59573437) | Nov 10, 2024 |
| Lenovo        | ThinkPad Edge E320 1298A... | Notebook    | [0af8d792c0](https://linux-hardware.org/?probe=0af8d792c0) | Nov 10, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cb797d9021](https://linux-hardware.org/?probe=cb797d9021) | Nov 10, 2024 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [3578d7c78f](https://linux-hardware.org/?probe=3578d7c78f) | Nov 09, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [8268a446ea](https://linux-hardware.org/?probe=8268a446ea) | Nov 09, 2024 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [8e2635b72b](https://linux-hardware.org/?probe=8e2635b72b) | Nov 09, 2024 |
| Dell          | 0KC9NP A01                  | Desktop     | [d4ce086214](https://linux-hardware.org/?probe=d4ce086214) | Nov 09, 2024 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [6be191dad3](https://linux-hardware.org/?probe=6be191dad3) | Nov 09, 2024 |
| HP            | 1905                        | Desktop     | [02b35a093f](https://linux-hardware.org/?probe=02b35a093f) | Nov 08, 2024 |
| HP            | 240 G8                      | Notebook    | [690c75feed](https://linux-hardware.org/?probe=690c75feed) | Nov 08, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8fad4727cc](https://linux-hardware.org/?probe=8fad4727cc) | Nov 08, 2024 |
| Lenovo        | ThinkPad X230 2324BN2       | Notebook    | [2040b5fccb](https://linux-hardware.org/?probe=2040b5fccb) | Nov 08, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [bc3bb9ceab](https://linux-hardware.org/?probe=bc3bb9ceab) | Nov 08, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [a3eba13ef1](https://linux-hardware.org/?probe=a3eba13ef1) | Nov 08, 2024 |
| Toshiba       | Satellite S50D-B            | Notebook    | [ce49220a67](https://linux-hardware.org/?probe=ce49220a67) | Nov 08, 2024 |
| Toshiba       | Satellite S50D-B            | Notebook    | [1f56de68ff](https://linux-hardware.org/?probe=1f56de68ff) | Nov 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db35fd585c](https://linux-hardware.org/?probe=db35fd585c) | Nov 07, 2024 |
| ASRock        | A520M-HVS                   | Desktop     | [5f9ee0de7f](https://linux-hardware.org/?probe=5f9ee0de7f) | Nov 07, 2024 |
| MSI           | Prestige 16 AI Studio B1... | Notebook    | [f0052fafb7](https://linux-hardware.org/?probe=f0052fafb7) | Nov 07, 2024 |
| Medion        | P7812                       | Notebook    | [e1d13cf7b2](https://linux-hardware.org/?probe=e1d13cf7b2) | Nov 07, 2024 |
| Gigabyte      | B760M AORUS ELITE           | Desktop     | [52a1a63a06](https://linux-hardware.org/?probe=52a1a63a06) | Nov 07, 2024 |
| HP            | 240 G8                      | Notebook    | [7144a2acc7](https://linux-hardware.org/?probe=7144a2acc7) | Nov 07, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS3... | Convertible | [3e64c9422a](https://linux-hardware.org/?probe=3e64c9422a) | Nov 06, 2024 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [734bd2b7df](https://linux-hardware.org/?probe=734bd2b7df) | Nov 06, 2024 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [39db395d37](https://linux-hardware.org/?probe=39db395d37) | Nov 06, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b61fa3d781](https://linux-hardware.org/?probe=b61fa3d781) | Nov 06, 2024 |
| HP            | 83F3                        | Desktop     | [e3c4ab7715](https://linux-hardware.org/?probe=e3c4ab7715) | Nov 06, 2024 |
| Unknown       | Unknown                     | Notebook    | [e10825d9a4](https://linux-hardware.org/?probe=e10825d9a4) | Nov 06, 2024 |
| Unknown       | Unknown                     | Notebook    | [385ca86468](https://linux-hardware.org/?probe=385ca86468) | Nov 06, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [7b279ff880](https://linux-hardware.org/?probe=7b279ff880) | Nov 06, 2024 |
| Lenovo        | 3176 NOK                    | Desktop     | [5e69593bff](https://linux-hardware.org/?probe=5e69593bff) | Nov 06, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [7ebbb04692](https://linux-hardware.org/?probe=7ebbb04692) | Nov 06, 2024 |
| Lenovo        | G40-70 80GA                 | Notebook    | [ba688aca3d](https://linux-hardware.org/?probe=ba688aca3d) | Nov 05, 2024 |
| Lenovo        | G40-70 80GA                 | Notebook    | [5f8395be15](https://linux-hardware.org/?probe=5f8395be15) | Nov 05, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [91e79369d6](https://linux-hardware.org/?probe=91e79369d6) | Nov 05, 2024 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [baf7cf7f68](https://linux-hardware.org/?probe=baf7cf7f68) | Nov 05, 2024 |
| Gigabyte      | Z890 AORUS ELITE X ICE      | Desktop     | [db6488790e](https://linux-hardware.org/?probe=db6488790e) | Nov 05, 2024 |
| Gigabyte      | Z890 AORUS ELITE X ICE      | Desktop     | [35195bf24c](https://linux-hardware.org/?probe=35195bf24c) | Nov 05, 2024 |
| Chuwi         | FreeBook                    | Notebook    | [a381dac424](https://linux-hardware.org/?probe=a381dac424) | Nov 05, 2024 |
| Chuwi         | FreeBook                    | Notebook    | [3eaecb4536](https://linux-hardware.org/?probe=3eaecb4536) | Nov 05, 2024 |
| Dell          | Precision M6500             | Notebook    | [e588051942](https://linux-hardware.org/?probe=e588051942) | Nov 05, 2024 |
| Dell          | Precision M6500             | Notebook    | [e4897c55f4](https://linux-hardware.org/?probe=e4897c55f4) | Nov 05, 2024 |
| Lenovo        | ThinkPad X240 20AMS2GS00    | Notebook    | [500009e99f](https://linux-hardware.org/?probe=500009e99f) | Nov 05, 2024 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [72ad256003](https://linux-hardware.org/?probe=72ad256003) | Nov 05, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [f2fb29214a](https://linux-hardware.org/?probe=f2fb29214a) | Nov 05, 2024 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [e5c50f24d2](https://linux-hardware.org/?probe=e5c50f24d2) | Nov 04, 2024 |
| Lenovo        | ThinkPad T450s 20BX0049G... | Notebook    | [a95c95efaf](https://linux-hardware.org/?probe=a95c95efaf) | Nov 04, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [3395c22619](https://linux-hardware.org/?probe=3395c22619) | Nov 04, 2024 |
| Dell          | System XPS L502X            | Notebook    | [0780a4c2b1](https://linux-hardware.org/?probe=0780a4c2b1) | Nov 04, 2024 |
| Casper        | C17B                        | Desktop     | [5d63a37717](https://linux-hardware.org/?probe=5d63a37717) | Nov 04, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [723e6b9be2](https://linux-hardware.org/?probe=723e6b9be2) | Nov 04, 2024 |
| Pegatron      | NARRA5                      | Desktop     | [23ce1fc4eb](https://linux-hardware.org/?probe=23ce1fc4eb) | Nov 04, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [d87047b8f7](https://linux-hardware.org/?probe=d87047b8f7) | Nov 04, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [212f338f8a](https://linux-hardware.org/?probe=212f338f8a) | Nov 04, 2024 |
| ASUSTek       | GL503VD                     | Notebook    | [a6175c9826](https://linux-hardware.org/?probe=a6175c9826) | Nov 04, 2024 |
| HP            | 550                         | Notebook    | [70807a2c26](https://linux-hardware.org/?probe=70807a2c26) | Nov 04, 2024 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [4bc817a06d](https://linux-hardware.org/?probe=4bc817a06d) | Nov 03, 2024 |
| Sony          | SVE14A18ECH                 | Notebook    | [121ce83647](https://linux-hardware.org/?probe=121ce83647) | Nov 03, 2024 |
| Alienware     | 0TYR0X A00                  | Desktop     | [8ac9740dcd](https://linux-hardware.org/?probe=8ac9740dcd) | Nov 03, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [362643c5ee](https://linux-hardware.org/?probe=362643c5ee) | Nov 03, 2024 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [8163b79289](https://linux-hardware.org/?probe=8163b79289) | Nov 03, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [355fdb65ca](https://linux-hardware.org/?probe=355fdb65ca) | Nov 03, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6a6e58c0fd](https://linux-hardware.org/?probe=6a6e58c0fd) | Nov 03, 2024 |
| Acer          | Aspire 8940G                | Notebook    | [bd62e27d46](https://linux-hardware.org/?probe=bd62e27d46) | Nov 02, 2024 |
| wpc           | zrd616                      | Desktop     | [1002f7593c](https://linux-hardware.org/?probe=1002f7593c) | Nov 02, 2024 |
| Dell          | Latitude 5580               | Notebook    | [171fb01f73](https://linux-hardware.org/?probe=171fb01f73) | Nov 02, 2024 |
| HP            | 8B3B A                      | Desktop     | [169caafde2](https://linux-hardware.org/?probe=169caafde2) | Nov 02, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [3e6a954b64](https://linux-hardware.org/?probe=3e6a954b64) | Nov 02, 2024 |
| Lenovo        | ThinkPad T470 20HES2130Q    | Notebook    | [aa38d6e195](https://linux-hardware.org/?probe=aa38d6e195) | Nov 02, 2024 |
| Dell          | Latitude E6430              | Notebook    | [c2e60e88ed](https://linux-hardware.org/?probe=c2e60e88ed) | Nov 02, 2024 |
| Lenovo        | 36FE SDK0T31540 WIN 3273... | All in one  | [135ba52d4b](https://linux-hardware.org/?probe=135ba52d4b) | Nov 01, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [d993d0ced3](https://linux-hardware.org/?probe=d993d0ced3) | Nov 01, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [e0bb43c354](https://linux-hardware.org/?probe=e0bb43c354) | Nov 01, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [385c17b3d5](https://linux-hardware.org/?probe=385c17b3d5) | Nov 01, 2024 |
| Dell          | 0P096C A01                  | Desktop     | [a3a653274c](https://linux-hardware.org/?probe=a3a653274c) | Nov 01, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [747dc000aa](https://linux-hardware.org/?probe=747dc000aa) | Nov 01, 2024 |
| HP            | 805A                        | Desktop     | [92461038c0](https://linux-hardware.org/?probe=92461038c0) | Oct 31, 2024 |
| MACHINIST     | E5-MR9A V1.0                | Desktop     | [54d4d9d3ba](https://linux-hardware.org/?probe=54d4d9d3ba) | Oct 31, 2024 |
| Medion        | MS-7366                     | Desktop     | [0fe38a33d1](https://linux-hardware.org/?probe=0fe38a33d1) | Oct 31, 2024 |
| ASUSTek       | A55BM-E                     | Desktop     | [3f7b67ed7e](https://linux-hardware.org/?probe=3f7b67ed7e) | Oct 31, 2024 |
| Acer          | Aspire A115-32              | Notebook    | [d3dd3c61dd](https://linux-hardware.org/?probe=d3dd3c61dd) | Oct 31, 2024 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [cc4eefbf48](https://linux-hardware.org/?probe=cc4eefbf48) | Oct 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [dcd26cf495](https://linux-hardware.org/?probe=dcd26cf495) | Oct 31, 2024 |
| Dell          | Latitude E6540              | Notebook    | [c890aeb493](https://linux-hardware.org/?probe=c890aeb493) | Oct 30, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [5133ff315e](https://linux-hardware.org/?probe=5133ff315e) | Oct 30, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [3b59592ecd](https://linux-hardware.org/?probe=3b59592ecd) | Oct 30, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [7264124e00](https://linux-hardware.org/?probe=7264124e00) | Oct 30, 2024 |
| Dell          | Inspiron 7720               | Notebook    | [f308c7c570](https://linux-hardware.org/?probe=f308c7c570) | Oct 30, 2024 |
| Dell          | Latitude E6420              | Notebook    | [4570d16303](https://linux-hardware.org/?probe=4570d16303) | Oct 30, 2024 |
| Dell          | Latitude E6420              | Notebook    | [9870142d15](https://linux-hardware.org/?probe=9870142d15) | Oct 30, 2024 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [645dabbfd9](https://linux-hardware.org/?probe=645dabbfd9) | Oct 30, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [14b49f275b](https://linux-hardware.org/?probe=14b49f275b) | Oct 30, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [81c61ad299](https://linux-hardware.org/?probe=81c61ad299) | Oct 30, 2024 |
| Acer          | Aspire M5-583P              | Notebook    | [af4d75f50b](https://linux-hardware.org/?probe=af4d75f50b) | Oct 30, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS3... | Convertible | [721ffed217](https://linux-hardware.org/?probe=721ffed217) | Oct 30, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [c4f0ec932d](https://linux-hardware.org/?probe=c4f0ec932d) | Oct 30, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [c453bcc368](https://linux-hardware.org/?probe=c453bcc368) | Oct 30, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9e438cb0e1](https://linux-hardware.org/?probe=9e438cb0e1) | Oct 30, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [dd9ac664ef](https://linux-hardware.org/?probe=dd9ac664ef) | Oct 30, 2024 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [a0cf793a11](https://linux-hardware.org/?probe=a0cf793a11) | Oct 30, 2024 |
| Lenovo        | YB1-X91F                    | Convertible | [fa3b8ed1c2](https://linux-hardware.org/?probe=fa3b8ed1c2) | Oct 29, 2024 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [83f8e03f32](https://linux-hardware.org/?probe=83f8e03f32) | Oct 29, 2024 |
| Dell          | 0N826N A03                  | Desktop     | [0c1f187190](https://linux-hardware.org/?probe=0c1f187190) | Oct 29, 2024 |
| HUAWEI        | MCLF-XX                     | Notebook    | [6a8410a585](https://linux-hardware.org/?probe=6a8410a585) | Oct 29, 2024 |
| AZW           | SER8 V10                    | Mini pc     | [28264462a8](https://linux-hardware.org/?probe=28264462a8) | Oct 29, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7547bc75a9](https://linux-hardware.org/?probe=7547bc75a9) | Oct 29, 2024 |
| Shuttle       | FZ87                        | Desktop     | [87e4a221d2](https://linux-hardware.org/?probe=87e4a221d2) | Oct 29, 2024 |
| Acer          | Aspire 5830TG               | Notebook    | [f93513560e](https://linux-hardware.org/?probe=f93513560e) | Oct 29, 2024 |
| HUAWEI        | MCLF-XX                     | Notebook    | [eb4b7fdf89](https://linux-hardware.org/?probe=eb4b7fdf89) | Oct 29, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [f8111d2bcb](https://linux-hardware.org/?probe=f8111d2bcb) | Oct 29, 2024 |
| Intel         | Unknown                     | Notebook    | [ae6815487a](https://linux-hardware.org/?probe=ae6815487a) | Oct 29, 2024 |
| ASUSTek       | BU401LA                     | Notebook    | [544471cf95](https://linux-hardware.org/?probe=544471cf95) | Oct 29, 2024 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e84fc0d40a](https://linux-hardware.org/?probe=e84fc0d40a) | Oct 28, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [5b8bbb16a9](https://linux-hardware.org/?probe=5b8bbb16a9) | Oct 28, 2024 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | Desktop     | [c65be546ec](https://linux-hardware.org/?probe=c65be546ec) | Oct 28, 2024 |
| Dell          | Latitude 7640               | Notebook    | [db98adb76d](https://linux-hardware.org/?probe=db98adb76d) | Oct 28, 2024 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [808ef20234](https://linux-hardware.org/?probe=808ef20234) | Oct 28, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [76d1943e3b](https://linux-hardware.org/?probe=76d1943e3b) | Oct 28, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [9af6dd6ef4](https://linux-hardware.org/?probe=9af6dd6ef4) | Oct 28, 2024 |
| HP            | 3047h                       | Desktop     | [42a80cd524](https://linux-hardware.org/?probe=42a80cd524) | Oct 28, 2024 |
| HP            | 3047h                       | Desktop     | [a0af71f769](https://linux-hardware.org/?probe=a0af71f769) | Oct 28, 2024 |
| HP            | 1998                        | Desktop     | [a5201bcf6a](https://linux-hardware.org/?probe=a5201bcf6a) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [6a6fb283b0](https://linux-hardware.org/?probe=6a6fb283b0) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [08bd9a802a](https://linux-hardware.org/?probe=08bd9a802a) | Oct 28, 2024 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [2a1d98e302](https://linux-hardware.org/?probe=2a1d98e302) | Oct 27, 2024 |
| Lenovo        | ThinkPad Edge E320 1298A... | Notebook    | [db967cf215](https://linux-hardware.org/?probe=db967cf215) | Oct 27, 2024 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [729eac7b69](https://linux-hardware.org/?probe=729eac7b69) | Oct 27, 2024 |
| HP            | ProBook 4730s               | Notebook    | [8c5e435a6b](https://linux-hardware.org/?probe=8c5e435a6b) | Oct 27, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [ffb4541701](https://linux-hardware.org/?probe=ffb4541701) | Oct 27, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [26b8d8ffba](https://linux-hardware.org/?probe=26b8d8ffba) | Oct 27, 2024 |
| Sony          | VPCF12Z1E                   | Notebook    | [419e054c06](https://linux-hardware.org/?probe=419e054c06) | Oct 27, 2024 |
| Sony          | VPCF12Z1E                   | Notebook    | [f68f55bfd6](https://linux-hardware.org/?probe=f68f55bfd6) | Oct 27, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [185363085a](https://linux-hardware.org/?probe=185363085a) | Oct 27, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [1503565765](https://linux-hardware.org/?probe=1503565765) | Oct 27, 2024 |
| HP            | ProBook 4730s               | Notebook    | [98b5e041d8](https://linux-hardware.org/?probe=98b5e041d8) | Oct 27, 2024 |
| Apple         | MacBook7,1                  | Notebook    | [8031f48834](https://linux-hardware.org/?probe=8031f48834) | Oct 27, 2024 |
| MSI           | GP72 7RE                    | Notebook    | [3495e8b210](https://linux-hardware.org/?probe=3495e8b210) | Oct 27, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [d561713c17](https://linux-hardware.org/?probe=d561713c17) | Oct 27, 2024 |
| Medion        | MS-7366                     | Desktop     | [786514f25e](https://linux-hardware.org/?probe=786514f25e) | Oct 27, 2024 |
| HP            | 8158 A01                    | Mini pc     | [31d2d49a69](https://linux-hardware.org/?probe=31d2d49a69) | Oct 27, 2024 |
| HP            | 8158 A01                    | Mini pc     | [dc60936a78](https://linux-hardware.org/?probe=dc60936a78) | Oct 27, 2024 |
| Juana Mans... | SF20GM7                     | Notebook    | [0b2f896cf6](https://linux-hardware.org/?probe=0b2f896cf6) | Oct 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [08b6a5d7d3](https://linux-hardware.org/?probe=08b6a5d7d3) | Oct 26, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [4ab4fd20bc](https://linux-hardware.org/?probe=4ab4fd20bc) | Oct 26, 2024 |
| Unknown       | CherryTrail                 | Notebook    | [be2389a1f2](https://linux-hardware.org/?probe=be2389a1f2) | Oct 26, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [7b016cc848](https://linux-hardware.org/?probe=7b016cc848) | Oct 26, 2024 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [dcdaf50f9f](https://linux-hardware.org/?probe=dcdaf50f9f) | Oct 26, 2024 |
| HP            | 2B2F MVB,A                  | All in one  | [006b770f80](https://linux-hardware.org/?probe=006b770f80) | Oct 26, 2024 |
| Gigabyte      | GA-E350N-USB3               | Desktop     | [7225d38fe2](https://linux-hardware.org/?probe=7225d38fe2) | Oct 25, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | Notebook    | [7f94eafaf2](https://linux-hardware.org/?probe=7f94eafaf2) | Oct 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4b872572eb](https://linux-hardware.org/?probe=4b872572eb) | Oct 25, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | Notebook    | [20e158e9fb](https://linux-hardware.org/?probe=20e158e9fb) | Oct 25, 2024 |
| Quanta        | XV1                         | All in one  | [6ce5faf821](https://linux-hardware.org/?probe=6ce5faf821) | Oct 25, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [ff5be70e84](https://linux-hardware.org/?probe=ff5be70e84) | Oct 25, 2024 |
| Gigabyte      | GA-E350N-USB3               | Desktop     | [95f022084d](https://linux-hardware.org/?probe=95f022084d) | Oct 25, 2024 |
| Unknown       | W1415A                      | Notebook    | [d8206d7318](https://linux-hardware.org/?probe=d8206d7318) | Oct 24, 2024 |
| ASUSTek       | K50C                        | Notebook    | [4da330858c](https://linux-hardware.org/?probe=4da330858c) | Oct 24, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7d6371be67](https://linux-hardware.org/?probe=7d6371be67) | Oct 24, 2024 |
| AZW           | SER8 V10                    | Mini pc     | [d38d39d4ce](https://linux-hardware.org/?probe=d38d39d4ce) | Oct 24, 2024 |
| ASUSTek       | P50IJ                       | Notebook    | [bf855fcb57](https://linux-hardware.org/?probe=bf855fcb57) | Oct 24, 2024 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [d6561c30ac](https://linux-hardware.org/?probe=d6561c30ac) | Oct 24, 2024 |
| Dell          | 0YJPT1 A00                  | Desktop     | [cf6085e6f9](https://linux-hardware.org/?probe=cf6085e6f9) | Oct 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0a783a20c1](https://linux-hardware.org/?probe=0a783a20c1) | Oct 24, 2024 |
| Unknown       | YEPBOOK PRO                 | Notebook    | [0d3c07610a](https://linux-hardware.org/?probe=0d3c07610a) | Oct 24, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [34af986c90](https://linux-hardware.org/?probe=34af986c90) | Oct 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0bd767b322](https://linux-hardware.org/?probe=0bd767b322) | Oct 23, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [7abf782ae9](https://linux-hardware.org/?probe=7abf782ae9) | Oct 23, 2024 |
| MSI           | B365M PRO-VDH               | Desktop     | [191f1bfd03](https://linux-hardware.org/?probe=191f1bfd03) | Oct 23, 2024 |
| Fujitsu Si... | AMILO Li 1718               | Notebook    | [8343c4f1d5](https://linux-hardware.org/?probe=8343c4f1d5) | Oct 23, 2024 |
| Fujitsu Si... | AMILO Li 1718               | Notebook    | [5873adb522](https://linux-hardware.org/?probe=5873adb522) | Oct 23, 2024 |
| MSI           | H81M-E33                    | Desktop     | [ab67b3a504](https://linux-hardware.org/?probe=ab67b3a504) | Oct 23, 2024 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [466c92fa21](https://linux-hardware.org/?probe=466c92fa21) | Oct 23, 2024 |
| MSI           | B365M PRO-VDH               | Desktop     | [3356b35619](https://linux-hardware.org/?probe=3356b35619) | Oct 23, 2024 |
| Apple         | MacBookAir7,1               | Notebook    | [3b54b1a84a](https://linux-hardware.org/?probe=3b54b1a84a) | Oct 23, 2024 |
| Apple         | MacBookAir7,1               | Notebook    | [8915d8d3bb](https://linux-hardware.org/?probe=8915d8d3bb) | Oct 23, 2024 |
| Unknown       | X79                         | Desktop     | [a454957608](https://linux-hardware.org/?probe=a454957608) | Oct 23, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [995eebde68](https://linux-hardware.org/?probe=995eebde68) | Oct 22, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [5089c146d6](https://linux-hardware.org/?probe=5089c146d6) | Oct 22, 2024 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a915ce3cad](https://linux-hardware.org/?probe=a915ce3cad) | Oct 22, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [97d5a16066](https://linux-hardware.org/?probe=97d5a16066) | Oct 22, 2024 |
| HP            | EliteBook 820 G2            | Notebook    | [8b3172d505](https://linux-hardware.org/?probe=8b3172d505) | Oct 22, 2024 |
| Dell          | Latitude 5490               | Notebook    | [3cabfe000a](https://linux-hardware.org/?probe=3cabfe000a) | Oct 22, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [c9ee515b39](https://linux-hardware.org/?probe=c9ee515b39) | Oct 22, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [15ebc4270f](https://linux-hardware.org/?probe=15ebc4270f) | Oct 21, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [f610cef4b5](https://linux-hardware.org/?probe=f610cef4b5) | Oct 21, 2024 |
| AVITA         | NS12T5                      | Tablet      | [d3ac0f6a92](https://linux-hardware.org/?probe=d3ac0f6a92) | Oct 21, 2024 |
| GEO           | GeoBook 240                 | Notebook    | [e7fdf54200](https://linux-hardware.org/?probe=e7fdf54200) | Oct 21, 2024 |
| ASUSTek       | K52JV                       | Notebook    | [3079996867](https://linux-hardware.org/?probe=3079996867) | Oct 21, 2024 |
| ECS           | GeForce6100PM-M2            | Desktop     | [ba0d87fee9](https://linux-hardware.org/?probe=ba0d87fee9) | Oct 21, 2024 |
| ASUSTek       | X441BA                      | Notebook    | [0481eb3049](https://linux-hardware.org/?probe=0481eb3049) | Oct 21, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [bb6af03bf3](https://linux-hardware.org/?probe=bb6af03bf3) | Oct 21, 2024 |
| Toshiba       | PORTEGE Z830                | Notebook    | [1d5f4bb615](https://linux-hardware.org/?probe=1d5f4bb615) | Oct 20, 2024 |
| Toshiba       | Satellite Pro C50-A-1K9     | Notebook    | [ee0af1751a](https://linux-hardware.org/?probe=ee0af1751a) | Oct 20, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [2f0d46fb23](https://linux-hardware.org/?probe=2f0d46fb23) | Oct 20, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [3d4a61447f](https://linux-hardware.org/?probe=3d4a61447f) | Oct 20, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [5ddfbb59eb](https://linux-hardware.org/?probe=5ddfbb59eb) | Oct 20, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [9f30927210](https://linux-hardware.org/?probe=9f30927210) | Oct 20, 2024 |
| HP            | 82F2 A01                    | Desktop     | [22bea705e2](https://linux-hardware.org/?probe=22bea705e2) | Oct 20, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [5cc130f16e](https://linux-hardware.org/?probe=5cc130f16e) | Oct 20, 2024 |
| Sony          | VPCEL3S1E                   | Notebook    | [befb361f1e](https://linux-hardware.org/?probe=befb361f1e) | Oct 20, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7fc2990d42](https://linux-hardware.org/?probe=7fc2990d42) | Oct 20, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cd7d1f8910](https://linux-hardware.org/?probe=cd7d1f8910) | Oct 20, 2024 |
| Acer          | Aspire V5-123               | Notebook    | [a47bf6ca57](https://linux-hardware.org/?probe=a47bf6ca57) | Oct 20, 2024 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [097be855e6](https://linux-hardware.org/?probe=097be855e6) | Oct 20, 2024 |
| ASUSTek       | X556UQ                      | Notebook    | [046fdf8e88](https://linux-hardware.org/?probe=046fdf8e88) | Oct 19, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [2882c1b751](https://linux-hardware.org/?probe=2882c1b751) | Oct 19, 2024 |
| ASRock        | Z77 Pro4                    | Desktop     | [484a1c621c](https://linux-hardware.org/?probe=484a1c621c) | Oct 19, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [5754b92f35](https://linux-hardware.org/?probe=5754b92f35) | Oct 19, 2024 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [d486c0f3cc](https://linux-hardware.org/?probe=d486c0f3cc) | Oct 19, 2024 |
| Samsung       | 370E4K                      | Notebook    | [5316144029](https://linux-hardware.org/?probe=5316144029) | Oct 19, 2024 |
| ASUSTek       | G55VW                       | Notebook    | [a1b8fade8a](https://linux-hardware.org/?probe=a1b8fade8a) | Oct 19, 2024 |
| HP            | 15                          | Notebook    | [b9758a830e](https://linux-hardware.org/?probe=b9758a830e) | Oct 19, 2024 |
| HP            | 15                          | Notebook    | [2219fa443f](https://linux-hardware.org/?probe=2219fa443f) | Oct 19, 2024 |
| Samsung       | 370E4K                      | Notebook    | [72b8154d51](https://linux-hardware.org/?probe=72b8154d51) | Oct 19, 2024 |
| ASRock        | X670E PG Lightning          | Notebook    | [a82784b122](https://linux-hardware.org/?probe=a82784b122) | Oct 19, 2024 |
| Sony          | VPCEL3S1E                   | Notebook    | [7dd43d769b](https://linux-hardware.org/?probe=7dd43d769b) | Oct 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | Desktop     | [6a3b145dbc](https://linux-hardware.org/?probe=6a3b145dbc) | Oct 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | Desktop     | [464acfecba](https://linux-hardware.org/?probe=464acfecba) | Oct 19, 2024 |
| Exo           | Smart Serie L               | Notebook    | [0ca04a37d8](https://linux-hardware.org/?probe=0ca04a37d8) | Oct 19, 2024 |
| Exo           | Smart Serie L               | Notebook    | [c2c7184260](https://linux-hardware.org/?probe=c2c7184260) | Oct 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [c494c18d97](https://linux-hardware.org/?probe=c494c18d97) | Oct 18, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [15d2f1b66d](https://linux-hardware.org/?probe=15d2f1b66d) | Oct 18, 2024 |
| HP            | G42                         | Notebook    | [72bf54ec1e](https://linux-hardware.org/?probe=72bf54ec1e) | Oct 18, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [1494cb934c](https://linux-hardware.org/?probe=1494cb934c) | Oct 18, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [83c00e0695](https://linux-hardware.org/?probe=83c00e0695) | Oct 18, 2024 |
| ASUSTek       | P5G41-M LX                  | Desktop     | [02f29e0739](https://linux-hardware.org/?probe=02f29e0739) | Oct 18, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7d19f92203](https://linux-hardware.org/?probe=7d19f92203) | Oct 18, 2024 |
| Dell          | XPS 13 9365                 | Convertible | [c9e2ec979b](https://linux-hardware.org/?probe=c9e2ec979b) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [7e4fe6c29c](https://linux-hardware.org/?probe=7e4fe6c29c) | Oct 18, 2024 |
| Dell          | 07F37C A00                  | Desktop     | [10c1d68877](https://linux-hardware.org/?probe=10c1d68877) | Oct 17, 2024 |
| Dell          | 0JP3NX A01                  | Desktop     | [591b9985d6](https://linux-hardware.org/?probe=591b9985d6) | Oct 17, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [717f10e863](https://linux-hardware.org/?probe=717f10e863) | Oct 17, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [3ffc7f702a](https://linux-hardware.org/?probe=3ffc7f702a) | Oct 17, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [58861dc8f9](https://linux-hardware.org/?probe=58861dc8f9) | Oct 17, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [b9a1fce690](https://linux-hardware.org/?probe=b9a1fce690) | Oct 17, 2024 |
| Packard Be... | EasyNote_MX37-U-056NL       | Notebook    | [7a6a98e8e7](https://linux-hardware.org/?probe=7a6a98e8e7) | Oct 17, 2024 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [1b7e79796e](https://linux-hardware.org/?probe=1b7e79796e) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | Notebook    | [d8b92ea891](https://linux-hardware.org/?probe=d8b92ea891) | Oct 17, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [260d61bcf0](https://linux-hardware.org/?probe=260d61bcf0) | Oct 17, 2024 |
| HP            | 3648h                       | Desktop     | [0aff8ec887](https://linux-hardware.org/?probe=0aff8ec887) | Oct 17, 2024 |
| Gigabyte      | P55A-UD5                    | Desktop     | [427287ea8d](https://linux-hardware.org/?probe=427287ea8d) | Oct 16, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | Desktop     | [7ad6aad489](https://linux-hardware.org/?probe=7ad6aad489) | Oct 16, 2024 |
| Positivo      | C8256AI-15                  | Notebook    | [c3bad33452](https://linux-hardware.org/?probe=c3bad33452) | Oct 16, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [ea6b8939d2](https://linux-hardware.org/?probe=ea6b8939d2) | Oct 16, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [42860ad3af](https://linux-hardware.org/?probe=42860ad3af) | Oct 16, 2024 |
| Sony          | SVE1711V1EB                 | Notebook    | [f57853bbf9](https://linux-hardware.org/?probe=f57853bbf9) | Oct 16, 2024 |
| Sony          | SVE1711V1EB                 | Notebook    | [8cfbbedec2](https://linux-hardware.org/?probe=8cfbbedec2) | Oct 16, 2024 |
| itel Mobil... | Epic 1                      | Notebook    | [b99b7f9e7a](https://linux-hardware.org/?probe=b99b7f9e7a) | Oct 16, 2024 |
| Sony          | VGN-AR41S                   | Notebook    | [d41cbf35f9](https://linux-hardware.org/?probe=d41cbf35f9) | Oct 16, 2024 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [c498134667](https://linux-hardware.org/?probe=c498134667) | Oct 16, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [fc05d76312](https://linux-hardware.org/?probe=fc05d76312) | Oct 16, 2024 |
| Dell          | Latitude 3440               | Notebook    | [d6d3377f4d](https://linux-hardware.org/?probe=d6d3377f4d) | Oct 16, 2024 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [bc56e44248](https://linux-hardware.org/?probe=bc56e44248) | Oct 16, 2024 |
| HP            | ProBook 4510s               | Notebook    | [82921bfaa3](https://linux-hardware.org/?probe=82921bfaa3) | Oct 16, 2024 |
| Dell          | 033FF6 A00                  | Desktop     | [eb7537a3dd](https://linux-hardware.org/?probe=eb7537a3dd) | Oct 15, 2024 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [abe078a53a](https://linux-hardware.org/?probe=abe078a53a) | Oct 15, 2024 |
| Intel         | Unknown                     | Notebook    | [800aa4f46b](https://linux-hardware.org/?probe=800aa4f46b) | Oct 15, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [b4b50a0e63](https://linux-hardware.org/?probe=b4b50a0e63) | Oct 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | Notebook    | [ae22524e06](https://linux-hardware.org/?probe=ae22524e06) | Oct 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | Notebook    | [e86ff90245](https://linux-hardware.org/?probe=e86ff90245) | Oct 15, 2024 |
| Getac         | B300G5                      | Notebook    | [5de20509e3](https://linux-hardware.org/?probe=5de20509e3) | Oct 15, 2024 |
| Quanta        | XV1                         | All in one  | [78ac1f0275](https://linux-hardware.org/?probe=78ac1f0275) | Oct 15, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [80a134427f](https://linux-hardware.org/?probe=80a134427f) | Oct 15, 2024 |
| OEM           | X79G                        | Desktop     | [c6b10f3799](https://linux-hardware.org/?probe=c6b10f3799) | Oct 14, 2024 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [3daad6b7aa](https://linux-hardware.org/?probe=3daad6b7aa) | Oct 14, 2024 |
| Alienware     | 0P0JWX A00                  | Desktop     | [c2a8e068bd](https://linux-hardware.org/?probe=c2a8e068bd) | Oct 14, 2024 |
| ASUSTek       | G10CE                       | Desktop     | [752a87865a](https://linux-hardware.org/?probe=752a87865a) | Oct 14, 2024 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [8fba64a511](https://linux-hardware.org/?probe=8fba64a511) | Oct 13, 2024 |
| Dell          | Latitude 3540               | Notebook    | [08840c6bb5](https://linux-hardware.org/?probe=08840c6bb5) | Oct 13, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [1dd7fc6421](https://linux-hardware.org/?probe=1dd7fc6421) | Oct 13, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [2a5b1c44cc](https://linux-hardware.org/?probe=2a5b1c44cc) | Oct 13, 2024 |
| Dell          | Precision M4500             | Notebook    | [61cc876a50](https://linux-hardware.org/?probe=61cc876a50) | Oct 13, 2024 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [f8f51b5bdb](https://linux-hardware.org/?probe=f8f51b5bdb) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [abb2c26d54](https://linux-hardware.org/?probe=abb2c26d54) | Oct 13, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b59a4de42d](https://linux-hardware.org/?probe=b59a4de42d) | Oct 13, 2024 |
| Dell          | Latitude E7450              | Notebook    | [7119b42c95](https://linux-hardware.org/?probe=7119b42c95) | Oct 13, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [e297bab7ce](https://linux-hardware.org/?probe=e297bab7ce) | Oct 13, 2024 |
| Dell          | 0XPDFK A01                  | Desktop     | [5b41e36020](https://linux-hardware.org/?probe=5b41e36020) | Oct 12, 2024 |
| Dell          | 0XPDFK A01                  | Desktop     | [feea088ac3](https://linux-hardware.org/?probe=feea088ac3) | Oct 12, 2024 |
| ASUSTek       | K50C                        | Notebook    | [8618444a5d](https://linux-hardware.org/?probe=8618444a5d) | Oct 12, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d8c217d807](https://linux-hardware.org/?probe=d8c217d807) | Oct 12, 2024 |
| ASUSTek       | G55VW                       | Notebook    | [101bba7262](https://linux-hardware.org/?probe=101bba7262) | Oct 12, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | Notebook    | [8e06db2e61](https://linux-hardware.org/?probe=8e06db2e61) | Oct 11, 2024 |
| HUAWEI        | FLMH-XX                     | Notebook    | [b05f724fb4](https://linux-hardware.org/?probe=b05f724fb4) | Oct 11, 2024 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [21f53b5459](https://linux-hardware.org/?probe=21f53b5459) | Oct 11, 2024 |
| HUAWEI        | FLMH-XX                     | Notebook    | [1467f8690d](https://linux-hardware.org/?probe=1467f8690d) | Oct 11, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [504f098627](https://linux-hardware.org/?probe=504f098627) | Oct 11, 2024 |
| Dell          | Latitude E7450              | Notebook    | [b5f8c62bb7](https://linux-hardware.org/?probe=b5f8c62bb7) | Oct 11, 2024 |
| Acer          | Aspire M5-583P              | Notebook    | [ff2ac16a5d](https://linux-hardware.org/?probe=ff2ac16a5d) | Oct 11, 2024 |
| HP            | 1000                        | Notebook    | [27c136a8c5](https://linux-hardware.org/?probe=27c136a8c5) | Oct 11, 2024 |
| GMKtec        | NucBox G3                   | Other       | [103be64c81](https://linux-hardware.org/?probe=103be64c81) | Oct 11, 2024 |
| Dell          | Latitude 7430               | Notebook    | [fbee722228](https://linux-hardware.org/?probe=fbee722228) | Oct 11, 2024 |
| OEM           | Unknown                     | Notebook    | [ceb87bcdba](https://linux-hardware.org/?probe=ceb87bcdba) | Oct 11, 2024 |
| Samsung       | 550XBE/350XBE               | Notebook    | [f6303aadd6](https://linux-hardware.org/?probe=f6303aadd6) | Oct 11, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [19bda37f58](https://linux-hardware.org/?probe=19bda37f58) | Oct 10, 2024 |
| AZW           | SER V01                     | Mini pc     | [57886498ac](https://linux-hardware.org/?probe=57886498ac) | Oct 10, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [6049e27844](https://linux-hardware.org/?probe=6049e27844) | Oct 10, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [98ce6f6b57](https://linux-hardware.org/?probe=98ce6f6b57) | Oct 10, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [04dbd52935](https://linux-hardware.org/?probe=04dbd52935) | Oct 10, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [8ecca901ac](https://linux-hardware.org/?probe=8ecca901ac) | Oct 10, 2024 |
| HP            | 455                         | Notebook    | [1cf38a08fd](https://linux-hardware.org/?probe=1cf38a08fd) | Oct 10, 2024 |
| ECS           | Iris8                       | Desktop     | [7ebf751b4d](https://linux-hardware.org/?probe=7ebf751b4d) | Oct 10, 2024 |
| HP            | EliteBook 8760w             | Notebook    | [26485c8559](https://linux-hardware.org/?probe=26485c8559) | Oct 09, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [2906c94383](https://linux-hardware.org/?probe=2906c94383) | Oct 09, 2024 |
| Gigabyte      | B150M-D3P-WG-CF             | Desktop     | [de88d62e95](https://linux-hardware.org/?probe=de88d62e95) | Oct 09, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [ed859cf79b](https://linux-hardware.org/?probe=ed859cf79b) | Oct 09, 2024 |
| Gigabyte      | B150M-D3P-WG-CF             | Desktop     | [d0e808d5c5](https://linux-hardware.org/?probe=d0e808d5c5) | Oct 09, 2024 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [6feeb04bd6](https://linux-hardware.org/?probe=6feeb04bd6) | Oct 09, 2024 |
| Toshiba       | Satellite C855-29M          | Notebook    | [759aa92d05](https://linux-hardware.org/?probe=759aa92d05) | Oct 09, 2024 |
| Dell          | Latitude E7440              | Notebook    | [d319ecb94f](https://linux-hardware.org/?probe=d319ecb94f) | Oct 09, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [3258142b11](https://linux-hardware.org/?probe=3258142b11) | Oct 09, 2024 |
| Dell          | Latitude E7440              | Notebook    | [4db806b12e](https://linux-hardware.org/?probe=4db806b12e) | Oct 09, 2024 |
| HP            | 3648h                       | Desktop     | [0920749527](https://linux-hardware.org/?probe=0920749527) | Oct 09, 2024 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1205d137c5](https://linux-hardware.org/?probe=1205d137c5) | Oct 09, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a41400db8d](https://linux-hardware.org/?probe=a41400db8d) | Oct 09, 2024 |
| Itautec       | W7655                       | Notebook    | [b423f7e91d](https://linux-hardware.org/?probe=b423f7e91d) | Oct 09, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | Notebook    | [4994171903](https://linux-hardware.org/?probe=4994171903) | Oct 09, 2024 |
| Exo           | EXOMATE X5                  | Notebook    | [0db79727e7](https://linux-hardware.org/?probe=0db79727e7) | Oct 08, 2024 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [c5c62657ee](https://linux-hardware.org/?probe=c5c62657ee) | Oct 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [290c3faa24](https://linux-hardware.org/?probe=290c3faa24) | Oct 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [ae49c8f2cb](https://linux-hardware.org/?probe=ae49c8f2cb) | Oct 08, 2024 |
| Dell          | 0NVFV9 A00                  | All in one  | [2fe91b25be](https://linux-hardware.org/?probe=2fe91b25be) | Oct 08, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [05330a1c5b](https://linux-hardware.org/?probe=05330a1c5b) | Oct 08, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [03c799451f](https://linux-hardware.org/?probe=03c799451f) | Oct 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [51d8f5f774](https://linux-hardware.org/?probe=51d8f5f774) | Oct 08, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [323ebbba62](https://linux-hardware.org/?probe=323ebbba62) | Oct 08, 2024 |
| Acer          | Extensa 5620                | Notebook    | [82f3c9f52b](https://linux-hardware.org/?probe=82f3c9f52b) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [8253f323a0](https://linux-hardware.org/?probe=8253f323a0) | Oct 07, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [6273853b03](https://linux-hardware.org/?probe=6273853b03) | Oct 07, 2024 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [83d59869de](https://linux-hardware.org/?probe=83d59869de) | Oct 07, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [69db239040](https://linux-hardware.org/?probe=69db239040) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ab67f0f4c4](https://linux-hardware.org/?probe=ab67f0f4c4) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8dfb3bab34](https://linux-hardware.org/?probe=8dfb3bab34) | Oct 07, 2024 |
| Unknown       | W1415A                      | Notebook    | [a0c0ca59b5](https://linux-hardware.org/?probe=a0c0ca59b5) | Oct 07, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [92e702792f](https://linux-hardware.org/?probe=92e702792f) | Oct 07, 2024 |
| Alienware     | 0446JC A01                  | Desktop     | [7bc596b378](https://linux-hardware.org/?probe=7bc596b378) | Oct 07, 2024 |
| ASUSTek       | PRIME H310M-F R2.0          | Desktop     | [1b09e0c3c0](https://linux-hardware.org/?probe=1b09e0c3c0) | Oct 06, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [ca7c7ed0b0](https://linux-hardware.org/?probe=ca7c7ed0b0) | Oct 06, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | Notebook    | [ef61fde952](https://linux-hardware.org/?probe=ef61fde952) | Oct 06, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [bc06f61edf](https://linux-hardware.org/?probe=bc06f61edf) | Oct 06, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0dbb83780d](https://linux-hardware.org/?probe=0dbb83780d) | Oct 06, 2024 |
| ASUSTek       | T300LA                      | Notebook    | [b6e3dc4b6e](https://linux-hardware.org/?probe=b6e3dc4b6e) | Oct 06, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [9d8638d734](https://linux-hardware.org/?probe=9d8638d734) | Oct 06, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [567e4c6343](https://linux-hardware.org/?probe=567e4c6343) | Oct 06, 2024 |
| ASUSTek       | UX31E                       | Notebook    | [f8881d8b4e](https://linux-hardware.org/?probe=f8881d8b4e) | Oct 06, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [00e8066675](https://linux-hardware.org/?probe=00e8066675) | Oct 06, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [37e187d1c9](https://linux-hardware.org/?probe=37e187d1c9) | Oct 06, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4ecb717139](https://linux-hardware.org/?probe=4ecb717139) | Oct 06, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [4e30f006ed](https://linux-hardware.org/?probe=4e30f006ed) | Oct 06, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [e85e0d90e6](https://linux-hardware.org/?probe=e85e0d90e6) | Oct 05, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [c14b9319d4](https://linux-hardware.org/?probe=c14b9319d4) | Oct 05, 2024 |
| ASRock        | H61M-DGS                    | Desktop     | [6bdbe5bc33](https://linux-hardware.org/?probe=6bdbe5bc33) | Oct 05, 2024 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [fe5bb258a3](https://linux-hardware.org/?probe=fe5bb258a3) | Oct 05, 2024 |
| Dell          | Latitude D630               | Notebook    | [329c0abded](https://linux-hardware.org/?probe=329c0abded) | Oct 05, 2024 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [793d87adb1](https://linux-hardware.org/?probe=793d87adb1) | Oct 05, 2024 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [1856abb0a4](https://linux-hardware.org/?probe=1856abb0a4) | Oct 05, 2024 |
| Biostar       | A320MH                      | Desktop     | [c281d9f2aa](https://linux-hardware.org/?probe=c281d9f2aa) | Oct 05, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [0c7aff3c04](https://linux-hardware.org/?probe=0c7aff3c04) | Oct 05, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | Desktop     | [229998424d](https://linux-hardware.org/?probe=229998424d) | Oct 05, 2024 |
| Lenovo        | G550 2958                   | Notebook    | [93d0e9368e](https://linux-hardware.org/?probe=93d0e9368e) | Oct 05, 2024 |
| HP            | Snappy                      | Notebook    | [437d8947c4](https://linux-hardware.org/?probe=437d8947c4) | Oct 04, 2024 |
| HP            | Snappy                      | Notebook    | [4aac934df2](https://linux-hardware.org/?probe=4aac934df2) | Oct 04, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fbed489d65](https://linux-hardware.org/?probe=fbed489d65) | Oct 03, 2024 |
| Alienware     | 0446JC A01                  | Desktop     | [60b8cc6ef1](https://linux-hardware.org/?probe=60b8cc6ef1) | Oct 03, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [49a3a7f013](https://linux-hardware.org/?probe=49a3a7f013) | Oct 03, 2024 |
| ASUSTek       | X75VBP                      | Notebook    | [0c6a739c42](https://linux-hardware.org/?probe=0c6a739c42) | Oct 03, 2024 |
| ASUSTek       | X75VBP                      | Notebook    | [b34a212443](https://linux-hardware.org/?probe=b34a212443) | Oct 03, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [632dfc1140](https://linux-hardware.org/?probe=632dfc1140) | Oct 02, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [86046789e4](https://linux-hardware.org/?probe=86046789e4) | Oct 02, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1e94397b11](https://linux-hardware.org/?probe=1e94397b11) | Oct 02, 2024 |
| Dell          | Latitude 3420               | Notebook    | [621cf7dbc5](https://linux-hardware.org/?probe=621cf7dbc5) | Oct 02, 2024 |
| LG Electro... | 22V280 FAB1                 | All in one  | [ea5f223ff6](https://linux-hardware.org/?probe=ea5f223ff6) | Oct 02, 2024 |
| ASRock        | Z790 Pro RS/D4              | Desktop     | [fbe99fdf47](https://linux-hardware.org/?probe=fbe99fdf47) | Oct 02, 2024 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [690a6356bc](https://linux-hardware.org/?probe=690a6356bc) | Oct 01, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [e9a9dd5664](https://linux-hardware.org/?probe=e9a9dd5664) | Oct 01, 2024 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [94201090b9](https://linux-hardware.org/?probe=94201090b9) | Oct 01, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [ca529d5234](https://linux-hardware.org/?probe=ca529d5234) | Oct 01, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | Desktop     | [7a2d2bacd1](https://linux-hardware.org/?probe=7a2d2bacd1) | Oct 01, 2024 |
| MOTILE        | M141                        | Notebook    | [de62b8afab](https://linux-hardware.org/?probe=de62b8afab) | Oct 01, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [7cbe0719e7](https://linux-hardware.org/?probe=7cbe0719e7) | Oct 01, 2024 |
| HP            | Stream Notebook PC 11       | Notebook    | [075ac358e1](https://linux-hardware.org/?probe=075ac358e1) | Oct 01, 2024 |
| Intel         | X79G-A V2.0                 | Desktop     | [a1557bdeba](https://linux-hardware.org/?probe=a1557bdeba) | Oct 01, 2024 |
| ECS           | H61H2-MV                    | Desktop     | [29d29072da](https://linux-hardware.org/?probe=29d29072da) | Oct 01, 2024 |
| ASRock        | H61M-VS4                    | Desktop     | [14561e27dc](https://linux-hardware.org/?probe=14561e27dc) | Oct 01, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a53d5826f1](https://linux-hardware.org/?probe=a53d5826f1) | Oct 01, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [63301b1c31](https://linux-hardware.org/?probe=63301b1c31) | Sep 30, 2024 |
| Dell          | Latitude E6520              | Notebook    | [4ed4a2acc3](https://linux-hardware.org/?probe=4ed4a2acc3) | Sep 30, 2024 |
| Intel         | X79G-A V2.0                 | Desktop     | [b5e98605a4](https://linux-hardware.org/?probe=b5e98605a4) | Sep 30, 2024 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [89b9efdf37](https://linux-hardware.org/?probe=89b9efdf37) | Sep 30, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [22b4245aa3](https://linux-hardware.org/?probe=22b4245aa3) | Sep 30, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [9c0542b834](https://linux-hardware.org/?probe=9c0542b834) | Sep 30, 2024 |
| Unknown       | Unknown                     | Notebook    | [b2ac2537df](https://linux-hardware.org/?probe=b2ac2537df) | Sep 29, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [64a20e4d8c](https://linux-hardware.org/?probe=64a20e4d8c) | Sep 29, 2024 |
| Dell          | 0FM586                      | Desktop     | [67cb39d9d4](https://linux-hardware.org/?probe=67cb39d9d4) | Sep 29, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [6696fe76a8](https://linux-hardware.org/?probe=6696fe76a8) | Sep 29, 2024 |
| Dell          | Inspiron 3459               | Notebook    | [f36d24d646](https://linux-hardware.org/?probe=f36d24d646) | Sep 29, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [680a669b9e](https://linux-hardware.org/?probe=680a669b9e) | Sep 29, 2024 |
| SGIN          | M15                         | Notebook    | [16d90e5195](https://linux-hardware.org/?probe=16d90e5195) | Sep 29, 2024 |
| ASRock        | J3355B-ITX                  | Desktop     | [3d82bcbf1c](https://linux-hardware.org/?probe=3d82bcbf1c) | Sep 29, 2024 |
| ASRock        | J3355B-ITX                  | Desktop     | [2e9ef6e2bc](https://linux-hardware.org/?probe=2e9ef6e2bc) | Sep 29, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [fc1ea5dd8c](https://linux-hardware.org/?probe=fc1ea5dd8c) | Sep 28, 2024 |
| Acer          | Aspire ES1-711              | Notebook    | [b68a5e4910](https://linux-hardware.org/?probe=b68a5e4910) | Sep 28, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [5f637ddf6b](https://linux-hardware.org/?probe=5f637ddf6b) | Sep 28, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [77cd5b5988](https://linux-hardware.org/?probe=77cd5b5988) | Sep 28, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [d59e554ef6](https://linux-hardware.org/?probe=d59e554ef6) | Sep 28, 2024 |
| HP            | 3647h                       | Desktop     | [a7f7f8a677](https://linux-hardware.org/?probe=a7f7f8a677) | Sep 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b3a8e4c5e9](https://linux-hardware.org/?probe=b3a8e4c5e9) | Sep 28, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [e829303e25](https://linux-hardware.org/?probe=e829303e25) | Sep 27, 2024 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [e893a6c80e](https://linux-hardware.org/?probe=e893a6c80e) | Sep 27, 2024 |
| Digibras      | NH4CU53                     | Notebook    | [7254433879](https://linux-hardware.org/?probe=7254433879) | Sep 27, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6ac57e29ba](https://linux-hardware.org/?probe=6ac57e29ba) | Sep 27, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [57f528793e](https://linux-hardware.org/?probe=57f528793e) | Sep 27, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [04b943d1ad](https://linux-hardware.org/?probe=04b943d1ad) | Sep 27, 2024 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [0f503c4d45](https://linux-hardware.org/?probe=0f503c4d45) | Sep 27, 2024 |
| Gigabyte      | B760 DS3H                   | Desktop     | [740eb5ea15](https://linux-hardware.org/?probe=740eb5ea15) | Sep 27, 2024 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [c891f656c5](https://linux-hardware.org/?probe=c891f656c5) | Sep 27, 2024 |
| Quanta        | XV1                         | All in one  | [58aa972695](https://linux-hardware.org/?probe=58aa972695) | Sep 27, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [67736c95b5](https://linux-hardware.org/?probe=67736c95b5) | Sep 27, 2024 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [8dc1f740de](https://linux-hardware.org/?probe=8dc1f740de) | Sep 26, 2024 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [0df47e18d9](https://linux-hardware.org/?probe=0df47e18d9) | Sep 26, 2024 |
| LG Electro... | R510                        | Notebook    | [a37143fb1e](https://linux-hardware.org/?probe=a37143fb1e) | Sep 26, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [f4d0cccdf1](https://linux-hardware.org/?probe=f4d0cccdf1) | Sep 26, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [93b881282f](https://linux-hardware.org/?probe=93b881282f) | Sep 26, 2024 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [116c290a50](https://linux-hardware.org/?probe=116c290a50) | Sep 26, 2024 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [7d35226fe2](https://linux-hardware.org/?probe=7d35226fe2) | Sep 26, 2024 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [355059e70a](https://linux-hardware.org/?probe=355059e70a) | Sep 26, 2024 |
| Dell          | Latitude 7640               | Notebook    | [c90fe866d1](https://linux-hardware.org/?probe=c90fe866d1) | Sep 26, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [a524e39cfb](https://linux-hardware.org/?probe=a524e39cfb) | Sep 26, 2024 |
| Gigabyte      | F2A78M-DASHV                | Desktop     | [ebba91d68c](https://linux-hardware.org/?probe=ebba91d68c) | Sep 26, 2024 |
| Google        | Peppy                       | Notebook    | [43b1f58c7d](https://linux-hardware.org/?probe=43b1f58c7d) | Sep 26, 2024 |
| ASUSTek       | K73SD                       | Notebook    | [f177a48833](https://linux-hardware.org/?probe=f177a48833) | Sep 26, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [e2b213efc7](https://linux-hardware.org/?probe=e2b213efc7) | Sep 25, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcf3d67e7b](https://linux-hardware.org/?probe=fcf3d67e7b) | Sep 25, 2024 |
| Dell          | Inspiron 5447               | Notebook    | [4543c01d21](https://linux-hardware.org/?probe=4543c01d21) | Sep 25, 2024 |
| Dell          | 0NW73C A01                  | Desktop     | [a219f52b9b](https://linux-hardware.org/?probe=a219f52b9b) | Sep 25, 2024 |
| Dell          | 0NW73C A01                  | Desktop     | [6f6c30cd6f](https://linux-hardware.org/?probe=6f6c30cd6f) | Sep 25, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [2f1952026d](https://linux-hardware.org/?probe=2f1952026d) | Sep 25, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [a1569ace68](https://linux-hardware.org/?probe=a1569ace68) | Sep 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ed2f09d21e](https://linux-hardware.org/?probe=ed2f09d21e) | Sep 24, 2024 |
| Lenovo        | Unknown                     | Notebook    | [e5d9460e3d](https://linux-hardware.org/?probe=e5d9460e3d) | Sep 24, 2024 |
| ATOPNUC       | MA90                        | Mini pc     | [87d024a242](https://linux-hardware.org/?probe=87d024a242) | Sep 24, 2024 |
| Dell          | 04Y8V0 A01                  | Desktop     | [0bb87c76b0](https://linux-hardware.org/?probe=0bb87c76b0) | Sep 24, 2024 |
| HP            | 82A1                        | Desktop     | [9e17703561](https://linux-hardware.org/?probe=9e17703561) | Sep 24, 2024 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [2d6d8b648b](https://linux-hardware.org/?probe=2d6d8b648b) | Sep 24, 2024 |
| Apple         | MacBook7,1                  | Notebook    | [3910ad68a4](https://linux-hardware.org/?probe=3910ad68a4) | Sep 24, 2024 |
| Lenovo        | IdeaPadFlex Pro-13IKB 81... | Convertible | [0b12c74237](https://linux-hardware.org/?probe=0b12c74237) | Sep 24, 2024 |
| Lenovo        | IdeaPadFlex Pro-13IKB 81... | Convertible | [a33d32e565](https://linux-hardware.org/?probe=a33d32e565) | Sep 24, 2024 |
| HP            | ProBook 650 G5              | Notebook    | [21bbaa3557](https://linux-hardware.org/?probe=21bbaa3557) | Sep 24, 2024 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [98c9e52a71](https://linux-hardware.org/?probe=98c9e52a71) | Sep 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [69b3719446](https://linux-hardware.org/?probe=69b3719446) | Sep 24, 2024 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [d495664aee](https://linux-hardware.org/?probe=d495664aee) | Sep 24, 2024 |
| AZW           | SER V01                     | Mini pc     | [83ae87be80](https://linux-hardware.org/?probe=83ae87be80) | Sep 24, 2024 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1e4a64e920](https://linux-hardware.org/?probe=1e4a64e920) | Sep 23, 2024 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [cab80f4b28](https://linux-hardware.org/?probe=cab80f4b28) | Sep 23, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [8173fdd55a](https://linux-hardware.org/?probe=8173fdd55a) | Sep 23, 2024 |
| Acer          | Swift SFX14-71G             | Notebook    | [47b57a8693](https://linux-hardware.org/?probe=47b57a8693) | Sep 23, 2024 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [51fb99ea77](https://linux-hardware.org/?probe=51fb99ea77) | Sep 23, 2024 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [4a47cb40b4](https://linux-hardware.org/?probe=4a47cb40b4) | Sep 23, 2024 |
| Dell          | 0GK1K2 A00                  | Desktop     | [2053759f81](https://linux-hardware.org/?probe=2053759f81) | Sep 23, 2024 |
| Samsung       | 300E5M/300E5L               | Notebook    | [2410e3bb5f](https://linux-hardware.org/?probe=2410e3bb5f) | Sep 23, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [532f17f668](https://linux-hardware.org/?probe=532f17f668) | Sep 23, 2024 |
| Medion        | MS-7366                     | Desktop     | [d3f9e281e9](https://linux-hardware.org/?probe=d3f9e281e9) | Sep 23, 2024 |
| Dell          | Latitude 5285               | Tablet      | [9bdef7697e](https://linux-hardware.org/?probe=9bdef7697e) | Sep 23, 2024 |
| Samsung       | 700Z7C                      | Notebook    | [8107298d16](https://linux-hardware.org/?probe=8107298d16) | Sep 23, 2024 |
| Gigabyte      | P55A-UD5                    | Desktop     | [03ad1cf760](https://linux-hardware.org/?probe=03ad1cf760) | Sep 23, 2024 |
| Gigabyte      | P55A-UD5                    | Desktop     | [46eade1992](https://linux-hardware.org/?probe=46eade1992) | Sep 23, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [3c4b7eecfb](https://linux-hardware.org/?probe=3c4b7eecfb) | Sep 22, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7f53516227](https://linux-hardware.org/?probe=7f53516227) | Sep 22, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [aff31dc8ce](https://linux-hardware.org/?probe=aff31dc8ce) | Sep 22, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_17/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.5.0-35-generic        | 269       | 9.6%    |
| 6.8.0-40-generic        | 260       | 9.28%   |
| 6.8.0-49-generic        | 213       | 7.6%    |
| 6.5.0-41-generic        | 196       | 7%      |
| 6.8.0-45-generic        | 185       | 6.6%    |
| 6.2.0-39-generic        | 183       | 6.53%   |
| 6.5.0-28-generic        | 163       | 5.82%   |
| 6.5.0-26-generic        | 154       | 5.5%    |
| 6.5.0-45-generic        | 135       | 4.82%   |
| 6.8.0-47-generic        | 123       | 4.39%   |
| 6.8.0-48-generic        | 122       | 4.35%   |
| 6.5.0-21-generic        | 104       | 3.71%   |
| 6.8.0-50-generic        | 101       | 3.6%    |
| 6.5.0-14-generic        | 99        | 3.53%   |
| 6.5.0-25-generic        | 97        | 3.46%   |
| 6.5.0-27-generic        | 96        | 3.43%   |
| 6.5.0-15-generic        | 93        | 3.32%   |
| 6.5.0-18-generic        | 55        | 1.96%   |
| 6.5.0-44-generic        | 49        | 1.75%   |
| 6.5.0-17-generic        | 49        | 1.75%   |
| 6.2.0-37-generic        | 7         | 0.25%   |
| 6.11.0-061100-generic   | 3         | 0.11%   |
| 6.9.9-060909-generic    | 2         | 0.07%   |
| 6.8.12-060812-generic   | 2         | 0.07%   |
| 6.9.5-x64v3-xanmod1     | 1         | 0.04%   |
| 6.9.5-1-liquorix-amd64  | 1         | 0.04%   |
| 6.9.3-surface-2         | 1         | 0.04%   |
| 6.9.3-060903-generic    | 1         | 0.04%   |
| 6.8.9-5-liquorix-amd64  | 1         | 0.04%   |
| 6.8.8-surface-1         | 1         | 0.04%   |
| 6.8.8-060808-generic    | 1         | 0.04%   |
| 6.8.7-2-liquorix-amd64  | 1         | 0.04%   |
| 6.8.7-060807-generic    | 1         | 0.04%   |
| 6.8.5-060805-generic    | 1         | 0.04%   |
| 6.8.10-2-liquorix-amd64 | 1         | 0.04%   |
| 6.8.10-1-liquorix-amd64 | 1         | 0.04%   |
| 6.8.0-41-generic        | 1         | 0.04%   |
| 6.7.7-060707-generic    | 1         | 0.04%   |
| 6.7.6-surface-1         | 1         | 0.04%   |
| 6.7.5-060705-generic    | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.0   | 1467      | 54.96%  |
| 6.8.0   | 967       | 36.23%  |
| 6.2.0   | 190       | 7.12%   |
| 5.15.0  | 7         | 0.26%   |
| 6.11.0  | 3         | 0.11%   |
| 6.9.9   | 2         | 0.07%   |
| 6.9.5   | 2         | 0.07%   |
| 6.9.3   | 2         | 0.07%   |
| 6.8.8   | 2         | 0.07%   |
| 6.8.7   | 2         | 0.07%   |
| 6.8.12  | 2         | 0.07%   |
| 6.8.10  | 2         | 0.07%   |
| 6.8.9   | 1         | 0.04%   |
| 6.8.5   | 1         | 0.04%   |
| 6.7.7   | 1         | 0.04%   |
| 6.7.6   | 1         | 0.04%   |
| 6.7.5   | 1         | 0.04%   |
| 6.7.3   | 1         | 0.04%   |
| 6.7.2   | 1         | 0.04%   |
| 6.7.10  | 1         | 0.04%   |
| 6.6.13  | 1         | 0.04%   |
| 6.6.11  | 1         | 0.04%   |
| 6.6.10  | 1         | 0.04%   |
| 6.12.5  | 1         | 0.04%   |
| 6.12.2  | 1         | 0.04%   |
| 6.12.1  | 1         | 0.04%   |
| 6.10.9  | 1         | 0.04%   |
| 6.10.8  | 1         | 0.04%   |
| 6.10.5  | 1         | 0.04%   |
| 6.10.2  | 1         | 0.04%   |
| 6.10.12 | 1         | 0.04%   |
| 6.10.10 | 1         | 0.04%   |
| 6.1.0   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 1467      | 55.03%  |
| 6.8     | 976       | 36.61%  |
| 6.2     | 190       | 7.13%   |
| 5.15    | 7         | 0.26%   |
| 6.9     | 6         | 0.23%   |
| 6.7     | 5         | 0.19%   |
| 6.10    | 5         | 0.19%   |
| 6.6     | 3         | 0.11%   |
| 6.12    | 3         | 0.11%   |
| 6.11    | 3         | 0.11%   |
| 6.1     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2577      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 2492      | 96.63%  |
| XFCE          | 84        | 3.26%   |
| X-Cinnamon    | 1         | 0.04%   |
| KDE5          | 1         | 0.04%   |
| Enlightenment | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1986      | 76.15%  |
| X11     | 606       | 23.24%  |
| Unknown | 12        | 0.46%   |
| Tty     | 4         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2151      | 82.32%  |
| GDM3    | 445       | 17.03%  |
| LightDM | 14        | 0.54%   |
| GDM     | 3         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 916       | 35.48%  |
| de_DE | 275       | 10.65%  |
| pt_BR | 219       | 8.48%   |
| en_GB | 126       | 4.88%   |
| it_IT | 119       | 4.61%   |
| fr_FR | 107       | 4.14%   |
| es_ES | 84        | 3.25%   |
| en_CA | 73        | 2.83%   |
| en_IN | 53        | 2.05%   |
| en_AU | 48        | 1.86%   |
| nl_NL | 43        | 1.67%   |
| es_MX | 41        | 1.59%   |
| pl_PL | 37        | 1.43%   |
| tr_TR | 34        | 1.32%   |
| pt_PT | 31        | 1.2%    |
| ru_RU | 28        | 1.08%   |
| es_AR | 26        | 1.01%   |
| en_ZA | 26        | 1.01%   |
| hu_HU | 22        | 0.85%   |
| de_AT | 19        | 0.74%   |
| cs_CZ | 19        | 0.74%   |
| es_CO | 18        | 0.7%    |
| es_CL | 14        | 0.54%   |
| en_NZ | 12        | 0.46%   |
| nl_BE | 11        | 0.43%   |
| sv_SE | 10        | 0.39%   |
| da_DK | 9         | 0.35%   |
| ja_JP | 8         | 0.31%   |
| es_EC | 8         | 0.31%   |
| en_IE | 8         | 0.31%   |
| de_CH | 8         | 0.31%   |
| ro_RO | 7         | 0.27%   |
| nb_NO | 7         | 0.27%   |
| hr_HR | 7         | 0.27%   |
| es_VE | 6         | 0.23%   |
| es_PE | 6         | 0.23%   |
| es_BO | 6         | 0.23%   |
| fi_FI | 5         | 0.19%   |
| es_SV | 5         | 0.19%   |
| sl_SI | 4         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2342      | 90.35%  |
| EFI  | 250       | 9.65%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2210      | 84.71%  |
| Tmpfs   | 211       | 8.09%   |
| Zfs     | 88        | 3.37%   |
| Overlay | 51        | 1.95%   |
| Btrfs   | 36        | 1.38%   |
| Ext2    | 7         | 0.27%   |
| Xfs     | 3         | 0.11%   |
| Ext3    | 3         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2148      | 82.2%   |
| GPT     | 434       | 16.61%  |
| MBR     | 31        | 1.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2529      | 97.91%  |
| Yes       | 54        | 2.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2397      | 92.33%  |
| Yes       | 199       | 7.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 397       | 15.41%  |
| ASUSTek Computer    | 359       | 13.93%  |
| Lenovo              | 341       | 13.23%  |
| Dell                | 314       | 12.18%  |
| Apple               | 139       | 5.39%   |
| Gigabyte Technology | 137       | 5.32%   |
| MSI                 | 122       | 4.73%   |
| Acer                | 117       | 4.54%   |
| ASRock              | 60        | 2.33%   |
| Toshiba             | 45        | 1.75%   |
| Intel               | 42        | 1.63%   |
| Unknown             | 41        | 1.59%   |
| Samsung Electronics | 36        | 1.4%    |
| Microsoft           | 31        | 1.2%    |
| Fujitsu             | 29        | 1.13%   |
| Sony                | 25        | 0.97%   |
| HUAWEI              | 25        | 0.97%   |
| Positivo            | 16        | 0.62%   |
| Google              | 14        | 0.54%   |
| Packard Bell        | 12        | 0.47%   |
| Medion              | 12        | 0.47%   |
| AZW                 | 11        | 0.43%   |
| Alienware           | 10        | 0.39%   |
| Pegatron            | 8         | 0.31%   |
| OEM                 | 8         | 0.31%   |
| ECS                 | 8         | 0.31%   |
| Biostar             | 8         | 0.31%   |
| Fujitsu Siemens     | 7         | 0.27%   |
| AMI                 | 7         | 0.27%   |
| GEEKOM              | 6         | 0.23%   |
| Foxconn             | 6         | 0.23%   |
| Chuwi               | 6         | 0.23%   |
| Teclast             | 5         | 0.19%   |
| Panasonic           | 5         | 0.19%   |
| MACHINIST           | 5         | 0.19%   |
| Tactus              | 4         | 0.16%   |
| Semp Toshiba        | 4         | 0.16%   |
| Notebook            | 4         | 0.16%   |
| LG Electronics      | 4         | 0.16%   |
| Exo                 | 4         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 53        | 2.06%   |
| ASUS All Series              | 13        | 0.5%    |
| Microsoft Surface Pro 4      | 12        | 0.47%   |
| Apple MacBookPro14,1         | 10        | 0.39%   |
| Apple MacBookPro9,2          | 8         | 0.31%   |
| MSI MS-7C56                  | 7         | 0.27%   |
| HP Pavilion dv6              | 7         | 0.27%   |
| HP Notebook                  | 7         | 0.27%   |
| Apple MacBookPro5,5          | 7         | 0.27%   |
| MSI MS-7C37                  | 6         | 0.23%   |
| Dell OptiPlex 9020           | 6         | 0.23%   |
| Dell OptiPlex 7010           | 6         | 0.23%   |
| ASUS TUF Gaming X570-PLUS    | 6         | 0.23%   |
| Apple MacBookAir6,2          | 6         | 0.23%   |
| HP Pavilion dv7              | 5         | 0.19%   |
| HP EliteBook 840 G2          | 5         | 0.19%   |
| HP 15                        | 5         | 0.19%   |
| Fujitsu ESPRIMO Q920         | 5         | 0.19%   |
| Dell OptiPlex 790            | 5         | 0.19%   |
| Dell Latitude E7440          | 5         | 0.19%   |
| Dell Inspiron N4050          | 5         | 0.19%   |
| Dell Inspiron 15-3567        | 5         | 0.19%   |
| AZW SER                      | 5         | 0.19%   |
| Apple MacBookPro8,1          | 5         | 0.19%   |
| Apple MacBookPro7,1          | 5         | 0.19%   |
| Apple iMac12,1               | 5         | 0.19%   |
| Lenovo IdeaPad 3 15ALC6 82MF | 4         | 0.16%   |
| HUAWEI HVY-WXX9              | 4         | 0.16%   |
| HP ProBook 650 G1            | 4         | 0.16%   |
| HP Laptop 15-bw0xx           | 4         | 0.16%   |
| Gigabyte Z790 AORUS ELITE AX | 4         | 0.16%   |
| Dell XPS 15 9500             | 4         | 0.16%   |
| Dell System XPS L502X        | 4         | 0.16%   |
| Dell OptiPlex 990            | 4         | 0.16%   |
| Dell OptiPlex 7040           | 4         | 0.16%   |
| Dell OptiPlex 3050           | 4         | 0.16%   |
| Dell Latitude E7450          | 4         | 0.16%   |
| Dell Latitude E6430          | 4         | 0.16%   |
| Dell Latitude E6420          | 4         | 0.16%   |
| Dell Latitude E6400          | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 124       | 4.81%   |
| Dell Latitude         | 90        | 3.49%   |
| Lenovo IdeaPad        | 79        | 3.07%   |
| Dell Inspiron         | 79        | 3.07%   |
| Acer Aspire           | 75        | 2.91%   |
| HP Pavilion           | 67        | 2.6%    |
| Dell OptiPlex         | 60        | 2.33%   |
| Unknown               | 53        | 2.06%   |
| HP Laptop             | 43        | 1.67%   |
| HP EliteBook          | 43        | 1.67%   |
| ASUS VivoBook         | 42        | 1.63%   |
| HP ProBook            | 41        | 1.59%   |
| ASUS ROG              | 38        | 1.47%   |
| Toshiba Satellite     | 34        | 1.32%   |
| Microsoft Surface     | 31        | 1.2%    |
| ASUS TUF              | 29        | 1.13%   |
| ASUS PRIME            | 29        | 1.13%   |
| HP ENVY               | 26        | 1.01%   |
| Dell XPS              | 26        | 1.01%   |
| Dell Precision        | 26        | 1.01%   |
| Lenovo ThinkCentre    | 25        | 0.97%   |
| HP Compaq             | 21        | 0.81%   |
| Lenovo Yoga           | 17        | 0.66%   |
| HP EliteDesk          | 17        | 0.66%   |
| ASUS ASUS             | 17        | 0.66%   |
| Dell Vostro           | 16        | 0.62%   |
| Acer Nitro            | 16        | 0.62%   |
| Fujitsu LIFEBOOK      | 15        | 0.58%   |
| HP ZBook              | 14        | 0.54%   |
| HP ProDesk            | 14        | 0.54%   |
| ASUS Zenbook          | 13        | 0.5%    |
| ASUS All              | 13        | 0.5%    |
| Packard Bell EasyNote | 10        | 0.39%   |
| Lenovo IdeaPadFlex    | 10        | 0.39%   |
| Apple MacBookPro14    | 10        | 0.39%   |
| Lenovo Legion         | 9         | 0.35%   |
| HP 15                 | 9         | 0.35%   |
| Fujitsu ESPRIMO       | 9         | 0.35%   |
| Apple MacBookPro9     | 9         | 0.35%   |
| Lenovo IdeaCentre     | 8         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 202       | 7.84%   |
| 2021    | 200       | 7.76%   |
| 2012    | 178       | 6.91%   |
| 2023    | 177       | 6.87%   |
| 2017    | 176       | 6.83%   |
| 2020    | 173       | 6.71%   |
| 2011    | 173       | 6.71%   |
| 2022    | 167       | 6.48%   |
| 2019    | 166       | 6.44%   |
| 2014    | 155       | 6.01%   |
| 2018    | 154       | 5.98%   |
| 2010    | 135       | 5.24%   |
| 2016    | 124       | 4.81%   |
| 2015    | 113       | 4.38%   |
| 2009    | 93        | 3.61%   |
| 2008    | 85        | 3.3%    |
| 2024    | 50        | 1.94%   |
| 2007    | 46        | 1.79%   |
| 2006    | 8         | 0.31%   |
| 2000    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1440      | 55.88%  |
| Desktop     | 846       | 32.83%  |
| Convertible | 88        | 3.41%   |
| All in one  | 81        | 3.14%   |
| Tablet      | 64        | 2.48%   |
| Mini pc     | 50        | 1.94%   |
| Server      | 7         | 0.27%   |
| Other       | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2528      | 98.02%  |
| Enabled  | 51        | 1.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2558      | 99.26%  |
| Yes  | 19        | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 731       | 28.26%  |
| 16.01-24.0      | 503       | 19.44%  |
| 3.01-4.0        | 464       | 17.94%  |
| 8.01-16.0       | 435       | 16.81%  |
| 32.01-64.0      | 242       | 9.35%   |
| 64.01-256.0     | 83        | 3.21%   |
| 24.01-32.0      | 62        | 2.4%    |
| 1.01-2.0        | 47        | 1.82%   |
| 2.01-3.0        | 19        | 0.73%   |
| More than 256.0 | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 945       | 34.72%  |
| 1.01-2.0   | 741       | 27.22%  |
| 4.01-8.0   | 456       | 16.75%  |
| 3.01-4.0   | 456       | 16.75%  |
| 8.01-16.0  | 82        | 3.01%   |
| 0.51-1.0   | 28        | 1.03%   |
| 16.01-24.0 | 11        | 0.4%    |
| 32.01-64.0 | 2         | 0.07%   |
| 24.01-32.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1688      | 64.67%  |
| 2      | 625       | 23.95%  |
| 3      | 163       | 6.25%   |
| 4      | 69        | 2.64%   |
| 5      | 23        | 0.88%   |
| 6      | 20        | 0.77%   |
| 8      | 8         | 0.31%   |
| 7      | 6         | 0.23%   |
| 9      | 3         | 0.11%   |
| 0      | 3         | 0.11%   |
| 11     | 1         | 0.04%   |
| 10     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1650      | 63.9%   |
| Yes       | 932       | 36.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2147      | 83.25%  |
| No        | 432       | 16.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2131      | 82.5%   |
| No        | 452       | 17.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1756      | 67.64%  |
| No        | 840       | 32.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 487       | 18.8%   |
| Germany         | 299       | 11.54%  |
| Brazil          | 237       | 9.15%   |
| Italy           | 129       | 4.98%   |
| UK              | 120       | 4.63%   |
| France          | 106       | 4.09%   |
| Canada          | 86        | 3.32%   |
| Spain           | 82        | 3.17%   |
| Netherlands     | 64        | 2.47%   |
| Mexico          | 57        | 2.2%    |
| India           | 57        | 2.2%    |
| Australia       | 45        | 1.74%   |
| Poland          | 44        | 1.7%    |
| Turkey          | 42        | 1.62%   |
| Portugal        | 40        | 1.54%   |
| Argentina       | 31        | 1.2%    |
| South Africa    | 27        | 1.04%   |
| Austria         | 27        | 1.04%   |
| Hungary         | 26        | 1%      |
| Belgium         | 26        | 1%      |
| Switzerland     | 25        | 0.97%   |
| Egypt           | 25        | 0.97%   |
| Russia          | 24        | 0.93%   |
| Romania         | 24        | 0.93%   |
| Sweden          | 23        | 0.89%   |
| Czechia         | 23        | 0.89%   |
| Indonesia       | 22        | 0.85%   |
| Colombia        | 19        | 0.73%   |
| Japan           | 16        | 0.62%   |
| Denmark         | 16        | 0.62%   |
| Chile           | 16        | 0.62%   |
| Norway          | 15        | 0.58%   |
| Greece          | 15        | 0.58%   |
| New Zealand     | 13        | 0.5%    |
| Finland         | 13        | 0.5%    |
| Saudi Arabia    | 11        | 0.42%   |
| The Netherlands | 10        | 0.39%   |
| Malaysia        | 9         | 0.35%   |
| Ireland         | 9         | 0.35%   |
| Slovenia        | 8         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 27        | 1.02%   |
| Berlin         | 22        | 0.83%   |
| Rio de Janeiro | 20        | 0.75%   |
| Sydney         | 18        | 0.68%   |
| Istanbul       | 17        | 0.64%   |
| Milan          | 15        | 0.56%   |
| Budapest       | 15        | 0.56%   |
| Mexico City    | 14        | 0.53%   |
| Melbourne      | 13        | 0.49%   |
| Cairo          | 13        | 0.49%   |
| Santiago       | 12        | 0.45%   |
| Rome           | 12        | 0.45%   |
| Prague         | 12        | 0.45%   |
| Amsterdam      | 12        | 0.45%   |
| Vienna         | 10        | 0.38%   |
| Paris          | 10        | 0.38%   |
| Madrid         | 10        | 0.38%   |
| Johannesburg   | 10        | 0.38%   |
| Hamburg        | 10        | 0.38%   |
| Stockholm      | 9         | 0.34%   |
| London         | 9         | 0.34%   |
| Chennai        | 9         | 0.34%   |
| Cape Town      | 9         | 0.34%   |
| Birmingham     | 9         | 0.34%   |
| Ribeirao Preto | 8         | 0.3%    |
| Porto          | 8         | 0.3%    |
| Warsaw         | 7         | 0.26%   |
| Stuttgart      | 7         | 0.26%   |
| New York       | 7         | 0.26%   |
| Munich         | 7         | 0.26%   |
| Mumbai         | 7         | 0.26%   |
| Moscow         | 7         | 0.26%   |
| Montreal       | 7         | 0.26%   |
| Minneapolis    | 7         | 0.26%   |
| Los Angeles    | 7         | 0.26%   |
| Joao Pessoa    | 7         | 0.26%   |
| Helsinki       | 7         | 0.26%   |
| Düsseldorf    | 7         | 0.26%   |
| Brisbane       | 7         | 0.26%   |
| Brasília      | 7         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 550       | 748    | 15.08%  |
| WDC                          | 398       | 525    | 10.91%  |
| Seagate                      | 393       | 505    | 10.78%  |
| SanDisk                      | 227       | 292    | 6.22%   |
| Kingston                     | 214       | 250    | 5.87%   |
| Toshiba                      | 176       | 197    | 4.83%   |
| Unknown                      | 163       | 195    | 4.47%   |
| Crucial                      | 127       | 147    | 3.48%   |
| SK hynix                     | 94        | 105    | 2.58%   |
| Hitachi                      | 80        | 96     | 2.19%   |
| Micron Technology            | 79        | 84     | 2.17%   |
| China                        | 71        | 83     | 1.95%   |
| Apple                        | 63        | 80     | 1.73%   |
| Intel                        | 60        | 76     | 1.65%   |
| HGST                         | 57        | 69     | 1.56%   |
| A-DATA Technology            | 47        | 51     | 1.29%   |
| Micron/Crucial Technology    | 45        | 55     | 1.23%   |
| Phison Electronics           | 43        | 56     | 1.18%   |
| Kingston Technology Company  | 42        | 46     | 1.15%   |
| Intenso                      | 40        | 44     | 1.1%    |
| Silicon Motion               | 34        | 35     | 0.93%   |
| MAXIO Technology (Hangzhou)  | 31        | 37     | 0.85%   |
| SPCC                         | 26        | 26     | 0.71%   |
| KIOXIA                       | 25        | 25     | 0.69%   |
| ADATA Technology             | 24        | 24     | 0.66%   |
| Unknown                      | 24        | 29     | 0.66%   |
| PNY                          | 22        | 26     | 0.6%    |
| Fanxiang                     | 19        | 25     | 0.52%   |
| Realtek Semiconductor        | 18        | 21     | 0.49%   |
| LITEON                       | 16        | 19     | 0.44%   |
| Shenzhen Longsys Electronics | 15        | 16     | 0.41%   |
| Lexar                        | 15        | 17     | 0.41%   |
| Netac                        | 14        | 16     | 0.38%   |
| OCZ                          | 13        | 15     | 0.36%   |
| KingSpec                     | 13        | 15     | 0.36%   |
| Verbatim                     | 12        | 17     | 0.33%   |
| JMicron Technology           | 12        | 12     | 0.33%   |
| LITEONIT                     | 10        | 11     | 0.27%   |
| Gigabyte Technology          | 10        | 11     | 0.27%   |
| Corsair                      | 10        | 14     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                                | 60        | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 60        | 1.54%   |
| Kingston SA400S37240G 240GB SSD                       | 46        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 45        | 1.15%   |
| Unknown MMC Card  128GB                               | 35        | 0.9%    |
| Kingston SA400S37480G 480GB SSD                       | 35        | 0.9%    |
| Unknown MMC Card  32GB                                | 27        | 0.69%   |
| Samsung SSD 850 EVO 250GB                             | 26        | 0.67%   |
| Samsung SSD 860 EVO 500GB                             | 25        | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 25        | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 24        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 24        | 0.62%   |
| Unknown                                               | 24        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 23        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 22        | 0.56%   |
| Samsung SSD 870 EVO 500GB                             | 21        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                          | 21        | 0.54%   |
| Toshiba MQ01ABF050 500GB                              | 20        | 0.51%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 19        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                       | 18        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                           | 18        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB                        | 16        | 0.41%   |
| Samsung SSD 850 EVO 500GB                             | 16        | 0.41%   |
| Kingston SA400S37960G 960GB SSD                       | 16        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                       | 16        | 0.41%   |
| Toshiba MQ04ABF100 1TB                                | 14        | 0.36%   |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 14        | 0.36%   |
| Samsung SSD 990 PRO 2TB                               | 14        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                          | 14        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                        | 13        | 0.33%   |
| Toshiba MQ01ABD100 1TB                                | 12        | 0.31%   |
| Toshiba DT01ACA100 1TB                                | 12        | 0.31%   |
| Seagate ST500LT012-1DG142 500GB                       | 12        | 0.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 12        | 0.31%   |
| Kingston Company SNV2S1000G 1TB                       | 12        | 0.31%   |
| China SSD 256GB                                       | 12        | 0.31%   |
| SK hynix BC511 512GB                                  | 11        | 0.28%   |
| Seagate ST9500325AS 500GB                             | 11        | 0.28%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11        | 0.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 11        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 382       | 486    | 34.82%  |
| WDC                 | 325       | 425    | 29.63%  |
| Toshiba             | 135       | 152    | 12.31%  |
| Hitachi             | 80        | 96     | 7.29%   |
| HGST                | 57        | 69     | 5.2%    |
| Samsung Electronics | 34        | 38     | 3.1%    |
| Apple               | 22        | 22     | 2.01%   |
| Unknown             | 10        | 10     | 0.91%   |
| Fujitsu             | 9         | 9      | 0.82%   |
| SABRENT             | 6         | 8      | 0.55%   |
| Maxtor              | 5         | 5      | 0.46%   |
| JMicron Technology  | 5         | 5      | 0.46%   |
| External            | 4         | 4      | 0.36%   |
| LaCie               | 3         | 3      | 0.27%   |
| Intenso             | 3         | 4      | 0.27%   |
| TO Exter            | 2         | 2      | 0.18%   |
| EAGET               | 2         | 2      | 0.18%   |
| ASMT                | 2         | 2      | 0.18%   |
| ASMedia             | 2         | 2      | 0.18%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| WALRAM              | 1         | 1      | 0.09%   |
| USB                 | 1         | 1      | 0.09%   |
| Min Yi U            | 1         | 1      | 0.09%   |
| MARVELL             | 1         | 1      | 0.09%   |
| KESU                | 1         | 1      | 0.09%   |
| HPE                 | 1         | 1      | 0.09%   |
| Fantom              | 1         | 1      | 0.09%   |
| Apricorn            | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 279       | 361    | 21.2%   |
| Kingston            | 180       | 205    | 13.68%  |
| Crucial             | 121       | 140    | 9.19%   |
| SanDisk             | 98        | 112    | 7.45%   |
| China               | 70        | 82     | 5.32%   |
| WDC                 | 66        | 82     | 5.02%   |
| A-DATA Technology   | 41        | 45     | 3.12%   |
| Intenso             | 27        | 28     | 2.05%   |
| Intel               | 26        | 27     | 1.98%   |
| Apple               | 26        | 26     | 1.98%   |
| SPCC                | 25        | 25     | 1.9%    |
| PNY                 | 22        | 26     | 1.67%   |
| Micron Technology   | 21        | 24     | 1.6%    |
| SK hynix            | 16        | 18     | 1.22%   |
| LITEON              | 16        | 19     | 1.22%   |
| Lexar               | 15        | 17     | 1.14%   |
| Toshiba             | 13        | 14     | 0.99%   |
| OCZ                 | 13        | 15     | 0.99%   |
| KingSpec            | 13        | 15     | 0.99%   |
| Unknown             | 13        | 15     | 0.99%   |
| Verbatim            | 10        | 15     | 0.76%   |
| Netac               | 10        | 12     | 0.76%   |
| LITEONIT            | 10        | 11     | 0.76%   |
| Transcend           | 9         | 9      | 0.68%   |
| Team                | 8         | 8      | 0.61%   |
| Patriot             | 8         | 10     | 0.61%   |
| Gigabyte Technology | 8         | 9      | 0.61%   |
| Apacer              | 8         | 8      | 0.61%   |
| Hewlett-Packard     | 7         | 7      | 0.53%   |
| GOODRAM             | 7         | 11     | 0.53%   |
| Fanxiang            | 7         | 7      | 0.53%   |
| Corsair             | 7         | 9      | 0.53%   |
| Teclast             | 6         | 8      | 0.46%   |
| XrayDisk            | 5         | 6      | 0.38%   |
| Seagate             | 4         | 6      | 0.3%    |
| KIOXIA-EXCERIA      | 4         | 5      | 0.3%    |
| FORESEE             | 4         | 5      | 0.3%    |
| SSSTC               | 3         | 4      | 0.23%   |
| Phison              | 3         | 4      | 0.23%   |
| EVM                 | 3         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1177      | 1546   | 35.47%  |
| HDD     | 974       | 1353   | 29.36%  |
| NVMe    | 912       | 1260   | 27.49%  |
| MMC     | 142       | 161    | 4.28%   |
| Unknown | 113       | 145    | 3.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1837      | 2851   | 60.41%  |
| NVMe | 908       | 1249   | 29.86%  |
| SAS  | 154       | 204    | 5.06%   |
| MMC  | 142       | 161    | 4.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1325      | 1718   | 59.77%  |
| 0.51-1.0   | 605       | 777    | 27.29%  |
| 1.01-2.0   | 166       | 227    | 7.49%   |
| 3.01-4.0   | 48        | 75     | 2.17%   |
| 4.01-10.0  | 39        | 60     | 1.76%   |
| 2.01-3.0   | 23        | 27     | 1.04%   |
| 10.01-20.0 | 10        | 14     | 0.45%   |
| 20.01-50.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 873       | 33.28%  |
| 251-500        | 645       | 24.59%  |
| 501-1000       | 390       | 14.87%  |
| 51-100         | 180       | 6.86%   |
| 1001-2000      | 172       | 6.56%   |
| More than 3000 | 110       | 4.19%   |
| 21-50          | 75        | 2.86%   |
| 1-20           | 72        | 2.74%   |
| Unknown        | 60        | 2.29%   |
| 2001-3000      | 45        | 1.72%   |
| 0              | 1         | 0.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 920       | 33.95%  |
| 1-20           | 867       | 31.99%  |
| 51-100         | 291       | 10.74%  |
| 101-250        | 243       | 8.97%   |
| 251-500        | 136       | 5.02%   |
| 501-1000       | 92        | 3.39%   |
| Unknown        | 60        | 2.21%   |
| 1001-2000      | 47        | 1.73%   |
| More than 3000 | 33        | 1.22%   |
| 2001-3000      | 20        | 0.74%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500LM000-1EJ162 500GB                  | 3         | 3      | 7.89%   |
| A-DATA Technology IM2P33F3A NVMe 256GB           | 2         | 2      | 5.26%   |
| WDC WD5000BPVT-75HXZT1 500GB                     | 1         | 1      | 2.63%   |
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 2.63%   |
| WDC WD3200AAJS-56M0A0 320GB                      | 1         | 1      | 2.63%   |
| WDC WD3200AAJS-22L7A0 320GB                      | 1         | 1      | 2.63%   |
| WDC WD3200AAJS-08B4A0 320GB                      | 1         | 1      | 2.63%   |
| WDC WD2500BEKT-75PVMT1 250GB                     | 1         | 1      | 2.63%   |
| WDC WD15EARS-00MVWB0 1TB                         | 1         | 1      | 2.63%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.63%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.63%   |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 2.63%   |
| Toshiba MK2565GSX 250GB                          | 1         | 1      | 2.63%   |
| Seagate ST320LT012-9WS14C 320GB                  | 1         | 1      | 2.63%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.63%   |
| SanDisk SSD PLUS 480GB                           | 1         | 1      | 2.63%   |
| SanDisk SSD PLUS 240GB                           | 1         | 2      | 2.63%   |
| Samsung Electronics SSD 870 EVO 500GB            | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 870 EVO 1TB              | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 850 PRO 512GB            | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 840 PRO Series 256GB     | 1         | 1      | 2.63%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.63%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD   | 1         | 1      | 2.63%   |
| Kingston SA400S37960G 960GB SSD                  | 1         | 1      | 2.63%   |
| KingFast SSD 120GB                               | 1         | 1      | 2.63%   |
| Intel HBRPEKNX0202AHO 32GB                       | 1         | 1      | 2.63%   |
| Hitachi HTS723232L9A360 320GB                    | 1         | 1      | 2.63%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.63%   |
| Hitachi HDS721680PLA380 80GB                     | 1         | 1      | 2.63%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.63%   |
| HGST HTS541010A7E630 1TB                         | 1         | 1      | 2.63%   |
| China SSD 1TB                                    | 1         | 1      | 2.63%   |
| BIWIN SSD 64GB                                   | 1         | 1      | 2.63%   |
| A-DATA Technology SX8200PNP 512GB                | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 8      | 16.67%  |
| Seagate             | 6         | 6      | 16.67%  |
| Samsung Electronics | 5         | 5      | 13.89%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| A-DATA Technology   | 3         | 3      | 8.33%   |
| SanDisk             | 2         | 3      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| KingFast            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| China               | 1         | 1      | 2.78%   |
| BIWIN               | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 30%     |
| Seagate | 6         | 6      | 30%     |
| Toshiba | 3         | 3      | 15%     |
| Hitachi | 3         | 3      | 15%     |
| HGST    | 2         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 22     | 55.56%  |
| SSD  | 12        | 13     | 33.33%  |
| NVMe | 4         | 4      | 11.11%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2372      | 4089   | 89.98%  |
| Works    | 229       | 337    | 8.69%   |
| Malfunc  | 35        | 39     | 1.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1724      | 51.94%  |
| AMD                              | 435       | 13.11%  |
| Samsung Electronics              | 279       | 8.41%   |
| SanDisk                          | 143       | 4.31%   |
| SK hynix                         | 78        | 2.35%   |
| Kingston Technology Company      | 76        | 2.29%   |
| Micron Technology                | 59        | 1.78%   |
| Phison Electronics               | 52        | 1.57%   |
| ASMedia Technology               | 51        | 1.54%   |
| Micron/Crucial Technology        | 50        | 1.51%   |
| Silicon Motion                   | 38        | 1.14%   |
| Nvidia                           | 37        | 1.11%   |
| MAXIO Technology (Hangzhou)      | 37        | 1.11%   |
| Marvell Technology Group         | 30        | 0.9%    |
| ADATA Technology                 | 30        | 0.9%    |
| KIOXIA                           | 29        | 0.87%   |
| Toshiba America Info Systems     | 27        | 0.81%   |
| JMicron Technology               | 26        | 0.78%   |
| Realtek Semiconductor            | 20        | 0.6%    |
| Apple                            | 17        | 0.51%   |
| Shenzhen Longsys Electronics     | 16        | 0.48%   |
| Solid State Storage Technology   | 7         | 0.21%   |
| Silicon Integrated Systems [SiS] | 7         | 0.21%   |
| Seagate Technology               | 6         | 0.18%   |
| Solidigm                         | 5         | 0.15%   |
| LSI Logic / Symbios Logic        | 5         | 0.15%   |
| Broadcom / LSI                   | 5         | 0.15%   |
| Netac Technology                 | 4         | 0.12%   |
| Integrated Technology Express    | 3         | 0.09%   |
| Hosin Global Electronics         | 3         | 0.09%   |
| Unknown                          | 3         | 0.09%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| VIA Technologies                 | 2         | 0.06%   |
| Union Memory (Shenzhen)          | 2         | 0.06%   |
| Lite-On Technology               | 2         | 0.06%   |
| Biwin Storage Technology         | 2         | 0.06%   |
| Adaptec                          | 2         | 0.06%   |
| Silicon Image                    | 1         | 0.03%   |
| OCZ Technology Group             | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 261       | 7.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 125       | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 124       | 3.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 118       | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 95        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 88        | 2.39%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 76        | 2.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 74        | 2.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 68        | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 67        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 62        | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 60        | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 60        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 57        | 1.55%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 50        | 1.36%   |
| AMD 500 Series Chipset SATA Controller                                                  | 48        | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 47        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 46        | 1.25%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 45        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 45        | 1.22%   |
| AMD 400 Series Chipset SATA Controller                                                  | 44        | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 42        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 42        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 39        | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 36        | 0.98%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 35        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 33        | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 32        | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 30        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 30        | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 29        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 27        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 27        | 0.73%   |
| AMD 600 Series Chipset SATA Controller                                                  | 27        | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 26        | 0.71%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 26        | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 26        | 0.71%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 26        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 26        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 26        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1871      | 57.08%  |
| NVMe | 906       | 27.64%  |
| IDE  | 253       | 7.72%   |
| RAID | 238       | 7.26%   |
| SAS  | 7         | 0.21%   |
| SCSI | 3         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2039      | 79.12%  |
| AMD    | 538       | 20.88%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz       | 26        | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 25        | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 24        | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 24        | 0.93%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 24        | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 21        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 21        | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 19        | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 18        | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 17        | 0.66%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 16        | 0.62%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 15        | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 15        | 0.58%   |
| AMD Ryzen 5 3600 6-Core Processor       | 15        | 0.58%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 14        | 0.54%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 14        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 13        | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz        | 13        | 0.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 13        | 0.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 13        | 0.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics  | 13        | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 12        | 0.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 12        | 0.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 12        | 0.47%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 12        | 0.47%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 12        | 0.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 11        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 11        | 0.43%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 11        | 0.43%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 11        | 0.43%   |
| Intel 12th Gen Core i5-1235U            | 11        | 0.43%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 11        | 0.43%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 11        | 0.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 10        | 0.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 10        | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 10        | 0.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 0.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 10        | 0.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 10        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 597       | 23.15%  |
| Intel Core i7           | 406       | 15.74%  |
| Other                   | 279       | 10.82%  |
| Intel Core i3           | 220       | 8.53%   |
| Intel Celeron           | 168       | 6.51%   |
| AMD Ryzen 5             | 131       | 5.08%   |
| Intel Core 2 Duo        | 129       | 5%      |
| AMD Ryzen 7             | 119       | 4.61%   |
| Intel Pentium           | 51        | 1.98%   |
| Intel Xeon              | 49        | 1.9%    |
| AMD Ryzen 9             | 41        | 1.59%   |
| AMD Ryzen 3             | 27        | 1.05%   |
| Intel Pentium Dual-Core | 24        | 0.93%   |
| Intel Atom              | 24        | 0.93%   |
| AMD A6                  | 24        | 0.93%   |
| AMD FX                  | 23        | 0.89%   |
| Intel Core i9           | 21        | 0.81%   |
| Intel Core 2 Quad       | 20        | 0.78%   |
| AMD A8                  | 20        | 0.78%   |
| AMD E1                  | 18        | 0.7%    |
| AMD A10                 | 17        | 0.66%   |
| Intel Pentium Dual      | 12        | 0.47%   |
| AMD E                   | 11        | 0.43%   |
| AMD Ryzen 5 PRO         | 10        | 0.39%   |
| AMD Phenom II X4        | 10        | 0.39%   |
| Intel Core              | 9         | 0.35%   |
| Intel Pentium Silver    | 8         | 0.31%   |
| Intel Core m3           | 7         | 0.27%   |
| Intel Core 2            | 7         | 0.27%   |
| AMD Athlon              | 7         | 0.27%   |
| AMD A4                  | 7         | 0.27%   |
| AMD A12                 | 7         | 0.27%   |
| AMD Ryzen 3 PRO         | 5         | 0.19%   |
| AMD E2                  | 5         | 0.19%   |
| AMD Athlon II           | 5         | 0.19%   |
| Intel Pentium Gold      | 4         | 0.16%   |
| AMD Ryzen 7 PRO         | 4         | 0.16%   |
| AMD Athlon II X4        | 4         | 0.16%   |
| Intel Core m5           | 3         | 0.12%   |
| Intel Core M            | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1106      | 42.87%  |
| 4      | 833       | 32.29%  |
| 6      | 210       | 8.14%   |
| 8      | 188       | 7.29%   |
| 12     | 65        | 2.52%   |
| 10     | 46        | 1.78%   |
| 14     | 45        | 1.74%   |
| 16     | 26        | 1.01%   |
| 1      | 23        | 0.89%   |
| 24     | 14        | 0.54%   |
| 3      | 14        | 0.54%   |
| 20     | 7         | 0.27%   |
| 18     | 2         | 0.08%   |
| 32     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2567      | 99.61%  |
| 2      | 9         | 0.35%   |
| 20     | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1738      | 67.36%  |
| 1      | 842       | 32.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2577      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2540      | 98.34%  |
| 0x0a50000d | 5         | 0.19%   |
| 0x0a50000c | 4         | 0.15%   |
| 0x0a601206 | 3         | 0.12%   |
| 0x0a20120a | 3         | 0.12%   |
| 0x0a601203 | 2         | 0.08%   |
| 0x08608103 | 2         | 0.08%   |
| 0x08600109 | 2         | 0.08%   |
| 0x08600106 | 2         | 0.08%   |
| 0x08108109 | 2         | 0.08%   |
| 0x08001138 | 2         | 0.08%   |
| 0x806d1    | 1         | 0.04%   |
| 0x306c3    | 1         | 0.04%   |
| 0x0a20102b | 1         | 0.04%   |
| 0x08a00008 | 1         | 0.04%   |
| 0x08701030 | 1         | 0.04%   |
| 0x08701021 | 1         | 0.04%   |
| 0x08608107 | 1         | 0.04%   |
| 0x08608104 | 1         | 0.04%   |
| 0x0860010c | 1         | 0.04%   |
| 0x08108102 | 1         | 0.04%   |
| 0x08101007 | 1         | 0.04%   |
| 0x0800820d | 1         | 0.04%   |
| 0x0700010f | 1         | 0.04%   |
| 0x06006705 | 1         | 0.04%   |
| 0x06003109 | 1         | 0.04%   |
| 0x05000119 | 1         | 0.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 321       | 12.45%  |
| Unknown           | 275       | 10.66%  |
| Haswell           | 258       | 10%     |
| SandyBridge       | 197       | 7.64%   |
| IvyBridge         | 194       | 7.52%   |
| Penryn            | 150       | 5.82%   |
| Skylake           | 149       | 5.78%   |
| Zen 3             | 115       | 4.46%   |
| Westmere          | 87        | 3.37%   |
| Goldmont plus     | 79        | 3.06%   |
| TigerLake         | 75        | 2.91%   |
| Zen 2             | 66        | 2.56%   |
| Broadwell         | 64        | 2.48%   |
| Core              | 56        | 2.17%   |
| Silvermont        | 55        | 2.13%   |
| Zen+              | 45        | 1.74%   |
| Goldmont          | 38        | 1.47%   |
| K10               | 36        | 1.4%    |
| Piledriver        | 34        | 1.32%   |
| Alderlake Hybrid  | 33        | 1.28%   |
| Zen               | 32        | 1.24%   |
| CometLake         | 32        | 1.24%   |
| Excavator         | 29        | 1.12%   |
| IceLake           | 27        | 1.05%   |
| Nehalem           | 25        | 0.97%   |
| Puma              | 22        | 0.85%   |
| Bobcat            | 19        | 0.74%   |
| Jaguar            | 13        | 0.5%    |
| Steamroller       | 11        | 0.43%   |
| K8 Hammer         | 8         | 0.31%   |
| K10 Llano         | 8         | 0.31%   |
| Bulldozer         | 8         | 0.31%   |
| K8 & K10 hybrid   | 4         | 0.16%   |
| Bonnell           | 4         | 0.16%   |
| Tremont           | 3         | 0.12%   |
| Gracemont         | 3         | 0.12%   |
| NetBurst          | 2         | 0.08%   |
| Meteorlake Hybrid | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1553      | 51.84%  |
| Nvidia                           | 743       | 24.8%   |
| AMD                              | 687       | 22.93%  |
| Silicon Integrated Systems [SiS] | 5         | 0.17%   |
| ASPEED Technology                | 3         | 0.1%    |
| Matrox Electronics Systems       | 2         | 0.07%   |
| ATI Technologies                 | 2         | 0.07%   |
| 3DLabs                           | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 144       | 4.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 111       | 3.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 2.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 73        | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 68        | 2.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 2.03%   |
| Intel HD Graphics 620                                                                    | 58        | 1.89%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 53        | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 48        | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 45        | 1.47%   |
| Intel HD Graphics 530                                                                    | 41        | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 40        | 1.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 37        | 1.21%   |
| Intel HD Graphics 500                                                                    | 36        | 1.18%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 34        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 1.05%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 31        | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 0.91%   |
| Intel HD Graphics 630                                                                    | 27        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26        | 0.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 0.82%   |
| AMD Lucienne                                                                             | 25        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 22        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 0.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 22        | 0.72%   |
| AMD Raphael                                                                              | 22        | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 0.65%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 20        | 0.65%   |
| AMD Barcelo                                                                              | 19        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 0.59%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 17        | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 0.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 16        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 1185      | 45.89%  |
| 1 x AMD                 | 535       | 20.72%  |
| 1 x Nvidia              | 434       | 16.81%  |
| Intel + Nvidia          | 259       | 10.03%  |
| Intel + AMD             | 69        | 2.67%   |
| AMD + Nvidia            | 45        | 1.74%   |
| 2 x AMD                 | 35        | 1.36%   |
| 1 x SiS                 | 5         | 0.19%   |
| Other                   | 4         | 0.15%   |
| 2 x Nvidia              | 3         | 0.12%   |
| 3 x AMD                 | 1         | 0.04%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.04%   |
| 2 x Intel               | 1         | 0.04%   |
| 2 x AMD + 1 x 3DLabs    | 1         | 0.04%   |
| Nvidia + Matrox         | 1         | 0.04%   |
| Nvidia + ASPEED         | 1         | 0.04%   |
| 1 x Matrox              | 1         | 0.04%   |
| 1 x ASPEED              | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2077      | 80.07%  |
| Proprietary | 386       | 14.88%  |
| Unknown     | 131       | 5.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2360      | 91.08%  |
| 1.01-2.0   | 53        | 2.05%   |
| 7.01-8.0   | 38        | 1.47%   |
| 0.01-0.5   | 38        | 1.47%   |
| 3.01-4.0   | 28        | 1.08%   |
| 8.01-16.0  | 28        | 1.08%   |
| 5.01-6.0   | 18        | 0.69%   |
| 0.51-1.0   | 18        | 0.69%   |
| 2.01-3.0   | 7         | 0.27%   |
| 16.01-24.0 | 3         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 357       | 13.46%  |
| AU Optronics            | 311       | 11.73%  |
| BOE                     | 268       | 10.11%  |
| LG Display              | 232       | 8.75%   |
| Chimei Innolux          | 205       | 7.73%   |
| Goldstar                | 140       | 5.28%   |
| Apple                   | 122       | 4.6%    |
| Dell                    | 120       | 4.52%   |
| Hewlett-Packard         | 82        | 3.09%   |
| Acer                    | 79        | 2.98%   |
| AOC                     | 63        | 2.38%   |
| Philips                 | 49        | 1.85%   |
| BenQ                    | 44        | 1.66%   |
| Lenovo                  | 42        | 1.58%   |
| Chi Mei Optoelectronics | 41        | 1.55%   |
| Sharp                   | 40        | 1.51%   |
| Ancor Communications    | 32        | 1.21%   |
| PANDA                   | 27        | 1.02%   |
| InfoVision              | 25        | 0.94%   |
| ViewSonic               | 24        | 0.9%    |
| Sony                    | 23        | 0.87%   |
| ASUSTek Computer        | 23        | 0.87%   |
| CSO                     | 16        | 0.6%    |
| Iiyama                  | 14        | 0.53%   |
| Hitachi                 | 13        | 0.49%   |
| Panasonic               | 12        | 0.45%   |
| HKC                     | 12        | 0.45%   |
| MSI                     | 11        | 0.41%   |
| Vizio                   | 10        | 0.38%   |
| RTK                     | 7         | 0.26%   |
| LG Philips              | 7         | 0.26%   |
| Fujitsu Siemens         | 7         | 0.26%   |
| Unknown                 | 6         | 0.23%   |
| TMX                     | 6         | 0.23%   |
| Sceptre Tech            | 6         | 0.23%   |
| NEC Computers           | 6         | 0.23%   |
| Eizo                    | 6         | 0.23%   |
| CPT                     | 6         | 0.23%   |
| ___                     | 5         | 0.19%   |
| Toshiba                 | 5         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 18        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 14        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.44%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 10        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.3%    |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 8         | 0.3%    |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 8         | 0.3%    |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 8         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 7         | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 7         | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 7         | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 6         | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.22%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch               | 6         | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch         | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 6         | 0.22%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 6         | 0.22%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 6         | 0.22%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 5         | 0.18%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 5         | 0.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.18%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 5         | 0.18%   |
| LG Display LCD Monitor LGD0555 2880x1920 274x183mm 13.0-inch          | 5         | 0.18%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 5         | 0.18%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 5         | 0.18%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch               | 5         | 0.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 5         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1033      | 40.21%  |
| 1366x768 (WXGA)    | 554       | 21.56%  |
| 3840x2160 (4K)     | 206       | 8.02%   |
| 1600x900 (HD+)     | 128       | 4.98%   |
| 2560x1440 (QHD)    | 107       | 4.17%   |
| 1920x1200 (WUXGA)  | 73        | 2.84%   |
| 1280x800 (WXGA)    | 68        | 2.65%   |
| 1440x900 (WXGA+)   | 66        | 2.57%   |
| 1680x1050 (WSXGA+) | 45        | 1.75%   |
| 2880x1800          | 36        | 1.4%    |
| 2560x1600          | 34        | 1.32%   |
| 1280x1024 (SXGA)   | 34        | 1.32%   |
| 3440x1440          | 21        | 0.82%   |
| 2560x1080          | 20        | 0.78%   |
| 1360x768           | 16        | 0.62%   |
| 3840x1080          | 12        | 0.47%   |
| 2736x1824          | 11        | 0.43%   |
| 1920x1280          | 10        | 0.39%   |
| 2160x1440          | 8         | 0.31%   |
| Unknown            | 8         | 0.31%   |
| 2880x1920          | 7         | 0.27%   |
| 1920x540           | 7         | 0.27%   |
| 3840x2400          | 6         | 0.23%   |
| 3200x2000          | 6         | 0.23%   |
| 2256x1504          | 6         | 0.23%   |
| 1024x768 (XGA)     | 4         | 0.16%   |
| 3840x1600          | 3         | 0.12%   |
| 3200x1800 (QHD+)   | 3         | 0.12%   |
| 2304x1440          | 3         | 0.12%   |
| 1024x600           | 3         | 0.12%   |
| 5120x1440          | 2         | 0.08%   |
| 504x315            | 2         | 0.08%   |
| 3840x1200          | 2         | 0.08%   |
| 3072x1920          | 2         | 0.08%   |
| 2880x1620          | 2         | 0.08%   |
| 2560x2880          | 2         | 0.08%   |
| 1680x945           | 2         | 0.08%   |
| 5760x2160          | 1         | 0.04%   |
| 5120x1080          | 1         | 0.04%   |
| 480x1920           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 660       | 24.92%  |
| 13      | 294       | 11.1%   |
| 14      | 232       | 8.76%   |
| 27      | 204       | 7.7%    |
| 17      | 142       | 5.36%   |
| 24      | 141       | 5.32%   |
| 23      | 130       | 4.91%   |
| 21      | 115       | 4.34%   |
| 31      | 87        | 3.29%   |
| Unknown | 64        | 2.42%   |
| 16      | 63        | 2.38%   |
| 18      | 60        | 2.27%   |
| 12      | 60        | 2.27%   |
| 20      | 46        | 1.74%   |
| 19      | 45        | 1.7%    |
| 84      | 36        | 1.36%   |
| 34      | 36        | 1.36%   |
| 11      | 36        | 1.36%   |
| 22      | 28        | 1.06%   |
| 32      | 23        | 0.87%   |
| 72      | 16        | 0.6%    |
| 40      | 14        | 0.53%   |
| 54      | 11        | 0.42%   |
| 48      | 10        | 0.38%   |
| 10      | 10        | 0.38%   |
| 26      | 9         | 0.34%   |
| 42      | 7         | 0.26%   |
| 28      | 7         | 0.26%   |
| 65      | 6         | 0.23%   |
| 49      | 6         | 0.23%   |
| 25      | 6         | 0.23%   |
| 75      | 4         | 0.15%   |
| 52      | 4         | 0.15%   |
| 39      | 4         | 0.15%   |
| 29      | 4         | 0.15%   |
| 74      | 3         | 0.11%   |
| 60      | 3         | 0.11%   |
| 43      | 3         | 0.11%   |
| 37      | 3         | 0.11%   |
| 46      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1074      | 41.02%  |
| 501-600     | 439       | 16.77%  |
| 401-500     | 276       | 10.54%  |
| 201-300     | 248       | 9.47%   |
| 351-400     | 188       | 7.18%   |
| 601-700     | 125       | 4.77%   |
| Unknown     | 64        | 2.44%   |
| 1501-2000   | 61        | 2.33%   |
| 701-800     | 59        | 2.25%   |
| 1001-1500   | 48        | 1.83%   |
| 801-900     | 22        | 0.84%   |
| 901-1000    | 12        | 0.46%   |
| 101-200     | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1908      | 78%     |
| 16/10   | 339       | 13.86%  |
| 3/2     | 50        | 2.04%   |
| 21/9    | 43        | 1.76%   |
| Unknown | 42        | 1.72%   |
| 5/4     | 27        | 1.1%    |
| 32/9    | 13        | 0.53%   |
| 4/3     | 10        | 0.41%   |
| 6/5     | 4         | 0.16%   |
| 2.00    | 2         | 0.08%   |
| 0.89    | 2         | 0.08%   |
| 3.40    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 0.80    | 1         | 0.04%   |
| 0.31    | 1         | 0.04%   |
| 0.25    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 658       | 24.99%  |
| 81-90          | 429       | 16.29%  |
| 201-250        | 318       | 12.08%  |
| 301-350        | 208       | 7.9%    |
| 351-500        | 157       | 5.96%   |
| 151-200        | 135       | 5.13%   |
| 121-130        | 111       | 4.22%   |
| 71-80          | 94        | 3.57%   |
| More than 1000 | 93        | 3.53%   |
| 141-150        | 65        | 2.47%   |
| Unknown        | 64        | 2.43%   |
| 251-300        | 59        | 2.24%   |
| 61-70          | 57        | 2.16%   |
| 111-120        | 53        | 2.01%   |
| 501-1000       | 48        | 1.82%   |
| 51-60          | 38        | 1.44%   |
| 131-140        | 24        | 0.91%   |
| 91-100         | 11        | 0.42%   |
| 41-50          | 9         | 0.34%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 789       | 30.63%  |
| 101-120       | 720       | 27.95%  |
| 121-160       | 682       | 26.48%  |
| 161-240       | 191       | 7.41%   |
| More than 240 | 70        | 2.72%   |
| Unknown       | 64        | 2.48%   |
| 1-50          | 60        | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2104      | 80.77%  |
| 2     | 299       | 11.48%  |
| 0     | 170       | 6.53%   |
| 3     | 29        | 1.11%   |
| 4     | 3         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1430      | 36.53%  |
| Intel                             | 1204      | 30.75%  |
| Qualcomm Atheros                  | 391       | 9.99%   |
| Broadcom                          | 269       | 6.87%   |
| MediaTek                          | 83        | 2.12%   |
| Marvell Technology Group          | 62        | 1.58%   |
| Broadcom Limited                  | 57        | 1.46%   |
| TP-Link                           | 51        | 1.3%    |
| Ralink Technology                 | 46        | 1.17%   |
| Ralink                            | 40        | 1.02%   |
| Samsung Electronics               | 26        | 0.66%   |
| Nvidia                            | 26        | 0.66%   |
| ASIX Electronics                  | 24        | 0.61%   |
| Sierra Wireless                   | 20        | 0.51%   |
| Microsoft                         | 15        | 0.38%   |
| NetGear                           | 11        | 0.28%   |
| Xiaomi                            | 9         | 0.23%   |
| JMicron Technology                | 9         | 0.23%   |
| Hewlett-Packard                   | 9         | 0.23%   |
| Dell                              | 9         | 0.23%   |
| DisplayLink                       | 8         | 0.2%    |
| D-Link                            | 8         | 0.2%    |
| Qualcomm Atheros Communications   | 7         | 0.18%   |
| Ericsson Business Mobile Networks | 7         | 0.18%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.15%   |
| Qualcomm                          | 6         | 0.15%   |
| Lenovo                            | 6         | 0.15%   |
| ASUSTek Computer                  | 6         | 0.15%   |
| Qualcomm Technologies             | 5         | 0.13%   |
| D-Link System                     | 4         | 0.1%    |
| Aquantia                          | 4         | 0.1%    |
| U-Blox                            | 3         | 0.08%   |
| Motorola PCS                      | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| Edimax Technology                 | 3         | 0.08%   |
| Belkin Components                 | 3         | 0.08%   |
| ZyXEL Communications              | 2         | 0.05%   |
| T & A Mobile Phones               | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| Manta                             | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 864       | 18.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 192       | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 93        | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 79        | 1.71%   |
| Realtek RTL8125 2.5GbE Controller                                      | 79        | 1.71%   |
| Intel Wireless 8265 / 8275                                             | 68        | 1.47%   |
| Intel Wireless 7260                                                    | 64        | 1.38%   |
| Intel Wi-Fi 6 AX201                                                    | 64        | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 62        | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 61        | 1.32%   |
| Intel Wi-Fi 6 AX200                                                    | 60        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 58        | 1.25%   |
| Intel Wireless 7265                                                    | 57        | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 54        | 1.17%   |
| Intel Ethernet Connection I217-LM                                      | 54        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 51        | 1.1%    |
| Intel Wireless 3165                                                    | 45        | 0.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 44        | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 42        | 0.91%   |
| Intel Ethernet Controller I225-V                                       | 42        | 0.91%   |
| Intel Wireless 8260                                                    | 40        | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 38        | 0.82%   |
| Realtek 802.11ac NIC                                                   | 36        | 0.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 36        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 34        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 32        | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 30        | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 29        | 0.63%   |
| Intel I211 Gigabit Network Connection                                  | 28        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 27        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 27        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 27        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 26        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 26        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 25        | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 25        | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 25        | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 24        | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 24        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 24        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 926       | 40.79%  |
| Realtek Semiconductor                 | 440       | 19.38%  |
| Qualcomm Atheros                      | 324       | 14.27%  |
| Broadcom                              | 196       | 8.63%   |
| MediaTek                              | 74        | 3.26%   |
| TP-Link                               | 49        | 2.16%   |
| Ralink Technology                     | 46        | 2.03%   |
| Broadcom Limited                      | 45        | 1.98%   |
| Ralink                                | 40        | 1.76%   |
| Sierra Wireless                       | 20        | 0.88%   |
| Marvell Technology Group              | 19        | 0.84%   |
| Microsoft                             | 13        | 0.57%   |
| NetGear                               | 11        | 0.48%   |
| Dell                                  | 8         | 0.35%   |
| D-Link                                | 8         | 0.35%   |
| Qualcomm Atheros Communications       | 7         | 0.31%   |
| Qualcomm Technologies                 | 5         | 0.22%   |
| ASUSTek Computer                      | 5         | 0.22%   |
| Qualcomm                              | 3         | 0.13%   |
| Linksys                               | 3         | 0.13%   |
| Edimax Technology                     | 3         | 0.13%   |
| D-Link System                         | 3         | 0.13%   |
| Belkin Components                     | 3         | 0.13%   |
| ZyXEL Communications                  | 2         | 0.09%   |
| Hewlett-Packard                       | 2         | 0.09%   |
| BUFFALO                               | 2         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.09%   |
| ZTopInc                               | 1         | 0.04%   |
| Wilocity                              | 1         | 0.04%   |
| TRENDnet                              | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Mercucys                              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| Fibocom                               | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| 3Com                                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 79        | 3.45%   |
| Intel Wireless 8265 / 8275                                           | 68        | 2.97%   |
| Intel Wireless 7260                                                  | 64        | 2.8%    |
| Intel Wi-Fi 6 AX201                                                  | 64        | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 62        | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 61        | 2.67%   |
| Intel Wi-Fi 6 AX200                                                  | 60        | 2.62%   |
| Intel Wireless 7265                                                  | 57        | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 54        | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 51        | 2.23%   |
| Intel Wireless 3165                                                  | 45        | 1.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 44        | 1.92%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 42        | 1.84%   |
| Intel Wireless 8260                                                  | 40        | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 38        | 1.66%   |
| Realtek 802.11ac NIC                                                 | 36        | 1.57%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 36        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 32        | 1.4%    |
| Ralink MT7601U Wireless Adapter                                      | 27        | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 26        | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 25        | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 25        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 25        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 25        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 24        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 24        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 24        | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 23        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                        | 22        | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 21        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 20        | 0.87%   |
| Intel WiFi Link 5100                                                 | 20        | 0.87%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 20        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 20        | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 20        | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 20        | 0.87%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 19        | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 19        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 18        | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 18        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1232      | 54.39%  |
| Intel                             | 585       | 25.83%  |
| Broadcom                          | 133       | 5.87%   |
| Qualcomm Atheros                  | 111       | 4.9%    |
| Marvell Technology Group          | 43        | 1.9%    |
| Nvidia                            | 26        | 1.15%   |
| ASIX Electronics                  | 24        | 1.06%   |
| Samsung Electronics               | 18        | 0.79%   |
| Broadcom Limited                  | 12        | 0.53%   |
| Xiaomi                            | 9         | 0.4%    |
| MediaTek                          | 9         | 0.4%    |
| JMicron Technology                | 9         | 0.4%    |
| DisplayLink                       | 8         | 0.35%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.26%   |
| Lenovo                            | 6         | 0.26%   |
| Hewlett-Packard                   | 5         | 0.22%   |
| Aquantia                          | 4         | 0.18%   |
| Qualcomm                          | 3         | 0.13%   |
| Motorola PCS                      | 3         | 0.13%   |
| TP-Link                           | 2         | 0.09%   |
| T & A Mobile Phones               | 2         | 0.09%   |
| OPPO Electronics                  | 2         | 0.09%   |
| Microsoft                         | 2         | 0.09%   |
| Huawei Technologies               | 2         | 0.09%   |
| Sundance Technology Inc / IC Plus | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| Panini                            | 1         | 0.04%   |
| Mellanox Technologies             | 1         | 0.04%   |
| Google                            | 1         | 0.04%   |
| D-Link System                     | 1         | 0.04%   |
| Attansic Technology               | 1         | 0.04%   |
| ASUSTek Computer                  | 1         | 0.04%   |
| Unknown                           | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 864       | 37.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 192       | 8.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 93        | 4.03%   |
| Realtek RTL8125 2.5GbE Controller                                      | 79        | 3.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 58        | 2.51%   |
| Intel Ethernet Connection I217-LM                                      | 54        | 2.34%   |
| Intel Ethernet Controller I225-V                                       | 42        | 1.82%   |
| Intel Ethernet Connection (2) I219-V                                   | 34        | 1.47%   |
| Intel I211 Gigabit Network Connection                                  | 28        | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                                  | 27        | 1.17%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 27        | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 26        | 1.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 26        | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                                  | 24        | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                          | 21        | 0.91%   |
| Intel Ethernet Connection I219-LM                                      | 20        | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 18        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 18        | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 18        | 0.78%   |
| Nvidia MCP79 Ethernet                                                  | 17        | 0.74%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.74%   |
| Intel Ethernet Connection I217-V                                       | 17        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                  | 17        | 0.74%   |
| Realtek Killer E2600 GbE Controller                                    | 16        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 13        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 13        | 0.56%   |
| Intel Ethernet Controller I226-V                                       | 12        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 12        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 12        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                               | 11        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 10        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 9         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 9         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                                  | 9         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2145      | 49.78%  |
| WiFi     | 2130      | 49.43%  |
| Modem    | 31        | 0.72%   |
| Unknown  | 3         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1699      | 62.88%  |
| Ethernet | 1002      | 37.08%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1453      | 56.32%  |
| 1     | 1032      | 40%     |
| 0     | 45        | 1.74%   |
| 3     | 42        | 1.63%   |
| 4     | 6         | 0.23%   |
| 5     | 2         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1617      | 62.29%  |
| Yes  | 979       | 37.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 764       | 42.9%   |
| Realtek Semiconductor           | 217       | 12.18%  |
| Qualcomm Atheros Communications | 124       | 6.96%   |
| Apple                           | 120       | 6.74%   |
| Cambridge Silicon Radio         | 102       | 5.73%   |
| IMC Networks                    | 88        | 4.94%   |
| Broadcom                        | 60        | 3.37%   |
| Foxconn / Hon Hai               | 54        | 3.03%   |
| Lite-On Technology              | 41        | 2.3%    |
| ASUSTek Computer                | 29        | 1.63%   |
| MediaTek                        | 25        | 1.4%    |
| Hewlett-Packard                 | 24        | 1.35%   |
| Dell                            | 24        | 1.35%   |
| Marvell Semiconductor           | 21        | 1.18%   |
| Toshiba                         | 20        | 1.12%   |
| Ralink                          | 12        | 0.67%   |
| Actions                         | 10        | 0.56%   |
| TP-Link                         | 9         | 0.51%   |
| Realtek                         | 6         | 0.34%   |
| Alps Electric                   | 6         | 0.34%   |
| Integrated System Solution      | 3         | 0.17%   |
| Foxconn International           | 3         | 0.17%   |
| Ralink Technology               | 2         | 0.11%   |
| Qcom                            | 2         | 0.11%   |
| Micro Star International        | 2         | 0.11%   |
| Dynex                           | 2         | 0.11%   |
| Unknown                         | 2         | 0.11%   |
| USI                             | 1         | 0.06%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Smart Modular Technologies      | 1         | 0.06%   |
| Roper                           | 1         | 0.06%   |
| Kensington                      | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 276       | 15.5%   |
| Intel AX201 Bluetooth                               | 151       | 8.48%   |
| Realtek Bluetooth Radio                             | 135       | 7.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 102       | 5.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 93        | 5.22%   |
| Intel AX211 Bluetooth                               | 71        | 3.99%   |
| Intel AX200 Bluetooth                               | 58        | 3.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 56        | 3.14%   |
| Apple Bluetooth Host Controller                     | 51        | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 47        | 2.64%   |
| Apple Bluetooth USB Host Controller                 | 39        | 2.19%   |
| Intel AX210 Bluetooth                               | 38        | 2.13%   |
| IMC Networks Wireless_Device                        | 35        | 1.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 28        | 1.57%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.4%    |
| MediaTek Wireless_Device                            | 24        | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 1.18%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                    | 20        | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.07%   |
| Marvell Bluetooth and Wireless LAN Composite        | 17        | 0.95%   |
| IMC Networks Bluetooth Device                       | 16        | 0.9%    |
| Lite-On Bluetooth Device                            | 13        | 0.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 0.73%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.73%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.73%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.73%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.67%   |
| Dell DW375 Bluetooth Module                         | 11        | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 10        | 0.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.56%   |
| Actions general adapter                             | 10        | 0.56%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 9         | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 9         | 0.51%   |
| Realtek 802.11ac WLAN Adapter                       | 9         | 0.51%   |
| Apple Bluetooth HCI                                 | 9         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1966      | 54.92%  |
| AMD                                          | 698       | 19.5%   |
| Nvidia                                       | 593       | 16.56%  |
| C-Media Electronics                          | 44        | 1.23%   |
| Creative Labs                                | 20        | 0.56%   |
| ASUSTek Computer                             | 15        | 0.42%   |
| Logitech                                     | 14        | 0.39%   |
| Micro Star International                     | 12        | 0.34%   |
| Texas Instruments                            | 11        | 0.31%   |
| JMTek                                        | 10        | 0.28%   |
| Generalplus Technology                       | 9         | 0.25%   |
| GN Netcom                                    | 8         | 0.22%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.2%    |
| Silicon Integrated Systems [SiS]             | 7         | 0.2%    |
| Realtek Semiconductor                        | 7         | 0.2%    |
| Plantronics                                  | 7         | 0.2%    |
| Focusrite-Novation                           | 7         | 0.2%    |
| SteelSeries ApS                              | 6         | 0.17%   |
| Sony                                         | 6         | 0.17%   |
| Razer USA                                    | 6         | 0.17%   |
| Unknown                                      | 6         | 0.17%   |
| Walmart                                      | 5         | 0.14%   |
| Thesycon Systemsoftware & Consulting         | 5         | 0.14%   |
| Kingston Technology                          | 5         | 0.14%   |
| Hewlett-Packard                              | 5         | 0.14%   |
| Creative Technology                          | 5         | 0.14%   |
| Trust                                        | 4         | 0.11%   |
| Lenovo                                       | 4         | 0.11%   |
| KTMicro                                      | 4         | 0.11%   |
| Jieli Technology                             | 4         | 0.11%   |
| Tenx Technology                              | 3         | 0.08%   |
| M-Audio                                      | 3         | 0.08%   |
| Lautsprecher Teufel                          | 3         | 0.08%   |
| DSEA A/S                                     | 3         | 0.08%   |
| Dell                                         | 3         | 0.08%   |
| Corsair                                      | 3         | 0.08%   |
| Blue Microphones                             | 3         | 0.08%   |
| Apple                                        | 3         | 0.08%   |
| VIA Technologies                             | 2         | 0.06%   |
| RODE Microphones                             | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 235       | 5.5%    |
| Intel Sunrise Point-LP HD Audio                                            | 218       | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 192       | 4.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 188       | 4.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 150       | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 119       | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 102       | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 96        | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 84        | 1.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 83        | 1.94%   |
| Intel 8 Series HD Audio Controller                                         | 83        | 1.94%   |
| AMD FCH Azalia Controller                                                  | 83        | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 79        | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 75        | 1.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 74        | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 70        | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 70        | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 62        | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 54        | 1.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 53        | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 50        | 1.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 49        | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 48        | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 48        | 1.12%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 44        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 38        | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 38        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 37        | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 37        | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 36        | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 35        | 0.82%   |
| Intel Raptor Lake High Definition Audio Controller                         | 35        | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 33        | 0.77%   |
| Nvidia High Definition Audio Controller                                    | 30        | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                              | 30        | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 30        | 0.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 29        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 95        | 23.46%  |
| SK hynix            | 86        | 21.23%  |
| Micron Technology   | 50        | 12.35%  |
| Kingston            | 32        | 7.9%    |
| Unknown             | 30        | 7.41%   |
| Corsair             | 21        | 5.19%   |
| Crucial             | 20        | 4.94%   |
| G.Skill             | 10        | 2.47%   |
| A-DATA Technology   | 10        | 2.47%   |
| Unknown (ABCD)      | 9         | 2.22%   |
| Team                | 5         | 1.23%   |
| Ramaxel Technology  | 5         | 1.23%   |
| Elpida              | 5         | 1.23%   |
| Unknown             | 5         | 1.23%   |
| Lexar               | 3         | 0.74%   |
| Unknown (0x0B45)    | 2         | 0.49%   |
| Smart               | 2         | 0.49%   |
| Unknown (C289)      | 1         | 0.25%   |
| Unknown (0x8945)    | 1         | 0.25%   |
| Unknown (0x0E9D)    | 1         | 0.25%   |
| Unknown (0x0B38)    | 1         | 0.25%   |
| Transcend           | 1         | 0.25%   |
| Timetec             | 1         | 0.25%   |
| Teikon              | 1         | 0.25%   |
| Smart Brazil        | 1         | 0.25%   |
| Silicon Power       | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| Nanya Technology    | 1         | 0.25%   |
| Multilaser          | 1         | 0.25%   |
| Juhor               | 1         | 0.25%   |
| ChangXin Memory     | 1         | 0.25%   |
| Axiom               | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 8         | 1.86%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 6         | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.17%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.17%   |
| Unknown                                                          | 5         | 1.17%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.93%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.93%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 4         | 0.93%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 3         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 3         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 2         | 0.47%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 2         | 0.47%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.47%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.47%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.47%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.47%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.47%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 157       | 45.51%  |
| DDR3    | 92        | 26.67%  |
| LPDDR4  | 28        | 8.12%   |
| DDR5    | 21        | 6.09%   |
| LPDDR5  | 17        | 4.93%   |
| LPDDR3  | 8         | 2.32%   |
| DDR2    | 8         | 2.32%   |
| Unknown | 8         | 2.32%   |
| SDRAM   | 6         | 1.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 221       | 63.51%  |
| DIMM         | 75        | 21.55%  |
| Row Of Chips | 48        | 13.79%  |
| Chip         | 2         | 0.57%   |
| Unknown      | 2         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 163       | 43.01%  |
| 4096  | 98        | 25.86%  |
| 16384 | 65        | 17.15%  |
| 2048  | 35        | 9.23%   |
| 1024  | 9         | 2.37%   |
| 32768 | 8         | 2.11%   |
| 12288 | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 75        | 20.22%  |
| 1600    | 60        | 16.17%  |
| 2667    | 45        | 12.13%  |
| 2400    | 29        | 7.82%   |
| 1333    | 19        | 5.12%   |
| 6400    | 13        | 3.5%    |
| 4267    | 11        | 2.96%   |
| 2133    | 10        | 2.7%    |
| 3600    | 9         | 2.43%   |
| Unknown | 9         | 2.43%   |
| 5600    | 7         | 1.89%   |
| 4800    | 7         | 1.89%   |
| 1867    | 7         | 1.89%   |
| 1334    | 7         | 1.89%   |
| 3733    | 6         | 1.62%   |
| 1067    | 5         | 1.35%   |
| 800     | 5         | 1.35%   |
| 667     | 5         | 1.35%   |
| 1066    | 4         | 1.08%   |
| 6000    | 3         | 0.81%   |
| 1800    | 3         | 0.81%   |
| 7500    | 2         | 0.54%   |
| 5200    | 2         | 0.54%   |
| 4266    | 2         | 0.54%   |
| 4199    | 2         | 0.54%   |
| 3534    | 2         | 0.54%   |
| 3400    | 2         | 0.54%   |
| 3266    | 2         | 0.54%   |
| 2933    | 2         | 0.54%   |
| 1866    | 2         | 0.54%   |
| 1648    | 2         | 0.54%   |
| 8533    | 1         | 0.27%   |
| 7467    | 1         | 0.27%   |
| 7000    | 1         | 0.27%   |
| 5500    | 1         | 0.27%   |
| 3800    | 1         | 0.27%   |
| 3466    | 1         | 0.27%   |
| 3000    | 1         | 0.27%   |
| 2800    | 1         | 0.27%   |
| 2200    | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 23        | 34.85%  |
| Seiko Epson              | 10        | 15.15%  |
| Samsung Electronics      | 8         | 12.12%  |
| Canon                    | 8         | 12.12%  |
| Brother Industries       | 7         | 10.61%  |
| Dymo-CoStar              | 4         | 6.06%   |
| Lexmark International    | 2         | 3.03%   |
| Zhuhai Poskey Technology | 1         | 1.52%   |
| Zebra                    | 1         | 1.52%   |
| Ricoh                    | 1         | 1.52%   |
| Kyocera                  | 1         | 1.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung SCX-3400 Series                               | 3         | 4.48%   |
| HP DeskJet 2700 series                                | 3         | 4.48%   |
| Seiko Epson L3150 Series                              | 2         | 2.99%   |
| Seiko Epson ET-4850 Series                            | 2         | 2.99%   |
| HP LaserJet 1020                                      | 2         | 2.99%   |
| Dymo-CoStar LabelWriter 450                           | 2         | 2.99%   |
| Canon CanoScan LiDE 300                               | 2         | 2.99%   |
| Zhuhai Poskey 4B-2054L                                | 1         | 1.49%   |
| Zebra GK420d Label Printer                            | 1         | 1.49%   |
| Seiko Epson XP-4100 Series                            | 1         | 1.49%   |
| Seiko Epson XP-3100 Series                            | 1         | 1.49%   |
| Seiko Epson TM-T20X                                   | 1         | 1.49%   |
| Seiko Epson L6270 Series                              | 1         | 1.49%   |
| Seiko Epson L3110 Series                              | 1         | 1.49%   |
| Seiko Epson ET-4700 Series                            | 1         | 1.49%   |
| Samsung ML-216x Series Laser Printer                  | 1         | 1.49%   |
| Samsung CLX-3180 Series                               | 1         | 1.49%   |
| Samsung CLX-3170 Series                               | 1         | 1.49%   |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 1.49%   |
| Samsung C43x Series                                   | 1         | 1.49%   |
| Ricoh Printing Support                                | 1         | 1.49%   |
| Lexmark International MS710                           | 1         | 1.49%   |
| Lexmark International CX310dn                         | 1         | 1.49%   |
| Kyocera ECOSYS P2235dn                                | 1         | 1.49%   |
| HP Smart Tank 580-590 series                          | 1         | 1.49%   |
| HP Smart Tank 500 series                              | 1         | 1.49%   |
| HP Printing Support                                   | 1         | 1.49%   |
| HP OfficeJet 4650 series                              | 1         | 1.49%   |
| HP LaserJet M101-M106                                 | 1         | 1.49%   |
| HP LaserJet 400 M401n                                 | 1         | 1.49%   |
| HP LaserJet 1010                                      | 1         | 1.49%   |
| HP HP LaserJet Pro M404-M405                          | 1         | 1.49%   |
| HP HP LaserJet M14-M17                                | 1         | 1.49%   |
| HP ENVY 6000 series                                   | 1         | 1.49%   |
| HP ENVY 5540 series                                   | 1         | 1.49%   |
| HP ENVY 4520 series                                   | 1         | 1.49%   |
| HP Deskjet F4500 series                               | 1         | 1.49%   |
| HP DeskJet 3700 series                                | 1         | 1.49%   |
| HP DeskJet 2130 series                                | 1         | 1.49%   |
| HP Deskjet 2050 J510                                  | 1         | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 71.43%  |
| Seiko Epson     | 2         | 14.29%  |
| Mustek Systems  | 1         | 7.14%   |
| Hewlett-Packard | 1         | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                | 2         | 14.29%  |
| Canon CanoScan LiDE 220                           | 2         | 14.29%  |
| Canon CanoScan LiDE 110                           | 2         | 14.29%  |
| Seiko Epson GT-F670 [Perfection V200 Photo]       | 1         | 7.14%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 7.14%   |
| Mustek Systems ScanExpress 1200 UB                | 1         | 7.14%   |
| HP ScanJet 5300c/5370c                            | 1         | 7.14%   |
| Canon CanoScan LiDE 90                            | 1         | 7.14%   |
| Canon CanoScan LiDE 210                           | 1         | 7.14%   |
| Canon CanoScan LiDE 200                           | 1         | 7.14%   |
| Canon CanoScan 8800F                              | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 327       | 20.15%  |
| Microdia                               | 120       | 7.39%   |
| Realtek Semiconductor                  | 117       | 7.21%   |
| IMC Networks                           | 106       | 6.53%   |
| Apple                                  | 94        | 5.79%   |
| Bison Electronics                      | 93        | 5.73%   |
| Sunplus Innovation Technology          | 92        | 5.67%   |
| Quanta                                 | 80        | 4.93%   |
| Logitech                               | 79        | 4.87%   |
| Suyin                                  | 63        | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 58        | 3.57%   |
| Lite-On Technology                     | 33        | 2.03%   |
| Syntek                                 | 32        | 1.97%   |
| Luxvisions Innotech Limited            | 30        | 1.85%   |
| Silicon Motion                         | 29        | 1.79%   |
| Sonix Technology                       | 27        | 1.66%   |
| Alcor Micro                            | 26        | 1.6%    |
| Microsoft                              | 19        | 1.17%   |
| SunplusIT                              | 18        | 1.11%   |
| Ricoh                                  | 17        | 1.05%   |
| Acer                                   | 17        | 1.05%   |
| icSpring                               | 14        | 0.86%   |
| Shinetech                              | 12        | 0.74%   |
| Samsung Electronics                    | 7         | 0.43%   |
| Lenovo                                 | 6         | 0.37%   |
| Importek                               | 6         | 0.37%   |
| Generalplus Technology                 | 6         | 0.37%   |
| Shine-optics                           | 5         | 0.31%   |
| Primax Electronics                     | 5         | 0.31%   |
| Unknown                                | 5         | 0.31%   |
| Z-Star Microelectronics                | 4         | 0.25%   |
| Y Media                                | 4         | 0.25%   |
| DigiTech                               | 4         | 0.25%   |
| ALi                                    | 4         | 0.25%   |
| Sunplus Technology                     | 3         | 0.18%   |
| OmniVision Technologies                | 3         | 0.18%   |
| Insta360                               | 3         | 0.18%   |
| Genesys Logic                          | 3         | 0.18%   |
| 2M UVC CAMERA                          | 3         | 0.18%   |
| Trust                                  | 2         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 54        | 3.3%    |
| Bison Integrated Camera                       | 37        | 2.26%   |
| Apple Built-in iSight                         | 36        | 2.2%    |
| Microdia Integrated_Webcam_HD                 | 32        | 1.95%   |
| Apple FaceTime HD Camera (Built-in)           | 32        | 1.95%   |
| Realtek Integrated_Webcam_HD                  | 29        | 1.77%   |
| IMC Networks USB2.0 HD UVC WebCam             | 27        | 1.65%   |
| IMC Networks Integrated Camera                | 25        | 1.53%   |
| Syntek Integrated Camera                      | 19        | 1.16%   |
| Sunplus Integrated_Webcam_HD                  | 19        | 1.16%   |
| Logitech Webcam C270                          | 19        | 1.16%   |
| Logitech HD Pro Webcam C920                   | 18        | 1.1%    |
| Realtek USB Camera                            | 17        | 1.04%   |
| Chicony HP TrueVision HD Camera               | 17        | 1.04%   |
| Chicony HD Webcam                             | 16        | 0.98%   |
| Apple FaceTime HD Camera                      | 16        | 0.98%   |
| Chicony HP TrueVision HD                      | 15        | 0.92%   |
| icSpring camera                               | 14        | 0.86%   |
| Chicony HP HD Camera                          | 14        | 0.86%   |
| Alcor Micro USB 2.0 Camera                    | 14        | 0.86%   |
| Sunplus HD WebCam                             | 13        | 0.79%   |
| Suyin HP Truevision HD                        | 12        | 0.73%   |
| Sonix USB2.0 HD UVC WebCam                    | 12        | 0.73%   |
| Quanta HD User Facing                         | 12        | 0.73%   |
| Microdia Integrated Webcam                    | 12        | 0.73%   |
| Chicony TOSHIBA Web Camera - HD               | 12        | 0.73%   |
| Chicony FJ Camera                             | 12        | 0.73%   |
| Quanta HP Wide Vision HD Camera               | 11        | 0.67%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 11        | 0.67%   |
| Chicony HP HD Webcam                          | 11        | 0.67%   |
| Chicony EasyCamera                            | 11        | 0.67%   |
| Sonix USB2.0 FHD UVC WebCam                   | 10        | 0.61%   |
| Microdia USB 2.0 Camera                       | 10        | 0.61%   |
| Lite-On Integrated Camera                     | 10        | 0.61%   |
| Lite-On HP HD Camera                          | 10        | 0.61%   |
| Realtek Integrated Webcam                     | 9         | 0.55%   |
| IMC Networks HD Camera                        | 9         | 0.55%   |
| Bison EasyCamera                              | 9         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 8         | 0.49%   |
| Luxvisions Innotech Limited Integrated Camera | 8         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 121       | 47.83%  |
| Synaptics                          | 45        | 17.79%  |
| Shenzhen Goodix Technology         | 31        | 12.25%  |
| AuthenTec                          | 17        | 6.72%   |
| Upek                               | 12        | 4.74%   |
| Elan Microelectronics              | 11        | 4.35%   |
| LighTuning Technology              | 4         | 1.58%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.19%   |
| HOLTEK                             | 2         | 0.79%   |
| Dell                               | 2         | 0.79%   |
| STMicroelectronics                 | 1         | 0.4%    |
| Samsung Electronics                | 1         | 0.4%    |
| Microsoft                          | 1         | 0.4%    |
| FocalTech                          | 1         | 0.4%    |
| Focal-systems.Corp                 | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 11.07%  |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 6.72%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 5.14%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 4.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.95%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 3.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 3.56%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 3.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 3.16%   |
| Synaptics  WBDI                                                            | 7         | 2.77%   |
| Synaptics WBDI                                                             | 6         | 2.37%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 2.37%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.37%   |
| AuthenTec AES1600                                                          | 6         | 2.37%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.98%   |
| Validity Sensors VFS491                                                    | 5         | 1.98%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.98%   |
| AuthenTec AES2810                                                          | 5         | 1.98%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.98%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.58%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 1.58%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.58%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.58%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.19%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.19%   |
| Synaptics UWP WBDI                                                         | 3         | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.19%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.19%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.79%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.79%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.79%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 64        | 51.61%  |
| Alcor Micro                       | 19        | 15.32%  |
| Upek                              | 11        | 8.87%   |
| Lenovo                            | 8         | 6.45%   |
| O2 Micro                          | 6         | 4.84%   |
| SCM Microsystems                  | 3         | 2.42%   |
| Reiner SCT Kartensysteme          | 2         | 1.61%   |
| NXP Semiconductors                | 2         | 1.61%   |
| Gemalto (was Gemplus)             | 2         | 1.61%   |
| Chicony Electronics               | 2         | 1.61%   |
| VASCO Data Security International | 1         | 0.81%   |
| Hewlett-Packard                   | 1         | 0.81%   |
| Bit4id                            | 1         | 0.81%   |
| Athena Smartcard Solutions        | 1         | 0.81%   |
| Aladdin Knowledge Systems         | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 21.77%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 15.32%  |
| Broadcom 5880                                                                | 15        | 12.1%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 8.87%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.87%   |
| Broadcom 58200                                                               | 11        | 8.87%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 5.65%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 4.84%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 1.61%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.61%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 1.61%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.81%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.81%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.81%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.81%   |
| NXP Semiconductors PR533                                                     | 1         | 0.81%   |
| NXP Semiconductors HUSCR-NFC                                                 | 1         | 0.81%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.81%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.81%   |
| Bit4id miniLector EVO                                                        | 1         | 0.81%   |
| Athena Smartcard Solutions ASEDrive V3C                                      | 1         | 0.81%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1738      | 66.46%  |
| 1     | 733       | 28.03%  |
| 2     | 126       | 4.82%   |
| 3     | 17        | 0.65%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 297       | 29.26%  |
| Fingerprint reader       | 248       | 24.43%  |
| Multimedia controller    | 122       | 12.02%  |
| Chipcard                 | 115       | 11.33%  |
| Net/wireless             | 111       | 10.94%  |
| Camera                   | 24        | 2.36%   |
| Storage                  | 20        | 1.97%   |
| Bluetooth                | 20        | 1.97%   |
| Communication controller | 12        | 1.18%   |
| Unassigned class         | 9         | 0.89%   |
| Net/ethernet             | 8         | 0.79%   |
| Card reader              | 7         | 0.69%   |
| Sound                    | 5         | 0.49%   |
| Storage/ide              | 4         | 0.39%   |
| Network                  | 4         | 0.39%   |
| Storage/raid             | 3         | 0.3%    |
| Unclassified device      | 2         | 0.2%    |
| Video                    | 1         | 0.1%    |
| Tv card                  | 1         | 0.1%    |
| Modem                    | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

