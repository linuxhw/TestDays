Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 6638

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| MSI           | Boston                      | Desktop     | [a5fd252dc2](https://linux-hardware.org/?probe=a5fd252dc2) | Dec 30, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | Notebook    | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | Notebook    | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [328cfe3747](https://linux-hardware.org/?probe=328cfe3747) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Teclast       | TbooK 16 Power              | Tablet      | [c8a0dcd956](https://linux-hardware.org/?probe=c8a0dcd956) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | Notebook    | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | Notebook    | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [305018336b](https://linux-hardware.org/?probe=305018336b) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [aef3959b18](https://linux-hardware.org/?probe=aef3959b18) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [9c75de7af7](https://linux-hardware.org/?probe=9c75de7af7) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| Lenovo        | 318D                        | All in one  | [1bc8e7088b](https://linux-hardware.org/?probe=1bc8e7088b) | Dec 24, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | MS-B1421                    | Desktop     | [58968767bd](https://linux-hardware.org/?probe=58968767bd) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [031afb1b20](https://linux-hardware.org/?probe=031afb1b20) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7502622c61](https://linux-hardware.org/?probe=7502622c61) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | Notebook    | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [405443fc24](https://linux-hardware.org/?probe=405443fc24) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2c931919d](https://linux-hardware.org/?probe=d2c931919d) | Dec 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [e048dd7a4e](https://linux-hardware.org/?probe=e048dd7a4e) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| HP            | 8597                        | Desktop     | [5a7ae7c6d7](https://linux-hardware.org/?probe=5a7ae7c6d7) | Dec 19, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c47ff5ba34](https://linux-hardware.org/?probe=c47ff5ba34) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | Notebook    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [631f80f725](https://linux-hardware.org/?probe=631f80f725) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [b6c7b47859](https://linux-hardware.org/?probe=b6c7b47859) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [3af8ddb8cc](https://linux-hardware.org/?probe=3af8ddb8cc) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Lenovo        | 318D                        | All in one  | [da52280286](https://linux-hardware.org/?probe=da52280286) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [bbf59c4c2a](https://linux-hardware.org/?probe=bbf59c4c2a) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [33d60ebbbe](https://linux-hardware.org/?probe=33d60ebbbe) | Dec 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [7d1ece638c](https://linux-hardware.org/?probe=7d1ece638c) | Dec 14, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f46b869c82](https://linux-hardware.org/?probe=f46b869c82) | Dec 14, 2022 |
| Pro-B         | INSYS                       | Desktop     | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9d665864a0](https://linux-hardware.org/?probe=9d665864a0) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [0af09d12d5](https://linux-hardware.org/?probe=0af09d12d5) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | Desktop     | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [238bda76a3](https://linux-hardware.org/?probe=238bda76a3) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [7870cee549](https://linux-hardware.org/?probe=7870cee549) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | Notebook    | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | Notebook    | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | Notebook    | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [e088d4027d](https://linux-hardware.org/?probe=e088d4027d) | Dec 10, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [aefce63130](https://linux-hardware.org/?probe=aefce63130) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [c72c2382b3](https://linux-hardware.org/?probe=c72c2382b3) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [e098953c51](https://linux-hardware.org/?probe=e098953c51) | Dec 09, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [314ed3ea05](https://linux-hardware.org/?probe=314ed3ea05) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [4be2d528de](https://linux-hardware.org/?probe=4be2d528de) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [787a504fd5](https://linux-hardware.org/?probe=787a504fd5) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [345597cd78](https://linux-hardware.org/?probe=345597cd78) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | Notebook    | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Gigabyte      | H510M S2H V2                | Desktop     | [b0b53bc408](https://linux-hardware.org/?probe=b0b53bc408) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | Notebook    | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [0a028304a1](https://linux-hardware.org/?probe=0a028304a1) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | Notebook    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [e46ba957f0](https://linux-hardware.org/?probe=e46ba957f0) | Dec 02, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [85eab170d2](https://linux-hardware.org/?probe=85eab170d2) | Dec 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f27e558f3](https://linux-hardware.org/?probe=0f27e558f3) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | Notebook    | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Medion        | D3F3-EM                     | Desktop     | [ae428a6a6a](https://linux-hardware.org/?probe=ae428a6a6a) | Nov 29, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9d7352a65d](https://linux-hardware.org/?probe=9d7352a65d) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a95de3b373](https://linux-hardware.org/?probe=a95de3b373) | Nov 29, 2022 |
| HP            | Notebook                    | Notebook    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [982d7f7d0b](https://linux-hardware.org/?probe=982d7f7d0b) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [e311874280](https://linux-hardware.org/?probe=e311874280) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | Desktop     | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [fc74dc1357](https://linux-hardware.org/?probe=fc74dc1357) | Nov 22, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [5f50e13ad0](https://linux-hardware.org/?probe=5f50e13ad0) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [81c02af38c](https://linux-hardware.org/?probe=81c02af38c) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [934f31fcac](https://linux-hardware.org/?probe=934f31fcac) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8de96e0012](https://linux-hardware.org/?probe=8de96e0012) | Nov 20, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [71b3224c4d](https://linux-hardware.org/?probe=71b3224c4d) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [9d276a36d8](https://linux-hardware.org/?probe=9d276a36d8) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [362cf69f1f](https://linux-hardware.org/?probe=362cf69f1f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | Notebook    | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | Notebook    | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [469ead98f8](https://linux-hardware.org/?probe=469ead98f8) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | Notebook    | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| HP            | 0AA8h                       | Desktop     | [0f88d64eeb](https://linux-hardware.org/?probe=0f88d64eeb) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c9e0bcd9d6](https://linux-hardware.org/?probe=c9e0bcd9d6) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [f588871a3a](https://linux-hardware.org/?probe=f588871a3a) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [5086b0aa3e](https://linux-hardware.org/?probe=5086b0aa3e) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c16c0f7d8f](https://linux-hardware.org/?probe=c16c0f7d8f) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | Notebook    | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [ea1d9a2fa4](https://linux-hardware.org/?probe=ea1d9a2fa4) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [e0b38a3d54](https://linux-hardware.org/?probe=e0b38a3d54) | Nov 11, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| HP            | 805E                        | All in one  | [fdd688e64e](https://linux-hardware.org/?probe=fdd688e64e) | Nov 11, 2022 |
| HP            | 805E                        | All in one  | [c37ec12e5f](https://linux-hardware.org/?probe=c37ec12e5f) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | Notebook    | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | Notebook    | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [4b5ec389d9](https://linux-hardware.org/?probe=4b5ec389d9) | Nov 09, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [292caf8ccf](https://linux-hardware.org/?probe=292caf8ccf) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [3900976672](https://linux-hardware.org/?probe=3900976672) | Nov 08, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [0aad7f7578](https://linux-hardware.org/?probe=0aad7f7578) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | Notebook    | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | Notebook    | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | Notebook    | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | Notebook    | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| HP            | 8459                        | Desktop     | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| HP            | 1998                        | Desktop     | [ba48cbeebe](https://linux-hardware.org/?probe=ba48cbeebe) | Nov 04, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [93b2e9aea5](https://linux-hardware.org/?probe=93b2e9aea5) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [5466838c04](https://linux-hardware.org/?probe=5466838c04) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [3bec3377a8](https://linux-hardware.org/?probe=3bec3377a8) | Nov 03, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [347b32510b](https://linux-hardware.org/?probe=347b32510b) | Nov 03, 2022 |
| HP            | G62                         | Notebook    | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | Notebook    | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [f0db98f6bb](https://linux-hardware.org/?probe=f0db98f6bb) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [fc832e8881](https://linux-hardware.org/?probe=fc832e8881) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [416db8870a](https://linux-hardware.org/?probe=416db8870a) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | Notebook    | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [55aa58c274](https://linux-hardware.org/?probe=55aa58c274) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| Unknown       | Unknown                     | Soc         | [44fc490d82](https://linux-hardware.org/?probe=44fc490d82) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | Notebook    | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Intel         | H410M-E                     | Desktop     | [854c3ec5b1](https://linux-hardware.org/?probe=854c3ec5b1) | Oct 27, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [5b6d2d2922](https://linux-hardware.org/?probe=5b6d2d2922) | Oct 27, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [033d6281bd](https://linux-hardware.org/?probe=033d6281bd) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [f9e114a7e9](https://linux-hardware.org/?probe=f9e114a7e9) | Oct 26, 2022 |
| Intel         | H410M-E                     | Desktop     | [69d7d07e13](https://linux-hardware.org/?probe=69d7d07e13) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | Notebook    | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [696c30d8c3](https://linux-hardware.org/?probe=696c30d8c3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | Notebook    | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c05a08e1af](https://linux-hardware.org/?probe=c05a08e1af) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [936e43f0bc](https://linux-hardware.org/?probe=936e43f0bc) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [cce3979970](https://linux-hardware.org/?probe=cce3979970) | Oct 22, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6105b0d3a9](https://linux-hardware.org/?probe=6105b0d3a9) | Oct 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | Notebook    | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | K54C                        | Notebook    | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [18c1a4a04d](https://linux-hardware.org/?probe=18c1a4a04d) | Oct 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff6334ee8f](https://linux-hardware.org/?probe=ff6334ee8f) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [e1eacaa737](https://linux-hardware.org/?probe=e1eacaa737) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| MSI           | IONA                        | Desktop     | [7c164d5733](https://linux-hardware.org/?probe=7c164d5733) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a7941186ab](https://linux-hardware.org/?probe=a7941186ab) | Oct 16, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| HP            | 1495                        | Desktop     | [109913631a](https://linux-hardware.org/?probe=109913631a) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [8bfcad8486](https://linux-hardware.org/?probe=8bfcad8486) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [99fe717434](https://linux-hardware.org/?probe=99fe717434) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [b75b67267c](https://linux-hardware.org/?probe=b75b67267c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [0e3ba8fdb3](https://linux-hardware.org/?probe=0e3ba8fdb3) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [78abe50673](https://linux-hardware.org/?probe=78abe50673) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | Notebook    | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [100f7e1b46](https://linux-hardware.org/?probe=100f7e1b46) | Oct 12, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [5b1999a241](https://linux-hardware.org/?probe=5b1999a241) | Oct 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [1a2fe5eeb4](https://linux-hardware.org/?probe=1a2fe5eeb4) | Oct 12, 2022 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [f3b5809fc9](https://linux-hardware.org/?probe=f3b5809fc9) | Oct 12, 2022 |
| HP            | 3397                        | Desktop     | [c374208e14](https://linux-hardware.org/?probe=c374208e14) | Oct 11, 2022 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [b8c2a39217](https://linux-hardware.org/?probe=b8c2a39217) | Oct 10, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c3a4a7983b](https://linux-hardware.org/?probe=c3a4a7983b) | Oct 10, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [d223d492fe](https://linux-hardware.org/?probe=d223d492fe) | Oct 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | Notebook    | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [dd8bbe4068](https://linux-hardware.org/?probe=dd8bbe4068) | Oct 08, 2022 |
| Medion        | E2221T MD61083              | Convertible | [9f7f0f4ea8](https://linux-hardware.org/?probe=9f7f0f4ea8) | Oct 07, 2022 |
| Medion        | E2221T MD61083              | Convertible | [2eaf3df98c](https://linux-hardware.org/?probe=2eaf3df98c) | Oct 07, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5b30b0591e](https://linux-hardware.org/?probe=5b30b0591e) | Oct 07, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [2550504760](https://linux-hardware.org/?probe=2550504760) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6f0bd5a568](https://linux-hardware.org/?probe=6f0bd5a568) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | Notebook    | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Lenovo        | 1031 SDK0E50510 WIN 2625... | Desktop     | [771e19629c](https://linux-hardware.org/?probe=771e19629c) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [c6dd3eef5d](https://linux-hardware.org/?probe=c6dd3eef5d) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | Notebook    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Shuttle       | DH470                       | Desktop     | [408e44b18b](https://linux-hardware.org/?probe=408e44b18b) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | Notebook    | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [fc1fb9966e](https://linux-hardware.org/?probe=fc1fb9966e) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [d19e0fb48b](https://linux-hardware.org/?probe=d19e0fb48b) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4707a778dc](https://linux-hardware.org/?probe=4707a778dc) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [255a0a928a](https://linux-hardware.org/?probe=255a0a928a) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [77d108e391](https://linux-hardware.org/?probe=77d108e391) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| HP            | 2B35                        | Desktop     | [724e0d61e3](https://linux-hardware.org/?probe=724e0d61e3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Acer          | Aspire X1900                | Desktop     | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | Notebook    | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [173834876c](https://linux-hardware.org/?probe=173834876c) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | Notebook    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [d00d31309a](https://linux-hardware.org/?probe=d00d31309a) | Sep 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [cb519b4bfe](https://linux-hardware.org/?probe=cb519b4bfe) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Sony          | VPCEB1Z1E                   | Notebook    | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | Notebook    | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Minix         | NEO G41V-4 Max              | Desktop     | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Unknown       | 1.0                         | Desktop     | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | Notebook    | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [7ea35cc80a](https://linux-hardware.org/?probe=7ea35cc80a) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0b32a9e842](https://linux-hardware.org/?probe=0b32a9e842) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [fab04fe2c7](https://linux-hardware.org/?probe=fab04fe2c7) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | Notebook    | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | Notebook    | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | Notebook    | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [0b03396c93](https://linux-hardware.org/?probe=0b03396c93) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Acer          | Aspire X3990                | Desktop     | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [c5ebccdc5d](https://linux-hardware.org/?probe=c5ebccdc5d) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [74a9860a2e](https://linux-hardware.org/?probe=74a9860a2e) | Sep 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | Notebook    | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [93a5a7089c](https://linux-hardware.org/?probe=93a5a7089c) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | Notebook    | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | Notebook    | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [0caf1e7324](https://linux-hardware.org/?probe=0caf1e7324) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [06d3f051d1](https://linux-hardware.org/?probe=06d3f051d1) | Sep 09, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Medion        | H61H2-LM3 V1.0              | Desktop     | [96b497db35](https://linux-hardware.org/?probe=96b497db35) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [c0ad8b81fa](https://linux-hardware.org/?probe=c0ad8b81fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9128ddb611](https://linux-hardware.org/?probe=9128ddb611) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6596b0d415](https://linux-hardware.org/?probe=6596b0d415) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b84d0acafb](https://linux-hardware.org/?probe=b84d0acafb) | Sep 01, 2022 |
| Dell          | 07PXPY A04                  | Server      | [f0b9cd86ef](https://linux-hardware.org/?probe=f0b9cd86ef) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | Notebook    | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3955b91269](https://linux-hardware.org/?probe=3955b91269) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3148482797](https://linux-hardware.org/?probe=3148482797) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [12033c4a8b](https://linux-hardware.org/?probe=12033c4a8b) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| MSI           | H97M-G43                    | Desktop     | [978d5b45be](https://linux-hardware.org/?probe=978d5b45be) | Aug 31, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [71ce0b707c](https://linux-hardware.org/?probe=71ce0b707c) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | Notebook    | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | F3F                         | Notebook    | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | Notebook    | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [437b0cd64f](https://linux-hardware.org/?probe=437b0cd64f) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [28ebe8cc1f](https://linux-hardware.org/?probe=28ebe8cc1f) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| Gigabyte      | H81M-D3H                    | Desktop     | [89ced19bd4](https://linux-hardware.org/?probe=89ced19bd4) | Aug 25, 2022 |
| Fujitsu       | D3173-A1 S26361-D3173-A1    | Mini pc     | [273ce0954a](https://linux-hardware.org/?probe=273ce0954a) | Aug 25, 2022 |
| MSI           | H97M-G43                    | Desktop     | [3f781247f0](https://linux-hardware.org/?probe=3f781247f0) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | Notebook    | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HP            | 3647h                       | Desktop     | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | Notebook    | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [216ea6f436](https://linux-hardware.org/?probe=216ea6f436) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Gateway       | DS50                        | Desktop     | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [02f9463f2b](https://linux-hardware.org/?probe=02f9463f2b) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | Notebook    | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| sunxi         | Unknown                     | Soc         | [a57117f63f](https://linux-hardware.org/?probe=a57117f63f) | Aug 15, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [f223d64d8f](https://linux-hardware.org/?probe=f223d64d8f) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b69d60f568](https://linux-hardware.org/?probe=b69d60f568) | Aug 15, 2022 |
| GPD           | G1618-03                    | Notebook    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | Notebook    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Pegatron      | 2A94                        | Desktop     | [81b0cdd377](https://linux-hardware.org/?probe=81b0cdd377) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fd9bae65fa](https://linux-hardware.org/?probe=fd9bae65fa) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [1840f48c85](https://linux-hardware.org/?probe=1840f48c85) | Aug 12, 2022 |
| Dell          | Latitude D630               | Notebook    | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [be29e8b357](https://linux-hardware.org/?probe=be29e8b357) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | Notebook    | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | 3397                        | Desktop     | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [f04f6e3bed](https://linux-hardware.org/?probe=f04f6e3bed) | Aug 07, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [305bf6182f](https://linux-hardware.org/?probe=305bf6182f) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | Notebook    | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| ASUSTek       | M3A78                       | Desktop     | [bda5207234](https://linux-hardware.org/?probe=bda5207234) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | Notebook    | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ab497e8975](https://linux-hardware.org/?probe=ab497e8975) | Aug 04, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f013fa996e](https://linux-hardware.org/?probe=f013fa996e) | Aug 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [c290aae7c6](https://linux-hardware.org/?probe=c290aae7c6) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [19d2273e6b](https://linux-hardware.org/?probe=19d2273e6b) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [8e83e6141d](https://linux-hardware.org/?probe=8e83e6141d) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Acer          | Aspire X3470                | Desktop     | [88ad041430](https://linux-hardware.org/?probe=88ad041430) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | 2AF7                        | Desktop     | [da51487005](https://linux-hardware.org/?probe=da51487005) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e3a44e4c5b](https://linux-hardware.org/?probe=e3a44e4c5b) | Jul 30, 2022 |
| HP            | Compaq 8510p                | Notebook    | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [db241f583d](https://linux-hardware.org/?probe=db241f583d) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | Notebook    | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [d29d943a24](https://linux-hardware.org/?probe=d29d943a24) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | Notebook    | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | Notebook    | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [6b300beb70](https://linux-hardware.org/?probe=6b300beb70) | Jul 25, 2022 |
| Acer          | Aspire 5749                 | Notebook    | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [c7c46e080e](https://linux-hardware.org/?probe=c7c46e080e) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7cc616f3c8](https://linux-hardware.org/?probe=7cc616f3c8) | Jul 24, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [ce14e41b96](https://linux-hardware.org/?probe=ce14e41b96) | Jul 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| Dell          | 0GM819                      | Desktop     | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [89fadaa563](https://linux-hardware.org/?probe=89fadaa563) | Jul 23, 2022 |
| HP            | Stream Notebook             | Notebook    | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | Notebook    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| Dell          | 0GM819                      | Desktop     | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [7ff3bd3639](https://linux-hardware.org/?probe=7ff3bd3639) | Jul 20, 2022 |
| Foxconn       | ETON                        | Desktop     | [1686897e74](https://linux-hardware.org/?probe=1686897e74) | Jul 20, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [67faad589b](https://linux-hardware.org/?probe=67faad589b) | Jul 19, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | Notebook    | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | Notebook    | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [03fca40d38](https://linux-hardware.org/?probe=03fca40d38) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | Notebook    | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| MSI           | Boston                      | Desktop     | [c1474f9d2f](https://linux-hardware.org/?probe=c1474f9d2f) | Jul 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c7a2ebd9dc](https://linux-hardware.org/?probe=c7a2ebd9dc) | Jul 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | Notebook    | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [3fe93a38f6](https://linux-hardware.org/?probe=3fe93a38f6) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Acer          | Aspire X3470                | Desktop     | [61b7216da0](https://linux-hardware.org/?probe=61b7216da0) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [3ec331da1f](https://linux-hardware.org/?probe=3ec331da1f) | Jul 12, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [26c70348e9](https://linux-hardware.org/?probe=26c70348e9) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | 318D                        | All in one  | [6c8aa85c66](https://linux-hardware.org/?probe=6c8aa85c66) | Jul 10, 2022 |
| HP            | 805E                        | All in one  | [c7570f51e8](https://linux-hardware.org/?probe=c7570f51e8) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [75f0ca97b8](https://linux-hardware.org/?probe=75f0ca97b8) | Jul 08, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [560e81bb64](https://linux-hardware.org/?probe=560e81bb64) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [4f57a8d7f4](https://linux-hardware.org/?probe=4f57a8d7f4) | Jul 08, 2022 |
| Dell          | Latitude 5285               | Notebook    | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| HP            | 18E7                        | Desktop     | [68781cd22f](https://linux-hardware.org/?probe=68781cd22f) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [aed7de4f94](https://linux-hardware.org/?probe=aed7de4f94) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [8e5892c130](https://linux-hardware.org/?probe=8e5892c130) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | Notebook    | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| MSI           | Z87 MPOWER                  | Desktop     | [ba26baf84a](https://linux-hardware.org/?probe=ba26baf84a) | Jun 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [6dff126482](https://linux-hardware.org/?probe=6dff126482) | Jun 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| HP            | 3647h                       | Desktop     | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [ace3582eee](https://linux-hardware.org/?probe=ace3582eee) | Jun 28, 2022 |
| HP            | 805E                        | All in one  | [efbad579d1](https://linux-hardware.org/?probe=efbad579d1) | Jun 27, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [5d18d90cda](https://linux-hardware.org/?probe=5d18d90cda) | Jun 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [6c18625cb3](https://linux-hardware.org/?probe=6c18625cb3) | Jun 27, 2022 |
| ASUSTek       | P5K                         | Desktop     | [e401eb71bc](https://linux-hardware.org/?probe=e401eb71bc) | Jun 27, 2022 |
| Lenovo        | YB1-X91F                    | Convertible | [0a0f43a4af](https://linux-hardware.org/?probe=0a0f43a4af) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [48cbc869da](https://linux-hardware.org/?probe=48cbc869da) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [ea31080862](https://linux-hardware.org/?probe=ea31080862) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | Notebook    | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | Notebook    | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [2d1c05fefc](https://linux-hardware.org/?probe=2d1c05fefc) | Jun 26, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [5047471b41](https://linux-hardware.org/?probe=5047471b41) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [874e7081c6](https://linux-hardware.org/?probe=874e7081c6) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [b91a1b0ded](https://linux-hardware.org/?probe=b91a1b0ded) | Jun 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | Notebook    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| Acer          | Aspire X1700                | Desktop     | [6a67f8cba0](https://linux-hardware.org/?probe=6a67f8cba0) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | Notebook    | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | Notebook    | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | Notebook    | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | 18E7                        | Desktop     | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [5f5c3fcba9](https://linux-hardware.org/?probe=5f5c3fcba9) | Jun 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [a5d23b52d1](https://linux-hardware.org/?probe=a5d23b52d1) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d22ca1b39a](https://linux-hardware.org/?probe=d22ca1b39a) | Jun 12, 2022 |
| HP            | 1496                        | Desktop     | [d6fba97175](https://linux-hardware.org/?probe=d6fba97175) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 460 20EMCT... | Convertible | [2e1daf6e92](https://linux-hardware.org/?probe=2e1daf6e92) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a3ca1ea153](https://linux-hardware.org/?probe=a3ca1ea153) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 708       | 14.66%  |
| Ubuntu 18.04      | 502       | 10.4%   |
| Debian 11         | 189       | 3.91%   |
| OpenMandriva 4.2  | 181       | 3.75%   |
| Ubuntu 22.04      | 164       | 3.4%    |
| OpenMandriva 4.3  | 113       | 2.34%   |
| KDE neon 20.04    | 111       | 2.3%    |
| Debian 10         | 81        | 1.68%   |
| Zorin 16          | 80        | 1.66%   |
| Manjaro           | 73        | 1.51%   |
| Ubuntu 20.10      | 72        | 1.49%   |
| Linux Mint 20.3   | 72        | 1.49%   |
| Linux Mint 19.3   | 70        | 1.45%   |
| Arch              | 65        | 1.35%   |
| Ubuntu 19.04      | 61        | 1.26%   |
| Xubuntu 20.04     | 60        | 1.24%   |
| Ubuntu 19.10      | 58        | 1.2%    |
| Linux Mint 20.1   | 57        | 1.18%   |
| Arch Rolling      | 57        | 1.18%   |
| Ubuntu 21.04      | 53        | 1.1%    |
| Fedora 36         | 53        | 1.1%    |
| Linux Mint 20     | 52        | 1.08%   |
| Ubuntu 21.10      | 50        | 1.04%   |
| Fedora 35         | 47        | 0.97%   |
| Xubuntu 18.04     | 46        | 0.95%   |
| Linux Mint 20.2   | 46        | 0.95%   |
| ROSA R10          | 43        | 0.89%   |
| Kubuntu 20.04     | 43        | 0.89%   |
| Fedora 34         | 40        | 0.83%   |
| Zorin 15          | 39        | 0.81%   |
| Fedora 33         | 38        | 0.79%   |
| Pop!_OS 20.04     | 37        | 0.77%   |
| Linux Mint 21     | 35        | 0.72%   |
| Ubuntu 18.10      | 33        | 0.68%   |
| Linux Mint 19.2   | 30        | 0.62%   |
| Ubuntu 16.04      | 29        | 0.6%    |
| Debian Testing    | 29        | 0.6%    |
| Ubuntu MATE 20.04 | 28        | 0.58%   |
| ROSA R11          | 28        | 0.58%   |
| Pop!_OS 22.04     | 27        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1665      | 36.29%  |
| Linux Mint    | 378       | 8.24%   |
| OpenMandriva  | 325       | 7.08%   |
| Debian        | 323       | 7.04%   |
| Fedora        | 228       | 4.97%   |
| Manjaro       | 177       | 3.86%   |
| KDE neon      | 129       | 2.81%   |
| Zorin         | 124       | 2.7%    |
| Endless       | 123       | 2.68%   |
| Xubuntu       | 120       | 2.62%   |
| Arch          | 120       | 2.62%   |
| Pop!_OS       | 111       | 2.42%   |
| ROSA          | 106       | 2.31%   |
| Kubuntu       | 94        | 2.05%   |
| Ubuntu MATE   | 54        | 1.18%   |
| Elementary    | 48        | 1.05%   |
| Gentoo        | 42        | 0.92%   |
| openSUSE      | 41        | 0.89%   |
| Ubuntu Unity  | 39        | 0.85%   |
| ArcoLinux     | 29        | 0.63%   |
| BlackPanther  | 28        | 0.61%   |
| Lubuntu       | 24        | 0.52%   |
| Kali          | 24        | 0.52%   |
| SteamOS       | 18        | 0.39%   |
| Parrot        | 18        | 0.39%   |
| LMDE          | 18        | 0.39%   |
| EndeavourOS   | 15        | 0.33%   |
| Clear Linux   | 15        | 0.33%   |
| MX            | 14        | 0.31%   |
| Ubuntu Budgie | 12        | 0.26%   |
| Reborn OS     | 8         | 0.17%   |
| Garuda Linux  | 8         | 0.17%   |
| CentOS        | 8         | 0.17%   |
| Nobara        | 6         | 0.13%   |
| Deepin        | 6         | 0.13%   |
| Solus         | 5         | 0.11%   |
| RHEL          | 5         | 0.11%   |
| Peppermint    | 5         | 0.11%   |
| Ubuntu Studio | 4         | 0.09%   |
| UbuntuDDE     | 3         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 3.37%   |
| 5.16.7-desktop-1omv4003         | 113       | 2.15%   |
| 5.4.0-42-generic                | 96        | 1.83%   |
| 5.4.0-58-generic                | 60        | 1.14%   |
| 5.10.0-8-amd64                  | 56        | 1.07%   |
| 5.4.0-52-generic                | 49        | 0.93%   |
| 5.4.0-54-generic                | 48        | 0.91%   |
| 5.4.0-26-generic                | 47        | 0.89%   |
| 5.15.0-52-generic               | 44        | 0.84%   |
| 5.15.0-56-generic               | 43        | 0.82%   |
| 5.3.0-28-generic                | 42        | 0.8%    |
| 5.4.0-48-generic                | 39        | 0.74%   |
| 5.3.0-40-generic                | 37        | 0.7%    |
| 5.11.0-27-generic               | 37        | 0.7%    |
| 5.0.0-37-generic                | 36        | 0.68%   |
| 5.4.0-29-generic                | 34        | 0.65%   |
| 5.4.0-65-generic                | 32        | 0.61%   |
| 5.3.0-46-generic                | 32        | 0.61%   |
| 5.11.0-43-generic               | 32        | 0.61%   |
| 5.13.0-30-generic               | 31        | 0.59%   |
| 5.0.0-32-generic                | 30        | 0.57%   |
| 5.4.0-72-generic                | 29        | 0.55%   |
| 5.4.0-40-generic                | 29        | 0.55%   |
| 5.15.0-48-generic               | 29        | 0.55%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.55%   |
| 5.4.0-47-generic                | 27        | 0.51%   |
| 5.4.0-37-generic                | 27        | 0.51%   |
| 5.3.0-51-generic                | 27        | 0.51%   |
| 5.10.0-18-amd64                 | 27        | 0.51%   |
| 5.13.0-39-generic               | 26        | 0.49%   |
| 5.13.0-28-generic               | 26        | 0.49%   |
| 5.11.0-41-generic               | 26        | 0.49%   |
| 5.8.0-43-generic                | 25        | 0.48%   |
| 5.15.0-53-generic               | 25        | 0.48%   |
| 5.8.0-44-generic                | 24        | 0.46%   |
| 5.11.0-37-generic               | 24        | 0.46%   |
| 5.4.0-70-generic                | 23        | 0.44%   |
| 5.3.0-45-generic                | 23        | 0.44%   |
| 5.15.0-50-generic               | 23        | 0.44%   |
| 5.15.0-47-generic               | 23        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 931       | 18.85%  |
| 4.15.0  | 414       | 8.38%   |
| 5.15.0  | 310       | 6.28%   |
| 5.11.0  | 275       | 5.57%   |
| 5.8.0   | 266       | 5.39%   |
| 5.3.0   | 254       | 5.14%   |
| 5.13.0  | 234       | 4.74%   |
| 5.10.0  | 224       | 4.54%   |
| 5.0.0   | 198       | 4.01%   |
| 5.10.14 | 179       | 3.62%   |
| 5.16.7  | 117       | 2.37%   |
| 4.18.0  | 113       | 2.29%   |
| 4.19.0  | 83        | 1.68%   |
| 5.19.0  | 36        | 0.73%   |
| 4.9.60  | 33        | 0.67%   |
| 4.4.0   | 22        | 0.45%   |
| 4.18.16 | 22        | 0.45%   |
| 6.0.0   | 19        | 0.38%   |
| 5.18.0  | 19        | 0.38%   |
| 5.14.0  | 18        | 0.36%   |
| 5.9.16  | 15        | 0.3%    |
| 5.17.5  | 15        | 0.3%    |
| 5.9.0   | 13        | 0.26%   |
| 5.7.0   | 12        | 0.24%   |
| 5.3.18  | 12        | 0.24%   |
| 5.12.4  | 12        | 0.24%   |
| 4.9.20  | 12        | 0.24%   |
| 5.16.11 | 11        | 0.22%   |
| 5.16.0  | 11        | 0.22%   |
| 5.15.6  | 11        | 0.22%   |
| 5.8.11  | 10        | 0.2%    |
| 5.6.0   | 10        | 0.2%    |
| 5.15.32 | 10        | 0.2%    |
| 5.13.12 | 10        | 0.2%    |
| 5.11.12 | 10        | 0.2%    |
| 6.0.8   | 9         | 0.18%   |
| 6.0.6   | 9         | 0.18%   |
| 5.17.1  | 9         | 0.18%   |
| 5.15.15 | 9         | 0.18%   |
| 5.14.14 | 9         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 994       | 20.36%  |
| 5.10    | 483       | 9.89%   |
| 5.15    | 420       | 8.6%    |
| 4.15    | 414       | 8.48%   |
| 5.11    | 332       | 6.8%    |
| 5.8     | 326       | 6.68%   |
| 5.3     | 282       | 5.78%   |
| 5.13    | 272       | 5.57%   |
| 5.0     | 202       | 4.14%   |
| 5.16    | 176       | 3.6%    |
| 4.18    | 136       | 2.79%   |
| 4.19    | 98        | 2.01%   |
| 5.19    | 92        | 1.88%   |
| 6.0     | 84        | 1.72%   |
| 4.9     | 79        | 1.62%   |
| 5.14    | 71        | 1.45%   |
| 5.18    | 64        | 1.31%   |
| 5.9     | 52        | 1.06%   |
| 5.6     | 51        | 1.04%   |
| 5.17    | 47        | 0.96%   |
| 5.7     | 45        | 0.92%   |
| 5.12    | 44        | 0.9%    |
| 5.5     | 26        | 0.53%   |
| 4.4     | 26        | 0.53%   |
| 4.1     | 9         | 0.18%   |
| 5.2     | 8         | 0.16%   |
| 5.1     | 7         | 0.14%   |
| 6.1     | 6         | 0.12%   |
| 4.16    | 6         | 0.12%   |
| 3.10    | 6         | 0.12%   |
| 4.20    | 4         | 0.08%   |
| 4.17    | 4         | 0.08%   |
| 4.13    | 4         | 0.08%   |
| 4.8     | 3         | 0.06%   |
| 4.14    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 4.12    | 2         | 0.04%   |
| 3.18    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4228      | 95.46%  |
| i686    | 171       | 3.86%   |
| aarch64 | 23        | 0.52%   |
| armv7l  | 6         | 0.14%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1988      | 42.63%  |
| KDE5             | 766       | 16.43%  |
| Unknown          | 623       | 13.36%  |
| XFCE             | 339       | 7.27%   |
| X-Cinnamon       | 291       | 6.24%   |
| KDE              | 157       | 3.37%   |
| MATE             | 147       | 3.15%   |
| KDE4             | 47        | 1.01%   |
| Cinnamon         | 46        | 0.99%   |
| Pantheon         | 44        | 0.94%   |
| Unity            | 38        | 0.81%   |
| LXQt             | 37        | 0.79%   |
| i3               | 27        | 0.58%   |
| Budgie           | 21        | 0.45%   |
| LXDE             | 19        | 0.41%   |
| Deepin           | 19        | 0.41%   |
| GNOME Flashback  | 13        | 0.28%   |
| openbox          | 8         | 0.17%   |
| GNOME Classic    | 6         | 0.13%   |
| bspwm            | 5         | 0.11%   |
| qtile            | 4         | 0.09%   |
| Enlightenment    | 3         | 0.06%   |
| DWM              | 3         | 0.06%   |
| xmonad           | 2         | 0.04%   |
| Trinity          | 2         | 0.04%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| ICEWM            | 1         | 0.02%   |
| i3-with-shmlog   | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3634      | 79.76%  |
| Wayland | 524       | 11.5%   |
| Unknown | 332       | 7.29%   |
| Tty     | 66        | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2521      | 54.84%  |
| SDDM    | 672       | 14.62%  |
| GDM     | 517       | 11.25%  |
| GDM3    | 341       | 7.42%   |
| LightDM | 323       | 7.03%   |
| TDM     | 150       | 3.26%   |
| KDM     | 48        | 1.04%   |
| XDM     | 13        | 0.28%   |
| Ly      | 5         | 0.11%   |
| LXDM    | 4         | 0.09%   |
| SLiM    | 3         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 2638      | 57.86%  |
| en_US          | 747       | 16.39%  |
| Unknown        | 633       | 13.88%  |
| ca_ES          | 164       | 3.6%    |
| en_GB          | 93        | 2.04%   |
| C              | 42        | 0.92%   |
| gl_ES          | 32        | 0.7%    |
| de_DE          | 29        | 0.64%   |
| eu_ES          | 22        | 0.48%   |
| fr_FR          | 18        | 0.39%   |
| ru_RU          | 16        | 0.35%   |
| it_IT          | 13        | 0.29%   |
| an_ES          | 11        | 0.24%   |
| es_MX          | 9         | 0.2%    |
| es_AR          | 8         | 0.18%   |
| pt_BR          | 6         | 0.13%   |
| en_IE          | 6         | 0.13%   |
| ca_AD          | 6         | 0.13%   |
| C.UTF8         | 5         | 0.11%   |
| ro_RO          | 4         | 0.09%   |
| pl_PL          | 4         | 0.09%   |
| en_AG          | 4         | 0.09%   |
| ca_ES@valencia | 4         | 0.09%   |
| pt_PT          | 3         | 0.07%   |
| nl_NL          | 3         | 0.07%   |
| fr_BE          | 3         | 0.07%   |
| es_ES.UTF8     | 3         | 0.07%   |
| POSIX          | 2         | 0.04%   |
| fr_CH          | 2         | 0.04%   |
| es_US          | 2         | 0.04%   |
| es_BO          | 2         | 0.04%   |
| en_DK          | 2         | 0.04%   |
| en_AU          | 2         | 0.04%   |
| de_AT          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |
| et_EE          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2361      | 52.17%  |
| EFI  | 2165      | 47.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3527      | 77.84%  |
| Overlay  | 365       | 8.06%   |
| Btrfs    | 283       | 6.25%   |
| Unknown  | 212       | 4.68%   |
| Xfs      | 58        | 1.28%   |
| Ext3     | 33        | 0.73%   |
| Zfs      | 21        | 0.46%   |
| Ext2     | 16        | 0.35%   |
| Tmpfs    | 7         | 0.15%   |
| Reiserfs | 4         | 0.09%   |
| Jfs      | 2         | 0.04%   |
| Aufs     | 2         | 0.04%   |
| F2fs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2717      | 59.95%  |
| GPT     | 1348      | 29.74%  |
| MBR     | 467       | 10.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3806      | 84.11%  |
| Yes       | 719       | 15.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3013      | 66.75%  |
| Yes       | 1501      | 33.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 858       | 19.38%  |
| Hewlett-Packard         | 635       | 14.34%  |
| Lenovo                  | 530       | 11.97%  |
| MSI                     | 378       | 8.54%   |
| Gigabyte Technology     | 367       | 8.29%   |
| Acer                    | 297       | 6.71%   |
| Dell                    | 279       | 6.3%    |
| ASRock                  | 113       | 2.55%   |
| Toshiba                 | 104       | 2.35%   |
| Apple                   | 102       | 2.3%    |
| Intel                   | 65        | 1.47%   |
| Unknown                 | 60        | 1.36%   |
| Packard Bell            | 43        | 0.97%   |
| Sony                    | 36        | 0.81%   |
| Medion                  | 36        | 0.81%   |
| HUAWEI                  | 33        | 0.75%   |
| Chuwi                   | 31        | 0.7%    |
| Samsung Electronics     | 27        | 0.61%   |
| Notebook                | 25        | 0.56%   |
| SLIMBOOK                | 24        | 0.54%   |
| LG Electronics          | 21        | 0.47%   |
| Fujitsu                 | 20        | 0.45%   |
| Raspberry Pi Foundation | 19        | 0.43%   |
| Pegatron                | 17        | 0.38%   |
| eMachines               | 17        | 0.38%   |
| ECS                     | 16        | 0.36%   |
| Valve                   | 14        | 0.32%   |
| Teclast                 | 13        | 0.29%   |
| Timi                    | 12        | 0.27%   |
| Fujitsu Siemens         | 12        | 0.27%   |
| Foxconn                 | 12        | 0.27%   |
| BESSTAR Tech            | 12        | 0.27%   |
| Huanan                  | 10        | 0.23%   |
| AMI                     | 10        | 0.23%   |
| Supermicro              | 7         | 0.16%   |
| Clevo                   | 7         | 0.16%   |
| AZW                     | 7         | 0.16%   |
| Shuttle                 | 6         | 0.14%   |
| Microsoft               | 6         | 0.14%   |
| IBM                     | 6         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 85        | 1.92%   |
| ASUS All Series                            | 51        | 1.15%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.5%    |
| HP Pavilion g6                             | 20        | 0.45%   |
| HP Pavilion dv6                            | 19        | 0.43%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.41%   |
| HP Notebook                                | 17        | 0.38%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.34%   |
| Valve Jupiter                              | 14        | 0.32%   |
| MSI MS-7C37                                | 11        | 0.25%   |
| HP G62                                     | 11        | 0.25%   |
| RPi Raspberry Pi                           | 10        | 0.23%   |
| MSI MS-7817                                | 10        | 0.23%   |
| HP Laptop 15-da0xxx                        | 10        | 0.23%   |
| Gigabyte B450M DS3H                        | 10        | 0.23%   |
| Gigabyte 970A-DS3P                         | 10        | 0.23%   |
| Dell XPS 13 7390                           | 10        | 0.23%   |
| ASUS P5G41T-M LX                           | 10        | 0.23%   |
| HP Pavilion 15                             | 9         | 0.2%    |
| HP Laptop 15s-eq1xxx                       | 9         | 0.2%    |
| MSI Prestige 15 A11SCS                     | 8         | 0.18%   |
| MSI MS-7B79                                | 8         | 0.18%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.18%   |
| Gigabyte H110M-S2H                         | 8         | 0.18%   |
| Gigabyte B450 AORUS M                      | 8         | 0.18%   |
| ASUS X555LAB                               | 8         | 0.18%   |
| ASUS X540NA                                | 8         | 0.18%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.18%   |
| ASUS PRIME B450M-A                         | 8         | 0.18%   |
| ASUS PRIME A320M-K                         | 8         | 0.18%   |
| MSI MS-7C02                                | 7         | 0.16%   |
| MSI MS-7B86                                | 7         | 0.16%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.16%   |
| Lenovo G50-70 20351                        | 7         | 0.16%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.16%   |
| HP Pavilion dv7                            | 7         | 0.16%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.16%   |
| HP Laptop 15-bw0xx                         | 7         | 0.16%   |
| Gigabyte H61M-DS2                          | 7         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 215       | 4.86%   |
| Lenovo ThinkPad       | 168       | 3.79%   |
| HP Pavilion           | 137       | 3.09%   |
| Lenovo IdeaPad        | 127       | 2.87%   |
| HP Compaq             | 85        | 1.92%   |
| Unknown               | 85        | 1.92%   |
| Dell Latitude         | 83        | 1.87%   |
| Toshiba Satellite     | 80        | 1.81%   |
| ASUS PRIME            | 73        | 1.65%   |
| ASUS VivoBook         | 71        | 1.6%    |
| HP Laptop             | 67        | 1.51%   |
| HP EliteBook          | 60        | 1.36%   |
| ASUS ROG              | 58        | 1.31%   |
| Dell XPS              | 56        | 1.26%   |
| ASUS TUF              | 56        | 1.26%   |
| ASUS All              | 51        | 1.15%   |
| Lenovo ThinkCentre    | 50        | 1.13%   |
| Dell OptiPlex         | 44        | 0.99%   |
| HP ProBook            | 39        | 0.88%   |
| Dell Inspiron         | 37        | 0.84%   |
| ASUS ZenBook          | 34        | 0.77%   |
| Packard Bell EasyNote | 31        | 0.7%    |
| HP 250                | 30        | 0.68%   |
| MSI Prestige          | 24        | 0.54%   |
| Lenovo Yoga           | 24        | 0.54%   |
| Lenovo Legion         | 21        | 0.47%   |
| Gigabyte X570         | 21        | 0.47%   |
| HP OMEN               | 20        | 0.45%   |
| Dell Precision        | 20        | 0.45%   |
| RPi Raspberry         | 19        | 0.43%   |
| MSI Modern            | 19        | 0.43%   |
| HP ENVY               | 18        | 0.41%   |
| Acer Extensa          | 18        | 0.41%   |
| Lenovo ThinkBook      | 17        | 0.38%   |
| HP Notebook           | 17        | 0.38%   |
| ASUS ASUS             | 17        | 0.38%   |
| Gigabyte B450M        | 16        | 0.36%   |
| Acer TravelMate       | 16        | 0.36%   |
| Gigabyte B450         | 15        | 0.34%   |
| Valve Jupiter         | 14        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 465       | 10.5%   |
| 2019    | 426       | 9.62%   |
| 2020    | 368       | 8.31%   |
| 2014    | 312       | 7.05%   |
| 2013    | 279       | 6.3%    |
| 2017    | 275       | 6.21%   |
| 2012    | 274       | 6.19%   |
| 2011    | 263       | 5.94%   |
| 2015    | 258       | 5.83%   |
| 2021    | 252       | 5.69%   |
| 2010    | 244       | 5.51%   |
| 2009    | 217       | 4.9%    |
| 2008    | 215       | 4.86%   |
| 2016    | 209       | 4.72%   |
| 2007    | 152       | 3.43%   |
| 2006    | 81        | 1.83%   |
| 2022    | 72        | 1.63%   |
| Unknown | 29        | 0.66%   |
| 2005    | 22        | 0.5%    |
| 2004    | 7         | 0.16%   |
| 2003    | 3         | 0.07%   |
| 2002    | 2         | 0.05%   |
| 2001    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2461      | 55.59%  |
| Desktop        | 1673      | 37.79%  |
| All in one     | 76        | 1.72%   |
| Convertible    | 64        | 1.45%   |
| Mini pc        | 60        | 1.36%   |
| Tablet         | 38        | 0.86%   |
| System on chip | 26        | 0.59%   |
| Server         | 25        | 0.56%   |
| Phone          | 3         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4160      | 93.4%   |
| Enabled  | 294       | 6.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4422      | 99.89%  |
| Yes  | 5         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 987       | 21.95%  |
| 3.01-4.0        | 962       | 21.39%  |
| 16.01-24.0      | 917       | 20.39%  |
| 8.01-16.0       | 821       | 18.26%  |
| 32.01-64.0      | 359       | 7.98%   |
| 1.01-2.0        | 215       | 4.78%   |
| 2.01-3.0        | 74        | 1.65%   |
| 64.01-256.0     | 59        | 1.31%   |
| 0.51-1.0        | 56        | 1.25%   |
| 24.01-32.0      | 40        | 0.89%   |
| More than 256.0 | 4         | 0.09%   |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1935      | 39.52%  |
| 2.01-3.0   | 1228      | 25.08%  |
| 4.01-8.0   | 595       | 12.15%  |
| 3.01-4.0   | 519       | 10.6%   |
| 0.51-1.0   | 392       | 8.01%   |
| 8.01-16.0  | 154       | 3.15%   |
| 0.01-0.5   | 56        | 1.14%   |
| 24.01-32.0 | 8         | 0.16%   |
| 16.01-24.0 | 7         | 0.14%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2741      | 59.94%  |
| 2       | 1128      | 24.67%  |
| 3       | 376       | 8.22%   |
| 4       | 159       | 3.48%   |
| 5       | 66        | 1.44%   |
| 0       | 40        | 0.87%   |
| 6       | 30        | 0.66%   |
| 7       | 13        | 0.28%   |
| 9       | 6         | 0.13%   |
| 8       | 6         | 0.13%   |
| 11      | 2         | 0.04%   |
| 10      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2622      | 58.7%   |
| Yes       | 1845      | 41.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3843      | 86.52%  |
| No        | 599       | 13.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3313      | 74.23%  |
| No        | 1150      | 25.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2511      | 56.02%  |
| No        | 1971      | 43.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 4427      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 720       | 14.94%  |
| Barcelona                  | 486       | 10.09%  |
| Seville                    | 165       | 3.42%   |
| Valencia                   | 164       | 3.4%    |
| Zaragoza                   | 71        | 1.47%   |
| Málaga                    | 68        | 1.41%   |
| Granada                    | 60        | 1.25%   |
| Sabadell                   | 47        | 0.98%   |
| Palma                      | 47        | 0.98%   |
| Valladolid                 | 45        | 0.93%   |
| Alcobendas                 | 44        | 0.91%   |
| Vigo                       | 43        | 0.89%   |
| Las Palmas de Gran Canaria | 43        | 0.89%   |
| Bilbao                     | 43        | 0.89%   |
| Córdoba                   | 38        | 0.79%   |
| Ourense                    | 37        | 0.77%   |
| Murcia                     | 35        | 0.73%   |
| Pamplona                   | 33        | 0.68%   |
| Alicante                   | 30        | 0.62%   |
| Donostia / San Sebastian   | 29        | 0.6%    |
| Alcalá de Henares         | 29        | 0.6%    |
| Oviedo                     | 28        | 0.58%   |
| Gijón                     | 27        | 0.56%   |
| A Coruña                  | 27        | 0.56%   |
| Santa Cruz de Tenerife     | 26        | 0.54%   |
| Almería                   | 25        | 0.52%   |
| Santiago de Compostela     | 24        | 0.5%    |
| León                      | 24        | 0.5%    |
| Mostoles                   | 23        | 0.48%   |
| Barakaldo                  | 23        | 0.48%   |
| Vitoria-Gasteiz            | 21        | 0.44%   |
| Burgos                     | 21        | 0.44%   |
| Albacete                   | 21        | 0.44%   |
| Salamanca                  | 20        | 0.42%   |
| Santander                  | 19        | 0.39%   |
| Getxo                      | 19        | 0.39%   |
| Terrassa                   | 18        | 0.37%   |
| Cartagena                  | 18        | 0.37%   |
| Reus                       | 17        | 0.35%   |
| Pontevedra                 | 17        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1118      | 1712   | 17.34%  |
| WDC                         | 921       | 1339   | 14.29%  |
| Samsung Electronics         | 844       | 1201   | 13.09%  |
| Kingston                    | 724       | 993    | 11.23%  |
| Toshiba                     | 486       | 719    | 7.54%   |
| SanDisk                     | 350       | 465    | 5.43%   |
| Unknown                     | 245       | 311    | 3.8%    |
| Crucial                     | 233       | 324    | 3.61%   |
| Hitachi                     | 204       | 244    | 3.16%   |
| SK hynix                    | 154       | 197    | 2.39%   |
| Intel                       | 135       | 175    | 2.09%   |
| HGST                        | 116       | 148    | 1.8%    |
| Micron Technology           | 95        | 110    | 1.47%   |
| China                       | 57        | 75     | 0.88%   |
| Phison                      | 49        | 55     | 0.76%   |
| Fujitsu                     | 43        | 49     | 0.67%   |
| Maxtor                      | 36        | 47     | 0.56%   |
| KIOXIA                      | 36        | 43     | 0.56%   |
| Apple                       | 34        | 48     | 0.53%   |
| OCZ                         | 29        | 37     | 0.45%   |
| Micron/Crucial Technology   | 29        | 37     | 0.45%   |
| Silicon Motion              | 23        | 29     | 0.36%   |
| Netac                       | 21        | 29     | 0.33%   |
| JMicron Technology          | 21        | 23     | 0.33%   |
| Transcend                   | 19        | 39     | 0.29%   |
| LITEON                      | 19        | 20     | 0.29%   |
| Corsair                     | 19        | 24     | 0.29%   |
| A-DATA Technology           | 19        | 24     | 0.29%   |
| KingSpec                    | 18        | 24     | 0.28%   |
| Unknown                     | 17        | 19     | 0.26%   |
| KingDian                    | 16        | 19     | 0.25%   |
| PNY                         | 15        | 22     | 0.23%   |
| KIOXIA-EXCERIA              | 15        | 21     | 0.23%   |
| USB30                       | 14        | 28     | 0.22%   |
| Emtec                       | 12        | 14     | 0.19%   |
| Patriot                     | 11        | 18     | 0.17%   |
| Kingston Technology Company | 10        | 12     | 0.16%   |
| Intenso                     | 9         | 11     | 0.14%   |
| FORESEE                     | 9         | 10     | 0.14%   |
| Drevo                       | 9         | 12     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 240       | 3.39%   |
| Kingston SA400S37480G 480GB SSD        | 98        | 1.39%   |
| Seagate ST1000DM010-2EP102 1TB         | 84        | 1.19%   |
| Kingston SA400S37120G 120GB SSD        | 76        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB        | 70        | 0.99%   |
| Kingston SV300S37A120G 120GB SSD       | 66        | 0.93%   |
| Seagate ST3500418AS 500GB              | 58        | 0.82%   |
| Samsung SSD 860 EVO 500GB              | 55        | 0.78%   |
| Unknown MMC Card  64GB                 | 52        | 0.73%   |
| Unknown MMC Card  32GB                 | 45        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB         | 44        | 0.62%   |
| Crucial CT500MX500SSD1 500GB           | 44        | 0.62%   |
| Seagate ST500LT012-1DG142 500GB        | 42        | 0.59%   |
| Toshiba DT01ACA100 1TB                 | 41        | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB         | 41        | 0.58%   |
| Samsung SSD 850 EVO 500GB              | 41        | 0.58%   |
| Samsung SSD 850 EVO 250GB              | 41        | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB         | 40        | 0.57%   |
| Toshiba MQ01ABD100 1TB                 | 39        | 0.55%   |
| Kingston SUV400S37240G 240GB SSD       | 38        | 0.54%   |
| Seagate ST9500325AS 500GB              | 37        | 0.52%   |
| SanDisk SSD PLUS 480GB                 | 36        | 0.51%   |
| Samsung NVMe SSD Drive 512GB           | 36        | 0.51%   |
| Samsung NVMe SSD Drive 500GB           | 36        | 0.51%   |
| HGST HTS721010A9E630 1TB               | 36        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 34        | 0.48%   |
| Toshiba MQ01ABF050 500GB               | 33        | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB         | 32        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB           | 32        | 0.45%   |
| Kingston SV300S37A240G 240GB SSD       | 32        | 0.45%   |
| Seagate ST31000528AS 1TB               | 30        | 0.42%   |
| Intel NVMe SSD Drive 512GB             | 30        | 0.42%   |
| Toshiba MQ04ABF100 1TB                 | 28        | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 28        | 0.4%    |
| Unknown SD/MMC/MS PRO 64GB             | 27        | 0.38%   |
| Toshiba MQ01ABD050 500GB               | 27        | 0.38%   |
| WDC WD20EARX-00PASB0 2TB               | 26        | 0.37%   |
| Toshiba TR200 240GB SSD                | 26        | 0.37%   |
| Seagate Expansion 4TB                  | 26        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1107      | 1696   | 40.14%  |
| WDC                 | 724       | 1047   | 26.25%  |
| Toshiba             | 350       | 483    | 12.69%  |
| Hitachi             | 204       | 244    | 7.4%    |
| HGST                | 116       | 148    | 4.21%   |
| Samsung Electronics | 110       | 137    | 3.99%   |
| Fujitsu             | 42        | 48     | 1.52%   |
| Maxtor              | 31        | 41     | 1.12%   |
| Unknown             | 27        | 32     | 0.98%   |
| Apple               | 14        | 18     | 0.51%   |
| ASMT                | 8         | 12     | 0.29%   |
| USB3.0              | 6         | 6      | 0.22%   |
| Hewlett-Packard     | 3         | 4      | 0.11%   |
| USB                 | 2         | 2      | 0.07%   |
| Quantum             | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| OEM                 | 1         | 1      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| Intenso             | 1         | 1      | 0.04%   |
| Inateck             | 1         | 1      | 0.04%   |
| IBM-207x            | 1         | 8      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Generic-            | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 665       | 910    | 30.25%  |
| Samsung Electronics | 388       | 530    | 17.65%  |
| SanDisk             | 215       | 268    | 9.78%   |
| Crucial             | 210       | 292    | 9.55%   |
| WDC                 | 114       | 159    | 5.19%   |
| Toshiba             | 90        | 161    | 4.09%   |
| China               | 55        | 73     | 2.5%    |
| SK hynix            | 36        | 40     | 1.64%   |
| Micron Technology   | 32        | 39     | 1.46%   |
| Intel               | 32        | 48     | 1.46%   |
| OCZ                 | 29        | 37     | 1.32%   |
| Netac               | 21        | 29     | 0.96%   |
| Transcend           | 18        | 38     | 0.82%   |
| LITEON              | 18        | 18     | 0.82%   |
| KingSpec            | 18        | 24     | 0.82%   |
| A-DATA Technology   | 16        | 21     | 0.73%   |
| KingDian            | 15        | 18     | 0.68%   |
| USB30               | 14        | 28     | 0.64%   |
| JMicron Technology  | 14        | 15     | 0.64%   |
| Apple               | 14        | 17     | 0.64%   |
| PNY                 | 10        | 17     | 0.45%   |
| Patriot             | 10        | 17     | 0.45%   |
| KIOXIA-EXCERIA      | 10        | 14     | 0.45%   |
| Emtec               | 10        | 12     | 0.45%   |
| FORESEE             | 9         | 10     | 0.41%   |
| Unknown             | 9         | 9      | 0.41%   |
| Teclast             | 8         | 8      | 0.36%   |
| Corsair             | 8         | 11     | 0.36%   |
| Intenso             | 7         | 8      | 0.32%   |
| GOODRAM             | 6         | 8      | 0.27%   |
| Drevo               | 6         | 8      | 0.27%   |
| Maxtor              | 5         | 6      | 0.23%   |
| LITEONIT            | 5         | 6      | 0.23%   |
| BAITITON            | 5         | 5      | 0.23%   |
| Hoodisk             | 4         | 5      | 0.18%   |
| Dogfish             | 4         | 4      | 0.18%   |
| Unknown             | 3         | 3      | 0.14%   |
| TCSUNBOW            | 3         | 3      | 0.14%   |
| SPCC                | 3         | 3      | 0.14%   |
| Plextor             | 3         | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2350      | 3939   | 40.94%  |
| SSD     | 1896      | 2998   | 33.03%  |
| NVMe    | 1201      | 1669   | 20.92%  |
| MMC     | 222       | 291    | 3.87%   |
| Unknown | 71        | 89     | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3397      | 6758   | 67.59%  |
| NVMe | 1198      | 1663   | 23.84%  |
| MMC  | 222       | 291    | 4.42%   |
| SAS  | 209       | 274    | 4.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2722      | 4450   | 62.35%  |
| 0.51-1.0   | 1148      | 1665   | 26.29%  |
| 1.01-2.0   | 293       | 478    | 6.71%   |
| 3.01-4.0   | 95        | 145    | 2.18%   |
| 2.01-3.0   | 72        | 112    | 1.65%   |
| 4.01-10.0  | 35        | 86     | 0.8%    |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1331      | 28.36%  |
| 251-500        | 1103      | 23.5%   |
| 501-1000       | 615       | 13.1%   |
| 1-20           | 350       | 7.46%   |
| 51-100         | 325       | 6.93%   |
| 1001-2000      | 316       | 6.73%   |
| 21-50          | 203       | 4.33%   |
| More than 3000 | 175       | 3.73%   |
| 2001-3000      | 160       | 3.41%   |
| Unknown        | 115       | 2.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1915      | 39.21%  |
| 21-50          | 840       | 17.2%   |
| 101-250        | 628       | 12.86%  |
| 51-100         | 505       | 10.34%  |
| 251-500        | 363       | 7.43%   |
| 501-1000       | 252       | 5.16%   |
| 1001-2000      | 147       | 3.01%   |
| Unknown        | 115       | 2.35%   |
| More than 3000 | 65        | 1.33%   |
| 2001-3000      | 52        | 1.06%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 11        | 11     | 2.74%   |
| Kingston SV300S37A120G 120GB SSD   | 11        | 13     | 2.74%   |
| Seagate ST3500418AS 500GB          | 10        | 16     | 2.49%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 1.99%   |
| Seagate ST500LT012-1DG142 500GB    | 7         | 7      | 1.74%   |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 7      | 1.49%   |
| SanDisk SSD PLUS 480GB             | 6         | 7      | 1.49%   |
| HGST HTS545050A7E680 500GB         | 5         | 7      | 1.24%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 6      | 1%      |
| Seagate ST9500420AS 500GB          | 4         | 4      | 1%      |
| Seagate ST9250827AS 250GB          | 4         | 4      | 1%      |
| Seagate ST3500320AS 500GB          | 4         | 7      | 1%      |
| Seagate ST31000528AS 1TB           | 4         | 5      | 1%      |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 7      | 1%      |
| Drevo X1 SSD 120GB                 | 4         | 6      | 1%      |
| WDC WD5000BEVT-22ZAT0 500GB        | 3         | 3      | 0.75%   |
| WDC WD20EZRX-00DC0B0 2TB           | 3         | 3      | 0.75%   |
| WDC WD20EARX-00PASB0 2TB           | 3         | 4      | 0.75%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 0.75%   |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.75%   |
| Seagate ST31500341AS 1TB           | 3         | 3      | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 3      | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB     | 3         | 4      | 0.75%   |
| Samsung Electronics HD501LJ 500GB  | 3         | 3      | 0.75%   |
| Kingston SUV400S37240G 240GB SSD   | 3         | 4      | 0.75%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.75%   |
| HGST HTS721010A9E630 1TB           | 3         | 3      | 0.75%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.75%   |
| Fujitsu MHZ2250BH G2 250GB         | 3         | 4      | 0.75%   |
| WDC WD6400AAKS-22A7B0 640GB        | 2         | 2      | 0.5%    |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 0.5%    |
| WDC WD5000AAKS-402AA0 500GB        | 2         | 2      | 0.5%    |
| WDC WD40EZRX-00SPEB0 4TB           | 2         | 3      | 0.5%    |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 2      | 0.5%    |
| WDC WD2500AAJS-00B4A0 250GB        | 2         | 2      | 0.5%    |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 5      | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB            | 2         | 2      | 0.5%    |
| Toshiba Q300. 240GB SSD            | 2         | 2      | 0.5%    |
| Toshiba MQ01ABD075 752GB           | 2         | 3      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 134       | 172    | 34.1%   |
| WDC                 | 72        | 89     | 18.32%  |
| Samsung Electronics | 27        | 28     | 6.87%   |
| Hitachi             | 27        | 29     | 6.87%   |
| Toshiba             | 26        | 28     | 6.62%   |
| Kingston            | 21        | 27     | 5.34%   |
| HGST                | 17        | 20     | 4.33%   |
| SanDisk             | 11        | 12     | 2.8%    |
| Intel               | 9         | 9      | 2.29%   |
| Maxtor              | 8         | 8      | 2.04%   |
| Crucial             | 7         | 8      | 1.78%   |
| Fujitsu             | 6         | 7      | 1.53%   |
| Drevo               | 5         | 7      | 1.27%   |
| OCZ                 | 3         | 3      | 0.76%   |
| Micron Technology   | 3         | 3      | 0.76%   |
| China               | 3         | 4      | 0.76%   |
| SK hynix            | 2         | 2      | 0.51%   |
| KingDian            | 2         | 2      | 0.51%   |
| Transcend           | 1         | 4      | 0.25%   |
| Patriot             | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |
| IBM                 | 1         | 1      | 0.25%   |
| Hypertec            | 1         | 1      | 0.25%   |
| Dogfish             | 1         | 1      | 0.25%   |
| ASMT                | 1         | 2      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |
| A-DATA Technology   | 1         | 1      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 134       | 172    | 44.22%  |
| WDC                 | 70        | 87     | 23.1%   |
| Hitachi             | 27        | 29     | 8.91%   |
| Toshiba             | 21        | 23     | 6.93%   |
| HGST                | 17        | 20     | 5.61%   |
| Samsung Electronics | 16        | 17     | 5.28%   |
| Maxtor              | 8         | 8      | 2.64%   |
| Fujitsu             | 6         | 7      | 1.98%   |
| IBM                 | 1         | 1      | 0.33%   |
| China               | 1         | 1      | 0.33%   |
| ASMT                | 1         | 2      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 283       | 368    | 76.9%   |
| SSD  | 79        | 98     | 21.47%  |
| NVMe | 6         | 6      | 1.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 8.33%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 8.33%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 8.33%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 8.33%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 8.33%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 8.33%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| Samsung Electronics | 3         | 3      | 25%     |
| WDC                 | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2884      | 5738   | 60.15%  |
| Works    | 1545      | 2764   | 32.22%  |
| Malfunc  | 354       | 472    | 7.38%   |
| Failed   | 12        | 12     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3025      | 56.32%  |
| AMD                              | 763       | 14.21%  |
| Samsung Electronics              | 405       | 7.54%   |
| SanDisk                          | 234       | 4.36%   |
| SK hynix                         | 109       | 2.03%   |
| Nvidia                           | 103       | 1.92%   |
| Phison Electronics               | 80        | 1.49%   |
| Kingston Technology Company      | 77        | 1.43%   |
| JMicron Technology               | 76        | 1.42%   |
| ASMedia Technology               | 74        | 1.38%   |
| Micron Technology                | 65        | 1.21%   |
| Marvell Technology Group         | 58        | 1.08%   |
| Toshiba America Info Systems     | 51        | 0.95%   |
| Micron/Crucial Technology        | 48        | 0.89%   |
| KIOXIA                           | 48        | 0.89%   |
| VIA Technologies                 | 31        | 0.58%   |
| Silicon Motion                   | 30        | 0.56%   |
| Silicon Integrated Systems [SiS] | 20        | 0.37%   |
| LSI Logic / Symbios Logic        | 13        | 0.24%   |
| Union Memory (Shenzhen)          | 7         | 0.13%   |
| Hewlett-Packard                  | 6         | 0.11%   |
| Silicon Image                    | 5         | 0.09%   |
| Apple                            | 5         | 0.09%   |
| Realtek Semiconductor            | 4         | 0.07%   |
| ADATA Technology                 | 4         | 0.07%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| Lite-On Technology               | 3         | 0.06%   |
| Broadcom / LSI                   | 3         | 0.06%   |
| Adaptec                          | 3         | 0.06%   |
| Seagate Technology               | 2         | 0.04%   |
| O2 Micro                         | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| ULi Electronics                  | 1         | 0.02%   |
| Swissbit                         | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 533       | 8.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 239       | 3.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 226       | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 222       | 3.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 134       | 2.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 133       | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 122       | 1.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 120       | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 116       | 1.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 115       | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                         | 114       | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 111       | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 92        | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 87        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 87        | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 86        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 81        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 81        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 79        | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 79        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 78        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 77        | 1.22%   |
| Samsung NVMe SSD Controller 980                                                | 76        | 1.2%    |
| Intel SATA Controller [RAID mode]                                              | 75        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 75        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 73        | 1.15%   |
| Micron Non-Volatile memory controller                                          | 65        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 65        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 65        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 62        | 0.98%   |
| Intel SSD 660P Series                                                          | 61        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 56        | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 54        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 53        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 52        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 50        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 48        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 45        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 45        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 43        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3160      | 57.5%   |
| NVMe | 1212      | 22.05%  |
| IDE  | 773       | 14.06%  |
| RAID | 335       | 6.1%    |
| SCSI | 9         | 0.16%   |
| SAS  | 7         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3439      | 77.68%  |
| AMD          | 957       | 21.62%  |
| ARM          | 28        | 0.63%   |
| QUALCOMM     | 2         | 0.05%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 59        | 1.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 54        | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 47        | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 37        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 37        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 35        | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 33        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 33        | 0.74%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 32        | 0.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor             | 31        | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.59%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 26        | 0.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 26        | 0.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 25        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.52%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 23        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 22        | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 21        | 0.47%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 21        | 0.47%   |
| ARM Processor                                 | 21        | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 20        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 18        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.41%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.41%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.41%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 18        | 0.41%   |
| AMD FX-8350 Eight-Core Processor              | 18        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 859       | 19.36%  |
| Intel Core i7           | 843       | 19%     |
| Intel Core i3           | 357       | 8.04%   |
| Intel Celeron           | 272       | 6.13%   |
| Other                   | 265       | 5.97%   |
| AMD Ryzen 5             | 227       | 5.11%   |
| Intel Core 2 Duo        | 226       | 5.09%   |
| AMD Ryzen 7             | 200       | 4.51%   |
| Intel Atom              | 128       | 2.88%   |
| Intel Xeon              | 92        | 2.07%   |
| Intel Pentium           | 80        | 1.8%    |
| Intel Pentium Dual-Core | 73        | 1.64%   |
| Intel Core 2 Quad       | 69        | 1.55%   |
| AMD FX                  | 59        | 1.33%   |
| Intel Pentium Dual      | 51        | 1.15%   |
| Intel Core 2            | 48        | 1.08%   |
| AMD A4                  | 43        | 0.97%   |
| AMD Ryzen 9             | 37        | 0.83%   |
| AMD Ryzen 3             | 36        | 0.81%   |
| AMD A6                  | 35        | 0.79%   |
| Intel Genuine           | 32        | 0.72%   |
| AMD A10                 | 31        | 0.7%    |
| AMD A8                  | 27        | 0.61%   |
| Intel Core i9           | 26        | 0.59%   |
| Intel Pentium 4         | 25        | 0.56%   |
| AMD Athlon 64 X2        | 24        | 0.54%   |
| AMD E1                  | 20        | 0.45%   |
| AMD Athlon II X2        | 20        | 0.45%   |
| AMD Athlon              | 19        | 0.43%   |
| AMD Phenom II X4        | 14        | 0.32%   |
| AMD Ryzen 7 PRO         | 11        | 0.25%   |
| AMD E                   | 11        | 0.25%   |
| Intel Pentium D         | 10        | 0.23%   |
| AMD Phenom              | 10        | 0.23%   |
| Intel Pentium M         | 9         | 0.2%    |
| Intel Pentium Silver    | 8         | 0.18%   |
| Intel Pentium Gold      | 7         | 0.16%   |
| Intel Core m3           | 7         | 0.16%   |
| Intel Celeron M         | 7         | 0.16%   |
| AMD Sempron             | 7         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1858      | 41.82%  |
| 4       | 1575      | 35.45%  |
| 6       | 401       | 9.03%   |
| 8       | 297       | 6.68%   |
| 1       | 171       | 3.85%   |
| 12      | 48        | 1.08%   |
| 3       | 20        | 0.45%   |
| 10      | 19        | 0.43%   |
| 16      | 17        | 0.38%   |
| 14      | 16        | 0.36%   |
| Unknown | 13        | 0.29%   |
| 20      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 32      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4392      | 99.19%  |
| 2       | 33        | 0.75%   |
| Unknown | 3         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2744      | 61.82%  |
| 1       | 1682      | 37.89%  |
| Unknown | 13        | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4242      | 95.22%  |
| Unknown        | 113       | 2.54%   |
| 32-bit         | 66        | 1.48%   |
| 64-bit         | 34        | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 875       | 19.08%  |
| 0x306c3    | 245       | 5.34%   |
| 0x206a7    | 220       | 4.8%    |
| 0x306a9    | 199       | 4.34%   |
| 0x1067a    | 169       | 3.69%   |
| 0x906ea    | 137       | 2.99%   |
| 0x806ea    | 109       | 2.38%   |
| 0x6fd      | 103       | 2.25%   |
| 0x806c1    | 102       | 2.22%   |
| 0x506e3    | 100       | 2.18%   |
| 0x40651    | 96        | 2.09%   |
| 0x20655    | 93        | 2.03%   |
| 0x806ec    | 92        | 2.01%   |
| 0x806e9    | 87        | 1.9%    |
| 0x406e3    | 83        | 1.81%   |
| 0x306d4    | 75        | 1.64%   |
| 0x906e9    | 67        | 1.46%   |
| 0x08108109 | 62        | 1.35%   |
| 0x30678    | 53        | 1.16%   |
| 0x10676    | 52        | 1.13%   |
| 0x6fb      | 48        | 1.05%   |
| 0x20652    | 46        | 1%      |
| 0x08701021 | 44        | 0.96%   |
| 0x706a1    | 43        | 0.94%   |
| 0x0a50000c | 41        | 0.89%   |
| 0x0800820d | 41        | 0.89%   |
| 0x706e5    | 39        | 0.85%   |
| 0x506c9    | 38        | 0.83%   |
| 0x406c4    | 38        | 0.83%   |
| 0xa0652    | 35        | 0.76%   |
| 0x6f6      | 35        | 0.76%   |
| 0x06006705 | 35        | 0.76%   |
| 0x08600106 | 33        | 0.72%   |
| 0x08108102 | 33        | 0.72%   |
| 0x010000c8 | 33        | 0.72%   |
| 0x06000852 | 32        | 0.7%    |
| 0x06001119 | 31        | 0.68%   |
| 0x706a8    | 30        | 0.65%   |
| 0x906ed    | 28        | 0.61%   |
| 0x806eb    | 28        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 689       | 15.53%  |
| Haswell          | 436       | 9.82%   |
| Penryn           | 281       | 6.33%   |
| SandyBridge      | 273       | 6.15%   |
| Core             | 244       | 5.5%    |
| IvyBridge        | 234       | 5.27%   |
| Skylake          | 221       | 4.98%   |
| Zen+             | 173       | 3.9%    |
| Zen 2            | 168       | 3.79%   |
| Westmere         | 166       | 3.74%   |
| Silvermont       | 154       | 3.47%   |
| TigerLake        | 134       | 3.02%   |
| Broadwell        | 101       | 2.28%   |
| Unknown          | 101       | 2.28%   |
| CometLake        | 95        | 2.14%   |
| Zen 3            | 92        | 2.07%   |
| Piledriver       | 87        | 1.96%   |
| Goldmont plus    | 87        | 1.96%   |
| K10              | 86        | 1.94%   |
| Zen              | 83        | 1.87%   |
| IceLake          | 64        | 1.44%   |
| Excavator        | 61        | 1.37%   |
| Bonnell          | 61        | 1.37%   |
| K8 Hammer        | 52        | 1.17%   |
| Goldmont         | 43        | 0.97%   |
| Nehalem          | 42        | 0.95%   |
| NetBurst         | 38        | 0.86%   |
| Puma             | 30        | 0.68%   |
| P6               | 30        | 0.68%   |
| Jaguar           | 26        | 0.59%   |
| Alderlake Hybrid | 22        | 0.5%    |
| Steamroller      | 19        | 0.43%   |
| Bobcat           | 19        | 0.43%   |
| K10 Llano        | 9         | 0.2%    |
| Bulldozer        | 8         | 0.18%   |
| Tremont          | 5         | 0.11%   |
| K8 & K10 hybrid  | 3         | 0.07%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2547      | 48.73%  |
| Nvidia                                       | 1532      | 29.31%  |
| AMD                                          | 1097      | 20.99%  |
| Matrox Electronics Systems                   | 17        | 0.33%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.25%   |
| VIA Technologies                             | 10        | 0.19%   |
| ASPEED Technology                            | 8         | 0.15%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 188       | 3.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 128       | 2.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 123       | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 120       | 2.22%   |
| Intel UHD Graphics 620                                                                   | 110       | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 106       | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 104       | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 100       | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 94        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 91        | 1.68%   |
| Intel HD Graphics 620                                                                    | 90        | 1.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 86        | 1.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 81        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 81        | 1.5%    |
| AMD Renoir                                                                               | 80        | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 79        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 73        | 1.35%   |
| Intel HD Graphics 5500                                                                   | 72        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 70        | 1.29%   |
| Intel HD Graphics 530                                                                    | 67        | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 62        | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 1.13%   |
| Intel HD Graphics 630                                                                    | 61        | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 60        | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 54        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 52        | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 52        | 0.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 49        | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 45        | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 45        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 43        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 42        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 42        | 0.78%   |
| Intel HD Graphics 500                                                                    | 41        | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 38        | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 37        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1820      | 40.84%  |
| 1 x AMD                | 865       | 19.41%  |
| 1 x Nvidia             | 860       | 19.3%   |
| Intel + Nvidia         | 577       | 12.95%  |
| Intel + AMD            | 93        | 2.09%   |
| AMD + Nvidia           | 77        | 1.73%   |
| 2 x AMD                | 63        | 1.41%   |
| Other                  | 33        | 0.74%   |
| 2 x Nvidia             | 14        | 0.31%   |
| 1 x Matrox             | 14        | 0.31%   |
| 1 x SiS                | 13        | 0.29%   |
| 1 x VIA                | 10        | 0.22%   |
| 1 x ASPEED             | 5         | 0.11%   |
| Nvidia + Matrox        | 3         | 0.07%   |
| Nvidia + ASPEED        | 3         | 0.07%   |
| 3 x AMD                | 1         | 0.02%   |
| 2 x Intel              | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3559      | 79.12%  |
| Proprietary | 748       | 16.63%  |
| Unknown     | 191       | 4.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2382      | 52.21%  |
| 1.01-2.0   | 637       | 13.96%  |
| 0.01-0.5   | 546       | 11.97%  |
| 3.01-4.0   | 356       | 7.8%    |
| 0.51-1.0   | 343       | 7.52%   |
| 7.01-8.0   | 163       | 3.57%   |
| 5.01-6.0   | 81        | 1.78%   |
| 2.01-3.0   | 26        | 0.57%   |
| 8.01-16.0  | 23        | 0.5%    |
| 16.01-24.0 | 5         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 569       | 11.93%  |
| AU Optronics            | 512       | 10.73%  |
| Chimei Innolux          | 457       | 9.58%   |
| LG Display              | 404       | 8.47%   |
| Goldstar                | 342       | 7.17%   |
| BOE                     | 326       | 6.83%   |
| Hewlett-Packard         | 235       | 4.93%   |
| BenQ                    | 193       | 4.05%   |
| Dell                    | 186       | 3.9%    |
| Acer                    | 163       | 3.42%   |
| Ancor Communications    | 147       | 3.08%   |
| Philips                 | 126       | 2.64%   |
| AOC                     | 93        | 1.95%   |
| Apple                   | 91        | 1.91%   |
| Chi Mei Optoelectronics | 90        | 1.89%   |
| Sharp                   | 82        | 1.72%   |
| Lenovo                  | 73        | 1.53%   |
| PANDA                   | 55        | 1.15%   |
| LG Electronics          | 53        | 1.11%   |
| Unknown                 | 46        | 0.96%   |
| Sony                    | 44        | 0.92%   |
| HannStar                | 40        | 0.84%   |
| LG Philips              | 39        | 0.82%   |
| ASUSTek Computer        | 29        | 0.61%   |
| ViewSonic               | 26        | 0.55%   |
| InfoVision              | 18        | 0.38%   |
| MSI                     | 17        | 0.36%   |
| Eizo                    | 12        | 0.25%   |
| OEM                     | 11        | 0.23%   |
| Toshiba                 | 10        | 0.21%   |
| ___                     | 9         | 0.19%   |
| Panasonic               | 9         | 0.19%   |
| Hitachi                 | 9         | 0.19%   |
| CPT                     | 9         | 0.19%   |
| Quanta Display          | 8         | 0.17%   |
| Packard Bell            | 8         | 0.17%   |
| Xiaomi                  | 7         | 0.15%   |
| Vestel Elektronik       | 7         | 0.15%   |
| NEC Computers           | 7         | 0.15%   |
| Iiyama                  | 7         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 64        | 1.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 0.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 29        | 0.59%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 28        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 25        | 0.51%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 20        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 20        | 0.41%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 14        | 0.28%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 13        | 0.26%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.24%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 12        | 0.24%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.24%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 12        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 11        | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.22%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 11        | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 10        | 0.2%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 10        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1962      | 43.19%  |
| 1366x768 (WXGA)    | 957       | 21.07%  |
| 3840x2160 (4K)     | 205       | 4.51%   |
| 1280x1024 (SXGA)   | 196       | 4.31%   |
| 2560x1440 (QHD)    | 158       | 3.48%   |
| 1280x800 (WXGA)    | 153       | 3.37%   |
| 1680x1050 (WSXGA+) | 140       | 3.08%   |
| 1440x900 (WXGA+)   | 137       | 3.02%   |
| 1600x900 (HD+)     | 103       | 2.27%   |
| 1920x1200 (WUXGA)  | 76        | 1.67%   |
| Unknown            | 57        | 1.25%   |
| 2560x1080          | 49        | 1.08%   |
| 1360x768           | 44        | 0.97%   |
| 1024x600           | 39        | 0.86%   |
| 3440x1440          | 27        | 0.59%   |
| 2560x1600          | 24        | 0.53%   |
| 1024x768 (XGA)     | 23        | 0.51%   |
| 2160x1440          | 20        | 0.44%   |
| 3840x1080          | 15        | 0.33%   |
| 800x1280           | 14        | 0.31%   |
| 2880x1800          | 13        | 0.29%   |
| 1920x540           | 13        | 0.29%   |
| 1600x1200          | 12        | 0.26%   |
| 3200x1800 (QHD+)   | 8         | 0.18%   |
| 2288x1287          | 6         | 0.13%   |
| 3200x1080          | 5         | 0.11%   |
| 4480x1080          | 4         | 0.09%   |
| 3840x2400          | 4         | 0.09%   |
| 1280x768           | 4         | 0.09%   |
| 3840x1200          | 3         | 0.07%   |
| 3600x1080          | 3         | 0.07%   |
| 3360x1080          | 3         | 0.07%   |
| 2960x1050          | 3         | 0.07%   |
| 2736x1824          | 3         | 0.07%   |
| 2048x1152          | 3         | 0.07%   |
| 1920x1280          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 5760x2160          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1399      | 29.39%  |
| 13      | 361       | 7.58%   |
| 24      | 344       | 7.23%   |
| 21      | 336       | 7.06%   |
| 27      | 310       | 6.51%   |
| Unknown | 281       | 5.9%    |
| 23      | 269       | 5.65%   |
| 17      | 250       | 5.25%   |
| 14      | 243       | 5.11%   |
| 19      | 147       | 3.09%   |
| 18      | 109       | 2.29%   |
| 22      | 81        | 1.7%    |
| 34      | 69        | 1.45%   |
| 20      | 68        | 1.43%   |
| 31      | 63        | 1.32%   |
| 12      | 63        | 1.32%   |
| 11      | 47        | 0.99%   |
| 10      | 47        | 0.99%   |
| 84      | 40        | 0.84%   |
| 16      | 32        | 0.67%   |
| 72      | 23        | 0.48%   |
| 26      | 23        | 0.48%   |
| 25      | 22        | 0.46%   |
| 54      | 21        | 0.44%   |
| 32      | 19        | 0.4%    |
| 40      | 11        | 0.23%   |
| 52      | 7         | 0.15%   |
| 28      | 7         | 0.15%   |
| 65      | 6         | 0.13%   |
| 46      | 6         | 0.13%   |
| 142     | 5         | 0.11%   |
| 48      | 5         | 0.11%   |
| 60      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 8       | 4         | 0.08%   |
| 7       | 4         | 0.08%   |
| 47      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 37      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1884      | 40.28%  |
| 501-600        | 862       | 18.43%  |
| 401-500        | 668       | 14.28%  |
| 201-300        | 371       | 7.93%   |
| Unknown        | 281       | 6.01%   |
| 351-400        | 255       | 5.45%   |
| 601-700        | 107       | 2.29%   |
| 701-800        | 89        | 1.9%    |
| 1501-2000      | 65        | 1.39%   |
| 1001-1500      | 55        | 1.18%   |
| 801-900        | 19        | 0.41%   |
| 901-1000       | 6         | 0.13%   |
| 1-100          | 6         | 0.13%   |
| More than 2000 | 5         | 0.11%   |
| 101-200        | 4         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3158      | 73.24%  |
| 16/10   | 542       | 12.57%  |
| Unknown | 233       | 5.4%    |
| 5/4     | 181       | 4.2%    |
| 21/9    | 72        | 1.67%   |
| 4/3     | 50        | 1.16%   |
| 3/2     | 46        | 1.07%   |
| 0.62    | 12        | 0.28%   |
| 1.00    | 5         | 0.12%   |
| 0.67    | 4         | 0.09%   |
| 32/9    | 3         | 0.07%   |
| 6/5     | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1398      | 29.57%  |
| 201-250        | 844       | 17.85%  |
| 81-90          | 424       | 8.97%   |
| 301-350        | 318       | 6.73%   |
| 151-200        | 312       | 6.6%    |
| Unknown        | 281       | 5.94%   |
| 141-150        | 197       | 4.17%   |
| 71-80          | 180       | 3.81%   |
| 351-500        | 157       | 3.32%   |
| 251-300        | 121       | 2.56%   |
| More than 1000 | 116       | 2.45%   |
| 121-130        | 109       | 2.31%   |
| 61-70          | 55        | 1.16%   |
| 51-60          | 47        | 0.99%   |
| 41-50          | 47        | 0.99%   |
| 501-1000       | 36        | 0.76%   |
| 131-140        | 34        | 0.72%   |
| 111-120        | 25        | 0.53%   |
| 91-100         | 17        | 0.36%   |
| 1-40           | 10        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1603      | 34.86%  |
| 101-120       | 1278      | 27.79%  |
| 121-160       | 1060      | 23.05%  |
| Unknown       | 281       | 6.11%   |
| 161-240       | 218       | 4.74%   |
| 1-50          | 97        | 2.11%   |
| More than 240 | 61        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3602      | 79.46%  |
| 2     | 645       | 14.23%  |
| 0     | 205       | 4.52%   |
| 3     | 76        | 1.68%   |
| 4     | 5         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2527      | 37.81%  |
| Intel                             | 1859      | 27.82%  |
| Qualcomm Atheros                  | 867       | 12.97%  |
| Broadcom                          | 414       | 6.19%   |
| TP-Link                           | 107       | 1.6%    |
| Ralink Technology                 | 106       | 1.59%   |
| Marvell Technology Group          | 101       | 1.51%   |
| Broadcom Limited                  | 92        | 1.38%   |
| Nvidia                            | 86        | 1.29%   |
| Ralink                            | 70        | 1.05%   |
| MediaTek                          | 41        | 0.61%   |
| Qualcomm Atheros Communications   | 40        | 0.6%    |
| Samsung Electronics               | 27        | 0.4%    |
| Xiaomi                            | 25        | 0.37%   |
| D-Link                            | 23        | 0.34%   |
| ASIX Electronics                  | 22        | 0.33%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.27%   |
| VIA Technologies                  | 17        | 0.25%   |
| D-Link System                     | 16        | 0.24%   |
| ASUSTek Computer                  | 16        | 0.24%   |
| Qualcomm                          | 14        | 0.21%   |
| Sierra Wireless                   | 12        | 0.18%   |
| Hewlett-Packard                   | 12        | 0.18%   |
| Belkin Components                 | 12        | 0.18%   |
| Ericsson Business Mobile Networks | 11        | 0.16%   |
| DisplayLink                       | 11        | 0.16%   |
| Dell                              | 11        | 0.16%   |
| JMicron Technology                | 10        | 0.15%   |
| Lenovo                            | 9         | 0.13%   |
| Microsoft                         | 7         | 0.1%    |
| Huawei Technologies               | 7         | 0.1%    |
| ZyDAS                             | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| LSI                               | 4         | 0.06%   |
| Gemtek                            | 4         | 0.06%   |
| Edimax Technology                 | 4         | 0.06%   |
| Attansic Technology               | 4         | 0.06%   |
| Accton Technology                 | 4         | 0.06%   |
| Toshiba                           | 3         | 0.04%   |
| Texas Instruments                 | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1729      | 22.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 286       | 3.71%   |
| Intel Wi-Fi 6 AX200                                                     | 172       | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 132       | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 111       | 1.44%   |
| Intel Wireless 8265 / 8275                                              | 110       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 105       | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 100       | 1.3%    |
| Intel Wi-Fi 6 AX201                                                     | 100       | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 99        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 97        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 95        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 95        | 1.23%   |
| Intel Wireless 7265                                                     | 91        | 1.18%   |
| Intel Wireless 3165                                                     | 84        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 83        | 1.08%   |
| Intel I211 Gigabit Network Connection                                   | 78        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                    | 75        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 69        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 63        | 0.82%   |
| Intel Wireless 7260                                                     | 62        | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                       | 59        | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 46        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 42        | 0.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 41        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 41        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 41        | 0.53%   |
| Intel Wireless 8260                                                     | 40        | 0.52%   |
| Intel WiFi Link 5100                                                    | 40        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 38        | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 38        | 0.49%   |
| Intel 82579V Gigabit Network Connection                                 | 38        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 37        | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 36        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1393      | 39.53%  |
| Realtek Semiconductor           | 669       | 18.98%  |
| Qualcomm Atheros                | 666       | 18.9%   |
| Broadcom                        | 255       | 7.24%   |
| Ralink Technology               | 106       | 3.01%   |
| TP-Link                         | 90        | 2.55%   |
| Ralink                          | 70        | 1.99%   |
| Broadcom Limited                | 62        | 1.76%   |
| Qualcomm Atheros Communications | 40        | 1.14%   |
| MediaTek                        | 40        | 1.14%   |
| D-Link                          | 19        | 0.54%   |
| ASUSTek Computer                | 16        | 0.45%   |
| Sierra Wireless                 | 12        | 0.34%   |
| Belkin Components               | 12        | 0.34%   |
| D-Link System                   | 10        | 0.28%   |
| Microsoft                       | 7         | 0.2%    |
| Dell                            | 6         | 0.17%   |
| ZyDAS                           | 5         | 0.14%   |
| Marvell Technology Group        | 5         | 0.14%   |
| Qualcomm                        | 4         | 0.11%   |
| Hewlett-Packard                 | 4         | 0.11%   |
| Gemtek                          | 4         | 0.11%   |
| Edimax Technology               | 4         | 0.11%   |
| Texas Instruments               | 3         | 0.09%   |
| NetGear                         | 3         | 0.09%   |
| Linksys                         | 3         | 0.09%   |
| Sitecom Europe                  | 2         | 0.06%   |
| Fibocom                         | 2         | 0.06%   |
| Accton Technology               | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |
| Xiaomi                          | 1         | 0.03%   |
| Wilocity                        | 1         | 0.03%   |
| Wacom                           | 1         | 0.03%   |
| TRENDnet                        | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| Standard Microsystems           | 1         | 0.03%   |
| Samsung Electronics             | 1         | 0.03%   |
| AirTies Wireless Networks       | 1         | 0.03%   |
| 3Com                            | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 172       | 4.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 111       | 3.13%   |
| Intel Wireless 8265 / 8275                                              | 110       | 3.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 105       | 2.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 100       | 2.82%   |
| Intel Wi-Fi 6 AX201                                                     | 100       | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 97        | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 95        | 2.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 95        | 2.68%   |
| Intel Wireless 7265                                                     | 91        | 2.56%   |
| Intel Wireless 3165                                                     | 84        | 2.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 83        | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 69        | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 63        | 1.78%   |
| Intel Wireless 7260                                                     | 62        | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 1.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 46        | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 41        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 41        | 1.16%   |
| Intel Wireless 8260                                                     | 40        | 1.13%   |
| Intel WiFi Link 5100                                                    | 40        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 38        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 38        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 37        | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                         | 36        | 1.01%   |
| Intel Wireless 3160                                                     | 36        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 34        | 0.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 33        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 32        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 31        | 0.87%   |
| Realtek 802.11ac NIC                                                    | 29        | 0.82%   |
| Intel Wireless-AC 9260                                                  | 28        | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 27        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 26        | 0.73%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2249      | 56.06%  |
| Intel                                  | 844       | 21.04%  |
| Qualcomm Atheros                       | 278       | 6.93%   |
| Broadcom                               | 203       | 5.06%   |
| Marvell Technology Group               | 97        | 2.42%   |
| Nvidia                                 | 86        | 2.14%   |
| Broadcom Limited                       | 32        | 0.8%    |
| Samsung Electronics                    | 26        | 0.65%   |
| Xiaomi                                 | 24        | 0.6%    |
| ASIX Electronics                       | 22        | 0.55%   |
| Silicon Integrated Systems [SiS]       | 18        | 0.45%   |
| VIA Technologies                       | 17        | 0.42%   |
| TP-Link                                | 17        | 0.42%   |
| DisplayLink                            | 11        | 0.27%   |
| Qualcomm                               | 10        | 0.25%   |
| JMicron Technology                     | 10        | 0.25%   |
| Lenovo                                 | 9         | 0.22%   |
| D-Link System                          | 6         | 0.15%   |
| LSI                                    | 4         | 0.1%    |
| Hewlett-Packard                        | 4         | 0.1%    |
| D-Link                                 | 4         | 0.1%    |
| Attansic Technology                    | 4         | 0.1%    |
| Microchip Technology                   | 3         | 0.07%   |
| IBM                                    | 3         | 0.07%   |
| Aquantia                               | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.05%   |
| Huawei Technologies                    | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Davicom Semiconductor                  | 2         | 0.05%   |
| ADMtek                                 | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Meizu                                  | 1         | 0.02%   |
| MediaTek                               | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1729      | 42.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 286       | 6.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 132       | 3.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 99        | 2.42%   |
| Intel I211 Gigabit Network Connection                             | 78        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                              | 75        | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59        | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 41        | 1%      |
| Intel 82579V Gigabit Network Connection                           | 38        | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 35        | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 35        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 32        | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 29        | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 27        | 0.66%   |
| Nvidia MCP61 Ethernet                                             | 26        | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 24        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 22        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.44%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 17        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3839      | 53.28%  |
| WiFi     | 3311      | 45.95%  |
| Modem    | 51        | 0.71%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2520      | 54.63%  |
| Ethernet | 2093      | 45.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2379      | 53.47%  |
| 1     | 1880      | 42.26%  |
| 0     | 105       | 2.36%   |
| 3     | 62        | 1.39%   |
| 4     | 15        | 0.34%   |
| 6     | 4         | 0.09%   |
| 5     | 4         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4308      | 96.9%   |
| Yes  | 138       | 3.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1097      | 43.1%   |
| Realtek Semiconductor           | 305       | 11.98%  |
| Cambridge Silicon Radio         | 230       | 9.04%   |
| IMC Networks                    | 154       | 6.05%   |
| Qualcomm Atheros Communications | 148       | 5.82%   |
| Broadcom                        | 110       | 4.32%   |
| Apple                           | 100       | 3.93%   |
| Lite-On Technology              | 84        | 3.3%    |
| Foxconn / Hon Hai               | 76        | 2.99%   |
| ASUSTek Computer                | 46        | 1.81%   |
| Toshiba                         | 34        | 1.34%   |
| Realtek                         | 32        | 1.26%   |
| Dell                            | 27        | 1.06%   |
| Hewlett-Packard                 | 22        | 0.86%   |
| Ralink                          | 17        | 0.67%   |
| Alps Electric                   | 12        | 0.47%   |
| Belkin Components               | 9         | 0.35%   |
| Foxconn International           | 8         | 0.31%   |
| Integrated System Solution      | 7         | 0.28%   |
| TP-Link                         | 4         | 0.16%   |
| Ralink Technology               | 4         | 0.16%   |
| MediaTek                        | 4         | 0.16%   |
| Marvell Semiconductor           | 3         | 0.12%   |
| Edimax Technology               | 3         | 0.12%   |
| Roper                           | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 422       | 16.58%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 230       | 9.04%   |
| Realtek Bluetooth Radio                             | 222       | 8.72%   |
| Intel AX201 Bluetooth                               | 188       | 7.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 184       | 7.23%   |
| Intel AX200 Bluetooth                               | 167       | 6.56%   |
| IMC Networks Bluetooth Radio                        | 74        | 2.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 61        | 2.4%    |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 2.32%   |
| IMC Networks Bluetooth Device                       | 47        | 1.85%   |
| Apple Bluetooth Host Controller                     | 40        | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 39        | 1.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 35        | 1.38%   |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 1.38%   |
| Realtek Bluetooth Radio                             | 32        | 1.26%   |
| Apple Bluetooth USB Host Controller                 | 29        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 28        | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.06%   |
| Intel AX210 Bluetooth                               | 27        | 1.06%   |
| Lite-On Bluetooth Device                            | 24        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 21        | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.79%   |
| IMC Networks Wireless_Device                        | 19        | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.71%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 17        | 0.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.55%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.47%   |
| Intel Bluetooth Device                              | 12        | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.47%   |
| Apple Bluetooth HCI                                 | 12        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.43%   |
| Broadcom BCM2045 Bluetooth                          | 11        | 0.43%   |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.39%   |
| Realtek RTL8821A Bluetooth                          | 9         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3240      | 54.26%  |
| AMD                                  | 1164      | 19.49%  |
| Nvidia                               | 1043      | 17.47%  |
| C-Media Electronics                  | 96        | 1.61%   |
| Creative Labs                        | 37        | 0.62%   |
| Logitech                             | 33        | 0.55%   |
| Texas Instruments                    | 21        | 0.35%   |
| JMTek                                | 21        | 0.35%   |
| Silicon Integrated Systems [SiS]     | 20        | 0.33%   |
| VIA Technologies                     | 18        | 0.3%    |
| GN Netcom                            | 18        | 0.3%    |
| Kingston Technology                  | 16        | 0.27%   |
| Plantronics                          | 15        | 0.25%   |
| Corsair                              | 14        | 0.23%   |
| ASUSTek Computer                     | 12        | 0.2%    |
| Realtek Semiconductor                | 11        | 0.18%   |
| Focusrite-Novation                   | 11        | 0.18%   |
| Creative Technology                  | 11        | 0.18%   |
| Generalplus Technology               | 10        | 0.17%   |
| Lenovo                               | 9         | 0.15%   |
| SteelSeries ApS                      | 8         | 0.13%   |
| DSEA A/S                             | 7         | 0.12%   |
| Ensoniq                              | 6         | 0.1%    |
| BEHRINGER International              | 6         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 5         | 0.08%   |
| M-Audio                              | 5         | 0.08%   |
| Hewlett-Packard                      | 5         | 0.08%   |
| Yamaha                               | 4         | 0.07%   |
| Tenx Technology                      | 4         | 0.07%   |
| Razer USA                            | 4         | 0.07%   |
| Blue Microphones                     | 4         | 0.07%   |
| Apple                                | 4         | 0.07%   |
| Sony                                 | 3         | 0.05%   |
| SAVITECH                             | 3         | 0.05%   |
| QinHeng Electronics                  | 3         | 0.05%   |
| Micro Star International             | 3         | 0.05%   |
| Guillemot                            | 3         | 0.05%   |
| Evolution Electronics                | 3         | 0.05%   |
| Elite Silicon                        | 3         | 0.05%   |
| Dell                                 | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 314       | 4.45%   |
| Intel Sunrise Point-LP HD Audio                                            | 308       | 4.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 257       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 251       | 3.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 234       | 3.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 209       | 2.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 195       | 2.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 179       | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 178       | 2.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 174       | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 144       | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 138       | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 134       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 130       | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 130       | 1.84%   |
| AMD FCH Azalia Controller                                                  | 128       | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 124       | 1.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 123       | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 122       | 1.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 116       | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 107       | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 102       | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 100       | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 96        | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 94        | 1.33%   |
| Intel 200 Series PCH HD Audio                                              | 94        | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 92        | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 87        | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 86        | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 80        | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 73        | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 65        | 0.92%   |
| Intel Comet Lake PCH cAVS                                                  | 63        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 62        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 60        | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 60        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 55        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 52        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 50        | 0.71%   |
| AMD High Definition Audio Controller                                       | 49        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 560       | 22.97%  |
| SK hynix                     | 391       | 16.04%  |
| Kingston                     | 376       | 15.42%  |
| Unknown                      | 273       | 11.2%   |
| Micron Technology            | 216       | 8.86%   |
| Crucial                      | 160       | 6.56%   |
| Corsair                      | 103       | 4.22%   |
| G.Skill                      | 79        | 3.24%   |
| Ramaxel Technology           | 62        | 2.54%   |
| Unknown (ABCD)               | 33        | 1.35%   |
| Elpida                       | 33        | 1.35%   |
| Nanya Technology             | 21        | 0.86%   |
| A-DATA Technology            | 21        | 0.86%   |
| Silicon Power                | 12        | 0.49%   |
| Goodram                      | 10        | 0.41%   |
| Unknown                      | 10        | 0.41%   |
| Transcend                    | 8         | 0.33%   |
| Unifosa                      | 6         | 0.25%   |
| Apacer                       | 6         | 0.25%   |
| Team                         | 5         | 0.21%   |
| Wilk                         | 4         | 0.16%   |
| Patriot                      | 4         | 0.16%   |
| ASint Technology             | 4         | 0.16%   |
| Kllisre                      | 3         | 0.12%   |
| Atermiter                    | 3         | 0.12%   |
| Timetec                      | 2         | 0.08%   |
| SHARETRONIC                  | 2         | 0.08%   |
| Qimonda                      | 2         | 0.08%   |
| PNY                          | 2         | 0.08%   |
| Micron/Elpida                | 2         | 0.08%   |
| KomputerBay                  | 2         | 0.08%   |
| Innodisk                     | 2         | 0.08%   |
| Exceleram                    | 2         | 0.08%   |
| Avant                        | 2         | 0.08%   |
| Unknown (AB)                 | 1         | 0.04%   |
| Unknown (07FB)               | 1         | 0.04%   |
| Toshiba                      | 1         | 0.04%   |
| Thermaltake                  | 1         | 0.04%   |
| Pioneer                      | 1         | 0.04%   |
| Patriot Memory (PDP Systems) | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 29        | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 0.84%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 21        | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 17        | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 17        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 17        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 15        | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.5%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 13        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 12        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 12        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 11        | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.42%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 11        | 0.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 0.42%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 10        | 0.38%   |
| Unknown                                                          | 10        | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.34%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.34%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 9         | 0.34%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 8         | 0.31%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 8         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 998       | 46.94%  |
| DDR3    | 696       | 32.74%  |
| DDR2    | 131       | 6.16%   |
| LPDDR4  | 76        | 3.57%   |
| Unknown | 72        | 3.39%   |
| SDRAM   | 62        | 2.92%   |
| LPDDR3  | 55        | 2.59%   |
| DDR     | 16        | 0.75%   |
| DDR5    | 10        | 0.47%   |
| DRAM    | 6         | 0.28%   |
| LPDDR5  | 4         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1257      | 59.04%  |
| DIMM         | 719       | 33.77%  |
| Row Of Chips | 139       | 6.53%   |
| Chip         | 9         | 0.42%   |
| FB-DIMM      | 3         | 0.14%   |
| RIMM         | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 874       | 37.79%  |
| 4096  | 638       | 27.58%  |
| 2048  | 321       | 13.88%  |
| 16384 | 319       | 13.79%  |
| 1024  | 105       | 4.54%   |
| 32768 | 43        | 1.86%   |
| 512   | 8         | 0.35%   |
| 65536 | 2         | 0.09%   |
| 256   | 2         | 0.09%   |
| 3072  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 437       | 18.99%  |
| 2667    | 346       | 15.04%  |
| 3200    | 323       | 14.04%  |
| 2400    | 182       | 7.91%   |
| 1333    | 155       | 6.74%   |
| 2133    | 120       | 5.22%   |
| 667     | 85        | 3.69%   |
| 1334    | 72        | 3.13%   |
| 800     | 67        | 2.91%   |
| 3600    | 60        | 2.61%   |
| 1867    | 52        | 2.26%   |
| Unknown | 52        | 2.26%   |
| 8400    | 30        | 1.3%    |
| 4267    | 27        | 1.17%   |
| 1067    | 24        | 1.04%   |
| 3466    | 22        | 0.96%   |
| 2933    | 18        | 0.78%   |
| 3266    | 17        | 0.74%   |
| 1866    | 17        | 0.74%   |
| 1066    | 17        | 0.74%   |
| 533     | 16        | 0.7%    |
| 3400    | 14        | 0.61%   |
| 2048    | 13        | 0.56%   |
| 4199    | 12        | 0.52%   |
| 2733    | 12        | 0.52%   |
| 3733    | 11        | 0.48%   |
| 3000    | 10        | 0.43%   |
| 4800    | 9         | 0.39%   |
| 2666    | 7         | 0.3%    |
| 6400    | 5         | 0.22%   |
| 4266    | 5         | 0.22%   |
| 975     | 5         | 0.22%   |
| 400     | 5         | 0.22%   |
| 3800    | 4         | 0.17%   |
| 3500    | 4         | 0.17%   |
| 2800    | 4         | 0.17%   |
| 1800    | 4         | 0.17%   |
| 1639    | 4         | 0.17%   |
| 333     | 3         | 0.13%   |
| 5200    | 2         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 59        | 49.17%  |
| Brother Industries       | 23        | 19.17%  |
| Canon                    | 13        | 10.83%  |
| Samsung Electronics      | 9         | 7.5%    |
| Seiko Epson              | 7         | 5.83%   |
| Oki Data                 | 2         | 1.67%   |
| Dymo-CoStar              | 2         | 1.67%   |
| Ricoh                    | 1         | 0.83%   |
| Magic Control Technology | 1         | 0.83%   |
| Lexmark International    | 1         | 0.83%   |
| Kyocera                  | 1         | 0.83%   |
| Apple                    | 1         | 0.83%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 4.13%   |
| Brother HL-2030 Laser Printer                   | 5         | 4.13%   |
| Canon PIXMA MG2500 Series                       | 4         | 3.31%   |
| HP LaserJet 1020                                | 3         | 2.48%   |
| HP DeskJet 2620 All-in-One Printer              | 3         | 2.48%   |
| HP Deskjet 1050 J410                            | 3         | 2.48%   |
| Canon LiDE 400                                  | 3         | 2.48%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.65%   |
| Samsung M2070 Series                            | 2         | 1.65%   |
| Oki Data USB Device                             | 2         | 1.65%   |
| HP LaserJet 1010                                | 2         | 1.65%   |
| HP ENVY 5540 series                             | 2         | 1.65%   |
| HP ENVY 5000 series                             | 2         | 1.65%   |
| HP ENVY 4520 series                             | 2         | 1.65%   |
| HP DeskJet F2492 All-in-One                     | 2         | 1.65%   |
| HP DeskJet 5550                                 | 2         | 1.65%   |
| HP DeskJet 3630 series                          | 2         | 1.65%   |
| HP DeskJet 2700 series                          | 2         | 1.65%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.65%   |
| Brother Printer                                 | 2         | 1.65%   |
| Brother MFC-J5330DW                             | 2         | 1.65%   |
| Brother DCP-1510                                | 2         | 1.65%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.83%   |
| Seiko Epson XP-230 Series                       | 1         | 0.83%   |
| Seiko Epson XP-225 Series                       | 1         | 0.83%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.83%   |
| Seiko Epson Printer                             | 1         | 0.83%   |
| Seiko Epson L555 Series                         | 1         | 0.83%   |
| Seiko Epson L1300 Series                        | 1         | 0.83%   |
| Samsung SCX-4300 Series                         | 1         | 0.83%   |
| Samsung SCX-3400 Series                         | 1         | 0.83%   |
| Samsung SCX-3200 Series                         | 1         | 0.83%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.83%   |
| Samsung M267x 287x Series                       | 1         | 0.83%   |
| Ricoh SP 112                                    | 1         | 0.83%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.83%   |
| Lexmark International B2236dw                   | 1         | 0.83%   |
| Kyocera ECOSYS M5521cdn                         | 1         | 0.83%   |
| HP PSC-1315/PSC-1317                            | 1         | 0.83%   |
| HP PSC 1500 series                              | 1         | 0.83%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 43.75%  |
| Hewlett-Packard             | 8         | 25%     |
| Seiko Epson                 | 6         | 18.75%  |
| Acer Peripherals (now BenQ) | 2         | 6.25%   |
| Mustek Systems              | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.5%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.25%   |
| HP Scanjet 300                                           | 2         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 3.13%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.13%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.13%   |
| HP Scanjet N6010                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                         | 1         | 3.13%   |
| HP ScanJet 4570c                                         | 1         | 3.13%   |
| HP ScanJet 4300c                                         | 1         | 3.13%   |
| HP ScanJet 3570c                                         | 1         | 3.13%   |
| HP ScanJet 3300c                                         | 1         | 3.13%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 588       | 22.97%  |
| IMC Networks                           | 283       | 11.05%  |
| Acer                                   | 244       | 9.53%   |
| Realtek Semiconductor                  | 165       | 6.45%   |
| Microdia                               | 161       | 6.29%   |
| Logitech                               | 118       | 4.61%   |
| Suyin                                  | 112       | 4.38%   |
| Quanta                                 | 112       | 4.38%   |
| Sunplus Innovation Technology          | 107       | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 91        | 3.55%   |
| Syntek                                 | 74        | 2.89%   |
| Apple                                  | 69        | 2.7%    |
| Alcor Micro                            | 45        | 1.76%   |
| Lite-On Technology                     | 41        | 1.6%    |
| Ricoh                                  | 28        | 1.09%   |
| Luxvisions Innotech Limited            | 28        | 1.09%   |
| Samsung Electronics                    | 20        | 0.78%   |
| Silicon Motion                         | 19        | 0.74%   |
| Creative Technology                    | 17        | 0.66%   |
| Z-Star Microelectronics                | 15        | 0.59%   |
| Microsoft                              | 15        | 0.59%   |
| GEMBIRD                                | 13        | 0.51%   |
| Generalplus Technology                 | 11        | 0.43%   |
| Sonix Technology                       | 10        | 0.39%   |
| Lenovo                                 | 9         | 0.35%   |
| KYE Systems (Mouse Systems)            | 9         | 0.35%   |
| Importek                               | 9         | 0.35%   |
| Sunplus Technology                     | 8         | 0.31%   |
| ARC International                      | 8         | 0.31%   |
| ALi                                    | 8         | 0.31%   |
| USB Camera                             | 7         | 0.27%   |
| Jieli Technology                       | 7         | 0.27%   |
| HD 2MP WEBCAM                          | 6         | 0.23%   |
| Genesys Logic                          | 6         | 0.23%   |
| Cubeternet                             | 6         | 0.23%   |
| Primax Electronics                     | 5         | 0.2%    |
| Intel                                  | 5         | 0.2%    |
| SunplusIT                              | 4         | 0.16%   |
| OmniVision Technologies                | 4         | 0.16%   |
| DigiTech                               | 4         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 73        | 2.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 2.6%    |
| Microdia Integrated_Webcam_HD                           | 62        | 2.41%   |
| Chicony HD WebCam                                       | 62        | 2.41%   |
| Chicony Integrated Camera                               | 60        | 2.33%   |
| Acer Integrated Camera                                  | 60        | 2.33%   |
| Acer HD Webcam                                          | 49        | 1.9%    |
| IMC Networks Integrated Camera                          | 44        | 1.71%   |
| Chicony USB2.0 VGA UVC WebCam                           | 38        | 1.47%   |
| Realtek Integrated_Webcam_HD                            | 36        | 1.4%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 30        | 1.16%   |
| Apple Built-in iSight                                   | 30        | 1.16%   |
| Quanta HP TrueVision HD Camera                          | 29        | 1.13%   |
| Logitech Webcam C270                                    | 29        | 1.13%   |
| Syntek Integrated Camera                                | 28        | 1.09%   |
| Realtek USB Camera                                      | 28        | 1.09%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 1.01%   |
| Chicony EasyCamera                                      | 26        | 1.01%   |
| Sunplus HD WebCam                                       | 25        | 0.97%   |
| Chicony USB 2.0 Camera                                  | 24        | 0.93%   |
| Microdia Webcam Vitade AF                               | 23        | 0.89%   |
| Acer EasyCamera                                         | 21        | 0.81%   |
| Samsung Galaxy A5 (MTP)                                 | 20        | 0.78%   |
| Chicony USB2.0 HD UVC WebCam                            | 19        | 0.74%   |
| Acer HD Camera                                          | 19        | 0.74%   |
| Syntek EasyCamera                                       | 18        | 0.7%    |
| Lite-On Integrated Camera                               | 18        | 0.7%    |
| Chicony HP TrueVision HD                                | 18        | 0.7%    |
| Chicony HP TrueVision HD Camera                         | 17        | 0.66%   |
| Chicony HP HD Camera                                    | 17        | 0.66%   |
| Apple FaceTime HD Camera (Built-in)                     | 17        | 0.66%   |
| Syntek Lenovo EasyCamera                                | 16        | 0.62%   |
| Realtek Lenovo EasyCamera                               | 16        | 0.62%   |
| Microdia USB 2.0 Camera                                 | 16        | 0.62%   |
| Chicony VGA WebCam                                      | 16        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 16        | 0.62%   |
| Acer Lenovo EasyCamera                                  | 16        | 0.62%   |
| Quanta HP HD Camera                                     | 15        | 0.58%   |
| Logitech HD Pro Webcam C920                             | 15        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)                 | 15        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 111       | 30.16%  |
| Validity Sensors           | 87        | 23.64%  |
| Shenzhen Goodix Technology | 60        | 16.3%   |
| Elan Microelectronics      | 37        | 10.05%  |
| AuthenTec                  | 34        | 9.24%   |
| Upek                       | 21        | 5.71%   |
| LighTuning Technology      | 12        | 3.26%   |
| STMicroelectronics         | 6         | 1.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 48        | 13.04%  |
| Shenzhen Goodix  FingerPrint Device                                        | 41        | 11.14%  |
| Elan ELAN:Fingerprint                                                      | 34        | 9.24%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 7.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 4.62%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 3.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.99%   |
| Synaptics  WBDI                                                            | 10        | 2.72%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.9%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.63%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.63%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.63%   |
| AuthenTec AES1600                                                          | 6         | 1.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.36%   |
| AuthenTec AES2810                                                          | 5         | 1.36%   |
| Validity Sensors VFS491                                                    | 4         | 1.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.09%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.09%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.82%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.82%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.82%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.54%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.54%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.54%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.27%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 66        | 34.74%  |
| Broadcom                  | 48        | 25.26%  |
| O2 Micro                  | 23        | 12.11%  |
| Lenovo                    | 8         | 4.21%   |
| Advanced Card Systems     | 8         | 4.21%   |
| Chicony Electronics       | 6         | 3.16%   |
| Realtek Semiconductor     | 5         | 2.63%   |
| Cherry                    | 5         | 2.63%   |
| C3PO                      | 5         | 2.63%   |
| Upek                      | 4         | 2.11%   |
| SCM Microsystems          | 3         | 1.58%   |
| Gemalto (was Gemplus)     | 3         | 1.58%   |
| OmniKey                   | 2         | 1.05%   |
| Hewlett-Packard           | 2         | 1.05%   |
| In Focus Systems          | 1         | 0.53%   |
| Fujitsu Siemens Computers | 1         | 0.53%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 62        | 32.63%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 11.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 8.95%   |
| Broadcom 5880                                                                | 13        | 6.84%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 4.74%   |
| Broadcom 58200                                                               | 9         | 4.74%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 4.21%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 3.16%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 3.16%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 2.63%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.11%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 2.11%   |
| C3PO LTC31v2                                                                 | 4         | 2.11%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 2.11%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.05%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.05%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.05%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.05%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.53%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.53%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.53%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.53%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.53%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.53%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.53%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.53%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3331      | 73.43%  |
| 1     | 962       | 21.21%  |
| 2     | 201       | 4.43%   |
| 3     | 27        | 0.6%    |
| 4     | 7         | 0.15%   |
| 5     | 5         | 0.11%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 360       | 24.79%  |
| Graphics card            | 351       | 24.17%  |
| Net/wireless             | 217       | 14.94%  |
| Chipcard                 | 154       | 10.61%  |
| Multimedia controller    | 92        | 6.34%   |
| Camera                   | 47        | 3.24%   |
| Communication controller | 46        | 3.17%   |
| Bluetooth                | 38        | 2.62%   |
| Unassigned class         | 27        | 1.86%   |
| Storage                  | 23        | 1.58%   |
| Sound                    | 22        | 1.52%   |
| Card reader              | 20        | 1.38%   |
| Net/ethernet             | 14        | 0.96%   |
| Network                  | 10        | 0.69%   |
| Flash memory             | 10        | 0.69%   |
| Modem                    | 9         | 0.62%   |
| Dvb card                 | 6         | 0.41%   |
| Firewire controller      | 3         | 0.21%   |
| Tv card                  | 1         | 0.07%   |
| Storage/raid             | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |

