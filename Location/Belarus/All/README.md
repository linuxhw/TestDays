Linux in Belarus - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belarus/Desktop/README.md) and [notebooks](/Location/Belarus/Notebook/README.md).

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

Total: 1854

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | EP45-DS3L                   | Desktop     | [7cd20b2530](https://linux-hardware.org/?probe=7cd20b2530) | May 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32e408088d](https://linux-hardware.org/?probe=32e408088d) | May 07, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6e17fb9c95](https://linux-hardware.org/?probe=6e17fb9c95) | May 02, 2024 |
| Lenovo        | ThinkPad X395 20NMS0D900    | Notebook    | [47098170bb](https://linux-hardware.org/?probe=47098170bb) | May 01, 2024 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [b3631ed021](https://linux-hardware.org/?probe=b3631ed021) | Apr 29, 2024 |
| HP            | ProBook 4535s               | Notebook    | [34910d04e7](https://linux-hardware.org/?probe=34910d04e7) | Apr 28, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3dcaa02108](https://linux-hardware.org/?probe=3dcaa02108) | Apr 28, 2024 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [714f84cadb](https://linux-hardware.org/?probe=714f84cadb) | Apr 26, 2024 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [e21d70e37d](https://linux-hardware.org/?probe=e21d70e37d) | Apr 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8c81adc916](https://linux-hardware.org/?probe=8c81adc916) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [bc0e0ae6b8](https://linux-hardware.org/?probe=bc0e0ae6b8) | Apr 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [10a878e186](https://linux-hardware.org/?probe=10a878e186) | Apr 25, 2024 |
| Lenovo        | XiaoXinPro 16 AHP9 83D5     | Notebook    | [bec1c58cef](https://linux-hardware.org/?probe=bec1c58cef) | Apr 25, 2024 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d96419f8cf](https://linux-hardware.org/?probe=d96419f8cf) | Apr 23, 2024 |
| TECNO         | MEGABOOK T1                 | Notebook    | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [a3f2909959](https://linux-hardware.org/?probe=a3f2909959) | Apr 22, 2024 |
| ASRock        | B85M-ITX                    | Desktop     | [c868a15a8f](https://linux-hardware.org/?probe=c868a15a8f) | Apr 20, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [31da76530e](https://linux-hardware.org/?probe=31da76530e) | Apr 13, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9a0c435db3](https://linux-hardware.org/?probe=9a0c435db3) | Apr 12, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f73b16ab18](https://linux-hardware.org/?probe=f73b16ab18) | Apr 11, 2024 |
| ASUSTek       | K55VM                       | Notebook    | [9293006922](https://linux-hardware.org/?probe=9293006922) | Apr 09, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [2500fb4398](https://linux-hardware.org/?probe=2500fb4398) | Apr 09, 2024 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [81be04c868](https://linux-hardware.org/?probe=81be04c868) | Apr 09, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [eadddcdc8e](https://linux-hardware.org/?probe=eadddcdc8e) | Apr 06, 2024 |
| ASUSTek       | K55VM                       | Notebook    | [dff985be75](https://linux-hardware.org/?probe=dff985be75) | Apr 05, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [871311fcdc](https://linux-hardware.org/?probe=871311fcdc) | Apr 03, 2024 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [9e6d967077](https://linux-hardware.org/?probe=9e6d967077) | Apr 03, 2024 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [74e2ba96da](https://linux-hardware.org/?probe=74e2ba96da) | Apr 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | Notebook    | [6d0d8895f9](https://linux-hardware.org/?probe=6d0d8895f9) | Apr 02, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [a42873dcf9](https://linux-hardware.org/?probe=a42873dcf9) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [48dfdf4137](https://linux-hardware.org/?probe=48dfdf4137) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d209d00332](https://linux-hardware.org/?probe=d209d00332) | Apr 01, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [953610ee17](https://linux-hardware.org/?probe=953610ee17) | Mar 28, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [5d1d7ed87a](https://linux-hardware.org/?probe=5d1d7ed87a) | Mar 28, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [90ff22d8c1](https://linux-hardware.org/?probe=90ff22d8c1) | Mar 25, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6bb15775d7](https://linux-hardware.org/?probe=6bb15775d7) | Mar 24, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [11f7843550](https://linux-hardware.org/?probe=11f7843550) | Mar 23, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [4445879c66](https://linux-hardware.org/?probe=4445879c66) | Mar 21, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [90a25e637e](https://linux-hardware.org/?probe=90a25e637e) | Mar 21, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [01284be05a](https://linux-hardware.org/?probe=01284be05a) | Mar 20, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [9d76e364c6](https://linux-hardware.org/?probe=9d76e364c6) | Mar 20, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [8adaf6e6b2](https://linux-hardware.org/?probe=8adaf6e6b2) | Mar 17, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [de6730ef57](https://linux-hardware.org/?probe=de6730ef57) | Mar 13, 2024 |
| HP            | 650                         | Notebook    | [8968085c5a](https://linux-hardware.org/?probe=8968085c5a) | Mar 13, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6bea275119](https://linux-hardware.org/?probe=6bea275119) | Mar 12, 2024 |
| HP            | Laptop 17-ak0xx             | Notebook    | [a5d4f19046](https://linux-hardware.org/?probe=a5d4f19046) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [86024c45ed](https://linux-hardware.org/?probe=86024c45ed) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a65a82b4d4](https://linux-hardware.org/?probe=a65a82b4d4) | Mar 12, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [c99a1426a1](https://linux-hardware.org/?probe=c99a1426a1) | Mar 07, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [bab57077f5](https://linux-hardware.org/?probe=bab57077f5) | Mar 06, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [544a3548cc](https://linux-hardware.org/?probe=544a3548cc) | Mar 05, 2024 |
| Intel         | B760 E1.0G                  | Desktop     | [3908f7bec6](https://linux-hardware.org/?probe=3908f7bec6) | Mar 04, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [cda628788e](https://linux-hardware.org/?probe=cda628788e) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [08024a8cef](https://linux-hardware.org/?probe=08024a8cef) | Mar 01, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [43919c6c44](https://linux-hardware.org/?probe=43919c6c44) | Feb 29, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [19c9cc81e5](https://linux-hardware.org/?probe=19c9cc81e5) | Feb 26, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0fa9131028](https://linux-hardware.org/?probe=0fa9131028) | Feb 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [367494d4cf](https://linux-hardware.org/?probe=367494d4cf) | Feb 24, 2024 |
| Sony          | SVF1521L1RB                 | Notebook    | [4b0e081c62](https://linux-hardware.org/?probe=4b0e081c62) | Feb 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [3514879254](https://linux-hardware.org/?probe=3514879254) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [37b9530a2a](https://linux-hardware.org/?probe=37b9530a2a) | Feb 22, 2024 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [4aa25676bc](https://linux-hardware.org/?probe=4aa25676bc) | Feb 22, 2024 |
| HONOR         | NBR-WAX9                    | Notebook    | [6fa625a010](https://linux-hardware.org/?probe=6fa625a010) | Feb 21, 2024 |
| ASRock        | K10N78D                     | Desktop     | [31060d37cf](https://linux-hardware.org/?probe=31060d37cf) | Feb 18, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [16a4080794](https://linux-hardware.org/?probe=16a4080794) | Feb 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [cdd51cbb3d](https://linux-hardware.org/?probe=cdd51cbb3d) | Feb 16, 2024 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [c98ffdb659](https://linux-hardware.org/?probe=c98ffdb659) | Feb 16, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2f303b1ad2](https://linux-hardware.org/?probe=2f303b1ad2) | Feb 15, 2024 |
| AMD           | A88DA                       | Desktop     | [89ca695711](https://linux-hardware.org/?probe=89ca695711) | Feb 14, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [2d39984c89](https://linux-hardware.org/?probe=2d39984c89) | Feb 14, 2024 |
| MSI           | Katana GF66 11UD            | Notebook    | [2adf0be9f1](https://linux-hardware.org/?probe=2adf0be9f1) | Feb 12, 2024 |
| MSI           | Katana GF66 11UD            | Notebook    | [062c0b91a4](https://linux-hardware.org/?probe=062c0b91a4) | Feb 12, 2024 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [9b3e403b41](https://linux-hardware.org/?probe=9b3e403b41) | Feb 11, 2024 |
| ASRock        | N68-GS                      | Desktop     | [06f147ad72](https://linux-hardware.org/?probe=06f147ad72) | Feb 09, 2024 |
| ASRock        | H61M-HVGS                   | Desktop     | [dc3bd18c15](https://linux-hardware.org/?probe=dc3bd18c15) | Feb 09, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1e1676f874](https://linux-hardware.org/?probe=1e1676f874) | Feb 09, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [f4251d37e2](https://linux-hardware.org/?probe=f4251d37e2) | Feb 09, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [20aea10762](https://linux-hardware.org/?probe=20aea10762) | Feb 08, 2024 |
| HONOR         | HYM-WXX                     | Notebook    | [35503217de](https://linux-hardware.org/?probe=35503217de) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d731c8db9a](https://linux-hardware.org/?probe=d731c8db9a) | Feb 04, 2024 |
| Xiaomi        | Mi A2 Lite                  | Soc         | [a13944d5f3](https://linux-hardware.org/?probe=a13944d5f3) | Feb 04, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [cf54a4b360](https://linux-hardware.org/?probe=cf54a4b360) | Feb 02, 2024 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [fddf157b5f](https://linux-hardware.org/?probe=fddf157b5f) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c823432a5a](https://linux-hardware.org/?probe=c823432a5a) | Jan 30, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [c2ff3b6e2f](https://linux-hardware.org/?probe=c2ff3b6e2f) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [bc89935fa2](https://linux-hardware.org/?probe=bc89935fa2) | Jan 29, 2024 |
| Apple         | MacBookPro15,1              | Notebook    | [12fb54aa81](https://linux-hardware.org/?probe=12fb54aa81) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e78406b431](https://linux-hardware.org/?probe=e78406b431) | Jan 28, 2024 |
| Unknown       | Unknown                     | Notebook    | [5c676b44c6](https://linux-hardware.org/?probe=5c676b44c6) | Jan 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [52522836b8](https://linux-hardware.org/?probe=52522836b8) | Jan 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [7423289dfa](https://linux-hardware.org/?probe=7423289dfa) | Jan 26, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [d83af4e1b0](https://linux-hardware.org/?probe=d83af4e1b0) | Jan 26, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c9df4c296f](https://linux-hardware.org/?probe=c9df4c296f) | Jan 26, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [a0b0aa335e](https://linux-hardware.org/?probe=a0b0aa335e) | Jan 25, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [2add8788ab](https://linux-hardware.org/?probe=2add8788ab) | Jan 25, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6c409399d4](https://linux-hardware.org/?probe=6c409399d4) | Jan 25, 2024 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [11b9b2c55a](https://linux-hardware.org/?probe=11b9b2c55a) | Jan 22, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28be98f6c6](https://linux-hardware.org/?probe=28be98f6c6) | Jan 21, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [cc5193ad6b](https://linux-hardware.org/?probe=cc5193ad6b) | Jan 20, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [a244cafad7](https://linux-hardware.org/?probe=a244cafad7) | Jan 20, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [f3ba35a8ef](https://linux-hardware.org/?probe=f3ba35a8ef) | Jan 19, 2024 |
| Biostar       | A320MH                      | Desktop     | [9213e79212](https://linux-hardware.org/?probe=9213e79212) | Jan 19, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [106a1e0cd4](https://linux-hardware.org/?probe=106a1e0cd4) | Jan 17, 2024 |
| Acer          | Extensa 215-55              | Notebook    | [395b2c99b5](https://linux-hardware.org/?probe=395b2c99b5) | Jan 17, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [e793aff68b](https://linux-hardware.org/?probe=e793aff68b) | Jan 16, 2024 |
| Unknown       | X99                         | Desktop     | [7106b28d5f](https://linux-hardware.org/?probe=7106b28d5f) | Jan 16, 2024 |
| Unknown       | X99                         | Desktop     | [c4818c1229](https://linux-hardware.org/?probe=c4818c1229) | Jan 16, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [80798361e5](https://linux-hardware.org/?probe=80798361e5) | Jan 12, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9e8a81f355](https://linux-hardware.org/?probe=9e8a81f355) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [376c519812](https://linux-hardware.org/?probe=376c519812) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [13523b8324](https://linux-hardware.org/?probe=13523b8324) | Jan 07, 2024 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [55c4519a60](https://linux-hardware.org/?probe=55c4519a60) | Jan 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8ade7f9a3b](https://linux-hardware.org/?probe=8ade7f9a3b) | Jan 04, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [34fcef3266](https://linux-hardware.org/?probe=34fcef3266) | Dec 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [45038d4599](https://linux-hardware.org/?probe=45038d4599) | Dec 30, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d82dad2793](https://linux-hardware.org/?probe=d82dad2793) | Dec 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a4d9a001ff](https://linux-hardware.org/?probe=a4d9a001ff) | Dec 29, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [a353ad122c](https://linux-hardware.org/?probe=a353ad122c) | Dec 28, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4a6a6b9b9d](https://linux-hardware.org/?probe=4a6a6b9b9d) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef5699b685](https://linux-hardware.org/?probe=ef5699b685) | Dec 24, 2023 |
| Dell          | System XPS L702X            | Notebook    | [d69355a342](https://linux-hardware.org/?probe=d69355a342) | Dec 23, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [82a8bc3c6e](https://linux-hardware.org/?probe=82a8bc3c6e) | Dec 21, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [4aeb75b734](https://linux-hardware.org/?probe=4aeb75b734) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [812cd1effd](https://linux-hardware.org/?probe=812cd1effd) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [8fc6a74916](https://linux-hardware.org/?probe=8fc6a74916) | Dec 15, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [885e6000e2](https://linux-hardware.org/?probe=885e6000e2) | Dec 12, 2023 |
| ASUSTek       | X550VB                      | Notebook    | [cfc8172838](https://linux-hardware.org/?probe=cfc8172838) | Dec 11, 2023 |
| HP            | ProBook 4535s               | Notebook    | [9005c587a8](https://linux-hardware.org/?probe=9005c587a8) | Dec 10, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [f87c61387d](https://linux-hardware.org/?probe=f87c61387d) | Dec 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4d14243cb9](https://linux-hardware.org/?probe=4d14243cb9) | Dec 05, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [376ffad1f1](https://linux-hardware.org/?probe=376ffad1f1) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L7001SM... | Notebook    | [da99e083aa](https://linux-hardware.org/?probe=da99e083aa) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [deba3c2073](https://linux-hardware.org/?probe=deba3c2073) | Nov 30, 2023 |
| Dell          | 0PGMR1 A00                  | All in one  | [aaca525c1a](https://linux-hardware.org/?probe=aaca525c1a) | Nov 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [184a3ca616](https://linux-hardware.org/?probe=184a3ca616) | Nov 28, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [b74cd41faf](https://linux-hardware.org/?probe=b74cd41faf) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7084bb6ef8](https://linux-hardware.org/?probe=7084bb6ef8) | Nov 26, 2023 |
| HP            | ProBook 6460b               | Notebook    | [d489496b9f](https://linux-hardware.org/?probe=d489496b9f) | Nov 26, 2023 |
| Biostar       | H61MLV2                     | Desktop     | [1e2b4c3878](https://linux-hardware.org/?probe=1e2b4c3878) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1bb4c56d2b](https://linux-hardware.org/?probe=1bb4c56d2b) | Nov 24, 2023 |
| HP            | ProBook 6460b               | Notebook    | [0d13c42c84](https://linux-hardware.org/?probe=0d13c42c84) | Nov 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [93c68a0d33](https://linux-hardware.org/?probe=93c68a0d33) | Nov 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [743037d313](https://linux-hardware.org/?probe=743037d313) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cd775f0d29](https://linux-hardware.org/?probe=cd775f0d29) | Nov 18, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [a6742c43a4](https://linux-hardware.org/?probe=a6742c43a4) | Nov 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6461e4f7af](https://linux-hardware.org/?probe=6461e4f7af) | Nov 16, 2023 |
| HP            | ProBook 6460b               | Notebook    | [b0795caa4c](https://linux-hardware.org/?probe=b0795caa4c) | Nov 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [06cd45bab5](https://linux-hardware.org/?probe=06cd45bab5) | Nov 15, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1cffd5036c](https://linux-hardware.org/?probe=1cffd5036c) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [4d8ebb0232](https://linux-hardware.org/?probe=4d8ebb0232) | Nov 13, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [c648b2a80e](https://linux-hardware.org/?probe=c648b2a80e) | Nov 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c34342b820](https://linux-hardware.org/?probe=c34342b820) | Nov 10, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [5fb8105768](https://linux-hardware.org/?probe=5fb8105768) | Nov 10, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Khadas        | VIM3                        | Soc         | [701bf2eba1](https://linux-hardware.org/?probe=701bf2eba1) | Oct 31, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [c35ab1031d](https://linux-hardware.org/?probe=c35ab1031d) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [265d52a042](https://linux-hardware.org/?probe=265d52a042) | Oct 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [ee5373bbe1](https://linux-hardware.org/?probe=ee5373bbe1) | Oct 28, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8432e79c8](https://linux-hardware.org/?probe=e8432e79c8) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [47d1cb500e](https://linux-hardware.org/?probe=47d1cb500e) | Oct 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA            | Notebook    | [f321493adb](https://linux-hardware.org/?probe=f321493adb) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| Timi          | TM1701                      | Notebook    | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bd850cfed3](https://linux-hardware.org/?probe=bd850cfed3) | Oct 24, 2023 |
| Dell          | Latitude D830               | Notebook    | [53cbc541d2](https://linux-hardware.org/?probe=53cbc541d2) | Oct 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | Notebook    | [36c49585ba](https://linux-hardware.org/?probe=36c49585ba) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [6827d26220](https://linux-hardware.org/?probe=6827d26220) | Oct 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [cf096a11b6](https://linux-hardware.org/?probe=cf096a11b6) | Oct 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [908a750a93](https://linux-hardware.org/?probe=908a750a93) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [10b2d6465f](https://linux-hardware.org/?probe=10b2d6465f) | Oct 10, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [01bfe733f2](https://linux-hardware.org/?probe=01bfe733f2) | Oct 10, 2023 |
| HP            | 650                         | Notebook    | [1339361633](https://linux-hardware.org/?probe=1339361633) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [76449d7977](https://linux-hardware.org/?probe=76449d7977) | Oct 06, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1a20748a43](https://linux-hardware.org/?probe=1a20748a43) | Oct 06, 2023 |
| HP            | EliteBook 1050 G1           | Notebook    | [d5d3dd5136](https://linux-hardware.org/?probe=d5d3dd5136) | Oct 05, 2023 |
| Biostar       | H510MHP                     | Desktop     | [f562c8f7d7](https://linux-hardware.org/?probe=f562c8f7d7) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [46e4809bfe](https://linux-hardware.org/?probe=46e4809bfe) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [db7fa034a7](https://linux-hardware.org/?probe=db7fa034a7) | Oct 03, 2023 |
| HP            | 650                         | Notebook    | [f652e189f9](https://linux-hardware.org/?probe=f652e189f9) | Oct 03, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [5967be8309](https://linux-hardware.org/?probe=5967be8309) | Oct 03, 2023 |
| HP            | Compaq 610                  | Notebook    | [9570db13af](https://linux-hardware.org/?probe=9570db13af) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| Google        | Eve                         | Convertible | [b3c890ec7a](https://linux-hardware.org/?probe=b3c890ec7a) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [eccabb6bc2](https://linux-hardware.org/?probe=eccabb6bc2) | Sep 24, 2023 |
| Olimex        | A20-OLinuXino-LIME2         | Soc         | [b2c0e79757](https://linux-hardware.org/?probe=b2c0e79757) | Sep 22, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [6dfb722e45](https://linux-hardware.org/?probe=6dfb722e45) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [63bebc9690](https://linux-hardware.org/?probe=63bebc9690) | Sep 20, 2023 |
| ASUSTek       | K72Dr                       | Notebook    | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [8d0117a5f3](https://linux-hardware.org/?probe=8d0117a5f3) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [cdeced49b1](https://linux-hardware.org/?probe=cdeced49b1) | Sep 12, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [f588051436](https://linux-hardware.org/?probe=f588051436) | Sep 11, 2023 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [c83c0f03aa](https://linux-hardware.org/?probe=c83c0f03aa) | Sep 11, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8717619604](https://linux-hardware.org/?probe=8717619604) | Sep 11, 2023 |
| ECS           | A960M-M3                    | Desktop     | [70ee5683a4](https://linux-hardware.org/?probe=70ee5683a4) | Sep 11, 2023 |
| Dell          | Latitude 3410               | Notebook    | [c1c98adb51](https://linux-hardware.org/?probe=c1c98adb51) | Sep 10, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f096164a16](https://linux-hardware.org/?probe=f096164a16) | Sep 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [63dae39236](https://linux-hardware.org/?probe=63dae39236) | Sep 08, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [3fb594ab96](https://linux-hardware.org/?probe=3fb594ab96) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [63fd300645](https://linux-hardware.org/?probe=63fd300645) | Sep 07, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [d630819b59](https://linux-hardware.org/?probe=d630819b59) | Sep 05, 2023 |
| Gigabyte      | P55M-UD4                    | Desktop     | [d04a4aef90](https://linux-hardware.org/?probe=d04a4aef90) | Sep 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e04761c470](https://linux-hardware.org/?probe=e04761c470) | Sep 03, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d714ef63c2](https://linux-hardware.org/?probe=d714ef63c2) | Sep 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f6996b2905](https://linux-hardware.org/?probe=f6996b2905) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [4e753f77c7](https://linux-hardware.org/?probe=4e753f77c7) | Sep 01, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [04492867e2](https://linux-hardware.org/?probe=04492867e2) | Aug 31, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e3eb4b9ef5](https://linux-hardware.org/?probe=e3eb4b9ef5) | Aug 31, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f8906dfb9c](https://linux-hardware.org/?probe=f8906dfb9c) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [8ed8031a41](https://linux-hardware.org/?probe=8ed8031a41) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [3d2effa8c5](https://linux-hardware.org/?probe=3d2effa8c5) | Aug 27, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1538d66b38](https://linux-hardware.org/?probe=1538d66b38) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dd9b3b469e](https://linux-hardware.org/?probe=dd9b3b469e) | Aug 15, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [0482630783](https://linux-hardware.org/?probe=0482630783) | Aug 05, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [2a54f1c8ce](https://linux-hardware.org/?probe=2a54f1c8ce) | Aug 04, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| ASUSTek       | GL503VD                     | Notebook    | [4c3516813b](https://linux-hardware.org/?probe=4c3516813b) | Jul 28, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [cf57b5785a](https://linux-hardware.org/?probe=cf57b5785a) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| HP            | ProBook 4545s               | Notebook    | [cf43675118](https://linux-hardware.org/?probe=cf43675118) | Jul 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [7e6c1d1018](https://linux-hardware.org/?probe=7e6c1d1018) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [584f2a2ac4](https://linux-hardware.org/?probe=584f2a2ac4) | Jul 13, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [6456f7b16f](https://linux-hardware.org/?probe=6456f7b16f) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [dfb0bd07f1](https://linux-hardware.org/?probe=dfb0bd07f1) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [d33df8d1a0](https://linux-hardware.org/?probe=d33df8d1a0) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [5b11b41272](https://linux-hardware.org/?probe=5b11b41272) | Jul 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [37239831de](https://linux-hardware.org/?probe=37239831de) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| HP            | 255 G1                      | Notebook    | [f09174c096](https://linux-hardware.org/?probe=f09174c096) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Sony          | SVF1521L1RB                 | Notebook    | [b0dfbb64d0](https://linux-hardware.org/?probe=b0dfbb64d0) | Jun 17, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c7460aff4f](https://linux-hardware.org/?probe=c7460aff4f) | Jun 16, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [129574e8dc](https://linux-hardware.org/?probe=129574e8dc) | Jun 14, 2023 |
| HP            | 255 G1                      | Notebook    | [a8c4597ccd](https://linux-hardware.org/?probe=a8c4597ccd) | Jun 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [704cc1c02b](https://linux-hardware.org/?probe=704cc1c02b) | Jun 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e23f3e627](https://linux-hardware.org/?probe=1e23f3e627) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [eb644c96f3](https://linux-hardware.org/?probe=eb644c96f3) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [94c7ddea69](https://linux-hardware.org/?probe=94c7ddea69) | May 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [653f6e9a8e](https://linux-hardware.org/?probe=653f6e9a8e) | May 20, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [04dac52364](https://linux-hardware.org/?probe=04dac52364) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| MSI           | GE72 7RE                    | Notebook    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6e519b78e9](https://linux-hardware.org/?probe=6e519b78e9) | May 17, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [03b576ccc8](https://linux-hardware.org/?probe=03b576ccc8) | May 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a28a0c505](https://linux-hardware.org/?probe=5a28a0c505) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| Dell          | 0Y958C A00                  | Desktop     | [fb1b987ad5](https://linux-hardware.org/?probe=fb1b987ad5) | May 10, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [169b0a5bc0](https://linux-hardware.org/?probe=169b0a5bc0) | May 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fe4b074a5c](https://linux-hardware.org/?probe=fe4b074a5c) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [5a21b5acb8](https://linux-hardware.org/?probe=5a21b5acb8) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [c11c9964fa](https://linux-hardware.org/?probe=c11c9964fa) | Apr 27, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8bca3fa04b](https://linux-hardware.org/?probe=8bca3fa04b) | Apr 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [50c44b15eb](https://linux-hardware.org/?probe=50c44b15eb) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9cb44b75f5](https://linux-hardware.org/?probe=9cb44b75f5) | Apr 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [f87a34e474](https://linux-hardware.org/?probe=f87a34e474) | Apr 19, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [84dbb8ae74](https://linux-hardware.org/?probe=84dbb8ae74) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [9cacd6f238](https://linux-hardware.org/?probe=9cacd6f238) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [a02f8565dd](https://linux-hardware.org/?probe=a02f8565dd) | Apr 14, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [5ecb1bb650](https://linux-hardware.org/?probe=5ecb1bb650) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [5c23d1d7f7](https://linux-hardware.org/?probe=5c23d1d7f7) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [be2a3d30f2](https://linux-hardware.org/?probe=be2a3d30f2) | Apr 08, 2023 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [71c25d2dce](https://linux-hardware.org/?probe=71c25d2dce) | Apr 07, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [ca3f0771ce](https://linux-hardware.org/?probe=ca3f0771ce) | Apr 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [24ac3864d2](https://linux-hardware.org/?probe=24ac3864d2) | Apr 04, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1789a17694](https://linux-hardware.org/?probe=1789a17694) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| Biostar       | B365MHC                     | Desktop     | [95107f0e65](https://linux-hardware.org/?probe=95107f0e65) | Apr 02, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [6dafdf20a5](https://linux-hardware.org/?probe=6dafdf20a5) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [e5433e75fb](https://linux-hardware.org/?probe=e5433e75fb) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | Desktop     | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | System XPS L702X            | Notebook    | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [4c0751aa89](https://linux-hardware.org/?probe=4c0751aa89) | Mar 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6ae381093b](https://linux-hardware.org/?probe=6ae381093b) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| Getac         | B300-H                      | Notebook    | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c4b7067187](https://linux-hardware.org/?probe=c4b7067187) | Mar 24, 2023 |
| Iskratel, ... | IN6011AX                    | Desktop     | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [43940eb778](https://linux-hardware.org/?probe=43940eb778) | Mar 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d42628a0e9](https://linux-hardware.org/?probe=d42628a0e9) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b5746d500d](https://linux-hardware.org/?probe=b5746d500d) | Mar 13, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| HP            | Compaq 610                  | Notebook    | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [546d7b3f27](https://linux-hardware.org/?probe=546d7b3f27) | Mar 07, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [e8325b5ff1](https://linux-hardware.org/?probe=e8325b5ff1) | Mar 03, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [9cd0a2ea25](https://linux-hardware.org/?probe=9cd0a2ea25) | Mar 01, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [630c0e41b1](https://linux-hardware.org/?probe=630c0e41b1) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c85bd630f0](https://linux-hardware.org/?probe=c85bd630f0) | Feb 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [9b00bf7704](https://linux-hardware.org/?probe=9b00bf7704) | Feb 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dc6a6f7872](https://linux-hardware.org/?probe=dc6a6f7872) | Feb 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [788044d53c](https://linux-hardware.org/?probe=788044d53c) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Partner       | S1-J1900                    | Desktop     | [0dd4327553](https://linux-hardware.org/?probe=0dd4327553) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [faa600d8e5](https://linux-hardware.org/?probe=faa600d8e5) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dfa8cae135](https://linux-hardware.org/?probe=dfa8cae135) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [44e18a0f72](https://linux-hardware.org/?probe=44e18a0f72) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| Intel         | NUC7i3BNB J22859-316        | Mini pc     | [fc5fbe9d48](https://linux-hardware.org/?probe=fc5fbe9d48) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [a1549a7701](https://linux-hardware.org/?probe=a1549a7701) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7f8e95e496](https://linux-hardware.org/?probe=7f8e95e496) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASUSTek       | Z170M-E D3                  | Desktop     | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f94175d8c](https://linux-hardware.org/?probe=6f94175d8c) | Jan 28, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [add8440e16](https://linux-hardware.org/?probe=add8440e16) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f4e06ff0b2](https://linux-hardware.org/?probe=f4e06ff0b2) | Jan 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | Notebook    | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [7c116ff037](https://linux-hardware.org/?probe=7c116ff037) | Jan 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [4606ff1dab](https://linux-hardware.org/?probe=4606ff1dab) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43e346516e](https://linux-hardware.org/?probe=43e346516e) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [325952460c](https://linux-hardware.org/?probe=325952460c) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [ac63fca6cb](https://linux-hardware.org/?probe=ac63fca6cb) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d23fb14f2e](https://linux-hardware.org/?probe=d23fb14f2e) | Jan 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| MSI           | MS-7519                     | Desktop     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6f0f984312](https://linux-hardware.org/?probe=6f0f984312) | Dec 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d196b92cff](https://linux-hardware.org/?probe=d196b92cff) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | Notebook    | [9f1751d2e5](https://linux-hardware.org/?probe=9f1751d2e5) | Dec 22, 2022 |
| Pegatron      | A17                         | Notebook    | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [077f863ca3](https://linux-hardware.org/?probe=077f863ca3) | Dec 15, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a096df53ed](https://linux-hardware.org/?probe=a096df53ed) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [fcd4a2d840](https://linux-hardware.org/?probe=fcd4a2d840) | Dec 11, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b463c25c4d](https://linux-hardware.org/?probe=b463c25c4d) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1c80b48ea0](https://linux-hardware.org/?probe=1c80b48ea0) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| HP            | 550                         | Notebook    | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c3f0c49c7c](https://linux-hardware.org/?probe=c3f0c49c7c) | Dec 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cb93839085](https://linux-hardware.org/?probe=cb93839085) | Dec 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2de79b83d5](https://linux-hardware.org/?probe=2de79b83d5) | Nov 28, 2022 |
| ASUSTek       | K70AB                       | Notebook    | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [09c253d548](https://linux-hardware.org/?probe=09c253d548) | Nov 07, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Compaq 610                  | Notebook    | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| HP            | Compaq 610                  | Notebook    | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6e83c73646](https://linux-hardware.org/?probe=6e83c73646) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | T101MT                      | Notebook    | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a861ca9999](https://linux-hardware.org/?probe=a861ca9999) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| HP            | Compaq 610                  | Notebook    | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | Notebook    | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | Notebook    | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3decfcd64a](https://linux-hardware.org/?probe=3decfcd64a) | Aug 14, 2022 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Sony          | SVF1521L1RW                 | Notebook    | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e899f43a3f](https://linux-hardware.org/?probe=e899f43a3f) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [1ee2492f24](https://linux-hardware.org/?probe=1ee2492f24) | Jul 23, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2d2a17094e](https://linux-hardware.org/?probe=2d2a17094e) | Jul 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [3f20ad2267](https://linux-hardware.org/?probe=3f20ad2267) | Jul 11, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b7adccb849](https://linux-hardware.org/?probe=b7adccb849) | Jul 09, 2022 |
| Samsung       | 535U3C                      | Notebook    | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | Notebook    | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [26cbd669e4](https://linux-hardware.org/?probe=26cbd669e4) | Jul 05, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [2b31833bfe](https://linux-hardware.org/?probe=2b31833bfe) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| Biostar       | TA790GX 128M                | Desktop     | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| Getac         | B300-H                      | Notebook    | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Getac         | B300-H                      | Notebook    | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| Dell          | 0PGMR1 A00                  | All in one  | [bf057e65d8](https://linux-hardware.org/?probe=bf057e65d8) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | Notebook    | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| ECS           | IC780M-A2                   | Desktop     | [135f0a4328](https://linux-hardware.org/?probe=135f0a4328) | May 21, 2022 |
| MSI           | MS-7309                     | Desktop     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [8926d96550](https://linux-hardware.org/?probe=8926d96550) | May 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | Desktop     | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [517ef58b87](https://linux-hardware.org/?probe=517ef58b87) | Mar 11, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [55ce4f1460](https://linux-hardware.org/?probe=55ce4f1460) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| HP            | Mini 110-4100               | Notebook    | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| HP            | 635                         | Notebook    | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | Notebook    | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [601f46e5a4](https://linux-hardware.org/?probe=601f46e5a4) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a32dfea06a](https://linux-hardware.org/?probe=a32dfea06a) | Feb 07, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [583a1313c8](https://linux-hardware.org/?probe=583a1313c8) | Feb 01, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | Notebook    | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [ed633ddd09](https://linux-hardware.org/?probe=ed633ddd09) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [607ade73d0](https://linux-hardware.org/?probe=607ade73d0) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | H87M-E35                    | Desktop     | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| HP            | Presario CQ57               | Notebook    | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [de22d479a4](https://linux-hardware.org/?probe=de22d479a4) | Jan 20, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | Notebook    | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | Notebook    | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| Gigabyte      | M61SME-S2                   | Desktop     | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | Notebook    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | Notebook    | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [a2e037ba0e](https://linux-hardware.org/?probe=a2e037ba0e) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| LG Electro... | R510                        | Notebook    | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [00c297540d](https://linux-hardware.org/?probe=00c297540d) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASUSTek       | V241EA                      | All in one  | [ffb4ed2207](https://linux-hardware.org/?probe=ffb4ed2207) | Nov 02, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [04c5f1689d](https://linux-hardware.org/?probe=04c5f1689d) | Oct 27, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | Notebook    | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | Notebook    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| HP            | 86F0 11000                  | All in one  | [75738404ae](https://linux-hardware.org/?probe=75738404ae) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | Notebook    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0d6bbd5c75](https://linux-hardware.org/?probe=0d6bbd5c75) | Oct 05, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | Notebook    | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| Intel         | H61M-S1                     | Desktop     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| HP            | 86F0 11000                  | All in one  | [d94d1dcab2](https://linux-hardware.org/?probe=d94d1dcab2) | Sep 29, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f8bb575441](https://linux-hardware.org/?probe=f8bb575441) | Sep 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| HP            | ProBook 4515s               | Notebook    | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| Samsung       | R508                        | Notebook    | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | Notebook    | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [11fce4275a](https://linux-hardware.org/?probe=11fce4275a) | Sep 01, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| Biostar       | A960D+V3                    | Desktop     | [f65660cdbe](https://linux-hardware.org/?probe=f65660cdbe) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [46407e3bfe](https://linux-hardware.org/?probe=46407e3bfe) | Aug 24, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [240d31631f](https://linux-hardware.org/?probe=240d31631f) | Aug 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| Biostar       | Hi-Fi A75S3                 | Desktop     | [f75bdb68fa](https://linux-hardware.org/?probe=f75bdb68fa) | Aug 14, 2021 |
| Acer          | Veriton N4660G              | Desktop     | [7ee989172f](https://linux-hardware.org/?probe=7ee989172f) | Aug 13, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [21914d4123](https://linux-hardware.org/?probe=21914d4123) | Aug 11, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [11621d5877](https://linux-hardware.org/?probe=11621d5877) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EQS33800     | Notebook    | [2e1468bf31](https://linux-hardware.org/?probe=2e1468bf31) | Aug 02, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c90b5a2e7d](https://linux-hardware.org/?probe=c90b5a2e7d) | Jul 28, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [92c5d52e50](https://linux-hardware.org/?probe=92c5d52e50) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [960c966e4b](https://linux-hardware.org/?probe=960c966e4b) | Jul 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [af87c52a43](https://linux-hardware.org/?probe=af87c52a43) | Jul 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [30dd6fa596](https://linux-hardware.org/?probe=30dd6fa596) | Jul 14, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [ce3b5ecb17](https://linux-hardware.org/?probe=ce3b5ecb17) | Jul 13, 2021 |
| MSI           | MS-7369                     | Desktop     | [caf783ce91](https://linux-hardware.org/?probe=caf783ce91) | Jul 10, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | Notebook    | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a0792e787d](https://linux-hardware.org/?probe=a0792e787d) | Jun 30, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [945132609d](https://linux-hardware.org/?probe=945132609d) | Jun 30, 2021 |
| Intel         | H61M-S1                     | Desktop     | [10ef09acce](https://linux-hardware.org/?probe=10ef09acce) | Jun 28, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b34ddd69c9](https://linux-hardware.org/?probe=b34ddd69c9) | Jun 21, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7fe08a233a](https://linux-hardware.org/?probe=7fe08a233a) | Jun 20, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [f6436bedb8](https://linux-hardware.org/?probe=f6436bedb8) | Jun 16, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ec0c189e56](https://linux-hardware.org/?probe=ec0c189e56) | Jun 15, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0c5e09b00c](https://linux-hardware.org/?probe=0c5e09b00c) | Jun 14, 2021 |
| MSI           | MS-7369                     | Desktop     | [9852368309](https://linux-hardware.org/?probe=9852368309) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASUSTek       | X541UJ                      | Notebook    | [22f4d0228f](https://linux-hardware.org/?probe=22f4d0228f) | May 16, 2021 |
| Timi          | TM1703                      | Notebook    | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ECS           | Livermore8                  | Desktop     | [fba5a0dbb7](https://linux-hardware.org/?probe=fba5a0dbb7) | May 12, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3eefcf4b58](https://linux-hardware.org/?probe=3eefcf4b58) | May 11, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [f3d7663214](https://linux-hardware.org/?probe=f3d7663214) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [06af60abdc](https://linux-hardware.org/?probe=06af60abdc) | May 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b71c62e752](https://linux-hardware.org/?probe=b71c62e752) | May 09, 2021 |
| Biostar       | H81MLC                      | Desktop     | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ec9321bd41](https://linux-hardware.org/?probe=ec9321bd41) | May 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [46872b4b26](https://linux-hardware.org/?probe=46872b4b26) | May 02, 2021 |
| HP            | ProBook 4525s               | Notebook    | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| Dell          | 0CRH6C A02                  | Desktop     | [69cbbfec14](https://linux-hardware.org/?probe=69cbbfec14) | Apr 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [fb5b8d0021](https://linux-hardware.org/?probe=fb5b8d0021) | Apr 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [7ec9efef18](https://linux-hardware.org/?probe=7ec9efef18) | Apr 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [3f2270faad](https://linux-hardware.org/?probe=3f2270faad) | Apr 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [36129cbfda](https://linux-hardware.org/?probe=36129cbfda) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [644dd10952](https://linux-hardware.org/?probe=644dd10952) | Apr 22, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1832412dab](https://linux-hardware.org/?probe=1832412dab) | Apr 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b60d916c33](https://linux-hardware.org/?probe=b60d916c33) | Apr 19, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [309d8603b2](https://linux-hardware.org/?probe=309d8603b2) | Apr 15, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d945be0db8](https://linux-hardware.org/?probe=d945be0db8) | Apr 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [d6c3e7cb89](https://linux-hardware.org/?probe=d6c3e7cb89) | Apr 15, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [1e11286470](https://linux-hardware.org/?probe=1e11286470) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | Notebook    | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [15bd22b48d](https://linux-hardware.org/?probe=15bd22b48d) | Apr 11, 2021 |
| HP            | 304Ah                       | Desktop     | [66228ce4df](https://linux-hardware.org/?probe=66228ce4df) | Apr 09, 2021 |
| HP            | 304Ah                       | Desktop     | [5d8e8d559a](https://linux-hardware.org/?probe=5d8e8d559a) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ebd6174247](https://linux-hardware.org/?probe=ebd6174247) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [0362943e9e](https://linux-hardware.org/?probe=0362943e9e) | Apr 02, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [3228126df8](https://linux-hardware.org/?probe=3228126df8) | Mar 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [1dc07212db](https://linux-hardware.org/?probe=1dc07212db) | Mar 28, 2021 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [eeeb3a5b5d](https://linux-hardware.org/?probe=eeeb3a5b5d) | Mar 27, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [35964432d7](https://linux-hardware.org/?probe=35964432d7) | Mar 26, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | Notebook    | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [02a403c967](https://linux-hardware.org/?probe=02a403c967) | Mar 24, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [3157cd3bfe](https://linux-hardware.org/?probe=3157cd3bfe) | Mar 23, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [97df6a4a9a](https://linux-hardware.org/?probe=97df6a4a9a) | Mar 23, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d2e63cfaa6](https://linux-hardware.org/?probe=d2e63cfaa6) | Mar 22, 2021 |
| Dell          | 0P4T42 A01                  | All in one  | [2f14bf6c71](https://linux-hardware.org/?probe=2f14bf6c71) | Mar 22, 2021 |
| ASUSTek       | P5B                         | Desktop     | [a24c9c6d6a](https://linux-hardware.org/?probe=a24c9c6d6a) | Mar 22, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c947af2b99](https://linux-hardware.org/?probe=c947af2b99) | Mar 21, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [c6506a0289](https://linux-hardware.org/?probe=c6506a0289) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [18d693f712](https://linux-hardware.org/?probe=18d693f712) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | Notebook    | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [3e2336037f](https://linux-hardware.org/?probe=3e2336037f) | Mar 20, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [1002c3efd0](https://linux-hardware.org/?probe=1002c3efd0) | Mar 19, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [c63de512e5](https://linux-hardware.org/?probe=c63de512e5) | Mar 18, 2021 |
| HP            | 250 G1                      | Notebook    | [7b14b4e7e5](https://linux-hardware.org/?probe=7b14b4e7e5) | Mar 18, 2021 |
| HP            | ProBook 4525s               | Notebook    | [f9830feb98](https://linux-hardware.org/?probe=f9830feb98) | Mar 17, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [d2dde464de](https://linux-hardware.org/?probe=d2dde464de) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [12eebe7515](https://linux-hardware.org/?probe=12eebe7515) | Mar 17, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [e688898ed8](https://linux-hardware.org/?probe=e688898ed8) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [658c4e0d17](https://linux-hardware.org/?probe=658c4e0d17) | Mar 17, 2021 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [1b6cfd046e](https://linux-hardware.org/?probe=1b6cfd046e) | Mar 17, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [82f601055a](https://linux-hardware.org/?probe=82f601055a) | Mar 17, 2021 |
| ASRock        | 990FX Extreme4              | Desktop     | [d1536bcdfa](https://linux-hardware.org/?probe=d1536bcdfa) | Mar 17, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [863c6c5d68](https://linux-hardware.org/?probe=863c6c5d68) | Mar 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [51bf91aae7](https://linux-hardware.org/?probe=51bf91aae7) | Mar 14, 2021 |
| HP            | Mini 210-4000               | Notebook    | [9301f9c8ef](https://linux-hardware.org/?probe=9301f9c8ef) | Mar 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [72f398fcff](https://linux-hardware.org/?probe=72f398fcff) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [83f50b266f](https://linux-hardware.org/?probe=83f50b266f) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [ed293423f3](https://linux-hardware.org/?probe=ed293423f3) | Mar 11, 2021 |
| HP            | ProBook 4525s               | Notebook    | [912c2f075f](https://linux-hardware.org/?probe=912c2f075f) | Mar 09, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f63d1b8f0b](https://linux-hardware.org/?probe=f63d1b8f0b) | Mar 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1df473b11e](https://linux-hardware.org/?probe=1df473b11e) | Mar 03, 2021 |
| Dell          | System XPS L702X            | Notebook    | [1cce147fd2](https://linux-hardware.org/?probe=1cce147fd2) | Feb 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [902d3d474e](https://linux-hardware.org/?probe=902d3d474e) | Feb 25, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [390003cc95](https://linux-hardware.org/?probe=390003cc95) | Feb 24, 2021 |
| MSI           | MS-7250                     | Desktop     | [bd7bbadaad](https://linux-hardware.org/?probe=bd7bbadaad) | Feb 23, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [77748ba0e4](https://linux-hardware.org/?probe=77748ba0e4) | Feb 22, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [8d2b36f7c1](https://linux-hardware.org/?probe=8d2b36f7c1) | Feb 20, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [80cea1a03a](https://linux-hardware.org/?probe=80cea1a03a) | Feb 19, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | Notebook    | [0f4f85b4c1](https://linux-hardware.org/?probe=0f4f85b4c1) | Feb 19, 2021 |
| Packard Be... | EasyNote TM86               | Notebook    | [f548aa653a](https://linux-hardware.org/?probe=f548aa653a) | Feb 18, 2021 |
| Acer          | Extensa 5230                | Notebook    | [b128a06266](https://linux-hardware.org/?probe=b128a06266) | Feb 17, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [1a52fb16f9](https://linux-hardware.org/?probe=1a52fb16f9) | Feb 16, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [8bb7ec1035](https://linux-hardware.org/?probe=8bb7ec1035) | Feb 15, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [c5877ecd52](https://linux-hardware.org/?probe=c5877ecd52) | Feb 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [c500f1eff8](https://linux-hardware.org/?probe=c500f1eff8) | Feb 14, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [76e29e229d](https://linux-hardware.org/?probe=76e29e229d) | Feb 13, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 123       | 9.38%   |
| ROSA R11                     | 106       | 8.08%   |
| ROSA R8.1                    | 81        | 6.17%   |
| Ubuntu 20.04                 | 64        | 4.88%   |
| ROSA R9                      | 49        | 3.73%   |
| ROSA R11.1                   | 48        | 3.66%   |
| Ubuntu 18.04                 | 39        | 2.97%   |
| ROSA R8                      | 38        | 2.9%    |
| Ubuntu 22.04                 | 37        | 2.82%   |
| ROSA 12.2                    | 31        | 2.36%   |
| ROSA 12.4                    | 30        | 2.29%   |
| Arch Rolling                 | 25        | 1.91%   |
| OpenMandriva 4.2             | 24        | 1.83%   |
| Fedora 38                    | 22        | 1.68%   |
| ROSA 12.3                    | 21        | 1.6%    |
| Manjaro                      | 19        | 1.45%   |
| Fedora 39                    | 16        | 1.22%   |
| Debian 11                    | 16        | 1.22%   |
| Fedora 36                    | 15        | 1.14%   |
| OpenMandriva 4.3             | 13        | 0.99%   |
| Linux Mint 19.3              | 13        | 0.99%   |
| Linux Mint 20.3              | 12        | 0.91%   |
| KDE neon 20.04               | 12        | 0.91%   |
| Fedora 35                    | 12        | 0.91%   |
| Debian 12                    | 12        | 0.91%   |
| Linux Mint 21.1              | 11        | 0.84%   |
| Arch                         | 11        | 0.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.76%   |
| Fedora 34                    | 10        | 0.76%   |
| Kubuntu 20.04                | 9         | 0.69%   |
| Fedora 37                    | 9         | 0.69%   |
| OpenMandriva 23.03           | 8         | 0.61%   |
| Ubuntu 22.10                 | 7         | 0.53%   |
| OpenMandriva 23.08           | 7         | 0.53%   |
| Linux Mint 21.2              | 7         | 0.53%   |
| Fedora 40                    | 6         | 0.46%   |
| Fedora 32                    | 6         | 0.46%   |
| Fedora 31                    | 6         | 0.46%   |
| Debian 10                    | 6         | 0.46%   |
| Xubuntu 22.04                | 5         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 448       | 38.99%  |
| Ubuntu        | 167       | 14.53%  |
| Fedora        | 77        | 6.7%    |
| Linux Mint    | 74        | 6.44%   |
| OpenMandriva  | 59        | 5.13%   |
| Manjaro       | 49        | 4.26%   |
| Endless       | 38        | 3.31%   |
| Debian        | 38        | 3.31%   |
| Arch          | 35        | 3.05%   |
| KDE neon      | 18        | 1.57%   |
| Kubuntu       | 17        | 1.48%   |
| Xubuntu       | 14        | 1.22%   |
| openSUSE      | 12        | 1.04%   |
| Gentoo        | 11        | 0.96%   |
| Pop!_OS       | 9         | 0.78%   |
| Elementary    | 9         | 0.78%   |
| LMDE          | 8         | 0.7%    |
| Kali          | 6         | 0.52%   |
| Zorin         | 5         | 0.44%   |
| ALT Linux     | 5         | 0.44%   |
| Lubuntu       | 4         | 0.35%   |
| ArcoLinux     | 4         | 0.35%   |
| Ubuntu MATE   | 3         | 0.26%   |
| MX            | 3         | 0.26%   |
| Clear Linux   | 3         | 0.26%   |
| CentOS        | 3         | 0.26%   |
| BlackPanther  | 3         | 0.26%   |
| Ubuntu Unity  | 2         | 0.17%   |
| SteamOS       | 2         | 0.17%   |
| Nobara        | 2         | 0.17%   |
| NixOS         | 2         | 0.17%   |
| Artix         | 2         | 0.17%   |
| Xero          | 1         | 0.09%   |
| Ubuntu Budgie | 1         | 0.09%   |
| Trisquel      | 1         | 0.09%   |
| Solus         | 1         | 0.09%   |
| RHEL          | 1         | 0.09%   |
| Q4OS          | 1         | 0.09%   |
| PostmarketOS  | 1         | 0.09%   |
| Peppermint    | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 59        | 4.01%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 42        | 2.85%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 39        | 2.65%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 32        | 2.17%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 27        | 1.83%   |
| 5.10.14-desktop-1omv4002            | 23        | 1.56%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 20        | 1.36%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 19        | 1.29%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 18        | 1.22%   |
| 5.4.83-generic-2rosa-x86_64         | 16        | 1.09%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 16        | 1.09%   |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 1.02%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 14        | 0.95%   |
| 5.4.0-42-generic                    | 13        | 0.88%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 13        | 0.88%   |
| 5.16.7-desktop-1omv4003             | 12        | 0.82%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 12        | 0.82%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 11        | 0.75%   |
| 5.15.0-56-generic                   | 11        | 0.75%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 11        | 0.75%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 10        | 0.68%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 10        | 0.68%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 9         | 0.61%   |
| 5.4.32-generic-2rosa-x86_64         | 8         | 0.54%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 8         | 0.54%   |
| 6.4.11-desktop-1omv2390             | 7         | 0.48%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 7         | 0.48%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 7         | 0.48%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.48%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 7         | 0.48%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7         | 0.48%   |
| 6.2.6-desktop-1omv2390              | 6         | 0.41%   |
| 6.1.58-generic-1rosa2021.1-x86_64   | 6         | 0.41%   |
| 5.9.16-1-MANJARO                    | 6         | 0.41%   |
| 5.8.0-14-generic                    | 6         | 0.41%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 6         | 0.41%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 6         | 0.41%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 6         | 0.41%   |
| 6.2.0-26-generic                    | 5         | 0.34%   |
| 5.4.0-58-generic                    | 5         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 139       | 9.72%   |
| 5.4.0   | 83        | 5.8%    |
| 4.9.60  | 70        | 4.9%    |
| 4.9.20  | 49        | 3.43%   |
| 5.15.0  | 48        | 3.36%   |
| 4.9.124 | 33        | 2.31%   |
| 5.10.74 | 32        | 2.24%   |
| 5.8.0   | 31        | 2.17%   |
| 4.9.155 | 27        | 1.89%   |
| 4.1.38  | 27        | 1.89%   |
| 5.10.0  | 26        | 1.82%   |
| 4.1.34  | 26        | 1.82%   |
| 5.11.0  | 25        | 1.75%   |
| 5.10.14 | 23        | 1.61%   |
| 5.0.0   | 23        | 1.61%   |
| 4.9.9   | 22        | 1.54%   |
| 4.9.76  | 22        | 1.54%   |
| 5.13.0  | 21        | 1.47%   |
| 5.4.83  | 20        | 1.4%    |
| 5.3.0   | 20        | 1.4%    |
| 5.19.0  | 20        | 1.4%    |
| 6.5.0   | 18        | 1.26%   |
| 6.2.0   | 17        | 1.19%   |
| 6.1.0   | 16        | 1.12%   |
| 6.1.20  | 14        | 0.98%   |
| 4.9.41  | 14        | 0.98%   |
| 4.18.0  | 13        | 0.91%   |
| 5.16.7  | 12        | 0.84%   |
| 5.15.75 | 12        | 0.84%   |
| 5.4.32  | 9         | 0.63%   |
| 4.19.0  | 9         | 0.63%   |
| 4.13.0  | 9         | 0.63%   |
| 6.4.11  | 8         | 0.56%   |
| 5.9.16  | 8         | 0.56%   |
| 4.9.95  | 8         | 0.56%   |
| 5.15.79 | 7         | 0.49%   |
| 6.6.2   | 6         | 0.42%   |
| 6.2.6   | 6         | 0.42%   |
| 6.1.58  | 6         | 0.42%   |
| 4.9.87  | 6         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 216       | 16.3%   |
| 4.15    | 139       | 10.49%  |
| 5.4     | 128       | 9.66%   |
| 5.10    | 100       | 7.55%   |
| 5.15    | 95        | 7.17%   |
| 6.1     | 57        | 4.3%    |
| 4.1     | 56        | 4.23%   |
| 6.2     | 39        | 2.94%   |
| 5.8     | 39        | 2.94%   |
| 6.5     | 35        | 2.64%   |
| 5.11    | 35        | 2.64%   |
| 5.19    | 30        | 2.26%   |
| 5.13    | 30        | 2.26%   |
| 5.3     | 29        | 2.19%   |
| 6.6     | 26        | 1.96%   |
| 5.0     | 24        | 1.81%   |
| 6.4     | 21        | 1.58%   |
| 5.9     | 19        | 1.43%   |
| 5.16    | 19        | 1.43%   |
| 6.7     | 18        | 1.36%   |
| 4.18    | 16        | 1.21%   |
| 6.0     | 15        | 1.13%   |
| 4.19    | 15        | 1.13%   |
| 5.18    | 14        | 1.06%   |
| 5.14    | 13        | 0.98%   |
| 6.8     | 12        | 0.91%   |
| 5.6     | 11        | 0.83%   |
| 5.17    | 10        | 0.75%   |
| 6.3     | 9         | 0.68%   |
| 4.13    | 9         | 0.68%   |
| 5.12    | 8         | 0.6%    |
| 4.8     | 7         | 0.53%   |
| 5.7     | 5         | 0.38%   |
| 4.4     | 5         | 0.38%   |
| 4.14    | 5         | 0.38%   |
| 5.5     | 4         | 0.3%    |
| 4.17    | 3         | 0.23%   |
| 4.16    | 3         | 0.23%   |
| 4.10    | 2         | 0.15%   |
| 5.1     | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1012      | 91.5%   |
| i686    | 90        | 8.14%   |
| armv7l  | 2         | 0.18%   |
| aarch64 | 2         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 304       | 25.59%  |
| KDE5            | 300       | 25.25%  |
| KDE4            | 280       | 23.57%  |
| Unknown         | 83        | 6.99%   |
| XFCE            | 58        | 4.88%   |
| X-Cinnamon      | 50        | 4.21%   |
| LXQt            | 29        | 2.44%   |
| MATE            | 21        | 1.77%   |
| KDE             | 16        | 1.35%   |
| Cinnamon        | 11        | 0.93%   |
| Pantheon        | 8         | 0.67%   |
| LXDE            | 6         | 0.51%   |
| KDE6            | 6         | 0.51%   |
| Unity           | 2         | 0.17%   |
| i3              | 2         | 0.17%   |
| Deepin          | 2         | 0.17%   |
| Trinity         | 1         | 0.08%   |
| sway            | 1         | 0.08%   |
| Phosh:GNOME     | 1         | 0.08%   |
| Openbox         | 1         | 0.08%   |
| none+xmonad     | 1         | 0.08%   |
| GNOME Flashback | 1         | 0.08%   |
| Endless:GNOME   | 1         | 0.08%   |
| chadwm          | 1         | 0.08%   |
| Budgie          | 1         | 0.08%   |
| bspwm           | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 862       | 75.68%  |
| Wayland | 220       | 19.32%  |
| Unknown | 44        | 3.86%   |
| Tty     | 12        | 1.05%   |
| Web     | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 304       | 25.74%  |
| Unknown | 287       | 24.3%   |
| KDM     | 281       | 23.79%  |
| GDM     | 135       | 11.43%  |
| LightDM | 74        | 6.27%   |
| GDM3    | 67        | 5.67%   |
| TDM     | 29        | 2.46%   |
| MDM     | 2         | 0.17%   |
| SLiM    | 1         | 0.08%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ru_RU       | 426       | 37.37%  |
| Unknown     | 418       | 36.67%  |
| en_US       | 231       | 20.26%  |
| be_BY       | 18        | 1.58%   |
| C           | 16        | 1.4%    |
| en_GB       | 12        | 1.05%   |
| ru_RU.UTF_8 | 6         | 0.53%   |
| ru_UA       | 4         | 0.35%   |
| ru_BY       | 3         | 0.26%   |
| cv_RU       | 2         | 0.18%   |
| fr_FR       | 1         | 0.09%   |
| en_IN       | 1         | 0.09%   |
| en_CA       | 1         | 0.09%   |
| C.utf-8     | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 622       | 55.09%  |
| EFI  | 507       | 44.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 730       | 62.18%  |
| Unknown | 242       | 20.61%  |
| Btrfs   | 110       | 9.37%   |
| Overlay | 61        | 5.2%    |
| Tmpfs   | 15        | 1.28%   |
| Xfs     | 6         | 0.51%   |
| Ext3    | 4         | 0.34%   |
| F2fs    | 2         | 0.17%   |
| Ext2    | 2         | 0.17%   |
| Zfs     | 1         | 0.09%   |
| SAMSUNG | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 429       | 36.6%   |
| Unknown | 380       | 32.42%  |
| MBR     | 363       | 30.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 977       | 85.85%  |
| Yes       | 161       | 14.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 759       | 66%     |
| Yes       | 391       | 34%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 250       | 22.87%  |
| Lenovo              | 146       | 13.36%  |
| Hewlett-Packard     | 143       | 13.08%  |
| Gigabyte Technology | 105       | 9.61%   |
| ASRock              | 79        | 7.23%   |
| Acer                | 78        | 7.14%   |
| MSI                 | 58        | 5.31%   |
| Dell                | 49        | 4.48%   |
| Samsung Electronics | 36        | 3.29%   |
| Biostar             | 15        | 1.37%   |
| Intel               | 14        | 1.28%   |
| Timi                | 11        | 1.01%   |
| Toshiba             | 10        | 0.91%   |
| HONOR               | 8         | 0.73%   |
| Sony                | 7         | 0.64%   |
| Apple               | 7         | 0.64%   |
| Unknown             | 7         | 0.64%   |
| HUAWEI              | 6         | 0.55%   |
| Prestigio           | 5         | 0.46%   |
| Packard Bell        | 5         | 0.46%   |
| Fujitsu             | 4         | 0.37%   |
| ECS                 | 4         | 0.37%   |
| Fujitsu Siemens     | 3         | 0.27%   |
| XIAOMI              | 2         | 0.18%   |
| Valve               | 2         | 0.18%   |
| TECNO               | 2         | 0.18%   |
| Nvidia              | 2         | 0.18%   |
| EPoX Computer       | 2         | 0.18%   |
| Chuwi               | 2         | 0.18%   |
| BenQ                | 2         | 0.18%   |
| ZOTAC               | 1         | 0.09%   |
| ViewSonic           | 1         | 0.09%   |
| VIA Technologies    | 1         | 0.09%   |
| Supermicro          | 1         | 0.09%   |
| Quanta              | 1         | 0.09%   |
| Pegatron            | 1         | 0.09%   |
| Partner             | 1         | 0.09%   |
| Olimex              | 1         | 0.09%   |
| Notebook            | 1         | 0.09%   |
| Microsoft           | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 9         | 0.82%   |
| Lenovo G50-30 80G0                      | 8         | 0.73%   |
| HP Notebook                             | 6         | 0.55%   |
| Timi TM1701                             | 5         | 0.46%   |
| ASRock N68C-GS FX                       | 5         | 0.46%   |
| Acer Extensa 5220                       | 5         | 0.46%   |
| Samsung RV413/RV513                     | 4         | 0.37%   |
| MSI MS-7369                             | 4         | 0.37%   |
| Lenovo IdeaPad 320-15IAP 80XR           | 4         | 0.37%   |
| HONOR NBR-WAX9                          | 4         | 0.37%   |
| HP ProBook 455 G1                       | 4         | 0.37%   |
| HP ProBook 450 G5                       | 4         | 0.37%   |
| HP Pavilion g6                          | 4         | 0.37%   |
| HP Laptop 15s-eq2xxx                    | 4         | 0.37%   |
| Gigabyte 970A-DS3P                      | 4         | 0.37%   |
| ASUS X540NV                             | 4         | 0.37%   |
| ASUS All Series                         | 4         | 0.37%   |
| ASRock N68-VS3 UCC                      | 4         | 0.37%   |
| Acer Aspire E1-571G                     | 4         | 0.37%   |
| MSI MS-7309                             | 3         | 0.27%   |
| Lenovo IdeaPad Z570 HuronRiver Platform | 3         | 0.27%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 3         | 0.27%   |
| Lenovo IdeaPad 3 15IML05 81WB           | 3         | 0.27%   |
| Lenovo IdeaPad 100-15IBY 80MJ           | 3         | 0.27%   |
| Lenovo G570 20079                       | 3         | 0.27%   |
| Lenovo G500 20236                       | 3         | 0.27%   |
| Lenovo B590 20206                       | 3         | 0.27%   |
| Lenovo B50-30 20382                     | 3         | 0.27%   |
| HP Victus by Laptop 16-e0xxx            | 3         | 0.27%   |
| HP Pavilion dv6                         | 3         | 0.27%   |
| HP Pavilion 15                          | 3         | 0.27%   |
| HP 635                                  | 3         | 0.27%   |
| Gigabyte M61SME-S2                      | 3         | 0.27%   |
| Gigabyte H81M-S2H                       | 3         | 0.27%   |
| Gigabyte GA-MA74GM-S2H                  | 3         | 0.27%   |
| Gigabyte GA-780T-D3L                    | 3         | 0.27%   |
| Gigabyte B450M S2H                      | 3         | 0.27%   |
| Gigabyte B450M DS3H                     | 3         | 0.27%   |
| Dell Inspiron 7577                      | 3         | 0.27%   |
| ASUS ZenBook UX431DA_UM431DA            | 3         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 50        | 4.57%   |
| Lenovo IdeaPad     | 49        | 4.48%   |
| HP ProBook         | 40        | 3.66%   |
| Lenovo ThinkPad    | 32        | 2.93%   |
| ASUS VivoBook      | 32        | 2.93%   |
| HP Pavilion        | 31        | 2.84%   |
| Dell Inspiron      | 28        | 2.56%   |
| Acer Extensa       | 14        | 1.28%   |
| HP Laptop          | 13        | 1.19%   |
| ASUS PRIME         | 13        | 1.19%   |
| ASUS ROG           | 12        | 1.1%    |
| ASUS ZenBook       | 10        | 0.91%   |
| ASUS ASUS          | 10        | 0.91%   |
| Unknown            | 9         | 0.82%   |
| Toshiba Satellite  | 8         | 0.73%   |
| Lenovo G50-30      | 8         | 0.73%   |
| HP EliteBook       | 8         | 0.73%   |
| Gigabyte B450M     | 7         | 0.64%   |
| ASUS TUF           | 7         | 0.64%   |
| Lenovo Legion      | 6         | 0.55%   |
| HP Notebook        | 6         | 0.55%   |
| HP Compaq          | 6         | 0.55%   |
| Timi TM1701        | 5         | 0.46%   |
| HP 250             | 5         | 0.46%   |
| Dell XPS           | 5         | 0.46%   |
| Dell Vostro        | 5         | 0.46%   |
| ASRock N68C-GS     | 5         | 0.46%   |
| ASRock N68-VS3     | 5         | 0.46%   |
| Samsung RV413      | 4         | 0.37%   |
| MSI MS-7369        | 4         | 0.37%   |
| Lenovo Yoga        | 4         | 0.37%   |
| Lenovo ThinkBook   | 4         | 0.37%   |
| Lenovo G580        | 4         | 0.37%   |
| HONOR NBR-WAX9     | 4         | 0.37%   |
| HP Victus          | 4         | 0.37%   |
| HP 255             | 4         | 0.37%   |
| Gigabyte Z390      | 4         | 0.37%   |
| Gigabyte 970A-DS3P | 4         | 0.37%   |
| Dell Latitude      | 4         | 0.37%   |
| ASUS X540NV        | 4         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 108       | 9.88%   |
| 2013    | 102       | 9.33%   |
| 2011    | 101       | 9.24%   |
| 2018    | 99        | 9.06%   |
| 2020    | 73        | 6.68%   |
| 2017    | 71        | 6.5%    |
| 2010    | 63        | 5.76%   |
| 2021    | 60        | 5.49%   |
| 2014    | 55        | 5.03%   |
| 2019    | 54        | 4.94%   |
| 2009    | 54        | 4.94%   |
| 2007    | 50        | 4.57%   |
| 2015    | 47        | 4.3%    |
| 2008    | 45        | 4.12%   |
| 2022    | 36        | 3.29%   |
| 2016    | 34        | 3.11%   |
| 2006    | 19        | 1.74%   |
| 2023    | 9         | 0.82%   |
| 2005    | 7         | 0.64%   |
| Unknown | 4         | 0.37%   |
| 2024    | 1         | 0.09%   |
| 2003    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 694       | 63.49%  |
| Desktop        | 368       | 33.67%  |
| Convertible    | 9         | 0.82%   |
| All in one     | 8         | 0.73%   |
| Mini pc        | 4         | 0.37%   |
| System on chip | 3         | 0.27%   |
| Tablet         | 3         | 0.27%   |
| Server         | 3         | 0.27%   |
| Phone          | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1048      | 95.45%  |
| Enabled  | 50        | 4.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1092      | 99.91%  |
| Yes  | 1         | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 283       | 25.11%  |
| 4.01-8.0    | 257       | 22.8%   |
| 8.01-16.0   | 188       | 16.68%  |
| 16.01-24.0  | 166       | 14.73%  |
| 1.01-2.0    | 91        | 8.07%   |
| 32.01-64.0  | 62        | 5.5%    |
| 2.01-3.0    | 43        | 3.82%   |
| 0.51-1.0    | 21        | 1.86%   |
| 24.01-32.0  | 8         | 0.71%   |
| 64.01-256.0 | 7         | 0.62%   |
| 0.01-0.5    | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 422       | 33.39%  |
| 0.51-1.0   | 273       | 21.6%   |
| 2.01-3.0   | 234       | 18.51%  |
| 4.01-8.0   | 153       | 12.1%   |
| 3.01-4.0   | 118       | 9.34%   |
| 8.01-16.0  | 32        | 2.53%   |
| 0.01-0.5   | 22        | 1.74%   |
| 16.01-24.0 | 6         | 0.47%   |
| 24.01-32.0 | 2         | 0.16%   |
| 32.01-64.0 | 1         | 0.08%   |
| Unknown    | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 717       | 62.95%  |
| 2      | 292       | 25.64%  |
| 3      | 87        | 7.64%   |
| 4      | 22        | 1.93%   |
| 5      | 11        | 0.97%   |
| 0      | 6         | 0.53%   |
| 9      | 2         | 0.18%   |
| 8      | 1         | 0.09%   |
| 6      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 664       | 60.04%  |
| Yes       | 442       | 39.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 941       | 86.01%  |
| No        | 153       | 13.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 821       | 74.64%  |
| No        | 279       | 25.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 631       | 56.8%   |
| No        | 480       | 43.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belarus | 1093      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Minsk        | 540       | 44.74%  |
| Vitebsk      | 118       | 9.78%   |
| Gomel        | 109       | 9.03%   |
| Mogilev      | 64        | 5.3%    |
| Brest        | 64        | 5.3%    |
| Hrodna       | 61        | 5.05%   |
| Babruysk     | 24        | 1.99%   |
| Orsha        | 18        | 1.49%   |
| Polatsk      | 17        | 1.41%   |
| Borisov      | 13        | 1.08%   |
| Mazyr        | 10        | 0.83%   |
| Lida         | 9         | 0.75%   |
| Baranovichi  | 9         | 0.75%   |
| Zhodzina     | 7         | 0.58%   |
| Zhlobin      | 7         | 0.58%   |
| Slutsk       | 7         | 0.58%   |
| Bogushevichi | 7         | 0.58%   |
| Pinsk        | 6         | 0.5%    |
| Navapolatsk  | 6         | 0.5%    |
| Vawkavysk    | 5         | 0.41%   |
| Klyetsk      | 5         | 0.41%   |
| Drahichyn    | 5         | 0.41%   |
| Salihorsk    | 4         | 0.33%   |
| Syanno       | 3         | 0.25%   |
| Smalyavichy  | 3         | 0.25%   |
| Slonim       | 3         | 0.25%   |
| Rahachow     | 3         | 0.25%   |
| Ivanava      | 3         | 0.25%   |
| Fedorovka    | 3         | 0.25%   |
| Dubovka      | 3         | 0.25%   |
| Baran'       | 3         | 0.25%   |
| Aleksandrovo | 3         | 0.25%   |
| Svyetlahorsk | 2         | 0.17%   |
| Snitovo      | 2         | 0.17%   |
| Rechytsa     | 2         | 0.17%   |
| Pruzhany     | 2         | 0.17%   |
| Pastavy      | 2         | 0.17%   |
| Ogorodniki   | 2         | 0.17%   |
| Navahrudak   | 2         | 0.17%   |
| Murava       | 2         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 241       | 394    | 15.49%  |
| Seagate                     | 236       | 375    | 15.17%  |
| Samsung Electronics         | 217       | 311    | 13.95%  |
| Toshiba                     | 155       | 244    | 9.96%   |
| Kingston                    | 102       | 143    | 6.56%   |
| Hitachi                     | 93        | 123    | 5.98%   |
| HGST                        | 55        | 90     | 3.53%   |
| SK hynix                    | 40        | 47     | 2.57%   |
| Intel                       | 38        | 75     | 2.44%   |
| Sandisk                     | 35        | 43     | 2.25%   |
| Crucial                     | 33        | 42     | 2.12%   |
| Unknown                     | 31        | 39     | 1.99%   |
| Patriot                     | 21        | 29     | 1.35%   |
| Micron Technology           | 21        | 28     | 1.35%   |
| Gigabyte Technology         | 14        | 16     | 0.9%    |
| A-DATA Technology           | 14        | 17     | 0.9%    |
| SPCC                        | 12        | 18     | 0.77%   |
| OCZ                         | 12        | 14     | 0.77%   |
| Fujitsu                     | 12        | 19     | 0.77%   |
| KingSpec                    | 11        | 19     | 0.71%   |
| GOODRAM                     | 10        | 11     | 0.64%   |
| Netac                       | 9         | 11     | 0.58%   |
| KIOXIA                      | 9         | 34     | 0.58%   |
| China                       | 9         | 12     | 0.58%   |
| Apacer                      | 9         | 10     | 0.58%   |
| Transcend                   | 8         | 10     | 0.51%   |
| Silicon Motion              | 7         | 8      | 0.45%   |
| Plextor                     | 6         | 7      | 0.39%   |
| Phison Electronics          | 5         | 5      | 0.32%   |
| Maxtor                      | 4         | 4      | 0.26%   |
| Kingston Technology Company | 4         | 4      | 0.26%   |
| JMicron Technology          | 4         | 4      | 0.26%   |
| Apple                       | 4         | 4      | 0.26%   |
| XrayDisk                    | 3         | 3      | 0.19%   |
| XPG                         | 3         | 3      | 0.19%   |
| Smartbuy                    | 3         | 4      | 0.19%   |
| Phison                      | 3         | 3      | 0.19%   |
| Lenovo                      | 3         | 6      | 0.19%   |
| KingDian                    | 3         | 5      | 0.19%   |
| External                    | 3         | 4      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                          | 27        | 1.6%    |
| Toshiba DT01ACA050 500GB                          | 23        | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB                    | 22        | 1.31%   |
| Kingston SA400S37120G 120GB SSD                   | 21        | 1.25%   |
| Toshiba DT01ACA100 1TB                            | 20        | 1.19%   |
| Seagate ST500LT012-1DG142 500GB                   | 19        | 1.13%   |
| Samsung SSD 860 EVO 500GB                         | 18        | 1.07%   |
| Samsung SSD 860 EVO 250GB                         | 18        | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 14        | 0.83%   |
| Kingston SA400S37240G 240GB SSD                   | 13        | 0.77%   |
| Toshiba DT01ACA200 2TB                            | 12        | 0.71%   |
| HGST HTS545050A7E680 500GB                        | 12        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 11        | 0.65%   |
| Crucial CT120BX500SSD1 120GB                      | 11        | 0.65%   |
| Seagate ST9320325AS 320GB                         | 10        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                   | 10        | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 9         | 0.53%   |
| Toshiba MQ04ABF100 1TB                            | 9         | 0.53%   |
| Toshiba MQ01ABD100 1TB                            | 9         | 0.53%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 9         | 0.53%   |
| Hitachi HTS543232A7A384 320GB                     | 9         | 0.53%   |
| HGST HTS721010A9E630 1TB                          | 9         | 0.53%   |
| SK hynix NVMe SSD Drive 512GB                     | 8         | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                    | 8         | 0.48%   |
| Samsung SSD 850 EVO 250GB                         | 8         | 0.48%   |
| WDC WD10EZRZ-00HTKB0 1TB                          | 7         | 0.42%   |
| Toshiba MQ01ABD032 320GB                          | 7         | 0.42%   |
| Toshiba HDWD110 1TB                               | 7         | 0.42%   |
| Seagate ST9500325AS 500GB                         | 7         | 0.42%   |
| Kingston SUV400S37120G 120GB SSD                  | 7         | 0.42%   |
| Intel SSDPEKNU512GZ 512GB                         | 7         | 0.42%   |
| Hitachi HTS545050B9A300 500GB                     | 7         | 0.42%   |
| HGST HTS541010A9E680 1TB                          | 7         | 0.42%   |
| Toshiba MQ01ABD075 752GB                          | 6         | 0.36%   |
| Seagate ST9250315AS 250GB                         | 6         | 0.36%   |
| Patriot Burst 120GB SSD                           | 6         | 0.36%   |
| OCZ VERTEX4 128GB SSD                             | 6         | 0.36%   |
| Hitachi HTS547575A9E384 752GB                     | 6         | 0.36%   |
| Hitachi HTS547550A9E384 500GB                     | 6         | 0.36%   |
| Hitachi HDS721010CLA330 1TB                       | 6         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 235       | 373    | 28.48%  |
| WDC                 | 218       | 338    | 26.42%  |
| Toshiba             | 145       | 229    | 17.58%  |
| Hitachi             | 93        | 123    | 11.27%  |
| HGST                | 55        | 90     | 6.67%   |
| Samsung Electronics | 50        | 78     | 6.06%   |
| Fujitsu             | 12        | 19     | 1.45%   |
| Maxtor              | 4         | 4      | 0.48%   |
| JMicron Technology  | 4         | 4      | 0.48%   |
| WD MediaMax         | 2         | 2      | 0.24%   |
| TO Exter            | 2         | 3      | 0.24%   |
| Unknown             | 1         | 1      | 0.12%   |
| SINTECHI            | 1         | 1      | 0.12%   |
| SAGE                | 1         | 1      | 0.12%   |
| External            | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 86        | 121    | 20.57%  |
| Kingston            | 76        | 108    | 18.18%  |
| Crucial             | 31        | 40     | 7.42%   |
| Patriot             | 19        | 27     | 4.55%   |
| SanDisk             | 16        | 24     | 3.83%   |
| WDC                 | 15        | 39     | 3.59%   |
| OCZ                 | 12        | 14     | 2.87%   |
| SPCC                | 11        | 17     | 2.63%   |
| KingSpec            | 11        | 19     | 2.63%   |
| Intel               | 11        | 13     | 2.63%   |
| Gigabyte Technology | 11        | 13     | 2.63%   |
| A-DATA Technology   | 10        | 12     | 2.39%   |
| GOODRAM             | 9         | 10     | 2.15%   |
| China               | 9         | 12     | 2.15%   |
| Apacer              | 9         | 10     | 2.15%   |
| Transcend           | 8         | 10     | 1.91%   |
| SK hynix            | 8         | 10     | 1.91%   |
| Plextor             | 6         | 7      | 1.44%   |
| Netac               | 6         | 8      | 1.44%   |
| Toshiba             | 4         | 4      | 0.96%   |
| XrayDisk            | 3         | 3      | 0.72%   |
| Unknown             | 3         | 3      | 0.72%   |
| Smartbuy            | 3         | 4      | 0.72%   |
| KingDian            | 3         | 5      | 0.72%   |
| Team                | 2         | 2      | 0.48%   |
| Seagate             | 2         | 2      | 0.48%   |
| Micron Technology   | 2         | 2      | 0.48%   |
| LITEONIT            | 2         | 2      | 0.48%   |
| Lexar               | 2         | 2      | 0.48%   |
| External            | 2         | 3      | 0.48%   |
| Corsair             | 2         | 8      | 0.48%   |
| AMD                 | 2         | 2      | 0.48%   |
| Zheino              | 1         | 2      | 0.24%   |
| USB3.0              | 1         | 1      | 0.24%   |
| Union Memory        | 1         | 1      | 0.24%   |
| T-FORCE             | 1         | 1      | 0.24%   |
| PNY                 | 1         | 5      | 0.24%   |
| OSCOO               | 1         | 1      | 0.24%   |
| OCZ-VERTEX3         | 1         | 3      | 0.24%   |
| OCZ-VERTEX          | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 718       | 1268   | 50.89%  |
| SSD     | 379       | 591    | 26.86%  |
| NVMe    | 279       | 410    | 19.77%  |
| MMC     | 29        | 39     | 2.06%   |
| Unknown | 6         | 6      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 877       | 1835   | 72.42%  |
| NVMe | 279       | 409    | 23.04%  |
| MMC  | 29        | 39     | 2.39%   |
| SAS  | 26        | 31     | 2.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 717       | 1232   | 65.96%  |
| 0.51-1.0   | 285       | 450    | 26.22%  |
| 1.01-2.0   | 52        | 109    | 4.78%   |
| 3.01-4.0   | 11        | 15     | 1.01%   |
| 2.01-3.0   | 11        | 23     | 1.01%   |
| 4.01-10.0  | 7         | 25     | 0.64%   |
| 10.01-20.0 | 4         | 5      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 304       | 24.92%  |
| 251-500        | 286       | 23.44%  |
| 501-1000       | 167       | 13.69%  |
| 1-20           | 120       | 9.84%   |
| 51-100         | 109       | 8.93%   |
| 1001-2000      | 85        | 6.97%   |
| 21-50          | 78        | 6.39%   |
| Unknown        | 27        | 2.21%   |
| More than 3000 | 26        | 2.13%   |
| 2001-3000      | 18        | 1.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 538       | 43.28%  |
| 21-50          | 195       | 15.69%  |
| 101-250        | 139       | 11.18%  |
| 51-100         | 135       | 10.86%  |
| 251-500        | 101       | 8.13%   |
| 501-1000       | 63        | 5.07%   |
| Unknown        | 27        | 2.17%   |
| 1001-2000      | 25        | 2.01%   |
| 2001-3000      | 10        | 0.8%    |
| More than 3000 | 9         | 0.72%   |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 8         | 10     | 2.76%   |
| HGST HTS545050A7E680 500GB         | 7         | 9      | 2.41%   |
| Toshiba DT01ACA100 1TB             | 6         | 7      | 2.07%   |
| Seagate ST9320325AS 320GB          | 6         | 7      | 2.07%   |
| Seagate ST9500325AS 500GB          | 5         | 7      | 1.72%   |
| Toshiba MQ01ABF050 500GB           | 4         | 5      | 1.38%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1.38%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 1.38%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 11     | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 1.38%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 1.38%   |
| Hitachi HDS721010CLA330 1TB        | 4         | 5      | 1.38%   |
| Hitachi HDP725050GLA360 500GB      | 4         | 8      | 1.38%   |
| WDC WD20EARS-00MVWB0 2TB           | 3         | 6      | 1.03%   |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 3      | 1.03%   |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 1.03%   |
| Toshiba DT01ACA200 2TB             | 3         | 5      | 1.03%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 1.03%   |
| Samsung Electronics HD160JJ 160GB  | 3         | 3      | 1.03%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 1.03%   |
| Hitachi HTS543232A7A384 320GB      | 3         | 4      | 1.03%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2         | 2      | 0.69%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 0.69%   |
| WDC WD3200BEKT-60F3T1 320GB        | 2         | 2      | 0.69%   |
| WDC WD30EFRX-68EUZN0 3TB           | 2         | 3      | 0.69%   |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 0.69%   |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.69%   |
| Seagate ST9120822AS 120GB          | 2         | 3      | 0.69%   |
| Seagate ST3500320AS 500GB          | 2         | 3      | 0.69%   |
| Seagate ST340016A 40GB             | 2         | 3      | 0.69%   |
| Seagate ST3250820AS 250GB          | 2         | 2      | 0.69%   |
| Seagate ST3160812A 160GB           | 2         | 4      | 0.69%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 0.69%   |
| Samsung Electronics SP0802N 80GB   | 2         | 2      | 0.69%   |
| Samsung Electronics HD161HJ 160GB  | 2         | 3      | 0.69%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 2      | 0.69%   |
| OCZ VERTEX460A 120GB SSD           | 2         | 3      | 0.69%   |
| OCZ VERTEX4 128GB SSD              | 2         | 2      | 0.69%   |
| Hitachi HTS722010K9SA00 100GB      | 2         | 2      | 0.69%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 0.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 94     | 24.82%  |
| WDC                 | 62        | 79     | 21.99%  |
| Hitachi             | 50        | 64     | 17.73%  |
| Toshiba             | 26        | 35     | 9.22%   |
| Samsung Electronics | 22        | 32     | 7.8%    |
| HGST                | 14        | 16     | 4.96%   |
| Kingston            | 6         | 6      | 2.13%   |
| Fujitsu             | 6         | 8      | 2.13%   |
| OCZ                 | 5         | 6      | 1.77%   |
| SK hynix            | 3         | 3      | 1.06%   |
| Crucial             | 3         | 3      | 1.06%   |
| WD MediaMax         | 2         | 2      | 0.71%   |
| Maxtor              | 2         | 2      | 0.71%   |
| SanDisk             | 1         | 1      | 0.35%   |
| PNY                 | 1         | 4      | 0.35%   |
| OCZ-VERTEX3         | 1         | 3      | 0.35%   |
| Micron Technology   | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| KingSpec            | 1         | 6      | 0.35%   |
| Intel               | 1         | 1      | 0.35%   |
| Corsair             | 1         | 4      | 0.35%   |
| Apacer              | 1         | 1      | 0.35%   |
| A-DATA Technology   | 1         | 1      | 0.35%   |
| Unknown             | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 94     | 27.78%  |
| WDC                 | 62        | 79     | 24.6%   |
| Hitachi             | 50        | 64     | 19.84%  |
| Toshiba             | 26        | 35     | 10.32%  |
| Samsung Electronics | 20        | 30     | 7.94%   |
| HGST                | 14        | 16     | 5.56%   |
| Fujitsu             | 6         | 8      | 2.38%   |
| WD MediaMax         | 2         | 2      | 0.79%   |
| Maxtor              | 2         | 2      | 0.79%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 231       | 330    | 88.51%  |
| SSD  | 27        | 41     | 10.34%  |
| NVMe | 3         | 3      | 1.15%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB        | 1         | 1      | 10%     |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 10%     |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 10%     |
| Samsung Electronics SP0802N 80GB    | 1         | 1      | 10%     |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 10%     |
| Samsung Electronics HD252HJ 250GB   | 1         | 1      | 10%     |
| Maxtor STM380211AS 80GB             | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 10%     |
| HGST HTS545050B7E660 500GB          | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| Seagate             | 2         | 2      | 20%     |
| Maxtor              | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 644       | 1290   | 51.03%  |
| Detected | 350       | 640    | 27.73%  |
| Malfunc  | 258       | 374    | 20.44%  |
| Failed   | 10        | 10     | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 705       | 53.57%  |
| AMD                                     | 236       | 17.93%  |
| Samsung Electronics                     | 92        | 6.99%   |
| Nvidia                                  | 53        | 4.03%   |
| SanDisk                                 | 32        | 2.43%   |
| SK hynix                                | 31        | 2.36%   |
| Kingston Technology Company             | 30        | 2.28%   |
| JMicron Technology                      | 21        | 1.6%    |
| Micron Technology                       | 20        | 1.52%   |
| Phison Electronics                      | 13        | 0.99%   |
| Silicon Motion                          | 11        | 0.84%   |
| Marvell Technology Group                | 11        | 0.84%   |
| ASMedia Technology                      | 10        | 0.76%   |
| Toshiba America Info Systems            | 9         | 0.68%   |
| KIOXIA                                  | 9         | 0.68%   |
| VIA Technologies                        | 5         | 0.38%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.3%    |
| Realtek Semiconductor                   | 3         | 0.23%   |
| Netac Technology                        | 3         | 0.23%   |
| Lenovo                                  | 3         | 0.23%   |
| ADATA Technology                        | 3         | 0.23%   |
| Apple                                   | 2         | 0.15%   |
| Synopsys                                | 1         | 0.08%   |
| Solid State Storage Technology          | 1         | 0.08%   |
| Silicon Image                           | 1         | 0.08%   |
| Shenzhen Unionmemory Information System | 1         | 0.08%   |
| O2 Micro                                | 1         | 0.08%   |
| Micron/Crucial Technology               | 1         | 0.08%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.08%   |
| Integrated Technology Express           | 1         | 0.08%   |
| Broadcom / LSI                          | 1         | 0.08%   |
| Biwin Storage Technology                | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 121       | 7.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 71        | 4.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 50        | 3.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 49        | 3.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 48        | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 39        | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 38        | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 36        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 2.27%   |
| Nvidia MCP61 SATA Controller                                                            | 34        | 2.15%   |
| Nvidia MCP61 IDE                                                                        | 34        | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 31        | 1.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 27        | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26        | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 25        | 1.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 24        | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 23        | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 21        | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 20        | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 18        | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 17        | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 14        | 0.88%   |
| Intel SSD 660P Series                                                                   | 14        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 0.82%   |
| AMD FCH IDE Controller                                                                  | 13        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 12        | 0.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 11        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 802       | 58.28%  |
| NVMe | 280       | 20.35%  |
| IDE  | 242       | 17.59%  |
| RAID | 51        | 3.71%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 761       | 69.62%  |
| AMD    | 328       | 30.01%  |
| ARM    | 4         | 0.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.55%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 16        | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.91%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 0.91%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 0.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.73%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.64%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.64%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.55%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 0.55%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 0.55%   |
| AMD Athlon II X2 245 Processor                | 6         | 0.55%   |
| AMD Athlon II X2 240 Processor                | 6         | 0.55%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+    | 6         | 0.55%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 6         | 0.55%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 0.46%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 5         | 0.46%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.46%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.46%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 5         | 0.46%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.46%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 5         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 171       | 15.59%  |
| Intel Core i7           | 119       | 10.85%  |
| Intel Celeron           | 93        | 8.48%   |
| Intel Core i3           | 86        | 7.84%   |
| Other                   | 66        | 6.02%   |
| Intel Pentium           | 65        | 5.93%   |
| AMD Ryzen 5             | 64        | 5.83%   |
| Intel Core 2 Duo        | 46        | 4.19%   |
| Intel Atom              | 37        | 3.37%   |
| AMD Ryzen 7             | 35        | 3.19%   |
| AMD Athlon II X2        | 24        | 2.19%   |
| AMD Athlon 64 X2        | 24        | 2.19%   |
| AMD FX                  | 22        | 2.01%   |
| Intel Pentium Dual-Core | 16        | 1.46%   |
| AMD Ryzen 3             | 16        | 1.46%   |
| Intel Xeon              | 15        | 1.37%   |
| AMD A4                  | 14        | 1.28%   |
| AMD E                   | 13        | 1.19%   |
| AMD A6                  | 12        | 1.09%   |
| AMD Athlon II X3        | 10        | 0.91%   |
| AMD Phenom II X4        | 9         | 0.82%   |
| AMD E1                  | 9         | 0.82%   |
| AMD A8                  | 9         | 0.82%   |
| Intel Pentium Dual      | 8         | 0.73%   |
| AMD A10                 | 8         | 0.73%   |
| Intel Pentium Silver    | 7         | 0.64%   |
| Intel Genuine           | 7         | 0.64%   |
| AMD Athlon              | 7         | 0.64%   |
| Intel Core i9           | 6         | 0.55%   |
| Intel Pentium 4         | 5         | 0.46%   |
| Intel Celeron Dual-Core | 5         | 0.46%   |
| AMD Athlon X4           | 5         | 0.46%   |
| AMD Athlon II           | 5         | 0.46%   |
| AMD Turion II           | 4         | 0.36%   |
| AMD E2                  | 4         | 0.36%   |
| AMD Athlon II X4        | 4         | 0.36%   |
| Intel Core 2 Solo       | 3         | 0.27%   |
| Intel Core 2 Quad       | 3         | 0.27%   |
| Intel Core 2            | 3         | 0.27%   |
| AMD Ryzen 9             | 3         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 519       | 46.8%   |
| 4       | 308       | 27.77%  |
| 6       | 91        | 8.21%   |
| 8       | 57        | 5.14%   |
| 1       | 56        | 5.05%   |
| Unknown | 36        | 3.25%   |
| 3       | 17        | 1.53%   |
| 12      | 10        | 0.9%    |
| 10      | 10        | 0.9%    |
| 14      | 4         | 0.36%   |
| 16      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1089      | 99.63%  |
| 2       | 3         | 0.27%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 589       | 53.02%  |
| 1       | 486       | 43.74%  |
| Unknown | 36        | 3.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1056      | 96.44%  |
| Unknown        | 22        | 2.01%   |
| 32-bit         | 17        | 1.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 244       | 21.42%  |
| 0x206a7    | 76        | 6.67%   |
| 0x306a9    | 64        | 5.62%   |
| 0x1067a    | 47        | 4.13%   |
| 0x010000c8 | 39        | 3.42%   |
| 0x306c3    | 38        | 3.34%   |
| 0x806ea    | 27        | 2.37%   |
| 0x806c1    | 24        | 2.11%   |
| 0x30678    | 23        | 2.02%   |
| 0x906ea    | 21        | 1.84%   |
| 0x06001119 | 19        | 1.67%   |
| 0x806ec    | 18        | 1.58%   |
| 0x40651    | 17        | 1.49%   |
| 0x106ca    | 17        | 1.49%   |
| 0x6fd      | 16        | 1.4%    |
| 0x406e3    | 16        | 1.4%    |
| 0x906e9    | 14        | 1.23%   |
| 0x05000119 | 14        | 1.23%   |
| 0x010000c7 | 13        | 1.14%   |
| 0x506e3    | 12        | 1.05%   |
| 0x506c9    | 12        | 1.05%   |
| 0x306d4    | 12        | 1.05%   |
| 0x806e9    | 11        | 0.97%   |
| 0x0a50000c | 11        | 0.97%   |
| 0x706a1    | 10        | 0.88%   |
| 0x10676    | 10        | 0.88%   |
| 0x08608103 | 10        | 0.88%   |
| 0x08108102 | 10        | 0.88%   |
| 0x06000852 | 10        | 0.88%   |
| 0x10661    | 9         | 0.79%   |
| 0x0800820d | 9         | 0.79%   |
| 0x20652    | 8         | 0.7%    |
| 0x106c2    | 8         | 0.7%    |
| 0x08600106 | 8         | 0.7%    |
| 0x08600104 | 8         | 0.7%    |
| 0x03000027 | 8         | 0.7%    |
| 0x706e5    | 7         | 0.61%   |
| 0x6fb      | 7         | 0.61%   |
| 0x406c4    | 7         | 0.61%   |
| 0x406c3    | 7         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 146       | 13.3%   |
| SandyBridge       | 85        | 7.74%   |
| IvyBridge         | 80        | 7.29%   |
| K10               | 69        | 6.28%   |
| Haswell           | 68        | 6.19%   |
| Penryn            | 65        | 5.92%   |
| Core              | 43        | 3.92%   |
| Silvermont        | 42        | 3.83%   |
| Unknown           | 41        | 3.73%   |
| Piledriver        | 40        | 3.64%   |
| Skylake           | 36        | 3.28%   |
| K8 Hammer         | 31        | 2.82%   |
| Zen+              | 30        | 2.73%   |
| TigerLake         | 30        | 2.73%   |
| Bonnell           | 30        | 2.73%   |
| Zen 2             | 27        | 2.46%   |
| Zen 3             | 26        | 2.37%   |
| Zen               | 21        | 1.91%   |
| Goldmont plus     | 18        | 1.64%   |
| Bobcat            | 18        | 1.64%   |
| IceLake           | 17        | 1.55%   |
| Westmere          | 16        | 1.46%   |
| Alderlake Hybrid  | 16        | 1.46%   |
| Goldmont          | 15        | 1.37%   |
| Broadwell         | 14        | 1.28%   |
| CometLake         | 12        | 1.09%   |
| K10 Llano         | 11        | 1%      |
| Excavator         | 10        | 0.91%   |
| NetBurst          | 7         | 0.64%   |
| Puma              | 6         | 0.55%   |
| Nehalem           | 6         | 0.55%   |
| Jaguar            | 6         | 0.55%   |
| P6                | 5         | 0.46%   |
| Bulldozer         | 4         | 0.36%   |
| Steamroller       | 3         | 0.27%   |
| Tremont           | 2         | 0.18%   |
| Meteorlake Hybrid | 1         | 0.09%   |
| K8 & K10 hybrid   | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 592       | 43.85%  |
| Nvidia                           | 441       | 32.67%  |
| AMD                              | 310       | 22.96%  |
| Silicon Integrated Systems [SiS] | 3         | 0.22%   |
| ASPEED Technology                | 2         | 0.15%   |
| Matrox Electronics Systems       | 1         | 0.07%   |
| ATI Technologies                 | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 67        | 4.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 53        | 3.74%   |
| Intel UHD Graphics 620                                                                   | 33        | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 1.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 1.41%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 20        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.06%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.99%   |
| Intel HD Graphics 630                                                                    | 14        | 0.99%   |
| AMD Lucienne                                                                             | 14        | 0.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.92%   |
| Intel HD Graphics 620                                                                    | 13        | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 13        | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 0.85%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.85%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 11        | 0.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 10        | 0.71%   |
| Intel HD Graphics 500                                                                    | 10        | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.64%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 9         | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 358       | 32.6%   |
| 1 x Nvidia      | 237       | 21.58%  |
| 1 x AMD         | 212       | 19.31%  |
| Intel + Nvidia  | 181       | 16.48%  |
| Intel + AMD     | 46        | 4.19%   |
| 2 x AMD         | 33        | 3.01%   |
| AMD + Nvidia    | 19        | 1.73%   |
| Other           | 4         | 0.36%   |
| 1 x SiS         | 3         | 0.27%   |
| 2 x Nvidia      | 1         | 0.09%   |
| 2 x Intel       | 1         | 0.09%   |
| Nvidia + ASPEED | 1         | 0.09%   |
| 1 x Matrox      | 1         | 0.09%   |
| 1 x ASPEED      | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 881       | 78.1%   |
| Proprietary | 196       | 17.38%  |
| Unknown     | 51        | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 431       | 37.74%  |
| 1.01-2.0   | 254       | 22.24%  |
| 0.01-0.5   | 240       | 21.02%  |
| 0.51-1.0   | 104       | 9.11%   |
| 3.01-4.0   | 66        | 5.78%   |
| 7.01-8.0   | 20        | 1.75%   |
| 5.01-6.0   | 16        | 1.4%    |
| 2.01-3.0   | 5         | 0.44%   |
| 8.01-16.0  | 5         | 0.44%   |
| 4.01-5.0   | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 182       | 15.95%  |
| AU Optronics            | 152       | 13.32%  |
| BOE                     | 111       | 9.73%   |
| Goldstar                | 110       | 9.64%   |
| Chimei Innolux          | 97        | 8.5%    |
| LG Display              | 91        | 7.98%   |
| Chi Mei Optoelectronics | 51        | 4.47%   |
| Philips                 | 46        | 4.03%   |
| Dell                    | 41        | 3.59%   |
| BenQ                    | 30        | 2.63%   |
| AOC                     | 27        | 2.37%   |
| ViewSonic               | 18        | 1.58%   |
| PANDA                   | 18        | 1.58%   |
| Hewlett-Packard         | 14        | 1.23%   |
| Acer                    | 13        | 1.14%   |
| Lenovo                  | 12        | 1.05%   |
| LG Philips              | 10        | 0.88%   |
| Ancor Communications    | 10        | 0.88%   |
| HannStar                | 9         | 0.79%   |
| CPT                     | 9         | 0.79%   |
| Unknown                 | 8         | 0.7%    |
| Apple                   | 8         | 0.7%    |
| Sony                    | 7         | 0.61%   |
| Sharp                   | 7         | 0.61%   |
| NEC Computers           | 7         | 0.61%   |
| Iiyama                  | 7         | 0.61%   |
| LG Electronics          | 5         | 0.44%   |
| XYK                     | 3         | 0.26%   |
| Gigabyte Technology     | 3         | 0.26%   |
| ASUSTek Computer        | 3         | 0.26%   |
| Valve                   | 2         | 0.18%   |
| TMX                     | 2         | 0.18%   |
| Plain Tree Systems      | 2         | 0.18%   |
| Mi                      | 2         | 0.18%   |
| LGD                     | 2         | 0.18%   |
| CSO                     | 2         | 0.18%   |
| Toshiba                 | 1         | 0.09%   |
| SKK                     | 1         | 0.09%   |
| Seiko/Epson             | 1         | 0.09%   |
| RGT                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 1.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 12        | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.95%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.86%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.6%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 7         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.52%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.52%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                     | 6         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.52%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.52%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.52%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 5         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 5         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.43%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 5         | 0.43%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.43%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch     | 4         | 0.34%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 4         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.34%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 4         | 0.34%   |
| Goldstar L1919S GSM4AF2 1280x1024 376x301mm 19.0-inch                    | 4         | 0.34%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 4         | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 452       | 40.65%  |
| 1366x768 (WXGA)    | 271       | 24.37%  |
| 1280x1024 (SXGA)   | 62        | 5.58%   |
| 1600x900 (HD+)     | 51        | 4.59%   |
| 3840x2160 (4K)     | 42        | 3.78%   |
| 2560x1440 (QHD)    | 37        | 3.33%   |
| 1440x900 (WXGA+)   | 32        | 2.88%   |
| 1680x1050 (WSXGA+) | 31        | 2.79%   |
| 1280x800 (WXGA)    | 28        | 2.52%   |
| 1024x600           | 20        | 1.8%    |
| 1920x1200 (WUXGA)  | 12        | 1.08%   |
| 2560x1080          | 10        | 0.9%    |
| 2560x1600          | 8         | 0.72%   |
| 2880x1800          | 7         | 0.63%   |
| 2288x1287          | 5         | 0.45%   |
| 1360x768           | 5         | 0.45%   |
| 1024x768 (XGA)     | 5         | 0.45%   |
| 3440x1440          | 4         | 0.36%   |
| 3200x2000          | 3         | 0.27%   |
| 800x1280           | 2         | 0.18%   |
| 3840x2400          | 2         | 0.18%   |
| 2880x1620          | 2         | 0.18%   |
| 2160x1440          | 2         | 0.18%   |
| 1600x1200          | 2         | 0.18%   |
| 1152x864           | 2         | 0.18%   |
| Unknown            | 2         | 0.18%   |
| 4480x1200          | 1         | 0.09%   |
| 3840x1080          | 1         | 0.09%   |
| 3072x1920          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2400x1600          | 1         | 0.09%   |
| 2240x1400          | 1         | 0.09%   |
| 2048x1536          | 1         | 0.09%   |
| 2048x1152          | 1         | 0.09%   |
| 1920x540           | 1         | 0.09%   |
| 1920x1440          | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1400x1050          | 1         | 0.09%   |
| 1280x960           | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 435       | 38.02%  |
| 17      | 95        | 8.3%    |
| 21      | 86        | 7.52%   |
| 23      | 76        | 6.64%   |
| 13      | 59        | 5.16%   |
| 24      | 56        | 4.9%    |
| 19      | 54        | 4.72%   |
| 14      | 51        | 4.46%   |
| 27      | 39        | 3.41%   |
| Unknown | 26        | 2.27%   |
| 18      | 22        | 1.92%   |
| 10      | 20        | 1.75%   |
| 22      | 18        | 1.57%   |
| 16      | 18        | 1.57%   |
| 31      | 15        | 1.31%   |
| 20      | 15        | 1.31%   |
| 34      | 13        | 1.14%   |
| 40      | 7         | 0.61%   |
| 11      | 6         | 0.52%   |
| 142     | 5         | 0.44%   |
| 12      | 5         | 0.44%   |
| 72      | 4         | 0.35%   |
| 54      | 4         | 0.35%   |
| 84      | 2         | 0.17%   |
| 52      | 2         | 0.17%   |
| 46      | 2         | 0.17%   |
| 8       | 2         | 0.17%   |
| 7       | 2         | 0.17%   |
| 55      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 25      | 1         | 0.09%   |
| 9       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 548       | 48.54%  |
| 501-600        | 158       | 13.99%  |
| 401-500        | 158       | 13.99%  |
| 351-400        | 114       | 10.1%   |
| 201-300        | 60        | 5.31%   |
| Unknown        | 26        | 2.3%    |
| 601-700        | 19        | 1.68%   |
| 701-800        | 13        | 1.15%   |
| 1001-1500      | 9         | 0.8%    |
| 801-900        | 7         | 0.62%   |
| 1501-2000      | 6         | 0.53%   |
| More than 2000 | 5         | 0.44%   |
| 101-200        | 3         | 0.27%   |
| 1-100          | 2         | 0.18%   |
| 901-1000       | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 818       | 76.66%  |
| 16/10   | 122       | 11.43%  |
| 5/4     | 60        | 5.62%   |
| Unknown | 24        | 2.25%   |
| 4/3     | 14        | 1.31%   |
| 21/9    | 13        | 1.22%   |
| 3/2     | 7         | 0.66%   |
| 1.00    | 6         | 0.56%   |
| 0.67    | 2         | 0.19%   |
| 0.62    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 440       | 38.8%   |
| 201-250        | 191       | 16.84%  |
| 151-200        | 87        | 7.67%   |
| 81-90          | 84        | 7.41%   |
| 121-130        | 53        | 4.67%   |
| 141-150        | 47        | 4.14%   |
| 301-350        | 40        | 3.53%   |
| 351-500        | 28        | 2.47%   |
| Unknown        | 26        | 2.29%   |
| 71-80          | 24        | 2.12%   |
| 41-50          | 21        | 1.85%   |
| 251-300        | 21        | 1.85%   |
| More than 1000 | 18        | 1.59%   |
| 131-140        | 15        | 1.32%   |
| 111-120        | 12        | 1.06%   |
| 501-1000       | 10        | 0.88%   |
| 51-60          | 6         | 0.53%   |
| 61-70          | 5         | 0.44%   |
| 1-40           | 4         | 0.35%   |
| 91-100         | 2         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 368       | 33.21%  |
| 101-120       | 360       | 32.49%  |
| 121-160       | 269       | 24.28%  |
| 161-240       | 40        | 3.61%   |
| Unknown       | 26        | 2.35%   |
| 1-50          | 23        | 2.08%   |
| More than 240 | 22        | 1.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 950       | 85.51%  |
| 2     | 112       | 10.08%  |
| 0     | 41        | 3.69%   |
| 3     | 8         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 666       | 40.91%  |
| Intel                                  | 301       | 18.49%  |
| Qualcomm Atheros                       | 278       | 17.08%  |
| Broadcom                               | 111       | 6.82%   |
| Nvidia                                 | 40        | 2.46%   |
| Marvell Technology Group               | 32        | 1.97%   |
| MediaTek                               | 26        | 1.6%    |
| Ralink                                 | 25        | 1.54%   |
| Ralink Technology                      | 24        | 1.47%   |
| TP-Link                                | 23        | 1.41%   |
| Broadcom Limited                       | 19        | 1.17%   |
| Huawei Technologies                    | 9         | 0.55%   |
| D-Link                                 | 8         | 0.49%   |
| Xiaomi                                 | 5         | 0.31%   |
| VIA Technologies                       | 5         | 0.31%   |
| Qualcomm                               | 5         | 0.31%   |
| Qualcomm Atheros Communications        | 4         | 0.25%   |
| JMicron Technology                     | 4         | 0.25%   |
| D-Link System                          | 4         | 0.25%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.18%   |
| Sierra Wireless                        | 3         | 0.18%   |
| FIBOCOM                                | 3         | 0.18%   |
| Attansic Technology                    | 3         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| IMC Networks                           | 2         | 0.12%   |
| Hewlett-Packard                        | 2         | 0.12%   |
| ASIX Electronics                       | 2         | 0.12%   |
| Aquantia                               | 2         | 0.12%   |
| Texas Instruments                      | 1         | 0.06%   |
| STMicroelectronics                     | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Samsung Electronics                    | 1         | 0.06%   |
| Philips (or NXP)                       | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Mercucys                               | 1         | 0.06%   |
| Lenovo                                 | 1         | 0.06%   |
| HTC (High Tech Computer)               | 1         | 0.06%   |
| HMD Global                             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 476       | 25.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 112       | 6.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 56        | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 2.26%   |
| Intel Wireless 8265 / 8275                                              | 41        | 2.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 1.56%   |
| Nvidia MCP61 Ethernet                                                   | 27        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.18%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 1.13%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 1.08%   |
| Ralink MT7601U Wireless Adapter                                         | 18        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 14        | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 13        | 0.7%    |
| Intel Wireless 7265                                                     | 13        | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                       | 11        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 11        | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 11        | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.59%   |
| Intel Wireless 7260                                                     | 10        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                    | 10        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.48%   |
| Intel I211 Gigabit Network Connection                                   | 9         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 8         | 0.43%   |
| Intel WiFi Link 5100                                                    | 8         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 256       | 29.8%   |
| Qualcomm Atheros                | 221       | 25.73%  |
| Realtek Semiconductor           | 162       | 18.86%  |
| Broadcom                        | 82        | 9.55%   |
| MediaTek                        | 26        | 3.03%   |
| Ralink                          | 25        | 2.91%   |
| Ralink Technology               | 24        | 2.79%   |
| TP-Link                         | 20        | 2.33%   |
| Broadcom Limited                | 12        | 1.4%    |
| D-Link                          | 8         | 0.93%   |
| Qualcomm Atheros Communications | 4         | 0.47%   |
| Sierra Wireless                 | 3         | 0.35%   |
| Qualcomm                        | 3         | 0.35%   |
| Fibocom                         | 3         | 0.35%   |
| IMC Networks                    | 2         | 0.23%   |
| Texas Instruments               | 1         | 0.12%   |
| Philips (or NXP)                | 1         | 0.12%   |
| Microsoft                       | 1         | 0.12%   |
| Mercucys                        | 1         | 0.12%   |
| Marvell Technology Group        | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| D-Link System                   | 1         | 0.12%   |
| Unknown                         | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 56        | 6.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 5.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 4.87%   |
| Intel Wireless 8265 / 8275                                              | 41        | 4.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 3.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 3.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.55%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 2.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 2.43%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 2.32%   |
| Ralink MT7601U Wireless Adapter                                         | 18        | 2.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 2.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.62%   |
| Intel Wireless 7265                                                     | 13        | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.27%   |
| Intel Wireless 7260                                                     | 10        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.93%   |
| Intel WiFi Link 5100                                                    | 8         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.81%   |
| Intel Wireless 8260                                                     | 7         | 0.81%   |
| Intel Wireless 3165                                                     | 7         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 620       | 63.59%  |
| Intel                                  | 94        | 9.64%   |
| Qualcomm Atheros                       | 90        | 9.23%   |
| Broadcom                               | 43        | 4.41%   |
| Nvidia                                 | 40        | 4.1%    |
| Marvell Technology Group               | 31        | 3.18%   |
| Broadcom Limited                       | 7         | 0.72%   |
| Huawei Technologies                    | 6         | 0.62%   |
| Xiaomi                                 | 5         | 0.51%   |
| VIA Technologies                       | 5         | 0.51%   |
| JMicron Technology                     | 4         | 0.41%   |
| TP-Link                                | 3         | 0.31%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.31%   |
| D-Link System                          | 3         | 0.31%   |
| Attansic Technology                    | 3         | 0.31%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.21%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.21%   |
| Qualcomm                               | 2         | 0.21%   |
| ASIX Electronics                       | 2         | 0.21%   |
| Aquantia                               | 2         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Samsung Electronics                    | 1         | 0.1%    |
| Motorola PCS                           | 1         | 0.1%    |
| Lenovo                                 | 1         | 0.1%    |
| HTC (High Tech Computer)               | 1         | 0.1%    |
| HMD Global                             | 1         | 0.1%    |
| Davicom Semiconductor                  | 1         | 0.1%    |
| Apple                                  | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 476       | 48.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 112       | 11.34%  |
| Nvidia MCP61 Ethernet                                                          | 27        | 2.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 14        | 1.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 13        | 1.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 11        | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                           | 10        | 1.01%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.71%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 0.61%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.51%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 5         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 0.51%   |
| Huawei VTR-L09                                                                 | 5         | 0.51%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 4         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.4%    |
| Nvidia MCP65 Ethernet                                                          | 4         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.4%    |
| Intel Ethernet Controller I225-V                                               | 4         | 0.4%    |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.4%    |
| Intel Ethernet Connection (14) I219-V                                          | 4         | 0.4%    |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.4%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.4%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 939       | 53.14%  |
| WiFi     | 821       | 46.46%  |
| Modem    | 6         | 0.34%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 691       | 60.51%  |
| Ethernet | 451       | 39.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 622       | 56.8%   |
| 1     | 449       | 41%     |
| 0     | 16        | 1.46%   |
| 3     | 7         | 0.64%   |
| 4     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1080      | 98.18%  |
| Yes  | 20        | 1.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 212       | 33.23%  |
| Realtek Semiconductor           | 90        | 14.11%  |
| Qualcomm Atheros Communications | 69        | 10.82%  |
| IMC Networks                    | 54        | 8.46%   |
| Broadcom                        | 36        | 5.64%   |
| Lite-On Technology              | 30        | 4.7%    |
| Cambridge Silicon Radio         | 30        | 4.7%    |
| Foxconn / Hon Hai               | 29        | 4.55%   |
| Ralink                          | 15        | 2.35%   |
| ASUSTek Computer                | 15        | 2.35%   |
| Foxconn International           | 10        | 1.57%   |
| Hewlett-Packard                 | 8         | 1.25%   |
| Toshiba                         | 7         | 1.1%    |
| Apple                           | 5         | 0.78%   |
| MediaTek                        | 4         | 0.63%   |
| Realtek                         | 3         | 0.47%   |
| Ralink Technology               | 3         | 0.47%   |
| Dell                            | 3         | 0.47%   |
| Taiyo Yuden                     | 2         | 0.31%   |
| Qcom                            | 2         | 0.31%   |
| Integrated System Solution      | 2         | 0.31%   |
| USI                             | 1         | 0.16%   |
| TP-Link                         | 1         | 0.16%   |
| Opticis                         | 1         | 0.16%   |
| Micro Star International        | 1         | 0.16%   |
| Marvell Semiconductor           | 1         | 0.16%   |
| Chicony Electronics             | 1         | 0.16%   |
| Alps Electric                   | 1         | 0.16%   |
| Actions                         | 1         | 0.16%   |
| Unknown                         | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 59        | 9.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 48        | 7.51%   |
| Intel Bluetooth Device                              | 46        | 7.2%    |
| Intel AX201 Bluetooth                               | 38        | 5.95%   |
| Intel Bluetooth wireless interface                  | 36        | 5.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 4.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 3.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 20        | 3.13%   |
| Intel AX200 Bluetooth                               | 19        | 2.97%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 2.66%   |
| IMC Networks Wireless_Device                        | 16        | 2.5%    |
| Ralink RT3290 Bluetooth                             | 15        | 2.35%   |
| IMC Networks Bluetooth Radio                        | 13        | 2.03%   |
| Lite-On Bluetooth Device                            | 11        | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.56%   |
| Realtek 802.11ac WLAN Adapter                       | 10        | 1.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.56%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 1.56%   |
| IMC Networks Bluetooth Device                       | 9         | 1.41%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                   | 7         | 1.1%    |
| Realtek RTL8723B Bluetooth                          | 6         | 0.94%   |
| Qualcomm Atheros Bluetooth                          | 6         | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 0.94%   |
| Intel AX211 Bluetooth                               | 5         | 0.78%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.63%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.63%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.47%   |
| Realtek Bluetooth Radio                             | 3         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.47%   |
| MediaTek Wireless_Device                            | 3         | 0.47%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 737       | 51%     |
| AMD                              | 325       | 22.49%  |
| Nvidia                           | 270       | 18.69%  |
| C-Media Electronics              | 19        | 1.31%   |
| Logitech                         | 12        | 0.83%   |
| Creative Labs                    | 11        | 0.76%   |
| JMTek                            | 10        | 0.69%   |
| Texas Instruments                | 8         | 0.55%   |
| Silicon Integrated Systems [SiS] | 4         | 0.28%   |
| Generalplus Technology           | 4         | 0.28%   |
| Conexant Systems                 | 3         | 0.21%   |
| Tenx Technology                  | 2         | 0.14%   |
| SteelSeries ApS                  | 2         | 0.14%   |
| M-Audio                          | 2         | 0.14%   |
| Kingston Technology              | 2         | 0.14%   |
| GYROCOM C&C                      | 2         | 0.14%   |
| GN Netcom                        | 2         | 0.14%   |
| ESS Technology                   | 2         | 0.14%   |
| ASUSTek Computer                 | 2         | 0.14%   |
| Apple                            | 2         | 0.14%   |
| Yealink Network Technology       | 1         | 0.07%   |
| Yamaha                           | 1         | 0.07%   |
| VIA Technologies                 | 1         | 0.07%   |
| Synaptics                        | 1         | 0.07%   |
| ROCCAT                           | 1         | 0.07%   |
| Realtek Semiconductor            | 1         | 0.07%   |
| Razer USA                        | 1         | 0.07%   |
| Plantronics                      | 1         | 0.07%   |
| Pixart Imaging                   | 1         | 0.07%   |
| NXP Semiconductors               | 1         | 0.07%   |
| Nordic Semiconductor ASA         | 1         | 0.07%   |
| Micro Star International         | 1         | 0.07%   |
| JBL                              | 1         | 0.07%   |
| iCreate Technologies             | 1         | 0.07%   |
| Huawei Technologies              | 1         | 0.07%   |
| Focusrite-Novation               | 1         | 0.07%   |
| FIFINE Microphones               | 1         | 0.07%   |
| Edifier Technology               | 1         | 0.07%   |
| Creative Technology              | 1         | 0.07%   |
| BR25                             | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 94        | 5.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 93        | 5.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 87        | 5.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 68        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 64        | 3.71%   |
| AMD FCH Azalia Controller                                                  | 53        | 3.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52        | 3.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 2.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 39        | 2.26%   |
| Nvidia MCP61 High Definition Audio                                         | 33        | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 32        | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 32        | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 30        | 1.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 30        | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 25        | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 24        | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24        | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.39%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20        | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 18        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18        | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 1.04%   |
| AMD Trinity HDMI Audio Controller                                          | 18        | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17        | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 15        | 0.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 14        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14        | 0.81%   |
| AMD Wrestler HDMI Audio                                                    | 14        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 13        | 0.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 0.75%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 193       | 19.53%  |
| Samsung Electronics   | 187       | 18.93%  |
| SK hynix              | 150       | 15.18%  |
| Kingston              | 127       | 12.85%  |
| Micron Technology     | 78        | 7.89%   |
| Crucial               | 60        | 6.07%   |
| Elpida                | 26        | 2.63%   |
| Ramaxel Technology    | 17        | 1.72%   |
| Patriot               | 17        | 1.72%   |
| G.Skill               | 17        | 1.72%   |
| Nanya Technology      | 16        | 1.62%   |
| A-DATA Technology     | 14        | 1.42%   |
| Corsair               | 11        | 1.11%   |
| Transcend             | 8         | 0.81%   |
| Silicon Power         | 8         | 0.81%   |
| GOODRAM               | 7         | 0.71%   |
| ASint Technology      | 7         | 0.71%   |
| Team                  | 5         | 0.51%   |
| GeIL                  | 5         | 0.51%   |
| Unknown               | 5         | 0.51%   |
| Apacer                | 4         | 0.4%    |
| 48spaces              | 4         | 0.4%    |
| Unknown (ABCD)        | 3         | 0.3%    |
| TakeMS                | 2         | 0.2%    |
| SHARETRONIC           | 2         | 0.2%    |
| Qumo                  | 2         | 0.2%    |
| Kllisre               | 2         | 0.2%    |
| Kingmax               | 2         | 0.2%    |
| Wilk Elektronik       | 1         | 0.1%    |
| Wilk                  | 1         | 0.1%    |
| Unknown (89F7)        | 1         | 0.1%    |
| Qimonda               | 1         | 0.1%    |
| PNY                   | 1         | 0.1%    |
| Netac                 | 1         | 0.1%    |
| Kingmax Semiconductor | 1         | 0.1%    |
| Goldkey               | 1         | 0.1%    |
| AMD                   | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 13        | 1.2%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 11        | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 10        | 0.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 9         | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 9         | 0.83%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s | 8         | 0.74%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 7         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 7         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 7         | 0.65%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 6         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 6         | 0.55%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 6         | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 6         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 6         | 0.55%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s    | 6         | 0.55%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s   | 6         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 5         | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 5         | 0.46%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 5         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 5         | 0.46%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s            | 5         | 0.46%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s   | 5         | 0.46%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 0.46%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s   | 5         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 5         | 0.46%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s    | 5         | 0.46%   |
| Unknown                                                  | 5         | 0.46%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 4         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 4         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s            | 4         | 0.37%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 4         | 0.37%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 4         | 0.37%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 4         | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 4         | 0.37%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 4         | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 4         | 0.37%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s          | 4         | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s | 4         | 0.37%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s    | 4         | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s    | 4         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 335       | 39.79%  |
| DDR4    | 255       | 30.29%  |
| DDR2    | 78        | 9.26%   |
| Unknown | 75        | 8.91%   |
| SDRAM   | 51        | 6.06%   |
| LPDDR4  | 17        | 2.02%   |
| DDR     | 9         | 1.07%   |
| LPDDR5  | 8         | 0.95%   |
| DDR5    | 8         | 0.95%   |
| DRAM    | 4         | 0.48%   |
| LPDDR3  | 2         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 500       | 60.24%  |
| DIMM         | 299       | 36.02%  |
| Row Of Chips | 31        | 3.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 323       | 33.37%  |
| 2048  | 230       | 23.76%  |
| 8192  | 220       | 22.73%  |
| 16384 | 97        | 10.02%  |
| 1024  | 69        | 7.13%   |
| 512   | 14        | 1.45%   |
| 32768 | 12        | 1.24%   |
| 256   | 2         | 0.21%   |
| 16    | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 224       | 24.4%   |
| 3200    | 104       | 11.33%  |
| 2667    | 80        | 8.71%   |
| 1333    | 69        | 7.52%   |
| 2400    | 57        | 6.21%   |
| 800     | 47        | 5.12%   |
| Unknown | 45        | 4.9%    |
| 667     | 44        | 4.79%   |
| 1334    | 42        | 4.58%   |
| 2133    | 18        | 1.96%   |
| 4199    | 15        | 1.63%   |
| 3600    | 13        | 1.42%   |
| 1066    | 13        | 1.42%   |
| 533     | 13        | 1.42%   |
| 1067    | 12        | 1.31%   |
| 400     | 12        | 1.31%   |
| 3266    | 10        | 1.09%   |
| 1867    | 10        | 1.09%   |
| 2048    | 9         | 0.98%   |
| 6400    | 7         | 0.76%   |
| 4800    | 7         | 0.76%   |
| 333     | 7         | 0.76%   |
| 3466    | 6         | 0.65%   |
| 1866    | 6         | 0.65%   |
| 4267    | 5         | 0.54%   |
| 3733    | 4         | 0.44%   |
| 4266    | 3         | 0.33%   |
| 3400    | 3         | 0.33%   |
| 49926   | 2         | 0.22%   |
| 8400    | 2         | 0.22%   |
| 3800    | 2         | 0.22%   |
| 2933    | 2         | 0.22%   |
| 2666    | 2         | 0.22%   |
| 1800    | 2         | 0.22%   |
| 1639    | 2         | 0.22%   |
| 266     | 2         | 0.22%   |
| 65535   | 1         | 0.11%   |
| 8533    | 1         | 0.11%   |
| 6000    | 1         | 0.11%   |
| 3866    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 7         | 28%     |
| Hewlett-Packard       | 6         | 24%     |
| Seiko Epson           | 5         | 20%     |
| Samsung Electronics   | 3         | 12%     |
| Ricoh                 | 1         | 4%      |
| QinHeng Electronics   | 1         | 4%      |
| Lexmark International | 1         | 4%      |
| Kyocera               | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6030w/6018w              | 2         | 7.69%   |
| Canon CAPT USB Device             | 2         | 7.69%   |
| Seiko Epson M100 Series           | 1         | 3.85%   |
| Seiko Epson L805 Series           | 1         | 3.85%   |
| Seiko Epson L365 Series           | 1         | 3.85%   |
| Seiko Epson L360 Series           | 1         | 3.85%   |
| Seiko Epson ET-1810 Series        | 1         | 3.85%   |
| Samsung SCX-4300 Series           | 1         | 3.85%   |
| Samsung SCX-4200 series           | 1         | 3.85%   |
| Samsung Laser Printer             | 1         | 3.85%   |
| Ricoh SP 213SUw                   | 1         | 3.85%   |
| QinHeng CH340S                    | 1         | 3.85%   |
| Lexmark International Z35 Printer | 1         | 3.85%   |
| Kyocera FS-1125MFP                | 1         | 3.85%   |
| HP LaserJet P2055 series          | 1         | 3.85%   |
| HP LaserJet P1006                 | 1         | 3.85%   |
| HP LaserJet P1005                 | 1         | 3.85%   |
| HP LaserJet 1300                  | 1         | 3.85%   |
| HP LaserJet 1010                  | 1         | 3.85%   |
| HP DeskJet 840c                   | 1         | 3.85%   |
| Canon MF4410                      | 1         | 3.85%   |
| Canon MF4010 series               | 1         | 3.85%   |
| Canon MF3010                      | 1         | 3.85%   |
| Canon G1000 series                | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 66.67%  |
| Ultima Electronics | 1         | 16.67%  |
| Seiko Epson        | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 16.67%  |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 16.67%  |
| Canon CanoScan LiDE 600F                                                              | 1         | 16.67%  |
| Canon CanoScan LiDE 60                                                                | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                                                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 158       | 21.56%  |
| IMC Networks                           | 104       | 14.19%  |
| Realtek Semiconductor                  | 42        | 5.73%   |
| Quanta                                 | 41        | 5.59%   |
| Logitech                               | 37        | 5.05%   |
| Sunplus Innovation Technology          | 33        | 4.5%    |
| Suyin                                  | 31        | 4.23%   |
| Syntek                                 | 27        | 3.68%   |
| Bison Electronics                      | 27        | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.55%   |
| Microdia                               | 25        | 3.41%   |
| Z-Star Microelectronics                | 24        | 3.27%   |
| Silicon Motion                         | 22        | 3%      |
| Lite-On Technology                     | 22        | 3%      |
| Acer                                   | 22        | 3%      |
| Apple                                  | 11        | 1.5%    |
| Alcor Micro                            | 11        | 1.5%    |
| Luxvisions Innotech Limited            | 9         | 1.23%   |
| Sonix Technology                       | 6         | 0.82%   |
| SunplusIT                              | 4         | 0.55%   |
| Samsung Electronics                    | 4         | 0.55%   |
| Primax Electronics                     | 4         | 0.55%   |
| Microsoft                              | 3         | 0.41%   |
| lihappe8                               | 3         | 0.41%   |
| Lenovo                                 | 3         | 0.41%   |
| Importek                               | 3         | 0.41%   |
| DigiTech                               | 3         | 0.41%   |
| Cubeternet                             | 3         | 0.41%   |
| Aveo Technology                        | 3         | 0.41%   |
| Shine-optics                           | 2         | 0.27%   |
| Ricoh                                  | 2         | 0.27%   |
| Razer USA                              | 2         | 0.27%   |
| Arkmicro Technologies                  | 2         | 0.27%   |
| YGTek                                  | 1         | 0.14%   |
| Y Media                                | 1         | 0.14%   |
| Shinetech                              | 1         | 0.14%   |
| Pixart Imaging                         | 1         | 0.14%   |
| Nokia Mobile Phones                    | 1         | 0.14%   |
| Linux Foundation                       | 1         | 0.14%   |
| KYE Systems (Mouse Systems)            | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam | 31        | 4.22%   |
| IMC Networks USB2.0 HD UVC WebCam  | 20        | 2.72%   |
| Chicony Integrated Camera          | 17        | 2.31%   |
| Logitech Webcam C270               | 16        | 2.18%   |
| IMC Networks Integrated Camera     | 13        | 1.77%   |
| Chicony USB2.0 VGA UVC WebCam      | 13        | 1.77%   |
| Syntek Integrated Camera           | 12        | 1.63%   |
| Realtek Integrated_Webcam_HD       | 12        | 1.63%   |
| Chicony HD WebCam                  | 12        | 1.63%   |
| Sunplus HD WebCam                  | 10        | 1.36%   |
| Chicony Lenovo EasyCamera          | 10        | 1.36%   |
| Acer Lenovo Integrated Webcam      | 10        | 1.36%   |
| IMC Networks USB2.0 UVC HD Webcam  | 8         | 1.09%   |
| Syntek EasyCamera                  | 7         | 0.95%   |
| Quanta HP HD Camera                | 7         | 0.95%   |
| Chicony USB2.0 HD UVC WebCam       | 7         | 0.95%   |
| Chicony HP HD Camera               | 7         | 0.95%   |
| Chicony EasyCamera                 | 7         | 0.95%   |
| Bison Lenovo EasyCamera            | 7         | 0.95%   |
| Syntek Lenovo EasyCamera           | 6         | 0.82%   |
| Sunplus Integrated_Webcam_HD       | 6         | 0.82%   |
| Microdia Integrated_Webcam_HD      | 6         | 0.82%   |
| Logitech Webcam C310               | 6         | 0.82%   |
| Lite-On Integrated Camera          | 6         | 0.82%   |
| IMC Networks UVC VGA Webcam        | 6         | 0.82%   |
| IMC Networks Integrated Webcam     | 6         | 0.82%   |
| Bison Integrated Camera            | 6         | 0.82%   |
| Z-Star A4 TECH USB2.0 PC Camera J  | 5         | 0.68%   |
| Suyin HP TrueVision HD             | 5         | 0.68%   |
| Silicon Motion WebCam SC-0311139N  | 5         | 0.68%   |
| Realtek USB Camera                 | 5         | 0.68%   |
| Quanta HP TrueVision HD Camera     | 5         | 0.68%   |
| Microdia Camera                    | 5         | 0.68%   |
| Lite-On HP HD Camera               | 5         | 0.68%   |
| IMC Networks HD Camera             | 5         | 0.68%   |
| Chicony HP Wide Vision HD Camera   | 5         | 0.68%   |
| Chicony HP TrueVision HD Camera    | 5         | 0.68%   |
| Acer Lenovo EasyCamera             | 5         | 0.68%   |
| Z-Star Venus USB2.0 Camera         | 4         | 0.54%   |
| Suyin HD Video WebCam              | 4         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 23        | 26.44%  |
| Synaptics                          | 17        | 19.54%  |
| Shenzhen Goodix Technology         | 17        | 19.54%  |
| Elan Microelectronics              | 14        | 16.09%  |
| AuthenTec                          | 6         | 6.9%    |
| STMicroelectronics                 | 3         | 3.45%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 3.45%   |
| Upek                               | 2         | 2.3%    |
| LighTuning Technology              | 2         | 2.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 10        | 11.49%  |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 10.34%  |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 8.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.6%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 4.6%    |
| Elan ELAN:ARM-M4                                                           | 4         | 4.6%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.45%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 3.45%   |
| Validity Sensors VFS491                                                    | 2         | 2.3%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.3%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.3%    |
| Synaptics  WBDI                                                            | 2         | 2.3%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.3%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.15%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.15%   |
| Synaptics UWP WBDI                                                         | 1         | 1.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.15%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.15%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.15%   |
| AuthenTec AES2810                                                          | 1         | 1.15%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.15%   |
| AuthenTec AES1600                                                          | 1         | 1.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
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


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 849       | 75.27%  |
| 1     | 229       | 20.3%   |
| 2     | 42        | 3.72%   |
| 3     | 7         | 0.62%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 118       | 37.46%  |
| Fingerprint reader       | 85        | 26.98%  |
| Net/wireless             | 25        | 7.94%   |
| Multimedia controller    | 18        | 5.71%   |
| Bluetooth                | 18        | 5.71%   |
| Communication controller | 14        | 4.44%   |
| Chipcard                 | 14        | 4.44%   |
| Camera                   | 10        | 3.17%   |
| Storage                  | 4         | 1.27%   |
| Sound                    | 3         | 0.95%   |
| Card reader              | 2         | 0.63%   |
| Unassigned class         | 1         | 0.32%   |
| Net/ethernet             | 1         | 0.32%   |
| Modem                    | 1         | 0.32%   |
| Flash memory             | 1         | 0.32%   |

