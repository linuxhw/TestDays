Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 4211

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [4eaeb1d5ad](https://linux-hardware.org/?probe=4eaeb1d5ad) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| MSI           | PRO X670-P WIFI             | Desktop     | [64299c7b4a](https://linux-hardware.org/?probe=64299c7b4a) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | Notebook    | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Acer          | Spin SP314-53               | Convertible | [ce95ade177](https://linux-hardware.org/?probe=ce95ade177) | Sep 27, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [565d46fb85](https://linux-hardware.org/?probe=565d46fb85) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1b2f7b8972](https://linux-hardware.org/?probe=1b2f7b8972) | Sep 27, 2022 |
| System76      | Galago Pro                  | Notebook    | [e815519fb7](https://linux-hardware.org/?probe=e815519fb7) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dce9d30a10](https://linux-hardware.org/?probe=dce9d30a10) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | Notebook    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [a96f37005a](https://linux-hardware.org/?probe=a96f37005a) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [05dc7a54c7](https://linux-hardware.org/?probe=05dc7a54c7) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b598ecc4f8](https://linux-hardware.org/?probe=b598ecc4f8) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [67432a461e](https://linux-hardware.org/?probe=67432a461e) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| Acer          | TMP645-M                    | Notebook    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [d8d21241de](https://linux-hardware.org/?probe=d8d21241de) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| Dell          | Precision 7760              | Notebook    | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | Notebook    | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| ASRock        | Z690 Pro RS                 | Desktop     | [787589762f](https://linux-hardware.org/?probe=787589762f) | Sep 21, 2022 |
| Shuttle       | FS81                        | Desktop     | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [7c7043ad0f](https://linux-hardware.org/?probe=7c7043ad0f) | Sep 19, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [48d71b12fc](https://linux-hardware.org/?probe=48d71b12fc) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [43fbf9fec9](https://linux-hardware.org/?probe=43fbf9fec9) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [850e17ede5](https://linux-hardware.org/?probe=850e17ede5) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [126b3ed209](https://linux-hardware.org/?probe=126b3ed209) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [08c270ce3d](https://linux-hardware.org/?probe=08c270ce3d) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | Notebook    | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ebd7ab6202](https://linux-hardware.org/?probe=ebd7ab6202) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [d562164e67](https://linux-hardware.org/?probe=d562164e67) | Sep 12, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [491242ea90](https://linux-hardware.org/?probe=491242ea90) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [c3ceb9c38b](https://linux-hardware.org/?probe=c3ceb9c38b) | Sep 11, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e8c2730c9](https://linux-hardware.org/?probe=1e8c2730c9) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Dell          | Latitude E7470              | Notebook    | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [56357e3cc7](https://linux-hardware.org/?probe=56357e3cc7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [3432790e95](https://linux-hardware.org/?probe=3432790e95) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [ccd383a106](https://linux-hardware.org/?probe=ccd383a106) | Sep 05, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [0859dbdb1c](https://linux-hardware.org/?probe=0859dbdb1c) | Sep 04, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a746f6faa6](https://linux-hardware.org/?probe=a746f6faa6) | Sep 04, 2022 |
| HP            | 2AF3                        | Desktop     | [58eae39fe2](https://linux-hardware.org/?probe=58eae39fe2) | Sep 03, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [e03d937610](https://linux-hardware.org/?probe=e03d937610) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [888ed47bbe](https://linux-hardware.org/?probe=888ed47bbe) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [67aeed6eb1](https://linux-hardware.org/?probe=67aeed6eb1) | Sep 01, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [b1b4bd6ce0](https://linux-hardware.org/?probe=b1b4bd6ce0) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [d9505cea0a](https://linux-hardware.org/?probe=d9505cea0a) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [dc62f3b267](https://linux-hardware.org/?probe=dc62f3b267) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [4d1df25a9f](https://linux-hardware.org/?probe=4d1df25a9f) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | Notebook    | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [a0f47aaaa7](https://linux-hardware.org/?probe=a0f47aaaa7) | Aug 28, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [137641269c](https://linux-hardware.org/?probe=137641269c) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [a1b7c5d6ab](https://linux-hardware.org/?probe=a1b7c5d6ab) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | Notebook    | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [8a23dbfd36](https://linux-hardware.org/?probe=8a23dbfd36) | Aug 25, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [fda9abd530](https://linux-hardware.org/?probe=fda9abd530) | Aug 24, 2022 |
| HP            | 1905                        | Desktop     | [6693a2b3c7](https://linux-hardware.org/?probe=6693a2b3c7) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6d0a3e71d7](https://linux-hardware.org/?probe=6d0a3e71d7) | Aug 24, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Google        | Teemo                       | Desktop     | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [7a8fee05aa](https://linux-hardware.org/?probe=7a8fee05aa) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ed2076bba5](https://linux-hardware.org/?probe=ed2076bba5) | Aug 20, 2022 |
| ASUSTek       | X756UAK                     | Notebook    | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | Notebook    | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [1efeb7be2c](https://linux-hardware.org/?probe=1efeb7be2c) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [87ba9f4be1](https://linux-hardware.org/?probe=87ba9f4be1) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [171a797c22](https://linux-hardware.org/?probe=171a797c22) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [f882fcbe3a](https://linux-hardware.org/?probe=f882fcbe3a) | Aug 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [be0b70efdb](https://linux-hardware.org/?probe=be0b70efdb) | Aug 15, 2022 |
| MSI           | H61M-P20                    | Desktop     | [9adc2fa427](https://linux-hardware.org/?probe=9adc2fa427) | Aug 15, 2022 |
| HP            | 1493                        | Desktop     | [e5d0f16bbc](https://linux-hardware.org/?probe=e5d0f16bbc) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [dc9013cc44](https://linux-hardware.org/?probe=dc9013cc44) | Aug 14, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| MSI           | H61M-P20                    | Desktop     | [acc2520058](https://linux-hardware.org/?probe=acc2520058) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | Notebook    | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| Gigabyte      | Z87M-D3HP                   | Desktop     | [b6612680e2](https://linux-hardware.org/?probe=b6612680e2) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [dc354e0b4f](https://linux-hardware.org/?probe=dc354e0b4f) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| HP            | 2B21 A01                    | All in one  | [aba1a53f52](https://linux-hardware.org/?probe=aba1a53f52) | Aug 07, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a73917b78](https://linux-hardware.org/?probe=6a73917b78) | Aug 07, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [db3d9f24c6](https://linux-hardware.org/?probe=db3d9f24c6) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| Unknown       | Unknown                     | Soc         | [9efd347024](https://linux-hardware.org/?probe=9efd347024) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e477bf9f83](https://linux-hardware.org/?probe=e477bf9f83) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [360447806b](https://linux-hardware.org/?probe=360447806b) | Aug 04, 2022 |
| Dell          | 06WXJT A02                  | Server      | [424b1059df](https://linux-hardware.org/?probe=424b1059df) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Lenovo        | 3102                        | Desktop     | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Dell          | 06WXJT A07                  | Server      | [e0b1ede266](https://linux-hardware.org/?probe=e0b1ede266) | Aug 03, 2022 |
| Dell          | 06WXJT A02                  | Server      | [fcf7baab04](https://linux-hardware.org/?probe=fcf7baab04) | Aug 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Dell          | XPS 9320                    | Notebook    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [63553d673b](https://linux-hardware.org/?probe=63553d673b) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [2de5d5cf8a](https://linux-hardware.org/?probe=2de5d5cf8a) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [e1fa8ab12b](https://linux-hardware.org/?probe=e1fa8ab12b) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [81c46b891f](https://linux-hardware.org/?probe=81c46b891f) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| Intel         | NUC7i5BNB J31144-302        | Mini pc     | [638275ad97](https://linux-hardware.org/?probe=638275ad97) | Jul 31, 2022 |
| HP            | 82F2                        | Desktop     | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [51695dd3ea](https://linux-hardware.org/?probe=51695dd3ea) | Jul 29, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [2381ee35c0](https://linux-hardware.org/?probe=2381ee35c0) | Jul 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Unknown       | HX90                        | Desktop     | [1594710372](https://linux-hardware.org/?probe=1594710372) | Jul 28, 2022 |
| Dell          | Latitude E7250              | Notebook    | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [050aa57cb4](https://linux-hardware.org/?probe=050aa57cb4) | Jul 26, 2022 |
| Dell          | Latitude 3400               | Notebook    | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| Lenovo        | 3702 SDK0J40700 WIN 3258... | All in one  | [95af4e4f8e](https://linux-hardware.org/?probe=95af4e4f8e) | Jul 23, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Google        | Peppy                       | Notebook    | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | Notebook    | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | Latitude 5430               | Notebook    | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [85df5dd7a2](https://linux-hardware.org/?probe=85df5dd7a2) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a5082efd70](https://linux-hardware.org/?probe=a5082efd70) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [662e59e904](https://linux-hardware.org/?probe=662e59e904) | Jul 17, 2022 |
| Alienware     | x17 R1                      | Notebook    | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [950542a4a3](https://linux-hardware.org/?probe=950542a4a3) | Jul 16, 2022 |
| HP            | 802E                        | Desktop     | [c86ddd647b](https://linux-hardware.org/?probe=c86ddd647b) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | Notebook    | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [a27d53815e](https://linux-hardware.org/?probe=a27d53815e) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [77f2181e08](https://linux-hardware.org/?probe=77f2181e08) | Jul 13, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [ff67056edc](https://linux-hardware.org/?probe=ff67056edc) | Jul 13, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [29602ec66f](https://linux-hardware.org/?probe=29602ec66f) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Unknown       | Unknown                     | Soc         | [d3742575fd](https://linux-hardware.org/?probe=d3742575fd) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [9cc1538196](https://linux-hardware.org/?probe=9cc1538196) | Jul 12, 2022 |
| MSI           | X99S GAMING 9 AC            | Desktop     | [5f682aadd5](https://linux-hardware.org/?probe=5f682aadd5) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [07a37c99cb](https://linux-hardware.org/?probe=07a37c99cb) | Jul 11, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [7373f62fa5](https://linux-hardware.org/?probe=7373f62fa5) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [60d115ad0c](https://linux-hardware.org/?probe=60d115ad0c) | Jul 09, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [fd8bd29c03](https://linux-hardware.org/?probe=fd8bd29c03) | Jul 09, 2022 |
| Acer          | Aspire Z3-710               | All in one  | [5f7d41a8ae](https://linux-hardware.org/?probe=5f7d41a8ae) | Jul 09, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [36fa61e21d](https://linux-hardware.org/?probe=36fa61e21d) | Jul 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [fb5a2ac873](https://linux-hardware.org/?probe=fb5a2ac873) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [48bd0906cf](https://linux-hardware.org/?probe=48bd0906cf) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [503c38154f](https://linux-hardware.org/?probe=503c38154f) | Jul 07, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [8e7d7a945f](https://linux-hardware.org/?probe=8e7d7a945f) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e69b07f3e9](https://linux-hardware.org/?probe=e69b07f3e9) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [28b0984086](https://linux-hardware.org/?probe=28b0984086) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [e795477a20](https://linux-hardware.org/?probe=e795477a20) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [e165fd805c](https://linux-hardware.org/?probe=e165fd805c) | Jul 04, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [ac5093fe3d](https://linux-hardware.org/?probe=ac5093fe3d) | Jul 04, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e99c8ae46f](https://linux-hardware.org/?probe=e99c8ae46f) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [fc29bb14e9](https://linux-hardware.org/?probe=fc29bb14e9) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [f2a1afe8eb](https://linux-hardware.org/?probe=f2a1afe8eb) | Jul 03, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [1295c3de55](https://linux-hardware.org/?probe=1295c3de55) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [4044d76f9b](https://linux-hardware.org/?probe=4044d76f9b) | Jul 02, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [ef2f004b52](https://linux-hardware.org/?probe=ef2f004b52) | Jul 02, 2022 |
| ASRock        | Z390 Pro4                   | Desktop     | [25bd784ca6](https://linux-hardware.org/?probe=25bd784ca6) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [9b8bb163d3](https://linux-hardware.org/?probe=9b8bb163d3) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [4d1e0cc30c](https://linux-hardware.org/?probe=4d1e0cc30c) | Jun 30, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [f97c981688](https://linux-hardware.org/?probe=f97c981688) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af29dc9fe1](https://linux-hardware.org/?probe=af29dc9fe1) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | Notebook    | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| Dell          | Latitude 5430               | Notebook    | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [d2034a53b8](https://linux-hardware.org/?probe=d2034a53b8) | Jun 28, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [b7e193f50c](https://linux-hardware.org/?probe=b7e193f50c) | Jun 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [5b997790f1](https://linux-hardware.org/?probe=5b997790f1) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [d703a63932](https://linux-hardware.org/?probe=d703a63932) | Jun 26, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [34a2f4f726](https://linux-hardware.org/?probe=34a2f4f726) | Jun 26, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f4500ddad](https://linux-hardware.org/?probe=2f4500ddad) | Jun 26, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [bd52209b2a](https://linux-hardware.org/?probe=bd52209b2a) | Jun 24, 2022 |
| Alienware     | 14                          | Notebook    | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [015aa87271](https://linux-hardware.org/?probe=015aa87271) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | Notebook    | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | Notebook    | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | Notebook    | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [c4b2a02630](https://linux-hardware.org/?probe=c4b2a02630) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | Notebook    | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [989b450d8b](https://linux-hardware.org/?probe=989b450d8b) | Jun 23, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [447653d4f2](https://linux-hardware.org/?probe=447653d4f2) | Jun 22, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [4610c38358](https://linux-hardware.org/?probe=4610c38358) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [b65a5020db](https://linux-hardware.org/?probe=b65a5020db) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d5098cc011](https://linux-hardware.org/?probe=d5098cc011) | Jun 22, 2022 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [20cf9d2706](https://linux-hardware.org/?probe=20cf9d2706) | Jun 21, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ecc6e0f4ef](https://linux-hardware.org/?probe=ecc6e0f4ef) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | Notebook    | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | Notebook    | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| Dell          | Precision 5540              | Notebook    | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [0d4c3d0c10](https://linux-hardware.org/?probe=0d4c3d0c10) | Jun 17, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [ac205eb1ec](https://linux-hardware.org/?probe=ac205eb1ec) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17e9f5a71f](https://linux-hardware.org/?probe=17e9f5a71f) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | Notebook    | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [57ad2e9147](https://linux-hardware.org/?probe=57ad2e9147) | Jun 15, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8ded20d82b](https://linux-hardware.org/?probe=8ded20d82b) | Jun 15, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [670d05fbe3](https://linux-hardware.org/?probe=670d05fbe3) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [848f1d55c8](https://linux-hardware.org/?probe=848f1d55c8) | Jun 14, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [aca5883c17](https://linux-hardware.org/?probe=aca5883c17) | Jun 14, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [fb157585e5](https://linux-hardware.org/?probe=fb157585e5) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [8bb84d5aaf](https://linux-hardware.org/?probe=8bb84d5aaf) | Jun 14, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [0c6a9f5dff](https://linux-hardware.org/?probe=0c6a9f5dff) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [aeec9e715d](https://linux-hardware.org/?probe=aeec9e715d) | Jun 13, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [db209b6bf1](https://linux-hardware.org/?probe=db209b6bf1) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [1e3a9647e9](https://linux-hardware.org/?probe=1e3a9647e9) | Jun 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [23fa842567](https://linux-hardware.org/?probe=23fa842567) | Jun 11, 2022 |
| HP            | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [576fc8e8ed](https://linux-hardware.org/?probe=576fc8e8ed) | Jun 11, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fd1478145b](https://linux-hardware.org/?probe=fd1478145b) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [b1e492c444](https://linux-hardware.org/?probe=b1e492c444) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [9198e2d64c](https://linux-hardware.org/?probe=9198e2d64c) | Jun 10, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [267db233fa](https://linux-hardware.org/?probe=267db233fa) | Jun 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [b33d07af6c](https://linux-hardware.org/?probe=b33d07af6c) | Jun 09, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | Notebook    | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2ac69cc327](https://linux-hardware.org/?probe=2ac69cc327) | Jun 08, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [9342f5c46b](https://linux-hardware.org/?probe=9342f5c46b) | Jun 08, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [fdba6d0041](https://linux-hardware.org/?probe=fdba6d0041) | Jun 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d984f403e9](https://linux-hardware.org/?probe=d984f403e9) | Jun 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [73e68df88c](https://linux-hardware.org/?probe=73e68df88c) | Jun 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [bfa4e4ff74](https://linux-hardware.org/?probe=bfa4e4ff74) | Jun 07, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [67cfa56623](https://linux-hardware.org/?probe=67cfa56623) | Jun 07, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | Desktop     | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | Desktop     | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [0546f2fdfd](https://linux-hardware.org/?probe=0546f2fdfd) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f496dbb19](https://linux-hardware.org/?probe=8f496dbb19) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | Notebook    | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Acer          | Veriton N4670G              | Desktop     | [0b85f95c4c](https://linux-hardware.org/?probe=0b85f95c4c) | Jun 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3b4483236d](https://linux-hardware.org/?probe=3b4483236d) | Jun 05, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [9207d2f2d8](https://linux-hardware.org/?probe=9207d2f2d8) | Jun 04, 2022 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [a77acb5d89](https://linux-hardware.org/?probe=a77acb5d89) | Jun 04, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4bbee9909a](https://linux-hardware.org/?probe=4bbee9909a) | Jun 04, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [f770ece55b](https://linux-hardware.org/?probe=f770ece55b) | Jun 03, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [24c8a035ac](https://linux-hardware.org/?probe=24c8a035ac) | Jun 03, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0ddfd77617](https://linux-hardware.org/?probe=0ddfd77617) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Alienware     | 0XJKKD A00                  | Desktop     | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| HP            | 1632                        | Desktop     | [4f7993cf34](https://linux-hardware.org/?probe=4f7993cf34) | Jun 01, 2022 |
| HP            | 1632                        | Desktop     | [9e69c11025](https://linux-hardware.org/?probe=9e69c11025) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [20de61bf9f](https://linux-hardware.org/?probe=20de61bf9f) | Jun 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0faa61f3a9](https://linux-hardware.org/?probe=0faa61f3a9) | May 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [9f5906337b](https://linux-hardware.org/?probe=9f5906337b) | May 31, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [ec75dd8324](https://linux-hardware.org/?probe=ec75dd8324) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | Notebook    | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [33ac99c04e](https://linux-hardware.org/?probe=33ac99c04e) | May 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3bb74db496](https://linux-hardware.org/?probe=3bb74db496) | May 30, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [b1323f0c11](https://linux-hardware.org/?probe=b1323f0c11) | May 29, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [96cd8abf05](https://linux-hardware.org/?probe=96cd8abf05) | May 29, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [9c69f7b836](https://linux-hardware.org/?probe=9c69f7b836) | May 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b810bd52cc](https://linux-hardware.org/?probe=b810bd52cc) | May 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [719fe6db76](https://linux-hardware.org/?probe=719fe6db76) | May 28, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e7b6eddea](https://linux-hardware.org/?probe=6e7b6eddea) | May 27, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3302c5de16](https://linux-hardware.org/?probe=3302c5de16) | May 27, 2022 |
| HP            | 0AECh D                     | Desktop     | [ee3f56c60e](https://linux-hardware.org/?probe=ee3f56c60e) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9011cf0a9b](https://linux-hardware.org/?probe=9011cf0a9b) | May 27, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ac41fb756c](https://linux-hardware.org/?probe=ac41fb756c) | May 26, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [18427eddde](https://linux-hardware.org/?probe=18427eddde) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [89927eb8f5](https://linux-hardware.org/?probe=89927eb8f5) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [4ea6883bee](https://linux-hardware.org/?probe=4ea6883bee) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [192f2ac212](https://linux-hardware.org/?probe=192f2ac212) | May 23, 2022 |
| Toshiba       | TECRA R850                  | Notebook    | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [0ea1ce7372](https://linux-hardware.org/?probe=0ea1ce7372) | May 22, 2022 |
| Dell          | G3 3500                     | Notebook    | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [eaf9e6332b](https://linux-hardware.org/?probe=eaf9e6332b) | May 21, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [445a484f8d](https://linux-hardware.org/?probe=445a484f8d) | May 21, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Unknown       | Unknown                     | Soc         | [3028420085](https://linux-hardware.org/?probe=3028420085) | May 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [acbead429c](https://linux-hardware.org/?probe=acbead429c) | May 20, 2022 |
| HP            | 8053                        | Desktop     | [53c0148d64](https://linux-hardware.org/?probe=53c0148d64) | May 20, 2022 |
| ECS           | P67H2-A3                    | Desktop     | [2bc21b9c81](https://linux-hardware.org/?probe=2bc21b9c81) | May 20, 2022 |
| HP            | 8381 1000                   | All in one  | [04684aee01](https://linux-hardware.org/?probe=04684aee01) | May 19, 2022 |
| HP            | 8381 1000                   | All in one  | [57e63582bf](https://linux-hardware.org/?probe=57e63582bf) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c3438d922b](https://linux-hardware.org/?probe=c3438d922b) | May 19, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | Notebook    | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [031c2ec486](https://linux-hardware.org/?probe=031c2ec486) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c831b3937a](https://linux-hardware.org/?probe=c831b3937a) | May 16, 2022 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [3c99b8d861](https://linux-hardware.org/?probe=3c99b8d861) | May 16, 2022 |
| Gigabyte      | A7 K1                       | Notebook    | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [9161d40357](https://linux-hardware.org/?probe=9161d40357) | May 14, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [e34d9464b2](https://linux-hardware.org/?probe=e34d9464b2) | May 14, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [45a26a9322](https://linux-hardware.org/?probe=45a26a9322) | May 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3a07cc7daf](https://linux-hardware.org/?probe=3a07cc7daf) | May 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [91730625e9](https://linux-hardware.org/?probe=91730625e9) | May 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [210d27dd90](https://linux-hardware.org/?probe=210d27dd90) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [78c64b498b](https://linux-hardware.org/?probe=78c64b498b) | May 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | Desktop     | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [602289ad13](https://linux-hardware.org/?probe=602289ad13) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | Notebook    | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [05b277774e](https://linux-hardware.org/?probe=05b277774e) | May 12, 2022 |
| HP            | 8526 MVB, A                 | Desktop     | [50b2aa8de2](https://linux-hardware.org/?probe=50b2aa8de2) | May 12, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Acer          | Aspire X3990                | Desktop     | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [9797dc24f1](https://linux-hardware.org/?probe=9797dc24f1) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| MSI           | H97M-E35                    | Desktop     | [fdd0f51b46](https://linux-hardware.org/?probe=fdd0f51b46) | May 10, 2022 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [ffc3d3cf27](https://linux-hardware.org/?probe=ffc3d3cf27) | May 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| ASRock        | H87M                        | Desktop     | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| Acer          | Aspire XC-603               | Desktop     | [3d806cb212](https://linux-hardware.org/?probe=3d806cb212) | May 08, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [e4340f1707](https://linux-hardware.org/?probe=e4340f1707) | May 07, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [57d0654584](https://linux-hardware.org/?probe=57d0654584) | May 06, 2022 |
| HP            | Folio 13 - 2000             | Notebook    | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [c44c5e8931](https://linux-hardware.org/?probe=c44c5e8931) | May 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [f99b5cee66](https://linux-hardware.org/?probe=f99b5cee66) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [46adc67882](https://linux-hardware.org/?probe=46adc67882) | May 05, 2022 |
| Dell          | Studio 1555                 | Notebook    | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [ba7fe58d02](https://linux-hardware.org/?probe=ba7fe58d02) | May 03, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6bcd7320](https://linux-hardware.org/?probe=1d6bcd7320) | May 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8e220517f5](https://linux-hardware.org/?probe=8e220517f5) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [579cadce96](https://linux-hardware.org/?probe=579cadce96) | May 02, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [42067d196a](https://linux-hardware.org/?probe=42067d196a) | May 02, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [6203143b59](https://linux-hardware.org/?probe=6203143b59) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [71fee7e383](https://linux-hardware.org/?probe=71fee7e383) | Apr 29, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [64cb392628](https://linux-hardware.org/?probe=64cb392628) | Apr 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [1f26415f58](https://linux-hardware.org/?probe=1f26415f58) | Apr 28, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [910da71dd2](https://linux-hardware.org/?probe=910da71dd2) | Apr 28, 2022 |
| ASUSTek       | VANGUARD B85                | Desktop     | [d591002039](https://linux-hardware.org/?probe=d591002039) | Apr 27, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [77c2b99e9b](https://linux-hardware.org/?probe=77c2b99e9b) | Apr 27, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | Notebook    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| Unknown       | Unknown                     | Soc         | [5937b60f18](https://linux-hardware.org/?probe=5937b60f18) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [93c883ef59](https://linux-hardware.org/?probe=93c883ef59) | Apr 26, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [205ae74d07](https://linux-hardware.org/?probe=205ae74d07) | Apr 26, 2022 |
| HP            | ProBook 4710s               | Notebook    | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [973e161bd9](https://linux-hardware.org/?probe=973e161bd9) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [f0aea29124](https://linux-hardware.org/?probe=f0aea29124) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [d076b5c763](https://linux-hardware.org/?probe=d076b5c763) | Apr 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [e686789a94](https://linux-hardware.org/?probe=e686789a94) | Apr 24, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [551ea1b91f](https://linux-hardware.org/?probe=551ea1b91f) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8ff97fd246](https://linux-hardware.org/?probe=8ff97fd246) | Apr 23, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [e8e0b5fd5d](https://linux-hardware.org/?probe=e8e0b5fd5d) | Apr 22, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c32d394b3a](https://linux-hardware.org/?probe=c32d394b3a) | Apr 21, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [cbb3f353a5](https://linux-hardware.org/?probe=cbb3f353a5) | Apr 21, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [df18833e16](https://linux-hardware.org/?probe=df18833e16) | Apr 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fc1fd7355c](https://linux-hardware.org/?probe=fc1fd7355c) | Apr 21, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1c54ba7a0c](https://linux-hardware.org/?probe=1c54ba7a0c) | Apr 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e69787ee4](https://linux-hardware.org/?probe=3e69787ee4) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [a6bd59cad3](https://linux-hardware.org/?probe=a6bd59cad3) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [7969fc986b](https://linux-hardware.org/?probe=7969fc986b) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [350979cb0a](https://linux-hardware.org/?probe=350979cb0a) | Apr 19, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Unknown       | Unknown                     | Soc         | [290d2ba979](https://linux-hardware.org/?probe=290d2ba979) | Apr 19, 2022 |
| Timi          | A35S                        | Notebook    | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [4c845dc459](https://linux-hardware.org/?probe=4c845dc459) | Apr 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [179b76718e](https://linux-hardware.org/?probe=179b76718e) | Apr 18, 2022 |
| Dell          | 0X9M3X A05                  | Desktop     | [f049c88dfe](https://linux-hardware.org/?probe=f049c88dfe) | Apr 18, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [170db82573](https://linux-hardware.org/?probe=170db82573) | Apr 18, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [b5c71cfdef](https://linux-hardware.org/?probe=b5c71cfdef) | Apr 18, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [48f584f713](https://linux-hardware.org/?probe=48f584f713) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [69fdb71a72](https://linux-hardware.org/?probe=69fdb71a72) | Apr 16, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [6e722019b4](https://linux-hardware.org/?probe=6e722019b4) | Apr 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [7c4882a4ef](https://linux-hardware.org/?probe=7c4882a4ef) | Apr 16, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [2bc3cb42bb](https://linux-hardware.org/?probe=2bc3cb42bb) | Apr 16, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [4659a757bf](https://linux-hardware.org/?probe=4659a757bf) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [ebfcf670fc](https://linux-hardware.org/?probe=ebfcf670fc) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [568ce07bd0](https://linux-hardware.org/?probe=568ce07bd0) | Apr 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [2b32ed7311](https://linux-hardware.org/?probe=2b32ed7311) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [bbd732b5ca](https://linux-hardware.org/?probe=bbd732b5ca) | Apr 14, 2022 |
| Intel         | S5520UR E22554-752          | Server      | [476430304c](https://linux-hardware.org/?probe=476430304c) | Apr 14, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [930c18b320](https://linux-hardware.org/?probe=930c18b320) | Apr 14, 2022 |
| Dell          | 0H7TGR A00                  | Desktop     | [70bdc97d85](https://linux-hardware.org/?probe=70bdc97d85) | Apr 14, 2022 |
| Dell          | 01J90F A09                  | Server      | [a42e535407](https://linux-hardware.org/?probe=a42e535407) | Apr 14, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [794fbc68d8](https://linux-hardware.org/?probe=794fbc68d8) | Apr 14, 2022 |
| HP            | ProLiant ML330 G6           | Desktop     | [a62736690a](https://linux-hardware.org/?probe=a62736690a) | Apr 14, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [43aa5ccd47](https://linux-hardware.org/?probe=43aa5ccd47) | Apr 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Dell          | Latitude 5590               | Notebook    | [c306b97fcd](https://linux-hardware.org/?probe=c306b97fcd) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | Notebook    | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | Notebook    | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 805D                        | Desktop     | [56634964fb](https://linux-hardware.org/?probe=56634964fb) | Apr 13, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [4c5ccfbe60](https://linux-hardware.org/?probe=4c5ccfbe60) | Apr 12, 2022 |
| Acer          | Aspire Z5801                | All in one  | [b1f38ece1e](https://linux-hardware.org/?probe=b1f38ece1e) | Apr 12, 2022 |
| Lenovo        | ThinkCentre A55 8982A48     | Desktop     | [8de4cd1654](https://linux-hardware.org/?probe=8de4cd1654) | Apr 12, 2022 |
| ASUSTek       | PRIME X299-A                | Desktop     | [3cfaa62e07](https://linux-hardware.org/?probe=3cfaa62e07) | Apr 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [8cdc4f4558](https://linux-hardware.org/?probe=8cdc4f4558) | Apr 10, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [e4fc7cc2cc](https://linux-hardware.org/?probe=e4fc7cc2cc) | Apr 10, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [0d2b6aaa56](https://linux-hardware.org/?probe=0d2b6aaa56) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa7db96c10](https://linux-hardware.org/?probe=aa7db96c10) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [28b5efd5f1](https://linux-hardware.org/?probe=28b5efd5f1) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| ASUSTek       | P8H67-V                     | Desktop     | [a2ae5eb5b9](https://linux-hardware.org/?probe=a2ae5eb5b9) | Apr 09, 2022 |
| ASRock        | X299 Gaming K6              | Desktop     | [86fc074c1f](https://linux-hardware.org/?probe=86fc074c1f) | Apr 09, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [86b82467fd](https://linux-hardware.org/?probe=86b82467fd) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [10458d0000](https://linux-hardware.org/?probe=10458d0000) | Apr 08, 2022 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [8ee23e0e96](https://linux-hardware.org/?probe=8ee23e0e96) | Apr 08, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3524c0ef61](https://linux-hardware.org/?probe=3524c0ef61) | Apr 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [bc01cf4afc](https://linux-hardware.org/?probe=bc01cf4afc) | Apr 05, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | Notebook    | [c8a1f60191](https://linux-hardware.org/?probe=c8a1f60191) | Apr 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [b51d99ad47](https://linux-hardware.org/?probe=b51d99ad47) | Apr 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [e12e7fdd89](https://linux-hardware.org/?probe=e12e7fdd89) | Apr 04, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [ea426eda5e](https://linux-hardware.org/?probe=ea426eda5e) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| MSI           | A88XM-E35 V2                | Desktop     | [2366707e2c](https://linux-hardware.org/?probe=2366707e2c) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c5df2732a7](https://linux-hardware.org/?probe=c5df2732a7) | Apr 02, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [8d14068c4b](https://linux-hardware.org/?probe=8d14068c4b) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3bcc5c9790](https://linux-hardware.org/?probe=3bcc5c9790) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | Notebook    | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [c81e18c0f3](https://linux-hardware.org/?probe=c81e18c0f3) | Apr 01, 2022 |
| Acer          | Aspire Z24-880              | All in one  | [7df055cfac](https://linux-hardware.org/?probe=7df055cfac) | Apr 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [d923ae2736](https://linux-hardware.org/?probe=d923ae2736) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [0e27c2feb0](https://linux-hardware.org/?probe=0e27c2feb0) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d5b2536b95](https://linux-hardware.org/?probe=d5b2536b95) | Mar 30, 2022 |
| Unknown       | Unknown                     | Soc         | [509d960112](https://linux-hardware.org/?probe=509d960112) | Mar 30, 2022 |
| Dell          | Studio 1555                 | Notebook    | [db9f06343c](https://linux-hardware.org/?probe=db9f06343c) | Mar 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| Toshiba       | Satellite Radius L10W-C     | Notebook    | [fc18e171f3](https://linux-hardware.org/?probe=fc18e171f3) | Mar 29, 2022 |
| HP            | Notebook                    | Notebook    | [c53a6a41a2](https://linux-hardware.org/?probe=c53a6a41a2) | Mar 29, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [235c763f19](https://linux-hardware.org/?probe=235c763f19) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [756231c2f0](https://linux-hardware.org/?probe=756231c2f0) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [296d97246f](https://linux-hardware.org/?probe=296d97246f) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1272ec27ff](https://linux-hardware.org/?probe=1272ec27ff) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a9caf3d428](https://linux-hardware.org/?probe=a9caf3d428) | Mar 25, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f3f6025791](https://linux-hardware.org/?probe=f3f6025791) | Mar 25, 2022 |
| ASRock        | B560M-HDV                   | Desktop     | [f54eafc909](https://linux-hardware.org/?probe=f54eafc909) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e7181d25ff](https://linux-hardware.org/?probe=e7181d25ff) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [20f2d24112](https://linux-hardware.org/?probe=20f2d24112) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | Desktop     | [35f8ba571f](https://linux-hardware.org/?probe=35f8ba571f) | Mar 22, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [57038c6fd7](https://linux-hardware.org/?probe=57038c6fd7) | Mar 21, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [f2fb8fc533](https://linux-hardware.org/?probe=f2fb8fc533) | Mar 21, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | Desktop     | [db394898e7](https://linux-hardware.org/?probe=db394898e7) | Mar 20, 2022 |
| HP            | 1906                        | Desktop     | [5a67de9420](https://linux-hardware.org/?probe=5a67de9420) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [fef247389a](https://linux-hardware.org/?probe=fef247389a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7dcf73063d](https://linux-hardware.org/?probe=7dcf73063d) | Mar 19, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7a933d9603](https://linux-hardware.org/?probe=7a933d9603) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [05780b53fa](https://linux-hardware.org/?probe=05780b53fa) | Mar 19, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [77492abdcf](https://linux-hardware.org/?probe=77492abdcf) | Mar 19, 2022 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [4d8ff799cd](https://linux-hardware.org/?probe=4d8ff799cd) | Mar 18, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [191c15c66b](https://linux-hardware.org/?probe=191c15c66b) | Mar 18, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3001c43eca](https://linux-hardware.org/?probe=3001c43eca) | Mar 18, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [207eca584c](https://linux-hardware.org/?probe=207eca584c) | Mar 17, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [34167a6878](https://linux-hardware.org/?probe=34167a6878) | Mar 17, 2022 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [690ba35870](https://linux-hardware.org/?probe=690ba35870) | Mar 17, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [24314627ac](https://linux-hardware.org/?probe=24314627ac) | Mar 16, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [cb51b4388f](https://linux-hardware.org/?probe=cb51b4388f) | Mar 16, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7bdb7d2aeb](https://linux-hardware.org/?probe=7bdb7d2aeb) | Mar 16, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [dceb87e505](https://linux-hardware.org/?probe=dceb87e505) | Mar 16, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [34da0f3cdb](https://linux-hardware.org/?probe=34da0f3cdb) | Mar 16, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [3d7949b20c](https://linux-hardware.org/?probe=3d7949b20c) | Mar 16, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [84c03a7952](https://linux-hardware.org/?probe=84c03a7952) | Mar 16, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f1f12206d5](https://linux-hardware.org/?probe=f1f12206d5) | Mar 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [378424911d](https://linux-hardware.org/?probe=378424911d) | Mar 15, 2022 |
| ASUSTek       | VANGUARD B85                | Desktop     | [26090e1618](https://linux-hardware.org/?probe=26090e1618) | Mar 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2efb1bd4db](https://linux-hardware.org/?probe=2efb1bd4db) | Mar 15, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [0cd9132f27](https://linux-hardware.org/?probe=0cd9132f27) | Mar 14, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [1a1f571027](https://linux-hardware.org/?probe=1a1f571027) | Mar 14, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| Lenovo        | ThinkCentre M71e 3132B7M    | Desktop     | [fe771db462](https://linux-hardware.org/?probe=fe771db462) | Mar 13, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ed5eba97e9](https://linux-hardware.org/?probe=ed5eba97e9) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [ab25401c99](https://linux-hardware.org/?probe=ab25401c99) | Mar 12, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [a93650d1a2](https://linux-hardware.org/?probe=a93650d1a2) | Mar 12, 2022 |
| ASRock        | B560M-HDV                   | Desktop     | [45e9c424b0](https://linux-hardware.org/?probe=45e9c424b0) | Mar 12, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [b8bdf93d55](https://linux-hardware.org/?probe=b8bdf93d55) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [3d2d8b93fe](https://linux-hardware.org/?probe=3d2d8b93fe) | Mar 12, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [36aa2f932e](https://linux-hardware.org/?probe=36aa2f932e) | Mar 12, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| Lenovo        | ThinkPad T480 20L5A07TAU    | Notebook    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [f486888101](https://linux-hardware.org/?probe=f486888101) | Mar 10, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b979165379](https://linux-hardware.org/?probe=b979165379) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [89ef99bd01](https://linux-hardware.org/?probe=89ef99bd01) | Mar 09, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7eea4038f0](https://linux-hardware.org/?probe=7eea4038f0) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fe3e35f15b](https://linux-hardware.org/?probe=fe3e35f15b) | Mar 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [97bb5e5628](https://linux-hardware.org/?probe=97bb5e5628) | Mar 08, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a27291e807](https://linux-hardware.org/?probe=a27291e807) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [5fb0149650](https://linux-hardware.org/?probe=5fb0149650) | Mar 08, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [b227e92b83](https://linux-hardware.org/?probe=b227e92b83) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [ef72c023ac](https://linux-hardware.org/?probe=ef72c023ac) | Mar 07, 2022 |
| Toshiba       | Satellite Radius L10W-C     | Notebook    | [db90921ddd](https://linux-hardware.org/?probe=db90921ddd) | Mar 07, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [c2305ed449](https://linux-hardware.org/?probe=c2305ed449) | Mar 06, 2022 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [87bffb084f](https://linux-hardware.org/?probe=87bffb084f) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2d5c05af33](https://linux-hardware.org/?probe=2d5c05af33) | Mar 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [aff575b483](https://linux-hardware.org/?probe=aff575b483) | Mar 05, 2022 |
| HP            | Notebook                    | Notebook    | [d8b2e4567e](https://linux-hardware.org/?probe=d8b2e4567e) | Mar 05, 2022 |
| HP            | Notebook                    | Notebook    | [cafa2c6f1a](https://linux-hardware.org/?probe=cafa2c6f1a) | Mar 05, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [99effa6921](https://linux-hardware.org/?probe=99effa6921) | Mar 05, 2022 |
| HP            | 2187 A01                    | Desktop     | [fa0949ca91](https://linux-hardware.org/?probe=fa0949ca91) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [98d5649b75](https://linux-hardware.org/?probe=98d5649b75) | Mar 03, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ef4029185f](https://linux-hardware.org/?probe=ef4029185f) | Mar 03, 2022 |
| ASRock        | X470 Gaming K4              | Desktop     | [a5070f4f7a](https://linux-hardware.org/?probe=a5070f4f7a) | Mar 03, 2022 |
| Gigabyte      | B560M GAMING HD             | Desktop     | [e9ed858ae7](https://linux-hardware.org/?probe=e9ed858ae7) | Mar 03, 2022 |
| Acer          | Aspire V3-371               | Notebook    | [038cc99ead](https://linux-hardware.org/?probe=038cc99ead) | Mar 02, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [daef2e33ab](https://linux-hardware.org/?probe=daef2e33ab) | Mar 01, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [7a24cb7e43](https://linux-hardware.org/?probe=7a24cb7e43) | Feb 28, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [0da8223b4e](https://linux-hardware.org/?probe=0da8223b4e) | Feb 28, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [67943c7786](https://linux-hardware.org/?probe=67943c7786) | Feb 27, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [badbd8817c](https://linux-hardware.org/?probe=badbd8817c) | Feb 27, 2022 |
| Acer          | Aspire U5-620               | All in one  | [5114fbe445](https://linux-hardware.org/?probe=5114fbe445) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| Acer          | Aspire U5-620               | All in one  | [271e991a95](https://linux-hardware.org/?probe=271e991a95) | Feb 26, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [678e1eb19b](https://linux-hardware.org/?probe=678e1eb19b) | Feb 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e6ee79f80e](https://linux-hardware.org/?probe=e6ee79f80e) | Feb 25, 2022 |
| HP            | 870C                        | Desktop     | [619268c318](https://linux-hardware.org/?probe=619268c318) | Feb 25, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [7adb11305e](https://linux-hardware.org/?probe=7adb11305e) | Feb 25, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| ASRock        | P55 Pro/USB3                | Desktop     | [a251cf49af](https://linux-hardware.org/?probe=a251cf49af) | Feb 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [1f26dfd88f](https://linux-hardware.org/?probe=1f26dfd88f) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [03aa2b6723](https://linux-hardware.org/?probe=03aa2b6723) | Feb 21, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [c5079e020e](https://linux-hardware.org/?probe=c5079e020e) | Feb 21, 2022 |
| Gigabyte      | EP45-DS4                    | Desktop     | [a679fc7402](https://linux-hardware.org/?probe=a679fc7402) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [8a6f28fc9d](https://linux-hardware.org/?probe=8a6f28fc9d) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b75534890a](https://linux-hardware.org/?probe=b75534890a) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9130546637](https://linux-hardware.org/?probe=9130546637) | Feb 21, 2022 |
| Toshiba       | Satellite Pro C850          | Notebook    | [132557a51b](https://linux-hardware.org/?probe=132557a51b) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [f08a9db4fb](https://linux-hardware.org/?probe=f08a9db4fb) | Feb 20, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [794369f273](https://linux-hardware.org/?probe=794369f273) | Feb 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [70de36a2bb](https://linux-hardware.org/?probe=70de36a2bb) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [50b1c22625](https://linux-hardware.org/?probe=50b1c22625) | Feb 19, 2022 |
| HP            | Notebook                    | Notebook    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | Notebook    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [eb3ca47cd7](https://linux-hardware.org/?probe=eb3ca47cd7) | Feb 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3d816cc71a](https://linux-hardware.org/?probe=3d816cc71a) | Feb 19, 2022 |
| IT Channel... | P95xER                      | Notebook    | [c8add471fb](https://linux-hardware.org/?probe=c8add471fb) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f7e1ab4276](https://linux-hardware.org/?probe=f7e1ab4276) | Feb 18, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [fd7702ea67](https://linux-hardware.org/?probe=fd7702ea67) | Feb 18, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [0747de6777](https://linux-hardware.org/?probe=0747de6777) | Feb 18, 2022 |
| HP            | 0AACh                       | Desktop     | [5a45fe2b9b](https://linux-hardware.org/?probe=5a45fe2b9b) | Feb 18, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [0ef953e74d](https://linux-hardware.org/?probe=0ef953e74d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8791991562](https://linux-hardware.org/?probe=8791991562) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7fa47971c2](https://linux-hardware.org/?probe=7fa47971c2) | Feb 17, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [3e35c49d6c](https://linux-hardware.org/?probe=3e35c49d6c) | Feb 16, 2022 |
| Dell          | Inspiron 7591               | Notebook    | [f5cc709342](https://linux-hardware.org/?probe=f5cc709342) | Feb 16, 2022 |
| ASRock        | Z390 Taichi                 | Desktop     | [6355b5cd92](https://linux-hardware.org/?probe=6355b5cd92) | Feb 15, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [e88fd90806](https://linux-hardware.org/?probe=e88fd90806) | Feb 15, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| ASRock        | B150M Pro4                  | Desktop     | [fc9675169c](https://linux-hardware.org/?probe=fc9675169c) | Feb 14, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [4a5289bfbe](https://linux-hardware.org/?probe=4a5289bfbe) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | Notebook    | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [b34c0f52a5](https://linux-hardware.org/?probe=b34c0f52a5) | Feb 14, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [8731a73bfa](https://linux-hardware.org/?probe=8731a73bfa) | Feb 13, 2022 |
| ASRock        | X299 Taichi                 | Desktop     | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [1e9983d9ed](https://linux-hardware.org/?probe=1e9983d9ed) | Feb 13, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [d1d9e8d131](https://linux-hardware.org/?probe=d1d9e8d131) | Feb 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [5b1d12de98](https://linux-hardware.org/?probe=5b1d12de98) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | Notebook    | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [a1e2d401fe](https://linux-hardware.org/?probe=a1e2d401fe) | Feb 13, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [879dbc6171](https://linux-hardware.org/?probe=879dbc6171) | Feb 12, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [600104b8e2](https://linux-hardware.org/?probe=600104b8e2) | Feb 12, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9aabe7c08f](https://linux-hardware.org/?probe=9aabe7c08f) | Feb 12, 2022 |
| Dell          | 0PC5F7 A00                  | Desktop     | [db9f96cef3](https://linux-hardware.org/?probe=db9f96cef3) | Feb 12, 2022 |
| Dell          | 05YDCW A01                  | Desktop     | [569f5a48d8](https://linux-hardware.org/?probe=569f5a48d8) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [9ce361abd3](https://linux-hardware.org/?probe=9ce361abd3) | Feb 12, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [3d9251af74](https://linux-hardware.org/?probe=3d9251af74) | Feb 11, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [f92c7dd18b](https://linux-hardware.org/?probe=f92c7dd18b) | Feb 11, 2022 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [64281aefaa](https://linux-hardware.org/?probe=64281aefaa) | Feb 11, 2022 |
| ASRock        | J4125-ITX                   | Desktop     | [bea5cd5426](https://linux-hardware.org/?probe=bea5cd5426) | Feb 11, 2022 |
| Samsung       | 700T                        | Notebook    | [076ad3b906](https://linux-hardware.org/?probe=076ad3b906) | Feb 11, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fc3d05ce13](https://linux-hardware.org/?probe=fc3d05ce13) | Feb 11, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [e6ca2fb62e](https://linux-hardware.org/?probe=e6ca2fb62e) | Feb 10, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [ac4b2855c6](https://linux-hardware.org/?probe=ac4b2855c6) | Feb 10, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [3c75fd14fb](https://linux-hardware.org/?probe=3c75fd14fb) | Feb 09, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [87d3fd2916](https://linux-hardware.org/?probe=87d3fd2916) | Feb 09, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [48bdfd6acb](https://linux-hardware.org/?probe=48bdfd6acb) | Feb 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [f4c4b60509](https://linux-hardware.org/?probe=f4c4b60509) | Feb 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [efb945cc4f](https://linux-hardware.org/?probe=efb945cc4f) | Feb 09, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [2f6df3fff6](https://linux-hardware.org/?probe=2f6df3fff6) | Feb 09, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [933f07a2d6](https://linux-hardware.org/?probe=933f07a2d6) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [59c28827db](https://linux-hardware.org/?probe=59c28827db) | Feb 08, 2022 |
| HP            | 3395                        | All in one  | [7814e00461](https://linux-hardware.org/?probe=7814e00461) | Feb 08, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [9670ac12a4](https://linux-hardware.org/?probe=9670ac12a4) | Feb 08, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [fe65919edc](https://linux-hardware.org/?probe=fe65919edc) | Feb 08, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [d0f48fef55](https://linux-hardware.org/?probe=d0f48fef55) | Feb 08, 2022 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [43af5ac17f](https://linux-hardware.org/?probe=43af5ac17f) | Feb 08, 2022 |
| ASUSTek       | G20CB                       | Desktop     | [ea2e422fb5](https://linux-hardware.org/?probe=ea2e422fb5) | Feb 08, 2022 |
| Samsung       | R580                        | Notebook    | [f822930ecf](https://linux-hardware.org/?probe=f822930ecf) | Feb 08, 2022 |
| MSI           | A88XM-E35 V2                | Desktop     | [ef9a71e704](https://linux-hardware.org/?probe=ef9a71e704) | Feb 08, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [7135f3c638](https://linux-hardware.org/?probe=7135f3c638) | Feb 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [d6aefe2df6](https://linux-hardware.org/?probe=d6aefe2df6) | Feb 07, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | Notebook    | [1110112a7f](https://linux-hardware.org/?probe=1110112a7f) | Feb 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [e53bcff920](https://linux-hardware.org/?probe=e53bcff920) | Feb 06, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [148979565d](https://linux-hardware.org/?probe=148979565d) | Feb 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [97911feaef](https://linux-hardware.org/?probe=97911feaef) | Feb 06, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [2b0f2f8139](https://linux-hardware.org/?probe=2b0f2f8139) | Feb 06, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [a17e7fe261](https://linux-hardware.org/?probe=a17e7fe261) | Feb 06, 2022 |
| Dell          | 0DN075                      | Desktop     | [eb385877ae](https://linux-hardware.org/?probe=eb385877ae) | Feb 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [08962dc9f9](https://linux-hardware.org/?probe=08962dc9f9) | Feb 05, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8853c3aff1](https://linux-hardware.org/?probe=8853c3aff1) | Feb 05, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [6f0d26a803](https://linux-hardware.org/?probe=6f0d26a803) | Feb 05, 2022 |
| HP            | 339A                        | Desktop     | [2a3e077d71](https://linux-hardware.org/?probe=2a3e077d71) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| Biostar       | A320MH                      | Desktop     | [e024e56329](https://linux-hardware.org/?probe=e024e56329) | Feb 05, 2022 |
| Biostar       | A320MH                      | Desktop     | [9bf3504bc1](https://linux-hardware.org/?probe=9bf3504bc1) | Feb 05, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36bac5a046](https://linux-hardware.org/?probe=36bac5a046) | Feb 04, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [872772f278](https://linux-hardware.org/?probe=872772f278) | Feb 04, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [4df88dcf23](https://linux-hardware.org/?probe=4df88dcf23) | Feb 03, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [f4a6341837](https://linux-hardware.org/?probe=f4a6341837) | Feb 03, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [83678f76fc](https://linux-hardware.org/?probe=83678f76fc) | Feb 03, 2022 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [f49f0801c0](https://linux-hardware.org/?probe=f49f0801c0) | Feb 03, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [02e5c56a80](https://linux-hardware.org/?probe=02e5c56a80) | Feb 03, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [4aa06b4edd](https://linux-hardware.org/?probe=4aa06b4edd) | Feb 03, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [2403a2d0f9](https://linux-hardware.org/?probe=2403a2d0f9) | Feb 02, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [6075abc821](https://linux-hardware.org/?probe=6075abc821) | Feb 02, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [34cd69898b](https://linux-hardware.org/?probe=34cd69898b) | Feb 02, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [1de51c3e3b](https://linux-hardware.org/?probe=1de51c3e3b) | Feb 01, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4b00e6b290](https://linux-hardware.org/?probe=4b00e6b290) | Feb 01, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c29b15a852](https://linux-hardware.org/?probe=c29b15a852) | Feb 01, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e6dfa0f8ec](https://linux-hardware.org/?probe=e6dfa0f8ec) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [b08503a021](https://linux-hardware.org/?probe=b08503a021) | Feb 01, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [e8acac784c](https://linux-hardware.org/?probe=e8acac784c) | Jan 31, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [33a9d5357e](https://linux-hardware.org/?probe=33a9d5357e) | Jan 31, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5d06ba826f](https://linux-hardware.org/?probe=5d06ba826f) | Jan 31, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 417       | 14.99%  |
| Ubuntu 18.04      | 171       | 6.15%   |
| KDE neon 20.04    | 70        | 2.52%   |
| Debian 11         | 68        | 2.45%   |
| Pop!_OS 21.04     | 64        | 2.3%    |
| OpenMandriva 4.3  | 64        | 2.3%    |
| Ubuntu 22.04      | 60        | 2.16%   |
| OpenMandriva 4.2  | 56        | 2.01%   |
| Linux Mint 20.3   | 54        | 1.94%   |
| Pop!_OS 20.04     | 50        | 1.8%    |
| Fedora 36         | 49        | 1.76%   |
| Pop!_OS 20.10     | 48        | 1.73%   |
| Ubuntu 21.10      | 46        | 1.65%   |
| Linux Mint 20.2   | 46        | 1.65%   |
| Zorin 16          | 44        | 1.58%   |
| Pop!_OS 22.04     | 44        | 1.58%   |
| Arch              | 44        | 1.58%   |
| Linux Mint 20.1   | 42        | 1.51%   |
| Fedora 35         | 42        | 1.51%   |
| Ubuntu 19.04      | 41        | 1.47%   |
| Fedora 33         | 41        | 1.47%   |
| Ubuntu 20.10      | 39        | 1.4%    |
| Fedora 34         | 38        | 1.37%   |
| Ubuntu 21.04      | 37        | 1.33%   |
| Ubuntu 19.10      | 37        | 1.33%   |
| Manjaro           | 37        | 1.33%   |
| Arch Rolling      | 36        | 1.29%   |
| Linux Mint 19.3   | 34        | 1.22%   |
| Linux Mint 20     | 32        | 1.15%   |
| Pop!_OS 21.10     | 30        | 1.08%   |
| ArcoLinux Rolling | 30        | 1.08%   |
| Fedora 32         | 29        | 1.04%   |
| Xubuntu 20.04     | 28        | 1.01%   |
| Xubuntu 18.04     | 28        | 1.01%   |
| Ubuntu 18.10      | 26        | 0.93%   |
| Zorin 15          | 24        | 0.86%   |
| ClearOS 7         | 23        | 0.83%   |
| Debian 10         | 21        | 0.76%   |
| Fedora 31         | 19        | 0.68%   |
| Kubuntu 20.04     | 17        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 843       | 32.32%  |
| Linux Mint    | 232       | 8.9%    |
| Pop!_OS       | 223       | 8.55%   |
| Fedora        | 183       | 7.02%   |
| OpenMandriva  | 137       | 5.25%   |
| Debian        | 115       | 4.41%   |
| Manjaro       | 81        | 3.11%   |
| KDE neon      | 80        | 3.07%   |
| Arch          | 80        | 3.07%   |
| Zorin         | 77        | 2.95%   |
| Xubuntu       | 75        | 2.88%   |
| Kubuntu       | 51        | 1.96%   |
| ArcoLinux     | 31        | 1.19%   |
| Elementary    | 29        | 1.11%   |
| ROSA          | 28        | 1.07%   |
| Gentoo        | 23        | 0.88%   |
| ClearOS       | 23        | 0.88%   |
| Clear Linux   | 22        | 0.84%   |
| Ubuntu MATE   | 21        | 0.81%   |
| Kali          | 21        | 0.81%   |
| openSUSE      | 19        | 0.73%   |
| Lubuntu       | 18        | 0.69%   |
| Endless       | 17        | 0.65%   |
| BlackPanther  | 17        | 0.65%   |
| EndeavourOS   | 13        | 0.5%    |
| Ubuntu Unity  | 12        | 0.46%   |
| LMDE          | 12        | 0.46%   |
| CentOS        | 10        | 0.38%   |
| Ubuntu Budgie | 8         | 0.31%   |
| Raspbian      | 7         | 0.27%   |
| MX            | 7         | 0.27%   |
| LinuxFX       | 7         | 0.27%   |
| Feren OS      | 7         | 0.27%   |
| Reborn OS     | 6         | 0.23%   |
| Parrot        | 6         | 0.23%   |
| Solus         | 5         | 0.19%   |
| Manjaro-ARM   | 5         | 0.19%   |
| Rocky Linux   | 4         | 0.15%   |
| Garuda Linux  | 4         | 0.15%   |
| Ubuntu Studio | 3         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.4.0-42-generic          | 64        | 1.98%   |
| 5.16.7-desktop-1omv4003   | 61        | 1.89%   |
| 5.10.14-desktop-1omv4002  | 52        | 1.61%   |
| 5.4.0-40-generic          | 30        | 0.93%   |
| 5.11.0-7620-generic       | 30        | 0.93%   |
| 5.4.0-58-generic          | 29        | 0.9%    |
| 5.4.0-48-generic          | 27        | 0.84%   |
| 5.4.0-26-generic          | 24        | 0.74%   |
| 5.3.0-46-generic          | 24        | 0.74%   |
| 5.4.0-52-generic          | 23        | 0.71%   |
| 5.11.0-37-generic         | 23        | 0.71%   |
| 5.4.0-29-generic          | 22        | 0.68%   |
| 5.3.0-40-generic          | 22        | 0.68%   |
| 5.3.0-28-generic          | 22        | 0.68%   |
| 5.17.5-76051705-generic   | 21        | 0.65%   |
| 5.4.0-7634-generic        | 19        | 0.59%   |
| 5.11.0-27-generic         | 19        | 0.59%   |
| 5.4.0-47-generic          | 18        | 0.56%   |
| 5.4.0-74-generic          | 17        | 0.53%   |
| 5.15.0-46-generic         | 17        | 0.53%   |
| 5.13.0-7620-generic       | 17        | 0.53%   |
| 5.8.0-7630-generic        | 16        | 0.5%    |
| 5.8.0-44-generic          | 16        | 0.5%    |
| 5.4.0-65-generic          | 16        | 0.5%    |
| 5.13.0-40-generic         | 16        | 0.5%    |
| 4.15.0-99-generic         | 16        | 0.5%    |
| 5.8.0-7642-generic        | 15        | 0.46%   |
| 5.8.0-63-generic          | 15        | 0.46%   |
| 5.4.0-91-generic          | 15        | 0.46%   |
| 5.4.0-66-generic          | 15        | 0.46%   |
| 5.4.0-54-generic          | 15        | 0.46%   |
| 5.8.0-55-generic          | 14        | 0.43%   |
| 5.8.0-50-generic          | 14        | 0.43%   |
| 5.4.0-7642-generic        | 14        | 0.43%   |
| 5.13.0-39-generic         | 14        | 0.43%   |
| 5.13.0-30-generic         | 14        | 0.43%   |
| 5.11.0-34-generic         | 14        | 0.43%   |
| 5.11.0-25-generic         | 14        | 0.43%   |
| 5.0.0-13-generic          | 14        | 0.43%   |
| 3.10.0-862.11.6.v7.x86_64 | 14        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 544       | 18.37%  |
| 5.11.0  | 227       | 7.66%   |
| 5.13.0  | 183       | 6.18%   |
| 5.8.0   | 180       | 6.08%   |
| 4.15.0  | 158       | 5.33%   |
| 5.3.0   | 128       | 4.32%   |
| 5.15.0  | 109       | 3.68%   |
| 5.0.0   | 86        | 2.9%    |
| 5.10.0  | 70        | 2.36%   |
| 5.16.7  | 62        | 2.09%   |
| 4.18.0  | 60        | 2.03%   |
| 5.10.14 | 52        | 1.76%   |
| 4.19.0  | 35        | 1.18%   |
| 5.17.5  | 30        | 1.01%   |
| 3.10.0  | 29        | 0.98%   |
| 5.16.11 | 14        | 0.47%   |
| 5.19.0  | 13        | 0.44%   |
| 5.16.0  | 13        | 0.44%   |
| 4.4.0   | 12        | 0.41%   |
| 5.18.10 | 11        | 0.37%   |
| 5.17.0  | 11        | 0.37%   |
| 5.9.16  | 10        | 0.34%   |
| 5.6.14  | 10        | 0.34%   |
| 5.18.0  | 10        | 0.34%   |
| 5.15.11 | 10        | 0.34%   |
| 5.14.0  | 10        | 0.34%   |
| 5.13.13 | 10        | 0.34%   |
| 5.11.12 | 10        | 0.34%   |
| 4.9.60  | 10        | 0.34%   |
| 5.18.12 | 9         | 0.3%    |
| 5.16.19 | 9         | 0.3%    |
| 5.13.12 | 9         | 0.3%    |
| 5.12.4  | 9         | 0.3%    |
| 4.18.16 | 9         | 0.3%    |
| 5.8.16  | 8         | 0.27%   |
| 5.7.0   | 8         | 0.27%   |
| 5.6.6   | 8         | 0.27%   |
| 5.3.18  | 8         | 0.27%   |
| 5.17.15 | 8         | 0.27%   |
| 5.12.8  | 8         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 594       | 20.63%  |
| 5.11    | 266       | 9.24%   |
| 5.13    | 229       | 7.95%   |
| 5.8     | 227       | 7.88%   |
| 5.15    | 192       | 6.67%   |
| 5.10    | 183       | 6.35%   |
| 4.15    | 158       | 5.49%   |
| 5.3     | 143       | 4.97%   |
| 5.16    | 143       | 4.97%   |
| 5.0     | 95        | 3.3%    |
| 5.17    | 82        | 2.85%   |
| 4.18    | 71        | 2.47%   |
| 5.18    | 69        | 2.4%    |
| 5.12    | 46        | 1.6%    |
| 5.6     | 45        | 1.56%   |
| 4.19    | 45        | 1.56%   |
| 5.14    | 41        | 1.42%   |
| 5.9     | 38        | 1.32%   |
| 5.19    | 37        | 1.28%   |
| 4.9     | 30        | 1.04%   |
| 3.10    | 29        | 1.01%   |
| 5.5     | 26        | 0.9%    |
| 5.7     | 25        | 0.87%   |
| 5.2     | 17        | 0.59%   |
| 4.4     | 13        | 0.45%   |
| 5.1     | 9         | 0.31%   |
| 6.0     | 4         | 0.14%   |
| 4.1     | 4         | 0.14%   |
| 4.20    | 3         | 0.1%    |
| 4.14    | 3         | 0.1%    |
| 4.13    | 3         | 0.1%    |
| 3.16    | 2         | 0.07%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |
| 3.9     | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2400      | 96.42%  |
| i686    | 46        | 1.85%   |
| aarch64 | 28        | 1.12%   |
| armv7l  | 11        | 0.44%   |
| i586    | 2         | 0.08%   |
| riscv64 | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1160      | 44.07%  |
| Unknown         | 357       | 13.56%  |
| KDE5            | 353       | 13.41%  |
| X-Cinnamon      | 196       | 7.45%   |
| XFCE            | 182       | 6.91%   |
| KDE             | 100       | 3.8%    |
| MATE            | 70        | 2.66%   |
| Cinnamon        | 47        | 1.79%   |
| Pantheon        | 27        | 1.03%   |
| LXQt            | 20        | 0.76%   |
| KDE4            | 18        | 0.68%   |
| Unity           | 17        | 0.65%   |
| LXDE            | 16        | 0.61%   |
| Budgie          | 16        | 0.61%   |
| i3              | 12        | 0.46%   |
| Deepin          | 7         | 0.27%   |
| awesome         | 7         | 0.27%   |
| Openbox         | 5         | 0.19%   |
| GNOME Flashback | 4         | 0.15%   |
| GNOME Classic   | 4         | 0.15%   |
| xmonad          | 3         | 0.11%   |
| qtile           | 2         | 0.08%   |
| Trinity         | 1         | 0.04%   |
| sway            | 1         | 0.04%   |
| pop             | 1         | 0.04%   |
| Phosh:GNOME     | 1         | 0.04%   |
| icewm           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |
| DWM             | 1         | 0.04%   |
| dusk            | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2037      | 79.14%  |
| Wayland | 285       | 11.07%  |
| Unknown | 160       | 6.22%   |
| Tty     | 91        | 3.54%   |
| Web     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1489      | 57.6%   |
| SDDM    | 312       | 12.07%  |
| GDM     | 278       | 10.75%  |
| LightDM | 223       | 8.63%   |
| GDM3    | 163       | 6.31%   |
| TDM     | 85        | 3.29%   |
| KDM     | 17        | 0.66%   |
| SLiM    | 6         | 0.23%   |
| LXDM    | 5         | 0.19%   |
| XDM     | 4         | 0.15%   |
| Ly      | 2         | 0.08%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_AU   | 1819      | 70.75%  |
| en_US   | 340       | 13.22%  |
| Unknown | 317       | 12.33%  |
| C       | 57        | 2.22%   |
| en_GB   | 27        | 1.05%   |
| C.UTF8  | 3         | 0.12%   |
| zh_CN   | 2         | 0.08%   |
| ru_RU   | 1         | 0.04%   |
| POSIX   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_CA   | 1         | 0.04%   |
| de_DE   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1353      | 53.23%  |
| EFI  | 1189      | 46.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1958      | 76.66%  |
| Btrfs   | 194       | 7.6%    |
| Overlay | 177       | 6.93%   |
| Unknown | 100       | 3.92%   |
| Xfs     | 70        | 2.74%   |
| Zfs     | 34        | 1.33%   |
| Ext2    | 8         | 0.31%   |
| Ext3    | 5         | 0.2%    |
| Tmpfs   | 4         | 0.16%   |
| XXXXXXX | 1         | 0.04%   |
| Jfs     | 1         | 0.04%   |
| F2fs    | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1570      | 61.86%  |
| GPT     | 703       | 27.7%   |
| MBR     | 265       | 10.44%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2145      | 84.42%  |
| Yes       | 396       | 15.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1862      | 73.34%  |
| Yes       | 677       | 26.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 364       | 14.66%  |
| Hewlett-Packard         | 332       | 13.37%  |
| Dell                    | 324       | 13.05%  |
| Gigabyte Technology     | 315       | 12.69%  |
| Lenovo                  | 254       | 10.23%  |
| MSI                     | 148       | 5.96%   |
| Acer                    | 127       | 5.11%   |
| ASRock                  | 101       | 4.07%   |
| Apple                   | 96        | 3.87%   |
| Toshiba                 | 89        | 3.58%   |
| Intel                   | 71        | 2.86%   |
| Raspberry Pi Foundation | 26        | 1.05%   |
| Microsoft               | 25        | 1.01%   |
| Alienware               | 19        | 0.77%   |
| Unknown                 | 15        | 0.6%    |
| Samsung Electronics     | 12        | 0.48%   |
| Sony                    | 10        | 0.4%    |
| Notebook                | 9         | 0.36%   |
| Timi                    | 8         | 0.32%   |
| AMI                     | 8         | 0.32%   |
| Pegatron                | 7         | 0.28%   |
| Medion                  | 7         | 0.28%   |
| IT Channel Pty          | 7         | 0.28%   |
| Metabox                 | 6         | 0.24%   |
| Google                  | 6         | 0.24%   |
| Supermicro              | 5         | 0.2%    |
| Pine Microsystems       | 5         | 0.2%    |
| Panasonic               | 5         | 0.2%    |
| Kogan                   | 5         | 0.2%    |
| HUAWEI                  | 5         | 0.2%    |
| ECS                     | 5         | 0.2%    |
| System76                | 4         | 0.16%   |
| Razer                   | 4         | 0.16%   |
| IBM                     | 4         | 0.16%   |
| Hardkernel              | 4         | 0.16%   |
| Shuttle                 | 3         | 0.12%   |
| LG Electronics          | 3         | 0.12%   |
| IP3 Tech                | 2         | 0.08%   |
| Intel Client Systems    | 2         | 0.08%   |
| Framework               | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 27        | 1.09%   |
| Dell OptiPlex 9020           | 21        | 0.85%   |
| Unknown                      | 19        | 0.77%   |
| HP Pavilion dv6              | 14        | 0.56%   |
| HP Pavilion g6               | 11        | 0.44%   |
| RPi Raspberry Pi             | 10        | 0.4%    |
| Gigabyte 970A-D3P            | 10        | 0.4%    |
| MSI MS-7B89                  | 8         | 0.32%   |
| HP Pavilion 15               | 8         | 0.32%   |
| HP Notebook                  | 8         | 0.32%   |
| Apple iMac12,2               | 8         | 0.32%   |
| MSI MS-7817                  | 7         | 0.28%   |
| Dell OptiPlex 780            | 7         | 0.28%   |
| Apple MacBookPro9,2          | 7         | 0.28%   |
| MSI MS-7C84                  | 6         | 0.24%   |
| Gigabyte X58A-UD3R           | 6         | 0.24%   |
| Dell OptiPlex 9010           | 6         | 0.24%   |
| Apple MacBookPro10,1         | 6         | 0.24%   |
| Acer ConceptD CN315-71P      | 6         | 0.24%   |
| MSI MS-7C37                  | 5         | 0.2%    |
| Gigabyte X570 AORUS PRO WIFI | 5         | 0.2%    |
| Gigabyte GA-870A-UD3         | 5         | 0.2%    |
| Gigabyte B75M-D3H            | 5         | 0.2%    |
| Dell XPS 15 9560             | 5         | 0.2%    |
| Dell OptiPlex 3010           | 5         | 0.2%    |
| ASUS ROG CROSSHAIR VIII HERO | 5         | 0.2%    |
| Apple MacBookPro8,1          | 5         | 0.2%    |
| Acer Aspire 5750G            | 5         | 0.2%    |
| Toshiba Satellite P750       | 4         | 0.16%   |
| Toshiba Satellite L850       | 4         | 0.16%   |
| Toshiba Satellite L500       | 4         | 0.16%   |
| Toshiba Satellite L50-A      | 4         | 0.16%   |
| MSI MS-7C02                  | 4         | 0.16%   |
| MSI MS-7A38                  | 4         | 0.16%   |
| MSI MS-7A37                  | 4         | 0.16%   |
| Microsoft Surface Book 2     | 4         | 0.16%   |
| Lenovo G50-45 80E3           | 4         | 0.16%   |
| HP ProDesk 600 G2 SFF        | 4         | 0.16%   |
| HP Pavilion x360 Convertible | 4         | 0.16%   |
| HP EliteBook x360 1030 G2    | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 119       | 4.79%   |
| Acer Aspire            | 88        | 3.54%   |
| Dell OptiPlex          | 78        | 3.14%   |
| Toshiba Satellite      | 72        | 2.9%    |
| HP Pavilion            | 71        | 2.86%   |
| Dell Latitude          | 65        | 2.62%   |
| Dell Inspiron          | 64        | 2.58%   |
| ASUS PRIME             | 50        | 2.01%   |
| Dell XPS               | 48        | 1.93%   |
| ASUS ROG               | 46        | 1.85%   |
| HP EliteBook           | 43        | 1.73%   |
| HP Compaq              | 36        | 1.45%   |
| Dell Precision         | 34        | 1.37%   |
| Lenovo Yoga            | 28        | 1.13%   |
| Lenovo ThinkCentre     | 28        | 1.13%   |
| Lenovo IdeaPad         | 28        | 1.13%   |
| ASUS All               | 27        | 1.09%   |
| RPi Raspberry          | 26        | 1.05%   |
| Microsoft Surface      | 25        | 1.01%   |
| HP ProBook             | 24        | 0.97%   |
| ASUS TUF               | 23        | 0.93%   |
| HP ENVY                | 19        | 0.77%   |
| Unknown                | 19        | 0.77%   |
| Gigabyte X570          | 18        | 0.72%   |
| HP Laptop              | 17        | 0.68%   |
| Gigabyte B450          | 13        | 0.52%   |
| Dell Vostro            | 13        | 0.52%   |
| Gigabyte B450M         | 12        | 0.48%   |
| HP ProDesk             | 10        | 0.4%    |
| Gigabyte 970A-D3P      | 10        | 0.4%    |
| ASUS ZenBook           | 10        | 0.4%    |
| Apple MacBookPro10     | 9         | 0.36%   |
| Acer Swift             | 9         | 0.36%   |
| Toshiba PORTEGE        | 8         | 0.32%   |
| MSI MS-7B89            | 8         | 0.32%   |
| HP Spectre             | 8         | 0.32%   |
| HP Notebook            | 8         | 0.32%   |
| HP 250                 | 8         | 0.32%   |
| Gigabyte GA-78LMT-USB3 | 8         | 0.32%   |
| Apple MacBookPro9      | 8         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 242       | 9.75%   |
| 2019    | 240       | 9.67%   |
| 2020    | 205       | 8.26%   |
| 2012    | 202       | 8.14%   |
| 2013    | 192       | 7.73%   |
| 2011    | 187       | 7.53%   |
| 2017    | 178       | 7.17%   |
| 2014    | 158       | 6.36%   |
| 2016    | 140       | 5.64%   |
| 2010    | 135       | 5.44%   |
| 2015    | 129       | 5.2%    |
| 2021    | 120       | 4.83%   |
| 2009    | 105       | 4.23%   |
| 2008    | 103       | 4.15%   |
| 2007    | 49        | 1.97%   |
| Unknown | 38        | 1.53%   |
| 2022    | 27        | 1.09%   |
| 2006    | 19        | 0.77%   |
| 2005    | 10        | 0.4%    |
| 2004    | 2         | 0.08%   |
| 2003    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1127      | 45.39%  |
| Notebook       | 1068      | 43.01%  |
| Convertible    | 80        | 3.22%   |
| All in one     | 60        | 2.42%   |
| Mini pc        | 52        | 2.09%   |
| Tablet         | 38        | 1.53%   |
| System on chip | 33        | 1.33%   |
| Server         | 20        | 0.81%   |
| Phone          | 3         | 0.12%   |
| Stick pc       | 2         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2300      | 92.15%  |
| Enabled  | 196       | 7.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2473      | 99.6%   |
| Yes  | 10        | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 622       | 24.47%  |
| 4.01-8.0        | 512       | 20.14%  |
| 8.01-16.0       | 431       | 16.96%  |
| 3.01-4.0        | 428       | 16.84%  |
| 32.01-64.0      | 301       | 11.84%  |
| 1.01-2.0        | 93        | 3.66%   |
| 64.01-256.0     | 77        | 3.03%   |
| 24.01-32.0      | 40        | 1.57%   |
| 2.01-3.0        | 17        | 0.67%   |
| 0.51-1.0        | 12        | 0.47%   |
| 0.01-0.5        | 6         | 0.24%   |
| More than 256.0 | 2         | 0.08%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 986       | 34.62%  |
| 2.01-3.0    | 706       | 24.79%  |
| 4.01-8.0    | 391       | 13.73%  |
| 3.01-4.0    | 351       | 12.32%  |
| 0.51-1.0    | 209       | 7.34%   |
| 8.01-16.0   | 131       | 4.6%    |
| 0.01-0.5    | 42        | 1.47%   |
| 16.01-24.0  | 20        | 0.7%    |
| 24.01-32.0  | 6         | 0.21%   |
| 64.01-256.0 | 2         | 0.07%   |
| 0           | 2         | 0.07%   |
| Unknown     | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1420      | 54.2%   |
| 2       | 610       | 23.28%  |
| 3       | 263       | 10.04%  |
| 4       | 149       | 5.69%   |
| 5       | 68        | 2.6%    |
| 6       | 36        | 1.37%   |
| 0       | 28        | 1.07%   |
| 7       | 19        | 0.73%   |
| 8       | 13        | 0.5%    |
| 9       | 5         | 0.19%   |
| 10      | 3         | 0.11%   |
| 13      | 2         | 0.08%   |
| 36      | 1         | 0.04%   |
| 14      | 1         | 0.04%   |
| 11      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1467      | 58.35%  |
| Yes       | 1047      | 41.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2173      | 87.34%  |
| No        | 315       | 12.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1820      | 72.45%  |
| No        | 692       | 27.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1392      | 55.15%  |
| No        | 1132      | 44.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 2483      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 699       | 26.15%  |
| Melbourne      | 493       | 18.44%  |
| Brisbane       | 374       | 13.99%  |
| Perth          | 223       | 8.34%   |
| Adelaide       | 161       | 6.02%   |
| Canberra       | 54        | 2.02%   |
| Wahroonga      | 39        | 1.46%   |
| Hobart         | 28        | 1.05%   |
| Launceston     | 21        | 0.79%   |
| Alexandria     | 19        | 0.71%   |
| Surry Hills    | 17        | 0.64%   |
| Gold Coast     | 11        | 0.41%   |
| Geelong        | 11        | 0.41%   |
| Woolloongabba  | 10        | 0.37%   |
| Mitcham        | 10        | 0.37%   |
| Lane Cove      | 10        | 0.37%   |
| Richmond       | 9         | 0.34%   |
| Newcastle      | 9         | 0.34%   |
| Brighton       | 9         | 0.34%   |
| Traralgon      | 8         | 0.3%    |
| Central Coast  | 8         | 0.3%    |
| Townsville     | 7         | 0.26%   |
| Southport      | 7         | 0.26%   |
| Parramatta     | 7         | 0.26%   |
| Artarmon       | 7         | 0.26%   |
| Wollongong     | 6         | 0.22%   |
| West End       | 6         | 0.22%   |
| Point Cook     | 6         | 0.22%   |
| North Sydney   | 6         | 0.22%   |
| Mount Waverley | 6         | 0.22%   |
| Macquarie Park | 6         | 0.22%   |
| Spring Field   | 5         | 0.19%   |
| Ringwood East  | 5         | 0.19%   |
| Northcote      | 5         | 0.19%   |
| Mascot         | 5         | 0.19%   |
| Mandurah       | 5         | 0.19%   |
| Doncaster      | 5         | 0.19%   |
| Clifton Hill   | 5         | 0.19%   |
| Buderim        | 5         | 0.19%   |
| Brownlow Hill  | 5         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 702       | 1242   | 18.49%  |
| Seagate                   | 668       | 1272   | 17.6%   |
| WDC                       | 613       | 1159   | 16.15%  |
| Toshiba                   | 202       | 289    | 5.32%   |
| Crucial                   | 189       | 282    | 4.98%   |
| Kingston                  | 171       | 224    | 4.5%    |
| Intel                     | 144       | 255    | 3.79%   |
| SanDisk                   | 143       | 188    | 3.77%   |
| Unknown                   | 142       | 215    | 3.74%   |
| Hitachi                   | 130       | 206    | 3.42%   |
| SK hynix                  | 77        | 92     | 2.03%   |
| HGST                      | 61        | 88     | 1.61%   |
| Apple                     | 53        | 69     | 1.4%    |
| Micron Technology         | 44        | 56     | 1.16%   |
| Phison                    | 33        | 51     | 0.87%   |
| Micron/Crucial Technology | 28        | 41     | 0.74%   |
| OCZ                       | 27        | 41     | 0.71%   |
| A-DATA Technology         | 26        | 35     | 0.68%   |
| KIOXIA                    | 24        | 26     | 0.63%   |
| SPCC                      | 20        | 26     | 0.53%   |
| Corsair                   | 17        | 29     | 0.45%   |
| LITEON                    | 16        | 24     | 0.42%   |
| LITEONIT                  | 14        | 19     | 0.37%   |
| JMicron Technology        | 14        | 17     | 0.37%   |
| KingSpec                  | 13        | 28     | 0.34%   |
| Fujitsu                   | 13        | 17     | 0.34%   |
| Transcend                 | 11        | 17     | 0.29%   |
| Patriot                   | 11        | 16     | 0.29%   |
| LaCie                     | 11        | 18     | 0.29%   |
| Maxtor                    | 9         | 11     | 0.24%   |
| Gigabyte Technology       | 9         | 12     | 0.24%   |
| ASMT                      | 9         | 15     | 0.24%   |
| Hewlett-Packard           | 8         | 12     | 0.21%   |
| Unknown                   | 8         | 9      | 0.21%   |
| Silicon Motion            | 7         | 17     | 0.18%   |
| Realtek Semiconductor     | 7         | 9      | 0.18%   |
| China                     | 7         | 9      | 0.18%   |
| XPG                       | 6         | 7      | 0.16%   |
| TO Exter                  | 6         | 6      | 0.16%   |
| OWC                       | 6         | 12     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 50        | 1.14%   |
| Samsung SSD 850 EVO 250GB          | 40        | 0.91%   |
| Unknown MMC Card  32GB             | 33        | 0.75%   |
| Samsung NVMe SSD Drive 1TB         | 32        | 0.73%   |
| Seagate Expansion Desk 2TB         | 30        | 0.68%   |
| Seagate ST500DM002-1BD142 500GB    | 29        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB     | 29        | 0.66%   |
| Samsung SSD 850 EVO 500GB          | 29        | 0.66%   |
| Crucial CT240BX500SSD1 240GB       | 29        | 0.66%   |
| Samsung NVMe SSD Drive 512GB       | 28        | 0.64%   |
| Samsung NVMe SSD Drive 500GB       | 28        | 0.64%   |
| Unknown MMC Card  64GB             | 26        | 0.59%   |
| Seagate ST4000DM004-2CV104 4TB     | 25        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB     | 25        | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB     | 25        | 0.57%   |
| Seagate Expansion 1TB              | 25        | 0.57%   |
| Seagate ST3500418AS 500GB          | 22        | 0.5%    |
| Seagate ST2000DM001-1CH164 2TB     | 22        | 0.5%    |
| Samsung SSD 860 EVO 1TB            | 22        | 0.5%    |
| Samsung NVMe SSD Drive 256GB       | 22        | 0.5%    |
| Crucial CT480BX500SSD1 480GB       | 22        | 0.5%    |
| Crucial CT500MX500SSD1 500GB       | 21        | 0.48%   |
| Toshiba MQ01ABD100 1TB             | 20        | 0.45%   |
| Kingston SA400S37240G 240GB SSD    | 20        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD   | 19        | 0.43%   |
| Kingston SA400S37120G 120GB SSD    | 19        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB        | 19        | 0.43%   |
| Seagate ST2000DL003-9VT166 2TB     | 18        | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB     | 18        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 18        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB     | 18        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB       | 18        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB     | 18        | 0.41%   |
| Samsung SSD 860 QVO 1TB            | 18        | 0.41%   |
| Intel NVMe SSD Drive 512GB         | 18        | 0.41%   |
| Seagate ST31000528AS 1TB           | 17        | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB     | 17        | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 16        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB       | 16        | 0.36%   |
| WDC WD20EARX-00PASB0 2TB           | 15        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 657       | 1234   | 39.7%   |
| WDC                 | 500       | 959    | 30.21%  |
| Toshiba             | 141       | 211    | 8.52%   |
| Hitachi             | 130       | 206    | 7.85%   |
| Samsung Electronics | 88        | 189    | 5.32%   |
| HGST                | 59        | 86     | 3.56%   |
| Unknown             | 15        | 25     | 0.91%   |
| Apple               | 15        | 20     | 0.91%   |
| Fujitsu             | 12        | 16     | 0.73%   |
| Maxtor              | 9         | 11     | 0.54%   |
| LaCie               | 9         | 15     | 0.54%   |
| ASMT                | 5         | 11     | 0.3%    |
| Hewlett-Packard     | 3         | 4      | 0.18%   |
| USB                 | 2         | 3      | 0.12%   |
| HGST HUS            | 2         | 2      | 0.12%   |
| USB3.0              | 1         | 2      | 0.06%   |
| MaxDigital          | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| Hajaan              | 1         | 1      | 0.06%   |
| DAS                 | 1         | 1      | 0.06%   |
| AAPL                | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 406       | 665    | 31.52%  |
| Crucial             | 166       | 253    | 12.89%  |
| Kingston            | 130       | 168    | 10.09%  |
| WDC                 | 103       | 135    | 8%      |
| SanDisk             | 96        | 124    | 7.45%   |
| Intel               | 78        | 149    | 6.06%   |
| Apple               | 30        | 32     | 2.33%   |
| SK hynix            | 27        | 32     | 2.1%    |
| OCZ                 | 27        | 41     | 2.1%    |
| Toshiba             | 21        | 28     | 1.63%   |
| SPCC                | 19        | 24     | 1.48%   |
| Micron Technology   | 19        | 22     | 1.48%   |
| A-DATA Technology   | 15        | 20     | 1.16%   |
| LITEONIT            | 14        | 19     | 1.09%   |
| LITEON              | 14        | 22     | 1.09%   |
| Seagate             | 12        | 17     | 0.93%   |
| Transcend           | 11        | 17     | 0.85%   |
| Patriot             | 11        | 16     | 0.85%   |
| KingSpec            | 11        | 26     | 0.85%   |
| Corsair             | 11        | 23     | 0.85%   |
| China               | 7         | 9      | 0.54%   |
| TO Exter            | 6         | 6      | 0.47%   |
| OWC                 | 6         | 12     | 0.47%   |
| Plextor             | 5         | 16     | 0.39%   |
| Gigabyte Technology | 5         | 5      | 0.39%   |
| Team                | 3         | 4      | 0.23%   |
| ASMT                | 3         | 3      | 0.23%   |
| Vaseky              | 2         | 3      | 0.16%   |
| T-CREATE            | 2         | 2      | 0.16%   |
| Lexar               | 2         | 2      | 0.16%   |
| KingFast            | 2         | 2      | 0.16%   |
| Unknown             | 1         | 1      | 0.08%   |
| SATA3 12            | 1         | 1      | 0.08%   |
| SAMSWEET            | 1         | 1      | 0.08%   |
| Radeon              | 1         | 1      | 0.08%   |
| PNY                 | 1         | 1      | 0.08%   |
| OCZ-VERTEX3         | 1         | 1      | 0.08%   |
| Netac               | 1         | 1      | 0.08%   |
| MyDigitalSSD        | 1         | 1      | 0.08%   |
| Mushkin             | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1337      | 3001   | 39.77%  |
| SSD     | 1121      | 1923   | 33.34%  |
| NVMe    | 731       | 1116   | 21.74%  |
| MMC     | 124       | 183    | 3.69%   |
| Unknown | 49        | 63     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1930      | 4671   | 64.77%  |
| NVMe | 727       | 1102   | 24.4%   |
| SAS  | 199       | 330    | 6.68%   |
| MMC  | 124       | 183    | 4.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1411      | 2611   | 52.67%  |
| 0.51-1.0   | 706       | 1248   | 26.35%  |
| 1.01-2.0   | 323       | 589    | 12.06%  |
| 3.01-4.0   | 99        | 204    | 3.7%    |
| 2.01-3.0   | 67        | 115    | 2.5%    |
| 4.01-10.0  | 66        | 148    | 2.46%   |
| 10.01-20.0 | 6         | 8      | 0.22%   |
| 0          | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 600       | 22.37%  |
| 251-500        | 563       | 20.99%  |
| 501-1000       | 418       | 15.59%  |
| 1001-2000      | 243       | 9.06%   |
| More than 3000 | 204       | 7.61%   |
| 1-20           | 202       | 7.53%   |
| 51-100         | 187       | 6.97%   |
| 2001-3000      | 102       | 3.8%    |
| 21-50          | 83        | 3.09%   |
| Unknown        | 80        | 2.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1073      | 38.09%  |
| 21-50          | 454       | 16.12%  |
| 101-250        | 318       | 11.29%  |
| 51-100         | 280       | 9.94%   |
| 251-500        | 229       | 8.13%   |
| 501-1000       | 150       | 5.32%   |
| 1001-2000      | 105       | 3.73%   |
| More than 3000 | 86        | 3.05%   |
| Unknown        | 80        | 2.84%   |
| 2001-3000      | 41        | 1.46%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 7         | 24     | 3.06%   |
| Seagate ST3500418AS 500GB               | 5         | 11     | 2.18%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 2.18%   |
| Seagate ST500DM002-1BD142 500GB         | 4         | 4      | 1.75%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 1.31%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 1.31%   |
| Maxtor 6Y080L0 81GB                     | 3         | 4      | 1.31%   |
| Maxtor 6L200M0 208GB                    | 3         | 4      | 1.31%   |
| Kingston SV300S37A120G 120GB SSD        | 3         | 3      | 1.31%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 1.31%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.87%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.87%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 2      | 0.87%   |
| WDC WD2002FAEX-007BA0 2TB               | 2         | 3      | 0.87%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.87%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.87%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.87%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 2      | 0.87%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.87%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.87%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.87%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.87%   |
| Seagate ST3500413AS 500GB               | 2         | 2      | 0.87%   |
| Seagate ST31000333AS 1TB                | 2         | 4      | 0.87%   |
| Seagate ST2000DM001-9YN164 2TB          | 2         | 2      | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB          | 2         | 2      | 0.87%   |
| Seagate ST2000DM001-1CH164 2TB          | 2         | 2      | 0.87%   |
| Seagate ST1000DX001-1CM162 1TB          | 2         | 2      | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 2      | 0.87%   |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 6      | 0.87%   |
| Samsung Electronics HD501LJ 500GB       | 2         | 22     | 0.87%   |
| Samsung Electronics HD154UI 1TB         | 2         | 3      | 0.87%   |
| Samsung Electronics HD103UJ 1TB         | 2         | 13     | 0.87%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 0.87%   |
| Intel SSDSC2KW010T8 1TB                 | 2         | 2      | 0.87%   |
| HGST HTS545050A7E680 500GB              | 2         | 3      | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1      | 0.44%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 1      | 0.44%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1         | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 86     | 27.1%   |
| WDC                 | 42        | 71     | 19.63%  |
| Samsung Electronics | 24        | 61     | 11.21%  |
| Intel               | 18        | 42     | 8.41%   |
| Hitachi             | 16        | 19     | 7.48%   |
| Toshiba             | 8         | 11     | 3.74%   |
| Kingston            | 8         | 8      | 3.74%   |
| HGST                | 7         | 8      | 3.27%   |
| Maxtor              | 6         | 8      | 2.8%    |
| Crucial             | 4         | 4      | 1.87%   |
| Corsair             | 4         | 5      | 1.87%   |
| SanDisk             | 3         | 3      | 1.4%    |
| Fujitsu             | 3         | 3      | 1.4%    |
| SK hynix            | 2         | 2      | 0.93%   |
| SPCC                | 1         | 1      | 0.47%   |
| OCZ                 | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| MaxDigital          | 1         | 1      | 0.47%   |
| KingSpec            | 1         | 3      | 0.47%   |
| KingFast            | 1         | 1      | 0.47%   |
| HPE                 | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 2      | 0.47%   |
| Gigabyte Technology | 1         | 1      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |
| A-DATA Technology   | 1         | 1      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 86     | 37.91%  |
| WDC                 | 41        | 68     | 26.8%   |
| Hitachi             | 16        | 19     | 10.46%  |
| Samsung Electronics | 13        | 49     | 8.5%    |
| HGST                | 7         | 8      | 4.58%   |
| Toshiba             | 6         | 9      | 3.92%   |
| Maxtor              | 6         | 8      | 3.92%   |
| Fujitsu             | 3         | 3      | 1.96%   |
| MaxDigital          | 1         | 1      | 0.65%   |
| HPE                 | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 2      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 136       | 254    | 68.34%  |
| SSD  | 54        | 81     | 27.14%  |
| NVMe | 9         | 10     | 4.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB | 1         | 6      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 6      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1652      | 3786   | 61.34%  |
| Works    | 846       | 2148   | 31.41%  |
| Malfunc  | 193       | 345    | 7.17%   |
| Failed   | 2         | 7      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1678      | 52.47%  |
| AMD                              | 490       | 15.32%  |
| Samsung Electronics              | 305       | 9.54%   |
| SanDisk                          | 82        | 2.56%   |
| Marvell Technology Group         | 76        | 2.38%   |
| JMicron Technology               | 66        | 2.06%   |
| ASMedia Technology               | 58        | 1.81%   |
| SK hynix                         | 51        | 1.59%   |
| Micron/Crucial Technology        | 51        | 1.59%   |
| Phison Electronics               | 48        | 1.5%    |
| Kingston Technology Company      | 46        | 1.44%   |
| Toshiba America Info Systems     | 42        | 1.31%   |
| Micron Technology                | 25        | 0.78%   |
| Nvidia                           | 23        | 0.72%   |
| KIOXIA                           | 22        | 0.69%   |
| ADATA Technology                 | 19        | 0.59%   |
| LSI Logic / Symbios Logic        | 16        | 0.5%    |
| Silicon Motion                   | 12        | 0.38%   |
| VIA Technologies                 | 11        | 0.34%   |
| Realtek Semiconductor            | 10        | 0.31%   |
| Apple                            | 8         | 0.25%   |
| Integrated Technology Express    | 7         | 0.22%   |
| Silicon Image                    | 6         | 0.19%   |
| Broadcom / LSI                   | 6         | 0.19%   |
| Seagate Technology               | 5         | 0.16%   |
| Lite-On Technology               | 5         | 0.16%   |
| Union Memory (Shenzhen)          | 4         | 0.13%   |
| Solid State Storage Technology   | 4         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.13%   |
| ULi Electronics                  | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Adaptec                          | 3         | 0.09%   |
| Shenzhen Longsys Electronics     | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| 3ware                            | 2         | 0.06%   |
| Promise Technology               | 1         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 332       | 8.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 173       | 4.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 128       | 3.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 102       | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 92        | 2.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 89        | 2.37%   |
| AMD 400 Series Chipset SATA Controller                                                  | 79        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 74        | 1.97%   |
| Intel SATA Controller [RAID mode]                                                       | 70        | 1.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 66        | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 65        | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 64        | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 59        | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 58        | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 56        | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 53        | 1.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 52        | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 51        | 1.36%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 51        | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 46        | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 46        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 45        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 39        | 1.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 39        | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 33        | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 32        | 0.85%   |
| Samsung NVMe SSD Controller 980                                                         | 31        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 31        | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 31        | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 31        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 31        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 31        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 30        | 0.8%    |
| Intel SSD 660P Series                                                                   | 28        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 27        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 26        | 0.69%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 26        | 0.69%   |
| Micron Non-Volatile memory controller                                                   | 24        | 0.64%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 24        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1777      | 56.29%  |
| NVMe | 732       | 23.19%  |
| IDE  | 396       | 12.54%  |
| RAID | 233       | 7.38%   |
| SAS  | 12        | 0.38%   |
| SCSI | 7         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1892      | 76.2%   |
| AMD          | 550       | 22.15%  |
| ARM          | 39        | 1.57%   |
| CentaurHauls | 1         | 0.04%   |
| Unknown      | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz        | 32        | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor       | 31        | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 30        | 1.21%   |
| ARM Processor                           | 28        | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 27        | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 26        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 25        | 1.01%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 24        | 0.97%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 22        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 21        | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 21        | 0.84%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 20        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 19        | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 18        | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 18        | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 18        | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 17        | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 0.68%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 17        | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 15        | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz        | 15        | 0.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 14        | 0.56%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 14        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 0.52%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 13        | 0.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 13        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 0.52%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 13        | 0.52%   |
| AMD FX-6300 Six-Core Processor          | 13        | 0.52%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 12        | 0.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 12        | 0.48%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 12        | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 11        | 0.44%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 11        | 0.44%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 11        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 681       | 27.4%   |
| Intel Core i5           | 558       | 22.45%  |
| AMD Ryzen 5             | 126       | 5.07%   |
| Other                   | 125       | 5.03%   |
| Intel Core 2 Duo        | 113       | 4.55%   |
| Intel Core i3           | 109       | 4.39%   |
| AMD Ryzen 7             | 100       | 4.02%   |
| Intel Celeron           | 85        | 3.42%   |
| Intel Xeon              | 60        | 2.41%   |
| AMD Ryzen 9             | 56        | 2.25%   |
| AMD FX                  | 43        | 1.73%   |
| Intel Pentium           | 42        | 1.69%   |
| Intel Atom              | 31        | 1.25%   |
| AMD A6                  | 24        | 0.97%   |
| Intel Core 2            | 22        | 0.89%   |
| AMD Ryzen 3             | 21        | 0.85%   |
| Intel Core 2 Quad       | 20        | 0.8%    |
| AMD A4                  | 20        | 0.8%    |
| AMD A8                  | 19        | 0.76%   |
| Intel Core i9           | 15        | 0.6%    |
| Intel Pentium Dual-Core | 14        | 0.56%   |
| AMD Phenom II X4        | 14        | 0.56%   |
| AMD E2                  | 13        | 0.52%   |
| AMD A10                 | 13        | 0.52%   |
| AMD Phenom II X6        | 10        | 0.4%    |
| ARM BCM                 | 9         | 0.36%   |
| AMD Athlon              | 9         | 0.36%   |
| Intel Genuine           | 8         | 0.32%   |
| AMD Ryzen Threadripper  | 8         | 0.32%   |
| Intel Pentium D         | 7         | 0.28%   |
| Intel Core m3           | 7         | 0.28%   |
| AMD Ryzen 7 PRO         | 7         | 0.28%   |
| AMD E1                  | 7         | 0.28%   |
| Intel Pentium 4         | 5         | 0.2%    |
| AMD Phenom II X2        | 5         | 0.2%    |
| AMD E                   | 5         | 0.2%    |
| AMD Athlon II X4        | 5         | 0.2%    |
| AMD Athlon II X2        | 5         | 0.2%    |
| AMD Athlon 64 X2        | 5         | 0.2%    |
| Intel Pentium Dual      | 4         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1000      | 40.23%  |
| 2       | 857       | 34.47%  |
| 6       | 283       | 11.38%  |
| 8       | 174       | 7%      |
| 12      | 51        | 2.05%   |
| 1       | 50        | 2.01%   |
| 16      | 23        | 0.93%   |
| 3       | 18        | 0.72%   |
| 10      | 11        | 0.44%   |
| 14      | 6         | 0.24%   |
| 24      | 5         | 0.2%    |
| Unknown | 3         | 0.12%   |
| 40      | 2         | 0.08%   |
| 32      | 2         | 0.08%   |
| 128     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2445      | 98.43%  |
| 2       | 35        | 1.41%   |
| Unknown | 3         | 0.12%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1666      | 67.02%  |
| 1       | 815       | 32.78%  |
| Unknown | 3         | 0.12%   |
| 8       | 1         | 0.04%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2400      | 96.27%  |
| Unknown        | 65        | 2.61%   |
| 32-bit         | 22        | 0.88%   |
| 64-bit         | 6         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 612       | 23.73%  |
| 0x206a7    | 153       | 5.93%   |
| 0x306a9    | 150       | 5.82%   |
| 0x306c3    | 126       | 4.89%   |
| 0x1067a    | 86        | 3.33%   |
| 0x906ea    | 74        | 2.87%   |
| 0x506e3    | 58        | 2.25%   |
| 0x906e9    | 55        | 2.13%   |
| 0x806e9    | 52        | 2.02%   |
| 0x40651    | 52        | 2.02%   |
| 0x806ea    | 51        | 1.98%   |
| 0x806ec    | 49        | 1.9%    |
| 0x406e3    | 49        | 1.9%    |
| 0x08701021 | 46        | 1.78%   |
| 0x20655    | 41        | 1.59%   |
| 0x306d4    | 36        | 1.4%    |
| 0x806c1    | 35        | 1.36%   |
| 0x08701013 | 32        | 1.24%   |
| 0x106e5    | 27        | 1.05%   |
| 0x0800820d | 27        | 1.05%   |
| 0x30678    | 24        | 0.93%   |
| 0x20652    | 24        | 0.93%   |
| 0x10676    | 22        | 0.85%   |
| 0x06000852 | 21        | 0.81%   |
| 0xa0652    | 19        | 0.74%   |
| 0x906ed    | 18        | 0.7%    |
| 0x106a5    | 18        | 0.7%    |
| 0x010000c8 | 18        | 0.7%    |
| 0x0a50000c | 17        | 0.66%   |
| 0x06001119 | 17        | 0.66%   |
| 0x806eb    | 16        | 0.62%   |
| 0x6fb      | 16        | 0.62%   |
| 0x6f6      | 16        | 0.62%   |
| 0x706e5    | 15        | 0.58%   |
| 0x206c2    | 15        | 0.58%   |
| 0x08108109 | 15        | 0.58%   |
| 0x08001138 | 15        | 0.58%   |
| 0x06006705 | 15        | 0.58%   |
| 0x07030105 | 14        | 0.54%   |
| 0x6fd      | 13        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 411       | 16.53%  |
| Haswell          | 250       | 10.05%  |
| SandyBridge      | 196       | 7.88%   |
| IvyBridge        | 195       | 7.84%   |
| Skylake          | 146       | 5.87%   |
| Zen 2            | 130       | 5.23%   |
| Penryn           | 127       | 5.11%   |
| Westmere         | 97        | 3.9%    |
| Unknown          | 70        | 2.81%   |
| Zen 3            | 67        | 2.69%   |
| Zen+             | 63        | 2.53%   |
| Core             | 63        | 2.53%   |
| Zen              | 58        | 2.33%   |
| Silvermont       | 58        | 2.33%   |
| CometLake        | 57        | 2.29%   |
| Nehalem          | 56        | 2.25%   |
| Piledriver       | 52        | 2.09%   |
| K10              | 51        | 2.05%   |
| Broadwell        | 48        | 1.93%   |
| TigerLake        | 43        | 1.73%   |
| IceLake          | 34        | 1.37%   |
| Excavator        | 30        | 1.21%   |
| Goldmont plus    | 21        | 0.84%   |
| Puma             | 19        | 0.76%   |
| Goldmont         | 17        | 0.68%   |
| Bonnell          | 16        | 0.64%   |
| Steamroller      | 14        | 0.56%   |
| NetBurst         | 14        | 0.56%   |
| Alderlake Hybrid | 13        | 0.52%   |
| K8 Hammer        | 12        | 0.48%   |
| Jaguar           | 12        | 0.48%   |
| Bulldozer        | 12        | 0.48%   |
| P6               | 11        | 0.44%   |
| K10 Llano        | 10        | 0.4%    |
| Bobcat           | 8         | 0.32%   |
| Tremont          | 4         | 0.16%   |
| K8 & K10 hybrid  | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1316      | 45.38%  |
| Nvidia                           | 909       | 31.34%  |
| AMD                              | 650       | 22.41%  |
| Matrox Electronics Systems       | 14        | 0.48%   |
| VIA Technologies                 | 4         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Neomagic                         | 2         | 0.07%   |
| ASPEED Technology                | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 130       | 4.34%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 85        | 2.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 69        | 2.3%    |
| Intel UHD Graphics 620                                                                   | 64        | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 64        | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 62        | 2.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 58        | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 57        | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 1.7%    |
| Intel HD Graphics 620                                                                    | 50        | 1.67%   |
| Intel HD Graphics 530                                                                    | 42        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 1.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 1.34%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 38        | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.24%   |
| Intel HD Graphics 630                                                                    | 37        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 32        | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 1.04%   |
| Intel HD Graphics 5500                                                                   | 30        | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 0.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 0.87%   |
| AMD Cezanne                                                                              | 25        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 23        | 0.77%   |
| AMD Renoir                                                                               | 23        | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22        | 0.73%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 21        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 20        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 20        | 0.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 20        | 0.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 19        | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 0.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 19        | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 0.6%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 912       | 36.29%  |
| 1 x Nvidia               | 574       | 22.84%  |
| 1 x AMD                  | 517       | 20.57%  |
| Intel + Nvidia           | 298       | 11.86%  |
| Intel + AMD              | 60        | 2.39%   |
| 2 x AMD                  | 47        | 1.87%   |
| Other                    | 40        | 1.59%   |
| AMD + Nvidia             | 27        | 1.07%   |
| 1 x Matrox               | 11        | 0.44%   |
| 2 x Nvidia               | 8         | 0.32%   |
| 1 x VIA                  | 4         | 0.16%   |
| 1 x SiS                  | 3         | 0.12%   |
| Nvidia + Matrox          | 3         | 0.12%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.12%   |
| Nvidia + ASPEED          | 2         | 0.08%   |
| 1 x Neomagic             | 2         | 0.08%   |
| 2 x Intel                | 1         | 0.04%   |
| Intel + 2 x AMD          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1904      | 74.81%  |
| Proprietary | 508       | 19.96%  |
| Unknown     | 133       | 5.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1288      | 50.1%   |
| 1.01-2.0   | 342       | 13.3%   |
| 0.01-0.5   | 235       | 9.14%   |
| 0.51-1.0   | 221       | 8.6%    |
| 3.01-4.0   | 198       | 7.7%    |
| 7.01-8.0   | 147       | 5.72%   |
| 5.01-6.0   | 67        | 2.61%   |
| 8.01-16.0  | 37        | 1.44%   |
| 2.01-3.0   | 26        | 1.01%   |
| 16.01-24.0 | 8         | 0.31%   |
| 32.01-64.0 | 1         | 0.04%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 352       | 12.5%   |
| AU Optronics            | 265       | 9.41%   |
| LG Display              | 212       | 7.53%   |
| Dell                    | 208       | 7.39%   |
| Chimei Innolux          | 160       | 5.68%   |
| Acer                    | 139       | 4.94%   |
| Goldstar                | 126       | 4.48%   |
| BOE                     | 121       | 4.3%    |
| BenQ                    | 115       | 4.09%   |
| Hewlett-Packard         | 114       | 4.05%   |
| Apple                   | 90        | 3.2%    |
| Ancor Communications    | 89        | 3.16%   |
| Philips                 | 87        | 3.09%   |
| AOC                     | 63        | 2.24%   |
| Sharp                   | 60        | 2.13%   |
| ViewSonic               | 58        | 2.06%   |
| Lenovo                  | 57        | 2.02%   |
| Unknown                 | 51        | 1.81%   |
| Chi Mei Optoelectronics | 42        | 1.49%   |
| Sony                    | 32        | 1.14%   |
| ASUSTek Computer        | 29        | 1.03%   |
| ___                     | 27        | 0.96%   |
| LG Electronics          | 25        | 0.89%   |
| Panasonic               | 22        | 0.78%   |
| Kogan                   | 18        | 0.64%   |
| GKK                     | 16        | 0.57%   |
| PANDA                   | 14        | 0.5%    |
| Toshiba                 | 13        | 0.46%   |
| SAC                     | 11        | 0.39%   |
| Hitachi                 | 10        | 0.36%   |
| Unknown (XXX)           | 9         | 0.32%   |
| MSI                     | 8         | 0.28%   |
| CVT                     | 8         | 0.28%   |
| MStar                   | 7         | 0.25%   |
| eMachines               | 7         | 0.25%   |
| MiTAC                   | 6         | 0.21%   |
| LG Philips              | 6         | 0.21%   |
| InfoVision              | 6         | 0.21%   |
| Gigabyte Technology     | 6         | 0.21%   |
| Eizo                    | 6         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch      | 21        | 0.71%   |
| ___ LCDTV16 ___0101 1920x1080                                            | 19        | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.51%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 12        | 0.41%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 10        | 0.34%   |
| ___ TV ___9000 1360x768                                                  | 9         | 0.3%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 9         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 9         | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 8         | 0.27%   |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch     | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.27%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                    | 7         | 0.24%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                        | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 7         | 0.24%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                       | 7         | 0.24%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 7         | 0.24%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 7         | 0.24%   |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch         | 7         | 0.24%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                       | 6         | 0.2%    |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch           | 6         | 0.2%    |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 6         | 0.2%    |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                  | 6         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.2%    |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.2%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 6         | 0.2%    |
| Acer ET322QR ACR0568 1920x1080 698x393mm 31.5-inch                       | 6         | 0.2%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 5         | 0.17%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch     | 5         | 0.17%   |
| Philips 190S PHL082F 1280x1024 380x300mm 19.1-inch                       | 5         | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1135      | 42.46%  |
| 1366x768 (WXGA)    | 405       | 15.15%  |
| 3840x2160 (4K)     | 228       | 8.53%   |
| 2560x1440 (QHD)    | 130       | 4.86%   |
| 1680x1050 (WSXGA+) | 106       | 3.97%   |
| 1280x1024 (SXGA)   | 101       | 3.78%   |
| 1440x900 (WXGA+)   | 79        | 2.96%   |
| 1920x1200 (WUXGA)  | 70        | 2.62%   |
| 1600x900 (HD+)     | 60        | 2.24%   |
| 1280x800 (WXGA)    | 52        | 1.95%   |
| Unknown            | 46        | 1.72%   |
| 3440x1440          | 31        | 1.16%   |
| 3840x1080          | 22        | 0.82%   |
| 2560x1600          | 21        | 0.79%   |
| 1360x768           | 19        | 0.71%   |
| 2560x1080          | 18        | 0.67%   |
| 3840x2400          | 12        | 0.45%   |
| 2880x1800          | 11        | 0.41%   |
| 2736x1824          | 9         | 0.34%   |
| 1280x768           | 9         | 0.34%   |
| 1920x540           | 8         | 0.3%    |
| 3200x1800 (QHD+)   | 7         | 0.26%   |
| 2160x1440          | 7         | 0.26%   |
| 1280x720 (HD)      | 6         | 0.22%   |
| 1024x600           | 6         | 0.22%   |
| 3840x1600          | 5         | 0.19%   |
| 1024x768 (XGA)     | 5         | 0.19%   |
| 5760x2160          | 4         | 0.15%   |
| 5120x1440          | 4         | 0.15%   |
| 4480x1440          | 4         | 0.15%   |
| 3600x1080          | 4         | 0.15%   |
| 3072x1920          | 4         | 0.15%   |
| 1920x1280          | 4         | 0.15%   |
| 1600x1200          | 4         | 0.15%   |
| 2256x1504          | 3         | 0.11%   |
| 7680x2160          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3286x1080          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 3200x1080          | 2         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 528       | 18.96%  |
| 27      | 268       | 9.62%   |
| 13      | 225       | 8.08%   |
| 24      | 216       | 7.76%   |
| 23      | 204       | 7.32%   |
| Unknown | 196       | 7.04%   |
| 21      | 159       | 5.71%   |
| 14      | 149       | 5.35%   |
| 19      | 119       | 4.27%   |
| 17      | 117       | 4.2%    |
| 31      | 83        | 2.98%   |
| 22      | 75        | 2.69%   |
| 12      | 51        | 1.83%   |
| 72      | 45        | 1.62%   |
| 34      | 44        | 1.58%   |
| 20      | 42        | 1.51%   |
| 11      | 38        | 1.36%   |
| 18      | 30        | 1.08%   |
| 84      | 21        | 0.75%   |
| 26      | 19        | 0.68%   |
| 32      | 16        | 0.57%   |
| 54      | 15        | 0.54%   |
| 52      | 13        | 0.47%   |
| 40      | 12        | 0.43%   |
| 16      | 12        | 0.43%   |
| 48      | 10        | 0.36%   |
| 37      | 8         | 0.29%   |
| 25      | 8         | 0.29%   |
| 10      | 8         | 0.29%   |
| 29      | 7         | 0.25%   |
| 55      | 5         | 0.18%   |
| 46      | 5         | 0.18%   |
| 42      | 5         | 0.18%   |
| 35      | 5         | 0.18%   |
| 49      | 4         | 0.14%   |
| 63      | 3         | 0.11%   |
| 36      | 3         | 0.11%   |
| 75      | 2         | 0.07%   |
| 65      | 2         | 0.07%   |
| 60      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 778       | 28.52%  |
| 501-600     | 629       | 23.06%  |
| 401-500     | 340       | 12.46%  |
| 201-300     | 239       | 8.76%   |
| Unknown     | 196       | 7.18%   |
| 351-400     | 186       | 6.82%   |
| 601-700     | 133       | 4.88%   |
| 1501-2000   | 69        | 2.53%   |
| 1001-1500   | 63        | 2.31%   |
| 701-800     | 60        | 2.2%    |
| 801-900     | 27        | 0.99%   |
| 901-1000    | 6         | 0.22%   |
| 101-200     | 2         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1769      | 71.13%  |
| 16/10   | 332       | 13.35%  |
| Unknown | 165       | 6.63%   |
| 5/4     | 89        | 3.58%   |
| 21/9    | 54        | 2.17%   |
| 3/2     | 31        | 1.25%   |
| 4/3     | 26        | 1.05%   |
| 6/5     | 10        | 0.4%    |
| 32/9    | 10        | 0.4%    |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 543       | 19.72%  |
| 101-110        | 528       | 19.18%  |
| 301-350        | 280       | 10.17%  |
| 81-90          | 258       | 9.37%   |
| Unknown        | 196       | 7.12%   |
| 151-200        | 195       | 7.08%   |
| 351-500        | 149       | 5.41%   |
| 71-80          | 118       | 4.29%   |
| More than 1000 | 115       | 4.18%   |
| 251-300        | 81        | 2.94%   |
| 121-130        | 81        | 2.94%   |
| 501-1000       | 46        | 1.67%   |
| 141-150        | 42        | 1.53%   |
| 61-70          | 41        | 1.49%   |
| 51-60          | 39        | 1.42%   |
| 111-120        | 11        | 0.4%    |
| 131-140        | 10        | 0.36%   |
| 91-100         | 10        | 0.36%   |
| 41-50          | 8         | 0.29%   |
| 1-40           | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 972       | 36.72%  |
| 101-120       | 616       | 23.27%  |
| 121-160       | 521       | 19.68%  |
| Unknown       | 196       | 7.4%    |
| 161-240       | 155       | 5.86%   |
| 1-50          | 95        | 3.59%   |
| More than 240 | 92        | 3.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1976      | 76.38%  |
| 2     | 439       | 16.97%  |
| 0     | 119       | 4.6%    |
| 3     | 48        | 1.86%   |
| 4     | 5         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1287      | 33.71%  |
| Realtek Semiconductor           | 1266      | 33.16%  |
| Qualcomm Atheros                | 415       | 10.87%  |
| Broadcom                        | 250       | 6.55%   |
| Broadcom Limited                | 53        | 1.39%   |
| Marvell Technology Group        | 52        | 1.36%   |
| Ralink                          | 51        | 1.34%   |
| TP-Link                         | 36        | 0.94%   |
| Ralink Technology               | 36        | 0.94%   |
| Samsung Electronics             | 26        | 0.68%   |
| NetGear                         | 20        | 0.52%   |
| MediaTek                        | 19        | 0.5%    |
| D-Link System                   | 17        | 0.45%   |
| D-Link                          | 17        | 0.45%   |
| Nvidia                          | 16        | 0.42%   |
| DisplayLink                     | 16        | 0.42%   |
| Huawei Technologies             | 15        | 0.39%   |
| Microsoft                       | 14        | 0.37%   |
| Edimax Technology               | 14        | 0.37%   |
| Dell                            | 14        | 0.37%   |
| Sierra Wireless                 | 13        | 0.34%   |
| ASIX Electronics                | 11        | 0.29%   |
| Aquantia                        | 11        | 0.29%   |
| Lenovo                          | 10        | 0.26%   |
| ZTE WCDMA Technologies MSM      | 9         | 0.24%   |
| ASUSTek Computer                | 9         | 0.24%   |
| Apple                           | 9         | 0.24%   |
| Motorola PCS                    | 8         | 0.21%   |
| VIA Technologies                | 7         | 0.18%   |
| Google                          | 7         | 0.18%   |
| Qualcomm Atheros Communications | 6         | 0.16%   |
| OPPO Electronics                | 6         | 0.16%   |
| Hewlett-Packard                 | 6         | 0.16%   |
| Mellanox Technologies           | 5         | 0.13%   |
| Arduino SA                      | 5         | 0.13%   |
| Standard Microsystems           | 4         | 0.1%    |
| Qualcomm                        | 4         | 0.1%    |
| JMicron Technology              | 4         | 0.1%    |
| Xiaomi                          | 3         | 0.08%   |
| Microchip Technology            | 3         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 879       | 19.66%  |
| Intel Wi-Fi 6 AX200                                               | 124       | 2.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 107       | 2.39%   |
| Intel I211 Gigabit Network Connection                             | 103       | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98        | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 81        | 1.81%   |
| Intel Wireless 8265 / 8275                                        | 66        | 1.48%   |
| Intel Wireless 8260                                               | 60        | 1.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 54        | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 53        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 48        | 1.07%   |
| Intel Wireless 7260                                               | 47        | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 47        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 46        | 1.03%   |
| Intel Wireless 7265                                               | 46        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 43        | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 41        | 0.92%   |
| Realtek 802.11ac NIC                                              | 40        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.87%   |
| Intel Wireless 3165                                               | 38        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 38        | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 33        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.74%   |
| Intel Wireless-AC 9260                                            | 33        | 0.74%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 31        | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29        | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 29        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 27        | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 27        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 26        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 23        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 885       | 45.48%  |
| Qualcomm Atheros                | 309       | 15.88%  |
| Realtek Semiconductor           | 276       | 14.18%  |
| Broadcom                        | 170       | 8.74%   |
| Ralink                          | 51        | 2.62%   |
| Ralink Technology               | 36        | 1.85%   |
| Broadcom Limited                | 35        | 1.8%    |
| TP-Link                         | 34        | 1.75%   |
| NetGear                         | 19        | 0.98%   |
| Marvell Technology Group        | 18        | 0.92%   |
| MediaTek                        | 15        | 0.77%   |
| Edimax Technology               | 14        | 0.72%   |
| Sierra Wireless                 | 13        | 0.67%   |
| D-Link System                   | 12        | 0.62%   |
| Microsoft                       | 10        | 0.51%   |
| D-Link                          | 10        | 0.51%   |
| ASUSTek Computer                | 9         | 0.46%   |
| Dell                            | 8         | 0.41%   |
| Qualcomm Atheros Communications | 6         | 0.31%   |
| Belkin Components               | 3         | 0.15%   |
| Wacom                           | 2         | 0.1%    |
| Linksys                         | 2         | 0.1%    |
| BUFFALO                         | 2         | 0.1%    |
| Xiaomi                          | 1         | 0.05%   |
| Wilocity                        | 1         | 0.05%   |
| Toshiba                         | 1         | 0.05%   |
| Qualcomm                        | 1         | 0.05%   |
| IMC Networks                    | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 124       | 6.34%   |
| Intel Wireless 8265 / 8275                                     | 66        | 3.37%   |
| Intel Wireless 8260                                            | 60        | 3.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 53        | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 48        | 2.45%   |
| Intel Wireless 7260                                            | 47        | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 46        | 2.35%   |
| Intel Wireless 7265                                            | 46        | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 43        | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 41        | 2.1%    |
| Realtek 802.11ac NIC                                           | 40        | 2.04%   |
| Intel Wireless 3165                                            | 38        | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 38        | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 33        | 1.69%   |
| Intel Wireless-AC 9260                                         | 33        | 1.69%   |
| Intel Wi-Fi 6 AX201                                            | 33        | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 31        | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 31        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 29        | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 29        | 1.48%   |
| Intel Centrino Ultimate-N 6300                                 | 27        | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 27        | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 23        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.07%   |
| Intel Wireless 3160                                            | 20        | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 20        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 20        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 0.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 19        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 19        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 17        | 0.87%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 17        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 16        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 16        | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 16        | 0.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 15        | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 15        | 0.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 14        | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 13        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1130      | 47.3%   |
| Intel                            | 735       | 30.77%  |
| Qualcomm Atheros                 | 152       | 6.36%   |
| Broadcom                         | 124       | 5.19%   |
| Marvell Technology Group         | 34        | 1.42%   |
| Samsung Electronics              | 26        | 1.09%   |
| Broadcom Limited                 | 18        | 0.75%   |
| Nvidia                           | 16        | 0.67%   |
| DisplayLink                      | 16        | 0.67%   |
| Huawei Technologies              | 12        | 0.5%    |
| ASIX Electronics                 | 11        | 0.46%   |
| Aquantia                         | 11        | 0.46%   |
| Lenovo                           | 10        | 0.42%   |
| ZTE WCDMA Technologies MSM       | 9         | 0.38%   |
| Apple                            | 9         | 0.38%   |
| VIA Technologies                 | 7         | 0.29%   |
| Google                           | 7         | 0.29%   |
| D-Link                           | 7         | 0.29%   |
| OPPO Electronics                 | 6         | 0.25%   |
| D-Link System                    | 5         | 0.21%   |
| Standard Microsystems            | 4         | 0.17%   |
| Motorola PCS                     | 4         | 0.17%   |
| JMicron Technology               | 4         | 0.17%   |
| Microsoft                        | 3         | 0.13%   |
| Microchip Technology             | 3         | 0.13%   |
| MediaTek                         | 3         | 0.13%   |
| ICS Advent                       | 3         | 0.13%   |
| Xiaomi                           | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Qualcomm                         | 2         | 0.08%   |
| NetGear                          | 2         | 0.08%   |
| Mellanox Technologies            | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| vivo                             | 1         | 0.04%   |
| TP-Link                          | 1         | 0.04%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| IBM                              | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Cypress Semiconductor            | 1         | 0.04%   |
| Attansic Technology              | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 879       | 35.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 107       | 4.34%   |
| Intel I211 Gigabit Network Connection                             | 103       | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98        | 3.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 81        | 3.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 54        | 2.19%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 47        | 1.91%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 1.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 26        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 18        | 0.73%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 16        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 15        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.61%   |
| Intel 82574L Gigabit Network Connection                           | 15        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.45%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                | 11        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.41%   |
| Intel 82578DM Gigabit Network Connection                          | 10        | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.37%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2167      | 53.73%  |
| WiFi     | 1815      | 45%     |
| Modem    | 36        | 0.89%   |
| Unknown  | 15        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1370      | 53.41%  |
| Ethernet | 1194      | 46.55%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1326      | 52.91%  |
| 1     | 1000      | 39.9%   |
| 3     | 88        | 3.51%   |
| 0     | 66        | 2.63%   |
| 4     | 16        | 0.64%   |
| 5     | 7         | 0.28%   |
| 6     | 3         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2275      | 90.03%  |
| Yes  | 252       | 9.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 710       | 50.18%  |
| Broadcom                        | 101       | 7.14%   |
| Cambridge Silicon Radio         | 92        | 6.5%    |
| Apple                           | 91        | 6.43%   |
| Qualcomm Atheros Communications | 90        | 6.36%   |
| Realtek Semiconductor           | 76        | 5.37%   |
| Lite-On Technology              | 39        | 2.76%   |
| Toshiba                         | 35        | 2.47%   |
| IMC Networks                    | 35        | 2.47%   |
| Foxconn / Hon Hai               | 33        | 2.33%   |
| ASUSTek Computer                | 20        | 1.41%   |
| Ralink                          | 16        | 1.13%   |
| Marvell Semiconductor           | 16        | 1.13%   |
| Hewlett-Packard                 | 16        | 1.13%   |
| Dell                            | 15        | 1.06%   |
| Alps Electric                   | 6         | 0.42%   |
| Realtek                         | 5         | 0.35%   |
| Ralink Technology               | 3         | 0.21%   |
| Edimax Technology               | 3         | 0.21%   |
| USI                             | 2         | 0.14%   |
| TP-Link                         | 2         | 0.14%   |
| MediaTek                        | 2         | 0.14%   |
| Integrated System Solution      | 2         | 0.14%   |
| Belkin Components               | 2         | 0.14%   |
| Opticis                         | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Creative Technology             | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 262       | 18.49%  |
| Intel AX200 Bluetooth                               | 120       | 8.47%   |
| Intel AX201 Bluetooth                               | 112       | 7.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 92        | 6.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 87        | 6.14%   |
| Realtek Bluetooth Radio                             | 40        | 2.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 2.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 37        | 2.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 36        | 2.54%   |
| Apple Bluetooth Host Controller                     | 33        | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 31        | 2.19%   |
| Apple Bluetooth USB Host Controller                 | 31        | 2.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 29        | 2.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.34%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.27%   |
| Intel AX210 Bluetooth                               | 17        | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 17        | 1.2%    |
| Ralink RT3290 Bluetooth                             | 16        | 1.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.99%   |
| Marvell Bluetooth and Wireless LAN Composite        | 13        | 0.92%   |
| Intel Bluetooth Device                              | 13        | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.92%   |
| Toshiba Bluetooth Device                            | 12        | 0.85%   |
| Lite-On Bluetooth Device                            | 12        | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.71%   |
| IMC Networks Bluetooth Radio                        | 10        | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.71%   |
| Apple Bluetooth HCI                                 | 10        | 0.71%   |
| Broadcom HP Portable Bumble Bee                     | 9         | 0.64%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.56%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.42%   |
| IMC Networks Bluetooth Device                       | 6         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.42%   |
| Toshiba Askey Bluetooth Module                      | 5         | 0.35%   |
| Realtek Bluetooth Radio                             | 5         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1807      | 49.89%  |
| AMD                                  | 727       | 20.07%  |
| Nvidia                               | 678       | 18.72%  |
| C-Media Electronics                  | 50        | 1.38%   |
| Logitech                             | 36        | 0.99%   |
| Creative Labs                        | 22        | 0.61%   |
| Realtek Semiconductor                | 20        | 0.55%   |
| Texas Instruments                    | 16        | 0.44%   |
| Kingston Technology                  | 15        | 0.41%   |
| Plantronics                          | 12        | 0.33%   |
| GN Netcom                            | 12        | 0.33%   |
| Creative Technology                  | 12        | 0.33%   |
| RODE Microphones                     | 10        | 0.28%   |
| Razer USA                            | 9         | 0.25%   |
| Generalplus Technology               | 8         | 0.22%   |
| Apple                                | 8         | 0.22%   |
| VIA Technologies                     | 7         | 0.19%   |
| SteelSeries ApS                      | 7         | 0.19%   |
| Lenovo                               | 7         | 0.19%   |
| Corsair                              | 7         | 0.19%   |
| Blue Microphones                     | 7         | 0.19%   |
| JMTek                                | 6         | 0.17%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.14%   |
| Sennheiser Communications            | 5         | 0.14%   |
| OPPO Electronics                     | 5         | 0.14%   |
| Microsoft                            | 5         | 0.14%   |
| Hewlett-Packard                      | 5         | 0.14%   |
| Dell                                 | 5         | 0.14%   |
| Cambridge Silicon Radio              | 5         | 0.14%   |
| M-Audio                              | 4         | 0.11%   |
| Giga-Byte Technology                 | 4         | 0.11%   |
| Chicony Electronics                  | 4         | 0.11%   |
| Audio-Technica                       | 4         | 0.11%   |
| Astro Gaming                         | 4         | 0.11%   |
| Unknown                              | 3         | 0.08%   |
| ULi Electronics                      | 3         | 0.08%   |
| Turtle Beach                         | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.08%   |
| Samson Technologies                  | 3         | 0.08%   |
| PreSonus Audio Electronics           | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 192       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 189       | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 179       | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 149       | 3.54%   |
| AMD Starship/Matisse HD Audio Controller                                          | 142       | 3.38%   |
| Intel Cannon Lake PCH cAVS                                                        | 111       | 2.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 110       | 2.62%   |
| AMD Family 17h/19h HD Audio Controller                                            | 110       | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 104       | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 86        | 2.04%   |
| AMD FCH Azalia Controller                                                         | 78        | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 77        | 1.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 69        | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 68        | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 67        | 1.59%   |
| Intel 8 Series HD Audio Controller                                                | 66        | 1.57%   |
| Intel Haswell-ULT HD Audio Controller                                             | 65        | 1.55%   |
| Intel 200 Series PCH HD Audio                                                     | 58        | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 55        | 1.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 55        | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 52        | 1.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 50        | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                     | 46        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                                     | 43        | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 43        | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 43        | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 42        | 1%      |
| Intel Broadwell-U Audio Controller                                                | 42        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                   | 41        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 41        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                         | 40        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                     | 39        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 39        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 37        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                          | 36        | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 33        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                     | 33        | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 32        | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                | 30        | 0.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 30        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 275       | 20.82%  |
| SK hynix            | 223       | 16.88%  |
| Kingston            | 152       | 11.51%  |
| Corsair             | 125       | 9.46%   |
| Unknown             | 120       | 9.08%   |
| Micron Technology   | 119       | 9.01%   |
| G.Skill             | 75        | 5.68%   |
| Crucial             | 73        | 5.53%   |
| Team                | 23        | 1.74%   |
| Nanya Technology    | 22        | 1.67%   |
| Elpida              | 21        | 1.59%   |
| Ramaxel Technology  | 14        | 1.06%   |
| Patriot             | 13        | 0.98%   |
| Transcend           | 8         | 0.61%   |
| Apacer              | 8         | 0.61%   |
| A-DATA Technology   | 8         | 0.61%   |
| Unknown             | 6         | 0.45%   |
| Neo Forza           | 4         | 0.3%    |
| GeIL                | 4         | 0.3%    |
| Unknown (ABCD)      | 2         | 0.15%   |
| Strontium           | 2         | 0.15%   |
| Smart               | 2         | 0.15%   |
| Silicon Power       | 2         | 0.15%   |
| pqi                 | 2         | 0.15%   |
| Unknown (0x89AD)    | 1         | 0.08%   |
| Unknown (0x873E)    | 1         | 0.08%   |
| Unknown (0x0562)    | 1         | 0.08%   |
| Undefi              | 1         | 0.08%   |
| Toshiba             | 1         | 0.08%   |
| Qimonda             | 1         | 0.08%   |
| Princeton           | 1         | 0.08%   |
| PNY                 | 1         | 0.08%   |
| Netlist             | 1         | 0.08%   |
| Innodisk            | 1         | 0.08%   |
| Hewlett-Packard     | 1         | 0.08%   |
| GSkill              | 1         | 0.08%   |
| Goldenmars          | 1         | 0.08%   |
| Golden Empire       | 1         | 0.08%   |
| CSX                 | 1         | 0.08%   |
| Avant               | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 1.11%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 13        | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 10        | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.63%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 9         | 0.63%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 8         | 0.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 7         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 0.49%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s | 7         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.42%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 6         | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.42%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 6         | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 6         | 0.42%   |
| Unknown                                                          | 6         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5         | 0.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.35%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.35%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.35%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 0.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.35%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 5         | 0.35%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s           | 5         | 0.35%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 5         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 528       | 45.6%   |
| DDR3    | 404       | 34.89%  |
| Unknown | 62        | 5.35%   |
| LPDDR3  | 55        | 4.75%   |
| DDR2    | 47        | 4.06%   |
| LPDDR4  | 26        | 2.25%   |
| SDRAM   | 17        | 1.47%   |
| DDR     | 8         | 0.69%   |
| LPDDR5  | 5         | 0.43%   |
| DDR5    | 4         | 0.35%   |
| DRAM    | 2         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 547       | 47.4%   |
| DIMM         | 508       | 44.02%  |
| Row Of Chips | 87        | 7.54%   |
| Chip         | 8         | 0.69%   |
| FB-DIMM      | 2         | 0.17%   |
| Unknown      | 2         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 478       | 38.74%  |
| 4096  | 333       | 26.99%  |
| 16384 | 191       | 15.48%  |
| 2048  | 157       | 12.72%  |
| 32768 | 35        | 2.84%   |
| 1024  | 31        | 2.51%   |
| 512   | 6         | 0.49%   |
| 65536 | 2         | 0.16%   |
| 256   | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 262       | 20.83%  |
| 2667    | 177       | 14.07%  |
| 3200    | 129       | 10.25%  |
| 1333    | 104       | 8.27%   |
| 2133    | 83        | 6.6%    |
| 2400    | 71        | 5.64%   |
| 3600    | 49        | 3.9%    |
| 1334    | 43        | 3.42%   |
| 800     | 40        | 3.18%   |
| 667     | 32        | 2.54%   |
| 1867    | 30        | 2.38%   |
| 1067    | 21        | 1.67%   |
| 3000    | 18        | 1.43%   |
| Unknown | 17        | 1.35%   |
| 3466    | 16        | 1.27%   |
| 4267    | 14        | 1.11%   |
| 3400    | 14        | 1.11%   |
| 1066    | 13        | 1.03%   |
| 1866    | 11        | 0.87%   |
| 2933    | 10        | 0.79%   |
| 4800    | 8         | 0.64%   |
| 3733    | 8         | 0.64%   |
| 3266    | 8         | 0.64%   |
| 8400    | 7         | 0.56%   |
| 2666    | 7         | 0.56%   |
| 6400    | 5         | 0.4%    |
| 3100    | 5         | 0.4%    |
| 2800    | 5         | 0.4%    |
| 2048    | 5         | 0.4%    |
| 400     | 5         | 0.4%    |
| 533     | 4         | 0.32%   |
| 3500    | 3         | 0.24%   |
| 1800    | 3         | 0.24%   |
| 933     | 3         | 0.24%   |
| 333     | 3         | 0.24%   |
| 4199    | 2         | 0.16%   |
| 4133    | 2         | 0.16%   |
| 4000    | 2         | 0.16%   |
| 3007    | 2         | 0.16%   |
| 2934    | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 24        | 25.26%  |
| Brother Industries     | 24        | 25.26%  |
| Canon                  | 15        | 15.79%  |
| Fuji Xerox             | 7         | 7.37%   |
| Samsung Electronics    | 6         | 6.32%   |
| Prolific Technology    | 6         | 6.32%   |
| Seiko Epson            | 4         | 4.21%   |
| Lexmark International  | 2         | 2.11%   |
| Dymo-CoStar            | 2         | 2.11%   |
| Xerox                  | 1         | 1.05%   |
| Ricoh                  | 1         | 1.05%   |
| Kyocera                | 1         | 1.05%   |
| Custom Engineering SPA | 1         | 1.05%   |
| BIXOLON                | 1         | 1.05%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer           | 8         | 8.25%   |
| Prolific PL2305 Parallel Port                | 6         | 6.19%   |
| HP DeskJet 2130 series                       | 4         | 4.12%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 3.09%   |
| Brother HL-2130 series                       | 3         | 3.09%   |
| Brother HL-1110 series                       | 3         | 3.09%   |
| HP ENVY 5000 series                          | 2         | 2.06%   |
| HP DeskJet F2100 Printer series              | 2         | 2.06%   |
| Canon TR8500 series                          | 2         | 2.06%   |
| Canon PIXMA MX920 Series                     | 2         | 2.06%   |
| Canon PIXMA MG2500 Series                    | 2         | 2.06%   |
| Canon MG5600 series                          | 2         | 2.06%   |
| Brother MFC-L8690CDW series                  | 2         | 2.06%   |
| Brother HL-L3230CDW series                   | 2         | 2.06%   |
| Xerox Phaser 8400N                           | 1         | 1.03%   |
| Seiko Epson XP-243 245 247 Series            | 1         | 1.03%   |
| Seiko Epson WF-5190 Series                   | 1         | 1.03%   |
| Seiko Epson TM-T20                           | 1         | 1.03%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.03%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 1.03%   |
| Samsung ML-1865                              | 1         | 1.03%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 1.03%   |
| Samsung ML-1450                              | 1         | 1.03%   |
| Samsung M267x 287x Series                    | 1         | 1.03%   |
| Samsung M2020 Series                         | 1         | 1.03%   |
| Ricoh Printer                                | 1         | 1.03%   |
| Lexmark International Lexmark E260dn         | 1         | 1.03%   |
| Lexmark International CX410de                | 1         | 1.03%   |
| Kyocera FS-1100                              | 1         | 1.03%   |
| HP OfficeJet 5200 series                     | 1         | 1.03%   |
| HP LaserJet Professional P 1102w             | 1         | 1.03%   |
| HP ENVY Photo 7100 series                    | 1         | 1.03%   |
| HP ENVY 4520 series                          | 1         | 1.03%   |
| HP DeskJet 3630 series                       | 1         | 1.03%   |
| HP Deskjet 3520 series                       | 1         | 1.03%   |
| HP DeskJet 2300 series                       | 1         | 1.03%   |
| HP Deskjet 1050 J410                         | 1         | 1.03%   |
| Fuji Xerox DocuPrint P355 d                  | 1         | 1.03%   |
| Fuji Xerox DocuPrint P205 b                  | 1         | 1.03%   |
| Fuji Xerox DocuPrint CM315/318 z             | 1         | 1.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 9         | 60%     |
| Seiko Epson    | 4         | 26.67%  |
| Syscan         | 1         | 6.67%   |
| Mustek Systems | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 13.33%  |
| Canon CanoScan LiDE 210                                 | 2         | 13.33%  |
| Syscan TravelScan 460/464                               | 1         | 6.67%   |
| Seiko Epson Scanner                                     | 1         | 6.67%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.67%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.67%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 6.67%   |
| Canon CanoScan LiDE 220                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 300       | 21.95%  |
| Logitech                               | 130       | 9.51%   |
| Microdia                               | 115       | 8.41%   |
| Realtek Semiconductor                  | 109       | 7.97%   |
| Sunplus Innovation Technology          | 98        | 7.17%   |
| Apple                                  | 89        | 6.51%   |
| IMC Networks                           | 86        | 6.29%   |
| Acer                                   | 71        | 5.19%   |
| Quanta                                 | 49        | 3.58%   |
| Suyin                                  | 47        | 3.44%   |
| Cheng Uei Precision Industry (Foxlink) | 44        | 3.22%   |
| Microsoft                              | 31        | 2.27%   |
| Lite-On Technology                     | 25        | 1.83%   |
| Samsung Electronics                    | 19        | 1.39%   |
| Syntek                                 | 18        | 1.32%   |
| Silicon Motion                         | 10        | 0.73%   |
| Luxvisions Innotech Limited            | 10        | 0.73%   |
| Importek                               | 10        | 0.73%   |
| Ricoh                                  | 9         | 0.66%   |
| Lenovo                                 | 8         | 0.59%   |
| Alcor Micro                            | 8         | 0.59%   |
| Primax Electronics                     | 7         | 0.51%   |
| GEMBIRD                                | 7         | 0.51%   |
| Generalplus Technology                 | 5         | 0.37%   |
| OmniVision Technologies                | 4         | 0.29%   |
| Magic Control Technology               | 4         | 0.29%   |
| Genesys Logic                          | 4         | 0.29%   |
| Cubeternet                             | 4         | 0.29%   |
| Z-Star Microelectronics                | 3         | 0.22%   |
| Sonix Technology                       | 3         | 0.22%   |
| Razer USA                              | 3         | 0.22%   |
| LG Electronics                         | 3         | 0.22%   |
| DigiTech                               | 3         | 0.22%   |
| ALi                                    | 3         | 0.22%   |
| Unknown                                | 2         | 0.15%   |
| SunplusIT                              | 2         | 0.15%   |
| Asuscom Network                        | 2         | 0.15%   |
| Tobii Technology AB                    | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 56        | 4.02%   |
| Chicony Integrated Camera                               | 39        | 2.8%    |
| Realtek Integrated_Webcam_HD                            | 29        | 2.08%   |
| IMC Networks Integrated Camera                          | 26        | 1.87%   |
| Apple FaceTime HD Camera (Built-in)                     | 26        | 1.87%   |
| Sunplus Integrated_Webcam_HD                            | 24        | 1.72%   |
| Chicony TOSHIBA Web Camera - HD                         | 24        | 1.72%   |
| Chicony HD WebCam                                       | 24        | 1.72%   |
| Apple Built-in iSight                                   | 23        | 1.65%   |
| Apple iPhone5/5C/5S/6                                   | 21        | 1.51%   |
| Acer Integrated Camera                                  | 21        | 1.51%   |
| Samsung Galaxy A5 (MTP)                                 | 19        | 1.36%   |
| Logitech HD Pro Webcam C920                             | 19        | 1.36%   |
| Realtek USB Camera                                      | 18        | 1.29%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 17        | 1.22%   |
| Logitech Webcam C270                                    | 15        | 1.08%   |
| Chicony HP TrueVision HD Camera                         | 14        | 1%      |
| Syntek Integrated Camera                                | 13        | 0.93%   |
| Chicony HP HD Camera                                    | 13        | 0.93%   |
| Apple FaceTime HD Camera                                | 13        | 0.93%   |
| Sunplus HD WebCam                                       | 12        | 0.86%   |
| Chicony USB 2.0 Camera                                  | 12        | 0.86%   |
| Chicony HP TrueVision HD                                | 12        | 0.86%   |
| Chicony HD User Facing                                  | 12        | 0.86%   |
| Logitech Webcam C930e                                   | 11        | 0.79%   |
| Lite-On Integrated Camera                               | 11        | 0.79%   |
| Chicony USB2.0 Camera                                   | 11        | 0.79%   |
| Acer EasyCamera                                         | 11        | 0.79%   |
| Quanta HD User Facing                                   | 10        | 0.72%   |
| Microsoft LifeCam HD-3000                               | 10        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 0.72%   |
| Microdia Integrated Webcam                              | 9         | 0.65%   |
| Logitech Webcam C170                                    | 9         | 0.65%   |
| Logitech C922 Pro Stream Webcam                         | 9         | 0.65%   |
| Chicony CNF9055 Toshiba Webcam                          | 9         | 0.65%   |
| Suyin HP Truevision HD                                  | 8         | 0.57%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.57%   |
| Logitech HD Webcam C910                                 | 8         | 0.57%   |
| Quanta HP Webcam                                        | 7         | 0.5%    |
| Quanta HD Webcam                                        | 7         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 104       | 40.15%  |
| Synaptics                  | 64        | 24.71%  |
| Shenzhen Goodix Technology | 29        | 11.2%   |
| LighTuning Technology      | 18        | 6.95%   |
| AuthenTec                  | 14        | 5.41%   |
| Upek                       | 12        | 4.63%   |
| Elan Microelectronics      | 12        | 4.63%   |
| STMicroelectronics         | 6         | 2.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 7.34%   |
| Unknown                                                                    | 18        | 6.95%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 6.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 5.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 4.63%   |
| Validity Sensors VFS491                                                    | 9         | 3.47%   |
| Synaptics  WBDI                                                            | 9         | 3.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 3.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 3.09%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 3.09%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 3.09%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 3.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 7         | 2.7%    |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.7%    |
| Elan ELAN:Fingerprint                                                      | 7         | 2.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.32%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.32%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.32%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.93%   |
| Synaptics WBDI Device                                                      | 5         | 1.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.93%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.93%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 1.54%   |
| AuthenTec AES1600                                                          | 4         | 1.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.16%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.16%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.16%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.16%   |
| AuthenTec AES2810                                                          | 2         | 0.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.39%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.39%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 29        | 61.7%   |
| Alcor Micro           | 11        | 23.4%   |
| Upek                  | 2         | 4.26%   |
| O2 Micro              | 2         | 4.26%   |
| Lenovo                | 2         | 4.26%   |
| Advanced Card Systems | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 29.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 23.4%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 10.64%  |
| Broadcom 5880                                                                | 5         | 10.64%  |
| Broadcom 58200                                                               | 5         | 10.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.26%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.26%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1823      | 70.74%  |
| 1     | 625       | 24.25%  |
| 2     | 98        | 3.8%    |
| 3     | 22        | 0.85%   |
| 4     | 8         | 0.31%   |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 258       | 29.72%  |
| Graphics card            | 187       | 21.54%  |
| Net/wireless             | 136       | 15.67%  |
| Multimedia controller    | 47        | 5.41%   |
| Chipcard                 | 43        | 4.95%   |
| Communication controller | 40        | 4.61%   |
| Bluetooth                | 27        | 3.11%   |
| Camera                   | 26        | 3%      |
| Unassigned class         | 24        | 2.76%   |
| Sound                    | 15        | 1.73%   |
| Net/ethernet             | 15        | 1.73%   |
| Storage                  | 10        | 1.15%   |
| Dvb card                 | 8         | 0.92%   |
| Network                  | 7         | 0.81%   |
| Modem                    | 7         | 0.81%   |
| Card reader              | 7         | 0.81%   |
| Video                    | 2         | 0.23%   |
| Storage/raid             | 2         | 0.23%   |
| Storage/ata              | 2         | 0.23%   |
| Unclassified device      | 1         | 0.12%   |
| Tv card                  | 1         | 0.12%   |
| Storage/nvme             | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |

