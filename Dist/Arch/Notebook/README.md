Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 5992

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15-3567            | [50d926ec76](https://linux-hardware.org/?probe=50d926ec76) | Jan 02, 2024 |
| Acidanther... | MacBookPro16,4              | [3c8c520472](https://linux-hardware.org/?probe=3c8c520472) | Jan 02, 2024 |
| Google        | Blooguard                   | [dc6c0354a9](https://linux-hardware.org/?probe=dc6c0354a9) | Jan 02, 2024 |
| Philco        | 14M2                        | [b5771423fb](https://linux-hardware.org/?probe=b5771423fb) | Jan 02, 2024 |
| HP            | ProBook 440 G5              | [04753e77e0](https://linux-hardware.org/?probe=04753e77e0) | Jan 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | [6ea14ec02e](https://linux-hardware.org/?probe=6ea14ec02e) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [8a14ad7cc9](https://linux-hardware.org/?probe=8a14ad7cc9) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [a2acc5bb5f](https://linux-hardware.org/?probe=a2acc5bb5f) | Jan 01, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [67ef36b749](https://linux-hardware.org/?probe=67ef36b749) | Jan 01, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [494b496889](https://linux-hardware.org/?probe=494b496889) | Jan 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [488deac73a](https://linux-hardware.org/?probe=488deac73a) | Jan 01, 2024 |
| Dell          | Latitude 7420               | [a32d08979b](https://linux-hardware.org/?probe=a32d08979b) | Dec 31, 2023 |
| Dell          | Inspiron 15-3567            | [390160b8e5](https://linux-hardware.org/?probe=390160b8e5) | Dec 31, 2023 |
| Dell          | Latitude 7420               | [9bee55a186](https://linux-hardware.org/?probe=9bee55a186) | Dec 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [577f6b15de](https://linux-hardware.org/?probe=577f6b15de) | Dec 31, 2023 |
| Dell          | Inspiron 3537               | [7adc50aeab](https://linux-hardware.org/?probe=7adc50aeab) | Dec 31, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [f160a53f1b](https://linux-hardware.org/?probe=f160a53f1b) | Dec 31, 2023 |
| Apple         | MacBookPro8,2               | [34fcef3266](https://linux-hardware.org/?probe=34fcef3266) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [7130d1a699](https://linux-hardware.org/?probe=7130d1a699) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [d04c4d749f](https://linux-hardware.org/?probe=d04c4d749f) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [815e8736a2](https://linux-hardware.org/?probe=815e8736a2) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [4dd47839a4](https://linux-hardware.org/?probe=4dd47839a4) | Dec 31, 2023 |
| Dell          | Inspiron 15-3567            | [5d1ed5c106](https://linux-hardware.org/?probe=5d1ed5c106) | Dec 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [ff8e890649](https://linux-hardware.org/?probe=ff8e890649) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p              | [e45829bd8b](https://linux-hardware.org/?probe=e45829bd8b) | Dec 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [24ca756f75](https://linux-hardware.org/?probe=24ca756f75) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [36856f5ac1](https://linux-hardware.org/?probe=36856f5ac1) | Dec 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [42c812d36d](https://linux-hardware.org/?probe=42c812d36d) | Dec 29, 2023 |
| Monster       | TULPAR T5 V23.2             | [9592c22858](https://linux-hardware.org/?probe=9592c22858) | Dec 29, 2023 |
| HP            | OMEN Laptop 15-ek1xxx       | [16c7cb0337](https://linux-hardware.org/?probe=16c7cb0337) | Dec 28, 2023 |
| TrekStor      | Notebook Slim S130          | [9fbe38b102](https://linux-hardware.org/?probe=9fbe38b102) | Dec 28, 2023 |
| Razer         | Blade                       | [bd2101718d](https://linux-hardware.org/?probe=bd2101718d) | Dec 28, 2023 |
| Apple         | MacBookPro8,2               | [a353ad122c](https://linux-hardware.org/?probe=a353ad122c) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a81c208684](https://linux-hardware.org/?probe=a81c208684) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c56c8e1bcf](https://linux-hardware.org/?probe=c56c8e1bcf) | Dec 27, 2023 |
| TUXEDO        | Pulse 14 Gen3               | [7873276f27](https://linux-hardware.org/?probe=7873276f27) | Dec 27, 2023 |
| ASUSTek       | X75A                        | [a7b35ca7c8](https://linux-hardware.org/?probe=a7b35ca7c8) | Dec 27, 2023 |
| Lenovo        | IdeaPad S740-15IRH Touch... | [6584c1853d](https://linux-hardware.org/?probe=6584c1853d) | Dec 27, 2023 |
| Gigabyte      | AERO 15-X9                  | [906642b6ec](https://linux-hardware.org/?probe=906642b6ec) | Dec 27, 2023 |
| Alienware     | m16 R1 AMD                  | [98aaf575cc](https://linux-hardware.org/?probe=98aaf575cc) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f2094a7c07](https://linux-hardware.org/?probe=f2094a7c07) | Dec 26, 2023 |
| ASUSTek       | X550CC                      | [6fa1156580](https://linux-hardware.org/?probe=6fa1156580) | Dec 26, 2023 |
| Samsung       | RF511/RF411/RF711           | [743bed087b](https://linux-hardware.org/?probe=743bed087b) | Dec 26, 2023 |
| Dell          | Inspiron 5391               | [a97f2efb6f](https://linux-hardware.org/?probe=a97f2efb6f) | Dec 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [77553a2b0e](https://linux-hardware.org/?probe=77553a2b0e) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | [a35ed82108](https://linux-hardware.org/?probe=a35ed82108) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | [d9ec9cb0f7](https://linux-hardware.org/?probe=d9ec9cb0f7) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [029b043cec](https://linux-hardware.org/?probe=029b043cec) | Dec 25, 2023 |
| HP            | Laptop 14s-fq0xxx           | [00a9997bfc](https://linux-hardware.org/?probe=00a9997bfc) | Dec 25, 2023 |
| Dell          | Latitude E6420              | [ffcec7155a](https://linux-hardware.org/?probe=ffcec7155a) | Dec 25, 2023 |
| ASUSTek       | X550CC                      | [ee3308d282](https://linux-hardware.org/?probe=ee3308d282) | Dec 25, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| ASUSTek       | X75A                        | [3af5f7aed7](https://linux-hardware.org/?probe=3af5f7aed7) | Dec 24, 2023 |
| Acer          | Aspire A315-41              | [a54e95fcab](https://linux-hardware.org/?probe=a54e95fcab) | Dec 24, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [d41bca7300](https://linux-hardware.org/?probe=d41bca7300) | Dec 24, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [8080c75b27](https://linux-hardware.org/?probe=8080c75b27) | Dec 24, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [39e33e4510](https://linux-hardware.org/?probe=39e33e4510) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| TECNO Mobi... | MEGABOOK T15DA              | [82d65cfce4](https://linux-hardware.org/?probe=82d65cfce4) | Dec 23, 2023 |
| Lenovo        | G50-80 80L0                 | [21df7039b9](https://linux-hardware.org/?probe=21df7039b9) | Dec 23, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [569ce717aa](https://linux-hardware.org/?probe=569ce717aa) | Dec 23, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [8dad235090](https://linux-hardware.org/?probe=8dad235090) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8a36394313](https://linux-hardware.org/?probe=8a36394313) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eb035a95fa](https://linux-hardware.org/?probe=eb035a95fa) | Dec 22, 2023 |
| Dell          | Inspiron 5577               | [e6827a291e](https://linux-hardware.org/?probe=e6827a291e) | Dec 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0280... | [239bc0b85a](https://linux-hardware.org/?probe=239bc0b85a) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [e1225d2a37](https://linux-hardware.org/?probe=e1225d2a37) | Dec 22, 2023 |
| HP            | G62                         | [9f6a13bc50](https://linux-hardware.org/?probe=9f6a13bc50) | Dec 22, 2023 |
| ASUSTek       | X75A                        | [ed3c88f944](https://linux-hardware.org/?probe=ed3c88f944) | Dec 22, 2023 |
| Sony          | VPCCA3X1R                   | [156b109950](https://linux-hardware.org/?probe=156b109950) | Dec 21, 2023 |
| HP            | ProBook 6450b               | [dd9c6803cb](https://linux-hardware.org/?probe=dd9c6803cb) | Dec 21, 2023 |
| ASUSTek       | X75A                        | [6d9c65c8ac](https://linux-hardware.org/?probe=6d9c65c8ac) | Dec 21, 2023 |
| HP            | ProBook 6570b               | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| Dell          | Latitude 5590               | [9877862088](https://linux-hardware.org/?probe=9877862088) | Dec 21, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [6e4bcb9311](https://linux-hardware.org/?probe=6e4bcb9311) | Dec 21, 2023 |
| Lenovo        | ThinkPad X280 20KEA00SUK    | [bc380b4334](https://linux-hardware.org/?probe=bc380b4334) | Dec 21, 2023 |
| HUAWEI        | NBLL-WXX9                   | [c125585a5d](https://linux-hardware.org/?probe=c125585a5d) | Dec 21, 2023 |
| Lenovo        | ThinkPad SL 2746E9G         | [594a56a070](https://linux-hardware.org/?probe=594a56a070) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5a16e00d6c](https://linux-hardware.org/?probe=5a16e00d6c) | Dec 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [d420770c44](https://linux-hardware.org/?probe=d420770c44) | Dec 20, 2023 |
| HP            | ProBook 445 14 inch G10 ... | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| Acer          | Aspire E1-771G              | [07bcd26f94](https://linux-hardware.org/?probe=07bcd26f94) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [00d649079a](https://linux-hardware.org/?probe=00d649079a) | Dec 20, 2023 |
| Google        | Pantheon                    | [f4640ed7c1](https://linux-hardware.org/?probe=f4640ed7c1) | Dec 19, 2023 |
| HP            | ElitePad 1000 G2            | [533ccb0c41](https://linux-hardware.org/?probe=533ccb0c41) | Dec 19, 2023 |
| Dell          | Inspiron 15 3535            | [f86bf3e2f1](https://linux-hardware.org/?probe=f86bf3e2f1) | Dec 18, 2023 |
| Apple         | MacBookPro12,1              | [6db91b5eb2](https://linux-hardware.org/?probe=6db91b5eb2) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | [c18f5d3a21](https://linux-hardware.org/?probe=c18f5d3a21) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | [982ae3655c](https://linux-hardware.org/?probe=982ae3655c) | Dec 18, 2023 |
| Samsung       | 750XDA                      | [bdaba42db8](https://linux-hardware.org/?probe=bdaba42db8) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [ed79377477](https://linux-hardware.org/?probe=ed79377477) | Dec 17, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [812cd1effd](https://linux-hardware.org/?probe=812cd1effd) | Dec 16, 2023 |
| Dell          | Latitude 7350               | [ab9a873c1e](https://linux-hardware.org/?probe=ab9a873c1e) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bac2e83dd7](https://linux-hardware.org/?probe=bac2e83dd7) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6689e06c77](https://linux-hardware.org/?probe=6689e06c77) | Dec 15, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | [88ffce598c](https://linux-hardware.org/?probe=88ffce598c) | Dec 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [921d38d2df](https://linux-hardware.org/?probe=921d38d2df) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4cb7a5528b](https://linux-hardware.org/?probe=4cb7a5528b) | Dec 15, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [0b08ee22d8](https://linux-hardware.org/?probe=0b08ee22d8) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [262bfe0585](https://linux-hardware.org/?probe=262bfe0585) | Dec 14, 2023 |
| Dell          | Precision 5680              | [1e063996da](https://linux-hardware.org/?probe=1e063996da) | Dec 14, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [b5b534e106](https://linux-hardware.org/?probe=b5b534e106) | Dec 14, 2023 |
| Apple         | MacBookPro5,1               | [277dadb387](https://linux-hardware.org/?probe=277dadb387) | Dec 13, 2023 |
| Lenovo        | ThinkPad T480 20L50004MX    | [691f1ae82f](https://linux-hardware.org/?probe=691f1ae82f) | Dec 13, 2023 |
| HP            | Laptop 15-bs1xx             | [1785db3e7b](https://linux-hardware.org/?probe=1785db3e7b) | Dec 13, 2023 |
| Timi          | TM1604                      | [67597f3bd5](https://linux-hardware.org/?probe=67597f3bd5) | Dec 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6a497408c3](https://linux-hardware.org/?probe=6a497408c3) | Dec 13, 2023 |
| HP            | Pavilion g6                 | [f79863b604](https://linux-hardware.org/?probe=f79863b604) | Dec 13, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| HP            | Pavilion Notebook           | [81baeeb4c6](https://linux-hardware.org/?probe=81baeeb4c6) | Dec 12, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [e340ad2e3a](https://linux-hardware.org/?probe=e340ad2e3a) | Dec 12, 2023 |
| HP            | ENVY 15                     | [d8a9e409c9](https://linux-hardware.org/?probe=d8a9e409c9) | Dec 12, 2023 |
| ASUSTek       | K45VD                       | [527a669776](https://linux-hardware.org/?probe=527a669776) | Dec 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [c9dd6aebbd](https://linux-hardware.org/?probe=c9dd6aebbd) | Dec 12, 2023 |
| HP            | ProBook 440 G5              | [af38b45c59](https://linux-hardware.org/?probe=af38b45c59) | Dec 12, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [ffcb3c9798](https://linux-hardware.org/?probe=ffcb3c9798) | Dec 11, 2023 |
| Acer          | Aspire E5-571G              | [c136ca6eff](https://linux-hardware.org/?probe=c136ca6eff) | Dec 11, 2023 |
| HUAWEI        | NBD-WXX9                    | [2e767eb168](https://linux-hardware.org/?probe=2e767eb168) | Dec 11, 2023 |
| GPD           | G1619-03                    | [92773d52d8](https://linux-hardware.org/?probe=92773d52d8) | Dec 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | [d9227b24b0](https://linux-hardware.org/?probe=d9227b24b0) | Dec 10, 2023 |
| Dell          | Latitude 7490               | [d9f20ad453](https://linux-hardware.org/?probe=d9f20ad453) | Dec 10, 2023 |
| Dell          | Precision 5480              | [e2ef5d90ca](https://linux-hardware.org/?probe=e2ef5d90ca) | Dec 10, 2023 |
| Acer          | Nitro AN515-58              | [9939fe96d2](https://linux-hardware.org/?probe=9939fe96d2) | Dec 10, 2023 |
| ASUSTek       | ROG Strix G533QM_G533QM     | [200be2174b](https://linux-hardware.org/?probe=200be2174b) | Dec 09, 2023 |
| ASUSTek       | X540SA                      | [71c6b35d56](https://linux-hardware.org/?probe=71c6b35d56) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [551b412a34](https://linux-hardware.org/?probe=551b412a34) | Dec 09, 2023 |
| Dell          | Inspiron 5567               | [ac6488c0c8](https://linux-hardware.org/?probe=ac6488c0c8) | Dec 09, 2023 |
| Acer          | AOD270                      | [b5729a6428](https://linux-hardware.org/?probe=b5729a6428) | Dec 09, 2023 |
| Dell          | Inspiron 5567               | [f061ab31d0](https://linux-hardware.org/?probe=f061ab31d0) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [051769648f](https://linux-hardware.org/?probe=051769648f) | Dec 09, 2023 |
| Dell          | Latitude E5550              | [740c338fbe](https://linux-hardware.org/?probe=740c338fbe) | Dec 08, 2023 |
| GPD           | G1619-03                    | [bc2ade83b8](https://linux-hardware.org/?probe=bc2ade83b8) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [a696c1d832](https://linux-hardware.org/?probe=a696c1d832) | Dec 08, 2023 |
| Maibenben     | MaiBook X series            | [d3de4cf5b2](https://linux-hardware.org/?probe=d3de4cf5b2) | Dec 08, 2023 |
| ASUSTek       | X540SC                      | [4d5388e6ab](https://linux-hardware.org/?probe=4d5388e6ab) | Dec 08, 2023 |
| Dell          | Latitude E5550              | [52866a9d1a](https://linux-hardware.org/?probe=52866a9d1a) | Dec 08, 2023 |
| Alienware     | x15 R1                      | [08aa034a6d](https://linux-hardware.org/?probe=08aa034a6d) | Dec 08, 2023 |
| Acer          | Aspire E1-771G              | [099fae46db](https://linux-hardware.org/?probe=099fae46db) | Dec 07, 2023 |
| VPU Compan... | VWNC71429-S                 | [c0b0f86403](https://linux-hardware.org/?probe=c0b0f86403) | Dec 07, 2023 |
| Lenovo        | ThinkPad T480s 20L7001LM... | [37c62fe0ba](https://linux-hardware.org/?probe=37c62fe0ba) | Dec 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c37147ae36](https://linux-hardware.org/?probe=c37147ae36) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [87aa35c45c](https://linux-hardware.org/?probe=87aa35c45c) | Dec 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [36fe4a1de9](https://linux-hardware.org/?probe=36fe4a1de9) | Dec 06, 2023 |
| Acer          | Aspire E1-771G              | [28f6aca279](https://linux-hardware.org/?probe=28f6aca279) | Dec 06, 2023 |
| ASUSTek       | P553UA                      | [4c19d8a91e](https://linux-hardware.org/?probe=4c19d8a91e) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ed77f35114](https://linux-hardware.org/?probe=ed77f35114) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ac764bedcc](https://linux-hardware.org/?probe=ac764bedcc) | Dec 06, 2023 |
| Acer          | Nitro AN515-58              | [a475eb0eb8](https://linux-hardware.org/?probe=a475eb0eb8) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [fae6162d7b](https://linux-hardware.org/?probe=fae6162d7b) | Dec 06, 2023 |
| Acer          | Aspire E5-772G              | [1be5bb95d1](https://linux-hardware.org/?probe=1be5bb95d1) | Dec 05, 2023 |
| Lenovo        | G500 20236                  | [6d0f07a930](https://linux-hardware.org/?probe=6d0f07a930) | Dec 05, 2023 |
| HP            | Pavilion 13 x360 PC         | [3eba272feb](https://linux-hardware.org/?probe=3eba272feb) | Dec 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a2c9c3b295](https://linux-hardware.org/?probe=a2c9c3b295) | Dec 05, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [0964d78171](https://linux-hardware.org/?probe=0964d78171) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d91e8dc1a8](https://linux-hardware.org/?probe=d91e8dc1a8) | Dec 04, 2023 |
| Dell          | Latitude 7350               | [74c3983604](https://linux-hardware.org/?probe=74c3983604) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b1fdfbc998](https://linux-hardware.org/?probe=b1fdfbc998) | Dec 03, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [3c9d00c839](https://linux-hardware.org/?probe=3c9d00c839) | Dec 03, 2023 |
| ASUSTek       | N552VW                      | [c2e09d65d5](https://linux-hardware.org/?probe=c2e09d65d5) | Dec 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b052f32ef5](https://linux-hardware.org/?probe=b052f32ef5) | Dec 03, 2023 |
| HP            | ZBook 17 G2                 | [e1edd54ac3](https://linux-hardware.org/?probe=e1edd54ac3) | Dec 03, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | [f4c7fc7890](https://linux-hardware.org/?probe=f4c7fc7890) | Dec 03, 2023 |
| System76      | Lemur Pro                   | [8dcc66a7e6](https://linux-hardware.org/?probe=8dcc66a7e6) | Dec 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a18c178195](https://linux-hardware.org/?probe=a18c178195) | Dec 02, 2023 |
| Gigabyte      | AERO 15 KD                  | [58b6cdf11c](https://linux-hardware.org/?probe=58b6cdf11c) | Dec 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1G63Q    | [0bb363e4fc](https://linux-hardware.org/?probe=0bb363e4fc) | Dec 02, 2023 |
| ASUSTek       | X550CC                      | [cc61afde30](https://linux-hardware.org/?probe=cc61afde30) | Dec 02, 2023 |
| HP            | Notebook                    | [399699d1ce](https://linux-hardware.org/?probe=399699d1ce) | Dec 02, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [5cf002f5af](https://linux-hardware.org/?probe=5cf002f5af) | Dec 02, 2023 |
| Acer          | Nitro AN515-58              | [34df3b2497](https://linux-hardware.org/?probe=34df3b2497) | Dec 02, 2023 |
| HP            | ZBook 15 G2                 | [ba6823f38e](https://linux-hardware.org/?probe=ba6823f38e) | Dec 02, 2023 |
| Framework     | Laptop                      | [92f0d97b05](https://linux-hardware.org/?probe=92f0d97b05) | Dec 02, 2023 |
| Framework     | Laptop                      | [995d231691](https://linux-hardware.org/?probe=995d231691) | Dec 02, 2023 |
| Casper        | EXCALIBUR G770              | [f5e978e47d](https://linux-hardware.org/?probe=f5e978e47d) | Dec 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6ece5a0c44](https://linux-hardware.org/?probe=6ece5a0c44) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [27ca1601a1](https://linux-hardware.org/?probe=27ca1601a1) | Dec 01, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | [a82cdb418c](https://linux-hardware.org/?probe=a82cdb418c) | Dec 01, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [22263182fb](https://linux-hardware.org/?probe=22263182fb) | Dec 01, 2023 |
| Lenovo        | 14w Gen 2 82N8              | [bc02b5a084](https://linux-hardware.org/?probe=bc02b5a084) | Dec 01, 2023 |
| Lenovo        | B5400 20278                 | [fd17e40f77](https://linux-hardware.org/?probe=fd17e40f77) | Dec 01, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [f98f84669d](https://linux-hardware.org/?probe=f98f84669d) | Dec 01, 2023 |
| Dell          | Inspiron 15 3520            | [945c324d2b](https://linux-hardware.org/?probe=945c324d2b) | Nov 30, 2023 |
| Acer          | Nitro AN515-54              | [7c4f4d3207](https://linux-hardware.org/?probe=7c4f4d3207) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e0e3a6f229](https://linux-hardware.org/?probe=e0e3a6f229) | Nov 30, 2023 |
| Lenovo        | ThinkPad T14s Gen1 20UH0... | [9c37d9bff8](https://linux-hardware.org/?probe=9c37d9bff8) | Nov 30, 2023 |
| Dell          | Precision M6800             | [0112706077](https://linux-hardware.org/?probe=0112706077) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | [eb52097d1b](https://linux-hardware.org/?probe=eb52097d1b) | Nov 29, 2023 |
| HP            | EliteBook 840 G1            | [bb1d8fb09e](https://linux-hardware.org/?probe=bb1d8fb09e) | Nov 29, 2023 |
| HP            | EliteBook 8530p             | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Lenovo        | ThinkPad P52s 20LCA0ANUK    | [2cf85106d8](https://linux-hardware.org/?probe=2cf85106d8) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [f43aaf1d39](https://linux-hardware.org/?probe=f43aaf1d39) | Nov 29, 2023 |
| HP            | 255 G8 Notebook PC          | [be0c718878](https://linux-hardware.org/?probe=be0c718878) | Nov 29, 2023 |
| Gigabyte      | AERO 15 KD                  | [772e5ce3f6](https://linux-hardware.org/?probe=772e5ce3f6) | Nov 29, 2023 |
| ASUSTek       | K501UW                      | [37ecb34a8a](https://linux-hardware.org/?probe=37ecb34a8a) | Nov 29, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [21451de65a](https://linux-hardware.org/?probe=21451de65a) | Nov 28, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [2a9b640b54](https://linux-hardware.org/?probe=2a9b640b54) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [35775b438a](https://linux-hardware.org/?probe=35775b438a) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [b8337b50d8](https://linux-hardware.org/?probe=b8337b50d8) | Nov 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [5358617403](https://linux-hardware.org/?probe=5358617403) | Nov 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [8c51aa422e](https://linux-hardware.org/?probe=8c51aa422e) | Nov 27, 2023 |
| ASUSTek       | X550ZE                      | [d597be352c](https://linux-hardware.org/?probe=d597be352c) | Nov 27, 2023 |
| HP            | 255 G8 Notebook PC          | [3342bb8661](https://linux-hardware.org/?probe=3342bb8661) | Nov 27, 2023 |
| Google        | Osiris                      | [104c509853](https://linux-hardware.org/?probe=104c509853) | Nov 26, 2023 |
| Apple         | MacBookPro11,1              | [9bb8e96cf9](https://linux-hardware.org/?probe=9bb8e96cf9) | Nov 26, 2023 |
| Acer          | Aspire Lite AL15-41         | [1ab369fc06](https://linux-hardware.org/?probe=1ab369fc06) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ce86d3d6](https://linux-hardware.org/?probe=76ce86d3d6) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [41443f69e3](https://linux-hardware.org/?probe=41443f69e3) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | [e17bdfe79f](https://linux-hardware.org/?probe=e17bdfe79f) | Nov 25, 2023 |
| Acer          | Swift SF314-59              | [3ffe3ca5b7](https://linux-hardware.org/?probe=3ffe3ca5b7) | Nov 25, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [5cbdf33238](https://linux-hardware.org/?probe=5cbdf33238) | Nov 25, 2023 |
| Timi          | TM1604                      | [6dca61908e](https://linux-hardware.org/?probe=6dca61908e) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [5b41f73363](https://linux-hardware.org/?probe=5b41f73363) | Nov 25, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [0b974daf24](https://linux-hardware.org/?probe=0b974daf24) | Nov 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d69be34130](https://linux-hardware.org/?probe=d69be34130) | Nov 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [e225477a30](https://linux-hardware.org/?probe=e225477a30) | Nov 24, 2023 |
| HP            | EliteBook 1040 14 inch G... | [f84212c870](https://linux-hardware.org/?probe=f84212c870) | Nov 24, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [432ec62dd0](https://linux-hardware.org/?probe=432ec62dd0) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | [1302407078](https://linux-hardware.org/?probe=1302407078) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | [7871e7654b](https://linux-hardware.org/?probe=7871e7654b) | Nov 24, 2023 |
| HP            | 255 G8 Notebook PC          | [dfe4473084](https://linux-hardware.org/?probe=dfe4473084) | Nov 24, 2023 |
| Apple         | MacBookPro14,3              | [f6a6c2a2fe](https://linux-hardware.org/?probe=f6a6c2a2fe) | Nov 24, 2023 |
| Dell          | G3 3500                     | [c53dff54a2](https://linux-hardware.org/?probe=c53dff54a2) | Nov 24, 2023 |
| A14CR         | Unknown                     | [c0924a368e](https://linux-hardware.org/?probe=c0924a368e) | Nov 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [c45c9df0f9](https://linux-hardware.org/?probe=c45c9df0f9) | Nov 24, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [422a19e5a3](https://linux-hardware.org/?probe=422a19e5a3) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [aaccb61f12](https://linux-hardware.org/?probe=aaccb61f12) | Nov 24, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [df38b119a1](https://linux-hardware.org/?probe=df38b119a1) | Nov 23, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [04dd78f309](https://linux-hardware.org/?probe=04dd78f309) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | [e0be96f7e5](https://linux-hardware.org/?probe=e0be96f7e5) | Nov 23, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [e01de3faf5](https://linux-hardware.org/?probe=e01de3faf5) | Nov 23, 2023 |
| Acer          | Aspire E5-576               | [714225261c](https://linux-hardware.org/?probe=714225261c) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [193588412a](https://linux-hardware.org/?probe=193588412a) | Nov 23, 2023 |
| Dell          | Latitude E6420              | [dab1a90459](https://linux-hardware.org/?probe=dab1a90459) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [7172a8aca0](https://linux-hardware.org/?probe=7172a8aca0) | Nov 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [b23adf2f66](https://linux-hardware.org/?probe=b23adf2f66) | Nov 22, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c6e62720db](https://linux-hardware.org/?probe=c6e62720db) | Nov 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [522acd0620](https://linux-hardware.org/?probe=522acd0620) | Nov 22, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | [746bd8c3d5](https://linux-hardware.org/?probe=746bd8c3d5) | Nov 21, 2023 |
| Lenovo        | ThinkPad T480s 20L7004PG... | [32665cdd0e](https://linux-hardware.org/?probe=32665cdd0e) | Nov 21, 2023 |
| Grupo Nucl... | Eurocase MB40               | [aaedd81604](https://linux-hardware.org/?probe=aaedd81604) | Nov 21, 2023 |
| Grupo Nucl... | Eurocase MB40               | [6c601d96d9](https://linux-hardware.org/?probe=6c601d96d9) | Nov 21, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6b88b81e69](https://linux-hardware.org/?probe=6b88b81e69) | Nov 21, 2023 |
| HP            | Laptop 15-dy1xxx            | [9218c25c70](https://linux-hardware.org/?probe=9218c25c70) | Nov 21, 2023 |
| Dell          | Latitude E6510              | [1ac84451c5](https://linux-hardware.org/?probe=1ac84451c5) | Nov 21, 2023 |
| ASUSTek       | X456UV                      | [f38105228e](https://linux-hardware.org/?probe=f38105228e) | Nov 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [58af364f54](https://linux-hardware.org/?probe=58af364f54) | Nov 20, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4191c265d7](https://linux-hardware.org/?probe=4191c265d7) | Nov 20, 2023 |
| Acer          | Aspire A517-53              | [9572f8f8c1](https://linux-hardware.org/?probe=9572f8f8c1) | Nov 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [6381dd5516](https://linux-hardware.org/?probe=6381dd5516) | Nov 20, 2023 |
| Apple         | MacBookPro10,2              | [a41e49fbb9](https://linux-hardware.org/?probe=a41e49fbb9) | Nov 20, 2023 |
| Acer          | Aspire 5920                 | [ceafa361bc](https://linux-hardware.org/?probe=ceafa361bc) | Nov 19, 2023 |
| ASUSTek       | K56CB                       | [b20c5c71dd](https://linux-hardware.org/?probe=b20c5c71dd) | Nov 19, 2023 |
| Apple         | MacBookPro10,2              | [414a04328d](https://linux-hardware.org/?probe=414a04328d) | Nov 19, 2023 |
| Lenovo        | ThinkBook 16 G5+ ARP 21J... | [e5148f6b93](https://linux-hardware.org/?probe=e5148f6b93) | Nov 18, 2023 |
| Apple         | MacBookAir7,2               | [186bca6f10](https://linux-hardware.org/?probe=186bca6f10) | Nov 18, 2023 |
| Lenovo        | B5400 20278                 | [69336c15b9](https://linux-hardware.org/?probe=69336c15b9) | Nov 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [67b231cfe0](https://linux-hardware.org/?probe=67b231cfe0) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | [8f5057710c](https://linux-hardware.org/?probe=8f5057710c) | Nov 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [e551d74658](https://linux-hardware.org/?probe=e551d74658) | Nov 17, 2023 |
| Dell          | Latitude 3410               | [edb19e1704](https://linux-hardware.org/?probe=edb19e1704) | Nov 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6518d0d83e](https://linux-hardware.org/?probe=6518d0d83e) | Nov 17, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [644a0b97d3](https://linux-hardware.org/?probe=644a0b97d3) | Nov 16, 2023 |
| HONOR         | HYM-WXX                     | [8fd3066986](https://linux-hardware.org/?probe=8fd3066986) | Nov 16, 2023 |
| MSI           | GF75 Thin 10SC              | [5388f8cbdd](https://linux-hardware.org/?probe=5388f8cbdd) | Nov 16, 2023 |
| Samsung       | 300E5M/300E5L               | [0f53418be5](https://linux-hardware.org/?probe=0f53418be5) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470 20HES04Q00    | [ebb179e02e](https://linux-hardware.org/?probe=ebb179e02e) | Nov 16, 2023 |
| Acer          | Nitro AN515-58              | [29dc31d4de](https://linux-hardware.org/?probe=29dc31d4de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0f5f7fb08d](https://linux-hardware.org/?probe=0f5f7fb08d) | Nov 16, 2023 |
| Dell          | G5 5505                     | [d764e0bb8a](https://linux-hardware.org/?probe=d764e0bb8a) | Nov 16, 2023 |
| Acer          | Nitro AN515-58              | [b612f7a489](https://linux-hardware.org/?probe=b612f7a489) | Nov 16, 2023 |
| Alienware     | m15 R6                      | [c341b25df2](https://linux-hardware.org/?probe=c341b25df2) | Nov 16, 2023 |
| Acer          | Aspire ES1-512              | [03c6bfd1ee](https://linux-hardware.org/?probe=03c6bfd1ee) | Nov 15, 2023 |
| Acer          | Aspire ES1-512              | [41ae79ffa6](https://linux-hardware.org/?probe=41ae79ffa6) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [378bb9c07b](https://linux-hardware.org/?probe=378bb9c07b) | Nov 15, 2023 |
| Google        | Markarth                    | [5fb5241c23](https://linux-hardware.org/?probe=5fb5241c23) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [bceb77e476](https://linux-hardware.org/?probe=bceb77e476) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0fae742aa3](https://linux-hardware.org/?probe=0fae742aa3) | Nov 15, 2023 |
| Dell          | Latitude 3340               | [2b92bb812f](https://linux-hardware.org/?probe=2b92bb812f) | Nov 15, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [7725a67bda](https://linux-hardware.org/?probe=7725a67bda) | Nov 15, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [d643e4ee02](https://linux-hardware.org/?probe=d643e4ee02) | Nov 15, 2023 |
| HP            | Laptop 14-fq0xxx            | [a5718f2f4d](https://linux-hardware.org/?probe=a5718f2f4d) | Nov 15, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [0b16b45e10](https://linux-hardware.org/?probe=0b16b45e10) | Nov 14, 2023 |
| Dell          | G3 3779                     | [af4af2b0b5](https://linux-hardware.org/?probe=af4af2b0b5) | Nov 14, 2023 |
| Dell          | G3 3779                     | [e48e3e3d67](https://linux-hardware.org/?probe=e48e3e3d67) | Nov 14, 2023 |
| ASUSTek       | X555QG                      | [243bc51d12](https://linux-hardware.org/?probe=243bc51d12) | Nov 14, 2023 |
| HP            | ZBook 17 G6                 | [b7d9898316](https://linux-hardware.org/?probe=b7d9898316) | Nov 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [b8e2bf284d](https://linux-hardware.org/?probe=b8e2bf284d) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f3d934ed44](https://linux-hardware.org/?probe=f3d934ed44) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ba805ada14](https://linux-hardware.org/?probe=ba805ada14) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [381c8b164d](https://linux-hardware.org/?probe=381c8b164d) | Nov 13, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [22ba69f09d](https://linux-hardware.org/?probe=22ba69f09d) | Nov 13, 2023 |
| Acer          | Nitro AN515-54              | [656ba48c77](https://linux-hardware.org/?probe=656ba48c77) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | [6fb9ac1dd2](https://linux-hardware.org/?probe=6fb9ac1dd2) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 42369N1       | [632121ae02](https://linux-hardware.org/?probe=632121ae02) | Nov 12, 2023 |
| Dell          | Latitude 5420               | [9f68e8d365](https://linux-hardware.org/?probe=9f68e8d365) | Nov 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [51e8be0935](https://linux-hardware.org/?probe=51e8be0935) | Nov 12, 2023 |
| HP            | Pavilion g6                 | [e00bbf5062](https://linux-hardware.org/?probe=e00bbf5062) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4ba028b0e9](https://linux-hardware.org/?probe=4ba028b0e9) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a681b54073](https://linux-hardware.org/?probe=a681b54073) | Nov 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [569f3a5034](https://linux-hardware.org/?probe=569f3a5034) | Nov 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [0ff417d90e](https://linux-hardware.org/?probe=0ff417d90e) | Nov 11, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [bad94e2ebe](https://linux-hardware.org/?probe=bad94e2ebe) | Nov 11, 2023 |
| Lenovo        | ThinkPad P16 Gen 2 21FAC... | [820f65395e](https://linux-hardware.org/?probe=820f65395e) | Nov 11, 2023 |
| Dell          | Latitude 7390               | [b1f996e81e](https://linux-hardware.org/?probe=b1f996e81e) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [4c24ca4aa2](https://linux-hardware.org/?probe=4c24ca4aa2) | Nov 11, 2023 |
| ASUSTek       | X202E                       | [b78da681e7](https://linux-hardware.org/?probe=b78da681e7) | Nov 11, 2023 |
| Chuwi         | GemiBook                    | [5fb8105768](https://linux-hardware.org/?probe=5fb8105768) | Nov 10, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [f2e379d36f](https://linux-hardware.org/?probe=f2e379d36f) | Nov 10, 2023 |
| Apple         | MacBookPro9,1               | [3bd9aacc85](https://linux-hardware.org/?probe=3bd9aacc85) | Nov 10, 2023 |
| System76      | Pangolin                    | [f71f405b6d](https://linux-hardware.org/?probe=f71f405b6d) | Nov 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [ebbeac415f](https://linux-hardware.org/?probe=ebbeac415f) | Nov 10, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| HP            | Elite x2 1012 G1            | [0ffa68a85f](https://linux-hardware.org/?probe=0ffa68a85f) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [4af4346c2a](https://linux-hardware.org/?probe=4af4346c2a) | Nov 09, 2023 |
| Dell          | Vostro 5402                 | [67a604ba54](https://linux-hardware.org/?probe=67a604ba54) | Nov 08, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [745cc9650d](https://linux-hardware.org/?probe=745cc9650d) | Nov 08, 2023 |
| Dell          | Latitude 7280               | [a91cab2bb9](https://linux-hardware.org/?probe=a91cab2bb9) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | [a48d1ad818](https://linux-hardware.org/?probe=a48d1ad818) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | [b5982ee614](https://linux-hardware.org/?probe=b5982ee614) | Nov 08, 2023 |
| Acer          | Swift SF314-511             | [ba5db231dd](https://linux-hardware.org/?probe=ba5db231dd) | Nov 08, 2023 |
| Dell          | Latitude 7280               | [22957cd62d](https://linux-hardware.org/?probe=22957cd62d) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | [3cf76cfbda](https://linux-hardware.org/?probe=3cf76cfbda) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [598b5837e5](https://linux-hardware.org/?probe=598b5837e5) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b9eabfe817](https://linux-hardware.org/?probe=b9eabfe817) | Nov 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [048559335e](https://linux-hardware.org/?probe=048559335e) | Nov 06, 2023 |
| Dell          | G15 5510                    | [270a41e12b](https://linux-hardware.org/?probe=270a41e12b) | Nov 06, 2023 |
| Acer          | Swift SF314-511             | [1e2ba13164](https://linux-hardware.org/?probe=1e2ba13164) | Nov 06, 2023 |
| Apple         | MacBookPro11,3              | [0009d8a468](https://linux-hardware.org/?probe=0009d8a468) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [5cfef4c0b7](https://linux-hardware.org/?probe=5cfef4c0b7) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [f1d9fe0bb7](https://linux-hardware.org/?probe=f1d9fe0bb7) | Nov 06, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | [8d789a3937](https://linux-hardware.org/?probe=8d789a3937) | Nov 06, 2023 |
| MSI           | Bravo 17 C7VF               | [5982277b4b](https://linux-hardware.org/?probe=5982277b4b) | Nov 06, 2023 |
| HP            | EliteBook 830 G5            | [07ef51bd31](https://linux-hardware.org/?probe=07ef51bd31) | Nov 05, 2023 |
| Dell          | Latitude 7280               | [3f1419b0ea](https://linux-hardware.org/?probe=3f1419b0ea) | Nov 05, 2023 |
| HP            | ProBook 450 G5              | [6407166dd5](https://linux-hardware.org/?probe=6407166dd5) | Nov 05, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [53f5c381aa](https://linux-hardware.org/?probe=53f5c381aa) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [c235d90592](https://linux-hardware.org/?probe=c235d90592) | Nov 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [e95c10c89d](https://linux-hardware.org/?probe=e95c10c89d) | Nov 04, 2023 |
| Notebook      | N141CU                      | [8f817eeabf](https://linux-hardware.org/?probe=8f817eeabf) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [34e4bd156f](https://linux-hardware.org/?probe=34e4bd156f) | Nov 04, 2023 |
| HP            | 255 G8 Notebook PC          | [2d1116cd1b](https://linux-hardware.org/?probe=2d1116cd1b) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| Lenovo        | IdeaPad 710S Plus-13ISK ... | [f143d09ba7](https://linux-hardware.org/?probe=f143d09ba7) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [d17e6059bb](https://linux-hardware.org/?probe=d17e6059bb) | Nov 03, 2023 |
| HP            | OMEN by Laptop 17-ck2xxx    | [e34a0ab109](https://linux-hardware.org/?probe=e34a0ab109) | Nov 03, 2023 |
| Dell          | Latitude 7280               | [b795f0157b](https://linux-hardware.org/?probe=b795f0157b) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2ac0d5a547](https://linux-hardware.org/?probe=2ac0d5a547) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [bc3b3daf33](https://linux-hardware.org/?probe=bc3b3daf33) | Nov 03, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [9ea1c674f9](https://linux-hardware.org/?probe=9ea1c674f9) | Nov 03, 2023 |
| Notebook      | NJ50_70CU                   | [9cabd6fd2c](https://linux-hardware.org/?probe=9cabd6fd2c) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | [3414d178f2](https://linux-hardware.org/?probe=3414d178f2) | Nov 02, 2023 |
| Dell          | Inspiron 5567               | [97348209dd](https://linux-hardware.org/?probe=97348209dd) | Nov 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d17a8bc08a](https://linux-hardware.org/?probe=d17a8bc08a) | Nov 02, 2023 |
| Dell          | Latitude E6330              | [b31f60152f](https://linux-hardware.org/?probe=b31f60152f) | Nov 02, 2023 |
| Samsung       | 750XDA                      | [130a1273e5](https://linux-hardware.org/?probe=130a1273e5) | Nov 02, 2023 |
| Fujitsu       | LIFEBOOK A532               | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Valve         | Jupiter                     | [3ee2512ba0](https://linux-hardware.org/?probe=3ee2512ba0) | Nov 02, 2023 |
| Valve         | Jupiter                     | [2c454d7632](https://linux-hardware.org/?probe=2c454d7632) | Nov 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c7d2d860fb](https://linux-hardware.org/?probe=c7d2d860fb) | Nov 02, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [4ba182f0d5](https://linux-hardware.org/?probe=4ba182f0d5) | Nov 02, 2023 |
| ASUSTek       | K56CB                       | [9fff1dc94c](https://linux-hardware.org/?probe=9fff1dc94c) | Nov 01, 2023 |
| Dell          | Latitude 7370               | [b16724db59](https://linux-hardware.org/?probe=b16724db59) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3c04d0213b](https://linux-hardware.org/?probe=3c04d0213b) | Nov 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6afebfd732](https://linux-hardware.org/?probe=6afebfd732) | Nov 01, 2023 |
| HP            | Laptop 15-bs1xx             | [1bd48815fe](https://linux-hardware.org/?probe=1bd48815fe) | Nov 01, 2023 |
| Dell          | Inspiron 7520               | [460c9255bd](https://linux-hardware.org/?probe=460c9255bd) | Nov 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [446efaf1bb](https://linux-hardware.org/?probe=446efaf1bb) | Oct 31, 2023 |
| ASUSTek       | F5N                         | [8da324b4fa](https://linux-hardware.org/?probe=8da324b4fa) | Oct 31, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8e86103e06](https://linux-hardware.org/?probe=8e86103e06) | Oct 31, 2023 |
| Samsung       | 750XED                      | [9dab50e37e](https://linux-hardware.org/?probe=9dab50e37e) | Oct 31, 2023 |
| Dell          | G15 5515                    | [c59e97ba9e](https://linux-hardware.org/?probe=c59e97ba9e) | Oct 31, 2023 |
| Dell          | Vostro 3549                 | [259c646ecb](https://linux-hardware.org/?probe=259c646ecb) | Oct 31, 2023 |
| HP            | Laptop 15s-eq0xxx           | [1323e3ad04](https://linux-hardware.org/?probe=1323e3ad04) | Oct 31, 2023 |
| Lenovo        | G500 20236                  | [6779e74408](https://linux-hardware.org/?probe=6779e74408) | Oct 31, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [38b70999b9](https://linux-hardware.org/?probe=38b70999b9) | Oct 31, 2023 |
| Lenovo        | G500 20236                  | [000230db12](https://linux-hardware.org/?probe=000230db12) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ab5cef69c3](https://linux-hardware.org/?probe=ab5cef69c3) | Oct 30, 2023 |
| HP            | Pavilion Gaming Notebook    | [17dd2ce988](https://linux-hardware.org/?probe=17dd2ce988) | Oct 30, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [5f8cf197d5](https://linux-hardware.org/?probe=5f8cf197d5) | Oct 30, 2023 |
| HP            | 255 G8 Notebook PC          | [941ca289ce](https://linux-hardware.org/?probe=941ca289ce) | Oct 30, 2023 |
| MSI           | GP66 Leopard 10UG           | [47dbfa475a](https://linux-hardware.org/?probe=47dbfa475a) | Oct 30, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [2b883f993f](https://linux-hardware.org/?probe=2b883f993f) | Oct 30, 2023 |
| MSI           | GF75 Thin 10SC              | [7aa47ebfa1](https://linux-hardware.org/?probe=7aa47ebfa1) | Oct 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE13    | [28a8f59777](https://linux-hardware.org/?probe=28a8f59777) | Oct 29, 2023 |
| Lenovo        | ThinkPad X250 20CMS04J00    | [773098b9e5](https://linux-hardware.org/?probe=773098b9e5) | Oct 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [d690fa8f27](https://linux-hardware.org/?probe=d690fa8f27) | Oct 29, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [e34ea8701a](https://linux-hardware.org/?probe=e34ea8701a) | Oct 28, 2023 |
| ASRock        | B550M-C                     | [51c187d805](https://linux-hardware.org/?probe=51c187d805) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b65d7d3b4a](https://linux-hardware.org/?probe=b65d7d3b4a) | Oct 28, 2023 |
| HP            | EliteBook 2570p             | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | [07a3c8eea8](https://linux-hardware.org/?probe=07a3c8eea8) | Oct 28, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | [906ed51ecf](https://linux-hardware.org/?probe=906ed51ecf) | Oct 27, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | [f74328fd58](https://linux-hardware.org/?probe=f74328fd58) | Oct 27, 2023 |
| HONOR         | BOD-WXX9                    | [6de8b3afda](https://linux-hardware.org/?probe=6de8b3afda) | Oct 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [334f8582b0](https://linux-hardware.org/?probe=334f8582b0) | Oct 27, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [5e0942e6b0](https://linux-hardware.org/?probe=5e0942e6b0) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bbba3e21c7](https://linux-hardware.org/?probe=bbba3e21c7) | Oct 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | [c9ba633d37](https://linux-hardware.org/?probe=c9ba633d37) | Oct 27, 2023 |
| Dell          | Latitude 5430               | [af33081c9b](https://linux-hardware.org/?probe=af33081c9b) | Oct 27, 2023 |
| LG Electro... | 15Z95N-G.AAC6U1             | [7f2e8a07de](https://linux-hardware.org/?probe=7f2e8a07de) | Oct 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | [ae3bbe4ecf](https://linux-hardware.org/?probe=ae3bbe4ecf) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [e3c1de1472](https://linux-hardware.org/?probe=e3c1de1472) | Oct 26, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [cbba790d59](https://linux-hardware.org/?probe=cbba790d59) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [0ed2bd399f](https://linux-hardware.org/?probe=0ed2bd399f) | Oct 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d69762902a](https://linux-hardware.org/?probe=d69762902a) | Oct 25, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [e51b06f086](https://linux-hardware.org/?probe=e51b06f086) | Oct 24, 2023 |
| Apple         | MacBookPro9,2               | [97f4660a4d](https://linux-hardware.org/?probe=97f4660a4d) | Oct 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [3907a62f64](https://linux-hardware.org/?probe=3907a62f64) | Oct 24, 2023 |
| Acer          | Aspire A315-510P            | [332b714861](https://linux-hardware.org/?probe=332b714861) | Oct 24, 2023 |
| Dell          | Inspiron 7559               | [24a664955f](https://linux-hardware.org/?probe=24a664955f) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | [c931b1ef73](https://linux-hardware.org/?probe=c931b1ef73) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G533QM_G533QM     | [a4c0d7be24](https://linux-hardware.org/?probe=a4c0d7be24) | Oct 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4f06b99b2e](https://linux-hardware.org/?probe=4f06b99b2e) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [817e0c8438](https://linux-hardware.org/?probe=817e0c8438) | Oct 23, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [399c501d43](https://linux-hardware.org/?probe=399c501d43) | Oct 23, 2023 |
| Dell          | Latitude 5430               | [8d552380c4](https://linux-hardware.org/?probe=8d552380c4) | Oct 23, 2023 |
| Acer          | Aspire A315-58              | [60402f4ad8](https://linux-hardware.org/?probe=60402f4ad8) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [d04399e8fd](https://linux-hardware.org/?probe=d04399e8fd) | Oct 23, 2023 |
| UNOWHY        | Y13G012S4EI                 | [37680f1ed6](https://linux-hardware.org/?probe=37680f1ed6) | Oct 22, 2023 |
| HP            | 250 G8 Notebook PC          | [9538ff99bf](https://linux-hardware.org/?probe=9538ff99bf) | Oct 22, 2023 |
| Dell          | XPS 9315                    | [e3c5d45e2a](https://linux-hardware.org/?probe=e3c5d45e2a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [2ee834d08a](https://linux-hardware.org/?probe=2ee834d08a) | Oct 22, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [f3cde0eac8](https://linux-hardware.org/?probe=f3cde0eac8) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [f204c7469c](https://linux-hardware.org/?probe=f204c7469c) | Oct 21, 2023 |
| Dell          | Precision 5520              | [79b5c73851](https://linux-hardware.org/?probe=79b5c73851) | Oct 21, 2023 |
| HP            | 250 15.6 inch G10 Notebo... | [f5f8e6f37d](https://linux-hardware.org/?probe=f5f8e6f37d) | Oct 21, 2023 |
| Dell          | Latitude D830               | [53cbc541d2](https://linux-hardware.org/?probe=53cbc541d2) | Oct 20, 2023 |
| Avell High... | B.ON                        | [7f8ce9da76](https://linux-hardware.org/?probe=7f8ce9da76) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7323684232](https://linux-hardware.org/?probe=7323684232) | Oct 20, 2023 |
| Dell          | Vostro 3300                 | [827b95e65c](https://linux-hardware.org/?probe=827b95e65c) | Oct 20, 2023 |
| Acer          | Aspire A315-42G             | [46d5d338b3](https://linux-hardware.org/?probe=46d5d338b3) | Oct 20, 2023 |
| Dell          | XPS 13 9310                 | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| MSI           | GF63 Thin 10SC              | [41635aba8a](https://linux-hardware.org/?probe=41635aba8a) | Oct 19, 2023 |
| MSI           | GF63 Thin 10SC              | [a370d171d1](https://linux-hardware.org/?probe=a370d171d1) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [94cd063a64](https://linux-hardware.org/?probe=94cd063a64) | Oct 19, 2023 |
| Dell          | Latitude E7270              | [673245c691](https://linux-hardware.org/?probe=673245c691) | Oct 19, 2023 |
| Acer          | Aspire A514-55              | [f25a7d5b9e](https://linux-hardware.org/?probe=f25a7d5b9e) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [57dbbcb9f3](https://linux-hardware.org/?probe=57dbbcb9f3) | Oct 18, 2023 |
| Dell          | Inspiron N5110              | [8543bed1b3](https://linux-hardware.org/?probe=8543bed1b3) | Oct 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [843098c658](https://linux-hardware.org/?probe=843098c658) | Oct 17, 2023 |
| Dell          | XPS 13 9310                 | [295c6b08bd](https://linux-hardware.org/?probe=295c6b08bd) | Oct 17, 2023 |
| Dell          | Latitude 7300               | [e68476c5ee](https://linux-hardware.org/?probe=e68476c5ee) | Oct 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [b962ac1dff](https://linux-hardware.org/?probe=b962ac1dff) | Oct 17, 2023 |
| Dell          | XPS 9315                    | [e629bbd153](https://linux-hardware.org/?probe=e629bbd153) | Oct 16, 2023 |
| Dell          | XPS 9315                    | [a0b5099438](https://linux-hardware.org/?probe=a0b5099438) | Oct 16, 2023 |
| Dell          | Latitude 7424 Rugged Ext... | [5e2983dfb6](https://linux-hardware.org/?probe=5e2983dfb6) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | [e66f442843](https://linux-hardware.org/?probe=e66f442843) | Oct 16, 2023 |
| Dell          | XPS 15 9500                 | [0dcdd0a6a6](https://linux-hardware.org/?probe=0dcdd0a6a6) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | [eab86d1cc0](https://linux-hardware.org/?probe=eab86d1cc0) | Oct 16, 2023 |
| Dell          | Precision M6700             | [2fb2e2e9a5](https://linux-hardware.org/?probe=2fb2e2e9a5) | Oct 16, 2023 |
| ASUSTek       | N551JW                      | [c78d74d584](https://linux-hardware.org/?probe=c78d74d584) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | [7f9e09a9e1](https://linux-hardware.org/?probe=7f9e09a9e1) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | [2571e4fd1b](https://linux-hardware.org/?probe=2571e4fd1b) | Oct 16, 2023 |
| HP            | Victus by Gaming Laptop ... | [f7b210b108](https://linux-hardware.org/?probe=f7b210b108) | Oct 16, 2023 |
| Dell          | Precision 3530              | [79e1f32ab8](https://linux-hardware.org/?probe=79e1f32ab8) | Oct 16, 2023 |
| HONOR         | HYM-WXX                     | [eaff1b458a](https://linux-hardware.org/?probe=eaff1b458a) | Oct 15, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [81cbdd66c8](https://linux-hardware.org/?probe=81cbdd66c8) | Oct 15, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a9438a93a7](https://linux-hardware.org/?probe=a9438a93a7) | Oct 15, 2023 |
| Dell          | XPS 13 9343                 | [97a3c4d92d](https://linux-hardware.org/?probe=97a3c4d92d) | Oct 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [585c33a966](https://linux-hardware.org/?probe=585c33a966) | Oct 15, 2023 |
| HP            | ProBook 6560b               | [49ffe8b6c5](https://linux-hardware.org/?probe=49ffe8b6c5) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [e9d04fdd59](https://linux-hardware.org/?probe=e9d04fdd59) | Oct 14, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ab093317ba](https://linux-hardware.org/?probe=ab093317ba) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [5584acb2f0](https://linux-hardware.org/?probe=5584acb2f0) | Oct 14, 2023 |
| Dell          | Inspiron 5575               | [c50573f4ae](https://linux-hardware.org/?probe=c50573f4ae) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [4015286a79](https://linux-hardware.org/?probe=4015286a79) | Oct 14, 2023 |
| Dell          | Latitude 7390               | [12de4c5026](https://linux-hardware.org/?probe=12de4c5026) | Oct 14, 2023 |
| Sony          | VPCEB15EL                   | [f7a3de3793](https://linux-hardware.org/?probe=f7a3de3793) | Oct 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [08a6026b21](https://linux-hardware.org/?probe=08a6026b21) | Oct 13, 2023 |
| Acer          | Swift SF314-511             | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| Acer          | Aspire E5-523               | [e45e982b6e](https://linux-hardware.org/?probe=e45e982b6e) | Oct 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [c97af886ef](https://linux-hardware.org/?probe=c97af886ef) | Oct 12, 2023 |
| Acer          | Predator PH315-54           | [541e679856](https://linux-hardware.org/?probe=541e679856) | Oct 12, 2023 |
| Dell          | G3 3500                     | [1f975cc52a](https://linux-hardware.org/?probe=1f975cc52a) | Oct 12, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [d5040f4ca4](https://linux-hardware.org/?probe=d5040f4ca4) | Oct 12, 2023 |
| Dell          | XPS 13 9300                 | [6a0e699ccc](https://linux-hardware.org/?probe=6a0e699ccc) | Oct 11, 2023 |
| ASUSTek       | S550CM                      | [ad1b08de66](https://linux-hardware.org/?probe=ad1b08de66) | Oct 10, 2023 |
| HP            | Notebook                    | [efd1dac9ef](https://linux-hardware.org/?probe=efd1dac9ef) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [908a750a93](https://linux-hardware.org/?probe=908a750a93) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [10b2d6465f](https://linux-hardware.org/?probe=10b2d6465f) | Oct 10, 2023 |
| Dell          | Latitude E5440              | [2f6ed33823](https://linux-hardware.org/?probe=2f6ed33823) | Oct 10, 2023 |
| Dell          | Latitude E5440              | [90b9b12b1b](https://linux-hardware.org/?probe=90b9b12b1b) | Oct 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c397035651](https://linux-hardware.org/?probe=c397035651) | Oct 10, 2023 |
| HUAWEI        | HN-WX9X                     | [3bb1bed686](https://linux-hardware.org/?probe=3bb1bed686) | Oct 09, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [6e8b2311e4](https://linux-hardware.org/?probe=6e8b2311e4) | Oct 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d739639932](https://linux-hardware.org/?probe=d739639932) | Oct 09, 2023 |
| HP            | Laptop 15s-eq2xxx           | [341fc3d0f1](https://linux-hardware.org/?probe=341fc3d0f1) | Oct 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [29c7192a14](https://linux-hardware.org/?probe=29c7192a14) | Oct 08, 2023 |
| Dell          | Latitude 3440               | [88a0ec8369](https://linux-hardware.org/?probe=88a0ec8369) | Oct 08, 2023 |
| Dell          | Latitude 7430               | [1de7d3085b](https://linux-hardware.org/?probe=1de7d3085b) | Oct 08, 2023 |
| HP            | Notebook                    | [a181ec12af](https://linux-hardware.org/?probe=a181ec12af) | Oct 08, 2023 |
| HP            | Notebook                    | [039a70e9ce](https://linux-hardware.org/?probe=039a70e9ce) | Oct 07, 2023 |
| Toshiba       | Satellite L655              | [3f3879060f](https://linux-hardware.org/?probe=3f3879060f) | Oct 07, 2023 |
| Dell          | XPS 15 9530                 | [1423f1793b](https://linux-hardware.org/?probe=1423f1793b) | Oct 07, 2023 |
| HP            | EliteBook 8460p             | [80b914414e](https://linux-hardware.org/?probe=80b914414e) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d8d241531e](https://linux-hardware.org/?probe=d8d241531e) | Oct 07, 2023 |
| Apple         | MacBookPro11,1              | [b30fe669c6](https://linux-hardware.org/?probe=b30fe669c6) | Oct 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [0354977d6c](https://linux-hardware.org/?probe=0354977d6c) | Oct 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [faea5bdeba](https://linux-hardware.org/?probe=faea5bdeba) | Oct 07, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| HONOR         | FRI-HXX                     | [fd2a01c055](https://linux-hardware.org/?probe=fd2a01c055) | Oct 06, 2023 |
| HP            | 255 G4                      | [7097fff4ee](https://linux-hardware.org/?probe=7097fff4ee) | Oct 06, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [058c6a0ee6](https://linux-hardware.org/?probe=058c6a0ee6) | Oct 06, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9dc2fd3247](https://linux-hardware.org/?probe=9dc2fd3247) | Oct 06, 2023 |
| Dell          | XPS 15 9530                 | [425aa2b0f7](https://linux-hardware.org/?probe=425aa2b0f7) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [39b9855097](https://linux-hardware.org/?probe=39b9855097) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [74bb875f9f](https://linux-hardware.org/?probe=74bb875f9f) | Oct 05, 2023 |
| Acidanther... | MacBookPro16,4              | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [e23d98e73b](https://linux-hardware.org/?probe=e23d98e73b) | Oct 05, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [02ff66cc0c](https://linux-hardware.org/?probe=02ff66cc0c) | Oct 05, 2023 |
| Timi          | A30                         | [36d352fb7f](https://linux-hardware.org/?probe=36d352fb7f) | Oct 04, 2023 |
| Dell          | Vostro 15-3568              | [3639fedec4](https://linux-hardware.org/?probe=3639fedec4) | Oct 04, 2023 |
| Positivo      | S14BW01                     | [3027fc7d9b](https://linux-hardware.org/?probe=3027fc7d9b) | Oct 04, 2023 |
| HP            | Pavilion g7                 | [ec5cf4fb00](https://linux-hardware.org/?probe=ec5cf4fb00) | Oct 03, 2023 |
| Dell          | Latitude E7440              | [3cb4fc2857](https://linux-hardware.org/?probe=3cb4fc2857) | Oct 03, 2023 |
| Acer          | Aspire A314-36M             | [5276b99f12](https://linux-hardware.org/?probe=5276b99f12) | Oct 03, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [09b97f9681](https://linux-hardware.org/?probe=09b97f9681) | Oct 02, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b0b5262c87](https://linux-hardware.org/?probe=b0b5262c87) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | [11d6cad851](https://linux-hardware.org/?probe=11d6cad851) | Oct 02, 2023 |
| HP            | ProBook 6560b               | [ea59e8557f](https://linux-hardware.org/?probe=ea59e8557f) | Oct 01, 2023 |
| Sony          | SVF1421PSGB                 | [84a0c8ea9b](https://linux-hardware.org/?probe=84a0c8ea9b) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6801ddb23b](https://linux-hardware.org/?probe=6801ddb23b) | Oct 01, 2023 |
| Dell          | Latitude E5450              | [76401b3ca2](https://linux-hardware.org/?probe=76401b3ca2) | Oct 01, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [5ee355215f](https://linux-hardware.org/?probe=5ee355215f) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef74c51c65](https://linux-hardware.org/?probe=ef74c51c65) | Oct 01, 2023 |
| Dell          | Inspiron 5567               | [493a83e70a](https://linux-hardware.org/?probe=493a83e70a) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| HP            | ProBook 6560b               | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| eMachines     | eME732Z                     | [ba03824830](https://linux-hardware.org/?probe=ba03824830) | Sep 29, 2023 |
| Dell          | Precision 5480              | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [eef8975f1e](https://linux-hardware.org/?probe=eef8975f1e) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| Google        | Lindar                      | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| Google        | Lindar                      | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | G3 3590                     | [3523165978](https://linux-hardware.org/?probe=3523165978) | Sep 27, 2023 |
| Dell          | Latitude 3540               | [eb8bf9b174](https://linux-hardware.org/?probe=eb8bf9b174) | Sep 26, 2023 |
| Dell          | G5 5590                     | [c7e7205fff](https://linux-hardware.org/?probe=c7e7205fff) | Sep 26, 2023 |
| Dell          | G5 5590                     | [0e80b66cb6](https://linux-hardware.org/?probe=0e80b66cb6) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [742cfeafb0](https://linux-hardware.org/?probe=742cfeafb0) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a7d0f8e075](https://linux-hardware.org/?probe=a7d0f8e075) | Sep 26, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [1ce8f959f1](https://linux-hardware.org/?probe=1ce8f959f1) | Sep 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [549941d843](https://linux-hardware.org/?probe=549941d843) | Sep 25, 2023 |
| Samsung       | 750XDA                      | [dd03d00004](https://linux-hardware.org/?probe=dd03d00004) | Sep 25, 2023 |
| MSI           | Bravo 15 C7VF               | [ab0a5a435f](https://linux-hardware.org/?probe=ab0a5a435f) | Sep 25, 2023 |
| Dell          | Latitude E5440              | [f4accb1cb0](https://linux-hardware.org/?probe=f4accb1cb0) | Sep 25, 2023 |
| Dell          | Latitude E6330              | [1375d355a5](https://linux-hardware.org/?probe=1375d355a5) | Sep 24, 2023 |
| Dell          | Latitude E5470              | [efb0e356d6](https://linux-hardware.org/?probe=efb0e356d6) | Sep 24, 2023 |
| Lenovo        | IdeaPad N581 7505           | [ed2e5eed86](https://linux-hardware.org/?probe=ed2e5eed86) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| Dell          | Inspiron 3543               | [2075d98d66](https://linux-hardware.org/?probe=2075d98d66) | Sep 24, 2023 |
| Dell          | Inspiron 7577               | [685f51111f](https://linux-hardware.org/?probe=685f51111f) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E431 62778... | [31b0e8e9ce](https://linux-hardware.org/?probe=31b0e8e9ce) | Sep 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [234fc6a6fb](https://linux-hardware.org/?probe=234fc6a6fb) | Sep 24, 2023 |
| Dell          | Latitude 5580               | [6353ffcdf5](https://linux-hardware.org/?probe=6353ffcdf5) | Sep 23, 2023 |
| MSI           | Katana GF76 11UE            | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| Fujitsu       | LIFEBOOK A357               | [d18e2d8811](https://linux-hardware.org/?probe=d18e2d8811) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [04141bd71c](https://linux-hardware.org/?probe=04141bd71c) | Sep 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [900334906e](https://linux-hardware.org/?probe=900334906e) | Sep 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [0f097b1b88](https://linux-hardware.org/?probe=0f097b1b88) | Sep 22, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [8c65f7a68a](https://linux-hardware.org/?probe=8c65f7a68a) | Sep 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | [0f189d3c2a](https://linux-hardware.org/?probe=0f189d3c2a) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | [5dae6d6eda](https://linux-hardware.org/?probe=5dae6d6eda) | Sep 21, 2023 |
| Lenovo        | ThinkPad L540 20AU006CRI    | [e8885911a0](https://linux-hardware.org/?probe=e8885911a0) | Sep 21, 2023 |
| Apple         | MacBookPro12,1              | [bb796b1e6e](https://linux-hardware.org/?probe=bb796b1e6e) | Sep 21, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [2310ddb9a7](https://linux-hardware.org/?probe=2310ddb9a7) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | [ae062bd5ca](https://linux-hardware.org/?probe=ae062bd5ca) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1850488dd1](https://linux-hardware.org/?probe=1850488dd1) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c122be4331](https://linux-hardware.org/?probe=c122be4331) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | [49ed4b61ff](https://linux-hardware.org/?probe=49ed4b61ff) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [91c2eeef2f](https://linux-hardware.org/?probe=91c2eeef2f) | Sep 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [052438c7dd](https://linux-hardware.org/?probe=052438c7dd) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a87ec029ab](https://linux-hardware.org/?probe=a87ec029ab) | Sep 19, 2023 |
| Dell          | Vostro 15 3515              | [1929f30e86](https://linux-hardware.org/?probe=1929f30e86) | Sep 18, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| Dell          | Latitude 5501               | [66b2685ca5](https://linux-hardware.org/?probe=66b2685ca5) | Sep 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| Lenovo        | ThinkPad X220 4290LT8       | [56d2386012](https://linux-hardware.org/?probe=56d2386012) | Sep 17, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [959cef0f9e](https://linux-hardware.org/?probe=959cef0f9e) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [506d025e1e](https://linux-hardware.org/?probe=506d025e1e) | Sep 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [282def5c2a](https://linux-hardware.org/?probe=282def5c2a) | Sep 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Acer          | Predator PH315-54           | [bb4b6fe52f](https://linux-hardware.org/?probe=bb4b6fe52f) | Sep 15, 2023 |
| Acer          | Nitro AN515-45              | [51c7125a22](https://linux-hardware.org/?probe=51c7125a22) | Sep 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [fca517e53f](https://linux-hardware.org/?probe=fca517e53f) | Sep 15, 2023 |
| Timi          | A35S                        | [b229627e35](https://linux-hardware.org/?probe=b229627e35) | Sep 14, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Acer          | Predator PH315-54           | [e1a54edbdc](https://linux-hardware.org/?probe=e1a54edbdc) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [b06966adc5](https://linux-hardware.org/?probe=b06966adc5) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [9f459c45cc](https://linux-hardware.org/?probe=9f459c45cc) | Sep 14, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [c4b64b54dd](https://linux-hardware.org/?probe=c4b64b54dd) | Sep 14, 2023 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [040dc9433a](https://linux-hardware.org/?probe=040dc9433a) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | [b8b03de96a](https://linux-hardware.org/?probe=b8b03de96a) | Sep 13, 2023 |
| HP            | Victus by Gaming Laptop ... | [ac50c36768](https://linux-hardware.org/?probe=ac50c36768) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0XL0... | [31e98e457c](https://linux-hardware.org/?probe=31e98e457c) | Sep 13, 2023 |
| Lenovo        | ThinkPad T450s 20BWS03F0... | [772c104a64](https://linux-hardware.org/?probe=772c104a64) | Sep 13, 2023 |
| Acer          | Aspire A515-45              | [1df9430f46](https://linux-hardware.org/?probe=1df9430f46) | Sep 13, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [deb3ba5bf7](https://linux-hardware.org/?probe=deb3ba5bf7) | Sep 13, 2023 |
| ASUSTek       | GL753VD                     | [c122d5178e](https://linux-hardware.org/?probe=c122d5178e) | Sep 12, 2023 |
| Apple         | MacBookPro15,1              | [3d297f7444](https://linux-hardware.org/?probe=3d297f7444) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | [c549b7a562](https://linux-hardware.org/?probe=c549b7a562) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | [26fe63f6ba](https://linux-hardware.org/?probe=26fe63f6ba) | Sep 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [471faa50e0](https://linux-hardware.org/?probe=471faa50e0) | Sep 12, 2023 |
| ASUSTek       | X555LN                      | [d5d9b73baa](https://linux-hardware.org/?probe=d5d9b73baa) | Sep 11, 2023 |
| ASUSTek       | X555LN                      | [3aef7779ec](https://linux-hardware.org/?probe=3aef7779ec) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | [afa0844d9f](https://linux-hardware.org/?probe=afa0844d9f) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| HP            | Elite x2 1012 G1            | [f7546a9d25](https://linux-hardware.org/?probe=f7546a9d25) | Sep 11, 2023 |
| Dell          | Latitude 5420               | [d561f541f6](https://linux-hardware.org/?probe=d561f541f6) | Sep 10, 2023 |
| Dell          | Latitude 5420               | [982a0e5ce2](https://linux-hardware.org/?probe=982a0e5ce2) | Sep 10, 2023 |
| Acer          | Swift SF314-71              | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Dell          | Inspiron 5515               | [a6c468e52d](https://linux-hardware.org/?probe=a6c468e52d) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | [320bbb4e83](https://linux-hardware.org/?probe=320bbb4e83) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | [534003f1ab](https://linux-hardware.org/?probe=534003f1ab) | Sep 10, 2023 |
| ASUSTek       | X550CC                      | [838e1d8f4a](https://linux-hardware.org/?probe=838e1d8f4a) | Sep 10, 2023 |
| HUAWEI        | HKD-WXX                     | [3b97b2d662](https://linux-hardware.org/?probe=3b97b2d662) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [57e235e93d](https://linux-hardware.org/?probe=57e235e93d) | Sep 09, 2023 |
| ASUSTek       | X555LAB                     | [dd0683372d](https://linux-hardware.org/?probe=dd0683372d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [0ede91c6cd](https://linux-hardware.org/?probe=0ede91c6cd) | Sep 08, 2023 |
| HP            | Laptop 15s-fr1xxx           | [a6e3c47b2d](https://linux-hardware.org/?probe=a6e3c47b2d) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [727b5526f9](https://linux-hardware.org/?probe=727b5526f9) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905f93bc0a](https://linux-hardware.org/?probe=905f93bc0a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e87517b925](https://linux-hardware.org/?probe=e87517b925) | Sep 08, 2023 |
| HP            | Pavilion 15                 | [b6de5d8503](https://linux-hardware.org/?probe=b6de5d8503) | Sep 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b6686658dc](https://linux-hardware.org/?probe=b6686658dc) | Sep 07, 2023 |
| HP            | Pavilion 15                 | [6ab4c7f2d8](https://linux-hardware.org/?probe=6ab4c7f2d8) | Sep 07, 2023 |
| HP            | Pavilion 15                 | [c251475f43](https://linux-hardware.org/?probe=c251475f43) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f33c62ab06](https://linux-hardware.org/?probe=f33c62ab06) | Sep 07, 2023 |
| HP            | ProBook 445 G7              | [373ba724e4](https://linux-hardware.org/?probe=373ba724e4) | Sep 06, 2023 |
| HP            | Pavilion dv6                | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| HUAWEI        | BOM-WXX9                    | [8e0ee8ad83](https://linux-hardware.org/?probe=8e0ee8ad83) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Samsung       | 750XDA                      | [efe919fb13](https://linux-hardware.org/?probe=efe919fb13) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Dell          | XPS 15 9500                 | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| Dell          | XPS 13 9310                 | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| HP            | EliteBook Folio 9470m       | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| ASUSTek       | X555LAB                     | [b8aba55b59](https://linux-hardware.org/?probe=b8aba55b59) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| MSI           | Modern 14 B11MOU            | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| Dell          | Latitude 3410               | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6736962dbe](https://linux-hardware.org/?probe=6736962dbe) | Sep 01, 2023 |
| ASUSTek       | X555LAB                     | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [3c434cdeda](https://linux-hardware.org/?probe=3c434cdeda) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| MSI           | MS-7E06                     | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| HP            | Pavilion Notebook           | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| ASUSTek       | X555LAB                     | [ce793ccb8d](https://linux-hardware.org/?probe=ce793ccb8d) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [aa23e296ad](https://linux-hardware.org/?probe=aa23e296ad) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7d74c2bc61](https://linux-hardware.org/?probe=7d74c2bc61) | Aug 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [dcceb74a56](https://linux-hardware.org/?probe=dcceb74a56) | Aug 29, 2023 |
| Acer          | One Z1402                   | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| Dell          | Precision 3520              | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Dell          | Latitude 5580               | [e16786f57e](https://linux-hardware.org/?probe=e16786f57e) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f30251883f](https://linux-hardware.org/?probe=f30251883f) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Chuwi         | GemiBook Pro                | [95b9733408](https://linux-hardware.org/?probe=95b9733408) | Aug 23, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [34532a7998](https://linux-hardware.org/?probe=34532a7998) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [3a3b362bd0](https://linux-hardware.org/?probe=3a3b362bd0) | Aug 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8e478e15da](https://linux-hardware.org/?probe=8e478e15da) | Aug 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cdb0c49b6a](https://linux-hardware.org/?probe=cdb0c49b6a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2e4f8c0f7c](https://linux-hardware.org/?probe=2e4f8c0f7c) | Aug 21, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Acer          | Aspire E5-573G              | [005b310c55](https://linux-hardware.org/?probe=005b310c55) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| Dell          | XPS 15 9500                 | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [1289521063](https://linux-hardware.org/?probe=1289521063) | Aug 18, 2023 |
| ASUSTek       | GL552VX                     | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| Notebook      | NS50MU                      | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| Acer          | Swift SFX14-41G             | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| HUAWEI        | WRT-WX9                     | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| Timi          | A35S                        | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Dell          | Latitude 5300               | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Valve         | Jupiter                     | [acf70a31a9](https://linux-hardware.org/?probe=acf70a31a9) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [bbe00bbe48](https://linux-hardware.org/?probe=bbe00bbe48) | Aug 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [10f2a6448d](https://linux-hardware.org/?probe=10f2a6448d) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Acer          | Aspire 7750G                | [494c725472](https://linux-hardware.org/?probe=494c725472) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| Alienware     | 15                          | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| HP            | EliteBook 840 G1            | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Dell          | Inspiron 5570               | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | [fdfeffb5f3](https://linux-hardware.org/?probe=fdfeffb5f3) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | [71424c4380](https://linux-hardware.org/?probe=71424c4380) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| HP            | Pavilion 17                 | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | [0b797c9368](https://linux-hardware.org/?probe=0b797c9368) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | [90fbc716ed](https://linux-hardware.org/?probe=90fbc716ed) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| ASUSTek       | K73SV                       | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [21eaf09dc9](https://linux-hardware.org/?probe=21eaf09dc9) | Aug 05, 2023 |
| Dell          | Latitude E5440              | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| HP            | OMEN by Laptop              | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| Acer          | Nitro AN515-54              | [c4d1667ffe](https://linux-hardware.org/?probe=c4d1667ffe) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| HP            | EliteBook 840 G2            | [64810e5a10](https://linux-hardware.org/?probe=64810e5a10) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Chuwi         | GemiBook Pro                | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| HP            | Notebook                    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| PC Special... | Lafite Pro III 17           | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [a251ad988c](https://linux-hardware.org/?probe=a251ad988c) | Aug 03, 2023 |
| Acer          | Predator PHN16-71           | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Timi          | A7S                         | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| HUAWEI        | KPR-WX9                     | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| Dell          | Latitude 5590               | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| Apple         | MacBookPro14,1              | [cb322d77a4](https://linux-hardware.org/?probe=cb322d77a4) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| Dell          | G15 5511                    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Dell          | G15 5511                    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| Dell          | Latitude E6400              | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| Acer          | Aspire A315-53              | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Latitude 5421               | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [5e1021c76b](https://linux-hardware.org/?probe=5e1021c76b) | Jul 30, 2023 |
| Razer         | Blade                       | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| HP            | EliteBook 745 G3            | [30e5e63466](https://linux-hardware.org/?probe=30e5e63466) | Jul 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [6426edf740](https://linux-hardware.org/?probe=6426edf740) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| MSI           | Raider GE78HX 13VI          | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Google        | Atlas                       | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [407859fa58](https://linux-hardware.org/?probe=407859fa58) | Jul 27, 2023 |
| HP            | ProBook 4530s               | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HUAWEI        | KPR-WX9                     | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| Acer          | Aspire A514-54              | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7910b0c067](https://linux-hardware.org/?probe=7910b0c067) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Acer          | Nitro AN515-54              | [f1db825d10](https://linux-hardware.org/?probe=f1db825d10) | Jul 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3bd5c9d59c](https://linux-hardware.org/?probe=3bd5c9d59c) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [0e123e6d85](https://linux-hardware.org/?probe=0e123e6d85) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| Acer          | Aspire V5-551               | [8a13138f82](https://linux-hardware.org/?probe=8a13138f82) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| HP            | ProBook 4530s               | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| Dell          | Latitude 5580               | [f115a04168](https://linux-hardware.org/?probe=f115a04168) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9a2d353d76](https://linux-hardware.org/?probe=9a2d353d76) | Jul 20, 2023 |
| Panasonic     | CFSZ5-3                     | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| ASUSTek       | N501VW                      | [08cd5a81b2](https://linux-hardware.org/?probe=08cd5a81b2) | Jul 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Dell          | Inspiron 7400               | [f145687601](https://linux-hardware.org/?probe=f145687601) | Jul 19, 2023 |
| Avell High... | B.ON                        | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| Apple         | MacBookPro11,2              | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| Lenovo        | B50-45 20388                | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [53c97d91d4](https://linux-hardware.org/?probe=53c97d91d4) | Jul 18, 2023 |
| HP            | EliteBook 830 G5            | [42eb1edbb6](https://linux-hardware.org/?probe=42eb1edbb6) | Jul 17, 2023 |
| Apple         | MacBookPro11,2              | [6bebb2e751](https://linux-hardware.org/?probe=6bebb2e751) | Jul 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b53aa427b9](https://linux-hardware.org/?probe=b53aa427b9) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [5be1306636](https://linux-hardware.org/?probe=5be1306636) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [2b81f8a707](https://linux-hardware.org/?probe=2b81f8a707) | Jul 17, 2023 |
| HP            | Pavilion 17                 | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| Lenovo        | M490s 20215                 | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e204dc6cf1](https://linux-hardware.org/?probe=e204dc6cf1) | Jul 15, 2023 |
| HUAWEI        | HN-WX9X                     | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [793289bc48](https://linux-hardware.org/?probe=793289bc48) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| Acer          | TravelMate P246-MG          | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Dell          | Latitude 7480               | [a375f7685c](https://linux-hardware.org/?probe=a375f7685c) | Jul 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS0P300    | [2c96c19647](https://linux-hardware.org/?probe=2c96c19647) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [23e018569e](https://linux-hardware.org/?probe=23e018569e) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [222924f1c2](https://linux-hardware.org/?probe=222924f1c2) | Jul 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e2792f841d](https://linux-hardware.org/?probe=e2792f841d) | Jul 12, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| Dell          | Precision M4700             | [69a672ec44](https://linux-hardware.org/?probe=69a672ec44) | Jul 11, 2023 |
| Acer          | SF714-52T                   | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [214dd1ad57](https://linux-hardware.org/?probe=214dd1ad57) | Jul 09, 2023 |
| HP            | ProBook 6460b               | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| HP            | OMEN by Laptop              | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [6f3284cac3](https://linux-hardware.org/?probe=6f3284cac3) | Jul 07, 2023 |
| Purism        | Librem 14                   | [18db47d3f6](https://linux-hardware.org/?probe=18db47d3f6) | Jul 07, 2023 |
| HP            | Laptop 14s-dk0xxx           | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| Lenovo        | B50-70 20384                | [8a0a97b362](https://linux-hardware.org/?probe=8a0a97b362) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| HP            | ENVY 15                     | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf134cbdd9](https://linux-hardware.org/?probe=cf134cbdd9) | Jul 06, 2023 |
| Dell          | G3 3590                     | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Dell          | G3 3590                     | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| Dell          | Latitude 7350               | [bc00420bfc](https://linux-hardware.org/?probe=bc00420bfc) | Jul 05, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c387c4fbf1](https://linux-hardware.org/?probe=c387c4fbf1) | Jul 04, 2023 |
| Dell          | Latitude 7350               | [14d41ff667](https://linux-hardware.org/?probe=14d41ff667) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [90b6b19a97](https://linux-hardware.org/?probe=90b6b19a97) | Jul 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [25d3329df1](https://linux-hardware.org/?probe=25d3329df1) | Jul 03, 2023 |
| ASUSTek       | 1015BX                      | [c4bc43a932](https://linux-hardware.org/?probe=c4bc43a932) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| Lenovo        | ThinkPad T520 4243B65       | [07584ce70c](https://linux-hardware.org/?probe=07584ce70c) | Jul 02, 2023 |
| Lenovo        | ThinkPad T410 2537PW4       | [10079a3e26](https://linux-hardware.org/?probe=10079a3e26) | Jul 02, 2023 |
| Lenovo        | ThinkPad T530 2429AA9       | [708fe309bc](https://linux-hardware.org/?probe=708fe309bc) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [d69c578d83](https://linux-hardware.org/?probe=d69c578d83) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [2e20df184f](https://linux-hardware.org/?probe=2e20df184f) | Jul 02, 2023 |
| Dell          | Inspiron 7460               | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| Apple         | MacBookPro11,1              | [998267633e](https://linux-hardware.org/?probe=998267633e) | Jul 01, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [2ba1cce30e](https://linux-hardware.org/?probe=2ba1cce30e) | Jul 01, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Arch Rolling           | 2510      | 58.84%  |
| Arch                   | 1744      | 40.88%  |
| Arch V20.5.7           | 2         | 0.05%   |
| Arch V19.04.4          | 2         | 0.05%   |
| Arch V6.9.2            | 1         | 0.02%   |
| Arch V20.3.4           | 1         | 0.02%   |
| Arch V19.07.9          | 1         | 0.02%   |
| Arch V19.06.1          | 1         | 0.02%   |
| Arch V19.01.4          | 1         | 0.02%   |
| Arch 23.0.0            | 1         | 0.02%   |
| Arch 20230723.0.166908 | 1         | 0.02%   |
| Arch 2.7               | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 4145      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 52        | 1.06%   |
| 6.0.2-arch1-1   | 51        | 1.04%   |
| 6.6.1-arch1-1   | 47        | 0.96%   |
| 6.5.9-arch2-1   | 46        | 0.94%   |
| 6.4.12-arch1-1  | 42        | 0.85%   |
| 6.5.7-arch1-1   | 32        | 0.65%   |
| 5.9.14-arch1-1  | 31        | 0.63%   |
| 5.9.1-arch1-1   | 31        | 0.63%   |
| 6.6.7-arch1-1   | 29        | 0.59%   |
| 6.0.9-arch1-1   | 28        | 0.57%   |
| 5.8.5-arch1-1   | 28        | 0.57%   |
| 5.17.5-arch1-1  | 28        | 0.57%   |
| 6.5.5-arch1-1   | 27        | 0.55%   |
| 6.1.1-arch1-1   | 26        | 0.53%   |
| 5.8.10-arch1-1  | 26        | 0.53%   |
| 6.2.8-arch1-1   | 25        | 0.51%   |
| 5.17.9-arch1-1  | 25        | 0.51%   |
| 6.3.9-arch1-1   | 24        | 0.49%   |
| 6.3.2-arch1-1   | 24        | 0.49%   |
| 6.0.12-arch1-1  | 24        | 0.49%   |
| 5.11.16-arch1-1 | 24        | 0.49%   |
| 6.6.8-arch1-1   | 23        | 0.47%   |
| 6.6.3-arch1-1   | 23        | 0.47%   |
| 6.2.10-arch1-1  | 23        | 0.47%   |
| 5.8.14-arch1-1  | 23        | 0.47%   |
| 5.8.1-arch1-1   | 23        | 0.47%   |
| 5.7.12-arch1-1  | 23        | 0.47%   |
| 6.6.2-arch1-1   | 22        | 0.45%   |
| 6.5.4-arch2-1   | 22        | 0.45%   |
| 5.18.1-arch1-1  | 22        | 0.45%   |
| 5.13.13-arch1-1 | 22        | 0.45%   |
| 5.13.12-arch1-1 | 22        | 0.45%   |
| 6.4.10-arch1-1  | 21        | 0.43%   |
| 5.18.16-arch1-1 | 21        | 0.43%   |
| 6.5.3-arch1-1   | 20        | 0.41%   |
| 6.3.5-arch1-1   | 20        | 0.41%   |
| 5.9.10-arch1-1  | 20        | 0.41%   |
| 5.8.12-arch1-1  | 20        | 0.41%   |
| 6.6.4-arch1-1   | 19        | 0.39%   |
| 6.0.7-arch1-1   | 19        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 1.32%   |
| 6.6.1   | 64        | 1.3%    |
| 6.0.2   | 60        | 1.22%   |
| 6.5.9   | 59        | 1.2%    |
| 6.4.12  | 49        | 1%      |
| 6.5.5   | 42        | 0.85%   |
| 6.5.7   | 40        | 0.81%   |
| 5.9.1   | 40        | 0.81%   |
| 5.9.14  | 38        | 0.77%   |
| 5.8.5   | 38        | 0.77%   |
| 5.17.5  | 38        | 0.77%   |
| 6.3.1   | 36        | 0.73%   |
| 6.6.7   | 34        | 0.69%   |
| 6.0.9   | 34        | 0.69%   |
| 6.3.2   | 32        | 0.65%   |
| 6.6.8   | 31        | 0.63%   |
| 6.6.2   | 31        | 0.63%   |
| 6.1.9   | 31        | 0.63%   |
| 6.1.1   | 31        | 0.63%   |
| 5.13.13 | 31        | 0.63%   |
| 6.3.5   | 30        | 0.61%   |
| 6.2.8   | 30        | 0.61%   |
| 5.8.14  | 30        | 0.61%   |
| 5.17.9  | 30        | 0.61%   |
| 6.0.12  | 29        | 0.59%   |
| 5.8.10  | 29        | 0.59%   |
| 6.3.9   | 28        | 0.57%   |
| 6.2.10  | 28        | 0.57%   |
| 5.18.16 | 27        | 0.55%   |
| 6.6.3   | 26        | 0.53%   |
| 6.5.4   | 26        | 0.53%   |
| 6.4.3   | 26        | 0.53%   |
| 6.4.10  | 26        | 0.53%   |
| 6.2.2   | 26        | 0.53%   |
| 5.8.12  | 26        | 0.53%   |
| 5.8.1   | 26        | 0.53%   |
| 5.18.1  | 26        | 0.53%   |
| 5.16.2  | 26        | 0.53%   |
| 5.13.12 | 26        | 0.53%   |
| 5.11.16 | 26        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 293       | 6.19%   |
| 5.15    | 266       | 5.62%   |
| 6.0     | 246       | 5.2%    |
| 6.5     | 238       | 5.03%   |
| 6.4     | 236       | 4.99%   |
| 5.8     | 232       | 4.9%    |
| 6.2     | 225       | 4.75%   |
| 6.6     | 223       | 4.71%   |
| 5.18    | 220       | 4.65%   |
| 6.3     | 214       | 4.52%   |
| 5.9     | 208       | 4.39%   |
| 5.17    | 198       | 4.18%   |
| 5.4     | 193       | 4.08%   |
| 5.16    | 188       | 3.97%   |
| 5.10    | 182       | 3.84%   |
| 5.19    | 177       | 3.74%   |
| 5.11    | 168       | 3.55%   |
| 5.12    | 153       | 3.23%   |
| 5.13    | 142       | 3%      |
| 5.7     | 138       | 2.92%   |
| 5.6     | 135       | 2.85%   |
| 5.14    | 129       | 2.72%   |
| 5.5     | 93        | 1.96%   |
| 5.3     | 64        | 1.35%   |
| 5.2     | 33        | 0.7%    |
| 4.19    | 26        | 0.55%   |
| 5.0     | 19        | 0.4%    |
| 5.1     | 16        | 0.34%   |
| 4.18    | 16        | 0.34%   |
| 4.17    | 12        | 0.25%   |
| 4.20    | 9         | 0.19%   |
| 4.14    | 9         | 0.19%   |
| 4.15    | 5         | 0.11%   |
| 4.9     | 4         | 0.08%   |
| 4.7     | 4         | 0.08%   |
| 4.16    | 4         | 0.08%   |
| 4.6     | 3         | 0.06%   |
| 4.4     | 3         | 0.06%   |
| 6.7     | 2         | 0.04%   |
| 4.8     | 2         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4141      | 99.9%   |
| i686   | 4         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1434      | 33.22%  |
| KDE5            | 1160      | 26.87%  |
| Unknown         | 489       | 11.33%  |
| XFCE            | 326       | 7.55%   |
| i3              | 230       | 5.33%   |
| KDE             | 147       | 3.41%   |
| sway            | 66        | 1.53%   |
| Hyprland        | 55        | 1.27%   |
| X-Cinnamon      | 52        | 1.2%    |
| MATE            | 49        | 1.14%   |
| Budgie          | 44        | 1.02%   |
| Cinnamon        | 43        | 1%      |
| LXQt            | 37        | 0.86%   |
| bspwm           | 26        | 0.6%    |
| awesome         | 26        | 0.6%    |
| Deepin          | 25        | 0.58%   |
| LXDE            | 18        | 0.42%   |
| DWM             | 11        | 0.25%   |
| xmonad          | 10        | 0.23%   |
| Unity           | 9         | 0.21%   |
| qtile           | 9         | 0.21%   |
| GNOME Flashback | 9         | 0.21%   |
| openbox         | 6         | 0.14%   |
| GNOME Classic   | 6         | 0.14%   |
| i3-with-shmlog  | 5         | 0.12%   |
| Enlightenment   | 5         | 0.12%   |
| LeftWM          | 2         | 0.05%   |
| KDE6            | 2         | 0.05%   |
| X-Generic       | 1         | 0.02%   |
| wayland         | 1         | 0.02%   |
| swayland        | 1         | 0.02%   |
| river           | 1         | 0.02%   |
| Pantheon        | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| instantwm       | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| herbstluftwm    | 1         | 0.02%   |
| GNOME-Classic   | 1         | 0.02%   |
| dusk            | 1         | 0.02%   |
| default         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2360      | 54.92%  |
| Wayland | 1300      | 30.25%  |
| Tty     | 345       | 8.03%   |
| Unknown | 292       | 6.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1752      | 40.97%  |
| SDDM    | 1044      | 24.42%  |
| GDM     | 632       | 14.78%  |
| LightDM | 514       | 12.02%  |
| TDM     | 188       | 4.4%    |
| Ly      | 42        | 0.98%   |
| XDM     | 29        | 0.68%   |
| LXDM    | 27        | 0.63%   |
| SLiM    | 17        | 0.4%    |
| GREETD  | 11        | 0.26%   |
| LY-DM   | 9         | 0.21%   |
| EMPTTY  | 7         | 0.16%   |
| NODM    | 3         | 0.07%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2080      | 49.17%  |
| Unknown | 375       | 8.87%   |
| en_GB   | 241       | 5.7%    |
| C       | 234       | 5.53%   |
| it_IT   | 159       | 3.76%   |
| de_DE   | 137       | 3.24%   |
| ru_RU   | 125       | 2.96%   |
| pt_BR   | 119       | 2.81%   |
| fr_FR   | 107       | 2.53%   |
| zh_CN   | 61        | 1.44%   |
| en_IN   | 50        | 1.18%   |
| pl_PL   | 48        | 1.13%   |
| es_ES   | 45        | 1.06%   |
| en_CA   | 45        | 1.06%   |
| en_AU   | 31        | 0.73%   |
| es_MX   | 26        | 0.61%   |
| tr_TR   | 16        | 0.38%   |
| es_AR   | 16        | 0.38%   |
| en_IE   | 15        | 0.35%   |
| pt_PT   | 13        | 0.31%   |
| en_DK   | 13        | 0.31%   |
| de_AT   | 13        | 0.31%   |
| es_CL   | 12        | 0.28%   |
| ja_JP   | 10        | 0.24%   |
| hu_HU   | 10        | 0.24%   |
| es_CO   | 9         | 0.21%   |
| nl_NL   | 8         | 0.19%   |
| en_ZA   | 8         | 0.19%   |
| en_SG   | 8         | 0.19%   |
| en_NZ   | 8         | 0.19%   |
| en_AG   | 8         | 0.19%   |
| zh_TW   | 7         | 0.17%   |
| ru_UA   | 7         | 0.17%   |
| es_PE   | 7         | 0.17%   |
| cs_CZ   | 7         | 0.17%   |
| fr_CA   | 6         | 0.14%   |
| en-US   | 6         | 0.14%   |
| ca_ES   | 6         | 0.14%   |
| lv_LV   | 5         | 0.12%   |
| en_DE   | 5         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2638      | 62.39%  |
| BIOS | 1590      | 37.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 2959      | 70.49%  |
| Btrfs               | 901       | 21.46%  |
| Unknown             | 116       | 2.76%   |
| Xfs                 | 95        | 2.26%   |
| F2fs                | 49        | 1.17%   |
| Overlay             | 28        | 0.67%   |
| Zfs                 | 25        | 0.6%    |
| Tmpfs               | 12        | 0.29%   |
| XXXXX               | 3         | 0.07%   |
| Ext2                | 3         | 0.07%   |
| XXX4                | 2         | 0.05%   |
| Jfs                 | 1         | 0.02%   |
| Fuse.fuse-overlayfs | 1         | 0.02%   |
| Ext3                | 1         | 0.02%   |
| Bcachefs            | 1         | 0.02%   |
| Aufs                | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2660      | 63.33%  |
| Unknown | 1215      | 28.93%  |
| MBR     | 325       | 7.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3778      | 90.19%  |
| Yes       | 411       | 9.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3108      | 73.93%  |
| Yes       | 1096      | 26.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1191      | 28.73%  |
| Dell                   | 657       | 15.85%  |
| Hewlett-Packard        | 570       | 13.75%  |
| ASUSTek Computer       | 519       | 12.52%  |
| Acer                   | 323       | 7.79%   |
| MSI                    | 118       | 2.85%   |
| Apple                  | 83        | 2%      |
| HUAWEI                 | 80        | 1.93%   |
| Samsung Electronics    | 57        | 1.38%   |
| Toshiba                | 48        | 1.16%   |
| Notebook               | 36        | 0.87%   |
| Timi                   | 34        | 0.82%   |
| Google                 | 32        | 0.77%   |
| Sony                   | 26        | 0.63%   |
| Framework              | 25        | 0.6%    |
| TUXEDO                 | 24        | 0.58%   |
| Alienware              | 22        | 0.53%   |
| Razer                  | 19        | 0.46%   |
| Fujitsu                | 18        | 0.43%   |
| Unknown                | 13        | 0.31%   |
| System76               | 12        | 0.29%   |
| LG Electronics         | 12        | 0.29%   |
| Gigabyte Technology    | 11        | 0.27%   |
| Avell High Performance | 11        | 0.27%   |
| Schenker               | 10        | 0.24%   |
| Chuwi                  | 10        | 0.24%   |
| HONOR                  | 9         | 0.22%   |
| Packard Bell           | 8         | 0.19%   |
| MECHREVO               | 8         | 0.19%   |
| Medion                 | 7         | 0.17%   |
| Intel                  | 7         | 0.17%   |
| GPD                    | 7         | 0.17%   |
| Positivo               | 6         | 0.14%   |
| Monster                | 6         | 0.14%   |
| Valve                  | 5         | 0.12%   |
| Intel Client Systems   | 5         | 0.12%   |
| Teclast                | 4         | 0.1%    |
| Star Labs              | 4         | 0.1%    |
| SLIMBOOK               | 4         | 0.1%    |
| PC Specialist          | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 35        | 0.84%   |
| HP Notebook                          | 19        | 0.46%   |
| Dell XPS 15 9500                     | 19        | 0.46%   |
| Dell XPS 15 9570                     | 18        | 0.43%   |
| Framework Laptop                     | 17        | 0.41%   |
| Dell XPS 13 9360                     | 14        | 0.34%   |
| Dell XPS 13 9310                     | 12        | 0.29%   |
| ASUS ROG Strix G513QY_G513QY         | 12        | 0.29%   |
| HUAWEI NBLK-WAX9X                    | 11        | 0.27%   |
| Dell XPS 13 9380                     | 11        | 0.27%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 10        | 0.24%   |
| Dell XPS 15 7590                     | 10        | 0.24%   |
| Dell Latitude E6430                  | 10        | 0.24%   |
| Dell Inspiron 15 7000 Gaming         | 10        | 0.24%   |
| HP Pavilion Notebook                 | 9         | 0.22%   |
| HP Pavilion g6                       | 9         | 0.22%   |
| HP Pavilion dv6                      | 9         | 0.22%   |
| HP EliteBook 840 G6                  | 9         | 0.22%   |
| Dell XPS 13 9370                     | 9         | 0.22%   |
| Dell XPS 13 9350                     | 9         | 0.22%   |
| Dell Inspiron 5570                   | 9         | 0.22%   |
| Lenovo Legion 5 15ARH05 82B5         | 8         | 0.19%   |
| Lenovo Legion 5 15ACH6H 82JU         | 8         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 8         | 0.19%   |
| HUAWEI BOHK-WAX9X                    | 8         | 0.19%   |
| HP EliteBook 840 G5                  | 8         | 0.19%   |
| Dell XPS 15 9560                     | 8         | 0.19%   |
| Dell Latitude E7450                  | 8         | 0.19%   |
| Dell Latitude 5480                   | 8         | 0.19%   |
| Dell G3 3500                         | 8         | 0.19%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 8         | 0.19%   |
| Acer Nitro AN515-54                  | 8         | 0.19%   |
| Acer Nitro AN515-45                  | 8         | 0.19%   |
| Acer Aspire E5-571                   | 8         | 0.19%   |
| Razer Blade                          | 7         | 0.17%   |
| Lenovo Legion Y530-15ICH 81FV        | 7         | 0.17%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 7         | 0.17%   |
| HP Pavilion Gaming Laptop 15-dk0xxx  | 7         | 0.17%   |
| HP Laptop 15s-eq2xxx                 | 7         | 0.17%   |
| HP Laptop 15-da0xxx                  | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 696       | 16.79%  |
| Lenovo IdeaPad     | 236       | 5.69%   |
| Dell Latitude      | 183       | 4.41%   |
| Acer Aspire        | 183       | 4.41%   |
| Dell Inspiron      | 171       | 4.13%   |
| Dell XPS           | 161       | 3.88%   |
| HP Pavilion        | 120       | 2.9%    |
| HP EliteBook       | 114       | 2.75%   |
| ASUS VivoBook      | 93        | 2.24%   |
| Lenovo Legion      | 87        | 2.1%    |
| HP Laptop          | 85        | 2.05%   |
| ASUS ROG           | 83        | 2%      |
| HP ProBook         | 68        | 1.64%   |
| Acer Nitro         | 57        | 1.38%   |
| Dell Precision     | 56        | 1.35%   |
| ASUS ASUS          | 55        | 1.33%   |
| ASUS Zenbook       | 42        | 1.01%   |
| Acer Swift         | 41        | 0.99%   |
| Toshiba Satellite  | 39        | 0.94%   |
| Lenovo ThinkBook   | 38        | 0.92%   |
| Dell Vostro        | 35        | 0.84%   |
| Unknown            | 35        | 0.84%   |
| ASUS TUF           | 33        | 0.8%    |
| HP OMEN            | 32        | 0.77%   |
| Lenovo Yoga        | 26        | 0.63%   |
| HP ENVY            | 26        | 0.63%   |
| Framework Laptop   | 25        | 0.6%    |
| Dell G3            | 20        | 0.48%   |
| Razer Blade        | 19        | 0.46%   |
| HP Notebook        | 19        | 0.46%   |
| HP 250             | 17        | 0.41%   |
| Fujitsu LIFEBOOK   | 17        | 0.41%   |
| MSI Modern         | 16        | 0.39%   |
| HP ZBook           | 16        | 0.39%   |
| Apple MacBookPro11 | 14        | 0.34%   |
| Acer Predator      | 13        | 0.31%   |
| HP 255             | 12        | 0.29%   |
| HUAWEI NBLK-WAX9X  | 11        | 0.27%   |
| HP Victus          | 10        | 0.24%   |
| Dell G15           | 10        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 536       | 12.93%  |
| 2021    | 514       | 12.4%   |
| 2019    | 509       | 12.28%  |
| 2018    | 441       | 10.64%  |
| 2017    | 303       | 7.31%   |
| 2022    | 263       | 6.34%   |
| 2012    | 226       | 5.45%   |
| 2016    | 216       | 5.21%   |
| 2015    | 214       | 5.16%   |
| 2013    | 208       | 5.02%   |
| 2014    | 194       | 4.68%   |
| 2011    | 174       | 4.2%    |
| 2010    | 106       | 2.56%   |
| 2023    | 102       | 2.46%   |
| 2008    | 68        | 1.64%   |
| 2009    | 44        | 1.06%   |
| 2007    | 22        | 0.53%   |
| 2006    | 4         | 0.1%    |
| Unknown | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4145      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4095      | 98.58%  |
| Enabled  | 59        | 1.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4089      | 98.65%  |
| Yes  | 56        | 1.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1102      | 26.29%  |
| 16.01-24.0  | 980       | 23.38%  |
| 8.01-16.0   | 952       | 22.71%  |
| 32.01-64.0  | 438       | 10.45%  |
| 3.01-4.0    | 433       | 10.33%  |
| 24.01-32.0  | 99        | 2.36%   |
| 64.01-256.0 | 89        | 2.12%   |
| 1.01-2.0    | 61        | 1.46%   |
| 2.01-3.0    | 32        | 0.76%   |
| 0.51-1.0    | 6         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1127      | 24.56%  |
| 4.01-8.0   | 1044      | 22.75%  |
| 1.01-2.0   | 1031      | 22.47%  |
| 3.01-4.0   | 807       | 17.59%  |
| 8.01-16.0  | 320       | 6.97%   |
| 0.51-1.0   | 173       | 3.77%   |
| 0.01-0.5   | 36        | 0.78%   |
| 16.01-24.0 | 33        | 0.72%   |
| 24.01-32.0 | 15        | 0.33%   |
| 32.01-64.0 | 3         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2912      | 69.05%  |
| 2      | 1120      | 26.56%  |
| 3      | 152       | 3.6%    |
| 4      | 15        | 0.36%   |
| 0      | 14        | 0.33%   |
| 5      | 3         | 0.07%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3382      | 81.28%  |
| Yes       | 779       | 18.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3151      | 75.62%  |
| No        | 1016      | 24.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4109      | 99.04%  |
| No        | 40        | 0.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3623      | 86.57%  |
| No        | 562       | 13.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 682       | 16.34%  |
| Germany     | 355       | 8.51%   |
| Italy       | 268       | 6.42%   |
| Russia      | 265       | 6.35%   |
| Brazil      | 225       | 5.39%   |
| France      | 197       | 4.72%   |
| India       | 180       | 4.31%   |
| UK          | 142       | 3.4%    |
| Poland      | 121       | 2.9%    |
| Canada      | 105       | 2.52%   |
| Spain       | 93        | 2.23%   |
| China       | 86        | 2.06%   |
| Netherlands | 77        | 1.84%   |
| Turkey      | 64        | 1.53%   |
| Australia   | 59        | 1.41%   |
| Austria     | 52        | 1.25%   |
| Ukraine     | 47        | 1.13%   |
| Sweden      | 47        | 1.13%   |
| Indonesia   | 47        | 1.13%   |
| Mexico      | 45        | 1.08%   |
| Romania     | 38        | 0.91%   |
| Czechia     | 38        | 0.91%   |
| Portugal    | 37        | 0.89%   |
| Belgium     | 37        | 0.89%   |
| Switzerland | 34        | 0.81%   |
| Vietnam     | 33        | 0.79%   |
| Argentina   | 33        | 0.79%   |
| Japan       | 27        | 0.65%   |
| Hungary     | 27        | 0.65%   |
| Denmark     | 27        | 0.65%   |
| Iran        | 26        | 0.62%   |
| Chile       | 26        | 0.62%   |
| Finland     | 25        | 0.6%    |
| Colombia    | 24        | 0.57%   |
| New Zealand | 23        | 0.55%   |
| Belarus     | 23        | 0.55%   |
| Greece      | 21        | 0.5%    |
| Peru        | 20        | 0.48%   |
| Hong Kong   | 20        | 0.48%   |
| Taiwan      | 19        | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 76        | 1.71%   |
| Milan             | 44        | 0.99%   |
| Berlin            | 42        | 0.94%   |
| Sao Paulo         | 39        | 0.88%   |
| Paris             | 39        | 0.88%   |
| St Petersburg     | 38        | 0.85%   |
| Warsaw            | 33        | 0.74%   |
| Vienna            | 27        | 0.61%   |
| Munich            | 27        | 0.61%   |
| Bengaluru         | 24        | 0.54%   |
| Melbourne         | 23        | 0.52%   |
| Los Angeles       | 23        | 0.52%   |
| Istanbul          | 23        | 0.52%   |
| Valencia          | 21        | 0.47%   |
| Sydney            | 19        | 0.43%   |
| Amsterdam         | 19        | 0.43%   |
| Rome              | 18        | 0.4%    |
| Prague            | 18        | 0.4%    |
| Kyiv              | 18        | 0.4%    |
| Frankfurt am Main | 18        | 0.4%    |
| Tehran            | 16        | 0.36%   |
| Montreal          | 16        | 0.36%   |
| Turin             | 15        | 0.34%   |
| Phoenix           | 15        | 0.34%   |
| Mexico City       | 15        | 0.34%   |
| Madrid            | 15        | 0.34%   |
| Jakarta           | 15        | 0.34%   |
| Helsinki          | 15        | 0.34%   |
| Hamburg           | 15        | 0.34%   |
| Budapest          | 15        | 0.34%   |
| Beijing           | 15        | 0.34%   |
| New York          | 14        | 0.31%   |
| Lima              | 14        | 0.31%   |
| Chennai           | 14        | 0.31%   |
| Singapore         | 13        | 0.29%   |
| Krakow            | 13        | 0.29%   |
| Curitiba          | 13        | 0.29%   |
| Cologne           | 13        | 0.29%   |
| Bogotá           | 13        | 0.29%   |
| London            | 12        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1143      | 1522   | 21.07%  |
| WDC                            | 502       | 617    | 9.25%   |
| SanDisk                        | 475       | 573    | 8.76%   |
| Seagate                        | 420       | 510    | 7.74%   |
| Toshiba                        | 346       | 396    | 6.38%   |
| SK hynix                       | 318       | 389    | 5.86%   |
| Kingston                       | 258       | 325    | 4.76%   |
| Unknown                        | 211       | 252    | 3.89%   |
| Micron Technology              | 209       | 255    | 3.85%   |
| Intel                          | 209       | 274    | 3.85%   |
| Crucial                        | 146       | 210    | 2.69%   |
| HGST                           | 131       | 142    | 2.41%   |
| Hitachi                        | 71        | 72     | 1.31%   |
| A-DATA Technology              | 71        | 99     | 1.31%   |
| KIOXIA                         | 62        | 73     | 1.14%   |
| Apple                          | 50        | 63     | 0.92%   |
| Phison Electronics             | 43        | 51     | 0.79%   |
| Micron/Crucial Technology      | 38        | 42     | 0.7%    |
| Kingston Technology Company    | 38        | 38     | 0.7%    |
| LITEON                         | 34        | 35     | 0.63%   |
| Silicon Motion                 | 33        | 36     | 0.61%   |
| Phison                         | 32        | 37     | 0.59%   |
| China                          | 30        | 38     | 0.55%   |
| Transcend                      | 27        | 29     | 0.5%    |
| SPCC                           | 22        | 24     | 0.41%   |
| PNY                            | 17        | 21     | 0.31%   |
| Lenovo                         | 17        | 23     | 0.31%   |
| JMicron Technology             | 16        | 19     | 0.29%   |
| ADATA Technology               | 16        | 18     | 0.29%   |
| MAXIO Technology (Hangzhou)    | 14        | 16     | 0.26%   |
| Yangtze Memory Technologies    | 13        | 13     | 0.24%   |
| LITEONIT                       | 12        | 12     | 0.22%   |
| KingSpec                       | 12        | 14     | 0.22%   |
| GOODRAM                        | 12        | 13     | 0.22%   |
| Union Memory (Shenzhen)        | 11        | 12     | 0.2%    |
| Solid State Storage            | 11        | 14     | 0.2%    |
| Intenso                        | 11        | 13     | 0.2%    |
| ASMT                           | 11        | 13     | 0.2%    |
| Union Memory                   | 10        | 10     | 0.18%   |
| Solid State Storage Technology | 10        | 10     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 155       | 2.73%   |
| Seagate ST1000LM035-1RK172 1TB                      | 95        | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 85        | 1.5%    |
| Samsung NVMe SSD Drive 512GB                        | 63        | 1.11%   |
| HGST HTS721010A9E630 1TB                            | 52        | 0.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 48        | 0.85%   |
| Toshiba MQ04ABF100 1TB                              | 46        | 0.81%   |
| SanDisk NVMe SSD Drive 512GB                        | 46        | 0.81%   |
| Kingston SA400S37240G 240GB SSD                     | 45        | 0.79%   |
| Toshiba MQ01ABD100 1TB                              | 43        | 0.76%   |
| SK hynix NVMe SSD Drive 512GB                       | 39        | 0.69%   |
| Unknown MMC Card  32GB                              | 36        | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 36        | 0.63%   |
| Samsung SSD 860 EVO 500GB                           | 36        | 0.63%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 35        | 0.62%   |
| Unknown MMC Card  64GB                              | 34        | 0.6%    |
| Intel SSDPEKNU512GZ 512GB                           | 34        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 33        | 0.58%   |
| Samsung SSD 850 EVO 500GB                           | 32        | 0.56%   |
| Unknown MMC Card  128GB                             | 26        | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB                      | 26        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 26        | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 25        | 0.44%   |
| Intel SSD 660P Series 1TB                           | 25        | 0.44%   |
| SanDisk NVMe SSD Drive 256GB                        | 24        | 0.42%   |
| Kingston SA400S37480G 480GB SSD                     | 24        | 0.42%   |
| Toshiba MQ01ABF050 500GB                            | 23        | 0.41%   |
| Seagate ST2000LM007-1R8174 2TB                      | 23        | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 23        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                         | 23        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB                     | 22        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 22        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                        | 22        | 0.39%   |
| Seagate ST1000LX015-1U7172 1TB                      | 21        | 0.37%   |
| Samsung SSD 980 1TB                                 | 21        | 0.37%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.37%   |
| HGST HTS541010A9E680 1TB                            | 21        | 0.37%   |
| Toshiba NVMe SSD Drive 512GB                        | 20        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                      | 20        | 0.35%   |
| Samsung SSD 850 EVO 250GB                           | 20        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 412       | 500    | 35.15%  |
| WDC                 | 294       | 338    | 25.09%  |
| Toshiba             | 190       | 212    | 16.21%  |
| HGST                | 131       | 142    | 11.18%  |
| Hitachi             | 71        | 72     | 6.06%   |
| Samsung Electronics | 13        | 13     | 1.11%   |
| Unknown             | 10        | 13     | 0.85%   |
| ASMT                | 6         | 7      | 0.51%   |
| TO Exter            | 5         | 10     | 0.43%   |
| SABRENT             | 5         | 5      | 0.43%   |
| Fujitsu             | 5         | 6      | 0.43%   |
| External            | 5         | 6      | 0.43%   |
| HGST HTS            | 3         | 3      | 0.26%   |
| Generic-            | 3         | 4      | 0.26%   |
| Apple               | 3         | 3      | 0.26%   |
| USB3.0              | 2         | 2      | 0.17%   |
| USB                 | 2         | 2      | 0.17%   |
| SSK                 | 2         | 2      | 0.17%   |
| SAGE                | 2         | 3      | 0.17%   |
| NeoTech             | 2         | 2      | 0.17%   |
| ACASIS              | 2         | 2      | 0.17%   |
| StoreJet            | 1         | 1      | 0.09%   |
| Pioneer             | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 378       | 468    | 24.79%  |
| Kingston            | 173       | 211    | 11.34%  |
| SanDisk             | 167       | 192    | 10.95%  |
| Crucial             | 132       | 186    | 8.66%   |
| WDC                 | 94        | 124    | 6.16%   |
| A-DATA Technology   | 44        | 64     | 2.89%   |
| Intel               | 40        | 44     | 2.62%   |
| Toshiba             | 39        | 47     | 2.56%   |
| SK hynix            | 39        | 48     | 2.56%   |
| Micron Technology   | 36        | 43     | 2.36%   |
| LITEON              | 31        | 32     | 2.03%   |
| Apple               | 31        | 32     | 2.03%   |
| China               | 30        | 38     | 1.97%   |
| Transcend           | 26        | 28     | 1.7%    |
| SPCC                | 18        | 19     | 1.18%   |
| PNY                 | 16        | 20     | 1.05%   |
| LITEONIT            | 12        | 12     | 0.79%   |
| KingSpec            | 12        | 14     | 0.79%   |
| JMicron Technology  | 11        | 15     | 0.72%   |
| Intenso             | 11        | 13     | 0.72%   |
| GOODRAM             | 11        | 12     | 0.72%   |
| OCZ                 | 10        | 10     | 0.66%   |
| Patriot             | 9         | 10     | 0.59%   |
| Plextor             | 8         | 8      | 0.52%   |
| Lexar               | 6         | 12     | 0.39%   |
| FORESEE             | 6         | 9      | 0.39%   |
| Apacer              | 6         | 6      | 0.39%   |
| Netac               | 5         | 6      | 0.33%   |
| Mushkin             | 5         | 6      | 0.33%   |
| Gigabyte Technology | 5         | 5      | 0.33%   |
| BHT                 | 5         | 7      | 0.33%   |
| ASMT                | 5         | 5      | 0.33%   |
| Verbatim            | 4         | 4      | 0.26%   |
| Team                | 4         | 4      | 0.26%   |
| Hewlett-Packard     | 4         | 5      | 0.26%   |
| Unknown             | 4         | 4      | 0.26%   |
| Unknown             | 3         | 3      | 0.2%    |
| Phison              | 3         | 3      | 0.2%    |
| HS-SSD-E100         | 3         | 6      | 0.2%    |
| BIWIN               | 3         | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2278      | 3186   | 44.89%  |
| SSD     | 1411      | 1864   | 27.8%   |
| HDD     | 1135      | 1351   | 22.36%  |
| MMC     | 197       | 232    | 3.88%   |
| Unknown | 54        | 58     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2275      | 3171   | 47.3%   |
| SATA | 2152      | 3054   | 44.74%  |
| MMC  | 197       | 232    | 4.1%    |
| SAS  | 186       | 234    | 3.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1507      | 1981   | 59.61%  |
| 0.51-1.0   | 880       | 1053   | 34.81%  |
| 1.01-2.0   | 128       | 167    | 5.06%   |
| 3.01-4.0   | 6         | 7      | 0.24%   |
| 4.01-10.0  | 6         | 6      | 0.24%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1140      | 26.39%  |
| 101-250        | 1095      | 25.35%  |
| 501-1000       | 819       | 18.96%  |
| 1001-2000      | 501       | 11.6%   |
| More than 3000 | 191       | 4.42%   |
| 51-100         | 188       | 4.35%   |
| 2001-3000      | 145       | 3.36%   |
| Unknown        | 100       | 2.31%   |
| 21-50          | 73        | 1.69%   |
| 1-20           | 68        | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 999       | 22.11%  |
| 101-250        | 871       | 19.27%  |
| 21-50          | 739       | 16.35%  |
| 51-100         | 662       | 14.65%  |
| 251-500        | 566       | 12.52%  |
| 501-1000       | 361       | 7.99%   |
| 1001-2000      | 138       | 3.05%   |
| Unknown        | 100       | 2.21%   |
| More than 3000 | 42        | 0.93%   |
| 2001-3000      | 40        | 0.89%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                        | 12        | 12     | 4.69%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 11        | 12     | 4.3%    |
| HGST HTS545050A7E680 500GB                                      | 6         | 7      | 2.34%   |
| HGST HTS541010A9E680 1TB                                        | 6         | 6      | 2.34%   |
| Seagate ST9500325AS 500GB                                       | 5         | 5      | 1.95%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 5         | 5      | 1.95%   |
| HGST HTS725050A7E630 500GB                                      | 5         | 5      | 1.95%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 1.56%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 4         | 5      | 1.56%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 3         | 3      | 1.17%   |
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 1.17%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 3         | 3      | 1.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 3      | 1.17%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 3         | 3      | 1.17%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 4      | 1.17%   |
| Hitachi HTS545050A7E380 500GB                                   | 3         | 4      | 1.17%   |
| Hitachi HTS545025B9A300 250GB                                   | 3         | 3      | 1.17%   |
| Hitachi HTS541616J9SA00 160GB                                   | 3         | 3      | 1.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2         | 2      | 0.78%   |
| WDC WD10SPZX-75Z10T2 1TB                                        | 2         | 2      | 0.78%   |
| Toshiba MQ01ABD100 1TB                                          | 2         | 2      | 0.78%   |
| Toshiba MK3276GSX 320GB                                         | 2         | 2      | 0.78%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 2         | 2      | 0.78%   |
| Seagate ST95005620AS 500GB                                      | 2         | 4      | 0.78%   |
| Seagate ST9320325AS 320GB                                       | 2         | 2      | 0.78%   |
| Seagate ST9250315AS 250GB                                       | 2         | 2      | 0.78%   |
| Seagate ST500LT012-9WS142 500GB                                 | 2         | 2      | 0.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB                             | 2         | 2      | 0.78%   |
| Seagate ST500LM000-SSHD-8GB                                     | 2         | 2      | 0.78%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 2         | 2      | 0.78%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 2         | 2      | 0.78%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 2         | 2      | 0.78%   |
| Seagate ST1000LM014-1EJ164 1TB                                  | 2         | 2      | 0.78%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                               | 2         | 2      | 0.78%   |
| Samsung Electronics SSD 970 EVO 2TB                             | 2         | 2      | 0.78%   |
| LITEON CV8-8E128-HP 128GB SSD                                   | 2         | 2      | 0.78%   |
| Intel SSDSC2BF240A4L 240GB                                      | 2         | 2      | 0.78%   |
| Hitachi HTS723232A7A364 320GB                                   | 2         | 2      | 0.78%   |
| Hitachi HTS541680J9SA00 80GB                                    | 2         | 2      | 0.78%   |
| HGST HTS545050A7E380 500GB                                      | 2         | 2      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 69        | 75     | 26.95%  |
| HGST                  | 34        | 35     | 13.28%  |
| WDC                   | 33        | 36     | 12.89%  |
| Toshiba               | 23        | 26     | 8.98%   |
| Hitachi               | 23        | 24     | 8.98%   |
| Samsung Electronics   | 13        | 18     | 5.08%   |
| SK hynix              | 12        | 13     | 4.69%   |
| Intel                 | 8         | 9      | 3.13%   |
| SanDisk               | 7         | 8      | 2.73%   |
| Kingston              | 6         | 6      | 2.34%   |
| Micron Technology     | 5         | 6      | 1.95%   |
| Crucial               | 5         | 5      | 1.95%   |
| LITEON                | 3         | 3      | 1.17%   |
| China                 | 3         | 3      | 1.17%   |
| A-DATA Technology     | 3         | 3      | 1.17%   |
| ASMT                  | 2         | 2      | 0.78%   |
| VNYEZ                 | 1         | 1      | 0.39%   |
| SSSTC                 | 1         | 1      | 0.39%   |
| Realtek Semiconductor | 1         | 1      | 0.39%   |
| OCZ                   | 1         | 1      | 0.39%   |
| KingSpec              | 1         | 1      | 0.39%   |
| Fujitsu               | 1         | 1      | 0.39%   |
| Apple                 | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 69        | 75     | 38.98%  |
| HGST    | 34        | 35     | 19.21%  |
| WDC     | 30        | 33     | 16.95%  |
| Hitachi | 23        | 24     | 12.99%  |
| Toshiba | 18        | 21     | 10.17%  |
| Fujitsu | 1         | 1      | 0.56%   |
| ASMT    | 1         | 1      | 0.56%   |
| Apple   | 1         | 1      | 0.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 176       | 191    | 69.02%  |
| SSD  | 61        | 66     | 23.92%  |
| NVMe | 18        | 22     | 7.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 16.67%  |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB    | 1         | 1      | 16.67%  |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 16.67%  |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 16.67%  |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 2         | 3      | 33.33%  |
| WDC                     | 1         | 1      | 16.67%  |
| Union Memory (Shenzhen) | 1         | 1      | 16.67%  |
| Phison                  | 1         | 1      | 16.67%  |
| Kingston                | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2136      | 3247   | 47.45%  |
| Detected | 2109      | 3158   | 46.85%  |
| Malfunc  | 251       | 279    | 5.58%   |
| Failed   | 6         | 7      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2449      | 46.34%  |
| Samsung Electronics                     | 798       | 15.1%   |
| AMD                                     | 493       | 9.33%   |
| SanDisk                                 | 404       | 7.64%   |
| SK hynix                                | 276       | 5.22%   |
| Micron Technology                       | 174       | 3.29%   |
| Kingston Technology Company             | 122       | 2.31%   |
| Toshiba America Info Systems            | 117       | 2.21%   |
| Phison Electronics                      | 81        | 1.53%   |
| KIOXIA                                  | 63        | 1.19%   |
| Micron/Crucial Technology               | 53        | 1%      |
| Silicon Motion                          | 40        | 0.76%   |
| ADATA Technology                        | 39        | 0.74%   |
| Solid State Storage Technology          | 24        | 0.45%   |
| Union Memory (Shenzhen)                 | 23        | 0.44%   |
| Apple                                   | 16        | 0.3%    |
| Yangtze Memory Technologies             | 15        | 0.28%   |
| Lenovo                                  | 15        | 0.28%   |
| MAXIO Technology (Hangzhou)             | 14        | 0.26%   |
| Realtek Semiconductor                   | 13        | 0.25%   |
| Lite-On Technology                      | 12        | 0.23%   |
| Shenzhen Longsys Electronics            | 8         | 0.15%   |
| Nvidia                                  | 8         | 0.15%   |
| Biwin Storage Technology                | 5         | 0.09%   |
| Marvell Technology Group                | 4         | 0.08%   |
| INNOGRIT                                | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.06%   |
| Netac Technology                        | 3         | 0.06%   |
| Solidigm                                | 2         | 0.04%   |
| Shenzhen Unionmemory Information System | 2         | 0.04%   |
| Transcend                               | 1         | 0.02%   |
| Seagate Technology                      | 1         | 0.02%   |
| O2 Micro                                | 1         | 0.02%   |
| ASMedia Technology                      | 1         | 0.02%   |
| Unknown                                 | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 468       | 8.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 413       | 7.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 338       | 6.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 227       | 4.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 225       | 4.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 181       | 3.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 181       | 3.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 144       | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 141       | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 138       | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 131       | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 129       | 2.34%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 114       | 2.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 113       | 2.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 109       | 1.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 103       | 1.87%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 74        | 1.34%   |
| Intel SSD 660P Series                                                          | 73        | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 68        | 1.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 65        | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 60        | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 57        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                            | 55        | 1%      |
| Intel SSD 670p Series [Keystone Harbor]                                        | 50        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 46        | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 41        | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 41        | 0.75%   |
| Phison E12 NVMe Controller                                                     | 41        | 0.75%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 41        | 0.75%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 40        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 39        | 0.71%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 38        | 0.69%   |
| SK hynix BC511 NVMe SSD                                                        | 37        | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                          | 37        | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 36        | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 36        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 35        | 0.64%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 34        | 0.62%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 32        | 0.58%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 30        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2512      | 47.92%  |
| NVMe | 2279      | 43.48%  |
| RAID | 393       | 7.5%    |
| IDE  | 58        | 1.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3154      | 76.09%  |
| AMD    | 991       | 23.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 90        | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 87        | 2.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 86        | 2.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 82        | 1.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 80        | 1.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 79        | 1.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 76        | 1.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 70        | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 69        | 1.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 57        | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 57        | 1.37%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 56        | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 53        | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 48        | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 48        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 47        | 1.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 46        | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 46        | 1.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 45        | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 44        | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 39        | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 37        | 0.89%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 36        | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 35        | 0.84%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 34        | 0.82%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 34        | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 33        | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 32        | 0.77%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 32        | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 30        | 0.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 30        | 0.72%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 29        | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 29        | 0.7%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 28        | 0.68%   |
| Intel 12th Gen Core i7-12700H                 | 28        | 0.68%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 27        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.65%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 27        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1083      | 26.11%  |
| Intel Core i5           | 992       | 23.92%  |
| Other                   | 476       | 11.48%  |
| AMD Ryzen 7             | 320       | 7.71%   |
| AMD Ryzen 5             | 306       | 7.38%   |
| Intel Core i3           | 220       | 5.3%    |
| Intel Celeron           | 119       | 2.87%   |
| Intel Core 2 Duo        | 90        | 2.17%   |
| AMD Ryzen 7 PRO         | 87        | 2.1%    |
| AMD Ryzen 9             | 79        | 1.9%    |
| Intel Pentium           | 56        | 1.35%   |
| AMD Ryzen 3             | 40        | 0.96%   |
| Intel Atom              | 39        | 0.94%   |
| Intel Core i9           | 31        | 0.75%   |
| AMD Ryzen 5 PRO         | 27        | 0.65%   |
| AMD A6                  | 18        | 0.43%   |
| AMD A10                 | 17        | 0.41%   |
| Intel Pentium Silver    | 15        | 0.36%   |
| AMD A4                  | 15        | 0.36%   |
| AMD A8                  | 13        | 0.31%   |
| Intel Xeon              | 12        | 0.29%   |
| AMD E2                  | 12        | 0.29%   |
| AMD E1                  | 8         | 0.19%   |
| Intel Pentium Dual-Core | 7         | 0.17%   |
| Intel Genuine           | 6         | 0.14%   |
| Intel Core m3           | 6         | 0.14%   |
| AMD E                   | 6         | 0.14%   |
| AMD Athlon              | 5         | 0.12%   |
| Intel Core 2            | 4         | 0.1%    |
| AMD A12                 | 4         | 0.1%    |
| Intel Core m5           | 3         | 0.07%   |
| Intel Celeron Dual-Core | 3         | 0.07%   |
| Intel Pentium Gold      | 2         | 0.05%   |
| Intel Pentium Dual      | 2         | 0.05%   |
| Intel Core m7           | 2         | 0.05%   |
| Intel Core M            | 2         | 0.05%   |
| AMD Turion Neo X2       | 2         | 0.05%   |
| AMD Phenom II           | 2         | 0.05%   |
| AMD C-60                | 2         | 0.05%   |
| AMD Athlon X2           | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1516      | 36.55%  |
| 2      | 1448      | 34.91%  |
| 8      | 535       | 12.9%   |
| 6      | 477       | 11.5%   |
| 14     | 52        | 1.25%   |
| 12     | 48        | 1.16%   |
| 10     | 32        | 0.77%   |
| 1      | 23        | 0.55%   |
| 16     | 10        | 0.24%   |
| 24     | 5         | 0.12%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4145      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3583      | 86.36%  |
| 1      | 566       | 13.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4084      | 98.48%  |
| Unknown        | 60        | 1.45%   |
| 32-bit         | 3         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1796      | 41.65%  |
| 0x906ea    | 140       | 3.25%   |
| 0x806ea    | 140       | 3.25%   |
| 0x306a9    | 122       | 2.83%   |
| 0x0a50000c | 119       | 2.76%   |
| 0x806ec    | 117       | 2.71%   |
| 0x806c1    | 113       | 2.62%   |
| 0x206a7    | 105       | 2.44%   |
| 0x406e3    | 101       | 2.34%   |
| 0x306d4    | 90        | 2.09%   |
| 0x40651    | 86        | 1.99%   |
| 0x906e9    | 84        | 1.95%   |
| 0x806e9    | 82        | 1.9%    |
| 0x08600106 | 82        | 1.9%    |
| 0x08108102 | 77        | 1.79%   |
| 0x306c3    | 67        | 1.55%   |
| 0xa0652    | 64        | 1.48%   |
| 0x08108109 | 58        | 1.35%   |
| 0x08608103 | 48        | 1.11%   |
| 0x20655    | 46        | 1.07%   |
| 0x0a404102 | 46        | 1.07%   |
| 0x08600104 | 45        | 1.04%   |
| 0x506e3    | 44        | 1.02%   |
| 0x806eb    | 40        | 0.93%   |
| 0x08600103 | 40        | 0.93%   |
| 0x1067a    | 34        | 0.79%   |
| 0x906a3    | 26        | 0.6%    |
| 0x0a50000d | 26        | 0.6%    |
| 0x0810100b | 25        | 0.58%   |
| 0x706e5    | 24        | 0.56%   |
| 0x08608102 | 23        | 0.53%   |
| 0x806d1    | 21        | 0.49%   |
| 0x406c4    | 21        | 0.49%   |
| 0x30678    | 20        | 0.46%   |
| 0x10676    | 19        | 0.44%   |
| 0x906ed    | 18        | 0.42%   |
| 0x706a1    | 16        | 0.37%   |
| 0x506c9    | 16        | 0.37%   |
| 0x20652    | 15        | 0.35%   |
| 0x06006705 | 15        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1040      | 25.06%  |
| Unknown          | 295       | 7.11%   |
| Haswell          | 268       | 6.46%   |
| Skylake          | 253       | 6.1%    |
| TigerLake        | 251       | 6.05%   |
| IvyBridge        | 227       | 5.47%   |
| Zen 2            | 220       | 5.3%    |
| Zen 3            | 204       | 4.92%   |
| SandyBridge      | 178       | 4.29%   |
| Zen+             | 173       | 4.17%   |
| Broadwell        | 153       | 3.69%   |
| CometLake        | 137       | 3.3%    |
| Alderlake Hybrid | 112       | 2.7%    |
| Penryn           | 87        | 2.1%    |
| Icelake          | 87        | 2.1%    |
| Westmere         | 84        | 2.02%   |
| Silvermont       | 83        | 2%      |
| Zen              | 50        | 1.2%    |
| Goldmont plus    | 46        | 1.11%   |
| Excavator        | 42        | 1.01%   |
| Core             | 27        | 0.65%   |
| Goldmont         | 23        | 0.55%   |
| Bobcat           | 17        | 0.41%   |
| Puma             | 16        | 0.39%   |
| Bonnell          | 15        | 0.36%   |
| Jaguar           | 10        | 0.24%   |
| Nehalem          | 9         | 0.22%   |
| Piledriver       | 8         | 0.19%   |
| K10 Llano        | 8         | 0.19%   |
| Tremont          | 7         | 0.17%   |
| K10              | 7         | 0.17%   |
| Steamroller      | 4         | 0.1%    |
| K8 Hammer        | 4         | 0.1%    |
| P6               | 2         | 0.05%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2966      | 52.75%  |
| Nvidia                           | 1470      | 26.14%  |
| AMD                              | 1183      | 21.04%  |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 237       | 4.14%   |
| Intel UHD Graphics 620                                                                   | 231       | 4.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 220       | 3.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 215       | 3.75%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 210       | 3.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 177       | 3.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 169       | 2.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 162       | 2.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 161       | 2.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 148       | 2.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 147       | 2.57%   |
| Intel HD Graphics 620                                                                    | 138       | 2.41%   |
| Intel HD Graphics 5500                                                                   | 130       | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 121       | 2.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 119       | 2.08%   |
| Intel HD Graphics 630                                                                    | 110       | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 106       | 1.85%   |
| AMD Lucienne                                                                             | 98        | 1.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 92        | 1.61%   |
| AMD Rembrandt [Radeon 680M]                                                              | 83        | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 80        | 1.4%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 68        | 1.19%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 68        | 1.19%   |
| Intel HD Graphics 530                                                                    | 66        | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 62        | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 58        | 1.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 1.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 54        | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 46        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 45        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 43        | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 40        | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 38        | 0.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 36        | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 36        | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 35        | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 34        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1708      | 41.05%  |
| Intel + Nvidia           | 1089      | 26.17%  |
| 1 x AMD                  | 720       | 17.3%   |
| AMD + Nvidia             | 220       | 5.29%   |
| 1 x Nvidia               | 159       | 3.82%   |
| Intel + AMD              | 155       | 3.73%   |
| 2 x AMD                  | 86        | 2.07%   |
| 2 x Intel                | 11        | 0.26%   |
| Other                    | 3         | 0.07%   |
| 1 x SiS                  | 3         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.07%   |
| 2 x Nvidia               | 2         | 0.05%   |
| Intel + 2 x Nvidia       | 2         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3259      | 77.85%  |
| Proprietary | 910       | 21.74%  |
| Unknown     | 17        | 0.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2900      | 68.08%  |
| 0.01-0.5   | 451       | 10.59%  |
| 1.01-2.0   | 344       | 8.08%   |
| 3.01-4.0   | 218       | 5.12%   |
| 0.51-1.0   | 160       | 3.76%   |
| 7.01-8.0   | 84        | 1.97%   |
| 5.01-6.0   | 77        | 1.81%   |
| 8.01-16.0  | 14        | 0.33%   |
| 2.01-3.0   | 12        | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 937       | 18.69%  |
| BOE                     | 773       | 15.42%  |
| Chimei Innolux          | 696       | 13.88%  |
| LG Display              | 623       | 12.43%  |
| Samsung Electronics     | 418       | 8.34%   |
| Sharp                   | 211       | 4.21%   |
| Dell                    | 161       | 3.21%   |
| Goldstar                | 123       | 2.45%   |
| PANDA                   | 121       | 2.41%   |
| Lenovo                  | 94        | 1.87%   |
| Apple                   | 86        | 1.72%   |
| Hewlett-Packard         | 66        | 1.32%   |
| CSO                     | 61        | 1.22%   |
| AOC                     | 57        | 1.14%   |
| Acer                    | 56        | 1.12%   |
| BenQ                    | 51        | 1.02%   |
| InfoVision              | 50        | 1%      |
| Philips                 | 42        | 0.84%   |
| Chi Mei Optoelectronics | 39        | 0.78%   |
| Ancor Communications    | 30        | 0.6%    |
| TMX                     | 26        | 0.52%   |
| Iiyama                  | 22        | 0.44%   |
| ASUSTek Computer        | 18        | 0.36%   |
| ViewSonic               | 16        | 0.32%   |
| Sony                    | 15        | 0.3%    |
| JDI                     | 10        | 0.2%    |
| CPT                     | 10        | 0.2%    |
| NEC Computers           | 9         | 0.18%   |
| MSI                     | 9         | 0.18%   |
| LG Philips              | 9         | 0.18%   |
| Eizo                    | 9         | 0.18%   |
| Toshiba                 | 8         | 0.16%   |
| Panasonic               | 8         | 0.16%   |
| BOE Technology Group    | 7         | 0.14%   |
| RTK                     | 5         | 0.1%    |
| Pixio                   | 5         | 0.1%    |
| LGD                     | 5         | 0.1%    |
| InnoLux Display         | 5         | 0.1%    |
| HannStar                | 5         | 0.1%    |
| Mi                      | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 47        | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 45        | 0.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 42        | 0.83%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 36        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 33        | 0.65%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 28        | 0.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 26        | 0.51%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 24        | 0.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 22        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 21        | 0.41%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 21        | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 19        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 19        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 18        | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 17        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 17        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 17        | 0.34%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 16        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 16        | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.3%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 15        | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 15        | 0.3%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 14        | 0.28%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 13        | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 12        | 0.24%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 12        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 12        | 0.24%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 11        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2397      | 51.52%  |
| 1366x768 (WXGA)    | 875       | 18.81%  |
| 3840x2160 (4K)     | 227       | 4.88%   |
| 2560x1440 (QHD)    | 192       | 4.13%   |
| 1600x900 (HD+)     | 155       | 3.33%   |
| 1920x1200 (WUXGA)  | 138       | 2.97%   |
| 2560x1600          | 104       | 2.24%   |
| 1280x800 (WXGA)    | 64        | 1.38%   |
| 2880x1800          | 63        | 1.35%   |
| 1440x900 (WXGA+)   | 46        | 0.99%   |
| 3840x2400          | 39        | 0.84%   |
| 3440x1440          | 37        | 0.8%    |
| 1680x1050 (WSXGA+) | 37        | 0.8%    |
| 2256x1504          | 26        | 0.56%   |
| 3200x1800 (QHD+)   | 24        | 0.52%   |
| 2560x1080          | 24        | 0.52%   |
| 1280x1024 (SXGA)   | 24        | 0.52%   |
| 2160x1440          | 22        | 0.47%   |
| 1360x768           | 16        | 0.34%   |
| 3200x2000          | 13        | 0.28%   |
| 3072x1920          | 12        | 0.26%   |
| 3840x1600          | 10        | 0.21%   |
| 3000x2000          | 10        | 0.21%   |
| Unknown            | 10        | 0.21%   |
| 1024x600           | 9         | 0.19%   |
| 3456x2160          | 8         | 0.17%   |
| 2240x1400          | 8         | 0.17%   |
| 2520x1680          | 6         | 0.13%   |
| 1920x540           | 6         | 0.13%   |
| 1600x1200          | 5         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.11%   |
| 800x1280           | 4         | 0.09%   |
| 3840x1080          | 4         | 0.09%   |
| 2880x1620          | 4         | 0.09%   |
| 3840x1100          | 3         | 0.06%   |
| 1680x945           | 3         | 0.06%   |
| 2944x1840          | 2         | 0.04%   |
| 1920x550           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1400x1050          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1915      | 38.25%  |
| 13      | 784       | 15.66%  |
| 14      | 719       | 14.36%  |
| 17      | 251       | 5.01%   |
| 27      | 220       | 4.39%   |
| 24      | 207       | 4.13%   |
| 23      | 144       | 2.88%   |
| 16      | 121       | 2.42%   |
| 12      | 117       | 2.34%   |
| 21      | 102       | 2.04%   |
| 34      | 55        | 1.1%    |
| 11      | 55        | 1.1%    |
| Unknown | 54        | 1.08%   |
| 18      | 40        | 0.8%    |
| 31      | 31        | 0.62%   |
| 19      | 25        | 0.5%    |
| 22      | 20        | 0.4%    |
| 20      | 18        | 0.36%   |
| 10      | 16        | 0.32%   |
| 84      | 11        | 0.22%   |
| 40      | 10        | 0.2%    |
| 37      | 9         | 0.18%   |
| 25      | 9         | 0.18%   |
| 72      | 8         | 0.16%   |
| 54      | 8         | 0.16%   |
| 28      | 8         | 0.16%   |
| 29      | 7         | 0.14%   |
| 32      | 5         | 0.1%    |
| 26      | 5         | 0.1%    |
| 52      | 4         | 0.08%   |
| 48      | 4         | 0.08%   |
| 74      | 3         | 0.06%   |
| 65      | 3         | 0.06%   |
| 42      | 2         | 0.04%   |
| 38      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |
| 3       | 2         | 0.04%   |
| 142     | 1         | 0.02%   |
| 57      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3078      | 62.09%  |
| 201-300        | 580       | 11.7%   |
| 501-600        | 533       | 10.75%  |
| 351-400        | 315       | 6.35%   |
| 401-500        | 189       | 3.81%   |
| 601-700        | 69        | 1.39%   |
| 701-800        | 61        | 1.23%   |
| Unknown        | 54        | 1.09%   |
| 801-900        | 23        | 0.46%   |
| 1001-1500      | 23        | 0.46%   |
| 1501-2000      | 22        | 0.44%   |
| 1-100          | 4         | 0.08%   |
| 901-1000       | 3         | 0.06%   |
| 101-200        | 2         | 0.04%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3579      | 82.01%  |
| 16/10   | 543       | 12.44%  |
| 3/2     | 77        | 1.76%   |
| 21/9    | 70        | 1.6%    |
| Unknown | 36        | 0.82%   |
| 5/4     | 24        | 0.55%   |
| 4/3     | 13        | 0.3%    |
| 32/9    | 8         | 0.18%   |
| 2.65    | 4         | 0.09%   |
| 6/5     | 3         | 0.07%   |
| 3.40    | 3         | 0.07%   |
| 0.67    | 2         | 0.05%   |
| 1.03    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1913      | 38.31%  |
| 81-90          | 1191      | 23.85%  |
| 201-250        | 390       | 7.81%   |
| 71-80          | 295       | 5.91%   |
| 301-350        | 224       | 4.49%   |
| 121-130        | 219       | 4.39%   |
| 61-70          | 113       | 2.26%   |
| 111-120        | 107       | 2.14%   |
| 351-500        | 98        | 1.96%   |
| 251-300        | 71        | 1.42%   |
| 151-200        | 68        | 1.36%   |
| 51-60          | 58        | 1.16%   |
| Unknown        | 54        | 1.08%   |
| 141-150        | 44        | 0.88%   |
| More than 1000 | 42        | 0.84%   |
| 91-100         | 30        | 0.6%    |
| 501-1000       | 29        | 0.58%   |
| 131-140        | 25        | 0.5%    |
| 41-50          | 17        | 0.34%   |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2295      | 46.81%  |
| 101-120       | 1007      | 20.54%  |
| 51-100        | 681       | 13.89%  |
| 161-240       | 568       | 11.58%  |
| More than 240 | 255       | 5.2%    |
| Unknown       | 54        | 1.1%    |
| 1-50          | 43        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3309      | 78.02%  |
| 2     | 808       | 19.05%  |
| 3     | 98        | 2.31%   |
| 0     | 17        | 0.4%    |
| 4     | 9         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2486      | 38.33%  |
| Realtek Semiconductor             | 2186      | 33.71%  |
| Qualcomm Atheros                  | 718       | 11.07%  |
| Broadcom                          | 251       | 3.87%   |
| MediaTek                          | 216       | 3.33%   |
| Broadcom Limited                  | 63        | 0.97%   |
| ASIX Electronics                  | 53        | 0.82%   |
| Qualcomm                          | 52        | 0.8%    |
| Lenovo                            | 49        | 0.76%   |
| TP-Link                           | 41        | 0.63%   |
| Sierra Wireless                   | 32        | 0.49%   |
| Ericsson Business Mobile Networks | 27        | 0.42%   |
| Xiaomi                            | 25        | 0.39%   |
| Ralink                            | 25        | 0.39%   |
| Marvell Technology Group          | 25        | 0.39%   |
| DisplayLink                       | 23        | 0.35%   |
| Samsung Electronics               | 21        | 0.32%   |
| Ralink Technology                 | 19        | 0.29%   |
| Dell                              | 19        | 0.29%   |
| Hewlett-Packard                   | 16        | 0.25%   |
| Apple                             | 12        | 0.19%   |
| Google                            | 11        | 0.17%   |
| D-Link                            | 11        | 0.17%   |
| Fibocom                           | 9         | 0.14%   |
| Huawei Technologies               | 8         | 0.12%   |
| Cypress Semiconductor             | 7         | 0.11%   |
| Qualcomm Atheros Communications   | 6         | 0.09%   |
| Nvidia                            | 6         | 0.09%   |
| NetGear                           | 6         | 0.09%   |
| Motorola PCS                      | 6         | 0.09%   |
| JMicron Technology                | 6         | 0.09%   |
| OPPO Electronics                  | 5         | 0.08%   |
| Linksys                           | 5         | 0.08%   |
| ASUSTek Computer                  | 4         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |
| Microsoft                         | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |
| Unknown                           | 3         | 0.05%   |
| U-Blox                            | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1442      | 18.61%  |
| Intel Wi-Fi 6 AX200                                               | 339       | 4.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 245       | 3.16%   |
| Intel Wireless 8265 / 8275                                        | 243       | 3.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 194       | 2.5%    |
| Intel Wi-Fi 6 AX201                                               | 187       | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 170       | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 148       | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 144       | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 143       | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 139       | 1.79%   |
| Intel Wireless 7265                                               | 136       | 1.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 121       | 1.56%   |
| Intel Wireless 8260                                               | 118       | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 115       | 1.48%   |
| Intel Wireless 7260                                               | 113       | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 102       | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 100       | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 97        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 96        | 1.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 96        | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 89        | 1.15%   |
| Intel Wireless 3165                                               | 86        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 82        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 78        | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 77        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 66        | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 59        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 59        | 0.76%   |
| Intel Wireless-AC 9260                                            | 58        | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 56        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 55        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 50        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 50        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 0.59%   |
| Intel Wireless 3160                                               | 45        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 44        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 44        | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2392      | 55.71%  |
| Qualcomm Atheros                  | 611       | 14.23%  |
| Realtek Semiconductor             | 582       | 13.55%  |
| Broadcom                          | 215       | 5.01%   |
| MediaTek                          | 211       | 4.91%   |
| Qualcomm                          | 49        | 1.14%   |
| Broadcom Limited                  | 49        | 1.14%   |
| Sierra Wireless                   | 32        | 0.75%   |
| TP-Link                           | 31        | 0.72%   |
| Ralink                            | 25        | 0.58%   |
| Ralink Technology                 | 19        | 0.44%   |
| Dell                              | 13        | 0.3%    |
| Ericsson Business Mobile Networks | 11        | 0.26%   |
| Fibocom                           | 9         | 0.21%   |
| D-Link                            | 9         | 0.21%   |
| Hewlett-Packard                   | 7         | 0.16%   |
| Qualcomm Atheros Communications   | 6         | 0.14%   |
| NetGear                           | 5         | 0.12%   |
| Linksys                           | 5         | 0.12%   |
| ASUSTek Computer                  | 3         | 0.07%   |
| Unknown                           | 3         | 0.07%   |
| Xiaomi                            | 2         | 0.05%   |
| Quectel Wireless Solutions        | 1         | 0.02%   |
| Qualcomm Technologies             | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |
| Marvell Technology Group          | 1         | 0.02%   |
| Edimax Technology                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 339       | 7.87%   |
| Intel Wireless 8265 / 8275                                     | 243       | 5.64%   |
| Intel Wi-Fi 6 AX201                                            | 187       | 4.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 170       | 3.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 148       | 3.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 143       | 3.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 139       | 3.23%   |
| Intel Wireless 7265                                            | 136       | 3.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 121       | 2.81%   |
| Intel Wireless 8260                                            | 118       | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 115       | 2.67%   |
| Intel Wireless 7260                                            | 113       | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 102       | 2.37%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 100       | 2.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 97        | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 2.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 96        | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 89        | 2.07%   |
| Intel Wireless 3165                                            | 86        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 82        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 77        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 66        | 1.53%   |
| Intel Wireless-AC 9260                                         | 58        | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 57        | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 56        | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 55        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 50        | 1.16%   |
| Intel Wireless 3160                                            | 45        | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 44        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 37        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 36        | 0.84%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 35        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                 | 31        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 30        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.63%   |
| Intel Centrino Advanced-N 6235                                 | 25        | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 24        | 0.56%   |
| Intel Centrino Advanced-N 6200                                 | 21        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1948      | 58.73%  |
| Intel                            | 841       | 25.35%  |
| Qualcomm Atheros                 | 166       | 5%      |
| Broadcom                         | 67        | 2.02%   |
| ASIX Electronics                 | 53        | 1.6%    |
| Lenovo                           | 45        | 1.36%   |
| Marvell Technology Group         | 24        | 0.72%   |
| Xiaomi                           | 23        | 0.69%   |
| DisplayLink                      | 23        | 0.69%   |
| Samsung Electronics              | 14        | 0.42%   |
| Broadcom Limited                 | 14        | 0.42%   |
| Apple                            | 12        | 0.36%   |
| Google                           | 11        | 0.33%   |
| TP-Link                          | 10        | 0.3%    |
| Cypress Semiconductor            | 7         | 0.21%   |
| Nvidia                           | 6         | 0.18%   |
| MediaTek                         | 6         | 0.18%   |
| JMicron Technology               | 6         | 0.18%   |
| OPPO Electronics                 | 5         | 0.15%   |
| Motorola PCS                     | 5         | 0.15%   |
| Huawei Technologies              | 4         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Qualcomm                         | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.06%   |
| Microsoft                        | 2         | 0.06%   |
| D-Link                           | 2         | 0.06%   |
| Aquantia                         | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| QNAP System                      | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |
| ASUSTek Computer                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1442      | 42.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 245       | 7.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 194       | 5.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 144       | 4.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 78        | 2.31%   |
| Intel Ethernet Connection (4) I219-V                              | 59        | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 1.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 50        | 1.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 44        | 1.3%    |
| Intel Ethernet Connection I218-LM                                 | 43        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 1.21%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 41        | 1.21%   |
| Intel Ethernet Connection (6) I219-V                              | 41        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 32        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 29        | 0.86%   |
| Intel 82567LM Gigabit Network Connection                          | 27        | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.77%   |
| Intel Ethernet Connection (6) I219-LM                             | 26        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 22        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.56%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.47%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.35%   |
| Lenovo USB-C Dock Ethernet                                        | 12        | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 12        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.33%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.33%   |
| Intel Ethernet Connection (16) I219-V                             | 11        | 0.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4110      | 56.22%  |
| Ethernet | 3144      | 43%     |
| Modem    | 52        | 0.71%   |
| Unknown  | 5         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3520      | 79.78%  |
| Ethernet | 890       | 20.17%  |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2838      | 68.37%  |
| 1     | 1232      | 29.68%  |
| 3     | 46        | 1.11%   |
| 0     | 33        | 0.79%   |
| 4     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3393      | 80.38%  |
| Yes  | 828       | 19.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2044      | 55.95%  |
| Realtek Semiconductor           | 355       | 9.72%   |
| Qualcomm Atheros Communications | 272       | 7.45%   |
| IMC Networks                    | 203       | 5.56%   |
| Foxconn / Hon Hai               | 163       | 4.46%   |
| Lite-On Technology              | 152       | 4.16%   |
| Broadcom                        | 144       | 3.94%   |
| Apple                           | 63        | 1.72%   |
| Realtek                         | 49        | 1.34%   |
| Dell                            | 39        | 1.07%   |
| Cambridge Silicon Radio         | 29        | 0.79%   |
| MediaTek                        | 25        | 0.68%   |
| USI                             | 22        | 0.6%    |
| Hewlett-Packard                 | 21        | 0.57%   |
| Toshiba                         | 14        | 0.38%   |
| Ralink                          | 14        | 0.38%   |
| Foxconn International           | 8         | 0.22%   |
| ASUSTek Computer                | 7         | 0.19%   |
| Opticis                         | 5         | 0.14%   |
| TP-Link                         | 3         | 0.08%   |
| Chicony Electronics             | 3         | 0.08%   |
| Askey Computer                  | 3         | 0.08%   |
| Smart Modular Technologies      | 2         | 0.05%   |
| Ralink Technology               | 2         | 0.05%   |
| Dynex                           | 2         | 0.05%   |
| Belkin Components               | 2         | 0.05%   |
| Alps Electric                   | 2         | 0.05%   |
| Syntek                          | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 713       | 19.49%  |
| Intel Bluetooth Device                              | 478       | 13.06%  |
| Intel AX200 Bluetooth                               | 320       | 8.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 301       | 8.23%   |
| Realtek Bluetooth Radio                             | 226       | 6.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 150       | 4.1%    |
| Intel AX210 Bluetooth                               | 97        | 2.65%   |
| IMC Networks Wireless_Device                        | 81        | 2.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 74        | 2.02%   |
| IMC Networks Bluetooth Radio                        | 58        | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 54        | 1.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 50        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 50        | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 50        | 1.37%   |
| Realtek Bluetooth Radio                             | 49        | 1.34%   |
| Lite-On Bluetooth Device                            | 44        | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 44        | 1.2%    |
| Apple Bluetooth Host Controller                     | 41        | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.01%   |
| IMC Networks Bluetooth Device                       | 37        | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 1.01%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 34        | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 0.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                   | 27        | 0.74%   |
| MediaTek Wireless_Device                            | 24        | 0.66%   |
| Lite-On Wireless_Device                             | 24        | 0.66%   |
| USI Bluetooth Device                                | 22        | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 21        | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.49%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 17        | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.44%   |
| Apple Bluetooth USB Host Controller                 | 16        | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 15        | 0.41%   |
| Ralink RT3290 Bluetooth                             | 14        | 0.38%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.38%   |
| Realtek RTL8821A Bluetooth                          | 13        | 0.36%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.36%   |
| Dell DW375 Bluetooth Module                         | 13        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3109      | 56.81%  |
| AMD                                  | 1056      | 19.29%  |
| Nvidia                               | 837       | 15.29%  |
| C-Media Electronics                  | 53        | 0.97%   |
| Lenovo                               | 46        | 0.84%   |
| Realtek Semiconductor                | 38        | 0.69%   |
| Logitech                             | 26        | 0.48%   |
| JMTek                                | 26        | 0.48%   |
| Texas Instruments                    | 22        | 0.4%    |
| GN Netcom                            | 21        | 0.38%   |
| Apple                                | 17        | 0.31%   |
| Kingston Technology                  | 15        | 0.27%   |
| Focusrite-Novation                   | 15        | 0.27%   |
| Razer USA                            | 12        | 0.22%   |
| SteelSeries ApS                      | 10        | 0.18%   |
| ASUSTek Computer                     | 10        | 0.18%   |
| Plantronics                          | 9         | 0.16%   |
| Hewlett-Packard                      | 8         | 0.15%   |
| Creative Technology                  | 8         | 0.15%   |
| Generalplus Technology               | 6         | 0.11%   |
| Corsair                              | 5         | 0.09%   |
| Samson Technologies                  | 4         | 0.07%   |
| DSEA A/S                             | 4         | 0.07%   |
| Unknown                              | 4         | 0.07%   |
| Yamaha                               | 3         | 0.05%   |
| Sony                                 | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.05%   |
| SAVITECH                             | 3         | 0.05%   |
| No brand                             | 3         | 0.05%   |
| Conexant Systems                     | 3         | 0.05%   |
| BR23                                 | 3         | 0.05%   |
| BEHRINGER International              | 3         | 0.05%   |
| XMOS                                 | 2         | 0.04%   |
| Valve Software                       | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |
| Silicon Motion                       | 2         | 0.04%   |
| Sennheiser Communications            | 2         | 0.04%   |
| Schiit Audio                         | 2         | 0.04%   |
| Native Instruments                   | 2         | 0.04%   |
| Microsoft                            | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 842       | 12.46%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 556       | 8.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 420       | 6.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 254       | 3.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 254       | 3.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 251       | 3.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 201       | 2.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 171       | 2.53%   |
| Intel Broadwell-U Audio Controller                                                                | 152       | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 150       | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 149       | 2.2%    |
| Intel 8 Series HD Audio Controller                                                                | 149       | 2.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 148       | 2.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 135       | 2%      |
| Intel Comet Lake PCH cAVS                                                                         | 129       | 1.91%   |
| Intel CM238 HD Audio Controller                                                                   | 129       | 1.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 122       | 1.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 112       | 1.66%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 109       | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 102       | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 101       | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 100       | 1.48%   |
| Nvidia Audio device                                                                               | 93        | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 93        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 79        | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 78        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 70        | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 69        | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 66        | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 62        | 0.92%   |
| AMD FCH Azalia Controller                                                                         | 53        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 48        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 46        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 43        | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 42        | 0.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 42        | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 37        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 33        | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 31        | 0.46%   |
| Realtek Semiconductor USB Audio                                                                   | 30        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1088      | 30.01%  |
| SK hynix            | 819       | 22.59%  |
| Micron Technology   | 488       | 13.46%  |
| Kingston            | 345       | 9.51%   |
| Crucial             | 224       | 6.18%   |
| Unknown             | 121       | 3.34%   |
| Ramaxel Technology  | 90        | 2.48%   |
| A-DATA Technology   | 79        | 2.18%   |
| Corsair             | 57        | 1.57%   |
| Elpida              | 48        | 1.32%   |
| G.Skill             | 28        | 0.77%   |
| Nanya Technology    | 21        | 0.58%   |
| Unknown             | 21        | 0.58%   |
| Team                | 17        | 0.47%   |
| Transcend           | 16        | 0.44%   |
| Smart               | 16        | 0.44%   |
| GOODRAM             | 16        | 0.44%   |
| Patriot             | 15        | 0.41%   |
| Unknown (ABCD)      | 13        | 0.36%   |
| Smart Brazil        | 7         | 0.19%   |
| AMD                 | 7         | 0.19%   |
| Teikon              | 6         | 0.17%   |
| PNY                 | 5         | 0.14%   |
| Goldkey             | 5         | 0.14%   |
| Apacer              | 5         | 0.14%   |
| Avant               | 4         | 0.11%   |
| V-GeN               | 3         | 0.08%   |
| Silicon Power       | 3         | 0.08%   |
| GSkill              | 3         | 0.08%   |
| 4ea5                | 3         | 0.08%   |
| 48spaces            | 3         | 0.08%   |
| V-Color             | 2         | 0.06%   |
| Unknown (08AE)      | 2         | 0.06%   |
| Sesame              | 2         | 0.06%   |
| PKI/Kingston        | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| High Bridge         | 2         | 0.06%   |
| fef5                | 2         | 0.06%   |
| ASint Technology    | 2         | 0.06%   |
| ZIFEI               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 67        | 1.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 67        | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 62        | 1.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 46        | 1.2%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 40        | 1.05%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 35        | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 35        | 0.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 0.84%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 31        | 0.81%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.76%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 28        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 26        | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 26        | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 24        | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 23        | 0.6%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 23        | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 21        | 0.55%   |
| Unknown                                                          | 21        | 0.55%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 19        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 19        | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.5%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 18        | 0.47%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 17        | 0.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 17        | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 16        | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 15        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1739      | 57.93%  |
| DDR3    | 726       | 24.18%  |
| LPDDR4  | 162       | 5.4%    |
| LPDDR3  | 110       | 3.66%   |
| DDR5    | 97        | 3.23%   |
| LPDDR5  | 83        | 2.76%   |
| DDR2    | 43        | 1.43%   |
| SDRAM   | 35        | 1.17%   |
| Unknown | 5         | 0.17%   |
| DRAM    | 1         | 0.03%   |
| DDR     | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2597      | 86.05%  |
| Row Of Chips | 364       | 12.06%  |
| Chip         | 34        | 1.13%   |
| Unknown      | 15        | 0.5%    |
| DIMM         | 8         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1486      | 44.96%  |
| 4096  | 795       | 24.05%  |
| 16384 | 611       | 18.49%  |
| 2048  | 231       | 6.99%   |
| 32768 | 139       | 4.21%   |
| 1024  | 42        | 1.27%   |
| 49152 | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 768       | 23.55%  |
| 3200    | 751       | 23.03%  |
| 1600    | 517       | 15.85%  |
| 2400    | 272       | 8.34%   |
| 2133    | 176       | 5.4%    |
| 1334    | 103       | 3.16%   |
| 4800    | 85        | 2.61%   |
| 4267    | 83        | 2.55%   |
| 6400    | 79        | 2.42%   |
| 1333    | 66        | 2.02%   |
| 3266    | 62        | 1.9%    |
| 1867    | 53        | 1.63%   |
| 1067    | 36        | 1.1%    |
| 667     | 31        | 0.95%   |
| 4266    | 30        | 0.92%   |
| 4199    | 20        | 0.61%   |
| 8400    | 19        | 0.58%   |
| Unknown | 16        | 0.49%   |
| 5600    | 15        | 0.46%   |
| 1066    | 14        | 0.43%   |
| 2048    | 12        | 0.37%   |
| 800     | 10        | 0.31%   |
| 2933    | 9         | 0.28%   |
| 975     | 9         | 0.28%   |
| 3733    | 5         | 0.15%   |
| 1866    | 3         | 0.09%   |
| 7500    | 2         | 0.06%   |
| 1200    | 2         | 0.06%   |
| 533     | 2         | 0.06%   |
| 400     | 2         | 0.06%   |
| 6000    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 3000    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 333     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 52.63%  |
| Samsung Electronics | 2         | 10.53%  |
| Prolific Technology | 2         | 10.53%  |
| Canon               | 2         | 10.53%  |
| Seiko Epson         | 1         | 5.26%   |
| Dymo-CoStar         | 1         | 5.26%   |
| Brother Industries  | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 10.53%  |
| HP DeskJet 2130 series        | 2         | 10.53%  |
| Seiko Epson WF-2530 Series    | 1         | 5.26%   |
| Samsung SCX-3200 Series       | 1         | 5.26%   |
| Samsung M2020 Series          | 1         | 5.26%   |
| HP OfficeJet 5600 (USBHUB)    | 1         | 5.26%   |
| HP LaserJet P1102             | 1         | 5.26%   |
| HP LaserJet 1320              | 1         | 5.26%   |
| HP LaserJet 1022              | 1         | 5.26%   |
| HP ENVY 5000 series           | 1         | 5.26%   |
| HP DeskJet 840c               | 1         | 5.26%   |
| HP DeskJet 4100 series        | 1         | 5.26%   |
| HP DeskJet 2600 series        | 1         | 5.26%   |
| Dymo-CoStar LabelWriter 400   | 1         | 5.26%   |
| Canon PIXMA MG2500 Series     | 1         | 5.26%   |
| Canon LiDE 400                | 1         | 5.26%   |
| Brother HL-1110 series        | 1         | 5.26%   |

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
| Chicony Electronics                    | 884       | 23.28%  |
| IMC Networks                           | 496       | 13.06%  |
| Microdia                               | 331       | 8.72%   |
| Bison Electronics                      | 322       | 8.48%   |
| Realtek Semiconductor                  | 282       | 7.43%   |
| Quanta                                 | 245       | 6.45%   |
| Sunplus Innovation Technology          | 195       | 5.14%   |
| Cheng Uei Precision Industry (Foxlink) | 128       | 3.37%   |
| Syntek                                 | 120       | 3.16%   |
| Lite-On Technology                     | 101       | 2.66%   |
| Luxvisions Innotech Limited            | 93        | 2.45%   |
| Logitech                               | 69        | 1.82%   |
| Acer                                   | 65        | 1.71%   |
| Apple                                  | 64        | 1.69%   |
| Suyin                                  | 61        | 1.61%   |
| Silicon Motion                         | 43        | 1.13%   |
| Sonix Technology                       | 40        | 1.05%   |
| Alcor Micro                            | 37        | 0.97%   |
| Lenovo                                 | 25        | 0.66%   |
| SunplusIT                              | 22        | 0.58%   |
| Samsung Electronics                    | 19        | 0.5%    |
| Importek                               | 14        | 0.37%   |
| Ricoh                                  | 13        | 0.34%   |
| ALi                                    | 11        | 0.29%   |
| Primax Electronics                     | 9         | 0.24%   |
| Microsoft                              | 7         | 0.18%   |
| Z-Star Microelectronics                | 6         | 0.16%   |
| ShineTech                              | 5         | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.13%   |
| ARC International                      | 5         | 0.13%   |
| OmniVision Technologies                | 4         | 0.11%   |
| MacroSilicon                           | 4         | 0.11%   |
| Google                                 | 4         | 0.11%   |
| 8SSC21D67422V1SR28902JL                | 4         | 0.11%   |
| LG Electronics                         | 3         | 0.08%   |
| 8SSC20F27114V1SR0BK1X4S                | 3         | 0.08%   |
| YGTek                                  | 2         | 0.05%   |
| Valve Software                         | 2         | 0.05%   |
| Shine-optics                           | 2         | 0.05%   |
| Razer USA                              | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 258       | 6.75%   |
| Microdia Integrated_Webcam_HD                                              | 187       | 4.89%   |
| IMC Networks Integrated Camera                                             | 160       | 4.18%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 154       | 4.03%   |
| Bison Integrated Camera                                                    | 110       | 2.88%   |
| Realtek Integrated_Webcam_HD                                               | 108       | 2.82%   |
| Sunplus Integrated_Webcam_HD                                               | 94        | 2.46%   |
| Chicony HD WebCam                                                          | 93        | 2.43%   |
| Syntek Integrated Camera                                                   | 81        | 2.12%   |
| Quanta HD User Facing                                                      | 55        | 1.44%   |
| Lite-On Integrated Camera                                                  | 55        | 1.44%   |
| Bison HD Webcam                                                            | 54        | 1.41%   |
| Bison SunplusIT Integrated Camera                                          | 46        | 1.2%    |
| Chicony HD User Facing                                                     | 41        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 39        | 1.02%   |
| Chicony Integrated Camera (1280x720@30)                                    | 38        | 0.99%   |
| Chicony USB2.0 Camera                                                      | 36        | 0.94%   |
| Chicony HP HD Camera                                                       | 35        | 0.92%   |
| Microdia Integrated Webcam                                                 | 33        | 0.86%   |
| Realtek USB Camera                                                         | 32        | 0.84%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 30        | 0.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 29        | 0.76%   |
| Chicony HP Wide Vision HD Camera                                           | 29        | 0.76%   |
| IMC Networks HD Camera                                                     | 28        | 0.73%   |
| Quanta HP Wide Vision HD Camera                                            | 27        | 0.71%   |
| Chicony HP Truevision HD                                                   | 27        | 0.71%   |
| Realtek Integrated Webcam                                                  | 25        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 25        | 0.65%   |
| Quanta HP TrueVision HD Camera                                             | 24        | 0.63%   |
| Chicony Integrated IR Camera                                               | 24        | 0.63%   |
| Chicony HP TrueVision HD Camera                                            | 24        | 0.63%   |
| Sunplus HD WebCam                                                          | 23        | 0.6%    |
| Quanta VGA WebCam                                                          | 23        | 0.6%    |
| Quanta HP HD Camera                                                        | 22        | 0.58%   |
| Lite-On HP HD Camera                                                       | 22        | 0.58%   |
| IMC Networks ov9734_azurewave_camera                                       | 21        | 0.55%   |
| Chicony EasyCamera                                                         | 21        | 0.55%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 21        | 0.55%   |
| Syntek Lenovo EasyCamera                                                   | 20        | 0.52%   |
| Quanta HD WebCam                                                           | 20        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 299       | 34.13%  |
| Validity Sensors                   | 240       | 27.4%   |
| Shenzhen Goodix Technology         | 175       | 19.98%  |
| Elan Microelectronics              | 58        | 6.62%   |
| LighTuning Technology              | 32        | 3.65%   |
| Upek                               | 30        | 3.42%   |
| AuthenTec                          | 20        | 2.28%   |
| STMicroelectronics                 | 9         | 1.03%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.57%   |
| HOLTEK                             | 4         | 0.46%   |
| Samsung Electronics                | 3         | 0.34%   |
| Focal-systems.Corp                 | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 124       | 14.16%  |
| Shenzhen Goodix  Fingerprint Device                                        | 103       | 11.76%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 61        | 6.96%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 45        | 5.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 4.68%   |
| Shenzhen Goodix FingerPrint                                                | 40        | 4.57%   |
| Elan ELAN:Fingerprint                                                      | 34        | 3.88%   |
| Validity Sensors Synaptics WBDI                                            | 32        | 3.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 32        | 3.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 29        | 3.31%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 3.2%    |
| Elan ELAN:ARM-M4                                                           | 24        | 2.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 20        | 2.28%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 19        | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 19        | 2.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 18        | 2.05%   |
| Synaptics UWP WBDI Device                                                  | 16        | 1.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.71%   |
| Validity Sensors VFS491                                                    | 14        | 1.6%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 14        | 1.6%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 14        | 1.6%    |
| Validity Sensors Fingerprint scanner                                       | 13        | 1.48%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 1.48%   |
| AuthenTec AES2810                                                          | 11        | 1.26%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 1.03%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 0.8%    |
| Synaptics  WBDI                                                            | 6         | 0.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 0.57%   |
| Synaptics UWP WBDI                                                         | 5         | 0.57%   |
| Synaptics TouchPad                                                         | 5         | 0.57%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 0.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.46%   |
| Synaptics WBDI Device                                                      | 4         | 0.46%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 0.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.34%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.34%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.34%   |
| Synaptics WBDI                                                             | 3         | 0.34%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 153       | 43.1%   |
| Broadcom                  | 132       | 37.18%  |
| Upek                      | 25        | 7.04%   |
| Lenovo                    | 13        | 3.66%   |
| O2 Micro                  | 12        | 3.38%   |
| SCM Microsystems          | 5         | 1.41%   |
| Yubico.com                | 4         | 1.13%   |
| Gemalto (was Gemplus)     | 3         | 0.85%   |
| Clay Logic                | 2         | 0.56%   |
| Realtek Semiconductor     | 1         | 0.28%   |
| Hewlett-Packard           | 1         | 0.28%   |
| Chicony Electronics       | 1         | 0.28%   |
| Aladdin Knowledge Systems | 1         | 0.28%   |
| Aktiv                     | 1         | 0.28%   |
| Advanced Card Systems     | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 153       | 43.1%   |
| Broadcom 5880                                                                | 36        | 10.14%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 9.58%   |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 8.45%   |
| Broadcom 58200                                                               | 30        | 8.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 25        | 7.04%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 3.66%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 3.1%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 1.13%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 4         | 1.13%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.85%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.56%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.28%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.28%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.28%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.28%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.28%   |
| Aktiv Rutoken lite                                                           | 1         | 0.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2535      | 59.72%  |
| 1     | 1348      | 31.76%  |
| 2     | 288       | 6.78%   |
| 3     | 64        | 1.51%   |
| 4     | 8         | 0.19%   |
| 7     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 856       | 40.76%  |
| Graphics card            | 399       | 19%     |
| Chipcard                 | 312       | 14.86%  |
| Multimedia controller    | 151       | 7.19%   |
| Net/wireless             | 125       | 5.95%   |
| Camera                   | 106       | 5.05%   |
| Bluetooth                | 40        | 1.9%    |
| Net/ethernet             | 21        | 1%      |
| Storage                  | 19        | 0.9%    |
| Sound                    | 16        | 0.76%   |
| Card reader              | 15        | 0.71%   |
| Communication controller | 14        | 0.67%   |
| Network                  | 9         | 0.43%   |
| Modem                    | 7         | 0.33%   |
| Dvb card                 | 3         | 0.14%   |
| Wireless                 | 2         | 0.1%    |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

