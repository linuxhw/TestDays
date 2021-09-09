Fedora 34 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 34.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_34/Desktop/README.md) and [notebooks](/Dist/Fedora_34/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-34

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook 17 G5                 | Notebook    | [92b0b6c126](https://linux-hardware.org/?probe=92b0b6c126) | Sep 09, 2021 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [b9aae4c16e](https://linux-hardware.org/?probe=b9aae4c16e) | Sep 09, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [41e7d9f66e](https://linux-hardware.org/?probe=41e7d9f66e) | Sep 09, 2021 |
| ASRock        | Z390 Taichi                 | Desktop     | [8052fb9273](https://linux-hardware.org/?probe=8052fb9273) | Sep 09, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [03aad3f850](https://linux-hardware.org/?probe=03aad3f850) | Sep 09, 2021 |
| Intel         | A133L                       | Notebook    | [5958280b38](https://linux-hardware.org/?probe=5958280b38) | Sep 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| Google        | Delbin                      | Notebook    | [c5e8f37c1b](https://linux-hardware.org/?probe=c5e8f37c1b) | Sep 09, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [bd88876ddf](https://linux-hardware.org/?probe=bd88876ddf) | Sep 08, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [5b385a4866](https://linux-hardware.org/?probe=5b385a4866) | Sep 08, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [d387648c16](https://linux-hardware.org/?probe=d387648c16) | Sep 08, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| Lenovo        | Yoga 510-15ISK 80S8         | Convertible | [b5f8faae60](https://linux-hardware.org/?probe=b5f8faae60) | Sep 08, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [74bbee7dfb](https://linux-hardware.org/?probe=74bbee7dfb) | Sep 07, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [1585af0565](https://linux-hardware.org/?probe=1585af0565) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b6b99a61a3](https://linux-hardware.org/?probe=b6b99a61a3) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e6b54f6ad3](https://linux-hardware.org/?probe=e6b54f6ad3) | Sep 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b34fb7492d](https://linux-hardware.org/?probe=b34fb7492d) | Sep 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [feff42e39c](https://linux-hardware.org/?probe=feff42e39c) | Sep 07, 2021 |
| Acer          | Aspire 7738                 | Notebook    | [ab6b1bb415](https://linux-hardware.org/?probe=ab6b1bb415) | Sep 07, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [409ed1f8a4](https://linux-hardware.org/?probe=409ed1f8a4) | Sep 06, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [2b6a35c2e2](https://linux-hardware.org/?probe=2b6a35c2e2) | Sep 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [dcd49ffb0e](https://linux-hardware.org/?probe=dcd49ffb0e) | Sep 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8275c1d1e8](https://linux-hardware.org/?probe=8275c1d1e8) | Sep 06, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [a1ef6a3a8b](https://linux-hardware.org/?probe=a1ef6a3a8b) | Sep 06, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [546843fe50](https://linux-hardware.org/?probe=546843fe50) | Sep 06, 2021 |
| HP            | 2AF7                        | Desktop     | [ea75e63661](https://linux-hardware.org/?probe=ea75e63661) | Sep 06, 2021 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [498e35c473](https://linux-hardware.org/?probe=498e35c473) | Sep 06, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [b60c660326](https://linux-hardware.org/?probe=b60c660326) | Sep 06, 2021 |
| ASUSTek       | G11CD-K                     | Desktop     | [c4364afff6](https://linux-hardware.org/?probe=c4364afff6) | Sep 05, 2021 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | Notebook    | [51637c3908](https://linux-hardware.org/?probe=51637c3908) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [38256f8942](https://linux-hardware.org/?probe=38256f8942) | Sep 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [734b8a2cfa](https://linux-hardware.org/?probe=734b8a2cfa) | Sep 05, 2021 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [cc4ad372df](https://linux-hardware.org/?probe=cc4ad372df) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [78f1531e54](https://linux-hardware.org/?probe=78f1531e54) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [d306a73462](https://linux-hardware.org/?probe=d306a73462) | Sep 05, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ffa4f6aef7](https://linux-hardware.org/?probe=ffa4f6aef7) | Sep 05, 2021 |
| PC Special... | N150CU                      | Notebook    | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| ASUSTek       | X555QA                      | Notebook    | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [b1bb1e8325](https://linux-hardware.org/?probe=b1bb1e8325) | Sep 04, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [04ee8db8eb](https://linux-hardware.org/?probe=04ee8db8eb) | Sep 04, 2021 |
| HP            | 2AF7                        | Desktop     | [63afb7c7f5](https://linux-hardware.org/?probe=63afb7c7f5) | Sep 04, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [c1a354c2e2](https://linux-hardware.org/?probe=c1a354c2e2) | Sep 03, 2021 |
| HP            | 2B5E                        | Desktop     | [51682d8e81](https://linux-hardware.org/?probe=51682d8e81) | Sep 03, 2021 |
| HP            | 2B5E                        | Desktop     | [9fd111c3eb](https://linux-hardware.org/?probe=9fd111c3eb) | Sep 03, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [975a9765d5](https://linux-hardware.org/?probe=975a9765d5) | Sep 03, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [b27580d3b3](https://linux-hardware.org/?probe=b27580d3b3) | Sep 03, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [f617f97f20](https://linux-hardware.org/?probe=f617f97f20) | Sep 03, 2021 |
| HP            | 8056                        | Desktop     | [b9c18a445b](https://linux-hardware.org/?probe=b9c18a445b) | Sep 03, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | Notebook    | [4115bc0195](https://linux-hardware.org/?probe=4115bc0195) | Sep 03, 2021 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [ba2155b8b9](https://linux-hardware.org/?probe=ba2155b8b9) | Sep 03, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c55d1ba8bf](https://linux-hardware.org/?probe=c55d1ba8bf) | Sep 03, 2021 |
| HP            | Spectre Notebook            | Notebook    | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | Notebook    | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [43894b89a7](https://linux-hardware.org/?probe=43894b89a7) | Sep 02, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [972f2ce955](https://linux-hardware.org/?probe=972f2ce955) | Sep 02, 2021 |
| Dell          | Latitude E5420              | Notebook    | [7cbabbfdf3](https://linux-hardware.org/?probe=7cbabbfdf3) | Sep 02, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a72ba74a3f](https://linux-hardware.org/?probe=a72ba74a3f) | Sep 02, 2021 |
| Dell          | Latitude 5580               | Notebook    | [2d949d7117](https://linux-hardware.org/?probe=2d949d7117) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [167e800e3a](https://linux-hardware.org/?probe=167e800e3a) | Sep 02, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [724ad5d6a2](https://linux-hardware.org/?probe=724ad5d6a2) | Sep 02, 2021 |
| Positivo      | C41TB                       | Notebook    | [d100e19cde](https://linux-hardware.org/?probe=d100e19cde) | Sep 01, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [5e4bbca202](https://linux-hardware.org/?probe=5e4bbca202) | Sep 01, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [79afad37d2](https://linux-hardware.org/?probe=79afad37d2) | Sep 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [d2f0fba8f9](https://linux-hardware.org/?probe=d2f0fba8f9) | Sep 01, 2021 |
| Dell          | Latitude E7270              | Notebook    | [1bd5f17116](https://linux-hardware.org/?probe=1bd5f17116) | Sep 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [7bb30a79c1](https://linux-hardware.org/?probe=7bb30a79c1) | Sep 01, 2021 |
| Positivo      | C41TB                       | Notebook    | [e904092d0d](https://linux-hardware.org/?probe=e904092d0d) | Sep 01, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [37c4ed4ed7](https://linux-hardware.org/?probe=37c4ed4ed7) | Sep 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [6ce2d4fb15](https://linux-hardware.org/?probe=6ce2d4fb15) | Sep 01, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [20389db1bd](https://linux-hardware.org/?probe=20389db1bd) | Aug 31, 2021 |
| Lenovo        | ThinkPad T490 20N2S13B00    | Notebook    | [504e179093](https://linux-hardware.org/?probe=504e179093) | Aug 31, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [44eda17ebc](https://linux-hardware.org/?probe=44eda17ebc) | Aug 31, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [1f13431849](https://linux-hardware.org/?probe=1f13431849) | Aug 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3ccd4032a1](https://linux-hardware.org/?probe=3ccd4032a1) | Aug 31, 2021 |
| Dell          | Latitude 7400               | Notebook    | [256ab697f4](https://linux-hardware.org/?probe=256ab697f4) | Aug 31, 2021 |
| HP            | 2AF7                        | Desktop     | [38b5cbf28d](https://linux-hardware.org/?probe=38b5cbf28d) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [96d9d18052](https://linux-hardware.org/?probe=96d9d18052) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [fb5e0539da](https://linux-hardware.org/?probe=fb5e0539da) | Aug 31, 2021 |
| Dell          | G5 5500                     | Notebook    | [50db6e93f1](https://linux-hardware.org/?probe=50db6e93f1) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [05321484a1](https://linux-hardware.org/?probe=05321484a1) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e014d83782](https://linux-hardware.org/?probe=e014d83782) | Aug 31, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e134361dc2](https://linux-hardware.org/?probe=e134361dc2) | Aug 31, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [3b8f234fa8](https://linux-hardware.org/?probe=3b8f234fa8) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [0cdd08839f](https://linux-hardware.org/?probe=0cdd08839f) | Aug 31, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [997ce785b2](https://linux-hardware.org/?probe=997ce785b2) | Aug 31, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [6f0e81a6d9](https://linux-hardware.org/?probe=6f0e81a6d9) | Aug 31, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [c4b5fdc75f](https://linux-hardware.org/?probe=c4b5fdc75f) | Aug 30, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [dcc0bda879](https://linux-hardware.org/?probe=dcc0bda879) | Aug 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [e8370d3b93](https://linux-hardware.org/?probe=e8370d3b93) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [548bf9f816](https://linux-hardware.org/?probe=548bf9f816) | Aug 30, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [75cbc94a98](https://linux-hardware.org/?probe=75cbc94a98) | Aug 30, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6d630f76dc](https://linux-hardware.org/?probe=6d630f76dc) | Aug 30, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9a3be042e0](https://linux-hardware.org/?probe=9a3be042e0) | Aug 30, 2021 |
| HP            | 8056                        | Desktop     | [8614fae216](https://linux-hardware.org/?probe=8614fae216) | Aug 30, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8d862a60c9](https://linux-hardware.org/?probe=8d862a60c9) | Aug 29, 2021 |
| VINGA         | Iron S140                   | Notebook    | [8a48730847](https://linux-hardware.org/?probe=8a48730847) | Aug 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ff35c10221](https://linux-hardware.org/?probe=ff35c10221) | Aug 29, 2021 |
| HP            | 198E                        | Desktop     | [82d1a8a5a7](https://linux-hardware.org/?probe=82d1a8a5a7) | Aug 29, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e539faacf5](https://linux-hardware.org/?probe=e539faacf5) | Aug 29, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [fce2351650](https://linux-hardware.org/?probe=fce2351650) | Aug 29, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [d2b4c85e96](https://linux-hardware.org/?probe=d2b4c85e96) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [3d54bf05f1](https://linux-hardware.org/?probe=3d54bf05f1) | Aug 28, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cf5f33a843](https://linux-hardware.org/?probe=cf5f33a843) | Aug 28, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [313b97b58c](https://linux-hardware.org/?probe=313b97b58c) | Aug 28, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [5fd92a80fa](https://linux-hardware.org/?probe=5fd92a80fa) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [8f10e30326](https://linux-hardware.org/?probe=8f10e30326) | Aug 28, 2021 |
| Lenovo        | Board                       | Desktop     | [ec9c58b54e](https://linux-hardware.org/?probe=ec9c58b54e) | Aug 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4331eedde2](https://linux-hardware.org/?probe=4331eedde2) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [614ac09d36](https://linux-hardware.org/?probe=614ac09d36) | Aug 28, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [d8daca96d1](https://linux-hardware.org/?probe=d8daca96d1) | Aug 28, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ece0ff2fa3](https://linux-hardware.org/?probe=ece0ff2fa3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [53d712fdcb](https://linux-hardware.org/?probe=53d712fdcb) | Aug 28, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [d46f0b24a4](https://linux-hardware.org/?probe=d46f0b24a4) | Aug 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [3c31559d95](https://linux-hardware.org/?probe=3c31559d95) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7945f91910](https://linux-hardware.org/?probe=7945f91910) | Aug 28, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [830bfb129f](https://linux-hardware.org/?probe=830bfb129f) | Aug 27, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [39ae07c4d8](https://linux-hardware.org/?probe=39ae07c4d8) | Aug 27, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [c8010f8066](https://linux-hardware.org/?probe=c8010f8066) | Aug 27, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [9b218c7903](https://linux-hardware.org/?probe=9b218c7903) | Aug 27, 2021 |
| MSI           | A320M-A PRO M2              | Desktop     | [fda90307d4](https://linux-hardware.org/?probe=fda90307d4) | Aug 27, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [877e0e98a4](https://linux-hardware.org/?probe=877e0e98a4) | Aug 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1e4bb62683](https://linux-hardware.org/?probe=1e4bb62683) | Aug 27, 2021 |
| ASUSTek       | P6T                         | Desktop     | [ad049817af](https://linux-hardware.org/?probe=ad049817af) | Aug 27, 2021 |
| HP            | 8056                        | Desktop     | [e64dab1375](https://linux-hardware.org/?probe=e64dab1375) | Aug 27, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [7e3f5621ba](https://linux-hardware.org/?probe=7e3f5621ba) | Aug 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [a0ed3c6558](https://linux-hardware.org/?probe=a0ed3c6558) | Aug 27, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [adde1df1d0](https://linux-hardware.org/?probe=adde1df1d0) | Aug 27, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [21f8762e74](https://linux-hardware.org/?probe=21f8762e74) | Aug 26, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [63104dc43a](https://linux-hardware.org/?probe=63104dc43a) | Aug 26, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [42184613d7](https://linux-hardware.org/?probe=42184613d7) | Aug 26, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [6e2699cc9e](https://linux-hardware.org/?probe=6e2699cc9e) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Acer          | Aspire 5516                 | Notebook    | [5c779547e8](https://linux-hardware.org/?probe=5c779547e8) | Aug 26, 2021 |
| Maibenben     | S431                        | Notebook    | [6950bbec9b](https://linux-hardware.org/?probe=6950bbec9b) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [a663972867](https://linux-hardware.org/?probe=a663972867) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d29deaa58e](https://linux-hardware.org/?probe=d29deaa58e) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| System76      | Oryx Pro                    | Notebook    | [766916b305](https://linux-hardware.org/?probe=766916b305) | Aug 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2c4c7620cc](https://linux-hardware.org/?probe=2c4c7620cc) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48121667a9](https://linux-hardware.org/?probe=48121667a9) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3e39cc51a8](https://linux-hardware.org/?probe=3e39cc51a8) | Aug 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [74a9538d04](https://linux-hardware.org/?probe=74a9538d04) | Aug 25, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [dcd95a7374](https://linux-hardware.org/?probe=dcd95a7374) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [11d9254c35](https://linux-hardware.org/?probe=11d9254c35) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [778e5aa3ae](https://linux-hardware.org/?probe=778e5aa3ae) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [15552cf8da](https://linux-hardware.org/?probe=15552cf8da) | Aug 24, 2021 |
| Dell          | 0HH807                      | Desktop     | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1ab639abb8](https://linux-hardware.org/?probe=1ab639abb8) | Aug 24, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | Notebook    | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [bb902b38e1](https://linux-hardware.org/?probe=bb902b38e1) | Aug 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Sony          | VPCEH16EN                   | Notebook    | [b74cb4b68e](https://linux-hardware.org/?probe=b74cb4b68e) | Aug 24, 2021 |
| HP            | EliteBook 820 G4            | Notebook    | [5d6a3388dc](https://linux-hardware.org/?probe=5d6a3388dc) | Aug 24, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [ffd49f5a01](https://linux-hardware.org/?probe=ffd49f5a01) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [25ce57f1be](https://linux-hardware.org/?probe=25ce57f1be) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [cef75c8a5a](https://linux-hardware.org/?probe=cef75c8a5a) | Aug 23, 2021 |
| Biostar       | A68I-450 DELUXE             | Desktop     | [3e0a375af7](https://linux-hardware.org/?probe=3e0a375af7) | Aug 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [847e7f4c1a](https://linux-hardware.org/?probe=847e7f4c1a) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Supermicro    | X10DRi                      | Server      | [c04f902b93](https://linux-hardware.org/?probe=c04f902b93) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [014af10464](https://linux-hardware.org/?probe=014af10464) | Aug 23, 2021 |
| HP            | 8056                        | Desktop     | [d604c95726](https://linux-hardware.org/?probe=d604c95726) | Aug 23, 2021 |
| Dell          | 0F3KHR A01                  | Desktop     | [b5bc473971](https://linux-hardware.org/?probe=b5bc473971) | Aug 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [e506f7ea95](https://linux-hardware.org/?probe=e506f7ea95) | Aug 23, 2021 |
| HP            | 14                          | Notebook    | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [07d9074437](https://linux-hardware.org/?probe=07d9074437) | Aug 23, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Timi          | A35S                        | Notebook    | [d00b7954e8](https://linux-hardware.org/?probe=d00b7954e8) | Aug 23, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [c682421190](https://linux-hardware.org/?probe=c682421190) | Aug 23, 2021 |
| Positivo      | C14CR21                     | Notebook    | [c4ae2acc0b](https://linux-hardware.org/?probe=c4ae2acc0b) | Aug 23, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [0cd9bde7b4](https://linux-hardware.org/?probe=0cd9bde7b4) | Aug 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7373f6a54d](https://linux-hardware.org/?probe=7373f6a54d) | Aug 22, 2021 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [1ba570a081](https://linux-hardware.org/?probe=1ba570a081) | Aug 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3d417f197c](https://linux-hardware.org/?probe=3d417f197c) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [b6390e7b7d](https://linux-hardware.org/?probe=b6390e7b7d) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [2ec395c6ca](https://linux-hardware.org/?probe=2ec395c6ca) | Aug 22, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f983e2baca](https://linux-hardware.org/?probe=f983e2baca) | Aug 22, 2021 |
| MSI           | GP62MVR 7RFX                | Notebook    | [64a52a91b1](https://linux-hardware.org/?probe=64a52a91b1) | Aug 22, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [07e3a21f1c](https://linux-hardware.org/?probe=07e3a21f1c) | Aug 22, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b2190e55e8](https://linux-hardware.org/?probe=b2190e55e8) | Aug 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7f439ff799](https://linux-hardware.org/?probe=7f439ff799) | Aug 22, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [971dc3b5c7](https://linux-hardware.org/?probe=971dc3b5c7) | Aug 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [987edc4158](https://linux-hardware.org/?probe=987edc4158) | Aug 21, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [a428352ddc](https://linux-hardware.org/?probe=a428352ddc) | Aug 21, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [1215c27927](https://linux-hardware.org/?probe=1215c27927) | Aug 21, 2021 |
| Dell          | Inspiron 13-7359            | Notebook    | [555a25c577](https://linux-hardware.org/?probe=555a25c577) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [edc2f605d1](https://linux-hardware.org/?probe=edc2f605d1) | Aug 21, 2021 |
| ASUSTek       | UX303UA                     | Notebook    | [6f88337886](https://linux-hardware.org/?probe=6f88337886) | Aug 21, 2021 |
| Sony          | SVS1511X9RB                 | Notebook    | [5ee85bc3a6](https://linux-hardware.org/?probe=5ee85bc3a6) | Aug 21, 2021 |
| Sony          | SVS1511X9RB                 | Notebook    | [77326cdac5](https://linux-hardware.org/?probe=77326cdac5) | Aug 21, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [112c79071e](https://linux-hardware.org/?probe=112c79071e) | Aug 21, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [4a611b712a](https://linux-hardware.org/?probe=4a611b712a) | Aug 21, 2021 |
| HP            | 2AF7                        | Desktop     | [beb4167201](https://linux-hardware.org/?probe=beb4167201) | Aug 21, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | EliteBook 820 G4            | Notebook    | [d31c0fcaac](https://linux-hardware.org/?probe=d31c0fcaac) | Aug 21, 2021 |
| Dell          | Latitude 7400               | Notebook    | [61fd9efe24](https://linux-hardware.org/?probe=61fd9efe24) | Aug 21, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c673203c6b](https://linux-hardware.org/?probe=c673203c6b) | Aug 20, 2021 |
| Dell          | XPS L702X                   | Notebook    | [32448925cb](https://linux-hardware.org/?probe=32448925cb) | Aug 20, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [6136df7463](https://linux-hardware.org/?probe=6136df7463) | Aug 20, 2021 |
| Dell          | XPS L702X                   | Notebook    | [93f7edad9b](https://linux-hardware.org/?probe=93f7edad9b) | Aug 20, 2021 |
| ASUSTek       | P6T                         | Desktop     | [d0495a4765](https://linux-hardware.org/?probe=d0495a4765) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [1d1d8a4620](https://linux-hardware.org/?probe=1d1d8a4620) | Aug 20, 2021 |
| Chuwi         | UBook X                     | Tablet      | [5a15d9b82a](https://linux-hardware.org/?probe=5a15d9b82a) | Aug 20, 2021 |
| Lenovo        | ThinkPad P43s 20RJS1C200    | Notebook    | [3dab4fd1db](https://linux-hardware.org/?probe=3dab4fd1db) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4b37f6047e](https://linux-hardware.org/?probe=4b37f6047e) | Aug 20, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e49dbd40b5](https://linux-hardware.org/?probe=e49dbd40b5) | Aug 20, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [41874518ea](https://linux-hardware.org/?probe=41874518ea) | Aug 20, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [bf0f2ff4a0](https://linux-hardware.org/?probe=bf0f2ff4a0) | Aug 20, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [78feb5ae08](https://linux-hardware.org/?probe=78feb5ae08) | Aug 20, 2021 |
| Lenovo        | ThinkPad T580 20LAS5XS00    | Notebook    | [472494a25c](https://linux-hardware.org/?probe=472494a25c) | Aug 20, 2021 |
| BESSTAR Te... | HM80                        | Desktop     | [60fdee03d6](https://linux-hardware.org/?probe=60fdee03d6) | Aug 19, 2021 |
| HP            | 83E9                        | Desktop     | [21b492b0bf](https://linux-hardware.org/?probe=21b492b0bf) | Aug 19, 2021 |
| HP            | 83E9                        | Desktop     | [7cb2c3256a](https://linux-hardware.org/?probe=7cb2c3256a) | Aug 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [70e32af3f7](https://linux-hardware.org/?probe=70e32af3f7) | Aug 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [84153c2a8d](https://linux-hardware.org/?probe=84153c2a8d) | Aug 19, 2021 |
| Alienware     | 15 R4                       | Notebook    | [bd2c12701c](https://linux-hardware.org/?probe=bd2c12701c) | Aug 19, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [0d33aed04c](https://linux-hardware.org/?probe=0d33aed04c) | Aug 19, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [b9d5b6e9e9](https://linux-hardware.org/?probe=b9d5b6e9e9) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [5019993be7](https://linux-hardware.org/?probe=5019993be7) | Aug 19, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [2aed19ac0a](https://linux-hardware.org/?probe=2aed19ac0a) | Aug 19, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5c3e90c735](https://linux-hardware.org/?probe=5c3e90c735) | Aug 19, 2021 |
| Notebook      | N150CU                      | Notebook    | [8d2621da6a](https://linux-hardware.org/?probe=8d2621da6a) | Aug 19, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [07fc61d3ba](https://linux-hardware.org/?probe=07fc61d3ba) | Aug 19, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d789709af4](https://linux-hardware.org/?probe=d789709af4) | Aug 19, 2021 |
| Gigabyte      | P55-USB3                    | Desktop     | [5e6a1d1926](https://linux-hardware.org/?probe=5e6a1d1926) | Aug 19, 2021 |
| HP            | 8056                        | Desktop     | [44b754f972](https://linux-hardware.org/?probe=44b754f972) | Aug 19, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [24f73e707a](https://linux-hardware.org/?probe=24f73e707a) | Aug 18, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [6c1ab8d85f](https://linux-hardware.org/?probe=6c1ab8d85f) | Aug 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6eaf105bca](https://linux-hardware.org/?probe=6eaf105bca) | Aug 18, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [7731a3a1da](https://linux-hardware.org/?probe=7731a3a1da) | Aug 18, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [64adb81ad2](https://linux-hardware.org/?probe=64adb81ad2) | Aug 18, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [2e4833ff3b](https://linux-hardware.org/?probe=2e4833ff3b) | Aug 18, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [366e1c4e64](https://linux-hardware.org/?probe=366e1c4e64) | Aug 18, 2021 |
| HP            | 2AF7                        | Desktop     | [909c6f5c0a](https://linux-hardware.org/?probe=909c6f5c0a) | Aug 18, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [efead486a3](https://linux-hardware.org/?probe=efead486a3) | Aug 18, 2021 |
| HP            | 82F2 A01                    | Desktop     | [b6847d9605](https://linux-hardware.org/?probe=b6847d9605) | Aug 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [5c3c22a21d](https://linux-hardware.org/?probe=5c3c22a21d) | Aug 17, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [affdbcbf08](https://linux-hardware.org/?probe=affdbcbf08) | Aug 17, 2021 |
| ASRock        | B460M-ITX/ac                | Desktop     | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [28cd688d16](https://linux-hardware.org/?probe=28cd688d16) | Aug 17, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [63a8a28fd9](https://linux-hardware.org/?probe=63a8a28fd9) | Aug 17, 2021 |
| HP            | 8056                        | Desktop     | [5607e09042](https://linux-hardware.org/?probe=5607e09042) | Aug 17, 2021 |
| Acer          | S7-392                      | Notebook    | [1251d42538](https://linux-hardware.org/?probe=1251d42538) | Aug 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [584785653a](https://linux-hardware.org/?probe=584785653a) | Aug 17, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [43ee57ed48](https://linux-hardware.org/?probe=43ee57ed48) | Aug 17, 2021 |
| Acer          | Aspire A515-46              | Notebook    | [ad8f403c6d](https://linux-hardware.org/?probe=ad8f403c6d) | Aug 17, 2021 |
| Dell          | Latitude E6510              | Notebook    | [b7071ddea1](https://linux-hardware.org/?probe=b7071ddea1) | Aug 17, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [4d3d87b641](https://linux-hardware.org/?probe=4d3d87b641) | Aug 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d64c2407ca](https://linux-hardware.org/?probe=d64c2407ca) | Aug 17, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [86101835e0](https://linux-hardware.org/?probe=86101835e0) | Aug 17, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [10cec0686e](https://linux-hardware.org/?probe=10cec0686e) | Aug 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [78a3158393](https://linux-hardware.org/?probe=78a3158393) | Aug 16, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [1c581950df](https://linux-hardware.org/?probe=1c581950df) | Aug 16, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| HP            | 198E                        | Desktop     | [d1c56bffb1](https://linux-hardware.org/?probe=d1c56bffb1) | Aug 15, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [86f9693894](https://linux-hardware.org/?probe=86f9693894) | Aug 15, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [2864cc0f2a](https://linux-hardware.org/?probe=2864cc0f2a) | Aug 15, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [b29b9f86ab](https://linux-hardware.org/?probe=b29b9f86ab) | Aug 15, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [31c30e5c1f](https://linux-hardware.org/?probe=31c30e5c1f) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [419995b0da](https://linux-hardware.org/?probe=419995b0da) | Aug 15, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [f931b86af5](https://linux-hardware.org/?probe=f931b86af5) | Aug 15, 2021 |
| Lenovo        | Board                       | Desktop     | [cd8825c8d0](https://linux-hardware.org/?probe=cd8825c8d0) | Aug 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [41e2825c3d](https://linux-hardware.org/?probe=41e2825c3d) | Aug 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [d34022df3b](https://linux-hardware.org/?probe=d34022df3b) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b8722b62ff](https://linux-hardware.org/?probe=b8722b62ff) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [eda5da5e9d](https://linux-hardware.org/?probe=eda5da5e9d) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [518309e6c8](https://linux-hardware.org/?probe=518309e6c8) | Aug 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7df108445b](https://linux-hardware.org/?probe=7df108445b) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [e93a65b9cf](https://linux-hardware.org/?probe=e93a65b9cf) | Aug 14, 2021 |
| Framework     | Laptop                      | Notebook    | [bd868e3985](https://linux-hardware.org/?probe=bd868e3985) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [5f49d58f42](https://linux-hardware.org/?probe=5f49d58f42) | Aug 14, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [7d0c7834be](https://linux-hardware.org/?probe=7d0c7834be) | Aug 14, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [c7d0df9fbb](https://linux-hardware.org/?probe=c7d0df9fbb) | Aug 13, 2021 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4a9b684e95](https://linux-hardware.org/?probe=4a9b684e95) | Aug 13, 2021 |
| HP            | Pavilion dv7                | Notebook    | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [05bfca3339](https://linux-hardware.org/?probe=05bfca3339) | Aug 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [32bc94c4e2](https://linux-hardware.org/?probe=32bc94c4e2) | Aug 13, 2021 |
| Intel         | B75                         | Desktop     | [2bac7a8140](https://linux-hardware.org/?probe=2bac7a8140) | Aug 13, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [07f3a8a2c9](https://linux-hardware.org/?probe=07f3a8a2c9) | Aug 13, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bfd432fba](https://linux-hardware.org/?probe=8bfd432fba) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [5e9853124d](https://linux-hardware.org/?probe=5e9853124d) | Aug 13, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [10db213e5d](https://linux-hardware.org/?probe=10db213e5d) | Aug 13, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [13558f63ab](https://linux-hardware.org/?probe=13558f63ab) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6f0b883adb](https://linux-hardware.org/?probe=6f0b883adb) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [5d036af9c0](https://linux-hardware.org/?probe=5d036af9c0) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0b46a87be6](https://linux-hardware.org/?probe=0b46a87be6) | Aug 13, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [f8af262ae5](https://linux-hardware.org/?probe=f8af262ae5) | Aug 13, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [f4dd349090](https://linux-hardware.org/?probe=f4dd349090) | Aug 13, 2021 |
| Dell          | 03NVJ6 A01                  | Desktop     | [ef0028e285](https://linux-hardware.org/?probe=ef0028e285) | Aug 12, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| Acer          | Aspire E5-574               | Notebook    | [7fb046bc6a](https://linux-hardware.org/?probe=7fb046bc6a) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [3ed6340d82](https://linux-hardware.org/?probe=3ed6340d82) | Aug 12, 2021 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [adae4a7ada](https://linux-hardware.org/?probe=adae4a7ada) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [5f70360eea](https://linux-hardware.org/?probe=5f70360eea) | Aug 12, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [7b708488a2](https://linux-hardware.org/?probe=7b708488a2) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [aeec0ec477](https://linux-hardware.org/?probe=aeec0ec477) | Aug 12, 2021 |
| Acer          | Aspire TC-705               | Desktop     | [bbf5c161d3](https://linux-hardware.org/?probe=bbf5c161d3) | Aug 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| Alienware     | x17 R1                      | Notebook    | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [f1eabffafd](https://linux-hardware.org/?probe=f1eabffafd) | Aug 12, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [745332d76b](https://linux-hardware.org/?probe=745332d76b) | Aug 12, 2021 |
| HP            | 8056                        | Desktop     | [afe5072bf8](https://linux-hardware.org/?probe=afe5072bf8) | Aug 12, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [34848a17dc](https://linux-hardware.org/?probe=34848a17dc) | Aug 12, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2e9babd6f4](https://linux-hardware.org/?probe=2e9babd6f4) | Aug 11, 2021 |
| HP            | Pavilion 15                 | Notebook    | [4e8387b8e9](https://linux-hardware.org/?probe=4e8387b8e9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [42368b3305](https://linux-hardware.org/?probe=42368b3305) | Aug 10, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6808748401](https://linux-hardware.org/?probe=6808748401) | Aug 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7ee6c3801e](https://linux-hardware.org/?probe=7ee6c3801e) | Aug 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [02a92f8ff3](https://linux-hardware.org/?probe=02a92f8ff3) | Aug 10, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [d8e685c049](https://linux-hardware.org/?probe=d8e685c049) | Aug 10, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Dell          | Precision 5530              | Notebook    | [e1f4582882](https://linux-hardware.org/?probe=e1f4582882) | Aug 09, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [dc5848146e](https://linux-hardware.org/?probe=dc5848146e) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [c3b36c30d8](https://linux-hardware.org/?probe=c3b36c30d8) | Aug 09, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b1cab0fd9c](https://linux-hardware.org/?probe=b1cab0fd9c) | Aug 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8ad0df4157](https://linux-hardware.org/?probe=8ad0df4157) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [985e447ff5](https://linux-hardware.org/?probe=985e447ff5) | Aug 09, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [fac88c2a70](https://linux-hardware.org/?probe=fac88c2a70) | Aug 09, 2021 |
| HP            | ProBook 6465b               | Notebook    | [8d7f457e6e](https://linux-hardware.org/?probe=8d7f457e6e) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | Notebook    | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [fa2d2aa603](https://linux-hardware.org/?probe=fa2d2aa603) | Aug 09, 2021 |
| ASUSTek       | ZenBook 13 UX331FN_UX331... | Notebook    | [fe9a44853c](https://linux-hardware.org/?probe=fe9a44853c) | Aug 08, 2021 |
| Biostar       | X370GTN                     | Desktop     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [ec3a3d05e5](https://linux-hardware.org/?probe=ec3a3d05e5) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [795328301d](https://linux-hardware.org/?probe=795328301d) | Aug 08, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a81ec533a8](https://linux-hardware.org/?probe=a81ec533a8) | Aug 08, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1a68be3ffe](https://linux-hardware.org/?probe=1a68be3ffe) | Aug 08, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [feacdb6873](https://linux-hardware.org/?probe=feacdb6873) | Aug 08, 2021 |
| HP            | 1998                        | Desktop     | [38acf34efb](https://linux-hardware.org/?probe=38acf34efb) | Aug 08, 2021 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [8e1e7782d9](https://linux-hardware.org/?probe=8e1e7782d9) | Aug 08, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [f51ff5d22f](https://linux-hardware.org/?probe=f51ff5d22f) | Aug 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5a46a3aa4a](https://linux-hardware.org/?probe=5a46a3aa4a) | Aug 07, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [7b24aa2b0c](https://linux-hardware.org/?probe=7b24aa2b0c) | Aug 07, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a18e7eaaa9](https://linux-hardware.org/?probe=a18e7eaaa9) | Aug 07, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [d2819f7f94](https://linux-hardware.org/?probe=d2819f7f94) | Aug 07, 2021 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [4d2a5f5d27](https://linux-hardware.org/?probe=4d2a5f5d27) | Aug 07, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [322608eeb3](https://linux-hardware.org/?probe=322608eeb3) | Aug 07, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [2dd10ed83f](https://linux-hardware.org/?probe=2dd10ed83f) | Aug 07, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [e04191385a](https://linux-hardware.org/?probe=e04191385a) | Aug 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [dd86f5be32](https://linux-hardware.org/?probe=dd86f5be32) | Aug 06, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [20b75d980d](https://linux-hardware.org/?probe=20b75d980d) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4c87b2ff27](https://linux-hardware.org/?probe=4c87b2ff27) | Aug 06, 2021 |
| Dell          | Inspiron 5323               | Notebook    | [3600f5a7a8](https://linux-hardware.org/?probe=3600f5a7a8) | Aug 06, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [4c2763b512](https://linux-hardware.org/?probe=4c2763b512) | Aug 06, 2021 |
| Notebook      | Titanium B155 MAX           | Notebook    | [f1fd39abcd](https://linux-hardware.org/?probe=f1fd39abcd) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [a41678d0ce](https://linux-hardware.org/?probe=a41678d0ce) | Aug 06, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [6a9e7d18fc](https://linux-hardware.org/?probe=6a9e7d18fc) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [aea38e48c7](https://linux-hardware.org/?probe=aea38e48c7) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| Notebook      | Titanium B155 MAX           | Notebook    | [2311d7a604](https://linux-hardware.org/?probe=2311d7a604) | Aug 05, 2021 |
| Dell          | Latitude 7410               | Notebook    | [013122833c](https://linux-hardware.org/?probe=013122833c) | Aug 05, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f74df24802](https://linux-hardware.org/?probe=f74df24802) | Aug 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a5e93c2b7f](https://linux-hardware.org/?probe=a5e93c2b7f) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6fe693a80e](https://linux-hardware.org/?probe=6fe693a80e) | Aug 05, 2021 |
| HP            | 8432                        | All in one  | [ab036fdfb9](https://linux-hardware.org/?probe=ab036fdfb9) | Aug 05, 2021 |
| HP            | ProBook 6465b               | Notebook    | [73822c2796](https://linux-hardware.org/?probe=73822c2796) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [234f1782ff](https://linux-hardware.org/?probe=234f1782ff) | Aug 05, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2fbf46c559](https://linux-hardware.org/?probe=2fbf46c559) | Aug 05, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [a096b9bb71](https://linux-hardware.org/?probe=a096b9bb71) | Aug 05, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [7c04b89c8a](https://linux-hardware.org/?probe=7c04b89c8a) | Aug 04, 2021 |
| HP            | Pavilion dv6                | Notebook    | [87b441ff00](https://linux-hardware.org/?probe=87b441ff00) | Aug 04, 2021 |
| Dell          | Inspiron 5370               | Notebook    | [40360bb1e3](https://linux-hardware.org/?probe=40360bb1e3) | Aug 04, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [dfb3b0302c](https://linux-hardware.org/?probe=dfb3b0302c) | Aug 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e70f3ab4cd](https://linux-hardware.org/?probe=e70f3ab4cd) | Aug 04, 2021 |
| ASUSTek       | K75DE                       | Notebook    | [139840a80c](https://linux-hardware.org/?probe=139840a80c) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [b3ae79f78f](https://linux-hardware.org/?probe=b3ae79f78f) | Aug 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d4f12adb88](https://linux-hardware.org/?probe=d4f12adb88) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [a124194272](https://linux-hardware.org/?probe=a124194272) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [dce96ae07e](https://linux-hardware.org/?probe=dce96ae07e) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [345ce8fb64](https://linux-hardware.org/?probe=345ce8fb64) | Aug 04, 2021 |
| HP            | 82F2 A01                    | Desktop     | [b6b124c434](https://linux-hardware.org/?probe=b6b124c434) | Aug 03, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b1d2bc3821](https://linux-hardware.org/?probe=b1d2bc3821) | Aug 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f776a4eb93](https://linux-hardware.org/?probe=f776a4eb93) | Aug 03, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [bed31de6b8](https://linux-hardware.org/?probe=bed31de6b8) | Aug 03, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [4d3a4d6db1](https://linux-hardware.org/?probe=4d3a4d6db1) | Aug 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [3f857761fa](https://linux-hardware.org/?probe=3f857761fa) | Aug 03, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [ad5bc52a88](https://linux-hardware.org/?probe=ad5bc52a88) | Aug 03, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [323ac43e6d](https://linux-hardware.org/?probe=323ac43e6d) | Aug 03, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [5e01ce0d4f](https://linux-hardware.org/?probe=5e01ce0d4f) | Aug 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [39919aab55](https://linux-hardware.org/?probe=39919aab55) | Aug 02, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [cc58c27c6f](https://linux-hardware.org/?probe=cc58c27c6f) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [847bf89546](https://linux-hardware.org/?probe=847bf89546) | Aug 02, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d09a20ffb6](https://linux-hardware.org/?probe=d09a20ffb6) | Aug 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [454fecb7fb](https://linux-hardware.org/?probe=454fecb7fb) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E440 20C50... | Notebook    | [ba11bbceb8](https://linux-hardware.org/?probe=ba11bbceb8) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c18e0a53fc](https://linux-hardware.org/?probe=c18e0a53fc) | Aug 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ba0a55bf85](https://linux-hardware.org/?probe=ba0a55bf85) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [8431041495](https://linux-hardware.org/?probe=8431041495) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [8218aa8198](https://linux-hardware.org/?probe=8218aa8198) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0d6c963f0e](https://linux-hardware.org/?probe=0d6c963f0e) | Jul 31, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [c0d8e5adf6](https://linux-hardware.org/?probe=c0d8e5adf6) | Jul 31, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [052a6762c4](https://linux-hardware.org/?probe=052a6762c4) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e88f8edeb9](https://linux-hardware.org/?probe=e88f8edeb9) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e5e3591da2](https://linux-hardware.org/?probe=e5e3591da2) | Jul 31, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2b00e34271](https://linux-hardware.org/?probe=2b00e34271) | Jul 31, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [4a5ead6209](https://linux-hardware.org/?probe=4a5ead6209) | Jul 31, 2021 |
| HONOR         | NBD-WXX9                    | Notebook    | [2b6a0f8576](https://linux-hardware.org/?probe=2b6a0f8576) | Jul 31, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [b92fbcc1fd](https://linux-hardware.org/?probe=b92fbcc1fd) | Jul 31, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [07d66d0963](https://linux-hardware.org/?probe=07d66d0963) | Jul 30, 2021 |
| Timi          | A35S                        | Notebook    | [dfd89e45de](https://linux-hardware.org/?probe=dfd89e45de) | Jul 30, 2021 |
| Dell          | Inspiron 5323               | Notebook    | [52700f62dc](https://linux-hardware.org/?probe=52700f62dc) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | Notebook    | [23d664d987](https://linux-hardware.org/?probe=23d664d987) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | Notebook    | [95a364c010](https://linux-hardware.org/?probe=95a364c010) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | Notebook    | [a95b853ed8](https://linux-hardware.org/?probe=a95b853ed8) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b5a0d25d72](https://linux-hardware.org/?probe=b5a0d25d72) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e842eefc11](https://linux-hardware.org/?probe=e842eefc11) | Jul 29, 2021 |
| Acer          | Aspire E5-576               | Notebook    | [11d9b03eca](https://linux-hardware.org/?probe=11d9b03eca) | Jul 29, 2021 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [ae31c59ee8](https://linux-hardware.org/?probe=ae31c59ee8) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [20e3d5c8af](https://linux-hardware.org/?probe=20e3d5c8af) | Jul 29, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [6933a56e5a](https://linux-hardware.org/?probe=6933a56e5a) | Jul 29, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [c1c1ff83e5](https://linux-hardware.org/?probe=c1c1ff83e5) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8121463c28](https://linux-hardware.org/?probe=8121463c28) | Jul 29, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [21bcfb6822](https://linux-hardware.org/?probe=21bcfb6822) | Jul 29, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [961bafd03a](https://linux-hardware.org/?probe=961bafd03a) | Jul 29, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [edfea43d47](https://linux-hardware.org/?probe=edfea43d47) | Jul 28, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [5b6c57fdb2](https://linux-hardware.org/?probe=5b6c57fdb2) | Jul 28, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [d95d409e75](https://linux-hardware.org/?probe=d95d409e75) | Jul 28, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [cbbc9c0451](https://linux-hardware.org/?probe=cbbc9c0451) | Jul 28, 2021 |
| Dell          | Inspiron 3502               | Notebook    | [9216707eed](https://linux-hardware.org/?probe=9216707eed) | Jul 28, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [85dececf7f](https://linux-hardware.org/?probe=85dececf7f) | Jul 28, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [4d811eb752](https://linux-hardware.org/?probe=4d811eb752) | Jul 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [744ab63b06](https://linux-hardware.org/?probe=744ab63b06) | Jul 28, 2021 |
| Timi          | TM1707                      | Notebook    | [69ece09721](https://linux-hardware.org/?probe=69ece09721) | Jul 28, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c6239b2672](https://linux-hardware.org/?probe=c6239b2672) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Lenovo        | ThinkPad T590 20N5S72000    | Notebook    | [f82a0e5777](https://linux-hardware.org/?probe=f82a0e5777) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [5e769c8137](https://linux-hardware.org/?probe=5e769c8137) | Jul 26, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [25961dfa1f](https://linux-hardware.org/?probe=25961dfa1f) | Jul 26, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [79fbd86b2a](https://linux-hardware.org/?probe=79fbd86b2a) | Jul 26, 2021 |
| Dell          | Latitude 7400               | Notebook    | [0ad7b49f7a](https://linux-hardware.org/?probe=0ad7b49f7a) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [a470eeaa37](https://linux-hardware.org/?probe=a470eeaa37) | Jul 26, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| HP            | 2AF7                        | Desktop     | [a24b46f292](https://linux-hardware.org/?probe=a24b46f292) | Jul 26, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [7df57c3e0c](https://linux-hardware.org/?probe=7df57c3e0c) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a085cda70b](https://linux-hardware.org/?probe=a085cda70b) | Jul 25, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c94593c3bd](https://linux-hardware.org/?probe=c94593c3bd) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [97b8085def](https://linux-hardware.org/?probe=97b8085def) | Jul 25, 2021 |
| Acer          | Aspire A315-42G             | Notebook    | [bfb12f37c8](https://linux-hardware.org/?probe=bfb12f37c8) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1cbc95eb56](https://linux-hardware.org/?probe=1cbc95eb56) | Jul 25, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [95937e3a67](https://linux-hardware.org/?probe=95937e3a67) | Jul 25, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [5025f05f95](https://linux-hardware.org/?probe=5025f05f95) | Jul 25, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [7ebac3504c](https://linux-hardware.org/?probe=7ebac3504c) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [f2f6ae3a0d](https://linux-hardware.org/?probe=f2f6ae3a0d) | Jul 24, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| HP            | 250 G1                      | Notebook    | [61d592b754](https://linux-hardware.org/?probe=61d592b754) | Jul 24, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [9f6fa077ca](https://linux-hardware.org/?probe=9f6fa077ca) | Jul 24, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b26e588a14](https://linux-hardware.org/?probe=b26e588a14) | Jul 24, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [f2c2beb7da](https://linux-hardware.org/?probe=f2c2beb7da) | Jul 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [4c1fea7f03](https://linux-hardware.org/?probe=4c1fea7f03) | Jul 23, 2021 |
| FUJITSU CL... | LIFEBOOK U7411              | Notebook    | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Timi          | TM1701                      | Notebook    | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| HP            | EliteBook x360 1020 G2      | Convertible | [bf9a3d1a33](https://linux-hardware.org/?probe=bf9a3d1a33) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [0bf537187a](https://linux-hardware.org/?probe=0bf537187a) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [8681aef84a](https://linux-hardware.org/?probe=8681aef84a) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [1da124bb23](https://linux-hardware.org/?probe=1da124bb23) | Jul 23, 2021 |
| Lenovo        | Yoga 510-15ISK 80S8         | Convertible | [9a0dbf2630](https://linux-hardware.org/?probe=9a0dbf2630) | Jul 23, 2021 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [5ca74a5c0a](https://linux-hardware.org/?probe=5ca74a5c0a) | Jul 22, 2021 |
| Acer          | WG43M                       | Desktop     | [9efd66b779](https://linux-hardware.org/?probe=9efd66b779) | Jul 22, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Positivo      | C41TB                       | Notebook    | [fa578942bc](https://linux-hardware.org/?probe=fa578942bc) | Jul 22, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [b788dcfcdb](https://linux-hardware.org/?probe=b788dcfcdb) | Jul 22, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [76203cb8e7](https://linux-hardware.org/?probe=76203cb8e7) | Jul 22, 2021 |
| Lenovo        | ThinkPad X220 4289A92       | Notebook    | [c985a9874f](https://linux-hardware.org/?probe=c985a9874f) | Jul 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| Dell          | 0W0CHX A01                  | Desktop     | [d4f3e21abc](https://linux-hardware.org/?probe=d4f3e21abc) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [0b87f80aa9](https://linux-hardware.org/?probe=0b87f80aa9) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [114ecaea11](https://linux-hardware.org/?probe=114ecaea11) | Jul 22, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [831024faec](https://linux-hardware.org/?probe=831024faec) | Jul 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [47b95dd012](https://linux-hardware.org/?probe=47b95dd012) | Jul 21, 2021 |
| Intel         | H81                         | Desktop     | [166b35fa7f](https://linux-hardware.org/?probe=166b35fa7f) | Jul 21, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0b2a96b6d7](https://linux-hardware.org/?probe=0b2a96b6d7) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [437aef57fd](https://linux-hardware.org/?probe=437aef57fd) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Google        | Kindred                     | Notebook    | [19b81352aa](https://linux-hardware.org/?probe=19b81352aa) | Jul 21, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6ba7627daa](https://linux-hardware.org/?probe=6ba7627daa) | Jul 21, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [785c30284d](https://linux-hardware.org/?probe=785c30284d) | Jul 21, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [4dd5b903b6](https://linux-hardware.org/?probe=4dd5b903b6) | Jul 21, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [977c0df343](https://linux-hardware.org/?probe=977c0df343) | Jul 21, 2021 |
| HP            | 83E1                        | Desktop     | [977631dbb5](https://linux-hardware.org/?probe=977631dbb5) | Jul 20, 2021 |
| ASUSTek       | CM1740                      | Desktop     | [bddfad8365](https://linux-hardware.org/?probe=bddfad8365) | Jul 20, 2021 |
| ASUSTek       | CM1740                      | Desktop     | [2dcaee58ab](https://linux-hardware.org/?probe=2dcaee58ab) | Jul 20, 2021 |
| Lenovo        | ThinkPad L580 20LXS4K600    | Notebook    | [fc8ad7a780](https://linux-hardware.org/?probe=fc8ad7a780) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [87370c4ac2](https://linux-hardware.org/?probe=87370c4ac2) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5194fe4e7](https://linux-hardware.org/?probe=b5194fe4e7) | Jul 20, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ebed27d481](https://linux-hardware.org/?probe=ebed27d481) | Jul 20, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [54677110b4](https://linux-hardware.org/?probe=54677110b4) | Jul 20, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [d0d9ea99c9](https://linux-hardware.org/?probe=d0d9ea99c9) | Jul 20, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c8821b395f](https://linux-hardware.org/?probe=c8821b395f) | Jul 19, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [33cd8cd38a](https://linux-hardware.org/?probe=33cd8cd38a) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3e9218d801](https://linux-hardware.org/?probe=3e9218d801) | Jul 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [23e7b76362](https://linux-hardware.org/?probe=23e7b76362) | Jul 19, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [9e97498649](https://linux-hardware.org/?probe=9e97498649) | Jul 19, 2021 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [8cee50ac90](https://linux-hardware.org/?probe=8cee50ac90) | Jul 19, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [811ff5b5d4](https://linux-hardware.org/?probe=811ff5b5d4) | Jul 19, 2021 |
| Dell          | Precision 5510              | Notebook    | [62987d66d1](https://linux-hardware.org/?probe=62987d66d1) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e1d4b0e45d](https://linux-hardware.org/?probe=e1d4b0e45d) | Jul 18, 2021 |
| Lenovo        | ThinkPad L580 20LWZ3SMUS    | Notebook    | [0ec8152ed0](https://linux-hardware.org/?probe=0ec8152ed0) | Jul 18, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [5f182f7f80](https://linux-hardware.org/?probe=5f182f7f80) | Jul 18, 2021 |
| HP            | 3646h                       | Desktop     | [b4dd06e5ce](https://linux-hardware.org/?probe=b4dd06e5ce) | Jul 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [944b172397](https://linux-hardware.org/?probe=944b172397) | Jul 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [140d166cbb](https://linux-hardware.org/?probe=140d166cbb) | Jul 18, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [67e30e41e8](https://linux-hardware.org/?probe=67e30e41e8) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d51165f3df](https://linux-hardware.org/?probe=d51165f3df) | Jul 17, 2021 |
| Notebook      | L14xMU                      | Notebook    | [90d627350d](https://linux-hardware.org/?probe=90d627350d) | Jul 17, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [b747ae8605](https://linux-hardware.org/?probe=b747ae8605) | Jul 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [f969140705](https://linux-hardware.org/?probe=f969140705) | Jul 17, 2021 |
| Sony          | VPCEB3PGX                   | Notebook    | [d979c2edc1](https://linux-hardware.org/?probe=d979c2edc1) | Jul 17, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [8384c9bc8b](https://linux-hardware.org/?probe=8384c9bc8b) | Jul 17, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Purism        | Librem 15 v4                | Notebook    | [4d73479f35](https://linux-hardware.org/?probe=4d73479f35) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [6f6f7c6f5b](https://linux-hardware.org/?probe=6f6f7c6f5b) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [02c451c80b](https://linux-hardware.org/?probe=02c451c80b) | Jul 16, 2021 |
| Biostar       | X370GTN                     | Desktop     | [22114c765e](https://linux-hardware.org/?probe=22114c765e) | Jul 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [0f518d6dd3](https://linux-hardware.org/?probe=0f518d6dd3) | Jul 16, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b38895b98](https://linux-hardware.org/?probe=3b38895b98) | Jul 16, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [15a186d484](https://linux-hardware.org/?probe=15a186d484) | Jul 16, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [29781e432b](https://linux-hardware.org/?probe=29781e432b) | Jul 16, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [3ccfcf4bc7](https://linux-hardware.org/?probe=3ccfcf4bc7) | Jul 16, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [f339240754](https://linux-hardware.org/?probe=f339240754) | Jul 15, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [38067d7d6d](https://linux-hardware.org/?probe=38067d7d6d) | Jul 15, 2021 |
| Medion        | E15301                      | Notebook    | [20b60d58c9](https://linux-hardware.org/?probe=20b60d58c9) | Jul 15, 2021 |
| HP            | 8056                        | Desktop     | [bff5c3bb8d](https://linux-hardware.org/?probe=bff5c3bb8d) | Jul 15, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [0621ec449f](https://linux-hardware.org/?probe=0621ec449f) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5292f36e16](https://linux-hardware.org/?probe=5292f36e16) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [3367527048](https://linux-hardware.org/?probe=3367527048) | Jul 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aec09069ed](https://linux-hardware.org/?probe=aec09069ed) | Jul 15, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [23ba122f57](https://linux-hardware.org/?probe=23ba122f57) | Jul 15, 2021 |
| Toshiba       | Satellite P50-C             | Notebook    | [3b8ead252b](https://linux-hardware.org/?probe=3b8ead252b) | Jul 15, 2021 |
| Lenovo        | IdeaPad 15ARE05 81YQ        | Notebook    | [9edec18576](https://linux-hardware.org/?probe=9edec18576) | Jul 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [433f44e117](https://linux-hardware.org/?probe=433f44e117) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [24a13881c1](https://linux-hardware.org/?probe=24a13881c1) | Jul 14, 2021 |
| Lenovo        | ThinkPad 25 20K70004US      | Notebook    | [444232e659](https://linux-hardware.org/?probe=444232e659) | Jul 14, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [8294dc2b59](https://linux-hardware.org/?probe=8294dc2b59) | Jul 14, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [bad5668fb0](https://linux-hardware.org/?probe=bad5668fb0) | Jul 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [663c98e1f6](https://linux-hardware.org/?probe=663c98e1f6) | Jul 13, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [197a44190e](https://linux-hardware.org/?probe=197a44190e) | Jul 13, 2021 |
| HP            | 872B                        | Desktop     | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [c7fad2195c](https://linux-hardware.org/?probe=c7fad2195c) | Jul 13, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c632e51628](https://linux-hardware.org/?probe=c632e51628) | Jul 13, 2021 |
| FUJITSU CL... | LIFEBOOK U7411              | Notebook    | [9d1dfce344](https://linux-hardware.org/?probe=9d1dfce344) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [d3700506ef](https://linux-hardware.org/?probe=d3700506ef) | Jul 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [cb44035a70](https://linux-hardware.org/?probe=cb44035a70) | Jul 13, 2021 |
| Dell          | G7 7588                     | Notebook    | [899a0f9ae0](https://linux-hardware.org/?probe=899a0f9ae0) | Jul 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [d6812debb6](https://linux-hardware.org/?probe=d6812debb6) | Jul 12, 2021 |
| SYWZ          | S200 Series                 | Desktop     | [842ae5d4a3](https://linux-hardware.org/?probe=842ae5d4a3) | Jul 12, 2021 |
| Dell          | Latitude 3570               | Notebook    | [de199e258b](https://linux-hardware.org/?probe=de199e258b) | Jul 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [e3d1b2dd96](https://linux-hardware.org/?probe=e3d1b2dd96) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8f5ed33e46](https://linux-hardware.org/?probe=8f5ed33e46) | Jul 12, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [6f04de798d](https://linux-hardware.org/?probe=6f04de798d) | Jul 12, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [3bca640897](https://linux-hardware.org/?probe=3bca640897) | Jul 12, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [1fdcb33dcd](https://linux-hardware.org/?probe=1fdcb33dcd) | Jul 12, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [891d514a94](https://linux-hardware.org/?probe=891d514a94) | Jul 12, 2021 |
| Linx          | VISION004                   | Notebook    | [52bb79b8a7](https://linux-hardware.org/?probe=52bb79b8a7) | Jul 12, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | Notebook    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | Notebook    | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [cfd00f1018](https://linux-hardware.org/?probe=cfd00f1018) | Jul 12, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3427802385](https://linux-hardware.org/?probe=3427802385) | Jul 12, 2021 |
| EVGA          | 111-KS-E272                 | Desktop     | [a97173038d](https://linux-hardware.org/?probe=a97173038d) | Jul 12, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [592276c98f](https://linux-hardware.org/?probe=592276c98f) | Jul 12, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Dell          | XPS 15 9575                 | Convertible | [9694d7fb43](https://linux-hardware.org/?probe=9694d7fb43) | Jul 12, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [cd32be6d20](https://linux-hardware.org/?probe=cd32be6d20) | Jul 12, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [14595ee84e](https://linux-hardware.org/?probe=14595ee84e) | Jul 12, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [c73776222b](https://linux-hardware.org/?probe=c73776222b) | Jul 11, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [16799202de](https://linux-hardware.org/?probe=16799202de) | Jul 11, 2021 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [4056165c35](https://linux-hardware.org/?probe=4056165c35) | Jul 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS04B00    | Notebook    | [7601025893](https://linux-hardware.org/?probe=7601025893) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d1c166c13e](https://linux-hardware.org/?probe=d1c166c13e) | Jul 11, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cdc4222058](https://linux-hardware.org/?probe=cdc4222058) | Jul 11, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [c046880bd3](https://linux-hardware.org/?probe=c046880bd3) | Jul 11, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HASEE Comp... | Computer                    | Notebook    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| Dell          | Latitude E6420              | Notebook    | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | 0DF42J A00                  | Desktop     | [8a76db0ada](https://linux-hardware.org/?probe=8a76db0ada) | Jul 11, 2021 |
| ASUSTek       | EX-B250-V7                  | Desktop     | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [61ea8363bc](https://linux-hardware.org/?probe=61ea8363bc) | Jul 10, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [223f91e471](https://linux-hardware.org/?probe=223f91e471) | Jul 10, 2021 |
| Timi          | TM1604                      | Notebook    | [496798e57c](https://linux-hardware.org/?probe=496798e57c) | Jul 10, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3c18064125](https://linux-hardware.org/?probe=3c18064125) | Jul 10, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8cdf123315](https://linux-hardware.org/?probe=8cdf123315) | Jul 10, 2021 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [731361283a](https://linux-hardware.org/?probe=731361283a) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b411603809](https://linux-hardware.org/?probe=b411603809) | Jul 10, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [9a275b8307](https://linux-hardware.org/?probe=9a275b8307) | Jul 10, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [0394bf80be](https://linux-hardware.org/?probe=0394bf80be) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [89ed1de959](https://linux-hardware.org/?probe=89ed1de959) | Jul 10, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [3ec458e478](https://linux-hardware.org/?probe=3ec458e478) | Jul 10, 2021 |
| Lenovo        | ThinkPad T490 20N3S94A00    | Notebook    | [2c4c458feb](https://linux-hardware.org/?probe=2c4c458feb) | Jul 10, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [f008db5308](https://linux-hardware.org/?probe=f008db5308) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [e1049532a5](https://linux-hardware.org/?probe=e1049532a5) | Jul 09, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b059e3bcea](https://linux-hardware.org/?probe=b059e3bcea) | Jul 09, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [b4240819e1](https://linux-hardware.org/?probe=b4240819e1) | Jul 09, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [6d939a6434](https://linux-hardware.org/?probe=6d939a6434) | Jul 09, 2021 |
| Dell          | Latitude E6530              | Notebook    | [7df496ffb5](https://linux-hardware.org/?probe=7df496ffb5) | Jul 09, 2021 |
| Dell          | Latitude 7420               | Notebook    | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [4f880e87a0](https://linux-hardware.org/?probe=4f880e87a0) | Jul 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [b1ae6e7111](https://linux-hardware.org/?probe=b1ae6e7111) | Jul 09, 2021 |
| Acer          | One S1003                   | Tablet      | [5b88dd3887](https://linux-hardware.org/?probe=5b88dd3887) | Jul 09, 2021 |
| MSI           | MS-B1711                    | Desktop     | [ad46286aa7](https://linux-hardware.org/?probe=ad46286aa7) | Jul 09, 2021 |
| Dell          | Latitude D530               | Notebook    | [d48cd58890](https://linux-hardware.org/?probe=d48cd58890) | Jul 09, 2021 |
| HP            | 1497                        | Desktop     | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [413c28caa0](https://linux-hardware.org/?probe=413c28caa0) | Jul 08, 2021 |
| Dell          | Latitude E6540              | Notebook    | [1b488de7b9](https://linux-hardware.org/?probe=1b488de7b9) | Jul 08, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [af389420e2](https://linux-hardware.org/?probe=af389420e2) | Jul 08, 2021 |
| Dell          | Precision M4600             | Notebook    | [388aad414f](https://linux-hardware.org/?probe=388aad414f) | Jul 08, 2021 |
| eMachines     | eME732                      | Notebook    | [50e1042533](https://linux-hardware.org/?probe=50e1042533) | Jul 08, 2021 |
| HP            | 8056                        | Desktop     | [c35a7e4e65](https://linux-hardware.org/?probe=c35a7e4e65) | Jul 08, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [785027f8f6](https://linux-hardware.org/?probe=785027f8f6) | Jul 08, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [bdcc6ae937](https://linux-hardware.org/?probe=bdcc6ae937) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | Notebook    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [553b287a99](https://linux-hardware.org/?probe=553b287a99) | Jul 08, 2021 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [d93e096489](https://linux-hardware.org/?probe=d93e096489) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [68be809f45](https://linux-hardware.org/?probe=68be809f45) | Jul 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ba806c9513](https://linux-hardware.org/?probe=ba806c9513) | Jul 08, 2021 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [bd0b0aa6ab](https://linux-hardware.org/?probe=bd0b0aa6ab) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | Desktop     | [9314761de4](https://linux-hardware.org/?probe=9314761de4) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | Desktop     | [c658575abc](https://linux-hardware.org/?probe=c658575abc) | Jul 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0f7853a74f](https://linux-hardware.org/?probe=0f7853a74f) | Jul 08, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [f0474e6193](https://linux-hardware.org/?probe=f0474e6193) | Jul 08, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [25fdba4c4f](https://linux-hardware.org/?probe=25fdba4c4f) | Jul 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [47e2b55bb5](https://linux-hardware.org/?probe=47e2b55bb5) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c325080602](https://linux-hardware.org/?probe=c325080602) | Jul 07, 2021 |
| HP            | 8056                        | Desktop     | [f40b845088](https://linux-hardware.org/?probe=f40b845088) | Jul 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc542d5a92](https://linux-hardware.org/?probe=cc542d5a92) | Jul 07, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [d24bfb0cba](https://linux-hardware.org/?probe=d24bfb0cba) | Jul 07, 2021 |
| HP            | Laptop 17-bs1xx             | Notebook    | [17baeef261](https://linux-hardware.org/?probe=17baeef261) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | Notebook    | [72aa4529ca](https://linux-hardware.org/?probe=72aa4529ca) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | Notebook    | [8360c2bcdc](https://linux-hardware.org/?probe=8360c2bcdc) | Jul 07, 2021 |
| Dell          | Latitude D530               | Notebook    | [21ad721b61](https://linux-hardware.org/?probe=21ad721b61) | Jul 07, 2021 |
| Dell          | Inspiron 5770               | Notebook    | [48d7ad6341](https://linux-hardware.org/?probe=48d7ad6341) | Jul 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS4NUSA    | Notebook    | [2f6b8a2bd6](https://linux-hardware.org/?probe=2f6b8a2bd6) | Jul 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS4NUSA    | Notebook    | [c36dd3d8e6](https://linux-hardware.org/?probe=c36dd3d8e6) | Jul 07, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [ec0db39d7a](https://linux-hardware.org/?probe=ec0db39d7a) | Jul 07, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [86fdf9dc69](https://linux-hardware.org/?probe=86fdf9dc69) | Jul 07, 2021 |
| Acer          | Aspire 5749                 | Notebook    | [7aa3ecf46d](https://linux-hardware.org/?probe=7aa3ecf46d) | Jul 07, 2021 |
| ASUSTek       | X99-A II                    | Desktop     | [d84c3b80a1](https://linux-hardware.org/?probe=d84c3b80a1) | Jul 07, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [0ae36379ae](https://linux-hardware.org/?probe=0ae36379ae) | Jul 07, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a7ffc7e0dd](https://linux-hardware.org/?probe=a7ffc7e0dd) | Jul 07, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e3ea65a467](https://linux-hardware.org/?probe=e3ea65a467) | Jul 07, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [4831f1aed2](https://linux-hardware.org/?probe=4831f1aed2) | Jul 07, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [4533c4325a](https://linux-hardware.org/?probe=4533c4325a) | Jul 07, 2021 |
| ASUSTek       | X555LA                      | Notebook    | [8c44ea27c9](https://linux-hardware.org/?probe=8c44ea27c9) | Jul 06, 2021 |
| ASUSTek       | X555LA                      | Notebook    | [9974f7325e](https://linux-hardware.org/?probe=9974f7325e) | Jul 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [429e94317f](https://linux-hardware.org/?probe=429e94317f) | Jul 06, 2021 |
| Dell          | Inspiron 13-7378            | Notebook    | [2006f747eb](https://linux-hardware.org/?probe=2006f747eb) | Jul 06, 2021 |
| Dell          | 0PC5F7 A02                  | Desktop     | [ea43204b3b](https://linux-hardware.org/?probe=ea43204b3b) | Jul 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [04b8667d2e](https://linux-hardware.org/?probe=04b8667d2e) | Jul 06, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [936f2b1169](https://linux-hardware.org/?probe=936f2b1169) | Jul 06, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [5c9b345041](https://linux-hardware.org/?probe=5c9b345041) | Jul 06, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [e031e80b6b](https://linux-hardware.org/?probe=e031e80b6b) | Jul 06, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [53ae472c1d](https://linux-hardware.org/?probe=53ae472c1d) | Jul 06, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [9b868b0c9b](https://linux-hardware.org/?probe=9b868b0c9b) | Jul 06, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [5758df25ec](https://linux-hardware.org/?probe=5758df25ec) | Jul 06, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [85ee7fa5f1](https://linux-hardware.org/?probe=85ee7fa5f1) | Jul 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a44525ea2d](https://linux-hardware.org/?probe=a44525ea2d) | Jul 05, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [faa3279fc6](https://linux-hardware.org/?probe=faa3279fc6) | Jul 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [f5c0f2dd2d](https://linux-hardware.org/?probe=f5c0f2dd2d) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6fdc284c1a](https://linux-hardware.org/?probe=6fdc284c1a) | Jul 05, 2021 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [efe8014efa](https://linux-hardware.org/?probe=efe8014efa) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [74a262254d](https://linux-hardware.org/?probe=74a262254d) | Jul 05, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [7fe084720d](https://linux-hardware.org/?probe=7fe084720d) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [3779d55f6e](https://linux-hardware.org/?probe=3779d55f6e) | Jul 05, 2021 |
| Acer          | Swift SF314-52G             | Notebook    | [ad7dfb7bf6](https://linux-hardware.org/?probe=ad7dfb7bf6) | Jul 05, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [3803784209](https://linux-hardware.org/?probe=3803784209) | Jul 05, 2021 |
| Dell          | G3 3579                     | Notebook    | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [13f5ecaf06](https://linux-hardware.org/?probe=13f5ecaf06) | Jul 04, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [6f974e427e](https://linux-hardware.org/?probe=6f974e427e) | Jul 04, 2021 |
| Alienware     | 0N4R4N A00                  | Desktop     | [9219336156](https://linux-hardware.org/?probe=9219336156) | Jul 04, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [3376c8f541](https://linux-hardware.org/?probe=3376c8f541) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [be18b0347f](https://linux-hardware.org/?probe=be18b0347f) | Jul 04, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [9e7e50fd74](https://linux-hardware.org/?probe=9e7e50fd74) | Jul 04, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [5b2d86e06f](https://linux-hardware.org/?probe=5b2d86e06f) | Jul 04, 2021 |
| HP            | ProBook 6465b               | Notebook    | [dd03f5f10c](https://linux-hardware.org/?probe=dd03f5f10c) | Jul 04, 2021 |
| HP            | ProBook 6465b               | Notebook    | [27a6794579](https://linux-hardware.org/?probe=27a6794579) | Jul 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [de1eb87e32](https://linux-hardware.org/?probe=de1eb87e32) | Jul 04, 2021 |
| HP            | 8056                        | Desktop     | [56f294962a](https://linux-hardware.org/?probe=56f294962a) | Jul 04, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [e684bf151e](https://linux-hardware.org/?probe=e684bf151e) | Jul 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| MSI           | MS-B9321                    | Desktop     | [93243d00da](https://linux-hardware.org/?probe=93243d00da) | Jul 03, 2021 |
| Google        | Panther                     | Desktop     | [043feff8fe](https://linux-hardware.org/?probe=043feff8fe) | Jul 03, 2021 |
| ASRock        | J3160DC-ITX                 | Desktop     | [cfd320c331](https://linux-hardware.org/?probe=cfd320c331) | Jul 03, 2021 |
| Chuwi         | LarkBox Pro                 | Desktop     | [0b050f9b1d](https://linux-hardware.org/?probe=0b050f9b1d) | Jul 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [0e5e9b16b8](https://linux-hardware.org/?probe=0e5e9b16b8) | Jul 03, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5aa1cef5bb](https://linux-hardware.org/?probe=5aa1cef5bb) | Jul 03, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [f61ba12c20](https://linux-hardware.org/?probe=f61ba12c20) | Jul 03, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [713b8738d7](https://linux-hardware.org/?probe=713b8738d7) | Jul 03, 2021 |
| CompuLab      | Intense-PC                  | Mini pc     | [04d1fd85d9](https://linux-hardware.org/?probe=04d1fd85d9) | Jul 03, 2021 |
| CompuLab      | Intense-PC                  | Mini pc     | [2cfeeb8105](https://linux-hardware.org/?probe=2cfeeb8105) | Jul 03, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [36c64a337b](https://linux-hardware.org/?probe=36c64a337b) | Jul 03, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [55cdedffc2](https://linux-hardware.org/?probe=55cdedffc2) | Jul 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [aa4b4e2c5e](https://linux-hardware.org/?probe=aa4b4e2c5e) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9282890b2e](https://linux-hardware.org/?probe=9282890b2e) | Jul 02, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [e4c275224b](https://linux-hardware.org/?probe=e4c275224b) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8f0d98b462](https://linux-hardware.org/?probe=8f0d98b462) | Jul 02, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [f3ef9d51b3](https://linux-hardware.org/?probe=f3ef9d51b3) | Jul 02, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f29842baff](https://linux-hardware.org/?probe=f29842baff) | Jul 02, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [2c9eb028c4](https://linux-hardware.org/?probe=2c9eb028c4) | Jul 02, 2021 |
| MSI           | MS-B1711                    | Desktop     | [21ec3e7523](https://linux-hardware.org/?probe=21ec3e7523) | Jul 02, 2021 |
| Lenovo        | 30BB SDK0J40705 WIN 3425... | All in one  | [27cd95557e](https://linux-hardware.org/?probe=27cd95557e) | Jul 02, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [51e1bb06dd](https://linux-hardware.org/?probe=51e1bb06dd) | Jul 02, 2021 |
| Lenovo        | ThinkPad X220 42914CG       | Notebook    | [4f886f5775](https://linux-hardware.org/?probe=4f886f5775) | Jul 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [99c56b3bda](https://linux-hardware.org/?probe=99c56b3bda) | Jul 01, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cca3e863f7](https://linux-hardware.org/?probe=cca3e863f7) | Jul 01, 2021 |
| AMD           | A320IPC VER:1.00            | Desktop     | [f165ce8a70](https://linux-hardware.org/?probe=f165ce8a70) | Jul 01, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [4a9dcc3234](https://linux-hardware.org/?probe=4a9dcc3234) | Jul 01, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [04e26d7f9d](https://linux-hardware.org/?probe=04e26d7f9d) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6ee9cba880](https://linux-hardware.org/?probe=6ee9cba880) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [c2eb051f8c](https://linux-hardware.org/?probe=c2eb051f8c) | Jul 01, 2021 |
| HP            | 8056                        | Desktop     | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [6b924d8505](https://linux-hardware.org/?probe=6b924d8505) | Jul 01, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [48bef18c1a](https://linux-hardware.org/?probe=48bef18c1a) | Jul 01, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [544a5040ad](https://linux-hardware.org/?probe=544a5040ad) | Jul 01, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ed64b27c12](https://linux-hardware.org/?probe=ed64b27c12) | Jul 01, 2021 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [e2c078e281](https://linux-hardware.org/?probe=e2c078e281) | Jul 01, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2caf3e1dd5](https://linux-hardware.org/?probe=2caf3e1dd5) | Jun 30, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [d6bf3eece4](https://linux-hardware.org/?probe=d6bf3eece4) | Jun 30, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [47dfbc7a00](https://linux-hardware.org/?probe=47dfbc7a00) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [a37dd487ac](https://linux-hardware.org/?probe=a37dd487ac) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d85a7c67f9](https://linux-hardware.org/?probe=d85a7c67f9) | Jun 30, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [132edccbe5](https://linux-hardware.org/?probe=132edccbe5) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e6cda3b64b](https://linux-hardware.org/?probe=e6cda3b64b) | Jun 30, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [28dd0487c3](https://linux-hardware.org/?probe=28dd0487c3) | Jun 30, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [ce332204a6](https://linux-hardware.org/?probe=ce332204a6) | Jun 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [f38fd14520](https://linux-hardware.org/?probe=f38fd14520) | Jun 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [a8268a0c9d](https://linux-hardware.org/?probe=a8268a0c9d) | Jun 29, 2021 |
| Dell          | Latitude E6320              | Notebook    | [dd93a97faf](https://linux-hardware.org/?probe=dd93a97faf) | Jun 29, 2021 |
| Lenovo        | Board                       | Desktop     | [1e1ba598d3](https://linux-hardware.org/?probe=1e1ba598d3) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1185271556](https://linux-hardware.org/?probe=1185271556) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [0369ff2b06](https://linux-hardware.org/?probe=0369ff2b06) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [353a5052a1](https://linux-hardware.org/?probe=353a5052a1) | Jun 29, 2021 |
| Dell          | G7 7588                     | Notebook    | [c053b00ac1](https://linux-hardware.org/?probe=c053b00ac1) | Jun 29, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6820c53176](https://linux-hardware.org/?probe=6820c53176) | Jun 29, 2021 |
| eMachines     | eME732                      | Notebook    | [81bbc7fe0f](https://linux-hardware.org/?probe=81bbc7fe0f) | Jun 29, 2021 |
| eMachines     | eME732                      | Notebook    | [1f334d1a64](https://linux-hardware.org/?probe=1f334d1a64) | Jun 29, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [67e302d5d5](https://linux-hardware.org/?probe=67e302d5d5) | Jun 29, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [52e029b58e](https://linux-hardware.org/?probe=52e029b58e) | Jun 28, 2021 |
| Acer          | One S1003                   | Tablet      | [db5be6c431](https://linux-hardware.org/?probe=db5be6c431) | Jun 28, 2021 |
| SYWZ          | S200 Series                 | Desktop     | [a848b9e433](https://linux-hardware.org/?probe=a848b9e433) | Jun 28, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d6ef1b054b](https://linux-hardware.org/?probe=d6ef1b054b) | Jun 28, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3ef8e128d8](https://linux-hardware.org/?probe=3ef8e128d8) | Jun 27, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [ea190d7d5b](https://linux-hardware.org/?probe=ea190d7d5b) | Jun 27, 2021 |
| Lenovo        | ThinkPad W530 2447AC4       | Notebook    | [42a4d32f82](https://linux-hardware.org/?probe=42a4d32f82) | Jun 27, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | Notebook    | [09705e74ac](https://linux-hardware.org/?probe=09705e74ac) | Jun 27, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [fd4be0982e](https://linux-hardware.org/?probe=fd4be0982e) | Jun 27, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [a6b799f108](https://linux-hardware.org/?probe=a6b799f108) | Jun 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [62c1b02c31](https://linux-hardware.org/?probe=62c1b02c31) | Jun 27, 2021 |
| Dell          | Latitude E6510              | Notebook    | [554b7b8739](https://linux-hardware.org/?probe=554b7b8739) | Jun 27, 2021 |
| HP            | 8436                        | Desktop     | [617d5e50fd](https://linux-hardware.org/?probe=617d5e50fd) | Jun 27, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [f479cb95d4](https://linux-hardware.org/?probe=f479cb95d4) | Jun 26, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [4f8ff6b6a4](https://linux-hardware.org/?probe=4f8ff6b6a4) | Jun 26, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [3c33ace801](https://linux-hardware.org/?probe=3c33ace801) | Jun 26, 2021 |
| Positivo      | CHT14B                      | Notebook    | [4fd6be9b48](https://linux-hardware.org/?probe=4fd6be9b48) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [c1e9364997](https://linux-hardware.org/?probe=c1e9364997) | Jun 26, 2021 |
| Lenovo        | Yoga S740-15IRH 81NX        | Convertible | [5c409fa78e](https://linux-hardware.org/?probe=5c409fa78e) | Jun 26, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [533712977b](https://linux-hardware.org/?probe=533712977b) | Jun 26, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [39a0c32be8](https://linux-hardware.org/?probe=39a0c32be8) | Jun 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [44c09f0096](https://linux-hardware.org/?probe=44c09f0096) | Jun 26, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [03a472ae41](https://linux-hardware.org/?probe=03a472ae41) | Jun 26, 2021 |
| ASUSTek       | X510URR                     | Notebook    | [980f6dda35](https://linux-hardware.org/?probe=980f6dda35) | Jun 25, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [2c4a16ea24](https://linux-hardware.org/?probe=2c4a16ea24) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| HP            | 8056                        | Desktop     | [3cce894f08](https://linux-hardware.org/?probe=3cce894f08) | Jun 25, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [95a80b91fd](https://linux-hardware.org/?probe=95a80b91fd) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a6c3875064](https://linux-hardware.org/?probe=a6c3875064) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3fabc021d6](https://linux-hardware.org/?probe=3fabc021d6) | Jun 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| Acer          | Aspire E1-572P              | Notebook    | [b6b916afd7](https://linux-hardware.org/?probe=b6b916afd7) | Jun 25, 2021 |
| ASUSTek       | N551JX                      | Notebook    | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [3853510dae](https://linux-hardware.org/?probe=3853510dae) | Jun 24, 2021 |
| HP            | EliteBook 745 G5            | Notebook    | [5b2fd462f9](https://linux-hardware.org/?probe=5b2fd462f9) | Jun 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [0a87a16629](https://linux-hardware.org/?probe=0a87a16629) | Jun 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [f08002593f](https://linux-hardware.org/?probe=f08002593f) | Jun 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f008bcb38f](https://linux-hardware.org/?probe=f008bcb38f) | Jun 24, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [7f19e67108](https://linux-hardware.org/?probe=7f19e67108) | Jun 24, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f8a74fc57a](https://linux-hardware.org/?probe=f8a74fc57a) | Jun 24, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [febe8388b9](https://linux-hardware.org/?probe=febe8388b9) | Jun 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b5d17f5b99](https://linux-hardware.org/?probe=b5d17f5b99) | Jun 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [3e700499c7](https://linux-hardware.org/?probe=3e700499c7) | Jun 24, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0K    | Notebook    | [7f9142fffb](https://linux-hardware.org/?probe=7f9142fffb) | Jun 24, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [121770a05e](https://linux-hardware.org/?probe=121770a05e) | Jun 23, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [1189ce0f29](https://linux-hardware.org/?probe=1189ce0f29) | Jun 23, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [63d7af3f6c](https://linux-hardware.org/?probe=63d7af3f6c) | Jun 23, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [3d037467a7](https://linux-hardware.org/?probe=3d037467a7) | Jun 23, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [8edc5f4d03](https://linux-hardware.org/?probe=8edc5f4d03) | Jun 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [2c6ef158c3](https://linux-hardware.org/?probe=2c6ef158c3) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [e1346ace5c](https://linux-hardware.org/?probe=e1346ace5c) | Jun 23, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [89e7443645](https://linux-hardware.org/?probe=89e7443645) | Jun 23, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [458921c45b](https://linux-hardware.org/?probe=458921c45b) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e563be02ff](https://linux-hardware.org/?probe=e563be02ff) | Jun 23, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0B    | Notebook    | [3e8ac913f5](https://linux-hardware.org/?probe=3e8ac913f5) | Jun 23, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c69a0b8125](https://linux-hardware.org/?probe=c69a0b8125) | Jun 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [6dc73fd38c](https://linux-hardware.org/?probe=6dc73fd38c) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b9d01c99ff](https://linux-hardware.org/?probe=b9d01c99ff) | Jun 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [30717e79a0](https://linux-hardware.org/?probe=30717e79a0) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7a6f9e9890](https://linux-hardware.org/?probe=7a6f9e9890) | Jun 22, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [38f25268b8](https://linux-hardware.org/?probe=38f25268b8) | Jun 22, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [643c704c39](https://linux-hardware.org/?probe=643c704c39) | Jun 22, 2021 |
| Lenovo        | 3714 SDK0R32862 WIN 3258... | Desktop     | [b20ad5477a](https://linux-hardware.org/?probe=b20ad5477a) | Jun 22, 2021 |
| HP            | 198E                        | Desktop     | [b614ce2528](https://linux-hardware.org/?probe=b614ce2528) | Jun 22, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b71a93aed](https://linux-hardware.org/?probe=9b71a93aed) | Jun 22, 2021 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [6dbda9f5d3](https://linux-hardware.org/?probe=6dbda9f5d3) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca17e02509](https://linux-hardware.org/?probe=ca17e02509) | Jun 22, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [b9ad532089](https://linux-hardware.org/?probe=b9ad532089) | Jun 22, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [1776eab993](https://linux-hardware.org/?probe=1776eab993) | Jun 22, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [b57edde05d](https://linux-hardware.org/?probe=b57edde05d) | Jun 22, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [3fbcc9554f](https://linux-hardware.org/?probe=3fbcc9554f) | Jun 22, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [fecaaeafe2](https://linux-hardware.org/?probe=fecaaeafe2) | Jun 22, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [8d0a64c8c1](https://linux-hardware.org/?probe=8d0a64c8c1) | Jun 22, 2021 |
| ASUSTek       | X450LA                      | Notebook    | [243cc91799](https://linux-hardware.org/?probe=243cc91799) | Jun 22, 2021 |
| HP            | ProLiant DL380 G6           | Server      | [096d3e62fe](https://linux-hardware.org/?probe=096d3e62fe) | Jun 21, 2021 |
| HP            | ProLiant ML150 G5           | Desktop     | [dd931cb4e6](https://linux-hardware.org/?probe=dd931cb4e6) | Jun 21, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [9974950d4a](https://linux-hardware.org/?probe=9974950d4a) | Jun 21, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [4d638e6ba4](https://linux-hardware.org/?probe=4d638e6ba4) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [4ac446c37b](https://linux-hardware.org/?probe=4ac446c37b) | Jun 21, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [d0164778ea](https://linux-hardware.org/?probe=d0164778ea) | Jun 21, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [0c1eb0be4f](https://linux-hardware.org/?probe=0c1eb0be4f) | Jun 21, 2021 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [235d2d6944](https://linux-hardware.org/?probe=235d2d6944) | Jun 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [7499a86ba1](https://linux-hardware.org/?probe=7499a86ba1) | Jun 21, 2021 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [df96074b07](https://linux-hardware.org/?probe=df96074b07) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [5af8c6f41c](https://linux-hardware.org/?probe=5af8c6f41c) | Jun 21, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [5050b7baad](https://linux-hardware.org/?probe=5050b7baad) | Jun 21, 2021 |
| LG Electro... | 17Z90N-R.AAC8U1             | Notebook    | [09434b48cf](https://linux-hardware.org/?probe=09434b48cf) | Jun 21, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [5b26e5e2c9](https://linux-hardware.org/?probe=5b26e5e2c9) | Jun 20, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [59fa18019a](https://linux-hardware.org/?probe=59fa18019a) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [edb0b62fe0](https://linux-hardware.org/?probe=edb0b62fe0) | Jun 19, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e3e63b4e4c](https://linux-hardware.org/?probe=e3e63b4e4c) | Jun 19, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [ed109bbeda](https://linux-hardware.org/?probe=ed109bbeda) | Jun 19, 2021 |
| Dell          | 0F8101                      | Desktop     | [a33d01212c](https://linux-hardware.org/?probe=a33d01212c) | Jun 19, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [de8b613aef](https://linux-hardware.org/?probe=de8b613aef) | Jun 19, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [0cdcd68d1e](https://linux-hardware.org/?probe=0cdcd68d1e) | Jun 19, 2021 |
| Medion        | E3223 MD61127               | Convertible | [7c073ecfb9](https://linux-hardware.org/?probe=7c073ecfb9) | Jun 19, 2021 |
| HP            | 255 G4                      | Notebook    | [3a4a67761f](https://linux-hardware.org/?probe=3a4a67761f) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [55d0bea92e](https://linux-hardware.org/?probe=55d0bea92e) | Jun 19, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [5d9f586d72](https://linux-hardware.org/?probe=5d9f586d72) | Jun 19, 2021 |
| Acer          | Predator G3-571             | Notebook    | [1e3a3e9e1b](https://linux-hardware.org/?probe=1e3a3e9e1b) | Jun 19, 2021 |
| HP            | 8056                        | Desktop     | [f1b5c0d45e](https://linux-hardware.org/?probe=f1b5c0d45e) | Jun 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3489fe1584](https://linux-hardware.org/?probe=3489fe1584) | Jun 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0fe1eac567](https://linux-hardware.org/?probe=0fe1eac567) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [0cfbaaded5](https://linux-hardware.org/?probe=0cfbaaded5) | Jun 18, 2021 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8e3aa30f32](https://linux-hardware.org/?probe=8e3aa30f32) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L6S29D07    | Notebook    | [5c87bcb1dc](https://linux-hardware.org/?probe=5c87bcb1dc) | Jun 18, 2021 |
| Dell          | Latitude 5310               | Notebook    | [a38b907625](https://linux-hardware.org/?probe=a38b907625) | Jun 18, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [92d16a4d2d](https://linux-hardware.org/?probe=92d16a4d2d) | Jun 18, 2021 |
| ASRock        | H97 Killer                  | Desktop     | [acc4773b1b](https://linux-hardware.org/?probe=acc4773b1b) | Jun 18, 2021 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [d7cfb8d16f](https://linux-hardware.org/?probe=d7cfb8d16f) | Jun 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [04fa70e3af](https://linux-hardware.org/?probe=04fa70e3af) | Jun 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ecdf88f402](https://linux-hardware.org/?probe=ecdf88f402) | Jun 18, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | 81C5 MVB                    | Desktop     | [eb5550cdef](https://linux-hardware.org/?probe=eb5550cdef) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [419ff5b1e5](https://linux-hardware.org/?probe=419ff5b1e5) | Jun 17, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c9cf129666](https://linux-hardware.org/?probe=c9cf129666) | Jun 17, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [4a5c3ed30c](https://linux-hardware.org/?probe=4a5c3ed30c) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a078b826cc](https://linux-hardware.org/?probe=a078b826cc) | Jun 17, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d17aa6436e](https://linux-hardware.org/?probe=d17aa6436e) | Jun 17, 2021 |
| Intel         | MIR1 RVP7                   | Desktop     | [b0a36a3845](https://linux-hardware.org/?probe=b0a36a3845) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | Desktop     | [5320c39497](https://linux-hardware.org/?probe=5320c39497) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | Desktop     | [096e520c57](https://linux-hardware.org/?probe=096e520c57) | Jun 16, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e66e2f9e89](https://linux-hardware.org/?probe=e66e2f9e89) | Jun 16, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [180e2dcad0](https://linux-hardware.org/?probe=180e2dcad0) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [caee94b554](https://linux-hardware.org/?probe=caee94b554) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [28d36f1b88](https://linux-hardware.org/?probe=28d36f1b88) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | Notebook    | [312670a9e8](https://linux-hardware.org/?probe=312670a9e8) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | Notebook    | [c5bd6200eb](https://linux-hardware.org/?probe=c5bd6200eb) | Jun 16, 2021 |
| Dell          | Precision 7530              | Notebook    | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| HP            | Notebook                    | Notebook    | [d8ac22f956](https://linux-hardware.org/?probe=d8ac22f956) | Jun 15, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Positivo      | C41TB                       | Notebook    | [3824885cc3](https://linux-hardware.org/?probe=3824885cc3) | Jun 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [28f64a2715](https://linux-hardware.org/?probe=28f64a2715) | Jun 15, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [6d61e60824](https://linux-hardware.org/?probe=6d61e60824) | Jun 15, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [7e4f2022c8](https://linux-hardware.org/?probe=7e4f2022c8) | Jun 15, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [6cf8aa4053](https://linux-hardware.org/?probe=6cf8aa4053) | Jun 15, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9145765cc5](https://linux-hardware.org/?probe=9145765cc5) | Jun 15, 2021 |
| Lenovo        | Board                       | Desktop     | [b30a75edb2](https://linux-hardware.org/?probe=b30a75edb2) | Jun 15, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8fa18de364](https://linux-hardware.org/?probe=8fa18de364) | Jun 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [891f747f39](https://linux-hardware.org/?probe=891f747f39) | Jun 15, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [9d6796ee13](https://linux-hardware.org/?probe=9d6796ee13) | Jun 14, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| Dell          | Latitude 5285               | Notebook    | [0fad55c520](https://linux-hardware.org/?probe=0fad55c520) | Jun 14, 2021 |
| Dell          | Latitude 5285               | Notebook    | [4d7dfa80fc](https://linux-hardware.org/?probe=4d7dfa80fc) | Jun 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [11bea838aa](https://linux-hardware.org/?probe=11bea838aa) | Jun 14, 2021 |
| Lenovo        | ThinkPad W520 4282AB9       | Notebook    | [a5d7b02f3f](https://linux-hardware.org/?probe=a5d7b02f3f) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [692dcceeee](https://linux-hardware.org/?probe=692dcceeee) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [3b280580e0](https://linux-hardware.org/?probe=3b280580e0) | Jun 14, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [0c32c6e173](https://linux-hardware.org/?probe=0c32c6e173) | Jun 14, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [ed5ee6c4fd](https://linux-hardware.org/?probe=ed5ee6c4fd) | Jun 14, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [2f146aa93d](https://linux-hardware.org/?probe=2f146aa93d) | Jun 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [c995062581](https://linux-hardware.org/?probe=c995062581) | Jun 14, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | Board                       | Desktop     | [c89aa8ea82](https://linux-hardware.org/?probe=c89aa8ea82) | Jun 13, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [0f4817a280](https://linux-hardware.org/?probe=0f4817a280) | Jun 13, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [f70d1d9749](https://linux-hardware.org/?probe=f70d1d9749) | Jun 13, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [1ffaea82ea](https://linux-hardware.org/?probe=1ffaea82ea) | Jun 13, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [ab3536f2c6](https://linux-hardware.org/?probe=ab3536f2c6) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [c1805791ab](https://linux-hardware.org/?probe=c1805791ab) | Jun 13, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [dc2adb8c8b](https://linux-hardware.org/?probe=dc2adb8c8b) | Jun 13, 2021 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [48d6b0c4de](https://linux-hardware.org/?probe=48d6b0c4de) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3f74265d6d](https://linux-hardware.org/?probe=3f74265d6d) | Jun 12, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [86c9df0816](https://linux-hardware.org/?probe=86c9df0816) | Jun 12, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [01e22d19b3](https://linux-hardware.org/?probe=01e22d19b3) | Jun 12, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [2dcbc551cd](https://linux-hardware.org/?probe=2dcbc551cd) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [0a78275a12](https://linux-hardware.org/?probe=0a78275a12) | Jun 12, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| Dell          | Precision 5510              | Notebook    | [afb07c1b1a](https://linux-hardware.org/?probe=afb07c1b1a) | Jun 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [edcaa9a1be](https://linux-hardware.org/?probe=edcaa9a1be) | Jun 12, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [755e53550d](https://linux-hardware.org/?probe=755e53550d) | Jun 12, 2021 |
| Lenovo        | ThinkPad E480 20KN003YUS    | Notebook    | [33d07363b6](https://linux-hardware.org/?probe=33d07363b6) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [3641fab1a0](https://linux-hardware.org/?probe=3641fab1a0) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [92f48178fc](https://linux-hardware.org/?probe=92f48178fc) | Jun 12, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [dd9bf62ea7](https://linux-hardware.org/?probe=dd9bf62ea7) | Jun 11, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [b012f183ba](https://linux-hardware.org/?probe=b012f183ba) | Jun 11, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [94d4ada14e](https://linux-hardware.org/?probe=94d4ada14e) | Jun 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [7805e2e2a1](https://linux-hardware.org/?probe=7805e2e2a1) | Jun 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [2d43d8a465](https://linux-hardware.org/?probe=2d43d8a465) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d4c54270ff](https://linux-hardware.org/?probe=d4c54270ff) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c346ece974](https://linux-hardware.org/?probe=c346ece974) | Jun 11, 2021 |
| HP            | 3397                        | Desktop     | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [9c821bc1eb](https://linux-hardware.org/?probe=9c821bc1eb) | Jun 11, 2021 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [aa273ff14d](https://linux-hardware.org/?probe=aa273ff14d) | Jun 10, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [405b055ebd](https://linux-hardware.org/?probe=405b055ebd) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [cf5a4ceda4](https://linux-hardware.org/?probe=cf5a4ceda4) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [43b8801add](https://linux-hardware.org/?probe=43b8801add) | Jun 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5221d99db7](https://linux-hardware.org/?probe=5221d99db7) | Jun 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [c51cb3ca6a](https://linux-hardware.org/?probe=c51cb3ca6a) | Jun 10, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [565cd46886](https://linux-hardware.org/?probe=565cd46886) | Jun 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [241e4071cc](https://linux-hardware.org/?probe=241e4071cc) | Jun 10, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [403ab2f377](https://linux-hardware.org/?probe=403ab2f377) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ebca8fe85a](https://linux-hardware.org/?probe=ebca8fe85a) | Jun 09, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [0023c36bb4](https://linux-hardware.org/?probe=0023c36bb4) | Jun 09, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [d0192aebbf](https://linux-hardware.org/?probe=d0192aebbf) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [2cbf5797c7](https://linux-hardware.org/?probe=2cbf5797c7) | Jun 09, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [85ad270405](https://linux-hardware.org/?probe=85ad270405) | Jun 09, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [783d8a89bd](https://linux-hardware.org/?probe=783d8a89bd) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91d8938c98](https://linux-hardware.org/?probe=91d8938c98) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [07bd5e87d7](https://linux-hardware.org/?probe=07bd5e87d7) | Jun 09, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [a1cfc1d335](https://linux-hardware.org/?probe=a1cfc1d335) | Jun 09, 2021 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [47401d66ce](https://linux-hardware.org/?probe=47401d66ce) | Jun 09, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [d5fbd4c05d](https://linux-hardware.org/?probe=d5fbd4c05d) | Jun 08, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [02463072c4](https://linux-hardware.org/?probe=02463072c4) | Jun 08, 2021 |
| Lenovo        | ThinkPad E560 20EV003WUS    | Notebook    | [fc739d0d64](https://linux-hardware.org/?probe=fc739d0d64) | Jun 08, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [2ac85efa40](https://linux-hardware.org/?probe=2ac85efa40) | Jun 08, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [0604956adc](https://linux-hardware.org/?probe=0604956adc) | Jun 08, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [8d4983662d](https://linux-hardware.org/?probe=8d4983662d) | Jun 08, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [efff65d826](https://linux-hardware.org/?probe=efff65d826) | Jun 08, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [391865c5a2](https://linux-hardware.org/?probe=391865c5a2) | Jun 08, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [ead95cf972](https://linux-hardware.org/?probe=ead95cf972) | Jun 08, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [74bfd5efb9](https://linux-hardware.org/?probe=74bfd5efb9) | Jun 08, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c493d4cdf9](https://linux-hardware.org/?probe=c493d4cdf9) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2c66c12e1b](https://linux-hardware.org/?probe=2c66c12e1b) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [13eaba8cd2](https://linux-hardware.org/?probe=13eaba8cd2) | Jun 07, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [8f4c9482d3](https://linux-hardware.org/?probe=8f4c9482d3) | Jun 07, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [47a618e206](https://linux-hardware.org/?probe=47a618e206) | Jun 07, 2021 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | Convertible | [6c78870b5b](https://linux-hardware.org/?probe=6c78870b5b) | Jun 07, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [872d0ecc32](https://linux-hardware.org/?probe=872d0ecc32) | Jun 07, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [521f3e1bde](https://linux-hardware.org/?probe=521f3e1bde) | Jun 07, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [517c800c42](https://linux-hardware.org/?probe=517c800c42) | Jun 07, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [10cb3b472b](https://linux-hardware.org/?probe=10cb3b472b) | Jun 07, 2021 |
| Lenovo        | ThinkPad X220 4290LT8       | Notebook    | [281446b9b1](https://linux-hardware.org/?probe=281446b9b1) | Jun 07, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [c98bcbf189](https://linux-hardware.org/?probe=c98bcbf189) | Jun 07, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [3f5df2365c](https://linux-hardware.org/?probe=3f5df2365c) | Jun 07, 2021 |
| Gateway       | DX4860                      | Desktop     | [bd9a842eec](https://linux-hardware.org/?probe=bd9a842eec) | Jun 07, 2021 |
| Gateway       | DX4860                      | Desktop     | [a26d972766](https://linux-hardware.org/?probe=a26d972766) | Jun 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [d5b58807dd](https://linux-hardware.org/?probe=d5b58807dd) | Jun 07, 2021 |
| Dell          | Latitude 7370               | Notebook    | [ddfe1dc0a3](https://linux-hardware.org/?probe=ddfe1dc0a3) | Jun 07, 2021 |
| ASRock        | B560M Steel Legend          | Desktop     | [c87d28e8c0](https://linux-hardware.org/?probe=c87d28e8c0) | Jun 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [010da56dde](https://linux-hardware.org/?probe=010da56dde) | Jun 06, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5541611054](https://linux-hardware.org/?probe=5541611054) | Jun 06, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| HP            | EliteBook x360 1040 G5      | Convertible | [3af4716969](https://linux-hardware.org/?probe=3af4716969) | Jun 06, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [8ba65755ff](https://linux-hardware.org/?probe=8ba65755ff) | Jun 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7e68daad35](https://linux-hardware.org/?probe=7e68daad35) | Jun 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [4d157e0cce](https://linux-hardware.org/?probe=4d157e0cce) | Jun 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [ba3e1c4e32](https://linux-hardware.org/?probe=ba3e1c4e32) | Jun 05, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [6bd42268f6](https://linux-hardware.org/?probe=6bd42268f6) | Jun 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94c194ba5](https://linux-hardware.org/?probe=d94c194ba5) | Jun 05, 2021 |
| Intel         | H61                         | Desktop     | [607d6e5e33](https://linux-hardware.org/?probe=607d6e5e33) | Jun 05, 2021 |
| Intel         | H61                         | Desktop     | [8ed3e75d2d](https://linux-hardware.org/?probe=8ed3e75d2d) | Jun 05, 2021 |
| HP            | 8768 A                      | Desktop     | [f239501901](https://linux-hardware.org/?probe=f239501901) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [25a53bf5a0](https://linux-hardware.org/?probe=25a53bf5a0) | Jun 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [4fb050f895](https://linux-hardware.org/?probe=4fb050f895) | Jun 05, 2021 |
| MSI           | A78M-E35                    | Desktop     | [4d4959df32](https://linux-hardware.org/?probe=4d4959df32) | Jun 04, 2021 |
| MSI           | A78M-E35                    | Desktop     | [7dc4db6092](https://linux-hardware.org/?probe=7dc4db6092) | Jun 04, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [557557b4eb](https://linux-hardware.org/?probe=557557b4eb) | Jun 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| HP            | 0AECh D                     | Desktop     | [0a0a487efe](https://linux-hardware.org/?probe=0a0a487efe) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [43a9dc51d9](https://linux-hardware.org/?probe=43a9dc51d9) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [4023b437d2](https://linux-hardware.org/?probe=4023b437d2) | Jun 04, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c8d175865c](https://linux-hardware.org/?probe=c8d175865c) | Jun 04, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [f3ffbcfa47](https://linux-hardware.org/?probe=f3ffbcfa47) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [4931426516](https://linux-hardware.org/?probe=4931426516) | Jun 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b967eaa6db](https://linux-hardware.org/?probe=b967eaa6db) | Jun 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1cb5b38d5e](https://linux-hardware.org/?probe=1cb5b38d5e) | Jun 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [00119f7ba5](https://linux-hardware.org/?probe=00119f7ba5) | Jun 03, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [221e440b21](https://linux-hardware.org/?probe=221e440b21) | Jun 03, 2021 |
| ASUSTek       | PRIME H310M-D               | Desktop     | [5f98fdcb02](https://linux-hardware.org/?probe=5f98fdcb02) | Jun 03, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f0057c8374](https://linux-hardware.org/?probe=f0057c8374) | Jun 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1c0016dc30](https://linux-hardware.org/?probe=1c0016dc30) | Jun 03, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0e54cb2214](https://linux-hardware.org/?probe=0e54cb2214) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1cba119582](https://linux-hardware.org/?probe=1cba119582) | Jun 03, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ceb72d0ae7](https://linux-hardware.org/?probe=ceb72d0ae7) | Jun 03, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [9bae888d70](https://linux-hardware.org/?probe=9bae888d70) | Jun 03, 2021 |
| Lenovo        | Board                       | Desktop     | [4c17a95dc1](https://linux-hardware.org/?probe=4c17a95dc1) | Jun 03, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [0cde3de43d](https://linux-hardware.org/?probe=0cde3de43d) | Jun 03, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [dbfeab0bb4](https://linux-hardware.org/?probe=dbfeab0bb4) | Jun 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [1a7c5aee0e](https://linux-hardware.org/?probe=1a7c5aee0e) | Jun 02, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [203b62c458](https://linux-hardware.org/?probe=203b62c458) | Jun 02, 2021 |
| Acer          | Swift SF315-52G             | Notebook    | [8ed81a9451](https://linux-hardware.org/?probe=8ed81a9451) | Jun 02, 2021 |
| Acer          | Swift SF315-52G             | Notebook    | [5d8e928b43](https://linux-hardware.org/?probe=5d8e928b43) | Jun 02, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [09a3733791](https://linux-hardware.org/?probe=09a3733791) | Jun 01, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [475195dcd9](https://linux-hardware.org/?probe=475195dcd9) | Jun 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ad37db1da8](https://linux-hardware.org/?probe=ad37db1da8) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | Notebook    | [e47851b0ed](https://linux-hardware.org/?probe=e47851b0ed) | Jun 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f5dafbe2de](https://linux-hardware.org/?probe=f5dafbe2de) | Jun 01, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [90afa2df5b](https://linux-hardware.org/?probe=90afa2df5b) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [9c3ecf7ae2](https://linux-hardware.org/?probe=9c3ecf7ae2) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a6131ffc39](https://linux-hardware.org/?probe=a6131ffc39) | Jun 01, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [1b59a580ea](https://linux-hardware.org/?probe=1b59a580ea) | Jun 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [add3cc76ee](https://linux-hardware.org/?probe=add3cc76ee) | Jun 01, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [f7ca87e974](https://linux-hardware.org/?probe=f7ca87e974) | Jun 01, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [5441c2ab6f](https://linux-hardware.org/?probe=5441c2ab6f) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | Notebook    | [0a9b2c114f](https://linux-hardware.org/?probe=0a9b2c114f) | Jun 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b8d0e81636](https://linux-hardware.org/?probe=b8d0e81636) | Jun 01, 2021 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [77fcb9cf4a](https://linux-hardware.org/?probe=77fcb9cf4a) | Jun 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [ad3c1fb56a](https://linux-hardware.org/?probe=ad3c1fb56a) | May 31, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e0277e3530](https://linux-hardware.org/?probe=e0277e3530) | May 31, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [7a75936b55](https://linux-hardware.org/?probe=7a75936b55) | May 31, 2021 |
| Dell          | 0GXM1W A01                  | Desktop     | [4daf9fdc0d](https://linux-hardware.org/?probe=4daf9fdc0d) | May 31, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | Notebook                    | Notebook    | [7493540206](https://linux-hardware.org/?probe=7493540206) | May 31, 2021 |
| HP            | Notebook                    | Notebook    | [eaabc0c626](https://linux-hardware.org/?probe=eaabc0c626) | May 31, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [4caf31da4e](https://linux-hardware.org/?probe=4caf31da4e) | May 31, 2021 |
| ASUSTek       | K54C                        | Notebook    | [389e1a52a6](https://linux-hardware.org/?probe=389e1a52a6) | May 31, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9b20a88d5e](https://linux-hardware.org/?probe=9b20a88d5e) | May 31, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| HP            | EliteBook 745 G4            | Notebook    | [c401996108](https://linux-hardware.org/?probe=c401996108) | May 31, 2021 |
| Dell          | Latitude 7490               | Notebook    | [a92377cb2a](https://linux-hardware.org/?probe=a92377cb2a) | May 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [65310866eb](https://linux-hardware.org/?probe=65310866eb) | May 31, 2021 |
| ASUSTek       | TUF Gaming FX505DD_TUF50... | Notebook    | [d8a3297ab9](https://linux-hardware.org/?probe=d8a3297ab9) | May 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ff3d2367ee](https://linux-hardware.org/?probe=ff3d2367ee) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [80a31f37f4](https://linux-hardware.org/?probe=80a31f37f4) | May 30, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e334fad2cc](https://linux-hardware.org/?probe=e334fad2cc) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [5002e43f11](https://linux-hardware.org/?probe=5002e43f11) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0449b14156](https://linux-hardware.org/?probe=0449b14156) | May 30, 2021 |
| HP            | 8056                        | Desktop     | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [32ca60dcea](https://linux-hardware.org/?probe=32ca60dcea) | May 30, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [1f075feb49](https://linux-hardware.org/?probe=1f075feb49) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [00c5d17913](https://linux-hardware.org/?probe=00c5d17913) | May 30, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [64a9e43743](https://linux-hardware.org/?probe=64a9e43743) | May 30, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [31a6f21ccd](https://linux-hardware.org/?probe=31a6f21ccd) | May 29, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [1b68ebc549](https://linux-hardware.org/?probe=1b68ebc549) | May 29, 2021 |
| MSI           | PX60 6QE                    | Notebook    | [eca3f4ce76](https://linux-hardware.org/?probe=eca3f4ce76) | May 29, 2021 |
| Samsung       | 700T                        | Notebook    | [374154a439](https://linux-hardware.org/?probe=374154a439) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [35941050e8](https://linux-hardware.org/?probe=35941050e8) | May 29, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [73da9f35d4](https://linux-hardware.org/?probe=73da9f35d4) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [7a13082af6](https://linux-hardware.org/?probe=7a13082af6) | May 29, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [bdb612797a](https://linux-hardware.org/?probe=bdb612797a) | May 29, 2021 |
| Gigabyte      | H370N WIFI-CF               | Desktop     | [197e319075](https://linux-hardware.org/?probe=197e319075) | May 29, 2021 |
| HUAWEI        | KPR-WX9                     | Notebook    | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [06bb083e38](https://linux-hardware.org/?probe=06bb083e38) | May 29, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1268e75895](https://linux-hardware.org/?probe=1268e75895) | May 29, 2021 |
| Acer          | Nitro AN515-56              | Notebook    | [d468019e77](https://linux-hardware.org/?probe=d468019e77) | May 29, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [eee4dbbb99](https://linux-hardware.org/?probe=eee4dbbb99) | May 28, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [e8440f3a09](https://linux-hardware.org/?probe=e8440f3a09) | May 28, 2021 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [1761317692](https://linux-hardware.org/?probe=1761317692) | May 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [168717d052](https://linux-hardware.org/?probe=168717d052) | May 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9e26259821](https://linux-hardware.org/?probe=9e26259821) | May 28, 2021 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [f23de0d726](https://linux-hardware.org/?probe=f23de0d726) | May 28, 2021 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [e88de55691](https://linux-hardware.org/?probe=e88de55691) | May 28, 2021 |
| Dell          | Inspiron 5391               | Notebook    | [6722a1c1a6](https://linux-hardware.org/?probe=6722a1c1a6) | May 28, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [927f339e68](https://linux-hardware.org/?probe=927f339e68) | May 28, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [7a7114baf9](https://linux-hardware.org/?probe=7a7114baf9) | May 28, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| HP            | Pavilion 15                 | Notebook    | [379b83c4c6](https://linux-hardware.org/?probe=379b83c4c6) | May 27, 2021 |
| Dell          | Latitude 7490               | Notebook    | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| HP            | Laptop 17-bs1xx             | Notebook    | [582d387cec](https://linux-hardware.org/?probe=582d387cec) | May 27, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [5474165f7b](https://linux-hardware.org/?probe=5474165f7b) | May 27, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | Notebook    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [95561ae2cf](https://linux-hardware.org/?probe=95561ae2cf) | May 27, 2021 |
| Dell          | Latitude 5480               | Notebook    | [8a2f2558ac](https://linux-hardware.org/?probe=8a2f2558ac) | May 27, 2021 |
| Dell          | Latitude 5480               | Notebook    | [faa9bc7f20](https://linux-hardware.org/?probe=faa9bc7f20) | May 27, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [07190ac752](https://linux-hardware.org/?probe=07190ac752) | May 27, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [7d0b344759](https://linux-hardware.org/?probe=7d0b344759) | May 27, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [bfb194b61c](https://linux-hardware.org/?probe=bfb194b61c) | May 27, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [ff37a9c00d](https://linux-hardware.org/?probe=ff37a9c00d) | May 27, 2021 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [9fcfe8bf6a](https://linux-hardware.org/?probe=9fcfe8bf6a) | May 27, 2021 |
| System76      | Oryx Pro                    | Notebook    | [a3d9cae93e](https://linux-hardware.org/?probe=a3d9cae93e) | May 27, 2021 |
| Unknown       | X79                         | Desktop     | [c6dcb137fb](https://linux-hardware.org/?probe=c6dcb137fb) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| ASRock        | X99 Extreme4                | Desktop     | [6feb0aec47](https://linux-hardware.org/?probe=6feb0aec47) | May 26, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [22f2fd6b39](https://linux-hardware.org/?probe=22f2fd6b39) | May 26, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [7fb630f632](https://linux-hardware.org/?probe=7fb630f632) | May 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [fb9abea0c5](https://linux-hardware.org/?probe=fb9abea0c5) | May 26, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [172ab027e5](https://linux-hardware.org/?probe=172ab027e5) | May 26, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| HP            | 21D0                        | Desktop     | [d6d7cbe7c5](https://linux-hardware.org/?probe=d6d7cbe7c5) | May 26, 2021 |
| HP            | 21D0                        | Desktop     | [68f25edcdd](https://linux-hardware.org/?probe=68f25edcdd) | May 26, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [a6751fcc02](https://linux-hardware.org/?probe=a6751fcc02) | May 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [fbf4582983](https://linux-hardware.org/?probe=fbf4582983) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [5c2536f2d0](https://linux-hardware.org/?probe=5c2536f2d0) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [426b6eecef](https://linux-hardware.org/?probe=426b6eecef) | May 25, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [4e5245a71d](https://linux-hardware.org/?probe=4e5245a71d) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [c88a440423](https://linux-hardware.org/?probe=c88a440423) | May 25, 2021 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [e14edc9f4c](https://linux-hardware.org/?probe=e14edc9f4c) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [3bd27c32fa](https://linux-hardware.org/?probe=3bd27c32fa) | May 25, 2021 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [6cdaad9758](https://linux-hardware.org/?probe=6cdaad9758) | May 25, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [2ffefbd96c](https://linux-hardware.org/?probe=2ffefbd96c) | May 25, 2021 |
| Acer          | Aspire A315-41G             | Notebook    | [8dab17c109](https://linux-hardware.org/?probe=8dab17c109) | May 25, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [b07793f86c](https://linux-hardware.org/?probe=b07793f86c) | May 25, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [522583da69](https://linux-hardware.org/?probe=522583da69) | May 25, 2021 |
| ASUSTek       | TP410UAR                    | Convertible | [ce8e9af30d](https://linux-hardware.org/?probe=ce8e9af30d) | May 25, 2021 |
| Gigabyte      | Z97N-Gaming 5               | Desktop     | [b1b61b4aa6](https://linux-hardware.org/?probe=b1b61b4aa6) | May 25, 2021 |
| Intel         | H61                         | Desktop     | [5b5682ab2e](https://linux-hardware.org/?probe=5b5682ab2e) | May 25, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [e4c4563465](https://linux-hardware.org/?probe=e4c4563465) | May 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [980ef053d1](https://linux-hardware.org/?probe=980ef053d1) | May 24, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [be51fbb033](https://linux-hardware.org/?probe=be51fbb033) | May 24, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [cecc5ad69e](https://linux-hardware.org/?probe=cecc5ad69e) | May 24, 2021 |
| NEC Comput... | PC-VK25MXZCB                | Notebook    | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Timi          | RedmiBook 16                | Notebook    | [6ec8bb7df6](https://linux-hardware.org/?probe=6ec8bb7df6) | May 24, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [4d0c48aa12](https://linux-hardware.org/?probe=4d0c48aa12) | May 24, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [07a4b88864](https://linux-hardware.org/?probe=07a4b88864) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [cf4e1cb0d6](https://linux-hardware.org/?probe=cf4e1cb0d6) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [e65ad78e90](https://linux-hardware.org/?probe=e65ad78e90) | May 24, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fd10e51b1d](https://linux-hardware.org/?probe=fd10e51b1d) | May 24, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [a200c3666a](https://linux-hardware.org/?probe=a200c3666a) | May 23, 2021 |
| HP            | 198E                        | Desktop     | [45fbf9c1d7](https://linux-hardware.org/?probe=45fbf9c1d7) | May 23, 2021 |
| Dell          | Latitude 5480               | Notebook    | [bc9170f4cd](https://linux-hardware.org/?probe=bc9170f4cd) | May 23, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [93b4f5b14e](https://linux-hardware.org/?probe=93b4f5b14e) | May 22, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [2198e565bf](https://linux-hardware.org/?probe=2198e565bf) | May 22, 2021 |
| Wortmann      | 1220692_1470187             | Notebook    | [8febf0d66c](https://linux-hardware.org/?probe=8febf0d66c) | May 22, 2021 |
| Acer          | Aspire C24-865              | All in one  | [eb23862ded](https://linux-hardware.org/?probe=eb23862ded) | May 22, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [fd98fd839e](https://linux-hardware.org/?probe=fd98fd839e) | May 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f04eba21ce](https://linux-hardware.org/?probe=f04eba21ce) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [ad90a50d8d](https://linux-hardware.org/?probe=ad90a50d8d) | May 22, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [acaa4c3731](https://linux-hardware.org/?probe=acaa4c3731) | May 22, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [893f642cbb](https://linux-hardware.org/?probe=893f642cbb) | May 22, 2021 |
| Positivo      | CHT14B                      | Notebook    | [4aab647b4f](https://linux-hardware.org/?probe=4aab647b4f) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [d5ea76578b](https://linux-hardware.org/?probe=d5ea76578b) | May 22, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3762e2020](https://linux-hardware.org/?probe=d3762e2020) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [0ccd96a39e](https://linux-hardware.org/?probe=0ccd96a39e) | May 21, 2021 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [6ca37bdf8b](https://linux-hardware.org/?probe=6ca37bdf8b) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0ab74390ed](https://linux-hardware.org/?probe=0ab74390ed) | May 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [0a4bf488d4](https://linux-hardware.org/?probe=0a4bf488d4) | May 21, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [662203ff7f](https://linux-hardware.org/?probe=662203ff7f) | May 21, 2021 |
| HP            | Notebook                    | Notebook    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | Notebook    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c7d85ee10a](https://linux-hardware.org/?probe=c7d85ee10a) | May 21, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [197cbc5a5d](https://linux-hardware.org/?probe=197cbc5a5d) | May 21, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [b17a5c4cd5](https://linux-hardware.org/?probe=b17a5c4cd5) | May 21, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f908acc1ad](https://linux-hardware.org/?probe=f908acc1ad) | May 20, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [550a3398ee](https://linux-hardware.org/?probe=550a3398ee) | May 20, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c0b08eec61](https://linux-hardware.org/?probe=c0b08eec61) | May 20, 2021 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [88a08a450d](https://linux-hardware.org/?probe=88a08a450d) | May 20, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [7f2f6d6fc2](https://linux-hardware.org/?probe=7f2f6d6fc2) | May 20, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| ASRock        | E3C226D2I                   | Desktop     | [195f9748ad](https://linux-hardware.org/?probe=195f9748ad) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [295d74c4f2](https://linux-hardware.org/?probe=295d74c4f2) | May 20, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [a0188a80b1](https://linux-hardware.org/?probe=a0188a80b1) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [16725e35f7](https://linux-hardware.org/?probe=16725e35f7) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0a4ef78253](https://linux-hardware.org/?probe=0a4ef78253) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [e447290fed](https://linux-hardware.org/?probe=e447290fed) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [29f08a2300](https://linux-hardware.org/?probe=29f08a2300) | May 20, 2021 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [439e99b79e](https://linux-hardware.org/?probe=439e99b79e) | May 20, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [7911704f32](https://linux-hardware.org/?probe=7911704f32) | May 19, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [3366809177](https://linux-hardware.org/?probe=3366809177) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [4ec9eaac2f](https://linux-hardware.org/?probe=4ec9eaac2f) | May 19, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f2205716bb](https://linux-hardware.org/?probe=f2205716bb) | May 19, 2021 |
| Dell          | Inspiron 7737               | Notebook    | [ed5c16c955](https://linux-hardware.org/?probe=ed5c16c955) | May 19, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [d80f4e83a0](https://linux-hardware.org/?probe=d80f4e83a0) | May 19, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [507cb00cac](https://linux-hardware.org/?probe=507cb00cac) | May 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4a21e62a29](https://linux-hardware.org/?probe=4a21e62a29) | May 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [039435162c](https://linux-hardware.org/?probe=039435162c) | May 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6b27a727be](https://linux-hardware.org/?probe=6b27a727be) | May 19, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [4c5ee61420](https://linux-hardware.org/?probe=4c5ee61420) | May 19, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| Unknown       | X79                         | Desktop     | [718089029d](https://linux-hardware.org/?probe=718089029d) | May 18, 2021 |
| ASUSTek       | X510URR                     | Notebook    | [51577f00b4](https://linux-hardware.org/?probe=51577f00b4) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| ASUSTek       | X510URR                     | Notebook    | [e373dac808](https://linux-hardware.org/?probe=e373dac808) | May 18, 2021 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6e95528aca](https://linux-hardware.org/?probe=6e95528aca) | May 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [56baaff907](https://linux-hardware.org/?probe=56baaff907) | May 18, 2021 |
| Samsung       | R580/R590                   | Notebook    | [41ca2c7546](https://linux-hardware.org/?probe=41ca2c7546) | May 18, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [d2e4a69c16](https://linux-hardware.org/?probe=d2e4a69c16) | May 18, 2021 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [5a5c05e953](https://linux-hardware.org/?probe=5a5c05e953) | May 18, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [5569c32840](https://linux-hardware.org/?probe=5569c32840) | May 18, 2021 |
| HP            | Spectre Folio Convertibl... | Convertible | [87199d7e85](https://linux-hardware.org/?probe=87199d7e85) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [64c121a751](https://linux-hardware.org/?probe=64c121a751) | May 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS1B803    | Notebook    | [ae357880c6](https://linux-hardware.org/?probe=ae357880c6) | May 18, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| Dell          | Latitude 7400               | Notebook    | [660659882e](https://linux-hardware.org/?probe=660659882e) | May 17, 2021 |
| Dell          | Latitude 7400               | Notebook    | [4901f6b836](https://linux-hardware.org/?probe=4901f6b836) | May 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e32d9effa0](https://linux-hardware.org/?probe=e32d9effa0) | May 17, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [5287ceef8d](https://linux-hardware.org/?probe=5287ceef8d) | May 17, 2021 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [824bb881d7](https://linux-hardware.org/?probe=824bb881d7) | May 17, 2021 |
| Dell          | 077RRV A00                  | Desktop     | [c9ed9d5dfa](https://linux-hardware.org/?probe=c9ed9d5dfa) | May 17, 2021 |
| ASRock        | Z270 Pro4                   | Desktop     | [ba92e877c3](https://linux-hardware.org/?probe=ba92e877c3) | May 17, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [17722fe0bf](https://linux-hardware.org/?probe=17722fe0bf) | May 17, 2021 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [ca8565e246](https://linux-hardware.org/?probe=ca8565e246) | May 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c98ee08146](https://linux-hardware.org/?probe=c98ee08146) | May 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [d8cec0c95b](https://linux-hardware.org/?probe=d8cec0c95b) | May 17, 2021 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [89871a46e7](https://linux-hardware.org/?probe=89871a46e7) | May 17, 2021 |
| Dell          | G5 5590                     | Notebook    | [18621bd612](https://linux-hardware.org/?probe=18621bd612) | May 17, 2021 |
| Dell          | G5 5590                     | Notebook    | [3f55c4844d](https://linux-hardware.org/?probe=3f55c4844d) | May 17, 2021 |
| Dell          | Precision 5540              | Notebook    | [91e4aff19e](https://linux-hardware.org/?probe=91e4aff19e) | May 17, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [42eddedfb8](https://linux-hardware.org/?probe=42eddedfb8) | May 17, 2021 |
| Lenovo        | ThinkPad T440p 20AW009YB... | Notebook    | [1dda6f002e](https://linux-hardware.org/?probe=1dda6f002e) | May 16, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [5da8abe961](https://linux-hardware.org/?probe=5da8abe961) | May 16, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [43bbdc2153](https://linux-hardware.org/?probe=43bbdc2153) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [51c5d13230](https://linux-hardware.org/?probe=51c5d13230) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [557f952ce8](https://linux-hardware.org/?probe=557f952ce8) | May 16, 2021 |
| Sony          | VPCS12C5E                   | Notebook    | [188765c8f8](https://linux-hardware.org/?probe=188765c8f8) | May 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a035be3ea2](https://linux-hardware.org/?probe=a035be3ea2) | May 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1579b9c9d7](https://linux-hardware.org/?probe=1579b9c9d7) | May 16, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [16c877dbfe](https://linux-hardware.org/?probe=16c877dbfe) | May 16, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [35257f4cf0](https://linux-hardware.org/?probe=35257f4cf0) | May 16, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [4af8e42b5a](https://linux-hardware.org/?probe=4af8e42b5a) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [1d398072e8](https://linux-hardware.org/?probe=1d398072e8) | May 15, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [be75687645](https://linux-hardware.org/?probe=be75687645) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [620cd76f75](https://linux-hardware.org/?probe=620cd76f75) | May 15, 2021 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | Notebook    | [0f8a6b3dcf](https://linux-hardware.org/?probe=0f8a6b3dcf) | May 15, 2021 |
| Alienware     | 07HV66 A01                  | Desktop     | [016da6343d](https://linux-hardware.org/?probe=016da6343d) | May 15, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [310752864a](https://linux-hardware.org/?probe=310752864a) | May 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c85191ea3e](https://linux-hardware.org/?probe=c85191ea3e) | May 15, 2021 |
| Dell          | Latitude 5480               | Notebook    | [2c7c1983ac](https://linux-hardware.org/?probe=2c7c1983ac) | May 15, 2021 |
| Intel         | NUC9i9QNB K49243-402        | Mini pc     | [592fa60c7d](https://linux-hardware.org/?probe=592fa60c7d) | May 14, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [16d1cff353](https://linux-hardware.org/?probe=16d1cff353) | May 14, 2021 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [529fdcaf2a](https://linux-hardware.org/?probe=529fdcaf2a) | May 14, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [ffe39a0c5a](https://linux-hardware.org/?probe=ffe39a0c5a) | May 14, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [a419bff4a3](https://linux-hardware.org/?probe=a419bff4a3) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| ASRock        | X570 Creator                | Desktop     | [6ac8300ce8](https://linux-hardware.org/?probe=6ac8300ce8) | May 14, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [f36ea99568](https://linux-hardware.org/?probe=f36ea99568) | May 14, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cb589a4d2c](https://linux-hardware.org/?probe=cb589a4d2c) | May 14, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [00a23f1149](https://linux-hardware.org/?probe=00a23f1149) | May 14, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [9907063783](https://linux-hardware.org/?probe=9907063783) | May 14, 2021 |
| Irbis         | TW94                        | Notebook    | [099d5c86c3](https://linux-hardware.org/?probe=099d5c86c3) | May 14, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [3853338a60](https://linux-hardware.org/?probe=3853338a60) | May 14, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [0885b824f7](https://linux-hardware.org/?probe=0885b824f7) | May 13, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [231212bfe0](https://linux-hardware.org/?probe=231212bfe0) | May 13, 2021 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [924b420c67](https://linux-hardware.org/?probe=924b420c67) | May 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [91d1b5e802](https://linux-hardware.org/?probe=91d1b5e802) | May 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [1e4a851ad2](https://linux-hardware.org/?probe=1e4a851ad2) | May 13, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3d9373090c](https://linux-hardware.org/?probe=3d9373090c) | May 13, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [d8f52bab1c](https://linux-hardware.org/?probe=d8f52bab1c) | May 12, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [a36fa0a3b4](https://linux-hardware.org/?probe=a36fa0a3b4) | May 12, 2021 |
| Lenovo        | ThinkPad T490s 20NYS04V0... | Notebook    | [18da93a841](https://linux-hardware.org/?probe=18da93a841) | May 12, 2021 |
| HP            | ProBook 4530s               | Notebook    | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [e0a49e12f1](https://linux-hardware.org/?probe=e0a49e12f1) | May 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [b526eddd71](https://linux-hardware.org/?probe=b526eddd71) | May 12, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [22e9d3f5fd](https://linux-hardware.org/?probe=22e9d3f5fd) | May 12, 2021 |
| ASUSTek       | UX330UAK                    | Notebook    | [0abe5082fe](https://linux-hardware.org/?probe=0abe5082fe) | May 12, 2021 |
| ASUSTek       | UX330UAK                    | Notebook    | [0f72a78d10](https://linux-hardware.org/?probe=0f72a78d10) | May 12, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [eeac0e0535](https://linux-hardware.org/?probe=eeac0e0535) | May 12, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [dc39103e2e](https://linux-hardware.org/?probe=dc39103e2e) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [370eb9dee4](https://linux-hardware.org/?probe=370eb9dee4) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [d2951f517e](https://linux-hardware.org/?probe=d2951f517e) | May 12, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [565e8ea07c](https://linux-hardware.org/?probe=565e8ea07c) | May 12, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [c4c9a421b7](https://linux-hardware.org/?probe=c4c9a421b7) | May 12, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [10b0865cab](https://linux-hardware.org/?probe=10b0865cab) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [744242646f](https://linux-hardware.org/?probe=744242646f) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [c5e4ff103f](https://linux-hardware.org/?probe=c5e4ff103f) | May 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ad9a7e706d](https://linux-hardware.org/?probe=ad9a7e706d) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [049f443199](https://linux-hardware.org/?probe=049f443199) | May 11, 2021 |
| HP            | EliteBook x360 830 G6       | Convertible | [d862548439](https://linux-hardware.org/?probe=d862548439) | May 11, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [702de808b0](https://linux-hardware.org/?probe=702de808b0) | May 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [6b7557c4d1](https://linux-hardware.org/?probe=6b7557c4d1) | May 11, 2021 |
| Dell          | Latitude E6320              | Notebook    | [3d76e2296e](https://linux-hardware.org/?probe=3d76e2296e) | May 11, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [6afabfb5b3](https://linux-hardware.org/?probe=6afabfb5b3) | May 11, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cff0fbf297](https://linux-hardware.org/?probe=cff0fbf297) | May 11, 2021 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [08a78a5d61](https://linux-hardware.org/?probe=08a78a5d61) | May 11, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [1c1e7aeecf](https://linux-hardware.org/?probe=1c1e7aeecf) | May 11, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [fcc03f3447](https://linux-hardware.org/?probe=fcc03f3447) | May 11, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [a7c97c0108](https://linux-hardware.org/?probe=a7c97c0108) | May 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6410919f51](https://linux-hardware.org/?probe=6410919f51) | May 10, 2021 |
| Positivo      | Q4128C-S                    | Notebook    | [15db0dcbec](https://linux-hardware.org/?probe=15db0dcbec) | May 10, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [bb0d6e1883](https://linux-hardware.org/?probe=bb0d6e1883) | May 10, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| AZW           | Z83-V                       | Notebook    | [6ca32efbd7](https://linux-hardware.org/?probe=6ca32efbd7) | May 10, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [22781d64e0](https://linux-hardware.org/?probe=22781d64e0) | May 10, 2021 |
| HP            | 1494                        | Desktop     | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b61a1c61d8](https://linux-hardware.org/?probe=b61a1c61d8) | May 10, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [a3a6a201cf](https://linux-hardware.org/?probe=a3a6a201cf) | May 10, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2910a4173e](https://linux-hardware.org/?probe=2910a4173e) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9b4ee21fd](https://linux-hardware.org/?probe=c9b4ee21fd) | May 10, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [c4df22f011](https://linux-hardware.org/?probe=c4df22f011) | May 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a1e5c2f4f5](https://linux-hardware.org/?probe=a1e5c2f4f5) | May 09, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [f66084bbd9](https://linux-hardware.org/?probe=f66084bbd9) | May 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [816b6507ca](https://linux-hardware.org/?probe=816b6507ca) | May 09, 2021 |
| HP            | 826A A01                    | All in one  | [c60fceaee4](https://linux-hardware.org/?probe=c60fceaee4) | May 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [16ae1580d3](https://linux-hardware.org/?probe=16ae1580d3) | May 09, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6969c309d4](https://linux-hardware.org/?probe=6969c309d4) | May 09, 2021 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [23c21ceedf](https://linux-hardware.org/?probe=23c21ceedf) | May 08, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [993800d632](https://linux-hardware.org/?probe=993800d632) | May 08, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [ef87a640ab](https://linux-hardware.org/?probe=ef87a640ab) | May 08, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [312ad18259](https://linux-hardware.org/?probe=312ad18259) | May 08, 2021 |
| Biostar       | H81MLC                      | Desktop     | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [25f309da06](https://linux-hardware.org/?probe=25f309da06) | May 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [dc95288d50](https://linux-hardware.org/?probe=dc95288d50) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [20fb29a6ae](https://linux-hardware.org/?probe=20fb29a6ae) | May 08, 2021 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [ec32719d86](https://linux-hardware.org/?probe=ec32719d86) | May 08, 2021 |
| Positivo      | C41TB                       | Notebook    | [060b2d882f](https://linux-hardware.org/?probe=060b2d882f) | May 08, 2021 |
| Dell          | Precision M4600             | Notebook    | [9f1f5b7ef7](https://linux-hardware.org/?probe=9f1f5b7ef7) | May 08, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [d6af9c1156](https://linux-hardware.org/?probe=d6af9c1156) | May 07, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [155ecefe3c](https://linux-hardware.org/?probe=155ecefe3c) | May 07, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [22aa84909b](https://linux-hardware.org/?probe=22aa84909b) | May 07, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a0c245e667](https://linux-hardware.org/?probe=a0c245e667) | May 07, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [f34f4b2b22](https://linux-hardware.org/?probe=f34f4b2b22) | May 07, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [73fd34e4a9](https://linux-hardware.org/?probe=73fd34e4a9) | May 07, 2021 |
| Acer          | Veriton S2660G              | Desktop     | [31f3a2c202](https://linux-hardware.org/?probe=31f3a2c202) | May 07, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| Dell          | Latitude 5480               | Notebook    | [05ee730b0f](https://linux-hardware.org/?probe=05ee730b0f) | May 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [bdd3604cd8](https://linux-hardware.org/?probe=bdd3604cd8) | May 07, 2021 |
| Toshiba       | Satellite Click Mini L9W... | Notebook    | [b6204cb85d](https://linux-hardware.org/?probe=b6204cb85d) | May 07, 2021 |
| HP            | 1497                        | Desktop     | [bd5ee666bd](https://linux-hardware.org/?probe=bd5ee666bd) | May 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [353367c079](https://linux-hardware.org/?probe=353367c079) | May 06, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [c5563f5d49](https://linux-hardware.org/?probe=c5563f5d49) | May 06, 2021 |
| HP            | 1497                        | Desktop     | [e52c3c2489](https://linux-hardware.org/?probe=e52c3c2489) | May 06, 2021 |
| HP            | 1791                        | Desktop     | [ad7ad34a9d](https://linux-hardware.org/?probe=ad7ad34a9d) | May 06, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a34826ba77](https://linux-hardware.org/?probe=a34826ba77) | May 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [85a71e335a](https://linux-hardware.org/?probe=85a71e335a) | May 06, 2021 |
| Lenovo        | Board                       | Desktop     | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b411cc602f](https://linux-hardware.org/?probe=b411cc602f) | May 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [91b671b246](https://linux-hardware.org/?probe=91b671b246) | May 06, 2021 |
| Gigabyte      | B75M-D3P                    | Desktop     | [ab4f7cc66d](https://linux-hardware.org/?probe=ab4f7cc66d) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [d186bad578](https://linux-hardware.org/?probe=d186bad578) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [9036e74d34](https://linux-hardware.org/?probe=9036e74d34) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Dell          | Latitude 5520               | Notebook    | [3d5b6379e3](https://linux-hardware.org/?probe=3d5b6379e3) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Acer          | Aspire E5-576               | Notebook    | [58d3bc658d](https://linux-hardware.org/?probe=58d3bc658d) | May 06, 2021 |
| Acer          | Aspire E5-576               | Notebook    | [ee72676e37](https://linux-hardware.org/?probe=ee72676e37) | May 05, 2021 |
| Dell          | Latitude 5480               | Notebook    | [08f77f376e](https://linux-hardware.org/?probe=08f77f376e) | May 05, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [bf28931c58](https://linux-hardware.org/?probe=bf28931c58) | May 05, 2021 |
| HP            | ProBook 6460b               | Notebook    | [939b480c49](https://linux-hardware.org/?probe=939b480c49) | May 05, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ce9091f8ae](https://linux-hardware.org/?probe=ce9091f8ae) | May 05, 2021 |
| HP            | G42                         | Notebook    | [4a107897cf](https://linux-hardware.org/?probe=4a107897cf) | May 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9e64212d9f](https://linux-hardware.org/?probe=9e64212d9f) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [05f84c951f](https://linux-hardware.org/?probe=05f84c951f) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0NS0... | Notebook    | [6c0c3b3ea0](https://linux-hardware.org/?probe=6c0c3b3ea0) | May 05, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [3d5896459f](https://linux-hardware.org/?probe=3d5896459f) | May 05, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [f813c25e0d](https://linux-hardware.org/?probe=f813c25e0d) | May 05, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [1aee0fab6e](https://linux-hardware.org/?probe=1aee0fab6e) | May 05, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| Lenovo        | ThinkPad Edge E535 32607... | Notebook    | [b8627e7f6d](https://linux-hardware.org/?probe=b8627e7f6d) | May 05, 2021 |
| Acer          | Aspire V3-574G              | Notebook    | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1fefa80fdd](https://linux-hardware.org/?probe=1fefa80fdd) | May 05, 2021 |
| MSI           | CX61 2PC                    | Notebook    | [e0f172fbd5](https://linux-hardware.org/?probe=e0f172fbd5) | May 05, 2021 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [9af0cba170](https://linux-hardware.org/?probe=9af0cba170) | May 04, 2021 |
| MSI           | P55-GD80                    | Desktop     | [e9002ad1ad](https://linux-hardware.org/?probe=e9002ad1ad) | May 04, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [2f8ba8af70](https://linux-hardware.org/?probe=2f8ba8af70) | May 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1d8be54bc6](https://linux-hardware.org/?probe=1d8be54bc6) | May 04, 2021 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [79dc3442b5](https://linux-hardware.org/?probe=79dc3442b5) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [6d2bb231a4](https://linux-hardware.org/?probe=6d2bb231a4) | May 04, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [1ea17840d1](https://linux-hardware.org/?probe=1ea17840d1) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| MSI           | B350I PRO AC                | Desktop     | [db10576980](https://linux-hardware.org/?probe=db10576980) | May 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [aa18447496](https://linux-hardware.org/?probe=aa18447496) | May 03, 2021 |
| HP            | 3561                        | All in one  | [90e0f93e8d](https://linux-hardware.org/?probe=90e0f93e8d) | May 03, 2021 |
| HP            | 3561                        | All in one  | [740d8be804](https://linux-hardware.org/?probe=740d8be804) | May 03, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [e9c4f5a257](https://linux-hardware.org/?probe=e9c4f5a257) | May 03, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c118461e82](https://linux-hardware.org/?probe=c118461e82) | May 03, 2021 |
| Dell          | Latitude E5420              | Notebook    | [989dd7d36f](https://linux-hardware.org/?probe=989dd7d36f) | May 03, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [e59bd99fd2](https://linux-hardware.org/?probe=e59bd99fd2) | May 03, 2021 |
| ordissimo     | E17201                      | Notebook    | [ada3ab54e0](https://linux-hardware.org/?probe=ada3ab54e0) | May 03, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [3ab07ff020](https://linux-hardware.org/?probe=3ab07ff020) | May 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0R    | Notebook    | [11c98724d5](https://linux-hardware.org/?probe=11c98724d5) | May 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0R    | Notebook    | [6b88e1bda9](https://linux-hardware.org/?probe=6b88e1bda9) | May 03, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [fec58faf85](https://linux-hardware.org/?probe=fec58faf85) | May 03, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [4ade35b9d9](https://linux-hardware.org/?probe=4ade35b9d9) | May 02, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [649dbceeff](https://linux-hardware.org/?probe=649dbceeff) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [74bff35fdd](https://linux-hardware.org/?probe=74bff35fdd) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [3551a877a0](https://linux-hardware.org/?probe=3551a877a0) | May 02, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [d0660819a7](https://linux-hardware.org/?probe=d0660819a7) | May 02, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| HP            | 3029h                       | Desktop     | [f0912110eb](https://linux-hardware.org/?probe=f0912110eb) | May 02, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fe7a0a48f9](https://linux-hardware.org/?probe=fe7a0a48f9) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [1c48dea9a3](https://linux-hardware.org/?probe=1c48dea9a3) | May 02, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [95581f21a3](https://linux-hardware.org/?probe=95581f21a3) | May 01, 2021 |
| Lenovo        | ThinkPad 10 2nd 20E4S0UD... | Tablet      | [aae6f982a0](https://linux-hardware.org/?probe=aae6f982a0) | May 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [98693d2a86](https://linux-hardware.org/?probe=98693d2a86) | May 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bd65b55f0a](https://linux-hardware.org/?probe=bd65b55f0a) | May 01, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [89532532bc](https://linux-hardware.org/?probe=89532532bc) | May 01, 2021 |
| MSI           | P55-GD80                    | Desktop     | [2fc3e6dd6a](https://linux-hardware.org/?probe=2fc3e6dd6a) | May 01, 2021 |
| MSI           | P55-GD80                    | Desktop     | [a950a914fc](https://linux-hardware.org/?probe=a950a914fc) | May 01, 2021 |
| HP            | ProBook 4525s               | Notebook    | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [285dfaddb2](https://linux-hardware.org/?probe=285dfaddb2) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [857022f167](https://linux-hardware.org/?probe=857022f167) | May 01, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [59ec21b8d7](https://linux-hardware.org/?probe=59ec21b8d7) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e019fb0b7a](https://linux-hardware.org/?probe=e019fb0b7a) | May 01, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f15da67866](https://linux-hardware.org/?probe=f15da67866) | May 01, 2021 |
| Biostar       | TB350-BTC                   | Desktop     | [905cd6f7b5](https://linux-hardware.org/?probe=905cd6f7b5) | May 01, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [18081fbf4f](https://linux-hardware.org/?probe=18081fbf4f) | May 01, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [c00cb7a2c9](https://linux-hardware.org/?probe=c00cb7a2c9) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2BN0... | Notebook    | [8e3b1498da](https://linux-hardware.org/?probe=8e3b1498da) | Apr 30, 2021 |
| MSI           | B365M PRO-VDH               | Desktop     | [e0ff71901e](https://linux-hardware.org/?probe=e0ff71901e) | Apr 30, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [3fb3ca76ae](https://linux-hardware.org/?probe=3fb3ca76ae) | Apr 30, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0b1a312f87](https://linux-hardware.org/?probe=0b1a312f87) | Apr 30, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [2c97753280](https://linux-hardware.org/?probe=2c97753280) | Apr 30, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [f37646891f](https://linux-hardware.org/?probe=f37646891f) | Apr 30, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [9f2a73a4d2](https://linux-hardware.org/?probe=9f2a73a4d2) | Apr 30, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [179e39ba13](https://linux-hardware.org/?probe=179e39ba13) | Apr 30, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [b9dbe92598](https://linux-hardware.org/?probe=b9dbe92598) | Apr 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [916b016881](https://linux-hardware.org/?probe=916b016881) | Apr 30, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [e66999f076](https://linux-hardware.org/?probe=e66999f076) | Apr 30, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [e0484075af](https://linux-hardware.org/?probe=e0484075af) | Apr 30, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3bb19f53e9](https://linux-hardware.org/?probe=3bb19f53e9) | Apr 30, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a9a63b3679](https://linux-hardware.org/?probe=a9a63b3679) | Apr 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3401ccaf08](https://linux-hardware.org/?probe=3401ccaf08) | Apr 30, 2021 |
| HP            | 82F2 A01                    | Desktop     | [abecc29894](https://linux-hardware.org/?probe=abecc29894) | Apr 30, 2021 |
| HP            | 82F2 A01                    | Desktop     | [6c0f1f15f5](https://linux-hardware.org/?probe=6c0f1f15f5) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [be1fac0a5c](https://linux-hardware.org/?probe=be1fac0a5c) | Apr 29, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [a93721363c](https://linux-hardware.org/?probe=a93721363c) | Apr 29, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [e36e444bac](https://linux-hardware.org/?probe=e36e444bac) | Apr 29, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [a09dab9f9b](https://linux-hardware.org/?probe=a09dab9f9b) | Apr 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [492d410d60](https://linux-hardware.org/?probe=492d410d60) | Apr 29, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [89cb767ad1](https://linux-hardware.org/?probe=89cb767ad1) | Apr 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ac1ae66d11](https://linux-hardware.org/?probe=ac1ae66d11) | Apr 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [880e12969e](https://linux-hardware.org/?probe=880e12969e) | Apr 29, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [b4ec0e1cfe](https://linux-hardware.org/?probe=b4ec0e1cfe) | Apr 29, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| MSI           | GF615M-P33                  | Desktop     | [4219571ca8](https://linux-hardware.org/?probe=4219571ca8) | Apr 29, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [f323b316a2](https://linux-hardware.org/?probe=f323b316a2) | Apr 29, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| HP            | ProBook 4525s               | Notebook    | [78228915c0](https://linux-hardware.org/?probe=78228915c0) | Apr 28, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| System76      | Oryx Pro                    | Notebook    | [8c925dbcbe](https://linux-hardware.org/?probe=8c925dbcbe) | Apr 28, 2021 |
| MSI           | B250 PC MATE                | Desktop     | [4feda9bc8e](https://linux-hardware.org/?probe=4feda9bc8e) | Apr 28, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b73eecf0c5](https://linux-hardware.org/?probe=b73eecf0c5) | Apr 28, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [2273e237c4](https://linux-hardware.org/?probe=2273e237c4) | Apr 28, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [69827caaf1](https://linux-hardware.org/?probe=69827caaf1) | Apr 28, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [190564ec8e](https://linux-hardware.org/?probe=190564ec8e) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | Notebook    | [267f4b13f7](https://linux-hardware.org/?probe=267f4b13f7) | Apr 28, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f603a8365a](https://linux-hardware.org/?probe=f603a8365a) | Apr 28, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [9edeb6f6ad](https://linux-hardware.org/?probe=9edeb6f6ad) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [2a73d602a7](https://linux-hardware.org/?probe=2a73d602a7) | Apr 28, 2021 |
| Lenovo        | ThinkPad T430 2347G2P       | Notebook    | [c1fa54ec47](https://linux-hardware.org/?probe=c1fa54ec47) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | Notebook    | [9595aedbc6](https://linux-hardware.org/?probe=9595aedbc6) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [ad0dfb309f](https://linux-hardware.org/?probe=ad0dfb309f) | Apr 27, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [97016e3ff3](https://linux-hardware.org/?probe=97016e3ff3) | Apr 27, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c1a5d52c30](https://linux-hardware.org/?probe=c1a5d52c30) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c3cb8df55c](https://linux-hardware.org/?probe=c3cb8df55c) | Apr 26, 2021 |
| Positivo      | C41TB                       | Notebook    | [1d746150af](https://linux-hardware.org/?probe=1d746150af) | Apr 26, 2021 |
| Chuwi         | CoreBook Pro                | Notebook    | [ca84914f1d](https://linux-hardware.org/?probe=ca84914f1d) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| Positivo      | C41TB                       | Notebook    | [179c326307](https://linux-hardware.org/?probe=179c326307) | Apr 25, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7a133af461](https://linux-hardware.org/?probe=7a133af461) | Apr 25, 2021 |
| HP            | 246 G7 Notebook PC          | Notebook    | [a1ab7115cf](https://linux-hardware.org/?probe=a1ab7115cf) | Apr 25, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [b3a1820a41](https://linux-hardware.org/?probe=b3a1820a41) | Apr 25, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [4a7617821f](https://linux-hardware.org/?probe=4a7617821f) | Apr 25, 2021 |
| ASRock        | K10N78D                     | Desktop     | [9b0a7f242b](https://linux-hardware.org/?probe=9b0a7f242b) | Apr 24, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [573385087f](https://linux-hardware.org/?probe=573385087f) | Apr 24, 2021 |
| Dell          | Latitude 5511               | Notebook    | [4884be79b4](https://linux-hardware.org/?probe=4884be79b4) | Apr 24, 2021 |
| Dell          | Latitude 5511               | Notebook    | [f9f9c1acaa](https://linux-hardware.org/?probe=f9f9c1acaa) | Apr 24, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [557ef5a2ae](https://linux-hardware.org/?probe=557ef5a2ae) | Apr 23, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| Acer          | One S1003                   | Tablet      | [42b52c70c7](https://linux-hardware.org/?probe=42b52c70c7) | Apr 22, 2021 |
| Acer          | One S1003                   | Tablet      | [16d2bb232b](https://linux-hardware.org/?probe=16d2bb232b) | Apr 22, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1c206551a3](https://linux-hardware.org/?probe=1c206551a3) | Apr 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [fa4b4edcec](https://linux-hardware.org/?probe=fa4b4edcec) | Apr 22, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [4e2eabe9ea](https://linux-hardware.org/?probe=4e2eabe9ea) | Apr 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c4f21a1871](https://linux-hardware.org/?probe=c4f21a1871) | Apr 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d384c6f71c](https://linux-hardware.org/?probe=d384c6f71c) | Apr 21, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [320bab5ee4](https://linux-hardware.org/?probe=320bab5ee4) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ba7a3bd259](https://linux-hardware.org/?probe=ba7a3bd259) | Apr 21, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7b5da54a3b](https://linux-hardware.org/?probe=7b5da54a3b) | Apr 20, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [50704a4b1b](https://linux-hardware.org/?probe=50704a4b1b) | Apr 20, 2021 |
| ASUSTek       | ZenBook UX481FAY_UX481FA    | Notebook    | [0ec748b06e](https://linux-hardware.org/?probe=0ec748b06e) | Apr 20, 2021 |
| ASUSTek       | ZenBook UX481FAY_UX481FA    | Notebook    | [79ae1f5b0c](https://linux-hardware.org/?probe=79ae1f5b0c) | Apr 20, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [1b6b0bfcef](https://linux-hardware.org/?probe=1b6b0bfcef) | Apr 20, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [94173730f8](https://linux-hardware.org/?probe=94173730f8) | Apr 20, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [d54729d43d](https://linux-hardware.org/?probe=d54729d43d) | Apr 20, 2021 |
| Connect       | Tablet 9                    | Notebook    | [6d68fde5d8](https://linux-hardware.org/?probe=6d68fde5d8) | Apr 19, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [3aa509bfc6](https://linux-hardware.org/?probe=3aa509bfc6) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [4046940d3e](https://linux-hardware.org/?probe=4046940d3e) | Apr 19, 2021 |
| HP            | Pavilion 15                 | Notebook    | [cb55fa7fcd](https://linux-hardware.org/?probe=cb55fa7fcd) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [41035d03ea](https://linux-hardware.org/?probe=41035d03ea) | Apr 19, 2021 |
| MPMAN         | MPWIN8900CL                 | Notebook    | [3c21016b82](https://linux-hardware.org/?probe=3c21016b82) | Apr 19, 2021 |
| Dell          | Latitude 7410               | Notebook    | [d2a62b6afb](https://linux-hardware.org/?probe=d2a62b6afb) | Apr 19, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FX506... | Notebook    | [9d9c3e89a5](https://linux-hardware.org/?probe=9d9c3e89a5) | Apr 19, 2021 |
| Insyde        | i71c                        | Notebook    | [ec749b6624](https://linux-hardware.org/?probe=ec749b6624) | Apr 18, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Irbis         | TW90                        | Tablet      | [129d1bda9e](https://linux-hardware.org/?probe=129d1bda9e) | Apr 18, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [1f0b5b042f](https://linux-hardware.org/?probe=1f0b5b042f) | Apr 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [71cec0648d](https://linux-hardware.org/?probe=71cec0648d) | Apr 18, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [12af9205b0](https://linux-hardware.org/?probe=12af9205b0) | Apr 18, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [8648cefc80](https://linux-hardware.org/?probe=8648cefc80) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [29537c9609](https://linux-hardware.org/?probe=29537c9609) | Apr 17, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FX506... | Notebook    | [f35c55ba89](https://linux-hardware.org/?probe=f35c55ba89) | Apr 17, 2021 |
| HP            | ProBook 4525s               | Notebook    | [5fea2f9652](https://linux-hardware.org/?probe=5fea2f9652) | Apr 17, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [757a310b4a](https://linux-hardware.org/?probe=757a310b4a) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2fe3493737](https://linux-hardware.org/?probe=2fe3493737) | Apr 17, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [4dd2eeb695](https://linux-hardware.org/?probe=4dd2eeb695) | Apr 17, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [dc8fb53f61](https://linux-hardware.org/?probe=dc8fb53f61) | Apr 17, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [d79109ba72](https://linux-hardware.org/?probe=d79109ba72) | Apr 16, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [f8d626eea1](https://linux-hardware.org/?probe=f8d626eea1) | Apr 16, 2021 |
| Dell          | Latitude 5480               | Notebook    | [ff6578cc63](https://linux-hardware.org/?probe=ff6578cc63) | Apr 16, 2021 |
| Shenzhen P... | MOMO7W                      | Notebook    | [763921a4a1](https://linux-hardware.org/?probe=763921a4a1) | Apr 16, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [0691d30eea](https://linux-hardware.org/?probe=0691d30eea) | Apr 16, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [6b2b705578](https://linux-hardware.org/?probe=6b2b705578) | Apr 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b5dda74089](https://linux-hardware.org/?probe=b5dda74089) | Apr 14, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [3089a9a333](https://linux-hardware.org/?probe=3089a9a333) | Apr 14, 2021 |
| Dell          | Latitude E6520              | Notebook    | [0283ca3671](https://linux-hardware.org/?probe=0283ca3671) | Apr 13, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [907647d9a2](https://linux-hardware.org/?probe=907647d9a2) | Apr 13, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| Sony          | VPCSC41FM                   | Notebook    | [b04963620c](https://linux-hardware.org/?probe=b04963620c) | Apr 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [e809ca489d](https://linux-hardware.org/?probe=e809ca489d) | Apr 12, 2021 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [6a307c820d](https://linux-hardware.org/?probe=6a307c820d) | Apr 12, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e6f339fbf7](https://linux-hardware.org/?probe=e6f339fbf7) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [b9ec42b5ff](https://linux-hardware.org/?probe=b9ec42b5ff) | Apr 11, 2021 |
| Lenovo        | ThinkPad E14 20RACTO1WW     | Notebook    | [a1d56d3f37](https://linux-hardware.org/?probe=a1d56d3f37) | Apr 11, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8cc623fb70](https://linux-hardware.org/?probe=8cc623fb70) | Apr 10, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5f52a14994](https://linux-hardware.org/?probe=5f52a14994) | Apr 10, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [722e60e516](https://linux-hardware.org/?probe=722e60e516) | Apr 10, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | Notebook    | [92079ca9e3](https://linux-hardware.org/?probe=92079ca9e3) | Apr 10, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [8f5d7459d2](https://linux-hardware.org/?probe=8f5d7459d2) | Apr 10, 2021 |
| Standard      | Unknown                     | Notebook    | [2e2b5648ce](https://linux-hardware.org/?probe=2e2b5648ce) | Apr 09, 2021 |
| Notebook      | N8xEJEK                     | Notebook    | [4794a1ad98](https://linux-hardware.org/?probe=4794a1ad98) | Apr 09, 2021 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [006b564b4d](https://linux-hardware.org/?probe=006b564b4d) | Apr 09, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [261dc7158d](https://linux-hardware.org/?probe=261dc7158d) | Apr 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a4b4d5abd6](https://linux-hardware.org/?probe=a4b4d5abd6) | Apr 09, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c9dcfde4e1](https://linux-hardware.org/?probe=c9dcfde4e1) | Apr 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [0b127087c5](https://linux-hardware.org/?probe=0b127087c5) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [b2c194ec6f](https://linux-hardware.org/?probe=b2c194ec6f) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | Notebook    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [3440af3ade](https://linux-hardware.org/?probe=3440af3ade) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Lenovo        | Board                       | Desktop     | [d27988d8dd](https://linux-hardware.org/?probe=d27988d8dd) | Apr 09, 2021 |
| HP            | EliteBook x360 830 G6       | Convertible | [c568aa9f2c](https://linux-hardware.org/?probe=c568aa9f2c) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4c2971804a](https://linux-hardware.org/?probe=4c2971804a) | Apr 09, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [6e9360be26](https://linux-hardware.org/?probe=6e9360be26) | Apr 09, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [f1bdcd63e8](https://linux-hardware.org/?probe=f1bdcd63e8) | Apr 09, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [7730367108](https://linux-hardware.org/?probe=7730367108) | Apr 08, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [8acf527693](https://linux-hardware.org/?probe=8acf527693) | Apr 08, 2021 |
| Lenovo        | G40-70 80GA                 | Notebook    | [ca5eaa8733](https://linux-hardware.org/?probe=ca5eaa8733) | Apr 08, 2021 |
| Dell          | 0GWHMW A03                  | Desktop     | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [352aee7525](https://linux-hardware.org/?probe=352aee7525) | Apr 08, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [b3b901029c](https://linux-hardware.org/?probe=b3b901029c) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [2824275b63](https://linux-hardware.org/?probe=2824275b63) | Apr 07, 2021 |
| SUN MICROS... | ASSY,MOTHERBOARD,X4170 5... | Server      | [8f6e544820](https://linux-hardware.org/?probe=8f6e544820) | Apr 07, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [0fe23f914d](https://linux-hardware.org/?probe=0fe23f914d) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [035de5bc79](https://linux-hardware.org/?probe=035de5bc79) | Apr 06, 2021 |
| Dell          | XPS L502X                   | Notebook    | [fe680d21e1](https://linux-hardware.org/?probe=fe680d21e1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | Notebook    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| Dell          | Inspiron 5580               | Notebook    | [9f4333693a](https://linux-hardware.org/?probe=9f4333693a) | Apr 06, 2021 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [66d90069a1](https://linux-hardware.org/?probe=66d90069a1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [7441379cc7](https://linux-hardware.org/?probe=7441379cc7) | Apr 06, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [de5a14a4f3](https://linux-hardware.org/?probe=de5a14a4f3) | Apr 06, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [1baa6a6817](https://linux-hardware.org/?probe=1baa6a6817) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7490f0847d](https://linux-hardware.org/?probe=7490f0847d) | Apr 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a78f2d8699](https://linux-hardware.org/?probe=a78f2d8699) | Apr 05, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [ec750c2771](https://linux-hardware.org/?probe=ec750c2771) | Apr 05, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [07b527d603](https://linux-hardware.org/?probe=07b527d603) | Apr 05, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [914388c5c5](https://linux-hardware.org/?probe=914388c5c5) | Apr 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [1fe5a2530d](https://linux-hardware.org/?probe=1fe5a2530d) | Apr 05, 2021 |
| Dell          | Latitude 7275               | Tablet      | [7a9c92f242](https://linux-hardware.org/?probe=7a9c92f242) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [ddfa056734](https://linux-hardware.org/?probe=ddfa056734) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [d38419f785](https://linux-hardware.org/?probe=d38419f785) | Apr 04, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b865e7ccff](https://linux-hardware.org/?probe=b865e7ccff) | Apr 04, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [4957115cec](https://linux-hardware.org/?probe=4957115cec) | Apr 04, 2021 |
| MSI           | GS73VR 7RG                  | Notebook    | [394ae3b96f](https://linux-hardware.org/?probe=394ae3b96f) | Apr 04, 2021 |
| Dell          | XPS L502X                   | Notebook    | [134b59c95e](https://linux-hardware.org/?probe=134b59c95e) | Apr 03, 2021 |
| Dell          | XPS L502X                   | Notebook    | [4b1e34e9ed](https://linux-hardware.org/?probe=4b1e34e9ed) | Apr 03, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [42b83bbd08](https://linux-hardware.org/?probe=42b83bbd08) | Apr 03, 2021 |
| ASUSTek       | UX303UA                     | Notebook    | [fb33764025](https://linux-hardware.org/?probe=fb33764025) | Apr 03, 2021 |
| ASUSTek       | UX303UA                     | Notebook    | [9c8c52cca9](https://linux-hardware.org/?probe=9c8c52cca9) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| Dell          | Latitude 3570               | Notebook    | [e83eac31ce](https://linux-hardware.org/?probe=e83eac31ce) | Apr 02, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [5af64d1099](https://linux-hardware.org/?probe=5af64d1099) | Apr 02, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [7dc56a24a6](https://linux-hardware.org/?probe=7dc56a24a6) | Apr 02, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| System76      | Oryx Pro                    | Notebook    | [a2d6163aef](https://linux-hardware.org/?probe=a2d6163aef) | Apr 02, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3b33c626bd](https://linux-hardware.org/?probe=3b33c626bd) | Apr 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ea8316fe72](https://linux-hardware.org/?probe=ea8316fe72) | Apr 01, 2021 |
| Gigabyte      | A520M DS3H                  | Desktop     | [6977cb0073](https://linux-hardware.org/?probe=6977cb0073) | Mar 31, 2021 |
| HP            | EliteBook 755 G2            | Notebook    | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [af3acea363](https://linux-hardware.org/?probe=af3acea363) | Mar 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e6a1ba54cc](https://linux-hardware.org/?probe=e6a1ba54cc) | Mar 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [84cc759796](https://linux-hardware.org/?probe=84cc759796) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [fcc9dabb3d](https://linux-hardware.org/?probe=fcc9dabb3d) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [ed7f2979b9](https://linux-hardware.org/?probe=ed7f2979b9) | Mar 30, 2021 |
| Dell          | G5 5505                     | Notebook    | [466cbb0b8e](https://linux-hardware.org/?probe=466cbb0b8e) | Mar 30, 2021 |
| HP            | ProBook 4525s               | Notebook    | [390e030b1e](https://linux-hardware.org/?probe=390e030b1e) | Mar 29, 2021 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [9b283640c6](https://linux-hardware.org/?probe=9b283640c6) | Mar 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [10b6c6cbc0](https://linux-hardware.org/?probe=10b6c6cbc0) | Mar 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [a0ef308b2c](https://linux-hardware.org/?probe=a0ef308b2c) | Mar 29, 2021 |
| Alienware     | 0FRTKJ A00                  | Desktop     | [e31c5f36aa](https://linux-hardware.org/?probe=e31c5f36aa) | Mar 28, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [cf1b5653e8](https://linux-hardware.org/?probe=cf1b5653e8) | Mar 28, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [56cafec701](https://linux-hardware.org/?probe=56cafec701) | Mar 28, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b41b0c2610](https://linux-hardware.org/?probe=b41b0c2610) | Mar 28, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [0f0ff492d9](https://linux-hardware.org/?probe=0f0ff492d9) | Mar 27, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [87cb9f98e5](https://linux-hardware.org/?probe=87cb9f98e5) | Mar 27, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6bf5c0b770](https://linux-hardware.org/?probe=6bf5c0b770) | Mar 27, 2021 |
| Dell          | Inspiron 5505               | Notebook    | [9b4af8147c](https://linux-hardware.org/?probe=9b4af8147c) | Mar 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| Lenovo        | ThinkPad T480s 20L7001RP... | Notebook    | [1992bbf887](https://linux-hardware.org/?probe=1992bbf887) | Mar 24, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [684313d4d9](https://linux-hardware.org/?probe=684313d4d9) | Mar 24, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a0f771669c](https://linux-hardware.org/?probe=a0f771669c) | Mar 24, 2021 |
| Lenovo        | ThinkPad T420 4236VD9       | Notebook    | [abaf5a9e37](https://linux-hardware.org/?probe=abaf5a9e37) | Mar 24, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [4a9ff479d0](https://linux-hardware.org/?probe=4a9ff479d0) | Mar 24, 2021 |
| HP            | Pavilion dm4                | Notebook    | [700de148a7](https://linux-hardware.org/?probe=700de148a7) | Mar 24, 2021 |
| Dell          | Precision 5520              | Notebook    | [f95b93d1ca](https://linux-hardware.org/?probe=f95b93d1ca) | Mar 23, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [01c43fc8b4](https://linux-hardware.org/?probe=01c43fc8b4) | Mar 23, 2021 |
| MSI           | 760GM-P21                   | Desktop     | [91a13be8c4](https://linux-hardware.org/?probe=91a13be8c4) | Mar 17, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6124e0aa83](https://linux-hardware.org/?probe=6124e0aa83) | Mar 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [07cd9eac56](https://linux-hardware.org/?probe=07cd9eac56) | Mar 17, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [25c2dd2a64](https://linux-hardware.org/?probe=25c2dd2a64) | Mar 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [cbabe52a7f](https://linux-hardware.org/?probe=cbabe52a7f) | Mar 10, 2021 |
| Dell          | 0GDJXY A00                  | All in one  | [a9270e1284](https://linux-hardware.org/?probe=a9270e1284) | Mar 06, 2021 |
| Dell          | 0GDJXY A00                  | All in one  | [1297bd9914](https://linux-hardware.org/?probe=1297bd9914) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a758fdf9af](https://linux-hardware.org/?probe=a758fdf9af) | Mar 01, 2021 |
| Gigabyte      | Z490 VISION D               | Desktop     | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6b611bf344](https://linux-hardware.org/?probe=6b611bf344) | Feb 26, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [fdc4baf022](https://linux-hardware.org/?probe=fdc4baf022) | Feb 23, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [86f60bbc44](https://linux-hardware.org/?probe=86f60bbc44) | Feb 23, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [24fe67fa00](https://linux-hardware.org/?probe=24fe67fa00) | Jan 29, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [ce19e3ee18](https://linux-hardware.org/?probe=ce19e3ee18) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [e133316a3c](https://linux-hardware.org/?probe=e133316a3c) | Nov 28, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [f1c5e6588a](https://linux-hardware.org/?probe=f1c5e6588a) | Nov 23, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [a6e7ec5f07](https://linux-hardware.org/?probe=a6e7ec5f07) | Nov 22, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e3a5631517](https://linux-hardware.org/?probe=e3a5631517) | Nov 15, 2020 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [ec056bb102](https://linux-hardware.org/?probe=ec056bb102) | Nov 12, 2020 |
| Dell          | G5 5505                     | Notebook    | [5770e00a83](https://linux-hardware.org/?probe=5770e00a83) | Nov 11, 2020 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [541347d1a0](https://linux-hardware.org/?probe=541347d1a0) | Nov 11, 2020 |
| HP            | Unknown                     | Notebook    | [734dd9e30e](https://linux-hardware.org/?probe=734dd9e30e) | Nov 08, 2020 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f695c35adf](https://linux-hardware.org/?probe=f695c35adf) | Oct 12, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | Notebook    | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Positivo      | POS-PARS760GCD              | Desktop     | [482e549764](https://linux-hardware.org/?probe=482e549764) | Sep 05, 2020 |
| HP            | Notebook                    | Notebook    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                             | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| 5.13.12-200.fc34.x86_64                             | 93        | 6.95%   |
| 5.11.12-300.fc34.x86_64                             | 92        | 6.88%   |
| 5.12.13-300.fc34.x86_64                             | 79        | 5.9%    |
| 5.12.8-300.fc34.x86_64                              | 60        | 4.48%   |
| 5.11.17-300.fc34.x86_64                             | 56        | 4.19%   |
| 5.11.16-300.fc34.x86_64                             | 55        | 4.11%   |
| 5.12.14-300.fc34.x86_64                             | 53        | 3.96%   |
| 5.12.9-300.fc34.x86_64                              | 46        | 3.44%   |
| 5.13.4-200.fc34.x86_64                              | 45        | 3.36%   |
| 5.13.9-200.fc34.x86_64                              | 43        | 3.21%   |
| 5.13.8-200.fc34.x86_64                              | 42        | 3.14%   |
| 5.11.18-300.fc34.x86_64                             | 41        | 3.06%   |
| 5.13.6-200.fc34.x86_64                              | 40        | 2.99%   |
| 5.12.11-300.fc34.x86_64                             | 40        | 2.99%   |
| 5.11.20-300.fc34.x86_64                             | 40        | 2.99%   |
| 5.11.11-300.fc34.x86_64                             | 39        | 2.91%   |
| 5.12.7-300.fc34.x86_64                              | 37        | 2.77%   |
| 5.12.15-300.fc34.x86_64                             | 37        | 2.77%   |
| 5.12.12-300.fc34.x86_64                             | 36        | 2.69%   |
| 5.13.10-200.fc34.x86_64                             | 31        | 2.32%   |
| 5.12.6-300.fc34.x86_64                              | 28        | 2.09%   |
| 5.12.10-300.fc34.x86_64                             | 28        | 2.09%   |
| 5.11.15-300.fc34.x86_64                             | 25        | 1.87%   |
| 5.13.13-200.fc34.x86_64                             | 22        | 1.64%   |
| 5.11.19-300.fc34.x86_64                             | 22        | 1.64%   |
| 5.11.3-300.fc34.x86_64                              | 18        | 1.35%   |
| 5.13.5-200.fc34.x86_64                              | 17        | 1.27%   |
| 5.11.21-300.fc34.x86_64                             | 16        | 1.2%    |
| 5.11.10-300.fc34.x86_64                             | 14        | 1.05%   |
| 5.13.7-200.fc34.x86_64                              | 12        | 0.9%    |
| 5.12.5-300.fc34.x86_64                              | 12        | 0.9%    |
| 5.11.14-300.fc34.x86_64                             | 11        | 0.82%   |
| 5.11.13-300.fc34.x86_64                             | 11        | 0.82%   |
| 5.12.17-300.fc34.x86_64                             | 8         | 0.6%    |
| 5.11.8-300.fc34.x86_64                              | 6         | 0.45%   |
| 5.13.14-200.fc34.x86_64                             | 5         | 0.37%   |
| 5.11.21-300.fc34.aarch64                            | 5         | 0.37%   |
| 5.13.1-300.fc34.x86_64                              | 4         | 0.3%    |
| 5.11.9-300.fc34.x86_64                              | 4         | 0.3%    |
| 5.11.0-156.fc34.x86_64                              | 4         | 0.3%    |
| 5.11.7-300.fc34.x86_64                              | 3         | 0.22%   |
| 5.12.2-300.fc34.x86_64                              | 2         | 0.15%   |
| 5.11.6-300.fc34.x86_64                              | 2         | 0.15%   |
| 5.11.2-300.fc34.x86_64                              | 2         | 0.15%   |
| 5.10.0-0.rc3.68.fc34.x86_64                         | 2         | 0.15%   |
| 5.10.0-0.rc1.20201028gited8780e3f2ec.57.fc34.x86_64 | 2         | 0.15%   |
| 5.9.0-0.rc8.20201009git7575fdda569b.32.fc34.x86_64  | 1         | 0.07%   |
| 5.9.0-0.rc3.1.fc34.x86_64                           | 1         | 0.07%   |
| 5.8.0-1.fc33.x86_64                                 | 1         | 0.07%   |
| 5.4.111                                             | 1         | 0.07%   |
| 5.14.0-0.rc7.54.vanilla.1.fc34.x86_64               | 1         | 0.07%   |
| 5.14.0-0.rc7.54.rog.fc34.x86_64                     | 1         | 0.07%   |
| 5.14.0-0.rc3.20210728git7d549995d4e0.31.fc35.x86_64 | 1         | 0.07%   |
| 5.13.9-200.rog.fc34.x86_64                          | 1         | 0.07%   |
| 5.13.8-xm1cacule.0.fc34.x86_64                      | 1         | 0.07%   |
| 5.13.6-250.vanilla.1.fc34.x86_64                    | 1         | 0.07%   |
| 5.13.4-201.fsync.fc34.x86_64                        | 1         | 0.07%   |
| 5.13.2-300.fc34.x86_64                              | 1         | 0.07%   |
| 5.13.11-xm1.0.fc34.x86_64                           | 1         | 0.07%   |
| 5.13.11-202108181951                                | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.13.12  | 93        | 6.95%   |
| 5.11.12  | 92        | 6.88%   |
| 5.12.13  | 80        | 5.98%   |
| 5.12.8   | 61        | 4.56%   |
| 5.11.17  | 56        | 4.19%   |
| 5.11.16  | 56        | 4.19%   |
| 5.12.14  | 55        | 4.11%   |
| 5.13.4   | 46        | 3.44%   |
| 5.12.9   | 46        | 3.44%   |
| 5.13.9   | 44        | 3.29%   |
| 5.13.8   | 43        | 3.21%   |
| 5.12.11  | 42        | 3.14%   |
| 5.13.6   | 41        | 3.06%   |
| 5.11.18  | 41        | 3.06%   |
| 5.11.20  | 40        | 2.99%   |
| 5.11.11  | 39        | 2.91%   |
| 5.12.7   | 38        | 2.84%   |
| 5.12.15  | 38        | 2.84%   |
| 5.12.12  | 36        | 2.69%   |
| 5.13.10  | 31        | 2.32%   |
| 5.12.10  | 30        | 2.24%   |
| 5.12.6   | 29        | 2.17%   |
| 5.11.15  | 25        | 1.87%   |
| 5.11.19  | 23        | 1.72%   |
| 5.13.13  | 22        | 1.64%   |
| 5.11.21  | 21        | 1.57%   |
| 5.11.3   | 18        | 1.35%   |
| 5.13.5   | 17        | 1.27%   |
| 5.11.10  | 14        | 1.05%   |
| 5.13.7   | 12        | 0.9%    |
| 5.12.5   | 12        | 0.9%    |
| 5.11.14  | 11        | 0.82%   |
| 5.11.13  | 11        | 0.82%   |
| 5.12.17  | 8         | 0.6%    |
| 5.11.0   | 8         | 0.6%    |
| 5.11.8   | 6         | 0.45%   |
| 5.10.0   | 6         | 0.45%   |
| 5.13.14  | 5         | 0.37%   |
| 5.13.1   | 5         | 0.37%   |
| 5.13.0   | 4         | 0.3%    |
| 5.11.9   | 4         | 0.3%    |
| 5.14.0   | 3         | 0.22%   |
| 5.11.7   | 3         | 0.22%   |
| 5.9.0    | 2         | 0.15%   |
| 5.13.11  | 2         | 0.15%   |
| 5.12.3   | 2         | 0.15%   |
| 5.12.2   | 2         | 0.15%   |
| 5.12.0   | 2         | 0.15%   |
| 5.11.6   | 2         | 0.15%   |
| 5.11.2   | 2         | 0.15%   |
| 5.8.0    | 1         | 0.07%   |
| 5.4.111  | 1         | 0.07%   |
| 5.13.2   | 1         | 0.07%   |
| 5.11.5   | 1         | 0.07%   |
| 5.10.47  | 1         | 0.07%   |
| 5.10.21  | 1         | 0.07%   |
| 5.10.13  | 1         | 0.07%   |
| 5.1.15   | 1         | 0.07%   |
| 4.14.190 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.12    | 450       | 35.66%  |
| 5.11    | 447       | 35.42%  |
| 5.13    | 347       | 27.5%   |
| 5.10    | 9         | 0.71%   |
| 5.14    | 3         | 0.24%   |
| 5.9     | 2         | 0.16%   |
| 5.8     | 1         | 0.08%   |
| 5.4     | 1         | 0.08%   |
| 5.1     | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1154      | 99.23%  |
| aarch64 | 9         | 0.77%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 931       | 79.23%  |
| KDE5          | 56        | 4.77%   |
| KDE           | 46        | 3.91%   |
| Unknown       | 42        | 3.57%   |
| X-Cinnamon    | 25        | 2.13%   |
| Cinnamon      | 23        | 1.96%   |
| XFCE          | 16        | 1.36%   |
| MATE          | 14        | 1.19%   |
| GNOME Classic | 4         | 0.34%   |
| Deepin        | 4         | 0.34%   |
| sway          | 2         | 0.17%   |
| openbox       | 2         | 0.17%   |
| LXDE          | 2         | 0.17%   |
| i3            | 2         | 0.17%   |
| Pantheon      | 1         | 0.09%   |
| NsCDE         | 1         | 0.09%   |
| LXQt          | 1         | 0.09%   |
| dwm           | 1         | 0.09%   |
| Budgie        | 1         | 0.09%   |
| awesome       | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 758       | 63.54%  |
| X11     | 384       | 32.19%  |
| Tty     | 31        | 2.6%    |
| Unknown | 20        | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 664       | 56.18%  |
| GDM     | 415       | 35.11%  |
| SDDM    | 48        | 4.06%   |
| TDM     | 31        | 2.62%   |
| LightDM | 20        | 1.69%   |
| KDM     | 2         | 0.17%   |
| XDM     | 1         | 0.08%   |
| SLiM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 586       | 50.13%  |
| en_GB   | 101       | 8.64%   |
| pt_BR   | 66        | 5.65%   |
| ru_RU   | 58        | 4.96%   |
| de_DE   | 49        | 4.19%   |
| fr_FR   | 44        | 3.76%   |
| en_CA   | 28        | 2.4%    |
| en_AU   | 25        | 2.14%   |
| it_IT   | 20        | 1.71%   |
| en_IN   | 20        | 1.71%   |
| es_ES   | 18        | 1.54%   |
| pl_PL   | 15        | 1.28%   |
| cs_CZ   | 11        | 0.94%   |
| ru_UA   | 7         | 0.6%    |
| es_CL   | 7         | 0.6%    |
| es_MX   | 6         | 0.51%   |
| en_DK   | 6         | 0.51%   |
| pt_PT   | 5         | 0.43%   |
| nl_NL   | 5         | 0.43%   |
| nl_BE   | 5         | 0.43%   |
| hu_HU   | 5         | 0.43%   |
| es_CO   | 5         | 0.43%   |
| C       | 5         | 0.43%   |
| tr_TR   | 4         | 0.34%   |
| ja_JP   | 4         | 0.34%   |
| fi_FI   | 4         | 0.34%   |
| en_SG   | 4         | 0.34%   |
| en_NZ   | 4         | 0.34%   |
| de_AT   | 4         | 0.34%   |
| Unknown | 4         | 0.34%   |
| fr_CH   | 3         | 0.26%   |
| es_EC   | 3         | 0.26%   |
| en_IE   | 3         | 0.26%   |
| ca_ES   | 3         | 0.26%   |
| zh_TW   | 2         | 0.17%   |
| sk_SK   | 2         | 0.17%   |
| ko_KR   | 2         | 0.17%   |
| fr_BE   | 2         | 0.17%   |
| es_DO   | 2         | 0.17%   |
| es_AR   | 2         | 0.17%   |
| en_PH   | 2         | 0.17%   |
| da_DK   | 2         | 0.17%   |
| uk_UA   | 1         | 0.09%   |
| sv_SE   | 1         | 0.09%   |
| sr_ME   | 1         | 0.09%   |
| ro_RO   | 1         | 0.09%   |
| nb_NO   | 1         | 0.09%   |
| ms_MY   | 1         | 0.09%   |
| fr_CA   | 1         | 0.09%   |
| es_UY   | 1         | 0.09%   |
| es_PA   | 1         | 0.09%   |
| es_NI   | 1         | 0.09%   |
| en_ZA   | 1         | 0.09%   |
| en_IL   | 1         | 0.09%   |
| el_GR   | 1         | 0.09%   |
| de_CH   | 1         | 0.09%   |
| ca_AD   | 1         | 0.09%   |
| ar_KW   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 887       | 76.01%  |
| BIOS | 280       | 23.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Btrfs               | 818       | 70.21%  |
| Ext4                | 292       | 25.06%  |
| Xfs                 | 48        | 4.12%   |
| Zfs                 | 2         | 0.17%   |
| Fuse.fuse-overlayfs | 2         | 0.17%   |
| Overlay             | 1         | 0.09%   |
| F2fs                | 1         | 0.09%   |
| Unknown             | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 646       | 54.84%  |
| GPT     | 443       | 37.61%  |
| MBR     | 89        | 7.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1059      | 90.44%  |
| Yes       | 112       | 9.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 950       | 81.2%   |
| Yes       | 220       | 18.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 242       | 20.81%  |
| ASUSTek Computer            | 179       | 15.39%  |
| Dell                        | 149       | 12.81%  |
| Hewlett-Packard             | 146       | 12.55%  |
| Gigabyte Technology         | 85        | 7.31%   |
| MSI                         | 62        | 5.33%   |
| Acer                        | 54        | 4.64%   |
| ASRock                      | 46        | 3.96%   |
| Apple                       | 27        | 2.32%   |
| Intel                       | 14        | 1.2%    |
| Unknown                     | 12        | 1.03%   |
| Fujitsu                     | 10        | 0.86%   |
| HUAWEI                      | 9         | 0.77%   |
| Toshiba                     | 8         | 0.69%   |
| Timi                        | 7         | 0.6%    |
| Samsung Electronics         | 7         | 0.6%    |
| Notebook                    | 7         | 0.6%    |
| Sony                        | 6         | 0.52%   |
| Raspberry Pi Foundation     | 6         | 0.52%   |
| Positivo                    | 6         | 0.52%   |
| Chuwi                       | 5         | 0.43%   |
| Biostar                     | 5         | 0.43%   |
| Alienware                   | 5         | 0.43%   |
| Medion                      | 3         | 0.26%   |
| LG Electronics              | 3         | 0.26%   |
| eMachines                   | 3         | 0.26%   |
| TUXEDO                      | 2         | 0.17%   |
| TrekStor                    | 2         | 0.17%   |
| System76                    | 2         | 0.17%   |
| Supermicro                  | 2         | 0.17%   |
| SLIMBOOK                    | 2         | 0.17%   |
| Pine Microsystems           | 2         | 0.17%   |
| PC Specialist               | 2         | 0.17%   |
| Microsoft                   | 2         | 0.17%   |
| Hampoo                      | 2         | 0.17%   |
| Google                      | 2         | 0.17%   |
| AMI                         | 2         | 0.17%   |
| Wortmann AG                 | 1         | 0.09%   |
| VINGA                       | 1         | 0.09%   |
| Teclast                     | 1         | 0.09%   |
| SYWZ                        | 1         | 0.09%   |
| SUN MICROSYSTEMS            | 1         | 0.09%   |
| Standard                    | 1         | 0.09%   |
| Shenzhen PLOYER electronics | 1         | 0.09%   |
| Razer                       | 1         | 0.09%   |
| Purism                      | 1         | 0.09%   |
| Prestigio                   | 1         | 0.09%   |
| ordissimo                   | 1         | 0.09%   |
| NEC Computers               | 1         | 0.09%   |
| MPMAN                       | 1         | 0.09%   |
| Maibenben                   | 1         | 0.09%   |
| Login Informatica           | 1         | 0.09%   |
| Linx                        | 1         | 0.09%   |
| Irbis                       | 1         | 0.09%   |
| Intel Client Systems        | 1         | 0.09%   |
| Insyde                      | 1         | 0.09%   |
| Huanan                      | 1         | 0.09%   |
| HONOR                       | 1         | 0.09%   |
| HASEE Computer              | 1         | 0.09%   |
| Gateway                     | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 14        | 1.2%    |
| ASUS All Series                            | 8         | 0.69%   |
| MSI MS-7C37                                | 7         | 0.6%    |
| RPi Raspberry Pi 4 Model B                 | 6         | 0.52%   |
| Lenovo IdeaPad Flex 5 14ARE05 81X2         | 6         | 0.52%   |
| Dell XPS 15 9500                           | 5         | 0.43%   |
| Lenovo Yoga 9 14ITL5 82BG                  | 4         | 0.34%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.34%   |
| HP Pavilion dv7                            | 4         | 0.34%   |
| HP Notebook                                | 4         | 0.34%   |
| Dell XPS 15 7590                           | 4         | 0.34%   |
| ASUS TUF GAMING X570-PLUS                  | 4         | 0.34%   |
| ASUS TUF GAMING B550M-PLUS                 | 4         | 0.34%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 4         | 0.34%   |
| Apple MacBookPro11,5                       | 4         | 0.34%   |
| MSI MS-7C84                                | 3         | 0.26%   |
| MSI MS-7C02                                | 3         | 0.26%   |
| HP Pavilion 15                             | 3         | 0.26%   |
| HP Laptop 15s-eq2xxx                       | 3         | 0.26%   |
| HP Laptop 15-da0xxx                        | 3         | 0.26%   |
| HP ENVY x360 Convertible 13-ay0xxx         | 3         | 0.26%   |
| HP EliteBook 840 G6                        | 3         | 0.26%   |
| Gigabyte B450M DS3H                        | 3         | 0.26%   |
| Gigabyte B450 I AORUS PRO WIFI             | 3         | 0.26%   |
| Dell XPS 15 9550                           | 3         | 0.26%   |
| Dell XPS 13 9310                           | 3         | 0.26%   |
| Dell XPS 13 7390                           | 3         | 0.26%   |
| Dell Latitude 7490                         | 3         | 0.26%   |
| Dell Latitude 7400                         | 3         | 0.26%   |
| Dell Latitude 5480                         | 3         | 0.26%   |
| ASUS ZenBook UX431DA_UM431DA               | 3         | 0.26%   |
| ASUS ROG STRIX X570-E GAMING               | 3         | 0.26%   |
| ASUS ROG STRIX B450-F GAMING               | 3         | 0.26%   |
| Apple MacBookPro11,3                       | 3         | 0.26%   |
| Acer Aspire E5-573G                        | 3         | 0.26%   |
| Timi A35S                                  | 2         | 0.17%   |
| System76 Oryx Pro                          | 2         | 0.17%   |
| SLIMBOOK PROX15-AMD                        | 2         | 0.17%   |
| Positivo CHT14B                            | 2         | 0.17%   |
| MSI MS-7C91                                | 2         | 0.17%   |
| MSI MS-7B98                                | 2         | 0.17%   |
| MSI MS-7B85                                | 2         | 0.17%   |
| MSI MS-7A38                                | 2         | 0.17%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 2         | 0.17%   |
| Lenovo Yoga C940-14IIL 81Q9                | 2         | 0.17%   |
| Lenovo Yoga 7 14ITL5 82BH                  | 2         | 0.17%   |
| Lenovo Yoga 2 Pro 20266                    | 2         | 0.17%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW       | 2         | 0.17%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW      | 2         | 0.17%   |
| Lenovo ThinkPad E595 20NFCTO1WW            | 2         | 0.17%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.17%   |
| Lenovo IdeaPad Yoga 13 20175               | 2         | 0.17%   |
| Lenovo IdeaPad S145-15IWL 81S9             | 2         | 0.17%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 2         | 0.17%   |
| Lenovo IdeaPad 5 15ALC05 82LN              | 2         | 0.17%   |
| Lenovo IdeaPad 330S-15IKB 81F5             | 2         | 0.17%   |
| Intel H61                                  | 2         | 0.17%   |
| HP ZBook 17 G5                             | 2         | 0.17%   |
| HP ZBook 15 G3                             | 2         | 0.17%   |
| HP ProBook x360 435 G7                     | 2         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 130       | 11.18%  |
| Lenovo IdeaPad           | 46        | 3.96%   |
| ASUS ROG                 | 43        | 3.7%    |
| Dell Inspiron            | 41        | 3.53%   |
| Dell XPS                 | 37        | 3.18%   |
| Acer Aspire              | 35        | 3.01%   |
| Dell Latitude            | 33        | 2.84%   |
| Lenovo Yoga              | 30        | 2.58%   |
| HP Pavilion              | 26        | 2.24%   |
| HP EliteBook             | 22        | 1.89%   |
| ASUS TUF                 | 19        | 1.63%   |
| HP ProBook               | 18        | 1.55%   |
| ASUS PRIME               | 18        | 1.55%   |
| HP Laptop                | 16        | 1.38%   |
| Dell OptiPlex            | 14        | 1.2%    |
| Unknown                  | 14        | 1.2%    |
| ASUS VivoBook            | 13        | 1.12%   |
| HP ENVY                  | 12        | 1.03%   |
| Apple MacBookPro11       | 10        | 0.86%   |
| Dell Precision           | 9         | 0.77%   |
| Gigabyte B450            | 8         | 0.69%   |
| ASUS All                 | 8         | 0.69%   |
| MSI MS-7C37              | 7         | 0.6%    |
| Lenovo ThinkBook         | 7         | 0.6%    |
| Lenovo Legion            | 7         | 0.6%    |
| HP ZBook                 | 7         | 0.6%    |
| ASUS ZenBook             | 7         | 0.6%    |
| ASUS ASUS                | 7         | 0.6%    |
| Acer Nitro               | 7         | 0.6%    |
| Toshiba Satellite        | 6         | 0.52%   |
| RPi Raspberry            | 6         | 0.52%   |
| Lenovo ThinkCentre       | 6         | 0.52%   |
| HP Compaq                | 6         | 0.52%   |
| Gigabyte X570            | 6         | 0.52%   |
| Fujitsu LIFEBOOK         | 6         | 0.52%   |
| Dell Vostro              | 6         | 0.52%   |
| Acer Swift               | 6         | 0.52%   |
| HP EliteDesk             | 5         | 0.43%   |
| Gigabyte B450M           | 5         | 0.43%   |
| HP Notebook              | 4         | 0.34%   |
| Fujitsu ESPRIMO          | 4         | 0.34%   |
| Dell G5                  | 4         | 0.34%   |
| ASRock B450              | 4         | 0.34%   |
| MSI MS-7C84              | 3         | 0.26%   |
| MSI MS-7C02              | 3         | 0.26%   |
| HP Spectre               | 3         | 0.26%   |
| Gigabyte Z390            | 3         | 0.26%   |
| ASUS P8H61-M             | 3         | 0.26%   |
| ASRock X570              | 3         | 0.26%   |
| ASRock X399              | 3         | 0.26%   |
| ASRock B550              | 3         | 0.26%   |
| Toshiba TECRA            | 2         | 0.17%   |
| Timi RedmiBook           | 2         | 0.17%   |
| Timi A35S                | 2         | 0.17%   |
| System76 Oryx            | 2         | 0.17%   |
| SLIMBOOK PROX15-AMD      | 2         | 0.17%   |
| Positivo CHT14B          | 2         | 0.17%   |
| Pine Microsystems Pine64 | 2         | 0.17%   |
| MSI MS-7C91              | 2         | 0.17%   |
| MSI MS-7B98              | 2         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 274       | 23.56%  |
| 2021    | 253       | 21.75%  |
| 2019    | 167       | 14.36%  |
| 2018    | 107       | 9.2%    |
| 2016    | 50        | 4.3%    |
| 2015    | 50        | 4.3%    |
| 2017    | 44        | 3.78%   |
| 2012    | 42        | 3.61%   |
| 2013    | 41        | 3.53%   |
| 2014    | 39        | 3.35%   |
| 2011    | 32        | 2.75%   |
| 2010    | 31        | 2.67%   |
| 2009    | 18        | 1.55%   |
| 2008    | 8         | 0.69%   |
| 2006    | 3         | 0.26%   |
| Unknown | 2         | 0.17%   |
| 2007    | 1         | 0.09%   |
| 2005    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 675       | 58.04%  |
| Desktop        | 381       | 32.76%  |
| Convertible    | 61        | 5.25%   |
| Tablet         | 12        | 1.03%   |
| All in one     | 12        | 1.03%   |
| Mini pc        | 11        | 0.95%   |
| System on chip | 7         | 0.6%    |
| Server         | 4         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1013      | 86.07%  |
| Enabled  | 164       | 13.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1158      | 99.57%  |
| Yes  | 5         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 296       | 25.21%  |
| 4.01-8.0    | 288       | 24.53%  |
| 8.01-16.0   | 216       | 18.4%   |
| 32.01-64.0  | 177       | 15.08%  |
| 3.01-4.0    | 97        | 8.26%   |
| 64.01-256.0 | 41        | 3.49%   |
| 24.01-32.0  | 28        | 2.39%   |
| 1.01-2.0    | 20        | 1.7%    |
| 0.51-1.0    | 7         | 0.6%    |
| 2.01-3.0    | 4         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 335       | 26.63%  |
| 4.01-8.0   | 327       | 25.99%  |
| 3.01-4.0   | 254       | 20.19%  |
| 1.01-2.0   | 203       | 16.14%  |
| 8.01-16.0  | 85        | 6.76%   |
| 0.51-1.0   | 33        | 2.62%   |
| 16.01-24.0 | 11        | 0.87%   |
| 24.01-32.0 | 4         | 0.32%   |
| 0.01-0.5   | 4         | 0.32%   |
| 32.01-64.0 | 2         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 666       | 56.58%  |
| 2      | 291       | 24.72%  |
| 3      | 122       | 10.37%  |
| 4      | 46        | 3.91%   |
| 5      | 24        | 2.04%   |
| 6      | 9         | 0.76%   |
| 8      | 7         | 0.59%   |
| 0      | 6         | 0.51%   |
| 7      | 3         | 0.25%   |
| 12     | 2         | 0.17%   |
| 9      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 889       | 76.05%  |
| Yes       | 280       | 23.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 907       | 77.59%  |
| No        | 262       | 22.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 934       | 79.9%   |
| No        | 235       | 20.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 825       | 70.51%  |
| No        | 345       | 29.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 212       | 18.17%  |
| Brazil       | 90        | 7.71%   |
| Germany      | 85        | 7.28%   |
| Russia       | 60        | 5.14%   |
| France       | 50        | 4.28%   |
| India        | 46        | 3.94%   |
| Netherlands  | 44        | 3.77%   |
| UK           | 42        | 3.6%    |
| Canada       | 42        | 3.6%    |
| Spain        | 32        | 2.74%   |
| Italy        | 31        | 2.66%   |
| Australia    | 28        | 2.4%    |
| Poland       | 25        | 2.14%   |
| Czechia      | 25        | 2.14%   |
| Ukraine      | 21        | 1.8%    |
| Switzerland  | 17        | 1.46%   |
| Sweden       | 17        | 1.46%   |
| Belgium      | 16        | 1.37%   |
| Turkey       | 15        | 1.29%   |
| Chile        | 14        | 1.2%    |
| Portugal     | 13        | 1.11%   |
| Slovakia     | 11        | 0.94%   |
| Finland      | 11        | 0.94%   |
| Mexico       | 10        | 0.86%   |
| Denmark      | 10        | 0.86%   |
| Argentina    | 10        | 0.86%   |
| Romania      | 9         | 0.77%   |
| Norway       | 9         | 0.77%   |
| Colombia     | 9         | 0.77%   |
| Belarus      | 9         | 0.77%   |
| Austria      | 9         | 0.77%   |
| Hungary      | 7         | 0.6%    |
| New Zealand  | 6         | 0.51%   |
| Estonia      | 6         | 0.51%   |
| China        | 6         | 0.51%   |
| Serbia       | 5         | 0.43%   |
| Malaysia     | 5         | 0.43%   |
| Japan        | 5         | 0.43%   |
| Israel       | 5         | 0.43%   |
| Iran         | 5         | 0.43%   |
| Indonesia    | 5         | 0.43%   |
| Greece       | 5         | 0.43%   |
| South Korea  | 4         | 0.34%   |
| South Africa | 4         | 0.34%   |
| Slovenia     | 4         | 0.34%   |
| Bulgaria     | 4         | 0.34%   |
| Taiwan       | 3         | 0.26%   |
| Singapore    | 3         | 0.26%   |
| Philippines  | 3         | 0.26%   |
| Moldova      | 3         | 0.26%   |
| Egypt        | 3         | 0.26%   |
| Ecuador      | 3         | 0.26%   |
| Vietnam      | 2         | 0.17%   |
| Uruguay      | 2         | 0.17%   |
| Sri Lanka    | 2         | 0.17%   |
| Montenegro   | 2         | 0.17%   |
| Lithuania    | 2         | 0.17%   |
| Latvia       | 2         | 0.17%   |
| Kyrgyzstan   | 2         | 0.17%   |
| Kenya        | 2         | 0.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 17        | 1.42%   |
| Moscow         | 16        | 1.33%   |
| Berlin         | 12        | 1%      |
| Prague         | 10        | 0.83%   |
| Madrid         | 10        | 0.83%   |
| The Hague      | 9         | 0.75%   |
| St Petersburg  | 9         | 0.75%   |
| Kyiv           | 8         | 0.67%   |
| Denver         | 8         | 0.67%   |
| Amsterdam      | 8         | 0.67%   |
| Santiago       | 7         | 0.58%   |
| Istanbul       | 7         | 0.58%   |
| Minsk          | 6         | 0.5%    |
| Milan          | 6         | 0.5%    |
| London         | 6         | 0.5%    |
| Bratislava     | 6         | 0.5%    |
| Bengaluru      | 6         | 0.5%    |
| Belo Horizonte | 6         | 0.5%    |
| Yekaterinburg  | 5         | 0.42%   |
| Toronto        | 5         | 0.42%   |
| Tallinn        | 5         | 0.42%   |
| São Paulo     | 5         | 0.42%   |
| Lodz           | 5         | 0.42%   |
| Kharkiv        | 5         | 0.42%   |
| Fortaleza      | 5         | 0.42%   |
| Buenos Aires   | 5         | 0.42%   |
| Budapest       | 5         | 0.42%   |
| Brussels       | 5         | 0.42%   |
| Zurich         | 4         | 0.33%   |
| Wroclaw        | 4         | 0.33%   |
| Vienna         | 4         | 0.33%   |
| Tel Aviv       | 4         | 0.33%   |
| Porto Alegre   | 4         | 0.33%   |
| Montreal       | 4         | 0.33%   |
| Melbourne      | 4         | 0.33%   |
| Hamburg        | 4         | 0.33%   |
| Feeding Hills  | 4         | 0.33%   |
| Dallas         | 4         | 0.33%   |
| Auckland       | 4         | 0.33%   |
| Winnipeg       | 3         | 0.25%   |
| Vancouver      | 3         | 0.25%   |
| Ufa            | 3         | 0.25%   |
| Tehran         | 3         | 0.25%   |
| Sofia          | 3         | 0.25%   |
| Singapore      | 3         | 0.25%   |
| Sharon         | 3         | 0.25%   |
| Rostov-on-Don  | 3         | 0.25%   |
| Riverside      | 3         | 0.25%   |
| Rio de Janeiro | 3         | 0.25%   |
| Raleigh        | 3         | 0.25%   |
| Pymble         | 3         | 0.25%   |
| Pune           | 3         | 0.25%   |
| Portland       | 3         | 0.25%   |
| Paris          | 3         | 0.25%   |
| Oslo           | 3         | 0.25%   |
| Munich         | 3         | 0.25%   |
| Lyon           | 3         | 0.25%   |
| Lisbon         | 3         | 0.25%   |
| Jambes         | 3         | 0.25%   |
| Helsinki       | 3         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 379       | 597    | 21.49%  |
| WDC                       | 237       | 344    | 13.44%  |
| Seagate                   | 196       | 296    | 11.11%  |
| Toshiba                   | 110       | 139    | 6.24%   |
| SanDisk                   | 92        | 106    | 5.22%   |
| Kingston                  | 92        | 112    | 5.22%   |
| Unknown                   | 74        | 98     | 4.2%    |
| Crucial                   | 71        | 101    | 4.02%   |
| SK Hynix                  | 64        | 78     | 3.63%   |
| Intel                     | 63        | 87     | 3.57%   |
| Hitachi                   | 37        | 49     | 2.1%    |
| Micron Technology         | 30        | 39     | 1.7%    |
| A-DATA Technology         | 26        | 30     | 1.47%   |
| Phison                    | 20        | 26     | 1.13%   |
| HGST                      | 19        | 31     | 1.08%   |
| KIOXIA                    | 18        | 26     | 1.02%   |
| Apple                     | 18        | 20     | 1.02%   |
| Corsair                   | 13        | 17     | 0.74%   |
| Silicon Motion            | 12        | 17     | 0.68%   |
| SPCC                      | 11        | 14     | 0.62%   |
| PNY                       | 11        | 14     | 0.62%   |
| XPG                       | 10        | 12     | 0.57%   |
| Union Memory              | 10        | 13     | 0.57%   |
| Micron/Crucial Technology | 9         | 10     | 0.51%   |
| Transcend                 | 8         | 8      | 0.45%   |
| OCZ                       | 8         | 13     | 0.45%   |
| Patriot                   | 7         | 8      | 0.4%    |
| LITEONIT                  | 7         | 7      | 0.4%    |
| LITEON                    | 6         | 6      | 0.34%   |
| Realtek Semiconductor     | 5         | 6      | 0.28%   |
| Maxtor                    | 5         | 6      | 0.28%   |
| Team                      | 4         | 5      | 0.23%   |
| JMicron                   | 4         | 4      | 0.23%   |
| Intenso                   | 4         | 4      | 0.23%   |
| Gigabyte Technology       | 4         | 5      | 0.23%   |
| Union Memory (Shenzhen)   | 3         | 6      | 0.17%   |
| Solid State Storage       | 3         | 3      | 0.17%   |
| SABRENT                   | 3         | 3      | 0.17%   |
| KingSpec                  | 3         | 5      | 0.17%   |
| KingFast                  | 3         | 4      | 0.17%   |
| GOODRAM                   | 3         | 3      | 0.17%   |
| China                     | 3         | 4      | 0.17%   |
| ASMT                      | 3         | 3      | 0.17%   |
| Apacer                    | 3         | 4      | 0.17%   |
| Phison Electronics        | 2         | 2      | 0.11%   |
| Mushkin                   | 2         | 5      | 0.11%   |
| Lite-On                   | 2         | 2      | 0.11%   |
| Lexar                     | 2         | 2      | 0.11%   |
| Lenovo                    | 2         | 2      | 0.11%   |
| Hewlett-Packard           | 2         | 2      | 0.11%   |
| DOGFISH                   | 2         | 2      | 0.11%   |
| BIWIN                     | 2         | 2      | 0.11%   |
| XrayDisk                  | 1         | 1      | 0.06%   |
| WDC WDS2                  | 1         | 1      | 0.06%   |
| W800S                     | 1         | 1      | 0.06%   |
| USB 3.0                   | 1         | 1      | 0.06%   |
| UNIC2                     | 1         | 1      | 0.06%   |
| Ugreen                    | 1         | 1      | 0.06%   |
| TCSUNBOW                  | 1         | 1      | 0.06%   |
| Tanbassh                  | 1         | 1      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB       | 35        | 1.74%   |
| Samsung SSD 860 EVO 500GB          | 28        | 1.4%    |
| Samsung NVMe SSD Drive 1TB         | 25        | 1.25%   |
| Samsung NVMe SSD Drive 500GB       | 23        | 1.15%   |
| Samsung SSD 860 EVO 1TB            | 22        | 1.1%    |
| Samsung NVMe SSD Drive 256GB       | 19        | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB     | 16        | 0.8%    |
| Samsung SSD 850 EVO 500GB          | 16        | 0.8%    |
| Samsung SSD 850 EVO 250GB          | 15        | 0.75%   |
| Kingston SA400S37240G 240GB SSD    | 15        | 0.75%   |
| Kingston SA400S37480G 480GB SSD    | 14        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB     | 13        | 0.65%   |
| Samsung NVMe SSD Drive 250GB       | 12        | 0.6%    |
| Kingston SA400S37120G 120GB SSD    | 12        | 0.6%    |
| Intel NVMe SSD Drive 512GB         | 12        | 0.6%    |
| Crucial CT500MX500SSD1 500GB       | 12        | 0.6%    |
| Unknown SD/MMC/MS PRO 64GB         | 11        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 0.55%   |
| Sandisk NVMe SSD Drive 512GB       | 11        | 0.55%   |
| Sandisk NVMe SSD Drive 500GB       | 11        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB       | 11        | 0.55%   |
| Samsung SSD 860 EVO 250GB          | 11        | 0.55%   |
| Toshiba NVMe SSD Drive 512GB       | 10        | 0.5%    |
| SK Hynix NVMe SSD Drive 512GB      | 10        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB    | 10        | 0.5%    |
| Unknown MMC Card  32GB             | 9         | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB     | 9         | 0.45%   |
| Samsung SSD 970 EVO 500GB          | 9         | 0.45%   |
| Samsung SSD 860 QVO 1TB            | 9         | 0.45%   |
| Samsung NVMe SSD Drive 1024GB      | 9         | 0.45%   |
| WDC WD20EZRZ-00Z5HB0  2TB          | 8         | 0.4%    |
| Toshiba DT01ACA100 1TB             | 8         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB     | 8         | 0.4%    |
| Sandisk NVMe SSD Drive 256GB       | 8         | 0.4%    |
| Micron/Crucial NVMe SSD Drive 1TB  | 8         | 0.4%    |
| Crucial CT1000MX500SSD1 1TB        | 8         | 0.4%    |
| Toshiba NVMe SSD Drive 256GB       | 7         | 0.35%   |
| Toshiba MQ01ABD100 1TB             | 7         | 0.35%   |
| SK Hynix NVMe SSD Drive 256GB      | 7         | 0.35%   |
| Seagate ST3500418AS 500GB          | 7         | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB     | 7         | 0.35%   |
| Samsung SSD 970 EVO Plus 2TB       | 7         | 0.35%   |
| Samsung SSD 840 EVO 250GB          | 7         | 0.35%   |
| Samsung NVMe SSD Drive 2TB         | 7         | 0.35%   |
| Crucial CT240BX500SSD1 240GB       | 7         | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 6         | 0.3%    |
| WDC WDS100T2B0C-00PXH0 1TB         | 6         | 0.3%    |
| Unknown MMC Card  128GB            | 6         | 0.3%    |
| Toshiba MQ04ABF100 1TB             | 6         | 0.3%    |
| Seagate ST1000DM003-1ER162 1TB     | 6         | 0.3%    |
| Seagate Expansion 1TB              | 6         | 0.3%    |
| Samsung SSD 980 PRO 1TB            | 6         | 0.3%    |
| PNY CS900 240GB SSD                | 6         | 0.3%    |
| Kingston SV300S37A120G 120GB SSD   | 6         | 0.3%    |
| HGST HTS541010A9E680 1TB           | 6         | 0.3%    |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 5         | 0.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 5         | 0.25%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 5         | 0.25%   |
| WDC WD10SPZX-21Z10T0 1TB           | 5         | 0.25%   |
| WDC WD10EZEX-08WN4A0 1TB           | 5         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 187       | 281    | 37.63%  |
| WDC                 | 163       | 246    | 32.8%   |
| Toshiba             | 59        | 80     | 11.87%  |
| Hitachi             | 37        | 49     | 7.44%   |
| HGST                | 19        | 31     | 3.82%   |
| Samsung Electronics | 17        | 27     | 3.42%   |
| Apple               | 5         | 5      | 1.01%   |
| Maxtor              | 3         | 3      | 0.6%    |
| Unknown             | 1         | 1      | 0.2%    |
| Synology            | 1         | 1      | 0.2%    |
| PHD 3.0             | 1         | 1      | 0.2%    |
| MaxDigital          | 1         | 1      | 0.2%    |
| Inateck             | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Fujitsu             | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 182       | 269    | 28.84%  |
| Kingston            | 68        | 83     | 10.78%  |
| Crucial             | 63        | 91     | 9.98%   |
| SanDisk             | 50        | 60     | 7.92%   |
| WDC                 | 40        | 47     | 6.34%   |
| Intel               | 23        | 31     | 3.65%   |
| A-DATA Technology   | 22        | 25     | 3.49%   |
| Toshiba             | 18        | 19     | 2.85%   |
| Micron Technology   | 16        | 18     | 2.54%   |
| SK Hynix            | 12        | 13     | 1.9%    |
| PNY                 | 11        | 13     | 1.74%   |
| Apple               | 11        | 12     | 1.74%   |
| SPCC                | 8         | 11     | 1.27%   |
| OCZ                 | 8         | 13     | 1.27%   |
| Transcend           | 7         | 7      | 1.11%   |
| LITEONIT            | 7         | 7      | 1.11%   |
| Patriot             | 6         | 6      | 0.95%   |
| LITEON              | 6         | 6      | 0.95%   |
| Unknown             | 5         | 5      | 0.79%   |
| Corsair             | 5         | 6      | 0.79%   |
| Team                | 4         | 5      | 0.63%   |
| Intenso             | 4         | 4      | 0.63%   |
| SABRENT             | 3         | 3      | 0.48%   |
| KingSpec            | 3         | 5      | 0.48%   |
| GOODRAM             | 3         | 3      | 0.48%   |
| China               | 3         | 4      | 0.48%   |
| ASMT                | 3         | 3      | 0.48%   |
| Apacer              | 3         | 4      | 0.48%   |
| Seagate             | 2         | 2      | 0.32%   |
| Mushkin             | 2         | 5      | 0.32%   |
| Maxtor              | 2         | 3      | 0.32%   |
| Lexar               | 2         | 2      | 0.32%   |
| JMicron             | 2         | 2      | 0.32%   |
| Gigabyte Technology | 2         | 3      | 0.32%   |
| DOGFISH             | 2         | 2      | 0.32%   |
| WDC WDS2            | 1         | 1      | 0.16%   |
| W800S               | 1         | 1      | 0.16%   |
| Union Memory        | 1         | 1      | 0.16%   |
| UNIC2               | 1         | 1      | 0.16%   |
| TCSUNBOW            | 1         | 1      | 0.16%   |
| Smartbuy            | 1         | 1      | 0.16%   |
| SMART               | 1         | 1      | 0.16%   |
| PLEXTOR             | 1         | 2      | 0.16%   |
| OWC                 | 1         | 1      | 0.16%   |
| OCZ-ARC1            | 1         | 1      | 0.16%   |
| NGFF                | 1         | 2      | 0.16%   |
| Netac               | 1         | 1      | 0.16%   |
| MG                  | 1         | 1      | 0.16%   |
| Leven               | 1         | 1      | 0.16%   |
| KLEVV               | 1         | 1      | 0.16%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.16%   |
| Indilinx            | 1         | 1      | 0.16%   |
| Hoodisk             | 1         | 2      | 0.16%   |
| GALAX               | 1         | 1      | 0.16%   |
| EMTEC               | 1         | 1      | 0.16%   |
| DREVO               | 1         | 1      | 0.16%   |
| CT1000P1            | 1         | 2      | 0.16%   |
| BIWIN               | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 552       | 819    | 34.44%  |
| NVMe    | 549       | 776    | 34.25%  |
| HDD     | 410       | 729    | 25.58%  |
| MMC     | 61        | 82     | 3.81%   |
| Unknown | 31        | 37     | 1.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 762       | 1506   | 53.06%  |
| NVMe | 549       | 775    | 38.23%  |
| SAS  | 64        | 80     | 4.46%   |
| MMC  | 61        | 82     | 4.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 541       | 822    | 52.78%  |
| 0.51-1.0   | 320       | 468    | 31.22%  |
| 1.01-2.0   | 93        | 132    | 9.07%   |
| 3.01-4.0   | 27        | 44     | 2.63%   |
| 4.01-10.0  | 24        | 52     | 2.34%   |
| 2.01-3.0   | 15        | 19     | 1.46%   |
| 10.01-20.0 | 4         | 10     | 0.39%   |
| 0          | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 250       | 20.94%  |
| 251-500        | 219       | 18.34%  |
| 101-250        | 164       | 13.74%  |
| 1001-2000      | 145       | 12.14%  |
| 1-20           | 129       | 10.8%   |
| Unknown        | 98        | 8.21%   |
| More than 3000 | 73        | 6.11%   |
| 51-100         | 47        | 3.94%   |
| 2001-3000      | 41        | 3.43%   |
| 21-50          | 28        | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 340       | 27.85%  |
| 101-250        | 184       | 15.07%  |
| 21-50          | 182       | 14.91%  |
| 51-100         | 129       | 10.57%  |
| 251-500        | 119       | 9.75%   |
| 501-1000       | 99        | 8.11%   |
| Unknown        | 98        | 8.03%   |
| 1001-2000      | 42        | 3.44%   |
| More than 3000 | 18        | 1.47%   |
| 2001-3000      | 10        | 0.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB         | 3         | 15     | 4.76%   |
| Intel SSDSC2CT120A3 120GB               | 3         | 5      | 4.76%   |
| Toshiba DT01ACA200 2TB                  | 2         | 4      | 3.17%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2      | 3.17%   |
| Crucial CT1050MX300SSD1 1050GB          | 2         | 3      | 3.17%   |
| WDC WD60EFAX-68SHWN0 6TB                | 1         | 1      | 1.59%   |
| WDC WD40PURZ-85AKKY0 4TB                | 1         | 1      | 1.59%   |
| WDC WD3200BPVT-75ZEST0 320GB            | 1         | 1      | 1.59%   |
| WDC WD3200BPVT-24JJ5T0 320GB            | 1         | 1      | 1.59%   |
| WDC WD30EZRX-00AZ6B0 3TB                | 1         | 1      | 1.59%   |
| WDC WD15EARS-00Z5B1 1TB                 | 1         | 1      | 1.59%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 1.59%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 1      | 1.59%   |
| WDC WD1003FBYX-01Y7B1 1TB               | 1         | 1      | 1.59%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB | 1         | 1      | 1.59%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.59%   |
| Toshiba MQ01ABD050V 500GB               | 1         | 1      | 1.59%   |
| SPCC Solid State Disk 256GB             | 1         | 1      | 1.59%   |
| SK Hynix PC401 NVMe 1TB                 | 1         | 1      | 1.59%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 1         | 1      | 1.59%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1      | 1.59%   |
| Seagate ST4000DM000-1F2168 4TB          | 1         | 1      | 1.59%   |
| Seagate ST3500630AS 500GB               | 1         | 1      | 1.59%   |
| Seagate ST31000340NS 1TB                | 1         | 1      | 1.59%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 2      | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1      | 1.59%   |
| Seagate ST1000DX001-1CM162 1TB          | 1         | 1      | 1.59%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1      | 1.59%   |
| SanDisk SSD U100 64GB                   | 1         | 1      | 1.59%   |
| SanDisk SSD PLUS 480GB                  | 1         | 1      | 1.59%   |
| SanDisk SDSSDX240GG25 240GB             | 1         | 1      | 1.59%   |
| Samsung Electronics SSD 860 EVO 250GB   | 1         | 1      | 1.59%   |
| Samsung Electronics SP2514N 250GB       | 1         | 1      | 1.59%   |
| Samsung Electronics SP2004C 199GB       | 1         | 1      | 1.59%   |
| Samsung Electronics HM160HI 160GB       | 1         | 2      | 1.59%   |
| Samsung Electronics HD501LJ 500GB       | 1         | 6      | 1.59%   |
| LITEONIT LCS-128M6S-HP 128GB SSD        | 1         | 1      | 1.59%   |
| LITEON LGH-512V2G-11 M.2 2280 512GB SSD | 1         | 1      | 1.59%   |
| Intel SSDSCKJF180A5L 180GB              | 1         | 1      | 1.59%   |
| Intel SSDSC2KF480H6L 480GB              | 1         | 1      | 1.59%   |
| Intel SSDSC2BW240A4 240GB               | 1         | 1      | 1.59%   |
| Intel SSDSA2M080G2GC 80GB               | 1         | 1      | 1.59%   |
| Intel SSDPEKKW128G7 128GB               | 1         | 1      | 1.59%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 1      | 1.59%   |
| Hitachi HTS721010G9SA00 100GB           | 1         | 1      | 1.59%   |
| Hitachi HTS545032A7E380 320GB           | 1         | 1      | 1.59%   |
| Hitachi HTS542560K9SA00 64GB            | 1         | 1      | 1.59%   |
| Hitachi HDS721050CLA362 500GB           | 1         | 1      | 1.59%   |
| HGST HTS725050A7E630 500GB              | 1         | 1      | 1.59%   |
| Fujitsu MHY2120BH 120GB                 | 1         | 1      | 1.59%   |
| Crucial CT275MX300SSD1 275GB            | 1         | 1      | 1.59%   |
| Crucial CT128MX100SSD1 128GB            | 1         | 1      | 1.59%   |
| Crucial CT1000P1SSD8 1TB                | 1         | 1      | 1.59%   |
| A-DATA Technology SX6000NP 128GB        | 1         | 1      | 1.59%   |
| A-DATA Technology SP900 256GB SSD       | 1         | 1      | 1.59%   |
| A-DATA Technology SP900 128GB SSD       | 1         | 2      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 26     | 20.63%  |
| WDC                 | 9         | 9      | 14.29%  |
| Intel               | 8         | 10     | 12.7%   |
| Samsung Electronics | 5         | 11     | 7.94%   |
| Hitachi             | 5         | 5      | 7.94%   |
| Crucial             | 5         | 6      | 7.94%   |
| Toshiba             | 4         | 6      | 6.35%   |
| SanDisk             | 3         | 3      | 4.76%   |
| A-DATA Technology   | 3         | 4      | 4.76%   |
| SK Hynix            | 2         | 2      | 3.17%   |
| Union Memory        | 1         | 1      | 1.59%   |
| SPCC                | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| LITEON              | 1         | 1      | 1.59%   |
| HGST                | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 26     | 35.14%  |
| WDC                 | 9         | 9      | 24.32%  |
| Hitachi             | 5         | 5      | 13.51%  |
| Toshiba             | 4         | 6      | 10.81%  |
| Samsung Electronics | 4         | 10     | 10.81%  |
| HGST                | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 58     | 58.06%  |
| SSD  | 21        | 25     | 33.87%  |
| NVMe | 5         | 5      | 8.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB          | 1         | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 4      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 712       | 1429   | 55.8%   |
| Works    | 502       | 921    | 39.34%  |
| Malfunc  | 60        | 88     | 4.7%    |
| Failed   | 2         | 5      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 667       | 42.62%  |
| AMD                            | 262       | 16.74%  |
| Samsung Electronics            | 228       | 14.57%  |
| Sandisk                        | 85        | 5.43%   |
| SK Hynix                       | 47        | 3%      |
| Toshiba America Info Systems   | 35        | 2.24%   |
| Phison Electronics             | 33        | 2.11%   |
| ASMedia Technology             | 29        | 1.85%   |
| Kingston Technology Company    | 24        | 1.53%   |
| KIOXIA                         | 18        | 1.15%   |
| Micron/Crucial Technology      | 17        | 1.09%   |
| Micron Technology              | 15        | 0.96%   |
| Silicon Motion                 | 14        | 0.89%   |
| ADATA Technology               | 13        | 0.83%   |
| Union Memory (Shenzhen)        | 12        | 0.77%   |
| Nvidia                         | 11        | 0.7%    |
| Marvell Technology Group       | 7         | 0.45%   |
| JMicron Technology             | 7         | 0.45%   |
| Realtek Semiconductor          | 6         | 0.38%   |
| Broadcom / LSI                 | 6         | 0.38%   |
| Seagate Technology             | 5         | 0.32%   |
| Solid State Storage Technology | 3         | 0.19%   |
| LSI Logic / Symbios Logic      | 3         | 0.19%   |
| VIA Technologies               | 2         | 0.13%   |
| ULi Electronics                | 2         | 0.13%   |
| Silicon Image                  | 2         | 0.13%   |
| Lite-On Technology             | 2         | 0.13%   |
| Lenovo                         | 2         | 0.13%   |
| Hewlett-Packard                | 2         | 0.13%   |
| Apple                          | 2         | 0.13%   |
| Adaptec                        | 2         | 0.13%   |
| Shenzhen Longsys Electronics   | 1         | 0.06%   |
| Lite-On IT Corp. / Plextor     | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 203       | 11.75%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 144       | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 91        | 5.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 44        | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 43        | 2.49%   |
| AMD 400 Series Chipset SATA Controller                                         | 43        | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 35        | 2.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 33        | 1.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 32        | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 29        | 1.68%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 1.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 27        | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 1.5%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 26        | 1.5%    |
| Samsung NVMe Controller                                                        | 25        | 1.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 23        | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 22        | 1.27%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 21        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 20        | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 1.04%   |
| KIOXIA Non-Volatile memory controller                                          | 18        | 1.04%   |
| Intel SATA Controller [RAID mode]                                              | 18        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 1.04%   |
| Phison E12 NVMe Controller                                                     | 17        | 0.98%   |
| Intel SSD 660P Series                                                          | 17        | 0.98%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 16        | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 15        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 15        | 0.87%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 14        | 0.81%   |
| Micron Non-Volatile memory controller                                          | 14        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 14        | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                               | 13        | 0.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 13        | 0.75%   |
| SK Hynix NVMe SSD Controller                                                   | 12        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 12        | 0.69%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 11        | 0.64%   |
| SK Hynix Non-Volatile memory controller                                        | 11        | 0.64%   |
| SK Hynix BC511                                                                 | 11        | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 11        | 0.64%   |
| Kingston Company A2000 NVMe SSD                                                | 11        | 0.64%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 11        | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 11        | 0.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11        | 0.64%   |
| AMD 300 Series Chipset SATA Controller                                         | 11        | 0.64%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 10        | 0.58%   |
| Sandisk Non-Volatile memory controller                                         | 10        | 0.58%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 10        | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 0.58%   |
| AMD FCH SATA Controller D                                                      | 10        | 0.58%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 9         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 9         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 9         | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 8         | 0.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 822       | 53.48%  |
| NVMe | 546       | 35.52%  |
| RAID | 92        | 5.99%   |
| IDE  | 70        | 4.55%   |
| SCSI | 5         | 0.33%   |
| SAS  | 2         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 824       | 70.85%  |
| AMD      | 330       | 28.37%  |
| ARM      | 8         | 0.69%   |
| QUALCOMM | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 2.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 1.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.37%   |
| AMD Ryzen 5 3600 6-Core Processor             | 15        | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 15        | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 14        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.12%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 13        | 1.12%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 12        | 1.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.95%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.95%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 11        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.86%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 0.86%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 10        | 0.86%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 10        | 0.86%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 0.77%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 0.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 9         | 0.77%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.69%   |
| ARM Processor                                 | 8         | 0.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 7         | 0.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.6%    |
| Intel Atom CPU Z3735G @ 1.33GHz               | 7         | 0.6%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 7         | 0.6%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 7         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 0.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 6         | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.52%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 6         | 0.52%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 6         | 0.52%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 6         | 0.52%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 6         | 0.52%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 6         | 0.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.43%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 5         | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.43%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.43%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 5         | 0.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.43%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.43%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.43%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 292       | 25.11%  |
| Intel Core i5           | 261       | 22.44%  |
| AMD Ryzen 5             | 115       | 9.89%   |
| AMD Ryzen 7             | 75        | 6.45%   |
| Other                   | 66        | 5.67%   |
| Intel Core i3           | 64        | 5.5%    |
| AMD Ryzen 9             | 38        | 3.27%   |
| Intel Atom              | 27        | 2.32%   |
| Intel Xeon              | 25        | 2.15%   |
| Intel Celeron           | 21        | 1.81%   |
| Intel Core i9           | 18        | 1.55%   |
| Intel Core 2 Duo        | 16        | 1.38%   |
| AMD Ryzen 3             | 15        | 1.29%   |
| Intel Pentium           | 14        | 1.2%    |
| AMD Ryzen 7 PRO         | 12        | 1.03%   |
| AMD FX                  | 9         | 0.77%   |
| AMD A10                 | 9         | 0.77%   |
| Intel Pentium Silver    | 7         | 0.6%    |
| AMD Ryzen 5 PRO         | 7         | 0.6%    |
| Intel Pentium Dual-Core | 5         | 0.43%   |
| Intel Core 2 Quad       | 5         | 0.43%   |
| AMD Ryzen Threadripper  | 5         | 0.43%   |
| AMD A6                  | 5         | 0.43%   |
| AMD A4                  | 5         | 0.43%   |
| AMD Athlon 64 X2        | 4         | 0.34%   |
| Intel Pentium Dual      | 3         | 0.26%   |
| AMD Phenom II X2        | 3         | 0.26%   |
| AMD E                   | 3         | 0.26%   |
| AMD A8                  | 3         | 0.26%   |
| Intel Pentium D         | 2         | 0.17%   |
| Intel Core m7           | 2         | 0.17%   |
| AMD Phenom II X6        | 2         | 0.17%   |
| AMD Phenom II X4        | 2         | 0.17%   |
| AMD E2                  | 2         | 0.17%   |
| AMD Athlon II X2        | 2         | 0.17%   |
| AMD Athlon Dual Core    | 2         | 0.17%   |
| AMD Athlon              | 2         | 0.17%   |
| AMD A12                 | 2         | 0.17%   |
| QUALCOMM AArch64        | 1         | 0.09%   |
| Intel Pentium 4         | 1         | 0.09%   |
| Intel Core m5           | 1         | 0.09%   |
| Intel Core m3           | 1         | 0.09%   |
| Intel Core M            | 1         | 0.09%   |
| Intel Core 2            | 1         | 0.09%   |
| AMD Turion II           | 1         | 0.09%   |
| AMD Turion 64 X2 Mobile | 1         | 0.09%   |
| AMD PRO A10             | 1         | 0.09%   |
| AMD E1                  | 1         | 0.09%   |
| AMD Athlon X2           | 1         | 0.09%   |
| AMD Athlon II X4        | 1         | 0.09%   |
| AMD Athlon II           | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 505       | 43.38%  |
| 2      | 326       | 28.01%  |
| 6      | 161       | 13.83%  |
| 8      | 126       | 10.82%  |
| 12     | 23        | 1.98%   |
| 16     | 13        | 1.12%   |
| 1      | 5         | 0.43%   |
| 10     | 2         | 0.17%   |
| 3      | 2         | 0.17%   |
| 24     | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1153      | 99.14%  |
| 2      | 9         | 0.77%   |
| 3      | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 901       | 77.27%  |
| 1      | 265       | 22.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1163      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 5.13%   |
| 0x206a7    | 56        | 4.79%   |
| 0x806ec    | 55        | 4.7%    |
| 0x306c3    | 55        | 4.7%    |
| 0x806c1    | 51        | 4.36%   |
| 0x806ea    | 50        | 4.27%   |
| 0x306a9    | 49        | 4.19%   |
| 0x906ea    | 48        | 4.1%    |
| 0x806e9    | 45        | 3.85%   |
| 0x406e3    | 39        | 3.33%   |
| 0x08701021 | 36        | 3.08%   |
| 0x506e3    | 33        | 2.82%   |
| 0x906e9    | 32        | 2.74%   |
| 0x08600106 | 31        | 2.65%   |
| 0x306d4    | 27        | 2.31%   |
| 0x40651    | 24        | 2.05%   |
| 0x1067a    | 22        | 1.88%   |
| 0x08108109 | 21        | 1.79%   |
| 0x906ed    | 20        | 1.71%   |
| 0xa0652    | 19        | 1.62%   |
| 0x706e5    | 19        | 1.62%   |
| 0x08108102 | 19        | 1.62%   |
| 0x0800820d | 18        | 1.54%   |
| 0x0a201009 | 17        | 1.45%   |
| 0x08600104 | 17        | 1.45%   |
| 0x30678    | 16        | 1.37%   |
| 0x20655    | 16        | 1.37%   |
| 0x0a50000c | 16        | 1.37%   |
| 0x08701013 | 15        | 1.28%   |
| 0x806eb    | 14        | 1.2%    |
| 0x406c4    | 11        | 0.94%   |
| 0x706a1    | 10        | 0.85%   |
| 0x08600103 | 10        | 0.85%   |
| 0x0810100b | 9         | 0.77%   |
| 0x406c3    | 8         | 0.68%   |
| 0x40661    | 8         | 0.68%   |
| 0x106e5    | 8         | 0.68%   |
| 0x0a201016 | 8         | 0.68%   |
| 0x08101016 | 8         | 0.68%   |
| 0xa0655    | 7         | 0.6%    |
| 0x08001138 | 6         | 0.51%   |
| 0x906ec    | 5         | 0.43%   |
| 0x706a8    | 5         | 0.43%   |
| 0x08608102 | 5         | 0.43%   |
| 0x08001137 | 5         | 0.43%   |
| 0x010000c8 | 5         | 0.43%   |
| 0xa0671    | 4         | 0.34%   |
| 0xa0653    | 4         | 0.34%   |
| 0x6fd      | 4         | 0.34%   |
| 0x0a50000b | 4         | 0.34%   |
| 0x08608103 | 4         | 0.34%   |
| 0x08600102 | 4         | 0.34%   |
| 0x906eb    | 3         | 0.26%   |
| 0x6fb      | 3         | 0.26%   |
| 0x106a5    | 3         | 0.26%   |
| 0x08101007 | 3         | 0.26%   |
| 0x07030105 | 3         | 0.26%   |
| 0x0600611a | 3         | 0.26%   |
| 0x06003106 | 3         | 0.26%   |
| 0x06001119 | 3         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 282       | 24.25%  |
| Zen 2         | 117       | 10.06%  |
| Haswell       | 93        | 8%      |
| Skylake       | 76        | 6.53%   |
| Zen+          | 64        | 5.5%    |
| SandyBridge   | 58        | 4.99%   |
| IvyBridge     | 53        | 4.56%   |
| TigerLake     | 51        | 4.39%   |
| Zen 3         | 44        | 3.78%   |
| Silvermont    | 36        | 3.1%    |
| Zen           | 34        | 2.92%   |
| CometLake     | 33        | 2.84%   |
| Broadwell     | 30        | 2.58%   |
| Icelake       | 26        | 2.24%   |
| Penryn        | 24        | 2.06%   |
| Westmere      | 19        | 1.63%   |
| Unknown       | 18        | 1.55%   |
| Goldmont plus | 15        | 1.29%   |
| Piledriver    | 13        | 1.12%   |
| Nehalem       | 13        | 1.12%   |
| K10           | 13        | 1.12%   |
| Core          | 9         | 0.77%   |
| Excavator     | 8         | 0.69%   |
| K8 Hammer     | 7         | 0.6%    |
| Jaguar        | 5         | 0.43%   |
| Steamroller   | 4         | 0.34%   |
| Puma          | 4         | 0.34%   |
| NetBurst      | 3         | 0.26%   |
| K10 Llano     | 3         | 0.26%   |
| Bobcat        | 3         | 0.26%   |
| Goldmont      | 2         | 0.17%   |
| Bulldozer     | 2         | 0.17%   |
| Bonnell       | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 673       | 47.49%  |
| Nvidia                     | 393       | 27.73%  |
| AMD                        | 346       | 24.42%  |
| ASPEED Technology          | 3         | 0.21%   |
| Matrox Electronics Systems | 1         | 0.07%   |
| ATI Technologies           | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 64        | 4.44%   |
| Intel UHD Graphics 620                                                                   | 54        | 3.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 3.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 3.12%   |
| Intel HD Graphics 620                                                                    | 40        | 2.77%   |
| AMD Picasso                                                                              | 40        | 2.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 37        | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 32        | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 2.15%   |
| Intel HD Graphics 5500                                                                   | 26        | 1.8%    |
| Intel HD Graphics 630                                                                    | 24        | 1.66%   |
| Intel HD Graphics 530                                                                    | 22        | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 20        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 1.25%   |
| AMD Cezanne                                                                              | 18        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 0.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 11        | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 0.62%   |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.62%   |
| AMD Lucienne                                                                             | 9         | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 8         | 0.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 0.49%   |
| Nvidia GM108M [GeForce 940M]                                                             | 7         | 0.49%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 7         | 0.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.49%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 6         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.42%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 0.42%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 6         | 0.42%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 6         | 0.42%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 5         | 0.35%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.35%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5         | 0.35%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 0.35%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 5         | 0.35%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 5         | 0.35%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 5         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 439       | 37.68%  |
| 1 x AMD        | 269       | 23.09%  |
| Intel + Nvidia | 181       | 15.54%  |
| 1 x Nvidia     | 180       | 15.45%  |
| Intel + AMD    | 34        | 2.92%   |
| AMD + Nvidia   | 26        | 2.23%   |
| 2 x AMD        | 16        | 1.37%   |
| Other          | 10        | 0.86%   |
| 2 x Nvidia     | 6         | 0.52%   |
| 1 x ASPEED     | 3         | 0.26%   |
| 1 x Matrox     | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 967       | 82.16%  |
| Proprietary | 188       | 15.97%  |
| Unknown     | 22        | 1.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 598       | 50.42%  |
| 1.01-2.0   | 167       | 14.08%  |
| 0.01-0.5   | 125       | 10.54%  |
| 3.01-4.0   | 96        | 8.09%   |
| 0.51-1.0   | 71        | 5.99%   |
| 7.01-8.0   | 69        | 5.82%   |
| 5.01-6.0   | 32        | 2.7%    |
| 8.01-16.0  | 17        | 1.43%   |
| 2.01-3.0   | 10        | 0.84%   |
| 16.01-24.0 | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 155       | 11.21%  |
| LG Display              | 144       | 10.41%  |
| Samsung Electronics     | 132       | 9.54%   |
| Chimei Innolux          | 129       | 9.33%   |
| BOE                     | 117       | 8.46%   |
| Dell                    | 103       | 7.45%   |
| Goldstar                | 102       | 7.38%   |
| Sharp                   | 47        | 3.4%    |
| Acer                    | 45        | 3.25%   |
| BenQ                    | 44        | 3.18%   |
| Hewlett-Packard         | 41        | 2.96%   |
| AOC                     | 29        | 2.1%    |
| Philips                 | 28        | 2.02%   |
| Lenovo                  | 28        | 2.02%   |
| Apple                   | 25        | 1.81%   |
| Ancor Communications    | 25        | 1.81%   |
| Iiyama                  | 23        | 1.66%   |
| PANDA                   | 18        | 1.3%    |
| ViewSonic               | 12        | 0.87%   |
| CSO                     | 11        | 0.8%    |
| ASUSTek Computer        | 11        | 0.8%    |
| Sceptre Tech            | 9         | 0.65%   |
| InfoVision              | 8         | 0.58%   |
| Chi Mei Optoelectronics | 8         | 0.58%   |
| Sony                    | 6         | 0.43%   |
| ___                     | 5         | 0.36%   |
| Unknown                 | 5         | 0.36%   |
| MSI                     | 5         | 0.36%   |
| Vizio                   | 4         | 0.29%   |
| Toshiba                 | 4         | 0.29%   |
| NEC Computers           | 4         | 0.29%   |
| TMX                     | 3         | 0.22%   |
| Pixio                   | 3         | 0.22%   |
| Insignia                | 3         | 0.22%   |
| Vestel Elektronik       | 2         | 0.14%   |
| Mi                      | 2         | 0.14%   |
| KTC                     | 2         | 0.14%   |
| JDI                     | 2         | 0.14%   |
| HannStar                | 2         | 0.14%   |
| eMachines               | 2         | 0.14%   |
| Zoran                   | 1         | 0.07%   |
| WST                     | 1         | 0.07%   |
| Unknown (XXX)           | 1         | 0.07%   |
| SKY                     | 1         | 0.07%   |
| RZR                     | 1         | 0.07%   |
| RTK                     | 1         | 0.07%   |
| RIS                     | 1         | 0.07%   |
| QCM                     | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| Packard Bell            | 1         | 0.07%   |
| OUT                     | 1         | 0.07%   |
| Orion                   | 1         | 0.07%   |
| OPT                     | 1         | 0.07%   |
| Onkyo                   | 1         | 0.07%   |
| NEW                     | 1         | 0.07%   |
| Mitsubishi              | 1         | 0.07%   |
| Microstep               | 1         | 0.07%   |
| Medion Akoya            | 1         | 0.07%   |
| Medion                  | 1         | 0.07%   |
| Marantz                 | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch                        | 10        | 0.7%    |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch                           | 9         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch                      | 9         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch                      | 9         | 0.63%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch                        | 7         | 0.49%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                               | 6         | 0.42%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                              | 6         | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                                | 6         | 0.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                                     | 6         | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch                        | 6         | 0.42%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                               | 5         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch                     | 5         | 0.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch                     | 5         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch                  | 5         | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch                          | 5         | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch                           | 5         | 0.35%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                                 | 5         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch                       | 5         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch                      | 5         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch                        | 5         | 0.35%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                               | 4         | 0.28%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch                         | 4         | 0.28%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                               | 4         | 0.28%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch                          | 4         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch                          | 4         | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch                           | 4         | 0.28%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                             | 4         | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                               | 4         | 0.28%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                                | 4         | 0.28%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                                     | 4         | 0.28%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                                     | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch                      | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch                      | 4         | 0.28%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                                     | 4         | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch                        | 4         | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch                         | 4         | 0.28%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                                 | 4         | 0.28%   |
| AOC 2757M AOC2757 1920x1080 598x336mm 27.0-inch                                       | 4         | 0.28%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 3         | 0.21%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                               | 3         | 0.21%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                               | 3         | 0.21%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                               | 3         | 0.21%   |
| Sceptre Tech E275W-1920 SPT0ABF 1920x1080 443x249mm 20.0-inch                         | 3         | 0.21%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch                  | 3         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch                     | 3         | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                               | 3         | 0.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                               | 3         | 0.21%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                               | 3         | 0.21%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch                          | 3         | 0.21%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch                          | 3         | 0.21%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch                          | 3         | 0.21%   |
| Goldstar W2442 GSM56D9 1680x1050 530x300mm 24.0-inch                                  | 3         | 0.21%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                                  | 3         | 0.21%   |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch                               | 3         | 0.21%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                                | 3         | 0.21%   |
| Dell U2515H DELD06E 1920x1080 550x310mm 24.9-inch                                     | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch                      | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch                       | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch                      | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch                      | 3         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 656       | 51.01%  |
| 1366x768 (WXGA)    | 174       | 13.53%  |
| 3840x2160 (4K)     | 102       | 7.93%   |
| 2560x1440 (QHD)    | 94        | 7.31%   |
| 1920x1200 (WUXGA)  | 39        | 3.03%   |
| 1600x900 (HD+)     | 34        | 2.64%   |
| 2560x1080          | 27        | 2.1%    |
| 1440x900 (WXGA+)   | 19        | 1.48%   |
| 1280x1024 (SXGA)   | 19        | 1.48%   |
| 2560x1600          | 14        | 1.09%   |
| 3440x1440          | 12        | 0.93%   |
| 1360x768           | 12        | 0.93%   |
| 2880x1800          | 11        | 0.86%   |
| 1680x1050 (WSXGA+) | 11        | 0.86%   |
| 3200x1800 (QHD+)   | 8         | 0.62%   |
| 1280x800 (WXGA)    | 7         | 0.54%   |
| 3840x1080          | 6         | 0.47%   |
| 3840x2400          | 4         | 0.31%   |
| Unknown            | 4         | 0.31%   |
| 2160x1440          | 3         | 0.23%   |
| 1024x768 (XGA)     | 3         | 0.23%   |
| 3456x2160          | 2         | 0.16%   |
| 3000x2000          | 2         | 0.16%   |
| 2160x1350          | 2         | 0.16%   |
| 2048x1152          | 2         | 0.16%   |
| 1920x540           | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1600x1200          | 2         | 0.16%   |
| 7680x1440          | 1         | 0.08%   |
| 7120x1080          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 3240x2160          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 2256x1504          | 1         | 0.08%   |
| 1920x515           | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |
| 1440x2560          | 1         | 0.08%   |
| 1280x960           | 1         | 0.08%   |
| 1280x720 (HD)      | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 362       | 26.16%  |
| 13      | 162       | 11.71%  |
| 27      | 142       | 10.26%  |
| 24      | 130       | 9.39%   |
| 14      | 122       | 8.82%   |
| 23      | 90        | 6.5%    |
| 21      | 73        | 5.27%   |
| 17      | 44        | 3.18%   |
| 34      | 36        | 2.6%    |
| 31      | 27        | 1.95%   |
| 12      | 26        | 1.88%   |
| 19      | 25        | 1.81%   |
| 18      | 25        | 1.81%   |
| Unknown | 16        | 1.16%   |
| 20      | 11        | 0.79%   |
| 72      | 10        | 0.72%   |
| 32      | 9         | 0.65%   |
| 22      | 9         | 0.65%   |
| 16      | 8         | 0.58%   |
| 25      | 7         | 0.51%   |
| 11      | 7         | 0.51%   |
| 84      | 5         | 0.36%   |
| 48      | 5         | 0.36%   |
| 28      | 4         | 0.29%   |
| 49      | 3         | 0.22%   |
| 40      | 3         | 0.22%   |
| 39      | 3         | 0.22%   |
| 29      | 3         | 0.22%   |
| 54      | 2         | 0.14%   |
| 42      | 2         | 0.14%   |
| 33      | 2         | 0.14%   |
| 26      | 2         | 0.14%   |
| 74      | 1         | 0.07%   |
| 65      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 35      | 1         | 0.07%   |
| 30      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 565       | 42.07%  |
| 501-600     | 327       | 24.35%  |
| 401-500     | 123       | 9.16%   |
| 201-300     | 111       | 8.27%   |
| 351-400     | 68        | 5.06%   |
| 701-800     | 47        | 3.5%    |
| 601-700     | 45        | 3.35%   |
| 1501-2000   | 16        | 1.19%   |
| Unknown     | 16        | 1.19%   |
| 1001-1500   | 12        | 0.89%   |
| 801-900     | 8         | 0.6%    |
| 901-1000    | 4         | 0.3%    |
| 101-200     | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 977       | 82.24%  |
| 16/10   | 110       | 9.26%   |
| 21/9    | 41        | 3.45%   |
| 5/4     | 20        | 1.68%   |
| 3/2     | 13        | 1.09%   |
| 4/3     | 8         | 0.67%   |
| Unknown | 8         | 0.67%   |
| 32/9    | 6         | 0.51%   |
| 6/5     | 2         | 0.17%   |
| 3.88    | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 361       | 26.33%  |
| 201-250        | 228       | 16.63%  |
| 81-90          | 208       | 15.17%  |
| 301-350        | 143       | 10.43%  |
| 351-500        | 82        | 5.98%   |
| 71-80          | 76        | 5.54%   |
| 151-200        | 65        | 4.74%   |
| 251-300        | 47        | 3.43%   |
| 121-130        | 37        | 2.7%    |
| 61-70          | 24        | 1.75%   |
| 141-150        | 23        | 1.68%   |
| More than 1000 | 21        | 1.53%   |
| 501-1000       | 17        | 1.24%   |
| Unknown        | 16        | 1.17%   |
| 51-60          | 8         | 0.58%   |
| 131-140        | 5         | 0.36%   |
| 111-120        | 5         | 0.36%   |
| 91-100         | 3         | 0.22%   |
| 1-40           | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 443       | 33.28%  |
| 51-100        | 383       | 28.78%  |
| 101-120       | 308       | 23.14%  |
| 161-240       | 115       | 8.64%   |
| More than 240 | 48        | 3.61%   |
| 1-50          | 18        | 1.35%   |
| Unknown       | 16        | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 841       | 71.45%  |
| 2     | 256       | 21.75%  |
| 0     | 44        | 3.74%   |
| 3     | 35        | 2.97%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 702       | 41.39%  |
| Realtek Semiconductor             | 581       | 34.26%  |
| Qualcomm Atheros                  | 154       | 9.08%   |
| Broadcom                          | 64        | 3.77%   |
| Broadcom Limited                  | 23        | 1.36%   |
| TP-Link                           | 20        | 1.18%   |
| Ralink Technology                 | 18        | 1.06%   |
| Marvell Technology Group          | 10        | 0.59%   |
| Lenovo                            | 10        | 0.59%   |
| DisplayLink                       | 9         | 0.53%   |
| Aquantia                          | 9         | 0.53%   |
| Ralink                            | 8         | 0.47%   |
| Nvidia                            | 6         | 0.35%   |
| MEDIATEK                          | 6         | 0.35%   |
| NetGear                           | 5         | 0.29%   |
| Huawei Technologies               | 5         | 0.29%   |
| Hewlett-Packard                   | 5         | 0.29%   |
| Sierra Wireless                   | 4         | 0.24%   |
| Qualcomm                          | 4         | 0.24%   |
| Xiaomi                            | 3         | 0.18%   |
| Samsung Electronics               | 3         | 0.18%   |
| ICS Advent                        | 3         | 0.18%   |
| Dell                              | 3         | 0.18%   |
| D-Link System                     | 3         | 0.18%   |
| ASUSTek Computer                  | 3         | 0.18%   |
| ASIX Electronics                  | 3         | 0.18%   |
| Apple                             | 3         | 0.18%   |
| Qualcomm Atheros Communications   | 2         | 0.12%   |
| Motorola PCS                      | 2         | 0.12%   |
| Mellanox Technologies             | 2         | 0.12%   |
| Linksys                           | 2         | 0.12%   |
| Fibocom                           | 2         | 0.12%   |
| Ericsson Business Mobile Networks | 2         | 0.12%   |
| D-Link                            | 2         | 0.12%   |
| Wilocity                          | 1         | 0.06%   |
| T & A Mobile Phones               | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.06%   |
| Oculus VR                         | 1         | 0.06%   |
| MosChip Semiconductor             | 1         | 0.06%   |
| Microsoft                         | 1         | 0.06%   |
| MicroPython                       | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| LG Electronics                    | 1         | 0.06%   |
| JMicron Technology                | 1         | 0.06%   |
| InterBiometrics                   | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| Google                            | 1         | 0.06%   |
| Arduino SA                        | 1         | 0.06%   |
| Adafruit                          | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 398       | 19.6%   |
| Intel Wi-Fi 6 AX200                                               | 147       | 7.24%   |
| Intel Wireless 8265 / 8275                                        | 60        | 2.95%   |
| Intel I211 Gigabit Network Connection                             | 52        | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 49        | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 43        | 2.12%   |
| Intel Wi-Fi 6 AX201                                               | 42        | 2.07%   |
| Intel Wireless 8260                                               | 39        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 36        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 30        | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.48%   |
| Intel Wireless 7260                                               | 28        | 1.38%   |
| Intel Wireless 7265                                               | 27        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 25        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 21        | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 21        | 1.03%   |
| Intel Wireless-AC 9260                                            | 20        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 19        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.79%   |
| Intel Wireless 3165                                               | 16        | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 11        | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 0.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 0.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.39%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 7         | 0.34%   |
| Intel Wireless 3160                                               | 7         | 0.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.34%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 7         | 0.34%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 0.3%    |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.3%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 6         | 0.3%    |
| Intel Ethernet Connection I217-V                                  | 6         | 0.3%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 6         | 0.3%    |
| Intel Centrino Advanced-N 6235                                    | 6         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 596       | 60.94%  |
| Realtek Semiconductor           | 127       | 12.99%  |
| Qualcomm Atheros                | 126       | 12.88%  |
| Broadcom                        | 48        | 4.91%   |
| Ralink Technology               | 18        | 1.84%   |
| TP-Link                         | 14        | 1.43%   |
| Broadcom Limited                | 11        | 1.12%   |
| Ralink                          | 8         | 0.82%   |
| NetGear                         | 5         | 0.51%   |
| MEDIATEK                        | 5         | 0.51%   |
| Qualcomm Atheros Communications | 2         | 0.2%    |
| Qualcomm                        | 2         | 0.2%    |
| Marvell Technology Group        | 2         | 0.2%    |
| Fibocom                         | 2         | 0.2%    |
| Dell                            | 2         | 0.2%    |
| D-Link System                   | 2         | 0.2%    |
| ASUSTek Computer                | 2         | 0.2%    |
| Wilocity                        | 1         | 0.1%    |
| Sierra Wireless                 | 1         | 0.1%    |
| Microsoft                       | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| IMC Networks                    | 1         | 0.1%    |
| Hewlett-Packard                 | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 147       | 15%     |
| Intel Wireless 8265 / 8275                                     | 60        | 6.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 43        | 4.39%   |
| Intel Wi-Fi 6 AX201                                            | 42        | 4.29%   |
| Intel Wireless 8260                                            | 39        | 3.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 30        | 3.06%   |
| Intel Wireless 7260                                            | 28        | 2.86%   |
| Intel Wireless 7265                                            | 27        | 2.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 25        | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 2.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 24        | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 21        | 2.14%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 2.14%   |
| Intel Wireless-AC 9260                                         | 20        | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 1.63%   |
| Intel Wireless 3165                                            | 16        | 1.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 0.71%   |
| Intel Wireless 3160                                            | 7         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 0.61%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 6         | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 6         | 0.61%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.61%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 0.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 0.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 5         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 0.51%   |
| MEDIATEK Network controller                                    | 5         | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.41%   |
| Realtek 802.11ac NIC                                           | 4         | 0.41%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 0.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.41%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.41%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 3         | 0.31%   |
| TP-Link 802.11ac NIC                                           | 3         | 0.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.31%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 3         | 0.31%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 3         | 0.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 0.31%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.31%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 3         | 0.31%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 3         | 0.31%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 526       | 52.81%  |
| Intel                         | 308       | 30.92%  |
| Qualcomm Atheros              | 40        | 4.02%   |
| Broadcom                      | 24        | 2.41%   |
| Broadcom Limited              | 12        | 1.2%    |
| Lenovo                        | 10        | 1%      |
| DisplayLink                   | 9         | 0.9%    |
| Aquantia                      | 9         | 0.9%    |
| Marvell Technology Group      | 8         | 0.8%    |
| TP-Link                       | 6         | 0.6%    |
| Nvidia                        | 6         | 0.6%    |
| Xiaomi                        | 3         | 0.3%    |
| Sierra Wireless               | 3         | 0.3%    |
| Samsung Electronics           | 3         | 0.3%    |
| ICS Advent                    | 3         | 0.3%    |
| Huawei Technologies           | 3         | 0.3%    |
| ASIX Electronics              | 3         | 0.3%    |
| Apple                         | 3         | 0.3%    |
| Qualcomm                      | 2         | 0.2%    |
| Mellanox Technologies         | 2         | 0.2%    |
| D-Link                        | 2         | 0.2%    |
| OnePlus Technology (Shenzhen) | 1         | 0.1%    |
| Motorola PCS                  | 1         | 0.1%    |
| MosChip Semiconductor         | 1         | 0.1%    |
| MediaTek                      | 1         | 0.1%    |
| Linksys                       | 1         | 0.1%    |
| LG Electronics                | 1         | 0.1%    |
| JMicron Technology            | 1         | 0.1%    |
| Hewlett-Packard               | 1         | 0.1%    |
| Google                        | 1         | 0.1%    |
| D-Link System                 | 1         | 0.1%    |
| ASUSTek Computer              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 398       | 38.45%  |
| Intel I211 Gigabit Network Connection                                         | 52        | 5.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 49        | 4.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 49        | 4.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 36        | 3.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 30        | 2.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 30        | 2.9%    |
| Intel Ethernet Connection I217-LM                                             | 15        | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                          | 13        | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                         | 13        | 1.26%   |
| Intel Ethernet Connection (7) I219-V                                          | 12        | 1.16%   |
| Intel Ethernet Controller I225-V                                              | 11        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                         | 10        | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                                         | 9         | 0.87%   |
| Intel Ethernet Connection (2) I218-V                                          | 9         | 0.87%   |
| Intel Ethernet Connection (10) I219-V                                         | 9         | 0.87%   |
| Intel Ethernet Connection I218-LM                                             | 8         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                                          | 8         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                         | 8         | 0.77%   |
| Intel Ethernet Connection I219-LM                                             | 7         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                                         | 7         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 6         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 6         | 0.58%   |
| Intel Ethernet Connection I217-V                                              | 6         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                      | 6         | 0.58%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 0.58%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6         | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]               | 5         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 5         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 5         | 0.48%   |
| Intel I210 Gigabit Network Connection                                         | 5         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5         | 0.48%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 5         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 5         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 4         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 4         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 4         | 0.39%   |
| Lenovo ThinkPad TBT3 LAN                                                      | 4         | 0.39%   |
| Intel Ethernet Connection I219-V                                              | 4         | 0.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.39%   |
| DisplayLink Dell Universal Dock D6000                                         | 4         | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 4         | 0.39%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                       | 4         | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3         | 0.29%   |
| Sierra Wireless EM7345 4G LTE                                                 | 3         | 0.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3         | 0.29%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3         | 0.29%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3         | 0.29%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.29%   |
| Intel Ethernet Connection (12) I219-V                                         | 3         | 0.29%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.29%   |
| Intel 82576 Gigabit Network Connection                                        | 3         | 0.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.29%   |
| DisplayLink USB3.0 5K Graphic Docking                                         | 3         | 0.29%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 0.29%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3         | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.19%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 933       | 50.24%  |
| Ethernet | 908       | 48.9%   |
| Modem    | 14        | 0.75%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 829       | 53.8%   |
| Ethernet | 710       | 46.07%  |
| Modem    | 2         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 614       | 52.57%  |
| 1     | 457       | 39.13%  |
| 3     | 45        | 3.85%   |
| 0     | 40        | 3.42%   |
| 4     | 7         | 0.6%    |
| 5     | 3         | 0.26%   |
| 9     | 1         | 0.09%   |
| 8     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 889       | 75.85%  |
| Yes  | 283       | 24.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 520       | 62.42%  |
| Realtek Semiconductor           | 65        | 7.8%    |
| Qualcomm Atheros Communications | 56        | 6.72%   |
| Broadcom                        | 35        | 4.2%    |
| IMC Networks                    | 32        | 3.84%   |
| Cambridge Silicon Radio         | 32        | 3.84%   |
| Lite-On Technology              | 28        | 3.36%   |
| Apple                           | 25        | 3%      |
| ASUSTek Computer                | 11        | 1.32%   |
| Foxconn / Hon Hai               | 6         | 0.72%   |
| Dell                            | 6         | 0.72%   |
| Realtek                         | 4         | 0.48%   |
| Ralink                          | 4         | 0.48%   |
| Marvell Semiconductor           | 2         | 0.24%   |
| Hewlett-Packard                 | 2         | 0.24%   |
| Unknown                         | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Dynex                           | 1         | 0.12%   |
| D-Link System                   | 1         | 0.12%   |
| Askey Computer                  | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 361       | 43.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 64        | 7.68%   |
| Realtek Bluetooth Radio                                                             | 39        | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 33        | 3.96%   |
| Intel Bluetooth wireless interface                                                  | 33        | 3.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 32        | 3.84%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 25        | 3%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 2.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 20        | 2.4%    |
| Apple Bluetooth Host Controller                                                     | 16        | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.44%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 1.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 11        | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 9         | 1.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 8         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.84%   |
| IMC Networks Bluetooth Device                                                       | 7         | 0.84%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 0.6%    |
| Lite-On Bluetooth Device                                                            | 5         | 0.6%    |
| IMC Networks Wireless_Device                                                        | 5         | 0.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 5         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.48%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.48%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.48%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 0.36%   |
| Lite-On Bluetooth Radio                                                             | 3         | 0.36%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.36%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.36%   |
| Broadcom HP Portable Bumble Bee                                                     | 3         | 0.36%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.24%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 2         | 0.24%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.24%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.24%   |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                                              | 2         | 0.24%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.24%   |
| ASUS Bluetooth Radio                                                                | 2         | 0.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.24%   |
| Unknown Bluetooth Device                                                            | 1         | 0.12%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE                                | 1         | 0.12%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.12%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.12%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.12%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.12%   |
| IMC Networks Bluetooth                                                              | 1         | 0.12%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.12%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.12%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.12%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter                             | 1         | 0.12%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.12%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.12%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.12%   |
| D-Link System DBT-122 Bluetooth                                                     | 1         | 0.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 786       | 47.41%  |
| AMD                         | 375       | 22.62%  |
| Nvidia                      | 293       | 17.67%  |
| C-Media Electronics         | 30        | 1.81%   |
| Logitech                    | 18        | 1.09%   |
| Lenovo                      | 10        | 0.6%    |
| GN Netcom                   | 10        | 0.6%    |
| Creative Technology         | 9         | 0.54%   |
| Plantronics                 | 7         | 0.42%   |
| Kingston Technology         | 7         | 0.42%   |
| Blue Microphones            | 7         | 0.42%   |
| Realtek Semiconductor       | 6         | 0.36%   |
| Corsair                     | 6         | 0.36%   |
| RODE Microphones            | 5         | 0.3%    |
| Generalplus Technology      | 5         | 0.3%    |
| Focusrite-Novation          | 5         | 0.3%    |
| Creative Labs               | 5         | 0.3%    |
| SteelSeries ApS             | 4         | 0.24%   |
| Samson Technologies         | 4         | 0.24%   |
| Razer USA                   | 4         | 0.24%   |
| Sennheiser Communications   | 3         | 0.18%   |
| Microsoft                   | 3         | 0.18%   |
| JMTek                       | 3         | 0.18%   |
| Hewlett-Packard             | 3         | 0.18%   |
| GYROCOM C&C                 | 3         | 0.18%   |
| Dell                        | 3         | 0.18%   |
| ULi Electronics             | 2         | 0.12%   |
| Texas Instruments           | 2         | 0.12%   |
| Tenx Technology             | 2         | 0.12%   |
| Sony                        | 2         | 0.12%   |
| Schiit Audio                | 2         | 0.12%   |
| Cambridge Silicon Radio     | 2         | 0.12%   |
| ASUSTek Computer            | 2         | 0.12%   |
| ZOOM                        | 1         | 0.06%   |
| Yamaha                      | 1         | 0.06%   |
| VIA Technologies            | 1         | 0.06%   |
| USB MICROPHONE              | 1         | 0.06%   |
| Trust                       | 1         | 0.06%   |
| Thermaltake                 | 1         | 0.06%   |
| Signalpath International    | 1         | 0.06%   |
| Shenzhen Riitek Technology  | 1         | 0.06%   |
| SAVITECH                    | 1         | 0.06%   |
| ROCCAT                      | 1         | 0.06%   |
| Quanta                      | 1         | 0.06%   |
| PreSonus Audio Electronics  | 1         | 0.06%   |
| Native Instruments          | 1         | 0.06%   |
| Meridian                    | 1         | 0.06%   |
| Medeli Electronics          | 1         | 0.06%   |
| JBL                         | 1         | 0.06%   |
| iPassion Technology         | 1         | 0.06%   |
| iCreate Technologies        | 1         | 0.06%   |
| Griffin Technology          | 1         | 0.06%   |
| Fujitsu                     | 1         | 0.06%   |
| FiiO Electronics Technology | 1         | 0.06%   |
| FIFINE Microphones          | 1         | 0.06%   |
| EGO SYStems                 | 1         | 0.06%   |
| Conexant Systems            | 1         | 0.06%   |
| C&T12L5V                    | 1         | 0.06%   |
| BEHRINGER International     | 1         | 0.06%   |
| Audio-Technica              | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 155       | 7.73%   |
| Intel Sunrise Point-LP HD Audio                                            | 139       | 6.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 85        | 4.24%   |
| AMD Starship/Matisse HD Audio Controller                                   | 76        | 3.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 62        | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 60        | 2.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 56        | 2.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 51        | 2.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 50        | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 39        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 38        | 1.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37        | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 34        | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 33        | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 33        | 1.65%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 28        | 1.4%    |
| Intel Broadwell-U Audio Controller                                         | 28        | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26        | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 24        | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.2%    |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.2%    |
| AMD Navi 10 HDMI Audio                                                     | 23        | 1.15%   |
| AMD FCH Azalia Controller                                                  | 23        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 22        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 21        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 20        | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 19        | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                              | 19        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17        | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 17        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 15        | 0.75%   |
| Intel CM238 HD Audio Controller                                            | 15        | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 15        | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 13        | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                   | 13        | 0.65%   |
| Nvidia Audio device                                                        | 12        | 0.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 12        | 0.6%    |
| Nvidia TU104 HD Audio Controller                                           | 11        | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 11        | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 0.55%   |
| Nvidia High Definition Audio Controller                                    | 9         | 0.45%   |
| Nvidia GM204 High Definition Audio Controller                              | 8         | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                         | 8         | 0.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 0.4%    |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 8         | 0.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8         | 0.4%    |
| C-Media Electronics USB Audio Device                                       | 8         | 0.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 0.35%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7         | 0.35%   |
| Realtek Semiconductor USB Audio                                            | 6         | 0.3%    |
| Nvidia GM206 High Definition Audio Controller                              | 6         | 0.3%    |
| Blue Microphones Yeti Stereo Microphone                                    | 6         | 0.3%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 6         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 144       | 21.24%  |
| SK Hynix            | 129       | 19.03%  |
| Micron Technology   | 76        | 11.21%  |
| Kingston            | 76        | 11.21%  |
| Unknown             | 56        | 8.26%   |
| Corsair             | 50        | 7.37%   |
| Crucial             | 35        | 5.16%   |
| G.Skill             | 27        | 3.98%   |
| A-DATA Technology   | 18        | 2.65%   |
| Elpida              | 11        | 1.62%   |
| Ramaxel Technology  | 8         | 1.18%   |
| Unknown (ABCD)      | 7         | 1.03%   |
| GOODRAM             | 6         | 0.88%   |
| Teikon              | 5         | 0.74%   |
| Team                | 5         | 0.74%   |
| Smart               | 4         | 0.59%   |
| Silicon Power       | 3         | 0.44%   |
| Nanya Technology    | 3         | 0.44%   |
| Avant               | 3         | 0.44%   |
| Patriot             | 2         | 0.29%   |
| Goldkey             | 2         | 0.29%   |
| Transcend           | 1         | 0.15%   |
| pqi                 | 1         | 0.15%   |
| OnBoard             | 1         | 0.15%   |
| KomputerBay         | 1         | 0.15%   |
| Kllisre             | 1         | 0.15%   |
| Golden Empire       | 1         | 0.15%   |
| Gold Key            | 1         | 0.15%   |
| 0898000080AD        | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 10        | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 9         | 1.24%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 8         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 8         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 7         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB SODIMM LPDDR4 2400MT/s | 6         | 0.83%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 6         | 0.83%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 6         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 5         | 0.69%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 5         | 0.69%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 5         | 0.69%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.69%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s         | 5         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.69%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.55%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 4         | 0.55%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 4         | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.55%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s              | 4         | 0.55%   |
| Samsung RAM K4UBE3D4AA-MGCL 8192MB Row Of Chips LPDDR4 4267MT/s     | 4         | 0.55%   |
| Micron RAM Module 8GB Chip LPDDR4                                   | 4         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 3         | 0.41%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 3         | 0.41%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.41%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.41%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.41%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.41%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 3         | 0.41%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.41%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                         | 3         | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 3         | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s               | 3         | 0.41%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s            | 3         | 0.41%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 3         | 0.41%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 3         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 0.41%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s                | 3         | 0.41%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 3         | 0.41%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 3         | 0.41%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s               | 3         | 0.41%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s               | 3         | 0.41%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3000MT/s              | 3         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.28%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                           | 2         | 0.28%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                             | 2         | 0.28%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s               | 2         | 0.28%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 2         | 0.28%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                        | 2         | 0.28%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 2         | 0.28%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 2         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 340       | 59.23%  |
| DDR3    | 154       | 26.83%  |
| LPDDR4  | 33        | 5.75%   |
| LPDDR3  | 21        | 3.66%   |
| DDR2    | 11        | 1.92%   |
| Unknown | 10        | 1.74%   |
| DDR     | 3         | 0.52%   |
| SDRAM   | 2         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 339       | 58.55%  |
| DIMM         | 166       | 28.67%  |
| Row Of Chips | 59        | 10.19%  |
| Chip         | 13        | 2.25%   |
| RIMM         | 1         | 0.17%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 238       | 38.26%  |
| 4096  | 165       | 26.53%  |
| 16384 | 131       | 21.06%  |
| 2048  | 57        | 9.16%   |
| 1024  | 16        | 2.57%   |
| 32768 | 14        | 2.25%   |
| 512   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 131       | 21.2%   |
| 2667    | 113       | 18.28%  |
| 1600    | 102       | 16.5%   |
| 2400    | 49        | 7.93%   |
| 2133    | 41        | 6.63%   |
| 1333    | 29        | 4.69%   |
| 3600    | 17        | 2.75%   |
| 4267    | 16        | 2.59%   |
| 1867    | 15        | 2.43%   |
| 1334    | 12        | 1.94%   |
| Unknown | 12        | 1.94%   |
| 1066    | 11        | 1.78%   |
| 667     | 9         | 1.46%   |
| 3000    | 8         | 1.29%   |
| 1067    | 8         | 1.29%   |
| 2800    | 6         | 0.97%   |
| 800     | 4         | 0.65%   |
| 3800    | 3         | 0.49%   |
| 3733    | 3         | 0.49%   |
| 3466    | 3         | 0.49%   |
| 3400    | 3         | 0.49%   |
| 3266    | 3         | 0.49%   |
| 333     | 3         | 0.49%   |
| 3533    | 2         | 0.32%   |
| 1866    | 2         | 0.32%   |
| 1800    | 2         | 0.32%   |
| 4266    | 1         | 0.16%   |
| 4199    | 1         | 0.16%   |
| 3866    | 1         | 0.16%   |
| 3666    | 1         | 0.16%   |
| 3100    | 1         | 0.16%   |
| 2933    | 1         | 0.16%   |
| 2666    | 1         | 0.16%   |
| 2134    | 1         | 0.16%   |
| 933     | 1         | 0.16%   |
| 533     | 1         | 0.16%   |
| 400     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 48%     |
| Canon               | 4         | 16%     |
| Brother Industries  | 4         | 16%     |
| Seiko Epson         | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |
| Ricoh               | 1         | 4%      |
| Prolific Technology | 1         | 4%      |
| Dymo-CoStar         | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP OfficeJet 6950                            | 2         | 8%      |
| HP DeskJet 2600 series                       | 2         | 8%      |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 4%      |
| Samsung M2070 Series                         | 1         | 4%      |
| Ricoh SP 212SUw                              | 1         | 4%      |
| Prolific PL2305 Parallel Port                | 1         | 4%      |
| HP Officejet 4500 G510g-m                    | 1         | 4%      |
| HP Neverstop Laser 100x                      | 1         | 4%      |
| HP LaserJet P1006                            | 1         | 4%      |
| HP Ink Tank 310 series                       | 1         | 4%      |
| HP ENVY 5000 series                          | 1         | 4%      |
| HP DeskJet F4100 Printer series              | 1         | 4%      |
| HP Deskjet D2500 series                      | 1         | 4%      |
| HP DeskJet 4530 series                       | 1         | 4%      |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1         | 4%      |
| Canon TR8500 series                          | 1         | 4%      |
| Canon PIXMA MP270 All-In-One Printer         | 1         | 4%      |
| Canon PIXMA MG3000 series                    | 1         | 4%      |
| Canon LiDE 300                               | 1         | 4%      |
| Brother MFC-9330CDW                          | 1         | 4%      |
| Brother MFC-9325CW                           | 1         | 4%      |
| Brother HL-1430 Laser Printer                | 1         | 4%      |
| Brother DCP-7040                             | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 57.14%  |
| Seiko Epson | 3         | 42.86%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 14.29%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 14.29%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 14.29%  |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 14.29%  |
| Canon CanoScan LiDE 70                                  | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                 | 1         | 14.29%  |
| Canon CanoScan 4400F                                    | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 186       | 23.16%  |
| IMC Networks                           | 99        | 12.33%  |
| Microdia                               | 68        | 8.47%   |
| Logitech                               | 56        | 6.97%   |
| Acer                                   | 55        | 6.85%   |
| Realtek Semiconductor                  | 52        | 6.48%   |
| Sunplus Innovation Technology          | 42        | 5.23%   |
| Quanta                                 | 38        | 4.73%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 4.11%   |
| Syntek                                 | 24        | 2.99%   |
| Lite-On Technology                     | 23        | 2.86%   |
| Apple                                  | 21        | 2.62%   |
| Suyin                                  | 13        | 1.62%   |
| Alcor Micro                            | 11        | 1.37%   |
| Microsoft                              | 9         | 1.12%   |
| Samsung Electronics                    | 8         | 1%      |
| Silicon Motion                         | 6         | 0.75%   |
| Z-Star Microelectronics                | 4         | 0.5%    |
| webcam                                 | 4         | 0.5%    |
| Ricoh                                  | 3         | 0.37%   |
| Lenovo                                 | 3         | 0.37%   |
| KYE Systems (Mouse Systems)            | 3         | 0.37%   |
| Jieli Technology                       | 3         | 0.37%   |
| ALi                                    | 3         | 0.37%   |
| Razer USA                              | 2         | 0.25%   |
| Pixart Imaging                         | 2         | 0.25%   |
| Luxvisions Innotech Limited            | 2         | 0.25%   |
| HD WEBCAM                              | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| AVerMedia Technologies                 | 2         | 0.25%   |
| ARC International                      | 2         | 0.25%   |
| Y Media                                | 1         | 0.12%   |
| Xiaomi                                 | 1         | 0.12%   |
| WaveRider Communications               | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Trust                                  | 1         | 0.12%   |
| Sony                                   | 1         | 0.12%   |
| Sonix Technology                       | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |
| Mimaki Engineering                     | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| INOGENI                                | 1         | 0.12%   |
| Importek                               | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |
| Hewlett-Packard                        | 1         | 0.12%   |
| Google                                 | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| DJKANA1RSEYCJF                         | 1         | 0.12%   |
| DigiTech                               | 1         | 0.12%   |
| Denron                                 | 1         | 0.12%   |
| Creative Technology                    | 1         | 0.12%   |
| BUFFALO                                | 1         | 0.12%   |
| Alcorlink                              | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 66        | 8.03%   |
| IMC Networks Integrated Camera                      | 45        | 5.47%   |
| Microdia Integrated_Webcam_HD                       | 33        | 4.01%   |
| Acer Integrated Camera                              | 26        | 3.16%   |
| Realtek Integrated_Webcam_HD                        | 24        | 2.92%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 21        | 2.55%   |
| Syntek Integrated Camera                            | 20        | 2.43%   |
| Sunplus Integrated_Webcam_HD                        | 17        | 2.07%   |
| Logitech Webcam C270                                | 15        | 1.82%   |
| Logitech HD Pro Webcam C920                         | 15        | 1.82%   |
| Chicony HD WebCam                                   | 15        | 1.82%   |
| Lite-On Integrated Camera                           | 12        | 1.46%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 1.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 11        | 1.34%   |
| Chicony HP HD Camera                                | 10        | 1.22%   |
| Apple iPhone 5/5C/5S/6/SE                           | 10        | 1.22%   |
| Samsung Galaxy A5 (MTP)                             | 8         | 0.97%   |
| Chicony USB2.0 Camera                               | 8         | 0.97%   |
| Chicony HP TrueVision HD Camera                     | 8         | 0.97%   |
| Quanta HP TrueVision HD Camera                      | 7         | 0.85%   |
| Microdia Webcam Vitade AF                           | 7         | 0.85%   |
| Logitech HD Webcam C525                             | 7         | 0.85%   |
| Quanta HP HD Camera                                 | 6         | 0.73%   |
| Microdia USB 2.0 Camera                             | 6         | 0.73%   |
| Lite-On HP HD Camera                                | 6         | 0.73%   |
| Chicony HP Wide Vision HD Camera                    | 6         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 6         | 0.73%   |
| Apple FaceTime HD Camera (Built-in)                 | 6         | 0.73%   |
| Acer EasyCamera                                     | 6         | 0.73%   |
| Sunplus HD WebCam                                   | 5         | 0.61%   |
| Quanta HD User Facing                               | 5         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                        | 5         | 0.61%   |
| Chicony FJ Camera                                   | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 0.61%   |
| Acer Lenovo EasyCamera                              | 5         | 0.61%   |
| webcam webcam                                       | 4         | 0.49%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 0.49%   |
| Quanta HD Webcam                                    | 4         | 0.49%   |
| Microsoft LifeCam Cinema                            | 4         | 0.49%   |
| Microdia Integrated Webcam HD                       | 4         | 0.49%   |
| Microdia Integrated Webcam                          | 4         | 0.49%   |
| Chicony HD User Facing                              | 4         | 0.49%   |
| Apple Built-in iSight                               | 4         | 0.49%   |
| Acer BisonCam, NB Pro                               | 4         | 0.49%   |
| Syntek EasyCamera                                   | 3         | 0.36%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.36%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.36%   |
| Realtek Integrated Webcam                           | 3         | 0.36%   |
| Quanta VGA WebCam                                   | 3         | 0.36%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 3         | 0.36%   |
| Logitech Webcam C930e                               | 3         | 0.36%   |
| Logitech Webcam C925e                               | 3         | 0.36%   |
| Logitech Webcam C310                                | 3         | 0.36%   |
| Logitech StreamCam                                  | 3         | 0.36%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 0.36%   |
| Jieli USB PHY 2.0                                   | 3         | 0.36%   |
| IMC Networks USB Camera                             | 3         | 0.36%   |
| Chicony VGA Webcam                                  | 3         | 0.36%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 0.36%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 3         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 77        | 37.56%  |
| Validity Sensors           | 63        | 30.73%  |
| Shenzhen Goodix Technology | 35        | 17.07%  |
| LighTuning Technology      | 9         | 4.39%   |
| Elan Microelectronics      | 8         | 3.9%    |
| Upek                       | 7         | 3.41%   |
| AuthenTec                  | 4         | 1.95%   |
| STMicroelectronics         | 1         | 0.49%   |
| Focal-systems.Corp         | 1         | 0.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 13.17%  |
| Unknown                                                                    | 18        | 8.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 7.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 6.34%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 6.34%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 5.85%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 4.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 3.9%    |
| Elan ELAN:Fingerprint                                                      | 8         | 3.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 3.41%   |
| Synaptics  WBDI                                                            | 7         | 3.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 3.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.93%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 1.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.95%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.46%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.46%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.49%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.49%   |
| Synaptics WBDI Device                                                      | 1         | 0.49%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.49%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.49%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.49%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.49%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 24        | 35.82%  |
| Alcor Micro           | 23        | 34.33%  |
| Upek                  | 4         | 5.97%   |
| Lenovo                | 4         | 5.97%   |
| O2 Micro              | 3         | 4.48%   |
| Realtek Semiconductor | 2         | 2.99%   |
| OmniKey               | 2         | 2.99%   |
| SCM Microsystems      | 1         | 1.49%   |
| Hewlett-Packard       | 1         | 1.49%   |
| Gemalto (was Gemplus) | 1         | 1.49%   |
| Chicony Electronics   | 1         | 1.49%   |
| Cherry                | 1         | 1.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 34.33%  |
| Broadcom 58200                                                               | 8         | 11.94%  |
| Broadcom 5880                                                                | 7         | 10.45%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 7.46%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.97%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 5.97%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.48%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 2.99%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 1.49%   |
| OmniKey CardMan 4321                                                         | 1         | 1.49%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.49%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.49%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.49%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.49%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 818       | 69.2%   |
| 1     | 327       | 27.66%  |
| 2     | 31        | 2.62%   |
| 3     | 4         | 0.34%   |
| 4     | 2         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 204       | 50.75%  |
| Graphics card            | 47        | 11.69%  |
| Multimedia controller    | 45        | 11.19%  |
| Net/wireless             | 42        | 10.45%  |
| Chipcard                 | 11        | 2.74%   |
| Storage                  | 9         | 2.24%   |
| Camera                   | 9         | 2.24%   |
| Bluetooth                | 7         | 1.74%   |
| Unassigned class         | 6         | 1.49%   |
| Communication controller | 6         | 1.49%   |
| Sound                    | 3         | 0.75%   |
| Network                  | 3         | 0.75%   |
| Modem                    | 3         | 0.75%   |
| Card reader              | 3         | 0.75%   |
| Net/ethernet             | 2         | 0.5%    |
| Storage/ata              | 1         | 0.25%   |
| Dvb card                 | 1         | 0.25%   |

