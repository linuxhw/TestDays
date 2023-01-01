Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 3625

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | K53SC                       | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Valve         | Jupiter                     | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Valve         | Jupiter                     | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Apple         | MacBook5,1                  | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| HP            | Pavilion 15                 | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Valve         | Jupiter                     | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| HP            | G62                         | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Apple         | MacBookPro16,1              | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| ASUSTek       | K54C                        | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| Valve         | Jupiter                     | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| ASUSTek       | X540LA                      | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| HP            | Laptop 17-cn2xxx            | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Toshiba       | Satellite R830              | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Valve         | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| Sony          | VPCEB1Z1E                   | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Dell          | Latitude 7420               | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Dell          | Latitude E7240              | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| HP            | Laptop 15-db0xxx            | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| ASUSTek       | F3F                         | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HUAWEI        | NBD-WXX9                    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Valve         | Jupiter                     | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| GPD           | G1618-03                    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Dell          | Latitude 5420               | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Acer          | Aspire 5749                 | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| Dell          | Latitude E6540              | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| Dell          | XPS 15 9510                 | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| Acer          | Aspire 5750G                | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Chuwi         | HeroBook Air                | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| Apple         | MacBookAir7,2               | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| MSI           | Katana GF66 12UD            | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Dell          | Latitude 5285               | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Unknown       | Unknown                     | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| Dell          | XPS 9320                    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| Valve         | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| Dell          | Latitude E4310              | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |
| Alienware     | m15 R4                      | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| HP            | Compaq 6715b (GR667ET#AB... | [44de2345bb](https://linux-hardware.org/?probe=44de2345bb) | Jun 09, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| Dell          | Inspiron 13-7359            | [c46dcc9b6f](https://linux-hardware.org/?probe=c46dcc9b6f) | Jun 07, 2022 |
| HP            | Stream Notebook PC 13       | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3dd8394bb5](https://linux-hardware.org/?probe=3dd8394bb5) | Jun 04, 2022 |
| eMachines     | eME732                      | [c6d57c850c](https://linux-hardware.org/?probe=c6d57c850c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [185587d5e1](https://linux-hardware.org/?probe=185587d5e1) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | [65f67bae3c](https://linux-hardware.org/?probe=65f67bae3c) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | [41cad28720](https://linux-hardware.org/?probe=41cad28720) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [c996bce6b5](https://linux-hardware.org/?probe=c996bce6b5) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [08fe1f2d0f](https://linux-hardware.org/?probe=08fe1f2d0f) | May 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a1dfbe3337](https://linux-hardware.org/?probe=a1dfbe3337) | May 31, 2022 |
| Acer          | TravelMate P256-MG          | [22b617425d](https://linux-hardware.org/?probe=22b617425d) | May 31, 2022 |
| Fujitsu       | LIFEBOOK E5511              | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4fadee73e4](https://linux-hardware.org/?probe=4fadee73e4) | May 29, 2022 |
| Chuwi         | GemiBook                    | [432c1135b8](https://linux-hardware.org/?probe=432c1135b8) | May 29, 2022 |
| Lenovo        | G580 20150                  | [60128f5782](https://linux-hardware.org/?probe=60128f5782) | May 29, 2022 |
| Valve         | Jupiter                     | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Toshiba       | Satellite L10W-B-101        | [774d5a9eae](https://linux-hardware.org/?probe=774d5a9eae) | May 28, 2022 |
| MSI           | PR600                       | [09b736e706](https://linux-hardware.org/?probe=09b736e706) | May 27, 2022 |
| Medion        | S6421 MD60703               | [9fffed019c](https://linux-hardware.org/?probe=9fffed019c) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| HONOR         | HLYL-WXX9                   | [57d71fca8a](https://linux-hardware.org/?probe=57d71fca8a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| MSI           | Prestige 15 A11SCS          | [2433529434](https://linux-hardware.org/?probe=2433529434) | May 24, 2022 |
| Toshiba       | Satellite L10W-B-101        | [bb4ce9afdd](https://linux-hardware.org/?probe=bb4ce9afdd) | May 24, 2022 |
| Unknown       | Aspire E                    | [d437b15b97](https://linux-hardware.org/?probe=d437b15b97) | May 24, 2022 |
| Unknown       | Aspire E                    | [f46b38824f](https://linux-hardware.org/?probe=f46b38824f) | May 24, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| MSI           | GF63 Thin 9SC               | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| HP            | 15                          | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| Dell          | G15 5510                    | [0ca1f736f9](https://linux-hardware.org/?probe=0ca1f736f9) | May 22, 2022 |
| Samsung       | RF510/RF410/RF710           | [c146b79bd6](https://linux-hardware.org/?probe=c146b79bd6) | May 22, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| HP            | EliteBook 840 G5            | [48e5424ecb](https://linux-hardware.org/?probe=48e5424ecb) | May 19, 2022 |
| MSI           | Prestige 14 A12UC           | [189b62a372](https://linux-hardware.org/?probe=189b62a372) | May 19, 2022 |
| Dell          | Latitude E4310              | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| Valve         | Jupiter                     | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve         | Jupiter                     | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Lenovo        | V145-15AST 81MT             | [badf4d0a88](https://linux-hardware.org/?probe=badf4d0a88) | May 18, 2022 |
| Chuwi         | HeroBook Air                | [7d96e10672](https://linux-hardware.org/?probe=7d96e10672) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| Lenovo        | G580 2189                   | [e7de790c8a](https://linux-hardware.org/?probe=e7de790c8a) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude 5480               | [bccdb55064](https://linux-hardware.org/?probe=bccdb55064) | May 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [70cde2437b](https://linux-hardware.org/?probe=70cde2437b) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS0LE00    | [59eecf466b](https://linux-hardware.org/?probe=59eecf466b) | May 15, 2022 |
| Acer          | Aspire E1-522               | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Acer          | Aspire E1-522               | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| Dell          | Latitude 5420               | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| Samsung       | RF510/RF410/RF710           | [8134289438](https://linux-hardware.org/?probe=8134289438) | May 12, 2022 |
| HP            | Pavilion g6                 | [4f5ac891f4](https://linux-hardware.org/?probe=4f5ac891f4) | May 11, 2022 |
| Acer          | Aspire 5742G                | [f720d9e031](https://linux-hardware.org/?probe=f720d9e031) | May 11, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e6d1749248](https://linux-hardware.org/?probe=e6d1749248) | May 10, 2022 |
| MSI           | Modern 14 B11MO             | [75bc7c18db](https://linux-hardware.org/?probe=75bc7c18db) | May 10, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [02925e8fac](https://linux-hardware.org/?probe=02925e8fac) | May 10, 2022 |
| Acer          | TravelMate 6592             | [353516147d](https://linux-hardware.org/?probe=353516147d) | May 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [ae80aa69fe](https://linux-hardware.org/?probe=ae80aa69fe) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f269fd3294](https://linux-hardware.org/?probe=f269fd3294) | May 09, 2022 |
| Acer          | Aspire A515-54              | [1d37964706](https://linux-hardware.org/?probe=1d37964706) | May 08, 2022 |
| MSI           | GE62 2QD                    | [cef8637026](https://linux-hardware.org/?probe=cef8637026) | May 08, 2022 |
| SLIMBOOK      | Essential15L                | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Dell          | Inspiron 5515               | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Chuwi         | HeroBook Air                | [255ff705ac](https://linux-hardware.org/?probe=255ff705ac) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HP            | 340S G7 Notebook PC         | [c0d0f6435b](https://linux-hardware.org/?probe=c0d0f6435b) | May 06, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| Dell          | Latitude 5420               | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | Compaq 6730s                | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Compaq 15                   | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1467c3bb41](https://linux-hardware.org/?probe=1467c3bb41) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | [e8556f4acf](https://linux-hardware.org/?probe=e8556f4acf) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | [917add86ab](https://linux-hardware.org/?probe=917add86ab) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| Apple         | MacBookPro5,1               | [d6293e8334](https://linux-hardware.org/?probe=d6293e8334) | May 05, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [0afdbf373d](https://linux-hardware.org/?probe=0afdbf373d) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a30b11f1a0](https://linux-hardware.org/?probe=a30b11f1a0) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ecc7f176ff](https://linux-hardware.org/?probe=ecc7f176ff) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| Acer          | Aspire A315-56              | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| Acer          | Aspire one 1-131            | [ade813cf7f](https://linux-hardware.org/?probe=ade813cf7f) | May 03, 2022 |
| Acer          | Aspire 5742G                | [37dfe53a95](https://linux-hardware.org/?probe=37dfe53a95) | May 02, 2022 |
| Acer          | Aspire 5742G                | [aff42aff28](https://linux-hardware.org/?probe=aff42aff28) | May 02, 2022 |
| HP            | Notebook                    | [3bdd2a5e96](https://linux-hardware.org/?probe=3bdd2a5e96) | May 01, 2022 |
| HP            | Pavilion g6                 | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| HP            | 650                         | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Acer          | TravelMate 6592             | [7d4878ff33](https://linux-hardware.org/?probe=7d4878ff33) | Apr 29, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [dc1c531e45](https://linux-hardware.org/?probe=dc1c531e45) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [c3dad3331c](https://linux-hardware.org/?probe=c3dad3331c) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| Lenovo        | Z50-70 20354                | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| Dell          | G15 5510                    | [5126d58147](https://linux-hardware.org/?probe=5126d58147) | Apr 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [3fcb247b21](https://linux-hardware.org/?probe=3fcb247b21) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| MSI           | GX700                       | [b2cc52d381](https://linux-hardware.org/?probe=b2cc52d381) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| Lenovo        | ThinkPad P53 20QN000ESP     | [16b3189bd8](https://linux-hardware.org/?probe=16b3189bd8) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| eMachines     | D730                        | [09350021b3](https://linux-hardware.org/?probe=09350021b3) | Apr 20, 2022 |
| Lenovo        | Z50-70 20354                | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Chuwi         | Unknown                     | [a44bd392c5](https://linux-hardware.org/?probe=a44bd392c5) | Apr 18, 2022 |
| Lenovo        | Z50-70 20354                | [e693d05883](https://linux-hardware.org/?probe=e693d05883) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [4058d0c1ca](https://linux-hardware.org/?probe=4058d0c1ca) | Apr 17, 2022 |
| Acer          | Aspire 5750                 | [4ce545cc86](https://linux-hardware.org/?probe=4ce545cc86) | Apr 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | [65edd32378](https://linux-hardware.org/?probe=65edd32378) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| Toshiba       | NB520                       | [105666a973](https://linux-hardware.org/?probe=105666a973) | Apr 15, 2022 |
| AMI           | Intel                       | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Acer          | TravelMate P256-MG          | [55b07b48b3](https://linux-hardware.org/?probe=55b07b48b3) | Apr 14, 2022 |
| HP            | Laptop 15s-fq1xxx           | [48794f7ff0](https://linux-hardware.org/?probe=48794f7ff0) | Apr 14, 2022 |
| SLIMBOOK      | PRO                         | [97f545c3d4](https://linux-hardware.org/?probe=97f545c3d4) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | Presario C500 (RY512EA#A... | [558d84adac](https://linux-hardware.org/?probe=558d84adac) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| Unknown       | Unknown                     | [63f76ffc2b](https://linux-hardware.org/?probe=63f76ffc2b) | Apr 13, 2022 |
| Unknown       | Unknown                     | [3a9245cdab](https://linux-hardware.org/?probe=3a9245cdab) | Apr 13, 2022 |
| Acer          | Aspire E5-573G              | [0fbee9d8dc](https://linux-hardware.org/?probe=0fbee9d8dc) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| HP            | Compaq Mini CQ10-100        | [1acc227c33](https://linux-hardware.org/?probe=1acc227c33) | Apr 13, 2022 |
| Sony          | VGN-NW21EF_S                | [4ade997baf](https://linux-hardware.org/?probe=4ade997baf) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| MSI           | Prestige 15 A11SCX          | [a5bf5ddddf](https://linux-hardware.org/?probe=a5bf5ddddf) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| HP            | Pavilion g6                 | [19ccaef18f](https://linux-hardware.org/?probe=19ccaef18f) | Apr 11, 2022 |
| HP            | Pavilion g6                 | [dabfb4bb05](https://linux-hardware.org/?probe=dabfb4bb05) | Apr 11, 2022 |
| ASUSTek       | X540LJ                      | [2eb11881fa](https://linux-hardware.org/?probe=2eb11881fa) | Apr 09, 2022 |
| Dell          | Latitude D630               | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | [a0001e2492](https://linux-hardware.org/?probe=a0001e2492) | Apr 09, 2022 |
| HP            | Compaq 15                   | [e3c3ac6478](https://linux-hardware.org/?probe=e3c3ac6478) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| HP            | 250 G7 Notebook PC          | [6271f39c13](https://linux-hardware.org/?probe=6271f39c13) | Apr 08, 2022 |
| HP            | ProBook 650 G1              | [9bd404657b](https://linux-hardware.org/?probe=9bd404657b) | Apr 08, 2022 |
| HP            | Laptop 14s-dq1xxx           | [72c98b5e79](https://linux-hardware.org/?probe=72c98b5e79) | Apr 07, 2022 |
| Dell          | Studio 1749                 | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Acer          | Nitro AN517-41              | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| Acer          | Extensa 2511                | [00d24bfb95](https://linux-hardware.org/?probe=00d24bfb95) | Apr 05, 2022 |
| Dell          | XPS 15 9570                 | [0437f62b89](https://linux-hardware.org/?probe=0437f62b89) | Apr 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [91bae7b644](https://linux-hardware.org/?probe=91bae7b644) | Apr 05, 2022 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | [c5fcd04bc5](https://linux-hardware.org/?probe=c5fcd04bc5) | Apr 04, 2022 |
| HP            | Laptop 15-da0xxx            | [7894bcc256](https://linux-hardware.org/?probe=7894bcc256) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| Lenovo        | G580 2189                   | [da5b37bf9f](https://linux-hardware.org/?probe=da5b37bf9f) | Apr 02, 2022 |
| Toshiba       | Satellite L300              | [d3d1814f5d](https://linux-hardware.org/?probe=d3d1814f5d) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [afd4df967a](https://linux-hardware.org/?probe=afd4df967a) | Mar 29, 2022 |
| HP            | 355 G2                      | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dddc946b70](https://linux-hardware.org/?probe=dddc946b70) | Mar 29, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [e2dcac3e1a](https://linux-hardware.org/?probe=e2dcac3e1a) | Mar 29, 2022 |
| Chuwi         | LapBook SE                  | [69b963a8c0](https://linux-hardware.org/?probe=69b963a8c0) | Mar 28, 2022 |
| LG Electro... | 14Z90N-V.AR55B              | [4942a692f0](https://linux-hardware.org/?probe=4942a692f0) | Mar 28, 2022 |
| Dell          | XPS 13 9360                 | [9579421df6](https://linux-hardware.org/?probe=9579421df6) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 6464W4J        | [5f73680acf](https://linux-hardware.org/?probe=5f73680acf) | Mar 28, 2022 |
| HP            | Pavilion g6                 | [954723d6f4](https://linux-hardware.org/?probe=954723d6f4) | Mar 27, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [078c1af4c3](https://linux-hardware.org/?probe=078c1af4c3) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ba743bbb3b](https://linux-hardware.org/?probe=ba743bbb3b) | Mar 27, 2022 |
| Apple         | MacBook10,1                 | [62a1f4a38b](https://linux-hardware.org/?probe=62a1f4a38b) | Mar 25, 2022 |
| Apple         | MacBook10,1                 | [b58112c801](https://linux-hardware.org/?probe=b58112c801) | Mar 25, 2022 |
| Acer          | Aspire 5750G                | [4a7e22384f](https://linux-hardware.org/?probe=4a7e22384f) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8064b23bf4](https://linux-hardware.org/?probe=8064b23bf4) | Mar 25, 2022 |
| HP            | Laptop 17-cn0xxx            | [9400fdbebf](https://linux-hardware.org/?probe=9400fdbebf) | Mar 24, 2022 |
| HP            | Laptop 15-da0xxx            | [794139f740](https://linux-hardware.org/?probe=794139f740) | Mar 24, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [5a64dc1855](https://linux-hardware.org/?probe=5a64dc1855) | Mar 23, 2022 |
| Dell          | XPS 13 9360                 | [30003161fe](https://linux-hardware.org/?probe=30003161fe) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | Latitude E6330              | [a8d483108b](https://linux-hardware.org/?probe=a8d483108b) | Mar 22, 2022 |
| Acer          | TravelMate P256-MG          | [ec8aff9fc7](https://linux-hardware.org/?probe=ec8aff9fc7) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | [0d8a2d4ea4](https://linux-hardware.org/?probe=0d8a2d4ea4) | Mar 21, 2022 |
| DIODE         | MS-N014                     | [0b95290c21](https://linux-hardware.org/?probe=0b95290c21) | Mar 21, 2022 |
| ASUSTek       | X553MA                      | [56d8c8496b](https://linux-hardware.org/?probe=56d8c8496b) | Mar 20, 2022 |
| HUAWEI        | HN-WX9X                     | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E5430 non-vPro     | [28d7818dd8](https://linux-hardware.org/?probe=28d7818dd8) | Mar 19, 2022 |
| HP            | EliteBook 2740p             | [b0fbd4018d](https://linux-hardware.org/?probe=b0fbd4018d) | Mar 18, 2022 |
| HP            | Presario CQ57               | [d5985051c5](https://linux-hardware.org/?probe=d5985051c5) | Mar 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [cf2893ebfd](https://linux-hardware.org/?probe=cf2893ebfd) | Mar 16, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| HP            | Laptop 15-bs0xx             | [2dd60fe836](https://linux-hardware.org/?probe=2dd60fe836) | Mar 13, 2022 |
| HP            | Pavilion Notebook           | [1de76aac69](https://linux-hardware.org/?probe=1de76aac69) | Mar 12, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| ASUSTek       | K53U                        | [7f78b941ce](https://linux-hardware.org/?probe=7f78b941ce) | Mar 11, 2022 |
| Acer          | Aspire A114-31              | [aa9bcbb679](https://linux-hardware.org/?probe=aa9bcbb679) | Mar 11, 2022 |
| HP            | Pavilion g6                 | [a7ca755c8e](https://linux-hardware.org/?probe=a7ca755c8e) | Mar 11, 2022 |
| HP            | ENVY Notebook               | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS08Q0... | [10655c6e60](https://linux-hardware.org/?probe=10655c6e60) | Mar 11, 2022 |
| HP            | Pavilion g6                 | [570c07ee5c](https://linux-hardware.org/?probe=570c07ee5c) | Mar 10, 2022 |
| Acer          | Aspire S3                   | [6ae9c3b307](https://linux-hardware.org/?probe=6ae9c3b307) | Mar 10, 2022 |
| Dell          | Latitude 5520               | [bb234c5fd0](https://linux-hardware.org/?probe=bb234c5fd0) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | [3df16e8d72](https://linux-hardware.org/?probe=3df16e8d72) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | [a67d3468f1](https://linux-hardware.org/?probe=a67d3468f1) | Mar 10, 2022 |
| Quanta        | TW8/SW8/DW8                 | [463ca7f3a3](https://linux-hardware.org/?probe=463ca7f3a3) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| ASUSTek       | K52F                        | [8e1b16c60b](https://linux-hardware.org/?probe=8e1b16c60b) | Mar 09, 2022 |
| Timi          | TM1703                      | [f9a954eea3](https://linux-hardware.org/?probe=f9a954eea3) | Mar 09, 2022 |
| MSI           | Creator Z16 A11UET          | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4425801f5c](https://linux-hardware.org/?probe=4425801f5c) | Mar 09, 2022 |
| HP            | Laptop 14s-dq2xxx           | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| Notebook      | W517GU1                     | [6a4971b810](https://linux-hardware.org/?probe=6a4971b810) | Mar 09, 2022 |
| MSI           | Prestige 15 A11SCS          | [20757cc7e0](https://linux-hardware.org/?probe=20757cc7e0) | Mar 08, 2022 |
| Dell          | System XPS L322X            | [2aa0c05f64](https://linux-hardware.org/?probe=2aa0c05f64) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [6e8e3f12d0](https://linux-hardware.org/?probe=6e8e3f12d0) | Mar 06, 2022 |
| Dell          | Latitude E5430 non-vPro     | [04d9923f43](https://linux-hardware.org/?probe=04d9923f43) | Mar 06, 2022 |
| Toshiba       | Satellite Pro P200          | [6a8be21d50](https://linux-hardware.org/?probe=6a8be21d50) | Mar 06, 2022 |
| Chuwi         | HeroBook Air                | [77ffb9a5a6](https://linux-hardware.org/?probe=77ffb9a5a6) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | [167b8de1e1](https://linux-hardware.org/?probe=167b8de1e1) | Mar 05, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2862f94170](https://linux-hardware.org/?probe=2862f94170) | Mar 05, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [c480ac2c0f](https://linux-hardware.org/?probe=c480ac2c0f) | Mar 03, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e8dd84a845](https://linux-hardware.org/?probe=e8dd84a845) | Mar 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [89e8399104](https://linux-hardware.org/?probe=89e8399104) | Mar 03, 2022 |
| ASUSTek       | GL553VD                     | [b3c5530f89](https://linux-hardware.org/?probe=b3c5530f89) | Mar 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [3f1e43c90c](https://linux-hardware.org/?probe=3f1e43c90c) | Mar 01, 2022 |
| HONOR         | HLYL-WXX9                   | [c2de0e3f1c](https://linux-hardware.org/?probe=c2de0e3f1c) | Feb 28, 2022 |
| Apple         | MacBookAir7,2               | [e2bc04b6f4](https://linux-hardware.org/?probe=e2bc04b6f4) | Feb 27, 2022 |
| Apple         | MacBookAir7,2               | [592d42e16c](https://linux-hardware.org/?probe=592d42e16c) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| Packard Be... | EasyNote TK85               | [97ab51b64a](https://linux-hardware.org/?probe=97ab51b64a) | Feb 26, 2022 |
| HP            | Notebook                    | [51dbbe9d8d](https://linux-hardware.org/?probe=51dbbe9d8d) | Feb 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [efd62e1ed7](https://linux-hardware.org/?probe=efd62e1ed7) | Feb 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ac4073b44](https://linux-hardware.org/?probe=0ac4073b44) | Feb 26, 2022 |
| Teclast       | F15 Plus                    | [a14a5fd6eb](https://linux-hardware.org/?probe=a14a5fd6eb) | Feb 26, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| Toshiba       | Satellite Pro C650          | [15fb8724cf](https://linux-hardware.org/?probe=15fb8724cf) | Feb 25, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [928d2937db](https://linux-hardware.org/?probe=928d2937db) | Feb 25, 2022 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [bee22eb4da](https://linux-hardware.org/?probe=bee22eb4da) | Feb 25, 2022 |
| ASUSTek       | X751LD                      | [7159c22bcd](https://linux-hardware.org/?probe=7159c22bcd) | Feb 25, 2022 |
| Teclast       | F15 Plus                    | [e8e8b2f6da](https://linux-hardware.org/?probe=e8e8b2f6da) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [13b7868e73](https://linux-hardware.org/?probe=13b7868e73) | Feb 24, 2022 |
| ASUSTek       | X551MA                      | [4796f04ae9](https://linux-hardware.org/?probe=4796f04ae9) | Feb 24, 2022 |
| Packard Be... | DOT S                       | [e90543b727](https://linux-hardware.org/?probe=e90543b727) | Feb 24, 2022 |
| ASUSTek       | X551MA                      | [1a3cbf4e30](https://linux-hardware.org/?probe=1a3cbf4e30) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [15df5df598](https://linux-hardware.org/?probe=15df5df598) | Feb 24, 2022 |
| HP            | ProBook 4510s               | [83a16ef7f8](https://linux-hardware.org/?probe=83a16ef7f8) | Feb 23, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [46b3194e02](https://linux-hardware.org/?probe=46b3194e02) | Feb 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2394a1f3a8](https://linux-hardware.org/?probe=2394a1f3a8) | Feb 23, 2022 |
| HP            | Pavilion g6                 | [1c1f4685eb](https://linux-hardware.org/?probe=1c1f4685eb) | Feb 22, 2022 |
| Dell          | Inspiron 5515               | [883e979d85](https://linux-hardware.org/?probe=883e979d85) | Feb 22, 2022 |
| HP            | Mini 210-1100               | [fabcf91b6c](https://linux-hardware.org/?probe=fabcf91b6c) | Feb 22, 2022 |
| HP            | Mini 210-1100               | [55d5641a6b](https://linux-hardware.org/?probe=55d5641a6b) | Feb 22, 2022 |
| HP            | Laptop 15-db0xxx            | [32942f112f](https://linux-hardware.org/?probe=32942f112f) | Feb 21, 2022 |
| HP            | Notebook                    | [d734cd43d3](https://linux-hardware.org/?probe=d734cd43d3) | Feb 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [26dbfadfe1](https://linux-hardware.org/?probe=26dbfadfe1) | Feb 21, 2022 |
| HP            | 250 G4 Notebook PC          | [7d3c0014c0](https://linux-hardware.org/?probe=7d3c0014c0) | Feb 20, 2022 |
| HP            | Pavilion g6                 | [77bcf6cc10](https://linux-hardware.org/?probe=77bcf6cc10) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a551128b45](https://linux-hardware.org/?probe=a551128b45) | Feb 18, 2022 |
| Chuwi         | HeroBook Air                | [1955975178](https://linux-hardware.org/?probe=1955975178) | Feb 18, 2022 |
| Unknown       | Unknown                     | [e0ce842fa6](https://linux-hardware.org/?probe=e0ce842fa6) | Feb 18, 2022 |
| Dell          | Latitude E5410              | [c60f9e4a42](https://linux-hardware.org/?probe=c60f9e4a42) | Feb 17, 2022 |
| Chuwi         | GemiBook                    | [596102e73f](https://linux-hardware.org/?probe=596102e73f) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [bda7853dd1](https://linux-hardware.org/?probe=bda7853dd1) | Feb 17, 2022 |
| Acer          | Aspire M3-581T              | [1229cec202](https://linux-hardware.org/?probe=1229cec202) | Feb 16, 2022 |
| Notebook      | N141CU                      | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| HP            | EliteBook 2740p             | [30d2deeb07](https://linux-hardware.org/?probe=30d2deeb07) | Feb 16, 2022 |
| eMachines     | D730                        | [b1b46f9a2f](https://linux-hardware.org/?probe=b1b46f9a2f) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [64d19bc64f](https://linux-hardware.org/?probe=64d19bc64f) | Feb 13, 2022 |
| Acer          | Extensa 2519                | [4da8d63710](https://linux-hardware.org/?probe=4da8d63710) | Feb 13, 2022 |
| Toshiba       | Satellite L755              | [0c388987dc](https://linux-hardware.org/?probe=0c388987dc) | Feb 13, 2022 |
| Dell          | Latitude 14 Rugged (5404... | [c15ba7893e](https://linux-hardware.org/?probe=c15ba7893e) | Feb 13, 2022 |
| ASUSTek       | S550CM                      | [a6605f0fa3](https://linux-hardware.org/?probe=a6605f0fa3) | Feb 13, 2022 |
| Acer          | Aspire V5-122               | [d516569472](https://linux-hardware.org/?probe=d516569472) | Feb 13, 2022 |
| Dell          | Latitude 14 Rugged (5404... | [37267c6596](https://linux-hardware.org/?probe=37267c6596) | Feb 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [574d71e586](https://linux-hardware.org/?probe=574d71e586) | Feb 13, 2022 |
| Dell          | Inspiron 5515               | [3213a8a116](https://linux-hardware.org/?probe=3213a8a116) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| Toshiba       | TECRA M10                   | [69dc5e3118](https://linux-hardware.org/?probe=69dc5e3118) | Feb 11, 2022 |
| HP            | Pavilion g6                 | [da04806287](https://linux-hardware.org/?probe=da04806287) | Feb 11, 2022 |
| MSI           | Katana GF66 11UC            | [6c784517e1](https://linux-hardware.org/?probe=6c784517e1) | Feb 11, 2022 |
| MSI           | Prestige 14 A10RB           | [7195cacd54](https://linux-hardware.org/?probe=7195cacd54) | Feb 10, 2022 |
| ASUSTek       | X550LD                      | [65d1ec0733](https://linux-hardware.org/?probe=65d1ec0733) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [265a5ef9aa](https://linux-hardware.org/?probe=265a5ef9aa) | Feb 10, 2022 |
| Apple         | MacBookPro6,2               | [7208fba41e](https://linux-hardware.org/?probe=7208fba41e) | Feb 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [b3067b4ba2](https://linux-hardware.org/?probe=b3067b4ba2) | Feb 09, 2022 |
| HP            | Pavilion dv2000 (RR100EA... | [fc786f9d3f](https://linux-hardware.org/?probe=fc786f9d3f) | Feb 09, 2022 |
| Compal        | PBL21                       | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Acer          | TravelMate 5720             | [d0756aac7e](https://linux-hardware.org/?probe=d0756aac7e) | Feb 09, 2022 |
| HP            | Notebook                    | [7900320935](https://linux-hardware.org/?probe=7900320935) | Feb 09, 2022 |
| Samsung       | X420/X520                   | [cd4b91a032](https://linux-hardware.org/?probe=cd4b91a032) | Feb 08, 2022 |
| HP            | ProBook 6475b               | [770340d4f9](https://linux-hardware.org/?probe=770340d4f9) | Feb 08, 2022 |
| Samsung       | Q310                        | [a558af5b07](https://linux-hardware.org/?probe=a558af5b07) | Feb 08, 2022 |
| HP            | 250 G6 Notebook PC          | [40b0583970](https://linux-hardware.org/?probe=40b0583970) | Feb 08, 2022 |
| Toshiba       | Satellite U500              | [a5e6d93704](https://linux-hardware.org/?probe=a5e6d93704) | Feb 07, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c3722a690](https://linux-hardware.org/?probe=9c3722a690) | Feb 07, 2022 |
| ASUSTek       | K73SV                       | [d02cd235da](https://linux-hardware.org/?probe=d02cd235da) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e5f7c593d7](https://linux-hardware.org/?probe=e5f7c593d7) | Feb 06, 2022 |
| Medion        | E4241 MD60996               | [d89f5e4089](https://linux-hardware.org/?probe=d89f5e4089) | Feb 05, 2022 |
| HP            | Compaq Mini CQ10-100        | [5a471683f7](https://linux-hardware.org/?probe=5a471683f7) | Feb 05, 2022 |
| Acer          | Aspire 5715Z                | [378fec89b1](https://linux-hardware.org/?probe=378fec89b1) | Feb 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [cba975e95c](https://linux-hardware.org/?probe=cba975e95c) | Feb 02, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [4a5841b0dc](https://linux-hardware.org/?probe=4a5841b0dc) | Feb 02, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [006670e3fd](https://linux-hardware.org/?probe=006670e3fd) | Feb 02, 2022 |
| HP            | OMEN by Laptop              | [196508f0aa](https://linux-hardware.org/?probe=196508f0aa) | Feb 01, 2022 |
| MSI           | GL73 8RC                    | [597e463fc8](https://linux-hardware.org/?probe=597e463fc8) | Feb 01, 2022 |
| HP            | Laptop 15-db0xxx            | [523a77cee7](https://linux-hardware.org/?probe=523a77cee7) | Feb 01, 2022 |
| Dell          | Inspiron 7352               | [f36de689e1](https://linux-hardware.org/?probe=f36de689e1) | Feb 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7beeaf4687](https://linux-hardware.org/?probe=7beeaf4687) | Jan 31, 2022 |
| Lenovo        | V14-ADA 82C6                | [e8c4b3dfce](https://linux-hardware.org/?probe=e8c4b3dfce) | Jan 31, 2022 |
| HP            | OMEN by Laptop              | [67f194f1e2](https://linux-hardware.org/?probe=67f194f1e2) | Jan 29, 2022 |
| Acer          | Aspire V5-571               | [9c1e6c6a9e](https://linux-hardware.org/?probe=9c1e6c6a9e) | Jan 29, 2022 |
| Toshiba       | TECRA R950                  | [53fc5e9542](https://linux-hardware.org/?probe=53fc5e9542) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bc7f79d54b](https://linux-hardware.org/?probe=bc7f79d54b) | Jan 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a7df57bad0](https://linux-hardware.org/?probe=a7df57bad0) | Jan 28, 2022 |
| Dell          | XPS 15 7590                 | [39e13d6eeb](https://linux-hardware.org/?probe=39e13d6eeb) | Jan 27, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3c241e8e7f](https://linux-hardware.org/?probe=3c241e8e7f) | Jan 27, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9c8d4276ff](https://linux-hardware.org/?probe=9c8d4276ff) | Jan 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [a760b631d0](https://linux-hardware.org/?probe=a760b631d0) | Jan 26, 2022 |
| MSI           | GE60 2OC\2OE                | [dee5b3e5a3](https://linux-hardware.org/?probe=dee5b3e5a3) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [df690ab5bd](https://linux-hardware.org/?probe=df690ab5bd) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| Fujitsu       | LIFEBOOK U748               | [cad36b0eba](https://linux-hardware.org/?probe=cad36b0eba) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [b59e4cbfef](https://linux-hardware.org/?probe=b59e4cbfef) | Jan 23, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| AZW           | SEi                         | [71b530bc33](https://linux-hardware.org/?probe=71b530bc33) | Jan 22, 2022 |
| Lenovo        | G50-45 80MQ                 | [6a21be0bff](https://linux-hardware.org/?probe=6a21be0bff) | Jan 22, 2022 |
| Acer          | Aspire VN7-791              | [2abf48de85](https://linux-hardware.org/?probe=2abf48de85) | Jan 21, 2022 |
| Lenovo        | G580 2189                   | [3f1adf101d](https://linux-hardware.org/?probe=3f1adf101d) | Jan 21, 2022 |
| ASUSTek       | E200HA                      | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 381       | 14.31%  |
| Ubuntu 18.04      | 251       | 9.43%   |
| Debian 11         | 115       | 4.32%   |
| Ubuntu 22.04      | 96        | 3.6%    |
| OpenMandriva 4.2  | 83        | 3.12%   |
| KDE neon 20.04    | 63        | 2.37%   |
| OpenMandriva 4.3  | 57        | 2.14%   |
| Zorin 16          | 51        | 1.92%   |
| Linux Mint 20.3   | 41        | 1.54%   |
| Arch              | 41        | 1.54%   |
| Ubuntu 20.10      | 39        | 1.46%   |
| Xubuntu 20.04     | 37        | 1.39%   |
| Linux Mint 19.3   | 36        | 1.35%   |
| Debian 10         | 36        | 1.35%   |
| Ubuntu 19.10      | 34        | 1.28%   |
| Manjaro           | 33        | 1.24%   |
| Ubuntu 21.04      | 32        | 1.2%    |
| Ubuntu 19.04      | 32        | 1.2%    |
| Linux Mint 20.1   | 31        | 1.16%   |
| Linux Mint 20     | 30        | 1.13%   |
| Ubuntu 21.10      | 29        | 1.09%   |
| Fedora 36         | 29        | 1.09%   |
| Kubuntu 20.04     | 28        | 1.05%   |
| Xubuntu 18.04     | 27        | 1.01%   |
| Linux Mint 20.2   | 26        | 0.98%   |
| Zorin 15          | 25        | 0.94%   |
| Fedora 35         | 25        | 0.94%   |
| Fedora 34         | 24        | 0.9%    |
| Fedora 33         | 24        | 0.9%    |
| Arch Rolling      | 24        | 0.9%    |
| ROSA R10          | 22        | 0.83%   |
| Ubuntu 18.10      | 21        | 0.79%   |
| Pop!_OS 20.04     | 21        | 0.79%   |
| Linux Mint 21     | 20        | 0.75%   |
| Pop!_OS 22.04     | 19        | 0.71%   |
| Pop!_OS 20.10     | 19        | 0.71%   |
| Linux Mint 19.2   | 17        | 0.64%   |
| Debian Testing    | 17        | 0.64%   |
| Ubuntu 16.04      | 16        | 0.6%    |
| Ubuntu MATE 20.04 | 15        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 901       | 35.47%  |
| Linux Mint    | 207       | 8.15%   |
| Debian        | 179       | 7.05%   |
| OpenMandriva  | 155       | 6.1%    |
| Fedora        | 131       | 5.16%   |
| Endless       | 100       | 3.94%   |
| Manjaro       | 89        | 3.5%    |
| Zorin         | 79        | 3.11%   |
| KDE neon      | 74        | 2.91%   |
| Xubuntu       | 72        | 2.83%   |
| Pop!_OS       | 72        | 2.83%   |
| Arch          | 64        | 2.52%   |
| Kubuntu       | 59        | 2.32%   |
| ROSA          | 54        | 2.13%   |
| Ubuntu MATE   | 30        | 1.18%   |
| Elementary    | 26        | 1.02%   |
| Ubuntu Unity  | 23        | 0.91%   |
| openSUSE      | 19        | 0.75%   |
| Kali          | 18        | 0.71%   |
| BlackPanther  | 16        | 0.63%   |
| Lubuntu       | 15        | 0.59%   |
| SteamOS       | 14        | 0.55%   |
| Gentoo        | 13        | 0.51%   |
| ArcoLinux     | 13        | 0.51%   |
| Parrot        | 12        | 0.47%   |
| LMDE          | 11        | 0.43%   |
| EndeavourOS   | 9         | 0.35%   |
| Ubuntu Budgie | 7         | 0.28%   |
| MX            | 7         | 0.28%   |
| Clear Linux   | 6         | 0.24%   |
| Deepin        | 5         | 0.2%    |
| CentOS        | 5         | 0.2%    |
| RHEL          | 4         | 0.16%   |
| Garuda Linux  | 4         | 0.16%   |
| Solus         | 3         | 0.12%   |
| Reborn OS     | 3         | 0.12%   |
| Q4OS          | 3         | 0.12%   |
| Peppermint    | 3         | 0.12%   |
| Nobara        | 3         | 0.12%   |
| Linux Lite    | 3         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 81        | 2.82%   |
| 5.16.7-desktop-1omv4003         | 57        | 1.98%   |
| 5.4.0-42-generic                | 48        | 1.67%   |
| 5.10.0-8-amd64                  | 34        | 1.18%   |
| 5.4.0-58-generic                | 33        | 1.15%   |
| 5.15.0-52-generic               | 32        | 1.11%   |
| 5.3.0-28-generic                | 31        | 1.08%   |
| 5.15.0-56-generic               | 28        | 0.97%   |
| 5.4.0-54-generic                | 27        | 0.94%   |
| 5.4.0-52-generic                | 26        | 0.9%    |
| 5.4.0-26-generic                | 26        | 0.9%    |
| 5.10.0-18-amd64                 | 23        | 0.8%    |
| 5.0.0-37-generic                | 22        | 0.77%   |
| 5.3.0-46-generic                | 21        | 0.73%   |
| 5.3.0-40-generic                | 21        | 0.73%   |
| 5.15.0-53-generic               | 21        | 0.73%   |
| 5.15.0-48-generic               | 21        | 0.73%   |
| 5.11.0-27-generic               | 21        | 0.73%   |
| 5.4.0-65-generic                | 20        | 0.7%    |
| 5.4.0-48-generic                | 20        | 0.7%    |
| 5.11.0-43-generic               | 19        | 0.66%   |
| 5.11.0-41-generic               | 19        | 0.66%   |
| 5.4.0-72-generic                | 18        | 0.63%   |
| 5.4.0-40-generic                | 18        | 0.63%   |
| 5.0.0-32-generic                | 18        | 0.63%   |
| 5.8.0-44-generic                | 17        | 0.59%   |
| 5.4.0-19-generic                | 16        | 0.56%   |
| 5.3.0-45-generic                | 16        | 0.56%   |
| 5.8.0-14-generic                | 15        | 0.52%   |
| 5.4.0-29-generic                | 15        | 0.52%   |
| 5.15.0-47-generic               | 15        | 0.52%   |
| 5.13.0-28-generic               | 15        | 0.52%   |
| 5.8.0-43-generic                | 14        | 0.49%   |
| 5.4.0-70-generic                | 14        | 0.49%   |
| 5.4.0-53-generic                | 14        | 0.49%   |
| 5.3.0-51-generic                | 14        | 0.49%   |
| 5.3.0-42-generic                | 14        | 0.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14        | 0.49%   |
| 5.4.0-91-generic                | 13        | 0.45%   |
| 5.4.0-37-generic                | 13        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 528       | 19.42%  |
| 4.15.0  | 201       | 7.39%   |
| 5.15.0  | 194       | 7.13%   |
| 5.11.0  | 166       | 6.11%   |
| 5.3.0   | 153       | 5.63%   |
| 5.8.0   | 150       | 5.52%   |
| 5.10.0  | 135       | 4.97%   |
| 5.13.0  | 127       | 4.67%   |
| 5.0.0   | 109       | 4.01%   |
| 5.10.14 | 82        | 3.02%   |
| 4.18.0  | 71        | 2.61%   |
| 5.16.7  | 61        | 2.24%   |
| 4.19.0  | 41        | 1.51%   |
| 5.19.0  | 23        | 0.85%   |
| 4.9.60  | 15        | 0.55%   |
| 5.14.0  | 14        | 0.51%   |
| 5.18.0  | 13        | 0.48%   |
| 4.4.0   | 13        | 0.48%   |
| 4.18.16 | 13        | 0.48%   |
| 6.0.0   | 12        | 0.44%   |
| 5.9.16  | 10        | 0.37%   |
| 5.17.5  | 8         | 0.29%   |
| 5.3.18  | 7         | 0.26%   |
| 5.17.1  | 7         | 0.26%   |
| 5.16.0  | 7         | 0.26%   |
| 5.13.12 | 7         | 0.26%   |
| 5.11.12 | 7         | 0.26%   |
| 6.0.6   | 6         | 0.22%   |
| 6.0.12  | 6         | 0.22%   |
| 5.9.0   | 6         | 0.22%   |
| 5.16.11 | 6         | 0.22%   |
| 5.12.4  | 6         | 0.22%   |
| 6.0.10  | 5         | 0.18%   |
| 5.7.0   | 5         | 0.18%   |
| 5.19.2  | 5         | 0.18%   |
| 5.16.9  | 5         | 0.18%   |
| 5.15.12 | 5         | 0.18%   |
| 5.10.7  | 5         | 0.18%   |
| 4.9.20  | 5         | 0.18%   |
| 4.9.0   | 5         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 560       | 20.82%  |
| 5.10    | 254       | 9.44%   |
| 5.15    | 245       | 9.11%   |
| 4.15    | 201       | 7.47%   |
| 5.11    | 194       | 7.21%   |
| 5.8     | 176       | 6.54%   |
| 5.3     | 168       | 6.25%   |
| 5.13    | 147       | 5.46%   |
| 5.0     | 111       | 4.13%   |
| 5.16    | 96        | 3.57%   |
| 4.18    | 84        | 3.12%   |
| 5.19    | 55        | 2.04%   |
| 4.19    | 49        | 1.82%   |
| 6.0     | 46        | 1.71%   |
| 5.14    | 39        | 1.45%   |
| 4.9     | 38        | 1.41%   |
| 5.18    | 36        | 1.34%   |
| 5.9     | 29        | 1.08%   |
| 5.17    | 29        | 1.08%   |
| 5.6     | 25        | 0.93%   |
| 5.7     | 24        | 0.89%   |
| 5.12    | 23        | 0.86%   |
| 5.5     | 14        | 0.52%   |
| 4.4     | 14        | 0.52%   |
| 4.16    | 5         | 0.19%   |
| 6.1     | 4         | 0.15%   |
| 5.2     | 4         | 0.15%   |
| 4.1     | 4         | 0.15%   |
| 3.10    | 4         | 0.15%   |
| 5.1     | 3         | 0.11%   |
| 4.20    | 3         | 0.11%   |
| 4.13    | 3         | 0.11%   |
| 4.8     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 3.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2346      | 95.29%  |
| i686   | 116       | 4.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1137      | 44.09%  |
| KDE5             | 411       | 15.94%  |
| Unknown          | 323       | 12.52%  |
| XFCE             | 200       | 7.75%   |
| X-Cinnamon       | 156       | 6.05%   |
| MATE             | 78        | 3.02%   |
| KDE              | 76        | 2.95%   |
| Cinnamon         | 28        | 1.09%   |
| Pantheon         | 25        | 0.97%   |
| Unity            | 22        | 0.85%   |
| KDE4             | 22        | 0.85%   |
| LXQt             | 20        | 0.78%   |
| i3               | 15        | 0.58%   |
| LXDE             | 14        | 0.54%   |
| Budgie           | 11        | 0.43%   |
| GNOME Flashback  | 10        | 0.39%   |
| Deepin           | 9         | 0.35%   |
| openbox          | 4         | 0.16%   |
| GNOME Classic    | 4         | 0.16%   |
| bspwm            | 3         | 0.12%   |
| DWM              | 2         | 0.08%   |
| trinity          | 1         | 0.04%   |
| river            | 1         | 0.04%   |
| qtile            | 1         | 0.04%   |
| Lubuntu          | 1         | 0.04%   |
| lightdm-xsession | 1         | 0.04%   |
| i3-with-shmlog   | 1         | 0.04%   |
| enlightenment    | 1         | 0.04%   |
| Cutefish         | 1         | 0.04%   |
| awesome          | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2006      | 79.29%  |
| Wayland | 323       | 12.77%  |
| Unknown | 184       | 7.27%   |
| Tty     | 17        | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1356      | 53.22%  |
| SDDM    | 352       | 13.81%  |
| GDM     | 331       | 12.99%  |
| GDM3    | 192       | 7.54%   |
| LightDM | 191       | 7.5%    |
| TDM     | 90        | 3.53%   |
| KDM     | 24        | 0.94%   |
| XDM     | 7         | 0.27%   |
| Ly      | 3         | 0.12%   |
| SLiM    | 2         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1446      | 57.27%  |
| en_US          | 445       | 17.62%  |
| Unknown        | 333       | 13.19%  |
| ca_ES          | 96        | 3.8%    |
| en_GB          | 59        | 2.34%   |
| C              | 24        | 0.95%   |
| de_DE          | 18        | 0.71%   |
| gl_ES          | 12        | 0.48%   |
| eu_ES          | 10        | 0.4%    |
| fr_FR          | 9         | 0.36%   |
| ru_RU          | 8         | 0.32%   |
| it_IT          | 7         | 0.28%   |
| an_ES          | 7         | 0.28%   |
| es_AR          | 6         | 0.24%   |
| es_MX          | 5         | 0.2%    |
| pt_BR          | 4         | 0.16%   |
| en_AG          | 4         | 0.16%   |
| ca_AD          | 4         | 0.16%   |
| fr_BE          | 3         | 0.12%   |
| pl_PL          | 2         | 0.08%   |
| nl_NL          | 2         | 0.08%   |
| es_US          | 2         | 0.08%   |
| es_BO          | 2         | 0.08%   |
| en_IE          | 2         | 0.08%   |
| sp_SP          | 1         | 0.04%   |
| POSIX          | 1         | 0.04%   |
| nb_NO          | 1         | 0.04%   |
| fr_CH          | 1         | 0.04%   |
| et_EE          | 1         | 0.04%   |
| es_VE          | 1         | 0.04%   |
| es_PE          | 1         | 0.04%   |
| en_NZ          | 1         | 0.04%   |
| en_HK          | 1         | 0.04%   |
| en_CA          | 1         | 0.04%   |
| en_AU          | 1         | 0.04%   |
| de_CH          | 1         | 0.04%   |
| de_AT          | 1         | 0.04%   |
| ca_ES@valencia | 1         | 0.04%   |
| C.UTF8         | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1341      | 53.47%  |
| BIOS | 1167      | 46.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2002      | 79.63%  |
| Overlay | 177       | 7.04%   |
| Btrfs   | 153       | 6.09%   |
| Unknown | 111       | 4.42%   |
| Xfs     | 32        | 1.27%   |
| Zfs     | 16        | 0.64%   |
| Ext2    | 10        | 0.4%    |
| Tmpfs   | 4         | 0.16%   |
| Ext3    | 4         | 0.16%   |
| Jfs     | 2         | 0.08%   |
| Aufs    | 2         | 0.08%   |
| F2fs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1454      | 57.95%  |
| GPT     | 805       | 32.08%  |
| MBR     | 250       | 9.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2227      | 89.12%  |
| Yes       | 272       | 10.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1748      | 69.92%  |
| Yes       | 752       | 30.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 472       | 19.18%  |
| Lenovo              | 426       | 17.31%  |
| ASUSTek Computer    | 371       | 15.08%  |
| Acer                | 248       | 10.08%  |
| Dell                | 200       | 8.13%   |
| MSI                 | 150       | 6.1%    |
| Toshiba             | 103       | 4.19%   |
| Apple               | 59        | 2.4%    |
| Sony                | 36        | 1.46%   |
| Packard Bell        | 34        | 1.38%   |
| HUAWEI              | 33        | 1.34%   |
| Unknown             | 28        | 1.14%   |
| Samsung Electronics | 25        | 1.02%   |
| Notebook            | 25        | 1.02%   |
| Chuwi               | 25        | 1.02%   |
| SLIMBOOK            | 24        | 0.98%   |
| LG Electronics      | 20        | 0.81%   |
| Valve               | 14        | 0.57%   |
| Medion              | 13        | 0.53%   |
| Fujitsu             | 13        | 0.53%   |
| Timi                | 12        | 0.49%   |
| Fujitsu Siemens     | 11        | 0.45%   |
| eMachines           | 9         | 0.37%   |
| Teclast             | 7         | 0.28%   |
| Clevo               | 7         | 0.28%   |
| Dynabook            | 6         | 0.24%   |
| Gigabyte Technology | 5         | 0.2%    |
| PC Specialist       | 4         | 0.16%   |
| Intel               | 4         | 0.16%   |
| HONOR               | 4         | 0.16%   |
| IBM                 | 3         | 0.12%   |
| Compal              | 3         | 0.12%   |
| Alienware           | 3         | 0.12%   |
| TUXEDO              | 2         | 0.08%   |
| Thomson             | 2         | 0.08%   |
| TEKNOSERVICE        | 2         | 0.08%   |
| Razer               | 2         | 0.08%   |
| Qilive              | 2         | 0.08%   |
| OEM                 | 2         | 0.08%   |
| Minix               | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 47        | 1.91%   |
| HP Pavilion g6                             | 20        | 0.81%   |
| HP Pavilion dv6                            | 19        | 0.77%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.73%   |
| HP Notebook                                | 17        | 0.69%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.61%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.61%   |
| Valve Jupiter                              | 14        | 0.57%   |
| HP G62                                     | 11        | 0.45%   |
| HP Laptop 15-da0xxx                        | 10        | 0.41%   |
| Dell XPS 13 7390                           | 10        | 0.41%   |
| HP Pavilion 15                             | 9         | 0.37%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.37%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.33%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.33%   |
| ASUS X555LAB                               | 8         | 0.33%   |
| ASUS X540NA                                | 8         | 0.33%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.33%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.28%   |
| Lenovo G50-70 20351                        | 7         | 0.28%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.28%   |
| HP Pavilion dv7                            | 7         | 0.28%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.28%   |
| HP Laptop 15-bw0xx                         | 7         | 0.28%   |
| ASUS X550VX                                | 7         | 0.28%   |
| Acer Aspire 5750G                          | 7         | 0.28%   |
| Acer Aspire 5738                           | 7         | 0.28%   |
| Lenovo Y520-15IKBN 80WK                    | 6         | 0.24%   |
| Lenovo Legion 5 15ACH6H 82JU               | 6         | 0.24%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 6         | 0.24%   |
| HUAWEI NBLK-WAX9X                          | 6         | 0.24%   |
| HUAWEI BOHK-WAX9X                          | 6         | 0.24%   |
| HP Pavilion Notebook 15-bc5xxx             | 6         | 0.24%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 6         | 0.24%   |
| HP OMEN by Laptop                          | 6         | 0.24%   |
| HP Laptop 15-bs0xx                         | 6         | 0.24%   |
| HP 250 G7 Notebook PC                      | 6         | 0.24%   |
| HP 250 G6 Notebook PC                      | 6         | 0.24%   |
| Dell XPS 13 9370                           | 6         | 0.24%   |
| SLIMBOOK PROX15-AMD                        | 5         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 182       | 7.4%    |
| Lenovo ThinkPad       | 160       | 6.5%    |
| Lenovo IdeaPad        | 125       | 5.08%   |
| HP Pavilion           | 118       | 4.79%   |
| Dell Latitude         | 83        | 3.37%   |
| Toshiba Satellite     | 80        | 3.25%   |
| ASUS VivoBook         | 68        | 2.76%   |
| HP Laptop             | 67        | 2.72%   |
| HP EliteBook          | 55        | 2.23%   |
| Dell XPS              | 49        | 1.99%   |
| Unknown               | 47        | 1.91%   |
| HP ProBook            | 38        | 1.54%   |
| HP Compaq             | 37        | 1.5%    |
| Dell Inspiron         | 32        | 1.3%    |
| ASUS ZenBook          | 32        | 1.3%    |
| Packard Bell EasyNote | 31        | 1.26%   |
| HP 250                | 30        | 1.22%   |
| MSI Prestige          | 24        | 0.98%   |
| ASUS ROG              | 24        | 0.98%   |
| Lenovo Legion         | 21        | 0.85%   |
| MSI Modern            | 19        | 0.77%   |
| HP OMEN               | 17        | 0.69%   |
| HP Notebook           | 17        | 0.69%   |
| Acer Extensa          | 17        | 0.69%   |
| Lenovo ThinkBook      | 16        | 0.65%   |
| Acer TravelMate       | 16        | 0.65%   |
| ASUS TUF              | 15        | 0.61%   |
| Valve Jupiter         | 14        | 0.57%   |
| HP ENVY               | 14        | 0.57%   |
| ASUS ASUS             | 14        | 0.57%   |
| Lenovo Yoga           | 12        | 0.49%   |
| Fujitsu LIFEBOOK      | 12        | 0.49%   |
| Dell Vostro           | 12        | 0.49%   |
| HP G62                | 11        | 0.45%   |
| Toshiba PORTEGE       | 10        | 0.41%   |
| Toshiba TECRA         | 8         | 0.33%   |
| HP ZBook              | 8         | 0.33%   |
| Chuwi GemiBook        | 8         | 0.33%   |
| ASUS X555LAB          | 8         | 0.33%   |
| ASUS X540NA           | 8         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 258       | 10.48%  |
| 2019    | 253       | 10.28%  |
| 2020    | 232       | 9.43%   |
| 2021    | 176       | 7.15%   |
| 2014    | 169       | 6.87%   |
| 2015    | 165       | 6.7%    |
| 2011    | 154       | 6.26%   |
| 2017    | 151       | 6.14%   |
| 2010    | 134       | 5.44%   |
| 2013    | 126       | 5.12%   |
| 2008    | 126       | 5.12%   |
| 2012    | 120       | 4.88%   |
| 2016    | 109       | 4.43%   |
| 2009    | 102       | 4.14%   |
| 2007    | 79        | 3.21%   |
| 2022    | 56        | 2.28%   |
| 2006    | 28        | 1.14%   |
| 2005    | 10        | 0.41%   |
| 2004    | 5         | 0.2%    |
| 2003    | 3         | 0.12%   |
| Unknown | 3         | 0.12%   |
| 2002    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2461      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2254      | 90.96%  |
| Enabled  | 224       | 9.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2456      | 99.8%   |
| Yes  | 5         | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 647       | 26.06%  |
| 3.01-4.0    | 562       | 22.63%  |
| 8.01-16.0   | 451       | 18.16%  |
| 16.01-24.0  | 439       | 17.68%  |
| 32.01-64.0  | 141       | 5.68%   |
| 1.01-2.0    | 128       | 5.16%   |
| 2.01-3.0    | 47        | 1.89%   |
| 0.51-1.0    | 42        | 1.69%   |
| 64.01-256.0 | 13        | 0.52%   |
| 24.01-32.0  | 11        | 0.44%   |
| 0.01-0.5    | 2         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1054      | 38.99%  |
| 2.01-3.0   | 705       | 26.08%  |
| 4.01-8.0   | 321       | 11.88%  |
| 3.01-4.0   | 288       | 10.65%  |
| 0.51-1.0   | 218       | 8.07%   |
| 8.01-16.0  | 87        | 3.22%   |
| 0.01-0.5   | 24        | 0.89%   |
| 24.01-32.0 | 3         | 0.11%   |
| 16.01-24.0 | 3         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1893      | 75.81%  |
| 2      | 521       | 20.87%  |
| 3      | 54        | 2.16%   |
| 0      | 23        | 0.92%   |
| 4      | 4         | 0.16%   |
| 5      | 2         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1571      | 63.55%  |
| Yes       | 901       | 36.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1988      | 80.42%  |
| No        | 484       | 19.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2411      | 97.97%  |
| No        | 50        | 2.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1814      | 73.09%  |
| No        | 668       | 26.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 2461      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 414       | 15.49%  |
| Barcelona                  | 282       | 10.55%  |
| Seville                    | 96        | 3.59%   |
| Valencia                   | 83        | 3.11%   |
| Zaragoza                   | 41        | 1.53%   |
| Granada                    | 39        | 1.46%   |
| Málaga                    | 34        | 1.27%   |
| Alcobendas                 | 34        | 1.27%   |
| Palma                      | 30        | 1.12%   |
| Sabadell                   | 27        | 1.01%   |
| Vigo                       | 24        | 0.9%    |
| Valladolid                 | 24        | 0.9%    |
| Córdoba                   | 22        | 0.82%   |
| Bilbao                     | 21        | 0.79%   |
| Las Palmas de Gran Canaria | 20        | 0.75%   |
| Alcalá de Henares         | 20        | 0.75%   |
| Pamplona                   | 19        | 0.71%   |
| Alicante                   | 19        | 0.71%   |
| Santiago de Compostela     | 18        | 0.67%   |
| Donostia / San Sebastian   | 18        | 0.67%   |
| A Coruña                  | 17        | 0.64%   |
| Murcia                     | 16        | 0.6%    |
| Mostoles                   | 16        | 0.6%    |
| León                      | 16        | 0.6%    |
| Oviedo                     | 15        | 0.56%   |
| Gijón                     | 15        | 0.56%   |
| Burgos                     | 14        | 0.52%   |
| Barakaldo                  | 13        | 0.49%   |
| Vitoria-Gasteiz            | 12        | 0.45%   |
| Reus                       | 12        | 0.45%   |
| Getxo                      | 12        | 0.45%   |
| Salamanca                  | 11        | 0.41%   |
| Albacete                   | 11        | 0.41%   |
| Pontevedra                 | 10        | 0.37%   |
| Ourense                    | 10        | 0.37%   |
| Dos Hermanas               | 10        | 0.37%   |
| Cartagena                  | 10        | 0.37%   |
| Almería                   | 10        | 0.37%   |
| Alcorcón                  | 10        | 0.37%   |
| Tres Cantos                | 9         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 415       | 502    | 14.03%  |
| WDC                         | 335       | 414    | 11.33%  |
| Seagate                     | 313       | 372    | 10.58%  |
| Kingston                    | 301       | 377    | 10.18%  |
| Toshiba                     | 260       | 320    | 8.79%   |
| SanDisk                     | 193       | 245    | 6.52%   |
| Unknown                     | 143       | 186    | 4.83%   |
| SK hynix                    | 134       | 161    | 4.53%   |
| Hitachi                     | 111       | 132    | 3.75%   |
| Intel                       | 96        | 129    | 3.25%   |
| HGST                        | 94        | 117    | 3.18%   |
| Crucial                     | 87        | 105    | 2.94%   |
| Micron Technology           | 85        | 100    | 2.87%   |
| Fujitsu                     | 32        | 36     | 1.08%   |
| KIOXIA                      | 29        | 34     | 0.98%   |
| Phison                      | 25        | 27     | 0.85%   |
| China                       | 25        | 36     | 0.85%   |
| Apple                       | 21        | 28     | 0.71%   |
| LITEON                      | 16        | 17     | 0.54%   |
| Netac                       | 14        | 21     | 0.47%   |
| KingSpec                    | 14        | 18     | 0.47%   |
| Micron/Crucial Technology   | 12        | 14     | 0.41%   |
| A-DATA Technology           | 11        | 13     | 0.37%   |
| JMicron Technology          | 9         | 9      | 0.3%    |
| Transcend                   | 8         | 14     | 0.27%   |
| PNY                         | 8         | 12     | 0.27%   |
| OCZ                         | 8         | 9      | 0.27%   |
| Kingston Technology Company | 8         | 9      | 0.27%   |
| FORESEE                     | 7         | 8      | 0.24%   |
| USB30                       | 6         | 7      | 0.2%    |
| Unknown                     | 6         | 6      | 0.2%    |
| Teclast                     | 5         | 5      | 0.17%   |
| Patriot                     | 5         | 6      | 0.17%   |
| LITEONIT                    | 5         | 6      | 0.17%   |
| KingDian                    | 5         | 5      | 0.17%   |
| Silicon Motion              | 4         | 4      | 0.14%   |
| Phison Electronics          | 4         | 4      | 0.14%   |
| Gigabyte Technology         | 4         | 5      | 0.14%   |
| Emtec                       | 4         | 4      | 0.14%   |
| Corsair                     | 4         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 110       | 3.61%   |
| Seagate ST500LT012-1DG142 500GB        | 39        | 1.28%   |
| Kingston SA400S37480G 480GB SSD        | 39        | 1.28%   |
| Unknown MMC Card  32GB                 | 34        | 1.11%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 1.11%   |
| HGST HTS721010A9E630 1TB               | 32        | 1.05%   |
| Samsung NVMe SSD Drive 512GB           | 31        | 1.02%   |
| Unknown MMC Card  64GB                 | 29        | 0.95%   |
| Toshiba MQ01ABF050 500GB               | 29        | 0.95%   |
| Toshiba MQ01ABD100 1TB                 | 29        | 0.95%   |
| Seagate ST9500325AS 500GB              | 29        | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 28        | 0.92%   |
| Toshiba MQ04ABF100 1TB                 | 27        | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 27        | 0.89%   |
| SanDisk NVMe SSD Drive 512GB           | 26        | 0.85%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 22        | 0.72%   |
| Intel NVMe SSD Drive 512GB             | 21        | 0.69%   |
| Samsung SSD 850 EVO 250GB              | 20        | 0.66%   |
| Toshiba MQ01ABD050 500GB               | 19        | 0.62%   |
| Samsung SSD 860 EVO 500GB              | 19        | 0.62%   |
| Kingston RBUSC180DS37256GJ 256GB SSD   | 19        | 0.62%   |
| Kingston SUV400S37240G 240GB SSD       | 18        | 0.59%   |
| HGST HTS545050A7E680 500GB             | 18        | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB               | 17        | 0.56%   |
| SanDisk SSD PLUS 480GB                 | 17        | 0.56%   |
| SanDisk NVMe SSD Drive 256GB           | 17        | 0.56%   |
| Kingston SA400S37120G 120GB SSD        | 17        | 0.56%   |
| HGST HTS541010A9E680 1TB               | 17        | 0.56%   |
| Unknown MMC Card  128GB                | 15        | 0.49%   |
| Crucial CT500MX500SSD1 500GB           | 15        | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB         | 14        | 0.46%   |
| Samsung SSD 850 EVO 500GB              | 13        | 0.43%   |
| Micron NVMe SSD Drive 512GB            | 13        | 0.43%   |
| SK hynix NVMe SSD Drive 256GB          | 11        | 0.36%   |
| Seagate Expansion 4TB                  | 11        | 0.36%   |
| SanDisk SSD PLUS 1000GB                | 11        | 0.36%   |
| SanDisk NVMe SSD Drive 1024GB          | 11        | 0.36%   |
| Samsung NVMe SSD Drive 1024GB          | 11        | 0.36%   |
| Seagate ST9500420AS 500GB              | 10        | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 10        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 309       | 368    | 31.47%  |
| WDC                 | 215       | 259    | 21.89%  |
| Toshiba             | 177       | 207    | 18.02%  |
| Hitachi             | 111       | 132    | 11.3%   |
| HGST                | 94        | 117    | 9.57%   |
| Fujitsu             | 32        | 36     | 3.26%   |
| Samsung Electronics | 23        | 24     | 2.34%   |
| Unknown             | 5         | 8      | 0.51%   |
| USB3.0              | 3         | 3      | 0.31%   |
| ASMT                | 3         | 3      | 0.31%   |
| Apple               | 3         | 3      | 0.31%   |
| USB                 | 2         | 2      | 0.2%    |
| PHD 3.0             | 1         | 1      | 0.1%    |
| OEM                 | 1         | 1      | 0.1%    |
| Maxone              | 1         | 1      | 0.1%    |
| LaCie               | 1         | 1      | 0.1%    |
| IBM                 | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 263       | 329    | 27.03%  |
| Samsung Electronics | 165       | 197    | 16.96%  |
| SanDisk             | 111       | 134    | 11.41%  |
| Crucial             | 78        | 94     | 8.02%   |
| WDC                 | 39        | 50     | 4.01%   |
| Toshiba             | 38        | 48     | 3.91%   |
| SK hynix            | 31        | 34     | 3.19%   |
| Micron Technology   | 31        | 38     | 3.19%   |
| China               | 25        | 36     | 2.57%   |
| Intel               | 19        | 32     | 1.95%   |
| LITEON              | 15        | 15     | 1.54%   |
| Netac               | 14        | 21     | 1.44%   |
| KingSpec            | 14        | 18     | 1.44%   |
| Apple               | 12        | 14     | 1.23%   |
| A-DATA Technology   | 9         | 11     | 0.92%   |
| OCZ                 | 8         | 9      | 0.82%   |
| Transcend           | 7         | 13     | 0.72%   |
| FORESEE             | 7         | 8      | 0.72%   |
| USB30               | 6         | 7      | 0.62%   |
| PNY                 | 6         | 10     | 0.62%   |
| Teclast             | 5         | 5      | 0.51%   |
| LITEONIT            | 5         | 6      | 0.51%   |
| JMicron Technology  | 5         | 5      | 0.51%   |
| Patriot             | 4         | 5      | 0.41%   |
| KingDian            | 4         | 4      | 0.41%   |
| Corsair             | 4         | 5      | 0.41%   |
| Unknown             | 3         | 3      | 0.31%   |
| Emtec               | 3         | 3      | 0.31%   |
| Unknown             | 3         | 3      | 0.31%   |
| TCSUNBOW            | 2         | 2      | 0.21%   |
| ShanDianZhe         | 2         | 2      | 0.21%   |
| Plextor             | 2         | 3      | 0.21%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.21%   |
| Dogfish             | 2         | 2      | 0.21%   |
| BAITITON            | 2         | 2      | 0.21%   |
| Yeyian              | 1         | 1      | 0.1%    |
| W800S               | 1         | 2      | 0.1%    |
| Vaseky              | 1         | 1      | 0.1%    |
| Union Memory        | 1         | 1      | 0.1%    |
| SPCC                | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 959       | 1167   | 33.78%  |
| SSD     | 912       | 1210   | 32.12%  |
| NVMe    | 794       | 1034   | 27.97%  |
| MMC     | 141       | 183    | 4.97%   |
| Unknown | 33        | 38     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1667      | 2313   | 61.92%  |
| NVMe | 793       | 1031   | 29.46%  |
| MMC  | 141       | 183    | 5.24%   |
| SAS  | 91        | 105    | 3.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1346      | 1800   | 73.79%  |
| 0.51-1.0   | 429       | 517    | 23.52%  |
| 1.01-2.0   | 30        | 38     | 1.64%   |
| 3.01-4.0   | 16        | 18     | 0.88%   |
| 4.01-10.0  | 2         | 3      | 0.11%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 805       | 31.46%  |
| 251-500        | 731       | 28.57%  |
| 501-1000       | 307       | 12%     |
| 51-100         | 193       | 7.54%   |
| 1-20           | 185       | 7.23%   |
| 21-50          | 125       | 4.88%   |
| 1001-2000      | 104       | 4.06%   |
| Unknown        | 53        | 2.07%   |
| 2001-3000      | 31        | 1.21%   |
| More than 3000 | 25        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1126      | 42.01%  |
| 21-50          | 502       | 18.73%  |
| 101-250        | 371       | 13.84%  |
| 51-100         | 298       | 11.12%  |
| 251-500        | 193       | 7.2%    |
| 501-1000       | 95        | 3.54%   |
| Unknown        | 53        | 1.98%   |
| 1001-2000      | 26        | 0.97%   |
| 2001-3000      | 8         | 0.3%    |
| More than 3000 | 6         | 0.22%   |
| 0              | 2         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                | 6         | 7      | 4.26%   |
| Seagate ST500LT012-1DG142 500GB          | 5         | 5      | 3.55%   |
| SanDisk SSD PLUS 480GB                   | 5         | 6      | 3.55%   |
| HGST HTS545050A7E680 500GB               | 5         | 7      | 3.55%   |
| Seagate ST9500420AS 500GB                | 4         | 4      | 2.84%   |
| Seagate ST9250827AS 250GB                | 4         | 4      | 2.84%   |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 2.13%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 2.13%   |
| HGST HTS721010A9E630 1TB                 | 3         | 3      | 2.13%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.13%   |
| WDC WD5000BPVT-60HXZT3 500GB             | 2         | 2      | 1.42%   |
| Toshiba Q300. 240GB SSD                  | 2         | 2      | 1.42%   |
| Toshiba MK5076GSX 500GB                  | 2         | 2      | 1.42%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 1.42%   |
| Seagate ST320LT012-9WS14C 320GB          | 2         | 2      | 1.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 1.42%   |
| Intel SSDSC2BF180A5H SED 180GB           | 2         | 2      | 1.42%   |
| HGST HTS545050A7E380 500GB               | 2         | 2      | 1.42%   |
| Fujitsu MHZ2250BH G2 250GB               | 2         | 2      | 1.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.71%   |
| WDC WD7500BPVT-60HXZT1 752GB             | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-00A0RT0 320GB             | 1         | 1      | 0.71%   |
| WDC WD3200BEKT-60F3T1 320GB              | 1         | 2      | 0.71%   |
| WDC WD2500BEVS-60UST0 250GB              | 1         | 1      | 0.71%   |
| WDC WD2500BEVS-22UST0 250GB              | 1         | 1      | 0.71%   |
| WDC WD1600BEVT-60ZCT0 160GB              | 1         | 1      | 0.71%   |
| WDC WD1600BEVS-60RST0 160GB              | 1         | 1      | 0.71%   |
| WDC WD1600BEVS-22RST0 160GB              | 1         | 1      | 0.71%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.71%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 0.71%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.71%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.71%   |
| Toshiba THNSNJ256G8NY 256GB SSD          | 1         | 1      | 0.71%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 2      | 0.71%   |
| Toshiba MK8052GSX 80GB                   | 1         | 1      | 0.71%   |
| Toshiba MK5065GSXN 500GB                 | 1         | 1      | 0.71%   |
| Toshiba MK3256GSY 320GB                  | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 42     | 28.37%  |
| Hitachi             | 18        | 19     | 12.77%  |
| Toshiba             | 17        | 18     | 12.06%  |
| HGST                | 15        | 18     | 10.64%  |
| WDC                 | 14        | 15     | 9.93%   |
| Samsung Electronics | 8         | 8      | 5.67%   |
| SanDisk             | 6         | 7      | 4.26%   |
| Intel               | 6         | 6      | 4.26%   |
| Kingston            | 4         | 5      | 2.84%   |
| Fujitsu             | 4         | 4      | 2.84%   |
| Micron Technology   | 3         | 3      | 2.13%   |
| SK hynix            | 2         | 2      | 1.42%   |
| Crucial             | 2         | 3      | 1.42%   |
| OCZ                 | 1         | 1      | 0.71%   |
| IBM                 | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 42     | 37.38%  |
| Hitachi             | 18        | 19     | 16.82%  |
| HGST                | 15        | 18     | 14.02%  |
| WDC                 | 13        | 14     | 12.15%  |
| Toshiba             | 12        | 13     | 11.21%  |
| Samsung Electronics | 4         | 4      | 3.74%   |
| Fujitsu             | 4         | 4      | 3.74%   |
| IBM                 | 1         | 1      | 0.93%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 105       | 115    | 76.09%  |
| SSD  | 30        | 34     | 21.74%  |
| NVMe | 3         | 3      | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1548      | 2330   | 59.79%  |
| Works    | 903       | 1149   | 34.88%  |
| Malfunc  | 137       | 152    | 5.29%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1732      | 61.18%  |
| AMD                              | 278       | 9.82%   |
| Samsung Electronics              | 253       | 8.94%   |
| SanDisk                          | 158       | 5.58%   |
| SK hynix                         | 97        | 3.43%   |
| Micron Technology                | 54        | 1.91%   |
| Toshiba America Info Systems     | 46        | 1.62%   |
| Kingston Technology Company      | 45        | 1.59%   |
| Phison Electronics               | 35        | 1.24%   |
| KIOXIA                           | 34        | 1.2%    |
| Nvidia                           | 26        | 0.92%   |
| Micron/Crucial Technology        | 18        | 0.64%   |
| Silicon Integrated Systems [SiS] | 13        | 0.46%   |
| Silicon Motion                   | 7         | 0.25%   |
| VIA Technologies                 | 5         | 0.18%   |
| JMicron Technology               | 5         | 0.18%   |
| Apple                            | 5         | 0.18%   |
| Union Memory (Shenzhen)          | 4         | 0.14%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| O2 Micro                         | 2         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.07%   |
| Lite-On Technology               | 2         | 0.07%   |
| Lenovo                           | 2         | 0.07%   |
| ADATA Technology                 | 2         | 0.07%   |
| Silicon Image                    | 1         | 0.04%   |
| Marvell Technology Group         | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 236       | 7.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 196       | 6.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 127       | 4.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 123       | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 119       | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 119       | 3.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 115       | 3.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 102       | 3.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 87        | 2.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 80        | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 74        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 70        | 2.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 67        | 2.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 62        | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 62        | 2.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 62        | 2.02%   |
| Samsung NVMe SSD Controller 980                                                | 60        | 1.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 60        | 1.95%   |
| Micron Non-Volatile memory controller                                          | 54        | 1.76%   |
| Intel SSD 660P Series                                                          | 49        | 1.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 46        | 1.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 37        | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 35        | 1.14%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 31        | 1.01%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 31        | 1.01%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 31        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 29        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 28        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 28        | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                            | 26        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 26        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 26        | 0.85%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 24        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 23        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 23        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1745      | 58.81%  |
| NVMe | 802       | 27.03%  |
| IDE  | 227       | 7.65%   |
| RAID | 193       | 6.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2045      | 83.1%   |
| AMD          | 415       | 16.86%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 54        | 2.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 52        | 2.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 46        | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 1.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 1.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 35        | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 34        | 1.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 33        | 1.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 32        | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 30        | 1.22%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 30        | 1.22%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 1.06%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 23        | 0.93%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 20        | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.81%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.77%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.73%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 17        | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 17        | 0.69%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 17        | 0.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 17        | 0.69%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 16        | 0.65%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 15        | 0.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 15        | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 15        | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 15        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 14        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.57%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 14        | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 590       | 23.96%  |
| Intel Core i5           | 502       | 20.39%  |
| Other                   | 203       | 8.25%   |
| Intel Celeron           | 184       | 7.47%   |
| Intel Core i3           | 182       | 7.39%   |
| Intel Core 2 Duo        | 152       | 6.17%   |
| AMD Ryzen 7             | 115       | 4.67%   |
| Intel Atom              | 90        | 3.66%   |
| AMD Ryzen 5             | 80        | 3.25%   |
| Intel Pentium           | 32        | 1.3%    |
| Intel Pentium Dual-Core | 31        | 1.26%   |
| Intel Pentium Dual      | 29        | 1.18%   |
| AMD A6                  | 26        | 1.06%   |
| AMD A4                  | 26        | 1.06%   |
| Intel Genuine           | 22        | 0.89%   |
| Intel Core 2            | 22        | 0.89%   |
| AMD E1                  | 20        | 0.81%   |
| AMD A8                  | 15        | 0.61%   |
| AMD Ryzen 7 PRO         | 10        | 0.41%   |
| AMD E                   | 10        | 0.41%   |
| Intel Pentium M         | 9         | 0.37%   |
| AMD Ryzen 3             | 9         | 0.37%   |
| AMD Athlon              | 9         | 0.37%   |
| Intel Core i9           | 8         | 0.32%   |
| AMD A10                 | 8         | 0.32%   |
| Intel Celeron M         | 7         | 0.28%   |
| AMD Ryzen 9             | 7         | 0.28%   |
| Intel Core m3           | 5         | 0.2%    |
| Intel Pentium 4         | 4         | 0.16%   |
| AMD Turion II Dual-Core | 4         | 0.16%   |
| AMD Turion 64 X2 Mobile | 4         | 0.16%   |
| AMD FX                  | 4         | 0.16%   |
| AMD Athlon II           | 4         | 0.16%   |
| AMD Turion 64 Mobile    | 3         | 0.12%   |
| AMD A12                 | 3         | 0.12%   |
| Intel Xeon              | 2         | 0.08%   |
| Intel Pentium Silver    | 2         | 0.08%   |
| Intel Core m5           | 2         | 0.08%   |
| Intel Core Duo          | 2         | 0.08%   |
| AMD Ryzen 5 PRO         | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1249      | 50.71%  |
| 4       | 777       | 31.55%  |
| 6       | 160       | 6.5%    |
| 8       | 141       | 5.72%   |
| 1       | 106       | 4.3%    |
| 14      | 14        | 0.57%   |
| 10      | 7         | 0.28%   |
| 12      | 5         | 0.2%    |
| Unknown | 4         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2460      | 99.96%  |
| 2      | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1730      | 70.24%  |
| 1       | 729       | 29.6%   |
| Unknown | 4         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2351      | 94.99%  |
| 32-bit         | 56        | 2.26%   |
| Unknown        | 54        | 2.18%   |
| 64-bit         | 14        | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 452       | 17.84%  |
| 0x206a7    | 130       | 5.13%   |
| 0x306a9    | 106       | 4.18%   |
| 0x806c1    | 93        | 3.67%   |
| 0x906ea    | 90        | 3.55%   |
| 0x40651    | 90        | 3.55%   |
| 0x806ea    | 89        | 3.51%   |
| 0x806ec    | 82        | 3.24%   |
| 0x6fd      | 73        | 2.88%   |
| 0x406e3    | 73        | 2.88%   |
| 0x20655    | 73        | 2.88%   |
| 0x1067a    | 72        | 2.84%   |
| 0x806e9    | 69        | 2.72%   |
| 0x306d4    | 65        | 2.57%   |
| 0x306c3    | 59        | 2.33%   |
| 0x30678    | 46        | 1.82%   |
| 0x706e5    | 37        | 1.46%   |
| 0x10676    | 37        | 1.46%   |
| 0x08108109 | 37        | 1.46%   |
| 0xa0652    | 35        | 1.38%   |
| 0x706a1    | 34        | 1.34%   |
| 0x0a50000c | 33        | 1.3%    |
| 0x06006705 | 32        | 1.26%   |
| 0x506e3    | 30        | 1.18%   |
| 0x20652    | 30        | 1.18%   |
| 0x08108102 | 29        | 1.14%   |
| 0x906e9    | 24        | 0.95%   |
| 0x806eb    | 24        | 0.95%   |
| 0x08600106 | 24        | 0.95%   |
| 0x506c9    | 23        | 0.91%   |
| 0x406c4    | 23        | 0.91%   |
| 0x106ca    | 22        | 0.87%   |
| 0x406c3    | 21        | 0.83%   |
| 0x706a8    | 19        | 0.75%   |
| 0x106c2    | 19        | 0.75%   |
| 0x08600103 | 19        | 0.75%   |
| 0x906a3    | 17        | 0.67%   |
| 0x6f6      | 17        | 0.67%   |
| 0x806d1    | 16        | 0.63%   |
| 0x08608103 | 15        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 455       | 18.49%  |
| Haswell          | 193       | 7.84%   |
| SandyBridge      | 151       | 6.14%   |
| Penryn           | 136       | 5.53%   |
| Core             | 131       | 5.32%   |
| Skylake          | 124       | 5.04%   |
| TigerLake        | 120       | 4.88%   |
| IvyBridge        | 116       | 4.71%   |
| Westmere         | 113       | 4.59%   |
| Silvermont       | 106       | 4.31%   |
| Broadwell        | 81        | 3.29%   |
| Zen+             | 75        | 3.05%   |
| Zen 2            | 68        | 2.76%   |
| Goldmont plus    | 62        | 2.52%   |
| Excavator        | 56        | 2.28%   |
| Bonnell          | 53        | 2.15%   |
| Unknown          | 53        | 2.15%   |
| IceLake          | 51        | 2.07%   |
| CometLake        | 50        | 2.03%   |
| Zen 3            | 45        | 1.83%   |
| Goldmont         | 28        | 1.14%   |
| P6               | 27        | 1.1%    |
| Puma             | 24        | 0.98%   |
| Zen              | 23        | 0.93%   |
| Jaguar           | 23        | 0.93%   |
| Alderlake Hybrid | 18        | 0.73%   |
| Bobcat           | 17        | 0.69%   |
| K8 Hammer        | 14        | 0.57%   |
| K10              | 14        | 0.57%   |
| Nehalem          | 8         | 0.33%   |
| Piledriver       | 7         | 0.28%   |
| NetBurst         | 5         | 0.2%    |
| Tremont          | 4         | 0.16%   |
| Steamroller      | 4         | 0.16%   |
| K8 & K10 hybrid  | 3         | 0.12%   |
| K10 Llano        | 3         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1820      | 57.85%  |
| Nvidia                           | 729       | 23.17%  |
| AMD                              | 584       | 18.56%  |
| Silicon Integrated Systems [SiS] | 8         | 0.25%   |
| VIA Technologies                 | 5         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 136       | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 114       | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 114       | 3.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 111       | 3.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 104       | 3.19%   |
| Intel UHD Graphics 620                                                                   | 98        | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 85        | 2.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 82        | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 79        | 2.42%   |
| Intel HD Graphics 620                                                                    | 77        | 2.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 71        | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 70        | 2.14%   |
| Intel HD Graphics 5500                                                                   | 69        | 2.11%   |
| AMD Renoir                                                                               | 65        | 1.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 60        | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 58        | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 55        | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 52        | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 48        | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 45        | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 45        | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 42        | 1.29%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 41        | 1.26%   |
| Intel HD Graphics 530                                                                    | 39        | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 38        | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 36        | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 30        | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 29        | 0.89%   |
| Intel HD Graphics 630                                                                    | 28        | 0.86%   |
| Intel HD Graphics 500                                                                    | 26        | 0.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 24        | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 23        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 23        | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 23        | 0.7%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 23        | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 21        | 0.64%   |
| Nvidia TU117M                                                                            | 20        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1203      | 48.82%  |
| Intel + Nvidia | 531       | 21.55%  |
| 1 x AMD        | 397       | 16.11%  |
| 1 x Nvidia     | 127       | 5.15%   |
| Intel + AMD    | 84        | 3.41%   |
| AMD + Nvidia   | 68        | 2.76%   |
| 2 x AMD        | 34        | 1.38%   |
| 1 x SiS        | 8         | 0.32%   |
| 1 x VIA        | 5         | 0.2%    |
| 2 x Nvidia     | 4         | 0.16%   |
| Other          | 2         | 0.08%   |
| 2 x Intel      | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2072      | 83.25%  |
| Proprietary | 340       | 13.66%  |
| Unknown     | 77        | 3.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1516      | 60.11%  |
| 0.01-0.5   | 318       | 12.61%  |
| 1.01-2.0   | 317       | 12.57%  |
| 3.01-4.0   | 173       | 6.86%   |
| 0.51-1.0   | 139       | 5.51%   |
| 5.01-6.0   | 35        | 1.39%   |
| 7.01-8.0   | 20        | 0.79%   |
| 2.01-3.0   | 3         | 0.12%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 493       | 17.81%  |
| Chimei Innolux          | 440       | 15.9%   |
| LG Display              | 389       | 14.05%  |
| BOE                     | 310       | 11.2%   |
| Samsung Electronics     | 268       | 9.68%   |
| Chi Mei Optoelectronics | 82        | 2.96%   |
| Sharp                   | 76        | 2.75%   |
| Goldstar                | 72        | 2.6%    |
| Dell                    | 62        | 2.24%   |
| Apple                   | 58        | 2.1%    |
| PANDA                   | 55        | 1.99%   |
| Hewlett-Packard         | 55        | 1.99%   |
| Lenovo                  | 40        | 1.45%   |
| LG Philips              | 39        | 1.41%   |
| BenQ                    | 39        | 1.41%   |
| Acer                    | 25        | 0.9%    |
| Philips                 | 23        | 0.83%   |
| Ancor Communications    | 21        | 0.76%   |
| AOC                     | 20        | 0.72%   |
| HannStar                | 19        | 0.69%   |
| Sony                    | 16        | 0.58%   |
| InfoVision              | 14        | 0.51%   |
| ASUSTek Computer        | 10        | 0.36%   |
| CPT                     | 9         | 0.33%   |
| Quanta Display          | 8         | 0.29%   |
| CSO                     | 7         | 0.25%   |
| Analogix                | 7         | 0.25%   |
| ViewSonic               | 6         | 0.22%   |
| Unknown                 | 6         | 0.22%   |
| Seiko/Epson             | 5         | 0.18%   |
| Panasonic               | 5         | 0.18%   |
| MSI                     | 5         | 0.18%   |
| ANX                     | 5         | 0.18%   |
| Valve                   | 4         | 0.14%   |
| Toshiba                 | 3         | 0.11%   |
| TMX                     | 3         | 0.11%   |
| Mi                      | 3         | 0.11%   |
| Hitachi                 | 3         | 0.11%   |
| BOE Technology Group    | 3         | 0.11%   |
| AGO                     | 3         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 64        | 2.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 1.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 29        | 1.04%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 28        | 1%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 25        | 0.89%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.75%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 20        | 0.71%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.57%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.54%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.54%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 13        | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 13        | 0.46%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.43%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 12        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.43%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.39%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 11        | 0.39%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 10        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.36%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 9         | 0.32%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 9         | 0.32%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 9         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.32%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 9         | 0.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 8         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1038      | 40.33%  |
| 1366x768 (WXGA)    | 870       | 33.8%   |
| 1280x800 (WXGA)    | 150       | 5.83%   |
| 1600x900 (HD+)     | 70        | 2.72%   |
| 3840x2160 (4K)     | 68        | 2.64%   |
| 1440x900 (WXGA+)   | 58        | 2.25%   |
| 2560x1440 (QHD)    | 46        | 1.79%   |
| 1024x600           | 39        | 1.52%   |
| 1920x1200 (WUXGA)  | 27        | 1.05%   |
| 1280x1024 (SXGA)   | 26        | 1.01%   |
| 1680x1050 (WSXGA+) | 23        | 0.89%   |
| 2560x1600          | 21        | 0.82%   |
| 2160x1440          | 17        | 0.66%   |
| 800x1280           | 14        | 0.54%   |
| 2880x1800          | 13        | 0.51%   |
| 2560x1080          | 13        | 0.51%   |
| 3440x1440          | 12        | 0.47%   |
| 3200x1800 (QHD+)   | 7         | 0.27%   |
| 1360x768           | 7         | 0.27%   |
| 1024x768 (XGA)     | 7         | 0.27%   |
| Unknown            | 5         | 0.19%   |
| 3840x2400          | 4         | 0.16%   |
| 2288x1287          | 3         | 0.12%   |
| 1920x540           | 3         | 0.12%   |
| 1600x1200          | 3         | 0.12%   |
| 1400x1050          | 3         | 0.12%   |
| 1280x768           | 3         | 0.12%   |
| 3840x1080          | 2         | 0.08%   |
| 3456x2160          | 2         | 0.08%   |
| 3200x2000          | 2         | 0.08%   |
| 3072x1920          | 2         | 0.08%   |
| 1920x1280          | 2         | 0.08%   |
| 5760x1080          | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3200x1080          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2736x1824          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1370      | 49.55%  |
| 13      | 318       | 11.5%   |
| 14      | 222       | 8.03%   |
| 17      | 154       | 5.57%   |
| 24      | 92        | 3.33%   |
| 27      | 79        | 2.86%   |
| 21      | 73        | 2.64%   |
| 23      | 70        | 2.53%   |
| 12      | 55        | 1.99%   |
| Unknown | 47        | 1.7%    |
| 11      | 43        | 1.56%   |
| 10      | 43        | 1.56%   |
| 16      | 32        | 1.16%   |
| 34      | 26        | 0.94%   |
| 31      | 23        | 0.83%   |
| 19      | 17        | 0.61%   |
| 18      | 14        | 0.51%   |
| 20      | 13        | 0.47%   |
| 84      | 12        | 0.43%   |
| 72      | 7         | 0.25%   |
| 54      | 6         | 0.22%   |
| 25      | 6         | 0.22%   |
| 22      | 6         | 0.22%   |
| 40      | 5         | 0.18%   |
| 7       | 4         | 0.14%   |
| 52      | 3         | 0.11%   |
| 46      | 3         | 0.11%   |
| 26      | 3         | 0.11%   |
| 8       | 3         | 0.11%   |
| 142     | 2         | 0.07%   |
| 32      | 2         | 0.07%   |
| 65      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 38      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1721      | 62.72%  |
| 201-300        | 332       | 12.1%   |
| 501-600        | 234       | 8.53%   |
| 351-400        | 186       | 6.78%   |
| 401-500        | 113       | 4.12%   |
| Unknown        | 47        | 1.71%   |
| 601-700        | 29        | 1.06%   |
| 701-800        | 28        | 1.02%   |
| 1501-2000      | 19        | 0.69%   |
| 1001-1500      | 16        | 0.58%   |
| 801-900        | 8         | 0.29%   |
| 1-100          | 5         | 0.18%   |
| 101-200        | 3         | 0.11%   |
| More than 2000 | 2         | 0.07%   |
| 901-1000       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1991      | 81.7%   |
| 16/10   | 301       | 12.35%  |
| 3/2     | 30        | 1.23%   |
| Unknown | 28        | 1.15%   |
| 21/9    | 26        | 1.07%   |
| 5/4     | 25        | 1.03%   |
| 4/3     | 15        | 0.62%   |
| 0.62    | 12        | 0.49%   |
| 0.67    | 4         | 0.16%   |
| 1.00    | 2         | 0.08%   |
| 32/9    | 1         | 0.04%   |
| 1.03    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1377      | 49.87%  |
| 81-90          | 381       | 13.8%   |
| 201-250        | 202       | 7.32%   |
| 71-80          | 154       | 5.58%   |
| 121-130        | 107       | 3.88%   |
| 301-350        | 79        | 2.86%   |
| 61-70          | 52        | 1.88%   |
| 351-500        | 50        | 1.81%   |
| 151-200        | 47        | 1.7%    |
| Unknown        | 47        | 1.7%    |
| 51-60          | 43        | 1.56%   |
| 41-50          | 43        | 1.56%   |
| 131-140        | 34        | 1.23%   |
| More than 1000 | 33        | 1.2%    |
| 251-300        | 29        | 1.05%   |
| 141-150        | 27        | 0.98%   |
| 111-120        | 18        | 0.65%   |
| 91-100         | 16        | 0.58%   |
| 501-1000       | 14        | 0.51%   |
| 1-40           | 8         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 969       | 35.82%  |
| 101-120       | 902       | 33.35%  |
| 51-100        | 531       | 19.63%  |
| 161-240       | 167       | 6.17%   |
| More than 240 | 53        | 1.96%   |
| Unknown       | 47        | 1.74%   |
| 1-50          | 36        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1988      | 78.92%  |
| 2     | 392       | 15.56%  |
| 0     | 85        | 3.37%   |
| 3     | 50        | 1.98%   |
| 4     | 4         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1371      | 34.44%  |
| Intel                                  | 1162      | 29.19%  |
| Qualcomm Atheros                       | 648       | 16.28%  |
| Broadcom                               | 298       | 7.49%   |
| Broadcom Limited                       | 70        | 1.76%   |
| Marvell Technology Group               | 61        | 1.53%   |
| Ralink                                 | 42        | 1.06%   |
| TP-Link                                | 40        | 1%      |
| Ralink Technology                      | 34        | 0.85%   |
| MediaTek                               | 31        | 0.78%   |
| Nvidia                                 | 19        | 0.48%   |
| Samsung Electronics                    | 18        | 0.45%   |
| ASIX Electronics                       | 16        | 0.4%    |
| Xiaomi                                 | 15        | 0.38%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.33%   |
| Hewlett-Packard                        | 12        | 0.3%    |
| Dell                                   | 11        | 0.28%   |
| Sierra Wireless                        | 10        | 0.25%   |
| JMicron Technology                     | 10        | 0.25%   |
| Ericsson Business Mobile Networks      | 10        | 0.25%   |
| Qualcomm                               | 9         | 0.23%   |
| Lenovo                                 | 9         | 0.23%   |
| Qualcomm Atheros Communications        | 8         | 0.2%    |
| DisplayLink                            | 8         | 0.2%    |
| D-Link                                 | 5         | 0.13%   |
| VIA Technologies                       | 4         | 0.1%    |
| LSI                                    | 4         | 0.1%    |
| Huawei Technologies                    | 4         | 0.1%    |
| Attansic Technology                    | 4         | 0.1%    |
| ASUSTek Computer                       | 4         | 0.1%    |
| Toshiba                                | 3         | 0.08%   |
| Edimax Technology                      | 3         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Fibocom                                | 2         | 0.05%   |
| Arduino SA                             | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Sitecom Europe                         | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 793       | 16.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 251       | 5.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 107       | 2.28%   |
| Intel Wi-Fi 6 AX200                                                     | 103       | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 98        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 94        | 2.01%   |
| Intel Wireless 8265 / 8275                                              | 93        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 92        | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 90        | 1.92%   |
| Intel Wi-Fi 6 AX201                                                     | 89        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 88        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 74        | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 72        | 1.54%   |
| Intel Wireless 7265                                                     | 68        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 58        | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 1.22%   |
| Intel Wireless 7260                                                     | 57        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 55        | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.15%   |
| Intel Wireless 3165                                                     | 51        | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 51        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.9%    |
| Intel WiFi Link 5100                                                    | 39        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 38        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 33        | 0.7%    |
| Intel Wireless 8260                                                     | 33        | 0.7%    |
| Intel Wireless 3160                                                     | 32        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 32        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 32        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 31        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 31        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 26        | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 26        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 25        | 0.53%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 24        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1118      | 43.76%  |
| Qualcomm Atheros                | 544       | 21.29%  |
| Realtek Semiconductor           | 459       | 17.96%  |
| Broadcom                        | 198       | 7.75%   |
| Broadcom Limited                | 48        | 1.88%   |
| Ralink                          | 42        | 1.64%   |
| Ralink Technology               | 34        | 1.33%   |
| MediaTek                        | 31        | 1.21%   |
| TP-Link                         | 27        | 1.06%   |
| Sierra Wireless                 | 10        | 0.39%   |
| Qualcomm Atheros Communications | 8         | 0.31%   |
| Dell                            | 6         | 0.23%   |
| Qualcomm                        | 4         | 0.16%   |
| Hewlett-Packard                 | 4         | 0.16%   |
| D-Link                          | 4         | 0.16%   |
| ASUSTek Computer                | 4         | 0.16%   |
| Edimax Technology               | 3         | 0.12%   |
| Fibocom                         | 2         | 0.08%   |
| Accton Technology               | 2         | 0.08%   |
| Sitecom Europe                  | 1         | 0.04%   |
| NetGear                         | 1         | 0.04%   |
| Linksys                         | 1         | 0.04%   |
| Gemtek                          | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| AirTies Wireless Networks       | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 103       | 4.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 98        | 3.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 94        | 3.66%   |
| Intel Wireless 8265 / 8275                                              | 93        | 3.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 92        | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 90        | 3.5%    |
| Intel Wi-Fi 6 AX201                                                     | 89        | 3.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 88        | 3.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 74        | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 72        | 2.8%    |
| Intel Wireless 7265                                                     | 68        | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 58        | 2.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 2.22%   |
| Intel Wireless 7260                                                     | 57        | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 55        | 2.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 2.1%    |
| Intel Wireless 3165                                                     | 51        | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.63%   |
| Intel WiFi Link 5100                                                    | 39        | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 38        | 1.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 33        | 1.28%   |
| Intel Wireless 8260                                                     | 33        | 1.28%   |
| Intel Wireless 3160                                                     | 32        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 32        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 31        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 31        | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 25        | 0.97%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 24        | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 23        | 0.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 22        | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 21        | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 20        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 20        | 0.78%   |
| Realtek 802.11n WLAN Adapter                                            | 17        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1176      | 57.56%  |
| Intel                                  | 319       | 15.61%  |
| Qualcomm Atheros                       | 174       | 8.52%   |
| Broadcom                               | 135       | 6.61%   |
| Marvell Technology Group               | 61        | 2.99%   |
| Broadcom Limited                       | 24        | 1.17%   |
| Nvidia                                 | 19        | 0.93%   |
| Samsung Electronics                    | 18        | 0.88%   |
| ASIX Electronics                       | 16        | 0.78%   |
| Xiaomi                                 | 15        | 0.73%   |
| TP-Link                                | 13        | 0.64%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.64%   |
| JMicron Technology                     | 10        | 0.49%   |
| Lenovo                                 | 9         | 0.44%   |
| DisplayLink                            | 8         | 0.39%   |
| Qualcomm                               | 5         | 0.24%   |
| VIA Technologies                       | 4         | 0.2%    |
| LSI                                    | 4         | 0.2%    |
| Hewlett-Packard                        | 4         | 0.2%    |
| Attansic Technology                    | 4         | 0.2%    |
| Google                                 | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| Huawei Technologies                    | 1         | 0.05%   |
| Davicom Semiconductor                  | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| ADMtek                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 793       | 38.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 251       | 12.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 107       | 5.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 2.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 32        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 22        | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.68%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 13        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 12        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 11        | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.53%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 10        | 0.48%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 10        | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2411      | 54.31%  |
| Ethernet | 1986      | 44.74%  |
| Modem    | 41        | 0.92%   |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1966      | 75.5%   |
| Ethernet | 638       | 24.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1800      | 73.08%  |
| 1     | 601       | 24.4%   |
| 0     | 50        | 2.03%   |
| 3     | 11        | 0.45%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2395      | 96.77%  |
| Yes  | 80        | 3.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 835       | 45.68%  |
| Realtek Semiconductor           | 233       | 12.75%  |
| IMC Networks                    | 134       | 7.33%   |
| Qualcomm Atheros Communications | 129       | 7.06%   |
| Lite-On Technology              | 83        | 4.54%   |
| Broadcom                        | 83        | 4.54%   |
| Foxconn / Hon Hai               | 74        | 4.05%   |
| Apple                           | 53        | 2.9%    |
| Toshiba                         | 34        | 1.86%   |
| Cambridge Silicon Radio         | 34        | 1.86%   |
| Realtek                         | 31        | 1.7%    |
| Dell                            | 25        | 1.37%   |
| Hewlett-Packard                 | 22        | 1.2%    |
| Ralink                          | 17        | 0.93%   |
| ASUSTek Computer                | 13        | 0.71%   |
| Alps Electric                   | 12        | 0.66%   |
| Foxconn International           | 8         | 0.44%   |
| Ralink Technology               | 4         | 0.22%   |
| Askey Computer                  | 2         | 0.11%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 328       | 17.94%  |
| Intel AX201 Bluetooth                               | 164       | 8.97%   |
| Realtek Bluetooth Radio                             | 163       | 8.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 153       | 8.37%   |
| Intel AX200 Bluetooth                               | 101       | 5.53%   |
| IMC Networks Bluetooth Radio                        | 68        | 3.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 52        | 2.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 48        | 2.63%   |
| IMC Networks Bluetooth Device                       | 38        | 2.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 1.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 1.86%   |
| Apple Bluetooth Host Controller                     | 33        | 1.81%   |
| Realtek Bluetooth Radio                             | 31        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.48%   |
| Lite-On Bluetooth Device                            | 23        | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 21        | 1.15%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 1.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 19        | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.04%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.93%   |
| Intel AX210 Bluetooth                               | 17        | 0.93%   |
| IMC Networks Wireless_Device                        | 16        | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 0.77%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.71%   |
| Intel Bluetooth Device                              | 12        | 0.66%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.6%    |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.55%   |
| Realtek RTL8821A Bluetooth                          | 8         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                        | 8         | 0.44%   |
| Broadcom BCM2045 Bluetooth                          | 8         | 0.44%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1964      | 66.4%   |
| AMD                                  | 494       | 16.7%   |
| Nvidia                               | 332       | 11.22%  |
| C-Media Electronics                  | 22        | 0.74%   |
| Logitech                             | 16        | 0.54%   |
| Silicon Integrated Systems [SiS]     | 13        | 0.44%   |
| Lenovo                               | 9         | 0.3%    |
| GN Netcom                            | 9         | 0.3%    |
| Plantronics                          | 7         | 0.24%   |
| JMTek                                | 7         | 0.24%   |
| Realtek Semiconductor                | 6         | 0.2%    |
| VIA Technologies                     | 5         | 0.17%   |
| Texas Instruments                    | 4         | 0.14%   |
| Kingston Technology                  | 4         | 0.14%   |
| Generalplus Technology               | 4         | 0.14%   |
| Corsair                              | 4         | 0.14%   |
| SteelSeries ApS                      | 3         | 0.1%    |
| Hewlett-Packard                      | 3         | 0.1%    |
| Creative Technology                  | 3         | 0.1%    |
| BEHRINGER International              | 3         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| No brand                             | 2         | 0.07%   |
| Guillemot                            | 2         | 0.07%   |
| DSEA A/S                             | 2         | 0.07%   |
| CMX Systems                          | 2         | 0.07%   |
| Blue Microphones                     | 2         | 0.07%   |
| ASUSTek Computer                     | 2         | 0.07%   |
| Apple                                | 2         | 0.07%   |
| Alesis                               | 2         | 0.07%   |
| Vestax                               | 1         | 0.03%   |
| Veho                                 | 1         | 0.03%   |
| Unknown (ABC)                        | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| ThrustMaster                         | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Signalpath International             | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 265       | 7.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 229       | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 141       | 3.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 131       | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 126       | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 121       | 3.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 120       | 3.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 115       | 3.22%   |
| Intel 8 Series HD Audio Controller                                                                | 115       | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 112       | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 100       | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 91        | 2.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 87        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 82        | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 81        | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 79        | 2.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 78        | 2.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 76        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 68        | 1.9%    |
| AMD FCH Azalia Controller                                                                         | 67        | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 62        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 58        | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 57        | 1.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 55        | 1.54%   |
| AMD High Definition Audio Controller                                                              | 46        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 45        | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 44        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 42        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 40        | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 37        | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 33        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 32        | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 31        | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 30        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 29        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 28        | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 25        | 0.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 25        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 453       | 30.94%  |
| SK hynix                     | 313       | 21.38%  |
| Micron Technology            | 179       | 12.23%  |
| Kingston                     | 139       | 9.49%   |
| Unknown                      | 113       | 7.72%   |
| Crucial                      | 68        | 4.64%   |
| Ramaxel Technology           | 50        | 3.42%   |
| Unknown (ABCD)               | 22        | 1.5%    |
| Elpida                       | 21        | 1.43%   |
| A-DATA Technology            | 16        | 1.09%   |
| Nanya Technology             | 15        | 1.02%   |
| Corsair                      | 13        | 0.89%   |
| G.Skill                      | 11        | 0.75%   |
| Silicon Power                | 7         | 0.48%   |
| Transcend                    | 5         | 0.34%   |
| Goodram                      | 5         | 0.34%   |
| Unknown                      | 5         | 0.34%   |
| Wilk                         | 3         | 0.2%    |
| Apacer                       | 3         | 0.2%    |
| SHARETRONIC                  | 2         | 0.14%   |
| Patriot                      | 2         | 0.14%   |
| KomputerBay                  | 2         | 0.14%   |
| Avant                        | 2         | 0.14%   |
| Unifosa                      | 1         | 0.07%   |
| Toshiba                      | 1         | 0.07%   |
| Timetec                      | 1         | 0.07%   |
| Team                         | 1         | 0.07%   |
| Qimonda                      | 1         | 0.07%   |
| PNY                          | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Netlist                      | 1         | 0.07%   |
| Netac                        | 1         | 0.07%   |
| Micron/Elpida                | 1         | 0.07%   |
| Kllisre                      | 1         | 0.07%   |
| Kembona                      | 1         | 0.07%   |
| CSX                          | 1         | 0.07%   |
| Atermiter                    | 1         | 0.07%   |
| ASint Technology             | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 28        | 1.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 21        | 1.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 1.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 17        | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 1.11%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 17        | 1.11%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.98%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 14        | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.78%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 12        | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 11        | 0.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 11        | 0.72%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.59%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 8         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.52%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 8         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.52%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 8         | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 606       | 48.83%  |
| DDR3    | 396       | 31.91%  |
| DDR2    | 75        | 6.04%   |
| LPDDR4  | 58        | 4.67%   |
| LPDDR3  | 47        | 3.79%   |
| SDRAM   | 27        | 2.18%   |
| DDR5    | 8         | 0.64%   |
| DDR     | 7         | 0.56%   |
| Unknown | 7         | 0.56%   |
| DRAM    | 6         | 0.48%   |
| LPDDR5  | 4         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1119      | 89.16%  |
| Row Of Chips | 120       | 9.56%   |
| DIMM         | 8         | 0.64%   |
| Chip         | 8         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 527       | 39.04%  |
| 4096  | 387       | 28.67%  |
| 16384 | 195       | 14.44%  |
| 2048  | 155       | 11.48%  |
| 1024  | 52        | 3.85%   |
| 32768 | 27        | 2%      |
| 512   | 4         | 0.3%    |
| 256   | 2         | 0.15%   |
| 3072  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 281       | 21.06%  |
| 1600    | 266       | 19.94%  |
| 3200    | 242       | 18.14%  |
| 2400    | 93        | 6.97%   |
| 2133    | 67        | 5.02%   |
| 1334    | 64        | 4.8%    |
| 667     | 52        | 3.9%    |
| 1333    | 47        | 3.52%   |
| Unknown | 36        | 2.7%    |
| 8400    | 28        | 2.1%    |
| 4267    | 23        | 1.72%   |
| 1067    | 23        | 1.72%   |
| 1867    | 15        | 1.12%   |
| 3266    | 14        | 1.05%   |
| 800     | 13        | 0.97%   |
| 533     | 12        | 0.9%    |
| 4199    | 10        | 0.75%   |
| 2048    | 9         | 0.67%   |
| 4800    | 8         | 0.6%    |
| 6400    | 5         | 0.37%   |
| 4266    | 5         | 0.37%   |
| 1066    | 5         | 0.37%   |
| 975     | 5         | 0.37%   |
| 2933    | 2         | 0.15%   |
| 1200    | 2         | 0.15%   |
| 3733    | 1         | 0.07%   |
| 3000    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 1639    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |
| 333     | 1         | 0.07%   |
| 266     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 10        | 50%     |
| Canon              | 4         | 20%     |
| Seiko Epson        | 3         | 15%     |
| Brother Industries | 3         | 15%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series        | 3         | 15%     |
| Seiko Epson XP-230 Series        | 1         | 5%      |
| Seiko Epson Printer              | 1         | 5%      |
| Seiko Epson L555 Series          | 1         | 5%      |
| HP PSC 1500 series               | 1         | 5%      |
| HP Printing Support              | 1         | 5%      |
| HP LaserJet Professional P 1102w | 1         | 5%      |
| HP LaserJet Pro M404-M405        | 1         | 5%      |
| HP LaserJet 1320                 | 1         | 5%      |
| HP LaserJet 1020                 | 1         | 5%      |
| HP LaserJet 1018                 | 1         | 5%      |
| HP LaserJet 1000                 | 1         | 5%      |
| HP DeskJet F300 series           | 1         | 5%      |
| HP Deskjet 2050 J510             | 1         | 5%      |
| Canon TS3100 series              | 1         | 5%      |
| Brother MFC-J5330DW              | 1         | 5%      |
| Brother HL-2030 Laser Printer    | 1         | 5%      |
| Brother HL-1210W series          | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 4300c              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 210       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 558       | 26.37%  |
| IMC Networks                           | 268       | 12.67%  |
| Acer                                   | 229       | 10.82%  |
| Realtek Semiconductor                  | 141       | 6.66%   |
| Microdia                               | 137       | 6.47%   |
| Suyin                                  | 110       | 5.2%    |
| Quanta                                 | 105       | 4.96%   |
| Cheng Uei Precision Industry (Foxlink) | 87        | 4.11%   |
| Sunplus Innovation Technology          | 86        | 4.06%   |
| Syntek                                 | 65        | 3.07%   |
| Alcor Micro                            | 39        | 1.84%   |
| Lite-On Technology                     | 34        | 1.61%   |
| Apple                                  | 33        | 1.56%   |
| Ricoh                                  | 28        | 1.32%   |
| Luxvisions Innotech Limited            | 24        | 1.13%   |
| Silicon Motion                         | 18        | 0.85%   |
| Logitech                               | 17        | 0.8%    |
| Samsung Electronics                    | 11        | 0.52%   |
| Sonix Technology                       | 9         | 0.43%   |
| Importek                               | 9         | 0.43%   |
| Lenovo                                 | 8         | 0.38%   |
| ALi                                    | 8         | 0.38%   |
| Z-Star Microelectronics                | 7         | 0.33%   |
| USB Camera                             | 7         | 0.33%   |
| GEMBIRD                                | 7         | 0.33%   |
| Sunplus Technology                     | 6         | 0.28%   |
| Primax Electronics                     | 5         | 0.24%   |
| KYE Systems (Mouse Systems)            | 5         | 0.24%   |
| Intel                                  | 5         | 0.24%   |
| OmniVision Technologies                | 4         | 0.19%   |
| Genesys Logic                          | 4         | 0.19%   |
| DigiTech                               | 4         | 0.19%   |
| ARC International                      | 4         | 0.19%   |
| DJJHFA1BIF5595                         | 3         | 0.14%   |
| Trust                                  | 2         | 0.09%   |
| Novatek Microelectronics               | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| HD 2MP WEBCAM                          | 2         | 0.09%   |
| Creative Technology                    | 2         | 0.09%   |
| Xiaomi                                 | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 70        | 3.3%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 66        | 3.11%   |
| Chicony HD WebCam                                       | 62        | 2.92%   |
| Microdia Integrated_Webcam_HD                           | 60        | 2.83%   |
| Chicony Integrated Camera                               | 56        | 2.64%   |
| Acer Integrated Camera                                  | 52        | 2.45%   |
| Acer HD Webcam                                          | 49        | 2.31%   |
| IMC Networks Integrated Camera                          | 40        | 1.88%   |
| Chicony USB2.0 VGA UVC WebCam                           | 37        | 1.74%   |
| Realtek Integrated_Webcam_HD                            | 32        | 1.51%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 30        | 1.41%   |
| Quanta HP TrueVision HD Camera                          | 29        | 1.37%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 1.22%   |
| Sunplus HD WebCam                                       | 25        | 1.18%   |
| Realtek USB Camera                                      | 25        | 1.18%   |
| Chicony USB 2.0 Camera                                  | 22        | 1.04%   |
| Chicony EasyCamera                                      | 22        | 1.04%   |
| Syntek Integrated Camera                                | 21        | 0.99%   |
| Acer HD Camera                                          | 19        | 0.89%   |
| Acer EasyCamera                                         | 19        | 0.89%   |
| Chicony USB2.0 HD UVC WebCam                            | 18        | 0.85%   |
| Syntek EasyCamera                                       | 17        | 0.8%    |
| Lite-On Integrated Camera                               | 17        | 0.8%    |
| Chicony HP TrueVision HD                                | 17        | 0.8%    |
| Syntek Lenovo EasyCamera                                | 16        | 0.75%   |
| Realtek Lenovo EasyCamera                               | 16        | 0.75%   |
| Chicony VGA WebCam                                      | 16        | 0.75%   |
| Chicony HP HD Camera                                    | 16        | 0.75%   |
| Apple Built-in iSight                                   | 16        | 0.75%   |
| Acer Lenovo EasyCamera                                  | 16        | 0.75%   |
| Chicony Integrated Camera (1280x720@30)                 | 15        | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.71%   |
| Quanta HP HD Camera                                     | 14        | 0.66%   |
| IMC Networks ov9734_azurewave_camera                    | 14        | 0.66%   |
| Chicony USB2.0 Camera                                   | 14        | 0.66%   |
| Chicony HP TrueVision HD Camera                         | 14        | 0.66%   |
| Alcor Micro Asus Integrated Webcam                      | 14        | 0.66%   |
| Suyin HP TrueVision HD                                  | 13        | 0.61%   |
| Realtek USB2.0 VGA UVC WebCam                           | 13        | 0.61%   |
| Quanta HP Webcam                                        | 13        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 94        | 27.98%  |
| Validity Sensors           | 81        | 24.11%  |
| Shenzhen Goodix Technology | 55        | 16.37%  |
| Elan Microelectronics      | 36        | 10.71%  |
| AuthenTec                  | 34        | 10.12%  |
| Upek                       | 21        | 6.25%   |
| LighTuning Technology      | 9         | 2.68%   |
| STMicroelectronics         | 6         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 44        | 13.1%   |
| Shenzhen Goodix  FingerPrint Device                                        | 40        | 11.9%   |
| Elan ELAN:Fingerprint                                                      | 33        | 9.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 7.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 3.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.79%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.79%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.79%   |
| AuthenTec AES1600                                                          | 6         | 1.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.49%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.49%   |
| AuthenTec AES2810                                                          | 5         | 1.49%   |
| Validity Sensors VFS491                                                    | 4         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.19%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.19%   |
| Synaptics  WBDI                                                            | 4         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.19%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.19%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.89%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.89%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.6%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.6%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.6%    |
| LighTuning Fingerprint Reader                                              | 2         | 0.6%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.6%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 52        | 34.67%  |
| Broadcom              | 48        | 32%     |
| O2 Micro              | 23        | 15.33%  |
| Lenovo                | 8         | 5.33%   |
| Upek                  | 4         | 2.67%   |
| C3PO                  | 4         | 2.67%   |
| Realtek Semiconductor | 3         | 2%      |
| Cherry                | 3         | 2%      |
| Gemalto (was Gemplus) | 2         | 1.33%   |
| In Focus Systems      | 1         | 0.67%   |
| Chicony Electronics   | 1         | 0.67%   |
| Advanced Card Systems | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 52        | 34.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 14.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.33%  |
| Broadcom 5880                                                                | 13        | 8.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 6%      |
| Broadcom 58200                                                               | 9         | 6%      |
| Lenovo Integrated Smart Card Reader                                          | 8         | 5.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.67%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2%      |
| Cherry SmartTerminal XX1X                                                    | 3         | 2%      |
| C3PO LTC31v2                                                                 | 3         | 2%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.67%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.67%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.67%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.67%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1643      | 65.1%   |
| 1     | 685       | 27.14%  |
| 2     | 164       | 6.5%    |
| 3     | 21        | 0.83%   |
| 4     | 7         | 0.28%   |
| 5     | 3         | 0.12%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 328       | 30.34%  |
| Graphics card            | 245       | 22.66%  |
| Net/wireless             | 145       | 13.41%  |
| Chipcard                 | 131       | 12.12%  |
| Multimedia controller    | 66        | 6.11%   |
| Camera                   | 36        | 3.33%   |
| Bluetooth                | 26        | 2.41%   |
| Storage                  | 22        | 2.04%   |
| Communication controller | 22        | 2.04%   |
| Card reader              | 15        | 1.39%   |
| Sound                    | 11        | 1.02%   |
| Net/ethernet             | 11        | 1.02%   |
| Flash memory             | 10        | 0.93%   |
| Modem                    | 8         | 0.74%   |
| Dvb card                 | 3         | 0.28%   |
| Network                  | 2         | 0.19%   |

