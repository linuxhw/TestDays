Linux in Belarus - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

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

Total: 1170

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15s-eq2xxx           | [32e408088d](https://linux-hardware.org/?probe=32e408088d) | May 07, 2024 |
| Lenovo        | ThinkPad X395 20NMS0D900    | [47098170bb](https://linux-hardware.org/?probe=47098170bb) | May 01, 2024 |
| HP            | ProBook 4535s               | [34910d04e7](https://linux-hardware.org/?probe=34910d04e7) | Apr 28, 2024 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [714f84cadb](https://linux-hardware.org/?probe=714f84cadb) | Apr 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [8c81adc916](https://linux-hardware.org/?probe=8c81adc916) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [bc0e0ae6b8](https://linux-hardware.org/?probe=bc0e0ae6b8) | Apr 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10a878e186](https://linux-hardware.org/?probe=10a878e186) | Apr 25, 2024 |
| Lenovo        | XiaoXinPro 16 AHP9 83D5     | [bec1c58cef](https://linux-hardware.org/?probe=bec1c58cef) | Apr 25, 2024 |
| TECNO         | MEGABOOK T1                 | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Lenovo        | Legion R7000P APH8 82Y9     | [a3f2909959](https://linux-hardware.org/?probe=a3f2909959) | Apr 22, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [9a0c435db3](https://linux-hardware.org/?probe=9a0c435db3) | Apr 12, 2024 |
| HP            | Laptop 15s-eq2xxx           | [f73b16ab18](https://linux-hardware.org/?probe=f73b16ab18) | Apr 11, 2024 |
| ASUSTek       | K55VM                       | [9293006922](https://linux-hardware.org/?probe=9293006922) | Apr 09, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [2500fb4398](https://linux-hardware.org/?probe=2500fb4398) | Apr 09, 2024 |
| Toshiba       | Satellite C850-C5K          | [81be04c868](https://linux-hardware.org/?probe=81be04c868) | Apr 09, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [eadddcdc8e](https://linux-hardware.org/?probe=eadddcdc8e) | Apr 06, 2024 |
| ASUSTek       | K55VM                       | [dff985be75](https://linux-hardware.org/?probe=dff985be75) | Apr 05, 2024 |
| HP            | Laptop 15s-eq2xxx           | [871311fcdc](https://linux-hardware.org/?probe=871311fcdc) | Apr 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | [6d0d8895f9](https://linux-hardware.org/?probe=6d0d8895f9) | Apr 02, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [a42873dcf9](https://linux-hardware.org/?probe=a42873dcf9) | Apr 01, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [953610ee17](https://linux-hardware.org/?probe=953610ee17) | Mar 28, 2024 |
| ASUSTek       | X553MA                      | [5d1d7ed87a](https://linux-hardware.org/?probe=5d1d7ed87a) | Mar 28, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | [90ff22d8c1](https://linux-hardware.org/?probe=90ff22d8c1) | Mar 25, 2024 |
| HONOR         | BMH-WDX9                    | [4445879c66](https://linux-hardware.org/?probe=4445879c66) | Mar 21, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [90a25e637e](https://linux-hardware.org/?probe=90a25e637e) | Mar 21, 2024 |
| HONOR         | BMH-WDX9                    | [01284be05a](https://linux-hardware.org/?probe=01284be05a) | Mar 20, 2024 |
| HP            | 650                         | [8968085c5a](https://linux-hardware.org/?probe=8968085c5a) | Mar 13, 2024 |
| HP            | Laptop 17-ak0xx             | [a5d4f19046](https://linux-hardware.org/?probe=a5d4f19046) | Mar 12, 2024 |
| HP            | ProBook 650 G2              | [c99a1426a1](https://linux-hardware.org/?probe=c99a1426a1) | Mar 07, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [cda628788e](https://linux-hardware.org/?probe=cda628788e) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [08024a8cef](https://linux-hardware.org/?probe=08024a8cef) | Mar 01, 2024 |
| HP            | Pavilion Power Laptop 15... | [43919c6c44](https://linux-hardware.org/?probe=43919c6c44) | Feb 29, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [19c9cc81e5](https://linux-hardware.org/?probe=19c9cc81e5) | Feb 26, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0fa9131028](https://linux-hardware.org/?probe=0fa9131028) | Feb 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [367494d4cf](https://linux-hardware.org/?probe=367494d4cf) | Feb 24, 2024 |
| Sony          | SVF1521L1RB                 | [4b0e081c62](https://linux-hardware.org/?probe=4b0e081c62) | Feb 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [3514879254](https://linux-hardware.org/?probe=3514879254) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [37b9530a2a](https://linux-hardware.org/?probe=37b9530a2a) | Feb 22, 2024 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [4aa25676bc](https://linux-hardware.org/?probe=4aa25676bc) | Feb 22, 2024 |
| HONOR         | NBR-WAX9                    | [6fa625a010](https://linux-hardware.org/?probe=6fa625a010) | Feb 21, 2024 |
| Lenovo        | G50-30 80G0                 | [16a4080794](https://linux-hardware.org/?probe=16a4080794) | Feb 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [cdd51cbb3d](https://linux-hardware.org/?probe=cdd51cbb3d) | Feb 16, 2024 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [c98ffdb659](https://linux-hardware.org/?probe=c98ffdb659) | Feb 16, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [2f303b1ad2](https://linux-hardware.org/?probe=2f303b1ad2) | Feb 15, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [2d39984c89](https://linux-hardware.org/?probe=2d39984c89) | Feb 14, 2024 |
| MSI           | Katana GF66 11UD            | [2adf0be9f1](https://linux-hardware.org/?probe=2adf0be9f1) | Feb 12, 2024 |
| MSI           | Katana GF66 11UD            | [062c0b91a4](https://linux-hardware.org/?probe=062c0b91a4) | Feb 12, 2024 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [9b3e403b41](https://linux-hardware.org/?probe=9b3e403b41) | Feb 11, 2024 |
| HP            | Laptop 15s-eq2xxx           | [1e1676f874](https://linux-hardware.org/?probe=1e1676f874) | Feb 09, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [20aea10762](https://linux-hardware.org/?probe=20aea10762) | Feb 08, 2024 |
| HONOR         | HYM-WXX                     | [35503217de](https://linux-hardware.org/?probe=35503217de) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [d731c8db9a](https://linux-hardware.org/?probe=d731c8db9a) | Feb 04, 2024 |
| Timi          | Redmi Book Pro 15 2022      | [fddf157b5f](https://linux-hardware.org/?probe=fddf157b5f) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [bc89935fa2](https://linux-hardware.org/?probe=bc89935fa2) | Jan 29, 2024 |
| Apple         | MacBookPro15,1              | [12fb54aa81](https://linux-hardware.org/?probe=12fb54aa81) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e78406b431](https://linux-hardware.org/?probe=e78406b431) | Jan 28, 2024 |
| Unknown       | Unknown                     | [5c676b44c6](https://linux-hardware.org/?probe=5c676b44c6) | Jan 27, 2024 |
| Unknown       | Unknown                     | [52522836b8](https://linux-hardware.org/?probe=52522836b8) | Jan 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [7423289dfa](https://linux-hardware.org/?probe=7423289dfa) | Jan 26, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | [a0b0aa335e](https://linux-hardware.org/?probe=a0b0aa335e) | Jan 25, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | [2add8788ab](https://linux-hardware.org/?probe=2add8788ab) | Jan 25, 2024 |
| Toshiba       | Satellite C850-C5K          | [11b9b2c55a](https://linux-hardware.org/?probe=11b9b2c55a) | Jan 22, 2024 |
| HONOR         | BMH-WDX9                    | [cc5193ad6b](https://linux-hardware.org/?probe=cc5193ad6b) | Jan 20, 2024 |
| HONOR         | BMH-WDX9                    | [a244cafad7](https://linux-hardware.org/?probe=a244cafad7) | Jan 20, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [f3ba35a8ef](https://linux-hardware.org/?probe=f3ba35a8ef) | Jan 19, 2024 |
| ASUSTek       | X541UJ                      | [106a1e0cd4](https://linux-hardware.org/?probe=106a1e0cd4) | Jan 17, 2024 |
| Acer          | Extensa 215-55              | [395b2c99b5](https://linux-hardware.org/?probe=395b2c99b5) | Jan 17, 2024 |
| HONOR         | BMH-WDX9                    | [e793aff68b](https://linux-hardware.org/?probe=e793aff68b) | Jan 16, 2024 |
| HP            | Laptop 15s-eq2xxx           | [376c519812](https://linux-hardware.org/?probe=376c519812) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [13523b8324](https://linux-hardware.org/?probe=13523b8324) | Jan 07, 2024 |
| Toshiba       | Satellite C850-C5K          | [55c4519a60](https://linux-hardware.org/?probe=55c4519a60) | Jan 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [8ade7f9a3b](https://linux-hardware.org/?probe=8ade7f9a3b) | Jan 04, 2024 |
| Apple         | MacBookPro8,2               | [34fcef3266](https://linux-hardware.org/?probe=34fcef3266) | Dec 31, 2023 |
| HP            | ProBook 6460b               | [45038d4599](https://linux-hardware.org/?probe=45038d4599) | Dec 30, 2023 |
| HP            | Victus by Gaming Laptop ... | [d82dad2793](https://linux-hardware.org/?probe=d82dad2793) | Dec 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [a4d9a001ff](https://linux-hardware.org/?probe=a4d9a001ff) | Dec 29, 2023 |
| Apple         | MacBookPro8,2               | [a353ad122c](https://linux-hardware.org/?probe=a353ad122c) | Dec 28, 2023 |
| HP            | ProBook 6460b               | [4a6a6b9b9d](https://linux-hardware.org/?probe=4a6a6b9b9d) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ef5699b685](https://linux-hardware.org/?probe=ef5699b685) | Dec 24, 2023 |
| Dell          | System XPS L702X            | [d69355a342](https://linux-hardware.org/?probe=d69355a342) | Dec 23, 2023 |
| ASUSTek       | X541UJ                      | [4aeb75b734](https://linux-hardware.org/?probe=4aeb75b734) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [812cd1effd](https://linux-hardware.org/?probe=812cd1effd) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| ASUSTek       | X550VB                      | [cfc8172838](https://linux-hardware.org/?probe=cfc8172838) | Dec 11, 2023 |
| HP            | ProBook 4535s               | [9005c587a8](https://linux-hardware.org/?probe=9005c587a8) | Dec 10, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| HONOR         | HYM-WXX                     | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [f87c61387d](https://linux-hardware.org/?probe=f87c61387d) | Dec 06, 2023 |
| ASUSTek       | X550VC                      | [376ffad1f1](https://linux-hardware.org/?probe=376ffad1f1) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L7001SM... | [da99e083aa](https://linux-hardware.org/?probe=da99e083aa) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [deba3c2073](https://linux-hardware.org/?probe=deba3c2073) | Nov 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [184a3ca616](https://linux-hardware.org/?probe=184a3ca616) | Nov 28, 2023 |
| HP            | ProBook 6460b               | [d489496b9f](https://linux-hardware.org/?probe=d489496b9f) | Nov 26, 2023 |
| Unknown       | Unknown                     | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1bb4c56d2b](https://linux-hardware.org/?probe=1bb4c56d2b) | Nov 24, 2023 |
| HP            | ProBook 6460b               | [0d13c42c84](https://linux-hardware.org/?probe=0d13c42c84) | Nov 21, 2023 |
| Valve         | Jupiter                     | [93c68a0d33](https://linux-hardware.org/?probe=93c68a0d33) | Nov 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [743037d313](https://linux-hardware.org/?probe=743037d313) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cd775f0d29](https://linux-hardware.org/?probe=cd775f0d29) | Nov 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6461e4f7af](https://linux-hardware.org/?probe=6461e4f7af) | Nov 16, 2023 |
| HP            | ProBook 6460b               | [b0795caa4c](https://linux-hardware.org/?probe=b0795caa4c) | Nov 15, 2023 |
| HP            | ProBook 6570b               | [06cd45bab5](https://linux-hardware.org/?probe=06cd45bab5) | Nov 15, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [4d8ebb0232](https://linux-hardware.org/?probe=4d8ebb0232) | Nov 13, 2023 |
| HONOR         | NBR-WAX9                    | [c648b2a80e](https://linux-hardware.org/?probe=c648b2a80e) | Nov 13, 2023 |
| Chuwi         | GemiBook                    | [5fb8105768](https://linux-hardware.org/?probe=5fb8105768) | Nov 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [265d52a042](https://linux-hardware.org/?probe=265d52a042) | Oct 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [ee5373bbe1](https://linux-hardware.org/?probe=ee5373bbe1) | Oct 28, 2023 |
| Haier         | U1520SD                     | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Haier         | U1520SD                     | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Gigabyte      | AERO 17 XE5                 | [47d1cb500e](https://linux-hardware.org/?probe=47d1cb500e) | Oct 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA            | [f321493adb](https://linux-hardware.org/?probe=f321493adb) | Oct 25, 2023 |
| Timi          | TM1701                      | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [bd850cfed3](https://linux-hardware.org/?probe=bd850cfed3) | Oct 24, 2023 |
| Dell          | Latitude D830               | [53cbc541d2](https://linux-hardware.org/?probe=53cbc541d2) | Oct 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | [36c49585ba](https://linux-hardware.org/?probe=36c49585ba) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [cf096a11b6](https://linux-hardware.org/?probe=cf096a11b6) | Oct 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [908a750a93](https://linux-hardware.org/?probe=908a750a93) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [10b2d6465f](https://linux-hardware.org/?probe=10b2d6465f) | Oct 10, 2023 |
| HP            | ProBook 450 G7              | [01bfe733f2](https://linux-hardware.org/?probe=01bfe733f2) | Oct 10, 2023 |
| HP            | 650                         | [1339361633](https://linux-hardware.org/?probe=1339361633) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [76449d7977](https://linux-hardware.org/?probe=76449d7977) | Oct 06, 2023 |
| HP            | EliteBook 1050 G1           | [d5d3dd5136](https://linux-hardware.org/?probe=d5d3dd5136) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [46e4809bfe](https://linux-hardware.org/?probe=46e4809bfe) | Oct 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [db7fa034a7](https://linux-hardware.org/?probe=db7fa034a7) | Oct 03, 2023 |
| HP            | 650                         | [f652e189f9](https://linux-hardware.org/?probe=f652e189f9) | Oct 03, 2023 |
| HP            | Compaq 610                  | [9570db13af](https://linux-hardware.org/?probe=9570db13af) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| ASUSTek       | K72Dr                       | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| ASUSTek       | X502CA                      | [8d0117a5f3](https://linux-hardware.org/?probe=8d0117a5f3) | Sep 13, 2023 |
| Lenovo        | Z70-80 80FG                 | [f588051436](https://linux-hardware.org/?probe=f588051436) | Sep 11, 2023 |
| MSI           | Stealth GS77 12UGS          | [c83c0f03aa](https://linux-hardware.org/?probe=c83c0f03aa) | Sep 11, 2023 |
| Dell          | Latitude 3410               | [8717619604](https://linux-hardware.org/?probe=8717619604) | Sep 11, 2023 |
| Dell          | Latitude 3410               | [c1c98adb51](https://linux-hardware.org/?probe=c1c98adb51) | Sep 10, 2023 |
| HP            | ProBook 470 G3              | [f096164a16](https://linux-hardware.org/?probe=f096164a16) | Sep 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| Acer          | Aspire V5-531               | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [63fd300645](https://linux-hardware.org/?probe=63fd300645) | Sep 07, 2023 |
| Dell          | Inspiron 3542               | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| ASUSTek       | X502CA                      | [d630819b59](https://linux-hardware.org/?probe=d630819b59) | Sep 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e04761c470](https://linux-hardware.org/?probe=e04761c470) | Sep 03, 2023 |
| HP            | ProBook 470 G3              | [f6996b2905](https://linux-hardware.org/?probe=f6996b2905) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [4e753f77c7](https://linux-hardware.org/?probe=4e753f77c7) | Sep 01, 2023 |
| ASUSTek       | X502CA                      | [04492867e2](https://linux-hardware.org/?probe=04492867e2) | Aug 31, 2023 |
| HP            | Laptop 15s-eq2xxx           | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [dd9b3b469e](https://linux-hardware.org/?probe=dd9b3b469e) | Aug 15, 2023 |
| HUAWEI        | HLYL-WXX9                   | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HONOR         | HYM-WXX                     | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| HUAWEI        | KPRC-WX0                    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| HP            | ProBook 450 G5              | [0482630783](https://linux-hardware.org/?probe=0482630783) | Aug 05, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| ASUSTek       | GL503VD                     | [4c3516813b](https://linux-hardware.org/?probe=4c3516813b) | Jul 28, 2023 |
| ASUSTek       | X550CC                      | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| HP            | ProBook 4545s               | [cf43675118](https://linux-hardware.org/?probe=cf43675118) | Jul 20, 2023 |
| Unknown       | Unknown                     | [7e6c1d1018](https://linux-hardware.org/?probe=7e6c1d1018) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| HP            | 255 G8 Notebook PC          | [584f2a2ac4](https://linux-hardware.org/?probe=584f2a2ac4) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Valve         | Jupiter                     | [dfb0bd07f1](https://linux-hardware.org/?probe=dfb0bd07f1) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [d33df8d1a0](https://linux-hardware.org/?probe=d33df8d1a0) | Jul 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| HP            | EliteBook 840 G1            | [37239831de](https://linux-hardware.org/?probe=37239831de) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| HP            | 255 G1                      | [f09174c096](https://linux-hardware.org/?probe=f09174c096) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| ASUSTek       | X551CAP                     | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Sony          | SVF1521L1RB                 | [b0dfbb64d0](https://linux-hardware.org/?probe=b0dfbb64d0) | Jun 17, 2023 |
| Dell          | Inspiron 15-3573            | [129574e8dc](https://linux-hardware.org/?probe=129574e8dc) | Jun 14, 2023 |
| HP            | 255 G1                      | [a8c4597ccd](https://linux-hardware.org/?probe=a8c4597ccd) | Jun 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e23f3e627](https://linux-hardware.org/?probe=1e23f3e627) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| HP            | 255 G8 Notebook PC          | [eb644c96f3](https://linux-hardware.org/?probe=eb644c96f3) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| MSI           | GE72 7RE                    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [fe4b074a5c](https://linux-hardware.org/?probe=fe4b074a5c) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Acer          | Swift SF114-32              | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Samsung       | R59P/R60P/R61P              | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [50c44b15eb](https://linux-hardware.org/?probe=50c44b15eb) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [9cb44b75f5](https://linux-hardware.org/?probe=9cb44b75f5) | Apr 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | [f87a34e474](https://linux-hardware.org/?probe=f87a34e474) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | [9cacd6f238](https://linux-hardware.org/?probe=9cacd6f238) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| ASUSTek       | X75VCP                      | [a02f8565dd](https://linux-hardware.org/?probe=a02f8565dd) | Apr 14, 2023 |
| ASUSTek       | X75VCP                      | [5ecb1bb650](https://linux-hardware.org/?probe=5ecb1bb650) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Dell          | Inspiron 15-3552            | [5c23d1d7f7](https://linux-hardware.org/?probe=5c23d1d7f7) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | [be2a3d30f2](https://linux-hardware.org/?probe=be2a3d30f2) | Apr 08, 2023 |
| Apple         | MacBookAir4,2               | [6dafdf20a5](https://linux-hardware.org/?probe=6dafdf20a5) | Apr 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Toshiba       | Satellite C850-C5K          | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| Dell          | System XPS L702X            | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | Notebook                    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HP            | 250 G1                      | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| Lenovo        | 3000 G530 4151/200          | [4c0751aa89](https://linux-hardware.org/?probe=4c0751aa89) | Mar 26, 2023 |
| HP            | Pavilion dv7                | [6ae381093b](https://linux-hardware.org/?probe=6ae381093b) | Mar 26, 2023 |
| Getac         | B300-H                      | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| HP            | ProBook 450 G5              | [c4b7067187](https://linux-hardware.org/?probe=c4b7067187) | Mar 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| HP            | Pavilion dv6                | [43940eb778](https://linux-hardware.org/?probe=43940eb778) | Mar 20, 2023 |
| HP            | Pavilion dv7                | [d42628a0e9](https://linux-hardware.org/?probe=d42628a0e9) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| ASUSTek       | X555LB                      | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| HP            | Pavilion dv6                | [b5746d500d](https://linux-hardware.org/?probe=b5746d500d) | Mar 13, 2023 |
| Sony          | VPCEB3S1R                   | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Lenovo        | G50-70 20351                | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| HP            | Compaq 610                  | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| HP            | ProBook 450 G2              | [546d7b3f27](https://linux-hardware.org/?probe=546d7b3f27) | Mar 07, 2023 |
| Acer          | Aspire 5739G                | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| Dell          | Vostro 3500                 | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| Lenovo        | G550 20023                  | [e8325b5ff1](https://linux-hardware.org/?probe=e8325b5ff1) | Mar 03, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| Toshiba       | Satellite L300              | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c85bd630f0](https://linux-hardware.org/?probe=c85bd630f0) | Feb 25, 2023 |
| HP            | 250 G8 Notebook PC          | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Samsung       | RV413/RV513                 | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Dell          | Inspiron N5110              | [9b00bf7704](https://linux-hardware.org/?probe=9b00bf7704) | Feb 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [dc6a6f7872](https://linux-hardware.org/?probe=dc6a6f7872) | Feb 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [788044d53c](https://linux-hardware.org/?probe=788044d53c) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [faa600d8e5](https://linux-hardware.org/?probe=faa600d8e5) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [dfa8cae135](https://linux-hardware.org/?probe=dfa8cae135) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [44e18a0f72](https://linux-hardware.org/?probe=44e18a0f72) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| HP            | Compaq Presario CQ70        | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [a1549a7701](https://linux-hardware.org/?probe=a1549a7701) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f94175d8c](https://linux-hardware.org/?probe=6f94175d8c) | Jan 28, 2023 |
| Apple         | MacBookPro8,2               | [add8440e16](https://linux-hardware.org/?probe=add8440e16) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f4e06ff0b2](https://linux-hardware.org/?probe=f4e06ff0b2) | Jan 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Inspiron 15-3552            | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [7c116ff037](https://linux-hardware.org/?probe=7c116ff037) | Jan 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [4606ff1dab](https://linux-hardware.org/?probe=4606ff1dab) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| MSI           | Modern 15 A5M               | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [325952460c](https://linux-hardware.org/?probe=325952460c) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [ac63fca6cb](https://linux-hardware.org/?probe=ac63fca6cb) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [d196b92cff](https://linux-hardware.org/?probe=d196b92cff) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | [9f1751d2e5](https://linux-hardware.org/?probe=9f1751d2e5) | Dec 22, 2022 |
| Pegatron      | A17                         | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b463c25c4d](https://linux-hardware.org/?probe=b463c25c4d) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [1c80b48ea0](https://linux-hardware.org/?probe=1c80b48ea0) | Dec 11, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Dell          | Inspiron 5570               | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| HP            | Pavilion g6                 | [c3f0c49c7c](https://linux-hardware.org/?probe=c3f0c49c7c) | Dec 02, 2022 |
| HP            | Pavilion g6                 | [cb93839085](https://linux-hardware.org/?probe=cb93839085) | Dec 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [2de79b83d5](https://linux-hardware.org/?probe=2de79b83d5) | Nov 28, 2022 |
| ASUSTek       | K70AB                       | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Inspiron 3501               | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | G580 20150                  | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | UX31A                       | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [09c253d548](https://linux-hardware.org/?probe=09c253d548) | Nov 07, 2022 |
| Chuwi         | GemiBook                    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| Dell          | Inspiron 7577               | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| ASUSTek       | K501LB                      | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| Unknown       | Unknown                     | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| ASUSTek       | K501LB                      | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Compaq 610                  | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| HP            | Compaq 610                  | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| Dell          | Inspiron 7577               | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| Acer          | Aspire E1-531               | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Acer          | Aspire E1-531               | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | X751LD                      | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | T101MT                      | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| HP            | ProBook 450 G2              | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [a861ca9999](https://linux-hardware.org/?probe=a861ca9999) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Apple         | MacBookPro16,1              | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Toshiba       | Satellite C850-C5K          | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| HP            | Compaq 610                  | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Sony          | SVF1521L1RW                 | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Fujitsu       | AMILO Pi 3560               | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| Samsung       | 535U3C                      | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| HONOR         | NBR-WAX9                    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| Getac         | B300-H                      | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Getac         | B300-H                      | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| HP            | Pavilion 17                 | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| Dell          | XPS 13 9305                 | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| HP            | Mini 110-4100               | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| HP            | 635                         | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| Lenovo        | V580c 20160                 | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| HUAWEI        | HLYL-WXX9                   | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| HP            | Presario CQ57               | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| ASUSTek       | X550CA                      | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Dell          | G7 7700                     | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| ASUSTek       | X540UA                      | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| LG Electro... | R510                        | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| ASUSTek       | 1000HE                      | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| Acer          | Aspire 5750G                | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| HP            | ProBook 455 G1              | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASUSTek       | K53BR                       | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| Acer          | Aspire A515-44G             | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| HP            | Laptop 15s-eq2xxx           | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| HP            | ProBook 4515s               | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Samsung       | R508                        | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [11fce4275a](https://linux-hardware.org/?probe=11fce4275a) | Sep 01, 2021 |
| ASUSTek       | K53BR                       | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| Acer          | Extensa 2511G               | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| Samsung       | R59P/R60P/R61P              | [21914d4123](https://linux-hardware.org/?probe=21914d4123) | Aug 11, 2021 |
| HP            | ProBook 470 G0              | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | Z50-70 20354                | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EQS33800     | [2e1468bf31](https://linux-hardware.org/?probe=2e1468bf31) | Aug 02, 2021 |
| HP            | ProBook 450 G2              | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [c90b5a2e7d](https://linux-hardware.org/?probe=c90b5a2e7d) | Jul 28, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| HP            | Laptop 15-bs0xx             | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | [30dd6fa596](https://linux-hardware.org/?probe=30dd6fa596) | Jul 14, 2021 |
| Acer          | Nitro AN515-52              | [ce3b5ecb17](https://linux-hardware.org/?probe=ce3b5ecb17) | Jul 13, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| HP            | EliteBook 840 G2            | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| Samsung       | RV413/RV513                 | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Acer          | Aspire E5-572G              | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ec0c189e56](https://linux-hardware.org/?probe=ec0c189e56) | Jun 15, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Acer          | Aspire A515-51G             | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | Pavilion 15                 | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| HP            | Laptop 15-bs0xx             | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| HP            | Laptop 15-bs0xx             | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASUSTek       | X541UJ                      | [22f4d0228f](https://linux-hardware.org/?probe=22f4d0228f) | May 16, 2021 |
| Timi          | TM1703                      | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| Lenovo        | Z710 20250                  | [f3d7663214](https://linux-hardware.org/?probe=f3d7663214) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [06af60abdc](https://linux-hardware.org/?probe=06af60abdc) | May 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [b71c62e752](https://linux-hardware.org/?probe=b71c62e752) | May 09, 2021 |
| Lenovo        | Z50-70 20354                | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [46872b4b26](https://linux-hardware.org/?probe=46872b4b26) | May 02, 2021 |
| HP            | ProBook 4525s               | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| Acer          | Aspire A315-21              | [fb5b8d0021](https://linux-hardware.org/?probe=fb5b8d0021) | Apr 29, 2021 |
| Acer          | Aspire A315-21              | [7ec9efef18](https://linux-hardware.org/?probe=7ec9efef18) | Apr 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [3f2270faad](https://linux-hardware.org/?probe=3f2270faad) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [644dd10952](https://linux-hardware.org/?probe=644dd10952) | Apr 22, 2021 |
| HP            | ProBook 450 G7              | [1832412dab](https://linux-hardware.org/?probe=1832412dab) | Apr 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b60d916c33](https://linux-hardware.org/?probe=b60d916c33) | Apr 19, 2021 |
| Lenovo        | G580 20157                  | [1e11286470](https://linux-hardware.org/?probe=1e11286470) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | X541NA                      | [15bd22b48d](https://linux-hardware.org/?probe=15bd22b48d) | Apr 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ebd6174247](https://linux-hardware.org/?probe=ebd6174247) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [0362943e9e](https://linux-hardware.org/?probe=0362943e9e) | Apr 02, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [3228126df8](https://linux-hardware.org/?probe=3228126df8) | Mar 29, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| HP            | ProBook 4525s               | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [02a403c967](https://linux-hardware.org/?probe=02a403c967) | Mar 24, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | [3157cd3bfe](https://linux-hardware.org/?probe=3157cd3bfe) | Mar 23, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | [97df6a4a9a](https://linux-hardware.org/?probe=97df6a4a9a) | Mar 23, 2021 |
| ASUSTek       | UX31A                       | [c6506a0289](https://linux-hardware.org/?probe=c6506a0289) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | [18d693f712](https://linux-hardware.org/?probe=18d693f712) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| Acer          | Aspire 5551G                | [1002c3efd0](https://linux-hardware.org/?probe=1002c3efd0) | Mar 19, 2021 |
| Acer          | Aspire E5-572G              | [c63de512e5](https://linux-hardware.org/?probe=c63de512e5) | Mar 18, 2021 |
| HP            | 250 G1                      | [7b14b4e7e5](https://linux-hardware.org/?probe=7b14b4e7e5) | Mar 18, 2021 |
| HP            | ProBook 4525s               | [f9830feb98](https://linux-hardware.org/?probe=f9830feb98) | Mar 17, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [d2dde464de](https://linux-hardware.org/?probe=d2dde464de) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [12eebe7515](https://linux-hardware.org/?probe=12eebe7515) | Mar 17, 2021 |
| Prestigio     | PSB141C03                   | [82f601055a](https://linux-hardware.org/?probe=82f601055a) | Mar 17, 2021 |
| Acer          | Aspire E5-572G              | [863c6c5d68](https://linux-hardware.org/?probe=863c6c5d68) | Mar 17, 2021 |
| Lenovo        | B50-30 20382                | [51bf91aae7](https://linux-hardware.org/?probe=51bf91aae7) | Mar 14, 2021 |
| HP            | Mini 210-4000               | [9301f9c8ef](https://linux-hardware.org/?probe=9301f9c8ef) | Mar 12, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [83f50b266f](https://linux-hardware.org/?probe=83f50b266f) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [ed293423f3](https://linux-hardware.org/?probe=ed293423f3) | Mar 11, 2021 |
| HP            | ProBook 4525s               | [912c2f075f](https://linux-hardware.org/?probe=912c2f075f) | Mar 09, 2021 |
| ASUSTek       | X550CC                      | [f63d1b8f0b](https://linux-hardware.org/?probe=f63d1b8f0b) | Mar 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1df473b11e](https://linux-hardware.org/?probe=1df473b11e) | Mar 03, 2021 |
| Dell          | System XPS L702X            | [1cce147fd2](https://linux-hardware.org/?probe=1cce147fd2) | Feb 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [902d3d474e](https://linux-hardware.org/?probe=902d3d474e) | Feb 25, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [390003cc95](https://linux-hardware.org/?probe=390003cc95) | Feb 24, 2021 |
| ASUSTek       | K50C                        | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | [0f4f85b4c1](https://linux-hardware.org/?probe=0f4f85b4c1) | Feb 19, 2021 |
| Packard Be... | EasyNote TM86               | [f548aa653a](https://linux-hardware.org/?probe=f548aa653a) | Feb 18, 2021 |
| Acer          | Extensa 5230                | [b128a06266](https://linux-hardware.org/?probe=b128a06266) | Feb 17, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [1a52fb16f9](https://linux-hardware.org/?probe=1a52fb16f9) | Feb 16, 2021 |
| Dell          | Inspiron 5748               | [8bb7ec1035](https://linux-hardware.org/?probe=8bb7ec1035) | Feb 15, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [c5877ecd52](https://linux-hardware.org/?probe=c5877ecd52) | Feb 14, 2021 |
| ASUSTek       | X540NV                      | [3a64cfa43e](https://linux-hardware.org/?probe=3a64cfa43e) | Feb 13, 2021 |
| HP            | Mini 210-4000               | [966136f01f](https://linux-hardware.org/?probe=966136f01f) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | [2e31ed1ec6](https://linux-hardware.org/?probe=2e31ed1ec6) | Feb 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8f8fd2975a](https://linux-hardware.org/?probe=8f8fd2975a) | Feb 13, 2021 |
| Unknown       | Unknown                     | [440af1645f](https://linux-hardware.org/?probe=440af1645f) | Feb 13, 2021 |
| Acer          | Extensa 7630EZ              | [9a0378eb4d](https://linux-hardware.org/?probe=9a0378eb4d) | Feb 11, 2021 |
| Acer          | TravelMate 5760             | [bbd0961627](https://linux-hardware.org/?probe=bbd0961627) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [6487d4bd7c](https://linux-hardware.org/?probe=6487d4bd7c) | Feb 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8c35b025b2](https://linux-hardware.org/?probe=8c35b025b2) | Feb 08, 2021 |
| HP            | Laptop 15-dw2xxx            | [cbd3e60242](https://linux-hardware.org/?probe=cbd3e60242) | Feb 07, 2021 |
| HP            | 635                         | [e83d58e706](https://linux-hardware.org/?probe=e83d58e706) | Feb 03, 2021 |
| Acer          | Aspire 5551G                | [811535132b](https://linux-hardware.org/?probe=811535132b) | Feb 02, 2021 |
| Acer          | Aspire A315-21              | [e86c3d781d](https://linux-hardware.org/?probe=e86c3d781d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T410 2537V28       | [126c75190e](https://linux-hardware.org/?probe=126c75190e) | Jan 22, 2021 |
| Lenovo        | G580 20157                  | [e04d0e066e](https://linux-hardware.org/?probe=e04d0e066e) | Jan 22, 2021 |
| HP            | 255 G2                      | [3ebc0a9b9b](https://linux-hardware.org/?probe=3ebc0a9b9b) | Jan 21, 2021 |
| Lenovo        | G50-30 80G0                 | [48644938e9](https://linux-hardware.org/?probe=48644938e9) | Jan 17, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b3bfbdace0](https://linux-hardware.org/?probe=b3bfbdace0) | Jan 10, 2021 |
| ASUSTek       | N550JK                      | [f12a646f8b](https://linux-hardware.org/?probe=f12a646f8b) | Jan 09, 2021 |
| Acer          | Extensa 2511G               | [ca3628282a](https://linux-hardware.org/?probe=ca3628282a) | Jan 06, 2021 |
| HP            | Mini 5102                   | [76f0b2193f](https://linux-hardware.org/?probe=76f0b2193f) | Jan 06, 2021 |
| HP            | Laptop 15-db1xxx            | [76f271acf1](https://linux-hardware.org/?probe=76f271acf1) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b005d0780d](https://linux-hardware.org/?probe=b005d0780d) | Jan 04, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [f49ba1df9c](https://linux-hardware.org/?probe=f49ba1df9c) | Jan 01, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [997fd6a726](https://linux-hardware.org/?probe=997fd6a726) | Dec 30, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | [8eb79a3a10](https://linux-hardware.org/?probe=8eb79a3a10) | Dec 29, 2020 |
| Lenovo        | G580 20157                  | [f4ae75d77c](https://linux-hardware.org/?probe=f4ae75d77c) | Dec 16, 2020 |
| Dell          | Inspiron 5748               | [091c74353b](https://linux-hardware.org/?probe=091c74353b) | Dec 16, 2020 |
| Lenovo        | B5400 20278                 | [56ea17c80b](https://linux-hardware.org/?probe=56ea17c80b) | Dec 15, 2020 |
| Lenovo        | G580 20157                  | [b987e4cc7c](https://linux-hardware.org/?probe=b987e4cc7c) | Dec 11, 2020 |
| Lenovo        | G580 20157                  | [f6e40ea1a0](https://linux-hardware.org/?probe=f6e40ea1a0) | Dec 11, 2020 |
| Samsung       | R530/R730                   | [eaf1fed190](https://linux-hardware.org/?probe=eaf1fed190) | Dec 11, 2020 |
| Lenovo        | G50-30 80G0                 | [d0d9126db4](https://linux-hardware.org/?probe=d0d9126db4) | Dec 08, 2020 |
| Prestigio     | PSB141C03                   | [4087902d18](https://linux-hardware.org/?probe=4087902d18) | Dec 07, 2020 |
| Lenovo        | G50-30 80G0                 | [a566f76ca4](https://linux-hardware.org/?probe=a566f76ca4) | Dec 07, 2020 |
| Acer          | Aspire E1-532               | [27a4e636f6](https://linux-hardware.org/?probe=27a4e636f6) | Dec 02, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | [54886a9cc0](https://linux-hardware.org/?probe=54886a9cc0) | Nov 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [91ff5fdd53](https://linux-hardware.org/?probe=91ff5fdd53) | Nov 28, 2020 |
| ASUSTek       | K52N                        | [94f1b7362b](https://linux-hardware.org/?probe=94f1b7362b) | Nov 25, 2020 |
| Acer          | Aspire E1-530               | [e343493113](https://linux-hardware.org/?probe=e343493113) | Nov 25, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | [b265ff82a7](https://linux-hardware.org/?probe=b265ff82a7) | Nov 21, 2020 |
| Lenovo        | ThinkPad E15 20RD0014RT     | [81de71766f](https://linux-hardware.org/?probe=81de71766f) | Nov 21, 2020 |
| Prestigio     | PSB141C02                   | [08aa1ee2ff](https://linux-hardware.org/?probe=08aa1ee2ff) | Nov 20, 2020 |
| ASUSTek       | X541UAK                     | [bada67f585](https://linux-hardware.org/?probe=bada67f585) | Nov 20, 2020 |
| Lenovo        | G50-30 80G0                 | [9687208571](https://linux-hardware.org/?probe=9687208571) | Nov 19, 2020 |
| ASUSTek       | X541UAK                     | [c914110be9](https://linux-hardware.org/?probe=c914110be9) | Nov 19, 2020 |
| Acer          | Aspire E1-532G              | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| Samsung       | R508                        | [937a0199e0](https://linux-hardware.org/?probe=937a0199e0) | Nov 16, 2020 |
| ASUSTek       | K52N                        | [a96cd62a24](https://linux-hardware.org/?probe=a96cd62a24) | Nov 14, 2020 |
| HP            | EliteBook 850 G5            | [225c61e941](https://linux-hardware.org/?probe=225c61e941) | Nov 13, 2020 |
| Dell          | Inspiron 5521               | [1080310f19](https://linux-hardware.org/?probe=1080310f19) | Nov 11, 2020 |
| Intel         | SharkBay Platform           | [21647cb222](https://linux-hardware.org/?probe=21647cb222) | Nov 09, 2020 |
| Unknown       | Unknown                     | [091af6961a](https://linux-hardware.org/?probe=091af6961a) | Nov 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [5da1ec78a0](https://linux-hardware.org/?probe=5da1ec78a0) | Nov 07, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | [412e6eca38](https://linux-hardware.org/?probe=412e6eca38) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | [6fb42db6e5](https://linux-hardware.org/?probe=6fb42db6e5) | Nov 05, 2020 |
| Intel         | SharkBay Platform           | [dcd49fdf3b](https://linux-hardware.org/?probe=dcd49fdf3b) | Nov 04, 2020 |
| Samsung       | R508                        | [7915a99545](https://linux-hardware.org/?probe=7915a99545) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [45666ff7af](https://linux-hardware.org/?probe=45666ff7af) | Nov 01, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [830c1ed47a](https://linux-hardware.org/?probe=830c1ed47a) | Nov 01, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f5328a95d5](https://linux-hardware.org/?probe=f5328a95d5) | Oct 31, 2020 |
| Dell          | Inspiron 15 5501            | [557aca340e](https://linux-hardware.org/?probe=557aca340e) | Oct 27, 2020 |
| Timi          | TM1701                      | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Dell          | Inspiron 15 5501            | [92fa11d82d](https://linux-hardware.org/?probe=92fa11d82d) | Oct 25, 2020 |
| Dell          | Inspiron 15 5501            | [6a18afe215](https://linux-hardware.org/?probe=6a18afe215) | Oct 25, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b0e3f9ed28](https://linux-hardware.org/?probe=b0e3f9ed28) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f21f5a008c](https://linux-hardware.org/?probe=f21f5a008c) | Oct 21, 2020 |
| HP            | 250 G2                      | [164b391add](https://linux-hardware.org/?probe=164b391add) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | [50cb6d53ef](https://linux-hardware.org/?probe=50cb6d53ef) | Oct 18, 2020 |
| Dell          | Inspiron 7577               | [0e1b75fc55](https://linux-hardware.org/?probe=0e1b75fc55) | Oct 18, 2020 |
| Acer          | Unknown                     | [5dc51268a1](https://linux-hardware.org/?probe=5dc51268a1) | Oct 17, 2020 |
| Prestigio     | PSB141C03                   | [eb6b709b25](https://linux-hardware.org/?probe=eb6b709b25) | Oct 12, 2020 |
| Lenovo        | ThinkPad T400 7417CTO       | [41f5d8bbb1](https://linux-hardware.org/?probe=41f5d8bbb1) | Oct 12, 2020 |
| Lenovo        | V145-15AST 81MT             | [479a1ad655](https://linux-hardware.org/?probe=479a1ad655) | Oct 11, 2020 |
| HP            | Laptop 15-bs0xx             | [eefad2dd0f](https://linux-hardware.org/?probe=eefad2dd0f) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [1d6ca8e5fc](https://linux-hardware.org/?probe=1d6ca8e5fc) | Oct 09, 2020 |
| HP            | Laptop 15-bs0xx             | [b0244dd7f4](https://linux-hardware.org/?probe=b0244dd7f4) | Oct 08, 2020 |
| Dell          | G5 5587                     | [7ec299e574](https://linux-hardware.org/?probe=7ec299e574) | Oct 03, 2020 |
| Acer          | Aspire A515-51G             | [4308201e9f](https://linux-hardware.org/?probe=4308201e9f) | Sep 28, 2020 |
| Samsung       | R518                        | [c4db2214cd](https://linux-hardware.org/?probe=c4db2214cd) | Sep 27, 2020 |
| Timi          | TM1709                      | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| HP            | 250 G2                      | [0721c128e6](https://linux-hardware.org/?probe=0721c128e6) | Sep 22, 2020 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [586f647e41](https://linux-hardware.org/?probe=586f647e41) | Sep 13, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [41ed89087e](https://linux-hardware.org/?probe=41ed89087e) | Aug 31, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ed88384ae9](https://linux-hardware.org/?probe=ed88384ae9) | Aug 31, 2020 |
| MSI           | PS42 Modern 8RA             | [ab71a04043](https://linux-hardware.org/?probe=ab71a04043) | Aug 29, 2020 |
| HP            | Laptop 15-bs0xx             | [22adb53a27](https://linux-hardware.org/?probe=22adb53a27) | Aug 29, 2020 |
| Dell          | Precision 7540              | [8e97d27134](https://linux-hardware.org/?probe=8e97d27134) | Aug 27, 2020 |
| ASUSTek       | U36SG                       | [103ce98981](https://linux-hardware.org/?probe=103ce98981) | Aug 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [aaae1d3e78](https://linux-hardware.org/?probe=aaae1d3e78) | Aug 24, 2020 |
| Dell          | Vostro 5490                 | [873e3c07c7](https://linux-hardware.org/?probe=873e3c07c7) | Aug 24, 2020 |
| HP            | Laptop 15-bs0xx             | [a7b737f065](https://linux-hardware.org/?probe=a7b737f065) | Aug 23, 2020 |
| HP            | Laptop 15-bs0xx             | [494bb32560](https://linux-hardware.org/?probe=494bb32560) | Aug 23, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [9c05eb6ed3](https://linux-hardware.org/?probe=9c05eb6ed3) | Aug 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [42cfca7021](https://linux-hardware.org/?probe=42cfca7021) | Aug 14, 2020 |
| Acer          | Aspire 4810T                | [5ff79d2a64](https://linux-hardware.org/?probe=5ff79d2a64) | Aug 09, 2020 |
| Acer          | Aspire V3-571G              | [6ca9ef29fc](https://linux-hardware.org/?probe=6ca9ef29fc) | Aug 02, 2020 |
| HP            | 250 G6 Notebook PC          | [9b0eb8f018](https://linux-hardware.org/?probe=9b0eb8f018) | Aug 01, 2020 |
| Timi          | TM1701                      | [71882c9121](https://linux-hardware.org/?probe=71882c9121) | Jul 31, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [d38b29e9f6](https://linux-hardware.org/?probe=d38b29e9f6) | Jul 29, 2020 |
| Timi          | TM1701                      | [024ed71324](https://linux-hardware.org/?probe=024ed71324) | Jul 22, 2020 |
| Acer          | Aspire E1-731               | [e055f89ff6](https://linux-hardware.org/?probe=e055f89ff6) | Jul 15, 2020 |
| HP            | ProBook 450 G5              | [acd59fc735](https://linux-hardware.org/?probe=acd59fc735) | Jul 15, 2020 |
| HP            | ProBook 440 G5              | [744a29218a](https://linux-hardware.org/?probe=744a29218a) | Jul 09, 2020 |
| HP            | ProBook 445 G6              | [e82b679ba1](https://linux-hardware.org/?probe=e82b679ba1) | Jul 05, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| ASUSTek       | X705UQR                     | [caebcd4a78](https://linux-hardware.org/?probe=caebcd4a78) | Jul 03, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [a6dcbcadc4](https://linux-hardware.org/?probe=a6dcbcadc4) | Jun 30, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [df5777de6d](https://linux-hardware.org/?probe=df5777de6d) | Jun 29, 2020 |
| LG Electro... | R510                        | [51967b227c](https://linux-hardware.org/?probe=51967b227c) | Jun 29, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [566a257192](https://linux-hardware.org/?probe=566a257192) | Jun 07, 2020 |
| Dell          | Inspiron 3521               | [59c6b9d06f](https://linux-hardware.org/?probe=59c6b9d06f) | Jun 06, 2020 |
| ASUSTek       | X540NV                      | [f1a595ed8a](https://linux-hardware.org/?probe=f1a595ed8a) | Jun 05, 2020 |
| ASUSTek       | X541UJ                      | [4116c24ad8](https://linux-hardware.org/?probe=4116c24ad8) | Jun 03, 2020 |
| HP            | ProBook 4740s               | [bac1c80c34](https://linux-hardware.org/?probe=bac1c80c34) | Jun 02, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b73508569c](https://linux-hardware.org/?probe=b73508569c) | May 30, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [178a726d73](https://linux-hardware.org/?probe=178a726d73) | May 28, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [dbfbd4b70e](https://linux-hardware.org/?probe=dbfbd4b70e) | May 28, 2020 |
| ASUSTek       | S551LB                      | [4aed54f228](https://linux-hardware.org/?probe=4aed54f228) | May 28, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire VN7-592G             | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| HP            | Notebook                    | [672d0acfa1](https://linux-hardware.org/?probe=672d0acfa1) | May 26, 2020 |
| HP            | Notebook                    | [1fa50923d3](https://linux-hardware.org/?probe=1fa50923d3) | May 26, 2020 |
| Acer          | AOA150                      | [4879ee6a95](https://linux-hardware.org/?probe=4879ee6a95) | May 24, 2020 |
| Prestigio     | Multipad Visconte V         | [d3f3e2e2b4](https://linux-hardware.org/?probe=d3f3e2e2b4) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e82eb79af2](https://linux-hardware.org/?probe=e82eb79af2) | May 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06d027143f](https://linux-hardware.org/?probe=06d027143f) | May 11, 2020 |
| HP            | ProBook 450 G6              | [ff446033f4](https://linux-hardware.org/?probe=ff446033f4) | May 07, 2020 |
| HP            | ProBook 450 G6              | [fbdced7593](https://linux-hardware.org/?probe=fbdced7593) | Apr 30, 2020 |
| Timi          | TM1613                      | [5f55af6b8d](https://linux-hardware.org/?probe=5f55af6b8d) | Apr 27, 2020 |
| ASUSTek       | N551JM                      | [cd375242d3](https://linux-hardware.org/?probe=cd375242d3) | Apr 15, 2020 |
| Acer          | Aspire A315-42G             | [e050431a72](https://linux-hardware.org/?probe=e050431a72) | Apr 09, 2020 |
| Acer          | Aspire A315-42G             | [13a642b394](https://linux-hardware.org/?probe=13a642b394) | Apr 09, 2020 |
| HP            | ProBook 4710s               | [56f533f0f5](https://linux-hardware.org/?probe=56f533f0f5) | Apr 07, 2020 |
| HP            | Notebook                    | [d32a1f4247](https://linux-hardware.org/?probe=d32a1f4247) | Mar 30, 2020 |
| Acer          | Aspire 4810T                | [b7d82235f8](https://linux-hardware.org/?probe=b7d82235f8) | Mar 22, 2020 |
| Acer          | TravelMate P259-M           | [596bd79c7a](https://linux-hardware.org/?probe=596bd79c7a) | Mar 22, 2020 |
| Lenovo        | ThinkPad T61 7661WPF        | [ce22405483](https://linux-hardware.org/?probe=ce22405483) | Mar 19, 2020 |
| ASUSTek       | K52N                        | [a1fea085d9](https://linux-hardware.org/?probe=a1fea085d9) | Mar 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e0fa6f7e5](https://linux-hardware.org/?probe=0e0fa6f7e5) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0c7024795f](https://linux-hardware.org/?probe=0c7024795f) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [526830e223](https://linux-hardware.org/?probe=526830e223) | Mar 17, 2020 |
| ASUSTek       | X540NV                      | [e37fc99e67](https://linux-hardware.org/?probe=e37fc99e67) | Mar 11, 2020 |
| Lenovo        | G500 20236                  | [efbd3772bc](https://linux-hardware.org/?probe=efbd3772bc) | Mar 09, 2020 |
| ASUSTek       | X540NV                      | [123e49a129](https://linux-hardware.org/?probe=123e49a129) | Mar 07, 2020 |
| Dell          | Inspiron 3576               | [2938ca5aec](https://linux-hardware.org/?probe=2938ca5aec) | Mar 03, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [7c909cb955](https://linux-hardware.org/?probe=7c909cb955) | Mar 01, 2020 |
| Acer          | Extensa 5220                | [3ac52b68ad](https://linux-hardware.org/?probe=3ac52b68ad) | Mar 01, 2020 |
| Dell          | Inspiron 3576               | [c0fb2f48aa](https://linux-hardware.org/?probe=c0fb2f48aa) | Feb 29, 2020 |
| ASUSTek       | X705UQR                     | [a5cca23283](https://linux-hardware.org/?probe=a5cca23283) | Feb 29, 2020 |
| Packard Be... | DOT S                       | [cd2b5a2715](https://linux-hardware.org/?probe=cd2b5a2715) | Feb 28, 2020 |
| Packard Be... | DOT S                       | [8db7395b33](https://linux-hardware.org/?probe=8db7395b33) | Feb 27, 2020 |
| ASUSTek       | K53SV                       | [9192ccbb93](https://linux-hardware.org/?probe=9192ccbb93) | Feb 26, 2020 |
| Timi          | TM1701                      | [4185035b5f](https://linux-hardware.org/?probe=4185035b5f) | Feb 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [619c9af84e](https://linux-hardware.org/?probe=619c9af84e) | Feb 25, 2020 |
| HP            | Pavilion g6                 | [4e0759261c](https://linux-hardware.org/?probe=4e0759261c) | Feb 24, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8e0229807b](https://linux-hardware.org/?probe=8e0229807b) | Feb 24, 2020 |
| Acer          | Aspire V3-571G              | [dda987c8c9](https://linux-hardware.org/?probe=dda987c8c9) | Feb 24, 2020 |
| Acer          | Aspire E1-571G              | [9951bcb215](https://linux-hardware.org/?probe=9951bcb215) | Feb 23, 2020 |
| Packard Be... | DOT S                       | [ef2c3a6924](https://linux-hardware.org/?probe=ef2c3a6924) | Feb 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f3185269f](https://linux-hardware.org/?probe=3f3185269f) | Feb 18, 2020 |
| ASUSTek       | K70AE                       | [1c9b37e0bf](https://linux-hardware.org/?probe=1c9b37e0bf) | Feb 12, 2020 |
| Acer          | Aspire V3-571G              | [8d3edd49c5](https://linux-hardware.org/?probe=8d3edd49c5) | Feb 11, 2020 |
| Dell          | System XPS L702X            | [17383a48fc](https://linux-hardware.org/?probe=17383a48fc) | Feb 06, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | [1864afd83f](https://linux-hardware.org/?probe=1864afd83f) | Feb 03, 2020 |
| ASUSTek       | X705UQR                     | [8b15a6370b](https://linux-hardware.org/?probe=8b15a6370b) | Feb 01, 2020 |
| Acer          | Aspire V5-561G              | [a646ea611f](https://linux-hardware.org/?probe=a646ea611f) | Jan 29, 2020 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [cd7471d773](https://linux-hardware.org/?probe=cd7471d773) | Jan 25, 2020 |
| Dell          | XPS 15 9570                 | [c97d5c5a5e](https://linux-hardware.org/?probe=c97d5c5a5e) | Jan 24, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [485f1149df](https://linux-hardware.org/?probe=485f1149df) | Jan 20, 2020 |
| ASUSTek       | X705UQR                     | [87c3bdc009](https://linux-hardware.org/?probe=87c3bdc009) | Jan 19, 2020 |
| ASUSTek       | X705UQR                     | [bc34d4d0e9](https://linux-hardware.org/?probe=bc34d4d0e9) | Jan 19, 2020 |
| ASUSTek       | UL30A                       | [f9f8ddf425](https://linux-hardware.org/?probe=f9f8ddf425) | Jan 14, 2020 |
| ASUSTek       | X540SA                      | [22047ce8bb](https://linux-hardware.org/?probe=22047ce8bb) | Jan 11, 2020 |
| HP            | Unknown                     | [7845d03a39](https://linux-hardware.org/?probe=7845d03a39) | Jan 11, 2020 |
| HP            | ProBook 455 G1              | [08dcbaa82a](https://linux-hardware.org/?probe=08dcbaa82a) | Jan 02, 2020 |
| HP            | ProBook 4530s               | [48ca791cd2](https://linux-hardware.org/?probe=48ca791cd2) | Jan 02, 2020 |
| Samsung       | R519/R719                   | [1a0ac991d0](https://linux-hardware.org/?probe=1a0ac991d0) | Jan 01, 2020 |
| ASUSTek       | K53Z                        | [51da8ec92c](https://linux-hardware.org/?probe=51da8ec92c) | Jan 01, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [54845cd095](https://linux-hardware.org/?probe=54845cd095) | Dec 29, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [e96c98384b](https://linux-hardware.org/?probe=e96c98384b) | Dec 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [9f38052441](https://linux-hardware.org/?probe=9f38052441) | Dec 28, 2019 |
| Toshiba       | Satellite L850D-BJS         | [c77563a5fb](https://linux-hardware.org/?probe=c77563a5fb) | Dec 23, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | [57160cc915](https://linux-hardware.org/?probe=57160cc915) | Dec 16, 2019 |
| Samsung       | R508                        | [f2d52e0253](https://linux-hardware.org/?probe=f2d52e0253) | Dec 12, 2019 |
| ASUSTek       | X540NV                      | [e1396088af](https://linux-hardware.org/?probe=e1396088af) | Dec 11, 2019 |
| ASUSTek       | X540NV                      | [0649347201](https://linux-hardware.org/?probe=0649347201) | Dec 11, 2019 |
| Lenovo        | G50-30 80G0                 | [c6838b1dba](https://linux-hardware.org/?probe=c6838b1dba) | Dec 11, 2019 |
| Packard Be... | DOT S                       | [5bd4609615](https://linux-hardware.org/?probe=5bd4609615) | Dec 09, 2019 |
| HP            | Pavilion 17                 | [e5c53c61e8](https://linux-hardware.org/?probe=e5c53c61e8) | Dec 08, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | [4b5548d0bb](https://linux-hardware.org/?probe=4b5548d0bb) | Dec 05, 2019 |
| Dell          | G3 3579                     | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Pavilion 15                 | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| Dell          | Inspiron 5559               | [5a4aaf46f2](https://linux-hardware.org/?probe=5a4aaf46f2) | Dec 02, 2019 |
| HP            | ProBook 450 G5              | [9441c13ce5](https://linux-hardware.org/?probe=9441c13ce5) | Dec 02, 2019 |
| MSI           | GP72 7RDX                   | [445ae9719a](https://linux-hardware.org/?probe=445ae9719a) | Dec 02, 2019 |
| Dell          | Latitude E5450              | [9d71909e26](https://linux-hardware.org/?probe=9d71909e26) | Dec 02, 2019 |
| Lenovo        | G50-30 80G0                 | [320dde739d](https://linux-hardware.org/?probe=320dde739d) | Nov 27, 2019 |
| Acer          | Aspire E1-530               | [47bc99ddc7](https://linux-hardware.org/?probe=47bc99ddc7) | Nov 27, 2019 |
| Acer          | Aspire E1-532               | [ecb10a3db1](https://linux-hardware.org/?probe=ecb10a3db1) | Nov 27, 2019 |
| Lenovo        | G50-30 80G0                 | [3baee5b588](https://linux-hardware.org/?probe=3baee5b588) | Nov 26, 2019 |
| Acer          | Aspire E1-530               | [e6b4056c8c](https://linux-hardware.org/?probe=e6b4056c8c) | Nov 26, 2019 |
| Toshiba       | SATEGO X200                 | [087c0e291d](https://linux-hardware.org/?probe=087c0e291d) | Nov 25, 2019 |
| Packard Be... | EasyNote TK36               | [b85f41a113](https://linux-hardware.org/?probe=b85f41a113) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | [5ded5e4dc0](https://linux-hardware.org/?probe=5ded5e4dc0) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | [b0e6d88437](https://linux-hardware.org/?probe=b0e6d88437) | Nov 23, 2019 |
| Packard Be... | EasyNote TK36               | [f86cacb590](https://linux-hardware.org/?probe=f86cacb590) | Nov 23, 2019 |
| Lenovo        | S20-30 20421                | [969154a207](https://linux-hardware.org/?probe=969154a207) | Nov 21, 2019 |
| Lenovo        | S20-30 20421                | [d2625b22e1](https://linux-hardware.org/?probe=d2625b22e1) | Nov 19, 2019 |
| HP            | Pavilion 15                 | [ae59f09d06](https://linux-hardware.org/?probe=ae59f09d06) | Nov 19, 2019 |
| Lenovo        | ThinkPad T470 20HD005QRT    | [403acf7be3](https://linux-hardware.org/?probe=403acf7be3) | Nov 16, 2019 |
| ASUSTek       | X541UAK                     | [a765714f02](https://linux-hardware.org/?probe=a765714f02) | Nov 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [292caf76d2](https://linux-hardware.org/?probe=292caf76d2) | Nov 01, 2019 |
| Samsung       | RV408/RV508                 | [e4e8ab57d3](https://linux-hardware.org/?probe=e4e8ab57d3) | Oct 31, 2019 |
| Lenovo        | B50-30 20382                | [c21f8427bb](https://linux-hardware.org/?probe=c21f8427bb) | Oct 31, 2019 |
| BenQ          | JoyBook A53                 | [244ee24b1d](https://linux-hardware.org/?probe=244ee24b1d) | Oct 30, 2019 |
| Dream Mach... | N8xEJEK                     | [7d9991c02f](https://linux-hardware.org/?probe=7d9991c02f) | Oct 30, 2019 |
| MSI           | PS63 Modern 8M              | [3442120f57](https://linux-hardware.org/?probe=3442120f57) | Oct 29, 2019 |
| Samsung       | R528/R728                   | [72819f11a2](https://linux-hardware.org/?probe=72819f11a2) | Oct 26, 2019 |
| ASUSTek       | N550JV                      | [091b2a9dda](https://linux-hardware.org/?probe=091b2a9dda) | Oct 22, 2019 |
| Acer          | Aspire 4810T                | [f177f662c9](https://linux-hardware.org/?probe=f177f662c9) | Oct 21, 2019 |
| HP            | Laptop 15-bw0xx             | [3eade14c1a](https://linux-hardware.org/?probe=3eade14c1a) | Oct 18, 2019 |
| Fujitsu Si... | LIFEBOOK E8410              | [4a653fdd06](https://linux-hardware.org/?probe=4a653fdd06) | Oct 12, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d0e6b3a935](https://linux-hardware.org/?probe=d0e6b3a935) | Oct 08, 2019 |
| HP            | Laptop 15-bs0xx             | [5b817a0d34](https://linux-hardware.org/?probe=5b817a0d34) | Oct 06, 2019 |
| ASUSTek       | 1101HA                      | [61837b2a0e](https://linux-hardware.org/?probe=61837b2a0e) | Sep 27, 2019 |
| Dell          | Inspiron 13-5378            | [37c0832ec3](https://linux-hardware.org/?probe=37c0832ec3) | Sep 20, 2019 |
| ASUSTek       | 1101HA                      | [8ad347373c](https://linux-hardware.org/?probe=8ad347373c) | Sep 15, 2019 |
| ASUSTek       | X541UAK                     | [a8ec17e19a](https://linux-hardware.org/?probe=a8ec17e19a) | Sep 13, 2019 |
| Dell          | Vostro 5581                 | [137d404b4f](https://linux-hardware.org/?probe=137d404b4f) | Sep 04, 2019 |
| Samsung       | R528/R728                   | [9a81ee014c](https://linux-hardware.org/?probe=9a81ee014c) | Aug 31, 2019 |
| ASUSTek       | K501UX                      | [5e0c250961](https://linux-hardware.org/?probe=5e0c250961) | Aug 22, 2019 |
| Dell          | Vostro 5581                 | [6d17449b1e](https://linux-hardware.org/?probe=6d17449b1e) | Aug 19, 2019 |
| Dell          | Vostro 5581                 | [e890c77b5d](https://linux-hardware.org/?probe=e890c77b5d) | Aug 18, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | [85f5a138a1](https://linux-hardware.org/?probe=85f5a138a1) | Aug 16, 2019 |
| Lenovo        | G50-30 80G0                 | [03e68e8b7c](https://linux-hardware.org/?probe=03e68e8b7c) | Aug 14, 2019 |
| Samsung       | R580/R590                   | [ef8583eaed](https://linux-hardware.org/?probe=ef8583eaed) | Aug 09, 2019 |
| HP            | Pavilion 17                 | [24e7df16f9](https://linux-hardware.org/?probe=24e7df16f9) | Aug 03, 2019 |
| ASUSTek       | 1011PX                      | [5b135fd648](https://linux-hardware.org/?probe=5b135fd648) | Aug 01, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [47bfe0724a](https://linux-hardware.org/?probe=47bfe0724a) | Jul 30, 2019 |
| ASUSTek       | K54HR                       | [5e03bd6730](https://linux-hardware.org/?probe=5e03bd6730) | Jul 29, 2019 |
| Acer          | Extensa 2510G               | [1c77d7a584](https://linux-hardware.org/?probe=1c77d7a584) | Jul 27, 2019 |
| Acer          | Nitro AN515-31              | [c1f4538adb](https://linux-hardware.org/?probe=c1f4538adb) | Jul 24, 2019 |
| Lenovo        | G570 20079                  | [a7618091fb](https://linux-hardware.org/?probe=a7618091fb) | Jul 23, 2019 |
| Acer          | Extensa 2508                | [a1d2e02773](https://linux-hardware.org/?probe=a1d2e02773) | Jul 22, 2019 |
| ASUSTek       | X540SA                      | [9964879fbe](https://linux-hardware.org/?probe=9964879fbe) | Jul 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a385ff1671](https://linux-hardware.org/?probe=a385ff1671) | Jul 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1a41f9e428](https://linux-hardware.org/?probe=1a41f9e428) | Jul 20, 2019 |
| MSI           | MS-N014                     | [a6b6d22f92](https://linux-hardware.org/?probe=a6b6d22f92) | Jul 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [00eecf27f3](https://linux-hardware.org/?probe=00eecf27f3) | Jul 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6b13d225c0](https://linux-hardware.org/?probe=6b13d225c0) | Jul 09, 2019 |
| Acer          | Aspire E1-771               | [4a1964118d](https://linux-hardware.org/?probe=4a1964118d) | Jul 04, 2019 |
| Acer          | Aspire V3-772G              | [6cc64da5c5](https://linux-hardware.org/?probe=6cc64da5c5) | Jun 20, 2019 |
| Lenovo        | B570e HuronRiver Platfor... | [678d443649](https://linux-hardware.org/?probe=678d443649) | Jun 14, 2019 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [f72a609702](https://linux-hardware.org/?probe=f72a609702) | Jun 13, 2019 |
| Lenovo        | B570e HuronRiver Platfor... | [b74e6f3a71](https://linux-hardware.org/?probe=b74e6f3a71) | Jun 08, 2019 |
| HP            | ENVY 17                     | [9f9eeecefa](https://linux-hardware.org/?probe=9f9eeecefa) | Jun 05, 2019 |
| Acer          | Aspire 4810T                | [0b3243adb4](https://linux-hardware.org/?probe=0b3243adb4) | May 29, 2019 |
| Acer          | Aspire 5349                 | [8e79cddbda](https://linux-hardware.org/?probe=8e79cddbda) | May 23, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [8358a6f5f5](https://linux-hardware.org/?probe=8358a6f5f5) | May 22, 2019 |
| ASUSTek       | X551MA                      | [ef445a792b](https://linux-hardware.org/?probe=ef445a792b) | May 20, 2019 |
| ASUSTek       | X551MA                      | [5ad90522ec](https://linux-hardware.org/?probe=5ad90522ec) | May 20, 2019 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ba1f9829de](https://linux-hardware.org/?probe=ba1f9829de) | May 19, 2019 |
| ASUSTek       | X751SA                      | [412366312b](https://linux-hardware.org/?probe=412366312b) | May 18, 2019 |
| Dell          | Inspiron 7577               | [ae6c3a51b8](https://linux-hardware.org/?probe=ae6c3a51b8) | May 17, 2019 |
| ASUSTek       | X751SA                      | [bb1fd1c382](https://linux-hardware.org/?probe=bb1fd1c382) | May 17, 2019 |
| ASUSTek       | X751SA                      | [130b715a25](https://linux-hardware.org/?probe=130b715a25) | May 17, 2019 |
| Samsung       | RV413/RV513                 | [539459e889](https://linux-hardware.org/?probe=539459e889) | May 16, 2019 |
| Samsung       | RV413/RV513                 | [c6e6520b11](https://linux-hardware.org/?probe=c6e6520b11) | May 16, 2019 |
| ASUSTek       | UL30A                       | [6dac8a4d6f](https://linux-hardware.org/?probe=6dac8a4d6f) | May 13, 2019 |
| HP            | ProBook 455 G1              | [185cf26f05](https://linux-hardware.org/?probe=185cf26f05) | May 09, 2019 |
| ASUSTek       | X510UA                      | [f6c30b2027](https://linux-hardware.org/?probe=f6c30b2027) | May 05, 2019 |
| Acer          | Nitro AN515-31              | [7a2df83bd4](https://linux-hardware.org/?probe=7a2df83bd4) | Apr 20, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [67a4e2a8a4](https://linux-hardware.org/?probe=67a4e2a8a4) | Apr 18, 2019 |
| Acer          | Nitro AN515-31              | [7ffaa2afa6](https://linux-hardware.org/?probe=7ffaa2afa6) | Apr 16, 2019 |
| ASUSTek       | UL30A                       | [46271f4c83](https://linux-hardware.org/?probe=46271f4c83) | Apr 07, 2019 |
| ASUSTek       | UX550VD                     | [c440ebc340](https://linux-hardware.org/?probe=c440ebc340) | Apr 04, 2019 |
| ASUSTek       | UL30A                       | [059a9e0d5f](https://linux-hardware.org/?probe=059a9e0d5f) | Apr 02, 2019 |
| HP            | Notebook                    | [b09be0c6da](https://linux-hardware.org/?probe=b09be0c6da) | Mar 31, 2019 |
| Lenovo        | B590 20206                  | [c0039b9d80](https://linux-hardware.org/?probe=c0039b9d80) | Mar 27, 2019 |
| Lenovo        | G50-30 80G0                 | [f801da09f7](https://linux-hardware.org/?probe=f801da09f7) | Mar 26, 2019 |
| Lenovo        | IdeaPad Z565 20066          | [6e6d9742ed](https://linux-hardware.org/?probe=6e6d9742ed) | Mar 23, 2019 |
| ASUSTek       | K50IP                       | [16e798fc6d](https://linux-hardware.org/?probe=16e798fc6d) | Mar 22, 2019 |
| HP            | Laptop 15-bs0xx             | [61650808a4](https://linux-hardware.org/?probe=61650808a4) | Mar 16, 2019 |
| ASUSTek       | X541NA                      | [339f40edee](https://linux-hardware.org/?probe=339f40edee) | Mar 16, 2019 |
| ASUSTek       | X541NA                      | [deef5c1776](https://linux-hardware.org/?probe=deef5c1776) | Mar 16, 2019 |
| Lenovo        | G700 20251                  | [31a2a66abd](https://linux-hardware.org/?probe=31a2a66abd) | Mar 15, 2019 |
| Lenovo        | G570 20079                  | [dddc5b738c](https://linux-hardware.org/?probe=dddc5b738c) | Mar 12, 2019 |
| HP            | 635                         | [c510246cec](https://linux-hardware.org/?probe=c510246cec) | Mar 09, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bf7d967cac](https://linux-hardware.org/?probe=bf7d967cac) | Mar 05, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [42c1b17429](https://linux-hardware.org/?probe=42c1b17429) | Feb 28, 2019 |
| ASUSTek       | N73JF                       | [ac3cf92791](https://linux-hardware.org/?probe=ac3cf92791) | Feb 24, 2019 |
| ASUSTek       | N73JF                       | [74010f75ff](https://linux-hardware.org/?probe=74010f75ff) | Feb 24, 2019 |
| Acer          | Aspire 3810TZ               | [1af1fd4358](https://linux-hardware.org/?probe=1af1fd4358) | Feb 08, 2019 |
| Dell          | Inspiron 5558               | [74b5e8085f](https://linux-hardware.org/?probe=74b5e8085f) | Feb 06, 2019 |
| HP            | EliteBook 840 G3            | [9246996d88](https://linux-hardware.org/?probe=9246996d88) | Feb 04, 2019 |
| Acer          | Aspire V3-571G              | [5c2493db94](https://linux-hardware.org/?probe=5c2493db94) | Feb 03, 2019 |
| ASUSTek       | E402NA                      | [84151cf35d](https://linux-hardware.org/?probe=84151cf35d) | Jan 30, 2019 |
| Samsung       | R519/R719                   | [c2367f286b](https://linux-hardware.org/?probe=c2367f286b) | Jan 26, 2019 |
| ASUSTek       | X540NV                      | [fd26f0c83a](https://linux-hardware.org/?probe=fd26f0c83a) | Jan 22, 2019 |
| HP            | G62                         | [63c41b239d](https://linux-hardware.org/?probe=63c41b239d) | Jan 21, 2019 |
| HP            | Laptop 15-rb0xx             | [e4399cedcf](https://linux-hardware.org/?probe=e4399cedcf) | Jan 10, 2019 |
| HP            | Laptop 15-rb0xx             | [c4ca5d85f2](https://linux-hardware.org/?probe=c4ca5d85f2) | Jan 10, 2019 |
| ASUSTek       | T101MT                      | [742c2cd59e](https://linux-hardware.org/?probe=742c2cd59e) | Jan 10, 2019 |
| HP            | Compaq Mini 110c-1100       | [f1a0693718](https://linux-hardware.org/?probe=f1a0693718) | Jan 09, 2019 |
| HP            | Notebook                    | [93451d1d63](https://linux-hardware.org/?probe=93451d1d63) | Dec 31, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [441e47c023](https://linux-hardware.org/?probe=441e47c023) | Dec 30, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d942bb34d](https://linux-hardware.org/?probe=5d942bb34d) | Dec 30, 2018 |
| Samsung       | RV408/RV508                 | [f67c14e4d6](https://linux-hardware.org/?probe=f67c14e4d6) | Dec 27, 2018 |
| Samsung       | R508                        | [c9ea0249f2](https://linux-hardware.org/?probe=c9ea0249f2) | Dec 24, 2018 |
| Acer          | AOD257                      | [d6763cd3ef](https://linux-hardware.org/?probe=d6763cd3ef) | Dec 23, 2018 |
| Samsung       | RV413/RV513                 | [d069cd58a8](https://linux-hardware.org/?probe=d069cd58a8) | Dec 20, 2018 |
| Acer          | Extensa 7630EZ              | [ff4bc33ec4](https://linux-hardware.org/?probe=ff4bc33ec4) | Dec 18, 2018 |
| ASUSTek       | M51Sr                       | [c91fc1e6b1](https://linux-hardware.org/?probe=c91fc1e6b1) | Dec 15, 2018 |
| Acer          | TravelMate 5760             | [fd0de5be57](https://linux-hardware.org/?probe=fd0de5be57) | Dec 14, 2018 |
| Acer          | Aspire ES1-523              | [b586596a6a](https://linux-hardware.org/?probe=b586596a6a) | Dec 10, 2018 |
| Lenovo        | Z50-70 20354                | [5d8804f368](https://linux-hardware.org/?probe=5d8804f368) | Dec 07, 2018 |
| Acer          | TravelMate 8481T            | [af2aaf56d9](https://linux-hardware.org/?probe=af2aaf56d9) | Dec 07, 2018 |
| ASUSTek       | N76VJ                       | [2fa5ed1dfc](https://linux-hardware.org/?probe=2fa5ed1dfc) | Nov 30, 2018 |
| Toshiba       | Satellite L300              | [8585fa81bc](https://linux-hardware.org/?probe=8585fa81bc) | Nov 29, 2018 |
| HP            | ProBook 4515s               | [1842a1b183](https://linux-hardware.org/?probe=1842a1b183) | Nov 29, 2018 |
| Lenovo        | B590 20206                  | [020331dd95](https://linux-hardware.org/?probe=020331dd95) | Nov 29, 2018 |
| Lenovo        | B590 20206                  | [9cb3062067](https://linux-hardware.org/?probe=9cb3062067) | Nov 29, 2018 |
| ASUSTek       | X510UNR                     | [8cc859859e](https://linux-hardware.org/?probe=8cc859859e) | Nov 28, 2018 |
| Acer          | Aspire 5750ZG               | [d138e04435](https://linux-hardware.org/?probe=d138e04435) | Nov 27, 2018 |
| Acer          | Aspire 5750ZG               | [516c88099e](https://linux-hardware.org/?probe=516c88099e) | Nov 23, 2018 |
| Lenovo        | B590 20206                  | [0cd011a796](https://linux-hardware.org/?probe=0cd011a796) | Nov 14, 2018 |
| Dell          | Inspiron M5010              | [2457e3698d](https://linux-hardware.org/?probe=2457e3698d) | Nov 05, 2018 |
| Packard Be... | EasyNote TE11HC             | [a196f24690](https://linux-hardware.org/?probe=a196f24690) | Nov 01, 2018 |
| Toshiba       | Satellite A215              | [8bf0975fb2](https://linux-hardware.org/?probe=8bf0975fb2) | Oct 31, 2018 |
| Lenovo        | G700 20251                  | [e8d909b0fa](https://linux-hardware.org/?probe=e8d909b0fa) | Oct 27, 2018 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [fddef6b216](https://linux-hardware.org/?probe=fddef6b216) | Oct 25, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2d1c5d19bf](https://linux-hardware.org/?probe=2d1c5d19bf) | Oct 25, 2018 |
| ASUSTek       | U32VJ                       | [a1d3315657](https://linux-hardware.org/?probe=a1d3315657) | Oct 24, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0a670684fa](https://linux-hardware.org/?probe=0a670684fa) | Oct 24, 2018 |
| Lenovo        | G700 20251                  | [c556cef805](https://linux-hardware.org/?probe=c556cef805) | Oct 19, 2018 |
| Acer          | Aspire ES1-520              | [7734a8cc4b](https://linux-hardware.org/?probe=7734a8cc4b) | Oct 19, 2018 |
| Toshiba       | Satellite L650              | [3c94da7bb6](https://linux-hardware.org/?probe=3c94da7bb6) | Oct 17, 2018 |
| Samsung       | RV413/RV513                 | [6045dbdc70](https://linux-hardware.org/?probe=6045dbdc70) | Oct 14, 2018 |
| Lenovo        | V580c 20160                 | [9322372044](https://linux-hardware.org/?probe=9322372044) | Oct 05, 2018 |
| ASUSTek       | X55A                        | [5137394ef1](https://linux-hardware.org/?probe=5137394ef1) | Oct 04, 2018 |
| HP            | Pavilion dv6                | [b4469a7aa8](https://linux-hardware.org/?probe=b4469a7aa8) | Oct 02, 2018 |
| ASUSTek       | K42Jr                       | [4f4c1ec561](https://linux-hardware.org/?probe=4f4c1ec561) | Sep 19, 2018 |
| Samsung       | RV413/RV513                 | [074d9a8a6c](https://linux-hardware.org/?probe=074d9a8a6c) | Sep 15, 2018 |
| HP            | ProBook 450 G1              | [a451edb119](https://linux-hardware.org/?probe=a451edb119) | Sep 15, 2018 |
| ASUSTek       | K54L                        | [5db2420e7b](https://linux-hardware.org/?probe=5db2420e7b) | Sep 15, 2018 |
| Samsung       | RV408/RV508                 | [0fcb4ce699](https://linux-hardware.org/?probe=0fcb4ce699) | Sep 06, 2018 |
| Acer          | Extensa 5620                | [59004a5a4d](https://linux-hardware.org/?probe=59004a5a4d) | Aug 28, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 76        | 9.22%   |
| ROSA R11                     | 56        | 6.8%    |
| Ubuntu 20.04                 | 54        | 6.55%   |
| ROSA R8.1                    | 44        | 5.34%   |
| ROSA R9                      | 32        | 3.88%   |
| ROSA R11.1                   | 28        | 3.4%    |
| Ubuntu 22.04                 | 26        | 3.16%   |
| Ubuntu 18.04                 | 26        | 3.16%   |
| Arch Rolling                 | 21        | 2.55%   |
| ROSA R8                      | 20        | 2.43%   |
| ROSA 12.2                    | 19        | 2.31%   |
| ROSA 12.4                    | 15        | 1.82%   |
| ROSA 12.3                    | 14        | 1.7%    |
| OpenMandriva 4.2             | 12        | 1.46%   |
| Manjaro                      | 12        | 1.46%   |
| Fedora 39                    | 11        | 1.33%   |
| Fedora 38                    | 11        | 1.33%   |
| Fedora 36                    | 10        | 1.21%   |
| Arch                         | 10        | 1.21%   |
| Debian 12                    | 9         | 1.09%   |
| Debian 11                    | 9         | 1.09%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.97%   |
| OpenMandriva 4.3             | 7         | 0.85%   |
| Linux Mint 19.3              | 7         | 0.85%   |
| KDE neon 20.04               | 7         | 0.85%   |
| Fedora 35                    | 7         | 0.85%   |
| Linux Mint 21.1              | 6         | 0.73%   |
| Kubuntu 20.04                | 6         | 0.73%   |
| Fedora 37                    | 6         | 0.73%   |
| Fedora 34                    | 6         | 0.73%   |
| Ubuntu 23.04                 | 5         | 0.61%   |
| Ubuntu 22.10                 | 5         | 0.61%   |
| Manjaro 20.2.1               | 5         | 0.61%   |
| Linux Mint 20.3              | 5         | 0.61%   |
| Linux Mint 20                | 5         | 0.61%   |
| Linux Mint 19                | 5         | 0.61%   |
| Xubuntu 20.04                | 4         | 0.49%   |
| ROSA 12.1                    | 4         | 0.49%   |
| Pop!_OS 22.04                | 4         | 0.49%   |
| Manjaro 20.0.3               | 4         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ROSA             | 253       | 34.9%   |
| Ubuntu           | 127       | 17.52%  |
| Fedora           | 49        | 6.76%   |
| Linux Mint       | 43        | 5.93%   |
| Endless          | 36        | 4.97%   |
| Manjaro          | 35        | 4.83%   |
| Arch             | 30        | 4.14%   |
| OpenMandriva     | 27        | 3.72%   |
| Debian           | 21        | 2.9%    |
| Kubuntu          | 12        | 1.66%   |
| Xubuntu          | 11        | 1.52%   |
| KDE neon         | 10        | 1.38%   |
| openSUSE         | 9         | 1.24%   |
| LMDE             | 7         | 0.97%   |
| Pop!_OS          | 6         | 0.83%   |
| Elementary       | 6         | 0.83%   |
| Kali             | 5         | 0.69%   |
| Gentoo           | 5         | 0.69%   |
| MX               | 3         | 0.41%   |
| Lubuntu          | 3         | 0.41%   |
| Zorin            | 2         | 0.28%   |
| Ubuntu MATE      | 2         | 0.28%   |
| SteamOS          | 2         | 0.28%   |
| Nobara           | 2         | 0.28%   |
| NixOS            | 2         | 0.28%   |
| Clear Linux      | 2         | 0.28%   |
| ALT Linux        | 2         | 0.28%   |
| Ubuntu Unity     | 1         | 0.14%   |
| Ubuntu Budgie    | 1         | 0.14%   |
| Trisquel         | 1         | 0.14%   |
| Solus            | 1         | 0.14%   |
| Q4OS             | 1         | 0.14%   |
| Peppermint       | 1         | 0.14%   |
| Parrot           | 1         | 0.14%   |
| org.kde.Platform | 1         | 0.14%   |
| Devuan           | 1         | 0.14%   |
| Deepin           | 1         | 0.14%   |
| CentOS           | 1         | 0.14%   |
| Artix            | 1         | 0.14%   |
| Archcraft        | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 37        | 4.09%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 24        | 2.65%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 22        | 2.43%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 21        | 2.32%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 20        | 2.21%   |
| 5.10.14-desktop-1omv4002            | 12        | 1.33%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 12        | 1.33%   |
| 5.4.0-42-generic                    | 11        | 1.22%   |
| 5.4.83-generic-2rosa-x86_64         | 9         | 0.99%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 9         | 0.99%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 9         | 0.99%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 8         | 0.88%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 8         | 0.88%   |
| 4.15.0-desktop-45.1rosa-i586        | 8         | 0.88%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 8         | 0.88%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 7         | 0.77%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 7         | 0.77%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.77%   |
| 5.9.16-1-MANJARO                    | 6         | 0.66%   |
| 5.4.32-generic-2rosa-x86_64         | 6         | 0.66%   |
| 5.16.7-desktop-1omv4003             | 6         | 0.66%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 6         | 0.66%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 6         | 0.66%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 6         | 0.66%   |
| 6.1.58-generic-1rosa2021.1-x86_64   | 5         | 0.55%   |
| 5.8.0-14-generic                    | 5         | 0.55%   |
| 5.3.0-28-generic                    | 5         | 0.55%   |
| 5.15.0-56-generic                   | 5         | 0.55%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 5         | 0.55%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 5         | 0.55%   |
| 4.13.0-32-generic                   | 5         | 0.55%   |
| 5.4.0-26-generic                    | 4         | 0.44%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 4         | 0.44%   |
| 5.15.0-58-generic                   | 4         | 0.44%   |
| 5.15.0-43-generic                   | 4         | 0.44%   |
| 5.11.0-35-generic                   | 4         | 0.44%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 4         | 0.44%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 4         | 0.44%   |
| 6.5.11-300.fc39.x86_64              | 3         | 0.33%   |
| 6.5.0-14-generic                    | 3         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15.0  | 80        | 9.1%    |
| 5.4.0   | 56        | 6.37%   |
| 4.9.60  | 43        | 4.89%   |
| 5.15.0  | 34        | 3.87%   |
| 4.9.20  | 30        | 3.41%   |
| 4.9.124 | 25        | 2.84%   |
| 5.10.74 | 21        | 2.39%   |
| 5.8.0   | 20        | 2.28%   |
| 5.11.0  | 20        | 2.28%   |
| 5.0.0   | 17        | 1.93%   |
| 5.3.0   | 16        | 1.82%   |
| 5.10.0  | 16        | 1.82%   |
| 5.13.0  | 15        | 1.71%   |
| 4.9.9   | 14        | 1.59%   |
| 4.1.34  | 14        | 1.59%   |
| 6.5.0   | 13        | 1.48%   |
| 6.2.0   | 13        | 1.48%   |
| 5.19.0  | 13        | 1.48%   |
| 4.9.155 | 13        | 1.48%   |
| 5.10.14 | 12        | 1.37%   |
| 4.1.38  | 12        | 1.37%   |
| 6.1.0   | 11        | 1.25%   |
| 5.4.83  | 11        | 1.25%   |
| 4.9.76  | 10        | 1.14%   |
| 5.15.75 | 8         | 0.91%   |
| 4.18.0  | 8         | 0.91%   |
| 6.1.20  | 7         | 0.8%    |
| 5.9.16  | 7         | 0.8%    |
| 5.4.32  | 7         | 0.8%    |
| 4.9.41  | 7         | 0.8%    |
| 5.16.7  | 6         | 0.68%   |
| 4.13.0  | 6         | 0.68%   |
| 6.1.58  | 5         | 0.57%   |
| 4.9.95  | 5         | 0.57%   |
| 4.19.0  | 5         | 0.57%   |
| 6.7.4   | 4         | 0.46%   |
| 6.6.2   | 4         | 0.46%   |
| 6.1.1   | 4         | 0.46%   |
| 5.15.79 | 4         | 0.46%   |
| 5.14.0  | 4         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 132       | 15.92%  |
| 5.4     | 83        | 10.01%  |
| 4.15    | 80        | 9.65%   |
| 5.10    | 64        | 7.72%   |
| 5.15    | 63        | 7.6%    |
| 6.1     | 38        | 4.58%   |
| 4.1     | 29        | 3.5%    |
| 5.11    | 27        | 3.26%   |
| 6.2     | 24        | 2.9%    |
| 5.8     | 24        | 2.9%    |
| 6.5     | 23        | 2.77%   |
| 5.13    | 21        | 2.53%   |
| 5.19    | 20        | 2.41%   |
| 5.3     | 19        | 2.29%   |
| 6.6     | 17        | 2.05%   |
| 5.0     | 17        | 2.05%   |
| 5.9     | 15        | 1.81%   |
| 6.0     | 12        | 1.45%   |
| 6.4     | 11        | 1.33%   |
| 6.7     | 10        | 1.21%   |
| 5.18    | 10        | 1.21%   |
| 5.16    | 10        | 1.21%   |
| 6.8     | 9         | 1.09%   |
| 5.14    | 8         | 0.97%   |
| 4.19    | 8         | 0.97%   |
| 4.18    | 8         | 0.97%   |
| 6.3     | 7         | 0.84%   |
| 5.6     | 6         | 0.72%   |
| 4.13    | 6         | 0.72%   |
| 5.17    | 5         | 0.6%    |
| 4.8     | 4         | 0.48%   |
| 5.12    | 3         | 0.36%   |
| 4.16    | 3         | 0.36%   |
| 4.14    | 3         | 0.36%   |
| 5.7     | 2         | 0.24%   |
| 5.5     | 2         | 0.24%   |
| 4.17    | 2         | 0.24%   |
| 4.10    | 2         | 0.24%   |
| 5.1     | 1         | 0.12%   |
| 4.4     | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 648       | 91.91%  |
| i686   | 57        | 8.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 211       | 27.98%  |
| KDE5          | 176       | 23.34%  |
| KDE4          | 162       | 21.49%  |
| Unknown       | 54        | 7.16%   |
| XFCE          | 40        | 5.31%   |
| X-Cinnamon    | 30        | 3.98%   |
| LXQt          | 22        | 2.92%   |
| MATE          | 13        | 1.72%   |
| KDE           | 13        | 1.72%   |
| Cinnamon      | 9         | 1.19%   |
| Pantheon      | 6         | 0.8%    |
| LXDE          | 5         | 0.66%   |
| KDE6          | 5         | 0.66%   |
| i3            | 2         | 0.27%   |
| Unity         | 1         | 0.13%   |
| sway          | 1         | 0.13%   |
| none+xmonad   | 1         | 0.13%   |
| Endless:GNOME | 1         | 0.13%   |
| Deepin        | 1         | 0.13%   |
| Budgie        | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 536       | 74.55%  |
| Wayland | 147       | 20.45%  |
| Unknown | 33        | 4.59%   |
| Tty     | 3         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 195       | 26.14%  |
| SDDM    | 174       | 23.32%  |
| KDM     | 163       | 21.85%  |
| GDM     | 94        | 12.6%   |
| LightDM | 51        | 6.84%   |
| GDM3    | 50        | 6.7%    |
| TDM     | 17        | 2.28%   |
| SLiM    | 1         | 0.13%   |
| GREETD  | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| ru_RU       | 273       | 37.6%   |
| Unknown     | 241       | 33.2%   |
| en_US       | 166       | 22.87%  |
| C           | 12        | 1.65%   |
| be_BY       | 11        | 1.52%   |
| en_GB       | 8         | 1.1%    |
| ru_UA       | 4         | 0.55%   |
| ru_RU.UTF_8 | 4         | 0.55%   |
| ru_BY       | 2         | 0.28%   |
| cv_RU       | 2         | 0.28%   |
| fr_FR       | 1         | 0.14%   |
| en_IN       | 1         | 0.14%   |
| C.utf-8     | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 365       | 51.12%  |
| EFI  | 349       | 48.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 463       | 63.17%  |
| Unknown | 142       | 19.37%  |
| Btrfs   | 80        | 10.91%  |
| Overlay | 33        | 4.5%    |
| Tmpfs   | 9         | 1.23%   |
| Ext3    | 3         | 0.41%   |
| Xfs     | 2         | 0.27%   |
| F2fs    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 272       | 37.06%  |
| Unknown | 254       | 34.6%   |
| MBR     | 208       | 28.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 629       | 87.36%  |
| Yes       | 91        | 12.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 491       | 67.72%  |
| Yes       | 234       | 32.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 152       | 21.9%   |
| Lenovo              | 140       | 20.17%  |
| Hewlett-Packard     | 135       | 19.45%  |
| Acer                | 77        | 11.1%   |
| Dell                | 44        | 6.34%   |
| Samsung Electronics | 36        | 5.19%   |
| MSI                 | 17        | 2.45%   |
| Timi                | 11        | 1.59%   |
| Toshiba             | 10        | 1.44%   |
| HONOR               | 8         | 1.15%   |
| Sony                | 7         | 1.01%   |
| HUAWEI              | 6         | 0.86%   |
| Apple               | 6         | 0.86%   |
| Prestigio           | 4         | 0.58%   |
| Packard Bell        | 4         | 0.58%   |
| Unknown             | 4         | 0.58%   |
| Intel               | 3         | 0.43%   |
| Fujitsu Siemens     | 3         | 0.43%   |
| Fujitsu             | 3         | 0.43%   |
| Valve               | 2         | 0.29%   |
| TECNO               | 2         | 0.29%   |
| Chuwi               | 2         | 0.29%   |
| BenQ                | 2         | 0.29%   |
| XIAOMI              | 1         | 0.14%   |
| ViewSonic           | 1         | 0.14%   |
| Quanta              | 1         | 0.14%   |
| Pegatron            | 1         | 0.14%   |
| Notebook            | 1         | 0.14%   |
| LTD Delovoy Office  | 1         | 0.14%   |
| LG Electronics      | 1         | 0.14%   |
| IBM                 | 1         | 0.14%   |
| HASEE Computer      | 1         | 0.14%   |
| Haier               | 1         | 0.14%   |
| Gigabyte Technology | 1         | 0.14%   |
| Getac               | 1         | 0.14%   |
| Gateway             | 1         | 0.14%   |
| eMachines           | 1         | 0.14%   |
| Dream Machines      | 1         | 0.14%   |
| DNS                 | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo G50-30 80G0                      | 8         | 1.15%   |
| HP Notebook                             | 6         | 0.86%   |
| Unknown                                 | 6         | 0.86%   |
| Timi TM1701                             | 5         | 0.72%   |
| Acer Extensa 5220                       | 5         | 0.72%   |
| Samsung RV413/RV513                     | 4         | 0.58%   |
| Lenovo IdeaPad 320-15IAP 80XR           | 4         | 0.58%   |
| HONOR NBR-WAX9                          | 4         | 0.58%   |
| HP ProBook 455 G1                       | 4         | 0.58%   |
| HP ProBook 450 G5                       | 4         | 0.58%   |
| HP Pavilion g6                          | 4         | 0.58%   |
| HP Laptop 15s-eq2xxx                    | 4         | 0.58%   |
| ASUS X540NV                             | 4         | 0.58%   |
| Acer Aspire E1-571G                     | 4         | 0.58%   |
| Lenovo IdeaPad Z570 HuronRiver Platform | 3         | 0.43%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 3         | 0.43%   |
| Lenovo IdeaPad 3 15IML05 81WB           | 3         | 0.43%   |
| Lenovo IdeaPad 100-15IBY 80MJ           | 3         | 0.43%   |
| Lenovo G570 20079                       | 3         | 0.43%   |
| Lenovo G500 20236                       | 3         | 0.43%   |
| Lenovo B590 20206                       | 3         | 0.43%   |
| Lenovo B50-30 20382                     | 3         | 0.43%   |
| HP Victus by Laptop 16-e0xxx            | 3         | 0.43%   |
| HP Pavilion dv6                         | 3         | 0.43%   |
| HP Pavilion 15                          | 3         | 0.43%   |
| HP 635                                  | 3         | 0.43%   |
| Dell Inspiron 7577                      | 3         | 0.43%   |
| ASUS ZenBook UX431DA_UM431DA            | 3         | 0.43%   |
| ASUS X550CC                             | 3         | 0.43%   |
| ASUS X541UAK                            | 3         | 0.43%   |
| Acer Aspire V3-571G                     | 3         | 0.43%   |
| Acer Aspire E1-531                      | 3         | 0.43%   |
| Acer Aspire 4810T                       | 3         | 0.43%   |
| Valve Jupiter                           | 2         | 0.29%   |
| Timi TM1613                             | 2         | 0.29%   |
| TECNO MEGABOOK T1                       | 2         | 0.29%   |
| Samsung R528/R728                       | 2         | 0.29%   |
| Samsung R508                            | 2         | 0.29%   |
| Samsung 355V4C/356V4C/3445VC/3545VC     | 2         | 0.29%   |
| Samsung 305E4Z/305E5Z/305E7Z            | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 50        | 7.2%    |
| Lenovo IdeaPad        | 49        | 7.06%   |
| HP ProBook            | 39        | 5.62%   |
| Lenovo ThinkPad       | 32        | 4.61%   |
| ASUS VivoBook         | 32        | 4.61%   |
| HP Pavilion           | 30        | 4.32%   |
| Dell Inspiron         | 26        | 3.75%   |
| Acer Extensa          | 14        | 2.02%   |
| HP Laptop             | 13        | 1.87%   |
| ASUS Zenbook          | 10        | 1.44%   |
| ASUS ASUS             | 9         | 1.3%    |
| Toshiba Satellite     | 8         | 1.15%   |
| Lenovo G50-30         | 8         | 1.15%   |
| HP EliteBook          | 8         | 1.15%   |
| ASUS ROG              | 7         | 1.01%   |
| Lenovo Legion         | 6         | 0.86%   |
| HP Notebook           | 6         | 0.86%   |
| Unknown               | 6         | 0.86%   |
| Timi TM1701           | 5         | 0.72%   |
| HP 250                | 5         | 0.72%   |
| Dell Vostro           | 5         | 0.72%   |
| Samsung RV413         | 4         | 0.58%   |
| Lenovo ThinkBook      | 4         | 0.58%   |
| Lenovo G580           | 4         | 0.58%   |
| HONOR NBR-WAX9        | 4         | 0.58%   |
| HP Victus             | 4         | 0.58%   |
| HP Compaq             | 4         | 0.58%   |
| HP 255                | 4         | 0.58%   |
| Dell XPS              | 4         | 0.58%   |
| Dell Latitude         | 4         | 0.58%   |
| ASUS X540NV           | 4         | 0.58%   |
| Acer TravelMate       | 4         | 0.58%   |
| Packard Bell EasyNote | 3         | 0.43%   |
| Lenovo G570           | 3         | 0.43%   |
| Lenovo G500           | 3         | 0.43%   |
| Lenovo B590           | 3         | 0.43%   |
| Lenovo B50-30         | 3         | 0.43%   |
| HP Presario           | 3         | 0.43%   |
| HP Mini               | 3         | 0.43%   |
| HP 635                | 3         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 64        | 9.22%   |
| 2013 | 63        | 9.08%   |
| 2011 | 62        | 8.93%   |
| 2018 | 55        | 7.93%   |
| 2017 | 55        | 7.93%   |
| 2020 | 53        | 7.64%   |
| 2021 | 50        | 7.2%    |
| 2019 | 40        | 5.76%   |
| 2010 | 39        | 5.62%   |
| 2009 | 35        | 5.04%   |
| 2014 | 33        | 4.76%   |
| 2015 | 32        | 4.61%   |
| 2022 | 28        | 4.03%   |
| 2008 | 26        | 3.75%   |
| 2016 | 24        | 3.46%   |
| 2007 | 21        | 3.03%   |
| 2023 | 8         | 1.15%   |
| 2006 | 3         | 0.43%   |
| 2005 | 2         | 0.29%   |
| 2024 | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 694       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 651       | 93.27%  |
| Enabled  | 47        | 6.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 694       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 204       | 28.57%  |
| 3.01-4.0    | 187       | 26.19%  |
| 8.01-16.0   | 98        | 13.73%  |
| 16.01-24.0  | 91        | 12.75%  |
| 1.01-2.0    | 64        | 8.96%   |
| 32.01-64.0  | 30        | 4.2%    |
| 2.01-3.0    | 23        | 3.22%   |
| 0.51-1.0    | 13        | 1.82%   |
| 24.01-32.0  | 3         | 0.42%   |
| 64.01-256.0 | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 251       | 31.57%  |
| 2.01-3.0   | 161       | 20.25%  |
| 0.51-1.0   | 157       | 19.75%  |
| 4.01-8.0   | 110       | 13.84%  |
| 3.01-4.0   | 82        | 10.31%  |
| 8.01-16.0  | 20        | 2.52%   |
| 0.01-0.5   | 11        | 1.38%   |
| 16.01-24.0 | 2         | 0.25%   |
| 24.01-32.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 534       | 74.79%  |
| 2      | 159       | 22.27%  |
| 3      | 18        | 2.52%   |
| 0      | 2         | 0.28%   |
| 4      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 440       | 62.59%  |
| Yes       | 263       | 37.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 560       | 80.58%  |
| No        | 135       | 19.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 689       | 99.28%  |
| No        | 5         | 0.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 552       | 78.3%   |
| No        | 153       | 21.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Belarus | 694       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Minsk        | 360       | 47%     |
| Vitebsk      | 72        | 9.4%    |
| Gomel        | 61        | 7.96%   |
| Mogilev      | 40        | 5.22%   |
| Brest        | 38        | 4.96%   |
| Hrodna       | 34        | 4.44%   |
| Babruysk     | 19        | 2.48%   |
| Orsha        | 17        | 2.22%   |
| Borisov      | 13        | 1.7%    |
| Polatsk      | 10        | 1.31%   |
| Zhodzina     | 7         | 0.91%   |
| Mazyr        | 7         | 0.91%   |
| Lida         | 6         | 0.78%   |
| Zhlobin      | 5         | 0.65%   |
| Salihorsk    | 4         | 0.52%   |
| Drahichyn    | 4         | 0.52%   |
| Bogushevichi | 4         | 0.52%   |
| Navapolatsk  | 3         | 0.39%   |
| Klyetsk      | 3         | 0.39%   |
| Baranovichi  | 3         | 0.39%   |
| Baran'       | 3         | 0.39%   |
| Aleksandrovo | 3         | 0.39%   |
| Smalyavichy  | 2         | 0.26%   |
| Slutsk       | 2         | 0.26%   |
| Pinsk        | 2         | 0.26%   |
| Pastavy      | 2         | 0.26%   |
| Maladzyechna | 2         | 0.26%   |
| Loshnitsa    | 2         | 0.26%   |
| Krupki       | 2         | 0.26%   |
| Kolodishchi  | 2         | 0.26%   |
| Ivanava      | 2         | 0.26%   |
| Fedorovka    | 2         | 0.26%   |
| Borovlyany   | 2         | 0.26%   |
| Zaslawye     | 1         | 0.13%   |
| Vilyeyka     | 1         | 0.13%   |
| Vawkavysk    | 1         | 0.13%   |
| Syenitsa     | 1         | 0.13%   |
| Syanno       | 1         | 0.13%   |
| Snitovo      | 1         | 0.13%   |
| Slonim       | 1         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 120       | 151    | 13.9%   |
| WDC                         | 112       | 158    | 12.98%  |
| Seagate                     | 109       | 148    | 12.63%  |
| Toshiba                     | 83        | 105    | 9.62%   |
| Kingston                    | 57        | 72     | 6.6%    |
| Hitachi                     | 51        | 59     | 5.91%   |
| HGST                        | 47        | 60     | 5.45%   |
| SK hynix                    | 38        | 44     | 4.4%    |
| SanDisk                     | 28        | 35     | 3.24%   |
| Intel                       | 28        | 63     | 3.24%   |
| Unknown                     | 22        | 28     | 2.55%   |
| Micron Technology           | 19        | 26     | 2.2%    |
| Crucial                     | 16        | 22     | 1.85%   |
| Fujitsu                     | 10        | 17     | 1.16%   |
| KIOXIA                      | 9         | 34     | 1.04%   |
| Patriot                     | 8         | 10     | 0.93%   |
| Gigabyte Technology         | 7         | 9      | 0.81%   |
| A-DATA Technology           | 7         | 8      | 0.81%   |
| Transcend                   | 6         | 8      | 0.7%    |
| SPCC                        | 6         | 8      | 0.7%    |
| Netac                       | 6         | 8      | 0.7%    |
| KingSpec                    | 6         | 12     | 0.7%    |
| Phison Electronics          | 4         | 4      | 0.46%   |
| GOODRAM                     | 4         | 4      | 0.46%   |
| Apple                       | 4         | 4      | 0.46%   |
| Silicon Motion              | 3         | 3      | 0.35%   |
| Lenovo                      | 3         | 6      | 0.35%   |
| XrayDisk                    | 2         | 2      | 0.23%   |
| TO Exter                    | 2         | 3      | 0.23%   |
| Smartbuy                    | 2         | 2      | 0.23%   |
| Plextor                     | 2         | 2      | 0.23%   |
| Phison                      | 2         | 2      | 0.23%   |
| OCZ                         | 2         | 2      | 0.23%   |
| LITEONIT                    | 2         | 2      | 0.23%   |
| Lexar                       | 2         | 2      | 0.23%   |
| Kingston Technology Company | 2         | 2      | 0.23%   |
| KingDian                    | 2         | 4      | 0.23%   |
| JMicron Technology          | 2         | 2      | 0.23%   |
| Zheino                      | 1         | 2      | 0.12%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                          | 27        | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB                    | 21        | 2.36%   |
| Seagate ST500LT012-1DG142 500GB                   | 17        | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 12        | 1.35%   |
| HGST HTS545050A7E680 500GB                        | 11        | 1.24%   |
| Seagate ST9320325AS 320GB                         | 10        | 1.12%   |
| Kingston SA400S37120G 120GB SSD                   | 10        | 1.12%   |
| Toshiba MQ04ABF100 1TB                            | 9         | 1.01%   |
| Samsung SSD 860 EVO 250GB                         | 9         | 1.01%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 8         | 0.9%    |
| SK hynix NVMe SSD Drive 512GB                     | 8         | 0.9%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 8         | 0.9%    |
| HGST HTS721010A9E630 1TB                          | 8         | 0.9%    |
| Crucial CT120BX500SSD1 120GB                      | 8         | 0.9%    |
| Samsung SSD 860 EVO 500GB                         | 7         | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 7         | 0.79%   |
| Kingston SA400S37240G 240GB SSD                   | 7         | 0.79%   |
| Intel SSDPEKNU512GZ 512GB                         | 7         | 0.79%   |
| Hitachi HTS545050B9A300 500GB                     | 7         | 0.79%   |
| HGST HTS541010A9E680 1TB                          | 7         | 0.79%   |
| Toshiba MQ01ABD100 1TB                            | 6         | 0.67%   |
| Toshiba MQ01ABD075 752GB                          | 6         | 0.67%   |
| Toshiba MQ01ABD032 320GB                          | 6         | 0.67%   |
| Seagate ST9250315AS 250GB                         | 6         | 0.67%   |
| Hitachi HTS547575A9E384 752GB                     | 6         | 0.67%   |
| Hitachi HTS543232A7A384 320GB                     | 6         | 0.67%   |
| HGST HTS541010B7E610 1TB                          | 6         | 0.67%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 5         | 0.56%   |
| Seagate ST9500325AS 500GB                         | 5         | 0.56%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 5         | 0.56%   |
| Intel SSDPEKNW512G8H 512GB                        | 5         | 0.56%   |
| Hitachi HTS545032B9A300 320GB                     | 5         | 0.56%   |
| SK hynix NVMe SSD Drive 256GB                     | 4         | 0.45%   |
| Seagate ST750LM022 HN-M750MBB 752GB               | 4         | 0.45%   |
| Seagate ST500LT012-9WS142 500GB                   | 4         | 0.45%   |
| SanDisk NVMe SSD Drive 256GB                      | 4         | 0.45%   |
| Samsung SSD 850 EVO 250GB                         | 4         | 0.45%   |
| Samsung NVMe SSD Drive 512GB                      | 4         | 0.45%   |
| Samsung HM500JI 500GB                             | 4         | 0.45%   |
| Hitachi HTS547550A9E384 500GB                     | 4         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 108       | 147    | 26.87%  |
| WDC                 | 95        | 140    | 23.63%  |
| Toshiba             | 74        | 92     | 18.41%  |
| Hitachi             | 51        | 59     | 12.69%  |
| HGST                | 47        | 60     | 11.69%  |
| Samsung Electronics | 11        | 24     | 2.74%   |
| Fujitsu             | 10        | 17     | 2.49%   |
| TO Exter            | 2         | 3      | 0.5%    |
| JMicron Technology  | 2         | 2      | 0.5%    |
| SAGE                | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 53     | 21.13%  |
| Kingston            | 41        | 51     | 19.25%  |
| Crucial             | 16        | 22     | 7.51%   |
| SanDisk             | 13        | 20     | 6.1%    |
| SK hynix            | 8         | 10     | 3.76%   |
| Patriot             | 8         | 10     | 3.76%   |
| Gigabyte Technology | 7         | 9      | 3.29%   |
| Transcend           | 6         | 8      | 2.82%   |
| SPCC                | 6         | 8      | 2.82%   |
| KingSpec            | 6         | 12     | 2.82%   |
| A-DATA Technology   | 6         | 7      | 2.82%   |
| Netac               | 5         | 7      | 2.35%   |
| WDC                 | 4         | 4      | 1.88%   |
| GOODRAM             | 4         | 4      | 1.88%   |
| Toshiba             | 3         | 3      | 1.41%   |
| Intel               | 3         | 3      | 1.41%   |
| XrayDisk            | 2         | 2      | 0.94%   |
| Smartbuy            | 2         | 2      | 0.94%   |
| Plextor             | 2         | 2      | 0.94%   |
| OCZ                 | 2         | 2      | 0.94%   |
| LITEONIT            | 2         | 2      | 0.94%   |
| Lexar               | 2         | 2      | 0.94%   |
| KingDian            | 2         | 4      | 0.94%   |
| Zheino              | 1         | 2      | 0.47%   |
| Union Memory        | 1         | 1      | 0.47%   |
| Team                | 1         | 1      | 0.47%   |
| T-FORCE             | 1         | 1      | 0.47%   |
| Seagate             | 1         | 1      | 0.47%   |
| PNY                 | 1         | 5      | 0.47%   |
| OSCOO               | 1         | 1      | 0.47%   |
| OCZ-VERTEX          | 1         | 1      | 0.47%   |
| Micron Technology   | 1         | 1      | 0.47%   |
| MicroFrom           | 1         | 1      | 0.47%   |
| LT                  | 1         | 1      | 0.47%   |
| External            | 1         | 2      | 0.47%   |
| Corsair             | 1         | 3      | 0.47%   |
| China               | 1         | 3      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |
| Apacer              | 1         | 1      | 0.47%   |
| AMD                 | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 389       | 546    | 46.98%  |
| NVMe    | 210       | 314    | 25.36%  |
| SSD     | 201       | 275    | 24.28%  |
| MMC     | 22        | 29     | 2.66%   |
| Unknown | 6         | 6      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 505       | 810    | 67.24%  |
| NVMe | 210       | 313    | 27.96%  |
| MMC  | 22        | 29     | 2.93%   |
| SAS  | 14        | 18     | 1.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 404       | 604    | 72.14%  |
| 0.51-1.0   | 152       | 213    | 27.14%  |
| 1.01-2.0   | 4         | 4      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 208       | 27.23%  |
| 101-250        | 192       | 25.13%  |
| 501-1000       | 99        | 12.96%  |
| 1-20           | 76        | 9.95%   |
| 51-100         | 61        | 7.98%   |
| 21-50          | 55        | 7.2%    |
| 1001-2000      | 42        | 5.5%    |
| Unknown        | 20        | 2.62%   |
| 2001-3000      | 6         | 0.79%   |
| More than 3000 | 5         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 339       | 44.03%  |
| 21-50     | 137       | 17.79%  |
| 51-100    | 87        | 11.3%   |
| 101-250   | 86        | 11.17%  |
| 251-500   | 60        | 7.79%   |
| 501-1000  | 28        | 3.64%   |
| Unknown   | 20        | 2.6%    |
| 1001-2000 | 12        | 1.56%   |
| 0         | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 7         | 9      | 5.22%   |
| Seagate ST9320325AS 320GB          | 6         | 7      | 4.48%   |
| HGST HTS545050A7E680 500GB         | 6         | 7      | 4.48%   |
| Toshiba MQ01ABF050 500GB           | 4         | 5      | 2.99%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 2.99%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 2.99%   |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 2.24%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 2.24%   |
| Seagate ST9500325AS 500GB          | 3         | 4      | 2.24%   |
| Seagate ST500LT012-9WS142 500GB    | 3         | 3      | 2.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 4      | 2.24%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 2.24%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 1.49%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 2      | 1.49%   |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 1.49%   |
| Hitachi HTS722010K9SA00 100GB      | 2         | 2      | 1.49%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.49%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 2      | 1.49%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 2      | 1.49%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 1.49%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 1.49%   |
| WDC WD5000LPVX-60V0TT0 500GB       | 1         | 2      | 0.75%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 0.75%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 0.75%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 0.75%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 2      | 0.75%   |
| WDC WD3200BEVT-60A23T0 320GB       | 1         | 1      | 0.75%   |
| WDC WD3200BEVT-22A0RT0 320GB       | 1         | 1      | 0.75%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 1      | 0.75%   |
| WDC WD3200BEKT-60F3T1 320GB        | 1         | 1      | 0.75%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 1      | 0.75%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 0.75%   |
| WDC WD2500BEVT-22A23T0 250GB       | 1         | 1      | 0.75%   |
| WDC WD2500BEVT-00A23T0 250GB       | 1         | 1      | 0.75%   |
| WDC WD2500BEKT-60A25T1 250GB       | 1         | 1      | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1      | 0.75%   |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 1      | 0.75%   |
| Toshiba MK6476GSX 640GB            | 1         | 1      | 0.75%   |
| Toshiba MK5065GSX 500GB            | 1         | 1      | 0.75%   |
| Toshiba MK5055GSX 500GB            | 1         | 2      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 40     | 26.12%  |
| Hitachi             | 31        | 36     | 23.13%  |
| WDC                 | 20        | 26     | 14.93%  |
| Toshiba             | 15        | 20     | 11.19%  |
| HGST                | 12        | 13     | 8.96%   |
| Samsung Electronics | 5         | 12     | 3.73%   |
| Fujitsu             | 4         | 6      | 2.99%   |
| SK hynix            | 2         | 2      | 1.49%   |
| Kingston            | 2         | 2      | 1.49%   |
| SanDisk             | 1         | 1      | 0.75%   |
| PNY                 | 1         | 4      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| Micron Technology   | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 6      | 0.75%   |
| Crucial             | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 40     | 29.17%  |
| Hitachi             | 31        | 36     | 25.83%  |
| WDC                 | 20        | 26     | 16.67%  |
| Toshiba             | 15        | 20     | 12.5%   |
| HGST                | 12        | 13     | 10%     |
| Fujitsu             | 4         | 6      | 3.33%   |
| Samsung Electronics | 3         | 10     | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 118       | 151    | 89.39%  |
| SSD  | 13        | 21     | 9.85%   |
| NVMe | 1         | 1      | 0.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB      | 1         | 1      | 20%     |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 20%     |
| Samsung Electronics HM500JI 500GB | 1         | 1      | 20%     |
| HGST HTS545050B7E660 500GB        | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 390       | 633    | 51.11%  |
| Detected | 237       | 359    | 31.06%  |
| Malfunc  | 131       | 173    | 17.17%  |
| Failed   | 5         | 5      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 498       | 61.33%  |
| AMD                                     | 109       | 13.42%  |
| Samsung Electronics                     | 67        | 8.25%   |
| SK hynix                                | 30        | 3.69%   |
| SanDisk                                 | 27        | 3.33%   |
| Micron Technology                       | 18        | 2.22%   |
| Kingston Technology Company             | 18        | 2.22%   |
| KIOXIA                                  | 9         | 1.11%   |
| Toshiba America Info Systems            | 8         | 0.99%   |
| Phison Electronics                      | 6         | 0.74%   |
| Silicon Motion                          | 3         | 0.37%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.37%   |
| Lenovo                                  | 3         | 0.37%   |
| Nvidia                                  | 2         | 0.25%   |
| JMicron Technology                      | 2         | 0.25%   |
| Apple                                   | 2         | 0.25%   |
| Solid State Storage Technology          | 1         | 0.12%   |
| Silicon Image                           | 1         | 0.12%   |
| Shenzhen Unionmemory Information System | 1         | 0.12%   |
| O2 Micro                                | 1         | 0.12%   |
| Netac Technology                        | 1         | 0.12%   |
| Biwin Storage Technology                | 1         | 0.12%   |
| ADATA Technology                        | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 72        | 8.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 69        | 7.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 45        | 5.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 36        | 4.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 33        | 3.73%   |
| Intel Volume Management Device NVMe RAID Controller                              | 28        | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 26        | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 25        | 2.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 24        | 2.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 23        | 2.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 2.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 20        | 2.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 2.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 17        | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 16        | 1.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 1.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 1.47%   |
| Intel Tiger Lake-LP SATA Controller                                              | 13        | 1.47%   |
| Intel SSD 660P Series                                                            | 12        | 1.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 1.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 1.36%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 11        | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 11        | 1.24%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 10        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 9         | 1.02%   |
| SK hynix BC511 NVMe SSD                                                          | 8         | 0.9%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 7         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 7         | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.79%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 7         | 0.79%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 7         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 7         | 0.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 0.68%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 6         | 0.68%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 6         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 530       | 62.43%  |
| NVMe | 211       | 24.85%  |
| IDE  | 66        | 7.77%   |
| RAID | 42        | 4.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 546       | 78.67%  |
| AMD    | 148       | 21.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 2.29%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 15        | 2.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 1.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.43%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 1.43%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.15%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 1.15%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 1%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1%      |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 1%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 1%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1%      |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.86%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.86%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 0.86%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.86%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 6         | 0.86%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 0.72%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.72%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 5         | 0.72%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.72%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 5         | 0.72%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.72%   |
| Intel Celeron CPU B820 @ 1.70GHz              | 5         | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.72%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.72%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.72%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 4         | 0.57%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 111       | 15.93%  |
| Intel Core i7                        | 90        | 12.91%  |
| Intel Celeron                        | 71        | 10.19%  |
| Intel Core i3                        | 70        | 10.04%  |
| Other                                | 56        | 8.03%   |
| Intel Pentium                        | 48        | 6.89%   |
| AMD Ryzen 5                          | 37        | 5.31%   |
| Intel Core 2 Duo                     | 33        | 4.73%   |
| Intel Atom                           | 28        | 4.02%   |
| AMD Ryzen 7                          | 21        | 3.01%   |
| AMD E                                | 13        | 1.87%   |
| AMD A4                               | 12        | 1.72%   |
| Intel Pentium Dual-Core              | 10        | 1.43%   |
| AMD A6                               | 9         | 1.29%   |
| AMD E1                               | 8         | 1.15%   |
| Intel Pentium Silver                 | 6         | 0.86%   |
| AMD Ryzen 3                          | 6         | 0.86%   |
| Intel Pentium Dual                   | 5         | 0.72%   |
| Intel Genuine                        | 5         | 0.72%   |
| Intel Celeron Dual-Core              | 5         | 0.72%   |
| AMD Athlon II                        | 5         | 0.72%   |
| AMD A8                               | 5         | 0.72%   |
| AMD A10                              | 5         | 0.72%   |
| AMD Turion II                        | 4         | 0.57%   |
| AMD Athlon                           | 4         | 0.57%   |
| Intel Core i9                        | 3         | 0.43%   |
| Intel Core 2 Solo                    | 3         | 0.43%   |
| AMD Phenom II                        | 3         | 0.43%   |
| AMD E2                               | 3         | 0.43%   |
| Intel Pentium M                      | 2         | 0.29%   |
| AMD Turion 64 X2 Mobile              | 2         | 0.29%   |
| AMD Ryzen 9                          | 2         | 0.29%   |
| Intel Core m3                        | 1         | 0.14%   |
| Intel Core Duo                       | 1         | 0.14%   |
| Intel Core                           | 1         | 0.14%   |
| Intel Celeron M                      | 1         | 0.14%   |
| AMD V140                             | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.14%   |
| AMD Turion II Ultra Dual-Core Mobile | 1         | 0.14%   |
| AMD Turion II Dual-Core              | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 367       | 52.58%  |
| 4       | 193       | 27.65%  |
| 6       | 43        | 6.16%   |
| 1       | 39        | 5.59%   |
| 8       | 30        | 4.3%    |
| Unknown | 9         | 1.29%   |
| 10      | 7         | 1%      |
| 12      | 6         | 0.86%   |
| 14      | 3         | 0.43%   |
| 16      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 694       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 430       | 61.43%  |
| 1       | 261       | 37.29%  |
| Unknown | 9         | 1.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 664       | 95.68%  |
| 32-bit         | 15        | 2.16%   |
| Unknown        | 15        | 2.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 146       | 20.22%  |
| 0x206a7    | 55        | 7.62%   |
| 0x306a9    | 44        | 6.09%   |
| 0x1067a    | 29        | 4.02%   |
| 0x806ea    | 25        | 3.46%   |
| 0x806c1    | 22        | 3.05%   |
| 0x30678    | 21        | 2.91%   |
| 0x806ec    | 18        | 2.49%   |
| 0x40651    | 16        | 2.22%   |
| 0x906ea    | 14        | 1.94%   |
| 0x406e3    | 14        | 1.94%   |
| 0x106ca    | 14        | 1.94%   |
| 0x05000119 | 13        | 1.8%    |
| 0x6fd      | 12        | 1.66%   |
| 0x306d4    | 12        | 1.66%   |
| 0x306c3    | 12        | 1.66%   |
| 0x010000c8 | 12        | 1.66%   |
| 0x506c9    | 11        | 1.52%   |
| 0x08608103 | 10        | 1.39%   |
| 0x08108102 | 10        | 1.39%   |
| 0x06001119 | 10        | 1.39%   |
| 0x806e9    | 9         | 1.25%   |
| 0x706a1    | 9         | 1.25%   |
| 0x906e9    | 8         | 1.11%   |
| 0x0a50000c | 8         | 1.11%   |
| 0x08600104 | 8         | 1.11%   |
| 0x706e5    | 7         | 0.97%   |
| 0x20652    | 7         | 0.97%   |
| 0x08600106 | 7         | 0.97%   |
| 0x906a3    | 6         | 0.83%   |
| 0x106c2    | 6         | 0.83%   |
| 0x10661    | 6         | 0.83%   |
| 0x0700010f | 6         | 0.83%   |
| 0x6fb      | 5         | 0.69%   |
| 0x406c4    | 5         | 0.69%   |
| 0x30661    | 5         | 0.69%   |
| 0x20655    | 5         | 0.69%   |
| 0x10676    | 5         | 0.69%   |
| 0x07030105 | 5         | 0.69%   |
| 0x06006705 | 5         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 111       | 15.93%  |
| SandyBridge       | 60        | 8.61%   |
| IvyBridge         | 55        | 7.89%   |
| Penryn            | 41        | 5.88%   |
| Silvermont        | 35        | 5.02%   |
| Haswell           | 35        | 5.02%   |
| Unknown           | 31        | 4.45%   |
| TigerLake         | 28        | 4.02%   |
| Core              | 28        | 4.02%   |
| Skylake           | 24        | 3.44%   |
| Bonnell           | 24        | 3.44%   |
| Zen 2             | 19        | 2.73%   |
| K10               | 16        | 2.3%    |
| Goldmont plus     | 16        | 2.3%    |
| Bobcat            | 16        | 2.3%    |
| Zen+              | 15        | 2.15%   |
| Icelake           | 15        | 2.15%   |
| Alderlake Hybrid  | 15        | 2.15%   |
| Goldmont          | 14        | 2.01%   |
| Piledriver        | 13        | 1.87%   |
| Broadwell         | 13        | 1.87%   |
| Westmere          | 12        | 1.72%   |
| Zen 3             | 11        | 1.58%   |
| Excavator         | 8         | 1.15%   |
| Zen               | 6         | 0.86%   |
| Puma              | 6         | 0.86%   |
| K10 Llano         | 6         | 0.86%   |
| Jaguar            | 6         | 0.86%   |
| P6                | 5         | 0.72%   |
| CometLake         | 5         | 0.72%   |
| Nehalem           | 3         | 0.43%   |
| K8 Hammer         | 2         | 0.29%   |
| Tremont           | 1         | 0.14%   |
| Meteorlake Hybrid | 1         | 0.14%   |
| K8 & K10 hybrid   | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 495       | 53.23%  |
| Nvidia                           | 223       | 23.98%  |
| AMD                              | 209       | 22.47%  |
| Silicon Integrated Systems [SiS] | 3         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 57        | 5.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 52        | 5.3%    |
| Intel UHD Graphics 620                                                                   | 32        | 3.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 2.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 2.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.34%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 1.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 1.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.43%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 14        | 1.43%   |
| AMD Lucienne                                                                             | 14        | 1.43%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.33%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 13        | 1.33%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.22%   |
| Intel HD Graphics 630                                                                    | 11        | 1.12%   |
| Intel HD Graphics 620                                                                    | 11        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.92%   |
| Intel HD Graphics 500                                                                    | 9         | 0.92%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 9         | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.82%   |
| Nvidia GM108M [GeForce MX110]                                                            | 8         | 0.82%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.82%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 8         | 0.82%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 8         | 0.82%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 8         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 278       | 40%     |
| Intel + Nvidia | 173       | 24.89%  |
| 1 x AMD        | 119       | 17.12%  |
| Intel + AMD    | 44        | 6.33%   |
| 1 x Nvidia     | 31        | 4.46%   |
| 2 x AMD        | 28        | 4.03%   |
| AMD + Nvidia   | 18        | 2.59%   |
| 1 x SiS        | 3         | 0.43%   |
| 2 x Intel      | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 590       | 83.45%  |
| Proprietary | 93        | 13.15%  |
| Unknown     | 24        | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 324       | 45%     |
| 1.01-2.0   | 160       | 22.22%  |
| 0.01-0.5   | 138       | 19.17%  |
| 3.01-4.0   | 46        | 6.39%   |
| 0.51-1.0   | 43        | 5.97%   |
| 5.01-6.0   | 6         | 0.83%   |
| 7.01-8.0   | 1         | 0.14%   |
| 2.01-3.0   | 1         | 0.14%   |
| 8.01-16.0  | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 150       | 20.35%  |
| BOE                     | 107       | 14.52%  |
| Chimei Innolux          | 97        | 13.16%  |
| LG Display              | 91        | 12.35%  |
| Samsung Electronics     | 90        | 12.21%  |
| Chi Mei Optoelectronics | 51        | 6.92%   |
| PANDA                   | 18        | 2.44%   |
| Goldstar                | 18        | 2.44%   |
| Dell                    | 16        | 2.17%   |
| LG Philips              | 10        | 1.36%   |
| Lenovo                  | 9         | 1.22%   |
| CPT                     | 9         | 1.22%   |
| HannStar                | 8         | 1.09%   |
| Philips                 | 7         | 0.95%   |
| Apple                   | 7         | 0.95%   |
| Sony                    | 6         | 0.81%   |
| Sharp                   | 6         | 0.81%   |
| Hewlett-Packard         | 6         | 0.81%   |
| Unknown                 | 3         | 0.41%   |
| Iiyama                  | 3         | 0.41%   |
| BenQ                    | 3         | 0.41%   |
| ViewSonic               | 2         | 0.27%   |
| Valve                   | 2         | 0.27%   |
| TMX                     | 2         | 0.27%   |
| LGD                     | 2         | 0.27%   |
| CSO                     | 2         | 0.27%   |
| Seiko/Epson             | 1         | 0.14%   |
| Quanta Display          | 1         | 0.14%   |
| PCL                     | 1         | 0.14%   |
| MiTAC                   | 1         | 0.14%   |
| Mi                      | 1         | 0.14%   |
| Lenovo Group Limited    | 1         | 0.14%   |
| KDC                     | 1         | 0.14%   |
| ITE                     | 1         | 0.14%   |
| InnoLux Display         | 1         | 0.14%   |
| InfoVision              | 1         | 0.14%   |
| AOC                     | 1         | 0.14%   |
| Ancor Communications    | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 2.02%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 12        | 1.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 1.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.94%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 7         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.81%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.81%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.81%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.81%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.81%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 5         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 5         | 0.67%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 5         | 0.67%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.67%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.67%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 4         | 0.54%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.54%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.54%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.54%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 272       | 37.99%  |
| 1366x768 (WXGA)    | 254       | 35.47%  |
| 1600x900 (HD+)     | 42        | 5.87%   |
| 1280x800 (WXGA)    | 28        | 3.91%   |
| 3840x2160 (4K)     | 23        | 3.21%   |
| 1024x600           | 20        | 2.79%   |
| 1440x900 (WXGA+)   | 12        | 1.68%   |
| 2560x1440 (QHD)    | 11        | 1.54%   |
| 2560x1600          | 8         | 1.12%   |
| 1920x1200 (WUXGA)  | 7         | 0.98%   |
| 2880x1800          | 6         | 0.84%   |
| 1680x1050 (WSXGA+) | 4         | 0.56%   |
| 1280x1024 (SXGA)   | 4         | 0.56%   |
| 3200x2000          | 3         | 0.42%   |
| 800x1280           | 2         | 0.28%   |
| 3840x2400          | 2         | 0.28%   |
| 2880x1620          | 2         | 0.28%   |
| 2288x1287          | 2         | 0.28%   |
| 2160x1440          | 2         | 0.28%   |
| 1360x768           | 2         | 0.28%   |
| 3840x1080          | 1         | 0.14%   |
| 3440x1440          | 1         | 0.14%   |
| 3072x1920          | 1         | 0.14%   |
| 2560x1080          | 1         | 0.14%   |
| 2240x1400          | 1         | 0.14%   |
| 2048x1536          | 1         | 0.14%   |
| 2048x1152          | 1         | 0.14%   |
| 1680x945           | 1         | 0.14%   |
| 1024x768 (XGA)     | 1         | 0.14%   |
| Unknown            | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 428       | 57.99%  |
| 17      | 70        | 9.49%   |
| 13      | 55        | 7.45%   |
| 14      | 48        | 6.5%    |
| 10      | 20        | 2.71%   |
| 24      | 16        | 2.17%   |
| 16      | 16        | 2.17%   |
| 23      | 15        | 2.03%   |
| 21      | 15        | 2.03%   |
| 27      | 9         | 1.22%   |
| Unknown | 8         | 1.08%   |
| 31      | 5         | 0.68%   |
| 11      | 5         | 0.68%   |
| 72      | 3         | 0.41%   |
| 18      | 3         | 0.41%   |
| 12      | 3         | 0.41%   |
| 142     | 2         | 0.27%   |
| 40      | 2         | 0.27%   |
| 34      | 2         | 0.27%   |
| 20      | 2         | 0.27%   |
| 8       | 2         | 0.27%   |
| 7       | 2         | 0.27%   |
| 54      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 26      | 1         | 0.14%   |
| 25      | 1         | 0.14%   |
| 22      | 1         | 0.14%   |
| 19      | 1         | 0.14%   |
| 9       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 514       | 70.12%  |
| 351-400        | 79        | 10.78%  |
| 201-300        | 52        | 7.09%   |
| 501-600        | 37        | 5.05%   |
| 401-500        | 20        | 2.73%   |
| Unknown        | 8         | 1.09%   |
| 601-700        | 7         | 0.95%   |
| 1501-2000      | 3         | 0.41%   |
| 101-200        | 3         | 0.41%   |
| More than 2000 | 2         | 0.27%   |
| 801-900        | 2         | 0.27%   |
| 701-800        | 2         | 0.27%   |
| 1001-1500      | 2         | 0.27%   |
| 1-100          | 2         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 596       | 86.63%  |
| 16/10   | 70        | 10.17%  |
| Unknown | 7         | 1.02%   |
| 5/4     | 4         | 0.58%   |
| 4/3     | 2         | 0.29%   |
| 3/2     | 2         | 0.29%   |
| 21/9    | 2         | 0.29%   |
| 1.00    | 2         | 0.29%   |
| 0.67    | 2         | 0.29%   |
| 0.62    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 434       | 58.81%  |
| 81-90          | 82        | 11.11%  |
| 121-130        | 52        | 7.05%   |
| 201-250        | 34        | 4.61%   |
| 71-80          | 21        | 2.85%   |
| 41-50          | 21        | 2.85%   |
| 131-140        | 15        | 2.03%   |
| 301-350        | 10        | 1.36%   |
| 251-300        | 10        | 1.36%   |
| 111-120        | 9         | 1.22%   |
| Unknown        | 8         | 1.08%   |
| More than 1000 | 7         | 0.95%   |
| 351-500        | 7         | 0.95%   |
| 151-200        | 7         | 0.95%   |
| 141-150        | 6         | 0.81%   |
| 51-60          | 5         | 0.68%   |
| 1-40           | 4         | 0.54%   |
| 61-70          | 3         | 0.41%   |
| 501-1000       | 2         | 0.27%   |
| 91-100         | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 277       | 38.21%  |
| 121-160       | 259       | 35.72%  |
| 51-100        | 118       | 16.28%  |
| 161-240       | 34        | 4.69%   |
| More than 240 | 19        | 2.62%   |
| 1-50          | 10        | 1.38%   |
| Unknown       | 8         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 617       | 87.52%  |
| 2     | 66        | 9.36%   |
| 0     | 16        | 2.27%   |
| 3     | 6         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 401       | 35.87%  |
| Intel                             | 238       | 21.29%  |
| Qualcomm Atheros                  | 235       | 21.02%  |
| Broadcom                          | 105       | 9.39%   |
| Marvell Technology Group          | 25        | 2.24%   |
| Ralink                            | 23        | 2.06%   |
| MediaTek                          | 23        | 2.06%   |
| Broadcom Limited                  | 17        | 1.52%   |
| TP-Link                           | 6         | 0.54%   |
| Qualcomm                          | 5         | 0.45%   |
| Huawei Technologies               | 5         | 0.45%   |
| Ralink Technology                 | 4         | 0.36%   |
| JMicron Technology                | 4         | 0.36%   |
| Sierra Wireless                   | 3         | 0.27%   |
| FIBOCOM                           | 3         | 0.27%   |
| Attansic Technology               | 3         | 0.27%   |
| Xiaomi                            | 2         | 0.18%   |
| Hewlett-Packard                   | 2         | 0.18%   |
| ASIX Electronics                  | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| Philips (or NXP)                  | 1         | 0.09%   |
| Nvidia                            | 1         | 0.09%   |
| Mercucys                          | 1         | 0.09%   |
| Lenovo                            | 1         | 0.09%   |
| Ericsson Business Mobile Networks | 1         | 0.09%   |
| D-Link                            | 1         | 0.09%   |
| Aquantia                          | 1         | 0.09%   |
| Apple                             | 1         | 0.09%   |
| Unknown                           | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 252       | 19.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 98        | 7.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 56        | 4.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 3.08%   |
| Intel Wireless 8265 / 8275                                              | 40        | 3.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 2.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 1.54%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 1.39%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 0.85%   |
| Intel Wireless 7265                                                     | 10        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 9         | 0.69%   |
| Intel Wireless 7260                                                     | 9         | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 7         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 7         | 0.54%   |
| Intel WiFi Link 5100                                                    | 7         | 0.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.46%   |
| Intel Wireless 8260                                                     | 6         | 0.46%   |
| Intel Wireless 3165                                                     | 6         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 232       | 32.22%  |
| Qualcomm Atheros      | 204       | 28.33%  |
| Realtek Semiconductor | 128       | 17.78%  |
| Broadcom              | 79        | 10.97%  |
| Ralink                | 23        | 3.19%   |
| MediaTek              | 23        | 3.19%   |
| Broadcom Limited      | 10        | 1.39%   |
| Ralink Technology     | 4         | 0.56%   |
| TP-Link               | 3         | 0.42%   |
| Sierra Wireless       | 3         | 0.42%   |
| Qualcomm              | 3         | 0.42%   |
| Fibocom               | 3         | 0.42%   |
| Philips (or NXP)      | 1         | 0.14%   |
| Mercucys              | 1         | 0.14%   |
| Hewlett-Packard       | 1         | 0.14%   |
| D-Link                | 1         | 0.14%   |
| Unknown               | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 56        | 7.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 5.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 5.53%   |
| Intel Wireless 8265 / 8275                                              | 40        | 5.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 4.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 3.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 2.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 2.77%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 2.49%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.21%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 2.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.8%    |
| Intel Wireless 7265                                                     | 10        | 1.38%   |
| Intel Wireless 7260                                                     | 9         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.97%   |
| Intel WiFi Link 5100                                                    | 7         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.83%   |
| Intel Wireless 8260                                                     | 6         | 0.83%   |
| Intel Wireless 3165                                                     | 6         | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.69%   |
| Intel Centrino Wireless-N 130                                           | 5         | 0.69%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                          | 4         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 363       | 63.91%  |
| Qualcomm Atheros                 | 63        | 11.09%  |
| Intel                            | 45        | 7.92%   |
| Broadcom                         | 39        | 6.87%   |
| Marvell Technology Group         | 25        | 4.4%    |
| Broadcom Limited                 | 7         | 1.23%   |
| JMicron Technology               | 4         | 0.7%    |
| TP-Link                          | 3         | 0.53%   |
| Huawei Technologies              | 3         | 0.53%   |
| Attansic Technology              | 3         | 0.53%   |
| Xiaomi                           | 2         | 0.35%   |
| Qualcomm                         | 2         | 0.35%   |
| ASIX Electronics                 | 2         | 0.35%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Samsung Electronics              | 1         | 0.18%   |
| Nvidia                           | 1         | 0.18%   |
| Lenovo                           | 1         | 0.18%   |
| Aquantia                         | 1         | 0.18%   |
| Apple                            | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 252       | 44.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 98        | 17.16%  |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 2.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 11        | 1.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 9         | 1.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 1.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 7         | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 1.05%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 1.05%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 0.7%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 0.7%    |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.7%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 3         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.53%   |
| Intel Ethernet Connection (16) I219-V                                          | 3         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.53%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.53%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.35%   |
| TP-Link USB 10/100 LAN                                                         | 2         | 0.35%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.35%   |
| Realtek PCIe GbE Family Controller                                             | 2         | 0.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.35%   |
| Qualcomm Nokia G42 5G                                                          | 2         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 689       | 55.03%  |
| Ethernet | 558       | 44.57%  |
| Modem    | 4         | 0.32%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 605       | 81.65%  |
| Ethernet | 136       | 18.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 535       | 77.09%  |
| 1     | 150       | 21.61%  |
| 0     | 7         | 1.01%   |
| 3     | 2         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 682       | 97.57%  |
| Yes  | 17        | 2.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 192       | 34.47%  |
| Realtek Semiconductor           | 82        | 14.72%  |
| Qualcomm Atheros Communications | 68        | 12.21%  |
| IMC Networks                    | 50        | 8.98%   |
| Broadcom                        | 33        | 5.92%   |
| Lite-On Technology              | 29        | 5.21%   |
| Foxconn / Hon Hai               | 27        | 4.85%   |
| Ralink                          | 15        | 2.69%   |
| Foxconn International           | 10        | 1.8%    |
| ASUSTek Computer                | 9         | 1.62%   |
| Hewlett-Packard                 | 8         | 1.44%   |
| Toshiba                         | 7         | 1.26%   |
| Apple                           | 4         | 0.72%   |
| Realtek                         | 3         | 0.54%   |
| Ralink Technology               | 3         | 0.54%   |
| MediaTek                        | 3         | 0.54%   |
| Dell                            | 3         | 0.54%   |
| Taiyo Yuden                     | 2         | 0.36%   |
| Qcom                            | 2         | 0.36%   |
| Cambridge Silicon Radio         | 2         | 0.36%   |
| USI                             | 1         | 0.18%   |
| Opticis                         | 1         | 0.18%   |
| Micro Star International        | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                           | 52        | 9.32%   |
| Intel Bluetooth Device                            | 44        | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 43        | 7.71%   |
| Intel AX201 Bluetooth                             | 37        | 6.63%   |
| Intel Bluetooth wireless interface                | 30        | 5.38%   |
| Qualcomm Atheros  Bluetooth Device                | 21        | 3.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 20        | 3.58%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 17        | 3.05%   |
| Intel AX200 Bluetooth                             | 16        | 2.87%   |
| IMC Networks Wireless_Device                      | 16        | 2.87%   |
| Ralink RT3290 Bluetooth                           | 15        | 2.69%   |
| Foxconn / Hon Hai Bluetooth Device                | 11        | 1.97%   |
| Realtek 802.11ac WLAN Adapter                     | 10        | 1.79%   |
| Lite-On Bluetooth Device                          | 10        | 1.79%   |
| IMC Networks Bluetooth Radio                      | 10        | 1.79%   |
| Foxconn International BCM43142A0 Bluetooth module | 10        | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                    | 9         | 1.61%   |
| IMC Networks Bluetooth Device                     | 9         | 1.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 9         | 1.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 8         | 1.43%   |
| Lite-On Atheros AR3012 Bluetooth                  | 7         | 1.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 7         | 1.25%   |
| Broadcom BCM2070 Bluetooth Device                 | 7         | 1.25%   |
| Realtek RTL8723B Bluetooth                        | 6         | 1.08%   |
| Qualcomm Atheros Bluetooth                        | 6         | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 6         | 1.08%   |
| Intel AX211 Bluetooth                             | 5         | 0.9%    |
| Realtek RTL8821A Bluetooth                        | 4         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                  | 4         | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 4         | 0.72%   |
| Broadcom BCM2045 Bluetooth                        | 4         | 0.72%   |
| Toshiba RT Bluetooth Radio                        | 3         | 0.54%   |
| Realtek Bluetooth Radio                           | 3         | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 3         | 0.54%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 3         | 0.54%   |
| IMC Networks Bluetooth USB Host Controller        | 3         | 0.54%   |
| Foxconn / Hon Hai BCM43142A0                      | 3         | 0.54%   |
| Foxconn / Hon Hai BCM20702A0                      | 3         | 0.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]  | 3         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 533       | 66.05%  |
| AMD                              | 167       | 20.69%  |
| Nvidia                           | 76        | 9.42%   |
| Logitech                         | 5         | 0.62%   |
| JMTek                            | 4         | 0.5%    |
| C-Media Electronics              | 4         | 0.5%    |
| Silicon Integrated Systems [SiS] | 3         | 0.37%   |
| Generalplus Technology           | 2         | 0.25%   |
| Conexant Systems                 | 2         | 0.25%   |
| Apple                            | 2         | 0.25%   |
| Texas Instruments                | 1         | 0.12%   |
| Tenx Technology                  | 1         | 0.12%   |
| Kingston Technology              | 1         | 0.12%   |
| GYROCOM C&C                      | 1         | 0.12%   |
| GN Netcom                        | 1         | 0.12%   |
| Focusrite-Novation               | 1         | 0.12%   |
| ESS Technology                   | 1         | 0.12%   |
| Creative Labs                    | 1         | 0.12%   |
| ASUSTek Computer                 | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 76        | 7.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 72        | 7.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 62        | 6.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 38        | 3.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 37        | 3.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 34        | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 34        | 3.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 2.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 2.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 2.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 2.32%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 2.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 2.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 2.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 1.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 1.31%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 1.31%   |
| AMD Wrestler HDMI Audio                                                                           | 13        | 1.31%   |
| AMD Trinity HDMI Audio Controller                                                                 | 13        | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 0.71%   |
| Nvidia Audio device                                                                               | 7         | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 163       | 26.33%  |
| SK hynix              | 122       | 19.71%  |
| Kingston              | 69        | 11.15%  |
| Micron Technology     | 66        | 10.66%  |
| Unknown               | 62        | 10.02%  |
| Crucial               | 25        | 4.04%   |
| Elpida                | 23        | 3.72%   |
| Ramaxel Technology    | 17        | 2.75%   |
| Nanya Technology      | 14        | 2.26%   |
| A-DATA Technology     | 11        | 1.78%   |
| Transcend             | 6         | 0.97%   |
| ASint Technology      | 6         | 0.97%   |
| Corsair               | 4         | 0.65%   |
| 48spaces              | 4         | 0.65%   |
| Unknown (ABCD)        | 3         | 0.48%   |
| Patriot               | 3         | 0.48%   |
| Team                  | 2         | 0.32%   |
| Silicon Power         | 2         | 0.32%   |
| SHARETRONIC           | 2         | 0.32%   |
| Apacer                | 2         | 0.32%   |
| Unknown               | 2         | 0.32%   |
| Wilk                  | 1         | 0.16%   |
| Qumo                  | 1         | 0.16%   |
| Qimonda               | 1         | 0.16%   |
| PNY                   | 1         | 0.16%   |
| Netac                 | 1         | 0.16%   |
| Kllisre               | 1         | 0.16%   |
| Kingmax Semiconductor | 1         | 0.16%   |
| Kingmax               | 1         | 0.16%   |
| Goldkey               | 1         | 0.16%   |
| GeIL                  | 1         | 0.16%   |
| G.Skill               | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 13        | 1.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 11        | 1.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 9         | 1.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 9         | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 9         | 1.35%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                  | 8         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 7         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 7         | 1.05%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 6         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 6         | 0.9%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 6         | 0.9%    |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s                    | 6         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 5         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 5         | 0.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 5         | 0.75%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 0.75%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 5         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.75%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s                     | 5         | 0.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 4         | 0.6%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 4         | 0.6%    |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                           | 4         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s                  | 4         | 0.6%    |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s                     | 4         | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 4         | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s                  | 4         | 0.6%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 4         | 0.6%    |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 4         | 0.6%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 4         | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB Row Of Chips DDR4 3200MT/s            | 4         | 0.6%    |
| Kingston RAM 99U5469-070.A00LF 4GB SODIMM DDR3 1600MT/s                   | 4         | 0.6%    |
| Elpida RAM EBJ40UG8EFU0 4GB SODIMM DDR3 1600MT/s                          | 4         | 0.6%    |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 667MT/s | 4         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 3         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 3         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 3         | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 3         | 0.45%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s                 | 3         | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 3         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 226       | 44.31%  |
| DDR4    | 169       | 33.14%  |
| DDR2    | 40        | 7.84%   |
| SDRAM   | 27        | 5.29%   |
| LPDDR4  | 16        | 3.14%   |
| Unknown | 9         | 1.76%   |
| LPDDR5  | 7         | 1.37%   |
| DDR5    | 7         | 1.37%   |
| DRAM    | 4         | 0.78%   |
| DDR     | 3         | 0.59%   |
| LPDDR3  | 2         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 475       | 94.25%  |
| Row Of Chips | 28        | 5.56%   |
| DIMM         | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 215       | 36.26%  |
| 8192  | 137       | 23.1%   |
| 2048  | 130       | 21.92%  |
| 16384 | 69        | 11.64%  |
| 1024  | 32        | 5.4%    |
| 32768 | 5         | 0.84%   |
| 512   | 5         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 149       | 26.56%  |
| 3200    | 84        | 14.97%  |
| 2667    | 72        | 12.83%  |
| 1334    | 42        | 7.49%   |
| 1333    | 31        | 5.53%   |
| 2400    | 30        | 5.35%   |
| 667     | 27        | 4.81%   |
| Unknown | 18        | 3.21%   |
| 4199    | 15        | 2.67%   |
| 800     | 14        | 2.5%    |
| 1067    | 10        | 1.78%   |
| 3266    | 9         | 1.6%    |
| 2133    | 9         | 1.6%    |
| 2048    | 8         | 1.43%   |
| 4800    | 7         | 1.25%   |
| 6400    | 6         | 1.07%   |
| 1867    | 6         | 1.07%   |
| 4267    | 5         | 0.89%   |
| 533     | 4         | 0.71%   |
| 1066    | 3         | 0.53%   |
| 8400    | 2         | 0.36%   |
| 4266    | 2         | 0.36%   |
| 333     | 2         | 0.36%   |
| 65535   | 1         | 0.18%   |
| 8533    | 1         | 0.18%   |
| 1866    | 1         | 0.18%   |
| 1639    | 1         | 0.18%   |
| 975     | 1         | 0.18%   |
| 400     | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 28.57%  |
| Seiko Epson         | 1         | 14.29%  |
| Ricoh               | 1         | 14.29%  |
| Kyocera             | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L365 Series | 1         | 14.29%  |
| Samsung SCX-4300 Series | 1         | 14.29%  |
| Samsung Laser Printer   | 1         | 14.29%  |
| Ricoh SP 213SUw         | 1         | 14.29%  |
| Kyocera FS-1125MFP      | 1         | 14.29%  |
| HP LaserJet 1010        | 1         | 14.29%  |
| Canon CAPT USB Device   | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 153       | 24.09%  |
| IMC Networks                           | 101       | 15.91%  |
| Quanta                                 | 40        | 6.3%    |
| Realtek Semiconductor                  | 35        | 5.51%   |
| Sunplus Innovation Technology          | 33        | 5.2%    |
| Suyin                                  | 31        | 4.88%   |
| Syntek                                 | 27        | 4.25%   |
| Bison Electronics                      | 27        | 4.25%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 3.78%   |
| Lite-On Technology                     | 22        | 3.46%   |
| Acer                                   | 22        | 3.46%   |
| Silicon Motion                         | 21        | 3.31%   |
| Microdia                               | 15        | 2.36%   |
| Z-Star Microelectronics                | 11        | 1.73%   |
| Apple                                  | 11        | 1.73%   |
| Alcor Micro                            | 10        | 1.57%   |
| Luxvisions Innotech Limited            | 7         | 1.1%    |
| Sonix Technology                       | 6         | 0.94%   |
| Logitech                               | 5         | 0.79%   |
| SunplusIT                              | 4         | 0.63%   |
| Primax Electronics                     | 4         | 0.63%   |
| Samsung Electronics                    | 3         | 0.47%   |
| Lenovo                                 | 3         | 0.47%   |
| Importek                               | 3         | 0.47%   |
| DigiTech                               | 3         | 0.47%   |
| Shine-optics                           | 2         | 0.31%   |
| Ricoh                                  | 2         | 0.31%   |
| Y Media                                | 1         | 0.16%   |
| Shinetech                              | 1         | 0.16%   |
| Razer USA                              | 1         | 0.16%   |
| Pixart Imaging                         | 1         | 0.16%   |
| Linux Foundation                       | 1         | 0.16%   |
| Intel                                  | 1         | 0.16%   |
| Goodong                                | 1         | 0.16%   |
| Genesys Logic                          | 1         | 0.16%   |
| Arkmicro Technologies                  | 1         | 0.16%   |
| ALi                                    | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam   | 31        | 4.87%   |
| IMC Networks USB2.0 HD UVC WebCam    | 20        | 3.14%   |
| Chicony Integrated Camera            | 16        | 2.52%   |
| IMC Networks Integrated Camera       | 13        | 2.04%   |
| Chicony USB2.0 VGA UVC WebCam        | 13        | 2.04%   |
| Syntek Integrated Camera             | 12        | 1.89%   |
| Chicony HD WebCam                    | 12        | 1.89%   |
| Sunplus HD WebCam                    | 10        | 1.57%   |
| Realtek Integrated_Webcam_HD         | 10        | 1.57%   |
| Chicony Lenovo EasyCamera            | 10        | 1.57%   |
| Acer Lenovo Integrated Webcam        | 10        | 1.57%   |
| Syntek EasyCamera                    | 7         | 1.1%    |
| Quanta HP HD Camera                  | 7         | 1.1%    |
| Chicony USB2.0 HD UVC WebCam         | 7         | 1.1%    |
| Chicony EasyCamera                   | 7         | 1.1%    |
| Bison Lenovo EasyCamera              | 7         | 1.1%    |
| Syntek Lenovo EasyCamera             | 6         | 0.94%   |
| Sunplus Integrated_Webcam_HD         | 6         | 0.94%   |
| Microdia Integrated_Webcam_HD        | 6         | 0.94%   |
| Lite-On Integrated Camera            | 6         | 0.94%   |
| IMC Networks UVC VGA Webcam          | 6         | 0.94%   |
| IMC Networks USB2.0 UVC HD Webcam    | 6         | 0.94%   |
| IMC Networks Integrated Webcam       | 6         | 0.94%   |
| Chicony HP HD Camera                 | 6         | 0.94%   |
| Bison Integrated Camera              | 6         | 0.94%   |
| Suyin HP TrueVision HD               | 5         | 0.79%   |
| Silicon Motion WebCam SC-0311139N    | 5         | 0.79%   |
| Quanta HP TrueVision HD Camera       | 5         | 0.79%   |
| Lite-On HP HD Camera                 | 5         | 0.79%   |
| IMC Networks HD Camera               | 5         | 0.79%   |
| Acer Lenovo EasyCamera               | 5         | 0.79%   |
| Suyin HD Video WebCam                | 4         | 0.63%   |
| Silicon Motion WebCam SC-03FFL11939N | 4         | 0.63%   |
| Quanta VGA WebCam                    | 4         | 0.63%   |
| Quanta ov9734_techfront_camera       | 4         | 0.63%   |
| Quanta HD Webcam                     | 4         | 0.63%   |
| Primax HP HD Webcam [Fixed]          | 4         | 0.63%   |
| Lite-On HP Wide Vision HD Camera     | 4         | 0.63%   |
| Lite-On HP HD Webcam                 | 4         | 0.63%   |
| Chicony XiaoMi USB 2.0 Webcam        | 4         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 23        | 27.71%  |
| Synaptics                          | 16        | 19.28%  |
| Shenzhen Goodix Technology         | 15        | 18.07%  |
| Elan Microelectronics              | 13        | 15.66%  |
| AuthenTec                          | 6         | 7.23%   |
| STMicroelectronics                 | 3         | 3.61%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 3.61%   |
| Upek                               | 2         | 2.41%   |
| LighTuning Technology              | 2         | 2.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 10        | 12.05%  |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 10.84%  |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 6.02%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.82%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 4.82%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.61%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 3.61%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.61%   |
| Validity Sensors VFS491                                                    | 2         | 2.41%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.41%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.41%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.41%   |
| Synaptics  WBDI                                                            | 2         | 2.41%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.41%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.2%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.2%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.2%    |
| Synaptics UWP WBDI                                                         | 1         | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.2%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.2%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.2%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.2%    |
| AuthenTec AES2810                                                          | 1         | 1.2%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.2%    |
| AuthenTec AES1600                                                          | 1         | 1.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 9         | 50%     |
| Lenovo                | 4         | 22.22%  |
| Broadcom              | 2         | 11.11%  |
| Upek                  | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |
| Advanced Card Systems | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 50%     |
| Lenovo Integrated Smart Card Reader                                          | 4         | 22.22%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |
| Advanced Card Systems ACR39U                                                 | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 496       | 69.27%  |
| 1     | 174       | 24.3%   |
| 2     | 40        | 5.59%   |
| 3     | 5         | 0.7%    |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 88        | 34.78%  |
| Fingerprint reader       | 81        | 32.02%  |
| Net/wireless             | 18        | 7.11%   |
| Bluetooth                | 17        | 6.72%   |
| Chipcard                 | 14        | 5.53%   |
| Multimedia controller    | 12        | 4.74%   |
| Camera                   | 7         | 2.77%   |
| Communication controller | 6         | 2.37%   |
| Storage                  | 4         | 1.58%   |
| Card reader              | 2         | 0.79%   |
| Sound                    | 1         | 0.4%    |
| Net/ethernet             | 1         | 0.4%    |
| Modem                    | 1         | 0.4%    |
| Flash memory             | 1         | 0.4%    |

