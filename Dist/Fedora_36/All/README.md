Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

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

Total: 2151

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | Notebook    | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [d60b15ea91](https://linux-hardware.org/?probe=d60b15ea91) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f64b9ed3d](https://linux-hardware.org/?probe=9f64b9ed3d) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | Notebook    | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | Notebook    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [41dc234b26](https://linux-hardware.org/?probe=41dc234b26) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | Notebook    | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | Notebook    | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [89253de6f0](https://linux-hardware.org/?probe=89253de6f0) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | Notebook    | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | Notebook    | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | Desktop     | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HP            | 829A                        | Mini pc     | [1e26c7813f](https://linux-hardware.org/?probe=1e26c7813f) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [48d9a713b0](https://linux-hardware.org/?probe=48d9a713b0) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9ff2009089](https://linux-hardware.org/?probe=9ff2009089) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [d644aedbdd](https://linux-hardware.org/?probe=d644aedbdd) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [56c982050d](https://linux-hardware.org/?probe=56c982050d) | Sep 25, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | Notebook    | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| AZW           | SEi                         | Notebook    | [055096f57a](https://linux-hardware.org/?probe=055096f57a) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [e9205da026](https://linux-hardware.org/?probe=e9205da026) | Sep 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [be1d17baa4](https://linux-hardware.org/?probe=be1d17baa4) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [593ef93760](https://linux-hardware.org/?probe=593ef93760) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [307a3c2848](https://linux-hardware.org/?probe=307a3c2848) | Sep 24, 2022 |
| ASRock        | Z170M Extreme4              | Desktop     | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [2bdc1228a1](https://linux-hardware.org/?probe=2bdc1228a1) | Sep 24, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [eef9de3daf](https://linux-hardware.org/?probe=eef9de3daf) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0170bcbb42](https://linux-hardware.org/?probe=0170bcbb42) | Sep 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [08843e7c7c](https://linux-hardware.org/?probe=08843e7c7c) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2bb811e308](https://linux-hardware.org/?probe=2bb811e308) | Sep 23, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | Desktop     | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | Notebook    | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | Notebook    | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [289b9dcac8](https://linux-hardware.org/?probe=289b9dcac8) | Sep 21, 2022 |
| Framework     | Laptop                      | Notebook    | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | Notebook    | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [d5b4924a7b](https://linux-hardware.org/?probe=d5b4924a7b) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [a491827753](https://linux-hardware.org/?probe=a491827753) | Sep 20, 2022 |
| Dell          | Latitude 9420               | Convertible | [e8c592b354](https://linux-hardware.org/?probe=e8c592b354) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | Notebook    | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5b55138f5d](https://linux-hardware.org/?probe=5b55138f5d) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| HP            | ENVY 15                     | Notebook    | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [4ae5282199](https://linux-hardware.org/?probe=4ae5282199) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3f82789198](https://linux-hardware.org/?probe=3f82789198) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [b6ce2720e2](https://linux-hardware.org/?probe=b6ce2720e2) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [8027be6f7e](https://linux-hardware.org/?probe=8027be6f7e) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f8bf8fd596](https://linux-hardware.org/?probe=f8bf8fd596) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8072b6c0e0](https://linux-hardware.org/?probe=8072b6c0e0) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | Desktop     | [1e067b7c4f](https://linux-hardware.org/?probe=1e067b7c4f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | Notebook    | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | Notebook    | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7c52790345](https://linux-hardware.org/?probe=7c52790345) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| ASUSTek       | ROG Flow X16 GV601RE_GV6... | Convertible | [ad99d47a5e](https://linux-hardware.org/?probe=ad99d47a5e) | Sep 19, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [37f0f7b888](https://linux-hardware.org/?probe=37f0f7b888) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| Dell          | Precision 5560              | Notebook    | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| Dell          | Latitude 5420               | Notebook    | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | Notebook    | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | Desktop     | [171e24a5c1](https://linux-hardware.org/?probe=171e24a5c1) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | 84EF 01100                  | All in one  | [2cde64548f](https://linux-hardware.org/?probe=2cde64548f) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | PRIME H410M-K R2.0          | Desktop     | [7d18b85f33](https://linux-hardware.org/?probe=7d18b85f33) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [936ece435c](https://linux-hardware.org/?probe=936ece435c) | Sep 18, 2022 |
| Acer          | A75F2-M2 P21-A1             | Desktop     | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | Notebook    | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0760539d3d](https://linux-hardware.org/?probe=0760539d3d) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f27404a984](https://linux-hardware.org/?probe=f27404a984) | Sep 18, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1c3c64ca91](https://linux-hardware.org/?probe=1c3c64ca91) | Sep 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [fbeb9df498](https://linux-hardware.org/?probe=fbeb9df498) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5a541fecce](https://linux-hardware.org/?probe=5a541fecce) | Sep 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [88481ce853](https://linux-hardware.org/?probe=88481ce853) | Sep 16, 2022 |
| Dell          | G3 3779                     | Notebook    | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | Notebook    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | Notebook    | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [881adad6fb](https://linux-hardware.org/?probe=881adad6fb) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | Notebook    | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [55216d250b](https://linux-hardware.org/?probe=55216d250b) | Sep 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fb9010fc1f](https://linux-hardware.org/?probe=fb9010fc1f) | Sep 14, 2022 |
| HP            | 805D                        | Desktop     | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [23c756841a](https://linux-hardware.org/?probe=23c756841a) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | Notebook    | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [175c84f6ea](https://linux-hardware.org/?probe=175c84f6ea) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9b2a84cd02](https://linux-hardware.org/?probe=9b2a84cd02) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1285ab4d66](https://linux-hardware.org/?probe=1285ab4d66) | Sep 13, 2022 |
| Dell          | Precision 5560              | Notebook    | [78809c82c2](https://linux-hardware.org/?probe=78809c82c2) | Sep 13, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [4e73a1af5e](https://linux-hardware.org/?probe=4e73a1af5e) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | Desktop     | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [e040958337](https://linux-hardware.org/?probe=e040958337) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lanix         | AL V9                       | Notebook    | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Dell          | Latitude 5495               | Notebook    | [23586ab4ef](https://linux-hardware.org/?probe=23586ab4ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad P1 20MD0014RT      | Notebook    | [4935debbce](https://linux-hardware.org/?probe=4935debbce) | Sep 12, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [e956067fa0](https://linux-hardware.org/?probe=e956067fa0) | Sep 12, 2022 |
| AZW           | SEi                         | Notebook    | [3a4d2086b0](https://linux-hardware.org/?probe=3a4d2086b0) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [5bbf96fe23](https://linux-hardware.org/?probe=5bbf96fe23) | Sep 12, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [1f32b65385](https://linux-hardware.org/?probe=1f32b65385) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [d05595b19e](https://linux-hardware.org/?probe=d05595b19e) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| HP            | 1494                        | Desktop     | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [edb2842417](https://linux-hardware.org/?probe=edb2842417) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [c6df51fa3b](https://linux-hardware.org/?probe=c6df51fa3b) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [a3b824ba41](https://linux-hardware.org/?probe=a3b824ba41) | Sep 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [66c2198f48](https://linux-hardware.org/?probe=66c2198f48) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [998630e822](https://linux-hardware.org/?probe=998630e822) | Sep 10, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [5e145ec2d1](https://linux-hardware.org/?probe=5e145ec2d1) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [8fb4287325](https://linux-hardware.org/?probe=8fb4287325) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [03979fc286](https://linux-hardware.org/?probe=03979fc286) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [0a7b65b735](https://linux-hardware.org/?probe=0a7b65b735) | Sep 09, 2022 |
| HP            | Elite x2 1013 G3            | Tablet      | [a7b40883c3](https://linux-hardware.org/?probe=a7b40883c3) | Sep 09, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [7fc528e246](https://linux-hardware.org/?probe=7fc528e246) | Sep 09, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [a54dae9e4b](https://linux-hardware.org/?probe=a54dae9e4b) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2534b22e](https://linux-hardware.org/?probe=9f2534b22e) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c6dac06569](https://linux-hardware.org/?probe=c6dac06569) | Sep 09, 2022 |
| Notebook      | W230SS                      | Notebook    | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [e43ef549eb](https://linux-hardware.org/?probe=e43ef549eb) | Sep 08, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ac6cb859ad](https://linux-hardware.org/?probe=ac6cb859ad) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | Desktop     | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [daf3e0182b](https://linux-hardware.org/?probe=daf3e0182b) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8242cc3cab](https://linux-hardware.org/?probe=8242cc3cab) | Sep 08, 2022 |
| HP            | 18E4                        | Desktop     | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [0f0a18c852](https://linux-hardware.org/?probe=0f0a18c852) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e06271e233](https://linux-hardware.org/?probe=e06271e233) | Sep 08, 2022 |
| Dell          | Latitude E5450              | Notebook    | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [bcf93bb718](https://linux-hardware.org/?probe=bcf93bb718) | Sep 08, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [0bcf279fb8](https://linux-hardware.org/?probe=0bcf279fb8) | Sep 08, 2022 |
| Dell          | Precision 5770              | Notebook    | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [2395ab5aed](https://linux-hardware.org/?probe=2395ab5aed) | Sep 07, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [fb4bfcf055](https://linux-hardware.org/?probe=fb4bfcf055) | Sep 07, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [f91eeba2bd](https://linux-hardware.org/?probe=f91eeba2bd) | Sep 07, 2022 |
| ASRock        | EP2C602                     | Desktop     | [56a6980ddc](https://linux-hardware.org/?probe=56a6980ddc) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [8885f409d8](https://linux-hardware.org/?probe=8885f409d8) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a90b385c8e](https://linux-hardware.org/?probe=a90b385c8e) | Sep 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [42b1a82f1d](https://linux-hardware.org/?probe=42b1a82f1d) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [7a3494a230](https://linux-hardware.org/?probe=7a3494a230) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e7d57afa70](https://linux-hardware.org/?probe=e7d57afa70) | Sep 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [240ace226f](https://linux-hardware.org/?probe=240ace226f) | Sep 06, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [826deb0c55](https://linux-hardware.org/?probe=826deb0c55) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [bffe658238](https://linux-hardware.org/?probe=bffe658238) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b327372b50](https://linux-hardware.org/?probe=b327372b50) | Sep 05, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [3969240177](https://linux-hardware.org/?probe=3969240177) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [962cc1e746](https://linux-hardware.org/?probe=962cc1e746) | Sep 05, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [d38282759b](https://linux-hardware.org/?probe=d38282759b) | Sep 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [e590a83122](https://linux-hardware.org/?probe=e590a83122) | Sep 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Dell          | Latitude 5511               | Notebook    | [3193c29c67](https://linux-hardware.org/?probe=3193c29c67) | Sep 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [b4a71c0eff](https://linux-hardware.org/?probe=b4a71c0eff) | Sep 04, 2022 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [57f8a4e96b](https://linux-hardware.org/?probe=57f8a4e96b) | Sep 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [f0bcadac2f](https://linux-hardware.org/?probe=f0bcadac2f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 2320HPU       | Notebook    | [a8ba64ec12](https://linux-hardware.org/?probe=a8ba64ec12) | Sep 04, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [cc383de755](https://linux-hardware.org/?probe=cc383de755) | Sep 04, 2022 |
| Lenovo        | ThinkPad E560 20EV000RGE    | Notebook    | [5b69ce9986](https://linux-hardware.org/?probe=5b69ce9986) | Sep 04, 2022 |
| Acer          | AS VN7-571G                 | Notebook    | [1c14fbaf96](https://linux-hardware.org/?probe=1c14fbaf96) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | Desktop     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [7bb2d68f03](https://linux-hardware.org/?probe=7bb2d68f03) | Sep 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [b236b791c1](https://linux-hardware.org/?probe=b236b791c1) | Sep 04, 2022 |
| Lenovo        | 3000 N200 0769BAG           | Notebook    | [33fcb3e2b3](https://linux-hardware.org/?probe=33fcb3e2b3) | Sep 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c4db289b99](https://linux-hardware.org/?probe=c4db289b99) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [5b0da32c82](https://linux-hardware.org/?probe=5b0da32c82) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [dc3fd2d992](https://linux-hardware.org/?probe=dc3fd2d992) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [16c497325e](https://linux-hardware.org/?probe=16c497325e) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Dell          | Vostro 1320                 | Notebook    | [e66853cc37](https://linux-hardware.org/?probe=e66853cc37) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [ed392e6b79](https://linux-hardware.org/?probe=ed392e6b79) | Sep 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8208ccf8f6](https://linux-hardware.org/?probe=8208ccf8f6) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| ASUSTek       | GL503VM                     | Notebook    | [43cbef1764](https://linux-hardware.org/?probe=43cbef1764) | Sep 03, 2022 |
| MSI           | GP72MVR 7RFX                | Notebook    | [f370d7bbc3](https://linux-hardware.org/?probe=f370d7bbc3) | Sep 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f37e7a618](https://linux-hardware.org/?probe=5f37e7a618) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b73e153667](https://linux-hardware.org/?probe=b73e153667) | Sep 03, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [d6c9e33a55](https://linux-hardware.org/?probe=d6c9e33a55) | Sep 03, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [92d3e81be7](https://linux-hardware.org/?probe=92d3e81be7) | Sep 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [cec0b91aa9](https://linux-hardware.org/?probe=cec0b91aa9) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | Desktop     | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d9d6af9350](https://linux-hardware.org/?probe=d9d6af9350) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001JIX     | Notebook    | [30eb9dcb39](https://linux-hardware.org/?probe=30eb9dcb39) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| Alienware     | 14                          | Notebook    | [f30f3ddf3d](https://linux-hardware.org/?probe=f30f3ddf3d) | Sep 03, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [f1ca159a19](https://linux-hardware.org/?probe=f1ca159a19) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [33ae7d4c4b](https://linux-hardware.org/?probe=33ae7d4c4b) | Sep 03, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [b49d726ab0](https://linux-hardware.org/?probe=b49d726ab0) | Sep 03, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [ee80be714e](https://linux-hardware.org/?probe=ee80be714e) | Sep 03, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [634777751a](https://linux-hardware.org/?probe=634777751a) | Sep 02, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [006c26eaa0](https://linux-hardware.org/?probe=006c26eaa0) | Sep 02, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [dd250df1ef](https://linux-hardware.org/?probe=dd250df1ef) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a8e1884f32](https://linux-hardware.org/?probe=a8e1884f32) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| Acer          | Aspire M3910                | Desktop     | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [203baa4d7f](https://linux-hardware.org/?probe=203baa4d7f) | Sep 02, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c781ec4733](https://linux-hardware.org/?probe=c781ec4733) | Sep 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1ac18273da](https://linux-hardware.org/?probe=1ac18273da) | Sep 02, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0e3f950f3f](https://linux-hardware.org/?probe=0e3f950f3f) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [969ebd4d3a](https://linux-hardware.org/?probe=969ebd4d3a) | Sep 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| Dell          | 0MWYPT A02                  | Desktop     | [e2f98387b0](https://linux-hardware.org/?probe=e2f98387b0) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [b6b7c6dc62](https://linux-hardware.org/?probe=b6b7c6dc62) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [6b3c188071](https://linux-hardware.org/?probe=6b3c188071) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [b0d6660da8](https://linux-hardware.org/?probe=b0d6660da8) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [c5547cac7c](https://linux-hardware.org/?probe=c5547cac7c) | Aug 31, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| Dell          | Latitude 7430               | Notebook    | [8876fb0448](https://linux-hardware.org/?probe=8876fb0448) | Aug 31, 2022 |
| Eluktronic... | MAG-15 2070                 | Notebook    | [d7fb373622](https://linux-hardware.org/?probe=d7fb373622) | Aug 31, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [e5c7462ead](https://linux-hardware.org/?probe=e5c7462ead) | Aug 31, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [36eb80672f](https://linux-hardware.org/?probe=36eb80672f) | Aug 31, 2022 |
| Dell          | Latitude E5570              | Notebook    | [91513d0ee3](https://linux-hardware.org/?probe=91513d0ee3) | Aug 31, 2022 |
| Dell          | 0KV3RP A00                  | Desktop     | [731a14ee10](https://linux-hardware.org/?probe=731a14ee10) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [b9d306c31b](https://linux-hardware.org/?probe=b9d306c31b) | Aug 31, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2c72dfccbb](https://linux-hardware.org/?probe=2c72dfccbb) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [26d60edae6](https://linux-hardware.org/?probe=26d60edae6) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [05c3d5d7b7](https://linux-hardware.org/?probe=05c3d5d7b7) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| Dell          | G3 3579                     | Notebook    | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| HP            | 8464                        | Desktop     | [16bb2588e0](https://linux-hardware.org/?probe=16bb2588e0) | Aug 30, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [96a56c7cb9](https://linux-hardware.org/?probe=96a56c7cb9) | Aug 30, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [346eda373e](https://linux-hardware.org/?probe=346eda373e) | Aug 29, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [ecdb2875da](https://linux-hardware.org/?probe=ecdb2875da) | Aug 29, 2022 |
| Dell          | Inspiron 5721               | Notebook    | [d483434965](https://linux-hardware.org/?probe=d483434965) | Aug 29, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [473daa5ce3](https://linux-hardware.org/?probe=473daa5ce3) | Aug 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e19d574682](https://linux-hardware.org/?probe=e19d574682) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| MSI           | Prestige 14Evo A11MO        | Notebook    | [22cf60f50b](https://linux-hardware.org/?probe=22cf60f50b) | Aug 29, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [14f4c7e248](https://linux-hardware.org/?probe=14f4c7e248) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9fbdc83458](https://linux-hardware.org/?probe=9fbdc83458) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7b0113a203](https://linux-hardware.org/?probe=7b0113a203) | Aug 29, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [f921aef61e](https://linux-hardware.org/?probe=f921aef61e) | Aug 29, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [cf0cdab1da](https://linux-hardware.org/?probe=cf0cdab1da) | Aug 29, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [60bc287a81](https://linux-hardware.org/?probe=60bc287a81) | Aug 29, 2022 |
| HP            | 8751                        | Desktop     | [62c8c2f25e](https://linux-hardware.org/?probe=62c8c2f25e) | Aug 29, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [7d1dae1de6](https://linux-hardware.org/?probe=7d1dae1de6) | Aug 29, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [302c3f11ec](https://linux-hardware.org/?probe=302c3f11ec) | Aug 29, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [d82227c6d3](https://linux-hardware.org/?probe=d82227c6d3) | Aug 29, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [1d1864dabc](https://linux-hardware.org/?probe=1d1864dabc) | Aug 29, 2022 |
| Dell          | Precision 5750              | Notebook    | [2ee41b471e](https://linux-hardware.org/?probe=2ee41b471e) | Aug 28, 2022 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [ecaac234f3](https://linux-hardware.org/?probe=ecaac234f3) | Aug 28, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Google        | Eve                         | Notebook    | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Dell          | Precision 5750              | Notebook    | [af9992756f](https://linux-hardware.org/?probe=af9992756f) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [589154a65e](https://linux-hardware.org/?probe=589154a65e) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [505d987d1e](https://linux-hardware.org/?probe=505d987d1e) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [af00be0ff8](https://linux-hardware.org/?probe=af00be0ff8) | Aug 28, 2022 |
| Quanta        | 2AC5 101                    | All in one  | [b32f35a4b1](https://linux-hardware.org/?probe=b32f35a4b1) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [dc431e4826](https://linux-hardware.org/?probe=dc431e4826) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [5efa863ca3](https://linux-hardware.org/?probe=5efa863ca3) | Aug 28, 2022 |
| Chuwi         | UBook X                     | Tablet      | [27c118eaf1](https://linux-hardware.org/?probe=27c118eaf1) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [64cefbec58](https://linux-hardware.org/?probe=64cefbec58) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [3de4d575a9](https://linux-hardware.org/?probe=3de4d575a9) | Aug 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Acidanther... | MacBookPro12,1              | Notebook    | [9e48c5e245](https://linux-hardware.org/?probe=9e48c5e245) | Aug 27, 2022 |
| HP            | 805D                        | Desktop     | [419598ebba](https://linux-hardware.org/?probe=419598ebba) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [559d6f0e42](https://linux-hardware.org/?probe=559d6f0e42) | Aug 27, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [f4dd9de519](https://linux-hardware.org/?probe=f4dd9de519) | Aug 27, 2022 |
| HP            | Spectre Folio Convertibl... | Convertible | [1bf525d79a](https://linux-hardware.org/?probe=1bf525d79a) | Aug 27, 2022 |
| Acer          | One S1003                   | Tablet      | [0d0621c875](https://linux-hardware.org/?probe=0d0621c875) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [be9921e0e0](https://linux-hardware.org/?probe=be9921e0e0) | Aug 27, 2022 |
| Acer          | One S1003                   | Tablet      | [14016e8e79](https://linux-hardware.org/?probe=14016e8e79) | Aug 27, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [7bd19ce9a1](https://linux-hardware.org/?probe=7bd19ce9a1) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Exo           | Smart Serie L               | Notebook    | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [9fe64d4a60](https://linux-hardware.org/?probe=9fe64d4a60) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| HP            | ProBook 4530s               | Notebook    | [be1270c998](https://linux-hardware.org/?probe=be1270c998) | Aug 26, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [fa74c338ed](https://linux-hardware.org/?probe=fa74c338ed) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Dell          | 0KV3RP A00                  | Desktop     | [f73bf383ce](https://linux-hardware.org/?probe=f73bf383ce) | Aug 26, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [a55342c2f7](https://linux-hardware.org/?probe=a55342c2f7) | Aug 26, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [aa28bc2c61](https://linux-hardware.org/?probe=aa28bc2c61) | Aug 26, 2022 |
| Dell          | Latitude 5175               | Tablet      | [c751321ab1](https://linux-hardware.org/?probe=c751321ab1) | Aug 26, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [f1c16cf6e7](https://linux-hardware.org/?probe=f1c16cf6e7) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [dd68273352](https://linux-hardware.org/?probe=dd68273352) | Aug 26, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [c3ae4b86ac](https://linux-hardware.org/?probe=c3ae4b86ac) | Aug 26, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [e69218ea58](https://linux-hardware.org/?probe=e69218ea58) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [af216b7b4a](https://linux-hardware.org/?probe=af216b7b4a) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | UN62                        | Desktop     | [49fcd1324f](https://linux-hardware.org/?probe=49fcd1324f) | Aug 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [2b52864870](https://linux-hardware.org/?probe=2b52864870) | Aug 25, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [69fd53a234](https://linux-hardware.org/?probe=69fd53a234) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [47dc749c6c](https://linux-hardware.org/?probe=47dc749c6c) | Aug 25, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [9a362ed844](https://linux-hardware.org/?probe=9a362ed844) | Aug 25, 2022 |
| Dell          | 0PU052                      | Desktop     | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [7fd7791035](https://linux-hardware.org/?probe=7fd7791035) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f8213e35a4](https://linux-hardware.org/?probe=f8213e35a4) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ae4a81a473](https://linux-hardware.org/?probe=ae4a81a473) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [f9090c46a9](https://linux-hardware.org/?probe=f9090c46a9) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [ac93dd480f](https://linux-hardware.org/?probe=ac93dd480f) | Aug 24, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [f2bc1e0fae](https://linux-hardware.org/?probe=f2bc1e0fae) | Aug 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [199e70a85c](https://linux-hardware.org/?probe=199e70a85c) | Aug 23, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [0b1e1d125d](https://linux-hardware.org/?probe=0b1e1d125d) | Aug 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cc66ac722b](https://linux-hardware.org/?probe=cc66ac722b) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [704cec73e1](https://linux-hardware.org/?probe=704cec73e1) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [2e88f854f8](https://linux-hardware.org/?probe=2e88f854f8) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b0af95356c](https://linux-hardware.org/?probe=b0af95356c) | Aug 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bc32a93168](https://linux-hardware.org/?probe=bc32a93168) | Aug 22, 2022 |
| Dell          | XPS L421X                   | Notebook    | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [1b2c235511](https://linux-hardware.org/?probe=1b2c235511) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [c563f4b965](https://linux-hardware.org/?probe=c563f4b965) | Aug 22, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [eb81df27ce](https://linux-hardware.org/?probe=eb81df27ce) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [991487a61b](https://linux-hardware.org/?probe=991487a61b) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e404ccb462](https://linux-hardware.org/?probe=e404ccb462) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f25926e1fa](https://linux-hardware.org/?probe=f25926e1fa) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [784c6d89a6](https://linux-hardware.org/?probe=784c6d89a6) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [9856ca2463](https://linux-hardware.org/?probe=9856ca2463) | Aug 21, 2022 |
| Acer          | TravelMate P215-52G         | Notebook    | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| HP            | Compaq 15                   | Notebook    | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [f4f0162d9a](https://linux-hardware.org/?probe=f4f0162d9a) | Aug 21, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5f90bb65a6](https://linux-hardware.org/?probe=5f90bb65a6) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| Acer          | Popcorn                     | Notebook    | [1c3d0d6b87](https://linux-hardware.org/?probe=1c3d0d6b87) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | Notebook    | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [47b1480e61](https://linux-hardware.org/?probe=47b1480e61) | Aug 20, 2022 |
| HP            | ENVY Notebook               | Notebook    | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [b2ac87cffc](https://linux-hardware.org/?probe=b2ac87cffc) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c3e335499f](https://linux-hardware.org/?probe=c3e335499f) | Aug 20, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [1fdf41de8b](https://linux-hardware.org/?probe=1fdf41de8b) | Aug 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [fd0604d0fb](https://linux-hardware.org/?probe=fd0604d0fb) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | Notebook    | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | Notebook    | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| HP            | ProBook 655 G1              | Notebook    | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [20c406b9b0](https://linux-hardware.org/?probe=20c406b9b0) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [b745244bb7](https://linux-hardware.org/?probe=b745244bb7) | Aug 19, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [ce8c93b28f](https://linux-hardware.org/?probe=ce8c93b28f) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK UH552              | Notebook    | [ad8ec93f74](https://linux-hardware.org/?probe=ad8ec93f74) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [c7f7373ed5](https://linux-hardware.org/?probe=c7f7373ed5) | Aug 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [ed013e82aa](https://linux-hardware.org/?probe=ed013e82aa) | Aug 19, 2022 |
| HUAWEI        | EMD-WXX                     | Notebook    | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [81be616c6b](https://linux-hardware.org/?probe=81be616c6b) | Aug 19, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| ASUSTek       | K45A                        | Notebook    | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| Acidanther... | MacBookPro12,1              | Notebook    | [6afa5c842e](https://linux-hardware.org/?probe=6afa5c842e) | Aug 18, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8fc237babf](https://linux-hardware.org/?probe=8fc237babf) | Aug 17, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | Notebook    | [cfc3d5853c](https://linux-hardware.org/?probe=cfc3d5853c) | Aug 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e73d7ae317](https://linux-hardware.org/?probe=e73d7ae317) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| ASUSTek       | K45A                        | Notebook    | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8aea7a68ee](https://linux-hardware.org/?probe=8aea7a68ee) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [9defe532c0](https://linux-hardware.org/?probe=9defe532c0) | Aug 17, 2022 |
| MSI           | Modern 14 B11SBL            | Notebook    | [ad56f2a352](https://linux-hardware.org/?probe=ad56f2a352) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | Notebook    | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [b0aec6f095](https://linux-hardware.org/?probe=b0aec6f095) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [0793e37f62](https://linux-hardware.org/?probe=0793e37f62) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [8b591b08b0](https://linux-hardware.org/?probe=8b591b08b0) | Aug 16, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [fbeff3bff5](https://linux-hardware.org/?probe=fbeff3bff5) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [59db95ffee](https://linux-hardware.org/?probe=59db95ffee) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [2b63761318](https://linux-hardware.org/?probe=2b63761318) | Aug 16, 2022 |
| Lenovo        | ThinkBook Plus 20TG         | Notebook    | [1f39fbc5a8](https://linux-hardware.org/?probe=1f39fbc5a8) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [97ff4c0078](https://linux-hardware.org/?probe=97ff4c0078) | Aug 16, 2022 |
| Panasonic     | CFMX4-1                     | Notebook    | [01074aea14](https://linux-hardware.org/?probe=01074aea14) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [22194522c7](https://linux-hardware.org/?probe=22194522c7) | Aug 15, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [d9f8a6ea69](https://linux-hardware.org/?probe=d9f8a6ea69) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [bbbda98d21](https://linux-hardware.org/?probe=bbbda98d21) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | Notebook    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [4f73fd7cf8](https://linux-hardware.org/?probe=4f73fd7cf8) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | Notebook    | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [e09e349f03](https://linux-hardware.org/?probe=e09e349f03) | Aug 15, 2022 |
| Sony          | VPCS131FM                   | Notebook    | [22e32938e6](https://linux-hardware.org/?probe=22e32938e6) | Aug 14, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3decfcd64a](https://linux-hardware.org/?probe=3decfcd64a) | Aug 14, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [24b804043b](https://linux-hardware.org/?probe=24b804043b) | Aug 14, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [ad3ad84c75](https://linux-hardware.org/?probe=ad3ad84c75) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [a44a9b065b](https://linux-hardware.org/?probe=a44a9b065b) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Dell          | Inspiron 13 5320            | Notebook    | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [83abda5bc9](https://linux-hardware.org/?probe=83abda5bc9) | Aug 14, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [dbf529a586](https://linux-hardware.org/?probe=dbf529a586) | Aug 14, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [ca9974d27e](https://linux-hardware.org/?probe=ca9974d27e) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| HP            | 14                          | Notebook    | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [6a0c6ab778](https://linux-hardware.org/?probe=6a0c6ab778) | Aug 13, 2022 |
| Dell          | G3 3590                     | Notebook    | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [4983efddbb](https://linux-hardware.org/?probe=4983efddbb) | Aug 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [e1f4ef0670](https://linux-hardware.org/?probe=e1f4ef0670) | Aug 12, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [3cb2744dbe](https://linux-hardware.org/?probe=3cb2744dbe) | Aug 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [e7c81a6ce7](https://linux-hardware.org/?probe=e7c81a6ce7) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6a8f06be23](https://linux-hardware.org/?probe=6a8f06be23) | Aug 12, 2022 |
| HP            | 8183                        | Desktop     | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [ee57cf772f](https://linux-hardware.org/?probe=ee57cf772f) | Aug 12, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3d93d807ca](https://linux-hardware.org/?probe=3d93d807ca) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| MSI           | MS-16F1                     | Notebook    | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | Pavilion 17                 | Notebook    | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Sony          | SVT15115CXS                 | Notebook    | [f7915ecf99](https://linux-hardware.org/?probe=f7915ecf99) | Aug 12, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c39429aed6](https://linux-hardware.org/?probe=c39429aed6) | Aug 11, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [5f25d77994](https://linux-hardware.org/?probe=5f25d77994) | Aug 11, 2022 |
| HP            | 8183                        | Desktop     | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [0790b09ae3](https://linux-hardware.org/?probe=0790b09ae3) | Aug 11, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [43b4579869](https://linux-hardware.org/?probe=43b4579869) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Acer          | Predator PH317-53           | Notebook    | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [05042a439b](https://linux-hardware.org/?probe=05042a439b) | Aug 11, 2022 |
| AZW           | SEi                         | Notebook    | [fb26f11a19](https://linux-hardware.org/?probe=fb26f11a19) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [149d92cd3e](https://linux-hardware.org/?probe=149d92cd3e) | Aug 10, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [064c009010](https://linux-hardware.org/?probe=064c009010) | Aug 10, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c788f4d7a8](https://linux-hardware.org/?probe=c788f4d7a8) | Aug 10, 2022 |
| Lenovo        | 3307 SDK0J40700 WIN 3258... | Mini pc     | [5dde7d8c6b](https://linux-hardware.org/?probe=5dde7d8c6b) | Aug 10, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [2378dda760](https://linux-hardware.org/?probe=2378dda760) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [962a39b2c3](https://linux-hardware.org/?probe=962a39b2c3) | Aug 10, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [a24161deaa](https://linux-hardware.org/?probe=a24161deaa) | Aug 10, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [d586bdd82d](https://linux-hardware.org/?probe=d586bdd82d) | Aug 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [18f9226bc0](https://linux-hardware.org/?probe=18f9226bc0) | Aug 09, 2022 |
| Timi          | TM1701                      | Notebook    | [676fc52004](https://linux-hardware.org/?probe=676fc52004) | Aug 09, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f64a4de8a6](https://linux-hardware.org/?probe=f64a4de8a6) | Aug 09, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8558001fa2](https://linux-hardware.org/?probe=8558001fa2) | Aug 09, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [9471547f71](https://linux-hardware.org/?probe=9471547f71) | Aug 09, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1a95dd7974](https://linux-hardware.org/?probe=1a95dd7974) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [21fadb20ca](https://linux-hardware.org/?probe=21fadb20ca) | Aug 09, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [093a936372](https://linux-hardware.org/?probe=093a936372) | Aug 08, 2022 |
| Dell          | Precision 5510              | Notebook    | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [b421a8c6c4](https://linux-hardware.org/?probe=b421a8c6c4) | Aug 08, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [07c89bcbc6](https://linux-hardware.org/?probe=07c89bcbc6) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f08a60d37c](https://linux-hardware.org/?probe=f08a60d37c) | Aug 07, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [b9f6292104](https://linux-hardware.org/?probe=b9f6292104) | Aug 07, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | Notebook    | [30a447f95c](https://linux-hardware.org/?probe=30a447f95c) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [a823925843](https://linux-hardware.org/?probe=a823925843) | Aug 07, 2022 |
| Alienware     | x17 R2                      | Notebook    | [4e7fe87198](https://linux-hardware.org/?probe=4e7fe87198) | Aug 07, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [bc1daa0005](https://linux-hardware.org/?probe=bc1daa0005) | Aug 07, 2022 |
| HP            | 1587h                       | Desktop     | [d9d1b6832f](https://linux-hardware.org/?probe=d9d1b6832f) | Aug 07, 2022 |
| HP            | 1587h                       | Desktop     | [737b509512](https://linux-hardware.org/?probe=737b509512) | Aug 07, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [9d837de022](https://linux-hardware.org/?probe=9d837de022) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [438f5cce2a](https://linux-hardware.org/?probe=438f5cce2a) | Aug 07, 2022 |
| Toshiba       | Satellite Pro L300D         | Notebook    | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [31c87abaf3](https://linux-hardware.org/?probe=31c87abaf3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [572cb48d3c](https://linux-hardware.org/?probe=572cb48d3c) | Aug 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [a1caede3ea](https://linux-hardware.org/?probe=a1caede3ea) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [4f10e80880](https://linux-hardware.org/?probe=4f10e80880) | Aug 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8f7a78b973](https://linux-hardware.org/?probe=8f7a78b973) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [2eb53b5701](https://linux-hardware.org/?probe=2eb53b5701) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [36e148426c](https://linux-hardware.org/?probe=36e148426c) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [28ec23aa22](https://linux-hardware.org/?probe=28ec23aa22) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0b1216cb50](https://linux-hardware.org/?probe=0b1216cb50) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [c87812a2ae](https://linux-hardware.org/?probe=c87812a2ae) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| ASRock        | B460M Pro4S/ac              | Desktop     | [79f01ebf66](https://linux-hardware.org/?probe=79f01ebf66) | Aug 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aee6d50427](https://linux-hardware.org/?probe=aee6d50427) | Aug 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Spin SP513-51               | Convertible | [7531ebdab5](https://linux-hardware.org/?probe=7531ebdab5) | Aug 05, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [7867c6d24c](https://linux-hardware.org/?probe=7867c6d24c) | Aug 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cff355ec5f](https://linux-hardware.org/?probe=cff355ec5f) | Aug 05, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [eae703cf6f](https://linux-hardware.org/?probe=eae703cf6f) | Aug 05, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [6c5e2de730](https://linux-hardware.org/?probe=6c5e2de730) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [d59939b336](https://linux-hardware.org/?probe=d59939b336) | Aug 05, 2022 |
| Acer          | Aspire V3-572               | Notebook    | [dadff5cef8](https://linux-hardware.org/?probe=dadff5cef8) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| Gateway       | NE56R                       | Notebook    | [44de22f108](https://linux-hardware.org/?probe=44de22f108) | Aug 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [ec2efe1636](https://linux-hardware.org/?probe=ec2efe1636) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c6e5356615](https://linux-hardware.org/?probe=c6e5356615) | Aug 04, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [503200514f](https://linux-hardware.org/?probe=503200514f) | Aug 04, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [f8a0b1d6e6](https://linux-hardware.org/?probe=f8a0b1d6e6) | Aug 04, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [7c41cd3006](https://linux-hardware.org/?probe=7c41cd3006) | Aug 04, 2022 |
| HP            | Snappy                      | Notebook    | [d5e91bd56c](https://linux-hardware.org/?probe=d5e91bd56c) | Aug 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d31b834cdf](https://linux-hardware.org/?probe=d31b834cdf) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [df01e617f2](https://linux-hardware.org/?probe=df01e617f2) | Aug 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6e77095fb6](https://linux-hardware.org/?probe=6e77095fb6) | Aug 03, 2022 |
| Gateway       | NV55C                       | Notebook    | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| HP            | Snappy                      | Notebook    | [0a73175862](https://linux-hardware.org/?probe=0a73175862) | Aug 03, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [711cf515aa](https://linux-hardware.org/?probe=711cf515aa) | Aug 03, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [32bda73b5e](https://linux-hardware.org/?probe=32bda73b5e) | Aug 03, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [4678a0f755](https://linux-hardware.org/?probe=4678a0f755) | Aug 03, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 4290KJ6       | Notebook    | [ef5ee2a01e](https://linux-hardware.org/?probe=ef5ee2a01e) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [492d014205](https://linux-hardware.org/?probe=492d014205) | Aug 02, 2022 |
| HP            | 8767 A                      | Desktop     | [3679ccede7](https://linux-hardware.org/?probe=3679ccede7) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [b570321ffa](https://linux-hardware.org/?probe=b570321ffa) | Aug 02, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | Notebook    | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | ProBook 4540s               | Notebook    | [c96c493e64](https://linux-hardware.org/?probe=c96c493e64) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| Dell          | Inspiron 7386               | Convertible | [d29be38cd9](https://linux-hardware.org/?probe=d29be38cd9) | Aug 02, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [b321cd29a8](https://linux-hardware.org/?probe=b321cd29a8) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Dell          | Precision 5530              | Notebook    | [a5177f0edb](https://linux-hardware.org/?probe=a5177f0edb) | Aug 02, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [4bd0f9e461](https://linux-hardware.org/?probe=4bd0f9e461) | Aug 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [37b8171416](https://linux-hardware.org/?probe=37b8171416) | Aug 01, 2022 |
| MSI           | H81M-E34                    | Desktop     | [c0be356e96](https://linux-hardware.org/?probe=c0be356e96) | Aug 01, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3a496f366f](https://linux-hardware.org/?probe=3a496f366f) | Aug 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| Dell          | Latitude D620               | Notebook    | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [827883d38c](https://linux-hardware.org/?probe=827883d38c) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [7a0035ad18](https://linux-hardware.org/?probe=7a0035ad18) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d8bfe4a00b](https://linux-hardware.org/?probe=d8bfe4a00b) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0f72d43717](https://linux-hardware.org/?probe=0f72d43717) | Jul 31, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6699e8b6ea](https://linux-hardware.org/?probe=6699e8b6ea) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [f43e0c2c81](https://linux-hardware.org/?probe=f43e0c2c81) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [85208906cd](https://linux-hardware.org/?probe=85208906cd) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [ec939adba9](https://linux-hardware.org/?probe=ec939adba9) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81MD     | Tablet      | [d21006410b](https://linux-hardware.org/?probe=d21006410b) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | M4A77TD                     | Desktop     | [f10ef09086](https://linux-hardware.org/?probe=f10ef09086) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ebe9fe3b1a](https://linux-hardware.org/?probe=ebe9fe3b1a) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [cd5aa49da7](https://linux-hardware.org/?probe=cd5aa49da7) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | Notebook    | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [e4dfdaf9a0](https://linux-hardware.org/?probe=e4dfdaf9a0) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [25d688e258](https://linux-hardware.org/?probe=25d688e258) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [93caf82d7a](https://linux-hardware.org/?probe=93caf82d7a) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [87d143ab3d](https://linux-hardware.org/?probe=87d143ab3d) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | Notebook    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [256172b01e](https://linux-hardware.org/?probe=256172b01e) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| HP            | 348 G4                      | Notebook    | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [ba8e73bd09](https://linux-hardware.org/?probe=ba8e73bd09) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [066e5eb95d](https://linux-hardware.org/?probe=066e5eb95d) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [af4d396115](https://linux-hardware.org/?probe=af4d396115) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| HP            | 1494                        | Desktop     | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [2816cacd1b](https://linux-hardware.org/?probe=2816cacd1b) | Jul 27, 2022 |
| Clevo         | M570TU                      | Notebook    | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [2773e9510b](https://linux-hardware.org/?probe=2773e9510b) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [015e810904](https://linux-hardware.org/?probe=015e810904) | Jul 26, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d63a6f2607](https://linux-hardware.org/?probe=d63a6f2607) | Jul 26, 2022 |
| HP            | Notebook                    | Notebook    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| ASRock        | Z690 PG Riptide             | Desktop     | [87c499b088](https://linux-hardware.org/?probe=87c499b088) | Jul 26, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [4a49386ad2](https://linux-hardware.org/?probe=4a49386ad2) | Jul 26, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [8194e1dc19](https://linux-hardware.org/?probe=8194e1dc19) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| Dell          | Latitude 7320               | Notebook    | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [a3eeaecb07](https://linux-hardware.org/?probe=a3eeaecb07) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [0675bbd9d0](https://linux-hardware.org/?probe=0675bbd9d0) | Jul 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [24fec424ff](https://linux-hardware.org/?probe=24fec424ff) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [6a75ac249a](https://linux-hardware.org/?probe=6a75ac249a) | Jul 24, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [85e3fee140](https://linux-hardware.org/?probe=85e3fee140) | Jul 24, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | Notebook    | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2ae14bcbc1](https://linux-hardware.org/?probe=2ae14bcbc1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [9c0899916c](https://linux-hardware.org/?probe=9c0899916c) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [88c35211e1](https://linux-hardware.org/?probe=88c35211e1) | Jul 23, 2022 |
| Lenovo        | 3702 SDK0J40700 WIN 3258... | All in one  | [95af4e4f8e](https://linux-hardware.org/?probe=95af4e4f8e) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | Notebook    | [6a1cb48f15](https://linux-hardware.org/?probe=6a1cb48f15) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [6889befce9](https://linux-hardware.org/?probe=6889befce9) | Jul 23, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Lenovo        | 81FV                        | Notebook    | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f2eb36554b](https://linux-hardware.org/?probe=f2eb36554b) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_36/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64        | 135       | 7.77%   |
| 5.18.13-200.fc36.x86_64       | 113       | 6.5%    |
| 5.18.11-200.fc36.x86_64       | 91        | 5.24%   |
| 5.18.16-200.fc36.x86_64       | 84        | 4.83%   |
| 5.19.9-200.fc36.x86_64        | 83        | 4.78%   |
| 5.18.5-200.fc36.x86_64        | 76        | 4.37%   |
| 5.17.6-300.fc36.x86_64        | 74        | 4.26%   |
| 5.17.11-300.fc36.x86_64       | 72        | 4.14%   |
| 5.19.8-200.fc36.x86_64        | 66        | 3.8%    |
| 5.19.6-200.fc36.x86_64        | 65        | 3.74%   |
| 5.17.13-300.fc36.x86_64       | 54        | 3.11%   |
| 5.18.17-200.fc36.x86_64       | 53        | 3.05%   |
| 5.19.4-200.fc36.x86_64        | 51        | 2.93%   |
| 5.18.9-200.fc36.x86_64        | 47        | 2.7%    |
| 5.17.12-300.fc36.x86_64       | 47        | 2.7%    |
| 5.18.19-200.fc36.x86_64       | 46        | 2.65%   |
| 5.18.18-200.fc36.x86_64       | 46        | 2.65%   |
| 5.18.10-200.fc36.x86_64       | 46        | 2.65%   |
| 5.17.8-300.fc36.x86_64        | 44        | 2.53%   |
| 5.19.11-200.fc36.x86_64       | 40        | 2.3%    |
| 5.18.6-200.fc36.x86_64        | 39        | 2.24%   |
| 5.18.7-200.fc36.x86_64        | 36        | 2.07%   |
| 5.17.7-300.fc36.x86_64        | 33        | 1.9%    |
| 5.17.9-300.fc36.x86_64        | 29        | 1.67%   |
| 5.17.1-300.fc36.x86_64        | 29        | 1.67%   |
| 5.17.2-300.fc36.x86_64        | 25        | 1.44%   |
| 5.19.10-200.fc36.x86_64       | 20        | 1.15%   |
| 5.17.3-302.fc36.x86_64        | 20        | 1.15%   |
| 5.17.0-0.rc7.116.fc36.x86_64  | 18        | 1.04%   |
| 5.18.15-200.fc36.x86_64       | 15        | 0.86%   |
| 5.19.7-200.fc36.x86_64        | 13        | 0.75%   |
| 5.17.14-300.fc36.x86_64       | 8         | 0.46%   |
| 5.18.1-200.fc36.x86_64        | 5         | 0.29%   |
| 5.17.0-0.rc5.102.fc36.x86_64  | 5         | 0.29%   |
| 5.19.12-200.fc36.x86_64       | 4         | 0.23%   |
| 5.18.5-201.fsync.fc36.x86_64  | 4         | 0.23%   |
| 5.17.4-300.fc36.x86_64        | 4         | 0.23%   |
| 5.17.0-300.fc36.x86_64        | 4         | 0.23%   |
| 5.18.10-201.fsync.fc36.x86_64 | 3         | 0.17%   |
| 5.17.5-301.fsync.fc36.x86_64  | 3         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 138       | 7.94%   |
| 5.18.13 | 114       | 6.56%   |
| 5.18.11 | 91        | 5.24%   |
| 5.18.16 | 85        | 4.89%   |
| 5.19.9  | 84        | 4.84%   |
| 5.18.5  | 82        | 4.72%   |
| 5.17.6  | 77        | 4.43%   |
| 5.17.11 | 75        | 4.32%   |
| 5.19.6  | 67        | 3.86%   |
| 5.19.8  | 66        | 3.8%    |
| 5.17.13 | 54        | 3.11%   |
| 5.18.17 | 53        | 3.05%   |
| 5.19.4  | 52        | 2.99%   |
| 5.18.9  | 50        | 2.88%   |
| 5.18.10 | 50        | 2.88%   |
| 5.18.18 | 49        | 2.82%   |
| 5.17.12 | 48        | 2.76%   |
| 5.18.19 | 46        | 2.65%   |
| 5.17.8  | 44        | 2.53%   |
| 5.18.6  | 41        | 2.36%   |
| 5.19.11 | 40        | 2.3%    |
| 5.18.7  | 37        | 2.13%   |
| 5.17.7  | 35        | 2.01%   |
| 5.17.9  | 32        | 1.84%   |
| 5.17.1  | 30        | 1.73%   |
| 5.17.0  | 27        | 1.55%   |
| 5.17.2  | 26        | 1.5%    |
| 5.17.3  | 22        | 1.27%   |
| 5.19.10 | 20        | 1.15%   |
| 5.19.7  | 16        | 0.92%   |
| 5.18.15 | 15        | 0.86%   |
| 5.17.14 | 8         | 0.46%   |
| 5.15.0  | 8         | 0.46%   |
| 5.18.1  | 7         | 0.4%    |
| 5.19.0  | 5         | 0.29%   |
| 6.0.0   | 4         | 0.23%   |
| 5.19.12 | 4         | 0.23%   |
| 5.19.1  | 4         | 0.23%   |
| 5.17.4  | 4         | 0.23%   |
| 5.18.8  | 3         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18    | 693       | 41.42%  |
| 5.17    | 598       | 35.74%  |
| 5.19    | 358       | 21.4%   |
| 5.15    | 8         | 0.48%   |
| 5.16    | 6         | 0.36%   |
| 6.0     | 4         | 0.24%   |
| 5.14    | 4         | 0.24%   |
| 5.4     | 1         | 0.06%   |
| 5.11    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1581      | 99.81%  |
| aarch64 | 3         | 0.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 1193      | 74.84%  |
| KDE5          | 253       | 15.87%  |
| Unknown       | 40        | 2.51%   |
| XFCE          | 29        | 1.82%   |
| X-Cinnamon    | 22        | 1.38%   |
| Cinnamon      | 17        | 1.07%   |
| MATE          | 10        | 0.63%   |
| i3            | 10        | 0.63%   |
| LXQt          | 5         | 0.31%   |
| GNOME Classic | 5         | 0.31%   |
| awesome       | 3         | 0.19%   |
| sway          | 2         | 0.13%   |
| Deepin        | 2         | 0.13%   |
| openbox       | 1         | 0.06%   |
| KDE:old       | 1         | 0.06%   |
| bspwm         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1141      | 71.22%  |
| X11     | 409       | 25.53%  |
| Tty     | 30        | 1.87%   |
| Unknown | 20        | 1.25%   |
| Web     | 2         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 858       | 53.79%  |
| GDM     | 522       | 32.73%  |
| SDDM    | 128       | 8.03%   |
| LightDM | 85        | 5.33%   |
| Ly      | 1         | 0.06%   |
| KDM     | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 853       | 53.78%  |
| ru_RU   | 105       | 6.62%   |
| en_GB   | 96        | 6.05%   |
| pt_BR   | 66        | 4.16%   |
| de_DE   | 65        | 4.1%    |
| it_IT   | 48        | 3.03%   |
| en_AU   | 43        | 2.71%   |
| fr_FR   | 37        | 2.33%   |
| es_ES   | 27        | 1.7%    |
| pl_PL   | 25        | 1.58%   |
| en_CA   | 23        | 1.45%   |
| en_IN   | 18        | 1.13%   |
| es_MX   | 17        | 1.07%   |
| en_NZ   | 13        | 0.82%   |
| nl_NL   | 9         | 0.57%   |
| es_AR   | 9         | 0.57%   |
| nl_BE   | 8         | 0.5%    |
| hu_HU   | 8         | 0.5%    |
| es_CL   | 8         | 0.5%    |
| cs_CZ   | 8         | 0.5%    |
| tr_TR   | 6         | 0.38%   |
| pt_PT   | 6         | 0.38%   |
| zh_CN   | 5         | 0.32%   |
| de_AT   | 5         | 0.32%   |
| Unknown | 5         | 0.32%   |
| sv_SE   | 4         | 0.25%   |
| en_ZA   | 4         | 0.25%   |
| ru_UA   | 3         | 0.19%   |
| fr_BE   | 3         | 0.19%   |
| es_CO   | 3         | 0.19%   |
| en_IE   | 3         | 0.19%   |
| en_DK   | 3         | 0.19%   |
| da_DK   | 3         | 0.19%   |
| ca_ES   | 3         | 0.19%   |
| C       | 3         | 0.19%   |
| sr_RS   | 2         | 0.13%   |
| ja_JP   | 2         | 0.13%   |
| hr_HR   | 2         | 0.13%   |
| fi_FI   | 2         | 0.13%   |
| es_VE   | 2         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1295      | 81.5%   |
| BIOS | 294       | 18.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1280      | 80.66%  |
| Ext4    | 267       | 16.82%  |
| Xfs     | 37        | 2.33%   |
| F2fs    | 2         | 0.13%   |
| Unknown | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 857       | 53.7%   |
| GPT     | 654       | 40.98%  |
| MBR     | 85        | 5.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1411      | 88.74%  |
| Yes       | 179       | 11.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1252      | 78.59%  |
| Yes       | 341       | 21.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 321       | 20.27%  |
| ASUSTek Computer        | 273       | 17.23%  |
| Hewlett-Packard         | 213       | 13.45%  |
| Dell                    | 193       | 12.18%  |
| MSI                     | 112       | 7.07%   |
| Gigabyte Technology     | 104       | 6.57%   |
| Acer                    | 58        | 3.66%   |
| ASRock                  | 51        | 3.22%   |
| Apple                   | 41        | 2.59%   |
| HUAWEI                  | 20        | 1.26%   |
| Microsoft               | 13        | 0.82%   |
| Intel                   | 13        | 0.82%   |
| Toshiba                 | 11        | 0.69%   |
| Samsung Electronics     | 9         | 0.57%   |
| Notebook                | 8         | 0.51%   |
| Framework               | 8         | 0.51%   |
| Unknown                 | 8         | 0.51%   |
| Timi                    | 7         | 0.44%   |
| Sony                    | 7         | 0.44%   |
| Chuwi                   | 7         | 0.44%   |
| BESSTAR Tech            | 7         | 0.44%   |
| Positivo                | 5         | 0.32%   |
| Fujitsu                 | 4         | 0.25%   |
| Foxconn                 | 4         | 0.25%   |
| Alienware               | 4         | 0.25%   |
| VALE                    | 3         | 0.19%   |
| TUXEDO                  | 3         | 0.19%   |
| System76                | 3         | 0.19%   |
| Panasonic               | 3         | 0.19%   |
| Huanan                  | 3         | 0.19%   |
| HONOR                   | 3         | 0.19%   |
| GPU Company             | 3         | 0.19%   |
| Google                  | 3         | 0.19%   |
| Avell High Performance  | 3         | 0.19%   |
| ZOTAC                   | 2         | 0.13%   |
| Razer                   | 2         | 0.13%   |
| Raspberry Pi Foundation | 2         | 0.13%   |
| Pegatron                | 2         | 0.13%   |
| Medion                  | 2         | 0.13%   |
| LG Electronics          | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 16        | 1.01%   |
| ASUS All Series                       | 12        | 0.76%   |
| Framework Laptop                      | 7         | 0.44%   |
| ASUS ROG STRIX B550-F GAMING          | 7         | 0.44%   |
| MSI MS-7C91                           | 6         | 0.38%   |
| MSI MS-7C37                           | 6         | 0.38%   |
| MSI MS-7A38                           | 6         | 0.38%   |
| Dell XPS 15 9570                      | 6         | 0.38%   |
| MSI MS-7B86                           | 5         | 0.32%   |
| HP Notebook                           | 5         | 0.32%   |
| HP EliteBook 8470p                    | 5         | 0.32%   |
| ASUS TUF Gaming B550M-PLUS            | 5         | 0.32%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 4         | 0.25%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 4         | 0.25%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 4         | 0.25%   |
| HP Pavilion g6                        | 4         | 0.25%   |
| HP Pavilion Aero Laptop 13-be0xxx     | 4         | 0.25%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ | 4         | 0.25%   |
| ASUS ROG STRIX X570-F GAMING          | 4         | 0.25%   |
| ASUS ROG Strix G513QY_G513QY          | 4         | 0.25%   |
| Apple MacBookPro12,1                  | 4         | 0.25%   |
| Timi Redmi Book Pro 15 2022           | 3         | 0.19%   |
| MSI MS-7C95                           | 3         | 0.19%   |
| MSI MS-7C56                           | 3         | 0.19%   |
| MSI MS-7B79                           | 3         | 0.19%   |
| Microsoft Surface Pro 7               | 3         | 0.19%   |
| Lenovo ThinkBook 16p Gen 2 20YM       | 3         | 0.19%   |
| Lenovo ThinkBook 14 G3 ACL 21A2       | 3         | 0.19%   |
| Lenovo IdeaPad S340-14API 81NB        | 3         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 3         | 0.19%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7      | 3         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.19%   |
| HUAWEI KLVL-WXXW                      | 3         | 0.19%   |
| HP Pavilion Laptop 15-cs0xxx          | 3         | 0.19%   |
| HP ENVY x360 Convertible 13-ay0xxx    | 3         | 0.19%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx  | 3         | 0.19%   |
| HP EliteBook 8460p                    | 3         | 0.19%   |
| HP EliteBook 840 G3                   | 3         | 0.19%   |
| Gigabyte B550I AORUS PRO AX           | 3         | 0.19%   |
| Dell XPS 8940                         | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 145       | 9.15%   |
| Lenovo IdeaPad     | 79        | 4.99%   |
| ASUS ROG           | 79        | 4.99%   |
| Dell Inspiron      | 54        | 3.41%   |
| Dell XPS           | 46        | 2.9%    |
| HP Pavilion        | 42        | 2.65%   |
| Dell Latitude      | 39        | 2.46%   |
| ASUS PRIME         | 31        | 1.96%   |
| ASUS TUF           | 29        | 1.83%   |
| Acer Aspire        | 29        | 1.83%   |
| HP EliteBook       | 27        | 1.7%    |
| HP ENVY            | 25        | 1.58%   |
| Dell Precision     | 25        | 1.58%   |
| HP Laptop          | 24        | 1.52%   |
| HP ProBook         | 23        | 1.45%   |
| ASUS VivoBook      | 23        | 1.45%   |
| Lenovo Yoga        | 19        | 1.2%    |
| Lenovo ThinkBook   | 19        | 1.2%    |
| Unknown            | 16        | 1.01%   |
| Dell OptiPlex      | 15        | 0.95%   |
| Microsoft Surface  | 13        | 0.82%   |
| Lenovo Legion      | 12        | 0.76%   |
| ASUS All           | 12        | 0.76%   |
| ASUS ASUS          | 11        | 0.69%   |
| Lenovo ThinkCentre | 10        | 0.63%   |
| HP ZBook           | 10        | 0.63%   |
| Toshiba Satellite  | 9         | 0.57%   |
| Lenovo IdeaPadFlex | 9         | 0.57%   |
| Framework Laptop   | 8         | 0.51%   |
| Acer Swift         | 8         | 0.51%   |
| Acer Nitro         | 8         | 0.51%   |
| MSI Modern         | 7         | 0.44%   |
| HP Compaq          | 7         | 0.44%   |
| Dell Vostro        | 7         | 0.44%   |
| MSI MS-7C91        | 6         | 0.38%   |
| MSI MS-7C37        | 6         | 0.38%   |
| MSI MS-7A38        | 6         | 0.38%   |
| Gigabyte B550      | 6         | 0.38%   |
| ASRock B450M       | 6         | 0.38%   |
| MSI MS-7B86        | 5         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 281       | 17.74%  |
| 2020    | 256       | 16.16%  |
| 2019    | 182       | 11.49%  |
| 2018    | 154       | 9.72%   |
| 2022    | 97        | 6.12%   |
| 2017    | 92        | 5.81%   |
| 2016    | 78        | 4.92%   |
| 2014    | 78        | 4.92%   |
| 2012    | 77        | 4.86%   |
| 2015    | 76        | 4.8%    |
| 2013    | 72        | 4.55%   |
| 2011    | 59        | 3.72%   |
| 2010    | 29        | 1.83%   |
| 2009    | 21        | 1.33%   |
| 2008    | 20        | 1.26%   |
| 2007    | 6         | 0.38%   |
| 2006    | 4         | 0.25%   |
| 2005    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 921       | 58.14%  |
| Desktop        | 503       | 31.76%  |
| Convertible    | 92        | 5.81%   |
| Tablet         | 27        | 1.7%    |
| Mini pc        | 18        | 1.14%   |
| All in one     | 18        | 1.14%   |
| System on chip | 3         | 0.19%   |
| Server         | 2         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1290      | 81.13%  |
| Enabled  | 300       | 18.87%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1579      | 99.68%  |
| Yes  | 5         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 391       | 24.53%  |
| 16.01-24.0  | 389       | 24.4%   |
| 8.01-16.0   | 302       | 18.95%  |
| 32.01-64.0  | 271       | 17%     |
| 3.01-4.0    | 127       | 7.97%   |
| 64.01-256.0 | 64        | 4.02%   |
| 24.01-32.0  | 25        | 1.57%   |
| 1.01-2.0    | 20        | 1.25%   |
| 2.01-3.0    | 4         | 0.25%   |
| 0.51-1.0    | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 500       | 30.08%  |
| 2.01-3.0   | 427       | 25.69%  |
| 3.01-4.0   | 405       | 24.37%  |
| 1.01-2.0   | 171       | 10.29%  |
| 8.01-16.0  | 122       | 7.34%   |
| 0.51-1.0   | 16        | 0.96%   |
| 16.01-24.0 | 13        | 0.78%   |
| 24.01-32.0 | 4         | 0.24%   |
| 0.01-0.5   | 3         | 0.18%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 935       | 58.55%  |
| 2      | 411       | 25.74%  |
| 3      | 134       | 8.39%   |
| 4      | 65        | 4.07%   |
| 5      | 24        | 1.5%    |
| 6      | 14        | 0.88%   |
| 7      | 8         | 0.5%    |
| 10     | 2         | 0.13%   |
| 0      | 2         | 0.13%   |
| 11     | 1         | 0.06%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1255      | 79.18%  |
| Yes       | 330       | 20.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1201      | 75.58%  |
| No        | 388       | 24.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1343      | 84.73%  |
| No        | 242       | 15.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1189      | 74.78%  |
| No        | 401       | 25.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 333       | 20.92%  |
| Russia       | 127       | 7.98%   |
| Germany      | 117       | 7.35%   |
| Brazil       | 94        | 5.9%    |
| Italy        | 86        | 5.4%    |
| India        | 56        | 3.52%   |
| UK           | 51        | 3.2%    |
| Australia    | 49        | 3.08%   |
| France       | 46        | 2.89%   |
| Poland       | 45        | 2.83%   |
| Spain        | 41        | 2.58%   |
| Netherlands  | 38        | 2.39%   |
| Mexico       | 36        | 2.26%   |
| Canada       | 35        | 2.2%    |
| Turkey       | 25        | 1.57%   |
| Belgium      | 22        | 1.38%   |
| Argentina    | 21        | 1.32%   |
| Indonesia    | 17        | 1.07%   |
| Hungary      | 17        | 1.07%   |
| Sweden       | 15        | 0.94%   |
| Czechia      | 15        | 0.94%   |
| Norway       | 14        | 0.88%   |
| Finland      | 12        | 0.75%   |
| Belarus      | 12        | 0.75%   |
| Austria      | 12        | 0.75%   |
| Switzerland  | 11        | 0.69%   |
| New Zealand  | 11        | 0.69%   |
| Romania      | 10        | 0.63%   |
| Portugal     | 10        | 0.63%   |
| Japan        | 9         | 0.57%   |
| Israel       | 9         | 0.57%   |
| Colombia     | 9         | 0.57%   |
| Chile        | 9         | 0.57%   |
| Philippines  | 7         | 0.44%   |
| Ireland      | 7         | 0.44%   |
| Denmark      | 7         | 0.44%   |
| South Africa | 6         | 0.38%   |
| Greece       | 6         | 0.38%   |
| Bulgaria     | 6         | 0.38%   |
| Ukraine      | 5         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 35        | 2.15%   |
| St Petersburg     | 23        | 1.41%   |
| Sao Paulo         | 15        | 0.92%   |
| Berlin            | 15        | 0.92%   |
| Melbourne         | 14        | 0.86%   |
| Warsaw            | 13        | 0.8%    |
| Brisbane          | 12        | 0.74%   |
| Rome              | 10        | 0.61%   |
| Minsk             | 10        | 0.61%   |
| Mexico City       | 10        | 0.61%   |
| Paris             | 9         | 0.55%   |
| New York          | 9         | 0.55%   |
| Launceston        | 9         | 0.55%   |
| Istanbul          | 9         | 0.55%   |
| Prague            | 8         | 0.49%   |
| Kolkata           | 8         | 0.49%   |
| Chicago           | 8         | 0.49%   |
| Auckland          | 8         | 0.49%   |
| Sydney            | 7         | 0.43%   |
| Oslo              | 7         | 0.43%   |
| Munich            | 7         | 0.43%   |
| Budapest          | 7         | 0.43%   |
| Bengaluru         | 7         | 0.43%   |
| Amsterdam         | 7         | 0.43%   |
| Verona            | 6         | 0.37%   |
| Santiago          | 6         | 0.37%   |
| Portland          | 6         | 0.37%   |
| Novosibirsk       | 6         | 0.37%   |
| Milan             | 6         | 0.37%   |
| Los Angeles       | 6         | 0.37%   |
| Helsinki          | 6         | 0.37%   |
| Buenos Aires      | 6         | 0.37%   |
| Antwerp           | 6         | 0.37%   |
| Vienna            | 5         | 0.31%   |
| Rio de Janeiro    | 5         | 0.31%   |
| Montreal          | 5         | 0.31%   |
| Las Vegas         | 5         | 0.31%   |
| Jakarta           | 5         | 0.31%   |
| Izmir             | 5         | 0.31%   |
| Frankfurt am Main | 5         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 467       | 638    | 19.56%  |
| WDC                       | 291       | 403    | 12.19%  |
| Seagate                   | 257       | 350    | 10.76%  |
| SanDisk                   | 154       | 179    | 6.45%   |
| Kingston                  | 133       | 150    | 5.57%   |
| Toshiba                   | 117       | 137    | 4.9%    |
| Crucial                   | 104       | 125    | 4.36%   |
| SK hynix                  | 89        | 96     | 3.73%   |
| Intel                     | 76        | 101    | 3.18%   |
| Unknown                   | 73        | 90     | 3.06%   |
| Micron Technology         | 66        | 74     | 2.76%   |
| KIOXIA                    | 40        | 53     | 1.68%   |
| Phison                    | 39        | 42     | 1.63%   |
| A-DATA Technology         | 32        | 35     | 1.34%   |
| Hitachi                   | 31        | 37     | 1.3%    |
| HGST                      | 25        | 30     | 1.05%   |
| Silicon Motion            | 21        | 21     | 0.88%   |
| China                     | 21        | 24     | 0.88%   |
| Unknown                   | 21        | 21     | 0.88%   |
| Apple                     | 20        | 21     | 0.84%   |
| PNY                       | 15        | 18     | 0.63%   |
| Micron/Crucial Technology | 15        | 17     | 0.63%   |
| XPG                       | 13        | 18     | 0.54%   |
| SPCC                      | 13        | 18     | 0.54%   |
| Patriot                   | 12        | 14     | 0.5%    |
| LITEON                    | 11        | 11     | 0.46%   |
| Netac                     | 10        | 10     | 0.42%   |
| Transcend                 | 9         | 11     | 0.38%   |
| UMIS                      | 8         | 11     | 0.34%   |
| SSSTC                     | 8         | 8      | 0.34%   |
| SABRENT                   | 8         | 10     | 0.34%   |
| Intenso                   | 8         | 10     | 0.34%   |
| Gigabyte Technology       | 7         | 11     | 0.29%   |
| Corsair                   | 7         | 9      | 0.29%   |
| ADATA Technology          | 7         | 7      | 0.29%   |
| LITEONIT                  | 6         | 6      | 0.25%   |
| GOODRAM                   | 6         | 9      | 0.25%   |
| Team                      | 5         | 7      | 0.21%   |
| Realtek Semiconductor     | 5         | 5      | 0.21%   |
| Phison Electronics        | 5         | 6      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 36        | 1.37%   |
| SanDisk NVMe SSD Drive 512GB                        | 27        | 1.02%   |
| Samsung NVMe SSD Drive 512GB                        | 27        | 1.02%   |
| Kingston SA400S37240G 240GB SSD                     | 27        | 1.02%   |
| Samsung NVMe SSD Drive 500GB                        | 24        | 0.91%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.83%   |
| SanDisk NVMe SSD Drive 1TB                          | 21        | 0.8%    |
| Unknown                                             | 21        | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.76%   |
| Samsung SSD 850 EVO 250GB                           | 20        | 0.76%   |
| Samsung NVMe SSD Drive 1024GB                       | 20        | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB                      | 19        | 0.72%   |
| Intel NVMe SSD Drive 512GB                          | 19        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB                     | 17        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                      | 17        | 0.65%   |
| Samsung SSD 860 EVO 500GB                           | 16        | 0.61%   |
| Samsung NVMe SSD Drive 2TB                          | 16        | 0.61%   |
| Kingston SA400S37120G 120GB SSD                     | 16        | 0.61%   |
| HGST HTS721010A9E630 1TB                            | 16        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                         | 16        | 0.61%   |
| Unknown MMC Card  64GB                              | 15        | 0.57%   |
| SK hynix NVMe SSD Drive 512GB                       | 15        | 0.57%   |
| Crucial CT500MX500SSD1 500GB                        | 15        | 0.57%   |
| Samsung SSD 980 PRO 1TB                             | 14        | 0.53%   |
| Samsung SSD 850 EVO 500GB                           | 14        | 0.53%   |
| KIOXIA NVMe SSD Drive 512GB                         | 14        | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.49%   |
| SanDisk NVMe SSD Drive 500GB                        | 13        | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 13        | 0.49%   |
| Micron NVMe SSD Drive 512GB                         | 13        | 0.49%   |
| Crucial CT480BX500SSD1 480GB                        | 12        | 0.46%   |
| Samsung SSD 860 EVO 250GB                           | 11        | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 11        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 11        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 10        | 0.38%   |
| Toshiba NVMe SSD Drive 256GB                        | 10        | 0.38%   |
| Seagate ST500LT012-1DG142 500GB                     | 10        | 0.38%   |
| SanDisk NVMe SSD Drive 1024GB                       | 10        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                      | 10        | 0.38%   |
| Samsung NVMe SSD Drive 250GB                        | 10        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 248       | 336    | 41.13%  |
| WDC                 | 189       | 278    | 31.34%  |
| Toshiba             | 70        | 78     | 11.61%  |
| Hitachi             | 31        | 37     | 5.14%   |
| HGST                | 25        | 30     | 4.15%   |
| Samsung Electronics | 10        | 15     | 1.66%   |
| Apple               | 6         | 6      | 1%      |
| Unknown             | 5         | 6      | 0.83%   |
| Fujitsu             | 4         | 4      | 0.66%   |
| USB3.0              | 2         | 2      | 0.33%   |
| Hewlett-Packard     | 2         | 2      | 0.33%   |
| ASMT                | 2         | 2      | 0.33%   |
| USB                 | 1         | 1      | 0.17%   |
| RSH-339             | 1         | 1      | 0.17%   |
| Maxtor              | 1         | 3      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.17%   |
| Intenso             | 1         | 1      | 0.17%   |
| IB-AC703            | 1         | 1      | 0.17%   |
| ExcelStor           | 1         | 1      | 0.17%   |
| ASMT106x            | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 181       | 231    | 25%     |
| Crucial             | 91        | 111    | 12.57%  |
| Kingston            | 88        | 99     | 12.15%  |
| SanDisk             | 60        | 67     | 8.29%   |
| WDC                 | 42        | 51     | 5.8%    |
| Intel               | 22        | 26     | 3.04%   |
| China               | 20        | 23     | 2.76%   |
| A-DATA Technology   | 18        | 19     | 2.49%   |
| Micron Technology   | 15        | 16     | 2.07%   |
| PNY                 | 14        | 16     | 1.93%   |
| SPCC                | 11        | 16     | 1.52%   |
| Patriot             | 11        | 13     | 1.52%   |
| Apple               | 10        | 10     | 1.38%   |
| Transcend           | 9         | 11     | 1.24%   |
| SK hynix            | 9         | 9      | 1.24%   |
| LITEON              | 9         | 9      | 1.24%   |
| Netac               | 8         | 8      | 1.1%    |
| Gigabyte Technology | 7         | 11     | 0.97%   |
| LITEONIT            | 6         | 6      | 0.83%   |
| Intenso             | 6         | 8      | 0.83%   |
| GOODRAM             | 6         | 9      | 0.83%   |
| Toshiba             | 5         | 5      | 0.69%   |
| Seagate             | 5         | 5      | 0.69%   |
| Lexar               | 5         | 6      | 0.69%   |
| Corsair             | 5         | 6      | 0.69%   |
| Unknown             | 5         | 5      | 0.69%   |
| Team                | 4         | 6      | 0.55%   |
| OCZ                 | 4         | 7      | 0.55%   |
| Plextor             | 3         | 4      | 0.41%   |
| GALAX               | 3         | 3      | 0.41%   |
| Apacer              | 3         | 3      | 0.41%   |
| Verbatim            | 2         | 2      | 0.28%   |
| Leven               | 2         | 2      | 0.28%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.28%   |
| KingSpec            | 2         | 2      | 0.28%   |
| KingDian            | 2         | 2      | 0.28%   |
| GLOWAY              | 2         | 2      | 0.28%   |
| XSTAR               | 1         | 1      | 0.14%   |
| XrayDisk            | 1         | 1      | 0.14%   |
| Win Memory          | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 910       | 1184   | 42.38%  |
| SSD     | 612       | 860    | 28.5%   |
| HDD     | 511       | 807    | 23.8%   |
| MMC     | 72        | 94     | 3.35%   |
| Unknown | 42        | 46     | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 906       | 1171   | 46.04%  |
| SATA | 898       | 1603   | 45.63%  |
| SAS  | 92        | 123    | 4.67%   |
| MMC  | 72        | 94     | 3.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 611       | 872    | 50.41%  |
| 0.51-1.0   | 398       | 502    | 32.84%  |
| 1.01-2.0   | 113       | 171    | 9.32%   |
| 3.01-4.0   | 46        | 60     | 3.8%    |
| 2.01-3.0   | 22        | 26     | 1.82%   |
| 4.01-10.0  | 20        | 32     | 1.65%   |
| 10.01-20.0 | 2         | 4      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 338       | 20.93%  |
| 251-500        | 286       | 17.71%  |
| 1001-2000      | 222       | 13.75%  |
| 101-250        | 217       | 13.44%  |
| 1-20           | 175       | 10.84%  |
| More than 3000 | 122       | 7.55%   |
| Unknown        | 111       | 6.87%   |
| 2001-3000      | 70        | 4.33%   |
| 51-100         | 56        | 3.47%   |
| 21-50          | 18        | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 496       | 30.1%   |
| 21-50          | 256       | 15.53%  |
| 101-250        | 198       | 12.01%  |
| 51-100         | 183       | 11.1%   |
| 251-500        | 162       | 9.83%   |
| 501-1000       | 119       | 7.22%   |
| Unknown        | 111       | 6.74%   |
| 1001-2000      | 68        | 4.13%   |
| More than 3000 | 35        | 2.12%   |
| 2001-3000      | 20        | 1.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 5         | 7      | 4.95%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 3.96%   |
| Samsung Electronics SSD 870 EVO 1TB   | 4         | 4      | 3.96%   |
| HGST HTS721010A9E630 1TB              | 4         | 4      | 3.96%   |
| Seagate ST3500418AS 500GB             | 3         | 3      | 2.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 4      | 2.97%   |
| Toshiba MK3275GSX 320GB               | 2         | 2      | 1.98%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 1.98%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 1.98%   |
| Intel SSDSC2CT120A3 120GB             | 2         | 4      | 1.98%   |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 0.99%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 0.99%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 0.99%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.99%   |
| WDC WD4001FAEX-00MJRA0 4TB            | 1         | 1      | 0.99%   |
| WDC WD3200AAKS-75B3A0 320GB           | 1         | 1      | 0.99%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1         | 1      | 0.99%   |
| WDC WD2500AAKX-753CA1 250GB           | 1         | 1      | 0.99%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 0.99%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 1      | 0.99%   |
| WDC WD2003FYYS-02W0B1 2TB             | 1         | 6      | 0.99%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10EARS-22Y5B1 1TB               | 1         | 1      | 0.99%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 0.99%   |
| WDC WD10EADS-65M2B1 1TB               | 1         | 1      | 0.99%   |
| WDC WD1003FBYX-01Y7B1 1TB             | 1         | 2      | 0.99%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD050 500GB              | 1         | 2      | 0.99%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 0.99%   |
| Toshiba MK2556GSY 250GB               | 1         | 1      | 0.99%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 0.99%   |
| SPCC Solid State Disk 1TB             | 1         | 2      | 0.99%   |
| SK hynix SH920 2.5 7MM 256GB SSD      | 1         | 1      | 0.99%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 1      | 0.99%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 0.99%   |
| Seagate ST500LM030-2E717D 500GB       | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 33     | 26.04%  |
| WDC                 | 19        | 26     | 19.79%  |
| Samsung Electronics | 13        | 19     | 13.54%  |
| Toshiba             | 7         | 8      | 7.29%   |
| Hitachi             | 6         | 6      | 6.25%   |
| Intel               | 4         | 6      | 4.17%   |
| HGST                | 4         | 4      | 4.17%   |
| SanDisk             | 3         | 3      | 3.13%   |
| Crucial             | 3         | 3      | 3.13%   |
| SK hynix            | 2         | 2      | 2.08%   |
| Kingston            | 2         | 2      | 2.08%   |
| SPCC                | 1         | 2      | 1.04%   |
| Origin              | 1         | 1      | 1.04%   |
| OCZ-VERTEX3         | 1         | 1      | 1.04%   |
| Micron Technology   | 1         | 1      | 1.04%   |
| LITEONIT            | 1         | 1      | 1.04%   |
| LITEON              | 1         | 1      | 1.04%   |
| Lenovo              | 1         | 2      | 1.04%   |
| Fujitsu             | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 33     | 37.88%  |
| WDC                 | 19        | 26     | 28.79%  |
| Toshiba             | 7         | 8      | 10.61%  |
| Hitachi             | 6         | 6      | 9.09%   |
| Samsung Electronics | 4         | 9      | 6.06%   |
| HGST                | 4         | 4      | 6.06%   |
| Fujitsu             | 1         | 1      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 87     | 68.48%  |
| SSD  | 27        | 32     | 29.35%  |
| NVMe | 2         | 3      | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 50%     |
| Samsung Electronics SSD 980 500GB | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 946       | 1783   | 55.16%  |
| Works    | 676       | 1083   | 39.42%  |
| Malfunc  | 91        | 122    | 5.31%   |
| Failed   | 2         | 3      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 873       | 39.45%  |
| AMD                            | 345       | 15.59%  |
| Samsung Electronics            | 323       | 14.6%   |
| SanDisk                        | 155       | 7%      |
| SK hynix                       | 79        | 3.57%   |
| Phison Electronics             | 51        | 2.3%    |
| Micron Technology              | 50        | 2.26%   |
| Kingston Technology Company    | 49        | 2.21%   |
| Toshiba America Info Systems   | 45        | 2.03%   |
| KIOXIA                         | 38        | 1.72%   |
| ASMedia Technology             | 32        | 1.45%   |
| ADATA Technology               | 30        | 1.36%   |
| Micron/Crucial Technology      | 28        | 1.27%   |
| Silicon Motion                 | 25        | 1.13%   |
| Marvell Technology Group       | 12        | 0.54%   |
| Nvidia                         | 11        | 0.5%    |
| Union Memory (Shenzhen)        | 10        | 0.45%   |
| Solid State Storage Technology | 10        | 0.45%   |
| JMicron Technology             | 9         | 0.41%   |
| Realtek Semiconductor          | 7         | 0.32%   |
| Lite-On Technology             | 5         | 0.23%   |
| Lenovo                         | 4         | 0.18%   |
| Apple                          | 4         | 0.18%   |
| Seagate Technology             | 3         | 0.14%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.14%   |
| Unknown                        | 2         | 0.09%   |
| Silicon Image                  | 2         | 0.09%   |
| VIA Technologies               | 1         | 0.05%   |
| ULi Electronics                | 1         | 0.05%   |
| Netac Technology               | 1         | 0.05%   |
| LSI Logic / Symbios Logic      | 1         | 0.05%   |
| Integrated Technology Express  | 1         | 0.05%   |
| Broadcom / LSI                 | 1         | 0.05%   |
| Biwin Storage Technology       | 1         | 0.05%   |
| Unknown                        | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 237       | 9.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 140       | 5.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 81        | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 81        | 3.35%   |
| Samsung NVMe SSD Controller 980                                                | 80        | 3.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 62        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 61        | 2.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 57        | 2.36%   |
| AMD 500 Series Chipset SATA Controller                                         | 57        | 2.36%   |
| AMD 400 Series Chipset SATA Controller                                         | 57        | 2.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 53        | 2.19%   |
| Micron Non-Volatile memory controller                                          | 50        | 2.07%   |
| SanDisk Non-Volatile memory controller                                         | 42        | 1.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 42        | 1.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 40        | 1.65%   |
| SK hynix Gold P31 SSD                                                          | 35        | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 35        | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 34        | 1.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 33        | 1.36%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 32        | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 32        | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 31        | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                          | 28        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 28        | 1.16%   |
| Phison E12 NVMe Controller                                                     | 27        | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 24        | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                            | 24        | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 24        | 0.99%   |
| Intel Non-Volatile memory controller                                           | 23        | 0.95%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.91%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 22        | 0.91%   |
| Intel SSD 660P Series                                                          | 21        | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 20        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 20        | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 20        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 20        | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 20        | 0.83%   |
| Kingston Company Company Non-Volatile memory controller                        | 19        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1042      | 47.58%  |
| NVMe | 903       | 41.23%  |
| RAID | 168       | 7.67%   |
| IDE  | 74        | 3.38%   |
| SAS  | 3         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1086      | 68.56%  |
| AMD     | 494       | 31.19%  |
| ARM     | 2         | 0.13%   |
| Unknown | 2         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 39        | 2.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 38        | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 1.7%    |
| AMD Ryzen 5 3600 6-Core Processor             | 24        | 1.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 1.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 1.45%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 21        | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 19        | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 1.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 1.01%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 1.01%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 0.95%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 15        | 0.95%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 14        | 0.88%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 14        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.82%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 13        | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.63%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 0.63%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 10        | 0.63%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 10        | 0.63%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 9         | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 0.57%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 9         | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.5%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 8         | 0.5%    |
| Intel Core i5-10400F CPU @ 2.90GHz            | 8         | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.5%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 8         | 0.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics        | 8         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 328       | 20.69%  |
| Intel Core i7                  | 326       | 20.57%  |
| Other                          | 197       | 12.43%  |
| AMD Ryzen 5                    | 182       | 11.48%  |
| AMD Ryzen 7                    | 130       | 8.2%    |
| Intel Core i3                  | 77        | 4.86%   |
| AMD Ryzen 9                    | 68        | 4.29%   |
| Intel Celeron                  | 42        | 2.65%   |
| Intel Core 2 Duo               | 26        | 1.64%   |
| Intel Xeon                     | 22        | 1.39%   |
| Intel Core i9                  | 18        | 1.14%   |
| Intel Atom                     | 18        | 1.14%   |
| AMD Ryzen 7 PRO                | 17        | 1.07%   |
| AMD Ryzen 3                    | 15        | 0.95%   |
| Intel Pentium                  | 14        | 0.88%   |
| AMD FX                         | 13        | 0.82%   |
| AMD A10                        | 13        | 0.82%   |
| Intel Pentium Silver           | 8         | 0.5%    |
| AMD Ryzen 5 PRO                | 8         | 0.5%    |
| AMD A6                         | 8         | 0.5%    |
| AMD A8                         | 7         | 0.44%   |
| Intel Core 2 Quad              | 5         | 0.32%   |
| AMD Phenom II X4               | 5         | 0.32%   |
| Intel Pentium Gold             | 3         | 0.19%   |
| AMD Phenom II X2               | 3         | 0.19%   |
| Intel Pentium Dual-Core        | 2         | 0.13%   |
| Intel Core m3                  | 2         | 0.13%   |
| Intel Core 2                   | 2         | 0.13%   |
| AMD Opteron                    | 2         | 0.13%   |
| AMD E1                         | 2         | 0.13%   |
| AMD Athlon Dual Core           | 2         | 0.13%   |
| AMD Athlon 64 X2               | 2         | 0.13%   |
| AMD Athlon                     | 2         | 0.13%   |
| AMD A4                         | 2         | 0.13%   |
| Intel Genuine                  | 1         | 0.06%   |
| Intel Core m5                  | 1         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.06%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.06%   |
| AMD Ryzen Threadripper         | 1         | 0.06%   |
| AMD PRO A8                     | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 603       | 38.04%  |
| 2       | 398       | 25.11%  |
| 6       | 263       | 16.59%  |
| 8       | 211       | 13.31%  |
| 12      | 50        | 3.15%   |
| 10      | 17        | 1.07%   |
| 16      | 15        | 0.95%   |
| 14      | 13        | 0.82%   |
| 3       | 6         | 0.38%   |
| 1       | 5         | 0.32%   |
| Unknown | 3         | 0.19%   |
| 18      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1575      | 99.43%  |
| 2       | 6         | 0.38%   |
| Unknown | 3         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1305      | 82.33%  |
| 1       | 277       | 17.48%  |
| Unknown | 3         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1583      | 99.94%  |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 106       | 6.68%   |
| 0x306a9    | 75        | 4.73%   |
| 0x306c3    | 71        | 4.47%   |
| 0x0a50000c | 70        | 4.41%   |
| Unknown    | 69        | 4.35%   |
| 0x206a7    | 63        | 3.97%   |
| 0x906ea    | 61        | 3.84%   |
| 0x806ea    | 60        | 3.78%   |
| 0x806ec    | 54        | 3.4%    |
| 0x506e3    | 50        | 3.15%   |
| 0x08701021 | 47        | 2.96%   |
| 0x806e9    | 45        | 2.84%   |
| 0x40651    | 37        | 2.33%   |
| 0x08108109 | 36        | 2.27%   |
| 0xa0652    | 33        | 2.08%   |
| 0x906e9    | 33        | 2.08%   |
| 0x0a201016 | 33        | 2.08%   |
| 0x08600106 | 33        | 2.08%   |
| 0x08608103 | 31        | 1.95%   |
| 0x406e3    | 27        | 1.7%    |
| 0x306d4    | 27        | 1.7%    |
| 0x706e5    | 22        | 1.39%   |
| 0x906a3    | 21        | 1.32%   |
| 0x1067a    | 21        | 1.32%   |
| 0x0800820d | 19        | 1.2%    |
| 0x90672    | 16        | 1.01%   |
| 0x706a8    | 16        | 1.01%   |
| 0x0a404101 | 15        | 0.95%   |
| 0xa0653    | 14        | 0.88%   |
| 0x806d1    | 14        | 0.88%   |
| 0x08108102 | 14        | 0.88%   |
| 0xa0655    | 13        | 0.82%   |
| 0x906ed    | 12        | 0.76%   |
| 0x20655    | 12        | 0.76%   |
| 0x506c9    | 11        | 0.69%   |
| 0xa0671    | 10        | 0.63%   |
| 0x08608102 | 10        | 0.63%   |
| 0x08600104 | 10        | 0.63%   |
| 0x806eb    | 9         | 0.57%   |
| 0x406c4    | 9         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 295       | 18.61%  |
| Zen 3            | 149       | 9.4%    |
| Haswell          | 120       | 7.57%   |
| TigerLake        | 118       | 7.44%   |
| Zen 2            | 105       | 6.62%   |
| Skylake          | 84        | 5.3%    |
| IvyBridge        | 79        | 4.98%   |
| Unknown          | 75        | 4.73%   |
| Zen+             | 74        | 4.67%   |
| SandyBridge      | 68        | 4.29%   |
| CometLake        | 66        | 4.16%   |
| IceLake          | 48        | 3.03%   |
| Alderlake Hybrid | 45        | 2.84%   |
| Zen              | 31        | 1.96%   |
| Penryn           | 30        | 1.89%   |
| Broadwell        | 29        | 1.83%   |
| Silvermont       | 23        | 1.45%   |
| Goldmont plus    | 21        | 1.32%   |
| Westmere         | 20        | 1.26%   |
| Piledriver       | 17        | 1.07%   |
| K10              | 14        | 0.88%   |
| Excavator        | 13        | 0.82%   |
| Goldmont         | 11        | 0.69%   |
| Tremont          | 7         | 0.44%   |
| Core             | 7         | 0.44%   |
| Nehalem          | 6         | 0.38%   |
| K8 Hammer        | 6         | 0.38%   |
| Jaguar           | 5         | 0.32%   |
| Steamroller      | 4         | 0.25%   |
| Bulldozer        | 4         | 0.25%   |
| Bonnell          | 4         | 0.25%   |
| Puma             | 3         | 0.19%   |
| K10 Llano        | 2         | 0.13%   |
| K8 & K10 hybrid  | 1         | 0.06%   |
| Bobcat           | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 883       | 45.4%   |
| Nvidia                     | 532       | 27.35%  |
| AMD                        | 526       | 27.04%  |
| Matrox Electronics Systems | 3         | 0.15%   |
| ASPEED Technology          | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 108       | 5.43%   |
| AMD Cezanne                                                                              | 71        | 3.57%   |
| Intel UHD Graphics 620                                                                   | 61        | 3.07%   |
| AMD Renoir                                                                               | 52        | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 52        | 2.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 49        | 2.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 49        | 2.46%   |
| Intel HD Graphics 620                                                                    | 42        | 2.11%   |
| AMD Lucienne                                                                             | 41        | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 40        | 2.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 1.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 1.46%   |
| Intel HD Graphics 530                                                                    | 28        | 1.41%   |
| AMD Rembrandt [Radeon 680M]                                                              | 25        | 1.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.21%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 24        | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 23        | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 22        | 1.11%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 22        | 1.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 21        | 1.06%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.01%   |
| Intel HD Graphics 630                                                                    | 18        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 17        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 15        | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 15        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 0.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 15        | 0.75%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 14        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 13        | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 0.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 577       | 36.38%  |
| 1 x AMD         | 403       | 25.41%  |
| Intel + Nvidia  | 248       | 15.64%  |
| 1 x Nvidia      | 224       | 14.12%  |
| AMD + Nvidia    | 54        | 3.4%    |
| Intel + AMD     | 35        | 2.21%   |
| 2 x AMD         | 32        | 2.02%   |
| Other           | 4         | 0.25%   |
| 2 x Nvidia      | 3         | 0.19%   |
| 2 x Intel       | 1         | 0.06%   |
| Nvidia + Matrox | 1         | 0.06%   |
| 1 x Matrox      | 1         | 0.06%   |
| Intel + 2 x AMD | 1         | 0.06%   |
| 1 x ASPEED      | 1         | 0.06%   |
| AMD + Matrox    | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1290      | 81.03%  |
| Proprietary | 270       | 16.96%  |
| Unknown     | 32        | 2.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 793       | 49.59%  |
| 1.01-2.0   | 206       | 12.88%  |
| 0.01-0.5   | 184       | 11.51%  |
| 3.01-4.0   | 138       | 8.63%   |
| 7.01-8.0   | 102       | 6.38%   |
| 0.51-1.0   | 89        | 5.57%   |
| 8.01-16.0  | 42        | 2.63%   |
| 5.01-6.0   | 37        | 2.31%   |
| 2.01-3.0   | 8         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 240       | 13.09%  |
| BOE                     | 215       | 11.72%  |
| Samsung Electronics     | 161       | 8.78%   |
| Chimei Innolux          | 159       | 8.67%   |
| LG Display              | 146       | 7.96%   |
| Goldstar                | 123       | 6.71%   |
| Dell                    | 114       | 6.22%   |
| Hewlett-Packard         | 54        | 2.94%   |
| Sharp                   | 53        | 2.89%   |
| BenQ                    | 46        | 2.51%   |
| AOC                     | 46        | 2.51%   |
| Philips                 | 44        | 2.4%    |
| Acer                    | 44        | 2.4%    |
| Apple                   | 39        | 2.13%   |
| Lenovo                  | 37        | 2.02%   |
| Ancor Communications    | 30        | 1.64%   |
| PANDA                   | 27        | 1.47%   |
| ViewSonic               | 22        | 1.2%    |
| CSO                     | 21        | 1.15%   |
| InfoVision              | 18        | 0.98%   |
| Iiyama                  | 18        | 0.98%   |
| ASUSTek Computer        | 15        | 0.82%   |
| MSI                     | 12        | 0.65%   |
| Chi Mei Optoelectronics | 12        | 0.65%   |
| TMX                     | 11        | 0.6%    |
| Gigabyte Technology     | 10        | 0.55%   |
| Sceptre Tech            | 8         | 0.44%   |
| Sony                    | 6         | 0.33%   |
| Vizio                   | 5         | 0.27%   |
| Mi                      | 5         | 0.27%   |
| HannStar                | 5         | 0.27%   |
| Eizo                    | 5         | 0.27%   |
| NEC Computers           | 4         | 0.22%   |
| HUAWEI                  | 4         | 0.22%   |
| Toshiba                 | 3         | 0.16%   |
| ONN                     | 3         | 0.16%   |
| Medion                  | 3         | 0.16%   |
| JDI                     | 3         | 0.16%   |
| Unknown                 | 2         | 0.11%   |
| SKY                     | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 13        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 12        | 0.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 0.53%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 9         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.42%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 8         | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.42%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.37%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 7         | 0.37%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 7         | 0.37%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 7         | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 6         | 0.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 6         | 0.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 6         | 0.32%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.26%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 5         | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.26%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.26%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.26%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 5         | 0.26%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 5         | 0.26%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 5         | 0.26%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 5         | 0.26%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5         | 0.26%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.21%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 4         | 0.21%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 4         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 4         | 0.21%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 881       | 50.52%  |
| 1366x768 (WXGA)    | 203       | 11.64%  |
| 3840x2160 (4K)     | 145       | 8.31%   |
| 2560x1440 (QHD)    | 122       | 7%      |
| 1920x1200 (WUXGA)  | 54        | 3.1%    |
| 1600x900 (HD+)     | 48        | 2.75%   |
| 3440x1440          | 47        | 2.69%   |
| 2560x1600          | 32        | 1.83%   |
| 1280x1024 (SXGA)   | 26        | 1.49%   |
| 2560x1080          | 20        | 1.15%   |
| 1440x900 (WXGA+)   | 19        | 1.09%   |
| 3840x2400          | 16        | 0.92%   |
| 1680x1050 (WSXGA+) | 16        | 0.92%   |
| 1280x800 (WXGA)    | 15        | 0.86%   |
| 2880x1800          | 12        | 0.69%   |
| 2160x1440          | 11        | 0.63%   |
| 2736x1824          | 9         | 0.52%   |
| 2256x1504          | 8         | 0.46%   |
| 1360x768           | 8         | 0.46%   |
| 3456x2160          | 5         | 0.29%   |
| 3200x2000          | 4         | 0.23%   |
| 3000x2000          | 4         | 0.23%   |
| 1920x540           | 4         | 0.23%   |
| 1600x1200          | 4         | 0.23%   |
| 3840x1600          | 3         | 0.17%   |
| 3840x1080          | 3         | 0.17%   |
| 3072x1920          | 3         | 0.17%   |
| 2520x1680          | 3         | 0.17%   |
| 2240x1400          | 3         | 0.17%   |
| 1024x768 (XGA)     | 3         | 0.17%   |
| 2288x1287          | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.06%   |
| 2400x1600          | 1         | 0.06%   |
| 2304x1440          | 1         | 0.06%   |
| 2200x1650          | 1         | 0.06%   |
| 2160x1200          | 1         | 0.06%   |
| 1920x550           | 1         | 0.06%   |
| 1640x2048          | 1         | 0.06%   |
| 1400x1050          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 434       | 23.48%  |
| 13      | 228       | 12.34%  |
| 14      | 211       | 11.42%  |
| 27      | 180       | 9.74%   |
| 24      | 132       | 7.14%   |
| 21      | 108       | 5.84%   |
| 23      | 106       | 5.74%   |
| 17      | 71        | 3.84%   |
| 31      | 62        | 3.35%   |
| 34      | 56        | 3.03%   |
| 12      | 34        | 1.84%   |
| 18      | 29        | 1.57%   |
| 16      | 25        | 1.35%   |
| 20      | 21        | 1.14%   |
| 19      | 18        | 0.97%   |
| 22      | 15        | 0.81%   |
| 11      | 14        | 0.76%   |
| 32      | 12        | 0.65%   |
| Unknown | 12        | 0.65%   |
| 84      | 7         | 0.38%   |
| 72      | 7         | 0.38%   |
| 40      | 7         | 0.38%   |
| 26      | 6         | 0.32%   |
| 25      | 6         | 0.32%   |
| 29      | 5         | 0.27%   |
| 54      | 4         | 0.22%   |
| 48      | 4         | 0.22%   |
| 37      | 4         | 0.22%   |
| 52      | 3         | 0.16%   |
| 39      | 3         | 0.16%   |
| 35      | 3         | 0.16%   |
| 10      | 3         | 0.16%   |
| 142     | 2         | 0.11%   |
| 100     | 2         | 0.11%   |
| 75      | 2         | 0.11%   |
| 69      | 2         | 0.11%   |
| 46      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 50      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 769       | 42.42%  |
| 501-600        | 383       | 21.13%  |
| 201-300        | 176       | 9.71%   |
| 401-500        | 175       | 9.65%   |
| 601-700        | 88        | 4.85%   |
| 351-400        | 84        | 4.63%   |
| 701-800        | 68        | 3.75%   |
| 1501-2000      | 18        | 0.99%   |
| 801-900        | 17        | 0.94%   |
| 1001-1500      | 14        | 0.77%   |
| Unknown        | 12        | 0.66%   |
| 901-1000       | 5         | 0.28%   |
| More than 2000 | 4         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1284      | 79.06%  |
| 16/10   | 191       | 11.76%  |
| 21/9    | 66        | 4.06%   |
| 3/2     | 38        | 2.34%   |
| 5/4     | 23        | 1.42%   |
| 4/3     | 9         | 0.55%   |
| 32/9    | 4         | 0.25%   |
| Unknown | 3         | 0.18%   |
| 6/5     | 2         | 0.12%   |
| 1.00    | 2         | 0.12%   |
| 1.96    | 1         | 0.06%   |
| 0.80    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 437       | 23.88%  |
| 81-90          | 338       | 18.47%  |
| 201-250        | 273       | 14.92%  |
| 301-350        | 187       | 10.22%  |
| 351-500        | 135       | 7.38%   |
| 71-80          | 106       | 5.79%   |
| 151-200        | 77        | 4.21%   |
| 121-130        | 56        | 3.06%   |
| 251-300        | 49        | 2.68%   |
| 141-150        | 34        | 1.86%   |
| More than 1000 | 31        | 1.69%   |
| 61-70          | 25        | 1.37%   |
| 501-1000       | 23        | 1.26%   |
| 111-120        | 22        | 1.2%    |
| 51-60          | 14        | 0.77%   |
| Unknown        | 12        | 0.66%   |
| 131-140        | 5         | 0.27%   |
| 41-50          | 3         | 0.16%   |
| 91-100         | 3         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 621       | 34.65%  |
| 51-100        | 474       | 26.45%  |
| 101-120       | 380       | 21.21%  |
| 161-240       | 203       | 11.33%  |
| More than 240 | 77        | 4.3%    |
| 1-50          | 25        | 1.4%    |
| Unknown       | 12        | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1219      | 76.09%  |
| 2     | 300       | 18.73%  |
| 0     | 39        | 2.43%   |
| 3     | 35        | 2.18%   |
| 4     | 8         | 0.5%    |
| 5     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 903       | 38.89%  |
| Realtek Semiconductor             | 827       | 35.62%  |
| Qualcomm Atheros                  | 176       | 7.58%   |
| Broadcom                          | 82        | 3.53%   |
| MediaTek                          | 69        | 2.97%   |
| TP-Link                           | 32        | 1.38%   |
| Broadcom Limited                  | 19        | 0.82%   |
| Ralink Technology                 | 13        | 0.56%   |
| Ralink                            | 12        | 0.52%   |
| Marvell Technology Group          | 12        | 0.52%   |
| Nvidia                            | 11        | 0.47%   |
| Qualcomm Atheros Communications   | 10        | 0.43%   |
| Lenovo                            | 10        | 0.43%   |
| ASIX Electronics                  | 10        | 0.43%   |
| Sierra Wireless                   | 9         | 0.39%   |
| Samsung Electronics               | 9         | 0.39%   |
| Microsoft                         | 9         | 0.39%   |
| Qualcomm                          | 8         | 0.34%   |
| Xiaomi                            | 7         | 0.3%    |
| Huawei Technologies               | 6         | 0.26%   |
| Aquantia                          | 6         | 0.26%   |
| Hewlett-Packard                   | 5         | 0.22%   |
| Ericsson Business Mobile Networks | 5         | 0.22%   |
| DisplayLink                       | 5         | 0.22%   |
| D-Link                            | 5         | 0.22%   |
| ASUSTek Computer                  | 5         | 0.22%   |
| Apple                             | 5         | 0.22%   |
| T & A Mobile Phones               | 4         | 0.17%   |
| Fibocom                           | 4         | 0.17%   |
| Mellanox Technologies             | 3         | 0.13%   |
| Edimax Technology                 | 3         | 0.13%   |
| Dell                              | 3         | 0.13%   |
| Belkin Components                 | 3         | 0.13%   |
| OPPO Electronics                  | 2         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.09%   |
| NetGear                           | 2         | 0.09%   |
| Motorola PCS                      | 2         | 0.09%   |
| MicroPython                       | 2         | 0.09%   |
| Microchip Technology              | 2         | 0.09%   |
| Google                            | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 504       | 18.2%   |
| Intel Wi-Fi 6 AX200                                               | 137       | 4.95%   |
| Intel Wi-Fi 6 AX201                                               | 93        | 3.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 69        | 2.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69        | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 2.31%   |
| Intel Wireless 8265 / 8275                                        | 59        | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 55        | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 50        | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 46        | 1.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 46        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 43        | 1.55%   |
| Intel Ethernet Controller I225-V                                  | 43        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 38        | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 34        | 1.23%   |
| Intel Wireless 7265                                               | 33        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 30        | 1.08%   |
| Intel Wireless 8260                                               | 29        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27        | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 26        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 0.87%   |
| Intel Wireless 3165                                               | 23        | 0.83%   |
| Intel Wireless-AC 9260                                            | 22        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 22        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 21        | 0.76%   |
| Intel Wireless 7260                                               | 21        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 20        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 20        | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.69%   |
| Realtek 802.11ac NIC                                              | 18        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 17        | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 16        | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 751       | 53.38%  |
| Realtek Semiconductor             | 233       | 16.56%  |
| Qualcomm Atheros                  | 151       | 10.73%  |
| MediaTek                          | 68        | 4.83%   |
| Broadcom                          | 66        | 4.69%   |
| TP-Link                           | 30        | 2.13%   |
| Broadcom Limited                  | 16        | 1.14%   |
| Ralink Technology                 | 13        | 0.92%   |
| Ralink                            | 12        | 0.85%   |
| Qualcomm Atheros Communications   | 10        | 0.71%   |
| Sierra Wireless                   | 9         | 0.64%   |
| Microsoft                         | 9         | 0.64%   |
| Marvell Technology Group          | 8         | 0.57%   |
| Qualcomm                          | 6         | 0.43%   |
| Fibocom                           | 4         | 0.28%   |
| D-Link                            | 4         | 0.28%   |
| ASUSTek Computer                  | 4         | 0.28%   |
| Edimax Technology                 | 3         | 0.21%   |
| Belkin Components                 | 3         | 0.21%   |
| NetGear                           | 2         | 0.14%   |
| PLANEX                            | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| Ericsson Business Mobile Networks | 1         | 0.07%   |
| Dell                              | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 137       | 9.72%   |
| Intel Wi-Fi 6 AX201                                            | 93        | 6.6%    |
| Intel Wireless 8265 / 8275                                     | 59        | 4.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 46        | 3.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 46        | 3.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 43        | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 38        | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 34        | 2.41%   |
| Intel Wireless 7265                                            | 33        | 2.34%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 30        | 2.13%   |
| Intel Wireless 8260                                            | 29        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 27        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 1.7%    |
| Intel Wireless 3165                                            | 23        | 1.63%   |
| Intel Wireless-AC 9260                                         | 22        | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 1.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 1.49%   |
| Intel Wireless 7260                                            | 21        | 1.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 1.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 20        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 1.42%   |
| Realtek 802.11ac NIC                                           | 18        | 1.28%   |
| Intel Centrino Ultimate-N 6300                                 | 17        | 1.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 16        | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 0.99%   |
| Intel Wireless 3160                                            | 13        | 0.92%   |
| MediaTek WLAN controller                                       | 12        | 0.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 10        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 0.64%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 9         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 9         | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 9         | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 719       | 55.39%  |
| Intel                             | 407       | 31.36%  |
| Qualcomm Atheros                  | 40        | 3.08%   |
| Broadcom                          | 31        | 2.39%   |
| Nvidia                            | 11        | 0.85%   |
| Lenovo                            | 10        | 0.77%   |
| ASIX Electronics                  | 10        | 0.77%   |
| Samsung Electronics               | 9         | 0.69%   |
| Xiaomi                            | 7         | 0.54%   |
| Aquantia                          | 6         | 0.46%   |
| DisplayLink                       | 5         | 0.39%   |
| Apple                             | 5         | 0.39%   |
| Marvell Technology Group          | 4         | 0.31%   |
| Huawei Technologies               | 4         | 0.31%   |
| TP-Link                           | 3         | 0.23%   |
| Broadcom Limited                  | 3         | 0.23%   |
| Qualcomm                          | 2         | 0.15%   |
| OPPO Electronics                  | 2         | 0.15%   |
| Motorola PCS                      | 2         | 0.15%   |
| Mellanox Technologies             | 2         | 0.15%   |
| Google                            | 2         | 0.15%   |
| T & A Mobile Phones               | 1         | 0.08%   |
| Sundance Technology Inc / IC Plus | 1         | 0.08%   |
| QNAP System                       | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.08%   |
| MosChip Semiconductor             | 1         | 0.08%   |
| Microchip Technology              | 1         | 0.08%   |
| MediaTek                          | 1         | 0.08%   |
| LG Electronics                    | 1         | 0.08%   |
| HMD Global                        | 1         | 0.08%   |
| Hewlett-Packard                   | 1         | 0.08%   |
| Davicom Semiconductor             | 1         | 0.08%   |
| D-Link                            | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |
| ADMtek                            | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 504       | 37.89%  |
| Realtek RTL8125 2.5GbE Controller                                 | 69        | 5.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69        | 5.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 4.81%   |
| Intel I211 Gigabit Network Connection                             | 55        | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 50        | 3.76%   |
| Intel Ethernet Controller I225-V                                  | 43        | 3.23%   |
| Intel Ethernet Connection (2) I219-V                              | 26        | 1.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.98%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 0.9%    |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 6         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 6         | 0.45%   |
| Intel Ethernet Connection (11) I219-LM                            | 6         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.38%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 5         | 0.38%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.38%   |
| Intel Ethernet Connection (11) I219-V                             | 5         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1345      | 52.38%  |
| Ethernet | 1195      | 46.53%  |
| Modem    | 22        | 0.86%   |
| Unknown  | 6         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1081      | 65.24%  |
| Ethernet | 575       | 34.7%   |
| Modem    | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 803       | 50.66%  |
| 1     | 704       | 44.42%  |
| 3     | 49        | 3.09%   |
| 0     | 26        | 1.64%   |
| 4     | 3         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1180      | 73.89%  |
| Yes  | 417       | 26.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 665       | 55.19%  |
| Realtek Semiconductor           | 139       | 11.54%  |
| Qualcomm Atheros Communications | 83        | 6.89%   |
| IMC Networks                    | 52        | 4.32%   |
| Cambridge Silicon Radio         | 47        | 3.9%    |
| Broadcom                        | 40        | 3.32%   |
| Foxconn / Hon Hai               | 39        | 3.24%   |
| Apple                           | 38        | 3.15%   |
| Lite-On Technology              | 25        | 2.07%   |
| ASUSTek Computer                | 18        | 1.49%   |
| Realtek                         | 10        | 0.83%   |
| MediaTek                        | 9         | 0.75%   |
| Marvell Semiconductor           | 9         | 0.75%   |
| TP-Link                         | 5         | 0.41%   |
| Toshiba                         | 5         | 0.41%   |
| Ralink                          | 5         | 0.41%   |
| Hewlett-Packard                 | 4         | 0.33%   |
| Dell                            | 4         | 0.33%   |
| Opticis                         | 2         | 0.17%   |
| USI                             | 1         | 0.08%   |
| SINO WEALTH                     | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| HTC (High Tech Computer)        | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 173       | 14.34%  |
| Intel AX201 Bluetooth                               | 163       | 13.52%  |
| Intel AX200 Bluetooth                               | 131       | 10.86%  |
| Realtek Bluetooth Radio                             | 104       | 8.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 82        | 6.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 47        | 3.9%    |
| Intel AX210 Bluetooth                               | 44        | 3.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 37        | 3.07%   |
| IMC Networks Wireless_Device                        | 28        | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 1.91%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 1.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.74%   |
| Intel Bluetooth Device                              | 18        | 1.49%   |
| Apple Bluetooth Host Controller                     | 17        | 1.41%   |
| Apple Bluetooth USB Host Controller                 | 15        | 1.24%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 0.91%   |
| Realtek Bluetooth Radio                             | 10        | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 9         | 0.75%   |
| MediaTek Wireless_Device                            | 9         | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.58%   |
| Lite-On Bluetooth Device                            | 6         | 0.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.5%    |
| Broadcom HP Portable SoftSailing                    | 6         | 0.5%    |
| TP-Link UB500 Adapter                               | 5         | 0.41%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.41%   |
| Lite-On Wireless_Device                             | 5         | 0.41%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 5         | 0.41%   |
| ASUS Bluetooth Radio                                | 5         | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.33%   |
| IMC Networks Bluetooth Device                       | 4         | 0.33%   |
| ASUS ASUS USB-BT500                                 | 4         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 1055      | 44.84%  |
| AMD                         | 565       | 24.01%  |
| Nvidia                      | 384       | 16.32%  |
| C-Media Electronics         | 45        | 1.91%   |
| Logitech                    | 23        | 0.98%   |
| Realtek Semiconductor       | 15        | 0.64%   |
| Lenovo                      | 14        | 0.59%   |
| JMTek                       | 12        | 0.51%   |
| Creative Technology         | 12        | 0.51%   |
| Texas Instruments           | 11        | 0.47%   |
| Plantronics                 | 11        | 0.47%   |
| XMOS                        | 10        | 0.42%   |
| GN Netcom                   | 10        | 0.42%   |
| Creative Labs               | 10        | 0.42%   |
| Corsair                     | 10        | 0.42%   |
| Focusrite-Novation          | 8         | 0.34%   |
| Samson Technologies         | 7         | 0.3%    |
| Razer USA                   | 7         | 0.3%    |
| Kingston Technology         | 7         | 0.3%    |
| Hewlett-Packard             | 7         | 0.3%    |
| Generalplus Technology      | 7         | 0.3%    |
| SteelSeries ApS             | 6         | 0.25%   |
| Conexant Systems            | 6         | 0.25%   |
| ASUSTek Computer            | 6         | 0.25%   |
| Sony                        | 5         | 0.21%   |
| Blue Microphones            | 5         | 0.21%   |
| Micro Star International    | 4         | 0.17%   |
| FiiO Electronics Technology | 4         | 0.17%   |
| Apple                       | 4         | 0.17%   |
| PreSonus Audio Electronics  | 3         | 0.13%   |
| Dell                        | 3         | 0.13%   |
| ZOOM                        | 2         | 0.08%   |
| Yamaha                      | 2         | 0.08%   |
| Tenx Technology             | 2         | 0.08%   |
| Sennheiser Communications   | 2         | 0.08%   |
| Schiit Audio                | 2         | 0.08%   |
| Samsung Electronics         | 2         | 0.08%   |
| RODE Microphones            | 2         | 0.08%   |
| No brand                    | 2         | 0.08%   |
| Native Instruments          | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 263       | 9.14%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 162       | 5.63%   |
| Intel Sunrise Point-LP HD Audio                                            | 139       | 4.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 118       | 4.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 110       | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 81        | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 67        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 66        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 65        | 2.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 63        | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 58        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 53        | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 48        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 46        | 1.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 41        | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 40        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 39        | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 37        | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 37        | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 36        | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                              | 35        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 33        | 1.15%   |
| Intel Broadwell-U Audio Controller                                         | 29        | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 28        | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 28        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 28        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 27        | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 25        | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25        | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 25        | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 24        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 24        | 0.83%   |
| AMD Navi 10 HDMI Audio                                                     | 23        | 0.8%    |
| AMD FCH Azalia Controller                                                  | 23        | 0.8%    |
| Intel Alder Lake-S HD Audio Controller                                     | 22        | 0.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 21        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 215       | 23.92%  |
| SK hynix                                         | 158       | 17.58%  |
| Micron Technology                                | 117       | 13.01%  |
| Kingston                                         | 87        | 9.68%   |
| Crucial                                          | 65        | 7.23%   |
| Unknown                                          | 49        | 5.45%   |
| G.Skill                                          | 41        | 4.56%   |
| Corsair                                          | 40        | 4.45%   |
| A-DATA Technology                                | 19        | 2.11%   |
| Ramaxel Technology                               | 16        | 1.78%   |
| Unknown (ABCD)                                   | 14        | 1.56%   |
| Team                                             | 13        | 1.45%   |
| Patriot                                          | 11        | 1.22%   |
| Unknown                                          | 10        | 1.11%   |
| Nanya Technology                                 | 7         | 0.78%   |
| Smart                                            | 5         | 0.56%   |
| Elpida                                           | 5         | 0.56%   |
| PNY                                              | 3         | 0.33%   |
| Silicon Power                                    | 2         | 0.22%   |
| Atermiter                                        | 2         | 0.22%   |
| AMD                                              | 2         | 0.22%   |
| V-GeN                                            | 1         | 0.11%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.11%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.11%   |
| Timetec                                          | 1         | 0.11%   |
| Smart Brazil                                     | 1         | 0.11%   |
| Sesame                                           | 1         | 0.11%   |
| Samsung 1                                        | 1         | 0.11%   |
| Qimonda                                          | 1         | 0.11%   |
| PUSKILL                                          | 1         | 0.11%   |
| Neo Forza                                        | 1         | 0.11%   |
| Mushkin                                          | 1         | 0.11%   |
| Mircon                                           | 1         | 0.11%   |
| Kllisre                                          | 1         | 0.11%   |
| Hikvision                                        | 1         | 0.11%   |
| GOODRAM                                          | 1         | 0.11%   |
| Goldkey                                          | 1         | 0.11%   |
| ChangXin Memory                                  | 1         | 0.11%   |
| A-TECH                                           | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.6%    |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 12        | 1.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 1.28%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 11        | 1.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.07%   |
| Unknown                                                          | 10        | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 9         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.96%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 7         | 0.75%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.53%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.53%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.53%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 5         | 0.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.43%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.43%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.43%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 4         | 0.43%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.43%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 4         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 3         | 0.32%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.32%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.32%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 452       | 58.63%  |
| DDR3    | 178       | 23.09%  |
| LPDDR4  | 60        | 7.78%   |
| LPDDR3  | 25        | 3.24%   |
| Unknown | 21        | 2.72%   |
| LPDDR5  | 12        | 1.56%   |
| DDR5    | 9         | 1.17%   |
| DDR2    | 7         | 0.91%   |
| SDRAM   | 5         | 0.65%   |
| DDR     | 2         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 452       | 57.58%  |
| DIMM         | 210       | 26.75%  |
| Row Of Chips | 114       | 14.52%  |
| Chip         | 5         | 0.64%   |
| RIMM         | 2         | 0.25%   |
| Unknown      | 2         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 324       | 39.42%  |
| 4096  | 233       | 28.35%  |
| 16384 | 150       | 18.25%  |
| 2048  | 62        | 7.54%   |
| 32768 | 40        | 4.87%   |
| 1024  | 11        | 1.34%   |
| 3072  | 2         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 220       | 26.96%  |
| 1600    | 136       | 16.67%  |
| 2667    | 116       | 14.22%  |
| 2400    | 49        | 6%      |
| 2133    | 48        | 5.88%   |
| 4267    | 31        | 3.8%    |
| 3600    | 29        | 3.55%   |
| 1333    | 24        | 2.94%   |
| 1867    | 19        | 2.33%   |
| 6400    | 14        | 1.72%   |
| 4800    | 13        | 1.59%   |
| 1334    | 11        | 1.35%   |
| 3266    | 9         | 1.1%    |
| 1067    | 9         | 1.1%    |
| 667     | 7         | 0.86%   |
| Unknown | 7         | 0.86%   |
| 3733    | 6         | 0.74%   |
| 3466    | 6         | 0.74%   |
| 3000    | 6         | 0.74%   |
| 2933    | 6         | 0.74%   |
| 8400    | 5         | 0.61%   |
| 2666    | 5         | 0.61%   |
| 4266    | 4         | 0.49%   |
| 3400    | 4         | 0.49%   |
| 800     | 4         | 0.49%   |
| 3866    | 3         | 0.37%   |
| 400     | 3         | 0.37%   |
| 3800    | 2         | 0.25%   |
| 3100    | 2         | 0.25%   |
| 2800    | 2         | 0.25%   |
| 2048    | 2         | 0.25%   |
| 1066    | 2         | 0.25%   |
| 5200    | 1         | 0.12%   |
| 3467    | 1         | 0.12%   |
| 3333    | 1         | 0.12%   |
| 3067    | 1         | 0.12%   |
| 2733    | 1         | 0.12%   |
| 2600    | 1         | 0.12%   |
| 1800    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 7         | 31.82%  |
| Hewlett-Packard     | 5         | 22.73%  |
| Canon               | 3         | 13.64%  |
| Seiko Epson         | 2         | 9.09%   |
| Samsung Electronics | 1         | 4.55%   |
| Prolific Technology | 1         | 4.55%   |
| NXP Semiconductors  | 1         | 4.55%   |
| Kyocera             | 1         | 4.55%   |
| Graphtec America    | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson L3110 Series          | 1         | 4.55%   |
| Seiko Epson L300 Series           | 1         | 4.55%   |
| Samsung M2070 Series              | 1         | 4.55%   |
| Prolific PL2305 Parallel Port     | 1         | 4.55%   |
| NXP Semiconductors Printer-80     | 1         | 4.55%   |
| Kyocera ECOSYS M5521cdw           | 1         | 4.55%   |
| HP Neverstop Laser 100x           | 1         | 4.55%   |
| HP LaserJet 1150                  | 1         | 4.55%   |
| HP Ink Tank 310 series            | 1         | 4.55%   |
| HP DeskJet 3700 series            | 1         | 4.55%   |
| HP DeskJet 3630 series            | 1         | 4.55%   |
| Graphtec America Graphtec Printer | 1         | 4.55%   |
| Canon TR150 series                | 1         | 4.55%   |
| Canon PIXMA MG3500 Series         | 1         | 4.55%   |
| Canon LiDE 300                    | 1         | 4.55%   |
| Brother Printer                   | 1         | 4.55%   |
| Brother MFC-9330CDW               | 1         | 4.55%   |
| Brother HL-1110 series            | 1         | 4.55%   |
| Brother DCP-T510W                 | 1         | 4.55%   |
| Brother DCP-T220                  | 1         | 4.55%   |
| Brother DCP-L2530DW series        | 1         | 4.55%   |
| Brother DCP-7055W                 | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 71.43%  |
| Seiko Epson | 2         | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                                 | 2         | 28.57%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 14.29%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                 | 1         | 14.29%  |
| Canon CanoScan LiDE 210                                 | 1         | 14.29%  |
| Canon CanoScan LiDE 200                                 | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 232       | 20.73%  |
| IMC Networks                           | 134       | 11.97%  |
| Microdia                               | 88        | 7.86%   |
| Realtek Semiconductor                  | 85        | 7.6%    |
| Acer                                   | 84        | 7.51%   |
| Logitech                               | 78        | 6.97%   |
| Quanta                                 | 67        | 5.99%   |
| Sunplus Innovation Technology          | 53        | 4.74%   |
| Cheng Uei Precision Industry (Foxlink) | 42        | 3.75%   |
| Apple                                  | 38        | 3.4%    |
| Syntek                                 | 37        | 3.31%   |
| Luxvisions Innotech Limited            | 28        | 2.5%    |
| Lite-On Technology                     | 24        | 2.14%   |
| Suyin                                  | 13        | 1.16%   |
| Microsoft                              | 12        | 1.07%   |
| Ricoh                                  | 9         | 0.8%    |
| Silicon Motion                         | 8         | 0.71%   |
| Samsung Electronics                    | 8         | 0.71%   |
| KYE Systems (Mouse Systems)            | 8         | 0.71%   |
| SunplusIT                              | 7         | 0.63%   |
| Lenovo                                 | 7         | 0.63%   |
| Primax Electronics                     | 6         | 0.54%   |
| Alcor Micro                            | 6         | 0.54%   |
| icSpring                               | 4         | 0.36%   |
| Sonix Technology                       | 3         | 0.27%   |
| Hewlett-Packard                        | 3         | 0.27%   |
| Generalplus Technology                 | 3         | 0.27%   |
| Unknown                                | 2         | 0.18%   |
| MacroSilicon                           | 2         | 0.18%   |
| Intel                                  | 2         | 0.18%   |
| Creative Technology                    | 2         | 0.18%   |
| BKX-210918                             | 2         | 0.18%   |
| Asuscom Network                        | 2         | 0.18%   |
| ARC International                      | 2         | 0.18%   |
| Z-Star Microelectronics                | 1         | 0.09%   |
| Y Media                                | 1         | 0.09%   |
| Xiaomi                                 | 1         | 0.09%   |
| USB Camera CS                          | 1         | 0.09%   |
| ShineTech                              | 1         | 0.09%   |
| Razer USA                              | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 74        | 6.53%   |
| IMC Networks Integrated Camera                       | 57        | 5.03%   |
| Microdia Integrated_Webcam_HD                        | 54        | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 44        | 3.88%   |
| Realtek Integrated_Webcam_HD                         | 38        | 3.35%   |
| Acer Integrated Camera                               | 33        | 2.91%   |
| Syntek Integrated Camera                             | 28        | 2.47%   |
| Chicony HD Webcam                                    | 26        | 2.29%   |
| Logitech HD Pro Webcam C920                          | 21        | 1.85%   |
| Chicony HP Wide Vision HD Camera                     | 16        | 1.41%   |
| Sunplus Integrated_Webcam_HD                         | 14        | 1.23%   |
| Quanta HD User Facing                                | 14        | 1.23%   |
| Chicony Integrated Camera (1280x720@30)              | 13        | 1.15%   |
| Logitech Webcam C270                                 | 12        | 1.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 12        | 1.06%   |
| Apple FaceTime HD Camera (Built-in)                  | 12        | 1.06%   |
| Chicony HP HD Camera                                 | 11        | 0.97%   |
| Quanta HP HD Camera                                  | 10        | 0.88%   |
| Lite-On Integrated Camera                            | 10        | 0.88%   |
| Apple iPhone5/5C/5S/6                                | 10        | 0.88%   |
| Acer HD Webcam                                       | 10        | 0.88%   |
| Quanta HP TrueVision HD Camera                       | 9         | 0.79%   |
| Chicony HP Truevision HD camera                      | 9         | 0.79%   |
| Samsung Galaxy A5 (MTP)                              | 8         | 0.71%   |
| Apple Built-in iSight                                | 8         | 0.71%   |
| Acer Lenovo EasyCamera                               | 8         | 0.71%   |
| Sunplus HD 720P webcam                               | 7         | 0.62%   |
| Microdia Webcam Vitade AF                            | 7         | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 7         | 0.62%   |
| Logitech C920 PRO HD Webcam                          | 7         | 0.62%   |
| Chicony USB 2.0 Camera                               | 7         | 0.62%   |
| Chicony EasyCamera                                   | 7         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 7         | 0.62%   |
| Quanta USB2.0 HD UVC WebCam                          | 6         | 0.53%   |
| Primax HP HD Webcam [Fixed]                          | 6         | 0.53%   |
| Luxvisions Innotech Limited Integrated Camera        | 6         | 0.53%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 6         | 0.53%   |
| Lite-On HP Wide Vision HD Camera                     | 6         | 0.53%   |
| IMC Networks HD Camera                               | 6         | 0.53%   |
| Chicony USB2.0 HD UVC WebCam                         | 6         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 102       | 37.5%   |
| Shenzhen Goodix Technology | 62        | 22.79%  |
| Validity Sensors           | 60        | 22.06%  |
| Elan Microelectronics      | 16        | 5.88%   |
| LighTuning Technology      | 11        | 4.04%   |
| Upek                       | 9         | 3.31%   |
| AuthenTec                  | 6         | 2.21%   |
| Focal-systems.Corp         | 3         | 1.1%    |
| DigitalPersona             | 2         | 0.74%   |
| Dell                       | 1         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 13.97%  |
| Shenzhen Goodix  Fingerprint Device                                        | 32        | 11.76%  |
| Unknown                                                                    | 30        | 11.03%  |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 7.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 5.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 4.78%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.68%   |
| Validity Sensors VFS491                                                    | 9         | 3.31%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 3.31%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 3.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.57%   |
| Synaptics  WBDI                                                            | 7         | 2.57%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.21%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.21%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.84%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.84%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.1%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.1%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.74%   |
| Synaptics WBDI Device                                                      | 2         | 0.74%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.74%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.37%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.37%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.37%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.37%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.37%   |
| AuthenTec AES2810                                                          | 1         | 0.37%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.37%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.37%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 37        | 44.05%  |
| Broadcom                   | 28        | 33.33%  |
| Upek                       | 5         | 5.95%   |
| Lenovo                     | 3         | 3.57%   |
| SCM Microsystems           | 2         | 2.38%   |
| OmniKey                    | 2         | 2.38%   |
| O2 Micro                   | 2         | 2.38%   |
| Yubico.com                 | 1         | 1.19%   |
| Realtek Semiconductor      | 1         | 1.19%   |
| Gemalto (was Gemplus)      | 1         | 1.19%   |
| Athena Smartcard Solutions | 1         | 1.19%   |
| Aktiv                      | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 41.67%  |
| Broadcom 58200                                                               | 11        | 13.1%   |
| Broadcom 5880                                                                | 7         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.95%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.57%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 2.38%   |
| OmniKey CardMan 1021                                                         | 2         | 2.38%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.19%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.19%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.19%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.19%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.19%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.19%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.19%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.19%   |
| Aktiv Rutoken lite                                                           | 1         | 1.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1028      | 64.21%  |
| 1     | 467       | 29.17%  |
| 2     | 87        | 5.43%   |
| 3     | 14        | 0.87%   |
| 4     | 2         | 0.12%   |
| 8     | 1         | 0.06%   |
| 7     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 267       | 39.97%  |
| Graphics card            | 133       | 19.91%  |
| Multimedia controller    | 75        | 11.23%  |
| Net/wireless             | 73        | 10.93%  |
| Camera                   | 31        | 4.64%   |
| Chipcard                 | 17        | 2.54%   |
| Bluetooth                | 16        | 2.4%    |
| Sound                    | 9         | 1.35%   |
| Network                  | 9         | 1.35%   |
| Card reader              | 9         | 1.35%   |
| Storage                  | 7         | 1.05%   |
| Communication controller | 6         | 0.9%    |
| Modem                    | 5         | 0.75%   |
| Unassigned class         | 4         | 0.6%    |
| Net/ethernet             | 3         | 0.45%   |
| Storage/raid             | 2         | 0.3%    |
| Wireless                 | 1         | 0.15%   |
| Firewire controller      | 1         | 0.15%   |

