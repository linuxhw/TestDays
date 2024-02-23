Linux in Austria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Austria/Desktop/README.md) and [notebooks](/Location/Austria/Notebook/README.md).

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

Total: 3198

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire VN7-592G             | Notebook    | [95f618bdeb](https://linux-hardware.org/?probe=95f618bdeb) | Feb 02, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [97d6952c52](https://linux-hardware.org/?probe=97d6952c52) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cb15afccd0](https://linux-hardware.org/?probe=cb15afccd0) | Feb 02, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c62ec1a167](https://linux-hardware.org/?probe=c62ec1a167) | Jan 31, 2024 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0b511ae973](https://linux-hardware.org/?probe=0b511ae973) | Jan 30, 2024 |
| Medion        | B250H4-EM                   | Desktop     | [418b44d0a2](https://linux-hardware.org/?probe=418b44d0a2) | Jan 29, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [b2a4068ec1](https://linux-hardware.org/?probe=b2a4068ec1) | Jan 29, 2024 |
| Acer          | Aspire A114-31              | Notebook    | [9c767147fc](https://linux-hardware.org/?probe=9c767147fc) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [66d62ae7ed](https://linux-hardware.org/?probe=66d62ae7ed) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [9684aca764](https://linux-hardware.org/?probe=9684aca764) | Jan 29, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dda9e159b9](https://linux-hardware.org/?probe=dda9e159b9) | Jan 29, 2024 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [dcc6332a8e](https://linux-hardware.org/?probe=dcc6332a8e) | Jan 29, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [5f28b98de6](https://linux-hardware.org/?probe=5f28b98de6) | Jan 27, 2024 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [94257ca4de](https://linux-hardware.org/?probe=94257ca4de) | Jan 27, 2024 |
| Quanta        | S2B-MB 31S2BMB0040          | Server      | [845035a51b](https://linux-hardware.org/?probe=845035a51b) | Jan 27, 2024 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [b1abb90a3f](https://linux-hardware.org/?probe=b1abb90a3f) | Jan 25, 2024 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [ddf5524f10](https://linux-hardware.org/?probe=ddf5524f10) | Jan 25, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [89d4e508fa](https://linux-hardware.org/?probe=89d4e508fa) | Jan 25, 2024 |
| Hampoo        | Cherry Trail CR             | Notebook    | [1c0466fe53](https://linux-hardware.org/?probe=1c0466fe53) | Jan 25, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [356b235b8b](https://linux-hardware.org/?probe=356b235b8b) | Jan 24, 2024 |
| BESSTAR Te... | VB9                         | All in one  | [864cbd6a4c](https://linux-hardware.org/?probe=864cbd6a4c) | Jan 24, 2024 |
| MSI           | 880GM-E41                   | Desktop     | [a037ec8a1e](https://linux-hardware.org/?probe=a037ec8a1e) | Jan 23, 2024 |
| Quanta        | S2B-MB 31S2BMB0040          | Server      | [c83ba710f9](https://linux-hardware.org/?probe=c83ba710f9) | Jan 23, 2024 |
| Acer          | Aspire A114-31              | Notebook    | [f08742602c](https://linux-hardware.org/?probe=f08742602c) | Jan 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [09cb74358d](https://linux-hardware.org/?probe=09cb74358d) | Jan 23, 2024 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [b63d070fe7](https://linux-hardware.org/?probe=b63d070fe7) | Jan 22, 2024 |
| Dell          | Latitude E7440              | Notebook    | [4e05575433](https://linux-hardware.org/?probe=4e05575433) | Jan 22, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [3055120492](https://linux-hardware.org/?probe=3055120492) | Jan 22, 2024 |
| Dell          | Latitude 5490               | Notebook    | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [75f120a935](https://linux-hardware.org/?probe=75f120a935) | Jan 21, 2024 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [3224331d5e](https://linux-hardware.org/?probe=3224331d5e) | Jan 21, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [a06ba088e5](https://linux-hardware.org/?probe=a06ba088e5) | Jan 21, 2024 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [93339e731d](https://linux-hardware.org/?probe=93339e731d) | Jan 20, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [aa40e37f96](https://linux-hardware.org/?probe=aa40e37f96) | Jan 19, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [146eb01239](https://linux-hardware.org/?probe=146eb01239) | Jan 19, 2024 |
| ASRock        | N100DC-ITX                  | Desktop     | [dbca9c4ba2](https://linux-hardware.org/?probe=dbca9c4ba2) | Jan 19, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [5c18e1a4bc](https://linux-hardware.org/?probe=5c18e1a4bc) | Jan 18, 2024 |
| Acer          | Aspire A515-44G             | Notebook    | [6d540c596b](https://linux-hardware.org/?probe=6d540c596b) | Jan 17, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a5bd71f259](https://linux-hardware.org/?probe=a5bd71f259) | Jan 17, 2024 |
| MSI           | PRO Z690-A                  | Desktop     | [57e5890900](https://linux-hardware.org/?probe=57e5890900) | Jan 15, 2024 |
| Fujitsu       | LIFEBOOK U7613              | Notebook    | [9e38b7368d](https://linux-hardware.org/?probe=9e38b7368d) | Jan 14, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [35dd663593](https://linux-hardware.org/?probe=35dd663593) | Jan 14, 2024 |
| Microsoft     | Surface Go 3                | Tablet      | [4940f95cf9](https://linux-hardware.org/?probe=4940f95cf9) | Jan 13, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [62295225a7](https://linux-hardware.org/?probe=62295225a7) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [1b25ee0779](https://linux-hardware.org/?probe=1b25ee0779) | Jan 13, 2024 |
| SGIN          | M15                         | Notebook    | [022c34815c](https://linux-hardware.org/?probe=022c34815c) | Jan 12, 2024 |
| HP            | 8715                        | Mini pc     | [a7372e4bbc](https://linux-hardware.org/?probe=a7372e4bbc) | Jan 12, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [4ed2b7527c](https://linux-hardware.org/?probe=4ed2b7527c) | Jan 11, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [e12995730c](https://linux-hardware.org/?probe=e12995730c) | Jan 11, 2024 |
| HP            | 806A                        | Desktop     | [ab302e2dd9](https://linux-hardware.org/?probe=ab302e2dd9) | Jan 11, 2024 |
| HP            | 8715                        | Mini pc     | [912c2d5843](https://linux-hardware.org/?probe=912c2d5843) | Jan 11, 2024 |
| HP            | 8715                        | Mini pc     | [eb1b7c94e2](https://linux-hardware.org/?probe=eb1b7c94e2) | Jan 11, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2e480c8e36](https://linux-hardware.org/?probe=2e480c8e36) | Jan 11, 2024 |
| Lenovo        | ThinkPad W530 24474LG       | Notebook    | [7c1349e97d](https://linux-hardware.org/?probe=7c1349e97d) | Jan 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [3462a5ad9f](https://linux-hardware.org/?probe=3462a5ad9f) | Jan 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [eac99b5d0a](https://linux-hardware.org/?probe=eac99b5d0a) | Jan 09, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [7194fe43ed](https://linux-hardware.org/?probe=7194fe43ed) | Jan 09, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| SGIN          | M15                         | Notebook    | [b0b7267ad7](https://linux-hardware.org/?probe=b0b7267ad7) | Jan 08, 2024 |
| Valve         | Galileo                     | Notebook    | [e71ef9c36d](https://linux-hardware.org/?probe=e71ef9c36d) | Jan 07, 2024 |
| ASUSTek       | X75VC                       | Notebook    | [348451dd8f](https://linux-hardware.org/?probe=348451dd8f) | Jan 06, 2024 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [6e0b491486](https://linux-hardware.org/?probe=6e0b491486) | Jan 05, 2024 |
| Notebook      | P7xxTM1                     | Notebook    | [9ed3be2a69](https://linux-hardware.org/?probe=9ed3be2a69) | Jan 04, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [42e67a91b0](https://linux-hardware.org/?probe=42e67a91b0) | Jan 04, 2024 |
| Fujitsu       | LIFEBOOK U7413              | Notebook    | [b709a3069c](https://linux-hardware.org/?probe=b709a3069c) | Jan 03, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [00913517e5](https://linux-hardware.org/?probe=00913517e5) | Jan 02, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2cf15e0bf0](https://linux-hardware.org/?probe=2cf15e0bf0) | Jan 02, 2024 |
| Dell          | Latitude 5540               | Notebook    | [96e1aad010](https://linux-hardware.org/?probe=96e1aad010) | Jan 02, 2024 |
| ASUSTek       | X75VC                       | Notebook    | [6e3608409f](https://linux-hardware.org/?probe=6e3608409f) | Jan 02, 2024 |
| ASUSTek       | X75VC                       | Notebook    | [c80297163a](https://linux-hardware.org/?probe=c80297163a) | Jan 02, 2024 |
| Medion        | E11202                      | Notebook    | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| ASUSTek       | X75VC                       | Notebook    | [cb47b15eb9](https://linux-hardware.org/?probe=cb47b15eb9) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| MSI           | 880GM-E41                   | Desktop     | [caf8e2f533](https://linux-hardware.org/?probe=caf8e2f533) | Dec 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [c0587a6f3f](https://linux-hardware.org/?probe=c0587a6f3f) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [92906e6c95](https://linux-hardware.org/?probe=92906e6c95) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [e2ebd9354f](https://linux-hardware.org/?probe=e2ebd9354f) | Dec 31, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [fce85a876d](https://linux-hardware.org/?probe=fce85a876d) | Dec 31, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [26371b17d1](https://linux-hardware.org/?probe=26371b17d1) | Dec 31, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [9883edd543](https://linux-hardware.org/?probe=9883edd543) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3b6d015d5a](https://linux-hardware.org/?probe=3b6d015d5a) | Dec 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [fb4b958ae6](https://linux-hardware.org/?probe=fb4b958ae6) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [ab4628dffe](https://linux-hardware.org/?probe=ab4628dffe) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [9a7ee6f89e](https://linux-hardware.org/?probe=9a7ee6f89e) | Dec 29, 2023 |
| Medion        | E11202                      | Notebook    | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| Medion        | E7220                       | Notebook    | [8a10d2f8d1](https://linux-hardware.org/?probe=8a10d2f8d1) | Dec 28, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [d230832e06](https://linux-hardware.org/?probe=d230832e06) | Dec 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d8e2dd481d](https://linux-hardware.org/?probe=d8e2dd481d) | Dec 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [eaa0ff8b0c](https://linux-hardware.org/?probe=eaa0ff8b0c) | Dec 27, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [4a28e0da3c](https://linux-hardware.org/?probe=4a28e0da3c) | Dec 27, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [dfa2a6458d](https://linux-hardware.org/?probe=dfa2a6458d) | Dec 27, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [a14ae548b1](https://linux-hardware.org/?probe=a14ae548b1) | Dec 26, 2023 |
| Lenovo        | ThinkPad W530 24474LG       | Notebook    | [180b4817c4](https://linux-hardware.org/?probe=180b4817c4) | Dec 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2edba36887](https://linux-hardware.org/?probe=2edba36887) | Dec 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [77553a2b0e](https://linux-hardware.org/?probe=77553a2b0e) | Dec 26, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [58dd947260](https://linux-hardware.org/?probe=58dd947260) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [d8eafc52d5](https://linux-hardware.org/?probe=d8eafc52d5) | Dec 25, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [78b73643ff](https://linux-hardware.org/?probe=78b73643ff) | Dec 23, 2023 |
| Lenovo        | ThinkPad T500 20564RG       | Notebook    | [e17f4b51d6](https://linux-hardware.org/?probe=e17f4b51d6) | Dec 22, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [72084f8af0](https://linux-hardware.org/?probe=72084f8af0) | Dec 22, 2023 |
| Medion        | E11202                      | Notebook    | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | BU201LA                     | Notebook    | [2985f7a222](https://linux-hardware.org/?probe=2985f7a222) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [5d41a0e0d5](https://linux-hardware.org/?probe=5d41a0e0d5) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [ad67aeb103](https://linux-hardware.org/?probe=ad67aeb103) | Dec 22, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [45079856a0](https://linux-hardware.org/?probe=45079856a0) | Dec 22, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [62624ca97b](https://linux-hardware.org/?probe=62624ca97b) | Dec 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [da159da872](https://linux-hardware.org/?probe=da159da872) | Dec 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [091511a6c2](https://linux-hardware.org/?probe=091511a6c2) | Dec 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ef17f12758](https://linux-hardware.org/?probe=ef17f12758) | Dec 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fecbe03785](https://linux-hardware.org/?probe=fecbe03785) | Dec 20, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9839cacb3a](https://linux-hardware.org/?probe=9839cacb3a) | Dec 19, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [8268b72759](https://linux-hardware.org/?probe=8268b72759) | Dec 19, 2023 |
| HP            | Unknown                     | Notebook    | [43fae5ce53](https://linux-hardware.org/?probe=43fae5ce53) | Dec 19, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [020e3af833](https://linux-hardware.org/?probe=020e3af833) | Dec 18, 2023 |
| Dell          | Latitude E5550              | Notebook    | [671595a2e5](https://linux-hardware.org/?probe=671595a2e5) | Dec 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [c2dce135e4](https://linux-hardware.org/?probe=c2dce135e4) | Dec 18, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [4824537107](https://linux-hardware.org/?probe=4824537107) | Dec 18, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [cc0dbece31](https://linux-hardware.org/?probe=cc0dbece31) | Dec 18, 2023 |
| Medion        | E3216 MD61800               | Convertible | [c048f29733](https://linux-hardware.org/?probe=c048f29733) | Dec 18, 2023 |
| Medion        | E3216 MD61800               | Convertible | [fdc44cbae2](https://linux-hardware.org/?probe=fdc44cbae2) | Dec 18, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [4b43240ccd](https://linux-hardware.org/?probe=4b43240ccd) | Dec 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cd04b1b3df](https://linux-hardware.org/?probe=cd04b1b3df) | Dec 17, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b6aa52f693](https://linux-hardware.org/?probe=b6aa52f693) | Dec 17, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [f3725914ae](https://linux-hardware.org/?probe=f3725914ae) | Dec 17, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f64fa9a501](https://linux-hardware.org/?probe=f64fa9a501) | Dec 16, 2023 |
| Lenovo        | 13w Yoga Gen 2 82YR         | Convertible | [8ac4acf05f](https://linux-hardware.org/?probe=8ac4acf05f) | Dec 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [56e95fc392](https://linux-hardware.org/?probe=56e95fc392) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [933e5b48f2](https://linux-hardware.org/?probe=933e5b48f2) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [9df7fd000e](https://linux-hardware.org/?probe=9df7fd000e) | Dec 16, 2023 |
| Dell          | Latitude E5550              | Notebook    | [dc16864fb6](https://linux-hardware.org/?probe=dc16864fb6) | Dec 15, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [ffdec6f614](https://linux-hardware.org/?probe=ffdec6f614) | Dec 14, 2023 |
| Dell          | Precision 5680              | Notebook    | [1e063996da](https://linux-hardware.org/?probe=1e063996da) | Dec 14, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [1d935cbf02](https://linux-hardware.org/?probe=1d935cbf02) | Dec 13, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [3deb250922](https://linux-hardware.org/?probe=3deb250922) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5200cedaa0](https://linux-hardware.org/?probe=5200cedaa0) | Dec 13, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [ba6f8efad6](https://linux-hardware.org/?probe=ba6f8efad6) | Dec 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b949261978](https://linux-hardware.org/?probe=b949261978) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK U7413              | Notebook    | [088a24eb7d](https://linux-hardware.org/?probe=088a24eb7d) | Dec 13, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d3eea6ef7f](https://linux-hardware.org/?probe=d3eea6ef7f) | Dec 13, 2023 |
| Lenovo        | 1038 SDK0Q40104 WIN 3305... | Server      | [f2240b183a](https://linux-hardware.org/?probe=f2240b183a) | Dec 12, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [63cf57fa53](https://linux-hardware.org/?probe=63cf57fa53) | Dec 12, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [9887ecb3b0](https://linux-hardware.org/?probe=9887ecb3b0) | Dec 12, 2023 |
| Lenovo        | ThinkPad L470 20J5S1FW00    | Notebook    | [9ea0dccce0](https://linux-hardware.org/?probe=9ea0dccce0) | Dec 11, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [0bf86693bc](https://linux-hardware.org/?probe=0bf86693bc) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [840ffb67be](https://linux-hardware.org/?probe=840ffb67be) | Dec 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [14c50f3617](https://linux-hardware.org/?probe=14c50f3617) | Dec 10, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [ba43863b29](https://linux-hardware.org/?probe=ba43863b29) | Dec 09, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [8ec0cd2d39](https://linux-hardware.org/?probe=8ec0cd2d39) | Dec 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [f499be5e26](https://linux-hardware.org/?probe=f499be5e26) | Dec 09, 2023 |
| ASRock        | H510M-ITX/ac                | Desktop     | [4850c05764](https://linux-hardware.org/?probe=4850c05764) | Dec 08, 2023 |
| Lenovo        | Yoga Slim 6 14IRH8 83E0     | Notebook    | [a8b759b4a8](https://linux-hardware.org/?probe=a8b759b4a8) | Dec 07, 2023 |
| Dell          | 0GVPNP A03                  | Server      | [c618310d44](https://linux-hardware.org/?probe=c618310d44) | Dec 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [afd68e777f](https://linux-hardware.org/?probe=afd68e777f) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [9a8395654c](https://linux-hardware.org/?probe=9a8395654c) | Dec 06, 2023 |
| Samsung       | R580/R590                   | Notebook    | [89f285aacc](https://linux-hardware.org/?probe=89f285aacc) | Dec 05, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9478c73013](https://linux-hardware.org/?probe=9478c73013) | Dec 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [67d1badc93](https://linux-hardware.org/?probe=67d1badc93) | Dec 05, 2023 |
| ASUSTek       | X751LN                      | Notebook    | [72bc3137f4](https://linux-hardware.org/?probe=72bc3137f4) | Dec 05, 2023 |
| HP            | Notebook                    | Notebook    | [4f0e8aad8c](https://linux-hardware.org/?probe=4f0e8aad8c) | Dec 04, 2023 |
| Lenovo        | 1038 SDK0Q40104 WIN 3305... | Server      | [1a4b0ab519](https://linux-hardware.org/?probe=1a4b0ab519) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [452f677f7f](https://linux-hardware.org/?probe=452f677f7f) | Dec 03, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [442d7a2388](https://linux-hardware.org/?probe=442d7a2388) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [1f6674a16b](https://linux-hardware.org/?probe=1f6674a16b) | Dec 03, 2023 |
| MSI           | GE72 6QF                    | Notebook    | [2cce4d92fe](https://linux-hardware.org/?probe=2cce4d92fe) | Dec 02, 2023 |
| Lenovo        | ThinkPad T470 20HDA01RKR    | Notebook    | [f7fb5f1e5d](https://linux-hardware.org/?probe=f7fb5f1e5d) | Dec 01, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d956dae97a](https://linux-hardware.org/?probe=d956dae97a) | Nov 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [bfa4423c0f](https://linux-hardware.org/?probe=bfa4423c0f) | Nov 30, 2023 |
| Lenovo        | ThinkPad T470 20HDA01RKR    | Notebook    | [46a5719afb](https://linux-hardware.org/?probe=46a5719afb) | Nov 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ad9b9e5fd1](https://linux-hardware.org/?probe=ad9b9e5fd1) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [970202f2a1](https://linux-hardware.org/?probe=970202f2a1) | Nov 30, 2023 |
| Unknown       | Unknown                     | Soc         | [ab9297851b](https://linux-hardware.org/?probe=ab9297851b) | Nov 30, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [e3dab2d6dc](https://linux-hardware.org/?probe=e3dab2d6dc) | Nov 29, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [5bfe0aed96](https://linux-hardware.org/?probe=5bfe0aed96) | Nov 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3bbd848840](https://linux-hardware.org/?probe=3bbd848840) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [cd5316e290](https://linux-hardware.org/?probe=cd5316e290) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [29e5da6013](https://linux-hardware.org/?probe=29e5da6013) | Nov 29, 2023 |
| Unknown       | Unknown                     | Soc         | [7acffa679c](https://linux-hardware.org/?probe=7acffa679c) | Nov 29, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [bb1d8fb09e](https://linux-hardware.org/?probe=bb1d8fb09e) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a638d25ff0](https://linux-hardware.org/?probe=a638d25ff0) | Nov 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [8c51aa422e](https://linux-hardware.org/?probe=8c51aa422e) | Nov 27, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [43921895ea](https://linux-hardware.org/?probe=43921895ea) | Nov 27, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [2a870ea79e](https://linux-hardware.org/?probe=2a870ea79e) | Nov 27, 2023 |
| Toshiba       | Satellite Z30-B             | Notebook    | [80f2583617](https://linux-hardware.org/?probe=80f2583617) | Nov 27, 2023 |
| Fujitsu       | LIFEBOOK U7413              | Notebook    | [b8569ba845](https://linux-hardware.org/?probe=b8569ba845) | Nov 27, 2023 |
| VALE          | Notebook Classic C170       | Notebook    | [fcb0ab721b](https://linux-hardware.org/?probe=fcb0ab721b) | Nov 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [f31c8412d9](https://linux-hardware.org/?probe=f31c8412d9) | Nov 26, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [e7c6d5b018](https://linux-hardware.org/?probe=e7c6d5b018) | Nov 26, 2023 |
| Jetway        | TI61M5                      | Desktop     | [dff0fcc796](https://linux-hardware.org/?probe=dff0fcc796) | Nov 25, 2023 |
| HP            | 829A                        | Mini pc     | [189ab9b0f9](https://linux-hardware.org/?probe=189ab9b0f9) | Nov 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [1065af244c](https://linux-hardware.org/?probe=1065af244c) | Nov 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [e225477a30](https://linux-hardware.org/?probe=e225477a30) | Nov 24, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [5590ebdcca](https://linux-hardware.org/?probe=5590ebdcca) | Nov 24, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [a89e3b5a9d](https://linux-hardware.org/?probe=a89e3b5a9d) | Nov 24, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [52ff8830e8](https://linux-hardware.org/?probe=52ff8830e8) | Nov 24, 2023 |
| HP            | 829A                        | Mini pc     | [b8edb25d4c](https://linux-hardware.org/?probe=b8edb25d4c) | Nov 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1d10317040](https://linux-hardware.org/?probe=1d10317040) | Nov 22, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [7e25b00cb4](https://linux-hardware.org/?probe=7e25b00cb4) | Nov 22, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [f892ee3011](https://linux-hardware.org/?probe=f892ee3011) | Nov 21, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [43be1d8514](https://linux-hardware.org/?probe=43be1d8514) | Nov 21, 2023 |
| Jetway        | TI61M5                      | Desktop     | [968d83ba14](https://linux-hardware.org/?probe=968d83ba14) | Nov 21, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [d73c12597f](https://linux-hardware.org/?probe=d73c12597f) | Nov 21, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [69d60bac42](https://linux-hardware.org/?probe=69d60bac42) | Nov 20, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [ea5517388b](https://linux-hardware.org/?probe=ea5517388b) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [339c8003a9](https://linux-hardware.org/?probe=339c8003a9) | Nov 19, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [ee45badecb](https://linux-hardware.org/?probe=ee45badecb) | Nov 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [2f1ba470f6](https://linux-hardware.org/?probe=2f1ba470f6) | Nov 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [f3170951f8](https://linux-hardware.org/?probe=f3170951f8) | Nov 18, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [f93730616e](https://linux-hardware.org/?probe=f93730616e) | Nov 18, 2023 |
| Fujitsu       | LIFEBOOK U7413              | Notebook    | [62b13a5829](https://linux-hardware.org/?probe=62b13a5829) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | Desktop     | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [56ae69a7dc](https://linux-hardware.org/?probe=56ae69a7dc) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Lenovo        | ThinkPad E485 20KU000ACD    | Notebook    | [e03dd77d39](https://linux-hardware.org/?probe=e03dd77d39) | Nov 16, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a8112be1bd](https://linux-hardware.org/?probe=a8112be1bd) | Nov 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [477c710fe1](https://linux-hardware.org/?probe=477c710fe1) | Nov 15, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [9119b16d75](https://linux-hardware.org/?probe=9119b16d75) | Nov 15, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [ac5c2d0218](https://linux-hardware.org/?probe=ac5c2d0218) | Nov 15, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d2b8ae9725](https://linux-hardware.org/?probe=d2b8ae9725) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK U7413              | Notebook    | [b5ac0ee2ca](https://linux-hardware.org/?probe=b5ac0ee2ca) | Nov 13, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [e82ee1d840](https://linux-hardware.org/?probe=e82ee1d840) | Nov 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [feaa9f3eac](https://linux-hardware.org/?probe=feaa9f3eac) | Nov 11, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [0c374e0790](https://linux-hardware.org/?probe=0c374e0790) | Nov 11, 2023 |
| Intel         | X99                         | Desktop     | [5c6225ea2d](https://linux-hardware.org/?probe=5c6225ea2d) | Nov 11, 2023 |
| Minix         | NEO Z83-4 V1.5              | Desktop     | [3623dfcb88](https://linux-hardware.org/?probe=3623dfcb88) | Nov 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4859d7ce93](https://linux-hardware.org/?probe=4859d7ce93) | Nov 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd4b3a096e](https://linux-hardware.org/?probe=bd4b3a096e) | Nov 10, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [4e064613e4](https://linux-hardware.org/?probe=4e064613e4) | Nov 10, 2023 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [ab1560cd77](https://linux-hardware.org/?probe=ab1560cd77) | Nov 09, 2023 |
| MSI           | 970A-G43                    | Desktop     | [c4aecb23af](https://linux-hardware.org/?probe=c4aecb23af) | Nov 09, 2023 |
| MSI           | 970A-G43                    | Desktop     | [7c748629cb](https://linux-hardware.org/?probe=7c748629cb) | Nov 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [4eb5901f8c](https://linux-hardware.org/?probe=4eb5901f8c) | Nov 08, 2023 |
| ASUSTek       | GL702VMK                    | Notebook    | [4cb218a4f4](https://linux-hardware.org/?probe=4cb218a4f4) | Nov 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [ed6ede63bc](https://linux-hardware.org/?probe=ed6ede63bc) | Nov 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [27efb1bfd6](https://linux-hardware.org/?probe=27efb1bfd6) | Nov 07, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d9cfeee9df](https://linux-hardware.org/?probe=d9cfeee9df) | Nov 06, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [18053575fc](https://linux-hardware.org/?probe=18053575fc) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [52781b1111](https://linux-hardware.org/?probe=52781b1111) | Nov 06, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [5b5425c6d8](https://linux-hardware.org/?probe=5b5425c6d8) | Nov 05, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [d20af6bf95](https://linux-hardware.org/?probe=d20af6bf95) | Nov 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [30a0e0602f](https://linux-hardware.org/?probe=30a0e0602f) | Nov 04, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [e26ed8b740](https://linux-hardware.org/?probe=e26ed8b740) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [b0ee1e5f32](https://linux-hardware.org/?probe=b0ee1e5f32) | Nov 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd018c7ab7](https://linux-hardware.org/?probe=cd018c7ab7) | Nov 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [960c1dbbd2](https://linux-hardware.org/?probe=960c1dbbd2) | Nov 01, 2023 |
| ASUSTek       | M3A32-MVP DELUXE            | Desktop     | [fecdf24435](https://linux-hardware.org/?probe=fecdf24435) | Nov 01, 2023 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [a8ae4206d4](https://linux-hardware.org/?probe=a8ae4206d4) | Oct 31, 2023 |
| MSI           | Modern 15 A11M              | Notebook    | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| Acer          | Veriton M480                | Desktop     | [fb5c756319](https://linux-hardware.org/?probe=fb5c756319) | Oct 30, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [449c0df691](https://linux-hardware.org/?probe=449c0df691) | Oct 30, 2023 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [4e11be8872](https://linux-hardware.org/?probe=4e11be8872) | Oct 30, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [31d6b19c8d](https://linux-hardware.org/?probe=31d6b19c8d) | Oct 29, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [519bf4fbae](https://linux-hardware.org/?probe=519bf4fbae) | Oct 29, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [e9415cd88b](https://linux-hardware.org/?probe=e9415cd88b) | Oct 26, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8fb11a836e](https://linux-hardware.org/?probe=8fb11a836e) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [534c2c528c](https://linux-hardware.org/?probe=534c2c528c) | Oct 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e090fa6279](https://linux-hardware.org/?probe=e090fa6279) | Oct 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [d0b6352e7f](https://linux-hardware.org/?probe=d0b6352e7f) | Oct 23, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [e22a3baeb9](https://linux-hardware.org/?probe=e22a3baeb9) | Oct 23, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [ebfb310a2d](https://linux-hardware.org/?probe=ebfb310a2d) | Oct 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e579268b6](https://linux-hardware.org/?probe=5e579268b6) | Oct 23, 2023 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [c096ac6500](https://linux-hardware.org/?probe=c096ac6500) | Oct 22, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [81a0160338](https://linux-hardware.org/?probe=81a0160338) | Oct 22, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [b3397c9aa2](https://linux-hardware.org/?probe=b3397c9aa2) | Oct 22, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c1ad18b5c9](https://linux-hardware.org/?probe=c1ad18b5c9) | Oct 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d2beead33c](https://linux-hardware.org/?probe=d2beead33c) | Oct 21, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e8216f74dc](https://linux-hardware.org/?probe=e8216f74dc) | Oct 20, 2023 |
| HP            | 829A                        | Mini pc     | [8a3f72e9ef](https://linux-hardware.org/?probe=8a3f72e9ef) | Oct 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [686e5c87a9](https://linux-hardware.org/?probe=686e5c87a9) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d531813a7a](https://linux-hardware.org/?probe=d531813a7a) | Oct 18, 2023 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [37b97d2dd2](https://linux-hardware.org/?probe=37b97d2dd2) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [17314417bf](https://linux-hardware.org/?probe=17314417bf) | Oct 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [f776cdb186](https://linux-hardware.org/?probe=f776cdb186) | Oct 17, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [c84d539a84](https://linux-hardware.org/?probe=c84d539a84) | Oct 17, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [67ad226870](https://linux-hardware.org/?probe=67ad226870) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [47f6f3760d](https://linux-hardware.org/?probe=47f6f3760d) | Oct 17, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1ab24b9490](https://linux-hardware.org/?probe=1ab24b9490) | Oct 16, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [e41e92379e](https://linux-hardware.org/?probe=e41e92379e) | Oct 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4b5e14f452](https://linux-hardware.org/?probe=4b5e14f452) | Oct 15, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6ca7e8d16c](https://linux-hardware.org/?probe=6ca7e8d16c) | Oct 15, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [23c3f61285](https://linux-hardware.org/?probe=23c3f61285) | Oct 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | Notebook    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | Notebook    | [5298e96c35](https://linux-hardware.org/?probe=5298e96c35) | Oct 13, 2023 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [f25cb1517e](https://linux-hardware.org/?probe=f25cb1517e) | Oct 12, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [5cf8ab4b64](https://linux-hardware.org/?probe=5cf8ab4b64) | Oct 12, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [7f65a85252](https://linux-hardware.org/?probe=7f65a85252) | Oct 12, 2023 |
| AMI           | Intel                       | Notebook    | [e60ced0b11](https://linux-hardware.org/?probe=e60ced0b11) | Oct 12, 2023 |
| AMI           | Intel                       | Notebook    | [4b7c1bc00c](https://linux-hardware.org/?probe=4b7c1bc00c) | Oct 12, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [7108bb9955](https://linux-hardware.org/?probe=7108bb9955) | Oct 10, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [7e264895bf](https://linux-hardware.org/?probe=7e264895bf) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [f91905858e](https://linux-hardware.org/?probe=f91905858e) | Oct 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRC... | Notebook    | [a5e4eeba7f](https://linux-hardware.org/?probe=a5e4eeba7f) | Oct 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [af435b34a3](https://linux-hardware.org/?probe=af435b34a3) | Oct 07, 2023 |
| HP            | Notebook                    | Notebook    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| HP            | Notebook                    | Notebook    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a2fb75cc3e](https://linux-hardware.org/?probe=a2fb75cc3e) | Oct 06, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | Notebook    | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [3a5617ed7c](https://linux-hardware.org/?probe=3a5617ed7c) | Oct 01, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [25c3794b84](https://linux-hardware.org/?probe=25c3794b84) | Oct 01, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [8f0d72cf69](https://linux-hardware.org/?probe=8f0d72cf69) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [fb307526fa](https://linux-hardware.org/?probe=fb307526fa) | Oct 01, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [411e8279da](https://linux-hardware.org/?probe=411e8279da) | Oct 01, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [150d5d9afd](https://linux-hardware.org/?probe=150d5d9afd) | Oct 01, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [dea46b2302](https://linux-hardware.org/?probe=dea46b2302) | Sep 29, 2023 |
| HP            | 8923 00100                  | All in one  | [31d524cec8](https://linux-hardware.org/?probe=31d524cec8) | Sep 28, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [35f0e18f04](https://linux-hardware.org/?probe=35f0e18f04) | Sep 28, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [d93c40647f](https://linux-hardware.org/?probe=d93c40647f) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5-LT... | Tablet      | [d0b85eac7a](https://linux-hardware.org/?probe=d0b85eac7a) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | Notebook    | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [4259a21921](https://linux-hardware.org/?probe=4259a21921) | Sep 26, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [2fe436c443](https://linux-hardware.org/?probe=2fe436c443) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [f47493454f](https://linux-hardware.org/?probe=f47493454f) | Sep 25, 2023 |
| HP            | 802F                        | Desktop     | [a5fa953171](https://linux-hardware.org/?probe=a5fa953171) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [739be981d6](https://linux-hardware.org/?probe=739be981d6) | Sep 24, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [0b8e5fc8d0](https://linux-hardware.org/?probe=0b8e5fc8d0) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | Notebook    | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [0648a13752](https://linux-hardware.org/?probe=0648a13752) | Sep 24, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [c0e3bef058](https://linux-hardware.org/?probe=c0e3bef058) | Sep 24, 2023 |
| HP            | 350 G2                      | Notebook    | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | Notebook    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [2a09805fe9](https://linux-hardware.org/?probe=2a09805fe9) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [ddac5bba05](https://linux-hardware.org/?probe=ddac5bba05) | Sep 23, 2023 |
| Dell          | Latitude E7270              | Notebook    | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [10cd0244af](https://linux-hardware.org/?probe=10cd0244af) | Sep 23, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [0f276cde5a](https://linux-hardware.org/?probe=0f276cde5a) | Sep 23, 2023 |
| HP            | ProBook 4515s               | Notebook    | [0b755bf978](https://linux-hardware.org/?probe=0b755bf978) | Sep 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [20d494d943](https://linux-hardware.org/?probe=20d494d943) | Sep 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [6e8c507d61](https://linux-hardware.org/?probe=6e8c507d61) | Sep 22, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [968cd24afa](https://linux-hardware.org/?probe=968cd24afa) | Sep 22, 2023 |
| AMI           | Intel                       | Notebook    | [687044ba01](https://linux-hardware.org/?probe=687044ba01) | Sep 21, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [f55adbf4eb](https://linux-hardware.org/?probe=f55adbf4eb) | Sep 20, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [139fc573bf](https://linux-hardware.org/?probe=139fc573bf) | Sep 19, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [faa5140c74](https://linux-hardware.org/?probe=faa5140c74) | Sep 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [111652ff69](https://linux-hardware.org/?probe=111652ff69) | Sep 18, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [0578825483](https://linux-hardware.org/?probe=0578825483) | Sep 18, 2023 |
| Lenovo        | 7X16CTO1WW                  | Server      | [b6d0938617](https://linux-hardware.org/?probe=b6d0938617) | Sep 18, 2023 |
| Dell          | 084XW4 A06                  | Server      | [ea77b31f41](https://linux-hardware.org/?probe=ea77b31f41) | Sep 18, 2023 |
| Lenovo        | SB27B23563 03               | Server      | [b6b52e11fe](https://linux-hardware.org/?probe=b6b52e11fe) | Sep 18, 2023 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [b9f92fec9c](https://linux-hardware.org/?probe=b9f92fec9c) | Sep 17, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [5995975e04](https://linux-hardware.org/?probe=5995975e04) | Sep 16, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [0379270fb2](https://linux-hardware.org/?probe=0379270fb2) | Sep 15, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [dd369f3c60](https://linux-hardware.org/?probe=dd369f3c60) | Sep 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [15256fdeb2](https://linux-hardware.org/?probe=15256fdeb2) | Sep 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f155701b1](https://linux-hardware.org/?probe=5f155701b1) | Sep 13, 2023 |
| MSI           | PRO B760M-A WIFI            | Desktop     | [87577c165a](https://linux-hardware.org/?probe=87577c165a) | Sep 12, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [4070a28418](https://linux-hardware.org/?probe=4070a28418) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [3abcd33b9c](https://linux-hardware.org/?probe=3abcd33b9c) | Sep 11, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [41a8df4387](https://linux-hardware.org/?probe=41a8df4387) | Sep 10, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [39a15ba0ca](https://linux-hardware.org/?probe=39a15ba0ca) | Sep 10, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [5828591d02](https://linux-hardware.org/?probe=5828591d02) | Sep 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ae7c4440b](https://linux-hardware.org/?probe=3ae7c4440b) | Sep 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [56bef39b59](https://linux-hardware.org/?probe=56bef39b59) | Sep 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [bbbc40365d](https://linux-hardware.org/?probe=bbbc40365d) | Sep 10, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [780a68ac11](https://linux-hardware.org/?probe=780a68ac11) | Sep 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [a928ff5a33](https://linux-hardware.org/?probe=a928ff5a33) | Sep 09, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e34200af0f](https://linux-hardware.org/?probe=e34200af0f) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [59544c398a](https://linux-hardware.org/?probe=59544c398a) | Sep 07, 2023 |
| GMKtec        | NucBox G2                   | Desktop     | [8c03fc694f](https://linux-hardware.org/?probe=8c03fc694f) | Sep 05, 2023 |
| GMKtec        | NucBox G2                   | Desktop     | [ba313b48f8](https://linux-hardware.org/?probe=ba313b48f8) | Sep 05, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [2c94bcc096](https://linux-hardware.org/?probe=2c94bcc096) | Sep 05, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [245441c639](https://linux-hardware.org/?probe=245441c639) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [73e3b8ef8a](https://linux-hardware.org/?probe=73e3b8ef8a) | Sep 04, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [4764776393](https://linux-hardware.org/?probe=4764776393) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [7cf0b6a1c4](https://linux-hardware.org/?probe=7cf0b6a1c4) | Sep 01, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75ad357b16](https://linux-hardware.org/?probe=75ad357b16) | Sep 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5f50ef24fe](https://linux-hardware.org/?probe=5f50ef24fe) | Sep 01, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [0d1017e65a](https://linux-hardware.org/?probe=0d1017e65a) | Aug 31, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [0dd23cfbaa](https://linux-hardware.org/?probe=0dd23cfbaa) | Aug 31, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [05b083817c](https://linux-hardware.org/?probe=05b083817c) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [f6f76a2e9d](https://linux-hardware.org/?probe=f6f76a2e9d) | Aug 30, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [6bf92318e7](https://linux-hardware.org/?probe=6bf92318e7) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | Notebook    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [0e3563cf3e](https://linux-hardware.org/?probe=0e3563cf3e) | Aug 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [036ad179d7](https://linux-hardware.org/?probe=036ad179d7) | Aug 26, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [9e90f8b308](https://linux-hardware.org/?probe=9e90f8b308) | Aug 26, 2023 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [1025de1dcf](https://linux-hardware.org/?probe=1025de1dcf) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | Notebook    | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [86f9b36e03](https://linux-hardware.org/?probe=86f9b36e03) | Aug 20, 2023 |
| Chuwi         | LapBook SE                  | Notebook    | [8c338913ab](https://linux-hardware.org/?probe=8c338913ab) | Aug 19, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [89bb5a2821](https://linux-hardware.org/?probe=89bb5a2821) | Aug 19, 2023 |
| Acer          | Predator PH317-52           | Notebook    | [c942508cf0](https://linux-hardware.org/?probe=c942508cf0) | Aug 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [0122fef8fd](https://linux-hardware.org/?probe=0122fef8fd) | Aug 15, 2023 |
| MSI           | MS-B1831                    | Desktop     | [25e33380e5](https://linux-hardware.org/?probe=25e33380e5) | Aug 14, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [1bb822c058](https://linux-hardware.org/?probe=1bb822c058) | Aug 13, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c24273512e](https://linux-hardware.org/?probe=c24273512e) | Aug 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| HP            | 350 G2                      | Notebook    | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e6624cc619](https://linux-hardware.org/?probe=e6624cc619) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [aacbd7403c](https://linux-hardware.org/?probe=aacbd7403c) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [a7a57a8a56](https://linux-hardware.org/?probe=a7a57a8a56) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [69a5fc6981](https://linux-hardware.org/?probe=69a5fc6981) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [ac775a3228](https://linux-hardware.org/?probe=ac775a3228) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [e3f3b2fcfb](https://linux-hardware.org/?probe=e3f3b2fcfb) | Aug 09, 2023 |
| Dell          | Latitude 5540               | Notebook    | [08c875f58b](https://linux-hardware.org/?probe=08c875f58b) | Aug 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fe4aa817e1](https://linux-hardware.org/?probe=fe4aa817e1) | Aug 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [cb3d78955a](https://linux-hardware.org/?probe=cb3d78955a) | Aug 05, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [15826fe271](https://linux-hardware.org/?probe=15826fe271) | Aug 04, 2023 |
| Lenovo        | ThinkPad X230 23205XG       | Notebook    | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| ASUSTek       | M3A78-T                     | Desktop     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [c04f6d6467](https://linux-hardware.org/?probe=c04f6d6467) | Aug 01, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [19c877cd88](https://linux-hardware.org/?probe=19c877cd88) | Jul 31, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cd96592ef8](https://linux-hardware.org/?probe=cd96592ef8) | Jul 31, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad T470 20HES2C000    | Notebook    | [6cb5b31808](https://linux-hardware.org/?probe=6cb5b31808) | Jul 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [68d5cb02bf](https://linux-hardware.org/?probe=68d5cb02bf) | Jul 29, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [5bcf13119e](https://linux-hardware.org/?probe=5bcf13119e) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [067a1b82b7](https://linux-hardware.org/?probe=067a1b82b7) | Jul 25, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [ac0ba8e136](https://linux-hardware.org/?probe=ac0ba8e136) | Jul 25, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [bc4c439514](https://linux-hardware.org/?probe=bc4c439514) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [c78a2441ee](https://linux-hardware.org/?probe=c78a2441ee) | Jul 23, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [5bf3142c39](https://linux-hardware.org/?probe=5bf3142c39) | Jul 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [db220d13d6](https://linux-hardware.org/?probe=db220d13d6) | Jul 20, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [7171de16ea](https://linux-hardware.org/?probe=7171de16ea) | Jul 19, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [01b8ada2a7](https://linux-hardware.org/?probe=01b8ada2a7) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [4be00d26b2](https://linux-hardware.org/?probe=4be00d26b2) | Jul 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [080a9244cf](https://linux-hardware.org/?probe=080a9244cf) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | Notebook    | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | Notebook    | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| ASRock        | H97 Performance             | Desktop     | [3d8cc4b423](https://linux-hardware.org/?probe=3d8cc4b423) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [b2de29a3db](https://linux-hardware.org/?probe=b2de29a3db) | Jul 10, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3ad7db3176](https://linux-hardware.org/?probe=3ad7db3176) | Jul 10, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [596389ea27](https://linux-hardware.org/?probe=596389ea27) | Jul 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7c9b47b69f](https://linux-hardware.org/?probe=7c9b47b69f) | Jul 10, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [919d1fc65b](https://linux-hardware.org/?probe=919d1fc65b) | Jul 09, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [89dc06fa6d](https://linux-hardware.org/?probe=89dc06fa6d) | Jul 09, 2023 |
| ASUSTek       | G60VX                       | Notebook    | [3273a8de27](https://linux-hardware.org/?probe=3273a8de27) | Jul 09, 2023 |
| MSI           | MS-B9181                    | Desktop     | [4702ba374d](https://linux-hardware.org/?probe=4702ba374d) | Jul 09, 2023 |
| ASRock        | H97 Performance             | Desktop     | [8058c54fb2](https://linux-hardware.org/?probe=8058c54fb2) | Jul 08, 2023 |
| ASRock        | H97 Performance             | Desktop     | [6994d9f579](https://linux-hardware.org/?probe=6994d9f579) | Jul 08, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [c1b5a5f99b](https://linux-hardware.org/?probe=c1b5a5f99b) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4e0acb57f9](https://linux-hardware.org/?probe=4e0acb57f9) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [cae21c5121](https://linux-hardware.org/?probe=cae21c5121) | Jul 07, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [e328019dd8](https://linux-hardware.org/?probe=e328019dd8) | Jul 07, 2023 |
| Medion        | Unknown                     | Notebook    | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| ASUSTek       | M4A78-E                     | Desktop     | [c5e94d62b9](https://linux-hardware.org/?probe=c5e94d62b9) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | Desktop     | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bbce89859f](https://linux-hardware.org/?probe=bbce89859f) | Jul 06, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| HP            | ProBook 4740s               | Notebook    | [c920d177db](https://linux-hardware.org/?probe=c920d177db) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [117a651e12](https://linux-hardware.org/?probe=117a651e12) | Jul 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5f2c613312](https://linux-hardware.org/?probe=5f2c613312) | Jul 03, 2023 |
| MSI           | Z370 OC GAMING              | Desktop     | [f2796b9262](https://linux-hardware.org/?probe=f2796b9262) | Jul 02, 2023 |
| HP            | 2129                        | Desktop     | [cc9462c976](https://linux-hardware.org/?probe=cc9462c976) | Jul 02, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [31a9983e65](https://linux-hardware.org/?probe=31a9983e65) | Jul 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [88b0de8666](https://linux-hardware.org/?probe=88b0de8666) | Jul 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [cd28af9419](https://linux-hardware.org/?probe=cd28af9419) | Jun 30, 2023 |
| ASUSTek       | F1A75-V EVO                 | Desktop     | [b59f4f203c](https://linux-hardware.org/?probe=b59f4f203c) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | Aspire VN7-593G             | Notebook    | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [eeb516967a](https://linux-hardware.org/?probe=eeb516967a) | Jun 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a2a87af2a4](https://linux-hardware.org/?probe=a2a87af2a4) | Jun 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [2f3a03f9d4](https://linux-hardware.org/?probe=2f3a03f9d4) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | Notebook    | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [3cb015a09d](https://linux-hardware.org/?probe=3cb015a09d) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| MSI           | 760GM -E51                  | Desktop     | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [c3961b2aa5](https://linux-hardware.org/?probe=c3961b2aa5) | Jun 21, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [e00f1f735d](https://linux-hardware.org/?probe=e00f1f735d) | Jun 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [9fa828d2e4](https://linux-hardware.org/?probe=9fa828d2e4) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [576a62665a](https://linux-hardware.org/?probe=576a62665a) | Jun 20, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d95fa943f1](https://linux-hardware.org/?probe=d95fa943f1) | Jun 19, 2023 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [bae46c4d0b](https://linux-hardware.org/?probe=bae46c4d0b) | Jun 19, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [22fc172f71](https://linux-hardware.org/?probe=22fc172f71) | Jun 18, 2023 |
| HP            | 3646h                       | Desktop     | [bbe600a4ab](https://linux-hardware.org/?probe=bbe600a4ab) | Jun 18, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288db43785](https://linux-hardware.org/?probe=288db43785) | Jun 16, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [d254709437](https://linux-hardware.org/?probe=d254709437) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Acer          | TravelMate 5742Z            | Notebook    | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d2a0d735db](https://linux-hardware.org/?probe=d2a0d735db) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [93fe499e47](https://linux-hardware.org/?probe=93fe499e47) | Jun 12, 2023 |
| Lenovo        | ThinkPad W541 20EGS15J0N    | Notebook    | [ba935e9d5c](https://linux-hardware.org/?probe=ba935e9d5c) | Jun 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3918c9dc55](https://linux-hardware.org/?probe=3918c9dc55) | Jun 12, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [411faeafd4](https://linux-hardware.org/?probe=411faeafd4) | Jun 11, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d6be89e452](https://linux-hardware.org/?probe=d6be89e452) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [f0bad84fca](https://linux-hardware.org/?probe=f0bad84fca) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [7e07a9c15d](https://linux-hardware.org/?probe=7e07a9c15d) | Jun 07, 2023 |
| Dell          | Latitude E7250              | Notebook    | [a80182e728](https://linux-hardware.org/?probe=a80182e728) | Jun 06, 2023 |
| HP            | 8265                        | Desktop     | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5b7617b9c0](https://linux-hardware.org/?probe=5b7617b9c0) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| HP            | 1998                        | Desktop     | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [2378902ae8](https://linux-hardware.org/?probe=2378902ae8) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2cacb34a0d](https://linux-hardware.org/?probe=2cacb34a0d) | Jun 02, 2023 |
| Supermicro    | X12STD-F                    | Desktop     | [df7c4a738e](https://linux-hardware.org/?probe=df7c4a738e) | Jun 01, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [0c0dc06847](https://linux-hardware.org/?probe=0c0dc06847) | May 31, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [c496e8a74f](https://linux-hardware.org/?probe=c496e8a74f) | May 30, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [4cbc2f9044](https://linux-hardware.org/?probe=4cbc2f9044) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c2d144c313](https://linux-hardware.org/?probe=c2d144c313) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d7ccd868f](https://linux-hardware.org/?probe=4d7ccd868f) | May 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [f2f00bcfcc](https://linux-hardware.org/?probe=f2f00bcfcc) | May 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [242a13f378](https://linux-hardware.org/?probe=242a13f378) | May 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [69adae13fe](https://linux-hardware.org/?probe=69adae13fe) | May 27, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [692ba9d18f](https://linux-hardware.org/?probe=692ba9d18f) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Dell          | 08DM12 A05                  | Server      | [a6c10986c9](https://linux-hardware.org/?probe=a6c10986c9) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [a2e80bffac](https://linux-hardware.org/?probe=a2e80bffac) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0633ac39d](https://linux-hardware.org/?probe=d0633ac39d) | May 19, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [9d66e80652](https://linux-hardware.org/?probe=9d66e80652) | May 18, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [44bc1d8d62](https://linux-hardware.org/?probe=44bc1d8d62) | May 17, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7d8b9d4be1](https://linux-hardware.org/?probe=7d8b9d4be1) | May 16, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [996d19a70c](https://linux-hardware.org/?probe=996d19a70c) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3bd39e50a8](https://linux-hardware.org/?probe=3bd39e50a8) | May 15, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [82db8cdf8a](https://linux-hardware.org/?probe=82db8cdf8a) | May 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [66f97c57e2](https://linux-hardware.org/?probe=66f97c57e2) | May 14, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [4ac75a003b](https://linux-hardware.org/?probe=4ac75a003b) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [a130b1b1d0](https://linux-hardware.org/?probe=a130b1b1d0) | May 14, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [66ae15a360](https://linux-hardware.org/?probe=66ae15a360) | May 14, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [7d8bb12818](https://linux-hardware.org/?probe=7d8bb12818) | May 14, 2023 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [6a84af6428](https://linux-hardware.org/?probe=6a84af6428) | May 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [53bfb33732](https://linux-hardware.org/?probe=53bfb33732) | May 13, 2023 |
| ASRock        | H510M-ITX/ac                | Desktop     | [9a8da03c1e](https://linux-hardware.org/?probe=9a8da03c1e) | May 12, 2023 |
| Sony          | SVE1513Z1EB                 | Notebook    | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| Biostar       | A68N-5600E                  | Desktop     | [55db0c720e](https://linux-hardware.org/?probe=55db0c720e) | May 12, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [55046e008f](https://linux-hardware.org/?probe=55046e008f) | May 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [17d57b61d7](https://linux-hardware.org/?probe=17d57b61d7) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [fb307bc1bb](https://linux-hardware.org/?probe=fb307bc1bb) | May 11, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a9df4bc7fb](https://linux-hardware.org/?probe=a9df4bc7fb) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6fd3dea188](https://linux-hardware.org/?probe=6fd3dea188) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [e55b8813e3](https://linux-hardware.org/?probe=e55b8813e3) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [58a9b45939](https://linux-hardware.org/?probe=58a9b45939) | May 09, 2023 |
| Dell          | Latitude 5310               | Notebook    | [d72db172f0](https://linux-hardware.org/?probe=d72db172f0) | May 07, 2023 |
| Toshiba       | TECRA A11                   | Notebook    | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [40d1bba9e2](https://linux-hardware.org/?probe=40d1bba9e2) | May 07, 2023 |
| Lenovo        | 1038 SDK0Q40104 WIN 3305... | Server      | [7630762f0e](https://linux-hardware.org/?probe=7630762f0e) | May 06, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [d7c37a25de](https://linux-hardware.org/?probe=d7c37a25de) | May 05, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [a7e0c2d3b6](https://linux-hardware.org/?probe=a7e0c2d3b6) | May 05, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [470632e542](https://linux-hardware.org/?probe=470632e542) | May 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [65ddedbd24](https://linux-hardware.org/?probe=65ddedbd24) | May 05, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [c9b6063699](https://linux-hardware.org/?probe=c9b6063699) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0d4ad3c608](https://linux-hardware.org/?probe=0d4ad3c608) | May 04, 2023 |
| Medion        | MS-7848                     | Desktop     | [ab7b4e658f](https://linux-hardware.org/?probe=ab7b4e658f) | May 03, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [b8764f73bc](https://linux-hardware.org/?probe=b8764f73bc) | May 03, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [da5caa8155](https://linux-hardware.org/?probe=da5caa8155) | May 03, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [22f50229d9](https://linux-hardware.org/?probe=22f50229d9) | May 03, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a99c9cd007](https://linux-hardware.org/?probe=a99c9cd007) | May 02, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [79bad18cb6](https://linux-hardware.org/?probe=79bad18cb6) | May 02, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [9ca19209fd](https://linux-hardware.org/?probe=9ca19209fd) | May 01, 2023 |
| Lenovo        | Tablet 10 20L3000KGE        | Tablet      | [05edd845df](https://linux-hardware.org/?probe=05edd845df) | May 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [3fc2c4e9d9](https://linux-hardware.org/?probe=3fc2c4e9d9) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [e3984b7285](https://linux-hardware.org/?probe=e3984b7285) | May 01, 2023 |
| Medion        | E16402                      | Notebook    | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [86e1a89b72](https://linux-hardware.org/?probe=86e1a89b72) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [91011c02d6](https://linux-hardware.org/?probe=91011c02d6) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [c374148e49](https://linux-hardware.org/?probe=c374148e49) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [e70ee6019c](https://linux-hardware.org/?probe=e70ee6019c) | Apr 29, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [7ce0658b0f](https://linux-hardware.org/?probe=7ce0658b0f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | Notebook    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1404923301](https://linux-hardware.org/?probe=1404923301) | Apr 28, 2023 |
| HP            | 8715                        | Mini pc     | [8d210cce39](https://linux-hardware.org/?probe=8d210cce39) | Apr 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [0fecf73eea](https://linux-hardware.org/?probe=0fecf73eea) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [57261fe5ec](https://linux-hardware.org/?probe=57261fe5ec) | Apr 27, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [1fa553ab02](https://linux-hardware.org/?probe=1fa553ab02) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| Biostar       | A68N-5600E                  | Desktop     | [ccaeaae27b](https://linux-hardware.org/?probe=ccaeaae27b) | Apr 25, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f76dc1b9b7](https://linux-hardware.org/?probe=f76dc1b9b7) | Apr 24, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [0d6278dd3a](https://linux-hardware.org/?probe=0d6278dd3a) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a7359e872e](https://linux-hardware.org/?probe=a7359e872e) | Apr 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [d315f00cd8](https://linux-hardware.org/?probe=d315f00cd8) | Apr 21, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [3219512811](https://linux-hardware.org/?probe=3219512811) | Apr 20, 2023 |
| Medion        | P17605                      | Notebook    | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [bebc7ec91b](https://linux-hardware.org/?probe=bebc7ec91b) | Apr 19, 2023 |
| Acer          | AS5755                      | Notebook    | [1c163eb17f](https://linux-hardware.org/?probe=1c163eb17f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b425e2afaf](https://linux-hardware.org/?probe=b425e2afaf) | Apr 18, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [52272d52d3](https://linux-hardware.org/?probe=52272d52d3) | Apr 18, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c00d85072e](https://linux-hardware.org/?probe=c00d85072e) | Apr 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [aa1a6072ce](https://linux-hardware.org/?probe=aa1a6072ce) | Apr 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3ad72b64d](https://linux-hardware.org/?probe=f3ad72b64d) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [19bb54bd98](https://linux-hardware.org/?probe=19bb54bd98) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | Notebook    | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [fad0ef7fef](https://linux-hardware.org/?probe=fad0ef7fef) | Apr 16, 2023 |
| Medion        | E7220                       | Notebook    | [ab189f426b](https://linux-hardware.org/?probe=ab189f426b) | Apr 15, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [b5f4a1670f](https://linux-hardware.org/?probe=b5f4a1670f) | Apr 13, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c639e22b34](https://linux-hardware.org/?probe=c639e22b34) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [2f7cf166f0](https://linux-hardware.org/?probe=2f7cf166f0) | Apr 11, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [32867fa30e](https://linux-hardware.org/?probe=32867fa30e) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [5c0467f4cb](https://linux-hardware.org/?probe=5c0467f4cb) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [f410666614](https://linux-hardware.org/?probe=f410666614) | Apr 09, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [44351926f8](https://linux-hardware.org/?probe=44351926f8) | Apr 08, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [11aee4ed7b](https://linux-hardware.org/?probe=11aee4ed7b) | Apr 08, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a651483f3c](https://linux-hardware.org/?probe=a651483f3c) | Apr 07, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | Notebook    | [e9fa009df9](https://linux-hardware.org/?probe=e9fa009df9) | Apr 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [0ca203f8b0](https://linux-hardware.org/?probe=0ca203f8b0) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [b81dc294df](https://linux-hardware.org/?probe=b81dc294df) | Apr 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [62debd585f](https://linux-hardware.org/?probe=62debd585f) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [8e769590fb](https://linux-hardware.org/?probe=8e769590fb) | Apr 05, 2023 |
| HP            | 2B52                        | Desktop     | [4def1937bc](https://linux-hardware.org/?probe=4def1937bc) | Apr 04, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [89962b2435](https://linux-hardware.org/?probe=89962b2435) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e33abdae24](https://linux-hardware.org/?probe=e33abdae24) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9f9f72230c](https://linux-hardware.org/?probe=9f9f72230c) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [2cbd354a8f](https://linux-hardware.org/?probe=2cbd354a8f) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [a3c3e3267a](https://linux-hardware.org/?probe=a3c3e3267a) | Apr 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [774af9fced](https://linux-hardware.org/?probe=774af9fced) | Apr 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [68dade8d0a](https://linux-hardware.org/?probe=68dade8d0a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | Notebook    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [bcd377dcb7](https://linux-hardware.org/?probe=bcd377dcb7) | Apr 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b272d7b271](https://linux-hardware.org/?probe=b272d7b271) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [222fde0a83](https://linux-hardware.org/?probe=222fde0a83) | Mar 31, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [029afd6a5c](https://linux-hardware.org/?probe=029afd6a5c) | Mar 31, 2023 |
| HP            | EliteBook 2530p (KR059AV... | Notebook    | [e7f9bce466](https://linux-hardware.org/?probe=e7f9bce466) | Mar 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fcb2279eb0](https://linux-hardware.org/?probe=fcb2279eb0) | Mar 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [514d8ed8d6](https://linux-hardware.org/?probe=514d8ed8d6) | Mar 30, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [225e13e1f0](https://linux-hardware.org/?probe=225e13e1f0) | Mar 30, 2023 |
| HP            | Pavilion 17                 | Notebook    | [46e0a0aed1](https://linux-hardware.org/?probe=46e0a0aed1) | Mar 30, 2023 |
| HP            | Pavilion 17                 | Notebook    | [3da4500905](https://linux-hardware.org/?probe=3da4500905) | Mar 30, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [147c0afb99](https://linux-hardware.org/?probe=147c0afb99) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b165f54c80](https://linux-hardware.org/?probe=b165f54c80) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [9f3138d8d5](https://linux-hardware.org/?probe=9f3138d8d5) | Mar 27, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| HP            | 8158 A01                    | Mini pc     | [8d1c60fe86](https://linux-hardware.org/?probe=8d1c60fe86) | Mar 26, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [ad2be3eba7](https://linux-hardware.org/?probe=ad2be3eba7) | Mar 26, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [3c68ddf942](https://linux-hardware.org/?probe=3c68ddf942) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HP            | 1497                        | Desktop     | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [64485e9b53](https://linux-hardware.org/?probe=64485e9b53) | Mar 25, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [9320ecf2b2](https://linux-hardware.org/?probe=9320ecf2b2) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| Lenovo        | 3746 WIN SDK0T76463 3422... | All in one  | [ec07bb84cf](https://linux-hardware.org/?probe=ec07bb84cf) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [2f5c339d88](https://linux-hardware.org/?probe=2f5c339d88) | Mar 25, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [befbe47acc](https://linux-hardware.org/?probe=befbe47acc) | Mar 23, 2023 |
| Unknown       | Unknown                     | Soc         | [4a630d847a](https://linux-hardware.org/?probe=4a630d847a) | Mar 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b293f3ba3e](https://linux-hardware.org/?probe=b293f3ba3e) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | Notebook    | [f4830d41d6](https://linux-hardware.org/?probe=f4830d41d6) | Mar 21, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [32116dbba8](https://linux-hardware.org/?probe=32116dbba8) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [844b9094f9](https://linux-hardware.org/?probe=844b9094f9) | Mar 21, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [42629ad13b](https://linux-hardware.org/?probe=42629ad13b) | Mar 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c7c5415a8c](https://linux-hardware.org/?probe=c7c5415a8c) | Mar 21, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [aef19ecbd7](https://linux-hardware.org/?probe=aef19ecbd7) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [82d9122ebf](https://linux-hardware.org/?probe=82d9122ebf) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [192fe75be4](https://linux-hardware.org/?probe=192fe75be4) | Mar 19, 2023 |
| HP            | 8715                        | Mini pc     | [1c2c765978](https://linux-hardware.org/?probe=1c2c765978) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [fcb7a079cf](https://linux-hardware.org/?probe=fcb7a079cf) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [cd9310c350](https://linux-hardware.org/?probe=cd9310c350) | Mar 17, 2023 |
| HP            | EliteBook 1050 G1           | Notebook    | [6dcfa134ac](https://linux-hardware.org/?probe=6dcfa134ac) | Mar 16, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [1f081ed675](https://linux-hardware.org/?probe=1f081ed675) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [8f1af30bba](https://linux-hardware.org/?probe=8f1af30bba) | Mar 15, 2023 |
| HP            | 8715                        | Mini pc     | [7f9acb1f3e](https://linux-hardware.org/?probe=7f9acb1f3e) | Mar 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [36eacafa6f](https://linux-hardware.org/?probe=36eacafa6f) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| HP            | 2B52                        | Desktop     | [b541e6085e](https://linux-hardware.org/?probe=b541e6085e) | Mar 14, 2023 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [02c6d19dfa](https://linux-hardware.org/?probe=02c6d19dfa) | Mar 14, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [c9936da6ba](https://linux-hardware.org/?probe=c9936da6ba) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | Notebook    | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ASUSTek       | PN40                        | Mini pc     | [8c5e382d0a](https://linux-hardware.org/?probe=8c5e382d0a) | Mar 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6661b1166](https://linux-hardware.org/?probe=b6661b1166) | Mar 10, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| Samsung       | 950QDB                      | Convertible | [1ed34d5e26](https://linux-hardware.org/?probe=1ed34d5e26) | Mar 09, 2023 |
| Samsung       | 950QDB                      | Convertible | [1d1e08a117](https://linux-hardware.org/?probe=1d1e08a117) | Mar 09, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [1470c9fc46](https://linux-hardware.org/?probe=1470c9fc46) | Mar 09, 2023 |
| MSI           | Z68MA-ED55                  | Desktop     | [17a3d0c88b](https://linux-hardware.org/?probe=17a3d0c88b) | Mar 09, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [7d6aa1edeb](https://linux-hardware.org/?probe=7d6aa1edeb) | Mar 08, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [c1339ac8de](https://linux-hardware.org/?probe=c1339ac8de) | Mar 08, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [44c6479881](https://linux-hardware.org/?probe=44c6479881) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Clevo         | P370EM                      | Notebook    | [4ac46a0dab](https://linux-hardware.org/?probe=4ac46a0dab) | Mar 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a4ab100e59](https://linux-hardware.org/?probe=a4ab100e59) | Mar 07, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [b27b730e8f](https://linux-hardware.org/?probe=b27b730e8f) | Mar 06, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [1e09dd1123](https://linux-hardware.org/?probe=1e09dd1123) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [422fa2cf16](https://linux-hardware.org/?probe=422fa2cf16) | Mar 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [72b59f777e](https://linux-hardware.org/?probe=72b59f777e) | Mar 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [6ff1d34454](https://linux-hardware.org/?probe=6ff1d34454) | Feb 28, 2023 |
| ASRock        | G41M-S                      | Desktop     | [8802d04f08](https://linux-hardware.org/?probe=8802d04f08) | Feb 27, 2023 |
| HP            | 3397                        | Desktop     | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [a9605bf85e](https://linux-hardware.org/?probe=a9605bf85e) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3ab842532b](https://linux-hardware.org/?probe=3ab842532b) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| Dell          | Latitude E7250              | Notebook    | [db6ac786ef](https://linux-hardware.org/?probe=db6ac786ef) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [c8006c3bd5](https://linux-hardware.org/?probe=c8006c3bd5) | Feb 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2943aa6cd7](https://linux-hardware.org/?probe=2943aa6cd7) | Feb 25, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [d4a6916e4f](https://linux-hardware.org/?probe=d4a6916e4f) | Feb 24, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [0c69e8ef9b](https://linux-hardware.org/?probe=0c69e8ef9b) | Feb 23, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [bcae8ff254](https://linux-hardware.org/?probe=bcae8ff254) | Feb 23, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [49007433d0](https://linux-hardware.org/?probe=49007433d0) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [e67cca4a6c](https://linux-hardware.org/?probe=e67cca4a6c) | Feb 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [09c45a0b09](https://linux-hardware.org/?probe=09c45a0b09) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f5a22b7bb9](https://linux-hardware.org/?probe=f5a22b7bb9) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [72b8072c9a](https://linux-hardware.org/?probe=72b8072c9a) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1263eaf1f9](https://linux-hardware.org/?probe=1263eaf1f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [f49ba07c1e](https://linux-hardware.org/?probe=f49ba07c1e) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | A78M-E35                    | Desktop     | [30c75db366](https://linux-hardware.org/?probe=30c75db366) | Feb 16, 2023 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [9c461d33db](https://linux-hardware.org/?probe=9c461d33db) | Feb 16, 2023 |
| Medion        | E7220                       | Notebook    | [dd9de8bf69](https://linux-hardware.org/?probe=dd9de8bf69) | Feb 15, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3S... | Notebook    | [580215c6bb](https://linux-hardware.org/?probe=580215c6bb) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Notebook    | [ca4349a929](https://linux-hardware.org/?probe=ca4349a929) | Feb 15, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d2d359be39](https://linux-hardware.org/?probe=d2d359be39) | Feb 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [72b8d495ff](https://linux-hardware.org/?probe=72b8d495ff) | Feb 13, 2023 |
| Acer          | Aspire 7740                 | Notebook    | [caeb61e835](https://linux-hardware.org/?probe=caeb61e835) | Feb 12, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [78e7a0ae85](https://linux-hardware.org/?probe=78e7a0ae85) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [f2f95aef80](https://linux-hardware.org/?probe=f2f95aef80) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [74013e0688](https://linux-hardware.org/?probe=74013e0688) | Feb 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502FBA... | Convertible | [dd34aed5d9](https://linux-hardware.org/?probe=dd34aed5d9) | Feb 11, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [b7e924b0cd](https://linux-hardware.org/?probe=b7e924b0cd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T450 20BUS1110E    | Notebook    | [d08c46c46d](https://linux-hardware.org/?probe=d08c46c46d) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| ASUSTek       | P8P67 WS REVOLUTION         | Desktop     | [c0190f8f57](https://linux-hardware.org/?probe=c0190f8f57) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Dell          | Inspiron 7586               | Convertible | [732b3c8fb1](https://linux-hardware.org/?probe=732b3c8fb1) | Feb 05, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [3407774ba7](https://linux-hardware.org/?probe=3407774ba7) | Feb 05, 2023 |
| HP            | 0A98h                       | Desktop     | [1d3ae20ff5](https://linux-hardware.org/?probe=1d3ae20ff5) | Feb 04, 2023 |
| Dell          | MXG061                      | Notebook    | [40883298a9](https://linux-hardware.org/?probe=40883298a9) | Feb 04, 2023 |
| Dell          | 0D28YY A03                  | Desktop     | [ae7eeb7487](https://linux-hardware.org/?probe=ae7eeb7487) | Feb 04, 2023 |
| Dell          | 0D28YY A03                  | Desktop     | [0fe32fbdc2](https://linux-hardware.org/?probe=0fe32fbdc2) | Feb 04, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [063a4bb843](https://linux-hardware.org/?probe=063a4bb843) | Feb 03, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [82845bb849](https://linux-hardware.org/?probe=82845bb849) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [c68678a1a5](https://linux-hardware.org/?probe=c68678a1a5) | Jan 31, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8b43efc7ea](https://linux-hardware.org/?probe=8b43efc7ea) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [d528677cfd](https://linux-hardware.org/?probe=d528677cfd) | Jan 28, 2023 |
| HP            | 1495                        | Desktop     | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [6e5884ec0c](https://linux-hardware.org/?probe=6e5884ec0c) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [f1c0237cc0](https://linux-hardware.org/?probe=f1c0237cc0) | Jan 22, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2b5b2da951](https://linux-hardware.org/?probe=2b5b2da951) | Jan 20, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| MSI           | VR630                       | Notebook    | [943c1d68fa](https://linux-hardware.org/?probe=943c1d68fa) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a5cbba39d7](https://linux-hardware.org/?probe=a5cbba39d7) | Jan 19, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [4197c5f3d3](https://linux-hardware.org/?probe=4197c5f3d3) | Jan 19, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [a56a3691e9](https://linux-hardware.org/?probe=a56a3691e9) | Jan 18, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [c99128e783](https://linux-hardware.org/?probe=c99128e783) | Jan 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [b68853abf6](https://linux-hardware.org/?probe=b68853abf6) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [80f9124e5a](https://linux-hardware.org/?probe=80f9124e5a) | Jan 14, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [81d232a246](https://linux-hardware.org/?probe=81d232a246) | Jan 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [ba09b2045b](https://linux-hardware.org/?probe=ba09b2045b) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c3a30838c3](https://linux-hardware.org/?probe=c3a30838c3) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Latitude E5550              | Notebook    | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Medion        | E6222                       | Notebook    | [e3b3da28fa](https://linux-hardware.org/?probe=e3b3da28fa) | Jan 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e608d09ac5](https://linux-hardware.org/?probe=e608d09ac5) | Jan 11, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [0ddddc438d](https://linux-hardware.org/?probe=0ddddc438d) | Jan 11, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [7d56f2f733](https://linux-hardware.org/?probe=7d56f2f733) | Jan 11, 2023 |
| Dell          | Latitude E7440              | Notebook    | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [0f0b38970a](https://linux-hardware.org/?probe=0f0b38970a) | Jan 11, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b2d69bd762](https://linux-hardware.org/?probe=b2d69bd762) | Jan 11, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [3e54ca06f5](https://linux-hardware.org/?probe=3e54ca06f5) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fbde9a1dba](https://linux-hardware.org/?probe=fbde9a1dba) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [95aadb3cc4](https://linux-hardware.org/?probe=95aadb3cc4) | Jan 09, 2023 |
| Sony          | SVE1512H1EB                 | Notebook    | [723e8bfbe6](https://linux-hardware.org/?probe=723e8bfbe6) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [297380c89a](https://linux-hardware.org/?probe=297380c89a) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| Acer          | Iconia W700                 | Notebook    | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d67718b4e8](https://linux-hardware.org/?probe=d67718b4e8) | Jan 08, 2023 |
| Google        | Kled                        | Notebook    | [3cb98a4497](https://linux-hardware.org/?probe=3cb98a4497) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | Notebook    | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Sony          | VPCEH2D0E                   | Notebook    | [78367f11f5](https://linux-hardware.org/?probe=78367f11f5) | Jan 04, 2023 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [e6ee0cd764](https://linux-hardware.org/?probe=e6ee0cd764) | Jan 04, 2023 |
| ASUSTek       | K93SM                       | Notebook    | [c0fb78e9a3](https://linux-hardware.org/?probe=c0fb78e9a3) | Jan 03, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a35156e0c3](https://linux-hardware.org/?probe=a35156e0c3) | Jan 02, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [8f4f98da64](https://linux-hardware.org/?probe=8f4f98da64) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| Dell          | Latitude 7430               | Notebook    | [ad796336f7](https://linux-hardware.org/?probe=ad796336f7) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | Notebook    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [cdc31b8338](https://linux-hardware.org/?probe=cdc31b8338) | Dec 30, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [de6ea0ae2e](https://linux-hardware.org/?probe=de6ea0ae2e) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c28fb2edb2](https://linux-hardware.org/?probe=c28fb2edb2) | Dec 30, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [f725a0095a](https://linux-hardware.org/?probe=f725a0095a) | Dec 30, 2022 |
| Supermicro    | H8SCM                       | Server      | [9ee42dcf6f](https://linux-hardware.org/?probe=9ee42dcf6f) | Dec 29, 2022 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [6e3a112190](https://linux-hardware.org/?probe=6e3a112190) | Dec 28, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [d680b8dd2a](https://linux-hardware.org/?probe=d680b8dd2a) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [e8dce940d8](https://linux-hardware.org/?probe=e8dce940d8) | Dec 26, 2022 |
| Medion        | X782X/X783X                 | Notebook    | [a8befc040f](https://linux-hardware.org/?probe=a8befc040f) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | Desktop     | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [a6be229477](https://linux-hardware.org/?probe=a6be229477) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [26a548a6f3](https://linux-hardware.org/?probe=26a548a6f3) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [431eac7d11](https://linux-hardware.org/?probe=431eac7d11) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [8e15fef839](https://linux-hardware.org/?probe=8e15fef839) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [74207a9fec](https://linux-hardware.org/?probe=74207a9fec) | Dec 19, 2022 |
| Google        | Cyan                        | Notebook    | [fff3502929](https://linux-hardware.org/?probe=fff3502929) | Dec 19, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [88d7491a00](https://linux-hardware.org/?probe=88d7491a00) | Dec 19, 2022 |
| AXDIA Inte... | myBook PRO14 SE V2          | Notebook    | [14b79d7a8b](https://linux-hardware.org/?probe=14b79d7a8b) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [fa03fe621a](https://linux-hardware.org/?probe=fa03fe621a) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [8480834751](https://linux-hardware.org/?probe=8480834751) | Dec 17, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [d0d30cd96f](https://linux-hardware.org/?probe=d0d30cd96f) | Dec 14, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [943bcd1d12](https://linux-hardware.org/?probe=943bcd1d12) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [fd77b80943](https://linux-hardware.org/?probe=fd77b80943) | Dec 12, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [37267c6b3f](https://linux-hardware.org/?probe=37267c6b3f) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [b518609312](https://linux-hardware.org/?probe=b518609312) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [f815a2e4a3](https://linux-hardware.org/?probe=f815a2e4a3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e0b1d50b7c](https://linux-hardware.org/?probe=e0b1d50b7c) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [cc2d9043d9](https://linux-hardware.org/?probe=cc2d9043d9) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [f6341e7afb](https://linux-hardware.org/?probe=f6341e7afb) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [50e5b72a10](https://linux-hardware.org/?probe=50e5b72a10) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [b7171256c0](https://linux-hardware.org/?probe=b7171256c0) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | Desktop     | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [cd166beede](https://linux-hardware.org/?probe=cd166beede) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [2b34016cad](https://linux-hardware.org/?probe=2b34016cad) | Dec 04, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [f0c20f1a0a](https://linux-hardware.org/?probe=f0c20f1a0a) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [790ae8be94](https://linux-hardware.org/?probe=790ae8be94) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [373dac5bbb](https://linux-hardware.org/?probe=373dac5bbb) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [eb13a8db03](https://linux-hardware.org/?probe=eb13a8db03) | Dec 02, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [07ff06f360](https://linux-hardware.org/?probe=07ff06f360) | Dec 02, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [d7694493c0](https://linux-hardware.org/?probe=d7694493c0) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [01dfdc071e](https://linux-hardware.org/?probe=01dfdc071e) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [9aa4880856](https://linux-hardware.org/?probe=9aa4880856) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [c1f5a1f413](https://linux-hardware.org/?probe=c1f5a1f413) | Dec 01, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| W271ELQ       | Unknown                     | Notebook    | [ae170d1e81](https://linux-hardware.org/?probe=ae170d1e81) | Dec 01, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ae01075720](https://linux-hardware.org/?probe=ae01075720) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 264       | 11.44%  |
| Ubuntu 22.04                 | 144       | 6.24%   |
| Ubuntu 18.04                 | 126       | 5.46%   |
| Arch Rolling                 | 67        | 2.9%    |
| OpenMandriva 4.3             | 54        | 2.34%   |
| Debian 11                    | 53        | 2.3%    |
| Arch                         | 46        | 1.99%   |
| Linux Mint 20.2              | 44        | 1.91%   |
| Zorin 16                     | 42        | 1.82%   |
| OpenMandriva 4.2             | 41        | 1.78%   |
| Manjaro                      | 36        | 1.56%   |
| Fedora 35                    | 34        | 1.47%   |
| Debian 12                    | 34        | 1.47%   |
| Pop!_OS 22.04                | 33        | 1.43%   |
| Fedora 37                    | 33        | 1.43%   |
| Linux Mint 21.1              | 32        | 1.39%   |
| Linux Mint 21.2              | 31        | 1.34%   |
| Fedora 38                    | 29        | 1.26%   |
| Ubuntu 21.04                 | 28        | 1.21%   |
| Linux Mint 20.1              | 27        | 1.17%   |
| BlackPanther 18.1            | 27        | 1.17%   |
| Linux Mint 19.3              | 26        | 1.13%   |
| Fedora 39                    | 26        | 1.13%   |
| EndeavourOS Rolling          | 25        | 1.08%   |
| Ubuntu 20.10                 | 23        | 1%      |
| Linux Mint 20                | 22        | 0.95%   |
| Fedora 33                    | 22        | 0.95%   |
| OpenMandriva 23.01           | 21        | 0.91%   |
| Linux Mint 20.3              | 21        | 0.91%   |
| Ubuntu 22.10                 | 20        | 0.87%   |
| Fedora 32                    | 20        | 0.87%   |
| ArcoLinux Rolling            | 20        | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 19        | 0.82%   |
| KDE neon 20.04               | 19        | 0.82%   |
| Fedora 34                    | 19        | 0.82%   |
| Ubuntu 23.04                 | 18        | 0.78%   |
| Ubuntu 19.10                 | 18        | 0.78%   |
| Xubuntu 20.04                | 17        | 0.74%   |
| Ubuntu 21.10                 | 17        | 0.74%   |
| Pop!_OS 20.10                | 17        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 674       | 31.16%  |
| Linux Mint    | 220       | 10.17%  |
| Fedora        | 175       | 8.09%   |
| OpenMandriva  | 156       | 7.21%   |
| Debian        | 123       | 5.69%   |
| Arch          | 108       | 4.99%   |
| Manjaro       | 100       | 4.62%   |
| Pop!_OS       | 79        | 3.65%   |
| Zorin         | 58        | 2.68%   |
| Kubuntu       | 40        | 1.85%   |
| ROSA          | 36        | 1.66%   |
| Xubuntu       | 32        | 1.48%   |
| openSUSE      | 32        | 1.48%   |
| BlackPanther  | 30        | 1.39%   |
| KDE neon      | 29        | 1.34%   |
| Elementary    | 27        | 1.25%   |
| EndeavourOS   | 25        | 1.16%   |
| ArcoLinux     | 21        | 0.97%   |
| Ubuntu MATE   | 15        | 0.69%   |
| SteamOS       | 15        | 0.69%   |
| Gentoo        | 15        | 0.69%   |
| Nobara        | 11        | 0.51%   |
| Endless       | 11        | 0.51%   |
| LMDE          | 10        | 0.46%   |
| Ubuntu Unity  | 9         | 0.42%   |
| Ubuntu Budgie | 9         | 0.42%   |
| MX            | 8         | 0.37%   |
| Kali          | 8         | 0.37%   |
| NixOS         | 7         | 0.32%   |
| Clear Linux   | 6         | 0.28%   |
| Ubuntu Studio | 5         | 0.23%   |
| Raspbian      | 5         | 0.23%   |
| Lubuntu       | 5         | 0.23%   |
| Garuda Linux  | 5         | 0.23%   |
| Siduction     | 4         | 0.18%   |
| Parrot        | 4         | 0.18%   |
| Xero          | 3         | 0.14%   |
| TUXEDO OS     | 3         | 0.14%   |
| Deepin        | 3         | 0.14%   |
| CentOS        | 3         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 54        | 2.11%   |
| 5.10.14-desktop-1omv4002 | 40        | 1.56%   |
| 5.4.0-42-generic         | 30        | 1.17%   |
| 5.15.0-56-generic        | 24        | 0.94%   |
| 5.4.0-58-generic         | 21        | 0.82%   |
| 6.2.6-desktop-1omv2390   | 18        | 0.7%    |
| 5.4.0-52-generic         | 18        | 0.7%    |
| 5.15.0-52-generic        | 18        | 0.7%    |
| 5.15.0-43-generic        | 18        | 0.7%    |
| 4.18.16-desktop-1bP      | 18        | 0.7%    |
| 6.1.1-desktop-1omv2290   | 17        | 0.66%   |
| 5.13.0-39-generic        | 17        | 0.66%   |
| 5.3.0-46-generic         | 16        | 0.63%   |
| 5.15.0-58-generic        | 16        | 0.63%   |
| 5.4.0-91-generic         | 14        | 0.55%   |
| 5.4.0-48-generic         | 13        | 0.51%   |
| 5.4.0-26-generic         | 13        | 0.51%   |
| 5.13.0-27-generic        | 13        | 0.51%   |
| 5.4.0-74-generic         | 12        | 0.47%   |
| 5.4.0-33-generic         | 12        | 0.47%   |
| 5.4.0-28-generic         | 12        | 0.47%   |
| 5.13.0-28-generic        | 12        | 0.47%   |
| 5.11.0-37-generic        | 12        | 0.47%   |
| 6.5.0-14-generic         | 11        | 0.43%   |
| 5.6.14-desktop-2bP       | 11        | 0.43%   |
| 5.4.0-29-generic         | 11        | 0.43%   |
| 5.3.0-26-generic         | 11        | 0.43%   |
| 5.19.0-46-generic        | 11        | 0.43%   |
| 6.2.6-76060206-generic   | 10        | 0.39%   |
| 5.8.0-7630-generic       | 10        | 0.39%   |
| 5.19.0-35-generic        | 10        | 0.39%   |
| 5.15.0-91-generic        | 10        | 0.39%   |
| 5.15.0-47-generic        | 10        | 0.39%   |
| 5.11.0-27-generic        | 10        | 0.39%   |
| 5.11.0-25-generic        | 10        | 0.39%   |
| 6.2.0-39-generic         | 9         | 0.35%   |
| 5.4.0-80-generic         | 9         | 0.35%   |
| 5.4.0-72-generic         | 9         | 0.35%   |
| 5.3.0-42-generic         | 9         | 0.35%   |
| 5.19.0-38-generic        | 9         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 317       | 13.09%  |
| 5.15.0  | 223       | 9.21%   |
| 5.13.0  | 115       | 4.75%   |
| 5.11.0  | 103       | 4.25%   |
| 4.15.0  | 103       | 4.25%   |
| 5.8.0   | 94        | 3.88%   |
| 5.19.0  | 71        | 2.93%   |
| 5.3.0   | 66        | 2.73%   |
| 6.2.0   | 65        | 2.68%   |
| 5.16.7  | 56        | 2.31%   |
| 5.10.0  | 56        | 2.31%   |
| 6.1.0   | 42        | 1.73%   |
| 5.10.14 | 42        | 1.73%   |
| 6.2.6   | 35        | 1.45%   |
| 5.0.0   | 35        | 1.45%   |
| 4.18.0  | 34        | 1.4%    |
| 4.19.0  | 22        | 0.91%   |
| 6.5.0   | 20        | 0.83%   |
| 6.1.1   | 18        | 0.74%   |
| 4.18.16 | 18        | 0.74%   |
| 6.4.11  | 12        | 0.5%    |
| 6.6.6   | 11        | 0.45%   |
| 5.6.14  | 11        | 0.45%   |
| 5.17.5  | 11        | 0.45%   |
| 5.12.4  | 9         | 0.37%   |
| 6.6.8   | 8         | 0.33%   |
| 6.5.6   | 8         | 0.33%   |
| 6.3.5   | 8         | 0.33%   |
| 6.0.7   | 8         | 0.33%   |
| 5.9.11  | 8         | 0.33%   |
| 4.9.60  | 8         | 0.33%   |
| 4.4.0   | 8         | 0.33%   |
| 6.2.11  | 7         | 0.29%   |
| 5.9.16  | 7         | 0.29%   |
| 5.16.0  | 7         | 0.29%   |
| 5.15.12 | 7         | 0.29%   |
| 6.6.2   | 6         | 0.25%   |
| 6.5.3   | 6         | 0.25%   |
| 6.2.8   | 6         | 0.25%   |
| 6.2.12  | 6         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 352       | 14.79%  |
| 5.15    | 279       | 11.72%  |
| 5.10    | 139       | 5.84%   |
| 5.13    | 137       | 5.76%   |
| 6.2     | 136       | 5.71%   |
| 5.11    | 125       | 5.25%   |
| 5.8     | 124       | 5.21%   |
| 6.1     | 111       | 4.66%   |
| 4.15    | 103       | 4.33%   |
| 5.19    | 96        | 4.03%   |
| 5.16    | 86        | 3.61%   |
| 5.3     | 79        | 3.32%   |
| 6.5     | 54        | 2.27%   |
| 4.18    | 54        | 2.27%   |
| 6.6     | 53        | 2.23%   |
| 6.0     | 49        | 2.06%   |
| 5.17    | 37        | 1.55%   |
| 5.0     | 36        | 1.51%   |
| 6.4     | 35        | 1.47%   |
| 5.9     | 33        | 1.39%   |
| 5.6     | 32        | 1.34%   |
| 4.19    | 30        | 1.26%   |
| 5.12    | 28        | 1.18%   |
| 5.18    | 26        | 1.09%   |
| 6.3     | 25        | 1.05%   |
| 5.7     | 25        | 1.05%   |
| 5.14    | 23        | 0.97%   |
| 4.9     | 21        | 0.88%   |
| 5.5     | 11        | 0.46%   |
| 4.4     | 9         | 0.38%   |
| 4.17    | 4         | 0.17%   |
| 4.12    | 4         | 0.17%   |
| 4.1     | 4         | 0.17%   |
| 5.2     | 3         | 0.13%   |
| 4.10    | 3         | 0.13%   |
| 3.10    | 3         | 0.13%   |
| 5.1     | 2         | 0.08%   |
| 4.13    | 2         | 0.08%   |
| 6.8     | 1         | 0.04%   |
| 6.7     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2044      | 97.89%  |
| i686    | 20        | 0.96%   |
| aarch64 | 17        | 0.81%   |
| armv7l  | 7         | 0.34%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 917       | 42.34%  |
| KDE5             | 411       | 18.98%  |
| Unknown          | 243       | 11.22%  |
| X-Cinnamon       | 180       | 8.31%   |
| XFCE             | 157       | 7.25%   |
| MATE             | 58        | 2.68%   |
| KDE              | 39        | 1.8%    |
| Pantheon         | 27        | 1.25%   |
| Cinnamon         | 23        | 1.06%   |
| KDE4             | 19        | 0.88%   |
| Budgie           | 14        | 0.65%   |
| LXQt             | 13        | 0.6%    |
| i3               | 13        | 0.6%    |
| Unity            | 9         | 0.42%   |
| LXDE             | 8         | 0.37%   |
| Deepin           | 6         | 0.28%   |
| awesome          | 6         | 0.28%   |
| sway             | 4         | 0.18%   |
| GNOME Flashback  | 4         | 0.18%   |
| xmonad           | 2         | 0.09%   |
| lightdm-xsession | 2         | 0.09%   |
| Hyprland         | 2         | 0.09%   |
| qtile            | 1         | 0.05%   |
| openbox          | 1         | 0.05%   |
| leftwm           | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| gamescope        | 1         | 0.05%   |
| fluxbox          | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |
| DWM              | 1         | 0.05%   |
| Bspwm            | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1586      | 73.43%  |
| Wayland | 394       | 18.24%  |
| Unknown | 125       | 5.79%   |
| Tty     | 54        | 2.5%    |
| Web     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 974       | 44.7%   |
| SDDM    | 366       | 16.8%   |
| GDM3    | 282       | 12.94%  |
| LightDM | 245       | 11.24%  |
| GDM     | 232       | 10.65%  |
| TDM     | 50        | 2.29%   |
| KDM     | 20        | 0.92%   |
| SLiM    | 5         | 0.23%   |
| XDM     | 2         | 0.09%   |
| LXDM    | 2         | 0.09%   |
| MDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| de_AT      | 791       | 36.64%  |
| en_US      | 615       | 28.49%  |
| de_DE      | 309       | 14.31%  |
| Unknown    | 227       | 10.51%  |
| en_GB      | 91        | 4.21%   |
| C          | 36        | 1.67%   |
| en_IE      | 17        | 0.79%   |
| pl_PL      | 9         | 0.42%   |
| it_IT      | 8         | 0.37%   |
| es_ES      | 7         | 0.32%   |
| ru_RU      | 5         | 0.23%   |
| en_AT      | 5         | 0.23%   |
| POSIX      | 4         | 0.19%   |
| de_CH      | 4         | 0.19%   |
| tr_TR      | 3         | 0.14%   |
| uk_UA      | 2         | 0.09%   |
| hu_HU      | 2         | 0.09%   |
| en_DE      | 2         | 0.09%   |
| en_CA      | 2         | 0.09%   |
| en_AU      | 2         | 0.09%   |
| de_AT.UTF8 | 2         | 0.09%   |
| cs_CZ      | 2         | 0.09%   |
| sv_SE      | 1         | 0.05%   |
| ro_RO      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| nl_NL      | 1         | 0.05%   |
| nl_BE      | 1         | 0.05%   |
| hr_HR      | 1         | 0.05%   |
| fr_FR      | 1         | 0.05%   |
| fa_IR      | 1         | 0.05%   |
| en_US.UTF8 | 1         | 0.05%   |
| en         | 1         | 0.05%   |
| de_LI      | 1         | 0.05%   |
| da_DK      | 1         | 0.05%   |
| C.UTF8     | 1         | 0.05%   |
| bg_BG      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1137      | 52.96%  |
| BIOS | 1010      | 47.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1537      | 71.46%  |
| Btrfs   | 248       | 11.53%  |
| Overlay | 192       | 8.93%   |
| Unknown | 62        | 2.88%   |
| Tmpfs   | 61        | 2.84%   |
| Xfs     | 23        | 1.07%   |
| Zfs     | 15        | 0.7%    |
| Ext2    | 6         | 0.28%   |
| F2fs    | 2         | 0.09%   |
| Ext3    | 2         | 0.09%   |
| XXXXXXX | 1         | 0.05%   |
| Nfs     | 1         | 0.05%   |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1002      | 46.63%  |
| GPT     | 933       | 43.42%  |
| MBR     | 214       | 9.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1801      | 84.44%  |
| Yes       | 332       | 15.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1474      | 69.23%  |
| Yes       | 655       | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 381       | 18.26%  |
| ASUSTek Computer                     | 366       | 17.54%  |
| Hewlett-Packard                      | 293       | 14.04%  |
| MSI                                  | 155       | 7.43%   |
| Dell                                 | 147       | 7.04%   |
| Acer                                 | 118       | 5.65%   |
| Gigabyte Technology                  | 103       | 4.94%   |
| ASRock                               | 86        | 4.12%   |
| Medion                               | 53        | 2.54%   |
| Apple                                | 44        | 2.11%   |
| Toshiba                              | 28        | 1.34%   |
| Intel                                | 26        | 1.25%   |
| Fujitsu                              | 23        | 1.1%    |
| TUXEDO                               | 22        | 1.05%   |
| Sony                                 | 19        | 0.91%   |
| Unknown                              | 18        | 0.86%   |
| Raspberry Pi Foundation              | 15        | 0.72%   |
| Valve                                | 14        | 0.67%   |
| HUAWEI                               | 13        | 0.62%   |
| Samsung Electronics                  | 11        | 0.53%   |
| Biostar                              | 9         | 0.43%   |
| Microsoft                            | 8         | 0.38%   |
| TrekStor                             | 7         | 0.34%   |
| Notebook                             | 7         | 0.34%   |
| Fujitsu Siemens                      | 6         | 0.29%   |
| Foxconn                              | 6         | 0.29%   |
| ZOTAC                                | 5         | 0.24%   |
| Supermicro                           | 5         | 0.24%   |
| Shuttle                              | 5         | 0.24%   |
| Shenzhen Meigao Electronic Equipment | 5         | 0.24%   |
| BESSTAR Tech                         | 5         | 0.24%   |
| Razer                                | 4         | 0.19%   |
| Hampoo                               | 4         | 0.19%   |
| Clevo                                | 4         | 0.19%   |
| AMI                                  | 4         | 0.19%   |
| Wortmann AG                          | 3         | 0.14%   |
| VALE                                 | 3         | 0.14%   |
| Pegatron                             | 3         | 0.14%   |
| Packard Bell                         | 3         | 0.14%   |
| Hardkernel                           | 3         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 28        | 1.34%   |
| Unknown                            | 25        | 1.2%    |
| MSI MS-7C37                        | 16        | 0.77%   |
| Valve Jupiter                      | 13        | 0.62%   |
| ASUS H110M-A                       | 10        | 0.48%   |
| MSI MS-7B86                        | 8         | 0.38%   |
| MSI MS-7B79                        | 8         | 0.38%   |
| Apple MacBookPro15,1               | 8         | 0.38%   |
| HP EliteBook 8570p                 | 7         | 0.34%   |
| ASUS ROG STRIX B550-F GAMING       | 7         | 0.34%   |
| ASUS PRIME B450-PLUS               | 7         | 0.34%   |
| MSI MS-7C91                        | 6         | 0.29%   |
| HP EliteBook 840 G3                | 6         | 0.29%   |
| ASRock Z87 Killer                  | 6         | 0.29%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 5         | 0.24%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 5         | 0.24%   |
| HP Pavilion dv6                    | 5         | 0.24%   |
| HP Notebook                        | 5         | 0.24%   |
| HP EliteBook 8460p                 | 5         | 0.24%   |
| HP EliteBook 840 G6                | 5         | 0.24%   |
| ASUS TUF Gaming X570-PLUS          | 5         | 0.24%   |
| ASUS ROG STRIX B450-F GAMING       | 5         | 0.24%   |
| Toshiba Satellite C70D-B           | 4         | 0.19%   |
| RPi Raspberry Pi                   | 4         | 0.19%   |
| Lenovo Yoga Slim 7 14ARE05 82A2    | 4         | 0.19%   |
| Lenovo IdeaPad 700-15ISK 80RU      | 4         | 0.19%   |
| HP Pavilion dv7                    | 4         | 0.19%   |
| HP ENVY x360 Convertible 15-ee0xxx | 4         | 0.19%   |
| HP EliteDesk 800 G1 SFF            | 4         | 0.19%   |
| HP EliteBook 840 G1                | 4         | 0.19%   |
| HP EliteBook 6930p                 | 4         | 0.19%   |
| HP Compaq 8200 Elite SFF PC        | 4         | 0.19%   |
| Dell XPS 15 9570                   | 4         | 0.19%   |
| Dell Latitude E7450                | 4         | 0.19%   |
| Dell Latitude E6400                | 4         | 0.19%   |
| Dell Latitude 5520                 | 4         | 0.19%   |
| ASUS UX303LAB                      | 4         | 0.19%   |
| ASUS TUF Gaming B550-PLUS          | 4         | 0.19%   |
| ASUS ROG STRIX B550-I GAMING       | 4         | 0.19%   |
| ASUS PRIME A320M-K                 | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 220       | 10.54%  |
| HP EliteBook       | 76        | 3.64%   |
| Acer Aspire        | 67        | 3.21%   |
| Dell Latitude      | 54        | 2.59%   |
| ASUS ROG           | 50        | 2.4%    |
| ASUS PRIME         | 48        | 2.3%    |
| Lenovo IdeaPad     | 36        | 1.72%   |
| HP Pavilion        | 35        | 1.68%   |
| HP ProBook         | 34        | 1.63%   |
| Dell XPS           | 31        | 1.49%   |
| Lenovo Yoga        | 29        | 1.39%   |
| ASUS All           | 28        | 1.34%   |
| Toshiba Satellite  | 25        | 1.2%    |
| Unknown            | 25        | 1.2%    |
| HP Compaq          | 24        | 1.15%   |
| Lenovo ThinkCentre | 19        | 0.91%   |
| ASUS TUF           | 19        | 0.91%   |
| Dell OptiPlex      | 17        | 0.81%   |
| Dell Inspiron      | 17        | 0.81%   |
| ASUS VivoBook      | 17        | 0.81%   |
| MSI MS-7C37        | 16        | 0.77%   |
| RPi Raspberry      | 15        | 0.72%   |
| HP ENVY            | 15        | 0.72%   |
| HP ZBook           | 14        | 0.67%   |
| Dell Precision     | 14        | 0.67%   |
| Valve Jupiter      | 13        | 0.62%   |
| Lenovo ThinkBook   | 13        | 0.62%   |
| Fujitsu LIFEBOOK   | 13        | 0.62%   |
| HP Laptop          | 11        | 0.53%   |
| Acer TravelMate    | 11        | 0.53%   |
| HP EliteDesk       | 10        | 0.48%   |
| Gigabyte X570      | 10        | 0.48%   |
| ASUS H110M-A       | 10        | 0.48%   |
| Acer Swift         | 10        | 0.48%   |
| Lenovo Legion      | 9         | 0.43%   |
| MSI MS-7B86        | 8         | 0.38%   |
| MSI MS-7B79        | 8         | 0.38%   |
| Microsoft Surface  | 8         | 0.38%   |
| Gigabyte B550      | 8         | 0.38%   |
| Apple MacBookPro15 | 8         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 244       | 11.69%  |
| 2019    | 192       | 9.2%    |
| 2018    | 186       | 8.91%   |
| 2012    | 158       | 7.57%   |
| 2021    | 152       | 7.28%   |
| 2011    | 140       | 6.71%   |
| 2013    | 133       | 6.37%   |
| 2017    | 132       | 6.32%   |
| 2015    | 120       | 5.75%   |
| 2016    | 117       | 5.61%   |
| 2014    | 117       | 5.61%   |
| 2022    | 74        | 3.55%   |
| 2010    | 74        | 3.55%   |
| 2009    | 68        | 3.26%   |
| 2008    | 66        | 3.16%   |
| 2023    | 42        | 2.01%   |
| 2007    | 38        | 1.82%   |
| Unknown | 19        | 0.91%   |
| 2006    | 12        | 0.57%   |
| 2005    | 3         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1099      | 52.66%  |
| Desktop        | 804       | 38.52%  |
| Convertible    | 68        | 3.26%   |
| Mini pc        | 38        | 1.82%   |
| Tablet         | 26        | 1.25%   |
| System on chip | 24        | 1.15%   |
| Server         | 21        | 1.01%   |
| All in one     | 7         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1923      | 91.14%  |
| Enabled  | 187       | 8.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2082      | 99.76%  |
| Yes  | 5         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 478       | 22.65%  |
| 4.01-8.0        | 436       | 20.66%  |
| 8.01-16.0       | 389       | 18.44%  |
| 3.01-4.0        | 303       | 14.36%  |
| 32.01-64.0      | 281       | 13.32%  |
| 64.01-256.0     | 85        | 4.03%   |
| 24.01-32.0      | 52        | 2.46%   |
| 1.01-2.0        | 52        | 2.46%   |
| 2.01-3.0        | 14        | 0.66%   |
| 0.51-1.0        | 13        | 0.62%   |
| More than 256.0 | 6         | 0.28%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 749       | 32.06%  |
| 2.01-3.0   | 581       | 24.87%  |
| 4.01-8.0   | 385       | 16.48%  |
| 3.01-4.0   | 297       | 12.71%  |
| 8.01-16.0  | 130       | 5.57%   |
| 0.51-1.0   | 122       | 5.22%   |
| 16.01-24.0 | 28        | 1.2%    |
| 0.01-0.5   | 22        | 0.94%   |
| 24.01-32.0 | 12        | 0.51%   |
| 32.01-64.0 | 9         | 0.39%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1220      | 56.38%  |
| 2      | 531       | 24.54%  |
| 3      | 200       | 9.24%   |
| 4      | 97        | 4.48%   |
| 5      | 45        | 2.08%   |
| 6      | 23        | 1.06%   |
| 7      | 11        | 0.51%   |
| 9      | 10        | 0.46%   |
| 0      | 10        | 0.46%   |
| 10     | 6         | 0.28%   |
| 11     | 4         | 0.18%   |
| 8      | 4         | 0.18%   |
| 18     | 2         | 0.09%   |
| 12     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1298      | 61.84%  |
| Yes       | 801       | 38.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1803      | 86.06%  |
| No        | 292       | 13.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1584      | 75.54%  |
| No        | 513       | 24.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1264      | 60.28%  |
| No        | 833       | 39.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 2087      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Vienna            | 1190      | 53.82%  |
| Graz              | 117       | 5.29%   |
| Innsbruck         | 68        | 3.08%   |
| Linz              | 65        | 2.94%   |
| Salzburg          | 50        | 2.26%   |
| Bad Hall          | 31        | 1.4%    |
| Klagenfurt        | 26        | 1.18%   |
| Sankt Pölten     | 22        | 1%      |
| Wels              | 18        | 0.81%   |
| Dornbirn          | 18        | 0.81%   |
| Wiener Neustadt   | 15        | 0.68%   |
| Steyr             | 15        | 0.68%   |
| Leonding          | 13        | 0.59%   |
| Perg              | 10        | 0.45%   |
| Villach           | 9         | 0.41%   |
| Feldkirch         | 9         | 0.41%   |
| Baden bei Wien    | 9         | 0.41%   |
| Wörgl            | 8         | 0.36%   |
| Traun             | 8         | 0.36%   |
| Korneuburg        | 7         | 0.32%   |
| Falkenstein       | 7         | 0.32%   |
| Hallein           | 6         | 0.27%   |
| Bregenz           | 6         | 0.27%   |
| Zell am See       | 5         | 0.23%   |
| Traunkirchen      | 5         | 0.23%   |
| Perchtoldsdorf    | 5         | 0.23%   |
| Mautern           | 5         | 0.23%   |
| Lustenau          | 5         | 0.23%   |
| Klosterneuburg    | 5         | 0.23%   |
| Gaenserndorf      | 5         | 0.23%   |
| Brunn am Gebirge  | 5         | 0.23%   |
| Zirl              | 4         | 0.18%   |
| Voecklabruck      | 4         | 0.18%   |
| Umhausen          | 4         | 0.18%   |
| Seiersberg        | 4         | 0.18%   |
| Schwechat         | 4         | 0.18%   |
| Ried im Innkreis  | 4         | 0.18%   |
| Mauthausen        | 4         | 0.18%   |
| Krems             | 4         | 0.18%   |
| Kalsdorf bei Graz | 4         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 728       | 1178   | 22.71%  |
| Seagate                     | 355       | 544    | 11.07%  |
| WDC                         | 334       | 531    | 10.42%  |
| SanDisk                     | 291       | 411    | 9.08%   |
| Toshiba                     | 188       | 304    | 5.86%   |
| Kingston                    | 149       | 189    | 4.65%   |
| Unknown                     | 141       | 217    | 4.4%    |
| Crucial                     | 140       | 234    | 4.37%   |
| Intel                       | 79        | 99     | 2.46%   |
| SK hynix                    | 78        | 112    | 2.43%   |
| Intenso                     | 71        | 87     | 2.21%   |
| Hitachi                     | 69        | 82     | 2.15%   |
| Micron Technology           | 53        | 66     | 1.65%   |
| HGST                        | 43        | 74     | 1.34%   |
| Transcend                   | 31        | 38     | 0.97%   |
| Micron/Crucial Technology   | 28        | 34     | 0.87%   |
| KIOXIA                      | 26        | 42     | 0.81%   |
| Phison                      | 25        | 35     | 0.78%   |
| A-DATA Technology           | 22        | 30     | 0.69%   |
| China                       | 21        | 25     | 0.66%   |
| Apple                       | 21        | 34     | 0.66%   |
| Phison Electronics          | 15        | 19     | 0.47%   |
| OCZ                         | 15        | 25     | 0.47%   |
| Kingston Technology Company | 15        | 20     | 0.47%   |
| Corsair                     | 12        | 15     | 0.37%   |
| Unknown                     | 12        | 18     | 0.37%   |
| ASMT                        | 11        | 19     | 0.34%   |
| SABRENT                     | 10        | 11     | 0.31%   |
| Patriot                     | 10        | 13     | 0.31%   |
| LITEON                      | 10        | 11     | 0.31%   |
| JMicron Technology          | 10        | 24     | 0.31%   |
| LITEONIT                    | 8         | 11     | 0.25%   |
| Silicon Motion              | 7         | 10     | 0.22%   |
| INNOVATION IT               | 7         | 9      | 0.22%   |
| Hewlett-Packard             | 6         | 12     | 0.19%   |
| Apacer                      | 6         | 9      | 0.19%   |
| Verbatim                    | 5         | 5      | 0.16%   |
| SPCC                        | 5         | 18     | 0.16%   |
| PNY                         | 5         | 6      | 0.16%   |
| GOODRAM                     | 5         | 5      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 47        | 1.3%    |
| Samsung SSD 850 EVO 250GB                          | 39        | 1.08%   |
| Samsung SSD 860 EVO 500GB                          | 32        | 0.88%   |
| Samsung SSD 850 EVO 500GB                          | 30        | 0.83%   |
| Unknown MMC Card  64GB                             | 29        | 0.8%    |
| Samsung NVMe SSD Drive 512GB                       | 27        | 0.75%   |
| Seagate Expansion 1TB                              | 22        | 0.61%   |
| SanDisk SSD PLUS 240GB                             | 22        | 0.61%   |
| Samsung SSD 840 EVO 250GB                          | 22        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                       | 22        | 0.61%   |
| Samsung SSD 860 EVO 1TB                            | 21        | 0.58%   |
| Samsung SSD 850 PRO 256GB                          | 21        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                        | 21        | 0.58%   |
| SanDisk SSD PLUS 1000GB                            | 19        | 0.53%   |
| Samsung SSD 860 EVO 250GB                          | 19        | 0.53%   |
| Toshiba MQ01ABD100 1TB                             | 18        | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB                       | 18        | 0.5%    |
| Samsung NVMe SSD Drive 500GB                       | 18        | 0.5%    |
| Samsung NVMe SSD Drive 1TB                         | 18        | 0.5%    |
| Unknown MMC Card  32GB                             | 16        | 0.44%   |
| Toshiba DT01ACA200 2TB                             | 16        | 0.44%   |
| Kingston SUV400S37240G 240GB SSD                   | 16        | 0.44%   |
| SanDisk SSD PLUS 480GB                             | 15        | 0.41%   |
| Samsung SSD 980 PRO 1TB                            | 15        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                       | 15        | 0.41%   |
| Unknown SD/MMC/MS PRO 256GB                        | 14        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                         | 14        | 0.39%   |
| Kingston SA400S37240G 240GB SSD                    | 14        | 0.39%   |
| Toshiba MQ04ABF100 1TB                             | 13        | 0.36%   |
| Toshiba HDWD110 1TB                                | 13        | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB                     | 13        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 13        | 0.36%   |
| SanDisk NVMe SSD Drive 512GB                       | 13        | 0.36%   |
| Samsung SSD 860 QVO 1TB                            | 13        | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 13        | 0.36%   |
| Seagate ST4000VN008-2DR166 4TB                     | 12        | 0.33%   |
| SanDisk SDSSDH3 1T00 1TB                           | 12        | 0.33%   |
| SanDisk SDSSDA240G 240GB                           | 12        | 0.33%   |
| Samsung NVMe SSD Drive 1024GB                      | 12        | 0.33%   |
| Kingston SA400S37120G 120GB SSD                    | 12        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 345       | 521    | 34.99%  |
| WDC                 | 261       | 420    | 26.47%  |
| Toshiba             | 139       | 219    | 14.1%   |
| Hitachi             | 69        | 82     | 7%      |
| Samsung Electronics | 60        | 88     | 6.09%   |
| HGST                | 43        | 74     | 4.36%   |
| Unknown             | 15        | 22     | 1.52%   |
| Intenso             | 15        | 15     | 1.52%   |
| JMicron Technology  | 9         | 23     | 0.91%   |
| Maxtor              | 4         | 5      | 0.41%   |
| LaCie               | 3         | 3      | 0.3%    |
| ASMT                | 3         | 9      | 0.3%    |
| USB                 | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 9      | 0.2%    |
| Fujitsu             | 2         | 2      | 0.2%    |
| Apple               | 2         | 2      | 0.2%    |
| WD MediaMax         | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 3      | 0.1%    |
| Synology            | 1         | 8      | 0.1%    |
| SSK                 | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| Inateck             | 1         | 1      | 0.1%    |
| IBM-ESXS            | 1         | 2      | 0.1%    |
| IB-1122             | 1         | 1      | 0.1%    |
| IB                  | 1         | 2      | 0.1%    |
| Ext Hard            | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 382       | 581    | 30.88%  |
| SanDisk             | 211       | 303    | 17.06%  |
| Crucial             | 129       | 206    | 10.43%  |
| Kingston            | 110       | 135    | 8.89%   |
| Intenso             | 49        | 63     | 3.96%   |
| Intel               | 35        | 45     | 2.83%   |
| WDC                 | 28        | 35     | 2.26%   |
| Transcend           | 28        | 32     | 2.26%   |
| Micron Technology   | 25        | 33     | 2.02%   |
| SK hynix            | 23        | 38     | 1.86%   |
| China               | 21        | 25     | 1.7%    |
| A-DATA Technology   | 16        | 22     | 1.29%   |
| OCZ                 | 15        | 25     | 1.21%   |
| Toshiba             | 10        | 12     | 0.81%   |
| LITEON              | 10        | 11     | 0.81%   |
| Apple               | 10        | 11     | 0.81%   |
| SABRENT             | 9         | 10     | 0.73%   |
| LITEONIT            | 8         | 11     | 0.65%   |
| Corsair             | 8         | 8      | 0.65%   |
| Patriot             | 7         | 7      | 0.57%   |
| INNOVATION IT       | 7         | 9      | 0.57%   |
| ASMT                | 6         | 6      | 0.49%   |
| GOODRAM             | 5         | 5      | 0.4%    |
| Apacer              | 5         | 6      | 0.4%    |
| Verbatim            | 4         | 4      | 0.32%   |
| SPCC                | 4         | 4      | 0.32%   |
| Phison              | 4         | 6      | 0.32%   |
| PNY                 | 3         | 4      | 0.24%   |
| Plextor             | 3         | 3      | 0.24%   |
| KingDian            | 3         | 3      | 0.24%   |
| Hewlett-Packard     | 3         | 3      | 0.24%   |
| Fanxiang            | 3         | 3      | 0.24%   |
| BAITITON            | 3         | 4      | 0.24%   |
| Unknown             | 3         | 3      | 0.24%   |
| V7                  | 2         | 2      | 0.16%   |
| Unknown             | 2         | 3      | 0.16%   |
| TrekStor            | 2         | 4      | 0.16%   |
| Teclast             | 2         | 2      | 0.16%   |
| TCSUNBOW            | 2         | 2      | 0.16%   |
| Seagate             | 2         | 3      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1049      | 1736   | 36.88%  |
| NVMe    | 812       | 1253   | 28.55%  |
| HDD     | 808       | 1519   | 28.41%  |
| MMC     | 126       | 191    | 4.43%   |
| Unknown | 49        | 102    | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1455      | 3067   | 56.88%  |
| NVMe | 812       | 1250   | 31.74%  |
| SAS  | 165       | 293    | 6.45%   |
| MMC  | 126       | 191    | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1094      | 1812   | 54.75%  |
| 0.51-1.0   | 554       | 832    | 27.73%  |
| 1.01-2.0   | 180       | 298    | 9.01%   |
| 3.01-4.0   | 71        | 142    | 3.55%   |
| 4.01-10.0  | 47        | 77     | 2.35%   |
| 2.01-3.0   | 41        | 58     | 2.05%   |
| 10.01-20.0 | 11        | 36     | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 539       | 24.06%  |
| 251-500        | 419       | 18.71%  |
| 501-1000       | 339       | 15.13%  |
| 1001-2000      | 200       | 8.93%   |
| 1-20           | 169       | 7.54%   |
| More than 3000 | 154       | 6.88%   |
| 51-100         | 147       | 6.56%   |
| Unknown        | 110       | 4.91%   |
| 21-50          | 89        | 3.97%   |
| 2001-3000      | 74        | 3.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 807       | 34.81%  |
| 21-50          | 372       | 16.05%  |
| 101-250        | 281       | 12.12%  |
| 51-100         | 216       | 9.32%   |
| 251-500        | 180       | 7.77%   |
| 501-1000       | 163       | 7.03%   |
| Unknown        | 110       | 4.75%   |
| 1001-2000      | 93        | 4.01%   |
| More than 3000 | 57        | 2.46%   |
| 2001-3000      | 39        | 1.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB                  | 7         | 7      | 3.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 5      | 2.66%   |
| SanDisk SD6SF1M128G1022I 128GB SSD       | 5         | 5      | 2.66%   |
| Toshiba MQ01ABF050 500GB                 | 3         | 4      | 1.6%    |
| Seagate ST500LT012-9WS142 500GB          | 3         | 6      | 1.6%    |
| Samsung Electronics HD103UJ 1TB          | 3         | 3      | 1.6%    |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.06%   |
| Seagate ST9250315AS 250GB                | 2         | 2      | 1.06%   |
| Seagate ST9160412AS 160GB                | 2         | 2      | 1.06%   |
| Seagate ST3500413AS 500GB                | 2         | 2      | 1.06%   |
| SanDisk SSD PLUS 480GB                   | 2         | 2      | 1.06%   |
| Samsung Electronics SSD 840 Series 120GB | 2         | 2      | 1.06%   |
| Samsung Electronics HM500JI 500GB        | 2         | 2      | 1.06%   |
| Samsung Electronics HD753LJ 752GB        | 2         | 2      | 1.06%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 2      | 1.06%   |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.06%   |
| HGST HTS725050A7E630 500GB               | 2         | 14     | 1.06%   |
| HGST HTS721010A9E630 1TB                 | 2         | 3      | 1.06%   |
| WDC WD6400AACS-00G8B0 640GB              | 1         | 1      | 0.53%   |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.53%   |
| WDC WD5000AAKX-08U6AA0 500GB             | 1         | 1      | 0.53%   |
| WDC WD5000AAKS-60Z1A0 500GB              | 1         | 1      | 0.53%   |
| WDC WD5000AAKS-22A7B0 500GB              | 1         | 1      | 0.53%   |
| WDC WD5000AAKS-00UU3A0 500GB             | 1         | 1      | 0.53%   |
| WDC WD5000AAKS-00H2B0 500GB              | 1         | 1      | 0.53%   |
| WDC WD5000AADS-00M2B0 500GB              | 1         | 1      | 0.53%   |
| WDC WD3200BEVT-08A23T1 320GB             | 1         | 1      | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 1      | 0.53%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1         | 1      | 0.53%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.53%   |
| WDC WD20EFRX-68AX9N0 2TB                 | 1         | 14     | 0.53%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 2      | 0.53%   |
| WDC WD2003FYYS-02W0B1 2TB                | 1         | 1      | 0.53%   |
| WDC WD2002FYPS-02W3B0 2TB                | 1         | 1      | 0.53%   |
| WDC WD2000FYYZ-01UL1B1 2TB               | 1         | 1      | 0.53%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 1      | 0.53%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1         | 1      | 0.53%   |
| WDC WD10EZEX-75M2NA0 1TB                 | 1         | 1      | 0.53%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1      | 0.53%   |
| WDC WD10EACS-00D6B0 1TB                  | 1         | 2      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 36        | 55     | 20.11%  |
| WDC                         | 31        | 48     | 17.32%  |
| Samsung Electronics         | 26        | 32     | 14.53%  |
| Toshiba                     | 17        | 22     | 9.5%    |
| SanDisk                     | 15        | 16     | 8.38%   |
| Hitachi                     | 15        | 16     | 8.38%   |
| HGST                        | 7         | 20     | 3.91%   |
| Intel                       | 5         | 5      | 2.79%   |
| Kingston                    | 4         | 4      | 2.23%   |
| SK hynix                    | 2         | 12     | 1.12%   |
| OCZ                         | 2         | 4      | 1.12%   |
| LITEONIT                    | 2         | 3      | 1.12%   |
| Crucial                     | 2         | 2      | 1.12%   |
| TrekStor                    | 1         | 1      | 0.56%   |
| Transcend                   | 1         | 1      | 0.56%   |
| Patriot                     | 1         | 1      | 0.56%   |
| Micron Technology           | 1         | 1      | 0.56%   |
| Maxtor                      | 1         | 1      | 0.56%   |
| LITEON                      | 1         | 1      | 0.56%   |
| Kingston Technology Company | 1         | 1      | 0.56%   |
| Intenso                     | 1         | 1      | 0.56%   |
| HP Phison                   | 1         | 1      | 0.56%   |
| GOODRAM                     | 1         | 1      | 0.56%   |
| Fujitsu                     | 1         | 1      | 0.56%   |
| Corsair                     | 1         | 1      | 0.56%   |
| China                       | 1         | 1      | 0.56%   |
| BAITITON                    | 1         | 2      | 0.56%   |
| A-DATA Technology           | 1         | 3      | 0.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 55     | 30%     |
| WDC                 | 31        | 48     | 25.83%  |
| Toshiba             | 16        | 21     | 13.33%  |
| Hitachi             | 15        | 16     | 12.5%   |
| Samsung Electronics | 13        | 14     | 10.83%  |
| HGST                | 7         | 20     | 5.83%   |
| Maxtor              | 1         | 1      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.83%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 111       | 176    | 65.29%  |
| SSD  | 50        | 71     | 29.41%  |
| NVMe | 9         | 10     | 5.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 33.33%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Sandisk             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1249      | 2613   | 53.93%  |
| Works    | 903       | 1927   | 38.99%  |
| Malfunc  | 160       | 257    | 6.91%   |
| Failed   | 3         | 3      | 0.13%   |
| Limited  | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1269      | 45.76%  |
| AMD                                     | 434       | 15.65%  |
| Samsung Electronics                     | 360       | 12.98%  |
| SanDisk                                 | 131       | 4.72%   |
| ASMedia Technology                      | 74        | 2.67%   |
| SK hynix                                | 57        | 2.06%   |
| Kingston Technology Company             | 55        | 1.98%   |
| Phison Electronics                      | 45        | 1.62%   |
| Toshiba America Info Systems            | 43        | 1.55%   |
| Marvell Technology Group                | 40        | 1.44%   |
| Micron/Crucial Technology               | 39        | 1.41%   |
| JMicron Technology                      | 33        | 1.19%   |
| Micron Technology                       | 29        | 1.05%   |
| Nvidia                                  | 25        | 0.9%    |
| KIOXIA                                  | 23        | 0.83%   |
| Broadcom / LSI                          | 13        | 0.47%   |
| Silicon Motion                          | 11        | 0.4%    |
| LSI Logic / Symbios Logic               | 11        | 0.4%    |
| ADATA Technology                        | 10        | 0.36%   |
| Apple                                   | 9         | 0.32%   |
| Union Memory (Shenzhen)                 | 8         | 0.29%   |
| Seagate Technology                      | 8         | 0.29%   |
| VIA Technologies                        | 7         | 0.25%   |
| MAXIO Technology (Hangzhou)             | 7         | 0.25%   |
| Silicon Image                           | 5         | 0.18%   |
| Lenovo                                  | 4         | 0.14%   |
| Solid State Storage Technology          | 2         | 0.07%   |
| Shenzhen Longsys Electronics            | 2         | 0.07%   |
| Realtek Semiconductor                   | 2         | 0.07%   |
| OCZ Technology Group                    | 2         | 0.07%   |
| Lite-On IT Corp. / Plextor              | 2         | 0.07%   |
| Hewlett-Packard                         | 2         | 0.07%   |
| Adaptec                                 | 2         | 0.07%   |
| Transcend                               | 1         | 0.04%   |
| Solidigm                                | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| O2 Micro                                | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |
| Integrated Technology Express           | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 280       | 8.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 182       | 5.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 98        | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 89        | 2.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 79        | 2.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 69        | 2.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 68        | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 66        | 2.11%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 64        | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 58        | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 56        | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 54        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 48        | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 44        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 43        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 42        | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 41        | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 41        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 40        | 1.28%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 39        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 37        | 1.18%   |
| Intel SATA Controller [RAID mode]                                              | 33        | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 28        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.83%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 25        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 25        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 24        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 23        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 23        | 0.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 23        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                             | 22        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 22        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 22        | 0.7%    |
| Phison E12 NVMe Controller                                                     | 21        | 0.67%   |
| Intel SSD 660P Series                                                          | 21        | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1512      | 55.65%  |
| NVMe | 817       | 30.07%  |
| IDE  | 208       | 7.66%   |
| RAID | 164       | 6.04%   |
| SAS  | 8         | 0.29%   |
| SCSI | 8         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1501      | 71.92%  |
| AMD      | 562       | 26.93%  |
| ARM      | 23        | 1.1%    |
| Qualcomm | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 26        | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 25        | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 25        | 1.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 22        | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 21        | 1.01%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 21        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 20        | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 18        | 0.86%   |
| AMD Ryzen 5 3600 6-Core Processor           | 18        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 17        | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 17        | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 17        | 0.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 16        | 0.77%   |
| ARM Processor                               | 16        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 15        | 0.72%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 15        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 15        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 14        | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 14        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 14        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.67%   |
| AMD Custom APU 0405                         | 14        | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 13        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 13        | 0.62%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 13        | 0.62%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 13        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 12        | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 12        | 0.57%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 12        | 0.57%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 11        | 0.53%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11        | 0.53%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 11        | 0.53%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 11        | 0.53%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11        | 0.53%   |
| AMD FX-8350 Eight-Core Processor            | 11        | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 10        | 0.48%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 10        | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10        | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 10        | 0.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 10        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 470       | 22.51%  |
| Intel Core i7           | 440       | 21.07%  |
| Other                   | 174       | 8.33%   |
| AMD Ryzen 5             | 135       | 6.47%   |
| AMD Ryzen 7             | 132       | 6.32%   |
| Intel Core i3           | 84        | 4.02%   |
| Intel Core 2 Duo        | 74        | 3.54%   |
| Intel Celeron           | 72        | 3.45%   |
| Intel Xeon              | 49        | 2.35%   |
| AMD Ryzen 9             | 44        | 2.11%   |
| Intel Pentium           | 41        | 1.96%   |
| Intel Atom              | 38        | 1.82%   |
| AMD FX                  | 32        | 1.53%   |
| AMD Ryzen 7 PRO         | 27        | 1.29%   |
| Intel Core i9           | 26        | 1.25%   |
| AMD A8                  | 21        | 1.01%   |
| AMD Ryzen 3             | 20        | 0.96%   |
| Intel Pentium Dual-Core | 16        | 0.77%   |
| AMD Phenom II X4        | 15        | 0.72%   |
| AMD A10                 | 13        | 0.62%   |
| Intel Core 2 Quad       | 12        | 0.57%   |
| Intel Core 2            | 10        | 0.48%   |
| AMD Ryzen 5 PRO         | 10        | 0.48%   |
| AMD A6                  | 10        | 0.48%   |
| AMD A4                  | 10        | 0.48%   |
| Intel Pentium Silver    | 9         | 0.43%   |
| AMD Phenom II X6        | 8         | 0.38%   |
| AMD Athlon              | 7         | 0.34%   |
| AMD E2                  | 6         | 0.29%   |
| AMD E                   | 6         | 0.29%   |
| AMD Athlon II X4        | 6         | 0.29%   |
| AMD Athlon 64 X2        | 6         | 0.29%   |
| Intel Xeon Silver       | 5         | 0.24%   |
| Intel Genuine           | 5         | 0.24%   |
| ARM BCM                 | 5         | 0.24%   |
| AMD Ryzen Threadripper  | 5         | 0.24%   |
| AMD E1                  | 4         | 0.19%   |
| AMD Athlon II X2        | 4         | 0.19%   |
| Intel Pentium Dual      | 3         | 0.14%   |
| Intel Pentium 4         | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 821       | 39.26%  |
| 2       | 674       | 32.23%  |
| 6       | 222       | 10.62%  |
| 8       | 220       | 10.52%  |
| 12      | 37        | 1.77%   |
| 16      | 32        | 1.53%   |
| 1       | 20        | 0.96%   |
| 10      | 19        | 0.91%   |
| 14      | 14        | 0.67%   |
| Unknown | 10        | 0.48%   |
| 3       | 7         | 0.33%   |
| 24      | 5         | 0.24%   |
| 20      | 5         | 0.24%   |
| 64      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 40      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2060      | 98.66%  |
| 2       | 22        | 1.05%   |
| Unknown | 6         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1469      | 70.22%  |
| 1       | 613       | 29.3%   |
| Unknown | 10        | 0.48%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2039      | 97.65%  |
| Unknown        | 38        | 1.82%   |
| 32-bit         | 9         | 0.43%   |
| 64-bit         | 2         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 638       | 29.27%  |
| 0x206a7    | 107       | 4.91%   |
| 0x306a9    | 101       | 4.63%   |
| 0x306c3    | 82        | 3.76%   |
| 0x806ec    | 59        | 2.71%   |
| 0x506e3    | 50        | 2.29%   |
| 0x1067a    | 48        | 2.2%    |
| 0x806ea    | 46        | 2.11%   |
| 0x906ea    | 44        | 2.02%   |
| 0x806c1    | 44        | 2.02%   |
| 0x406e3    | 38        | 1.74%   |
| 0x306d4    | 38        | 1.74%   |
| 0x906e9    | 33        | 1.51%   |
| 0x40651    | 33        | 1.51%   |
| 0x08701021 | 33        | 1.51%   |
| 0x806e9    | 30        | 1.38%   |
| 0x0a50000c | 27        | 1.24%   |
| 0x08600106 | 25        | 1.15%   |
| 0x08108109 | 20        | 0.92%   |
| 0x506c9    | 18        | 0.83%   |
| 0x20655    | 18        | 0.83%   |
| 0x10676    | 17        | 0.78%   |
| 0x08701013 | 17        | 0.78%   |
| 0x06000852 | 17        | 0.78%   |
| 0x010000c8 | 17        | 0.78%   |
| 0x0800820d | 16        | 0.73%   |
| 0x706e5    | 15        | 0.69%   |
| 0x106e5    | 15        | 0.69%   |
| 0x0a201016 | 15        | 0.69%   |
| 0x08600103 | 15        | 0.69%   |
| 0x706a8    | 14        | 0.64%   |
| 0x406c4    | 14        | 0.64%   |
| 0x0a50000d | 14        | 0.64%   |
| 0x08108102 | 14        | 0.64%   |
| 0x06001119 | 14        | 0.64%   |
| 0xa0652    | 13        | 0.6%    |
| 0x906ed    | 13        | 0.6%    |
| 0x08600104 | 12        | 0.55%   |
| 0x806eb    | 11        | 0.5%    |
| 0x6fb      | 11        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 332       | 15.89%  |
| Haswell          | 173       | 8.28%   |
| Zen 2            | 147       | 7.03%   |
| SandyBridge      | 144       | 6.89%   |
| Skylake          | 143       | 6.84%   |
| IvyBridge        | 141       | 6.75%   |
| Unknown          | 111       | 5.31%   |
| Zen 3            | 91        | 4.35%   |
| Penryn           | 85        | 4.07%   |
| Zen+             | 66        | 3.16%   |
| TigerLake        | 64        | 3.06%   |
| Broadwell        | 51        | 2.44%   |
| Silvermont       | 48        | 2.3%    |
| Westmere         | 43        | 2.06%   |
| CometLake        | 43        | 2.06%   |
| Piledriver       | 42        | 2.01%   |
| K10              | 42        | 2.01%   |
| Alderlake Hybrid | 36        | 1.72%   |
| Zen              | 35        | 1.67%   |
| IceLake          | 35        | 1.67%   |
| Core             | 34        | 1.63%   |
| Goldmont plus    | 26        | 1.24%   |
| Nehalem          | 25        | 1.2%    |
| Goldmont         | 24        | 1.15%   |
| Excavator        | 21        | 1%      |
| Puma             | 15        | 0.72%   |
| Bonnell          | 12        | 0.57%   |
| Bobcat           | 12        | 0.57%   |
| K8 Hammer        | 10        | 0.48%   |
| Steamroller      | 7         | 0.33%   |
| K10 Llano        | 7         | 0.33%   |
| Jaguar           | 6         | 0.29%   |
| Tremont          | 5         | 0.24%   |
| NetBurst         | 4         | 0.19%   |
| Bulldozer        | 4         | 0.19%   |
| P6               | 3         | 0.14%   |
| K8 & K10 hybrid  | 2         | 0.1%    |
| Gracemont        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1092      | 45.39%  |
| Nvidia                           | 671       | 27.89%  |
| AMD                              | 617       | 25.64%  |
| Matrox Electronics Systems       | 14        | 0.58%   |
| ASPEED Technology                | 9         | 0.37%   |
| ATI Technologies                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 97        | 3.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 82        | 3.32%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 66        | 2.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 59        | 2.39%   |
| Intel UHD Graphics 620                                                                   | 52        | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 46        | 1.86%   |
| Intel HD Graphics 620                                                                    | 45        | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 1.78%   |
| Intel HD Graphics 530                                                                    | 40        | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 1.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.54%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 38        | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 37        | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 37        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33        | 1.34%   |
| Intel HD Graphics 630                                                                    | 25        | 1.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 0.89%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 19        | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 19        | 0.77%   |
| AMD Lucienne                                                                             | 18        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 17        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.69%   |
| Nvidia GP108M [GeForce MX250]                                                            | 16        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.65%   |
| Intel HD Graphics 500                                                                    | 16        | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 0.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 0.61%   |
| Intel Iris Plus Graphics G7                                                              | 14        | 0.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 14        | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 13        | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 0.53%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 13        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 790       | 37.53%  |
| 1 x AMD                 | 508       | 24.13%  |
| 1 x Nvidia              | 406       | 19.29%  |
| Intel + Nvidia          | 232       | 11.02%  |
| Intel + AMD             | 51        | 2.42%   |
| 2 x AMD                 | 35        | 1.66%   |
| AMD + Nvidia            | 26        | 1.24%   |
| Other                   | 25        | 1.19%   |
| 1 x Matrox              | 13        | 0.62%   |
| 1 x ASPEED              | 7         | 0.33%   |
| 2 x Nvidia              | 4         | 0.19%   |
| Nvidia + ASPEED         | 3         | 0.14%   |
| 2 x Intel               | 2         | 0.1%    |
| 2 x Nvidia + 1 x Matrox | 1         | 0.05%   |
| 1 x SiS                 | 1         | 0.05%   |
| AMD + 2 x Nvidia        | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1671      | 78.9%   |
| Proprietary | 356       | 16.81%  |
| Unknown     | 91        | 4.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1184      | 55.1%   |
| 1.01-2.0   | 243       | 11.31%  |
| 0.01-0.5   | 218       | 10.14%  |
| 0.51-1.0   | 148       | 6.89%   |
| 3.01-4.0   | 144       | 6.7%    |
| 7.01-8.0   | 104       | 4.84%   |
| 5.01-6.0   | 50        | 2.33%   |
| 8.01-16.0  | 37        | 1.72%   |
| 2.01-3.0   | 11        | 0.51%   |
| 16.01-24.0 | 9         | 0.42%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 334       | 14.18%  |
| AU Optronics            | 280       | 11.88%  |
| LG Display              | 200       | 8.49%   |
| BOE                     | 155       | 6.58%   |
| Chimei Innolux          | 152       | 6.45%   |
| Dell                    | 111       | 4.71%   |
| BenQ                    | 104       | 4.41%   |
| Goldstar                | 94        | 3.99%   |
| Hewlett-Packard         | 84        | 3.57%   |
| Acer                    | 74        | 3.14%   |
| AOC                     | 68        | 2.89%   |
| Lenovo                  | 59        | 2.5%    |
| Philips                 | 51        | 2.16%   |
| Iiyama                  | 50        | 2.12%   |
| Apple                   | 46        | 1.95%   |
| Sharp                   | 42        | 1.78%   |
| Ancor Communications    | 40        | 1.7%    |
| Eizo                    | 35        | 1.49%   |
| Gericom                 | 26        | 1.1%    |
| Medion                  | 25        | 1.06%   |
| Chi Mei Optoelectronics | 24        | 1.02%   |
| Fujitsu Siemens         | 17        | 0.72%   |
| ViewSonic               | 15        | 0.64%   |
| InfoVision              | 15        | 0.64%   |
| PANDA                   | 14        | 0.59%   |
| NEC Computers           | 13        | 0.55%   |
| Valve                   | 12        | 0.51%   |
| Sony                    | 12        | 0.51%   |
| ASUSTek Computer        | 12        | 0.51%   |
| Unknown                 | 11        | 0.47%   |
| HannStar                | 11        | 0.47%   |
| CSO                     | 11        | 0.47%   |
| LG Philips              | 9         | 0.38%   |
| Vestel Elektronik       | 8         | 0.34%   |
| Toshiba                 | 8         | 0.34%   |
| LG Electronics          | 6         | 0.25%   |
| GRM                     | 6         | 0.25%   |
| Panasonic               | 5         | 0.21%   |
| MSI                     | 5         | 0.21%   |
| Lenovo Group Limited    | 5         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 11        | 0.45%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 11        | 0.45%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 10        | 0.4%    |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                    | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 10        | 0.4%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 9         | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 9         | 0.36%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch | 8         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 8         | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 8         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 8         | 0.32%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                   | 8         | 0.32%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                | 8         | 0.32%   |
| Acer B193 ACR001D 1280x1024 380x300mm 19.1-inch                      | 8         | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 7         | 0.28%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch          | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 7         | 0.28%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch    | 6         | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch              | 6         | 0.24%   |
| GRM GM2600 GRM5BC6 1920x1080 550x344mm 25.5-inch                     | 6         | 0.24%   |
| Gericom Q24 QMX2421 1920x1080 521x293mm 23.5-inch                    | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch     | 6         | 0.24%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                | 6         | 0.24%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                   | 6         | 0.24%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 6         | 0.24%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 5         | 0.2%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch    | 5         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 5         | 0.2%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 5         | 0.2%    |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch         | 5         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.2%    |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch          | 5         | 0.2%    |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch             | 5         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 5         | 0.2%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1026      | 45.44%  |
| 1366x768 (WXGA)    | 218       | 9.65%   |
| 3840x2160 (4K)     | 196       | 8.68%   |
| 2560x1440 (QHD)    | 155       | 6.86%   |
| 1600x900 (HD+)     | 96        | 4.25%   |
| 1920x1200 (WUXGA)  | 90        | 3.99%   |
| 1680x1050 (WSXGA+) | 84        | 3.72%   |
| 1280x1024 (SXGA)   | 67        | 2.97%   |
| 1280x800 (WXGA)    | 48        | 2.13%   |
| 3440x1440          | 39        | 1.73%   |
| 1440x900 (WXGA+)   | 35        | 1.55%   |
| Unknown            | 25        | 1.11%   |
| 2880x1800          | 19        | 0.84%   |
| 2560x1600          | 18        | 0.8%    |
| 2560x1080          | 18        | 0.8%    |
| 3840x1080          | 14        | 0.62%   |
| 800x1280           | 13        | 0.58%   |
| 1920x540           | 11        | 0.49%   |
| 3840x2400          | 9         | 0.4%    |
| 1024x600           | 6         | 0.27%   |
| 2288x1287          | 5         | 0.22%   |
| 3200x1800 (QHD+)   | 4         | 0.18%   |
| 2736x1824          | 4         | 0.18%   |
| 2160x1440          | 4         | 0.18%   |
| 2048x1152          | 4         | 0.18%   |
| 1600x1200          | 4         | 0.18%   |
| 1024x768 (XGA)     | 4         | 0.18%   |
| 2256x1504          | 3         | 0.13%   |
| 2160x1200          | 3         | 0.13%   |
| 1920x1280          | 3         | 0.13%   |
| 1360x768           | 3         | 0.13%   |
| 5760x2160          | 2         | 0.09%   |
| 5760x1080          | 2         | 0.09%   |
| 5120x1440          | 2         | 0.09%   |
| 4480x1440          | 2         | 0.09%   |
| 3456x2160          | 2         | 0.09%   |
| 3360x1050          | 2         | 0.09%   |
| 6400x2560          | 1         | 0.04%   |
| 6400x1440          | 1         | 0.04%   |
| 3840x2560          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 453       | 19.21%  |
| 27      | 239       | 10.14%  |
| 24      | 224       | 9.5%    |
| 13      | 197       | 8.35%   |
| 14      | 187       | 7.93%   |
| 17      | 149       | 6.32%   |
| 23      | 144       | 6.11%   |
| Unknown | 106       | 4.5%    |
| 21      | 76        | 3.22%   |
| 31      | 70        | 2.97%   |
| 19      | 60        | 2.54%   |
| 22      | 59        | 2.5%    |
| 12      | 51        | 2.16%   |
| 34      | 48        | 2.04%   |
| 25      | 36        | 1.53%   |
| 20      | 24        | 1.02%   |
| 16      | 23        | 0.98%   |
| 84      | 22        | 0.93%   |
| 11      | 22        | 0.93%   |
| 54      | 19        | 0.81%   |
| 40      | 17        | 0.72%   |
| 18      | 13        | 0.55%   |
| 7       | 12        | 0.51%   |
| 28      | 11        | 0.47%   |
| 10      | 11        | 0.47%   |
| 32      | 8         | 0.34%   |
| 72      | 7         | 0.3%    |
| 26      | 7         | 0.3%    |
| 48      | 6         | 0.25%   |
| 65      | 5         | 0.21%   |
| 42      | 5         | 0.21%   |
| 35      | 5         | 0.21%   |
| 142     | 4         | 0.17%   |
| 33      | 4         | 0.17%   |
| 85      | 3         | 0.13%   |
| 47      | 3         | 0.13%   |
| 39      | 3         | 0.13%   |
| 36      | 3         | 0.13%   |
| 29      | 3         | 0.13%   |
| 3       | 3         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 743       | 32.3%   |
| 501-600        | 549       | 23.87%  |
| 351-400        | 211       | 9.17%   |
| 201-300        | 197       | 8.57%   |
| 401-500        | 174       | 7.57%   |
| 601-700        | 132       | 5.74%   |
| Unknown        | 106       | 4.61%   |
| 701-800        | 61        | 2.65%   |
| 1001-1500      | 43        | 1.87%   |
| 1501-2000      | 32        | 1.39%   |
| 801-900        | 27        | 1.17%   |
| 1-100          | 13        | 0.57%   |
| 901-1000       | 7         | 0.3%    |
| More than 2000 | 4         | 0.17%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1527      | 72.06%  |
| 16/10   | 323       | 15.24%  |
| Unknown | 81        | 3.82%   |
| 5/4     | 67        | 3.16%   |
| 21/9    | 54        | 2.55%   |
| 3/2     | 23        | 1.09%   |
| 32/9    | 12        | 0.57%   |
| 0.67    | 10        | 0.47%   |
| 4/3     | 9         | 0.42%   |
| 6/5     | 6         | 0.28%   |
| 1.00    | 4         | 0.19%   |
| 0.80    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 455       | 19.51%  |
| 201-250        | 376       | 16.12%  |
| 81-90          | 294       | 12.61%  |
| 301-350        | 243       | 10.42%  |
| 351-500        | 146       | 6.26%   |
| 251-300        | 126       | 5.4%    |
| 121-130        | 119       | 5.1%    |
| 151-200        | 113       | 4.85%   |
| Unknown        | 106       | 4.55%   |
| 71-80          | 92        | 3.95%   |
| More than 1000 | 67        | 2.87%   |
| 61-70          | 48        | 2.06%   |
| 501-1000       | 41        | 1.76%   |
| 51-60          | 23        | 0.99%   |
| 141-150        | 22        | 0.94%   |
| 131-140        | 20        | 0.86%   |
| 111-120        | 15        | 0.64%   |
| 1-40           | 14        | 0.6%    |
| 41-50          | 10        | 0.43%   |
| 91-100         | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 757       | 33.67%  |
| 121-160       | 654       | 29.09%  |
| 101-120       | 460       | 20.46%  |
| 161-240       | 165       | 7.34%   |
| Unknown       | 106       | 4.72%   |
| More than 240 | 62        | 2.76%   |
| 1-50          | 44        | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1599      | 74.62%  |
| 2     | 371       | 17.31%  |
| 0     | 102       | 4.76%   |
| 3     | 64        | 2.99%   |
| 4     | 7         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1176      | 37.52%  |
| Realtek Semiconductor             | 1027      | 32.77%  |
| Qualcomm Atheros                  | 258       | 8.23%   |
| Broadcom                          | 133       | 4.24%   |
| MediaTek                          | 38        | 1.21%   |
| Marvell Technology Group          | 30        | 0.96%   |
| Broadcom Limited                  | 29        | 0.93%   |
| Ralink Technology                 | 28        | 0.89%   |
| Ralink                            | 26        | 0.83%   |
| TP-Link                           | 25        | 0.8%    |
| Nvidia                            | 21        | 0.67%   |
| Sierra Wireless                   | 19        | 0.61%   |
| ASIX Electronics                  | 19        | 0.61%   |
| Dell                              | 18        | 0.57%   |
| Lenovo                            | 17        | 0.54%   |
| NetGear                           | 16        | 0.51%   |
| Ericsson Business Mobile Networks | 16        | 0.51%   |
| Microsoft                         | 15        | 0.48%   |
| Aquantia                          | 15        | 0.48%   |
| Huawei Technologies               | 14        | 0.45%   |
| Edimax Technology                 | 14        | 0.45%   |
| IMC Networks                      | 13        | 0.41%   |
| ASUSTek Computer                  | 13        | 0.41%   |
| Samsung Electronics               | 11        | 0.35%   |
| Hewlett-Packard                   | 11        | 0.35%   |
| DisplayLink                       | 11        | 0.35%   |
| Fibocom                           | 10        | 0.32%   |
| D-Link System                     | 9         | 0.29%   |
| D-Link                            | 9         | 0.29%   |
| Qualcomm Atheros Communications   | 8         | 0.26%   |
| Qualcomm                          | 8         | 0.26%   |
| Google                            | 6         | 0.19%   |
| JMicron Technology                | 5         | 0.16%   |
| ZyXEL Communications              | 4         | 0.13%   |
| Xiaomi                            | 4         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.13%   |
| VIA Technologies                  | 3         | 0.1%    |
| Sigma Sport                       | 3         | 0.1%    |
| Motorola PCS                      | 3         | 0.1%    |
| Microchip Technology              | 3         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 723       | 19.19%  |
| Intel Wi-Fi 6 AX200                                                    | 135       | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 86        | 2.28%   |
| Intel Wireless 8265 / 8275                                             | 77        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 75        | 1.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 64        | 1.7%    |
| Intel I211 Gigabit Network Connection                                  | 59        | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 58        | 1.54%   |
| Intel Wi-Fi 6 AX201                                                    | 50        | 1.33%   |
| Intel Wireless 7265                                                    | 48        | 1.27%   |
| Intel Ethernet Controller I225-V                                       | 47        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                   | 46        | 1.22%   |
| Intel Wireless 8260                                                    | 43        | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 42        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 40        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 36        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 35        | 0.93%   |
| Intel Wireless 3165                                                    | 34        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 33        | 0.88%   |
| Intel Wireless 7260                                                    | 32        | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 31        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 30        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 29        | 0.77%   |
| Intel Ethernet Connection I217-LM                                      | 29        | 0.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 28        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 28        | 0.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 27        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 26        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 26        | 0.69%   |
| Intel Centrino Ultimate-N 6300                                         | 24        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                   | 23        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 22        | 0.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 21        | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 21        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 21        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 20        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 18        | 0.48%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 18        | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 877       | 51.23%  |
| Realtek Semiconductor                 | 256       | 14.95%  |
| Qualcomm Atheros                      | 188       | 10.98%  |
| Broadcom                              | 95        | 5.55%   |
| MediaTek                              | 37        | 2.16%   |
| Ralink Technology                     | 28        | 1.64%   |
| Ralink                                | 26        | 1.52%   |
| TP-Link                               | 25        | 1.46%   |
| Sierra Wireless                       | 19        | 1.11%   |
| NetGear                               | 15        | 0.88%   |
| Broadcom Limited                      | 15        | 0.88%   |
| Microsoft                             | 14        | 0.82%   |
| Edimax Technology                     | 14        | 0.82%   |
| IMC Networks                          | 13        | 0.76%   |
| ASUSTek Computer                      | 13        | 0.76%   |
| Dell                                  | 12        | 0.7%    |
| Fibocom                               | 10        | 0.58%   |
| Qualcomm Atheros Communications       | 8         | 0.47%   |
| Qualcomm                              | 7         | 0.41%   |
| D-Link System                         | 7         | 0.41%   |
| D-Link                                | 7         | 0.41%   |
| ZyXEL Communications                  | 4         | 0.23%   |
| Ericsson Business Mobile Networks     | 4         | 0.23%   |
| Marvell Technology Group              | 3         | 0.18%   |
| ZyDAS                                 | 2         | 0.12%   |
| Sitecom Europe                        | 2         | 0.12%   |
| Hewlett-Packard                       | 2         | 0.12%   |
| AVM                                   | 2         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.12%   |
| Wilocity                              | 1         | 0.06%   |
| Philips (or NXP)                      | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| BUFFALO                               | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 135       | 7.85%   |
| Intel Wireless 8265 / 8275                                     | 77        | 4.48%   |
| Intel Wi-Fi 6 AX201                                            | 50        | 2.91%   |
| Intel Wireless 7265                                            | 48        | 2.79%   |
| Intel Wireless 8260                                            | 43        | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 42        | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 40        | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 36        | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.04%   |
| Intel Wireless 3165                                            | 34        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 1.92%   |
| Intel Wireless 7260                                            | 32        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 31        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 30        | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29        | 1.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 28        | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 1.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 27        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 26        | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 26        | 1.51%   |
| Intel Centrino Ultimate-N 6300                                 | 24        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 21        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 16        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 15        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 0.87%   |
| Intel WiFi Link 5100                                           | 14        | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 14        | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 14        | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 13        | 0.76%   |
| Intel Wireless 3160                                            | 13        | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 13        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 13        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 12        | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 0.7%    |
| Intel Centrino Advanced-N 6235                                 | 12        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 921       | 47.52%  |
| Intel                         | 675       | 34.83%  |
| Qualcomm Atheros              | 95        | 4.9%    |
| Broadcom                      | 56        | 2.89%   |
| Marvell Technology Group      | 27        | 1.39%   |
| Nvidia                        | 21        | 1.08%   |
| ASIX Electronics              | 19        | 0.98%   |
| Lenovo                        | 16        | 0.83%   |
| Aquantia                      | 15        | 0.77%   |
| Broadcom Limited              | 14        | 0.72%   |
| Samsung Electronics           | 11        | 0.57%   |
| DisplayLink                   | 11        | 0.57%   |
| Huawei Technologies           | 6         | 0.31%   |
| Google                        | 6         | 0.31%   |
| JMicron Technology            | 5         | 0.26%   |
| Xiaomi                        | 4         | 0.21%   |
| OnePlus Technology (Shenzhen) | 4         | 0.21%   |
| VIA Technologies              | 3         | 0.15%   |
| Motorola PCS                  | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM    | 2         | 0.1%    |
| IBM                           | 2         | 0.1%    |
| Hewlett-Packard               | 2         | 0.1%    |
| Dell                          | 2         | 0.1%    |
| D-Link System                 | 2         | 0.1%    |
| D-Link                        | 2         | 0.1%    |
| Apple                         | 2         | 0.1%    |
| Research In Motion            | 1         | 0.05%   |
| Qualcomm                      | 1         | 0.05%   |
| NetGear                       | 1         | 0.05%   |
| Microsoft                     | 1         | 0.05%   |
| Microchip Technology          | 1         | 0.05%   |
| Mellanox Technologies         | 1         | 0.05%   |
| MediaTek                      | 1         | 0.05%   |
| Linksys                       | 1         | 0.05%   |
| Insyde Software               | 1         | 0.05%   |
| Emulex                        | 1         | 0.05%   |
| Cypress Semiconductor         | 1         | 0.05%   |
| Attansic Technology           | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 723       | 36.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 86        | 4.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 75        | 3.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 64        | 3.21%   |
| Intel I211 Gigabit Network Connection                                  | 59        | 2.96%   |
| Realtek RTL8125 2.5GbE Controller                                      | 58        | 2.91%   |
| Intel Ethernet Controller I225-V                                       | 47        | 2.35%   |
| Intel Ethernet Connection (2) I219-V                                   | 46        | 2.3%    |
| Intel Ethernet Connection I217-LM                                      | 29        | 1.45%   |
| Intel Ethernet Connection (6) I219-V                                   | 23        | 1.15%   |
| Intel 82579V Gigabit Network Connection                                | 22        | 1.1%    |
| Intel Ethernet Connection I219-LM                                      | 21        | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                   | 21        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                   | 20        | 1%      |
| Intel Ethernet Connection (2) I219-LM                                  | 18        | 0.9%    |
| Intel 82577LM Gigabit Network Connection                               | 18        | 0.9%    |
| Intel 82567LM Gigabit Network Connection                               | 18        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17        | 0.85%   |
| Intel I210 Gigabit Network Connection                                  | 17        | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                  | 15        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 15        | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                  | 15        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 14        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 0.7%    |
| Intel Ethernet Connection I217-V                                       | 13        | 0.65%   |
| Intel 82574L Gigabit Network Connection                                | 13        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 13        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                   | 12        | 0.6%    |
| Intel Ethernet Connection I219-V                                       | 10        | 0.5%    |
| Intel Ethernet Connection (13) I219-V                                  | 10        | 0.5%    |
| Intel I350 Gigabit Network Connection                                  | 9         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 8         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 0.4%    |
| Nvidia MCP79 Ethernet                                                  | 8         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1799      | 52.4%   |
| WiFi     | 1583      | 46.11%  |
| Modem    | 46        | 1.34%   |
| Unknown  | 5         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1183      | 55.15%  |
| Ethernet | 962       | 44.85%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1109      | 53.04%  |
| 1     | 840       | 40.17%  |
| 3     | 70        | 3.35%   |
| 0     | 49        | 2.34%   |
| 4     | 12        | 0.57%   |
| 6     | 4         | 0.19%   |
| 5     | 4         | 0.19%   |
| 12    | 2         | 0.1%    |
| 13    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1820      | 85.77%  |
| Yes  | 302       | 14.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 700       | 54.47%  |
| Realtek Semiconductor           | 124       | 9.65%   |
| Cambridge Silicon Radio         | 73        | 5.68%   |
| Broadcom                        | 61        | 4.75%   |
| Qualcomm Atheros Communications | 60        | 4.67%   |
| IMC Networks                    | 47        | 3.66%   |
| Apple                           | 37        | 2.88%   |
| Lite-On Technology              | 35        | 2.72%   |
| Foxconn / Hon Hai               | 31        | 2.41%   |
| ASUSTek Computer                | 21        | 1.63%   |
| Hewlett-Packard                 | 17        | 1.32%   |
| Dell                            | 14        | 1.09%   |
| MediaTek                        | 12        | 0.93%   |
| Toshiba                         | 9         | 0.7%    |
| TP-Link                         | 5         | 0.39%   |
| Ralink                          | 5         | 0.39%   |
| Marvell Semiconductor           | 5         | 0.39%   |
| Foxconn International           | 5         | 0.39%   |
| Belkin Components               | 4         | 0.31%   |
| USI                             | 3         | 0.23%   |
| Realtek                         | 3         | 0.23%   |
| HTC (High Tech Computer)        | 3         | 0.23%   |
| Edimax Technology               | 2         | 0.16%   |
| D-Link System                   | 2         | 0.16%   |
| Alps Electric                   | 2         | 0.16%   |
| Micro Star International        | 1         | 0.08%   |
| Logitech                        | 1         | 0.08%   |
| i.Tech Dynamic Limited          | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |
| Askey Computer                  | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 236       | 18.37%  |
| Intel AX200 Bluetooth                               | 132       | 10.27%  |
| Intel AX201 Bluetooth                               | 126       | 9.81%   |
| Realtek Bluetooth Radio                             | 91        | 7.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 73        | 5.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 68        | 5.29%   |
| Intel Bluetooth Device                              | 40        | 3.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 26        | 2.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 1.95%   |
| Intel AX210 Bluetooth                               | 25        | 1.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.63%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 20        | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 1.25%   |
| Apple Bluetooth Host Controller                     | 15        | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.01%   |
| Apple Bluetooth USB Host Controller                 | 13        | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.93%   |
| MediaTek Wireless_Device                            | 10        | 0.78%   |
| IMC Networks Wireless_Device                        | 10        | 0.78%   |
| IMC Networks Bluetooth Device                       | 10        | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 0.78%   |
| Lite-On Bluetooth Device                            | 9         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.62%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.54%   |
| TP-Link UB500 Adapter                               | 5         | 0.39%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.39%   |
| Lite-On Wireless_Device                             | 5         | 0.39%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.39%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1419      | 47.41%  |
| AMD                                          | 670       | 22.39%  |
| Nvidia                                       | 496       | 16.57%  |
| C-Media Electronics                          | 70        | 2.34%   |
| Logitech                                     | 38        | 1.27%   |
| GN Netcom                                    | 22        | 0.74%   |
| Lenovo                                       | 17        | 0.57%   |
| Realtek Semiconductor                        | 15        | 0.5%    |
| ASUSTek Computer                             | 15        | 0.5%    |
| Creative Labs                                | 14        | 0.47%   |
| SteelSeries ApS                              | 12        | 0.4%    |
| Texas Instruments                            | 10        | 0.33%   |
| Razer USA                                    | 10        | 0.33%   |
| Creative Technology                          | 10        | 0.33%   |
| Apple                                        | 10        | 0.33%   |
| JMTek                                        | 9         | 0.3%    |
| Focusrite-Novation                           | 9         | 0.3%    |
| Corsair                                      | 9         | 0.3%    |
| Kingston Technology                          | 8         | 0.27%   |
| Hewlett-Packard                              | 8         | 0.27%   |
| Sony                                         | 6         | 0.2%    |
| Plantronics                                  | 6         | 0.2%    |
| RODE Microphones                             | 5         | 0.17%   |
| Bose                                         | 5         | 0.17%   |
| Micro Star International                     | 4         | 0.13%   |
| Generalplus Technology                       | 4         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.1%    |
| ZOOM                                         | 3         | 0.1%    |
| Yamaha                                       | 3         | 0.1%    |
| Sennheiser Communications                    | 3         | 0.1%    |
| GYROCOM C&C                                  | 3         | 0.1%    |
| Conexant Systems                             | 3         | 0.1%    |
| Asahi Kasei Microsystems                     | 3         | 0.1%    |
| XMOS                                         | 2         | 0.07%   |
| Thomann                                      | 2         | 0.07%   |
| SAVITECH                                     | 2         | 0.07%   |
| Samson Technologies                          | 2         | 0.07%   |
| Project                                      | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Microdia                                     | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 215       | 6.02%   |
| Intel Sunrise Point-LP HD Audio                                            | 154       | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 137       | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 127       | 3.55%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 125       | 3.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 110       | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 94        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 78        | 2.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 76        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 73        | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 64        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 60        | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 55        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 55        | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 54        | 1.51%   |
| Intel Haswell-ULT HD Audio Controller                                      | 49        | 1.37%   |
| Intel 8 Series HD Audio Controller                                         | 49        | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 49        | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 48        | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 47        | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 46        | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 44        | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 42        | 1.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 40        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37        | 1.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 36        | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 36        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 33        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 32        | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                              | 31        | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 30        | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 29        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 27        | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 27        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 26        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 26        | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 26        | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 24        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 305       | 22.33%  |
| SK hynix                     | 218       | 15.96%  |
| Kingston                     | 163       | 11.93%  |
| Micron Technology            | 144       | 10.54%  |
| Corsair                      | 128       | 9.37%   |
| Crucial                      | 109       | 7.98%   |
| Unknown                      | 96        | 7.03%   |
| G.Skill                      | 77        | 5.64%   |
| Ramaxel Technology           | 26        | 1.9%    |
| Elpida                       | 19        | 1.39%   |
| Unknown (ABCD)               | 17        | 1.24%   |
| A-DATA Technology            | 12        | 0.88%   |
| Nanya Technology             | 10        | 0.73%   |
| Silicon Power                | 4         | 0.29%   |
| Transcend                    | 3         | 0.22%   |
| Team                         | 3         | 0.22%   |
| GOODRAM                      | 3         | 0.22%   |
| Avant                        | 3         | 0.22%   |
| Unknown                      | 3         | 0.22%   |
| Toshiba                      | 2         | 0.15%   |
| JOY-IT                       | 2         | 0.15%   |
| Hewlett-Packard              | 2         | 0.15%   |
| Vaseky                       | 1         | 0.07%   |
| Unknown (130B)               | 1         | 0.07%   |
| Unknown (09D5)               | 1         | 0.07%   |
| Unifosa                      | 1         | 0.07%   |
| TakeMS                       | 1         | 0.07%   |
| Smart                        | 1         | 0.07%   |
| Qimonda                      | 1         | 0.07%   |
| PNY                          | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Patriot                      | 1         | 0.07%   |
| Mushkin                      | 1         | 0.07%   |
| Kingmax Semiconductor        | 1         | 0.07%   |
| Hitachi                      | 1         | 0.07%   |
| CSX                          | 1         | 0.07%   |
| ChangXin Memory              | 1         | 0.07%   |
| ASint Technology             | 1         | 0.07%   |
| 51010818AB6A1D42             | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 20        | 1.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 17        | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 14        | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.83%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s               | 12        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 11        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.76%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s              | 11        | 0.76%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 9         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 9         | 0.62%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 9         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 8         | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 8         | 0.55%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 8         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 8         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 8         | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 0.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 0.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 7         | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 7         | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.42%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 6         | 0.42%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.42%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s                | 6         | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 6         | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.35%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 5         | 0.35%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 5         | 0.35%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 0.35%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 5         | 0.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 0.35%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 5         | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 5         | 0.35%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 5         | 0.35%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                  | 5         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 616       | 52.43%  |
| DDR3    | 362       | 30.81%  |
| LPDDR4  | 51        | 4.34%   |
| DDR2    | 46        | 3.91%   |
| LPDDR3  | 28        | 2.38%   |
| SDRAM   | 23        | 1.96%   |
| DDR5    | 18        | 1.53%   |
| LPDDR5  | 14        | 1.19%   |
| Unknown | 14        | 1.19%   |
| DDR     | 3         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 642       | 54.41%  |
| DIMM         | 433       | 36.69%  |
| Row Of Chips | 96        | 8.14%   |
| Chip         | 8         | 0.68%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 532       | 41.66%  |
| 4096  | 278       | 21.77%  |
| 16384 | 256       | 20.05%  |
| 2048  | 128       | 10.02%  |
| 32768 | 51        | 3.99%   |
| 1024  | 25        | 1.96%   |
| 512   | 4         | 0.31%   |
| 65536 | 1         | 0.08%   |
| 256   | 1         | 0.08%   |
| 16    | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 231       | 18.25%  |
| 1600    | 226       | 17.85%  |
| 2667    | 170       | 13.43%  |
| 2400    | 106       | 8.37%   |
| 1333    | 70        | 5.53%   |
| 2133    | 61        | 4.82%   |
| 3600    | 35        | 2.76%   |
| 1334    | 30        | 2.37%   |
| 667     | 28        | 2.21%   |
| 4267    | 21        | 1.66%   |
| 3733    | 20        | 1.58%   |
| 1867    | 20        | 1.58%   |
| 1800    | 16        | 1.26%   |
| 800     | 16        | 1.26%   |
| 6400    | 13        | 1.03%   |
| 3800    | 13        | 1.03%   |
| 1067    | 12        | 0.95%   |
| 4800    | 11        | 0.87%   |
| Unknown | 11        | 0.87%   |
| 3266    | 10        | 0.79%   |
| 3000    | 10        | 0.79%   |
| 2933    | 10        | 0.79%   |
| 2666    | 9         | 0.71%   |
| 8400    | 8         | 0.63%   |
| 4199    | 8         | 0.63%   |
| 5600    | 7         | 0.55%   |
| 3533    | 7         | 0.55%   |
| 1866    | 7         | 0.55%   |
| 3866    | 6         | 0.47%   |
| 3400    | 6         | 0.47%   |
| 1066    | 6         | 0.47%   |
| 3066    | 5         | 0.39%   |
| 2048    | 5         | 0.39%   |
| 4266    | 4         | 0.32%   |
| 3666    | 4         | 0.32%   |
| 4000    | 3         | 0.24%   |
| 3534    | 3         | 0.24%   |
| 3466    | 3         | 0.24%   |
| 2134    | 3         | 0.24%   |
| 533     | 3         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 18        | 30.51%  |
| Canon                 | 16        | 27.12%  |
| Brother Industries    | 11        | 18.64%  |
| Seiko Epson           | 6         | 10.17%  |
| Samsung Electronics   | 3         | 5.08%   |
| Ricoh                 | 1         | 1.69%   |
| QinHeng Electronics   | 1         | 1.69%   |
| Prolific Technology   | 1         | 1.69%   |
| Oki Data              | 1         | 1.69%   |
| Lexmark International | 1         | 1.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3520 series                                     | 3         | 4.92%   |
| Seiko Epson XP-235 Series                                  | 2         | 3.28%   |
| Seiko Epson WF-2530 Series                                 | 2         | 3.28%   |
| Samsung C48x Series                                        | 2         | 3.28%   |
| HP LaserJet 1320                                           | 2         | 3.28%   |
| HP ENVY 4520 series                                        | 2         | 3.28%   |
| Canon TS5100 series                                        | 2         | 3.28%   |
| Canon CanoScan LiDE 300                                    | 2         | 3.28%   |
| Brother Printer                                            | 2         | 3.28%   |
| Brother MFC-L2710DW series                                 | 2         | 3.28%   |
| Brother HL-3040CN series                                   | 2         | 3.28%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.64%   |
| Seiko Epson AL-M310DN                                      | 1         | 1.64%   |
| Samsung SCX-4300 Series                                    | 1         | 1.64%   |
| Ricoh SP 211SU                                             | 1         | 1.64%   |
| QinHeng CH340S                                             | 1         | 1.64%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.64%   |
| Oki Data USB Device                                        | 1         | 1.64%   |
| Lexmark International CS417dn                              | 1         | 1.64%   |
| HP OfficeJet Pro 7720 series                               | 1         | 1.64%   |
| HP LaserJet Professional P1102w                            | 1         | 1.64%   |
| HP LaserJet P1102                                          | 1         | 1.64%   |
| HP LaserJet 1200                                           | 1         | 1.64%   |
| HP LaserJet 1022                                           | 1         | 1.64%   |
| HP ENVY Pro 6400 series                                    | 1         | 1.64%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.64%   |
| HP ENVY 5000 series                                        | 1         | 1.64%   |
| HP DeskJet 940c                                            | 1         | 1.64%   |
| HP DeskJet 2700 series                                     | 1         | 1.64%   |
| HP DeskJet 2600 series                                     | 1         | 1.64%   |
| HP Deskjet 2050 J510                                       | 1         | 1.64%   |
| HP Color Laser 150nw                                       | 1         | 1.64%   |
| Canon TS700 series                                         | 1         | 1.64%   |
| Canon TS6300 series                                        | 1         | 1.64%   |
| Canon PIXMA MX320 series                                   | 1         | 1.64%   |
| Canon PIXMA MG2500 Series                                  | 1         | 1.64%   |
| Canon PIXMA iX6850 Printer                                 | 1         | 1.64%   |
| Canon MG2100 series                                        | 1         | 1.64%   |
| Canon MF5650 (FAX)                                         | 1         | 1.64%   |
| Canon LiDE 400                                             | 1         | 1.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 26        | 78.79%  |
| Seiko Epson     | 3         | 9.09%   |
| Fujitsu         | 3         | 9.09%   |
| Hewlett-Packard | 1         | 3.03%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan                                           | 4         | 12.12%  |
| Fujitsu ScanSnap SV600                                   | 3         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 3         | 9.09%   |
| Canon CanoScan LiDE 110                                  | 3         | 9.09%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 6.06%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.06%   |
| Canon CanoScan LiDE 60                                   | 2         | 6.06%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 2         | 6.06%   |
| Canon CanoScan LiDE 220                                  | 2         | 6.06%   |
| Canon CanoScan LiDE 200                                  | 2         | 6.06%   |
| Canon CanoScan LiDE 100                                  | 2         | 6.06%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.03%   |
| HP ScanJet 4850C/4890C                                   | 1         | 3.03%   |
| Canon CanoScan N650U/N656U                               | 1         | 3.03%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.03%   |
| Canon CanoScan LiDE 210                                  | 1         | 3.03%   |
| Canon CanoScan FB630U                                    | 1         | 3.03%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 308       | 25.69%  |
| IMC Networks                           | 110       | 9.17%   |
| Microdia                               | 71        | 5.92%   |
| Logitech                               | 70        | 5.84%   |
| Realtek Semiconductor                  | 66        | 5.5%    |
| Bison Electronics                      | 66        | 5.5%    |
| Sunplus Innovation Technology          | 61        | 5.09%   |
| Quanta                                 | 54        | 4.5%    |
| Acer                                   | 41        | 3.42%   |
| Lite-On Technology                     | 38        | 3.17%   |
| Apple                                  | 37        | 3.09%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 3%      |
| Suyin                                  | 31        | 2.59%   |
| Luxvisions Innotech Limited            | 24        | 2%      |
| Syntek                                 | 23        | 1.92%   |
| Microsoft                              | 19        | 1.58%   |
| Alcor Micro                            | 15        | 1.25%   |
| Samsung Electronics                    | 12        | 1%      |
| Lenovo                                 | 9         | 0.75%   |
| Z-Star Microelectronics                | 8         | 0.67%   |
| Ricoh                                  | 7         | 0.58%   |
| Jieli Technology                       | 7         | 0.58%   |
| Primax Electronics                     | 6         | 0.5%    |
| ARC International                      | 5         | 0.42%   |
| USB Camera                             | 4         | 0.33%   |
| OmniVision Technologies                | 4         | 0.33%   |
| SunplusIT                              | 3         | 0.25%   |
| Sonix Technology                       | 3         | 0.25%   |
| SJ-180517-N                            | 3         | 0.25%   |
| Silicon Motion                         | 3         | 0.25%   |
| SHENZHEN EMEET TECHNOLOGY              | 3         | 0.25%   |
| SHENZHEN AONI ELECTRONIC               | 3         | 0.25%   |
| KYE Systems (Mouse Systems)            | 3         | 0.25%   |
| Generalplus Technology                 | 3         | 0.25%   |
| Fujitsu                                | 3         | 0.25%   |
| DigiTech                               | 3         | 0.25%   |
| XHT-211220-ZW                          | 2         | 0.17%   |
| Trust                                  | 2         | 0.17%   |
| Tobii Technology AB                    | 2         | 0.17%   |
| Sunplus Technology                     | 2         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 83        | 6.86%   |
| IMC Networks Integrated Camera           | 53        | 4.38%   |
| Microdia Integrated_Webcam_HD            | 28        | 2.31%   |
| Chicony HD WebCam                        | 27        | 2.23%   |
| Bison Integrated Camera                  | 26        | 2.15%   |
| Chicony HP HD Camera                     | 21        | 1.74%   |
| IMC Networks USB2.0 HD UVC WebCam        | 20        | 1.65%   |
| Realtek Integrated_Webcam_HD             | 18        | 1.49%   |
| Quanta HD User Facing                    | 16        | 1.32%   |
| Lite-On Integrated Camera                | 15        | 1.24%   |
| Acer Integrated Camera                   | 15        | 1.24%   |
| Sunplus Integrated_Webcam_HD             | 13        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 13        | 1.07%   |
| Samsung Galaxy series, misc. (MTP mode)  | 12        | 0.99%   |
| Quanta HP HD Camera                      | 12        | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 12        | 0.99%   |
| Syntek Integrated Camera                 | 11        | 0.91%   |
| Logitech Webcam C270                     | 11        | 0.91%   |
| Logitech HD Pro Webcam C920              | 11        | 0.91%   |
| Chicony TOSHIBA Web Camera - HD          | 11        | 0.91%   |
| Realtek USB2.0 HD UVC WebCam             | 10        | 0.83%   |
| Lite-On HP HD Camera                     | 10        | 0.83%   |
| Chicony USB2.0 HD UVC WebCam             | 10        | 0.83%   |
| Chicony HP HD Webcam                     | 10        | 0.83%   |
| Chicony VGA WebCam                       | 9         | 0.74%   |
| Chicony USB 2.0 Camera                   | 9         | 0.74%   |
| Bison Lenovo EasyCamera                  | 9         | 0.74%   |
| Apple FaceTime HD Camera                 | 9         | 0.74%   |
| Apple Built-in iSight                    | 9         | 0.74%   |
| Acer SunplusIT Integrated Camera         | 9         | 0.74%   |
| Microsoft LifeCam HD-3000                | 8         | 0.66%   |
| Logitech C922 Pro Stream Webcam          | 8         | 0.66%   |
| Sunplus FHD Camera Microphone            | 7         | 0.58%   |
| Realtek HD WebCam                        | 7         | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera | 7         | 0.58%   |
| Jieli USB PHY 2.0                        | 7         | 0.58%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 0.58%   |
| Chicony Integrated HP HD Webcam          | 7         | 0.58%   |
| Chicony Integrated Camera (1280x720@30)  | 7         | 0.58%   |
| Chicony HP Truevision HD camera          | 7         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 125       | 37.54%  |
| Validity Sensors           | 120       | 36.04%  |
| Shenzhen Goodix Technology | 32        | 9.61%   |
| Upek                       | 18        | 5.41%   |
| AuthenTec                  | 17        | 5.11%   |
| Elan Microelectronics      | 12        | 3.6%    |
| LighTuning Technology      | 7         | 2.1%    |
| STMicroelectronics         | 1         | 0.3%    |
| Focal-systems.Corp         | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 52        | 15.57%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 9.88%   |
| Shenzhen Goodix  Fingerprint Device                                        | 20        | 5.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 5.39%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 5.09%   |
| Synaptics WBDI                                                             | 12        | 3.59%   |
| Validity Sensors VFS491                                                    | 11        | 3.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 3.29%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 2.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 2.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.4%    |
| AuthenTec AES2810                                                          | 8         | 2.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 2.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.1%    |
| Validity Sensors Fingerprint scanner                                       | 7         | 2.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 2.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.8%    |
| Elan ELAN:Fingerprint                                                      | 6         | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.5%    |
| Synaptics UWP WBDI Device                                                  | 5         | 1.5%    |
| Synaptics UWP WBDI                                                         | 5         | 1.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.5%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.2%    |
| Synaptics WBDI Device                                                      | 4         | 1.2%    |
| Elan ELAN:ARM-M4                                                           | 4         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.2%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.9%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 3         | 0.9%    |
| Synaptics  WBDI                                                            | 3         | 0.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.6%    |
| Synaptics TouchPad                                                         | 2         | 0.6%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.6%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.3%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 84        | 52.17%  |
| Broadcom              | 44        | 27.33%  |
| Lenovo                | 12        | 7.45%   |
| Upek                  | 10        | 6.21%   |
| O2 Micro              | 5         | 3.11%   |
| Realtek Semiconductor | 2         | 1.24%   |
| Cherry                | 2         | 1.24%   |
| SCM Microsystems      | 1         | 0.62%   |
| Advanced Card Systems | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 83        | 51.55%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 10.56%  |
| Lenovo Integrated Smart Card Reader                                          | 11        | 6.83%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 6.83%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 6.21%   |
| Broadcom 58200                                                               | 9         | 5.59%   |
| Broadcom 5880                                                                | 7         | 4.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 2.48%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.24%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.62%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.62%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.62%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.62%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.62%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1416      | 65.62%  |
| 1     | 558       | 25.86%  |
| 2     | 131       | 6.07%   |
| 3     | 32        | 1.48%   |
| 4     | 10        | 0.46%   |
| 5     | 5         | 0.23%   |
| 6     | 3         | 0.14%   |
| 8     | 2         | 0.09%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 327       | 34.42%  |
| Graphics card            | 158       | 16.63%  |
| Chipcard                 | 129       | 13.58%  |
| Net/wireless             | 110       | 11.58%  |
| Multimedia controller    | 48        | 5.05%   |
| Communication controller | 36        | 3.79%   |
| Unassigned class         | 26        | 2.74%   |
| Camera                   | 24        | 2.53%   |
| Bluetooth                | 23        | 2.42%   |
| Sound                    | 22        | 2.32%   |
| Card reader              | 10        | 1.05%   |
| Net/ethernet             | 9         | 0.95%   |
| Storage                  | 7         | 0.74%   |
| Modem                    | 5         | 0.53%   |
| Network                  | 4         | 0.42%   |
| Storage/raid             | 3         | 0.32%   |
| Tv card                  | 2         | 0.21%   |
| Storage/ide              | 2         | 0.21%   |
| Flash memory             | 2         | 0.21%   |
| Storage/nvme             | 1         | 0.11%   |
| Storage/ata              | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |

