Linux in Belgium - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

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

Total: 1302

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | System XPS L702X            | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| HP            | Notebook                    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Dell          | Latitude 5580               | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| Notebook      | N7x0WU                      | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Valve         | Jupiter                     | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| Valve         | Jupiter                     | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| Packard Be... | EasyNote TR85               | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Valve         | Jupiter                     | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Dell          | G3 3779                     | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Acer          | NC-ES1-512-C3AH             | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| HP            | Pavilion dv6                | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Dell          | Latitude 5530               | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| Apple         | MacBookPro5,5               | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | EliteBook 850 G5            | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| Acer          | Aspire 7741                 | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| HP            | Pavilion 17                 | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| ASUSTek       | GL703VD                     | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Dell          | Latitude 5580               | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| HP            | ProBook 470 G5              | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| PC Special... | Recoil II                   | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| Acer          | Aspire E5-521               | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| HP            | ProBook 450 G6              | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Notebook      | W330SU2                     | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Dell          | Latitude 5530               | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Lenovo        | G50-45 80E3                 | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| Lenovo        | B570e 476025G               | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire 7551                 | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| Sony          | SVE1712L1EW                 | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| Notebook      | NL40_50CU                   | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Dell          | XPS 15 9560                 | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | Laptop 15-bs0xx             | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| Panasonic     | FZ55-2                      | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| Acer          | Aspire A515-54              | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Sony          | VGN-Z31XN_B                 | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Dell          | XPS 13 9360                 | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| NEC Comput... | NEC Versa M370              | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| Lenovo        | G50-45 80E3                 | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| ASUSTek       | GL502VMK                    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| HP            | ProBook 470 G5              | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Unknown       | Unknown                     | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | MacBookPro14,1              | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| HP            | Compaq 8710w                | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| Samsung       | 750XED                      | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| Toshiba       | Satellite C70D-A            | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| HP            | OMEN by Laptop              | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| MSI           | GF63 Thin 9SC               | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Dell          | XPS 13 9305                 | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [8080b9becd](https://linux-hardware.org/?probe=8080b9becd) | May 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| Dell          | Latitude E6330              | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| Lenovo        | ThinkPad X280 20KES94F05    | [16b4cbc9fb](https://linux-hardware.org/?probe=16b4cbc9fb) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Dell          | XPS 15 9570                 | [01a95b61fe](https://linux-hardware.org/?probe=01a95b61fe) | May 02, 2022 |
| ASUSTek       | X550LD                      | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| ASUSTek       | X756UQ                      | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [21fcbc1850](https://linux-hardware.org/?probe=21fcbc1850) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| BLAUPUNKT     | Discovery 1011WI            | [c20b87673e](https://linux-hardware.org/?probe=c20b87673e) | Apr 24, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK E744               | [ca56dc9824](https://linux-hardware.org/?probe=ca56dc9824) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| Lenovo        | ThinkPad T520 4243AP1       | [7723ab4bd9](https://linux-hardware.org/?probe=7723ab4bd9) | Apr 19, 2022 |
| MSI           | GL65 Leopard 10SER          | [2bdfe0279e](https://linux-hardware.org/?probe=2bdfe0279e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440s 20ARS1940... | [a7fbe1af34](https://linux-hardware.org/?probe=a7fbe1af34) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| Acer          | Aspire 5735                 | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Dell          | Inspiron 15-3567            | [4639b09a3e](https://linux-hardware.org/?probe=4639b09a3e) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | Latitude 5591               | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [5aafaf0890](https://linux-hardware.org/?probe=5aafaf0890) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [983dbbf9e8](https://linux-hardware.org/?probe=983dbbf9e8) | Apr 13, 2022 |
| Acer          | Aspire 7745G                | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [09f8f09862](https://linux-hardware.org/?probe=09f8f09862) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [da1cd5bf6e](https://linux-hardware.org/?probe=da1cd5bf6e) | Apr 11, 2022 |
| Google        | Akali 360                   | [dccccb359b](https://linux-hardware.org/?probe=dccccb359b) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [01f57dd952](https://linux-hardware.org/?probe=01f57dd952) | Apr 10, 2022 |
| HP            | ProBook 470 G2              | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Dell          | Latitude E6430              | [dd09c863c8](https://linux-hardware.org/?probe=dd09c863c8) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [af324f356f](https://linux-hardware.org/?probe=af324f356f) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [fc358abe4b](https://linux-hardware.org/?probe=fc358abe4b) | Apr 06, 2022 |
| HP            | 470 G7 Notebook PC          | [34fc91d9ac](https://linux-hardware.org/?probe=34fc91d9ac) | Apr 06, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| Dell          | XPS 13 7390                 | [8c4011afa9](https://linux-hardware.org/?probe=8c4011afa9) | Apr 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [94a9015090](https://linux-hardware.org/?probe=94a9015090) | Apr 03, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [086261ecef](https://linux-hardware.org/?probe=086261ecef) | Apr 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4731581e9b](https://linux-hardware.org/?probe=4731581e9b) | Mar 31, 2022 |
| HP            | ZBook Studio G4             | [d5ec5c3e8e](https://linux-hardware.org/?probe=d5ec5c3e8e) | Mar 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| HP            | ProBook 470 G5              | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| Acer          | Aspire 8930                 | [6774be59d3](https://linux-hardware.org/?probe=6774be59d3) | Mar 26, 2022 |
| HP            | EliteBook Folio 1040 G1     | [bbdb3c316f](https://linux-hardware.org/?probe=bbdb3c316f) | Mar 25, 2022 |
| HP            | EliteBook Folio 1040 G1     | [6096fbc1ba](https://linux-hardware.org/?probe=6096fbc1ba) | Mar 25, 2022 |
| ASUSTek       | N56VZ                       | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| Packard Be... | DOT S                       | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [26cd5cf250](https://linux-hardware.org/?probe=26cd5cf250) | Mar 20, 2022 |
| ASUSTek       | X555LJ                      | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Dell          | XPS 13 9370                 | [1feeb83fb4](https://linux-hardware.org/?probe=1feeb83fb4) | Mar 19, 2022 |
| Acer          | Aspire 8930                 | [79f6f7d9c1](https://linux-hardware.org/?probe=79f6f7d9c1) | Mar 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| HP            | Laptop 15-bs0xx             | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| ASUSTek       | X756UQ                      | [30ec3132c4](https://linux-hardware.org/?probe=30ec3132c4) | Mar 12, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | [a48bd2e59b](https://linux-hardware.org/?probe=a48bd2e59b) | Mar 10, 2022 |
| HP            | Pavilion zd8000 (EL052EA... | [18f42a184c](https://linux-hardware.org/?probe=18f42a184c) | Mar 08, 2022 |
| Dell          | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Dell          | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | [b4087fab13](https://linux-hardware.org/?probe=b4087fab13) | Mar 06, 2022 |
| Dell          | Latitude E6330              | [f4491d2da7](https://linux-hardware.org/?probe=f4491d2da7) | Mar 06, 2022 |
| Acer          | Aspire A315-21              | [435c237f8f](https://linux-hardware.org/?probe=435c237f8f) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| HP            | Pavilion dv6                | [d04802b99e](https://linux-hardware.org/?probe=d04802b99e) | Feb 27, 2022 |
| HP            | Pavilion 15                 | [e72fbddbc9](https://linux-hardware.org/?probe=e72fbddbc9) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8166a6711c](https://linux-hardware.org/?probe=8166a6711c) | Feb 25, 2022 |
| Packard Be... | EasyNote_MX67               | [0687a8a072](https://linux-hardware.org/?probe=0687a8a072) | Feb 23, 2022 |
| Dell          | Latitude E5550              | [7eb0675554](https://linux-hardware.org/?probe=7eb0675554) | Feb 22, 2022 |
| HP            | Pavilion 15                 | [6aaa686668](https://linux-hardware.org/?probe=6aaa686668) | Feb 22, 2022 |
| Sony          | VGN-FW51JF_H                | [03c4e88514](https://linux-hardware.org/?probe=03c4e88514) | Feb 22, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | [99676b9365](https://linux-hardware.org/?probe=99676b9365) | Feb 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [59476747e2](https://linux-hardware.org/?probe=59476747e2) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [ad3eb03b54](https://linux-hardware.org/?probe=ad3eb03b54) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [83b3333eb0](https://linux-hardware.org/?probe=83b3333eb0) | Feb 20, 2022 |
| Acer          | Aspire V3-771               | [962c444158](https://linux-hardware.org/?probe=962c444158) | Feb 19, 2022 |
| ASUSTek       | P751JA                      | [54c2cab341](https://linux-hardware.org/?probe=54c2cab341) | Feb 18, 2022 |
| ASUSTek       | X756UQ                      | [757a05c274](https://linux-hardware.org/?probe=757a05c274) | Feb 18, 2022 |
| Acer          | Aspire 7745G                | [b32ffb9adc](https://linux-hardware.org/?probe=b32ffb9adc) | Feb 17, 2022 |
| Acer          | Aspire 5750G                | [3bb86aa608](https://linux-hardware.org/?probe=3bb86aa608) | Feb 17, 2022 |
| ASUSTek       | P751JA                      | [8e2a0e2970](https://linux-hardware.org/?probe=8e2a0e2970) | Feb 16, 2022 |
| HP            | Pavilion dv6500             | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| HP            | Pavilion 15                 | [67825b30b9](https://linux-hardware.org/?probe=67825b30b9) | Feb 15, 2022 |
| HP            | ProBook 6560b               | [425caa152d](https://linux-hardware.org/?probe=425caa152d) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| Lenovo        | ThinkPad X260 20F5S3FY00    | [08006b1c3a](https://linux-hardware.org/?probe=08006b1c3a) | Feb 13, 2022 |
| ASUSTek       | N501JW                      | [7937164c8a](https://linux-hardware.org/?probe=7937164c8a) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [baf12e4099](https://linux-hardware.org/?probe=baf12e4099) | Feb 09, 2022 |
| GPD           | G1621-02                    | [d823ea2989](https://linux-hardware.org/?probe=d823ea2989) | Feb 09, 2022 |
| Acer          | Aspire A715-74G             | [00f0fe6cd3](https://linux-hardware.org/?probe=00f0fe6cd3) | Feb 09, 2022 |
| HP            | Pavilion dv7                | [03b19f857f](https://linux-hardware.org/?probe=03b19f857f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T500 20828VG       | [f79076499b](https://linux-hardware.org/?probe=f79076499b) | Feb 09, 2022 |
| PC Special... | GK5NPFO                     | [14695b59b4](https://linux-hardware.org/?probe=14695b59b4) | Feb 08, 2022 |
| Toshiba       | Satellite C855-112          | [99cb514a47](https://linux-hardware.org/?probe=99cb514a47) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [48b1ca5fbc](https://linux-hardware.org/?probe=48b1ca5fbc) | Feb 07, 2022 |
| Lenovo        | ThinkPad E495 20NES01600    | [c40a0c5222](https://linux-hardware.org/?probe=c40a0c5222) | Feb 07, 2022 |
| Sony          | VGN-FW51JF_H                | [0e5f92c7b7](https://linux-hardware.org/?probe=0e5f92c7b7) | Feb 07, 2022 |
| Acer          | Nitro AN515-52              | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | [0610b130c8](https://linux-hardware.org/?probe=0610b130c8) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | [519bc1d808](https://linux-hardware.org/?probe=519bc1d808) | Feb 05, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [0b95e33d17](https://linux-hardware.org/?probe=0b95e33d17) | Feb 03, 2022 |
| HP            | EliteBook 8570w             | [690ef309e9](https://linux-hardware.org/?probe=690ef309e9) | Feb 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [3171e9710d](https://linux-hardware.org/?probe=3171e9710d) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| Dell          | G3 3500                     | [141e63ae77](https://linux-hardware.org/?probe=141e63ae77) | Feb 02, 2022 |
| Sony          | SVE1713F1EW                 | [34db9cd3c0](https://linux-hardware.org/?probe=34db9cd3c0) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Sony          | SVE1713F1EW                 | [591b6e4d01](https://linux-hardware.org/?probe=591b6e4d01) | Feb 01, 2022 |
| Unknown       | Unknown                     | [f3b0dd4384](https://linux-hardware.org/?probe=f3b0dd4384) | Jan 31, 2022 |
| MSI           | GE70 2OC\2OD\2OE            | [f9efba7bbf](https://linux-hardware.org/?probe=f9efba7bbf) | Jan 30, 2022 |
| Sony          | SVE1712W1EB                 | [c6b525e9c3](https://linux-hardware.org/?probe=c6b525e9c3) | Jan 29, 2022 |
| Sony          | SVE1712W1EB                 | [c780c90c73](https://linux-hardware.org/?probe=c780c90c73) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | [a53478c6b1](https://linux-hardware.org/?probe=a53478c6b1) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | [90e1046590](https://linux-hardware.org/?probe=90e1046590) | Jan 28, 2022 |
| ASUSTek       | X551CA                      | [0cb832f85f](https://linux-hardware.org/?probe=0cb832f85f) | Jan 27, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [7a90772bfd](https://linux-hardware.org/?probe=7a90772bfd) | Jan 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| HP            | Pavilion dv7                | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| HP            | ProBook 6570b               | [681a804c88](https://linux-hardware.org/?probe=681a804c88) | Jan 24, 2022 |
| Lenovo        | ThinkPad X250 20CMS02F00    | [e4d90a5ae8](https://linux-hardware.org/?probe=e4d90a5ae8) | Jan 23, 2022 |
| Lenovo        | ThinkPad T420 423664U       | [0e2bb9a59f](https://linux-hardware.org/?probe=0e2bb9a59f) | Jan 23, 2022 |
| HP            | ProBook 470 G5              | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | XPS 13 9350                 | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| Dell          | Latitude E6530              | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SNC... | [0b0ddf4175](https://linux-hardware.org/?probe=0b0ddf4175) | Jan 21, 2022 |
| ASUSTek       | GL552VW                     | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| Dell          | Latitude E6530              | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [cf36481feb](https://linux-hardware.org/?probe=cf36481feb) | Jan 16, 2022 |
| Dell          | XPS 13 9305                 | [d6594c7edb](https://linux-hardware.org/?probe=d6594c7edb) | Jan 15, 2022 |
| Dell          | Latitude 5520               | [95721c3566](https://linux-hardware.org/?probe=95721c3566) | Jan 15, 2022 |
| ASUSTek       | X580VD                      | [9cb7ebea38](https://linux-hardware.org/?probe=9cb7ebea38) | Jan 14, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [e293ddf5fc](https://linux-hardware.org/?probe=e293ddf5fc) | Jan 14, 2022 |
| Dell          | Latitude 7490               | [98c318edfd](https://linux-hardware.org/?probe=98c318edfd) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de24bac4e8](https://linux-hardware.org/?probe=de24bac4e8) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [7edab0851b](https://linux-hardware.org/?probe=7edab0851b) | Jan 12, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Acer          | Aspire A315-21              | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [62c4e26a01](https://linux-hardware.org/?probe=62c4e26a01) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| Dell          | XPS 13 9305                 | [83ccc00b28](https://linux-hardware.org/?probe=83ccc00b28) | Jan 08, 2022 |
| Dell          | Latitude E6330              | [da29c6f100](https://linux-hardware.org/?probe=da29c6f100) | Jan 08, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5ed2055b1e](https://linux-hardware.org/?probe=5ed2055b1e) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| HP            | Compaq 8710w                | [ab5f731d97](https://linux-hardware.org/?probe=ab5f731d97) | Jan 05, 2022 |
| Acer          | Aspire 7520                 | [462c034a56](https://linux-hardware.org/?probe=462c034a56) | Jan 04, 2022 |
| HP            | Compaq 8710w                | [573e8e760f](https://linux-hardware.org/?probe=573e8e760f) | Jan 03, 2022 |
| Dell          | Latitude E6510              | [7a6c58b609](https://linux-hardware.org/?probe=7a6c58b609) | Jan 02, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e6e4d232a9](https://linux-hardware.org/?probe=e6e4d232a9) | Jan 02, 2022 |
| HP            | EliteBook 6930p (GB995EA... | [e0a482ab1e](https://linux-hardware.org/?probe=e0a482ab1e) | Jan 02, 2022 |
| Packard Be... | EasyNote TK85               | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| HP            | EliteBook 850 G5            | [f385608043](https://linux-hardware.org/?probe=f385608043) | Dec 28, 2021 |
| Sony          | VPCEL1E1E                   | [4deb7655c4](https://linux-hardware.org/?probe=4deb7655c4) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [0af1aded1f](https://linux-hardware.org/?probe=0af1aded1f) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Apple         | MacBookPro10,1              | [381c7dee2d](https://linux-hardware.org/?probe=381c7dee2d) | Dec 25, 2021 |
| HP            | ProBook 640 G4              | [f1fa3d65b1](https://linux-hardware.org/?probe=f1fa3d65b1) | Dec 25, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [14d7bc4e66](https://linux-hardware.org/?probe=14d7bc4e66) | Dec 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| MSI           | GE72 6QC                    | [4c5a8f6b4a](https://linux-hardware.org/?probe=4c5a8f6b4a) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [88a4b38685](https://linux-hardware.org/?probe=88a4b38685) | Dec 21, 2021 |
| HP            | G62                         | [fac3d0a6b6](https://linux-hardware.org/?probe=fac3d0a6b6) | Dec 21, 2021 |
| ASUSTek       | N501JW                      | [2b928f1e66](https://linux-hardware.org/?probe=2b928f1e66) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Google        | Pantheon                    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| HP            | Pavilion dv7                | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Acer          | Swift SF113-31              | [e951b45254](https://linux-hardware.org/?probe=e951b45254) | Dec 12, 2021 |
| Clevo         | W270HU                      | [486cbb154a](https://linux-hardware.org/?probe=486cbb154a) | Dec 12, 2021 |
| Dell          | Latitude E5410              | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Clevo         | W270HU                      | [5152801cbe](https://linux-hardware.org/?probe=5152801cbe) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Lenovo        | G50-80 80E5                 | [77ee4f08a8](https://linux-hardware.org/?probe=77ee4f08a8) | Dec 10, 2021 |
| Lenovo        | ThinkPad X280 20KES94F05    | [ba3d89dca3](https://linux-hardware.org/?probe=ba3d89dca3) | Dec 08, 2021 |
| Acer          | Aspire 5750G                | [fb84f5c3c5](https://linux-hardware.org/?probe=fb84f5c3c5) | Dec 05, 2021 |
| HP            | ProBook 470 G5              | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| Acer          | Aspire 7736                 | [20d3c3fff5](https://linux-hardware.org/?probe=20d3c3fff5) | Dec 01, 2021 |
| Celestica     | D4040                       | [109f886f1d](https://linux-hardware.org/?probe=109f886f1d) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [3a85954b66](https://linux-hardware.org/?probe=3a85954b66) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [5271c46262](https://linux-hardware.org/?probe=5271c46262) | Nov 29, 2021 |
| HP            | ProBook 640 G4              | [e58b0e7945](https://linux-hardware.org/?probe=e58b0e7945) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6e63fb12a3](https://linux-hardware.org/?probe=6e63fb12a3) | Nov 28, 2021 |
| HP            | Compaq 6720s                | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Dell          | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Toshiba       | Satellite A300              | [c62dc3b138](https://linux-hardware.org/?probe=c62dc3b138) | Nov 25, 2021 |
| HP            | EliteBook 735 G5            | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| ASUSTek       | GL552VW                     | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [8c5bc064e9](https://linux-hardware.org/?probe=8c5bc064e9) | Nov 21, 2021 |
| Dell          | Latitude D630               | [0d437ca2f6](https://linux-hardware.org/?probe=0d437ca2f6) | Nov 21, 2021 |
| Notebook      | PA70ES                      | [55d43af19e](https://linux-hardware.org/?probe=55d43af19e) | Nov 20, 2021 |
| Lenovo        | ThinkPad E495 20NES01600    | [aacc57f134](https://linux-hardware.org/?probe=aacc57f134) | Nov 17, 2021 |
| Notebook      | N24_25JU                    | [30df18e398](https://linux-hardware.org/?probe=30df18e398) | Nov 16, 2021 |
| Teclast       | F6 Plus                     | [7e5836dbaa](https://linux-hardware.org/?probe=7e5836dbaa) | Nov 16, 2021 |
| Dell          | Latitude D620               | [855218ab46](https://linux-hardware.org/?probe=855218ab46) | Nov 16, 2021 |
| ASUSTek       | Strix GL703GS_GL703GS       | [6eb0749ee8](https://linux-hardware.org/?probe=6eb0749ee8) | Nov 15, 2021 |
| ASUSTek       | X75VC                       | [39352780e5](https://linux-hardware.org/?probe=39352780e5) | Nov 12, 2021 |
| Packard Be... | EasyNote TE11BZ             | [de427e19ea](https://linux-hardware.org/?probe=de427e19ea) | Nov 11, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | [0cbad8aae1](https://linux-hardware.org/?probe=0cbad8aae1) | Nov 11, 2021 |
| Acer          | AO751h                      | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Sony          | VPCF13M1E                   | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| Toshiba       | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Unknown       | Unknown                     | [ed806d64c8](https://linux-hardware.org/?probe=ed806d64c8) | Nov 05, 2021 |
| Gigabyte      | Spring Peak                 | [fc1efa8df5](https://linux-hardware.org/?probe=fc1efa8df5) | Nov 04, 2021 |
| Lenovo        | G50-80 80E5                 | [2ecc44141a](https://linux-hardware.org/?probe=2ecc44141a) | Oct 30, 2021 |
| HP            | ZBook Studio G4             | [984d3cdc29](https://linux-hardware.org/?probe=984d3cdc29) | Oct 30, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [3f5dd495d5](https://linux-hardware.org/?probe=3f5dd495d5) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [65eac6abc6](https://linux-hardware.org/?probe=65eac6abc6) | Oct 27, 2021 |
| Dell          | Latitude 7390               | [92dcb677f7](https://linux-hardware.org/?probe=92dcb677f7) | Oct 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [39e318621b](https://linux-hardware.org/?probe=39e318621b) | Oct 26, 2021 |
| Notebook      | P7xxDM3(-G)                 | [5c62ec0ce3](https://linux-hardware.org/?probe=5c62ec0ce3) | Oct 24, 2021 |
| Dell          | Studio 1555                 | [3fed161971](https://linux-hardware.org/?probe=3fed161971) | Oct 24, 2021 |
| HP            | ProBook 4540s               | [49ce392cd2](https://linux-hardware.org/?probe=49ce392cd2) | Oct 24, 2021 |
| HP            | ProBook 470 G5              | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| Notebook      | P7xxDM3(-G)                 | [250e2a46b0](https://linux-hardware.org/?probe=250e2a46b0) | Oct 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [86bc5ddc56](https://linux-hardware.org/?probe=86bc5ddc56) | Oct 21, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [44537c7fba](https://linux-hardware.org/?probe=44537c7fba) | Oct 20, 2021 |
| Notebook      | PB50_70RF,RD,RC             | [ec41eeb7c0](https://linux-hardware.org/?probe=ec41eeb7c0) | Oct 20, 2021 |
| ASUSTek       | K72F                        | [0eedfc8a67](https://linux-hardware.org/?probe=0eedfc8a67) | Oct 20, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [2412314ad9](https://linux-hardware.org/?probe=2412314ad9) | Oct 18, 2021 |
| TUXEDO        | Aura 15 Gen1                | [57260c1999](https://linux-hardware.org/?probe=57260c1999) | Oct 18, 2021 |
| Lenovo        | G50-80 80E5                 | [7075439e69](https://linux-hardware.org/?probe=7075439e69) | Oct 17, 2021 |
| Acer          | Nitro AN515-55              | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| HP            | ProBook 4540s               | [046acc5982](https://linux-hardware.org/?probe=046acc5982) | Oct 14, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [a5072cec8c](https://linux-hardware.org/?probe=a5072cec8c) | Oct 10, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [4bb69f9fcc](https://linux-hardware.org/?probe=4bb69f9fcc) | Oct 10, 2021 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | [bf3209df55](https://linux-hardware.org/?probe=bf3209df55) | Oct 07, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [03ba78f145](https://linux-hardware.org/?probe=03ba78f145) | Oct 04, 2021 |
| ASUSTek       | N76VZ                       | [8e260cdbc8](https://linux-hardware.org/?probe=8e260cdbc8) | Oct 04, 2021 |
| ASUSTek       | N76VZ                       | [94e6fbc140](https://linux-hardware.org/?probe=94e6fbc140) | Oct 03, 2021 |
| Google        | Pantheon                    | [72ded95fab](https://linux-hardware.org/?probe=72ded95fab) | Oct 02, 2021 |
| HP            | ProBook 470 G5              | [fef4cfba03](https://linux-hardware.org/?probe=fef4cfba03) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | [f6fd6bd3dc](https://linux-hardware.org/?probe=f6fd6bd3dc) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | [fbcd6bfe42](https://linux-hardware.org/?probe=fbcd6bfe42) | Oct 02, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Notebook      | P7xxTM1                     | [a63472fe1d](https://linux-hardware.org/?probe=a63472fe1d) | Sep 30, 2021 |
| Dell          | Precision 3561              | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| HP            | Elite x2 1012 G1            | [90cbd6d0a7](https://linux-hardware.org/?probe=90cbd6d0a7) | Sep 26, 2021 |
| Apple         | MacBookPro16,2              | [f1c5cf0c43](https://linux-hardware.org/?probe=f1c5cf0c43) | Sep 25, 2021 |
| ASUSTek       | N56VZ                       | [824dc21fac](https://linux-hardware.org/?probe=824dc21fac) | Sep 23, 2021 |
| ASUSTek       | N56VZ                       | [6c4623e356](https://linux-hardware.org/?probe=6c4623e356) | Sep 23, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [81c1403674](https://linux-hardware.org/?probe=81c1403674) | Sep 22, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [710301deba](https://linux-hardware.org/?probe=710301deba) | Sep 22, 2021 |
| Google        | Pantheon                    | [eaa5a17c4b](https://linux-hardware.org/?probe=eaa5a17c4b) | Sep 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | X540SA                      | [177c537ae0](https://linux-hardware.org/?probe=177c537ae0) | Sep 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [094059270a](https://linux-hardware.org/?probe=094059270a) | Sep 16, 2021 |
| HP            | EliteBook 6930p             | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Dell          | Inspiron 14-3452            | [ec9da4ca73](https://linux-hardware.org/?probe=ec9da4ca73) | Sep 14, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | [3c213b818b](https://linux-hardware.org/?probe=3c213b818b) | Sep 14, 2021 |
| Lenovo        | ThinkPad X390 20Q00058MH    | [01755fd33c](https://linux-hardware.org/?probe=01755fd33c) | Sep 13, 2021 |
| Medion        | WIM2140                     | [cf2f9bdca7](https://linux-hardware.org/?probe=cf2f9bdca7) | Sep 12, 2021 |
| Medion        | WIM2140                     | [0023f88625](https://linux-hardware.org/?probe=0023f88625) | Sep 12, 2021 |
| ASUSTek       | F70SL                       | [32a3e01bbd](https://linux-hardware.org/?probe=32a3e01bbd) | Sep 12, 2021 |
| ASUSTek       | F70SL                       | [4db3ac07eb](https://linux-hardware.org/?probe=4db3ac07eb) | Sep 12, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | [4d544fc5d5](https://linux-hardware.org/?probe=4d544fc5d5) | Sep 09, 2021 |
| Acer          | Aspire A514-53              | [a4c57ccf99](https://linux-hardware.org/?probe=a4c57ccf99) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Dell          | Latitude 5520               | [7e327f4604](https://linux-hardware.org/?probe=7e327f4604) | Sep 09, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [6d55ad062f](https://linux-hardware.org/?probe=6d55ad062f) | Sep 08, 2021 |
| Lenovo        | Z50-70 20354                | [cfcaf524be](https://linux-hardware.org/?probe=cfcaf524be) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a47848e559](https://linux-hardware.org/?probe=a47848e559) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| ASUSTek       | K53U                        | [a2f8f1be7d](https://linux-hardware.org/?probe=a2f8f1be7d) | Sep 04, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| Dell          | Vostro 3300                 | [7d86f3f367](https://linux-hardware.org/?probe=7d86f3f367) | Aug 31, 2021 |
| Dell          | Vostro 3300                 | [be8b05e2a2](https://linux-hardware.org/?probe=be8b05e2a2) | Aug 31, 2021 |
| HP            | Pavilion 17                 | [ca125d2f3c](https://linux-hardware.org/?probe=ca125d2f3c) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| YJKC          | vBOOK Plus RVP7             | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| HP            | Laptop 14s-fq0xxx           | [ad12a8f4b5](https://linux-hardware.org/?probe=ad12a8f4b5) | Aug 26, 2021 |
| Dell          | Latitude E5440              | [ed4911006a](https://linux-hardware.org/?probe=ed4911006a) | Aug 23, 2021 |
| Lenovo        | Z50-70 20354                | [5fcfdd2678](https://linux-hardware.org/?probe=5fcfdd2678) | Aug 20, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | ProBook 430 G1              | [9567d77449](https://linux-hardware.org/?probe=9567d77449) | Aug 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [05e4a8bcb2](https://linux-hardware.org/?probe=05e4a8bcb2) | Aug 16, 2021 |
| Dell          | XPS 17 9700                 | [0c38591981](https://linux-hardware.org/?probe=0c38591981) | Aug 16, 2021 |
| HP            | Compaq 8710w                | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [eb8c86aba1](https://linux-hardware.org/?probe=eb8c86aba1) | Aug 13, 2021 |
| HP            | ProBook 6460b               | [83029580f3](https://linux-hardware.org/?probe=83029580f3) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a27b7d75c](https://linux-hardware.org/?probe=1a27b7d75c) | Aug 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f2c3f335f8](https://linux-hardware.org/?probe=f2c3f335f8) | Aug 09, 2021 |
| Dell          | Latitude 5500               | [7cb9c5d946](https://linux-hardware.org/?probe=7cb9c5d946) | Aug 09, 2021 |
| HP            | ProBook 430 G1              | [f7438f6cab](https://linux-hardware.org/?probe=f7438f6cab) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| Lenovo        | B40-30 80F1                 | [d7f9ec3de6](https://linux-hardware.org/?probe=d7f9ec3de6) | Aug 06, 2021 |
| HP            | ProBook 4540s               | [52b0186956](https://linux-hardware.org/?probe=52b0186956) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [6af058344f](https://linux-hardware.org/?probe=6af058344f) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Acer          | Aspire ES1-111              | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| Acer          | Swift SF314-54G             | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | [f1773945f2](https://linux-hardware.org/?probe=f1773945f2) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| ASUSTek       | UX305CA                     | [7fec0c7d28](https://linux-hardware.org/?probe=7fec0c7d28) | Aug 01, 2021 |
| HP            | Pavilion dv7                | [2966b0fcc3](https://linux-hardware.org/?probe=2966b0fcc3) | Jul 31, 2021 |
| Dell          | Latitude E6530              | [3318146af3](https://linux-hardware.org/?probe=3318146af3) | Jul 31, 2021 |
| Dell          | XPS 15 7590                 | [b423307c7c](https://linux-hardware.org/?probe=b423307c7c) | Jul 28, 2021 |
| Toshiba       | Satellite C850D-11K         | [c442634262](https://linux-hardware.org/?probe=c442634262) | Jul 24, 2021 |
| Lenovo        | ThinkPad L580 20LXS4K600    | [fc8ad7a780](https://linux-hardware.org/?probe=fc8ad7a780) | Jul 20, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1a3712c974](https://linux-hardware.org/?probe=1a3712c974) | Jul 19, 2021 |
| HP            | Laptop 17-by4xxx            | [d66405d958](https://linux-hardware.org/?probe=d66405d958) | Jul 19, 2021 |
| HP            | Pavilion Notebook           | [40d1ea391b](https://linux-hardware.org/?probe=40d1ea391b) | Jul 17, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [167ddb49ce](https://linux-hardware.org/?probe=167ddb49ce) | Jul 16, 2021 |
| HP            | Laptop 17-by4xxx            | [460e87a27d](https://linux-hardware.org/?probe=460e87a27d) | Jul 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [cb44035a70](https://linux-hardware.org/?probe=cb44035a70) | Jul 13, 2021 |
| HP            | Pavilion Notebook           | [0b23e90cfc](https://linux-hardware.org/?probe=0b23e90cfc) | Jul 12, 2021 |
| HP            | Laptop 17-by4xxx            | [fad62f8ce2](https://linux-hardware.org/?probe=fad62f8ce2) | Jul 08, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cc542d5a92](https://linux-hardware.org/?probe=cc542d5a92) | Jul 07, 2021 |
| HP            | Laptop 17-by4xxx            | [bd9ce451e8](https://linux-hardware.org/?probe=bd9ce451e8) | Jul 07, 2021 |
| Dell          | Latitude D530               | [daf9b88063](https://linux-hardware.org/?probe=daf9b88063) | Jul 06, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Dell          | XPS 15 9570                 | [f8f823ef89](https://linux-hardware.org/?probe=f8f823ef89) | Jul 02, 2021 |
| Acer          | Aspire E5-771G              | [75dbf43fd0](https://linux-hardware.org/?probe=75dbf43fd0) | Jul 02, 2021 |
| Acer          | Aspire 5250                 | [4a9dcc3234](https://linux-hardware.org/?probe=4a9dcc3234) | Jul 01, 2021 |
| Sony          | SVE1713Y1EB                 | [dfe0f426a0](https://linux-hardware.org/?probe=dfe0f426a0) | Jun 28, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [39f7878023](https://linux-hardware.org/?probe=39f7878023) | Jun 28, 2021 |
| Acer          | Swift SF114-32              | [016ae4ca5b](https://linux-hardware.org/?probe=016ae4ca5b) | Jun 26, 2021 |
| Packard Be... | EasyNote LV44HC             | [a02e170d18](https://linux-hardware.org/?probe=a02e170d18) | Jun 26, 2021 |
| HP            | Compaq 8710w                | [ee58ebb902](https://linux-hardware.org/?probe=ee58ebb902) | Jun 24, 2021 |
| Acer          | Aspire A314-22              | [195778fcc3](https://linux-hardware.org/?probe=195778fcc3) | Jun 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2ddbaed76b](https://linux-hardware.org/?probe=2ddbaed76b) | Jun 21, 2021 |
| Dell          | Latitude 5420               | [1356be4391](https://linux-hardware.org/?probe=1356be4391) | Jun 18, 2021 |
| Dell          | Latitude E5570              | [e73c4bfd97](https://linux-hardware.org/?probe=e73c4bfd97) | Jun 18, 2021 |
| Fujitsu       | FMVE01004                   | [ae55084eb8](https://linux-hardware.org/?probe=ae55084eb8) | Jun 17, 2021 |
| HP            | EliteBook 8740w             | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| Lenovo        | ThinkPad Helix 37027L8      | [7aebf5c1e1](https://linux-hardware.org/?probe=7aebf5c1e1) | Jun 15, 2021 |
| Dell          | Latitude E6330              | [69619cc6a0](https://linux-hardware.org/?probe=69619cc6a0) | Jun 12, 2021 |
| Dell          | Latitude E5570              | [d0c559ce72](https://linux-hardware.org/?probe=d0c559ce72) | Jun 12, 2021 |
| Acer          | Aspire 5100                 | [47cb66adb9](https://linux-hardware.org/?probe=47cb66adb9) | Jun 11, 2021 |
| Acer          | Aspire 5100                 | [d7758e5c1c](https://linux-hardware.org/?probe=d7758e5c1c) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Dell          | Latitude 7390               | [38724f6fd8](https://linux-hardware.org/?probe=38724f6fd8) | Jun 11, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [fa116a8e6d](https://linux-hardware.org/?probe=fa116a8e6d) | Jun 11, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [53af8c5600](https://linux-hardware.org/?probe=53af8c5600) | Jun 09, 2021 |
| ASUSTek       | K50IJ                       | [5ca8108e62](https://linux-hardware.org/?probe=5ca8108e62) | Jun 09, 2021 |
| HP            | ProBook 4730s               | [2e561b3995](https://linux-hardware.org/?probe=2e561b3995) | Jun 09, 2021 |
| ASUSTek       | X510UQ                      | [78ae37cf88](https://linux-hardware.org/?probe=78ae37cf88) | Jun 09, 2021 |
| Acer          | Aspire E5-771G              | [292f75ec92](https://linux-hardware.org/?probe=292f75ec92) | Jun 08, 2021 |
| HP            | ProBook 470 G5              | [517c800c42](https://linux-hardware.org/?probe=517c800c42) | Jun 07, 2021 |
| Apple         | MacBookPro11,1              | [f6f2cf5f89](https://linux-hardware.org/?probe=f6f2cf5f89) | Jun 05, 2021 |
| ASUSTek       | N76VJ                       | [278ef790cf](https://linux-hardware.org/?probe=278ef790cf) | Jun 05, 2021 |
| ASUSTek       | X302LA                      | [437c3c84e2](https://linux-hardware.org/?probe=437c3c84e2) | Jun 04, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [6b168c2c19](https://linux-hardware.org/?probe=6b168c2c19) | Jun 03, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1fa6a4756a](https://linux-hardware.org/?probe=1fa6a4756a) | Jun 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| Toshiba       | Satellite C670-17D          | [57b6c4f249](https://linux-hardware.org/?probe=57b6c4f249) | May 31, 2021 |
| Gigabyte      | Spring Peak                 | [20896c9bef](https://linux-hardware.org/?probe=20896c9bef) | May 29, 2021 |
| HP            | EliteBook 8440p             | [66a3f34824](https://linux-hardware.org/?probe=66a3f34824) | May 28, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [80fe8cc363](https://linux-hardware.org/?probe=80fe8cc363) | May 28, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [70849260b4](https://linux-hardware.org/?probe=70849260b4) | May 28, 2021 |
| HP            | EliteBook 8760w             | [dae07bf8cb](https://linux-hardware.org/?probe=dae07bf8cb) | May 26, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [065a3089d4](https://linux-hardware.org/?probe=065a3089d4) | May 24, 2021 |
| Samsung       | R780/R778                   | [3f35c907a2](https://linux-hardware.org/?probe=3f35c907a2) | May 21, 2021 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [6ca37bdf8b](https://linux-hardware.org/?probe=6ca37bdf8b) | May 21, 2021 |
| HP            | ProBook 6570b               | [2b341b7bf9](https://linux-hardware.org/?probe=2b341b7bf9) | May 21, 2021 |
| Acer          | Aspire 7750                 | [ecf8d0fa55](https://linux-hardware.org/?probe=ecf8d0fa55) | May 18, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1579b9c9d7](https://linux-hardware.org/?probe=1579b9c9d7) | May 16, 2021 |
| Sony          | VPCEL1E1E                   | [33f8327bbe](https://linux-hardware.org/?probe=33f8327bbe) | May 13, 2021 |
| Sony          | VPCEL1E1E                   | [4e53335200](https://linux-hardware.org/?probe=4e53335200) | May 13, 2021 |
| Toshiba       | Satellite L855              | [70615b0780](https://linux-hardware.org/?probe=70615b0780) | May 12, 2021 |
| ASUSTek       | N53SN                       | [63b3bf3fd2](https://linux-hardware.org/?probe=63b3bf3fd2) | May 11, 2021 |
| Dell          | Latitude E5470              | [9ed0c349f9](https://linux-hardware.org/?probe=9ed0c349f9) | May 10, 2021 |
| Notebook      | P7xxDM3(-G)                 | [31cd72db1b](https://linux-hardware.org/?probe=31cd72db1b) | May 08, 2021 |
| ASUSTek       | N76VJ                       | [3b614f915c](https://linux-hardware.org/?probe=3b614f915c) | May 08, 2021 |
| HP            | ZBook 15 G6                 | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6654328a0f](https://linux-hardware.org/?probe=6654328a0f) | May 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [48ff783788](https://linux-hardware.org/?probe=48ff783788) | May 05, 2021 |
| Lenovo        | G710 20252                  | [e77f1af187](https://linux-hardware.org/?probe=e77f1af187) | May 04, 2021 |
| HP            | ProBook 450 G0              | [f1828f8b3a](https://linux-hardware.org/?probe=f1828f8b3a) | May 03, 2021 |
| Dell          | Latitude E5570              | [497144cda8](https://linux-hardware.org/?probe=497144cda8) | Apr 23, 2021 |
| Dell          | XPS 13 9310                 | [3d4e2aaf41](https://linux-hardware.org/?probe=3d4e2aaf41) | Apr 22, 2021 |
| Toshiba       | Satellite C660              | [12faeec33f](https://linux-hardware.org/?probe=12faeec33f) | Apr 21, 2021 |
| Notebook      | N85_N87HCHN                 | [9a08ae1df0](https://linux-hardware.org/?probe=9a08ae1df0) | Apr 19, 2021 |
| Dell          | Latitude E4310              | [4135cd0970](https://linux-hardware.org/?probe=4135cd0970) | Apr 19, 2021 |
| HP            | ProBook 470 G5              | [1f0b5b042f](https://linux-hardware.org/?probe=1f0b5b042f) | Apr 18, 2021 |
| Acer          | Aspire E5-771G              | [eb63a6bb36](https://linux-hardware.org/?probe=eb63a6bb36) | Apr 17, 2021 |
| Acer          | Aspire E5-771G              | [e3bc507a07](https://linux-hardware.org/?probe=e3bc507a07) | Apr 17, 2021 |
| Notebook      | P7xxDM3(-G)                 | [7049a12bef](https://linux-hardware.org/?probe=7049a12bef) | Apr 17, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| Acer          | TravelMate 5720             | [4de4816949](https://linux-hardware.org/?probe=4de4816949) | Apr 14, 2021 |
| HP            | ProBook 650 G1              | [ce6e255493](https://linux-hardware.org/?probe=ce6e255493) | Apr 13, 2021 |
| HP            | Compaq 6830s                | [5b4a790a78](https://linux-hardware.org/?probe=5b4a790a78) | Apr 13, 2021 |
| HP            | Compaq 6830s                | [ff3b0f8b69](https://linux-hardware.org/?probe=ff3b0f8b69) | Apr 10, 2021 |
| TrekStor      | Notebook Slim S130          | [15a723bc0a](https://linux-hardware.org/?probe=15a723bc0a) | Apr 10, 2021 |
| Standard      | Unknown                     | [2e2b5648ce](https://linux-hardware.org/?probe=2e2b5648ce) | Apr 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ff08d60192](https://linux-hardware.org/?probe=ff08d60192) | Apr 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0DP0... | [8bca9f26df](https://linux-hardware.org/?probe=8bca9f26df) | Apr 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0DP0... | [f04bf70e2c](https://linux-hardware.org/?probe=f04bf70e2c) | Apr 09, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [59d83c563e](https://linux-hardware.org/?probe=59d83c563e) | Apr 09, 2021 |
| Dell          | Latitude E7440              | [9d9a93a1e7](https://linux-hardware.org/?probe=9d9a93a1e7) | Apr 08, 2021 |
| Dell          | Latitude E6330              | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Dell          | Latitude E7440              | [882711c39c](https://linux-hardware.org/?probe=882711c39c) | Apr 06, 2021 |
| Dell          | Latitude E7440              | [5cc52e4eb3](https://linux-hardware.org/?probe=5cc52e4eb3) | Apr 06, 2021 |
| Acer          | Aspire 7250                 | [e362ae4b3e](https://linux-hardware.org/?probe=e362ae4b3e) | Apr 05, 2021 |
| Acer          | Aspire 7250                 | [fe6bc9b5b9](https://linux-hardware.org/?probe=fe6bc9b5b9) | Apr 05, 2021 |
| ASUSTek       | PU551LA                     | [6a492952ec](https://linux-hardware.org/?probe=6a492952ec) | Apr 04, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [6e7b77b0ee](https://linux-hardware.org/?probe=6e7b77b0ee) | Mar 31, 2021 |
| Dell          | XPS 17 9700                 | [339118d4e1](https://linux-hardware.org/?probe=339118d4e1) | Mar 31, 2021 |
| Dell          | XPS 17 9700                 | [65c6679e82](https://linux-hardware.org/?probe=65c6679e82) | Mar 31, 2021 |
| ASUSTek       | X540LA                      | [280ac2515b](https://linux-hardware.org/?probe=280ac2515b) | Mar 29, 2021 |
| ASUSTek       | X540LA                      | [d454811086](https://linux-hardware.org/?probe=d454811086) | Mar 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [4d05114173](https://linux-hardware.org/?probe=4d05114173) | Mar 28, 2021 |
| ASUSTek       | K52F                        | [ca51314e8c](https://linux-hardware.org/?probe=ca51314e8c) | Mar 28, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [39d2fcc25c](https://linux-hardware.org/?probe=39d2fcc25c) | Mar 28, 2021 |
| Sony          | VGN-CR19VN_B                | [fb82fced50](https://linux-hardware.org/?probe=fb82fced50) | Mar 27, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [0b66d1d8d9](https://linux-hardware.org/?probe=0b66d1d8d9) | Mar 25, 2021 |
| HP            | Pavilion dv9000 (RP921EA... | [f39a330574](https://linux-hardware.org/?probe=f39a330574) | Mar 23, 2021 |
| HP            | Pavilion dv9000 (RP921EA... | [d04fc0aa98](https://linux-hardware.org/?probe=d04fc0aa98) | Mar 23, 2021 |
| Dell          | Latitude 7410               | [0805fdaa75](https://linux-hardware.org/?probe=0805fdaa75) | Mar 22, 2021 |
| Toshiba       | Satellite Pro A120          | [8a4710b123](https://linux-hardware.org/?probe=8a4710b123) | Mar 21, 2021 |
| Packard Be... | EasyNote_BG35-V-003BE       | [a3828dac52](https://linux-hardware.org/?probe=a3828dac52) | Mar 20, 2021 |
| Acer          | Aspire V3-771               | [6b0de26926](https://linux-hardware.org/?probe=6b0de26926) | Mar 19, 2021 |
| Acer          | Aspire 5755G                | [0984c7aebc](https://linux-hardware.org/?probe=0984c7aebc) | Mar 18, 2021 |
| Intel         | Tiger Lake Client Platfo... | [da214bbadb](https://linux-hardware.org/?probe=da214bbadb) | Mar 18, 2021 |
| HP            | EliteBook 850 G2            | [29665bb834](https://linux-hardware.org/?probe=29665bb834) | Mar 18, 2021 |
| HP            | EliteBook 850 G2            | [95d306f933](https://linux-hardware.org/?probe=95d306f933) | Mar 18, 2021 |
| Lenovo        | ThinkPad T495 20NKS0VY00    | [a30ff468ab](https://linux-hardware.org/?probe=a30ff468ab) | Mar 17, 2021 |
| Lenovo        | ThinkPad T495 20NKS0VY00    | [f8f4ebd88a](https://linux-hardware.org/?probe=f8f4ebd88a) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349GZG       | [592556c996](https://linux-hardware.org/?probe=592556c996) | Mar 17, 2021 |
| Lenovo        | ThinkPad T590 20N4004UMB    | [7746d65773](https://linux-hardware.org/?probe=7746d65773) | Mar 15, 2021 |
| HP            | ProBook 470 G5              | [ea759927d7](https://linux-hardware.org/?probe=ea759927d7) | Mar 13, 2021 |
| Medion        | S6421 MD60909               | [f43e4c999a](https://linux-hardware.org/?probe=f43e4c999a) | Mar 13, 2021 |
| Medion        | S6421 MD60909               | [7b1a21032f](https://linux-hardware.org/?probe=7b1a21032f) | Mar 12, 2021 |
| Dell          | XPS 13 7390                 | [49fa91c316](https://linux-hardware.org/?probe=49fa91c316) | Mar 10, 2021 |
| Dell          | XPS 13 7390                 | [7734e8dfb6](https://linux-hardware.org/?probe=7734e8dfb6) | Mar 10, 2021 |
| HP            | ProBook 6460b               | [d2997a258f](https://linux-hardware.org/?probe=d2997a258f) | Mar 09, 2021 |
| HP            | ProBook 6460b               | [9426162f4a](https://linux-hardware.org/?probe=9426162f4a) | Mar 09, 2021 |
| Acer          | Aspire 5755G                | [6fc4ecf2e5](https://linux-hardware.org/?probe=6fc4ecf2e5) | Mar 09, 2021 |
| Acer          | Aspire 5755G                | [861fb95171](https://linux-hardware.org/?probe=861fb95171) | Mar 09, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Sony          | VPCF23P1E                   | [5a1b84993b](https://linux-hardware.org/?probe=5a1b84993b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T420s 4174CN5      | [d781333e25](https://linux-hardware.org/?probe=d781333e25) | Mar 03, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [17164e2111](https://linux-hardware.org/?probe=17164e2111) | Mar 03, 2021 |
| Dell          | Precision M3800             | [946b253122](https://linux-hardware.org/?probe=946b253122) | Mar 03, 2021 |
| Dell          | Latitude E7470              | [7edde637cc](https://linux-hardware.org/?probe=7edde637cc) | Mar 02, 2021 |
| Dell          | Inspiron 5521               | [dbf7e551cd](https://linux-hardware.org/?probe=dbf7e551cd) | Mar 01, 2021 |
| Dell          | Inspiron 5521               | [7073ff4a30](https://linux-hardware.org/?probe=7073ff4a30) | Mar 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | [2e91ff573c](https://linux-hardware.org/?probe=2e91ff573c) | Mar 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | [c675742f98](https://linux-hardware.org/?probe=c675742f98) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK E554               | [422e106fbf](https://linux-hardware.org/?probe=422e106fbf) | Feb 28, 2021 |
| Clevo         | W35_37ET                    | [3082e61cbf](https://linux-hardware.org/?probe=3082e61cbf) | Feb 28, 2021 |
| Clevo         | W35_37ET                    | [cec3a7741f](https://linux-hardware.org/?probe=cec3a7741f) | Feb 28, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | [08f0761a98](https://linux-hardware.org/?probe=08f0761a98) | Feb 27, 2021 |
| Lenovo        | ThinkPad X230 23252P7       | [bc15b2e135](https://linux-hardware.org/?probe=bc15b2e135) | Feb 26, 2021 |
| HP            | ProBook 6570b               | [bf8cc9c3db](https://linux-hardware.org/?probe=bf8cc9c3db) | Feb 25, 2021 |
| HP            | HDX 16                      | [214dc69b28](https://linux-hardware.org/?probe=214dc69b28) | Feb 22, 2021 |
| HP            | Pavilion dv7                | [6761663105](https://linux-hardware.org/?probe=6761663105) | Feb 22, 2021 |
| HP            | ENVY Laptop 17-cg1xxx       | [280e648d24](https://linux-hardware.org/?probe=280e648d24) | Feb 21, 2021 |
| ASUSTek       | X541UA                      | [3539743457](https://linux-hardware.org/?probe=3539743457) | Feb 20, 2021 |
| ASUSTek       | X705NA                      | [0fd92654c8](https://linux-hardware.org/?probe=0fd92654c8) | Feb 19, 2021 |
| Sony          | VGN-FW21Z                   | [49af7bb079](https://linux-hardware.org/?probe=49af7bb079) | Feb 17, 2021 |
| Dell          | XPS 13 9343                 | [cdd5eb3377](https://linux-hardware.org/?probe=cdd5eb3377) | Feb 15, 2021 |
| Acer          | Aspire 5738                 | [a20559dfa9](https://linux-hardware.org/?probe=a20559dfa9) | Feb 15, 2021 |
| BLAUPUNKT     | Discovery 1011WI            | [d472298741](https://linux-hardware.org/?probe=d472298741) | Feb 14, 2021 |
| Dell          | XPS 13 9343                 | [b40b5302a0](https://linux-hardware.org/?probe=b40b5302a0) | Feb 14, 2021 |
| ASUSTek       | X541UA                      | [74216aff6a](https://linux-hardware.org/?probe=74216aff6a) | Feb 14, 2021 |
| Dell          | Inspiron 1750               | [142735e487](https://linux-hardware.org/?probe=142735e487) | Feb 14, 2021 |
| HP            | Compaq 6730b (GB987ET#UU... | [2ef76d4042](https://linux-hardware.org/?probe=2ef76d4042) | Feb 13, 2021 |
| ASUSTek       | X540SA                      | [1cd727b4e5](https://linux-hardware.org/?probe=1cd727b4e5) | Feb 13, 2021 |
| Medion        | P7612                       | [25bdf5c5e1](https://linux-hardware.org/?probe=25bdf5c5e1) | Feb 12, 2021 |
| Medion        | P7612                       | [dd2eae8c08](https://linux-hardware.org/?probe=dd2eae8c08) | Feb 12, 2021 |
| Dell          | Latitude E6500              | [200b4ad049](https://linux-hardware.org/?probe=200b4ad049) | Feb 11, 2021 |
| HP            | ProBook 470 G5              | [980c47c7e1](https://linux-hardware.org/?probe=980c47c7e1) | Feb 08, 2021 |
| Intel         | Skylake Platform            | [c3772356cc](https://linux-hardware.org/?probe=c3772356cc) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | [8da49e5276](https://linux-hardware.org/?probe=8da49e5276) | Feb 07, 2021 |
| ASUSTek       | X541UA                      | [195a92067a](https://linux-hardware.org/?probe=195a92067a) | Feb 07, 2021 |
| Toshiba       | Satellite S50-B             | [0603c22e84](https://linux-hardware.org/?probe=0603c22e84) | Feb 07, 2021 |
| Dell          | G3 3779                     | [363e754d51](https://linux-hardware.org/?probe=363e754d51) | Feb 06, 2021 |
| ASUSTek       | 1005HA                      | [3271c9fcf1](https://linux-hardware.org/?probe=3271c9fcf1) | Feb 04, 2021 |
| BLAUPUNKT     | Discovery 1011WI            | [11caa65562](https://linux-hardware.org/?probe=11caa65562) | Jan 31, 2021 |
| Dell          | XPS 17 9700                 | [ddff47f92b](https://linux-hardware.org/?probe=ddff47f92b) | Jan 31, 2021 |
| HP            | EliteBook 840 G1            | [18d0877f0f](https://linux-hardware.org/?probe=18d0877f0f) | Jan 31, 2021 |
| Dell          | Studio 1737                 | [3550b981dd](https://linux-hardware.org/?probe=3550b981dd) | Jan 31, 2021 |
| Dell          | Inspiron 5370               | [c4fc1198ca](https://linux-hardware.org/?probe=c4fc1198ca) | Jan 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0ea19084de](https://linux-hardware.org/?probe=0ea19084de) | Jan 29, 2021 |
| Toshiba       | Satellite L670              | [cf01b0dc10](https://linux-hardware.org/?probe=cf01b0dc10) | Jan 29, 2021 |
| Notebook      | NV4XMZ                      | [85227cca30](https://linux-hardware.org/?probe=85227cca30) | Jan 28, 2021 |
| Acer          | Aspire E5-571               | [2855a371c3](https://linux-hardware.org/?probe=2855a371c3) | Jan 24, 2021 |
| BLAUPUNKT     | Discovery 1011WI            | [ca7bef1a68](https://linux-hardware.org/?probe=ca7bef1a68) | Jan 24, 2021 |
| Lenovo        | Yoga 300-11IBY 80M0         | [73ac79ea35](https://linux-hardware.org/?probe=73ac79ea35) | Jan 24, 2021 |
| HP            | ZBook Studio G4             | [83f8b119c5](https://linux-hardware.org/?probe=83f8b119c5) | Jan 23, 2021 |
| Dell          | Inspiron 7520               | [145f521d9a](https://linux-hardware.org/?probe=145f521d9a) | Jan 22, 2021 |
| Medion        | E7222                       | [c5b59cdd1a](https://linux-hardware.org/?probe=c5b59cdd1a) | Jan 21, 2021 |
| HP            | ZBook Studio G4             | [b4828f90e1](https://linux-hardware.org/?probe=b4828f90e1) | Jan 21, 2021 |
| Apple         | MacBookAir7,2               | [da811652ff](https://linux-hardware.org/?probe=da811652ff) | Jan 20, 2021 |
| ASUSTek       | X200CA                      | [90675c7c5d](https://linux-hardware.org/?probe=90675c7c5d) | Jan 16, 2021 |
| Dell          | XPS 13 9370                 | [ddd11f8f67](https://linux-hardware.org/?probe=ddd11f8f67) | Jan 15, 2021 |
| Dell          | XPS 13 9370                 | [3b42708115](https://linux-hardware.org/?probe=3b42708115) | Jan 15, 2021 |
| ASUSTek       | X55A                        | [bbac234938](https://linux-hardware.org/?probe=bbac234938) | Jan 14, 2021 |
| Samsung       | SQ1US                       | [c5b1d00d5a](https://linux-hardware.org/?probe=c5b1d00d5a) | Jan 14, 2021 |
| Samsung       | SQ1US                       | [b7c374caa7](https://linux-hardware.org/?probe=b7c374caa7) | Jan 14, 2021 |
| Samsung       | SQ1US                       | [38c340b504](https://linux-hardware.org/?probe=38c340b504) | Jan 13, 2021 |
| Dell          | Studio 1747                 | [1fe32f1f6c](https://linux-hardware.org/?probe=1fe32f1f6c) | Jan 12, 2021 |
| ASUSTek       | S400CA                      | [598845d6da](https://linux-hardware.org/?probe=598845d6da) | Jan 12, 2021 |
| ASUSTek       | S400CA                      | [ad5e96299b](https://linux-hardware.org/?probe=ad5e96299b) | Jan 12, 2021 |
| HP            | ProBook 450 G6              | [8cb1a97eeb](https://linux-hardware.org/?probe=8cb1a97eeb) | Jan 12, 2021 |
| Lenovo        | B590 62743BG                | [74e74ba835](https://linux-hardware.org/?probe=74e74ba835) | Jan 12, 2021 |
| Dell          | Latitude E7440              | [b941db31df](https://linux-hardware.org/?probe=b941db31df) | Jan 11, 2021 |
| Dell          | Latitude E7440              | [945b6f9fd9](https://linux-hardware.org/?probe=945b6f9fd9) | Jan 10, 2021 |
| ASUSTek       | X555LJ                      | [1b20a57823](https://linux-hardware.org/?probe=1b20a57823) | Jan 10, 2021 |
| ASUSTek       | X540SA                      | [f0e4a2ef6d](https://linux-hardware.org/?probe=f0e4a2ef6d) | Jan 07, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [ae395b2f7a](https://linux-hardware.org/?probe=ae395b2f7a) | Jan 06, 2021 |
| HP            | ProBook 6570b               | [cdd52e19bc](https://linux-hardware.org/?probe=cdd52e19bc) | Jan 03, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [4460990877](https://linux-hardware.org/?probe=4460990877) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [3f3cc6b9d6](https://linux-hardware.org/?probe=3f3cc6b9d6) | Jan 02, 2021 |
| TUXEDO        | Unknown                     | [ab17e3576a](https://linux-hardware.org/?probe=ab17e3576a) | Jan 01, 2021 |
| Dell          | Inspiron 7537               | [0d0f758de9](https://linux-hardware.org/?probe=0d0f758de9) | Jan 01, 2021 |
| Dell          | XPS 13 7390                 | [e3c50af4ef](https://linux-hardware.org/?probe=e3c50af4ef) | Dec 31, 2020 |
| Medion        | S17402 MD63000              | [fba33aab51](https://linux-hardware.org/?probe=fba33aab51) | Dec 31, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2599b8b3f](https://linux-hardware.org/?probe=e2599b8b3f) | Dec 30, 2020 |
| Acer          | Aspire 7250                 | [9495fc4339](https://linux-hardware.org/?probe=9495fc4339) | Dec 30, 2020 |
| HP            | Laptop 15-db0xxx            | [2733859e34](https://linux-hardware.org/?probe=2733859e34) | Dec 29, 2020 |
| ASUSTek       | N76VB                       | [4e74a9d0c6](https://linux-hardware.org/?probe=4e74a9d0c6) | Dec 27, 2020 |
| ASUSTek       | X55A                        | [79e9816c30](https://linux-hardware.org/?probe=79e9816c30) | Dec 27, 2020 |
| Dell          | XPS 13 9380                 | [43cf1987c6](https://linux-hardware.org/?probe=43cf1987c6) | Dec 25, 2020 |
| Dell          | Latitude E7470              | [94ee07720c](https://linux-hardware.org/?probe=94ee07720c) | Dec 22, 2020 |
| HP            | Laptop 15-db0xxx            | [445ca5b97b](https://linux-hardware.org/?probe=445ca5b97b) | Dec 21, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [513655f2ce](https://linux-hardware.org/?probe=513655f2ce) | Dec 20, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [ee1787e510](https://linux-hardware.org/?probe=ee1787e510) | Dec 20, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [19d71cac1d](https://linux-hardware.org/?probe=19d71cac1d) | Dec 19, 2020 |
| HP            | ProBook 6570b               | [e3a804c090](https://linux-hardware.org/?probe=e3a804c090) | Dec 19, 2020 |
| HP            | ProBook 6570b               | [742afc21c9](https://linux-hardware.org/?probe=742afc21c9) | Dec 19, 2020 |
| Dell          | Precision 5540              | [eea500d1e4](https://linux-hardware.org/?probe=eea500d1e4) | Dec 18, 2020 |
| Dell          | Precision 5540              | [0e06bc0dae](https://linux-hardware.org/?probe=0e06bc0dae) | Dec 18, 2020 |
| Acer          | Aspire V3-771               | [6ec9609964](https://linux-hardware.org/?probe=6ec9609964) | Dec 18, 2020 |
| ASUSTek       | K53SC                       | [a4329e176c](https://linux-hardware.org/?probe=a4329e176c) | Dec 16, 2020 |
| HP            | EliteBook 8760w             | [5e2ff51ade](https://linux-hardware.org/?probe=5e2ff51ade) | Dec 15, 2020 |
| Dell          | Inspiron 1545               | [5a179cb315](https://linux-hardware.org/?probe=5a179cb315) | Dec 14, 2020 |
| Lenovo        | ThinkPad T460s 20FAS3KA0... | [df948532a2](https://linux-hardware.org/?probe=df948532a2) | Dec 14, 2020 |
| Acer          | Aspire 8943G                | [18d1fc7788](https://linux-hardware.org/?probe=18d1fc7788) | Dec 14, 2020 |
| HP            | Pavilion 17                 | [185a04ef97](https://linux-hardware.org/?probe=185a04ef97) | Dec 14, 2020 |
| ASUSTek       | X541UA                      | [53889fafd6](https://linux-hardware.org/?probe=53889fafd6) | Dec 13, 2020 |
| Dell          | Inspiron 5521               | [e98a579bc9](https://linux-hardware.org/?probe=e98a579bc9) | Dec 13, 2020 |
| Dell          | Latitude E6500              | [c12a3f1830](https://linux-hardware.org/?probe=c12a3f1830) | Dec 11, 2020 |
| Toshiba       | Portable PC                 | [9aec36b4b9](https://linux-hardware.org/?probe=9aec36b4b9) | Dec 11, 2020 |
| ASUSTek       | X541UA                      | [af5be056fb](https://linux-hardware.org/?probe=af5be056fb) | Dec 10, 2020 |
| Dell          | Inspiron 1545               | [1bd7a01295](https://linux-hardware.org/?probe=1bd7a01295) | Dec 09, 2020 |
| Dell          | Inspiron M301Z              | [cc51993e35](https://linux-hardware.org/?probe=cc51993e35) | Dec 09, 2020 |
| Dell          | Inspiron M301Z              | [11dc6b28f5](https://linux-hardware.org/?probe=11dc6b28f5) | Dec 09, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [8bc1a4d8b0](https://linux-hardware.org/?probe=8bc1a4d8b0) | Dec 09, 2020 |
| Dell          | Latitude E5520              | [ecfe12fa90](https://linux-hardware.org/?probe=ecfe12fa90) | Dec 08, 2020 |
| Dell          | Latitude E5470              | [cae4e793ab](https://linux-hardware.org/?probe=cae4e793ab) | Dec 08, 2020 |
| Dell          | Latitude E5520              | [83a7619e37](https://linux-hardware.org/?probe=83a7619e37) | Dec 07, 2020 |
| Dell          | Latitude E5520              | [9bd9761673](https://linux-hardware.org/?probe=9bd9761673) | Dec 07, 2020 |
| Acer          | Aspire 8943G                | [bb741f9db7](https://linux-hardware.org/?probe=bb741f9db7) | Dec 07, 2020 |
| HP            | EliteBook 850 G6            | [3f1f665734](https://linux-hardware.org/?probe=3f1f665734) | Dec 07, 2020 |
| Dell          | Latitude E6410              | [49f871123b](https://linux-hardware.org/?probe=49f871123b) | Dec 04, 2020 |
| ASUSTek       | UX51VZA                     | [934a52bce4](https://linux-hardware.org/?probe=934a52bce4) | Dec 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [52cf6d4786](https://linux-hardware.org/?probe=52cf6d4786) | Dec 02, 2020 |
| HP            | EliteBook 8570w             | [33131b9a5d](https://linux-hardware.org/?probe=33131b9a5d) | Dec 01, 2020 |
| Lenovo        | ThinkPad Helix 37027L8      | [5448534db9](https://linux-hardware.org/?probe=5448534db9) | Nov 29, 2020 |
| HP            | ZBook 15                    | [033521235f](https://linux-hardware.org/?probe=033521235f) | Nov 29, 2020 |
| HP            | Laptop 15-db0xxx            | [8a7c93e51a](https://linux-hardware.org/?probe=8a7c93e51a) | Nov 29, 2020 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [eecab17720](https://linux-hardware.org/?probe=eecab17720) | Nov 28, 2020 |
| Dell          | Latitude D630               | [234e02e8d5](https://linux-hardware.org/?probe=234e02e8d5) | Nov 27, 2020 |
| Dell          | Latitude D630               | [d9dcc0eb85](https://linux-hardware.org/?probe=d9dcc0eb85) | Nov 27, 2020 |
| Dell          | Latitude D630               | [92df09ba60](https://linux-hardware.org/?probe=92df09ba60) | Nov 26, 2020 |
| Dell          | Precision 5540              | [73beeb1ed9](https://linux-hardware.org/?probe=73beeb1ed9) | Nov 26, 2020 |
| Dell          | Precision 7540              | [cfabe88a55](https://linux-hardware.org/?probe=cfabe88a55) | Nov 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [bbdcb30776](https://linux-hardware.org/?probe=bbdcb30776) | Nov 24, 2020 |
| Acer          | Aspire 9300                 | [af7a2a10e6](https://linux-hardware.org/?probe=af7a2a10e6) | Nov 24, 2020 |
| HP            | ProBook 450 G3              | [715082dd77](https://linux-hardware.org/?probe=715082dd77) | Nov 22, 2020 |
| Packard Be... | EasyNote LE69KB             | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| Acer          | Aspire 9300                 | [cec568e69b](https://linux-hardware.org/?probe=cec568e69b) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [5d7d75bea0](https://linux-hardware.org/?probe=5d7d75bea0) | Nov 22, 2020 |
| Lenovo        | QIWG5                       | [e93059c86b](https://linux-hardware.org/?probe=e93059c86b) | Nov 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [a8aff7471b](https://linux-hardware.org/?probe=a8aff7471b) | Nov 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [8a88ea0405](https://linux-hardware.org/?probe=8a88ea0405) | Nov 16, 2020 |
| Dell          | Vostro 5490                 | [cd71584b67](https://linux-hardware.org/?probe=cd71584b67) | Nov 15, 2020 |
| Dell          | Latitude E6540              | [b13f43fd96](https://linux-hardware.org/?probe=b13f43fd96) | Nov 15, 2020 |
| Acer          | Aspire V3-771               | [706101337f](https://linux-hardware.org/?probe=706101337f) | Nov 15, 2020 |
| Timi          | TM1701                      | [ee53272b88](https://linux-hardware.org/?probe=ee53272b88) | Nov 14, 2020 |
| Dell          | Latitude E5540              | [f384c4cd47](https://linux-hardware.org/?probe=f384c4cd47) | Nov 14, 2020 |
| Dell          | Latitude E6400              | [498838be95](https://linux-hardware.org/?probe=498838be95) | Nov 13, 2020 |
| Toshiba       | Satellite S50-B             | [fb2a4b7225](https://linux-hardware.org/?probe=fb2a4b7225) | Nov 12, 2020 |
| HP            | Laptop 15-db0xxx            | [4d690cba73](https://linux-hardware.org/?probe=4d690cba73) | Nov 12, 2020 |
| Acer          | Aspire 7535                 | [76b533eabb](https://linux-hardware.org/?probe=76b533eabb) | Nov 12, 2020 |
| Acer          | Aspire 7535                 | [a3c3508073](https://linux-hardware.org/?probe=a3c3508073) | Nov 12, 2020 |
| Dell          | Latitude E5550              | [8122627b60](https://linux-hardware.org/?probe=8122627b60) | Nov 11, 2020 |
| ASUSTek       | N76VB                       | [be1a7a1846](https://linux-hardware.org/?probe=be1a7a1846) | Nov 11, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [df8f072c02](https://linux-hardware.org/?probe=df8f072c02) | Nov 10, 2020 |
| Lenovo        | G50-45 80MQ                 | [ae8765f215](https://linux-hardware.org/?probe=ae8765f215) | Nov 09, 2020 |
| ASUSTek       | K75VJ                       | [8c1aa2617a](https://linux-hardware.org/?probe=8c1aa2617a) | Nov 08, 2020 |
| HP            | ZBook 15u G6                | [5d55fe47d6](https://linux-hardware.org/?probe=5d55fe47d6) | Nov 07, 2020 |
| HP            | Pavilion dv7                | [8474983767](https://linux-hardware.org/?probe=8474983767) | Nov 02, 2020 |
| Dell          | Studio 1737                 | [a765cb1de5](https://linux-hardware.org/?probe=a765cb1de5) | Oct 31, 2020 |
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Precision 7510              | [2c75252866](https://linux-hardware.org/?probe=2c75252866) | Oct 28, 2020 |
| HP            | ProBook 450 G6              | [21bb2a58e7](https://linux-hardware.org/?probe=21bb2a58e7) | Oct 27, 2020 |
| Acer          | TravelMate 7750             | [72545e74b1](https://linux-hardware.org/?probe=72545e74b1) | Oct 27, 2020 |
| HP            | ProBook 650 G1              | [9ef7c0be85](https://linux-hardware.org/?probe=9ef7c0be85) | Oct 27, 2020 |
| HP            | ProBook 650 G1              | [613709ec5e](https://linux-hardware.org/?probe=613709ec5e) | Oct 26, 2020 |
| Dell          | XPS 13 9360                 | [54820a0946](https://linux-hardware.org/?probe=54820a0946) | Oct 26, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [544d12c1eb](https://linux-hardware.org/?probe=544d12c1eb) | Oct 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [40f76ec59d](https://linux-hardware.org/?probe=40f76ec59d) | Oct 25, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [084f4a0b16](https://linux-hardware.org/?probe=084f4a0b16) | Oct 25, 2020 |
| Dell          | XPS 13 9360                 | [d2a0360112](https://linux-hardware.org/?probe=d2a0360112) | Oct 22, 2020 |
| HP            | EliteBook 850 G1            | [ed517d476f](https://linux-hardware.org/?probe=ed517d476f) | Oct 20, 2020 |
| Dell          | Vostro 3350                 | [0790b14978](https://linux-hardware.org/?probe=0790b14978) | Oct 19, 2020 |
| Dell          | Vostro 3350                 | [632b09074e](https://linux-hardware.org/?probe=632b09074e) | Oct 19, 2020 |
| Toshiba       | Satellite C75-A             | [d83aee9a81](https://linux-hardware.org/?probe=d83aee9a81) | Oct 17, 2020 |
| Dell          | Latitude E7240              | [8f2a7e25e4](https://linux-hardware.org/?probe=8f2a7e25e4) | Oct 17, 2020 |
| Dell          | XPS 17 9700                 | [af5e192001](https://linux-hardware.org/?probe=af5e192001) | Oct 17, 2020 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [9966ca014f](https://linux-hardware.org/?probe=9966ca014f) | Oct 15, 2020 |
| Dell          | XPS 17 9700                 | [84d3d733e4](https://linux-hardware.org/?probe=84d3d733e4) | Oct 15, 2020 |
| HP            | EliteBook 8570w             | [6540f439d1](https://linux-hardware.org/?probe=6540f439d1) | Oct 15, 2020 |
| ASUSTek       | X751LJ                      | [8433490279](https://linux-hardware.org/?probe=8433490279) | Oct 13, 2020 |
| Dell          | Latitude E7240              | [62e2ef48ea](https://linux-hardware.org/?probe=62e2ef48ea) | Oct 13, 2020 |
| Dell          | Latitude E7440              | [ba3dae8fd9](https://linux-hardware.org/?probe=ba3dae8fd9) | Oct 12, 2020 |
| HP            | Pavilion dv6                | [63a5f64dd1](https://linux-hardware.org/?probe=63a5f64dd1) | Oct 11, 2020 |
| HP            | Compaq 6830s                | [16f4fc481e](https://linux-hardware.org/?probe=16f4fc481e) | Oct 11, 2020 |
| HP            | Pavilion Notebook           | [5c94f87831](https://linux-hardware.org/?probe=5c94f87831) | Oct 11, 2020 |
| HP            | EliteBook 820 G3            | [1875cb7756](https://linux-hardware.org/?probe=1875cb7756) | Oct 10, 2020 |
| HP            | ProBook 450 G4              | [d236268c6c](https://linux-hardware.org/?probe=d236268c6c) | Oct 10, 2020 |
| MSI           | Prestige 15 A10SC           | [3cc3cb1662](https://linux-hardware.org/?probe=3cc3cb1662) | Oct 10, 2020 |
| Medion        | Akoya THE TOUCH 10          | [1500397c93](https://linux-hardware.org/?probe=1500397c93) | Oct 10, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [3ac2f3c575](https://linux-hardware.org/?probe=3ac2f3c575) | Oct 09, 2020 |
| Medion        | P7624                       | [a4216be7a9](https://linux-hardware.org/?probe=a4216be7a9) | Oct 05, 2020 |
| Apple         | MacBookPro5,5               | [6f1a49515c](https://linux-hardware.org/?probe=6f1a49515c) | Oct 05, 2020 |
| Sony          | VGN-AW11M_H                 | [93eb90689f](https://linux-hardware.org/?probe=93eb90689f) | Oct 02, 2020 |
| ASUSTek       | X555LJ                      | [bd5306ec57](https://linux-hardware.org/?probe=bd5306ec57) | Oct 01, 2020 |
| Toshiba       | Satellite A40               | [6fdde857d2](https://linux-hardware.org/?probe=6fdde857d2) | Sep 28, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [58010df926](https://linux-hardware.org/?probe=58010df926) | Sep 27, 2020 |
| Dell          | Latitude E6520              | [96c3013976](https://linux-hardware.org/?probe=96c3013976) | Sep 27, 2020 |
| HP            | EliteBook 755 G5            | [48467304f0](https://linux-hardware.org/?probe=48467304f0) | Sep 26, 2020 |
| HP            | EliteBook 755 G5            | [cee814d244](https://linux-hardware.org/?probe=cee814d244) | Sep 26, 2020 |
| HP            | Pavilion Notebook           | [8e825ecbad](https://linux-hardware.org/?probe=8e825ecbad) | Sep 26, 2020 |
| HP            | EliteBook 850 G5            | [5aecf186c6](https://linux-hardware.org/?probe=5aecf186c6) | Sep 24, 2020 |
| Dell          | Inspiron 15-3552            | [5b7d09d221](https://linux-hardware.org/?probe=5b7d09d221) | Sep 21, 2020 |
| Lenovo        | ThinkPad T590 20N4004UMB    | [be3d2c8855](https://linux-hardware.org/?probe=be3d2c8855) | Sep 19, 2020 |
| Packard Be... | DOTS E2                     | [b2e136331d](https://linux-hardware.org/?probe=b2e136331d) | Sep 18, 2020 |
| Dell          | Latitude E6330              | [aed48c4596](https://linux-hardware.org/?probe=aed48c4596) | Sep 14, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [86096bb0d6](https://linux-hardware.org/?probe=86096bb0d6) | Sep 13, 2020 |
| Dell          | Latitude E6430              | [eb0a5e7d6b](https://linux-hardware.org/?probe=eb0a5e7d6b) | Sep 11, 2020 |
| MSI           | GE62MVR 7RG                 | [4ddb4dff7e](https://linux-hardware.org/?probe=4ddb4dff7e) | Sep 11, 2020 |
| Dell          | Latitude E6330              | [97b26267a6](https://linux-hardware.org/?probe=97b26267a6) | Sep 08, 2020 |
| HP            | Pavilion dv7                | [d0377566c3](https://linux-hardware.org/?probe=d0377566c3) | Sep 07, 2020 |
| MSI           | GP72 7RE                    | [190a9f1c60](https://linux-hardware.org/?probe=190a9f1c60) | Sep 05, 2020 |
| MSI           | GP72 7RE                    | [8d4d32a585](https://linux-hardware.org/?probe=8d4d32a585) | Sep 05, 2020 |
| MSI           | GP72 7RE                    | [b73297025a](https://linux-hardware.org/?probe=b73297025a) | Sep 05, 2020 |
| Acer          | Aspire 7250                 | [258fe8f47d](https://linux-hardware.org/?probe=258fe8f47d) | Sep 04, 2020 |
| Acer          | Aspire 7250                 | [efedcda2c8](https://linux-hardware.org/?probe=efedcda2c8) | Sep 04, 2020 |
| HP            | EliteBook 830 G6            | [fcfe0671f0](https://linux-hardware.org/?probe=fcfe0671f0) | Sep 04, 2020 |
| Lenovo        | Flex 2-15 20405             | [56c2d6c665](https://linux-hardware.org/?probe=56c2d6c665) | Sep 03, 2020 |
| HP            | EliteBook 850 G3            | [245f257f3f](https://linux-hardware.org/?probe=245f257f3f) | Sep 03, 2020 |
| Sony          | VGN-N21Z_W                  | [a82d56a4ed](https://linux-hardware.org/?probe=a82d56a4ed) | Sep 02, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [294fd98c3f](https://linux-hardware.org/?probe=294fd98c3f) | Sep 01, 2020 |
| HP            | ProBook 450 G1              | [b47678608e](https://linux-hardware.org/?probe=b47678608e) | Aug 30, 2020 |
| HP            | Compaq CQ58                 | [dbf5de4ccf](https://linux-hardware.org/?probe=dbf5de4ccf) | Aug 27, 2020 |
| HP            | Compaq CQ58                 | [4a55ea728a](https://linux-hardware.org/?probe=4a55ea728a) | Aug 26, 2020 |
| MSI           | GE62MVR 7RG                 | [8d15785d76](https://linux-hardware.org/?probe=8d15785d76) | Aug 26, 2020 |
| Notebook      | NJ50GU                      | [768588c7e0](https://linux-hardware.org/?probe=768588c7e0) | Aug 25, 2020 |
| Dell          | Latitude E5540              | [fd210b725d](https://linux-hardware.org/?probe=fd210b725d) | Aug 25, 2020 |
| Dell          | Inspiron 5721               | [5777fb441f](https://linux-hardware.org/?probe=5777fb441f) | Aug 25, 2020 |
| Gigabyte      | Spring Peak                 | [de142665e9](https://linux-hardware.org/?probe=de142665e9) | Aug 24, 2020 |
| HP            | EliteBook 8470p             | [46549f6aaf](https://linux-hardware.org/?probe=46549f6aaf) | Aug 24, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [cc1ddd0d81](https://linux-hardware.org/?probe=cc1ddd0d81) | Aug 23, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [c82c12e968](https://linux-hardware.org/?probe=c82c12e968) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [585b5cd200](https://linux-hardware.org/?probe=585b5cd200) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [b16e78abbf](https://linux-hardware.org/?probe=b16e78abbf) | Aug 21, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [fd339f3d69](https://linux-hardware.org/?probe=fd339f3d69) | Aug 17, 2020 |
| Dell          | XPS 15 9560                 | [d341994b7e](https://linux-hardware.org/?probe=d341994b7e) | Aug 14, 2020 |
| Dell          | Inspiron 7590               | [c600b0a8b4](https://linux-hardware.org/?probe=c600b0a8b4) | Aug 14, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c42db748da](https://linux-hardware.org/?probe=c42db748da) | Aug 14, 2020 |
| Apple         | MacBookPro9,2               | [75dcbf73ad](https://linux-hardware.org/?probe=75dcbf73ad) | Aug 13, 2020 |
| Lenovo        | ThinkPad X240 20AL007NMS    | [6b21cd8c3e](https://linux-hardware.org/?probe=6b21cd8c3e) | Aug 13, 2020 |
| Notebook      | N8xEJEK                     | [c3656a1913](https://linux-hardware.org/?probe=c3656a1913) | Aug 12, 2020 |
| HP            | Laptop 15s-eq0xxx           | [db484283e2](https://linux-hardware.org/?probe=db484283e2) | Aug 12, 2020 |
| Dell          | Latitude E7450              | [ae8d11da33](https://linux-hardware.org/?probe=ae8d11da33) | Aug 10, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [47781e0ca5](https://linux-hardware.org/?probe=47781e0ca5) | Aug 09, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [addd2d4dfb](https://linux-hardware.org/?probe=addd2d4dfb) | Aug 06, 2020 |
| HP            | ProBook 6570b               | [4d2bdc0407](https://linux-hardware.org/?probe=4d2bdc0407) | Aug 05, 2020 |
| HP            | ProBook 650 G1              | [1e65ebcb5c](https://linux-hardware.org/?probe=1e65ebcb5c) | Jul 30, 2020 |
| Dell          | Latitude E5540              | [5f85755562](https://linux-hardware.org/?probe=5f85755562) | Jul 28, 2020 |
| Dell          | Precision M3800             | [a8e05164be](https://linux-hardware.org/?probe=a8e05164be) | Jul 28, 2020 |
| HP            | EliteBook 2570p             | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [180d7fadbc](https://linux-hardware.org/?probe=180d7fadbc) | Jul 22, 2020 |
| ASUSTek       | 1015BXO                     | [6521645132](https://linux-hardware.org/?probe=6521645132) | Jul 21, 2020 |
| Lenovo        | B40-30 80F1                 | [352853e47a](https://linux-hardware.org/?probe=352853e47a) | Jul 20, 2020 |
| Lenovo        | B40-30 80F1                 | [9c25f7238d](https://linux-hardware.org/?probe=9c25f7238d) | Jul 19, 2020 |
| Dell          | Vostro 7590                 | [7ceff73a7c](https://linux-hardware.org/?probe=7ceff73a7c) | Jul 19, 2020 |
| ASUSTek       | X411UQ                      | [e4775db53f](https://linux-hardware.org/?probe=e4775db53f) | Jul 18, 2020 |
| Dell          | Vostro 7590                 | [0c470cda31](https://linux-hardware.org/?probe=0c470cda31) | Jul 17, 2020 |
| Dell          | Latitude 7490               | [e9df935f20](https://linux-hardware.org/?probe=e9df935f20) | Jul 14, 2020 |
| Dell          | Latitude 7490               | [e03e8bf65c](https://linux-hardware.org/?probe=e03e8bf65c) | Jul 14, 2020 |
| Packard Be... | EasyNote LE69KB             | [5a142eb432](https://linux-hardware.org/?probe=5a142eb432) | Jul 13, 2020 |
| Medion        | P8610                       | [719c317781](https://linux-hardware.org/?probe=719c317781) | Jul 10, 2020 |
| Dell          | Latitude E5550              | [eaabe83772](https://linux-hardware.org/?probe=eaabe83772) | Jul 08, 2020 |
| Dell          | Latitude E5500              | [5a4a6865e9](https://linux-hardware.org/?probe=5a4a6865e9) | Jul 07, 2020 |
| Dell          | Latitude E5520              | [ab997ac1d8](https://linux-hardware.org/?probe=ab997ac1d8) | Jul 06, 2020 |
| Dell          | Precision M3800             | [ec812206c4](https://linux-hardware.org/?probe=ec812206c4) | Jul 06, 2020 |
| Packard Be... | EasyNote LS11HR             | [4ae33159e8](https://linux-hardware.org/?probe=4ae33159e8) | Jul 04, 2020 |
| HP            | ProBook 450 G3              | [f2bc91ef33](https://linux-hardware.org/?probe=f2bc91ef33) | Jul 02, 2020 |
| Dell          | Precision M4800             | [a3c734dcca](https://linux-hardware.org/?probe=a3c734dcca) | Jul 02, 2020 |
| Dell          | Studio 1747                 | [7ab545cc97](https://linux-hardware.org/?probe=7ab545cc97) | Jun 30, 2020 |
| Dell          | Studio 1747                 | [4bde09ae7f](https://linux-hardware.org/?probe=4bde09ae7f) | Jun 30, 2020 |
| Lenovo        | ThinkPad X201 3680DV9       | [ed63d644f6](https://linux-hardware.org/?probe=ed63d644f6) | Jun 29, 2020 |
| HP            | Compaq 6830s                | [b1b243923c](https://linux-hardware.org/?probe=b1b243923c) | Jun 28, 2020 |
| Acer          | Aspire E5-575G              | [0a6f85883d](https://linux-hardware.org/?probe=0a6f85883d) | Jun 27, 2020 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [ccf327b2f0](https://linux-hardware.org/?probe=ccf327b2f0) | Jun 27, 2020 |
| Toshiba       | Satellite P50t-B-10T        | [7a315ecbf7](https://linux-hardware.org/?probe=7a315ecbf7) | Jun 25, 2020 |
| Acer          | Aspire 5750                 | [797fb5dd97](https://linux-hardware.org/?probe=797fb5dd97) | Jun 24, 2020 |
| Acer          | Aspire 5750                 | [c7bd8a1a13](https://linux-hardware.org/?probe=c7bd8a1a13) | Jun 24, 2020 |
| MSI           | Prestige 15 A10SC           | [83a1b14be9](https://linux-hardware.org/?probe=83a1b14be9) | Jun 23, 2020 |
| MSI           | Prestige 15 A10SC           | [edeaeef9b8](https://linux-hardware.org/?probe=edeaeef9b8) | Jun 23, 2020 |
| Dell          | Latitude 5500               | [8131cc1c89](https://linux-hardware.org/?probe=8131cc1c89) | Jun 23, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [3d29f99f8d](https://linux-hardware.org/?probe=3d29f99f8d) | Jun 21, 2020 |
| ASUSTek       | UX31A                       | [812725b1bd](https://linux-hardware.org/?probe=812725b1bd) | Jun 19, 2020 |
| HP            | Pavilion dv7                | [ab0c4d56ee](https://linux-hardware.org/?probe=ab0c4d56ee) | Jun 18, 2020 |
| Packard Be... | EasyNote LS11HR             | [4efd6d9fd5](https://linux-hardware.org/?probe=4efd6d9fd5) | Jun 17, 2020 |
| HP            | EliteBook 840 G1            | [aa8f97ff6c](https://linux-hardware.org/?probe=aa8f97ff6c) | Jun 15, 2020 |
| Dell          | Latitude D620               | [c19f47f037](https://linux-hardware.org/?probe=c19f47f037) | Jun 15, 2020 |
| HP            | EliteBook 820 G2            | [69e0efb1bf](https://linux-hardware.org/?probe=69e0efb1bf) | Jun 14, 2020 |
| Dell          | Latitude E5530 vPro         | [afad73e75b](https://linux-hardware.org/?probe=afad73e75b) | Jun 14, 2020 |
| Dell          | Latitude E6500              | [3a38afa413](https://linux-hardware.org/?probe=3a38afa413) | Jun 14, 2020 |
| Dell          | Latitude E5550              | [8e73005cc8](https://linux-hardware.org/?probe=8e73005cc8) | Jun 14, 2020 |
| HP            | ProBook 450 G6              | [8faea52812](https://linux-hardware.org/?probe=8faea52812) | Jun 13, 2020 |
| PC Special... | P95_96_97Ex,Rx              | [25f6b1bd84](https://linux-hardware.org/?probe=25f6b1bd84) | Jun 12, 2020 |
| PC Special... | P95_96_97Ex,Rx              | [6a802e0a2a](https://linux-hardware.org/?probe=6a802e0a2a) | Jun 11, 2020 |
| HP            | ProBook 430 G1              | [4203bc537c](https://linux-hardware.org/?probe=4203bc537c) | Jun 11, 2020 |
| HP            | ProBook 6550b               | [e52a77158f](https://linux-hardware.org/?probe=e52a77158f) | Jun 09, 2020 |
| HP            | ProBook 6550b               | [b80da242d0](https://linux-hardware.org/?probe=b80da242d0) | Jun 09, 2020 |
| Sony          | VGN-N21Z_W                  | [f5c84d68f7](https://linux-hardware.org/?probe=f5c84d68f7) | Jun 06, 2020 |
| ASUSTek       | X555LJ                      | [8a0dab5948](https://linux-hardware.org/?probe=8a0dab5948) | Jun 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d082b8d834](https://linux-hardware.org/?probe=d082b8d834) | Jun 03, 2020 |
| ASUSTek       | X553MA                      | [4c806ac902](https://linux-hardware.org/?probe=4c806ac902) | Jun 03, 2020 |
| ASUSTek       | X553MA                      | [dce6989d3c](https://linux-hardware.org/?probe=dce6989d3c) | Jun 03, 2020 |
| ASUSTek       | K55VD                       | [6976a25d72](https://linux-hardware.org/?probe=6976a25d72) | Jun 01, 2020 |
| Dell          | Latitude E5440              | [d31fc5cae1](https://linux-hardware.org/?probe=d31fc5cae1) | Jun 01, 2020 |
| HP            | Laptop 15-dw0xxx            | [3717bb5ab4](https://linux-hardware.org/?probe=3717bb5ab4) | May 29, 2020 |
| Dell          | Precision M4800             | [a11200c6f6](https://linux-hardware.org/?probe=a11200c6f6) | May 28, 2020 |
| ASUSTek       | K73SJ                       | [2c988f7e1b](https://linux-hardware.org/?probe=2c988f7e1b) | May 26, 2020 |
| Inter Sale... | NBW-10004B                  | [c706b2be14](https://linux-hardware.org/?probe=c706b2be14) | May 25, 2020 |
| Dell          | Latitude D420               | [40458ce50c](https://linux-hardware.org/?probe=40458ce50c) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 157       | 16.65%  |
| Ubuntu 18.04                 | 81        | 8.59%   |
| Ubuntu 22.04                 | 31        | 3.29%   |
| Zorin 16                     | 23        | 2.44%   |
| OpenMandriva 4.3             | 20        | 2.12%   |
| Linux Mint 20.3              | 20        | 2.12%   |
| OpenMandriva 4.2             | 19        | 2.01%   |
| ArcoLinux Rolling            | 19        | 2.01%   |
| Linux Mint 20.1              | 18        | 1.91%   |
| Ubuntu 19.10                 | 16        | 1.7%    |
| Manjaro                      | 16        | 1.7%    |
| Fedora 36                    | 16        | 1.7%    |
| Arch Rolling                 | 16        | 1.7%    |
| Arch                         | 16        | 1.7%    |
| Linux Mint 20                | 14        | 1.48%   |
| Linux Mint 19.3              | 13        | 1.38%   |
| Xubuntu 20.04                | 12        | 1.27%   |
| Debian 11                    | 12        | 1.27%   |
| Ubuntu 20.10                 | 11        | 1.17%   |
| Pop!_OS 21.04                | 11        | 1.17%   |
| Pop!_OS 20.04                | 11        | 1.17%   |
| KDE neon 20.04               | 11        | 1.17%   |
| Ubuntu 19.04                 | 10        | 1.06%   |
| Fedora 34                    | 10        | 1.06%   |
| Fedora 32                    | 10        | 1.06%   |
| Elementary 6.1               | 10        | 1.06%   |
| Ubuntu 21.10                 | 9         | 0.95%   |
| Ubuntu 21.04                 | 9         | 0.95%   |
| Linux Mint 20.2              | 9         | 0.95%   |
| Fedora 35                    | 9         | 0.95%   |
| ROSA R10                     | 8         | 0.85%   |
| Pop!_OS 22.04                | 8         | 0.85%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.85%   |
| Linux Mint 21                | 8         | 0.85%   |
| Debian Testing               | 8         | 0.85%   |
| Ubuntu Unity 20.04           | 7         | 0.74%   |
| ROSA R9                      | 7         | 0.74%   |
| Kubuntu 20.04                | 7         | 0.74%   |
| Zorin 15                     | 6         | 0.64%   |
| Ubuntu 18.10                 | 6         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 322       | 36.26%  |
| Linux Mint        | 90        | 10.14%  |
| OpenMandriva      | 49        | 5.52%   |
| Fedora            | 48        | 5.41%   |
| Pop!_OS           | 34        | 3.83%   |
| Zorin             | 32        | 3.6%    |
| Manjaro           | 32        | 3.6%    |
| Arch              | 31        | 3.49%   |
| Debian            | 29        | 3.27%   |
| Xubuntu           | 27        | 3.04%   |
| ArcoLinux         | 20        | 2.25%   |
| Kubuntu           | 19        | 2.14%   |
| ROSA              | 18        | 2.03%   |
| KDE neon          | 15        | 1.69%   |
| Ubuntu Unity      | 12        | 1.35%   |
| openSUSE          | 12        | 1.35%   |
| Lubuntu           | 11        | 1.24%   |
| Elementary        | 11        | 1.24%   |
| Gentoo            | 8         | 0.9%    |
| Ubuntu MATE       | 7         | 0.79%   |
| Endless           | 7         | 0.79%   |
| Kali              | 5         | 0.56%   |
| CentOS            | 5         | 0.56%   |
| BlackPanther      | 5         | 0.56%   |
| SteamOS           | 4         | 0.45%   |
| LMDE              | 4         | 0.45%   |
| EndeavourOS       | 4         | 0.45%   |
| Ubuntu Budgie     | 3         | 0.34%   |
| MX                | 3         | 0.34%   |
| LinuxFX           | 3         | 0.34%   |
| Clear Linux       | 3         | 0.34%   |
| Rocky Linux       | 2         | 0.23%   |
| NixOS             | 2         | 0.23%   |
| Garuda Linux      | 2         | 0.23%   |
| Ultramarine Linux | 1         | 0.11%   |
| Solus             | 1         | 0.11%   |
| Reborn OS         | 1         | 0.11%   |
| Parrot            | 1         | 0.11%   |
| Nobara            | 1         | 0.11%   |
| Kaisen            | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 19        | 1.81%   |
| 5.10.14-desktop-1omv4002        | 18        | 1.72%   |
| 5.4.0-42-generic                | 17        | 1.62%   |
| 5.4.0-58-generic                | 16        | 1.53%   |
| 5.3.0-42-generic                | 15        | 1.43%   |
| 5.4.0-48-generic                | 13        | 1.24%   |
| 5.4.0-66-generic                | 11        | 1.05%   |
| 5.15.0-48-generic               | 11        | 1.05%   |
| 5.4.0-29-generic                | 10        | 0.95%   |
| 5.3.0-46-generic                | 10        | 0.95%   |
| 5.15.0-56-generic               | 10        | 0.95%   |
| 5.15.0-46-generic               | 10        | 0.95%   |
| 5.8.0-43-generic                | 9         | 0.86%   |
| 5.15.0-52-generic               | 9         | 0.86%   |
| 5.11.0-43-generic               | 9         | 0.86%   |
| 5.4.0-74-generic                | 8         | 0.76%   |
| 5.13.0-39-generic               | 8         | 0.76%   |
| 5.4.0-65-generic                | 7         | 0.67%   |
| 5.4.0-52-generic                | 7         | 0.67%   |
| 5.4.0-40-generic                | 7         | 0.67%   |
| 5.4.0-26-generic                | 7         | 0.67%   |
| 5.15.0-47-generic               | 7         | 0.67%   |
| 5.13.0-28-generic               | 7         | 0.67%   |
| 5.11.0-7620-generic             | 7         | 0.67%   |
| 5.11.0-38-generic               | 7         | 0.67%   |
| 5.0.0-29-generic                | 7         | 0.67%   |
| 5.8.0-53-generic                | 6         | 0.57%   |
| 5.4.0-91-generic                | 6         | 0.57%   |
| 5.4.0-90-generic                | 6         | 0.57%   |
| 5.4.0-56-generic                | 6         | 0.57%   |
| 5.4.0-53-generic                | 6         | 0.57%   |
| 5.4.0-37-generic                | 6         | 0.57%   |
| 5.3.0-40-generic                | 6         | 0.57%   |
| 5.13.0-40-generic               | 6         | 0.57%   |
| 5.13.0-35-generic               | 6         | 0.57%   |
| 5.11.0-41-generic               | 6         | 0.57%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 6         | 0.57%   |
| 5.8.0-55-generic                | 5         | 0.48%   |
| 5.8.0-48-generic                | 5         | 0.48%   |
| 5.4.0-47-generic                | 5         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 194       | 19.74%  |
| 5.15.0  | 80        | 8.14%   |
| 5.11.0  | 68        | 6.92%   |
| 5.8.0   | 58        | 5.9%    |
| 5.13.0  | 58        | 5.9%    |
| 4.15.0  | 57        | 5.8%    |
| 5.3.0   | 49        | 4.98%   |
| 5.0.0   | 30        | 3.05%   |
| 5.10.0  | 22        | 2.24%   |
| 4.18.0  | 21        | 2.14%   |
| 5.16.7  | 19        | 1.93%   |
| 5.10.14 | 18        | 1.83%   |
| 5.19.0  | 6         | 0.61%   |
| 5.17.5  | 6         | 0.61%   |
| 4.9.20  | 6         | 0.61%   |
| 4.19.0  | 6         | 0.61%   |
| 6.0.0   | 5         | 0.51%   |
| 5.18.12 | 5         | 0.51%   |
| 4.18.16 | 5         | 0.51%   |
| 5.18.0  | 4         | 0.41%   |
| 5.16.0  | 4         | 0.41%   |
| 4.9.60  | 4         | 0.41%   |
| 4.4.0   | 4         | 0.41%   |
| 6.0.8   | 3         | 0.31%   |
| 5.9.11  | 3         | 0.31%   |
| 5.8.5   | 3         | 0.31%   |
| 5.8.18  | 3         | 0.31%   |
| 5.4.8   | 3         | 0.31%   |
| 5.4.15  | 3         | 0.31%   |
| 5.3.18  | 3         | 0.31%   |
| 5.19.5  | 3         | 0.31%   |
| 5.19.12 | 3         | 0.31%   |
| 5.18.10 | 3         | 0.31%   |
| 5.14.10 | 3         | 0.31%   |
| 5.12.8  | 3         | 0.31%   |
| 5.12.4  | 3         | 0.31%   |
| 6.0.6   | 2         | 0.2%    |
| 6.0.2   | 2         | 0.2%    |
| 6.0.12  | 2         | 0.2%    |
| 5.9.14  | 2         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 212       | 21.95%  |
| 5.15    | 100       | 10.35%  |
| 5.11    | 77        | 7.97%   |
| 5.8     | 71        | 7.35%   |
| 5.13    | 67        | 6.94%   |
| 4.15    | 57        | 5.9%    |
| 5.3     | 55        | 5.69%   |
| 5.10    | 54        | 5.59%   |
| 5.16    | 36        | 3.73%   |
| 5.0     | 32        | 3.31%   |
| 4.18    | 27        | 2.8%    |
| 5.18    | 22        | 2.28%   |
| 5.17    | 19        | 1.97%   |
| 5.19    | 18        | 1.86%   |
| 6.0     | 17        | 1.76%   |
| 5.12    | 15        | 1.55%   |
| 4.9     | 14        | 1.45%   |
| 5.6     | 12        | 1.24%   |
| 5.14    | 12        | 1.24%   |
| 5.9     | 10        | 1.04%   |
| 4.19    | 10        | 1.04%   |
| 5.7     | 8         | 0.83%   |
| 5.5     | 5         | 0.52%   |
| 4.4     | 4         | 0.41%   |
| 5.1     | 3         | 0.31%   |
| 5.2     | 2         | 0.21%   |
| 4.17    | 2         | 0.21%   |
| 4.1     | 2         | 0.21%   |
| 4.13    | 1         | 0.1%    |
| 4.12    | 1         | 0.1%    |
| 4.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 821       | 96.47%  |
| i686   | 30        | 3.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 384       | 42.48%  |
| KDE5            | 127       | 14.05%  |
| Unknown         | 119       | 13.16%  |
| XFCE            | 75        | 8.3%    |
| X-Cinnamon      | 61        | 6.75%   |
| MATE            | 29        | 3.21%   |
| KDE             | 20        | 2.21%   |
| Unity           | 12        | 1.33%   |
| Pantheon        | 11        | 1.22%   |
| LXQt            | 11        | 1.22%   |
| KDE4            | 11        | 1.22%   |
| Cinnamon        | 10        | 1.11%   |
| i3              | 9         | 1%      |
| Budgie          | 7         | 0.77%   |
| sway            | 3         | 0.33%   |
| LXDE            | 2         | 0.22%   |
| LeftWM          | 2         | 0.22%   |
| GNOME Flashback | 2         | 0.22%   |
| bspwm           | 2         | 0.22%   |
| awesome         | 2         | 0.22%   |
| xmonad          | 1         | 0.11%   |
| spectrwm        | 1         | 0.11%   |
| qtile           | 1         | 0.11%   |
| Openbox         | 1         | 0.11%   |
| Deepin          | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 694       | 79.13%  |
| Wayland | 111       | 12.66%  |
| Unknown | 67        | 7.64%   |
| Tty     | 5         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 466       | 52.13%  |
| SDDM    | 131       | 14.65%  |
| GDM     | 108       | 12.08%  |
| GDM3    | 75        | 8.39%   |
| LightDM | 64        | 7.16%   |
| TDM     | 37        | 4.14%   |
| KDM     | 11        | 1.23%   |
| XDM     | 1         | 0.11%   |
| SLiM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 289       | 32.66%  |
| fr_BE      | 151       | 17.06%  |
| nl_BE      | 123       | 13.9%   |
| Unknown    | 121       | 13.67%  |
| nl_NL      | 50        | 5.65%   |
| en_GB      | 47        | 5.31%   |
| fr_FR      | 38        | 4.29%   |
| C          | 13        | 1.47%   |
| de_DE      | 11        | 1.24%   |
| de_BE      | 6         | 0.68%   |
| ru_RU      | 4         | 0.45%   |
| pl_PL      | 4         | 0.45%   |
| es_ES      | 4         | 0.45%   |
| ro_RO      | 2         | 0.23%   |
| pt_PT      | 2         | 0.23%   |
| en_IE      | 2         | 0.23%   |
| en_CA      | 2         | 0.23%   |
| en_BE      | 2         | 0.23%   |
| tt_RU      | 1         | 0.11%   |
| tr_TR      | 1         | 0.11%   |
| pt_BR      | 1         | 0.11%   |
| POSIX      | 1         | 0.11%   |
| nl_AW      | 1         | 0.11%   |
| it_IT      | 1         | 0.11%   |
| it_CH      | 1         | 0.11%   |
| fr_CH      | 1         | 0.11%   |
| en_ZA      | 1         | 0.11%   |
| en_US.UTF8 | 1         | 0.11%   |
| en_IN      | 1         | 0.11%   |
| en_DK      | 1         | 0.11%   |
| C.UTF8     | 1         | 0.11%   |
| bg_BG      | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 443       | 50.69%  |
| EFI  | 431       | 49.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 699       | 79.98%  |
| Btrfs   | 65        | 7.44%   |
| Overlay | 57        | 6.52%   |
| Unknown | 32        | 3.66%   |
| Xfs     | 13        | 1.49%   |
| Tmpfs   | 4         | 0.46%   |
| Zfs     | 2         | 0.23%   |
| Ext2    | 2         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 507       | 58.21%  |
| GPT     | 286       | 32.84%  |
| MBR     | 78        | 8.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 753       | 86.75%  |
| Yes       | 115       | 13.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 634       | 73.46%  |
| Yes       | 229       | 26.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 179       | 21.06%  |
| Dell                | 155       | 18.24%  |
| Lenovo              | 146       | 17.18%  |
| ASUSTek Computer    | 93        | 10.94%  |
| Acer                | 61        | 7.18%   |
| Toshiba             | 31        | 3.65%   |
| Sony                | 25        | 2.94%   |
| Apple               | 22        | 2.59%   |
| Medion              | 21        | 2.47%   |
| Notebook            | 18        | 2.12%   |
| MSI                 | 16        | 1.88%   |
| Packard Bell        | 14        | 1.65%   |
| TUXEDO              | 8         | 0.94%   |
| Samsung Electronics | 7         | 0.82%   |
| Valve               | 5         | 0.59%   |
| PC Specialist       | 4         | 0.47%   |
| Gigabyte Technology | 4         | 0.47%   |
| Fujitsu             | 4         | 0.47%   |
| Unknown             | 4         | 0.47%   |
| Intel               | 3         | 0.35%   |
| HUAWEI              | 3         | 0.35%   |
| Google              | 3         | 0.35%   |
| Fujitsu Siemens     | 3         | 0.35%   |
| Razer               | 2         | 0.24%   |
| Panasonic           | 2         | 0.24%   |
| Clevo               | 2         | 0.24%   |
| YJKC                | 1         | 0.12%   |
| TrekStor            | 1         | 0.12%   |
| Timi                | 1         | 0.12%   |
| Teclast             | 1         | 0.12%   |
| Standard            | 1         | 0.12%   |
| SLIMBOOK            | 1         | 0.12%   |
| Schenker            | 1         | 0.12%   |
| NEC Computers       | 1         | 0.12%   |
| Inter Sales A/S     | 1         | 0.12%   |
| Hampoo              | 1         | 0.12%   |
| GPD                 | 1         | 0.12%   |
| Chuwi               | 1         | 0.12%   |
| Celestica           | 1         | 0.12%   |
| BLAUPUNKT           | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 6         | 0.71%   |
| Valve Jupiter                    | 5         | 0.59%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.59%   |
| HP ProBook 6570b                 | 5         | 0.59%   |
| HP ProBook 650 G1                | 5         | 0.59%   |
| HP Pavilion Notebook             | 5         | 0.59%   |
| HP Pavilion dv7                  | 5         | 0.59%   |
| Dell XPS 13 7390                 | 5         | 0.59%   |
| Toshiba Satellite C660           | 4         | 0.47%   |
| HP Pavilion g7                   | 4         | 0.47%   |
| HP Pavilion 17                   | 4         | 0.47%   |
| Gigabyte Spring Peak             | 4         | 0.47%   |
| Dell XPS 13 9370                 | 4         | 0.47%   |
| Dell Latitude 5520               | 4         | 0.47%   |
| Lenovo ThinkPad L390 20NSS1YV0B  | 3         | 0.35%   |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.35%   |
| HP ProBook 470 G2                | 3         | 0.35%   |
| HP ProBook 430 G1                | 3         | 0.35%   |
| HP Pavilion Laptop 15-eh1xxx     | 3         | 0.35%   |
| HP Pavilion Laptop 15-cw0xxx     | 3         | 0.35%   |
| HP Pavilion dv6                  | 3         | 0.35%   |
| HP Pavilion 15                   | 3         | 0.35%   |
| HP Notebook                      | 3         | 0.35%   |
| HP EliteBook 840 G1              | 3         | 0.35%   |
| Dell XPS 15 9570                 | 3         | 0.35%   |
| Dell XPS 13 9360                 | 3         | 0.35%   |
| Dell XPS 13 9305                 | 3         | 0.35%   |
| Dell Latitude E7440              | 3         | 0.35%   |
| Dell Latitude E6540              | 3         | 0.35%   |
| Dell Latitude E6500              | 3         | 0.35%   |
| Dell Latitude E6330              | 3         | 0.35%   |
| Dell Latitude E5540              | 3         | 0.35%   |
| Dell Latitude E5520              | 3         | 0.35%   |
| Dell Latitude 5530               | 3         | 0.35%   |
| Dell Latitude 5500               | 3         | 0.35%   |
| Dell Inspiron 5521               | 3         | 0.35%   |
| Apple MacBookPro9,2              | 3         | 0.35%   |
| Apple MacBookAir6,2              | 3         | 0.35%   |
| Acer Aspire V3-771               | 3         | 0.35%   |
| Acer Aspire 5750G                | 3         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 85        | 10%     |
| Dell Latitude         | 74        | 8.71%   |
| Acer Aspire           | 50        | 5.88%   |
| HP EliteBook          | 46        | 5.41%   |
| HP Pavilion           | 45        | 5.29%   |
| HP ProBook            | 40        | 4.71%   |
| Dell XPS              | 30        | 3.53%   |
| Toshiba Satellite     | 27        | 3.18%   |
| Lenovo IdeaPad        | 26        | 3.06%   |
| Dell Inspiron         | 20        | 2.35%   |
| HP Laptop             | 13        | 1.53%   |
| HP Compaq             | 13        | 1.53%   |
| Dell Precision        | 13        | 1.53%   |
| Packard Bell EasyNote | 12        | 1.41%   |
| Lenovo Legion         | 11        | 1.29%   |
| HP ZBook              | 7         | 0.82%   |
| Dell Vostro           | 7         | 0.82%   |
| ASUS VivoBook         | 6         | 0.71%   |
| Unknown               | 6         | 0.71%   |
| Valve Jupiter         | 5         | 0.59%   |
| Dell Studio           | 5         | 0.59%   |
| Medion Akoya          | 4         | 0.47%   |
| Lenovo ThinkBook      | 4         | 0.47%   |
| Gigabyte Spring       | 4         | 0.47%   |
| Dell G3               | 4         | 0.47%   |
| ASUS ZenBook          | 4         | 0.47%   |
| ASUS ROG              | 4         | 0.47%   |
| Apple MacBookPro9     | 4         | 0.47%   |
| Acer Swift            | 4         | 0.47%   |
| TUXEDO Pulse          | 3         | 0.35%   |
| HP OMEN               | 3         | 0.35%   |
| HP Notebook           | 3         | 0.35%   |
| HP ENVY               | 3         | 0.35%   |
| Fujitsu LIFEBOOK      | 3         | 0.35%   |
| Apple MacBookPro5     | 3         | 0.35%   |
| Apple MacBookAir6     | 3         | 0.35%   |
| Acer Nitro            | 3         | 0.35%   |
| TUXEDO Aura           | 2         | 0.24%   |
| Toshiba TECRA         | 2         | 0.24%   |
| Toshiba Portable      | 2         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 81        | 9.53%   |
| 2018    | 78        | 9.18%   |
| 2020    | 77        | 9.06%   |
| 2012    | 75        | 8.82%   |
| 2011    | 71        | 8.35%   |
| 2013    | 69        | 8.12%   |
| 2015    | 49        | 5.76%   |
| 2021    | 48        | 5.65%   |
| 2008    | 47        | 5.53%   |
| 2017    | 43        | 5.06%   |
| 2014    | 43        | 5.06%   |
| 2016    | 42        | 4.94%   |
| 2010    | 37        | 4.35%   |
| 2009    | 29        | 3.41%   |
| 2007    | 26        | 3.06%   |
| 2022    | 18        | 2.12%   |
| 2006    | 12        | 1.41%   |
| 2005    | 2         | 0.24%   |
| 2004    | 2         | 0.24%   |
| Unknown | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 850       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 767       | 89.39%  |
| Enabled  | 91        | 10.61%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 847       | 99.65%  |
| Yes  | 3         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 228       | 26.3%   |
| 3.01-4.0    | 178       | 20.53%  |
| 8.01-16.0   | 169       | 19.49%  |
| 16.01-24.0  | 147       | 16.96%  |
| 32.01-64.0  | 59        | 6.81%   |
| 1.01-2.0    | 35        | 4.04%   |
| 24.01-32.0  | 15        | 1.73%   |
| 0.51-1.0    | 13        | 1.5%    |
| 2.01-3.0    | 12        | 1.38%   |
| 64.01-256.0 | 10        | 1.15%   |
| 0.01-0.5    | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 337       | 35.29%  |
| 2.01-3.0   | 236       | 24.71%  |
| 4.01-8.0   | 120       | 12.57%  |
| 3.01-4.0   | 117       | 12.25%  |
| 0.51-1.0   | 68        | 7.12%   |
| 8.01-16.0  | 54        | 5.65%   |
| 0.01-0.5   | 18        | 1.88%   |
| 16.01-24.0 | 3         | 0.31%   |
| 24.01-32.0 | 2         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 618       | 70.71%  |
| 2      | 230       | 26.32%  |
| 3      | 16        | 1.83%   |
| 0      | 5         | 0.57%   |
| 4      | 3         | 0.34%   |
| 8      | 1         | 0.11%   |
| 5      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 500       | 58.48%  |
| Yes       | 355       | 41.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 755       | 88.2%   |
| No        | 101       | 11.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 839       | 98.24%  |
| No        | 15        | 1.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 639       | 74.04%  |
| No        | 224       | 25.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Belgium | 850       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brussels       | 108       | 11.55%  |
| Antwerp        | 61        | 6.52%   |
| Ghent          | 31        | 3.32%   |
| Ixelles-Elsene | 27        | 2.89%   |
| Liège         | 23        | 2.46%   |
| Mechelen       | 13        | 1.39%   |
| Turnhout       | 12        | 1.28%   |
| Leuven         | 11        | 1.18%   |
| Uccle          | 10        | 1.07%   |
| Schaarbeek     | 10        | 1.07%   |
| Anderlecht     | 10        | 1.07%   |
| Sint-Truiden   | 8         | 0.86%   |
| Mons           | 8         | 0.86%   |
| Jette          | 8         | 0.86%   |
| Harelbeke      | 8         | 0.86%   |
| Bruges         | 8         | 0.86%   |
| Aalst          | 8         | 0.86%   |
| Etterbeek      | 7         | 0.75%   |
| Brasschaat     | 7         | 0.75%   |
| Boom           | 7         | 0.75%   |
| Bilzen         | 7         | 0.75%   |
| La Louvière   | 6         | 0.64%   |
| Kontich        | 6         | 0.64%   |
| Kanne          | 6         | 0.64%   |
| Hasselt        | 6         | 0.64%   |
| Gavere         | 6         | 0.64%   |
| Edegem         | 6         | 0.64%   |
| Charleroi      | 6         | 0.64%   |
| Wetteren       | 5         | 0.53%   |
| Schoten        | 5         | 0.53%   |
| Namur          | 5         | 0.53%   |
| Mol            | 5         | 0.53%   |
| Geel           | 5         | 0.53%   |
| Ypres          | 4         | 0.43%   |
| Vilvoorde      | 4         | 0.43%   |
| Tielt-Winge    | 4         | 0.43%   |
| Sint-Amands    | 4         | 0.43%   |
| Seraing        | 4         | 0.43%   |
| Roeselare      | 4         | 0.43%   |
| Riemst         | 4         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 215       | 307    | 20.55%  |
| Seagate                   | 129       | 178    | 12.33%  |
| WDC                       | 116       | 159    | 11.09%  |
| Toshiba                   | 83        | 111    | 7.93%   |
| SK hynix                  | 55        | 69     | 5.26%   |
| SanDisk                   | 53        | 72     | 5.07%   |
| Kingston                  | 47        | 60     | 4.49%   |
| Unknown                   | 45        | 54     | 4.3%    |
| Hitachi                   | 42        | 50     | 4.02%   |
| Intel                     | 37        | 44     | 3.54%   |
| HGST                      | 30        | 40     | 2.87%   |
| Micron Technology         | 27        | 28     | 2.58%   |
| Crucial                   | 26        | 35     | 2.49%   |
| Fujitsu                   | 12        | 17     | 1.15%   |
| Apple                     | 11        | 15     | 1.05%   |
| LITEON                    | 9         | 11     | 0.86%   |
| KIOXIA                    | 9         | 11     | 0.86%   |
| LITEONIT                  | 8         | 11     | 0.76%   |
| A-DATA Technology         | 7         | 9      | 0.67%   |
| Intenso                   | 6         | 7      | 0.57%   |
| China                     | 6         | 8      | 0.57%   |
| PNY                       | 5         | 6      | 0.48%   |
| OCZ                       | 4         | 5      | 0.38%   |
| Transcend                 | 3         | 3      | 0.29%   |
| SSSTC                     | 3         | 3      | 0.29%   |
| Silicon Motion            | 3         | 4      | 0.29%   |
| Phison                    | 3         | 3      | 0.29%   |
| Micron/Crucial Technology | 3         | 5      | 0.29%   |
| GOODRAM                   | 3         | 5      | 0.29%   |
| Corsair                   | 3         | 3      | 0.29%   |
| Zheino                    | 2         | 2      | 0.19%   |
| Union Memory (Shenzhen)   | 2         | 2      | 0.19%   |
| Phison Electronics        | 2         | 2      | 0.19%   |
| LaCie                     | 2         | 2      | 0.19%   |
| KingSpec                  | 2         | 2      | 0.19%   |
| JMicron Technology        | 2         | 3      | 0.19%   |
| ASMT                      | 2         | 2      | 0.19%   |
| XrayDisk                  | 1         | 1      | 0.1%    |
| Union Memory              | 1         | 1      | 0.1%    |
| UMIS                      | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB          | 17        | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB        | 16        | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 14        | 1.28%   |
| Samsung NVMe SSD Drive 1TB            | 13        | 1.19%   |
| Intel NVMe SSD Drive 512GB            | 13        | 1.19%   |
| SK hynix NVMe SSD Drive 512GB         | 12        | 1.1%    |
| SanDisk NVMe SSD Drive 512GB          | 12        | 1.1%    |
| Seagate ST9500325AS 500GB             | 11        | 1.01%   |
| Samsung SSD 860 EVO 500GB             | 11        | 1.01%   |
| Samsung SSD 850 EVO 250GB             | 11        | 1.01%   |
| Toshiba MQ01ABD100 1TB                | 10        | 0.92%   |
| Samsung SSD 850 EVO 500GB             | 10        | 0.92%   |
| HGST HTS721010A9E630 1TB              | 10        | 0.92%   |
| Unknown MMC Card  32GB                | 9         | 0.83%   |
| Hitachi HTS547550A9E384 500GB         | 8         | 0.73%   |
| Seagate ST1000LM048-2E7172 1TB        | 7         | 0.64%   |
| Kingston SA400S37120G 120GB SSD       | 7         | 0.64%   |
| HGST HTS725050A7E630 500GB            | 7         | 0.64%   |
| Unknown MMC Card  128GB               | 6         | 0.55%   |
| Seagate ST500LT012-1DG142 500GB       | 6         | 0.55%   |
| Seagate Expansion 4TB                 | 6         | 0.55%   |
| Samsung NVMe SSD Drive 500GB          | 6         | 0.55%   |
| Kingston SA400S37240G 240GB SSD       | 6         | 0.55%   |
| Toshiba MQ01ABF050 500GB              | 5         | 0.46%   |
| SanDisk NVMe SSD Drive 256GB          | 5         | 0.46%   |
| Samsung SSD 870 EVO 1TB               | 5         | 0.46%   |
| Samsung SSD 860 EVO 1TB               | 5         | 0.46%   |
| Kingston SV300S37A240G 240GB SSD      | 5         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 4         | 0.37%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 4         | 0.37%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 4         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB              | 4         | 0.37%   |
| Unknown MMC Card  64GB                | 4         | 0.37%   |
| Unknown MMC Card  256GB               | 4         | 0.37%   |
| Toshiba NVMe SSD Drive 512GB          | 4         | 0.37%   |
| Toshiba MQ04ABF100 1TB                | 4         | 0.37%   |
| Toshiba MQ01ABD075 752GB              | 4         | 0.37%   |
| SK hynix NVMe SSD Drive 256GB         | 4         | 0.37%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 4         | 0.37%   |
| Seagate ST9500420AS 500GB             | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 124       | 169    | 34.54%  |
| WDC                 | 83        | 112    | 23.12%  |
| Toshiba             | 57        | 79     | 15.88%  |
| Hitachi             | 42        | 50     | 11.7%   |
| HGST                | 30        | 40     | 8.36%   |
| Fujitsu             | 12        | 16     | 3.34%   |
| Samsung Electronics | 6         | 7      | 1.67%   |
| ASMT                | 2         | 2      | 0.56%   |
| Unknown             | 1         | 1      | 0.28%   |
| LaCie               | 1         | 1      | 0.28%   |
| Apple               | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 109       | 155    | 31.5%   |
| Kingston            | 35        | 44     | 10.12%  |
| SanDisk             | 32        | 46     | 9.25%   |
| Crucial             | 22        | 30     | 6.36%   |
| WDC                 | 17        | 22     | 4.91%   |
| SK hynix            | 16        | 23     | 4.62%   |
| Intel               | 13        | 15     | 3.76%   |
| Micron Technology   | 12        | 12     | 3.47%   |
| Toshiba             | 11        | 14     | 3.18%   |
| LITEON              | 9         | 11     | 2.6%    |
| LITEONIT            | 8         | 11     | 2.31%   |
| Apple               | 8         | 11     | 2.31%   |
| China               | 6         | 8      | 1.73%   |
| PNY                 | 5         | 6      | 1.45%   |
| Intenso             | 5         | 6      | 1.45%   |
| A-DATA Technology   | 5         | 7      | 1.45%   |
| OCZ                 | 4         | 5      | 1.16%   |
| GOODRAM             | 3         | 5      | 0.87%   |
| Zheino              | 2         | 2      | 0.58%   |
| Transcend           | 2         | 2      | 0.58%   |
| KingSpec            | 2         | 2      | 0.58%   |
| Corsair             | 2         | 2      | 0.58%   |
| TO Exter            | 1         | 1      | 0.29%   |
| Teclast             | 1         | 1      | 0.29%   |
| SPCC                | 1         | 2      | 0.29%   |
| Reeinno             | 1         | 3      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| Patriot             | 1         | 1      | 0.29%   |
| OWC                 | 1         | 2      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| Leven               | 1         | 1      | 0.29%   |
| JMicron Technology  | 1         | 1      | 0.29%   |
| INTEL SS            | 1         | 1      | 0.29%   |
| Innodisk            | 1         | 1      | 0.29%   |
| Indilinx            | 1         | 1      | 0.29%   |
| HEORIADY            | 1         | 1      | 0.29%   |
| Fujitsu             | 1         | 1      | 0.29%   |
| FORESEE             | 1         | 1      | 0.29%   |
| Drevo               | 1         | 1      | 0.29%   |
| Dogfish             | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 341       | 478    | 34.31%  |
| SSD     | 324       | 461    | 32.6%   |
| NVMe    | 278       | 378    | 27.97%  |
| MMC     | 40        | 50     | 4.02%   |
| Unknown | 11        | 14     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 596       | 902    | 62.74%  |
| NVMe | 278       | 378    | 29.26%  |
| MMC  | 40        | 50     | 4.21%   |
| SAS  | 36        | 51     | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 475       | 648    | 70.68%  |
| 0.51-1.0   | 171       | 258    | 25.45%  |
| 1.01-2.0   | 15        | 18     | 2.23%   |
| 3.01-4.0   | 10        | 14     | 1.49%   |
| 2.01-3.0   | 1         | 1      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 284       | 31.31%  |
| 251-500        | 252       | 27.78%  |
| 501-1000       | 114       | 12.57%  |
| 51-100         | 61        | 6.73%   |
| 1001-2000      | 53        | 5.84%   |
| 1-20           | 48        | 5.29%   |
| Unknown        | 33        | 3.64%   |
| 21-50          | 26        | 2.87%   |
| 2001-3000      | 22        | 2.43%   |
| More than 3000 | 14        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 368       | 38.49%  |
| 21-50          | 166       | 17.36%  |
| 101-250        | 142       | 14.85%  |
| 51-100         | 118       | 12.34%  |
| 251-500        | 64        | 6.69%   |
| 501-1000       | 41        | 4.29%   |
| Unknown        | 33        | 3.45%   |
| 1001-2000      | 13        | 1.36%   |
| 2001-3000      | 7         | 0.73%   |
| More than 3000 | 4         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 4         | 4      | 6.78%   |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 3.39%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 3      | 3.39%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 3.39%   |
| WDC WD3200BPVT-55JJ5T0 320GB                   | 1         | 1      | 1.69%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD032 320GB                       | 1         | 1      | 1.69%   |
| Toshiba MK6476GSX 640GB                        | 1         | 1      | 1.69%   |
| Toshiba MK5075GSX 500GB                        | 1         | 1      | 1.69%   |
| Toshiba KSG60ZSE512G SATA 512GB SSD            | 1         | 1      | 1.69%   |
| SK hynix SH920 mSATA 256GB SSD                 | 1         | 1      | 1.69%   |
| SK hynix SH920 2.5 7MM 256GB SSD               | 1         | 1      | 1.69%   |
| SK hynix SC401 SATA 512GB SSD                  | 1         | 2      | 1.69%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 1.69%   |
| SK hynix HFS256G32MND-2900A 256GB SSD          | 1         | 1      | 1.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 1.69%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.69%   |
| Seagate ST9320423AS 320GB                      | 1         | 2      | 1.69%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 1.69%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 1.69%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 1      | 1.69%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 1.69%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 2      | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 6      | 1.69%   |
| SanDisk SSD PLUS 480GB                         | 1         | 1      | 1.69%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD            | 1         | 1      | 1.69%   |
| Samsung Electronics HM641JI 640GB              | 1         | 1      | 1.69%   |
| OCZ VERTEX3 256GB SSD                          | 1         | 1      | 1.69%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.69%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 1.69%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 6      | 1.69%   |
| Intel SSDSCKKF256H6 SATA 256GB                 | 1         | 1      | 1.69%   |
| Intel SSDSC2KW240H6 240GB                      | 1         | 1      | 1.69%   |
| Intel SSDSC2KF256H6L 256GB                     | 1         | 1      | 1.69%   |
| Intel SSDSC2CT180A3 180GB                      | 1         | 1      | 1.69%   |
| Intel SSDPEKKW256G7 256GB                      | 1         | 1      | 1.69%   |
| Hitachi HTS727550A9E364 500GB                  | 1         | 1      | 1.69%   |
| Hitachi HTS725050A7E630 500GB                  | 1         | 1      | 1.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 21     | 23.73%  |
| Hitachi             | 8         | 9      | 13.56%  |
| Toshiba             | 6         | 6      | 10.17%  |
| SK hynix            | 6         | 7      | 10.17%  |
| Intel               | 5         | 5      | 8.47%   |
| HGST                | 4         | 4      | 6.78%   |
| Fujitsu             | 4         | 7      | 6.78%   |
| WDC                 | 2         | 2      | 3.39%   |
| SanDisk             | 2         | 2      | 3.39%   |
| Micron Technology   | 2         | 2      | 3.39%   |
| Crucial             | 2         | 2      | 3.39%   |
| Samsung Electronics | 1         | 1      | 1.69%   |
| OCZ                 | 1         | 1      | 1.69%   |
| Kingston            | 1         | 6      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 21     | 36.84%  |
| Hitachi             | 8         | 9      | 21.05%  |
| Toshiba             | 5         | 5      | 13.16%  |
| HGST                | 4         | 4      | 10.53%  |
| Fujitsu             | 4         | 7      | 10.53%  |
| WDC                 | 2         | 2      | 5.26%   |
| Samsung Electronics | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 49     | 64.41%  |
| SSD  | 18        | 24     | 30.51%  |
| NVMe | 3         | 3      | 5.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 50%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 50%     |
| HGST                | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 540       | 880    | 59.93%  |
| Works    | 302       | 422    | 33.52%  |
| Malfunc  | 57        | 76     | 6.33%   |
| Failed   | 2         | 3      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 615       | 62.12%  |
| Samsung Electronics              | 108       | 10.91%  |
| AMD                              | 81        | 8.18%   |
| SK hynix                         | 39        | 3.94%   |
| SanDisk                          | 35        | 3.54%   |
| Toshiba America Info Systems     | 16        | 1.62%   |
| Micron Technology                | 15        | 1.52%   |
| Kingston Technology Company      | 13        | 1.31%   |
| KIOXIA                           | 10        | 1.01%   |
| Nvidia                           | 9         | 0.91%   |
| Union Memory (Shenzhen)          | 6         | 0.61%   |
| Solid State Storage Technology   | 6         | 0.61%   |
| Phison Electronics               | 6         | 0.61%   |
| Micron/Crucial Technology        | 6         | 0.61%   |
| Marvell Technology Group         | 5         | 0.51%   |
| Silicon Motion                   | 3         | 0.3%    |
| Silicon Image                    | 3         | 0.3%    |
| Seagate Technology               | 3         | 0.3%    |
| Silicon Integrated Systems [SiS] | 2         | 0.2%    |
| Apple                            | 2         | 0.2%    |
| ADATA Technology                 | 2         | 0.2%    |
| VIA Technologies                 | 1         | 0.1%    |
| Transcend                        | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| Biwin Storage Technology         | 1         | 0.1%    |
| ASMedia Technology               | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 84        | 7.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 64        | 5.94%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 64        | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 61        | 5.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 56        | 5.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 54        | 5.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 43        | 3.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 30        | 2.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 29        | 2.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 26        | 2.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 2.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 21        | 1.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 1.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 1.67%   |
| Micron Non-Volatile memory controller                                          | 15        | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 13        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 13        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.11%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 11        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 1.02%   |
| SK hynix Non-Volatile memory controller                                        | 10        | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 10        | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 10        | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 0.84%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 9         | 0.84%   |
| Intel SSD 660P Series                                                          | 9         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 9         | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 8         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 0.65%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 6         | 0.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 606       | 58.55%  |
| NVMe | 279       | 26.96%  |
| RAID | 76        | 7.34%   |
| IDE  | 74        | 7.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 719       | 84.59%  |
| AMD    | 131       | 15.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 2%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 1.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 12        | 1.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.18%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 1.18%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 10        | 1.18%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 10        | 1.18%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 10        | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 1.18%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 9         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 1.06%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 1.06%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 8         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.82%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 7         | 0.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.71%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 6         | 0.71%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.71%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 6         | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 0.71%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.71%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 6         | 0.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 5         | 0.59%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 5         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 242       | 28.47%  |
| Intel Core i5           | 206       | 24.24%  |
| Intel Core 2 Duo        | 65        | 7.65%   |
| Intel Core i3           | 60        | 7.06%   |
| Other                   | 48        | 5.65%   |
| AMD Ryzen 5             | 27        | 3.18%   |
| Intel Celeron           | 22        | 2.59%   |
| AMD Ryzen 7             | 22        | 2.59%   |
| Intel Pentium           | 16        | 1.88%   |
| Intel Atom              | 15        | 1.76%   |
| AMD Ryzen 7 PRO         | 11        | 1.29%   |
| AMD E1                  | 10        | 1.18%   |
| AMD E                   | 9         | 1.06%   |
| Intel Pentium Dual-Core | 8         | 0.94%   |
| Intel Core 2            | 8         | 0.94%   |
| Intel Genuine           | 7         | 0.82%   |
| AMD Ryzen 9             | 7         | 0.82%   |
| AMD A6                  | 7         | 0.82%   |
| Intel Core i9           | 6         | 0.71%   |
| AMD Ryzen 5 PRO         | 6         | 0.71%   |
| AMD A4                  | 6         | 0.71%   |
| Intel Pentium Silver    | 5         | 0.59%   |
| AMD A8                  | 5         | 0.59%   |
| Intel Pentium Dual      | 3         | 0.35%   |
| Intel Celeron M         | 3         | 0.35%   |
| AMD Ryzen 3             | 3         | 0.35%   |
| Intel Xeon              | 2         | 0.24%   |
| Intel Pentium 4         | 2         | 0.24%   |
| AMD Turion 64 X2 Mobile | 2         | 0.24%   |
| AMD Athlon II           | 2         | 0.24%   |
| AMD A12                 | 2         | 0.24%   |
| Intel Pentium M         | 1         | 0.12%   |
| Intel Mobile Pentium 4  | 1         | 0.12%   |
| Intel Core m5           | 1         | 0.12%   |
| Intel Core m3           | 1         | 0.12%   |
| Intel Core Duo          | 1         | 0.12%   |
| Intel Core 2 Quad       | 1         | 0.12%   |
| Intel Celeron Dual-Core | 1         | 0.12%   |
| AMD Turion II Neo       | 1         | 0.12%   |
| AMD Turion 64 Mobile    | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 431       | 50.65%  |
| 4       | 276       | 32.43%  |
| 6       | 61        | 7.17%   |
| 8       | 50        | 5.88%   |
| 1       | 19        | 2.23%   |
| 10      | 5         | 0.59%   |
| Unknown | 4         | 0.47%   |
| 12      | 3         | 0.35%   |
| 16      | 1         | 0.12%   |
| 14      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 850       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 645       | 75.7%   |
| 1       | 203       | 23.83%  |
| Unknown | 4         | 0.47%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 828       | 97.07%  |
| Unknown        | 14        | 1.64%   |
| 32-bit         | 11        | 1.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 19.5%   |
| 0x306a9    | 72        | 8.16%   |
| 0x206a7    | 60        | 6.8%    |
| 0x806ea    | 34        | 3.85%   |
| 0x806ec    | 33        | 3.74%   |
| 0x40651    | 32        | 3.63%   |
| 0x1067a    | 32        | 3.63%   |
| 0x306c3    | 29        | 3.29%   |
| 0x906ea    | 26        | 2.95%   |
| 0x406e3    | 25        | 2.83%   |
| 0x306d4    | 24        | 2.72%   |
| 0x20655    | 22        | 2.49%   |
| 0x906e9    | 20        | 2.27%   |
| 0x6fd      | 20        | 2.27%   |
| 0x806e9    | 18        | 2.04%   |
| 0x806c1    | 18        | 2.04%   |
| 0xa0652    | 15        | 1.7%    |
| 0x10676    | 15        | 1.7%    |
| 0x08600106 | 15        | 1.7%    |
| 0x806eb    | 10        | 1.13%   |
| 0x30678    | 10        | 1.13%   |
| 0x08608103 | 9         | 1.02%   |
| 0x05000119 | 9         | 1.02%   |
| 0x506e3    | 8         | 0.91%   |
| 0x0a50000c | 8         | 0.91%   |
| 0x07030105 | 8         | 0.91%   |
| 0x6f6      | 7         | 0.79%   |
| 0x08600103 | 7         | 0.79%   |
| 0x6fb      | 6         | 0.68%   |
| 0x20652    | 6         | 0.68%   |
| 0x906a4    | 5         | 0.57%   |
| 0x706a1    | 5         | 0.57%   |
| 0x08108102 | 5         | 0.57%   |
| 0x0700010f | 5         | 0.57%   |
| 0x906ed    | 4         | 0.45%   |
| 0x806d1    | 4         | 0.45%   |
| 0x406c4    | 4         | 0.45%   |
| 0x106ca    | 4         | 0.45%   |
| 0x106c2    | 4         | 0.45%   |
| 0x08600104 | 4         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 179       | 21.06%  |
| IvyBridge        | 82        | 9.65%   |
| SandyBridge      | 74        | 8.71%   |
| Haswell          | 74        | 8.71%   |
| Penryn           | 53        | 6.24%   |
| Core             | 39        | 4.59%   |
| Skylake          | 38        | 4.47%   |
| Zen 2            | 31        | 3.65%   |
| Westmere         | 31        | 3.65%   |
| TigerLake        | 28        | 3.29%   |
| Broadwell        | 26        | 3.06%   |
| Silvermont       | 21        | 2.47%   |
| CometLake        | 21        | 2.47%   |
| Unknown          | 21        | 2.47%   |
| Zen 3            | 14        | 1.65%   |
| Bobcat           | 14        | 1.65%   |
| Zen+             | 12        | 1.41%   |
| Puma             | 11        | 1.29%   |
| Goldmont plus    | 9         | 1.06%   |
| Bonnell          | 9         | 1.06%   |
| IceLake          | 8         | 0.94%   |
| P6               | 7         | 0.82%   |
| Jaguar           | 7         | 0.82%   |
| Excavator        | 7         | 0.82%   |
| Alderlake Hybrid | 7         | 0.82%   |
| Zen              | 6         | 0.71%   |
| NetBurst         | 3         | 0.35%   |
| Nehalem          | 3         | 0.35%   |
| K8 Hammer        | 3         | 0.35%   |
| K10              | 3         | 0.35%   |
| Tremont          | 2         | 0.24%   |
| Piledriver       | 2         | 0.24%   |
| K8 & K10 hybrid  | 2         | 0.24%   |
| Goldmont         | 2         | 0.24%   |
| K10 Llano        | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 619       | 57.53%  |
| Nvidia                           | 255       | 23.7%   |
| AMD                              | 200       | 18.59%  |
| VIA Technologies                 | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 75        | 6.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 63        | 5.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 3.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 39        | 3.5%    |
| Intel UHD Graphics 620                                                                   | 38        | 3.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 3.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 2.51%   |
| AMD Renoir                                                                               | 28        | 2.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.15%   |
| Intel HD Graphics 5500                                                                   | 24        | 2.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 1.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.71%   |
| Intel HD Graphics 620                                                                    | 18        | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.53%   |
| Intel HD Graphics 630                                                                    | 16        | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.26%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 1.17%   |
| AMD Lucienne                                                                             | 13        | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 6         | 0.54%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 0.54%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 6         | 0.54%   |
| Intel HD Graphics 530                                                                    | 6         | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.54%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 408       | 47.83%  |
| Intel + Nvidia | 167       | 19.58%  |
| 1 x AMD        | 132       | 15.47%  |
| 1 x Nvidia     | 72        | 8.44%   |
| Intel + AMD    | 44        | 5.16%   |
| AMD + Nvidia   | 16        | 1.88%   |
| 2 x AMD        | 8         | 0.94%   |
| Other          | 3         | 0.35%   |
| 2 x Nvidia     | 1         | 0.12%   |
| 1 x VIA        | 1         | 0.12%   |
| 1 x SiS        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 724       | 83.8%   |
| Proprietary | 120       | 13.89%  |
| Unknown     | 20        | 2.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 511       | 58.4%   |
| 0.01-0.5   | 123       | 14.06%  |
| 1.01-2.0   | 107       | 12.23%  |
| 0.51-1.0   | 64        | 7.31%   |
| 3.01-4.0   | 44        | 5.03%   |
| 7.01-8.0   | 11        | 1.26%   |
| 5.01-6.0   | 11        | 1.26%   |
| 2.01-3.0   | 4         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 220       | 22.56%  |
| LG Display              | 151       | 15.49%  |
| Samsung Electronics     | 112       | 11.49%  |
| Chimei Innolux          | 102       | 10.46%  |
| BOE                     | 88        | 9.03%   |
| Sharp                   | 31        | 3.18%   |
| Dell                    | 28        | 2.87%   |
| Chi Mei Optoelectronics | 28        | 2.87%   |
| Lenovo                  | 22        | 2.26%   |
| Apple                   | 21        | 2.15%   |
| Iiyama                  | 20        | 2.05%   |
| Hewlett-Packard         | 16        | 1.64%   |
| Goldstar                | 16        | 1.64%   |
| Philips                 | 14        | 1.44%   |
| LG Philips              | 9         | 0.92%   |
| PANDA                   | 8         | 0.82%   |
| BenQ                    | 8         | 0.82%   |
| AOC                     | 6         | 0.62%   |
| InfoVision              | 5         | 0.51%   |
| CSO                     | 5         | 0.51%   |
| Vestel Elektronik       | 4         | 0.41%   |
| Unknown                 | 4         | 0.41%   |
| Sony                    | 4         | 0.41%   |
| Seiko/Epson             | 4         | 0.41%   |
| Quanta Display          | 4         | 0.41%   |
| Panasonic               | 4         | 0.41%   |
| Medion                  | 4         | 0.41%   |
| ASUSTek Computer        | 4         | 0.41%   |
| Acer                    | 4         | 0.41%   |
| Valve                   | 2         | 0.21%   |
| HannStar                | 2         | 0.21%   |
| Arnos Instruments       | 2         | 0.21%   |
| Analogix                | 2         | 0.21%   |
| ___                     | 1         | 0.1%    |
| WST                     | 1         | 0.1%    |
| ViewSonic               | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |
| RGB                     | 1         | 0.1%    |
| Nvidia                  | 1         | 0.1%    |
| MS_ Nvidia              | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 16        | 1.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 14        | 1.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.91%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 8         | 0.81%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.7%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 7         | 0.7%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 6         | 0.6%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 6         | 0.6%    |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 6         | 0.6%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.5%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch      | 4         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 4         | 0.4%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 4         | 0.4%    |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 4         | 0.4%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                     | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 4         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 4         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 4         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch             | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 4         | 0.4%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 3         | 0.3%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch      | 3         | 0.3%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch               | 3         | 0.3%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 3         | 0.3%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 3         | 0.3%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 3         | 0.3%    |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch               | 3         | 0.3%    |
| LG Display LCD Monitor LGD01CA 1600x900 382x215mm 17.3-inch               | 3         | 0.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 3         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 374       | 40.79%  |
| 1366x768 (WXGA)    | 192       | 20.94%  |
| 1600x900 (HD+)     | 105       | 11.45%  |
| 3840x2160 (4K)     | 53        | 5.78%   |
| 2560x1440 (QHD)    | 37        | 4.03%   |
| 1280x800 (WXGA)    | 34        | 3.71%   |
| 1440x900 (WXGA+)   | 24        | 2.62%   |
| 1920x1200 (WUXGA)  | 13        | 1.42%   |
| 1680x1050 (WSXGA+) | 13        | 1.42%   |
| 2560x1600          | 7         | 0.76%   |
| 1280x1024 (SXGA)   | 7         | 0.76%   |
| 1024x600           | 6         | 0.65%   |
| 800x1280           | 5         | 0.55%   |
| 3200x1800 (QHD+)   | 5         | 0.55%   |
| Unknown            | 5         | 0.55%   |
| 3840x2400          | 4         | 0.44%   |
| 3440x1440          | 4         | 0.44%   |
| 1680x945           | 4         | 0.44%   |
| 1360x768           | 4         | 0.44%   |
| 2880x1800          | 3         | 0.33%   |
| 1024x768 (XGA)     | 3         | 0.33%   |
| 3840x1080          | 2         | 0.22%   |
| 7680x2160          | 1         | 0.11%   |
| 6320x1800          | 1         | 0.11%   |
| 3600x1080          | 1         | 0.11%   |
| 3200x1080          | 1         | 0.11%   |
| 2880x1920          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 2160x1440          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1920x515           | 1         | 0.11%   |
| 1920x1280          | 1         | 0.11%   |
| 1600x1200          | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |
| 1024x576           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 392       | 40.33%  |
| 17      | 136       | 13.99%  |
| 13      | 113       | 11.63%  |
| 14      | 78        | 8.02%   |
| 27      | 42        | 4.32%   |
| 24      | 40        | 4.12%   |
| Unknown | 31        | 3.19%   |
| 12      | 19        | 1.95%   |
| 23      | 18        | 1.85%   |
| 21      | 17        | 1.75%   |
| 18      | 14        | 1.44%   |
| 10      | 9         | 0.93%   |
| 11      | 8         | 0.82%   |
| 22      | 7         | 0.72%   |
| 16      | 6         | 0.62%   |
| 84      | 5         | 0.51%   |
| 25      | 5         | 0.51%   |
| 72      | 4         | 0.41%   |
| 34      | 4         | 0.41%   |
| 31      | 4         | 0.41%   |
| 20      | 4         | 0.41%   |
| 19      | 3         | 0.31%   |
| 54      | 2         | 0.21%   |
| 39      | 2         | 0.21%   |
| 32      | 2         | 0.21%   |
| 7       | 2         | 0.21%   |
| 65      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 40      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 500       | 51.81%  |
| 351-400     | 157       | 16.27%  |
| 201-300     | 109       | 11.3%   |
| 501-600     | 95        | 9.84%   |
| 401-500     | 38        | 3.94%   |
| Unknown     | 31        | 3.21%   |
| 601-700     | 10        | 1.04%   |
| 1501-2000   | 9         | 0.93%   |
| 701-800     | 6         | 0.62%   |
| 1001-1500   | 4         | 0.41%   |
| 801-900     | 3         | 0.31%   |
| 1-100       | 2         | 0.21%   |
| 901-1000    | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 699       | 83.21%  |
| 16/10   | 98        | 11.67%  |
| Unknown | 18        | 2.14%   |
| 5/4     | 7         | 0.83%   |
| 4/3     | 4         | 0.48%   |
| 3/2     | 4         | 0.48%   |
| 21/9    | 4         | 0.48%   |
| 0.62    | 3         | 0.36%   |
| 0.67    | 2         | 0.24%   |
| 3.73    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 392       | 40.62%  |
| 81-90          | 126       | 13.06%  |
| 121-130        | 116       | 12.02%  |
| 71-80          | 65        | 6.74%   |
| 201-250        | 62        | 6.42%   |
| 301-350        | 42        | 4.35%   |
| Unknown        | 31        | 3.21%   |
| 61-70          | 19        | 1.97%   |
| 131-140        | 19        | 1.97%   |
| 251-300        | 14        | 1.45%   |
| 151-200        | 14        | 1.45%   |
| More than 1000 | 13        | 1.35%   |
| 141-150        | 12        | 1.24%   |
| 351-500        | 11        | 1.14%   |
| 41-50          | 9         | 0.93%   |
| 51-60          | 8         | 0.83%   |
| 111-120        | 5         | 0.52%   |
| 501-1000       | 4         | 0.41%   |
| 1-40           | 2         | 0.21%   |
| 91-100         | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 360       | 38.14%  |
| 101-120       | 290       | 30.72%  |
| 51-100        | 148       | 15.68%  |
| 161-240       | 72        | 7.63%   |
| More than 240 | 34        | 3.6%    |
| Unknown       | 31        | 3.28%   |
| 1-50          | 9         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 683       | 78.24%  |
| 2     | 145       | 16.61%  |
| 0     | 27        | 3.09%   |
| 3     | 17        | 1.95%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 505       | 36.46%  |
| Realtek Semiconductor             | 422       | 30.47%  |
| Qualcomm Atheros                  | 193       | 13.94%  |
| Broadcom                          | 90        | 6.5%    |
| Broadcom Limited                  | 21        | 1.52%   |
| Marvell Technology Group          | 17        | 1.23%   |
| Ralink                            | 14        | 1.01%   |
| MediaTek                          | 14        | 1.01%   |
| TP-Link                           | 10        | 0.72%   |
| Dell                              | 10        | 0.72%   |
| Nvidia                            | 9         | 0.65%   |
| Ralink Technology                 | 7         | 0.51%   |
| Lenovo                            | 7         | 0.51%   |
| Ericsson Business Mobile Networks | 6         | 0.43%   |
| ASIX Electronics                  | 6         | 0.43%   |
| Sierra Wireless                   | 5         | 0.36%   |
| Hewlett-Packard                   | 4         | 0.29%   |
| DisplayLink                       | 4         | 0.29%   |
| D-Link System                     | 4         | 0.29%   |
| Qualcomm                          | 3         | 0.22%   |
| JMicron Technology                | 3         | 0.22%   |
| ASUSTek Computer                  | 3         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.14%   |
| Samsung Electronics               | 2         | 0.14%   |
| Motorola PCS                      | 2         | 0.14%   |
| Huawei Technologies               | 2         | 0.14%   |
| Fibocom                           | 2         | 0.14%   |
| Attansic Technology               | 2         | 0.14%   |
| ADMtek                            | 2         | 0.14%   |
| Z-Com                             | 1         | 0.07%   |
| Xiaomi                            | 1         | 0.07%   |
| VIA Technologies                  | 1         | 0.07%   |
| Shenzhen Goodix Technology        | 1         | 0.07%   |
| Seeed                             | 1         | 0.07%   |
| Panasonic (Matsushita)            | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| Microchip Technology              | 1         | 0.07%   |
| Edimax Technology                 | 1         | 0.07%   |
| D-Link                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 262       | 15.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69        | 4.05%   |
| Intel Wi-Fi 6 AX200                                               | 67        | 3.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 40        | 2.35%   |
| Intel Wireless 7260                                               | 39        | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 30        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 29        | 1.7%    |
| Intel Wireless 8260                                               | 27        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 25        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 1.47%   |
| Intel Wireless 7265                                               | 23        | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 22        | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 20        | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 20        | 1.17%   |
| Intel Wireless-AC 9260                                            | 18        | 1.06%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 17        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 1%      |
| Intel Ethernet Connection I218-LM                                 | 17        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 17        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 0.88%   |
| Intel WiFi Link 5100                                              | 15        | 0.88%   |
| Intel Centrino Wireless-N 2230                                    | 15        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 15        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 13        | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 11        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 11        | 0.65%   |
| Intel Centrino Advanced-N 6200                                    | 11        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 10        | 0.59%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 482       | 54.9%   |
| Qualcomm Atheros                      | 161       | 18.34%  |
| Realtek Semiconductor                 | 97        | 11.05%  |
| Broadcom                              | 60        | 6.83%   |
| Ralink                                | 14        | 1.59%   |
| Broadcom Limited                      | 14        | 1.59%   |
| MediaTek                              | 10        | 1.14%   |
| Ralink Technology                     | 7         | 0.8%    |
| TP-Link                               | 5         | 0.57%   |
| Sierra Wireless                       | 5         | 0.57%   |
| Dell                                  | 4         | 0.46%   |
| D-Link System                         | 4         | 0.46%   |
| Qualcomm                              | 3         | 0.34%   |
| ASUSTek Computer                      | 3         | 0.34%   |
| Fibocom                               | 2         | 0.23%   |
| Z-Com                                 | 1         | 0.11%   |
| Panasonic (Matsushita)                | 1         | 0.11%   |
| Microsoft                             | 1         | 0.11%   |
| Hewlett-Packard                       | 1         | 0.11%   |
| Edimax Technology                     | 1         | 0.11%   |
| D-Link                                | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 67        | 7.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 4.54%   |
| Intel Wireless 7260                                                     | 39        | 4.42%   |
| Intel Wireless 8265 / 8275                                              | 30        | 3.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 29        | 3.29%   |
| Intel Wireless 8260                                                     | 27        | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 2.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 2.83%   |
| Intel Wireless 7265                                                     | 23        | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 20        | 2.27%   |
| Intel Wireless-AC 9260                                                  | 18        | 2.04%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 1.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 17        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.7%    |
| Intel WiFi Link 5100                                                    | 15        | 1.7%    |
| Intel Centrino Wireless-N 2230                                          | 15        | 1.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 1.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 1.25%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 1.13%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.02%   |
| Intel Wireless 3160                                                     | 9         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.79%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.79%   |
| Intel Wireless 3165                                                     | 6         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 390       | 49.56%  |
| Intel                            | 210       | 26.68%  |
| Qualcomm Atheros                 | 66        | 8.39%   |
| Broadcom                         | 41        | 5.21%   |
| Marvell Technology Group         | 17        | 2.16%   |
| Nvidia                           | 9         | 1.14%   |
| Lenovo                           | 7         | 0.89%   |
| Broadcom Limited                 | 7         | 0.89%   |
| ASIX Electronics                 | 6         | 0.76%   |
| TP-Link                          | 4         | 0.51%   |
| MediaTek                         | 4         | 0.51%   |
| DisplayLink                      | 4         | 0.51%   |
| JMicron Technology               | 3         | 0.38%   |
| Hewlett-Packard                  | 3         | 0.38%   |
| Silicon Integrated Systems [SiS] | 2         | 0.25%   |
| Samsung Electronics              | 2         | 0.25%   |
| Motorola PCS                     | 2         | 0.25%   |
| Attansic Technology              | 2         | 0.25%   |
| ADMtek                           | 2         | 0.25%   |
| Xiaomi                           | 1         | 0.13%   |
| VIA Technologies                 | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| Huawei Technologies              | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 262       | 32.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69        | 8.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 6.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 4.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 2.13%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 2.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 1.63%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.63%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 1.38%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 1.38%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 1.25%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 1.25%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 1.13%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 1.13%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 1.13%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 1%      |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 7         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.63%   |
| Intel Ethernet Connection (13) I219-LM                            | 5         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.5%    |
| Lenovo ThinkPad Lan                                               | 4         | 0.5%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 4         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 839       | 51.92%  |
| Ethernet | 754       | 46.66%  |
| Modem    | 21        | 1.3%    |
| Unknown  | 2         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 678       | 72.9%   |
| Ethernet | 252       | 27.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 675       | 79.23%  |
| 1     | 153       | 17.96%  |
| 3     | 12        | 1.41%   |
| 0     | 11        | 1.29%   |
| 4     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 642       | 73.29%  |
| Yes  | 234       | 26.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 334       | 52.02%  |
| Realtek Semiconductor           | 54        | 8.41%   |
| Qualcomm Atheros Communications | 46        | 7.17%   |
| Broadcom                        | 36        | 5.61%   |
| IMC Networks                    | 27        | 4.21%   |
| Foxconn / Hon Hai               | 26        | 4.05%   |
| Dell                            | 25        | 3.89%   |
| Hewlett-Packard                 | 21        | 3.27%   |
| Apple                           | 20        | 3.12%   |
| Lite-On Technology              | 18        | 2.8%    |
| Toshiba                         | 10        | 1.56%   |
| Ralink                          | 5         | 0.78%   |
| Cambridge Silicon Radio         | 4         | 0.62%   |
| ASUSTek Computer                | 4         | 0.62%   |
| Alps Electric                   | 4         | 0.62%   |
| Foxconn International           | 3         | 0.47%   |
| Ralink Technology               | 2         | 0.31%   |
| Realtek                         | 1         | 0.16%   |
| Micro Star International        | 1         | 0.16%   |
| MediaTek                        | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 126       | 19.63%  |
| Intel AX200 Bluetooth                               | 66        | 10.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 49        | 7.63%   |
| Intel AX201 Bluetooth                               | 39        | 6.07%   |
| Realtek Bluetooth Radio                             | 33        | 5.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 3.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 2.65%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 2.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 1.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 12        | 1.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.71%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.71%   |
| IMC Networks Bluetooth Device                       | 10        | 1.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.56%   |
| Dell DW375 Bluetooth Module                         | 10        | 1.56%   |
| Apple Bluetooth Host Controller                     | 10        | 1.56%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.4%    |
| Broadcom HP Portable SoftSailing                    | 9         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 1.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 1.09%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 1.09%   |
| Intel Bluetooth Device                              | 6         | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.93%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.78%   |
| Intel AX210 Bluetooth                               | 5         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.78%   |
| Lite-On Bluetooth Device                            | 4         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.62%   |
| Toshiba Bluetooth Device                            | 3         | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 3         | 0.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.47%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 0.47%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 704       | 65.55%  |
| AMD                                  | 158       | 14.71%  |
| Nvidia                               | 138       | 12.85%  |
| Realtek Semiconductor                | 10        | 0.93%   |
| C-Media Electronics                  | 10        | 0.93%   |
| GN Netcom                            | 7         | 0.65%   |
| Logitech                             | 6         | 0.56%   |
| Plantronics                          | 4         | 0.37%   |
| Hewlett-Packard                      | 4         | 0.37%   |
| Corsair                              | 3         | 0.28%   |
| Texas Instruments                    | 2         | 0.19%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.19%   |
| Roland                               | 2         | 0.19%   |
| Razer USA                            | 2         | 0.19%   |
| Lenovo                               | 2         | 0.19%   |
| VIA Technologies                     | 1         | 0.09%   |
| Unknown (ABC)                        | 1         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.09%   |
| SteelSeries ApS                      | 1         | 0.09%   |
| Sennheiser Communications            | 1         | 0.09%   |
| Samson Technologies                  | 1         | 0.09%   |
| RODE Microphones                     | 1         | 0.09%   |
| QinHeng Electronics                  | 1         | 0.09%   |
| Pioneer DJ                           | 1         | 0.09%   |
| Pioneer                              | 1         | 0.09%   |
| OPPO Electronics                     | 1         | 0.09%   |
| M-Audio                              | 1         | 0.09%   |
| Kingston Technology                  | 1         | 0.09%   |
| Guillemot                            | 1         | 0.09%   |
| Bose                                 | 1         | 0.09%   |
| Audio-Technica                       | 1         | 0.09%   |
| ASUSTek Computer                     | 1         | 0.09%   |
| Apple                                | 1         | 0.09%   |
| Alesis                               | 1         | 0.09%   |
| AKAI                                 | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 92        | 7.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 91        | 7.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 75        | 5.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 65        | 5.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 47        | 3.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 46        | 3.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 40        | 3.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 40        | 3.13%   |
| Intel 8 Series HD Audio Controller                                                                | 40        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 38        | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 34        | 2.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 2.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 29        | 2.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 2.03%   |
| Intel Broadwell-U Audio Controller                                                                | 26        | 2.03%   |
| AMD FCH Azalia Controller                                                                         | 25        | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 1.64%   |
| Intel CM238 HD Audio Controller                                                                   | 21        | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 20        | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 13        | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.86%   |
| Realtek Semiconductor USB Audio                                                                   | 10        | 0.78%   |
| AMD Wrestler HDMI Audio                                                                           | 10        | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 8         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 0.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 151       | 30.14%  |
| SK hynix            | 123       | 24.55%  |
| Micron Technology   | 62        | 12.38%  |
| Kingston            | 50        | 9.98%   |
| Unknown             | 28        | 5.59%   |
| Crucial             | 22        | 4.39%   |
| Elpida              | 17        | 3.39%   |
| Corsair             | 11        | 2.2%    |
| Ramaxel Technology  | 8         | 1.6%    |
| Nanya Technology    | 8         | 1.6%    |
| A-DATA Technology   | 8         | 1.6%    |
| Unknown (ABCD)      | 3         | 0.6%    |
| Unknown (09D5)      | 1         | 0.2%    |
| Unifosa             | 1         | 0.2%    |
| TRS STAR            | 1         | 0.2%    |
| Transcend           | 1         | 0.2%    |
| Timetec             | 1         | 0.2%    |
| Team                | 1         | 0.2%    |
| Patriot             | 1         | 0.2%    |
| Goodram             | 1         | 0.2%    |
| G.Skill             | 1         | 0.2%    |
| A-DA                | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 2.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 7         | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 7         | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.3%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.3%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.11%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.93%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.93%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.93%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.74%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.74%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.74%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 4         | 0.74%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 3         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 3         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.56%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 3         | 0.56%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.56%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 215       | 47.99%  |
| DDR3    | 164       | 36.61%  |
| DDR2    | 23        | 5.13%   |
| LPDDR3  | 19        | 4.24%   |
| SDRAM   | 13        | 2.9%    |
| LPDDR4  | 12        | 2.68%   |
| DDR5    | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 405       | 92.05%  |
| Row Of Chips | 29        | 6.59%   |
| Chip         | 4         | 0.91%   |
| DIMM         | 2         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 176       | 36.9%   |
| 4096  | 143       | 29.98%  |
| 16384 | 87        | 18.24%  |
| 2048  | 53        | 11.11%  |
| 1024  | 10        | 2.1%    |
| 32768 | 8         | 1.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 109       | 22.9%   |
| 2667    | 98        | 20.59%  |
| 3200    | 81        | 17.02%  |
| 2400    | 39        | 8.19%   |
| 2133    | 33        | 6.93%   |
| 1334    | 24        | 5.04%   |
| 1333    | 19        | 3.99%   |
| 667     | 13        | 2.73%   |
| 1067    | 10        | 2.1%    |
| Unknown | 10        | 2.1%    |
| 2048    | 8         | 1.68%   |
| 800     | 5         | 1.05%   |
| 4267    | 4         | 0.84%   |
| 3266    | 4         | 0.84%   |
| 1867    | 4         | 0.84%   |
| 975     | 4         | 0.84%   |
| 4800    | 3         | 0.63%   |
| 4199    | 3         | 0.63%   |
| 8400    | 2         | 0.42%   |
| 4266    | 1         | 0.21%   |
| 3000    | 1         | 0.21%   |
| 1066    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-472x Series       | 1         | 20%     |
| Samsung ML-1660 Series        | 1         | 20%     |
| Prolific PL2305 Parallel Port | 1         | 20%     |
| HP Deskjet F4500 series       | 1         | 20%     |
| Canon TS5100 series           | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 40%     |
| Canon           | 2         | 40%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 20%     |
| Seiko Epson GT-X750 [Perfection 4490 Photo]      | 1         | 20%     |
| HP scanjet 8270                                  | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20               | 1         | 20%     |
| Canon CanoScan 3200F                             | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 198       | 26.72%  |
| Microdia                               | 85        | 11.47%  |
| Realtek Semiconductor                  | 70        | 9.45%   |
| IMC Networks                           | 60        | 8.1%    |
| Acer                                   | 54        | 7.29%   |
| Sunplus Innovation Technology          | 39        | 5.26%   |
| Suyin                                  | 33        | 4.45%   |
| Lite-On Technology                     | 31        | 4.18%   |
| Quanta                                 | 30        | 4.05%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.51%   |
| Syntek                                 | 22        | 2.97%   |
| Apple                                  | 15        | 2.02%   |
| Ricoh                                  | 13        | 1.75%   |
| Alcor Micro                            | 12        | 1.62%   |
| Luxvisions Innotech Limited            | 7         | 0.94%   |
| Logitech                               | 6         | 0.81%   |
| Silicon Motion                         | 5         | 0.67%   |
| Samsung Electronics                    | 5         | 0.67%   |
| Primax Electronics                     | 4         | 0.54%   |
| Z-Star Microelectronics                | 3         | 0.4%    |
| Lenovo                                 | 3         | 0.4%    |
| Importek                               | 3         | 0.4%    |
| ALi                                    | 3         | 0.4%    |
| DJJHFA1BIF5595                         | 2         | 0.27%   |
| Trust                                  | 1         | 0.13%   |
| SunplusIT                              | 1         | 0.13%   |
| STEREOLABS                             | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| Panasonic (Matsushita)                 | 1         | 0.13%   |
| Mustek Systems                         | 1         | 0.13%   |
| HD 2MP WEBCAM                          | 1         | 0.13%   |
| Genesys Logic                          | 1         | 0.13%   |
| Foxconn / Hon Hai                      | 1         | 0.13%   |
| Cubeternet                             | 1         | 0.13%   |
| Creative Technology                    | 1         | 0.13%   |
| Allwinner Technology                   | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 32        | 4.3%    |
| Realtek Integrated_Webcam_HD             | 30        | 4.03%   |
| IMC Networks Integrated Camera           | 24        | 3.22%   |
| Chicony Integrated Camera                | 23        | 3.09%   |
| Chicony HD Webcam                        | 17        | 2.28%   |
| Microdia Integrated Webcam               | 16        | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam        | 13        | 1.74%   |
| Syntek Integrated Camera                 | 12        | 1.61%   |
| Chicony USB2.0 Camera                    | 12        | 1.61%   |
| Chicony HP HD Webcam                     | 12        | 1.61%   |
| Acer Integrated Camera                   | 12        | 1.61%   |
| Realtek USB Camera                       | 11        | 1.48%   |
| Lite-On HP HD Camera                     | 11        | 1.48%   |
| Lite-On Integrated Camera                | 9         | 1.21%   |
| Chicony HP HD Camera                     | 9         | 1.21%   |
| Sunplus HD WebCam                        | 8         | 1.07%   |
| Quanta HP HD Camera                      | 8         | 1.07%   |
| Chicony USB2.0 HD UVC WebCam             | 8         | 1.07%   |
| Chicony TOSHIBA Web Camera - HD          | 8         | 1.07%   |
| Chicony Integrated Camera (1280x720@30)  | 8         | 1.07%   |
| Acer BisonCam,NB Pro                     | 7         | 0.94%   |
| Acer BisonCam, NB Pro                    | 7         | 0.94%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 6         | 0.81%   |
| Microdia Laptop_Integrated_Webcam_2M     | 6         | 0.81%   |
| Lite-On HP HD Webcam                     | 6         | 0.81%   |
| Chicony USB 2.0 Camera                   | 6         | 0.81%   |
| Chicony Integrated HP HD Webcam          | 6         | 0.81%   |
| Chicony HP Wide Vision HD Camera         | 6         | 0.81%   |
| Acer HD Webcam                           | 6         | 0.81%   |
| Sunplus Integrated_Webcam_HD             | 5         | 0.67%   |
| Sunplus Asus Webcam                      | 5         | 0.67%   |
| Samsung Galaxy A5 (MTP)                  | 5         | 0.67%   |
| Realtek USB2.0 VGA UVC WebCam            | 5         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam             | 5         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD     | 5         | 0.67%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 5         | 0.67%   |
| Chicony WebCam                           | 5         | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam            | 5         | 0.67%   |
| Chicony HP Truevision HD camera          | 5         | 0.67%   |
| Chicony EasyCamera                       | 5         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 68        | 39.08%  |
| Synaptics                  | 53        | 30.46%  |
| Shenzhen Goodix Technology | 16        | 9.2%    |
| AuthenTec                  | 14        | 8.05%   |
| LighTuning Technology      | 9         | 5.17%   |
| STMicroelectronics         | 6         | 3.45%   |
| Upek                       | 5         | 2.87%   |
| Elan Microelectronics      | 3         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 14.94%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 9.77%   |
| Unknown                                                                    | 11        | 6.32%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 5.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 4.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 3.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.45%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.87%   |
| Validity Sensors VFS491                                                    | 4         | 2.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.3%    |
| AuthenTec AES2810                                                          | 4         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.72%   |
| Synaptics WBDI Device                                                      | 3         | 1.72%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.72%   |
| AuthenTec AES1600                                                          | 3         | 1.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.15%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.15%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.15%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.15%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.15%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.15%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.57%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.57%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.57%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 51        | 39.23%  |
| Alcor Micro                       | 41        | 31.54%  |
| O2 Micro                          | 13        | 10%     |
| Lenovo                            | 9         | 6.92%   |
| VASCO Data Security International | 4         | 3.08%   |
| OmniKey                           | 3         | 2.31%   |
| Upek                              | 2         | 1.54%   |
| Realtek Semiconductor             | 2         | 1.54%   |
| SCM Microsystems                  | 1         | 0.77%   |
| Integrated Technology Express     | 1         | 0.77%   |
| Gemalto (was Gemplus)             | 1         | 0.77%   |
| Clay Logic                        | 1         | 0.77%   |
| Advanced Card Systems             | 1         | 0.77%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 31.54%  |
| Broadcom 58200                                                               | 16        | 12.31%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 11.54%  |
| Broadcom 5880                                                                | 12        | 9.23%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 6.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 6.15%   |
| VASCO Data Security International DIGIPASS 870                               | 3         | 2.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 2.31%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.54%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.54%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.54%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.77%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.77%   |
| OmniKey CardMan 4321                                                         | 1         | 0.77%   |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.77%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.77%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.77%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.77%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 501       | 56.87%  |
| 1     | 303       | 34.39%  |
| 2     | 62        | 7.04%   |
| 3     | 12        | 1.36%   |
| 4     | 2         | 0.23%   |
| 6     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 170       | 38.12%  |
| Chipcard                 | 91        | 20.4%   |
| Graphics card            | 69        | 15.47%  |
| Net/wireless             | 34        | 7.62%   |
| Multimedia controller    | 19        | 4.26%   |
| Storage                  | 11        | 2.47%   |
| Camera                   | 10        | 2.24%   |
| Card reader              | 9         | 2.02%   |
| Bluetooth                | 8         | 1.79%   |
| Communication controller | 7         | 1.57%   |
| Net/ethernet             | 6         | 1.35%   |
| Flash memory             | 4         | 0.9%    |
| Modem                    | 3         | 0.67%   |
| Sound                    | 2         | 0.45%   |
| Network                  | 2         | 0.45%   |
| Storage/ide              | 1         | 0.22%   |

