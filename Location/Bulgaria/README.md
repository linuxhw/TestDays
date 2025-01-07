Linux in Bulgaria - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bulgaria/Desktop/README.md) and [notebooks](/Location/Bulgaria/Notebook/README.md).

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

Total: 2111

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [0baddf7cbe](https://linux-hardware.org/?probe=0baddf7cbe) | Jan 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5e3d055319](https://linux-hardware.org/?probe=5e3d055319) | Jan 05, 2025 |
| Lenovo        | ThinkPad T490 20N3S82N1P    | Notebook    | [b9e31a2832](https://linux-hardware.org/?probe=b9e31a2832) | Jan 05, 2025 |
| Lenovo        | 1030                        | Desktop     | [aab2f96127](https://linux-hardware.org/?probe=aab2f96127) | Jan 03, 2025 |
| ASUSTek       | PTGD2-VX                    | Desktop     | [0f9603dd40](https://linux-hardware.org/?probe=0f9603dd40) | Jan 03, 2025 |
| ASUSTek       | PTGD2-VX                    | Desktop     | [c0ced145df](https://linux-hardware.org/?probe=c0ced145df) | Jan 03, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8a0d66e0ae](https://linux-hardware.org/?probe=8a0d66e0ae) | Jan 02, 2025 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [bf30d86827](https://linux-hardware.org/?probe=bf30d86827) | Jan 01, 2025 |
| Acer          | Aspire A315-44P             | Notebook    | [52b26cac3f](https://linux-hardware.org/?probe=52b26cac3f) | Dec 31, 2024 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [fe49d94f48](https://linux-hardware.org/?probe=fe49d94f48) | Dec 30, 2024 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [0f84cbbee8](https://linux-hardware.org/?probe=0f84cbbee8) | Dec 30, 2024 |
| Lenovo        | Unknown                     | Notebook    | [89b1437fa2](https://linux-hardware.org/?probe=89b1437fa2) | Dec 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [a135b01a74](https://linux-hardware.org/?probe=a135b01a74) | Dec 29, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [e36139662d](https://linux-hardware.org/?probe=e36139662d) | Dec 28, 2024 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0afcb0e788](https://linux-hardware.org/?probe=0afcb0e788) | Dec 28, 2024 |
| HP            | 805D                        | Desktop     | [e9bc2a5d7f](https://linux-hardware.org/?probe=e9bc2a5d7f) | Dec 28, 2024 |
| HP            | 805D                        | Desktop     | [a29891007f](https://linux-hardware.org/?probe=a29891007f) | Dec 28, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [2163561381](https://linux-hardware.org/?probe=2163561381) | Dec 27, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [d9ccd55fd5](https://linux-hardware.org/?probe=d9ccd55fd5) | Dec 26, 2024 |
| Lenovo        | YB1-X91F                    | Convertible | [4e217ea914](https://linux-hardware.org/?probe=4e217ea914) | Dec 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d48fae0d86](https://linux-hardware.org/?probe=d48fae0d86) | Dec 26, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [06e2ee69ef](https://linux-hardware.org/?probe=06e2ee69ef) | Dec 26, 2024 |
| HP            | 1998                        | Desktop     | [cdf0f59ddb](https://linux-hardware.org/?probe=cdf0f59ddb) | Dec 24, 2024 |
| Toshiba       | NB100                       | Notebook    | [1041e6c170](https://linux-hardware.org/?probe=1041e6c170) | Dec 24, 2024 |
| TongFang      | GX5HRXL                     | Notebook    | [c16d33a7aa](https://linux-hardware.org/?probe=c16d33a7aa) | Dec 23, 2024 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [c0a219ed53](https://linux-hardware.org/?probe=c0a219ed53) | Dec 22, 2024 |
| TongFang      | GX5HRXL                     | Notebook    | [27406f56fd](https://linux-hardware.org/?probe=27406f56fd) | Dec 18, 2024 |
| ASUSTek       | X555LF                      | Notebook    | [7c3dbd59b5](https://linux-hardware.org/?probe=7c3dbd59b5) | Dec 17, 2024 |
| Acer          | Aspire A315-23              | Notebook    | [e51fcf8215](https://linux-hardware.org/?probe=e51fcf8215) | Dec 16, 2024 |
| Dell          | Latitude 7340               | Notebook    | [01bf0e0d2c](https://linux-hardware.org/?probe=01bf0e0d2c) | Dec 16, 2024 |
| Fujitsu       | LIFEBOOK N532               | Notebook    | [6cb47f13c6](https://linux-hardware.org/?probe=6cb47f13c6) | Dec 15, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [f66ce0b3ee](https://linux-hardware.org/?probe=f66ce0b3ee) | Dec 14, 2024 |
| Toshiba       | NB100                       | Notebook    | [976e6530d5](https://linux-hardware.org/?probe=976e6530d5) | Dec 14, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [2219eae21d](https://linux-hardware.org/?probe=2219eae21d) | Dec 14, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [e51c407f40](https://linux-hardware.org/?probe=e51c407f40) | Dec 14, 2024 |
| Unknown       | Alviso                      | Desktop     | [b5254b9523](https://linux-hardware.org/?probe=b5254b9523) | Dec 13, 2024 |
| MSI           | B560-A PRO                  | Desktop     | [521113e45e](https://linux-hardware.org/?probe=521113e45e) | Dec 12, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [b819493263](https://linux-hardware.org/?probe=b819493263) | Dec 12, 2024 |
| HP            | 3032h                       | Desktop     | [ca96a21d5f](https://linux-hardware.org/?probe=ca96a21d5f) | Dec 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [5d948ce651](https://linux-hardware.org/?probe=5d948ce651) | Dec 08, 2024 |
| Panasonic     | CF-52PFP54QL                | Notebook    | [bcafd21454](https://linux-hardware.org/?probe=bcafd21454) | Dec 06, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [2d71a66a13](https://linux-hardware.org/?probe=2d71a66a13) | Dec 05, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [133b87bc4b](https://linux-hardware.org/?probe=133b87bc4b) | Dec 03, 2024 |
| Sony          | VPCEH25FD                   | Notebook    | [a5e2ac76fc](https://linux-hardware.org/?probe=a5e2ac76fc) | Dec 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [5b5b439904](https://linux-hardware.org/?probe=5b5b439904) | Nov 29, 2024 |
| Acer          | Aspire A315-34              | Notebook    | [16257c3b4b](https://linux-hardware.org/?probe=16257c3b4b) | Nov 27, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7abfcb89dd](https://linux-hardware.org/?probe=7abfcb89dd) | Nov 27, 2024 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [e735cedc40](https://linux-hardware.org/?probe=e735cedc40) | Nov 27, 2024 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [9c96eb4177](https://linux-hardware.org/?probe=9c96eb4177) | Nov 27, 2024 |
| Gigabyte      | H610M S2H                   | Desktop     | [dfa73747fa](https://linux-hardware.org/?probe=dfa73747fa) | Nov 22, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdad4ccabe](https://linux-hardware.org/?probe=bdad4ccabe) | Nov 22, 2024 |
| ASRock        | A520M-HVS                   | Desktop     | [573bea0296](https://linux-hardware.org/?probe=573bea0296) | Nov 21, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | Notebook    | [2711562e60](https://linux-hardware.org/?probe=2711562e60) | Nov 19, 2024 |
| Dell          | Precision 7710              | Notebook    | [f328fe1be2](https://linux-hardware.org/?probe=f328fe1be2) | Nov 18, 2024 |
| Dell          | Precision 7710              | Notebook    | [658f311eb3](https://linux-hardware.org/?probe=658f311eb3) | Nov 18, 2024 |
| Lenovo        | ThinkPad T530 2429AE1       | Notebook    | [3effeec5aa](https://linux-hardware.org/?probe=3effeec5aa) | Nov 17, 2024 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [25010cdc93](https://linux-hardware.org/?probe=25010cdc93) | Nov 16, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [afe93e20da](https://linux-hardware.org/?probe=afe93e20da) | Nov 16, 2024 |
| HP            | 15                          | Notebook    | [79f04083ac](https://linux-hardware.org/?probe=79f04083ac) | Nov 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c71e9a6fb2](https://linux-hardware.org/?probe=c71e9a6fb2) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5ddb463c28](https://linux-hardware.org/?probe=5ddb463c28) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b50cd6c13b](https://linux-hardware.org/?probe=b50cd6c13b) | Nov 12, 2024 |
| HP            | 1497                        | Desktop     | [b4fe73ae99](https://linux-hardware.org/?probe=b4fe73ae99) | Nov 09, 2024 |
| Lenovo        | ThinkPad T550 20CK0004GE    | Notebook    | [e7943e539d](https://linux-hardware.org/?probe=e7943e539d) | Nov 05, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [3a27360883](https://linux-hardware.org/?probe=3a27360883) | Nov 04, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ff66755d2c](https://linux-hardware.org/?probe=ff66755d2c) | Nov 04, 2024 |
| HP            | 3031h                       | Desktop     | [0a5295eeab](https://linux-hardware.org/?probe=0a5295eeab) | Nov 02, 2024 |
| Packard Be... | ONETWO M3700                | All in one  | [cf417581c6](https://linux-hardware.org/?probe=cf417581c6) | Oct 29, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | Notebook    | [3d56cceb9e](https://linux-hardware.org/?probe=3d56cceb9e) | Oct 28, 2024 |
| ASRock        | X370 Gaming K4              | Desktop     | [82b1f66adf](https://linux-hardware.org/?probe=82b1f66adf) | Oct 27, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d0905f7bb9](https://linux-hardware.org/?probe=d0905f7bb9) | Oct 26, 2024 |
| ASUSTek       | G551JM                      | Notebook    | [d6d0bfa34e](https://linux-hardware.org/?probe=d6d0bfa34e) | Oct 26, 2024 |
| ASUSTek       | G551JM                      | Notebook    | [c411632c1c](https://linux-hardware.org/?probe=c411632c1c) | Oct 26, 2024 |
| Apple         | MacBookPro16,1              | Notebook    | [fc397bc6c0](https://linux-hardware.org/?probe=fc397bc6c0) | Oct 26, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [1eb6d26665](https://linux-hardware.org/?probe=1eb6d26665) | Oct 25, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [fcfd360705](https://linux-hardware.org/?probe=fcfd360705) | Oct 24, 2024 |
| Acer          | Aspire A15-41M              | Notebook    | [b5a44016cd](https://linux-hardware.org/?probe=b5a44016cd) | Oct 23, 2024 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [f6d5295c3b](https://linux-hardware.org/?probe=f6d5295c3b) | Oct 21, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [38add3c407](https://linux-hardware.org/?probe=38add3c407) | Oct 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [1d18778ca6](https://linux-hardware.org/?probe=1d18778ca6) | Oct 15, 2024 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [c2aa718daa](https://linux-hardware.org/?probe=c2aa718daa) | Oct 15, 2024 |
| HP            | Pavilion dv8                | Notebook    | [21df937346](https://linux-hardware.org/?probe=21df937346) | Oct 14, 2024 |
| Dell          | Precision 5510              | Notebook    | [8b7f1841e7](https://linux-hardware.org/?probe=8b7f1841e7) | Oct 14, 2024 |
| Dell          | Precision 5510              | Notebook    | [0182ff27ab](https://linux-hardware.org/?probe=0182ff27ab) | Oct 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | Notebook    | [fe8096e733](https://linux-hardware.org/?probe=fe8096e733) | Oct 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [e9c7cab546](https://linux-hardware.org/?probe=e9c7cab546) | Oct 10, 2024 |
| ASRock        | Z68 Pro3                    | Desktop     | [1c593e0248](https://linux-hardware.org/?probe=1c593e0248) | Oct 09, 2024 |
| Dell          | Latitude E6540              | Notebook    | [c6635fa1dd](https://linux-hardware.org/?probe=c6635fa1dd) | Oct 08, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [17a82a3c73](https://linux-hardware.org/?probe=17a82a3c73) | Oct 08, 2024 |
| Dell          | G15 5511                    | Notebook    | [ed9b86e723](https://linux-hardware.org/?probe=ed9b86e723) | Oct 08, 2024 |
| Gigabyte      | B650M AORUS ELITE AX ICE    | Desktop     | [be22a62090](https://linux-hardware.org/?probe=be22a62090) | Oct 08, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [eb6a4540f2](https://linux-hardware.org/?probe=eb6a4540f2) | Oct 08, 2024 |
| ASRock        | H410M-HDV                   | Desktop     | [01a1e8594c](https://linux-hardware.org/?probe=01a1e8594c) | Oct 04, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [992bb7d24d](https://linux-hardware.org/?probe=992bb7d24d) | Oct 02, 2024 |
| ASRock        | H410M-HDV                   | Desktop     | [e8a196d76d](https://linux-hardware.org/?probe=e8a196d76d) | Oct 01, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [fc1ea5dd8c](https://linux-hardware.org/?probe=fc1ea5dd8c) | Sep 28, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [707360a70f](https://linux-hardware.org/?probe=707360a70f) | Sep 28, 2024 |
| AZW           | EQ                          | Desktop     | [26551abec1](https://linux-hardware.org/?probe=26551abec1) | Sep 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [a312838803](https://linux-hardware.org/?probe=a312838803) | Sep 24, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [db77b134d1](https://linux-hardware.org/?probe=db77b134d1) | Sep 24, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8d42414125](https://linux-hardware.org/?probe=8d42414125) | Sep 22, 2024 |
| ASUSTek       | X555LJ                      | Notebook    | [9dc481d73a](https://linux-hardware.org/?probe=9dc481d73a) | Sep 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e647d35e74](https://linux-hardware.org/?probe=e647d35e74) | Sep 20, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f7e510c730](https://linux-hardware.org/?probe=f7e510c730) | Sep 19, 2024 |
| Lenovo        | ThinkPad W530 2463A52       | Notebook    | [68f2429248](https://linux-hardware.org/?probe=68f2429248) | Sep 19, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [0bc35e551d](https://linux-hardware.org/?probe=0bc35e551d) | Sep 18, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [d24251c7a0](https://linux-hardware.org/?probe=d24251c7a0) | Sep 18, 2024 |
| Lenovo        | ThinkPad W530 2463A52       | Notebook    | [c0860a78cd](https://linux-hardware.org/?probe=c0860a78cd) | Sep 18, 2024 |
| HP            | ProLiant DL360p Gen8        | Server      | [6fef77f9b0](https://linux-hardware.org/?probe=6fef77f9b0) | Sep 18, 2024 |
| ASRock        | A520M-HVS                   | Desktop     | [dd1f6c0337](https://linux-hardware.org/?probe=dd1f6c0337) | Sep 17, 2024 |
| HP            | Pavilion 17                 | Notebook    | [fb7884d776](https://linux-hardware.org/?probe=fb7884d776) | Sep 16, 2024 |
| Sony          | VPCEH2E0E                   | Notebook    | [0db705664d](https://linux-hardware.org/?probe=0db705664d) | Sep 14, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [bea14db033](https://linux-hardware.org/?probe=bea14db033) | Sep 11, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [7f98effccd](https://linux-hardware.org/?probe=7f98effccd) | Sep 06, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [121ee8244a](https://linux-hardware.org/?probe=121ee8244a) | Sep 05, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [453cbe339f](https://linux-hardware.org/?probe=453cbe339f) | Sep 05, 2024 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [d8b60dcb98](https://linux-hardware.org/?probe=d8b60dcb98) | Sep 02, 2024 |
| Dell          | Latitude 5510               | Notebook    | [634228ff35](https://linux-hardware.org/?probe=634228ff35) | Sep 02, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c74b9009e8](https://linux-hardware.org/?probe=c74b9009e8) | Aug 31, 2024 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [151da93887](https://linux-hardware.org/?probe=151da93887) | Aug 31, 2024 |
| Dell          | Vostro 5481                 | Notebook    | [04820e5465](https://linux-hardware.org/?probe=04820e5465) | Aug 30, 2024 |
| Dell          | Latitude E7270              | Notebook    | [7b008f6780](https://linux-hardware.org/?probe=7b008f6780) | Aug 30, 2024 |
| HP            | Pavilion dv8                | Notebook    | [33c6d5838c](https://linux-hardware.org/?probe=33c6d5838c) | Aug 30, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [e9c6b514ef](https://linux-hardware.org/?probe=e9c6b514ef) | Aug 30, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2510b833ba](https://linux-hardware.org/?probe=2510b833ba) | Aug 27, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [fcb0a29b79](https://linux-hardware.org/?probe=fcb0a29b79) | Aug 27, 2024 |
| Dell          | G15 5530                    | Notebook    | [601308044e](https://linux-hardware.org/?probe=601308044e) | Aug 26, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [8a6c458a6b](https://linux-hardware.org/?probe=8a6c458a6b) | Aug 25, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [f3eedcecc1](https://linux-hardware.org/?probe=f3eedcecc1) | Aug 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [75931341d7](https://linux-hardware.org/?probe=75931341d7) | Aug 25, 2024 |
| Gigabyte      | G5 KF                       | Notebook    | [0e5c227ff1](https://linux-hardware.org/?probe=0e5c227ff1) | Aug 23, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a223c3c2be](https://linux-hardware.org/?probe=a223c3c2be) | Aug 23, 2024 |
| HP            | 158A                        | Desktop     | [ef7238898f](https://linux-hardware.org/?probe=ef7238898f) | Aug 20, 2024 |
| Dell          | Vostro 5481                 | Notebook    | [c76a7034cd](https://linux-hardware.org/?probe=c76a7034cd) | Aug 16, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [e259b80ab9](https://linux-hardware.org/?probe=e259b80ab9) | Aug 14, 2024 |
| MSI           | A320M GRENADE               | Desktop     | [7f2dfe2cff](https://linux-hardware.org/?probe=7f2dfe2cff) | Aug 12, 2024 |
| Lenovo        | ThinkPad T560 20FJS3X800    | Notebook    | [6a14a30f0c](https://linux-hardware.org/?probe=6a14a30f0c) | Aug 11, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [2ed3a493b2](https://linux-hardware.org/?probe=2ed3a493b2) | Aug 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [458556ade2](https://linux-hardware.org/?probe=458556ade2) | Aug 08, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d415774845](https://linux-hardware.org/?probe=d415774845) | Aug 07, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [f21bd1a58e](https://linux-hardware.org/?probe=f21bd1a58e) | Aug 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [feaff16732](https://linux-hardware.org/?probe=feaff16732) | Aug 05, 2024 |
| Lenovo        | Unknown                     | Notebook    | [60da7baec5](https://linux-hardware.org/?probe=60da7baec5) | Aug 05, 2024 |
| Fujitsu       | FARQ04001                   | Notebook    | [6196b6b339](https://linux-hardware.org/?probe=6196b6b339) | Aug 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [185cee5333](https://linux-hardware.org/?probe=185cee5333) | Aug 04, 2024 |
| MSI           | B560-A PRO                  | Desktop     | [f8bcd51ea3](https://linux-hardware.org/?probe=f8bcd51ea3) | Aug 03, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0a09eb534e](https://linux-hardware.org/?probe=0a09eb534e) | Aug 02, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [11bb0131b5](https://linux-hardware.org/?probe=11bb0131b5) | Aug 02, 2024 |
| Dell          | Vostro 1700                 | Notebook    | [c3520cb3d6](https://linux-hardware.org/?probe=c3520cb3d6) | Aug 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [846f130e8f](https://linux-hardware.org/?probe=846f130e8f) | Jul 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [99bd685bab](https://linux-hardware.org/?probe=99bd685bab) | Jul 30, 2024 |
| Unknown       | Unknown                     | Notebook    | [e667d93a6d](https://linux-hardware.org/?probe=e667d93a6d) | Jul 30, 2024 |
| Lenovo        | ThinkPad T480s 20L8002XM... | Notebook    | [5a1984e44d](https://linux-hardware.org/?probe=5a1984e44d) | Jul 30, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ab8522ee8f](https://linux-hardware.org/?probe=ab8522ee8f) | Jul 29, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [b2bc501e8d](https://linux-hardware.org/?probe=b2bc501e8d) | Jul 29, 2024 |
| Dell          | 06D7TR A00                  | Desktop     | [0120c5ec0f](https://linux-hardware.org/?probe=0120c5ec0f) | Jul 29, 2024 |
| HP            | EliteBook 745 G6            | Notebook    | [d4583a12a6](https://linux-hardware.org/?probe=d4583a12a6) | Jul 27, 2024 |
| Gigabyte      | MJ11-EC1-OT 01000100        | Server      | [182255b026](https://linux-hardware.org/?probe=182255b026) | Jul 27, 2024 |
| Lenovo        | 32E4 SDK0T76530 WIN 3556... | Mini pc     | [043508351f](https://linux-hardware.org/?probe=043508351f) | Jul 27, 2024 |
| Lenovo        | 312D NOK                    | Mini pc     | [9747aea3fa](https://linux-hardware.org/?probe=9747aea3fa) | Jul 27, 2024 |
| Lenovo        | 312D NOK                    | Mini pc     | [c704de3038](https://linux-hardware.org/?probe=c704de3038) | Jul 27, 2024 |
| Lenovo        | 312D NOK                    | Mini pc     | [3e02272166](https://linux-hardware.org/?probe=3e02272166) | Jul 27, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [a818073a3d](https://linux-hardware.org/?probe=a818073a3d) | Jul 27, 2024 |
| MSI           | Katana 15 B13VEK            | Notebook    | [c8c421d5c3](https://linux-hardware.org/?probe=c8c421d5c3) | Jul 26, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [9e97e029b6](https://linux-hardware.org/?probe=9e97e029b6) | Jul 26, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [48d8629eb0](https://linux-hardware.org/?probe=48d8629eb0) | Jul 22, 2024 |
| Alienware     | Area-51m R2 A00             | Notebook    | [b81380e2f7](https://linux-hardware.org/?probe=b81380e2f7) | Jul 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP34... | Convertible | [e963e945a3](https://linux-hardware.org/?probe=e963e945a3) | Jul 17, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [60b1f0475f](https://linux-hardware.org/?probe=60b1f0475f) | Jul 17, 2024 |
| ASRock        | B660M Pro RS                | Desktop     | [04faa5c724](https://linux-hardware.org/?probe=04faa5c724) | Jul 16, 2024 |
| Gigabyte      | X58A-UD7                    | Desktop     | [6ba0085048](https://linux-hardware.org/?probe=6ba0085048) | Jul 15, 2024 |
| HP            | 15                          | Notebook    | [382f3aa7d4](https://linux-hardware.org/?probe=382f3aa7d4) | Jul 15, 2024 |
| HP            | 815A                        | Mini pc     | [98c09abe53](https://linux-hardware.org/?probe=98c09abe53) | Jul 13, 2024 |
| HP            | 815A                        | Mini pc     | [0957a011e8](https://linux-hardware.org/?probe=0957a011e8) | Jul 12, 2024 |
| HP            | 815A                        | Mini pc     | [20bf216b88](https://linux-hardware.org/?probe=20bf216b88) | Jul 11, 2024 |
| HP            | Compaq 6720s                | Notebook    | [7eeec5b052](https://linux-hardware.org/?probe=7eeec5b052) | Jul 09, 2024 |
| HP            | Compaq 6720s                | Notebook    | [df5b153030](https://linux-hardware.org/?probe=df5b153030) | Jul 09, 2024 |
| Gigabyte      | X58A-UD7                    | Desktop     | [c5471b61ce](https://linux-hardware.org/?probe=c5471b61ce) | Jul 08, 2024 |
| Dell          | Inspiron 1564               | Notebook    | [3c5c95d839](https://linux-hardware.org/?probe=3c5c95d839) | Jul 07, 2024 |
| Acer          | Aspire 5251                 | Notebook    | [ee4236aa4b](https://linux-hardware.org/?probe=ee4236aa4b) | Jul 05, 2024 |
| Acer          | Aspire 5251                 | Notebook    | [738fcb5042](https://linux-hardware.org/?probe=738fcb5042) | Jul 04, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [455d216193](https://linux-hardware.org/?probe=455d216193) | Jul 02, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [d3426ed926](https://linux-hardware.org/?probe=d3426ed926) | Jul 02, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [62c4cfff56](https://linux-hardware.org/?probe=62c4cfff56) | Jul 01, 2024 |
| ASUSTek       | T100TAF                     | Notebook    | [05c827f54c](https://linux-hardware.org/?probe=05c827f54c) | Jun 29, 2024 |
| Lenovo        | ThinkPad P53 20QN000DGE     | Notebook    | [7f25d623fe](https://linux-hardware.org/?probe=7f25d623fe) | Jun 28, 2024 |
| ASUSTek       | X510UQR                     | Notebook    | [c4b1e2a969](https://linux-hardware.org/?probe=c4b1e2a969) | Jun 27, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [0d84f70d08](https://linux-hardware.org/?probe=0d84f70d08) | Jun 25, 2024 |
| Acer          | Predator PH317-53           | Notebook    | [d93de492ee](https://linux-hardware.org/?probe=d93de492ee) | Jun 25, 2024 |
| Acer          | Predator PH317-53           | Notebook    | [d2b4fa437b](https://linux-hardware.org/?probe=d2b4fa437b) | Jun 25, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [c31756829b](https://linux-hardware.org/?probe=c31756829b) | Jun 25, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [7945e52c36](https://linux-hardware.org/?probe=7945e52c36) | Jun 22, 2024 |
| Lenovo        | ThinkPad X390 20Q00055MX    | Notebook    | [edfa886a82](https://linux-hardware.org/?probe=edfa886a82) | Jun 20, 2024 |
| HP            | 18E4                        | Desktop     | [aa89247575](https://linux-hardware.org/?probe=aa89247575) | Jun 16, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [54e7691c73](https://linux-hardware.org/?probe=54e7691c73) | Jun 15, 2024 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [faeb824333](https://linux-hardware.org/?probe=faeb824333) | Jun 13, 2024 |
| ECS           | A780GM-A                    | Desktop     | [577391284a](https://linux-hardware.org/?probe=577391284a) | Jun 12, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [8462e256b8](https://linux-hardware.org/?probe=8462e256b8) | Jun 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [a8b17e7809](https://linux-hardware.org/?probe=a8b17e7809) | Jun 07, 2024 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | Notebook    | [144cbd14af](https://linux-hardware.org/?probe=144cbd14af) | Jun 07, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [dd9e579cf3](https://linux-hardware.org/?probe=dd9e579cf3) | Jun 06, 2024 |
| Supermicro    | C7Z170-M                    | Server      | [3af6d15be8](https://linux-hardware.org/?probe=3af6d15be8) | Jun 06, 2024 |
| Supermicro    | C7Z170-M                    | Server      | [987e2fb8ba](https://linux-hardware.org/?probe=987e2fb8ba) | Jun 06, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2be17ac82e](https://linux-hardware.org/?probe=2be17ac82e) | Jun 04, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | Notebook    | [6ccb04db71](https://linux-hardware.org/?probe=6ccb04db71) | Jun 03, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [0019cc311b](https://linux-hardware.org/?probe=0019cc311b) | Jun 02, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d7532d3f5c](https://linux-hardware.org/?probe=d7532d3f5c) | Jun 02, 2024 |
| HP            | EliteBook 1050 G1           | Notebook    | [25ad5b6cb8](https://linux-hardware.org/?probe=25ad5b6cb8) | May 30, 2024 |
| HP            | G62                         | Notebook    | [122c14c90c](https://linux-hardware.org/?probe=122c14c90c) | May 28, 2024 |
| Gigabyte      | X58A-UD7                    | Desktop     | [574d338fe6](https://linux-hardware.org/?probe=574d338fe6) | May 28, 2024 |
| Gigabyte      | X58A-UD7                    | Desktop     | [beb2ab8657](https://linux-hardware.org/?probe=beb2ab8657) | May 28, 2024 |
| Lenovo        | ThinkPad X270 20HMS7LM00    | Notebook    | [2d489a62b7](https://linux-hardware.org/?probe=2d489a62b7) | May 26, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [c4026575a0](https://linux-hardware.org/?probe=c4026575a0) | May 25, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d945b21cae](https://linux-hardware.org/?probe=d945b21cae) | May 25, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4c11d783c7](https://linux-hardware.org/?probe=4c11d783c7) | May 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [db5d8ff53d](https://linux-hardware.org/?probe=db5d8ff53d) | May 22, 2024 |
| HP            | Pavilion 15                 | Notebook    | [d266ada5a0](https://linux-hardware.org/?probe=d266ada5a0) | May 21, 2024 |
| MSI           | MS-B0A81                    | Desktop     | [3b16ea46f0](https://linux-hardware.org/?probe=3b16ea46f0) | May 20, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [9002cd7940](https://linux-hardware.org/?probe=9002cd7940) | May 19, 2024 |
| HP            | 650                         | Notebook    | [4e91cb9494](https://linux-hardware.org/?probe=4e91cb9494) | May 19, 2024 |
| HP            | Pavilion dv8                | Notebook    | [e9722285d5](https://linux-hardware.org/?probe=e9722285d5) | May 16, 2024 |
| Lenovo        | ThinkPad X390 20Q00055MX    | Notebook    | [4501efe852](https://linux-hardware.org/?probe=4501efe852) | May 15, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [7da82d13a9](https://linux-hardware.org/?probe=7da82d13a9) | May 14, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [346e57e708](https://linux-hardware.org/?probe=346e57e708) | May 14, 2024 |
| Dell          | 06D7TR A00                  | Desktop     | [92c8cc8db0](https://linux-hardware.org/?probe=92c8cc8db0) | May 13, 2024 |
| HP            | Pavilion dv8                | Notebook    | [a44fe4349b](https://linux-hardware.org/?probe=a44fe4349b) | May 13, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2a7caccf14](https://linux-hardware.org/?probe=2a7caccf14) | May 09, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0cd34decca](https://linux-hardware.org/?probe=0cd34decca) | May 08, 2024 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [0c39b2e745](https://linux-hardware.org/?probe=0c39b2e745) | May 05, 2024 |
| Dell          | Inspiron 11-3162            | Notebook    | [ccf99ca586](https://linux-hardware.org/?probe=ccf99ca586) | May 05, 2024 |
| Lenovo        | ThinkPad X270 20HMS34L00    | Notebook    | [dcc424b27d](https://linux-hardware.org/?probe=dcc424b27d) | May 04, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [a698a1991c](https://linux-hardware.org/?probe=a698a1991c) | May 03, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c03d3e0508](https://linux-hardware.org/?probe=c03d3e0508) | May 03, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e52fd6543b](https://linux-hardware.org/?probe=e52fd6543b) | May 03, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [58453faaf6](https://linux-hardware.org/?probe=58453faaf6) | May 03, 2024 |
| Toshiba       | Satellite P200              | Notebook    | [f9f88ee996](https://linux-hardware.org/?probe=f9f88ee996) | May 03, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [3b1c4174da](https://linux-hardware.org/?probe=3b1c4174da) | May 02, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f3681e3ab6](https://linux-hardware.org/?probe=f3681e3ab6) | May 02, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [135b6c8c4e](https://linux-hardware.org/?probe=135b6c8c4e) | Apr 30, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [e9acc27fce](https://linux-hardware.org/?probe=e9acc27fce) | Apr 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [01432a3384](https://linux-hardware.org/?probe=01432a3384) | Apr 23, 2024 |
| Allview       | Allbook J                   | Notebook    | [77d90c2a69](https://linux-hardware.org/?probe=77d90c2a69) | Apr 23, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [b0d7f30c2c](https://linux-hardware.org/?probe=b0d7f30c2c) | Apr 23, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [a04aab72d2](https://linux-hardware.org/?probe=a04aab72d2) | Apr 23, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [aa9d8113e9](https://linux-hardware.org/?probe=aa9d8113e9) | Apr 23, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [aa0595d186](https://linux-hardware.org/?probe=aa0595d186) | Apr 22, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [34d0d4f469](https://linux-hardware.org/?probe=34d0d4f469) | Apr 22, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [e0c405894c](https://linux-hardware.org/?probe=e0c405894c) | Apr 21, 2024 |
| ASUSTek       | P5K Premium                 | Desktop     | [5ff3e52237](https://linux-hardware.org/?probe=5ff3e52237) | Apr 21, 2024 |
| Toshiba       | Satellite C850-124          | Notebook    | [b580358635](https://linux-hardware.org/?probe=b580358635) | Apr 20, 2024 |
| Unknown       | Unknown                     | Notebook    | [7ee99946ca](https://linux-hardware.org/?probe=7ee99946ca) | Apr 19, 2024 |
| Acer          | Aspire 7738                 | Notebook    | [dc56784ca7](https://linux-hardware.org/?probe=dc56784ca7) | Apr 19, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [a5d4162d2f](https://linux-hardware.org/?probe=a5d4162d2f) | Apr 19, 2024 |
| Allview       | Allbook J                   | Notebook    | [a106195c34](https://linux-hardware.org/?probe=a106195c34) | Apr 18, 2024 |
| HP            | 1998                        | Desktop     | [d16f45d089](https://linux-hardware.org/?probe=d16f45d089) | Apr 18, 2024 |
| Pegatron      | 2AC3                        | Desktop     | [db5312ea90](https://linux-hardware.org/?probe=db5312ea90) | Apr 18, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [1642fe3a09](https://linux-hardware.org/?probe=1642fe3a09) | Apr 14, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [2d02eae5ec](https://linux-hardware.org/?probe=2d02eae5ec) | Apr 13, 2024 |
| Lenovo        | ThinkPad T440 20B7A0MN04    | Notebook    | [2244374672](https://linux-hardware.org/?probe=2244374672) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [2304feb790](https://linux-hardware.org/?probe=2304feb790) | Apr 13, 2024 |
| ASRock        | G31M-S                      | Desktop     | [d9694d3f33](https://linux-hardware.org/?probe=d9694d3f33) | Apr 12, 2024 |
| HP            | Pavilion dv8                | Notebook    | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| HP            | 1998                        | Desktop     | [4e592f29d7](https://linux-hardware.org/?probe=4e592f29d7) | Apr 11, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e5830d8754](https://linux-hardware.org/?probe=e5830d8754) | Apr 07, 2024 |
| Acer          | Predator PH315-53           | Notebook    | [4c8bbd0426](https://linux-hardware.org/?probe=4c8bbd0426) | Apr 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [18961ee7a8](https://linux-hardware.org/?probe=18961ee7a8) | Apr 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [d74a81067e](https://linux-hardware.org/?probe=d74a81067e) | Apr 07, 2024 |
| HP            | 1905                        | Desktop     | [d55405d144](https://linux-hardware.org/?probe=d55405d144) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e121ce9511](https://linux-hardware.org/?probe=e121ce9511) | Apr 06, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6496d4176b](https://linux-hardware.org/?probe=6496d4176b) | Apr 05, 2024 |
| Acer          | Aspire V5-572G              | Notebook    | [ca5e1f767e](https://linux-hardware.org/?probe=ca5e1f767e) | Apr 04, 2024 |
| ASUSTek       | X55VD                       | Notebook    | [bc22ba01de](https://linux-hardware.org/?probe=bc22ba01de) | Apr 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [708291ee28](https://linux-hardware.org/?probe=708291ee28) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [449d0ad45b](https://linux-hardware.org/?probe=449d0ad45b) | Mar 31, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [431002bc2d](https://linux-hardware.org/?probe=431002bc2d) | Mar 30, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [3d2abf7e0d](https://linux-hardware.org/?probe=3d2abf7e0d) | Mar 30, 2024 |
| Dell          | Latitude 5580               | Notebook    | [db427c180d](https://linux-hardware.org/?probe=db427c180d) | Mar 28, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [deae5b6cdf](https://linux-hardware.org/?probe=deae5b6cdf) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [602d79d663](https://linux-hardware.org/?probe=602d79d663) | Mar 27, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [bfe7fd8a2e](https://linux-hardware.org/?probe=bfe7fd8a2e) | Mar 26, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [806d659258](https://linux-hardware.org/?probe=806d659258) | Mar 26, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [99983f8fbf](https://linux-hardware.org/?probe=99983f8fbf) | Mar 25, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d402ccab08](https://linux-hardware.org/?probe=d402ccab08) | Mar 23, 2024 |
| Dell          | 06D7TR A00                  | Desktop     | [3c6718eb19](https://linux-hardware.org/?probe=3c6718eb19) | Mar 23, 2024 |
| Dell          | Precision M4700             | Notebook    | [212d29f26d](https://linux-hardware.org/?probe=212d29f26d) | Mar 21, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [f8fa83eaf5](https://linux-hardware.org/?probe=f8fa83eaf5) | Mar 20, 2024 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [80d82ca19d](https://linux-hardware.org/?probe=80d82ca19d) | Mar 19, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [e85fec8591](https://linux-hardware.org/?probe=e85fec8591) | Mar 18, 2024 |
| Acer          | Predator PT516-52s          | Notebook    | [86614957f2](https://linux-hardware.org/?probe=86614957f2) | Mar 17, 2024 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [9bde6bc531](https://linux-hardware.org/?probe=9bde6bc531) | Mar 17, 2024 |
| ASUSTek       | X55VD                       | Notebook    | [a959f1dfec](https://linux-hardware.org/?probe=a959f1dfec) | Mar 17, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3ec06d0273](https://linux-hardware.org/?probe=3ec06d0273) | Mar 16, 2024 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [311809b062](https://linux-hardware.org/?probe=311809b062) | Mar 16, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [75bc4f3af5](https://linux-hardware.org/?probe=75bc4f3af5) | Mar 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [fbc1335ccc](https://linux-hardware.org/?probe=fbc1335ccc) | Mar 12, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [edf84e43ee](https://linux-hardware.org/?probe=edf84e43ee) | Mar 11, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ca3f8b06ab](https://linux-hardware.org/?probe=ca3f8b06ab) | Mar 10, 2024 |
| Allview       | Allbook J                   | Notebook    | [58b6452c8f](https://linux-hardware.org/?probe=58b6452c8f) | Mar 08, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [f7f7bcc5ec](https://linux-hardware.org/?probe=f7f7bcc5ec) | Mar 07, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [1719342e74](https://linux-hardware.org/?probe=1719342e74) | Mar 07, 2024 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [d261ab3479](https://linux-hardware.org/?probe=d261ab3479) | Mar 06, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [898154cbf9](https://linux-hardware.org/?probe=898154cbf9) | Mar 05, 2024 |
| HP            | ZBook Studio G5             | Notebook    | [208ce1e5fd](https://linux-hardware.org/?probe=208ce1e5fd) | Mar 04, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b957a4b5d8](https://linux-hardware.org/?probe=b957a4b5d8) | Mar 03, 2024 |
| Allview       | Allbook J                   | Notebook    | [dd1b4469c1](https://linux-hardware.org/?probe=dd1b4469c1) | Mar 01, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | Notebook    | [935b64ed30](https://linux-hardware.org/?probe=935b64ed30) | Feb 29, 2024 |
| MSI           | Thin GF63 12UDX             | Notebook    | [648c7d0aa4](https://linux-hardware.org/?probe=648c7d0aa4) | Feb 28, 2024 |
| Lenovo        | YB1-X91F                    | Convertible | [dcb774f0e8](https://linux-hardware.org/?probe=dcb774f0e8) | Feb 27, 2024 |
| HP            | 1497                        | Desktop     | [58e91b7bbc](https://linux-hardware.org/?probe=58e91b7bbc) | Feb 26, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [47c8a22aea](https://linux-hardware.org/?probe=47c8a22aea) | Feb 26, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [5edfd90f55](https://linux-hardware.org/?probe=5edfd90f55) | Feb 26, 2024 |
| ASRock        | N68C-S UCC                  | Desktop     | [4aff653920](https://linux-hardware.org/?probe=4aff653920) | Feb 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [27c2f0156e](https://linux-hardware.org/?probe=27c2f0156e) | Feb 25, 2024 |
| MSI           | Modern 14 B11MO             | Notebook    | [6f5a4e6e1e](https://linux-hardware.org/?probe=6f5a4e6e1e) | Feb 23, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4e50b74dd4](https://linux-hardware.org/?probe=4e50b74dd4) | Feb 22, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [8070df1f8e](https://linux-hardware.org/?probe=8070df1f8e) | Feb 21, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e2780e976f](https://linux-hardware.org/?probe=e2780e976f) | Feb 18, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [95978292b2](https://linux-hardware.org/?probe=95978292b2) | Feb 18, 2024 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [fe0255bc9f](https://linux-hardware.org/?probe=fe0255bc9f) | Feb 15, 2024 |
| Dell          | Latitude E5470              | Notebook    | [4f6f03415f](https://linux-hardware.org/?probe=4f6f03415f) | Feb 12, 2024 |
| Acer          | Predator PT516-52s          | Notebook    | [d271f4b0ca](https://linux-hardware.org/?probe=d271f4b0ca) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | Notebook    | [a3255728e7](https://linux-hardware.org/?probe=a3255728e7) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | Notebook    | [aa78cf8909](https://linux-hardware.org/?probe=aa78cf8909) | Feb 12, 2024 |
| Foxconn       | A76GMV                      | Desktop     | [b15858bfd0](https://linux-hardware.org/?probe=b15858bfd0) | Feb 10, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [1d2758029b](https://linux-hardware.org/?probe=1d2758029b) | Feb 08, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [0b028612c5](https://linux-hardware.org/?probe=0b028612c5) | Feb 08, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [d01b52dd20](https://linux-hardware.org/?probe=d01b52dd20) | Feb 05, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [1e6645fdc9](https://linux-hardware.org/?probe=1e6645fdc9) | Feb 05, 2024 |
| HP            | 18E7                        | Desktop     | [84caef4dde](https://linux-hardware.org/?probe=84caef4dde) | Feb 02, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [e87efb031b](https://linux-hardware.org/?probe=e87efb031b) | Feb 02, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [62254b1636](https://linux-hardware.org/?probe=62254b1636) | Jan 31, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [a78d79030e](https://linux-hardware.org/?probe=a78d79030e) | Jan 30, 2024 |
| Dell          | Studio 1747                 | Notebook    | [b43d9b4a13](https://linux-hardware.org/?probe=b43d9b4a13) | Jan 29, 2024 |
| Dell          | Studio 1747                 | Notebook    | [9fe0b059bc](https://linux-hardware.org/?probe=9fe0b059bc) | Jan 29, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [49e891b67d](https://linux-hardware.org/?probe=49e891b67d) | Jan 28, 2024 |
| Dell          | 01W23F A05                  | Server      | [93f017d8b0](https://linux-hardware.org/?probe=93f017d8b0) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b55015259](https://linux-hardware.org/?probe=9b55015259) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3cecdef02f](https://linux-hardware.org/?probe=3cecdef02f) | Jan 26, 2024 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [32d1dff107](https://linux-hardware.org/?probe=32d1dff107) | Jan 26, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [44539fb8b1](https://linux-hardware.org/?probe=44539fb8b1) | Jan 25, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [dc93e0097a](https://linux-hardware.org/?probe=dc93e0097a) | Jan 25, 2024 |
| HP            | 3648h                       | Desktop     | [3905de5f4f](https://linux-hardware.org/?probe=3905de5f4f) | Jan 24, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [be74f076bd](https://linux-hardware.org/?probe=be74f076bd) | Jan 23, 2024 |
| Dell          | Latitude 7280               | Notebook    | [21e6e4a581](https://linux-hardware.org/?probe=21e6e4a581) | Jan 22, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0b0db0e2ef](https://linux-hardware.org/?probe=0b0db0e2ef) | Jan 22, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [36cb9057d7](https://linux-hardware.org/?probe=36cb9057d7) | Jan 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [f6204361d0](https://linux-hardware.org/?probe=f6204361d0) | Jan 19, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [12539bda5e](https://linux-hardware.org/?probe=12539bda5e) | Jan 19, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [667df4a998](https://linux-hardware.org/?probe=667df4a998) | Jan 17, 2024 |
| HP            | 255 G3                      | Notebook    | [7f8af802a0](https://linux-hardware.org/?probe=7f8af802a0) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [82f1c7e4f3](https://linux-hardware.org/?probe=82f1c7e4f3) | Jan 14, 2024 |
| HP            | EliteBook 745 G5            | Notebook    | [64314a5149](https://linux-hardware.org/?probe=64314a5149) | Jan 13, 2024 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [b37b59525e](https://linux-hardware.org/?probe=b37b59525e) | Jan 12, 2024 |
| Dell          | Latitude 5431               | Notebook    | [45d7b96fb3](https://linux-hardware.org/?probe=45d7b96fb3) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Dell          | Latitude E7470              | Notebook    | [2d36d1a363](https://linux-hardware.org/?probe=2d36d1a363) | Jan 11, 2024 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [f46fcb5ee9](https://linux-hardware.org/?probe=f46fcb5ee9) | Jan 10, 2024 |
| MSI           | Katana GF66 12UG            | Notebook    | [d4affacb08](https://linux-hardware.org/?probe=d4affacb08) | Jan 08, 2024 |
| Dell          | Latitude 7280               | Notebook    | [9557a37753](https://linux-hardware.org/?probe=9557a37753) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [26ec173956](https://linux-hardware.org/?probe=26ec173956) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [514f7e46c3](https://linux-hardware.org/?probe=514f7e46c3) | Jan 04, 2024 |
| Dell          | Latitude D630               | Notebook    | [e48315d3aa](https://linux-hardware.org/?probe=e48315d3aa) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [88f364d196](https://linux-hardware.org/?probe=88f364d196) | Jan 03, 2024 |
| ASRock        | Z87 Extreme4                | Desktop     | [eb75366525](https://linux-hardware.org/?probe=eb75366525) | Jan 03, 2024 |
| ASRock        | Z87 Extreme4                | Desktop     | [2b8d61b50d](https://linux-hardware.org/?probe=2b8d61b50d) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [15ae58d88c](https://linux-hardware.org/?probe=15ae58d88c) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [c9312cc676](https://linux-hardware.org/?probe=c9312cc676) | Jan 03, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Sony          | VGN-CS21Z_Q                 | Notebook    | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [8651fcb2dc](https://linux-hardware.org/?probe=8651fcb2dc) | Dec 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Dell          | Precision 5560              | Notebook    | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c8430d442b](https://linux-hardware.org/?probe=c8430d442b) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d412fe88ac](https://linux-hardware.org/?probe=d412fe88ac) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5aae59ec96](https://linux-hardware.org/?probe=5aae59ec96) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [217704dcb3](https://linux-hardware.org/?probe=217704dcb3) | Dec 27, 2023 |
| Biostar       | H61MHV3                     | Desktop     | [f03f05706c](https://linux-hardware.org/?probe=f03f05706c) | Dec 26, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [1ef527f93a](https://linux-hardware.org/?probe=1ef527f93a) | Dec 24, 2023 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [acee62fb75](https://linux-hardware.org/?probe=acee62fb75) | Dec 13, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [c6c8d22a8e](https://linux-hardware.org/?probe=c6c8d22a8e) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [ce858f7f7c](https://linux-hardware.org/?probe=ce858f7f7c) | Dec 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [c71041fa59](https://linux-hardware.org/?probe=c71041fa59) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [fc475e4cd3](https://linux-hardware.org/?probe=fc475e4cd3) | Dec 11, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [0841e29863](https://linux-hardware.org/?probe=0841e29863) | Dec 10, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| Dell          | 0GM819                      | Desktop     | [8ff7ec90b2](https://linux-hardware.org/?probe=8ff7ec90b2) | Dec 05, 2023 |
| Lenovo        | 3000 G410                   | Notebook    | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4cbc340e7c](https://linux-hardware.org/?probe=4cbc340e7c) | Dec 01, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [80e09b727b](https://linux-hardware.org/?probe=80e09b727b) | Nov 30, 2023 |
| HP            | EliteBook 8530p             | Notebook    | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [e3473e64c5](https://linux-hardware.org/?probe=e3473e64c5) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [c9b79740d2](https://linux-hardware.org/?probe=c9b79740d2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DV0Y    | Notebook    | [c68289cf4c](https://linux-hardware.org/?probe=c68289cf4c) | Nov 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [d979c6298f](https://linux-hardware.org/?probe=d979c6298f) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ab4754aa8](https://linux-hardware.org/?probe=2ab4754aa8) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [576d311bde](https://linux-hardware.org/?probe=576d311bde) | Nov 18, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a8cc099fb1](https://linux-hardware.org/?probe=a8cc099fb1) | Nov 18, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Lenovo        | ThinkPad X270 20HMS76D02    | Notebook    | [7da50d5ad3](https://linux-hardware.org/?probe=7da50d5ad3) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASRock        | J3455M                      | Desktop     | [6a3463b7e9](https://linux-hardware.org/?probe=6a3463b7e9) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [4a2561319d](https://linux-hardware.org/?probe=4a2561319d) | Nov 08, 2023 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [143a351fe0](https://linux-hardware.org/?probe=143a351fe0) | Nov 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [25ab11fca1](https://linux-hardware.org/?probe=25ab11fca1) | Nov 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| HP            | Spectre Pro x360 G2         | Convertible | [de099b29d0](https://linux-hardware.org/?probe=de099b29d0) | Nov 06, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | Notebook    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | Notebook    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ebfb135726](https://linux-hardware.org/?probe=ebfb135726) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c06d2e60fc](https://linux-hardware.org/?probe=c06d2e60fc) | Nov 01, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [09b312b58c](https://linux-hardware.org/?probe=09b312b58c) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [9b65c56faa](https://linux-hardware.org/?probe=9b65c56faa) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | Notebook    | [3b8803286b](https://linux-hardware.org/?probe=3b8803286b) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | Notebook    | [63963cbe04](https://linux-hardware.org/?probe=63963cbe04) | Oct 25, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [e0591a946d](https://linux-hardware.org/?probe=e0591a946d) | Oct 25, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [9c136d661d](https://linux-hardware.org/?probe=9c136d661d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | Notebook    | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [102735d7e5](https://linux-hardware.org/?probe=102735d7e5) | Oct 21, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [6c4a10bf6e](https://linux-hardware.org/?probe=6c4a10bf6e) | Oct 18, 2023 |
| Gigabyte      | Z590 VISION D               | Desktop     | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| Dell          | Latitude E5410              | Notebook    | [b1559718de](https://linux-hardware.org/?probe=b1559718de) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [63341aa786](https://linux-hardware.org/?probe=63341aa786) | Oct 13, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [c699787ab8](https://linux-hardware.org/?probe=c699787ab8) | Oct 11, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [a3b9e5b40c](https://linux-hardware.org/?probe=a3b9e5b40c) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ec7aee0455](https://linux-hardware.org/?probe=ec7aee0455) | Oct 10, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [e06a9dcd7d](https://linux-hardware.org/?probe=e06a9dcd7d) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | Notebook    | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| HP            | 635                         | Notebook    | [ef474a26d0](https://linux-hardware.org/?probe=ef474a26d0) | Oct 07, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [93e298660d](https://linux-hardware.org/?probe=93e298660d) | Oct 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [233fe08ffd](https://linux-hardware.org/?probe=233fe08ffd) | Oct 07, 2023 |
| AWOW          | AL34                        | Desktop     | [8933a81f53](https://linux-hardware.org/?probe=8933a81f53) | Oct 07, 2023 |
| ONDA          | V80 PLUS                    | Notebook    | [8651e33f83](https://linux-hardware.org/?probe=8651e33f83) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5584c834bc](https://linux-hardware.org/?probe=5584c834bc) | Oct 04, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [56a4c9aa55](https://linux-hardware.org/?probe=56a4c9aa55) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [efd92c3198](https://linux-hardware.org/?probe=efd92c3198) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Dell          | Precision 5510              | Notebook    | [34ddd03339](https://linux-hardware.org/?probe=34ddd03339) | Sep 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [03aa0d1366](https://linux-hardware.org/?probe=03aa0d1366) | Sep 25, 2023 |
| HP            | 3047h                       | Desktop     | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6c75af44c4](https://linux-hardware.org/?probe=6c75af44c4) | Sep 21, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Timi          | A30                         | Notebook    | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [744362d446](https://linux-hardware.org/?probe=744362d446) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [82d4f51421](https://linux-hardware.org/?probe=82d4f51421) | Sep 12, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ae29792d70](https://linux-hardware.org/?probe=ae29792d70) | Sep 11, 2023 |
| ASRock        | H81 Pro BTC                 | Desktop     | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| Dell          | Latitude 5431               | Notebook    | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [0405093009](https://linux-hardware.org/?probe=0405093009) | Sep 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [2e5644f065](https://linux-hardware.org/?probe=2e5644f065) | Sep 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| MSI           | Bravo 15 C7VF               | Notebook    | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [19d11f7098](https://linux-hardware.org/?probe=19d11f7098) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [245964564e](https://linux-hardware.org/?probe=245964564e) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| HP            | 1497                        | Desktop     | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f21550a5b3](https://linux-hardware.org/?probe=f21550a5b3) | Sep 02, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6dc701c67d](https://linux-hardware.org/?probe=6dc701c67d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | Notebook    | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| Dell          | Studio 1747                 | Notebook    | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [74ff13d301](https://linux-hardware.org/?probe=74ff13d301) | Aug 23, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [66691707c9](https://linux-hardware.org/?probe=66691707c9) | Aug 16, 2023 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [3dacfd8a02](https://linux-hardware.org/?probe=3dacfd8a02) | Aug 16, 2023 |
| Dell          | Latitude E4300              | Notebook    | [7c153c96f5](https://linux-hardware.org/?probe=7c153c96f5) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [ec4bac7b02](https://linux-hardware.org/?probe=ec4bac7b02) | Aug 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| Dell          | Precision M4600             | Notebook    | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [7723e84488](https://linux-hardware.org/?probe=7723e84488) | Aug 09, 2023 |
| Dell          | Latitude E4300              | Notebook    | [9ae3d19a62](https://linux-hardware.org/?probe=9ae3d19a62) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | Notebook    | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| Dell          | Precision 7750              | Notebook    | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| HP            | 198E                        | Desktop     | [34023c0d62](https://linux-hardware.org/?probe=34023c0d62) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [5a9a1e320d](https://linux-hardware.org/?probe=5a9a1e320d) | Jul 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | 635                         | Notebook    | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Latitude 7275               | Tablet      | [fdeba04a06](https://linux-hardware.org/?probe=fdeba04a06) | Jul 19, 2023 |
| HP            | ProBook 6570b               | Notebook    | [0a74371e23](https://linux-hardware.org/?probe=0a74371e23) | Jul 18, 2023 |
| Dell          | Inspiron 3551               | Notebook    | [543382ea16](https://linux-hardware.org/?probe=543382ea16) | Jul 16, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [cd17b6716c](https://linux-hardware.org/?probe=cd17b6716c) | Jul 16, 2023 |
| Dell          | Inspiron 3551               | Notebook    | [74050e892f](https://linux-hardware.org/?probe=74050e892f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [639eb4733c](https://linux-hardware.org/?probe=639eb4733c) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Dell          | G15 5511                    | Notebook    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| HP            | Notebook                    | Notebook    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | Notebook    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [5b561a0e00](https://linux-hardware.org/?probe=5b561a0e00) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [b2b20dd3f1](https://linux-hardware.org/?probe=b2b20dd3f1) | Jun 26, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Dell          | Latitude 3180               | Notebook    | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | Desktop     | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [3c0316ef92](https://linux-hardware.org/?probe=3c0316ef92) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a6fb35a2d8](https://linux-hardware.org/?probe=a6fb35a2d8) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [3d694e1b9a](https://linux-hardware.org/?probe=3d694e1b9a) | Jun 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Dell          | Precision 7710              | Notebook    | [f1b57ded18](https://linux-hardware.org/?probe=f1b57ded18) | Jun 08, 2023 |
| Dell          | Latitude 3350               | Notebook    | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Cube          | i16-L                       | Notebook    | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| HP            | 3047h                       | Desktop     | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | Notebook    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [aeb6fa2258](https://linux-hardware.org/?probe=aeb6fa2258) | May 26, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f0e96b17d7](https://linux-hardware.org/?probe=f0e96b17d7) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02d5fa9cc3](https://linux-hardware.org/?probe=02d5fa9cc3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0eec4b5bbe](https://linux-hardware.org/?probe=0eec4b5bbe) | May 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4280ce2bd4](https://linux-hardware.org/?probe=4280ce2bd4) | May 15, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [92c052d9b4](https://linux-hardware.org/?probe=92c052d9b4) | May 14, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Beelink       | BT3 PRO                     | Notebook    | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [dc317ab270](https://linux-hardware.org/?probe=dc317ab270) | May 06, 2023 |
| ASRock        | H370 Pro4                   | Desktop     | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | Notebook    | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [01c8d89ab9](https://linux-hardware.org/?probe=01c8d89ab9) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5d0819f25c](https://linux-hardware.org/?probe=5d0819f25c) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [3d73e4cd7e](https://linux-hardware.org/?probe=3d73e4cd7e) | Apr 27, 2023 |
| Dell          | Latitude E4300              | Notebook    | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | Notebook    | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | Notebook    | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| HP            | 8056                        | Desktop     | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| Dell          | Latitude E4300              | Notebook    | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Dell          | Latitude E4300              | Notebook    | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| HP            | ProBook 4540s               | Notebook    | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| ASRock        | Z97X Killer                 | Desktop     | [d258d06b23](https://linux-hardware.org/?probe=d258d06b23) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [3b0ab63643](https://linux-hardware.org/?probe=3b0ab63643) | Apr 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [f05e3341d3](https://linux-hardware.org/?probe=f05e3341d3) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [1f19b2c0dc](https://linux-hardware.org/?probe=1f19b2c0dc) | Apr 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| ASUSTek       | P5K                         | Desktop     | [ea3489709c](https://linux-hardware.org/?probe=ea3489709c) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [3fdeb525d1](https://linux-hardware.org/?probe=3fdeb525d1) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [90b9eaf3fe](https://linux-hardware.org/?probe=90b9eaf3fe) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [88caf7c0d1](https://linux-hardware.org/?probe=88caf7c0d1) | Mar 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53cd93c3f5](https://linux-hardware.org/?probe=53cd93c3f5) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 8954                        | Desktop     | [e7a2f29df5](https://linux-hardware.org/?probe=e7a2f29df5) | Mar 27, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [ec1dd7f3ab](https://linux-hardware.org/?probe=ec1dd7f3ab) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | Notebook    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [f5a9d12043](https://linux-hardware.org/?probe=f5a9d12043) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41289d94bf](https://linux-hardware.org/?probe=41289d94bf) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [1ccaab03c4](https://linux-hardware.org/?probe=1ccaab03c4) | Mar 25, 2023 |
| Toshiba       | Satellite C850-140          | Notebook    | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Gigabyte      | M52S-S3P                    | Desktop     | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [3c4c536325](https://linux-hardware.org/?probe=3c4c536325) | Mar 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [abd4bb0963](https://linux-hardware.org/?probe=abd4bb0963) | Mar 21, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4dcebf6a41](https://linux-hardware.org/?probe=4dcebf6a41) | Mar 21, 2023 |
| HP            | ProBook 6475b               | Notebook    | [1b7a5f385c](https://linux-hardware.org/?probe=1b7a5f385c) | Mar 18, 2023 |
| HP            | ProBook 6475b               | Notebook    | [0fd12da29b](https://linux-hardware.org/?probe=0fd12da29b) | Mar 18, 2023 |
| HP            | ProBook 6475b               | Notebook    | [701aca7f61](https://linux-hardware.org/?probe=701aca7f61) | Mar 18, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [2a6ded1018](https://linux-hardware.org/?probe=2a6ded1018) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [47df31e0fb](https://linux-hardware.org/?probe=47df31e0fb) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [c14956dd2d](https://linux-hardware.org/?probe=c14956dd2d) | Mar 12, 2023 |
| Acer          | Aspire 5333                 | Notebook    | [214db069e4](https://linux-hardware.org/?probe=214db069e4) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [65c2aab8aa](https://linux-hardware.org/?probe=65c2aab8aa) | Mar 11, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [95da35c192](https://linux-hardware.org/?probe=95da35c192) | Mar 11, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | Desktop     | [0d5c00b6fa](https://linux-hardware.org/?probe=0d5c00b6fa) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [e03e243c84](https://linux-hardware.org/?probe=e03e243c84) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Dell          | Latitude E4300              | Notebook    | [3c777f1c07](https://linux-hardware.org/?probe=3c777f1c07) | Mar 10, 2023 |
| HP            | ProBook 6475b               | Notebook    | [be06cdc105](https://linux-hardware.org/?probe=be06cdc105) | Mar 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [f4b107fbf3](https://linux-hardware.org/?probe=f4b107fbf3) | Mar 02, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [c068117b39](https://linux-hardware.org/?probe=c068117b39) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c3d0c5da79](https://linux-hardware.org/?probe=c3d0c5da79) | Mar 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [df09052bac](https://linux-hardware.org/?probe=df09052bac) | Mar 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f9cae700c7](https://linux-hardware.org/?probe=f9cae700c7) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [4f7bbbdd28](https://linux-hardware.org/?probe=4f7bbbdd28) | Feb 24, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| Google        | Astronaut                   | Notebook    | [71e8582f54](https://linux-hardware.org/?probe=71e8582f54) | Feb 22, 2023 |
| Google        | Astronaut                   | Notebook    | [4949e50dad](https://linux-hardware.org/?probe=4949e50dad) | Feb 22, 2023 |
| HP            | Notebook                    | Notebook    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [74b6676de3](https://linux-hardware.org/?probe=74b6676de3) | Feb 19, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5ebabab1c5](https://linux-hardware.org/?probe=5ebabab1c5) | Feb 14, 2023 |
| HP            | ProBook 6460b               | Notebook    | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [1df562d2d8](https://linux-hardware.org/?probe=1df562d2d8) | Feb 13, 2023 |
| Dell          | Precision M4700             | Notebook    | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9b58106fd6](https://linux-hardware.org/?probe=9b58106fd6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [65ebc31f26](https://linux-hardware.org/?probe=65ebc31f26) | Feb 08, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f2664ae2a](https://linux-hardware.org/?probe=9f2664ae2a) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [7037d37121](https://linux-hardware.org/?probe=7037d37121) | Feb 05, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
| Dell          | Precision 5540              | Notebook    | [de6a1c523e](https://linux-hardware.org/?probe=de6a1c523e) | Jan 28, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c34bc63cb0](https://linux-hardware.org/?probe=c34bc63cb0) | Jan 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a9a199e6f7](https://linux-hardware.org/?probe=a9a199e6f7) | Jan 24, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [e4b2eae84b](https://linux-hardware.org/?probe=e4b2eae84b) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| ASRock        | H81M-ITX                    | Desktop     | [036832c7d1](https://linux-hardware.org/?probe=036832c7d1) | Jan 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [ca332b4905](https://linux-hardware.org/?probe=ca332b4905) | Jan 13, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [30b776e4e8](https://linux-hardware.org/?probe=30b776e4e8) | Jan 11, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [7cd86f1bf1](https://linux-hardware.org/?probe=7cd86f1bf1) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [183b311eb2](https://linux-hardware.org/?probe=183b311eb2) | Jan 09, 2023 |
| Google        | Kled                        | Notebook    | [6380ae012e](https://linux-hardware.org/?probe=6380ae012e) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| System76      | Gazelle                     | Notebook    | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Fujitsu       | D3076-S1 S26361-D3076-S1    | Desktop     | [10b0d01482](https://linux-hardware.org/?probe=10b0d01482) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| Dell          | Precision M6400             | Notebook    | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [be5212ebcc](https://linux-hardware.org/?probe=be5212ebcc) | Jan 03, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [c51bc128e2](https://linux-hardware.org/?probe=c51bc128e2) | Dec 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Dell          | Latitude E5410              | Notebook    | [969f85bfc3](https://linux-hardware.org/?probe=969f85bfc3) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a4aed5865b](https://linux-hardware.org/?probe=a4aed5865b) | Dec 18, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [532dc55c4b](https://linux-hardware.org/?probe=532dc55c4b) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| Acer          | AO756                       | Notebook    | [ebc4d7cfcb](https://linux-hardware.org/?probe=ebc4d7cfcb) | Dec 16, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [936608196d](https://linux-hardware.org/?probe=936608196d) | Dec 14, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [6987aeacd5](https://linux-hardware.org/?probe=6987aeacd5) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [f464385b16](https://linux-hardware.org/?probe=f464385b16) | Dec 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [f4188b30c9](https://linux-hardware.org/?probe=f4188b30c9) | Dec 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [7ea67f4c69](https://linux-hardware.org/?probe=7ea67f4c69) | Dec 11, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9158c39614](https://linux-hardware.org/?probe=9158c39614) | Dec 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Acer          | Aspire ES1-731G             | Notebook    | [589cce31c8](https://linux-hardware.org/?probe=589cce31c8) | Dec 09, 2022 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [ff0997b72a](https://linux-hardware.org/?probe=ff0997b72a) | Dec 09, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [aae285b0ea](https://linux-hardware.org/?probe=aae285b0ea) | Dec 09, 2022 |
| HP            | 3047h                       | Desktop     | [223495dbab](https://linux-hardware.org/?probe=223495dbab) | Dec 08, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [01e7f95a23](https://linux-hardware.org/?probe=01e7f95a23) | Dec 07, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [c3b6c86431](https://linux-hardware.org/?probe=c3b6c86431) | Dec 07, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5ff0fd5395](https://linux-hardware.org/?probe=5ff0fd5395) | Dec 06, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [e2ffdfc5a8](https://linux-hardware.org/?probe=e2ffdfc5a8) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [50acc3b3b8](https://linux-hardware.org/?probe=50acc3b3b8) | Dec 04, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [9da9a87b5b](https://linux-hardware.org/?probe=9da9a87b5b) | Dec 03, 2022 |
| Acer          | Aspire ES1-731G             | Notebook    | [06918f4cc5](https://linux-hardware.org/?probe=06918f4cc5) | Dec 03, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [3e9458fd24](https://linux-hardware.org/?probe=3e9458fd24) | Dec 02, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | Notebook    | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [1424a94eb0](https://linux-hardware.org/?probe=1424a94eb0) | Nov 29, 2022 |
| Acer          | AO756                       | Notebook    | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | Notebook    | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| HP            | 1589                        | Desktop     | [4e67735055](https://linux-hardware.org/?probe=4e67735055) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d480b7ef56](https://linux-hardware.org/?probe=d480b7ef56) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d3b2f8aaf7](https://linux-hardware.org/?probe=d3b2f8aaf7) | Nov 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [faa15c49ae](https://linux-hardware.org/?probe=faa15c49ae) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [5468f11c01](https://linux-hardware.org/?probe=5468f11c01) | Nov 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [519c833f31](https://linux-hardware.org/?probe=519c833f31) | Nov 06, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | Notebook    | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | Notebook    | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| HP            | 8061                        | Desktop     | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| Acer          | Aspire 5830T                | Notebook    | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | Notebook    | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [b50165d9c9](https://linux-hardware.org/?probe=b50165d9c9) | Oct 11, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8f41682975](https://linux-hardware.org/?probe=8f41682975) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Samsung       | Galaxy TabPro S             | Tablet      | [25deda3e27](https://linux-hardware.org/?probe=25deda3e27) | Oct 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| HP            | 3047h                       | Desktop     | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3438959476](https://linux-hardware.org/?probe=3438959476) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | Notebook    | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [8047eeecb4](https://linux-hardware.org/?probe=8047eeecb4) | Aug 20, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | Notebook    | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c92d457cd6](https://linux-hardware.org/?probe=c92d457cd6) | Aug 13, 2022 |
| ASUSTek       | M2VTVM-VM890                | Desktop     | [8a822a57e8](https://linux-hardware.org/?probe=8a822a57e8) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [747ba68b28](https://linux-hardware.org/?probe=747ba68b28) | Aug 10, 2022 |
| Apple         | MacBookPro16,4              | Notebook    | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| Lenovo        | Unknown                     | Notebook    | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [616c57c367](https://linux-hardware.org/?probe=616c57c367) | Aug 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [e0129903ae](https://linux-hardware.org/?probe=e0129903ae) | Aug 04, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [69bd504820](https://linux-hardware.org/?probe=69bd504820) | Jul 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | Notebook    | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | Desktop     | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [2c0dd875b3](https://linux-hardware.org/?probe=2c0dd875b3) | Jun 21, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | Desktop     | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 118       | 7.85%   |
| Ubuntu 22.04                 | 103       | 6.85%   |
| Ubuntu 18.04                 | 81        | 5.39%   |
| Debian 11                    | 36        | 2.39%   |
| OpenMandriva 4.2             | 30        | 1.99%   |
| Arch Rolling                 | 30        | 1.99%   |
| Pop!_OS 22.04                | 26        | 1.73%   |
| Manjaro                      | 24        | 1.6%    |
| ArcoLinux Rolling            | 23        | 1.53%   |
| OpenMandriva 4.3             | 22        | 1.46%   |
| Fedora 38                    | 22        | 1.46%   |
| Fedora 39                    | 21        | 1.4%    |
| Fedora 40                    | 20        | 1.33%   |
| openSUSE Tumbleweed-XXXXXXXX | 19        | 1.26%   |
| OpenMandriva 23.08           | 19        | 1.26%   |
| Ubuntu 24.04                 | 18        | 1.2%    |
| ROSA R11                     | 18        | 1.2%    |
| Linux Mint 20.1              | 17        | 1.13%   |
| KDE neon 20.04               | 17        | 1.13%   |
| Debian 12                    | 17        | 1.13%   |
| Zorin 16                     | 16        | 1.06%   |
| Ubuntu 22.10                 | 16        | 1.06%   |
| ROSA R10                     | 16        | 1.06%   |
| Arch                         | 16        | 1.06%   |
| Linux Mint 20.3              | 15        | 1%      |
| Linux Mint 21.1              | 14        | 0.93%   |
| Linux Mint 19.3              | 14        | 0.93%   |
| Ubuntu 19.04                 | 13        | 0.86%   |
| Linux Mint 20.2              | 13        | 0.86%   |
| Linux Mint 20                | 13        | 0.86%   |
| Kubuntu 20.04                | 13        | 0.86%   |
| Zorin 15                     | 12        | 0.8%    |
| Xubuntu 18.04                | 12        | 0.8%    |
| Ubuntu 23.10                 | 12        | 0.8%    |
| OpenMandriva 23.03           | 12        | 0.8%    |
| Kubuntu 22.04                | 12        | 0.8%    |
| Xubuntu 20.04                | 11        | 0.73%   |
| Ubuntu 20.10                 | 11        | 0.73%   |
| Ubuntu 19.10                 | 11        | 0.73%   |
| Linux Mint 22                | 11        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 390       | 28.45%  |
| Linux Mint    | 113       | 8.24%   |
| OpenMandriva  | 102       | 7.44%   |
| Fedora        | 102       | 7.44%   |
| Debian        | 64        | 4.67%   |
| Manjaro       | 60        | 4.38%   |
| ROSA          | 55        | 4.01%   |
| Pop!_OS       | 54        | 3.94%   |
| Arch          | 44        | 3.21%   |
| Kubuntu       | 37        | 2.7%    |
| Zorin         | 36        | 2.63%   |
| Xubuntu       | 30        | 2.19%   |
| Endless       | 29        | 2.12%   |
| KDE neon      | 27        | 1.97%   |
| Kali          | 25        | 1.82%   |
| ArcoLinux     | 25        | 1.82%   |
| openSUSE      | 24        | 1.75%   |
| Ubuntu Unity  | 14        | 1.02%   |
| Clear Linux   | 12        | 0.88%   |
| Elementary    | 11        | 0.8%    |
| LMDE          | 9         | 0.66%   |
| Lubuntu       | 8         | 0.58%   |
| CentOS        | 8         | 0.58%   |
| Gentoo        | 7         | 0.51%   |
| EndeavourOS   | 7         | 0.51%   |
| Ubuntu MATE   | 6         | 0.44%   |
| SteamOS       | 5         | 0.36%   |
| Artix         | 5         | 0.36%   |
| MX            | 4         | 0.29%   |
| Void Linux    | 3         | 0.22%   |
| Ubuntu Budgie | 3         | 0.22%   |
| TUXEDO OS     | 3         | 0.22%   |
| Parrot        | 3         | 0.22%   |
| Nobara        | 3         | 0.22%   |
| NixOS         | 3         | 0.22%   |
| Garuda Linux  | 3         | 0.22%   |
| Xero          | 2         | 0.15%   |
| Ubuntu Studio | 2         | 0.15%   |
| Rocky Linux   | 2         | 0.15%   |
| Novos         | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 30        | 1.81%   |
| 5.16.7-desktop-1omv4003         | 21        | 1.26%   |
| 5.4.0-42-generic                | 17        | 1.02%   |
| 6.4.11-desktop-1omv2390         | 15        | 0.9%    |
| 5.4.0-58-generic                | 13        | 0.78%   |
| 5.15.0-56-generic               | 13        | 0.78%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 13        | 0.78%   |
| 6.2.6-desktop-1omv2390          | 11        | 0.66%   |
| 5.3.0-40-generic                | 10        | 0.6%    |
| 6.2.0-39-generic                | 9         | 0.54%   |
| 6.10.0-desktop-1omv2490         | 8         | 0.48%   |
| 5.9.16-1-MANJARO                | 8         | 0.48%   |
| 5.4.0-26-generic                | 8         | 0.48%   |
| 6.9.3-76060903-generic          | 7         | 0.42%   |
| 6.8.0-51-generic                | 7         | 0.42%   |
| 6.8.0-40-generic                | 7         | 0.42%   |
| 6.2.0-26-generic                | 7         | 0.42%   |
| 5.4.0-48-generic                | 7         | 0.42%   |
| 5.4.0-29-generic                | 7         | 0.42%   |
| 5.3.0-46-generic                | 7         | 0.42%   |
| 5.3.0-28-generic                | 7         | 0.42%   |
| 5.10.0-8-amd64                  | 7         | 0.42%   |
| 5.0.0-37-generic                | 7         | 0.42%   |
| 6.8.0-45-generic                | 6         | 0.36%   |
| 6.5.0-27-generic                | 6         | 0.36%   |
| 6.2.6-76060206-generic          | 6         | 0.36%   |
| 6.1.1-desktop-1omv2290          | 6         | 0.36%   |
| 5.8.0-14-generic                | 6         | 0.36%   |
| 5.4.0-65-generic                | 6         | 0.36%   |
| 5.4.0-56-generic                | 6         | 0.36%   |
| 5.4.0-40-generic                | 6         | 0.36%   |
| 5.3.0-42-generic                | 6         | 0.36%   |
| 5.19.0-35-generic               | 6         | 0.36%   |
| 5.11.0-37-generic               | 6         | 0.36%   |
| 5.11.0-27-generic               | 6         | 0.36%   |
| 5.0.0-23-generic                | 6         | 0.36%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 6         | 0.36%   |
| 4.15.0-20-generic               | 6         | 0.36%   |
| 6.8.0-49-generic                | 5         | 0.3%    |
| 6.8.0-31-generic                | 5         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 170       | 10.79%  |
| 5.15.0  | 112       | 7.11%   |
| 4.15.0  | 81        | 5.14%   |
| 5.8.0   | 55        | 3.49%   |
| 6.8.0   | 54        | 3.43%   |
| 6.5.0   | 51        | 3.24%   |
| 5.3.0   | 50        | 3.17%   |
| 6.2.0   | 44        | 2.79%   |
| 5.19.0  | 40        | 2.54%   |
| 5.11.0  | 39        | 2.47%   |
| 5.10.0  | 38        | 2.41%   |
| 5.13.0  | 37        | 2.35%   |
| 5.0.0   | 37        | 2.35%   |
| 5.10.14 | 31        | 1.97%   |
| 6.1.0   | 24        | 1.52%   |
| 4.18.0  | 23        | 1.46%   |
| 5.16.7  | 21        | 1.33%   |
| 6.2.6   | 18        | 1.14%   |
| 6.4.11  | 16        | 1.02%   |
| 4.19.0  | 13        | 0.82%   |
| 5.9.16  | 11        | 0.7%    |
| 6.1.1   | 9         | 0.57%   |
| 5.14.0  | 9         | 0.57%   |
| 4.9.20  | 9         | 0.57%   |
| 6.9.3   | 8         | 0.51%   |
| 6.10.0  | 8         | 0.51%   |
| 5.17.5  | 8         | 0.51%   |
| 6.6.10  | 7         | 0.44%   |
| 6.6.8   | 6         | 0.38%   |
| 6.0.0   | 6         | 0.38%   |
| 5.18.0  | 6         | 0.38%   |
| 4.9.60  | 6         | 0.38%   |
| 4.4.0   | 6         | 0.38%   |
| 6.8.11  | 5         | 0.32%   |
| 6.5.5   | 5         | 0.32%   |
| 6.4.8   | 5         | 0.32%   |
| 5.8.18  | 5         | 0.32%   |
| 4.9.124 | 5         | 0.32%   |
| 6.7.4   | 4         | 0.25%   |
| 6.6.9   | 4         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 181       | 11.74%  |
| 5.15    | 147       | 9.53%   |
| 5.10    | 96        | 6.23%   |
| 4.15    | 81        | 5.25%   |
| 6.2     | 79        | 5.12%   |
| 6.5     | 74        | 4.8%    |
| 6.8     | 73        | 4.73%   |
| 5.8     | 68        | 4.41%   |
| 5.3     | 59        | 3.83%   |
| 6.1     | 55        | 3.57%   |
| 5.11    | 51        | 3.31%   |
| 5.19    | 49        | 3.18%   |
| 5.13    | 43        | 2.79%   |
| 6.6     | 42        | 2.72%   |
| 5.16    | 40        | 2.59%   |
| 5.0     | 40        | 2.59%   |
| 6.4     | 35        | 2.27%   |
| 6.10    | 27        | 1.75%   |
| 4.9     | 26        | 1.69%   |
| 4.18    | 24        | 1.56%   |
| 5.17    | 20        | 1.3%    |
| 5.14    | 19        | 1.23%   |
| 6.0     | 18        | 1.17%   |
| 4.19    | 18        | 1.17%   |
| 6.9     | 17        | 1.1%    |
| 5.9     | 17        | 1.1%    |
| 6.11    | 16        | 1.04%   |
| 5.6     | 16        | 1.04%   |
| 6.7     | 15        | 0.97%   |
| 6.3     | 14        | 0.91%   |
| 5.18    | 13        | 0.84%   |
| 5.7     | 12        | 0.78%   |
| 5.12    | 12        | 0.78%   |
| 6.12    | 11        | 0.71%   |
| 5.5     | 7         | 0.45%   |
| 4.4     | 6         | 0.39%   |
| 5.2     | 5         | 0.32%   |
| 4.1     | 4         | 0.26%   |
| 5.1     | 3         | 0.19%   |
| 3.10    | 3         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1273      | 97.1%   |
| i686    | 34        | 2.59%   |
| aarch64 | 4         | 0.31%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 553       | 39.36%  |
| KDE5             | 251       | 17.86%  |
| Unknown          | 150       | 10.68%  |
| XFCE             | 118       | 8.4%    |
| X-Cinnamon       | 98        | 6.98%   |
| KDE4             | 33        | 2.35%   |
| KDE              | 32        | 2.28%   |
| MATE             | 31        | 2.21%   |
| KDE6             | 25        | 1.78%   |
| Cinnamon         | 21        | 1.49%   |
| LXQt             | 16        | 1.14%   |
| Unity            | 14        | 1%      |
| Pantheon         | 11        | 0.78%   |
| i3               | 9         | 0.64%   |
| Budgie           | 7         | 0.5%    |
| GNOME Flashback  | 5         | 0.36%   |
| GNOME Classic    | 4         | 0.28%   |
| Deepin           | 4         | 0.28%   |
| LXDE             | 3         | 0.21%   |
| bspwm            | 3         | 0.21%   |
| xmonad           | 2         | 0.14%   |
| sway             | 2         | 0.14%   |
| qtile            | 2         | 0.14%   |
| lightdm-xsession | 2         | 0.14%   |
| Hyprland         | 2         | 0.14%   |
| trinity          | 1         | 0.07%   |
| openbox          | 1         | 0.07%   |
| icewm            | 1         | 0.07%   |
| Endless:GNOME    | 1         | 0.07%   |
| DWM              | 1         | 0.07%   |
| COSMIC           | 1         | 0.07%   |
| awesome          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 985       | 71.9%   |
| Wayland | 282       | 20.58%  |
| Unknown | 73        | 5.33%   |
| Tty     | 30        | 2.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 611       | 44.24%  |
| SDDM    | 247       | 17.89%  |
| GDM3    | 183       | 13.25%  |
| LightDM | 160       | 11.59%  |
| GDM     | 111       | 8.04%   |
| TDM     | 33        | 2.39%   |
| KDM     | 32        | 2.32%   |
| XDM     | 3         | 0.22%   |
| MDM     | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 868       | 63.96%  |
| bg_BG   | 231       | 17.02%  |
| Unknown | 144       | 10.61%  |
| C       | 34        | 2.51%   |
| en_GB   | 33        | 2.43%   |
| ru_RU   | 14        | 1.03%   |
| de_DE   | 8         | 0.59%   |
| POSIX   | 3         | 0.22%   |
| it_IT   | 3         | 0.22%   |
| es_ES   | 3         | 0.22%   |
| en_DK   | 2         | 0.15%   |
| C.UTF8  | 2         | 0.15%   |
| uk_UA   | 1         | 0.07%   |
| tr_TR   | 1         | 0.07%   |
| sv_SE   | 1         | 0.07%   |
| ru_UA   | 1         | 0.07%   |
| ia_FR   | 1         | 0.07%   |
| hu_HU   | 1         | 0.07%   |
| fr_FR   | 1         | 0.07%   |
| en_NZ   | 1         | 0.07%   |
| en_CA   | 1         | 0.07%   |
| en_AU   | 1         | 0.07%   |
| en_AG   | 1         | 0.07%   |
| Default | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 735       | 54.53%  |
| EFI  | 613       | 45.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 952       | 69.95%  |
| Btrfs   | 135       | 9.92%   |
| Overlay | 100       | 7.35%   |
| Tmpfs   | 73        | 5.36%   |
| Unknown | 56        | 4.11%   |
| Xfs     | 25        | 1.84%   |
| Zfs     | 10        | 0.73%   |
| Ext3    | 4         | 0.29%   |
| Ext2    | 3         | 0.22%   |
| Nfs     | 1         | 0.07%   |
| Jfs     | 1         | 0.07%   |
| F2fs    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 625       | 46.16%  |
| GPT     | 548       | 40.47%  |
| MBR     | 181       | 13.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1146      | 85.2%   |
| Yes       | 199       | 14.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 922       | 69.01%  |
| Yes       | 414       | 30.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 267       | 20.4%   |
| ASUSTek Computer                     | 213       | 16.27%  |
| Hewlett-Packard                      | 189       | 14.44%  |
| Dell                                 | 154       | 11.76%  |
| Acer                                 | 89        | 6.8%    |
| ASRock                               | 86        | 6.57%   |
| Gigabyte Technology                  | 79        | 6.04%   |
| MSI                                  | 50        | 3.82%   |
| Toshiba                              | 36        | 2.75%   |
| Fujitsu                              | 21        | 1.6%    |
| Apple                                | 15        | 1.15%   |
| Intel                                | 10        | 0.76%   |
| Foxconn                              | 9         | 0.69%   |
| Unknown                              | 8         | 0.61%   |
| Sony                                 | 6         | 0.46%   |
| Fujitsu Siemens                      | 6         | 0.46%   |
| Valve                                | 5         | 0.38%   |
| AMI                                  | 5         | 0.38%   |
| Samsung Electronics                  | 4         | 0.31%   |
| Pegatron                             | 4         | 0.31%   |
| Packard Bell                         | 4         | 0.31%   |
| TUXEDO                               | 3         | 0.23%   |
| HUAWEI                               | 3         | 0.23%   |
| ECS                                  | 3         | 0.23%   |
| Wibtek                               | 2         | 0.15%   |
| TongFang                             | 2         | 0.15%   |
| Supermicro                           | 2         | 0.15%   |
| Raspberry Pi Foundation              | 2         | 0.15%   |
| Notebook                             | 2         | 0.15%   |
| Medion                               | 2         | 0.15%   |
| Google                               | 2         | 0.15%   |
| Timi                                 | 1         | 0.08%   |
| Thecus                               | 1         | 0.08%   |
| System76                             | 1         | 0.08%   |
| SLIMBOOK                             | 1         | 0.08%   |
| Shuttle                              | 1         | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.08%   |
| Seco                                 | 1         | 0.08%   |
| Razer                                | 1         | 0.08%   |
| Radxa                                | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 12        | 0.92%   |
| ASUS All Series                            | 7         | 0.53%   |
| Valve Jupiter                              | 5         | 0.38%   |
| Lenovo G500 20236                          | 5         | 0.38%   |
| Dell Inspiron N5110                        | 5         | 0.38%   |
| ASUS X541NA                                | 5         | 0.38%   |
| MSI MS-7C56                                | 4         | 0.31%   |
| Lenovo H520S 2561                          | 4         | 0.31%   |
| HP ProBook 4540s                           | 4         | 0.31%   |
| HP ProBook 450 G8 Notebook PC              | 4         | 0.31%   |
| HP Pavilion 15                             | 4         | 0.31%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA   | 4         | 0.31%   |
| MSI MS-7C37                                | 3         | 0.23%   |
| Lenovo Y520-15IKBN 80WK                    | 3         | 0.23%   |
| HP ProBook 450 G0                          | 3         | 0.23%   |
| HP Notebook                                | 3         | 0.23%   |
| HP EliteBook 840 G1                        | 3         | 0.23%   |
| HP 255 G8 Notebook PC                      | 3         | 0.23%   |
| Gigabyte B550 GAMING X V2                  | 3         | 0.23%   |
| Dell Precision Tower 5810                  | 3         | 0.23%   |
| Dell Precision M4600                       | 3         | 0.23%   |
| Dell OptiPlex 780                          | 3         | 0.23%   |
| Dell Latitude E6410                        | 3         | 0.23%   |
| Dell Latitude E4300                        | 3         | 0.23%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.23%   |
| ASUS N551VW                                | 3         | 0.23%   |
| ASRock Z97 Anniversary                     | 3         | 0.23%   |
| ASRock B450M Steel Legend                  | 3         | 0.23%   |
| Apple MacBookPro11,1                       | 3         | 0.23%   |
| Acer Aspire 5738                           | 3         | 0.23%   |
| Wibtek H61-M HDMI2                         | 2         | 0.15%   |
| Toshiba Satellite L50-B                    | 2         | 0.15%   |
| Toshiba Satellite L300                     | 2         | 0.15%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.15%   |
| Toshiba Satellite A300                     | 2         | 0.15%   |
| Toshiba Satellite A200                     | 2         | 0.15%   |
| TongFang GX5HRXL                           | 2         | 0.15%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.15%   |
| MSI MS-7B86                                | 2         | 0.15%   |
| MSI Modern 15 A5M                          | 2         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 117       | 8.94%   |
| Acer Aspire        | 61        | 4.66%   |
| Lenovo IdeaPad     | 54        | 4.13%   |
| Dell Latitude      | 46        | 3.51%   |
| Dell Inspiron      | 36        | 2.75%   |
| HP ProBook         | 34        | 2.6%    |
| HP Pavilion        | 33        | 2.52%   |
| HP Compaq          | 30        | 2.29%   |
| Toshiba Satellite  | 29        | 2.22%   |
| ASUS VivoBook      | 29        | 2.22%   |
| HP EliteBook       | 28        | 2.14%   |
| ASUS ROG           | 22        | 1.68%   |
| Dell Precision     | 19        | 1.45%   |
| Lenovo ThinkCentre | 17        | 1.3%    |
| Dell OptiPlex      | 17        | 1.3%    |
| ASUS PRIME         | 17        | 1.3%    |
| Lenovo Legion      | 16        | 1.22%   |
| Dell Vostro        | 16        | 1.22%   |
| Fujitsu ESPRIMO    | 12        | 0.92%   |
| Unknown            | 12        | 0.92%   |
| Lenovo Yoga        | 10        | 0.76%   |
| ASUS TUF           | 9         | 0.69%   |
| Dell XPS           | 8         | 0.61%   |
| Acer Nitro         | 8         | 0.61%   |
| HP 255             | 7         | 0.53%   |
| ASUS All           | 7         | 0.53%   |
| MSI Modern         | 6         | 0.46%   |
| Lenovo ThinkBook   | 6         | 0.46%   |
| HP Laptop          | 6         | 0.46%   |
| Gigabyte B550      | 6         | 0.46%   |
| ASUS P5K           | 6         | 0.46%   |
| ASUS ASUS          | 6         | 0.46%   |
| Acer Predator      | 6         | 0.46%   |
| Valve Jupiter      | 5         | 0.38%   |
| Lenovo G500        | 5         | 0.38%   |
| HP ZBook           | 5         | 0.38%   |
| HP ProDesk         | 5         | 0.38%   |
| HP 250             | 5         | 0.38%   |
| ASUS X541NA        | 5         | 0.38%   |
| MSI MS-7C56        | 4         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 106       | 8.1%    |
| 2020    | 102       | 7.79%   |
| 2012    | 100       | 7.64%   |
| 2011    | 100       | 7.64%   |
| 2013    | 96        | 7.33%   |
| 2017    | 95        | 7.26%   |
| 2018    | 88        | 6.72%   |
| 2021    | 85        | 6.49%   |
| 2014    | 73        | 5.58%   |
| 2022    | 67        | 5.12%   |
| 2015    | 66        | 5.04%   |
| 2008    | 63        | 4.81%   |
| 2010    | 62        | 4.74%   |
| 2009    | 54        | 4.13%   |
| 2007    | 41        | 3.13%   |
| 2016    | 40        | 3.06%   |
| 2023    | 36        | 2.75%   |
| 2006    | 16        | 1.22%   |
| 2024    | 9         | 0.69%   |
| Unknown | 4         | 0.31%   |
| 2005    | 3         | 0.23%   |
| 2004    | 3         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 803       | 61.34%  |
| Desktop        | 454       | 34.68%  |
| Convertible    | 18        | 1.38%   |
| Mini pc        | 14        | 1.07%   |
| All in one     | 7         | 0.53%   |
| Server         | 5         | 0.38%   |
| Tablet         | 4         | 0.31%   |
| System on chip | 3         | 0.23%   |
| Phone          | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1242      | 94.38%  |
| Enabled  | 74        | 5.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1305      | 99.69%  |
| Yes  | 4         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 333       | 24.78%  |
| 8.01-16.0       | 259       | 19.27%  |
| 3.01-4.0        | 242       | 18.01%  |
| 16.01-24.0      | 229       | 17.04%  |
| 32.01-64.0      | 131       | 9.75%   |
| 24.01-32.0      | 43        | 3.2%    |
| 1.01-2.0        | 38        | 2.83%   |
| 64.01-256.0     | 33        | 2.46%   |
| 2.01-3.0        | 28        | 2.08%   |
| 0.51-1.0        | 6         | 0.45%   |
| More than 256.0 | 2         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 424       | 28.04%  |
| 2.01-3.0   | 412       | 27.25%  |
| 4.01-8.0   | 245       | 16.2%   |
| 3.01-4.0   | 229       | 15.15%  |
| 0.51-1.0   | 96        | 6.35%   |
| 8.01-16.0  | 74        | 4.89%   |
| 16.01-24.0 | 16        | 1.06%   |
| 0.01-0.5   | 12        | 0.79%   |
| 24.01-32.0 | 2         | 0.13%   |
| 32.01-64.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 842       | 62.14%  |
| 2      | 342       | 25.24%  |
| 3      | 90        | 6.64%   |
| 4      | 28        | 2.07%   |
| 5      | 23        | 1.7%    |
| 6      | 12        | 0.89%   |
| 0      | 9         | 0.66%   |
| 7      | 4         | 0.3%    |
| 8      | 3         | 0.22%   |
| 11     | 1         | 0.07%   |
| 9      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 834       | 62.8%   |
| Yes       | 494       | 37.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1158      | 88.19%  |
| No        | 155       | 11.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 968       | 73.39%  |
| No        | 351       | 26.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 794       | 59.65%  |
| No        | 537       | 40.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Bulgaria | 1309      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Sofia               | 667       | 48.19%  |
| Varna               | 110       | 7.95%   |
| Plovdiv             | 95        | 6.86%   |
| Burgas              | 59        | 4.26%   |
| Stara Zagora        | 28        | 2.02%   |
| Rousse              | 20        | 1.45%   |
| Pernik              | 19        | 1.37%   |
| Pleven              | 17        | 1.23%   |
| Veliko Tarnovo      | 15        | 1.08%   |
| Yambol              | 14        | 1.01%   |
| Pazardzhik          | 13        | 0.94%   |
| Montana             | 13        | 0.94%   |
| Haskovo             | 13        | 0.94%   |
| Shumen              | 12        | 0.87%   |
| Dobrich             | 12        | 0.87%   |
| Razgrad             | 10        | 0.72%   |
| Gabrovo             | 10        | 0.72%   |
| Sliven              | 8         | 0.58%   |
| Kazanlak            | 8         | 0.58%   |
| Blagoevgrad         | 8         | 0.58%   |
| Asenovgrad          | 8         | 0.58%   |
| Vratsa              | 6         | 0.43%   |
| Vidin               | 6         | 0.43%   |
| Svilengrad          | 6         | 0.43%   |
| Sistov              | 6         | 0.43%   |
| Teteven             | 5         | 0.36%   |
| Silistra            | 5         | 0.36%   |
| Petrich             | 5         | 0.36%   |
| Kyustendil          | 5         | 0.36%   |
| Gorna Oryahovitsa   | 5         | 0.36%   |
| Botevgrad           | 5         | 0.36%   |
| Smolyan             | 4         | 0.29%   |
| Nesebar             | 4         | 0.29%   |
| Karlovo             | 4         | 0.29%   |
| Troyan Municipality | 3         | 0.22%   |
| Svoge               | 3         | 0.22%   |
| Lovech              | 3         | 0.22%   |
| Kardzhali           | 3         | 0.22%   |
| Dimitrovgrad        | 3         | 0.22%   |
| Chirpan             | 3         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 284       | 434    | 14.96%  |
| Seagate                     | 258       | 388    | 13.59%  |
| WDC                         | 242       | 367    | 12.74%  |
| Toshiba                     | 132       | 182    | 6.95%   |
| Kingston                    | 112       | 166    | 5.9%    |
| Hitachi                     | 88        | 117    | 4.63%   |
| Sandisk                     | 75        | 92     | 3.95%   |
| A-DATA Technology           | 65        | 88     | 3.42%   |
| Unknown                     | 58        | 76     | 3.05%   |
| Intel                       | 53        | 77     | 2.79%   |
| SK hynix                    | 46        | 63     | 2.42%   |
| HGST                        | 45        | 67     | 2.37%   |
| Micron Technology           | 44        | 51     | 2.32%   |
| Crucial                     | 35        | 52     | 1.84%   |
| SPCC                        | 31        | 39     | 1.63%   |
| Team                        | 25        | 26     | 1.32%   |
| KIOXIA                      | 20        | 21     | 1.05%   |
| Kingston Technology Company | 18        | 20     | 0.95%   |
| China                       | 18        | 22     | 0.95%   |
| Transcend                   | 16        | 18     | 0.84%   |
| Phison Electronics          | 16        | 23     | 0.84%   |
| KingSpec                    | 12        | 14     | 0.63%   |
| Phison                      | 10        | 12     | 0.53%   |
| Patriot                     | 10        | 12     | 0.53%   |
| Fujitsu                     | 10        | 13     | 0.53%   |
| Silicon Motion              | 9         | 12     | 0.47%   |
| Realtek Semiconductor       | 8         | 12     | 0.42%   |
| Apple                       | 8         | 10     | 0.42%   |
| Maxtor                      | 7         | 13     | 0.37%   |
| LITEON                      | 7         | 10     | 0.37%   |
| ADATA Technology            | 7         | 8      | 0.37%   |
| PNY                         | 6         | 7      | 0.32%   |
| JMicron Technology          | 6         | 9      | 0.32%   |
| XPG                         | 5         | 7      | 0.26%   |
| Intenso                     | 5         | 5      | 0.26%   |
| Hewlett-Packard             | 5         | 14     | 0.26%   |
| Verbatim                    | 4         | 4      | 0.21%   |
| TO Exter                    | 4         | 4      | 0.21%   |
| Teclast                     | 4         | 4      | 0.21%   |
| LITEONIT                    | 4         | 4      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 23        | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 20        | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB                       | 19        | 0.92%   |
| Seagate ST500DM002-1BD142 500GB                      | 18        | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 18        | 0.87%   |
| Kingston SA400S37120G 120GB SSD                      | 18        | 0.87%   |
| HGST HTS721010A9E630 1TB                             | 17        | 0.82%   |
| Samsung SSD 850 EVO 250GB                            | 16        | 0.78%   |
| Toshiba MQ01ABF050 500GB                             | 15        | 0.73%   |
| Toshiba MQ01ABD100 1TB                               | 15        | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB                       | 15        | 0.73%   |
| Samsung SSD 860 EVO 250GB                            | 15        | 0.73%   |
| Samsung SSD 860 EVO 500GB                            | 14        | 0.68%   |
| SPCC Solid State Disk 512GB                          | 13        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 13        | 0.63%   |
| Kingston SA400S37480G 480GB SSD                      | 13        | 0.63%   |
| Samsung NVMe SSD Drive 512GB                         | 12        | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 10        | 0.48%   |
| Unknown MMC Card  32GB                               | 10        | 0.48%   |
| Toshiba DT01ACA100 1TB                               | 10        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB                       | 10        | 0.48%   |
| Unknown MMC Card  64GB                               | 9         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                      | 9         | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                         | 9         | 0.44%   |
| HGST HTS541010A9E680 1TB                             | 9         | 0.44%   |
| Toshiba DT01ACA050 500GB                             | 8         | 0.39%   |
| Samsung SSD 850 PRO 256GB                            | 8         | 0.39%   |
| Kingston Company SNV2S2000G 2TB                      | 8         | 0.39%   |
| Hitachi HDP725050GLA360 500GB                        | 8         | 0.39%   |
| A-DATA SU650 240GB SSD                               | 8         | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 7         | 0.34%   |
| Toshiba MQ04ABF100 1TB                               | 7         | 0.34%   |
| Seagate ST9500325AS 500GB                            | 7         | 0.34%   |
| Seagate ST1000LM048-2E7172 1TB                       | 7         | 0.34%   |
| Seagate Expansion 1TB                                | 7         | 0.34%   |
| Samsung SSD 870 EVO 500GB                            | 7         | 0.34%   |
| Samsung SSD 850 EVO 500GB                            | 7         | 0.34%   |
| Samsung NVMe SSD Drive 500GB                         | 7         | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                     | 7         | 0.34%   |
| Intel SSDSC2CW120A3 120GB                            | 7         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 254       | 381    | 33.55%  |
| WDC                 | 211       | 316    | 27.87%  |
| Toshiba             | 104       | 142    | 13.74%  |
| Hitachi             | 88        | 117    | 11.62%  |
| HGST                | 45        | 67     | 5.94%   |
| Samsung Electronics | 12        | 16     | 1.59%   |
| Fujitsu             | 10        | 13     | 1.32%   |
| Maxtor              | 7         | 13     | 0.92%   |
| JMicron Technology  | 5         | 6      | 0.66%   |
| Unknown             | 4         | 6      | 0.53%   |
| TO Exter            | 4         | 4      | 0.53%   |
| Hewlett-Packard     | 4         | 14     | 0.53%   |
| ExcelStor           | 4         | 8      | 0.53%   |
| IBM/Hitachi         | 2         | 3      | 0.26%   |
| HGST HTS            | 1         | 1      | 0.13%   |
| ASMedia             | 1         | 1      | 0.13%   |
| Apple               | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 132       | 176    | 22.34%  |
| Kingston            | 82        | 107    | 13.87%  |
| A-DATA Technology   | 56        | 77     | 9.48%   |
| SanDisk             | 35        | 41     | 5.92%   |
| Crucial             | 30        | 45     | 5.08%   |
| SPCC                | 29        | 37     | 4.91%   |
| WDC                 | 23        | 33     | 3.89%   |
| Team                | 22        | 23     | 3.72%   |
| Intel               | 21        | 29     | 3.55%   |
| China               | 18        | 22     | 3.05%   |
| Transcend           | 14        | 16     | 2.37%   |
| Micron Technology   | 12        | 14     | 2.03%   |
| KingSpec            | 12        | 14     | 2.03%   |
| Toshiba             | 9         | 11     | 1.52%   |
| Patriot             | 9         | 11     | 1.52%   |
| LITEON              | 7         | 10     | 1.18%   |
| PNY                 | 6         | 7      | 1.02%   |
| Intenso             | 5         | 5      | 0.85%   |
| Apple               | 5         | 7      | 0.85%   |
| Verbatim            | 4         | 4      | 0.68%   |
| Teclast             | 4         | 4      | 0.68%   |
| LITEONIT            | 4         | 4      | 0.68%   |
| GOODRAM             | 4         | 4      | 0.68%   |
| AMD                 | 4         | 6      | 0.68%   |
| SK hynix            | 3         | 3      | 0.51%   |
| OCZ                 | 3         | 4      | 0.51%   |
| Lexar               | 3         | 3      | 0.51%   |
| Corsair             | 3         | 3      | 0.51%   |
| Seagate             | 2         | 3      | 0.34%   |
| Innodisk            | 2         | 2      | 0.34%   |
| Apacer              | 2         | 2      | 0.34%   |
| Unknown             | 2         | 2      | 0.34%   |
| XrayDisk            | 1         | 1      | 0.17%   |
| XPG                 | 1         | 1      | 0.17%   |
| Wibtek              | 1         | 2      | 0.17%   |
| VT                  | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |
| StoreJet            | 1         | 1      | 0.17%   |
| Origin              | 1         | 3      | 0.17%   |
| OCZ-VERTEX3         | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 657       | 1109   | 38.35%  |
| SSD     | 528       | 771    | 30.82%  |
| NVMe    | 466       | 722    | 27.2%   |
| MMC     | 50        | 62     | 2.92%   |
| Unknown | 12        | 17     | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 954       | 1825   | 62.68%  |
| NVMe | 465       | 719    | 30.55%  |
| SAS  | 53        | 75     | 3.48%   |
| MMC  | 50        | 62     | 3.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 734       | 1149   | 61.68%  |
| 0.51-1.0   | 353       | 552    | 29.66%  |
| 1.01-2.0   | 51        | 73     | 4.29%   |
| 3.01-4.0   | 25        | 49     | 2.1%    |
| 2.01-3.0   | 12        | 20     | 1.01%   |
| 4.01-10.0  | 10        | 18     | 0.84%   |
| 10.01-20.0 | 5         | 19     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 350       | 25.05%  |
| 251-500        | 324       | 23.19%  |
| 501-1000       | 230       | 16.46%  |
| 1001-2000      | 127       | 9.09%   |
| 1-20           | 111       | 7.95%   |
| 51-100         | 95        | 6.8%    |
| 21-50          | 52        | 3.72%   |
| More than 3000 | 47        | 3.36%   |
| Unknown        | 34        | 2.43%   |
| 2001-3000      | 27        | 1.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 536       | 35.85%  |
| 21-50          | 260       | 17.39%  |
| 101-250        | 198       | 13.24%  |
| 51-100         | 179       | 11.97%  |
| 251-500        | 122       | 8.16%   |
| 501-1000       | 97        | 6.49%   |
| 1001-2000      | 41        | 2.74%   |
| Unknown        | 34        | 2.27%   |
| More than 3000 | 16        | 1.07%   |
| 2001-3000      | 12        | 0.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                                       | 4         | 4      | 2.84%   |
| WDC WD6000HLHX-01JJPV0 600GB                                    | 3         | 5      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB                                 | 3         | 4      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 3      | 2.13%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 3         | 3      | 2.13%   |
| WDC WD5000LPVX-60V0TT0 500GB                                    | 2         | 2      | 1.42%   |
| WDC WD5000LPVX-55V0TT0 500GB                                    | 2         | 2      | 1.42%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2         | 6      | 1.42%   |
| WDC WD40PURX-64GVNY0 4TB                                        | 2         | 4      | 1.42%   |
| Toshiba MQ01ABF050 500GB                                        | 2         | 2      | 1.42%   |
| Toshiba MQ01ABD100 1TB                                          | 2         | 2      | 1.42%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 2         | 2      | 1.42%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 2      | 1.42%   |
| Kingston SA400S37480G 480GB SSD                                 | 2         | 2      | 1.42%   |
| KingSpec P3-128 128GB SSD                                       | 2         | 3      | 1.42%   |
| Intel SSDSC2CW120A3 120GB                                       | 2         | 2      | 1.42%   |
| Hitachi HDP725050GLA360 500GB                                   | 2         | 3      | 1.42%   |
| HGST HTS721010A9E630 1TB                                        | 2         | 2      | 1.42%   |
| China SSD 120GB                                                 | 2         | 2      | 1.42%   |
| A-DATA Technology SU900 256GB SSD                               | 2         | 2      | 1.42%   |
| A-DATA Technology SU650 120GB SSD                               | 2         | 2      | 1.42%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                  | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-75A0RT0 500GB                                    | 1         | 1      | 0.71%   |
| WDC WD5000AZLX-60K2TA0 500GB                                    | 1         | 1      | 0.71%   |
| WDC WD5000AADS-00S9B0 500GB                                     | 1         | 2      | 0.71%   |
| WDC WD5000AACS-00G8B1 500GB                                     | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-80A0RT0 320GB                                    | 1         | 1      | 0.71%   |
| WDC WD3200AAJS-07M0A0 320GB                                     | 1         | 2      | 0.71%   |
| WDC WD2500JS-00MHB0 250GB                                       | 1         | 1      | 0.71%   |
| WDC WD2500AAKX-753CA1 250GB                                     | 1         | 1      | 0.71%   |
| WDC WD1600BEVT-80A23T0 160GB                                    | 1         | 1      | 0.71%   |
| WDC WD15EARS-00S8B1 1TB                                         | 1         | 1      | 0.71%   |
| WDC WD10EFRX-68PJCN0 1TB                                        | 1         | 2      | 0.71%   |
| WDC WD10EARS-00MVWB0 1TB                                        | 1         | 1      | 0.71%   |
| WDC WD1003FZEX-00K3CA0 1TB                                      | 1         | 1      | 0.71%   |
| WDC WD Blue SA510 2.5 500GB                                     | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD050 500GB                                        | 1         | 1      | 0.71%   |
| Toshiba MK8052GSX 80GB                                          | 1         | 1      | 0.71%   |
| Toshiba MK3252GSX 320GB                                         | 1         | 1      | 0.71%   |
| Toshiba MK2552GSX 250GB                                         | 1         | 3      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 34     | 21.99%  |
| WDC                 | 26        | 37     | 18.44%  |
| Hitachi             | 14        | 16     | 9.93%   |
| Toshiba             | 13        | 15     | 9.22%   |
| A-DATA Technology   | 10        | 10     | 7.09%   |
| Samsung Electronics | 9         | 11     | 6.38%   |
| Intel               | 7         | 9      | 4.96%   |
| Kingston            | 5         | 5      | 3.55%   |
| SPCC                | 3         | 3      | 2.13%   |
| Maxtor              | 3         | 4      | 2.13%   |
| KingSpec            | 3         | 4      | 2.13%   |
| China               | 3         | 3      | 2.13%   |
| SK hynix            | 2         | 2      | 1.42%   |
| SanDisk             | 2         | 2      | 1.42%   |
| HGST                | 2         | 2      | 1.42%   |
| ExcelStor           | 2         | 3      | 1.42%   |
| T-FORCE             | 1         | 1      | 0.71%   |
| Phison              | 1         | 1      | 0.71%   |
| Patriot             | 1         | 1      | 0.71%   |
| OCZ                 | 1         | 2      | 0.71%   |
| Lenovo              | 1         | 1      | 0.71%   |
| Fujitsu             | 1         | 2      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 31        | 34     | 34.44%  |
| WDC       | 24        | 35     | 26.67%  |
| Hitachi   | 14        | 16     | 15.56%  |
| Toshiba   | 13        | 15     | 14.44%  |
| Maxtor    | 3         | 4      | 3.33%   |
| HGST      | 2         | 2      | 2.22%   |
| ExcelStor | 2         | 3      | 2.22%   |
| Fujitsu   | 1         | 2      | 1.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 87        | 111    | 64.44%  |
| SSD  | 38        | 46     | 28.15%  |
| NVMe | 10        | 11     | 7.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT3 752GB | 1         | 1      | 20%     |
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 20%     |
| WDC WD1600AAJS-00L7A0 160GB  | 1         | 1      | 20%     |
| Seagate ST9320325AS 320GB    | 1         | 1      | 20%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Seagate | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 767       | 1542   | 53.26%  |
| Works    | 540       | 966    | 37.5%   |
| Malfunc  | 128       | 168    | 8.89%   |
| Failed   | 5         | 5      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 891       | 52.97%  |
| AMD                              | 220       | 13.08%  |
| Samsung Electronics              | 166       | 9.87%   |
| SanDisk                          | 55        | 3.27%   |
| Kingston Technology Company      | 47        | 2.79%   |
| SK hynix                         | 43        | 2.56%   |
| Micron Technology                | 32        | 1.9%    |
| Phison Electronics               | 29        | 1.72%   |
| JMicron Technology               | 22        | 1.31%   |
| Nvidia                           | 21        | 1.25%   |
| KIOXIA                           | 21        | 1.25%   |
| ASMedia Technology               | 19        | 1.13%   |
| Toshiba America Info Systems     | 18        | 1.07%   |
| ADATA Technology                 | 17        | 1.01%   |
| Realtek Semiconductor            | 16        | 0.95%   |
| Silicon Motion                   | 13        | 0.77%   |
| Marvell Technology Group         | 13        | 0.77%   |
| Micron/Crucial Technology        | 6         | 0.36%   |
| Union Memory (Shenzhen)          | 5         | 0.3%    |
| Shenzhen Longsys Electronics     | 4         | 0.24%   |
| Lenovo                           | 3         | 0.18%   |
| Hewlett-Packard                  | 3         | 0.18%   |
| VIA Technologies                 | 2         | 0.12%   |
| Transcend                        | 2         | 0.12%   |
| Solid State Storage Technology   | 2         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.12%   |
| Apple                            | 2         | 0.12%   |
| Solidigm                         | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Seagate Technology               | 1         | 0.06%   |
| O2 Micro                         | 1         | 0.06%   |
| LSI Logic / Symbios Logic        | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| INNOGRIT                         | 1         | 0.06%   |
| Chelsio Communications           | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 137       | 7.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 79        | 4.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 73        | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 61        | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 53        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 45        | 2.31%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 38        | 1.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 38        | 1.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 37        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 34        | 1.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 29        | 1.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 28        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 26        | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25        | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25        | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 25        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24        | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 23        | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 23        | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21        | 1.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20        | 1.03%   |
| Intel SATA Controller [RAID Mode]                                                       | 19        | 0.98%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 19        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 18        | 0.92%   |
| AMD 500 Series Chipset SATA Controller                                                  | 18        | 0.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 17        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 17        | 0.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 17        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 15        | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 14        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 13        | 0.67%   |
| Intel SSD 660P Series                                                                   | 13        | 0.67%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 13        | 0.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 917       | 53.91%  |
| NVMe | 470       | 27.63%  |
| IDE  | 203       | 11.93%  |
| RAID | 106       | 6.23%   |
| SAS  | 4         | 0.24%   |
| SCSI | 1         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 986       | 75.32%  |
| AMD          | 318       | 24.29%  |
| ARM          | 4         | 0.31%   |
| CentaurHauls | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 13        | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 13        | 0.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 12        | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 11        | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 11        | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 10        | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 10        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 10        | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 10        | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 9         | 0.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 9         | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 8         | 0.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 8         | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 8         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 8         | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 8         | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 7         | 0.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 7         | 0.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 7         | 0.53%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 7         | 0.53%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 7         | 0.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 7         | 0.53%   |
| AMD Ryzen 5 5600X 6-Core Processor       | 7         | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 7         | 0.53%   |
| AMD Ryzen 5 1600 Six-Core Processor      | 7         | 0.53%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 6         | 0.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 6         | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 6         | 0.46%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 6         | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 6         | 0.46%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 6         | 0.46%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 6         | 0.46%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.46%   |
| Intel Celeron CPU N3050 @ 1.60GHz        | 6         | 0.46%   |
| Intel 12th Gen Core i5-1235U             | 6         | 0.46%   |
| AMD Ryzen 5 3600 6-Core Processor        | 6         | 0.46%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 6         | 0.46%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.38%   |
| Intel Pentium CPU G645 @ 2.90GHz         | 5         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 267       | 20.34%  |
| Intel Core i7           | 229       | 17.44%  |
| Other                   | 104       | 7.92%   |
| Intel Core i3           | 87        | 6.63%   |
| AMD Ryzen 5             | 73        | 5.56%   |
| AMD Ryzen 7             | 71        | 5.41%   |
| Intel Core 2 Duo        | 63        | 4.8%    |
| Intel Celeron           | 60        | 4.57%   |
| Intel Pentium           | 52        | 3.96%   |
| Intel Xeon              | 30        | 2.28%   |
| AMD Ryzen 3             | 20        | 1.52%   |
| AMD Ryzen 9             | 18        | 1.37%   |
| Intel Core 2 Quad       | 17        | 1.29%   |
| Intel Atom              | 17        | 1.29%   |
| Intel Pentium Dual-Core | 16        | 1.22%   |
| AMD Ryzen 7 PRO         | 13        | 0.99%   |
| AMD FX                  | 12        | 0.91%   |
| AMD Athlon 64 X2        | 12        | 0.91%   |
| Intel Pentium Dual      | 11        | 0.84%   |
| Intel Core i9           | 9         | 0.69%   |
| AMD Ryzen 5 PRO         | 9         | 0.69%   |
| Intel Pentium Silver    | 8         | 0.61%   |
| AMD Phenom II X4        | 8         | 0.61%   |
| AMD A8                  | 8         | 0.61%   |
| Intel Core 2            | 7         | 0.53%   |
| AMD Athlon II X2        | 7         | 0.53%   |
| AMD E1                  | 6         | 0.46%   |
| AMD A6                  | 6         | 0.46%   |
| AMD Athlon 64           | 5         | 0.38%   |
| AMD Athlon II X4        | 4         | 0.3%    |
| AMD A10                 | 4         | 0.3%    |
| Intel Pentium M         | 3         | 0.23%   |
| Intel Genuine           | 3         | 0.23%   |
| AMD Sempron             | 3         | 0.23%   |
| AMD E                   | 3         | 0.23%   |
| AMD Athlon              | 3         | 0.23%   |
| Intel Pentium Gold      | 2         | 0.15%   |
| Intel Core m3           | 2         | 0.15%   |
| Intel Core              | 2         | 0.15%   |
| Intel Celeron Dual-Core | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 515       | 39.19%  |
| 4       | 430       | 32.72%  |
| 6       | 136       | 10.35%  |
| 8       | 113       | 8.6%    |
| 1       | 33        | 2.51%   |
| 12      | 22        | 1.67%   |
| 10      | 18        | 1.37%   |
| 14      | 14        | 1.07%   |
| 3       | 12        | 0.91%   |
| 16      | 11        | 0.84%   |
| Unknown | 4         | 0.3%    |
| 24      | 2         | 0.15%   |
| 18      | 2         | 0.15%   |
| 40      | 1         | 0.08%   |
| 20      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1299      | 99.24%  |
| 2       | 7         | 0.53%   |
| Unknown | 2         | 0.15%   |
| 4       | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 842       | 64.08%  |
| 1       | 466       | 35.46%  |
| Unknown | 4         | 0.3%    |
| 8       | 1         | 0.08%   |
| 4       | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1276      | 96.89%  |
| Unknown        | 26        | 1.97%   |
| 32-bit         | 14        | 1.06%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 552       | 39.71%  |
| 0x206a7    | 70        | 5.04%   |
| 0x306a9    | 68        | 4.89%   |
| 0x306c3    | 51        | 3.67%   |
| 0x1067a    | 44        | 3.17%   |
| 0x906ea    | 27        | 1.94%   |
| 0x806ec    | 27        | 1.94%   |
| 0x506e3    | 25        | 1.8%    |
| 0x306d4    | 23        | 1.65%   |
| 0x906e9    | 20        | 1.44%   |
| 0x40651    | 20        | 1.44%   |
| 0x20655    | 20        | 1.44%   |
| 0x6fd      | 19        | 1.37%   |
| 0x406e3    | 19        | 1.37%   |
| 0x806ea    | 17        | 1.22%   |
| 0x806c1    | 16        | 1.15%   |
| 0x10676    | 15        | 1.08%   |
| 0x0a50000c | 13        | 0.94%   |
| 0x010000c8 | 13        | 0.94%   |
| 0x706a1    | 12        | 0.86%   |
| 0x506c9    | 12        | 0.86%   |
| 0x08108109 | 12        | 0.86%   |
| 0x08608103 | 11        | 0.79%   |
| 0x0a50000d | 10        | 0.72%   |
| 0x6fb      | 9         | 0.65%   |
| 0x806e9    | 8         | 0.58%   |
| 0xa0652    | 7         | 0.5%    |
| 0x406c3    | 7         | 0.5%    |
| 0x08600106 | 7         | 0.5%    |
| 0x08108102 | 7         | 0.5%    |
| 0x806eb    | 6         | 0.43%   |
| 0x6f6      | 6         | 0.43%   |
| 0x306f2    | 6         | 0.43%   |
| 0x0a404102 | 6         | 0.43%   |
| 0x08701021 | 6         | 0.43%   |
| 0x08600104 | 6         | 0.43%   |
| 0x0800820d | 6         | 0.43%   |
| 0x906a4    | 5         | 0.36%   |
| 0x706e5    | 5         | 0.36%   |
| 0x106c2    | 5         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 181       | 13.79%  |
| Haswell           | 121       | 9.22%   |
| IvyBridge         | 108       | 8.23%   |
| SandyBridge       | 98        | 7.46%   |
| Unknown           | 92        | 7.01%   |
| Penryn            | 80        | 6.09%   |
| Skylake           | 63        | 4.8%    |
| Zen 3             | 60        | 4.57%   |
| Core              | 45        | 3.43%   |
| Zen 2             | 40        | 3.05%   |
| Westmere          | 38        | 2.89%   |
| Zen+              | 36        | 2.74%   |
| TigerLake         | 33        | 2.51%   |
| Alderlake Hybrid  | 33        | 2.51%   |
| K10               | 32        | 2.44%   |
| Broadwell         | 30        | 2.28%   |
| Silvermont        | 27        | 2.06%   |
| CometLake         | 24        | 1.83%   |
| K8 Hammer         | 22        | 1.68%   |
| Zen               | 18        | 1.37%   |
| Goldmont plus     | 18        | 1.37%   |
| Piledriver        | 16        | 1.22%   |
| Icelake           | 16        | 1.22%   |
| Goldmont          | 16        | 1.22%   |
| Nehalem           | 10        | 0.76%   |
| Excavator         | 8         | 0.61%   |
| Bonnell           | 8         | 0.61%   |
| P6                | 6         | 0.46%   |
| Jaguar            | 6         | 0.46%   |
| Steamroller       | 5         | 0.38%   |
| Bobcat            | 5         | 0.38%   |
| Puma              | 4         | 0.3%    |
| NetBurst          | 3         | 0.23%   |
| K10 Llano         | 3         | 0.23%   |
| Bulldozer         | 3         | 0.23%   |
| Tremont           | 2         | 0.15%   |
| Meteorlake Hybrid | 1         | 0.08%   |
| K8 & K10 hybrid   | 1         | 0.08%   |
| Gracemont         | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 773       | 47.72%  |
| Nvidia                           | 452       | 27.9%   |
| AMD                              | 389       | 24.01%  |
| Matrox Electronics Systems       | 2         | 0.12%   |
| ASPEED Technology                | 2         | 0.12%   |
| VIA Technologies                 | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 4.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 68        | 4.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 1.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 1.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 1.68%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 27        | 1.62%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 26        | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 1.5%    |
| Intel HD Graphics 630                                                                    | 25        | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.44%   |
| Intel UHD Graphics 620                                                                   | 22        | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 1.32%   |
| Intel HD Graphics 530                                                                    | 20        | 1.2%    |
| AMD Lucienne                                                                             | 20        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 0.96%   |
| Intel HD Graphics 620                                                                    | 15        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.84%   |
| AMD Rembrandt [Radeon 680M]                                                              | 13        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 11        | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 0.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 0.66%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 11        | 0.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 11        | 0.66%   |
| AMD Barcelo                                                                              | 11        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10        | 0.6%    |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 9         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 493       | 37.15%  |
| 1 x AMD        | 294       | 22.16%  |
| Intel + Nvidia | 215       | 16.2%   |
| 1 x Nvidia     | 207       | 15.6%   |
| Intel + AMD    | 49        | 3.69%   |
| AMD + Nvidia   | 30        | 2.26%   |
| 2 x AMD        | 20        | 1.51%   |
| Other          | 5         | 0.38%   |
| 2 x Intel      | 5         | 0.38%   |
| 2 x Nvidia     | 3         | 0.23%   |
| 1 x Matrox     | 2         | 0.15%   |
| 1 x ASPEED     | 2         | 0.15%   |
| 1 x VIA        | 1         | 0.08%   |
| 1 x SiS        | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1029      | 76.68%  |
| Proprietary | 248       | 18.48%  |
| Unknown     | 65        | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 758       | 55.45%  |
| 1.01-2.0   | 170       | 12.44%  |
| 0.01-0.5   | 143       | 10.46%  |
| 3.01-4.0   | 94        | 6.88%   |
| 0.51-1.0   | 92        | 6.73%   |
| 7.01-8.0   | 54        | 3.95%   |
| 5.01-6.0   | 29        | 2.12%   |
| 8.01-16.0  | 15        | 1.1%    |
| 2.01-3.0   | 6         | 0.44%   |
| 16.01-24.0 | 6         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 196       | 13.86%  |
| AU Optronics            | 158       | 11.17%  |
| Samsung Electronics     | 134       | 9.48%   |
| BOE                     | 113       | 7.99%   |
| Chimei Innolux          | 112       | 7.92%   |
| Dell                    | 100       | 7.07%   |
| Goldstar                | 62        | 4.38%   |
| Philips                 | 56        | 3.96%   |
| Acer                    | 46        | 3.25%   |
| Hewlett-Packard         | 38        | 2.69%   |
| AOC                     | 37        | 2.62%   |
| Lenovo                  | 34        | 2.4%    |
| Ancor Communications    | 30        | 2.12%   |
| Chi Mei Optoelectronics | 25        | 1.77%   |
| BenQ                    | 24        | 1.7%    |
| Sharp                   | 16        | 1.13%   |
| PANDA                   | 15        | 1.06%   |
| Vestel Elektronik       | 12        | 0.85%   |
| LG Philips              | 12        | 0.85%   |
| Apple                   | 12        | 0.85%   |
| Fujitsu Siemens         | 11        | 0.78%   |
| Panasonic               | 10        | 0.71%   |
| Sony                    | 9         | 0.64%   |
| LG Electronics          | 9         | 0.64%   |
| MSI                     | 8         | 0.57%   |
| CSO                     | 8         | 0.57%   |
| ASUSTek Computer        | 8         | 0.57%   |
| Unknown                 | 6         | 0.42%   |
| NEC Computers           | 6         | 0.42%   |
| HannStar                | 6         | 0.42%   |
| Gigabyte Technology     | 6         | 0.42%   |
| Eizo                    | 6         | 0.42%   |
| ViewSonic               | 5         | 0.35%   |
| InfoVision              | 5         | 0.35%   |
| Valve                   | 4         | 0.28%   |
| Toshiba                 | 4         | 0.28%   |
| Iiyama                  | 4         | 0.28%   |
| CPT                     | 4         | 0.28%   |
| Vestel                  | 3         | 0.21%   |
| Belinea                 | 3         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 13        | 0.89%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 12        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.55%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.41%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 6         | 0.41%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 5         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 0.34%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.34%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                         | 5         | 0.34%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch    | 4         | 0.27%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 4         | 0.27%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 4         | 0.27%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 4         | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 4         | 0.27%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.27%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.27%   |
| Ancor Communications VW202 ACI20A2 1680x1050 433x271mm 20.1-inch         | 4         | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 3         | 0.21%   |
| Samsung Electronics SMXL2270HD SAM072B 1920x1080 476x268mm 21.5-inch     | 3         | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 610       | 44.79%  |
| 1366x768 (WXGA)    | 224       | 16.45%  |
| 3840x2160 (4K)     | 74        | 5.43%   |
| 2560x1440 (QHD)    | 61        | 4.48%   |
| 1280x1024 (SXGA)   | 56        | 4.11%   |
| 1600x900 (HD+)     | 46        | 3.38%   |
| 1920x1200 (WUXGA)  | 45        | 3.3%    |
| 1680x1050 (WSXGA+) | 45        | 3.3%    |
| 1280x800 (WXGA)    | 38        | 2.79%   |
| 1440x900 (WXGA+)   | 28        | 2.06%   |
| 2560x1600          | 19        | 1.4%    |
| Unknown            | 15        | 1.1%    |
| 3440x1440          | 12        | 0.88%   |
| 2560x1080          | 12        | 0.88%   |
| 1024x600           | 6         | 0.44%   |
| 800x1280           | 5         | 0.37%   |
| 3840x1080          | 5         | 0.37%   |
| 2880x1800          | 5         | 0.37%   |
| 3840x2400          | 4         | 0.29%   |
| 2288x1287          | 4         | 0.29%   |
| 1600x1200          | 4         | 0.29%   |
| 1360x768           | 4         | 0.29%   |
| 1024x768 (XGA)     | 4         | 0.29%   |
| 3840x1200          | 3         | 0.22%   |
| 2256x1504          | 3         | 0.22%   |
| 1400x1050          | 3         | 0.22%   |
| 1280x720 (HD)      | 3         | 0.22%   |
| 3200x1080          | 2         | 0.15%   |
| 3072x1920          | 2         | 0.15%   |
| 2160x1440          | 2         | 0.15%   |
| 1280x960           | 2         | 0.15%   |
| 800x480            | 1         | 0.07%   |
| 6784x2160          | 1         | 0.07%   |
| 6400x1080          | 1         | 0.07%   |
| 5120x1080          | 1         | 0.07%   |
| 4240x1440          | 1         | 0.07%   |
| 3600x1200          | 1         | 0.07%   |
| 3456x2160          | 1         | 0.07%   |
| 3200x2000          | 1         | 0.07%   |
| 3200x1800 (QHD+)   | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 451       | 31.76%  |
| 24      | 106       | 7.46%   |
| 14      | 91        | 6.41%   |
| 13      | 87        | 6.13%   |
| 17      | 83        | 5.85%   |
| 23      | 77        | 5.42%   |
| 27      | 73        | 5.14%   |
| 21      | 73        | 5.14%   |
| Unknown | 57        | 4.01%   |
| 19      | 44        | 3.1%    |
| 12      | 38        | 2.68%   |
| 22      | 28        | 1.97%   |
| 16      | 27        | 1.9%    |
| 84      | 25        | 1.76%   |
| 31      | 22        | 1.55%   |
| 20      | 20        | 1.41%   |
| 18      | 19        | 1.34%   |
| 34      | 18        | 1.27%   |
| 11      | 9         | 0.63%   |
| 54      | 7         | 0.49%   |
| 32      | 6         | 0.42%   |
| 25      | 6         | 0.42%   |
| 10      | 6         | 0.42%   |
| 65      | 5         | 0.35%   |
| 40      | 5         | 0.35%   |
| 72      | 4         | 0.28%   |
| 7       | 4         | 0.28%   |
| 142     | 3         | 0.21%   |
| 33      | 3         | 0.21%   |
| 29      | 3         | 0.21%   |
| 28      | 3         | 0.21%   |
| 26      | 3         | 0.21%   |
| 75      | 2         | 0.14%   |
| 35      | 2         | 0.14%   |
| 59      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 49      | 1         | 0.07%   |
| 46      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 630       | 44.81%  |
| 501-600        | 239       | 17%     |
| 401-500        | 159       | 11.31%  |
| 201-300        | 99        | 7.04%   |
| 351-400        | 89        | 6.33%   |
| Unknown        | 57        | 4.05%   |
| 601-700        | 40        | 2.84%   |
| 1501-2000      | 31        | 2.2%    |
| 701-800        | 27        | 1.92%   |
| 1001-1500      | 16        | 1.14%   |
| 801-900        | 8         | 0.57%   |
| 1-100          | 5         | 0.36%   |
| More than 2000 | 3         | 0.21%   |
| 101-200        | 2         | 0.14%   |
| 901-1000       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 922       | 71.98%  |
| 16/10   | 194       | 15.14%  |
| 5/4     | 56        | 4.37%   |
| Unknown | 50        | 3.9%    |
| 21/9    | 24        | 1.87%   |
| 4/3     | 15        | 1.17%   |
| 3/2     | 8         | 0.62%   |
| 1.00    | 4         | 0.31%   |
| 0.67    | 4         | 0.31%   |
| 6/5     | 2         | 0.16%   |
| 32/9    | 2         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 448       | 31.98%  |
| 201-250        | 210       | 14.99%  |
| 81-90          | 139       | 9.92%   |
| 151-200        | 89        | 6.35%   |
| 301-350        | 78        | 5.57%   |
| Unknown        | 57        | 4.07%   |
| 351-500        | 53        | 3.78%   |
| 251-300        | 48        | 3.43%   |
| More than 1000 | 46        | 3.28%   |
| 121-130        | 46        | 3.28%   |
| 141-150        | 44        | 3.14%   |
| 71-80          | 40        | 2.86%   |
| 61-70          | 35        | 2.5%    |
| 111-120        | 27        | 1.93%   |
| 51-60          | 9         | 0.64%   |
| 501-1000       | 9         | 0.64%   |
| 131-140        | 8         | 0.57%   |
| 1-40           | 7         | 0.5%    |
| 41-50          | 6         | 0.43%   |
| 91-100         | 2         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 444       | 32.48%  |
| 121-160       | 424       | 31.02%  |
| 101-120       | 311       | 22.75%  |
| 161-240       | 81        | 5.93%   |
| Unknown       | 57        | 4.17%   |
| More than 240 | 25        | 1.83%   |
| 1-50          | 25        | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1067      | 78.98%  |
| 2     | 189       | 13.99%  |
| 0     | 68        | 5.03%   |
| 3     | 25        | 1.85%   |
| 5     | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 699       | 34.47%  |
| Intel                                  | 646       | 31.85%  |
| Qualcomm Atheros                       | 198       | 9.76%   |
| Broadcom                               | 99        | 4.88%   |
| MediaTek                               | 55        | 2.71%   |
| TP-Link                                | 45        | 2.22%   |
| Broadcom Limited                       | 40        | 1.97%   |
| Ralink                                 | 28        | 1.38%   |
| Ralink Technology                      | 22        | 1.08%   |
| Nvidia                                 | 21        | 1.04%   |
| Marvell Technology Group               | 19        | 0.94%   |
| Qualcomm Atheros Communications        | 18        | 0.89%   |
| Ericsson Business Mobile Networks      | 15        | 0.74%   |
| Sierra Wireless                        | 13        | 0.64%   |
| Dell                                   | 9         | 0.44%   |
| D-Link                                 | 8         | 0.39%   |
| Xiaomi                                 | 6         | 0.3%    |
| Samsung Electronics                    | 6         | 0.3%    |
| Lenovo                                 | 5         | 0.25%   |
| Huawei Technologies                    | 5         | 0.25%   |
| Hewlett-Packard                        | 5         | 0.25%   |
| DisplayLink                            | 5         | 0.25%   |
| Sundance Technology Inc / IC Plus      | 4         | 0.2%    |
| Motorola PCS                           | 4         | 0.2%    |
| Microsoft                              | 4         | 0.2%    |
| ASIX Electronics                       | 4         | 0.2%    |
| Qualcomm                               | 3         | 0.15%   |
| Fibocom                                | 3         | 0.15%   |
| Aquantia                               | 3         | 0.15%   |
| AMD                                    | 3         | 0.15%   |
| Toshiba                                | 2         | 0.1%    |
| Suzhou Motorcomm Electronic Technology | 2         | 0.1%    |
| Microchip Technology                   | 2         | 0.1%    |
| Google                                 | 2         | 0.1%    |
| Davicom Semiconductor                  | 2         | 0.1%    |
| D-Link System                          | 2         | 0.1%    |
| Chelsio Communications                 | 2         | 0.1%    |
| ASUSTek Computer                       | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| VIA Technologies                       | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 449       | 19%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 91        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 66        | 2.79%   |
| Intel Wireless 8265 / 8275                                             | 37        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                    | 37        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 35        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 34        | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 33        | 1.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 32        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 27        | 1.14%   |
| Intel Wireless 7260                                                    | 27        | 1.14%   |
| Intel Wi-Fi 6 AX201                                                    | 27        | 1.14%   |
| Intel Wireless 7265                                                    | 26        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 24        | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 24        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 23        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 23        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                   | 22        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 22        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 20        | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 20        | 0.85%   |
| Intel Wireless 8260                                                    | 19        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 18        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 17        | 0.72%   |
| Intel I211 Gigabit Network Connection                                  | 17        | 0.72%   |
| Intel Wireless 3160                                                    | 16        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 16        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 16        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 15        | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                        | 15        | 0.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 15        | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                          | 15        | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 14        | 0.59%   |
| Intel Ethernet Controller I225-V                                       | 14        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 14        | 0.59%   |
| Intel 82579V Gigabit Network Connection                                | 14        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 13        | 0.55%   |
| Intel WiFi Link 5100                                                   | 13        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 481       | 46.07%  |
| Qualcomm Atheros                      | 146       | 13.98%  |
| Realtek Semiconductor                 | 144       | 13.79%  |
| Broadcom                              | 60        | 5.75%   |
| MediaTek                              | 47        | 4.5%    |
| TP-Link                               | 39        | 3.74%   |
| Ralink                                | 28        | 2.68%   |
| Ralink Technology                     | 22        | 2.11%   |
| Qualcomm Atheros Communications       | 18        | 1.72%   |
| Broadcom Limited                      | 16        | 1.53%   |
| Sierra Wireless                       | 13        | 1.25%   |
| Dell                                  | 6         | 0.57%   |
| D-Link                                | 5         | 0.48%   |
| Microsoft                             | 4         | 0.38%   |
| Qualcomm                              | 3         | 0.29%   |
| Fibocom                               | 3         | 0.29%   |
| ASUSTek Computer                      | 2         | 0.19%   |
| VIA Technologies                      | 1         | 0.1%    |
| Qualcomm Technologies                 | 1         | 0.1%    |
| NetGear                               | 1         | 0.1%    |
| Micro Star International              | 1         | 0.1%    |
| Hewlett-Packard                       | 1         | 0.1%    |
| Gemtek                                | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 37        | 3.52%   |
| Intel Wi-Fi 6 AX200                                            | 37        | 3.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 34        | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 33        | 3.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 2.57%   |
| Intel Wireless 7260                                            | 27        | 2.57%   |
| Intel Wi-Fi 6 AX201                                            | 27        | 2.57%   |
| Intel Wireless 7265                                            | 26        | 2.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 24        | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 23        | 2.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 2.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 20        | 1.9%    |
| Intel Wireless 8260                                            | 19        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 1.62%   |
| Intel Wireless 3160                                            | 16        | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 16        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 16        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 1.43%   |
| Qualcomm Atheros AR9271 802.11n                                | 15        | 1.43%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 15        | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 1.24%   |
| Intel WiFi Link 5100                                           | 13        | 1.24%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 12        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 1.14%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 11        | 1.05%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 10        | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 10        | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 10        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.86%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 9         | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 630       | 50.85%  |
| Intel                                  | 356       | 28.73%  |
| Qualcomm Atheros                       | 70        | 5.65%   |
| Broadcom                               | 47        | 3.79%   |
| Broadcom Limited                       | 24        | 1.94%   |
| Nvidia                                 | 21        | 1.69%   |
| Marvell Technology Group               | 19        | 1.53%   |
| MediaTek                               | 8         | 0.65%   |
| Xiaomi                                 | 6         | 0.48%   |
| TP-Link                                | 6         | 0.48%   |
| DisplayLink                            | 5         | 0.4%    |
| Sundance Technology Inc / IC Plus      | 4         | 0.32%   |
| Motorola PCS                           | 4         | 0.32%   |
| Lenovo                                 | 4         | 0.32%   |
| Huawei Technologies                    | 4         | 0.32%   |
| ASIX Electronics                       | 4         | 0.32%   |
| Samsung Electronics                    | 3         | 0.24%   |
| D-Link                                 | 3         | 0.24%   |
| Aquantia                               | 3         | 0.24%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.16%   |
| Davicom Semiconductor                  | 2         | 0.16%   |
| D-Link System                          | 2         | 0.16%   |
| Chelsio Communications                 | 2         | 0.16%   |
| Raspberry Pi                           | 1         | 0.08%   |
| NetXen Incorporated                    | 1         | 0.08%   |
| Microchip Technology                   | 1         | 0.08%   |
| JMicron Technology                     | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Google                                 | 1         | 0.08%   |
| Cypress Semiconductor                  | 1         | 0.08%   |
| Attansic Technology                    | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |
| 3Com                                   | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 449       | 35.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 91        | 7.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 66        | 5.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 32        | 2.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 2.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 24        | 1.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 22        | 1.73%   |
| Intel Ethernet Connection I217-LM                                      | 20        | 1.57%   |
| Intel I211 Gigabit Network Connection                                  | 17        | 1.34%   |
| Intel Ethernet Controller I225-V                                       | 14        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                   | 14        | 1.1%    |
| Intel 82579V Gigabit Network Connection                                | 14        | 1.1%    |
| Nvidia MCP61 Ethernet                                                  | 12        | 0.94%   |
| Intel Ethernet Connection I217-V                                       | 12        | 0.94%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.86%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.86%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.79%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 10        | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 9         | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 9         | 0.71%   |
| Realtek Killer E2600 GbE Controller                                    | 8         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 0.63%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 8         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 0.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 6         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5         | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 5         | 0.39%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                                  | 5         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1157      | 53.47%  |
| WiFi     | 967       | 44.69%  |
| Modem    | 40        | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 765       | 55.8%   |
| Ethernet | 605       | 44.13%  |
| Modem    | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 760       | 57.71%  |
| 1     | 511       | 38.8%   |
| 3     | 24        | 1.82%   |
| 0     | 14        | 1.06%   |
| 4     | 5         | 0.38%   |
| 7     | 2         | 0.15%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1258      | 94.23%  |
| Yes  | 77        | 5.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 351       | 43.23%  |
| Realtek Semiconductor           | 77        | 9.48%   |
| IMC Networks                    | 50        | 6.16%   |
| Qualcomm Atheros Communications | 49        | 6.03%   |
| Broadcom                        | 47        | 5.79%   |
| Cambridge Silicon Radio         | 43        | 5.3%    |
| Foxconn / Hon Hai               | 37        | 4.56%   |
| Lite-On Technology              | 32        | 3.94%   |
| Hewlett-Packard                 | 18        | 2.22%   |
| Toshiba                         | 17        | 2.09%   |
| Dell                            | 15        | 1.85%   |
| Apple                           | 15        | 1.85%   |
| Ralink                          | 12        | 1.48%   |
| MediaTek                        | 11        | 1.35%   |
| ASUSTek Computer                | 11        | 1.35%   |
| Integrated System Solution      | 7         | 0.86%   |
| Foxconn International           | 6         | 0.74%   |
| TP-Link                         | 3         | 0.37%   |
| USI                             | 2         | 0.25%   |
| Realtek                         | 2         | 0.25%   |
| Ralink Technology               | 2         | 0.25%   |
| Logitech                        | 1         | 0.12%   |
| HTC (High Tech Computer)        | 1         | 0.12%   |
| Belkin Components               | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |
| Unknown                         | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 123       | 15.15%  |
| Intel AX201 Bluetooth                                 | 78        | 9.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 57        | 7.02%   |
| Realtek Bluetooth Radio                               | 53        | 6.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 43        | 5.3%    |
| Intel AX200 Bluetooth                                 | 34        | 4.19%   |
| Qualcomm Atheros  Bluetooth Device                    | 28        | 3.45%   |
| IMC Networks Bluetooth Radio                          | 21        | 2.59%   |
| IMC Networks Wireless_Device                          | 18        | 2.22%   |
| Intel AX211 Bluetooth                                 | 15        | 1.85%   |
| Intel AX210 Bluetooth                                 | 14        | 1.72%   |
| Ralink RT3290 Bluetooth                               | 12        | 1.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 11        | 1.35%   |
| Realtek 802.11ac WLAN Adapter                         | 10        | 1.23%   |
| MediaTek Wireless_Device                              | 10        | 1.23%   |
| Lite-On Bluetooth Device                              | 10        | 1.23%   |
| IMC Networks Bluetooth Device                         | 10        | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 10        | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                     | 10        | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 9         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 9         | 1.11%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 9         | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                    | 9         | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 8         | 0.99%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 8         | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                      | 8         | 0.99%   |
| Toshiba Integrated Bluetooth HCI                      | 7         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                      | 7         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 7         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                           | 7         | 0.86%   |
| Apple Bluetooth Host Controller                       | 7         | 0.86%   |
| Lite-On Wireless_Device                               | 6         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module     | 6         | 0.74%   |
| Realtek  Bluetooth 4.2 Adapter                        | 5         | 0.62%   |
| Dell DW375 Bluetooth Module                           | 5         | 0.62%   |
| Realtek RTL8723B Bluetooth                            | 4         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 4         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                      | 4         | 0.49%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4         | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                      | 4         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 955       | 52.56%  |
| AMD                                          | 383       | 21.08%  |
| Nvidia                                       | 311       | 17.12%  |
| C-Media Electronics                          | 29        | 1.6%    |
| Creative Labs                                | 13        | 0.72%   |
| Razer USA                                    | 9         | 0.5%    |
| Logitech                                     | 9         | 0.5%    |
| Texas Instruments                            | 8         | 0.44%   |
| GN Netcom                                    | 8         | 0.44%   |
| Trust                                        | 7         | 0.39%   |
| Plantronics                                  | 7         | 0.39%   |
| Lenovo                                       | 7         | 0.39%   |
| Creative Technology                          | 6         | 0.33%   |
| JMTek                                        | 5         | 0.28%   |
| ASUSTek Computer                             | 5         | 0.28%   |
| Generalplus Technology                       | 4         | 0.22%   |
| VIA Technologies                             | 3         | 0.17%   |
| Tenx Technology                              | 3         | 0.17%   |
| Sony                                         | 3         | 0.17%   |
| Realtek Semiconductor                        | 3         | 0.17%   |
| Micro Star International                     | 3         | 0.17%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.11%   |
| Hewlett-Packard                              | 2         | 0.11%   |
| Dell                                         | 2         | 0.11%   |
| Corsair                                      | 2         | 0.11%   |
| BEHRINGER International                      | 2         | 0.11%   |
| Apple                                        | 2         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| ZOOM                                         | 1         | 0.06%   |
| Universal Audio                              | 1         | 0.06%   |
| SteelSeries ApS                              | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.06%   |
| Samson Technologies                          | 1         | 0.06%   |
| Roland                                       | 1         | 0.06%   |
| RODE Microphones                             | 1         | 0.06%   |
| Ploytec                                      | 1         | 0.06%   |
| OPPO Electronics                             | 1         | 0.06%   |
| No brand                                     | 1         | 0.06%   |
| Native Instruments                           | 1         | 0.06%   |
| NAD Electronics                              | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 148       | 6.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 97        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 97        | 4.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71        | 3.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 70        | 3.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 69        | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 62        | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 62        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 47        | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 44        | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 39        | 1.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37        | 1.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 34        | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 33        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 32        | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 31        | 1.42%   |
| Intel 8 Series HD Audio Controller                                         | 31        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 1.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30        | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 30        | 1.37%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 29        | 1.33%   |
| AMD FCH Azalia Controller                                                  | 28        | 1.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 27        | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27        | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 26        | 1.19%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 24        | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 20        | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 19        | 0.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 19        | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 17        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 17        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 16        | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 16        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 177       | 20.18%  |
| SK hynix                                | 150       | 17.1%   |
| Kingston                                | 134       | 15.28%  |
| Micron Technology                       | 93        | 10.6%   |
| Unknown                                 | 75        | 8.55%   |
| Corsair                                 | 45        | 5.13%   |
| A-DATA Technology                       | 44        | 5.02%   |
| Ramaxel Technology                      | 26        | 2.96%   |
| Crucial                                 | 22        | 2.51%   |
| Team                                    | 17        | 1.94%   |
| Nanya Technology                        | 15        | 1.71%   |
| Transcend                               | 12        | 1.37%   |
| G.Skill                                 | 12        | 1.37%   |
| Elpida                                  | 12        | 1.37%   |
| Apacer                                  | 8         | 0.91%   |
| Unknown                                 | 8         | 0.91%   |
| Silicon Power                           | 4         | 0.46%   |
| Silicon Power Computer & Communications | 3         | 0.34%   |
| GOODRAM                                 | 3         | 0.34%   |
| Unknown (ABCD)                          | 2         | 0.23%   |
| pqi                                     | 2         | 0.23%   |
| Atermiter                               | 2         | 0.23%   |
| ASint Technology                        | 2         | 0.23%   |
| Unifosa                                 | 1         | 0.11%   |
| Thermaltake                             | 1         | 0.11%   |
| Qimonda                                 | 1         | 0.11%   |
| Patriot                                 | 1         | 0.11%   |
| Neo Forza                               | 1         | 0.11%   |
| HBS                                     | 1         | 0.11%   |
| fef5                                    | 1         | 0.11%   |
| CSX                                     | 1         | 0.11%   |
| A Force                                 | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 11        | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 9         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s      | 9         | 0.94%   |
| Unknown                                                   | 8         | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 7         | 0.73%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 7         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 6         | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 6         | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 6         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 6         | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 6         | 0.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 6         | 0.63%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                | 6         | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 5         | 0.52%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 5         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 5         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 5         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 5         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 5         | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 5         | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 5         | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s     | 5         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 5         | 0.52%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 5         | 0.52%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s     | 4         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 4         | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 0.42%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 4         | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 0.42%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 0.42%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s   | 4         | 0.42%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 4         | 0.42%   |
| Unknown RAM Module 4GB DIMM 400MT/s                       | 3         | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 3         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 3         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 3         | 0.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 3         | 0.31%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 3         | 0.31%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 3         | 0.31%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 325       | 44.64%  |
| DDR3    | 253       | 34.75%  |
| DDR2    | 32        | 4.4%    |
| DDR5    | 30        | 4.12%   |
| SDRAM   | 24        | 3.3%    |
| Unknown | 22        | 3.02%   |
| LPDDR5  | 13        | 1.79%   |
| LPDDR4  | 11        | 1.51%   |
| DDR     | 7         | 0.96%   |
| LPDDR3  | 6         | 0.82%   |
| DRAM    | 5         | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 444       | 62.01%  |
| DIMM         | 240       | 33.52%  |
| Row Of Chips | 23        | 3.21%   |
| Chip         | 4         | 0.56%   |
| RIMM         | 2         | 0.28%   |
| FB-DIMM      | 2         | 0.28%   |
| Unknown      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 283       | 35.38%  |
| 4096    | 211       | 26.38%  |
| 16384   | 133       | 16.63%  |
| 2048    | 98        | 12.25%  |
| 32768   | 39        | 4.88%   |
| 1024    | 29        | 3.63%   |
| 512     | 4         | 0.5%    |
| 49152   | 1         | 0.13%   |
| 256     | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 159       | 19.92%  |
| 3200    | 133       | 16.67%  |
| 2667    | 110       | 13.78%  |
| 1333    | 55        | 6.89%   |
| 2400    | 45        | 5.64%   |
| 1334    | 33        | 4.14%   |
| 2133    | 24        | 3.01%   |
| 3600    | 20        | 2.51%   |
| 667     | 19        | 2.38%   |
| 800     | 18        | 2.26%   |
| Unknown | 18        | 2.26%   |
| 5600    | 15        | 1.88%   |
| 4800    | 12        | 1.5%    |
| 1867    | 10        | 1.25%   |
| 1067    | 10        | 1.25%   |
| 6400    | 9         | 1.13%   |
| 1066    | 8         | 1%      |
| 3266    | 7         | 0.88%   |
| 3466    | 6         | 0.75%   |
| 2048    | 6         | 0.75%   |
| 4199    | 5         | 0.63%   |
| 3800    | 5         | 0.63%   |
| 2666    | 5         | 0.63%   |
| 3000    | 4         | 0.5%    |
| 1866    | 4         | 0.5%    |
| 1800    | 4         | 0.5%    |
| 400     | 4         | 0.5%    |
| 333     | 4         | 0.5%    |
| 7500    | 3         | 0.38%   |
| 6000    | 3         | 0.38%   |
| 4266    | 3         | 0.38%   |
| 3733    | 3         | 0.38%   |
| 2933    | 3         | 0.38%   |
| 4267    | 2         | 0.25%   |
| 3400    | 2         | 0.25%   |
| 3333    | 2         | 0.25%   |
| 2800    | 2         | 0.25%   |
| 2200    | 2         | 0.25%   |
| 975     | 2         | 0.25%   |
| 533     | 2         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 25%     |
| Samsung Electronics | 4         | 14.29%  |
| Brother Industries  | 4         | 14.29%  |
| Xerox               | 3         | 10.71%  |
| Canon               | 3         | 10.71%  |
| Seiko Epson         | 2         | 7.14%   |
| STMicroelectronics  | 1         | 3.57%   |
| Prolific Technology | 1         | 3.57%   |
| Kyocera             | 1         | 3.57%   |
| Citizen             | 1         | 3.57%   |
| ATEN International  | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 2         | 7.14%   |
| Xerox Phaser 3140 and 3155                                | 1         | 3.57%   |
| Xerox Phaser 3020                                         | 1         | 3.57%   |
| Xerox Phaser 3010                                         | 1         | 3.57%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.57%   |
| Seiko Epson L3150 Series                                  | 1         | 3.57%   |
| Seiko Epson ET-2820 Series                                | 1         | 3.57%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 3.57%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.57%   |
| Samsung M332x 382x 402x Series                            | 1         | 3.57%   |
| Samsung M267x 287x Series                                 | 1         | 3.57%   |
| Prolific PL2305 Parallel Port                             | 1         | 3.57%   |
| Kyocera ECOSYS P2040dn                                    | 1         | 3.57%   |
| HP LaserJet Professional P1566                            | 1         | 3.57%   |
| HP LaserJet P1102                                         | 1         | 3.57%   |
| HP LaserJet 4350                                          | 1         | 3.57%   |
| HP LaserJet 1018                                          | 1         | 3.57%   |
| HP DeskJet 4530 series                                    | 1         | 3.57%   |
| Citizen Barcode Printer                                   | 1         | 3.57%   |
| Canon PIXMA MX370 Series                                  | 1         | 3.57%   |
| Canon PIXMA MP240                                         | 1         | 3.57%   |
| Canon MF3200 series                                       | 1         | 3.57%   |
| Brother Printer                                           | 1         | 3.57%   |
| Brother MFC-B7715DW series                                | 1         | 3.57%   |
| Brother DCP-T300                                          | 1         | 3.57%   |
| Brother DCP-7055 scanner/printer                          | 1         | 3.57%   |
| ATEN International UC-1284B Printer Port                  | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Mustek Systems  | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22        | 1         | 20%     |
| HP Scanjet G2710                   | 1         | 20%     |
| HP ScanJet 3400cse                 | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 193       | 23.95%  |
| IMC Networks                           | 90        | 11.17%  |
| Microdia                               | 70        | 8.68%   |
| Bison Electronics                      | 60        | 7.44%   |
| Realtek Semiconductor                  | 59        | 7.32%   |
| Quanta                                 | 50        | 6.2%    |
| Sunplus Innovation Technology          | 45        | 5.58%   |
| Syntek                                 | 23        | 2.85%   |
| Suyin                                  | 22        | 2.73%   |
| Logitech                               | 21        | 2.61%   |
| Luxvisions Innotech Limited            | 20        | 2.48%   |
| Lite-On Technology                     | 20        | 2.48%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 2.23%   |
| Apple                                  | 13        | 1.61%   |
| Acer                                   | 12        | 1.49%   |
| Z-Star Microelectronics                | 11        | 1.36%   |
| Alcor Micro                            | 9         | 1.12%   |
| Sonix Technology                       | 7         | 0.87%   |
| Microsoft                              | 7         | 0.87%   |
| Silicon Motion                         | 6         | 0.74%   |
| Lenovo                                 | 5         | 0.62%   |
| Samsung Electronics                    | 4         | 0.5%    |
| Ricoh                                  | 3         | 0.37%   |
| Generalplus Technology                 | 3         | 0.37%   |
| Creative Technology                    | 3         | 0.37%   |
| Unknown                                | 2         | 0.25%   |
| ShineTech                              | 2         | 0.25%   |
| Primax Electronics                     | 2         | 0.25%   |
| kingcome                               | 2         | 0.25%   |
| Importek                               | 2         | 0.25%   |
| Hewlett-Packard                        | 2         | 0.25%   |
| Aveo Technology                        | 2         | 0.25%   |
| Alpha Imaging Technology               | 2         | 0.25%   |
| ALi                                    | 2         | 0.25%   |
| Xiongmai                               | 1         | 0.12%   |
| Tobii Technology AB                    | 1         | 0.12%   |
| Sunplus Technology                     | 1         | 0.12%   |
| Razer USA                              | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 44        | 5.46%   |
| IMC Networks Integrated Camera                       | 30        | 3.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 24        | 2.98%   |
| Microdia Integrated_Webcam_HD                        | 21        | 2.61%   |
| Bison Integrated Camera                              | 18        | 2.23%   |
| Realtek Integrated_Webcam_HD                         | 16        | 1.99%   |
| Syntek Integrated Camera                             | 15        | 1.86%   |
| Sunplus Integrated_Webcam_HD                         | 15        | 1.86%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 15        | 1.86%   |
| Chicony HD Webcam                                    | 15        | 1.86%   |
| Quanta HP HD Camera                                  | 13        | 1.61%   |
| Chicony TOSHIBA Web Camera - HD                      | 10        | 1.24%   |
| Bison SunplusIT Integrated Camera                    | 9         | 1.12%   |
| Bison HD Webcam                                      | 9         | 1.12%   |
| Realtek Lenovo EasyCamera                            | 8         | 0.99%   |
| Lite-On Integrated Camera                            | 8         | 0.99%   |
| Quanta HD User Facing                                | 7         | 0.87%   |
| Quanta ACER HD User Facing                           | 7         | 0.87%   |
| Microdia Integrated Webcam                           | 7         | 0.87%   |
| Chicony USB 2.0 Camera                               | 7         | 0.87%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 7         | 0.87%   |
| Microdia Camera                                      | 6         | 0.74%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 6         | 0.74%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 6         | 0.74%   |
| Logitech Webcam C270                                 | 6         | 0.74%   |
| Chicony HP HD Camera                                 | 6         | 0.74%   |
| Bison Lenovo EasyCamera                              | 6         | 0.74%   |
| Z-Star A4 TECH HD PC Camera                          | 5         | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 5         | 0.62%   |
| Quanta HD Webcam                                     | 5         | 0.62%   |
| Lite-On HP HD Webcam                                 | 5         | 0.62%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 5         | 0.62%   |
| Chicony Lenovo EasyCamera                            | 5         | 0.62%   |
| Chicony Integrated Camera [ThinkPad]                 | 5         | 0.62%   |
| Chicony HP Truevision HD                             | 5         | 0.62%   |
| Chicony HP HD Webcam                                 | 5         | 0.62%   |
| Chicony HD WebCam (Asus N-series)                    | 5         | 0.62%   |
| Chicony HD User Facing                               | 5         | 0.62%   |
| Sunplus Laptop Integrated Webcam HD                  | 4         | 0.5%    |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 49        | 35%     |
| Synaptics                          | 47        | 33.57%  |
| AuthenTec                          | 15        | 10.71%  |
| Shenzhen Goodix Technology         | 9         | 6.43%   |
| Elan Microelectronics              | 7         | 5%      |
| Upek                               | 6         | 4.29%   |
| LighTuning Technology              | 4         | 2.86%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.43%   |
| STMicroelectronics                 | 1         | 0.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 8.57%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 7.14%   |
| AuthenTec AES2810                                                          | 8         | 5.71%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 4.29%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 3.57%   |
| Elan ELAN:ARM-M4                                                           | 5         | 3.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.86%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.86%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.43%   |
| Validity Sensors VFS491                                                    | 2         | 1.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.43%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.43%   |
| Synaptics WBDI                                                             | 2         | 1.43%   |
| Synaptics  WBDI                                                            | 2         | 1.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.43%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.43%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.43%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 1.43%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.43%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.43%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.71%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.71%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.71%   |
| Synaptics TouchPad                                                         | 1         | 0.71%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.71%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.71%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.71%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 0.71%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.71%   |
| AuthenTec AES1600                                                          | 1         | 0.71%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 36        | 36%     |
| Broadcom              | 34        | 34%     |
| Upek                  | 9         | 9%      |
| O2 Micro              | 6         | 6%      |
| Lenovo                | 5         | 5%      |
| Advanced Card Systems | 5         | 5%      |
| SCM Microsystems      | 2         | 2%      |
| OmniKey               | 2         | 2%      |
| Clay Logic            | 1         | 1%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 35.64%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 12.87%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 8.91%   |
| Broadcom 5880                                                                | 8         | 7.92%   |
| Broadcom 58200                                                               | 8         | 7.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 5.94%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.95%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 4.95%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.98%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.98%   |
| Advanced Card Systems ACR39U                                                 | 2         | 1.98%   |
| Advanced Card Systems ACR122U                                                | 2         | 1.98%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.99%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.99%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.99%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 905       | 66.54%  |
| 1     | 357       | 26.25%  |
| 2     | 88        | 6.47%   |
| 3     | 6         | 0.44%   |
| 4     | 2         | 0.15%   |
| 7     | 1         | 0.07%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 139       | 26.03%  |
| Graphics card            | 134       | 25.09%  |
| Chipcard                 | 82        | 15.36%  |
| Net/wireless             | 55        | 10.3%   |
| Multimedia controller    | 25        | 4.68%   |
| Bluetooth                | 22        | 4.12%   |
| Camera                   | 15        | 2.81%   |
| Unassigned class         | 12        | 2.25%   |
| Communication controller | 12        | 2.25%   |
| Storage                  | 10        | 1.87%   |
| Net/ethernet             | 7         | 1.31%   |
| Sound                    | 6         | 1.12%   |
| Card reader              | 6         | 1.12%   |
| Firewire controller      | 3         | 0.56%   |
| Network                  | 2         | 0.37%   |
| Modem                    | 2         | 0.37%   |
| Storage/ata              | 1         | 0.19%   |
| Flash memory             | 1         | 0.19%   |

