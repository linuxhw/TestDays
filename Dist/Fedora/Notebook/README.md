Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 7304

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MICROMAX      | Canvas Lapbook L1161        | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Timi          | A35S                        | [c46c820c25](https://linux-hardware.org/?probe=c46c820c25) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [41dc234b26](https://linux-hardware.org/?probe=41dc234b26) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| SK hynix      | HyBook                      | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| MSI           | GT72 6QE                    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| AZW           | SEi                         | [055096f57a](https://linux-hardware.org/?probe=055096f57a) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| Framework     | Laptop                      | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| HP            | Pavilion 17                 | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| HP            | Pavilion Power Laptop 15... | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| HP            | ENVY 15                     | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| HUAWEI        | WRT-WX9                     | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| Dell          | Precision 5560              | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Dell          | Latitude 5420               | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Unknown       | Unknown                     | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| Irbis         | NB264                       | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| Apple         | MacBookPro16,1              | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Dell          | G3 3779                     | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [930ee68921](https://linux-hardware.org/?probe=930ee68921) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| Dell          | Precision 5560              | [78809c82c2](https://linux-hardware.org/?probe=78809c82c2) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Dell          | Latitude 5495               | [23586ab4ef](https://linux-hardware.org/?probe=23586ab4ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad P1 20MD0014RT      | [4935debbce](https://linux-hardware.org/?probe=4935debbce) | Sep 12, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| AZW           | SEi                         | [3a4d2086b0](https://linux-hardware.org/?probe=3a4d2086b0) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [5bbf96fe23](https://linux-hardware.org/?probe=5bbf96fe23) | Sep 12, 2022 |
| HP            | ProBook 4540s               | [1f46e342f0](https://linux-hardware.org/?probe=1f46e342f0) | Sep 12, 2022 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [d05595b19e](https://linux-hardware.org/?probe=d05595b19e) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [edb2842417](https://linux-hardware.org/?probe=edb2842417) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [c6df51fa3b](https://linux-hardware.org/?probe=c6df51fa3b) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | ProBook 6570b               | [998630e822](https://linux-hardware.org/?probe=998630e822) | Sep 10, 2022 |
| Apple         | MacBookPro12,1              | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [8fb4287325](https://linux-hardware.org/?probe=8fb4287325) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [0a7b65b735](https://linux-hardware.org/?probe=0a7b65b735) | Sep 09, 2022 |
| Dell          | Inspiron 3543               | [7fc528e246](https://linux-hardware.org/?probe=7fc528e246) | Sep 09, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| Dell          | XPS 15 9570                 | [a54dae9e4b](https://linux-hardware.org/?probe=a54dae9e4b) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | [9f2534b22e](https://linux-hardware.org/?probe=9f2534b22e) | Sep 09, 2022 |
| Notebook      | W230SS                      | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8242cc3cab](https://linux-hardware.org/?probe=8242cc3cab) | Sep 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| Dell          | Latitude E5450              | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [0bcf279fb8](https://linux-hardware.org/?probe=0bcf279fb8) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Dell          | XPS 13 9305                 | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| Dell          | XPS 13 7390                 | [f91eeba2bd](https://linux-hardware.org/?probe=f91eeba2bd) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| Dell          | Latitude E6420              | [8885f409d8](https://linux-hardware.org/?probe=8885f409d8) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [a90b385c8e](https://linux-hardware.org/?probe=a90b385c8e) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7a3494a230](https://linux-hardware.org/?probe=7a3494a230) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [826deb0c55](https://linux-hardware.org/?probe=826deb0c55) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bffe658238](https://linux-hardware.org/?probe=bffe658238) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b327372b50](https://linux-hardware.org/?probe=b327372b50) | Sep 05, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [3969240177](https://linux-hardware.org/?probe=3969240177) | Sep 05, 2022 |
| Dell          | Inspiron 16 5625            | [d38282759b](https://linux-hardware.org/?probe=d38282759b) | Sep 05, 2022 |
| Notebook      | NJ5x_NJ7xLU                 | [1cadc455a1](https://linux-hardware.org/?probe=1cadc455a1) | Sep 05, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Dell          | Latitude 5511               | [3193c29c67](https://linux-hardware.org/?probe=3193c29c67) | Sep 04, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [57f8a4e96b](https://linux-hardware.org/?probe=57f8a4e96b) | Sep 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f0bcadac2f](https://linux-hardware.org/?probe=f0bcadac2f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 2320HPU       | [a8ba64ec12](https://linux-hardware.org/?probe=a8ba64ec12) | Sep 04, 2022 |
| HUAWEI        | KLVD-WXX9                   | [cc383de755](https://linux-hardware.org/?probe=cc383de755) | Sep 04, 2022 |
| Lenovo        | ThinkPad E560 20EV000RGE    | [5b69ce9986](https://linux-hardware.org/?probe=5b69ce9986) | Sep 04, 2022 |
| Acer          | AS VN7-571G                 | [1c14fbaf96](https://linux-hardware.org/?probe=1c14fbaf96) | Sep 04, 2022 |
| Dell          | Latitude 5420               | [b236b791c1](https://linux-hardware.org/?probe=b236b791c1) | Sep 04, 2022 |
| Lenovo        | 3000 N200 0769BAG           | [33fcb3e2b3](https://linux-hardware.org/?probe=33fcb3e2b3) | Sep 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c4db289b99](https://linux-hardware.org/?probe=c4db289b99) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [dc3fd2d992](https://linux-hardware.org/?probe=dc3fd2d992) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Dell          | Vostro 1320                 | [e66853cc37](https://linux-hardware.org/?probe=e66853cc37) | Sep 03, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| ASUSTek       | UX310UQK                    | [ed392e6b79](https://linux-hardware.org/?probe=ed392e6b79) | Sep 03, 2022 |
| ASUSTek       | GL503VM                     | [43cbef1764](https://linux-hardware.org/?probe=43cbef1764) | Sep 03, 2022 |
| MSI           | GP72MVR 7RFX                | [f370d7bbc3](https://linux-hardware.org/?probe=f370d7bbc3) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | [b73e153667](https://linux-hardware.org/?probe=b73e153667) | Sep 03, 2022 |
| HP            | Stream Notebook PC 13       | [d6c9e33a55](https://linux-hardware.org/?probe=d6c9e33a55) | Sep 03, 2022 |
| MSI           | Modern 14 B11MOL            | [92d3e81be7](https://linux-hardware.org/?probe=92d3e81be7) | Sep 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [cec0b91aa9](https://linux-hardware.org/?probe=cec0b91aa9) | Sep 03, 2022 |
| Toshiba       | Satellite C850-C5K          | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001JIX     | [30eb9dcb39](https://linux-hardware.org/?probe=30eb9dcb39) | Sep 03, 2022 |
| Alienware     | 14                          | [f30f3ddf3d](https://linux-hardware.org/?probe=f30f3ddf3d) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [33ae7d4c4b](https://linux-hardware.org/?probe=33ae7d4c4b) | Sep 03, 2022 |
| Acer          | Swift SF315-41              | [634777751a](https://linux-hardware.org/?probe=634777751a) | Sep 02, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [006c26eaa0](https://linux-hardware.org/?probe=006c26eaa0) | Sep 02, 2022 |
| Acer          | Swift SF315-41              | [dd250df1ef](https://linux-hardware.org/?probe=dd250df1ef) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | G50-45 80E3                 | [a8e1884f32](https://linux-hardware.org/?probe=a8e1884f32) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [5730a9015f](https://linux-hardware.org/?probe=5730a9015f) | Sep 02, 2022 |
| Dell          | Inspiron 5558               | [203baa4d7f](https://linux-hardware.org/?probe=203baa4d7f) | Sep 02, 2022 |
| Dell          | Latitude E6400              | [c781ec4733](https://linux-hardware.org/?probe=c781ec4733) | Sep 02, 2022 |
| Chuwi         | HeroBook Air                | [1ac18273da](https://linux-hardware.org/?probe=1ac18273da) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| HP            | ProBook 4540s               | [b5e6fa5a71](https://linux-hardware.org/?probe=b5e6fa5a71) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b6b7c6dc62](https://linux-hardware.org/?probe=b6b7c6dc62) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [6b3c188071](https://linux-hardware.org/?probe=6b3c188071) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b0d6660da8](https://linux-hardware.org/?probe=b0d6660da8) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| Dell          | Latitude 7430               | [8876fb0448](https://linux-hardware.org/?probe=8876fb0448) | Aug 31, 2022 |
| Eluktronic... | MAG-15 2070                 | [d7fb373622](https://linux-hardware.org/?probe=d7fb373622) | Aug 31, 2022 |
| ASUSTek       | K401UQK                     | [4f026584d7](https://linux-hardware.org/?probe=4f026584d7) | Aug 31, 2022 |
| Dell          | Latitude E5570              | [91513d0ee3](https://linux-hardware.org/?probe=91513d0ee3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [b9d306c31b](https://linux-hardware.org/?probe=b9d306c31b) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Acer          | TMP453-MG                   | [63efab9aef](https://linux-hardware.org/?probe=63efab9aef) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| HP            | 250 G7 Notebook PC          | [96a56c7cb9](https://linux-hardware.org/?probe=96a56c7cb9) | Aug 30, 2022 |
| Dell          | Inspiron 15 5510            | [346eda373e](https://linux-hardware.org/?probe=346eda373e) | Aug 29, 2022 |
| Dell          | Inspiron 15 5510            | [ecdb2875da](https://linux-hardware.org/?probe=ecdb2875da) | Aug 29, 2022 |
| Dell          | Inspiron 5721               | [d483434965](https://linux-hardware.org/?probe=d483434965) | Aug 29, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [473daa5ce3](https://linux-hardware.org/?probe=473daa5ce3) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| MSI           | Prestige 14Evo A11MO        | [22cf60f50b](https://linux-hardware.org/?probe=22cf60f50b) | Aug 29, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [f921aef61e](https://linux-hardware.org/?probe=f921aef61e) | Aug 29, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [d82227c6d3](https://linux-hardware.org/?probe=d82227c6d3) | Aug 29, 2022 |
| Dell          | Precision 5750              | [2ee41b471e](https://linux-hardware.org/?probe=2ee41b471e) | Aug 28, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Dell          | Precision 5750              | [af9992756f](https://linux-hardware.org/?probe=af9992756f) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [589154a65e](https://linux-hardware.org/?probe=589154a65e) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [af00be0ff8](https://linux-hardware.org/?probe=af00be0ff8) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| Apple         | MacBookPro8,1               | [5efa863ca3](https://linux-hardware.org/?probe=5efa863ca3) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [64cefbec58](https://linux-hardware.org/?probe=64cefbec58) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Acidanther... | MacBookPro12,1              | [9e48c5e245](https://linux-hardware.org/?probe=9e48c5e245) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [559d6f0e42](https://linux-hardware.org/?probe=559d6f0e42) | Aug 27, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [f4dd9de519](https://linux-hardware.org/?probe=f4dd9de519) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| Lenovo        | G50-45 80E3                 | [be9921e0e0](https://linux-hardware.org/?probe=be9921e0e0) | Aug 27, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| HP            | EliteBook 840 G5            | [7bd19ce9a1](https://linux-hardware.org/?probe=7bd19ce9a1) | Aug 27, 2022 |
| Exo           | Smart Serie L               | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| HP            | ProBook 4530s               | [be1270c998](https://linux-hardware.org/?probe=be1270c998) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Dell          | Inspiron 3593               | [c3ae4b86ac](https://linux-hardware.org/?probe=c3ae4b86ac) | Aug 26, 2022 |
| HP            | ENVY 15                     | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| MSI           | Modern 14 A10RAS            | [af216b7b4a](https://linux-hardware.org/?probe=af216b7b4a) | Aug 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [2b52864870](https://linux-hardware.org/?probe=2b52864870) | Aug 25, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| HP            | Pavilion dv6                | [7fd7791035](https://linux-hardware.org/?probe=7fd7791035) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [fd6ff49314](https://linux-hardware.org/?probe=fd6ff49314) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | [f8213e35a4](https://linux-hardware.org/?probe=f8213e35a4) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [f9090c46a9](https://linux-hardware.org/?probe=f9090c46a9) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [ac93dd480f](https://linux-hardware.org/?probe=ac93dd480f) | Aug 24, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [2e88f854f8](https://linux-hardware.org/?probe=2e88f854f8) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Aquarius      | Cmp NS765                   | [991487a61b](https://linux-hardware.org/?probe=991487a61b) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [f25926e1fa](https://linux-hardware.org/?probe=f25926e1fa) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [784c6d89a6](https://linux-hardware.org/?probe=784c6d89a6) | Aug 22, 2022 |
| Apple         | MacBookPro11,2              | [9856ca2463](https://linux-hardware.org/?probe=9856ca2463) | Aug 21, 2022 |
| Acer          | TravelMate P215-52G         | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| Acer          | Aspire E1-522               | [f4f0162d9a](https://linux-hardware.org/?probe=f4f0162d9a) | Aug 21, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| Acer          | Popcorn                     | [1c3d0d6b87](https://linux-hardware.org/?probe=1c3d0d6b87) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HP            | ENVY Notebook               | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| HONOR         | NBD-WXX9                    | [1fdf41de8b](https://linux-hardware.org/?probe=1fdf41de8b) | Aug 20, 2022 |
| Dell          | Latitude E6430              | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| HP            | ProBook 655 G1              | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Toshiba       | Satellite C55-C             | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [ad8ec93f74](https://linux-hardware.org/?probe=ad8ec93f74) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [81be616c6b](https://linux-hardware.org/?probe=81be616c6b) | Aug 19, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| ASUSTek       | K45A                        | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| Acidanther... | MacBookPro12,1              | [6afa5c842e](https://linux-hardware.org/?probe=6afa5c842e) | Aug 18, 2022 |
| Acer          | Aspire A515-45              | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | [1bde57f974](https://linux-hardware.org/?probe=1bde57f974) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [cfc3d5853c](https://linux-hardware.org/?probe=cfc3d5853c) | Aug 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| ASUSTek       | K45A                        | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [8aea7a68ee](https://linux-hardware.org/?probe=8aea7a68ee) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| MSI           | Modern 14 B11SBL            | [ad56f2a352](https://linux-hardware.org/?probe=ad56f2a352) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Eluktronic... | MAX-17                      | [b0aec6f095](https://linux-hardware.org/?probe=b0aec6f095) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0793e37f62](https://linux-hardware.org/?probe=0793e37f62) | Aug 17, 2022 |
| HP            | Pavilion TS 14              | [145fc8369f](https://linux-hardware.org/?probe=145fc8369f) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Acer          | Aspire A715-42G             | [fbeff3bff5](https://linux-hardware.org/?probe=fbeff3bff5) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| HP            | Laptop 17-by0xxx            | [59db95ffee](https://linux-hardware.org/?probe=59db95ffee) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | [2b63761318](https://linux-hardware.org/?probe=2b63761318) | Aug 16, 2022 |
| Lenovo        | ThinkBook Plus 20TG         | [1f39fbc5a8](https://linux-hardware.org/?probe=1f39fbc5a8) | Aug 16, 2022 |
| Panasonic     | CFMX4-1                     | [01074aea14](https://linux-hardware.org/?probe=01074aea14) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| HP            | Pavilion TS 15              | [22194522c7](https://linux-hardware.org/?probe=22194522c7) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d9f8a6ea69](https://linux-hardware.org/?probe=d9f8a6ea69) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4f73fd7cf8](https://linux-hardware.org/?probe=4f73fd7cf8) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [e09e349f03](https://linux-hardware.org/?probe=e09e349f03) | Aug 15, 2022 |
| Itautec       | Infoway W7425               | [64b3153e8a](https://linux-hardware.org/?probe=64b3153e8a) | Aug 15, 2022 |
| Sony          | VPCS131FM                   | [22e32938e6](https://linux-hardware.org/?probe=22e32938e6) | Aug 14, 2022 |
| Toshiba       | TECRA R940                  | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| UNOWHY        | Y13G010S4EI                 | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | XPS 15 9550                 | [ad3ad84c75](https://linux-hardware.org/?probe=ad3ad84c75) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| AXDIA Inte... | WINPAD V10                  | [a44a9b065b](https://linux-hardware.org/?probe=a44a9b065b) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Dell          | Inspiron 13 5320            | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Unknown       | Unknown                     | [dbf529a586](https://linux-hardware.org/?probe=dbf529a586) | Aug 14, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [ca9974d27e](https://linux-hardware.org/?probe=ca9974d27e) | Aug 14, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [03089b1469](https://linux-hardware.org/?probe=03089b1469) | Aug 13, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Dell          | G3 3590                     | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 15 9510                 | [3cb2744dbe](https://linux-hardware.org/?probe=3cb2744dbe) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| HP            | ProBook 440 G7              | [ee57cf772f](https://linux-hardware.org/?probe=ee57cf772f) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| MSI           | MS-16F1                     | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | Pavilion 17                 | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Sony          | SVT15115CXS                 | [f7915ecf99](https://linux-hardware.org/?probe=f7915ecf99) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| Dell          | Latitude 5511               | [69ebaebf95](https://linux-hardware.org/?probe=69ebaebf95) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Acer          | Predator PH317-53           | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [05042a439b](https://linux-hardware.org/?probe=05042a439b) | Aug 11, 2022 |
| AZW           | SEi                         | [fb26f11a19](https://linux-hardware.org/?probe=fb26f11a19) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Dell          | XPS 13 7390                 | [149d92cd3e](https://linux-hardware.org/?probe=149d92cd3e) | Aug 10, 2022 |
| HP            | EliteBook 8460p             | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| Lenovo        | Z40-70 20366                | [2378dda760](https://linux-hardware.org/?probe=2378dda760) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5eec4d3ccf](https://linux-hardware.org/?probe=5eec4d3ccf) | Aug 10, 2022 |
| HUAWEI        | MACH-WX9                    | [18f9226bc0](https://linux-hardware.org/?probe=18f9226bc0) | Aug 09, 2022 |
| Timi          | TM1701                      | [676fc52004](https://linux-hardware.org/?probe=676fc52004) | Aug 09, 2022 |
| MSI           | Prestige 15 A10SC           | [9471547f71](https://linux-hardware.org/?probe=9471547f71) | Aug 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [1a95dd7974](https://linux-hardware.org/?probe=1a95dd7974) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Dell          | Precision 5510              | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [30a447f95c](https://linux-hardware.org/?probe=30a447f95c) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| Alienware     | x17 R2                      | [4e7fe87198](https://linux-hardware.org/?probe=4e7fe87198) | Aug 07, 2022 |
| Acer          | Aspire 7741                 | [bc1daa0005](https://linux-hardware.org/?probe=bc1daa0005) | Aug 07, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9d837de022](https://linux-hardware.org/?probe=9d837de022) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [438f5cce2a](https://linux-hardware.org/?probe=438f5cce2a) | Aug 07, 2022 |
| Toshiba       | Satellite Pro L300D         | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [572cb48d3c](https://linux-hardware.org/?probe=572cb48d3c) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| Dell          | Latitude E5550              | [c1d9204443](https://linux-hardware.org/?probe=c1d9204443) | Aug 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8f7a78b973](https://linux-hardware.org/?probe=8f7a78b973) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2eb53b5701](https://linux-hardware.org/?probe=2eb53b5701) | Aug 06, 2022 |
| Toshiba       | Satellite C55-C             | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| HP            | Laptop 17-by4xxx            | [7867c6d24c](https://linux-hardware.org/?probe=7867c6d24c) | Aug 05, 2022 |
| Acer          | Aspire 7741                 | [eae703cf6f](https://linux-hardware.org/?probe=eae703cf6f) | Aug 05, 2022 |
| Acer          | Aspire A515-51              | [6c5e2de730](https://linux-hardware.org/?probe=6c5e2de730) | Aug 05, 2022 |
| HP            | ZBook 15 G3                 | [d59939b336](https://linux-hardware.org/?probe=d59939b336) | Aug 05, 2022 |
| Acer          | Aspire V3-572               | [dadff5cef8](https://linux-hardware.org/?probe=dadff5cef8) | Aug 05, 2022 |
| Gateway       | NE56R                       | [44de22f108](https://linux-hardware.org/?probe=44de22f108) | Aug 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [ec2efe1636](https://linux-hardware.org/?probe=ec2efe1636) | Aug 04, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [503200514f](https://linux-hardware.org/?probe=503200514f) | Aug 04, 2022 |
| MSI           | Modern 14 A10M              | [f8a0b1d6e6](https://linux-hardware.org/?probe=f8a0b1d6e6) | Aug 04, 2022 |
| HP            | Snappy                      | [d5e91bd56c](https://linux-hardware.org/?probe=d5e91bd56c) | Aug 04, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| HP            | Snappy                      | [0a73175862](https://linux-hardware.org/?probe=0a73175862) | Aug 03, 2022 |
| HP            | Laptop 17-by4xxx            | [711cf515aa](https://linux-hardware.org/?probe=711cf515aa) | Aug 03, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Dell          | Inspiron 3521               | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 4290KJ6       | [ef5ee2a01e](https://linux-hardware.org/?probe=ef5ee2a01e) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | [492d014205](https://linux-hardware.org/?probe=492d014205) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| HP            | Laptop 15-db0xxx            | [ec7e5864c2](https://linux-hardware.org/?probe=ec7e5864c2) | Aug 02, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | ProBook 4540s               | [c96c493e64](https://linux-hardware.org/?probe=c96c493e64) | Aug 02, 2022 |
| Dell          | XPS 13 7390                 | [2aedd7bad4](https://linux-hardware.org/?probe=2aedd7bad4) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| ASUSTek       | X750JN                      | [b321cd29a8](https://linux-hardware.org/?probe=b321cd29a8) | Aug 02, 2022 |
| Dell          | Precision 5530              | [a5177f0edb](https://linux-hardware.org/?probe=a5177f0edb) | Aug 02, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3a496f366f](https://linux-hardware.org/?probe=3a496f366f) | Aug 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Dell          | Latitude D620               | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [85208906cd](https://linux-hardware.org/?probe=85208906cd) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [cd5aa49da7](https://linux-hardware.org/?probe=cd5aa49da7) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| HP            | 348 G4                      | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [066e5eb95d](https://linux-hardware.org/?probe=066e5eb95d) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| Clevo         | M570TU                      | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2773e9510b](https://linux-hardware.org/?probe=2773e9510b) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Notebook                    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| HP            | Pavilion Power Laptop 15... | [e4de7eb090](https://linux-hardware.org/?probe=e4de7eb090) | Jul 26, 2022 |
| Dell          | Latitude E6520              | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Dell          | Latitude E6520              | [0675bbd9d0](https://linux-hardware.org/?probe=0675bbd9d0) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| HP            | Pavilion Power Laptop 15... | [5007f1aa43](https://linux-hardware.org/?probe=5007f1aa43) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [6a1cb48f15](https://linux-hardware.org/?probe=6a1cb48f15) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Dell          | Latitude E7440              | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [f611683c8a](https://linux-hardware.org/?probe=f611683c8a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [55f1eaa96c](https://linux-hardware.org/?probe=55f1eaa96c) | Jul 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [090cc78b83](https://linux-hardware.org/?probe=090cc78b83) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ASUSTek       | X750JN                      | [6bf181ed49](https://linux-hardware.org/?probe=6bf181ed49) | Jul 22, 2022 |
| Acer          | Aspire V3-572               | [5938905628](https://linux-hardware.org/?probe=5938905628) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| HP            | Laptop 17-by0xxx            | [afa7d8ba6c](https://linux-hardware.org/?probe=afa7d8ba6c) | Jul 21, 2022 |
| ASUSTek       | X541UVK                     | [a34ee52169](https://linux-hardware.org/?probe=a34ee52169) | Jul 21, 2022 |
| Lenovo        | ThinkPad E470 20H1006HRT    | [ff4adb2f7d](https://linux-hardware.org/?probe=ff4adb2f7d) | Jul 20, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [ea200c839f](https://linux-hardware.org/?probe=ea200c839f) | Jul 20, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4cde663cf9](https://linux-hardware.org/?probe=4cde663cf9) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [effe49f996](https://linux-hardware.org/?probe=effe49f996) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [8d18b6813f](https://linux-hardware.org/?probe=8d18b6813f) | Jul 20, 2022 |
| Dell          | G3 3590                     | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [944ba71eef](https://linux-hardware.org/?probe=944ba71eef) | Jul 19, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | Notebook                    | [79c0f60f74](https://linux-hardware.org/?probe=79c0f60f74) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [2c43b01e55](https://linux-hardware.org/?probe=2c43b01e55) | Jul 18, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| Dell          | Latitude E6230              | [a66cad27e9](https://linux-hardware.org/?probe=a66cad27e9) | Jul 18, 2022 |
| Dell          | Latitude E7470              | [709a460528](https://linux-hardware.org/?probe=709a460528) | Jul 18, 2022 |
| MSI           | MS-14Y1                     | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Acer          | TMP453-MG                   | [797f0ea7fe](https://linux-hardware.org/?probe=797f0ea7fe) | Jul 18, 2022 |
| Google        | Kohaku                      | [2f21de3ff6](https://linux-hardware.org/?probe=2f21de3ff6) | Jul 18, 2022 |
| Pegatron      | D15K                        | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Framework     | Laptop                      | [84d20eb09a](https://linux-hardware.org/?probe=84d20eb09a) | Jul 17, 2022 |
| Framework     | Laptop                      | [0489cc39db](https://linux-hardware.org/?probe=0489cc39db) | Jul 17, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [df94c841af](https://linux-hardware.org/?probe=df94c841af) | Jul 17, 2022 |
| Dell          | Inspiron 5515               | [502c19838a](https://linux-hardware.org/?probe=502c19838a) | Jul 17, 2022 |
| Unknown       | Unknown                     | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| ASUSTek       | X541NA                      | [3caa5cc13d](https://linux-hardware.org/?probe=3caa5cc13d) | Jul 17, 2022 |
| Dell          | Latitude E5440              | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| HP            | 250 G5                      | [979d1aea6f](https://linux-hardware.org/?probe=979d1aea6f) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| System76      | Bonobo Extreme              | [6c7f545300](https://linux-hardware.org/?probe=6c7f545300) | Jul 16, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| Dell          | XPS 13 7390                 | [eff723b9f2](https://linux-hardware.org/?probe=eff723b9f2) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | [48dd04e4c8](https://linux-hardware.org/?probe=48dd04e4c8) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | [3378b0fc15](https://linux-hardware.org/?probe=3378b0fc15) | Jul 16, 2022 |
| Toshiba       | Satellite L505D             | [1d7b1ed7c8](https://linux-hardware.org/?probe=1d7b1ed7c8) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | X541NA                      | [b9476b6cf9](https://linux-hardware.org/?probe=b9476b6cf9) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| Dell          | Latitude E5540              | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Lenovo        | G400s VILG1                 | [fbaf6e2d8f](https://linux-hardware.org/?probe=fbaf6e2d8f) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | [33853365fd](https://linux-hardware.org/?probe=33853365fd) | Jul 13, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f91143bc89](https://linux-hardware.org/?probe=f91143bc89) | Jul 13, 2022 |
| GPD           | G1621-02                    | [25da86e752](https://linux-hardware.org/?probe=25da86e752) | Jul 13, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [a687046e06](https://linux-hardware.org/?probe=a687046e06) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [c4b25937a7](https://linux-hardware.org/?probe=c4b25937a7) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [de328d9562](https://linux-hardware.org/?probe=de328d9562) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| Lenovo        | ThinkPad T490s 20NYS0LY0... | [882680a962](https://linux-hardware.org/?probe=882680a962) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [a002ac843c](https://linux-hardware.org/?probe=a002ac843c) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [79ecbebabd](https://linux-hardware.org/?probe=79ecbebabd) | Jul 12, 2022 |
| HP            | Sona                        | [504fddb8e9](https://linux-hardware.org/?probe=504fddb8e9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ea08980c33](https://linux-hardware.org/?probe=ea08980c33) | Jul 11, 2022 |
| VALE          | Notebook Classic C140       | [d6cc520dbe](https://linux-hardware.org/?probe=d6cc520dbe) | Jul 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| Framework     | Laptop                      | [a13ef2beee](https://linux-hardware.org/?probe=a13ef2beee) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [4b10924d6a](https://linux-hardware.org/?probe=4b10924d6a) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [8270068517](https://linux-hardware.org/?probe=8270068517) | Jul 09, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [36151ae5c3](https://linux-hardware.org/?probe=36151ae5c3) | Jul 09, 2022 |
| MSI           | Bravo 17 A4DDK              | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| Dell          | Vostro 3590                 | [7195de93ae](https://linux-hardware.org/?probe=7195de93ae) | Jul 09, 2022 |
| HP            | Laptop 17z-cp000            | [f6f0740c36](https://linux-hardware.org/?probe=f6f0740c36) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| HP            | ProBook 6570b               | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Acer          | Predator PH315-53           | [b6c6516360](https://linux-hardware.org/?probe=b6c6516360) | Jul 09, 2022 |
| Dell          | Latitude 3400               | [6a36fb9dd9](https://linux-hardware.org/?probe=6a36fb9dd9) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | V14-ADA 82C6                | [e72ccdd0c6](https://linux-hardware.org/?probe=e72ccdd0c6) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| Notebook      | NH55RGQ                     | [37de891a60](https://linux-hardware.org/?probe=37de891a60) | Jul 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | Pavilion g6                 | [30085f92b1](https://linux-hardware.org/?probe=30085f92b1) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [84f475721b](https://linux-hardware.org/?probe=84f475721b) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [447ba923ac](https://linux-hardware.org/?probe=447ba923ac) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [75f67b342a](https://linux-hardware.org/?probe=75f67b342a) | Jul 08, 2022 |
| Acer          | Predator PH315-53           | [69b6f2bdad](https://linux-hardware.org/?probe=69b6f2bdad) | Jul 08, 2022 |
| Dell          | Latitude 5290 2-in-1        | [5ecc52d011](https://linux-hardware.org/?probe=5ecc52d011) | Jul 08, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e850b43a12](https://linux-hardware.org/?probe=e850b43a12) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [74ed9232f8](https://linux-hardware.org/?probe=74ed9232f8) | Jul 07, 2022 |
| Acer          | Nitro AN515-55              | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e1f5b40789](https://linux-hardware.org/?probe=e1f5b40789) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| Dell          | XPS 17 9710                 | [81b2d3fa4f](https://linux-hardware.org/?probe=81b2d3fa4f) | Jul 06, 2022 |
| Toshiba       | Satellite L505D             | [cf5fedc6e5](https://linux-hardware.org/?probe=cf5fedc6e5) | Jul 06, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [fec0786471](https://linux-hardware.org/?probe=fec0786471) | Jul 06, 2022 |
| HP            | ProBook 450 G2              | [aeb16eb1eb](https://linux-hardware.org/?probe=aeb16eb1eb) | Jul 06, 2022 |
| Lenovo        | ThinkPad L380 20M5000FUS    | [9c6ab1a171](https://linux-hardware.org/?probe=9c6ab1a171) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Dell          | Inspiron 16 5625            | [dcbe63005c](https://linux-hardware.org/?probe=dcbe63005c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5afb466a35](https://linux-hardware.org/?probe=5afb466a35) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [162080ffcf](https://linux-hardware.org/?probe=162080ffcf) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [4df173f8f2](https://linux-hardware.org/?probe=4df173f8f2) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [8dbec85d36](https://linux-hardware.org/?probe=8dbec85d36) | Jul 06, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [a3c85d395b](https://linux-hardware.org/?probe=a3c85d395b) | Jul 05, 2022 |
| System76      | Oryx Pro                    | [338a8ed5ab](https://linux-hardware.org/?probe=338a8ed5ab) | Jul 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4826df34b3](https://linux-hardware.org/?probe=4826df34b3) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2cbcdfe2db](https://linux-hardware.org/?probe=2cbcdfe2db) | Jul 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [7f64f81a29](https://linux-hardware.org/?probe=7f64f81a29) | Jul 04, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [59a1c1c8b1](https://linux-hardware.org/?probe=59a1c1c8b1) | Jul 04, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [9e9a46d8ec](https://linux-hardware.org/?probe=9e9a46d8ec) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5a6c158296](https://linux-hardware.org/?probe=5a6c158296) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| Dell          | Precision M4700             | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Notebook                    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d0e94cff94](https://linux-hardware.org/?probe=d0e94cff94) | Jul 03, 2022 |
| HP            | EliteBook 840 G1            | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Apple         | MacBookPro5,1               | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Dell          | XPS 13 9350                 | [0c8bcdbcb1](https://linux-hardware.org/?probe=0c8bcdbcb1) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [576f59ec1b](https://linux-hardware.org/?probe=576f59ec1b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [4d9cb098c8](https://linux-hardware.org/?probe=4d9cb098c8) | Jul 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [1b45ef7d10](https://linux-hardware.org/?probe=1b45ef7d10) | Jul 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [16413aeb23](https://linux-hardware.org/?probe=16413aeb23) | Jul 01, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c9d0d64896](https://linux-hardware.org/?probe=c9d0d64896) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |
| Framework     | Laptop                      | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [f29c4de6b4](https://linux-hardware.org/?probe=f29c4de6b4) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [7ecd760977](https://linux-hardware.org/?probe=7ecd760977) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [8428ba0120](https://linux-hardware.org/?probe=8428ba0120) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| HP            | Laptop 15-da0xxx            | [9c512247ff](https://linux-hardware.org/?probe=9c512247ff) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [43c87260b2](https://linux-hardware.org/?probe=43c87260b2) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Alienware     | 17                          | [715b5b0dce](https://linux-hardware.org/?probe=715b5b0dce) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Precision M6800             | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| ASUSTek       | X750JN                      | [4ba4d14a1a](https://linux-hardware.org/?probe=4ba4d14a1a) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Toshiba       | Satellite C855-12R          | [e94a109546](https://linux-hardware.org/?probe=e94a109546) | Jun 28, 2022 |
| Dell          | Inspiron N5110              | [239e8c86c0](https://linux-hardware.org/?probe=239e8c86c0) | Jun 28, 2022 |
| Dell          | Latitude E6520              | [f688527838](https://linux-hardware.org/?probe=f688527838) | Jun 27, 2022 |
| Gigabyte      | RC14UD                      | [d2b55252d8](https://linux-hardware.org/?probe=d2b55252d8) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | MacBookPro5,1               | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| Dell          | Inspiron 7558               | [d34cfa83d3](https://linux-hardware.org/?probe=d34cfa83d3) | Jun 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [de3ca4e422](https://linux-hardware.org/?probe=de3ca4e422) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| Timi          | A35S                        | [606e376264](https://linux-hardware.org/?probe=606e376264) | Jun 26, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [400eaba39f](https://linux-hardware.org/?probe=400eaba39f) | Jun 26, 2022 |
| HP            | Compaq CQ58                 | [5948b56a82](https://linux-hardware.org/?probe=5948b56a82) | Jun 25, 2022 |
| Dell          | XPS 13 9310                 | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [81a9b9847d](https://linux-hardware.org/?probe=81a9b9847d) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| HP            | Pavilion g6                 | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Unknown       | Unknown                     | [6e62883390](https://linux-hardware.org/?probe=6e62883390) | Jun 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3b84529124](https://linux-hardware.org/?probe=3b84529124) | Jun 24, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| HP            | Laptop 15-ef2xxx            | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| HP            | ProBook 4520s               | [eb9033a7c1](https://linux-hardware.org/?probe=eb9033a7c1) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2c0b9c6402](https://linux-hardware.org/?probe=2c0b9c6402) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [bb8541d805](https://linux-hardware.org/?probe=bb8541d805) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | [e2790ebf7e](https://linux-hardware.org/?probe=e2790ebf7e) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | [c99aceab3b](https://linux-hardware.org/?probe=c99aceab3b) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [926d4055f7](https://linux-hardware.org/?probe=926d4055f7) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| HP            | 250 G7 Notebook PC          | [6ec1b55ac0](https://linux-hardware.org/?probe=6ec1b55ac0) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5dd91493a8](https://linux-hardware.org/?probe=5dd91493a8) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [f002062377](https://linux-hardware.org/?probe=f002062377) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| Acer          | NC-E5-774G-75TJ             | [55fce68116](https://linux-hardware.org/?probe=55fce68116) | Jun 22, 2022 |
| HP            | ZBook 17 G4                 | [bf03eb0fa7](https://linux-hardware.org/?probe=bf03eb0fa7) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | [03c703cc7f](https://linux-hardware.org/?probe=03c703cc7f) | Jun 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| HUAWEI        | MACH-WX9                    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| HP            | EliteBook 830 G6            | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ae54449547](https://linux-hardware.org/?probe=ae54449547) | Jun 21, 2022 |
| GEO           | GeoBook 240                 | [f08637137c](https://linux-hardware.org/?probe=f08637137c) | Jun 21, 2022 |
| Dell          | XPS 13 9380                 | [dc134b17e9](https://linux-hardware.org/?probe=dc134b17e9) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012G... | [92638f1b46](https://linux-hardware.org/?probe=92638f1b46) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Google        | Droid                       | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| HP            | EliteBook 865 16 inch G9... | [9a543a0273](https://linux-hardware.org/?probe=9a543a0273) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9cf3c1f84c](https://linux-hardware.org/?probe=9cf3c1f84c) | Jun 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| HP            | ProBook 4520s               | [b34f97ddb3](https://linux-hardware.org/?probe=b34f97ddb3) | Jun 19, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [e09cfb9236](https://linux-hardware.org/?probe=e09cfb9236) | Jun 19, 2022 |
| HP            | Pavilion dv7                | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| HP            | ProBook 470 G5              | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [91af0ec6df](https://linux-hardware.org/?probe=91af0ec6df) | Jun 18, 2022 |
| Acer          | Swift SF314-43              | [a6116d2e8c](https://linux-hardware.org/?probe=a6116d2e8c) | Jun 18, 2022 |
| HP            | ProBook 430 G5              | [1689773788](https://linux-hardware.org/?probe=1689773788) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| Acer          | Swift SF314-43              | [674addd96b](https://linux-hardware.org/?probe=674addd96b) | Jun 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e0b7e5c636](https://linux-hardware.org/?probe=e0b7e5c636) | Jun 17, 2022 |
| Dell          | XPS 13 7390                 | [9cbdc324b7](https://linux-hardware.org/?probe=9cbdc324b7) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| Acer          | Aspire E5-476G              | [df4b512aa8](https://linux-hardware.org/?probe=df4b512aa8) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [91f1df8a58](https://linux-hardware.org/?probe=91f1df8a58) | Jun 17, 2022 |
| Acer          | Predator PH315-53           | [7e65c001a5](https://linux-hardware.org/?probe=7e65c001a5) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4e53a55031](https://linux-hardware.org/?probe=4e53a55031) | Jun 16, 2022 |
| Dell          | XPS 13 7390                 | [7dbb9f4adf](https://linux-hardware.org/?probe=7dbb9f4adf) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [c6d123b5ec](https://linux-hardware.org/?probe=c6d123b5ec) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [d28d429121](https://linux-hardware.org/?probe=d28d429121) | Jun 16, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [f83da947b8](https://linux-hardware.org/?probe=f83da947b8) | Jun 16, 2022 |
| Itautec       | Infoway w7430               | [776d876064](https://linux-hardware.org/?probe=776d876064) | Jun 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [388285efe8](https://linux-hardware.org/?probe=388285efe8) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [6b73227c17](https://linux-hardware.org/?probe=6b73227c17) | Jun 15, 2022 |
| Acer          | Predator PH315-53           | [155af690bd](https://linux-hardware.org/?probe=155af690bd) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [6f25a1e394](https://linux-hardware.org/?probe=6f25a1e394) | Jun 15, 2022 |
| Dell          | Inspiron 7472               | [788b7856ca](https://linux-hardware.org/?probe=788b7856ca) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [fd2fb2f646](https://linux-hardware.org/?probe=fd2fb2f646) | Jun 14, 2022 |
| Dell          | Precision 3551              | [3499839fd0](https://linux-hardware.org/?probe=3499839fd0) | Jun 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b6f26fecef](https://linux-hardware.org/?probe=b6f26fecef) | Jun 14, 2022 |
| HP            | Notebook                    | [390f55db2e](https://linux-hardware.org/?probe=390f55db2e) | Jun 14, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Dell          | XPS 15 9510                 | [61104911ed](https://linux-hardware.org/?probe=61104911ed) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2385e525c](https://linux-hardware.org/?probe=e2385e525c) | Jun 14, 2022 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [605cab3041](https://linux-hardware.org/?probe=605cab3041) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| HP            | Pavilion g6                 | [20bd05081e](https://linux-hardware.org/?probe=20bd05081e) | Jun 13, 2022 |
| HP            | Pavilion g6                 | [d147676849](https://linux-hardware.org/?probe=d147676849) | Jun 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [b8b4869fa1](https://linux-hardware.org/?probe=b8b4869fa1) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| Acer          | Aspire 5552                 | [909cdd1a0e](https://linux-hardware.org/?probe=909cdd1a0e) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [17d6efccfa](https://linux-hardware.org/?probe=17d6efccfa) | Jun 12, 2022 |
| Acer          | Aspire E5-573G              | [967ef390e0](https://linux-hardware.org/?probe=967ef390e0) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [dbe7d6b6bf](https://linux-hardware.org/?probe=dbe7d6b6bf) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [554002fe47](https://linux-hardware.org/?probe=554002fe47) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| Apple         | MacBookPro6,2               | [a677849f96](https://linux-hardware.org/?probe=a677849f96) | Jun 12, 2022 |
| ASUSTek       | X750JN                      | [6748bf6f1e](https://linux-hardware.org/?probe=6748bf6f1e) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| HP            | ProBook 650 G1              | [8f468e1fc9](https://linux-hardware.org/?probe=8f468e1fc9) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4180BE1       | [a3c2ffc8e0](https://linux-hardware.org/?probe=a3c2ffc8e0) | Jun 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [3c8959c8dc](https://linux-hardware.org/?probe=3c8959c8dc) | Jun 11, 2022 |
| HP            | Laptop 17-bs1xx             | [aa23e1d53e](https://linux-hardware.org/?probe=aa23e1d53e) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| Acer          | Swift SF114-32              | [63f76026b7](https://linux-hardware.org/?probe=63f76026b7) | Jun 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [1967d32245](https://linux-hardware.org/?probe=1967d32245) | Jun 10, 2022 |
| Dell          | XPS 15 9570                 | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| HP            | ZBook 15                    | [540fada7d4](https://linux-hardware.org/?probe=540fada7d4) | Jun 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 35 | 949       | 18.17%  |
| Fedora 34 | 924       | 17.69%  |
| Fedora 36 | 921       | 17.63%  |
| Fedora 33 | 850       | 16.27%  |
| Fedora 32 | 745       | 14.26%  |
| Fedora 31 | 503       | 9.63%   |
| Fedora 30 | 162       | 3.1%    |
| Fedora 29 | 88        | 1.68%   |
| Fedora 37 | 40        | 0.77%   |
| Fedora 28 | 22        | 0.42%   |
| Fedora 27 | 8         | 0.15%   |
| Fedora 24 | 4         | 0.08%   |
| Fedora 21 | 4         | 0.08%   |
| Fedora 25 | 2         | 0.04%   |
| Fedora 38 | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 4699      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.16.18-200.fc35.x86_64 | 92        | 1.57%   |
| 5.9.16-200.fc33.x86_64  | 90        | 1.54%   |
| 5.17.5-300.fc36.x86_64  | 83        | 1.42%   |
| 5.11.12-300.fc34.x86_64 | 74        | 1.27%   |
| 5.14.10-300.fc35.x86_64 | 68        | 1.16%   |
| 5.8.16-300.fc33.x86_64  | 64        | 1.1%    |
| 5.18.13-200.fc36.x86_64 | 62        | 1.06%   |
| 5.8.15-301.fc33.x86_64  | 60        | 1.03%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.98%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.92%   |
| 5.18.11-200.fc36.x86_64 | 51        | 0.87%   |
| 5.8.18-300.fc33.x86_64  | 46        | 0.79%   |
| 5.17.11-300.fc36.x86_64 | 46        | 0.79%   |
| 5.14.16-301.fc35.x86_64 | 46        | 0.79%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.77%   |
| 5.18.16-200.fc36.x86_64 | 45        | 0.77%   |
| 5.16.16-200.fc35.x86_64 | 44        | 0.75%   |
| 5.17.6-300.fc36.x86_64  | 43        | 0.74%   |
| 5.15.6-200.fc35.x86_64  | 42        | 0.72%   |
| 5.19.9-200.fc36.x86_64  | 41        | 0.7%    |
| 5.16.12-200.fc35.x86_64 | 41        | 0.7%    |
| 5.10.19-200.fc33.x86_64 | 41        | 0.7%    |
| 5.9.11-200.fc33.x86_64  | 40        | 0.68%   |
| 5.3.16-300.fc31.x86_64  | 39        | 0.67%   |
| 5.18.5-200.fc36.x86_64  | 39        | 0.67%   |
| 5.12.13-300.fc34.x86_64 | 39        | 0.67%   |
| 5.7.8-200.fc32.x86_64   | 38        | 0.65%   |
| 5.18.17-200.fc36.x86_64 | 38        | 0.65%   |
| 5.15.12-200.fc35.x86_64 | 38        | 0.65%   |
| 5.14.18-300.fc35.x86_64 | 38        | 0.65%   |
| 5.19.8-200.fc36.x86_64  | 37        | 0.63%   |
| 5.7.10-201.fc32.x86_64  | 36        | 0.62%   |
| 5.19.6-200.fc36.x86_64  | 36        | 0.62%   |
| 5.17.4-200.fc35.x86_64  | 36        | 0.62%   |
| 5.17.13-300.fc36.x86_64 | 36        | 0.62%   |
| 5.11.11-200.fc33.x86_64 | 36        | 0.62%   |
| 5.9.10-200.fc33.x86_64  | 35        | 0.6%    |
| 5.6.6-300.fc32.x86_64   | 35        | 0.6%    |
| 5.3.7-301.fc31.x86_64   | 35        | 0.6%    |
| 5.12.14-300.fc34.x86_64 | 35        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 117       | 2%      |
| 5.9.16  | 96        | 1.64%   |
| 5.16.18 | 95        | 1.63%   |
| 5.8.15  | 87        | 1.49%   |
| 5.8.16  | 81        | 1.39%   |
| 5.11.12 | 81        | 1.39%   |
| 5.14.10 | 77        | 1.32%   |
| 5.18.13 | 66        | 1.13%   |
| 5.11.11 | 66        | 1.13%   |
| 5.8.18  | 64        | 1.1%    |
| 5.8.4   | 57        | 0.98%   |
| 5.13.12 | 57        | 0.98%   |
| 5.18.11 | 54        | 0.92%   |
| 5.14.18 | 53        | 0.91%   |
| 5.14.16 | 52        | 0.89%   |
| 5.9.8   | 51        | 0.87%   |
| 5.17.11 | 50        | 0.86%   |
| 5.15.6  | 50        | 0.86%   |
| 5.19.8  | 49        | 0.84%   |
| 5.19.9  | 48        | 0.82%   |
| 5.18.16 | 48        | 0.82%   |
| 5.17.6  | 47        | 0.8%    |
| 5.16.16 | 47        | 0.8%    |
| 5.16.12 | 46        | 0.79%   |
| 5.18.5  | 45        | 0.77%   |
| 5.10.19 | 45        | 0.77%   |
| 5.6.6   | 44        | 0.75%   |
| 5.9.11  | 43        | 0.74%   |
| 5.15.12 | 43        | 0.74%   |
| 5.17.4  | 42        | 0.72%   |
| 5.14.9  | 42        | 0.72%   |
| 5.12.13 | 42        | 0.72%   |
| 5.3.16  | 40        | 0.68%   |
| 5.9.10  | 39        | 0.67%   |
| 5.18.17 | 39        | 0.67%   |
| 5.7.8   | 38        | 0.65%   |
| 5.3.7   | 38        | 0.65%   |
| 5.19.6  | 37        | 0.63%   |
| 5.17.13 | 37        | 0.63%   |
| 5.11.17 | 37        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 471       | 8.43%   |
| 5.8     | 463       | 8.28%   |
| 5.11    | 446       | 7.98%   |
| 5.18    | 407       | 7.28%   |
| 5.14    | 388       | 6.94%   |
| 5.16    | 381       | 6.82%   |
| 5.15    | 309       | 5.53%   |
| 5.9     | 303       | 5.42%   |
| 5.13    | 303       | 5.42%   |
| 5.10    | 291       | 5.21%   |
| 5.6     | 286       | 5.12%   |
| 5.12    | 282       | 5.04%   |
| 5.19    | 244       | 4.36%   |
| 5.7     | 221       | 3.95%   |
| 5.3     | 192       | 3.43%   |
| 5.5     | 183       | 3.27%   |
| 5.4     | 168       | 3.01%   |
| 5.0     | 61        | 1.09%   |
| 5.2     | 47        | 0.84%   |
| 5.1     | 43        | 0.77%   |
| 4.19    | 30        | 0.54%   |
| 4.18    | 27        | 0.48%   |
| 4.20    | 18        | 0.32%   |
| 6.0     | 5         | 0.09%   |
| 4.16    | 3         | 0.05%   |
| 4.15    | 3         | 0.05%   |
| 4.11    | 3         | 0.05%   |
| 4.1     | 3         | 0.05%   |
| 4.8     | 2         | 0.04%   |
| 4.17    | 2         | 0.04%   |
| 4.5     | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4691      | 99.81%  |
| i686    | 4         | 0.09%   |
| aarch64 | 4         | 0.09%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3552      | 73.39%  |
| KDE5            | 447       | 9.24%   |
| Unknown         | 281       | 5.81%   |
| KDE             | 134       | 2.77%   |
| XFCE            | 101       | 2.09%   |
| X-Cinnamon      | 73        | 1.51%   |
| MATE            | 70        | 1.45%   |
| Cinnamon        | 63        | 1.3%    |
| i3              | 21        | 0.43%   |
| GNOME Classic   | 20        | 0.41%   |
| LXQt            | 19        | 0.39%   |
| LXDE            | 12        | 0.25%   |
| Deepin          | 11        | 0.23%   |
| sway            | 10        | 0.21%   |
| Pantheon        | 4         | 0.08%   |
| awesome         | 4         | 0.08%   |
| openbox         | 3         | 0.06%   |
| KDE4            | 3         | 0.06%   |
| Budgie          | 3         | 0.06%   |
| GNOME Flashback | 2         | 0.04%   |
| fluxbox         | 2         | 0.04%   |
| bspwm           | 2         | 0.04%   |
| xinit-compat    | 1         | 0.02%   |
| KDE:old         | 1         | 0.02%   |
| DWM             | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 2989      | 61.16%  |
| X11     | 1671      | 34.19%  |
| Unknown | 185       | 3.79%   |
| Tty     | 42        | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2442      | 50.54%  |
| GDM     | 1813      | 37.52%  |
| SDDM    | 313       | 6.48%   |
| LightDM | 156       | 3.23%   |
| TDM     | 87        | 1.8%    |
| XDM     | 10        | 0.21%   |
| KDM     | 7         | 0.14%   |
| LXDM    | 3         | 0.06%   |
| Ly      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2421      | 50.5%   |
| Unknown | 362       | 7.55%   |
| en_GB   | 326       | 6.8%    |
| pt_BR   | 237       | 4.94%   |
| ru_RU   | 188       | 3.92%   |
| de_DE   | 162       | 3.38%   |
| fr_FR   | 142       | 2.96%   |
| it_IT   | 116       | 2.42%   |
| pl_PL   | 78        | 1.63%   |
| es_ES   | 69        | 1.44%   |
| en_CA   | 68        | 1.42%   |
| en_AU   | 61        | 1.27%   |
| en_IN   | 51        | 1.06%   |
| es_MX   | 44        | 0.92%   |
| cs_CZ   | 36        | 0.75%   |
| es_AR   | 26        | 0.54%   |
| es_CL   | 25        | 0.52%   |
| nl_NL   | 22        | 0.46%   |
| tr_TR   | 19        | 0.4%    |
| en_NZ   | 19        | 0.4%    |
| zh_CN   | 18        | 0.38%   |
| pt_PT   | 18        | 0.38%   |
| sv_SE   | 17        | 0.35%   |
| de_AT   | 16        | 0.33%   |
| hu_HU   | 14        | 0.29%   |
| en_DK   | 14        | 0.29%   |
| C       | 14        | 0.29%   |
| es_CO   | 13        | 0.27%   |
| en_IE   | 11        | 0.23%   |
| fr_CA   | 10        | 0.21%   |
| fi_FI   | 10        | 0.21%   |
| en_ZA   | 10        | 0.21%   |
| ru_UA   | 9         | 0.19%   |
| de_CH   | 8         | 0.17%   |
| uk_UA   | 7         | 0.15%   |
| sk_SK   | 7         | 0.15%   |
| nb_NO   | 7         | 0.15%   |
| fr_BE   | 7         | 0.15%   |
| en_SG   | 7         | 0.15%   |
| ro_RO   | 6         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3705      | 77.79%  |
| BIOS | 1058      | 22.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 2519      | 52.09%  |
| Ext4                | 1975      | 40.84%  |
| Unknown             | 193       | 3.99%   |
| Xfs                 | 133       | 2.75%   |
| Overlay             | 8         | 0.17%   |
| F2fs                | 3         | 0.06%   |
| Zfs                 | 2         | 0.04%   |
| Fuse.fuse-overlayfs | 2         | 0.04%   |
| Ext3                | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2444      | 50.81%  |
| GPT     | 2014      | 41.87%  |
| MBR     | 352       | 7.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4312      | 90.76%  |
| Yes       | 439       | 9.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3895      | 81.79%  |
| Yes       | 867       | 18.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1437      | 30.58%  |
| Dell                   | 885       | 18.83%  |
| Hewlett-Packard        | 695       | 14.79%  |
| ASUSTek Computer       | 443       | 9.43%   |
| Acer                   | 302       | 6.43%   |
| Apple                  | 124       | 2.64%   |
| MSI                    | 96        | 2.04%   |
| HUAWEI                 | 79        | 1.68%   |
| Toshiba                | 72        | 1.53%   |
| Samsung Electronics    | 65        | 1.38%   |
| Sony                   | 44        | 0.94%   |
| Notebook               | 42        | 0.89%   |
| Timi                   | 27        | 0.57%   |
| Unknown                | 26        | 0.55%   |
| Positivo               | 22        | 0.47%   |
| Fujitsu                | 21        | 0.45%   |
| Framework              | 21        | 0.45%   |
| Alienware              | 19        | 0.4%    |
| System76               | 15        | 0.32%   |
| Razer                  | 14        | 0.3%    |
| LG Electronics         | 14        | 0.3%    |
| TUXEDO                 | 12        | 0.26%   |
| Google                 | 12        | 0.26%   |
| Gigabyte Technology    | 9         | 0.19%   |
| Chuwi                  | 9         | 0.19%   |
| Avell High Performance | 9         | 0.19%   |
| PC Specialist          | 7         | 0.15%   |
| Panasonic              | 7         | 0.15%   |
| GPU Company            | 6         | 0.13%   |
| Fujitsu Siemens        | 6         | 0.13%   |
| SLIMBOOK               | 5         | 0.11%   |
| Packard Bell           | 5         | 0.11%   |
| Hampoo                 | 5         | 0.11%   |
| Gateway                | 5         | 0.11%   |
| eMachines              | 5         | 0.11%   |
| Pine Microsystems      | 4         | 0.09%   |
| Medion                 | 4         | 0.09%   |
| HONOR                  | 4         | 0.09%   |
| Clevo                  | 4         | 0.09%   |
| AZW                    | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 42        | 0.89%   |
| HP Notebook                                | 25        | 0.53%   |
| Dell XPS 13 9370                           | 21        | 0.45%   |
| Framework Laptop                           | 20        | 0.43%   |
| Dell XPS 15 9570                           | 20        | 0.43%   |
| Dell XPS 15 7590                           | 20        | 0.43%   |
| Dell XPS 13 9360                           | 19        | 0.4%    |
| Dell XPS 15 9560                           | 18        | 0.38%   |
| Dell Latitude 7490                         | 17        | 0.36%   |
| HP Pavilion dv6                            | 16        | 0.34%   |
| HP EliteBook 840 G6                        | 16        | 0.34%   |
| Dell XPS 13 7390                           | 15        | 0.32%   |
| HP Pavilion 15                             | 14        | 0.3%    |
| Dell XPS 15 9550                           | 14        | 0.3%    |
| Dell XPS 15 9500                           | 14        | 0.3%    |
| Dell Latitude E7450                        | 14        | 0.3%    |
| Dell XPS 13 9310                           | 13        | 0.28%   |
| Dell Latitude 5480                         | 13        | 0.28%   |
| HP Pavilion Notebook                       | 12        | 0.26%   |
| Dell Inspiron 15 7000 Gaming               | 12        | 0.26%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 11        | 0.23%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 11        | 0.23%   |
| HP Laptop 15-da0xxx                        | 11        | 0.23%   |
| Dell Latitude E7440                        | 11        | 0.23%   |
| Dell Inspiron 5570                         | 11        | 0.23%   |
| Apple MacBookPro12,1                       | 11        | 0.23%   |
| HP Pavilion dv7                            | 10        | 0.21%   |
| HP EliteBook 840 G3                        | 10        | 0.21%   |
| Dell XPS 13 9350                           | 10        | 0.21%   |
| Dell XPS 13 9300                           | 10        | 0.21%   |
| Dell Latitude E6520                        | 10        | 0.21%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 10        | 0.21%   |
| Acer Aspire E5-573G                        | 10        | 0.21%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 9         | 0.19%   |
| HUAWEI KLVL-WXX9                           | 9         | 0.19%   |
| Dell Latitude E6420                        | 9         | 0.19%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 8         | 0.17%   |
| Lenovo Legion 5 15ARH05 82B5               | 8         | 0.17%   |
| Lenovo IdeaPad Flex-14API 81SS             | 8         | 0.17%   |
| HUAWEI NBLK-WAX9X                          | 8         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 889       | 18.92%  |
| Lenovo IdeaPad     | 295       | 6.28%   |
| Dell Latitude      | 255       | 5.43%   |
| Dell Inspiron      | 252       | 5.36%   |
| Dell XPS           | 213       | 4.53%   |
| Acer Aspire        | 198       | 4.21%   |
| HP Pavilion        | 150       | 3.19%   |
| HP EliteBook       | 134       | 2.85%   |
| HP ProBook         | 117       | 2.49%   |
| HP Laptop          | 92        | 1.96%   |
| Dell Precision     | 75        | 1.6%    |
| ASUS ROG           | 72        | 1.53%   |
| ASUS VivoBook      | 65        | 1.38%   |
| Toshiba Satellite  | 61        | 1.3%    |
| Lenovo Legion      | 48        | 1.02%   |
| Lenovo ThinkBook   | 42        | 0.89%   |
| Unknown            | 42        | 0.89%   |
| HP ZBook           | 40        | 0.85%   |
| Dell Vostro        | 40        | 0.85%   |
| Lenovo Yoga        | 36        | 0.77%   |
| Acer Swift         | 34        | 0.72%   |
| Acer Nitro         | 34        | 0.72%   |
| ASUS ZenBook       | 33        | 0.7%    |
| HP ENVY            | 31        | 0.66%   |
| ASUS ASUS          | 29        | 0.62%   |
| HP Notebook        | 25        | 0.53%   |
| ASUS TUF           | 24        | 0.51%   |
| Apple MacBookPro11 | 23        | 0.49%   |
| Framework Laptop   | 21        | 0.45%   |
| HP OMEN            | 20        | 0.43%   |
| Fujitsu LIFEBOOK   | 17        | 0.36%   |
| Dell G5            | 16        | 0.34%   |
| Razer Blade        | 13        | 0.28%   |
| MSI Modern         | 12        | 0.26%   |
| Apple MacBookPro12 | 11        | 0.23%   |
| Acer Predator      | 11        | 0.23%   |
| HP 250             | 10        | 0.21%   |
| Dell G3            | 10        | 0.21%   |
| Apple MacBookPro9  | 10        | 0.21%   |
| HUAWEI KLVL-WXX9   | 9         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 664       | 14.13%  |
| 2020    | 629       | 13.39%  |
| 2018    | 541       | 11.51%  |
| 2021    | 428       | 9.11%   |
| 2017    | 395       | 8.41%   |
| 2015    | 342       | 7.28%   |
| 2016    | 310       | 6.6%    |
| 2013    | 284       | 6.04%   |
| 2012    | 279       | 5.94%   |
| 2014    | 246       | 5.24%   |
| 2011    | 238       | 5.06%   |
| 2010    | 119       | 2.53%   |
| 2022    | 73        | 1.55%   |
| 2008    | 72        | 1.53%   |
| 2009    | 58        | 1.23%   |
| 2007    | 13        | 0.28%   |
| Unknown | 4         | 0.09%   |
| 2006    | 3         | 0.06%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4699      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3874      | 81.16%  |
| Enabled  | 899       | 18.84%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4673      | 99.45%  |
| Yes  | 26        | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1443      | 30.26%  |
| 16.01-24.0  | 1148      | 24.07%  |
| 8.01-16.0   | 921       | 19.31%  |
| 32.01-64.0  | 501       | 10.51%  |
| 3.01-4.0    | 486       | 10.19%  |
| 1.01-2.0    | 94        | 1.97%   |
| 64.01-256.0 | 73        | 1.53%   |
| 24.01-32.0  | 71        | 1.49%   |
| 2.01-3.0    | 21        | 0.44%   |
| 0.51-1.0    | 9         | 0.19%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1536      | 29.01%  |
| 4.01-8.0   | 1364      | 25.77%  |
| 3.01-4.0   | 1137      | 21.48%  |
| 1.01-2.0   | 783       | 14.79%  |
| 8.01-16.0  | 359       | 6.78%   |
| 0.51-1.0   | 59        | 1.11%   |
| 16.01-24.0 | 38        | 0.72%   |
| 24.01-32.0 | 8         | 0.15%   |
| 32.01-64.0 | 5         | 0.09%   |
| 0.01-0.5   | 3         | 0.06%   |
| Unknown    | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3446      | 72%     |
| 2      | 1141      | 23.84%  |
| 3      | 145       | 3.03%   |
| 0      | 25        | 0.52%   |
| 4      | 19        | 0.4%    |
| 5      | 6         | 0.13%   |
| 6      | 4         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3640      | 77.1%   |
| Yes       | 1081      | 22.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3573      | 75.57%  |
| No        | 1155      | 24.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4600      | 97.81%  |
| No        | 103       | 2.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3903      | 82.01%  |
| No        | 856       | 17.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 837       | 17.63%  |
| Brazil      | 364       | 7.67%   |
| Germany     | 319       | 6.72%   |
| Russia      | 286       | 6.02%   |
| Italy       | 201       | 4.23%   |
| France      | 196       | 4.13%   |
| UK          | 174       | 3.66%   |
| India       | 172       | 3.62%   |
| Poland      | 141       | 2.97%   |
| Netherlands | 140       | 2.95%   |
| Canada      | 131       | 2.76%   |
| Spain       | 114       | 2.4%    |
| Czechia     | 90        | 1.9%    |
| Mexico      | 84        | 1.77%   |
| Australia   | 72        | 1.52%   |
| Turkey      | 67        | 1.41%   |
| Sweden      | 63        | 1.33%   |
| Austria     | 63        | 1.33%   |
| Ukraine     | 54        | 1.14%   |
| Switzerland | 52        | 1.1%    |
| Portugal    | 48        | 1.01%   |
| Argentina   | 48        | 1.01%   |
| Norway      | 46        | 0.97%   |
| Romania     | 45        | 0.95%   |
| Indonesia   | 43        | 0.91%   |
| Finland     | 41        | 0.86%   |
| Belgium     | 41        | 0.86%   |
| Hungary     | 39        | 0.82%   |
| Chile       | 36        | 0.76%   |
| Denmark     | 34        | 0.72%   |
| Iran        | 31        | 0.65%   |
| China       | 31        | 0.65%   |
| Greece      | 27        | 0.57%   |
| Colombia    | 27        | 0.57%   |
| Bulgaria    | 27        | 0.57%   |
| Slovakia    | 24        | 0.51%   |
| New Zealand | 24        | 0.51%   |
| Belarus     | 22        | 0.46%   |
| Japan       | 21        | 0.44%   |
| Israel      | 21        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 100       | 1.98%   |
| Sao Paulo         | 49        | 0.97%   |
| St Petersburg     | 42        | 0.83%   |
| Vienna            | 39        | 0.77%   |
| Paris             | 39        | 0.77%   |
| Amsterdam         | 38        | 0.75%   |
| Prague            | 37        | 0.73%   |
| Warsaw            | 36        | 0.71%   |
| Istanbul          | 34        | 0.67%   |
| Berlin            | 34        | 0.67%   |
| Milan             | 30        | 0.59%   |
| Oslo              | 28        | 0.55%   |
| Munich            | 27        | 0.53%   |
| Madrid            | 26        | 0.51%   |
| Bengaluru         | 25        | 0.49%   |
| Mexico City       | 24        | 0.47%   |
| Helsinki          | 23        | 0.45%   |
| Sydney            | 22        | 0.44%   |
| Kyiv              | 22        | 0.44%   |
| Rio de Janeiro    | 20        | 0.4%    |
| Melbourne         | 20        | 0.4%    |
| Hamburg           | 18        | 0.36%   |
| Budapest          | 18        | 0.36%   |
| Bucharest         | 18        | 0.36%   |
| Zurich            | 17        | 0.34%   |
| Tehran            | 17        | 0.34%   |
| Singapore         | 17        | 0.34%   |
| Frankfurt am Main | 17        | 0.34%   |
| Brno              | 17        | 0.34%   |
| Sofia             | 16        | 0.32%   |
| Rome              | 16        | 0.32%   |
| Los Angeles       | 16        | 0.32%   |
| Lisbon            | 16        | 0.32%   |
| Brisbane          | 16        | 0.32%   |
| Seattle           | 15        | 0.3%    |
| Minsk             | 15        | 0.3%    |
| Delft             | 15        | 0.3%    |
| Buenos Aires      | 15        | 0.3%    |
| Brasília         | 15        | 0.3%    |
| Athens            | 15        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1253      | 1821   | 21%     |
| WDC                       | 631       | 798    | 10.57%  |
| Seagate                   | 493       | 652    | 8.26%   |
| Toshiba                   | 444       | 553    | 7.44%   |
| SanDisk                   | 411       | 534    | 6.89%   |
| SK hynix                  | 330       | 410    | 5.53%   |
| Unknown                   | 326       | 434    | 5.46%   |
| Kingston                  | 288       | 354    | 4.83%   |
| Intel                     | 254       | 360    | 4.26%   |
| Crucial                   | 179       | 231    | 3%      |
| Micron Technology         | 156       | 205    | 2.61%   |
| HGST                      | 138       | 194    | 2.31%   |
| A-DATA Technology         | 93        | 107    | 1.56%   |
| KIOXIA                    | 72        | 102    | 1.21%   |
| Apple                     | 69        | 83     | 1.16%   |
| Hitachi                   | 66        | 78     | 1.11%   |
| LITEON                    | 62        | 67     | 1.04%   |
| Phison                    | 46        | 51     | 0.77%   |
| Transcend                 | 35        | 52     | 0.59%   |
| China                     | 35        | 39     | 0.59%   |
| Silicon Motion            | 34        | 50     | 0.57%   |
| PNY                       | 28        | 35     | 0.47%   |
| SPCC                      | 25        | 32     | 0.42%   |
| LITEONIT                  | 23        | 29     | 0.39%   |
| Lenovo                    | 18        | 21     | 0.3%    |
| Corsair                   | 17        | 22     | 0.28%   |
| XPG                       | 16        | 26     | 0.27%   |
| Patriot                   | 16        | 20     | 0.27%   |
| Unknown                   | 14        | 16     | 0.23%   |
| Team                      | 13        | 15     | 0.22%   |
| OCZ                       | 13        | 15     | 0.22%   |
| ADATA Technology          | 13        | 13     | 0.22%   |
| Lite-On                   | 12        | 18     | 0.2%    |
| KingSpec                  | 12        | 14     | 0.2%    |
| JMicron Technology        | 12        | 13     | 0.2%    |
| Hewlett-Packard           | 12        | 11     | 0.2%    |
| Realtek Semiconductor     | 11        | 16     | 0.18%   |
| Gigabyte Technology       | 11        | 12     | 0.18%   |
| Union Memory (Shenzhen)   | 10        | 17     | 0.17%   |
| Micron/Crucial Technology | 10        | 11     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB       | 113       | 1.81%   |
| Seagate ST1000LM035-1RK172 1TB     | 99        | 1.58%   |
| Samsung NVMe SSD Drive 256GB       | 83        | 1.33%   |
| SanDisk NVMe SSD Drive 512GB       | 74        | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 61        | 0.98%   |
| HGST HTS721010A9E630 1TB           | 60        | 0.96%   |
| Kingston SA400S37240G 240GB SSD    | 54        | 0.86%   |
| SK hynix NVMe SSD Drive 512GB      | 51        | 0.82%   |
| Unknown MMC Card  32GB             | 50        | 0.8%    |
| Samsung NVMe SSD Drive 1024GB      | 50        | 0.8%    |
| Toshiba MQ01ABD100 1TB             | 49        | 0.78%   |
| Samsung SSD 860 EVO 500GB          | 48        | 0.77%   |
| SanDisk NVMe SSD Drive 256GB       | 46        | 0.74%   |
| Intel NVMe SSD Drive 512GB         | 46        | 0.74%   |
| Toshiba MQ04ABF100 1TB             | 45        | 0.72%   |
| Samsung NVMe SSD Drive 1TB         | 43        | 0.69%   |
| Unknown MMC Card  64GB             | 41        | 0.66%   |
| Toshiba NVMe SSD Drive 512GB       | 38        | 0.61%   |
| Samsung SSD 850 EVO 500GB          | 37        | 0.59%   |
| Samsung SSD 850 EVO 250GB          | 36        | 0.58%   |
| Kingston SA400S37480G 480GB SSD    | 36        | 0.58%   |
| Toshiba NVMe SSD Drive 256GB       | 33        | 0.53%   |
| Unknown MMC Card  128GB            | 31        | 0.5%    |
| Samsung NVMe SSD Drive 500GB       | 31        | 0.5%    |
| SK hynix NVMe SSD Drive 256GB      | 30        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB    | 30        | 0.48%   |
| Seagate Expansion 1TB              | 30        | 0.48%   |
| Samsung SSD 860 EVO 1TB            | 29        | 0.46%   |
| Samsung SSD 860 EVO 250GB          | 26        | 0.42%   |
| HGST HTS541010A9E680 1TB           | 26        | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB           | 24        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB       | 24        | 0.38%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 24        | 0.38%   |
| SK hynix NVMe SSD Drive 1024GB     | 23        | 0.37%   |
| Samsung MZVLB1T0HBLR-000L7 1TB     | 23        | 0.37%   |
| WDC WD10SPZX-24Z10 1TB             | 22        | 0.35%   |
| SanDisk NVMe SSD Drive 1024GB      | 22        | 0.35%   |
| Kingston SA400S37120G 120GB SSD    | 22        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB        | 22        | 0.35%   |
| Samsung SSD 970 EVO 1TB            | 21        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 477       | 627    | 37.47%  |
| WDC                 | 331       | 425    | 26%     |
| Toshiba             | 203       | 250    | 15.95%  |
| HGST                | 138       | 194    | 10.84%  |
| Hitachi             | 66        | 78     | 5.18%   |
| Unknown             | 16        | 23     | 1.26%   |
| Samsung Electronics | 13        | 16     | 1.02%   |
| Fujitsu             | 10        | 10     | 0.79%   |
| Apple               | 7         | 8      | 0.55%   |
| USB3.0              | 2         | 2      | 0.16%   |
| LIO-ORG             | 2         | 8      | 0.16%   |
| Phison              | 1         | 2      | 0.08%   |
| LaCie               | 1         | 2      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| IB-AC703            | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 513       | 735    | 26.01%  |
| SanDisk             | 214       | 298    | 10.85%  |
| Kingston            | 214       | 261    | 10.85%  |
| Crucial             | 163       | 214    | 8.27%   |
| WDC                 | 96        | 124    | 4.87%   |
| Intel               | 83        | 128    | 4.21%   |
| A-DATA Technology   | 67        | 79     | 3.4%    |
| Micron Technology   | 66        | 80     | 3.35%   |
| SK hynix            | 50        | 60     | 2.54%   |
| LITEON              | 49        | 54     | 2.48%   |
| Apple               | 46        | 52     | 2.33%   |
| Toshiba             | 40        | 52     | 2.03%   |
| China               | 34        | 38     | 1.72%   |
| Transcend           | 30        | 43     | 1.52%   |
| PNY                 | 27        | 33     | 1.37%   |
| LITEONIT            | 23        | 29     | 1.17%   |
| SPCC                | 21        | 28     | 1.06%   |
| Patriot             | 14        | 17     | 0.71%   |
| OCZ                 | 12        | 14     | 0.61%   |
| Corsair             | 12        | 14     | 0.61%   |
| KingSpec            | 11        | 12     | 0.56%   |
| GOODRAM             | 10        | 12     | 0.51%   |
| Team                | 9         | 11     | 0.46%   |
| Seagate             | 9         | 9      | 0.46%   |
| Intenso             | 9         | 11     | 0.46%   |
| Gigabyte Technology | 9         | 10     | 0.46%   |
| Netac               | 8         | 8      | 0.41%   |
| Unknown             | 6         | 6      | 0.3%    |
| Lexar               | 6         | 13     | 0.3%    |
| Hewlett-Packard     | 6         | 6      | 0.3%    |
| Plextor             | 5         | 6      | 0.25%   |
| Apacer              | 5         | 5      | 0.25%   |
| Unknown             | 5         | 6      | 0.25%   |
| Mushkin             | 4         | 10     | 0.2%    |
| Dogfish             | 4         | 4      | 0.2%    |
| BIWIN               | 4         | 5      | 0.2%    |
| Vaseky              | 3         | 4      | 0.15%   |
| TO Exter            | 3         | 3      | 0.15%   |
| TCSUNBOW            | 3         | 4      | 0.15%   |
| Maxtor              | 3         | 4      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2229      | 3124   | 39.49%  |
| SSD     | 1819      | 2593   | 32.22%  |
| HDD     | 1231      | 1651   | 21.81%  |
| MMC     | 301       | 411    | 5.33%   |
| Unknown | 65        | 75     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2673      | 4074   | 49.55%  |
| NVMe | 2222      | 3104   | 41.19%  |
| MMC  | 301       | 411    | 5.58%   |
| SAS  | 199       | 265    | 3.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1887      | 2666   | 61.95%  |
| 0.51-1.0   | 1030      | 1391   | 33.81%  |
| 1.01-2.0   | 113       | 170    | 3.71%   |
| 4.01-10.0  | 8         | 8      | 0.26%   |
| 3.01-4.0   | 7         | 7      | 0.23%   |
| 0          | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1102      | 22.31%  |
| 501-1000       | 1007      | 20.39%  |
| 101-250        | 1006      | 20.37%  |
| 1-20           | 501       | 10.14%  |
| 1001-2000      | 476       | 9.64%   |
| Unknown        | 334       | 6.76%   |
| 51-100         | 221       | 4.47%   |
| 21-50          | 119       | 2.41%   |
| More than 3000 | 87        | 1.76%   |
| 2001-3000      | 86        | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1522      | 29.48%  |
| 21-50          | 921       | 17.84%  |
| 101-250        | 830       | 16.08%  |
| 51-100         | 696       | 13.48%  |
| 251-500        | 481       | 9.32%   |
| Unknown        | 334       | 6.47%   |
| 501-1000       | 268       | 5.19%   |
| 1001-2000      | 86        | 1.67%   |
| More than 3000 | 15        | 0.29%   |
| 2001-3000      | 9         | 0.17%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 9         | 9      | 3.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 17     | 3.88%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 3.02%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 2.59%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 2.59%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 2.59%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 5         | 5      | 2.16%   |
| HGST HTS721010A9E630 1TB                       | 5         | 6      | 2.16%   |
| Seagate ST9500325AS 500GB                      | 4         | 6      | 1.72%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.72%   |
| Toshiba MQ01ABD075 752GB                       | 3         | 3      | 1.29%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 1.29%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 1.29%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 1.29%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.86%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.86%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.86%   |
| Toshiba MK3275GSX 320GB                        | 2         | 2      | 0.86%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.86%   |
| SK hynix SC308 SATA 128GB SSD                  | 2         | 2      | 0.86%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.86%   |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.86%   |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 0.86%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.86%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.86%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 2         | 2      | 0.86%   |
| LITEON CV8-8E128-HP 128GB SSD                  | 2         | 2      | 0.86%   |
| Intel SSDSC2BF180A5L 180GB                     | 2         | 2      | 0.86%   |
| Hitachi HTS545025B9SA02 250GB                  | 2         | 3      | 0.86%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 0.86%   |
| Fujitsu MHY2120BH 120GB                        | 2         | 2      | 0.86%   |
| Crucial CT1050MX300SSD1 1TB                    | 2         | 7      | 0.86%   |
| WDC WD7500BPVX-60JC3T0 752GB                   | 1         | 1      | 0.43%   |
| WDC WD6400BEVT-22A0RT0 640GB                   | 1         | 1      | 0.43%   |
| WDC WD5000LPVX-28V0TT0 500GB                   | 1         | 1      | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.43%   |
| WDC WD5000LPLX-60ZNTT1 500GB                   | 1         | 1      | 0.43%   |
| WDC WD5000LPLX-08ZNTT0 500GB                   | 1         | 2      | 0.43%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 1         | 1      | 0.43%   |
| WDC WD5000LPCX-00VHAT0 500GB                   | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 64     | 21.21%  |
| WDC                 | 23        | 25     | 9.96%   |
| Toshiba             | 23        | 23     | 9.96%   |
| HGST                | 22        | 23     | 9.52%   |
| Samsung Electronics | 17        | 21     | 7.36%   |
| Hitachi             | 17        | 20     | 7.36%   |
| Intel               | 12        | 23     | 5.19%   |
| Micron Technology   | 11        | 14     | 4.76%   |
| SanDisk             | 10        | 11     | 4.33%   |
| Crucial             | 10        | 15     | 4.33%   |
| SK hynix            | 9         | 10     | 3.9%    |
| Kingston            | 5         | 5      | 2.16%   |
| LITEON              | 4         | 4      | 1.73%   |
| A-DATA Technology   | 4         | 4      | 1.73%   |
| Fujitsu             | 3         | 3      | 1.3%    |
| SPCC                | 2         | 2      | 0.87%   |
| LITEONIT            | 2         | 3      | 0.87%   |
| Union Memory        | 1         | 1      | 0.43%   |
| Teclast             | 1         | 1      | 0.43%   |
| SSD                 | 1         | 1      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| Origin              | 1         | 1      | 0.43%   |
| OCZ-VERTEX3         | 1         | 1      | 0.43%   |
| Lenovo              | 1         | 2      | 0.43%   |
| China               | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 64     | 35.25%  |
| WDC                 | 23        | 25     | 16.55%  |
| Toshiba             | 22        | 22     | 15.83%  |
| HGST                | 22        | 23     | 15.83%  |
| Hitachi             | 17        | 20     | 12.23%  |
| Samsung Electronics | 3         | 3      | 2.16%   |
| Fujitsu             | 3         | 3      | 2.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 138       | 160    | 60.26%  |
| SSD  | 76        | 101    | 33.19%  |
| NVMe | 15        | 18     | 6.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB | 1         | 1      | 20%     |
| Toshiba THNSN5512GPUK NVMe 512GB     | 1         | 1      | 20%     |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 20%     |
| Samsung Electronics SSD 980 500GB    | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2683      | 4510   | 53.03%  |
| Works    | 2147      | 3060   | 42.44%  |
| Malfunc  | 224       | 279    | 4.43%   |
| Failed   | 5         | 5      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3023      | 52.62%  |
| Samsung Electronics              | 797       | 13.87%  |
| AMD                              | 476       | 8.29%   |
| SanDisk                          | 386       | 6.72%   |
| SK hynix                         | 266       | 4.63%   |
| Toshiba America Info Systems     | 200       | 3.48%   |
| Micron Technology                | 91        | 1.58%   |
| Kingston Technology Company      | 78        | 1.36%   |
| KIOXIA                           | 76        | 1.32%   |
| Phison Electronics               | 61        | 1.06%   |
| ADATA Technology                 | 50        | 0.87%   |
| Silicon Motion                   | 48        | 0.84%   |
| Micron/Crucial Technology        | 26        | 0.45%   |
| Lite-On Technology               | 25        | 0.44%   |
| Union Memory (Shenzhen)          | 23        | 0.4%    |
| Nvidia                           | 22        | 0.38%   |
| Lenovo                           | 18        | 0.31%   |
| Solid State Storage Technology   | 16        | 0.28%   |
| Realtek Semiconductor            | 16        | 0.28%   |
| Apple                            | 14        | 0.24%   |
| Seagate Technology               | 7         | 0.12%   |
| Yangtze Memory Technologies      | 4         | 0.07%   |
| Marvell Technology Group         | 4         | 0.07%   |
| JMicron Technology               | 4         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Unknown                          | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Beijing Starblaze Technology     | 1         | 0.02%   |
| ASMedia Technology               | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 518       | 8.66%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 449       | 7.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 447       | 7.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 305       | 5.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 294       | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 199       | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 196       | 3.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 176       | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 157       | 2.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 153       | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 146       | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                              | 130       | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 126       | 2.11%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 124       | 2.07%   |
| Micron Non-Volatile memory controller                                            | 91        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 89        | 1.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 83        | 1.39%   |
| SK hynix Gold P31 SSD                                                            | 79        | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                            | 75        | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 72        | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 70        | 1.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 69        | 1.15%   |
| Intel SSD 660P Series                                                            | 69        | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 67        | 1.12%   |
| SK hynix Non-Volatile memory controller                                          | 59        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 59        | 0.99%   |
| SanDisk Non-Volatile memory controller                                           | 56        | 0.94%   |
| Intel Tiger Lake-LP SATA Controller                                              | 55        | 0.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 55        | 0.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 54        | 0.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 51        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 51        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 49        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 48        | 0.8%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 46        | 0.77%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 45        | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 44        | 0.74%   |
| SK hynix BC511                                                                   | 43        | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 42        | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 41        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3034      | 52.39%  |
| NVMe | 2230      | 38.51%  |
| RAID | 437       | 7.55%   |
| IDE  | 90        | 1.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 3877      | 82.51%  |
| AMD     | 817       | 17.39%  |
| ARM     | 4         | 0.09%   |
| Unknown | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 138       | 2.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 110       | 2.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 96        | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 87        | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 86        | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 84        | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 83        | 1.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 82        | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 82        | 1.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 80        | 1.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 80        | 1.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 74        | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 74        | 1.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 69        | 1.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 67        | 1.43%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 55        | 1.17%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 53        | 1.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 53        | 1.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 52        | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 52        | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 51        | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 50        | 1.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 43        | 0.92%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 41        | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 39        | 0.83%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 39        | 0.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 37        | 0.79%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 36        | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 35        | 0.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 35        | 0.74%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 33        | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 32        | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 30        | 0.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 30        | 0.64%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 30        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 29        | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.62%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 29        | 0.62%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 28        | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 1572      | 33.45%  |
| Intel Core i5                  | 1247      | 26.54%  |
| Other                          | 328       | 6.98%   |
| Intel Core i3                  | 296       | 6.3%    |
| AMD Ryzen 5                    | 258       | 5.49%   |
| AMD Ryzen 7                    | 217       | 4.62%   |
| Intel Celeron                  | 106       | 2.26%   |
| Intel Core 2 Duo               | 84        | 1.79%   |
| Intel Atom                     | 80        | 1.7%    |
| Intel Pentium                  | 60        | 1.28%   |
| AMD Ryzen 7 PRO                | 59        | 1.26%   |
| AMD Ryzen 9                    | 57        | 1.21%   |
| Intel Core i9                  | 45        | 0.96%   |
| AMD Ryzen 3                    | 32        | 0.68%   |
| AMD Ryzen 5 PRO                | 29        | 0.62%   |
| AMD A6                         | 27        | 0.57%   |
| AMD A10                        | 27        | 0.57%   |
| AMD A8                         | 22        | 0.47%   |
| Intel Pentium Silver           | 17        | 0.36%   |
| AMD A4                         | 15        | 0.32%   |
| Intel Pentium Dual-Core        | 12        | 0.26%   |
| Intel Xeon                     | 11        | 0.23%   |
| AMD E1                         | 9         | 0.19%   |
| AMD Athlon                     | 9         | 0.19%   |
| AMD E                          | 7         | 0.15%   |
| AMD A12                        | 7         | 0.15%   |
| Intel Pentium Dual             | 6         | 0.13%   |
| Intel Core m5                  | 6         | 0.13%   |
| Intel Genuine                  | 5         | 0.11%   |
| Intel Core m3                  | 5         | 0.11%   |
| Intel Core M                   | 5         | 0.11%   |
| Intel Core m7                  | 4         | 0.09%   |
| AMD Phenom II                  | 4         | 0.09%   |
| AMD E2                         | 4         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.06%   |
| AMD PRO A10                    | 3         | 0.06%   |
| AMD Athlon II                  | 3         | 0.06%   |
| Intel Celeron Dual-Core        | 2         | 0.04%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.04%   |
| AMD Turion 64 Mobile           | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 1976      | 42.03%  |
| 2       | 1853      | 39.42%  |
| 6       | 450       | 9.57%   |
| 8       | 367       | 7.81%   |
| 14      | 17        | 0.36%   |
| 1       | 17        | 0.36%   |
| 12      | 12        | 0.26%   |
| 10      | 6         | 0.13%   |
| 3       | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 4697      | 99.94%  |
| 2       | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4092      | 86.93%  |
| 1       | 614       | 13.04%  |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4564      | 96.69%  |
| Unknown        | 151       | 3.2%    |
| 32-bit         | 3         | 0.06%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 327       | 6.85%   |
| 0x806ea    | 317       | 6.64%   |
| 0x306a9    | 305       | 6.39%   |
| Unknown    | 277       | 5.8%    |
| 0x206a7    | 251       | 5.26%   |
| 0x806e9    | 231       | 4.84%   |
| 0x406e3    | 229       | 4.8%    |
| 0x806c1    | 228       | 4.78%   |
| 0x906ea    | 227       | 4.75%   |
| 0x40651    | 192       | 4.02%   |
| 0x306d4    | 186       | 3.9%    |
| 0x306c3    | 154       | 3.23%   |
| 0xa0652    | 131       | 2.74%   |
| 0x906e9    | 103       | 2.16%   |
| 0x08108102 | 102       | 2.14%   |
| 0x0a50000c | 99        | 2.07%   |
| 0x506e3    | 93        | 1.95%   |
| 0x08600106 | 92        | 1.93%   |
| 0x706e5    | 79        | 1.65%   |
| 0x08108109 | 76        | 1.59%   |
| 0x20655    | 73        | 1.53%   |
| 0x806eb    | 64        | 1.34%   |
| 0x30678    | 63        | 1.32%   |
| 0x1067a    | 62        | 1.3%    |
| 0x08600104 | 55        | 1.15%   |
| 0x906ed    | 48        | 1.01%   |
| 0x08600103 | 43        | 0.9%    |
| 0x08608103 | 42        | 0.88%   |
| 0x406c4    | 35        | 0.73%   |
| 0x806d1    | 28        | 0.59%   |
| 0x406c3    | 28        | 0.59%   |
| 0x0810100b | 28        | 0.59%   |
| 0x906a3    | 26        | 0.54%   |
| 0x506c9    | 26        | 0.54%   |
| 0x706a8    | 24        | 0.5%    |
| 0x10676    | 24        | 0.5%    |
| 0x20652    | 22        | 0.46%   |
| 0x08608102 | 22        | 0.46%   |
| 0x08600102 | 21        | 0.44%   |
| 0x706a1    | 20        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1395      | 29.68%  |
| Haswell          | 381       | 8.11%   |
| Skylake          | 344       | 7.32%   |
| IvyBridge        | 315       | 6.7%    |
| SandyBridge      | 260       | 5.53%   |
| TigerLake        | 249       | 5.3%    |
| Zen 2            | 225       | 4.79%   |
| Broadwell        | 188       | 4%      |
| Zen+             | 185       | 3.94%   |
| CometLake        | 149       | 3.17%   |
| Silvermont       | 135       | 2.87%   |
| Zen 3            | 115       | 2.45%   |
| IceLake          | 114       | 2.43%   |
| Westmere         | 100       | 2.13%   |
| Unknown          | 98        | 2.09%   |
| Penryn           | 88        | 1.87%   |
| Zen              | 50        | 1.06%   |
| Goldmont plus    | 45        | 0.96%   |
| Excavator        | 42        | 0.89%   |
| Alderlake Hybrid | 30        | 0.64%   |
| Puma             | 27        | 0.57%   |
| Goldmont         | 27        | 0.57%   |
| Piledriver       | 22        | 0.47%   |
| Core             | 22        | 0.47%   |
| Nehalem          | 17        | 0.36%   |
| Jaguar           | 16        | 0.34%   |
| Bobcat           | 14        | 0.3%    |
| K10              | 10        | 0.21%   |
| K10 Llano        | 9         | 0.19%   |
| Tremont          | 8         | 0.17%   |
| Steamroller      | 5         | 0.11%   |
| K8 Hammer        | 4         | 0.09%   |
| K8 & K10 hybrid  | 4         | 0.09%   |
| Bonnell          | 4         | 0.09%   |
| P6               | 2         | 0.04%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3635      | 58.57%  |
| Nvidia                           | 1490      | 24.01%  |
| AMD                              | 1080      | 17.4%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 334       | 5.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 291       | 4.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 245       | 3.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 232       | 3.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 230       | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 229       | 3.63%   |
| Intel HD Graphics 620                                                                    | 226       | 3.58%   |
| AMD Renoir                                                                               | 219       | 3.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 209       | 3.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 195       | 3.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 185       | 2.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 174       | 2.75%   |
| Intel HD Graphics 5500                                                                   | 165       | 2.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 156       | 2.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 123       | 1.95%   |
| AMD Cezanne                                                                              | 104       | 1.65%   |
| Intel HD Graphics 630                                                                    | 95        | 1.5%    |
| Intel HD Graphics 530                                                                    | 85        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 77        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 73        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 72        | 1.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 71        | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 69        | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 66        | 1.04%   |
| AMD Lucienne                                                                             | 65        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 63        | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 54        | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 50        | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 48        | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 46        | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 44        | 0.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 44        | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 44        | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 42        | 0.66%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 39        | 0.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 0.62%   |
| Nvidia GP108M [GeForce MX250]                                                            | 34        | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 34        | 0.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 34        | 0.54%   |
| Intel Iris Plus Graphics G7                                                              | 32        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2264      | 48.01%  |
| Intel + Nvidia     | 1163      | 24.66%  |
| 1 x AMD            | 658       | 13.95%  |
| Intel + AMD        | 209       | 4.43%   |
| 1 x Nvidia         | 198       | 4.2%    |
| AMD + Nvidia       | 130       | 2.76%   |
| 2 x AMD            | 83        | 1.76%   |
| Other              | 7         | 0.15%   |
| 2 x Nvidia         | 2         | 0.04%   |
| 1 x SiS            | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4067      | 85.51%  |
| Proprietary | 634       | 13.33%  |
| Unknown     | 55        | 1.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2933      | 61.19%  |
| 1.01-2.0   | 684       | 14.27%  |
| 0.01-0.5   | 466       | 9.72%   |
| 3.01-4.0   | 307       | 6.41%   |
| 0.51-1.0   | 263       | 5.49%   |
| 7.01-8.0   | 57        | 1.19%   |
| 5.01-6.0   | 52        | 1.08%   |
| 2.01-3.0   | 18        | 0.38%   |
| 8.01-16.0  | 13        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1039      | 17.79%  |
| LG Display              | 814       | 13.93%  |
| BOE                     | 785       | 13.44%  |
| Chimei Innolux          | 762       | 13.04%  |
| Samsung Electronics     | 466       | 7.98%   |
| Dell                    | 295       | 5.05%   |
| Sharp                   | 270       | 4.62%   |
| Goldstar                | 187       | 3.2%    |
| Lenovo                  | 129       | 2.21%   |
| Apple                   | 124       | 2.12%   |
| PANDA                   | 106       | 1.81%   |
| Hewlett-Packard         | 106       | 1.81%   |
| Chi Mei Optoelectronics | 66        | 1.13%   |
| BenQ                    | 62        | 1.06%   |
| Philips                 | 61        | 1.04%   |
| Acer                    | 60        | 1.03%   |
| AOC                     | 53        | 0.91%   |
| InfoVision              | 51        | 0.87%   |
| CSO                     | 51        | 0.87%   |
| Ancor Communications    | 51        | 0.87%   |
| Iiyama                  | 28        | 0.48%   |
| ViewSonic               | 22        | 0.38%   |
| TMX                     | 22        | 0.38%   |
| ASUSTek Computer        | 17        | 0.29%   |
| Panasonic               | 16        | 0.27%   |
| Sony                    | 15        | 0.26%   |
| JDI                     | 14        | 0.24%   |
| Toshiba                 | 11        | 0.19%   |
| Sceptre Tech            | 10        | 0.17%   |
| HannStar                | 8         | 0.14%   |
| CPT                     | 8         | 0.14%   |
| MSI                     | 7         | 0.12%   |
| LG Philips              | 7         | 0.12%   |
| Eizo                    | 7         | 0.12%   |
| Vizio                   | 6         | 0.1%    |
| RTK                     | 5         | 0.09%   |
| NEC Computers           | 5         | 0.09%   |
| InnoLux Display         | 5         | 0.09%   |
| Vestel Elektronik       | 4         | 0.07%   |
| ONN                     | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 50        | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 40        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 38        | 0.64%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 35        | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 35        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 35        | 0.59%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 31        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 29        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 25        | 0.42%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 25        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 24        | 0.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 24        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 24        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 23        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 21        | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 21        | 0.35%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 21        | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 20        | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 20        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 20        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 20        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 20        | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 19        | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 19        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 19        | 0.32%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 19        | 0.32%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 19        | 0.32%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 19        | 0.32%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 18        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 18        | 0.3%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 17        | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 16        | 0.27%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 16        | 0.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 16        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 16        | 0.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 16        | 0.27%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 15        | 0.25%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 15        | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 15        | 0.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 15        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2727      | 51.01%  |
| 1366x768 (WXGA)    | 1110      | 20.76%  |
| 3840x2160 (4K)     | 326       | 6.1%    |
| 2560x1440 (QHD)    | 218       | 4.08%   |
| 1600x900 (HD+)     | 201       | 3.76%   |
| 1920x1200 (WUXGA)  | 140       | 2.62%   |
| 1280x800 (WXGA)    | 84        | 1.57%   |
| 2560x1600          | 66        | 1.23%   |
| 1440x900 (WXGA+)   | 52        | 0.97%   |
| 2880x1800          | 51        | 0.95%   |
| 2560x1080          | 51        | 0.95%   |
| 1680x1050 (WSXGA+) | 36        | 0.67%   |
| 3440x1440          | 35        | 0.65%   |
| 3840x2400          | 32        | 0.6%    |
| 2160x1440          | 31        | 0.58%   |
| 3200x1800 (QHD+)   | 30        | 0.56%   |
| 1280x1024 (SXGA)   | 27        | 0.51%   |
| 2256x1504          | 21        | 0.39%   |
| 1360x768           | 15        | 0.28%   |
| 3000x2000          | 14        | 0.26%   |
| 3456x2160          | 7         | 0.13%   |
| 3200x2000          | 7         | 0.13%   |
| 3072x1920          | 6         | 0.11%   |
| 2240x1400          | 6         | 0.11%   |
| 3840x1600          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 2160x1350          | 4         | 0.07%   |
| 1024x600           | 4         | 0.07%   |
| 2520x1680          | 3         | 0.06%   |
| 1920x540           | 3         | 0.06%   |
| 1024x768 (XGA)     | 3         | 0.06%   |
| Unknown            | 3         | 0.06%   |
| 3840x1080          | 2         | 0.04%   |
| 2880x1920          | 2         | 0.04%   |
| 2736x1824          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 9360x2160          | 1         | 0.02%   |
| 4680x2175          | 1         | 0.02%   |
| 3926x1440          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2157      | 36.92%  |
| 13      | 972       | 16.64%  |
| 14      | 809       | 13.85%  |
| 17      | 304       | 5.2%    |
| 27      | 277       | 4.74%   |
| 24      | 275       | 4.71%   |
| 23      | 194       | 3.32%   |
| 12      | 166       | 2.84%   |
| 21      | 144       | 2.46%   |
| 34      | 75        | 1.28%   |
| 31      | 61        | 1.04%   |
| 18      | 60        | 1.03%   |
| 11      | 54        | 0.92%   |
| 16      | 47        | 0.8%    |
| 19      | 30        | 0.51%   |
| 20      | 28        | 0.48%   |
| 22      | 25        | 0.43%   |
| 25      | 18        | 0.31%   |
| Unknown | 17        | 0.29%   |
| 40      | 14        | 0.24%   |
| 84      | 13        | 0.22%   |
| 32      | 12        | 0.21%   |
| 10      | 10        | 0.17%   |
| 35      | 9         | 0.15%   |
| 29      | 9         | 0.15%   |
| 26      | 9         | 0.15%   |
| 54      | 7         | 0.12%   |
| 37      | 6         | 0.1%    |
| 72      | 5         | 0.09%   |
| 39      | 4         | 0.07%   |
| 28      | 4         | 0.07%   |
| 48      | 3         | 0.05%   |
| 46      | 3         | 0.05%   |
| 33      | 3         | 0.05%   |
| 74      | 2         | 0.03%   |
| 63      | 2         | 0.03%   |
| 57      | 2         | 0.03%   |
| 52      | 2         | 0.03%   |
| 43      | 2         | 0.03%   |
| 42      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 3475      | 60.12%  |
| 501-600     | 692       | 11.97%  |
| 201-300     | 681       | 11.78%  |
| 351-400     | 368       | 6.37%   |
| 401-500     | 270       | 4.67%   |
| 601-700     | 104       | 1.8%    |
| 701-800     | 89        | 1.54%   |
| 801-900     | 34        | 0.59%   |
| 1001-1500   | 24        | 0.42%   |
| 1501-2000   | 21        | 0.36%   |
| Unknown     | 17        | 0.29%   |
| 901-1000    | 4         | 0.07%   |
| 101-200     | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4160      | 84.73%  |
| 16/10   | 515       | 10.49%  |
| 21/9    | 92        | 1.87%   |
| 3/2     | 89        | 1.81%   |
| 5/4     | 27        | 0.55%   |
| Unknown | 9         | 0.18%   |
| 4/3     | 7         | 0.14%   |
| 32/9    | 5         | 0.1%    |
| 6/5     | 2         | 0.04%   |
| 3.88    | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2161      | 37.06%  |
| 81-90          | 1409      | 24.16%  |
| 201-250        | 503       | 8.63%   |
| 71-80          | 371       | 6.36%   |
| 301-350        | 285       | 4.89%   |
| 121-130        | 277       | 4.75%   |
| 351-500        | 167       | 2.86%   |
| 61-70          | 161       | 2.76%   |
| 251-300        | 122       | 2.09%   |
| 151-200        | 85        | 1.46%   |
| 141-150        | 63        | 1.08%   |
| 51-60          | 55        | 0.94%   |
| 111-120        | 41        | 0.7%    |
| More than 1000 | 38        | 0.65%   |
| 501-1000       | 35        | 0.6%    |
| 131-140        | 24        | 0.41%   |
| Unknown        | 17        | 0.29%   |
| 41-50          | 10        | 0.17%   |
| 91-100         | 5         | 0.09%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2569      | 45.17%  |
| 101-120       | 1303      | 22.91%  |
| 51-100        | 908       | 15.96%  |
| 161-240       | 551       | 9.69%   |
| More than 240 | 307       | 5.4%    |
| 1-50          | 33        | 0.58%   |
| Unknown       | 17        | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3554      | 73.04%  |
| 2     | 1060      | 21.78%  |
| 3     | 143       | 2.94%   |
| 0     | 99        | 2.03%   |
| 4     | 9         | 0.18%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2887      | 40.31%  |
| Realtek Semiconductor             | 2308      | 32.23%  |
| Qualcomm Atheros                  | 884       | 12.34%  |
| Broadcom                          | 312       | 4.36%   |
| MediaTek                          | 99        | 1.38%   |
| Broadcom Limited                  | 75        | 1.05%   |
| Lenovo                            | 68        | 0.95%   |
| Sierra Wireless                   | 52        | 0.73%   |
| TP-Link                           | 47        | 0.66%   |
| ASIX Electronics                  | 44        | 0.61%   |
| Ralink                            | 35        | 0.49%   |
| Dell                              | 33        | 0.46%   |
| Marvell Technology Group          | 31        | 0.43%   |
| Ericsson Business Mobile Networks | 26        | 0.36%   |
| DisplayLink                       | 26        | 0.36%   |
| Ralink Technology                 | 23        | 0.32%   |
| Hewlett-Packard                   | 21        | 0.29%   |
| Qualcomm                          | 18        | 0.25%   |
| Samsung Electronics               | 16        | 0.22%   |
| Nvidia                            | 16        | 0.22%   |
| Huawei Technologies               | 14        | 0.2%    |
| Xiaomi                            | 10        | 0.14%   |
| ASUSTek Computer                  | 10        | 0.14%   |
| Apple                             | 10        | 0.14%   |
| FIBOCOM                           | 9         | 0.13%   |
| JMicron Technology                | 8         | 0.11%   |
| NetGear                           | 7         | 0.1%    |
| Qualcomm Atheros Communications   | 6         | 0.08%   |
| Google                            | 6         | 0.08%   |
| T & A Mobile Phones               | 5         | 0.07%   |
| Linksys                           | 5         | 0.07%   |
| D-Link                            | 5         | 0.07%   |
| OPPO Electronics                  | 4         | 0.06%   |
| Edimax Technology                 | 4         | 0.06%   |
| D-Link System                     | 4         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.04%   |
| Motorola PCS                      | 3         | 0.04%   |
| Cypress Semiconductor             | 3         | 0.04%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.03%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1466      | 16.7%   |
| Intel Wi-Fi 6 AX200                                               | 367       | 4.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 330       | 3.76%   |
| Intel Wireless 8265 / 8275                                        | 328       | 3.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 259       | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 206       | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 201       | 2.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 199       | 2.27%   |
| Intel Wireless 8260                                               | 190       | 2.16%   |
| Intel Wi-Fi 6 AX201                                               | 183       | 2.08%   |
| Intel Wireless 7260                                               | 177       | 2.02%   |
| Intel Wireless 7265                                               | 165       | 1.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 143       | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 137       | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 130       | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 128       | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 124       | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 121       | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 119       | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 116       | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 114       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 104       | 1.18%   |
| Intel Wireless 3165                                               | 93        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 80        | 0.91%   |
| Intel Wireless-AC 9260                                            | 80        | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 78        | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 75        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 71        | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 71        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 66        | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 64        | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 64        | 0.73%   |
| Intel Wireless 3160                                               | 59        | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 57        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 57        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 55        | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 53        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 52        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 51        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2809      | 58.11%  |
| Qualcomm Atheros                  | 781       | 16.16%  |
| Realtek Semiconductor             | 600       | 12.41%  |
| Broadcom                          | 256       | 5.3%    |
| MediaTek                          | 94        | 1.94%   |
| Broadcom Limited                  | 54        | 1.12%   |
| Sierra Wireless                   | 52        | 1.08%   |
| Ralink                            | 35        | 0.72%   |
| TP-Link                           | 33        | 0.68%   |
| Dell                              | 24        | 0.5%    |
| Ralink Technology                 | 23        | 0.48%   |
| Qualcomm                          | 12        | 0.25%   |
| FIBOCOM                           | 9         | 0.19%   |
| ASUSTek Computer                  | 9         | 0.19%   |
| Ericsson Business Mobile Networks | 7         | 0.14%   |
| Qualcomm Atheros Communications   | 6         | 0.12%   |
| NetGear                           | 6         | 0.12%   |
| Hewlett-Packard                   | 5         | 0.1%    |
| Linksys                           | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| D-Link System                     | 4         | 0.08%   |
| D-Link                            | 2         | 0.04%   |
| Belkin Components                 | 2         | 0.04%   |
| TRENDnet                          | 1         | 0.02%   |
| Quectel Wireless Solutions        | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 367       | 7.55%   |
| Intel Wireless 8265 / 8275                                     | 328       | 6.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 206       | 4.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 199       | 4.09%   |
| Intel Wireless 8260                                            | 190       | 3.91%   |
| Intel Wi-Fi 6 AX201                                            | 183       | 3.76%   |
| Intel Wireless 7260                                            | 177       | 3.64%   |
| Intel Wireless 7265                                            | 165       | 3.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 143       | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 137       | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 130       | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 128       | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 124       | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 121       | 2.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 119       | 2.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 116       | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 104       | 2.14%   |
| Intel Wireless 3165                                            | 93        | 1.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 80        | 1.64%   |
| Intel Wireless-AC 9260                                         | 80        | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 71        | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 71        | 1.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 66        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 64        | 1.32%   |
| Intel Wireless 3160                                            | 59        | 1.21%   |
| Intel Centrino Ultimate-N 6300                                 | 57        | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 53        | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 52        | 1.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 51        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                  | 46        | 0.95%   |
| Intel Centrino Advanced-N 6235                                 | 37        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 34        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 32        | 0.66%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 28        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.56%   |
| Intel Centrino Advanced-N 6200                                 | 27        | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 25        | 0.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 25        | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 24        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2075      | 54.76%  |
| Intel                            | 1108      | 29.24%  |
| Qualcomm Atheros                 | 186       | 4.91%   |
| Broadcom                         | 99        | 2.61%   |
| Lenovo                           | 68        | 1.79%   |
| ASIX Electronics                 | 44        | 1.16%   |
| Marvell Technology Group         | 31        | 0.82%   |
| DisplayLink                      | 26        | 0.69%   |
| Broadcom Limited                 | 21        | 0.55%   |
| TP-Link                          | 16        | 0.42%   |
| Samsung Electronics              | 16        | 0.42%   |
| Nvidia                           | 16        | 0.42%   |
| Xiaomi                           | 10        | 0.26%   |
| Apple                            | 10        | 0.26%   |
| JMicron Technology               | 8         | 0.21%   |
| Huawei Technologies              | 7         | 0.18%   |
| Qualcomm                         | 6         | 0.16%   |
| Google                           | 6         | 0.16%   |
| MediaTek                         | 5         | 0.13%   |
| Hewlett-Packard                  | 5         | 0.13%   |
| OPPO Electronics                 | 4         | 0.11%   |
| D-Link                           | 3         | 0.08%   |
| Cypress Semiconductor            | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| vivo                             | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Spreadtrum Communications        | 1         | 0.03%   |
| Novatel Wireless                 | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Motorola PCS                     | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| ASUSTek Computer                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1466      | 38.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 330       | 8.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 259       | 6.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 201       | 5.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 114       | 2.96%   |
| Intel Ethernet Connection I219-LM                                 | 78        | 2.03%   |
| Intel Ethernet Connection (4) I219-V                              | 75        | 1.95%   |
| Intel Ethernet Connection I218-LM                                 | 64        | 1.66%   |
| Intel Ethernet Connection (6) I219-V                              | 57        | 1.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 55        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 1.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 47        | 1.22%   |
| Intel Ethernet Connection (10) I219-V                             | 45        | 1.17%   |
| Intel Ethernet Connection (6) I219-LM                             | 43        | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                     | 39        | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 0.83%   |
| Intel Ethernet Connection I219-V                                  | 30        | 0.78%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 29        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 21        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 21        | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 20        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 17        | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 17        | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.42%   |
| Lenovo ThinkPad TBT3 LAN                                          | 15        | 0.39%   |
| Intel Ethernet Connection I217-V                                  | 15        | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.36%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 13        | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 13        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4602      | 55.88%  |
| Ethernet | 3570      | 43.35%  |
| Modem    | 55        | 0.67%   |
| Unknown  | 9         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4005      | 79.83%  |
| Ethernet | 1010      | 20.13%  |
| Modem    | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3225      | 68.54%  |
| 1     | 1327      | 28.2%   |
| 0     | 98        | 2.08%   |
| 3     | 55        | 1.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 4055      | 84.64%  |
| Yes     | 733       | 15.3%   |
| Unknown | 3         | 0.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2290      | 58.17%  |
| Qualcomm Atheros Communications | 391       | 9.93%   |
| Realtek Semiconductor           | 347       | 8.81%   |
| Broadcom                        | 171       | 4.34%   |
| IMC Networks                    | 154       | 3.91%   |
| Lite-On Technology              | 146       | 3.71%   |
| Foxconn / Hon Hai               | 121       | 3.07%   |
| Apple                           | 102       | 2.59%   |
| Realtek                         | 40        | 1.02%   |
| Cambridge Silicon Radio         | 35        | 0.89%   |
| Dell                            | 33        | 0.84%   |
| Ralink                          | 24        | 0.61%   |
| Hewlett-Packard                 | 22        | 0.56%   |
| Toshiba                         | 17        | 0.43%   |
| ASUSTek Computer                | 14        | 0.36%   |
| Foxconn International           | 9         | 0.23%   |
| Ralink Technology               | 4         | 0.1%    |
| Alps Electric                   | 3         | 0.08%   |
| Unknown                         | 2         | 0.05%   |
| Qcom                            | 2         | 0.05%   |
| Opticis                         | 2         | 0.05%   |
| MediaTek                        | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Taiyo Yuden                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 940       | 23.86%  |
| Intel AX201 Bluetooth                               | 411       | 10.43%  |
| Intel AX200 Bluetooth                               | 357       | 9.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 337       | 8.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 222       | 5.63%   |
| Realtek Bluetooth Radio                             | 196       | 4.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 94        | 2.39%   |
| Apple Bluetooth Host Controller                     | 74        | 1.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 70        | 1.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 66        | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 57        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 52        | 1.32%   |
| IMC Networks Bluetooth Radio                        | 50        | 1.27%   |
| Intel AX210 Bluetooth                               | 49        | 1.24%   |
| IMC Networks Wireless_Device                        | 46        | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.12%   |
| Realtek Bluetooth Radio                             | 40        | 1.02%   |
| Lite-On Bluetooth Device                            | 37        | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 36        | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 36        | 0.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35        | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 33        | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                   | 28        | 0.71%   |
| Ralink RT3290 Bluetooth                             | 24        | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 0.56%   |
| IMC Networks Bluetooth Device                       | 21        | 0.53%   |
| Intel Bluetooth Device                              | 20        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.43%   |
| Apple Bluetooth USB Host Controller                 | 17        | 0.43%   |
| Dell DW375 Bluetooth Module                         | 16        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.3%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 12        | 0.3%    |
| Broadcom HP Portable SoftSailing                    | 11        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 3770      | 62.53%  |
| AMD                         | 891       | 14.78%  |
| Nvidia                      | 788       | 13.07%  |
| Lenovo                      | 78        | 1.29%   |
| Realtek Semiconductor       | 64        | 1.06%   |
| C-Media Electronics         | 57        | 0.95%   |
| GN Netcom                   | 43        | 0.71%   |
| Logitech                    | 35        | 0.58%   |
| Plantronics                 | 30        | 0.5%    |
| Hewlett-Packard             | 23        | 0.38%   |
| JMTek                       | 17        | 0.28%   |
| Texas Instruments           | 13        | 0.22%   |
| Creative Technology         | 12        | 0.2%    |
| SteelSeries ApS             | 11        | 0.18%   |
| Sony                        | 9         | 0.15%   |
| Kingston Technology         | 9         | 0.15%   |
| Razer USA                   | 8         | 0.13%   |
| DSEA A/S                    | 8         | 0.13%   |
| Corsair                     | 8         | 0.13%   |
| Apple                       | 8         | 0.13%   |
| Generalplus Technology      | 7         | 0.12%   |
| Blue Microphones            | 7         | 0.12%   |
| XMOS                        | 6         | 0.1%    |
| Samson Technologies         | 6         | 0.1%    |
| RODE Microphones            | 6         | 0.1%    |
| Dell                        | 6         | 0.1%    |
| Conexant Systems            | 6         | 0.1%    |
| SAVITECH                    | 5         | 0.08%   |
| Microsoft                   | 5         | 0.08%   |
| CMX Systems                 | 5         | 0.08%   |
| Tenx Technology             | 4         | 0.07%   |
| No brand                    | 4         | 0.07%   |
| GYROCOM C&C                 | 4         | 0.07%   |
| FiiO Electronics Technology | 4         | 0.07%   |
| Samsung Electronics         | 3         | 0.05%   |
| PreSonus Audio Electronics  | 3         | 0.05%   |
| M-Audio                     | 3         | 0.05%   |
| Focusrite-Novation          | 3         | 0.05%   |
| FIFINE Microphones          | 3         | 0.05%   |
| Cambridge Silicon Radio     | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 828       | 11.29%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 638       | 8.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 347       | 4.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 340       | 4.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 282       | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 249       | 3.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 233       | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 228       | 3.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 219       | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 198       | 2.7%    |
| Intel 8 Series HD Audio Controller                                                                | 198       | 2.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 188       | 2.56%   |
| Intel Broadwell-U Audio Controller                                                                | 188       | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 186       | 2.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 183       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 152       | 2.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 135       | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 117       | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 116       | 1.58%   |
| Intel CM238 HD Audio Controller                                                                   | 114       | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 109       | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 98        | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 87        | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 84        | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 69        | 0.94%   |
| Realtek Semiconductor USB Audio                                                                   | 64        | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 61        | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 59        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 54        | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 49        | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 48        | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 46        | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 45        | 0.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 42        | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 39        | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 33        | 0.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 32        | 0.44%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 31        | 0.42%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 30        | 0.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 30        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 872       | 29.36%  |
| SK hynix                                         | 669       | 22.53%  |
| Micron Technology                                | 414       | 13.94%  |
| Kingston                                         | 265       | 8.92%   |
| Crucial                                          | 165       | 5.56%   |
| Unknown                                          | 164       | 5.52%   |
| A-DATA Technology                                | 69        | 2.32%   |
| Ramaxel Technology                               | 68        | 2.29%   |
| Corsair                                          | 43        | 1.45%   |
| Elpida                                           | 27        | 0.91%   |
| Smart                                            | 22        | 0.74%   |
| Unknown (ABCD)                                   | 20        | 0.67%   |
| G.Skill                                          | 20        | 0.67%   |
| Team                                             | 16        | 0.54%   |
| Nanya Technology                                 | 16        | 0.54%   |
| Patriot                                          | 13        | 0.44%   |
| Smart Brazil                                     | 10        | 0.34%   |
| Unknown                                          | 10        | 0.34%   |
| Teikon                                           | 9         | 0.3%    |
| GOODRAM                                          | 8         | 0.27%   |
| Transcend                                        | 7         | 0.24%   |
| Avant                                            | 6         | 0.2%    |
| Goldkey                                          | 5         | 0.17%   |
| Apacer                                           | 4         | 0.13%   |
| Silicon Power                                    | 3         | 0.1%    |
| OnBoard                                          | 3         | 0.1%    |
| Kllisre                                          | 3         | 0.1%    |
| CSX                                              | 3         | 0.1%    |
| SHARETRONIC                                      | 2         | 0.07%   |
| Sesame                                           | 2         | 0.07%   |
| RZX                                              | 2         | 0.07%   |
| Qimonda                                          | 2         | 0.07%   |
| PNY                                              | 2         | 0.07%   |
| Memox                                            | 2         | 0.07%   |
| Uroad                                            | 1         | 0.03%   |
| Unknown (0x7301)                                 | 1         | 0.03%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.03%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.03%   |
| Timetec                                          | 1         | 0.03%   |
| SanMax                                           | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 53        | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 51        | 1.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 44        | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 36        | 1.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.83%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 25        | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 24        | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.73%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 23        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 22        | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 21        | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 21        | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 21        | 0.67%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.64%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 20        | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 20        | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.61%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 19        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 18        | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.57%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 18        | 0.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 17        | 0.54%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 17        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 17        | 0.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 16        | 0.51%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.51%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s | 16        | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 16        | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 15        | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 15        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1379      | 55.78%  |
| DDR3    | 718       | 29.05%  |
| LPDDR3  | 157       | 6.35%   |
| LPDDR4  | 125       | 5.06%   |
| DDR2    | 33        | 1.33%   |
| SDRAM   | 17        | 0.69%   |
| Unknown | 14        | 0.57%   |
| LPDDR5  | 13        | 0.53%   |
| DDR5    | 12        | 0.49%   |
| DDR     | 3         | 0.12%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2137      | 84.8%   |
| Row Of Chips | 315       | 12.5%   |
| Chip         | 44        | 1.75%   |
| DIMM         | 15        | 0.6%    |
| Unknown      | 9         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1093      | 40.56%  |
| 4096  | 792       | 29.39%  |
| 16384 | 485       | 18%     |
| 2048  | 207       | 7.68%   |
| 32768 | 80        | 2.97%   |
| 1024  | 34        | 1.26%   |
| 3072  | 2         | 0.07%   |
| 512   | 1         | 0.04%   |
| 64    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 671       | 25.07%  |
| 1600    | 519       | 19.39%  |
| 3200    | 502       | 18.75%  |
| 2400    | 231       | 8.63%   |
| 2133    | 205       | 7.66%   |
| 1333    | 94        | 3.51%   |
| 1334    | 85        | 3.18%   |
| 4267    | 60        | 2.24%   |
| 1867    | 60        | 2.24%   |
| 3266    | 44        | 1.64%   |
| 1067    | 32        | 1.2%    |
| Unknown | 25        | 0.93%   |
| 8400    | 21        | 0.78%   |
| 667     | 21        | 0.78%   |
| 4800    | 18        | 0.67%   |
| 6400    | 15        | 0.56%   |
| 4199    | 14        | 0.52%   |
| 4266    | 13        | 0.49%   |
| 1066    | 13        | 0.49%   |
| 3733    | 9         | 0.34%   |
| 800     | 9         | 0.34%   |
| 2933    | 4         | 0.15%   |
| 975     | 3         | 0.11%   |
| 533     | 2         | 0.07%   |
| 2048    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1777    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1200    | 1         | 0.04%   |
| 333     | 1         | 0.04%   |
| 133     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 26.67%  |
| Samsung Electronics | 6         | 20%     |
| Canon               | 6         | 20%     |
| Seiko Epson         | 3         | 10%     |
| Brother Industries  | 3         | 10%     |
| Ricoh               | 1         | 3.33%   |
| Prolific Technology | 1         | 3.33%   |
| Pantum              | 1         | 3.33%   |
| NXP Semiconductors  | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson WF-2830 Series           | 1         | 3.33%   |
| Seiko Epson L200 Series              | 1         | 3.33%   |
| Seiko Epson ET-2710 Series           | 1         | 3.33%   |
| Samsung SCX-4200 series              | 1         | 3.33%   |
| Samsung SCX-3200 Series              | 1         | 3.33%   |
| Samsung ML-331x Series Laser Printer | 1         | 3.33%   |
| Samsung M2070 Series                 | 1         | 3.33%   |
| Samsung CLX-6260 Series              | 1         | 3.33%   |
| Samsung C43x Series                  | 1         | 3.33%   |
| Ricoh SP 212SUw                      | 1         | 3.33%   |
| Prolific PL2305 Parallel Port        | 1         | 3.33%   |
| Pantum P2500W series                 | 1         | 3.33%   |
| NXP Semiconductors Printer-80        | 1         | 3.33%   |
| HP Photosmart B010 series            | 1         | 3.33%   |
| HP LaserJet 400 colorMFP M475dw      | 1         | 3.33%   |
| HP ENVY Pro 6400 series              | 1         | 3.33%   |
| HP ENVY 4500 series                  | 1         | 3.33%   |
| HP Deskjet 3510 series               | 1         | 3.33%   |
| HP Deskjet 3050A                     | 1         | 3.33%   |
| HP DeskJet 2300 series               | 1         | 3.33%   |
| HP DeskJet 2130 series               | 1         | 3.33%   |
| Canon TR8500 series                  | 1         | 3.33%   |
| Canon TR150 series                   | 1         | 3.33%   |
| Canon PIXMA MG3500 Series            | 1         | 3.33%   |
| Canon PIXMA MG3000 series            | 1         | 3.33%   |
| Canon MF220 Series                   | 1         | 3.33%   |
| Canon iP7200 series                  | 1         | 3.33%   |
| Brother Printer                      | 1         | 3.33%   |
| Brother HL-5250DN Printer            | 1         | 3.33%   |
| Brother DCP-T220                     | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 71.43%  |
| Seiko Epson | 2         | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220               | 2         | 28.57%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 14.29%  |
| Seiko Epson ES-D400 [GT-S80]          | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20    | 1         | 14.29%  |
| Canon CanoScan N650U/N656U            | 1         | 14.29%  |
| Canon CanoScan LiDE 210               | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1110      | 25.07%  |
| IMC Networks                           | 519       | 11.72%  |
| Acer                                   | 419       | 9.46%   |
| Realtek Semiconductor                  | 408       | 9.21%   |
| Microdia                               | 399       | 9.01%   |
| Sunplus Innovation Technology          | 244       | 5.51%   |
| Quanta                                 | 217       | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 185       | 4.18%   |
| Lite-On Technology                     | 145       | 3.27%   |
| Syntek                                 | 119       | 2.69%   |
| Logitech                               | 103       | 2.33%   |
| Apple                                  | 97        | 2.19%   |
| Suyin                                  | 80        | 1.81%   |
| Silicon Motion                         | 56        | 1.26%   |
| Luxvisions Innotech Limited            | 50        | 1.13%   |
| Samsung Electronics                    | 33        | 0.75%   |
| Alcor Micro                            | 32        | 0.72%   |
| Ricoh                                  | 29        | 0.65%   |
| Lenovo                                 | 19        | 0.43%   |
| Primax Electronics                     | 18        | 0.41%   |
| Microsoft                              | 13        | 0.29%   |
| Importek                               | 12        | 0.27%   |
| Z-Star Microelectronics                | 10        | 0.23%   |
| Sonix Technology                       | 7         | 0.16%   |
| icSpring                               | 7         | 0.16%   |
| Generalplus Technology                 | 7         | 0.16%   |
| SunplusIT                              | 6         | 0.14%   |
| ARC International                      | 6         | 0.14%   |
| ALi                                    | 6         | 0.14%   |
| Pixart Imaging                         | 5         | 0.11%   |
| KYE Systems (Mouse Systems)            | 5         | 0.11%   |
| Intel                                  | 5         | 0.11%   |
| Unknown                                | 4         | 0.09%   |
| WaveRider Communications               | 3         | 0.07%   |
| Tobii Technology AB                    | 3         | 0.07%   |
| MacroSilicon                           | 3         | 0.07%   |
| Genesys Logic                          | 3         | 0.07%   |
| Creative Technology                    | 3         | 0.07%   |
| Alpha Imaging Technology               | 3         | 0.07%   |
| Y Media                                | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 375       | 8.38%   |
| Microdia Integrated_Webcam_HD                                              | 232       | 5.19%   |
| IMC Networks Integrated Camera                                             | 222       | 4.96%   |
| Realtek Integrated_Webcam_HD                                               | 184       | 4.11%   |
| Acer Integrated Camera                                                     | 125       | 2.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 122       | 2.73%   |
| Chicony HD Webcam                                                          | 119       | 2.66%   |
| Sunplus Integrated_Webcam_HD                                               | 108       | 2.41%   |
| Syntek Integrated Camera                                                   | 75        | 1.68%   |
| Lite-On Integrated Camera                                                  | 68        | 1.52%   |
| Chicony Integrated Camera (1280x720@30)                                    | 67        | 1.5%    |
| Quanta HD User Facing                                                      | 50        | 1.12%   |
| Acer Lenovo EasyCamera                                                     | 50        | 1.12%   |
| Chicony HP HD Camera                                                       | 49        | 1.1%    |
| Acer SunplusIT Integrated Camera                                           | 46        | 1.03%   |
| Quanta HP TrueVision HD Camera                                             | 41        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 39        | 0.87%   |
| Microdia Integrated Webcam                                                 | 37        | 0.83%   |
| Chicony USB2.0 Camera                                                      | 34        | 0.76%   |
| Samsung Galaxy A5 (MTP)                                                    | 33        | 0.74%   |
| Lite-On HP HD Camera                                                       | 33        | 0.74%   |
| Quanta HD Webcam                                                           | 31        | 0.69%   |
| Realtek Integrated Webcam                                                  | 30        | 0.67%   |
| Apple iPhone5/5C/5S/6                                                      | 30        | 0.67%   |
| Sunplus HD WebCam                                                          | 29        | 0.65%   |
| Apple Built-in iSight                                                      | 29        | 0.65%   |
| Acer BisonCam, NB Pro                                                      | 29        | 0.65%   |
| Realtek USB Camera                                                         | 28        | 0.63%   |
| Chicony HP Wide Vision HD Camera                                           | 28        | 0.63%   |
| Acer HD Webcam                                                             | 28        | 0.63%   |
| Realtek Integrated Webcam HD                                               | 27        | 0.6%    |
| Logitech HD Pro Webcam C920                                                | 27        | 0.6%    |
| Quanta HP HD Camera                                                        | 26        | 0.58%   |
| Chicony USB2.0 HD UVC WebCam                                               | 26        | 0.58%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 26        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 26        | 0.58%   |
| Chicony HP Truevision HD camera                                            | 24        | 0.54%   |
| Chicony HP Truevision HD                                                   | 24        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 23        | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 23        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 412       | 34.77%  |
| Validity Sensors           | 394       | 33.25%  |
| Shenzhen Goodix Technology | 181       | 15.27%  |
| Elan Microelectronics      | 63        | 5.32%   |
| Upek                       | 54        | 4.56%   |
| LighTuning Technology      | 42        | 3.54%   |
| AuthenTec                  | 26        | 2.19%   |
| Samsung Electronics        | 5         | 0.42%   |
| Focal-systems.Corp         | 4         | 0.34%   |
| STMicroelectronics         | 3         | 0.25%   |
| Dell                       | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 202       | 17.03%  |
| Shenzhen Goodix  Fingerprint Device                                        | 98        | 8.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 92        | 7.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 76        | 6.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 75        | 6.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 52        | 4.38%   |
| Elan ELAN:Fingerprint                                                      | 44        | 3.71%   |
| Shenzhen Goodix FingerPrint                                                | 43        | 3.63%   |
| Unknown                                                                    | 42        | 3.54%   |
| Shenzhen Goodix Fingerprint Reader                                         | 40        | 3.37%   |
| Validity Sensors Synaptics WBDI                                            | 38        | 3.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 37        | 3.12%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 33        | 2.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 32        | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 24        | 2.02%   |
| Validity Sensors VFS491                                                    | 23        | 1.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 22        | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 20        | 1.69%   |
| Elan ELAN:ARM-M4                                                           | 18        | 1.52%   |
| Synaptics  WBDI                                                            | 17        | 1.43%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 1.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 1.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 14        | 1.18%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 1.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.67%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.51%   |
| Synaptics WBDI Device                                                      | 6         | 0.51%   |
| AuthenTec AES2810                                                          | 5         | 0.42%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.34%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.34%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.25%   |
| Samsung Fingerprint Device                                                 | 3         | 0.25%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.25%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.25%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.25%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 185       | 41.57%  |
| Broadcom                   | 174       | 39.1%   |
| Upek                       | 29        | 6.52%   |
| Lenovo                     | 26        | 5.84%   |
| O2 Micro                   | 10        | 2.25%   |
| Gemalto (was Gemplus)      | 5         | 1.12%   |
| SCM Microsystems           | 3         | 0.67%   |
| OmniKey                    | 3         | 0.67%   |
| Aladdin Knowledge Systems  | 3         | 0.67%   |
| Yubico.com                 | 1         | 0.22%   |
| Reiner SCT Kartensysteme   | 1         | 0.22%   |
| Realtek Semiconductor      | 1         | 0.22%   |
| Hewlett-Packard            | 1         | 0.22%   |
| Chicony Electronics        | 1         | 0.22%   |
| Athena Smartcard Solutions | 1         | 0.22%   |
| Advanced Card Systems      | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 184       | 41.35%  |
| Broadcom 5880                                                                | 58        | 13.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 46        | 10.34%  |
| Broadcom 58200                                                               | 37        | 8.31%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 6.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 6.52%   |
| Lenovo Integrated Smart Card Reader                                          | 26        | 5.84%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 2.02%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 4         | 0.9%    |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.45%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.22%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.22%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.22%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.22%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.22%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.22%   |
| OmniKey CardMan 4321                                                         | 1         | 0.22%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.22%   |
| OmniKey CardMan 1021                                                         | 1         | 0.22%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.22%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.22%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.22%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.22%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.22%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.22%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2829      | 58.38%  |
| 1     | 1657      | 34.19%  |
| 2     | 308       | 6.36%   |
| 3     | 42        | 0.87%   |
| 4     | 4         | 0.08%   |
| 6     | 3         | 0.06%   |
| 5     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1174      | 49.98%  |
| Graphics card            | 376       | 16.01%  |
| Multimedia controller    | 203       | 8.64%   |
| Chipcard                 | 171       | 7.28%   |
| Net/wireless             | 168       | 7.15%   |
| Camera                   | 75        | 3.19%   |
| Bluetooth                | 47        | 2%      |
| Storage                  | 39        | 1.66%   |
| Card reader              | 33        | 1.4%    |
| Network                  | 14        | 0.6%    |
| Communication controller | 14        | 0.6%    |
| Net/ethernet             | 13        | 0.55%   |
| Sound                    | 11        | 0.47%   |
| Modem                    | 7         | 0.3%    |
| Flash memory             | 2         | 0.09%   |
| Video                    | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

