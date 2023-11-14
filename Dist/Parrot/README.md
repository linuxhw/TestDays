Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 756

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Notebook    | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [9b13411bc8](https://linux-hardware.org/?probe=9b13411bc8) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ce8997d5a](https://linux-hardware.org/?probe=4ce8997d5a) | Nov 05, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [be57c0ce22](https://linux-hardware.org/?probe=be57c0ce22) | Oct 29, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [3c959b9af8](https://linux-hardware.org/?probe=3c959b9af8) | Oct 25, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [e3540cf969](https://linux-hardware.org/?probe=e3540cf969) | Oct 23, 2023 |
| Google        | Reef                        | Notebook    | [819e00dd76](https://linux-hardware.org/?probe=819e00dd76) | Oct 22, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [fb0b3ea9e7](https://linux-hardware.org/?probe=fb0b3ea9e7) | Oct 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0755ce07a3](https://linux-hardware.org/?probe=0755ce07a3) | Oct 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [35081bd0e8](https://linux-hardware.org/?probe=35081bd0e8) | Oct 08, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [a13621c5d3](https://linux-hardware.org/?probe=a13621c5d3) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [144cbc70d0](https://linux-hardware.org/?probe=144cbc70d0) | Oct 03, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| HP            | 8619                        | Desktop     | [d631850d2f](https://linux-hardware.org/?probe=d631850d2f) | Sep 28, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [34e34036d7](https://linux-hardware.org/?probe=34e34036d7) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| HP            | 8714                        | Desktop     | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e10f21c5c5](https://linux-hardware.org/?probe=e10f21c5c5) | Sep 22, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [648ac87a81](https://linux-hardware.org/?probe=648ac87a81) | Sep 21, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [faf0bfe427](https://linux-hardware.org/?probe=faf0bfe427) | Sep 17, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [2f99528572](https://linux-hardware.org/?probe=2f99528572) | Sep 16, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [6495df6735](https://linux-hardware.org/?probe=6495df6735) | Sep 15, 2023 |
| Acer          | Aspire C20-820              | All in one  | [1b2bdeafca](https://linux-hardware.org/?probe=1b2bdeafca) | Sep 11, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e59c5b4fda](https://linux-hardware.org/?probe=e59c5b4fda) | Sep 10, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| Toshiba       | Satellite L775D             | Notebook    | [681dab0969](https://linux-hardware.org/?probe=681dab0969) | Sep 09, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [694ffed41f](https://linux-hardware.org/?probe=694ffed41f) | Sep 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [039aa353eb](https://linux-hardware.org/?probe=039aa353eb) | Sep 06, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [101a39c37a](https://linux-hardware.org/?probe=101a39c37a) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [57f24399d5](https://linux-hardware.org/?probe=57f24399d5) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [a7c7baada2](https://linux-hardware.org/?probe=a7c7baada2) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [8b42955659](https://linux-hardware.org/?probe=8b42955659) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Dell          | 0100P6 A01                  | Desktop     | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3e66a1f712](https://linux-hardware.org/?probe=3e66a1f712) | Aug 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b76b1bf00a](https://linux-hardware.org/?probe=b76b1bf00a) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63665fca24](https://linux-hardware.org/?probe=63665fca24) | Aug 08, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [324819c88d](https://linux-hardware.org/?probe=324819c88d) | Aug 08, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Dell          | Precision 7730              | Notebook    | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [48ec623298](https://linux-hardware.org/?probe=48ec623298) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [70c6936cfc](https://linux-hardware.org/?probe=70c6936cfc) | Aug 04, 2023 |
| Dell          | 0RY007                      | Desktop     | [8317045335](https://linux-hardware.org/?probe=8317045335) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [ad4e7cf4ad](https://linux-hardware.org/?probe=ad4e7cf4ad) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [36d9df3244](https://linux-hardware.org/?probe=36d9df3244) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | Notebook    | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [d047b35269](https://linux-hardware.org/?probe=d047b35269) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [af539103c5](https://linux-hardware.org/?probe=af539103c5) | Jul 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [3e6412c30b](https://linux-hardware.org/?probe=3e6412c30b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [c4b019ee7f](https://linux-hardware.org/?probe=c4b019ee7f) | Jul 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d7c21e7889](https://linux-hardware.org/?probe=d7c21e7889) | Jul 13, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [70a6354074](https://linux-hardware.org/?probe=70a6354074) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [4a4b49a909](https://linux-hardware.org/?probe=4a4b49a909) | Jul 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [12871de62d](https://linux-hardware.org/?probe=12871de62d) | Jun 30, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [a4b38b88cc](https://linux-hardware.org/?probe=a4b38b88cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [e28a0d43ed](https://linux-hardware.org/?probe=e28a0d43ed) | Jun 27, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [ee31bf4efe](https://linux-hardware.org/?probe=ee31bf4efe) | Jun 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| Samsung       | 530XBB                      | Notebook    | [51007aebd3](https://linux-hardware.org/?probe=51007aebd3) | Jun 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [190d408bc2](https://linux-hardware.org/?probe=190d408bc2) | Jun 23, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [fa49028492](https://linux-hardware.org/?probe=fa49028492) | Jun 23, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [3055046330](https://linux-hardware.org/?probe=3055046330) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | Notebook    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [2102fc8523](https://linux-hardware.org/?probe=2102fc8523) | Jun 19, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [464db6c1df](https://linux-hardware.org/?probe=464db6c1df) | Jun 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [11161fa30c](https://linux-hardware.org/?probe=11161fa30c) | Jun 18, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | Notebook    | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e25ec87b40](https://linux-hardware.org/?probe=e25ec87b40) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [35c6e2b80e](https://linux-hardware.org/?probe=35c6e2b80e) | Jun 17, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [20a66afa75](https://linux-hardware.org/?probe=20a66afa75) | Jun 14, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [dbf4a1d57c](https://linux-hardware.org/?probe=dbf4a1d57c) | Jun 12, 2023 |
| HP            | 339A                        | Desktop     | [d1fa07d03f](https://linux-hardware.org/?probe=d1fa07d03f) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | 339A                        | Desktop     | [f2147ed11b](https://linux-hardware.org/?probe=f2147ed11b) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [59e64db8de](https://linux-hardware.org/?probe=59e64db8de) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [15b23b6779](https://linux-hardware.org/?probe=15b23b6779) | May 30, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | Notebook    | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2ddb8221f](https://linux-hardware.org/?probe=d2ddb8221f) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | Notebook    | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [689db5f7b4](https://linux-hardware.org/?probe=689db5f7b4) | May 14, 2023 |
| Dell          | Latitude 7370               | Notebook    | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b4861cf35c](https://linux-hardware.org/?probe=b4861cf35c) | Apr 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0f3f45f8e9](https://linux-hardware.org/?probe=0f3f45f8e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [2f61bfa5a5](https://linux-hardware.org/?probe=2f61bfa5a5) | Apr 04, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1e81e330e1](https://linux-hardware.org/?probe=1e81e330e1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Google        | Lillipup                    | Notebook    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASRock        | B560M-C                     | Desktop     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | Desktop     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | 0C1R19 A02                  | Desktop     | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Biostar       | B450MH                      | Desktop     | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| Google        | Robo360                     | Notebook    | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bfb29a2d13](https://linux-hardware.org/?probe=bfb29a2d13) | Feb 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | Notebook    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [6552c7b8b3](https://linux-hardware.org/?probe=6552c7b8b3) | Jan 22, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [64164ef7df](https://linux-hardware.org/?probe=64164ef7df) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [46befb7112](https://linux-hardware.org/?probe=46befb7112) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | Notebook    | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | Notebook    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9496d56fab](https://linux-hardware.org/?probe=9496d56fab) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| HP            | 3397                        | Desktop     | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | G3 3500                     | Notebook    | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | Notebook    | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d57a12d93c](https://linux-hardware.org/?probe=d57a12d93c) | Nov 20, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| Dell          | 0C1R19 A02                  | Desktop     | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                      | Desktop     | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | Notebook    | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Clevo         | W25xHPx                     | Notebook    | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | Notebook    | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | Notebook    | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| HP            | Presario CQ58               | Notebook    | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [7ad1831ce9](https://linux-hardware.org/?probe=7ad1831ce9) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fa26302bd8](https://linux-hardware.org/?probe=fa26302bd8) | Aug 27, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | Notebook    | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [623281f994](https://linux-hardware.org/?probe=623281f994) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f6c3c6f86e](https://linux-hardware.org/?probe=f6c3c6f86e) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c680f5f212](https://linux-hardware.org/?probe=c680f5f212) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Unknown       | TB-4000                     | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Radxa         | ROCK 5B                     | Soc         | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 118       | 21.49%  |
| Parrot 5.3   | 100       | 18.21%  |
| Parrot 4.11  | 98        | 17.85%  |
| Parrot 5.1   | 74        | 13.48%  |
| Parrot 4.10  | 60        | 10.93%  |
| Parrot 5.2   | 35        | 6.38%   |
| Parrot 4.8   | 23        | 4.19%   |
| Parrot 4.9   | 22        | 4.01%   |
| Parrot 4.7   | 13        | 2.37%   |
| Parrot 4.6   | 2         | 0.36%   |
| Parrot 4.5   | 1         | 0.18%   |
| Parrot 4.4   | 1         | 0.18%   |
| Parrot 4.2.2 | 1         | 0.18%   |
| Parrot 3.10  | 1         | 0.18%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 526       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 6.1.0-1parrot1-amd64      | 96        | 17.17%  |
| 5.16.0-12parrot1-amd64    | 56        | 10.02%  |
| 5.14.0-9parrot1-amd64     | 53        | 9.48%   |
| 6.0.0-12parrot1-amd64     | 46        | 8.23%   |
| 5.10.0-6parrot1-amd64     | 35        | 6.26%   |
| 5.18.0-14parrot1-amd64    | 34        | 6.08%   |
| 6.0.0-2parrot1-amd64      | 33        | 5.9%    |
| 5.7.0-2parrot2-amd64      | 33        | 5.9%    |
| 5.5.0-1parrot1-amd64      | 24        | 4.29%   |
| 5.10.0-8parrot1-amd64     | 18        | 3.22%   |
| 5.18.0-1parrot1-amd64     | 17        | 3.04%   |
| 5.4.0-4parrot1-amd64      | 16        | 2.86%   |
| 5.15.0-15parrot1-amd64    | 11        | 1.97%   |
| 5.14.0-2parrot1-amd64     | 11        | 1.97%   |
| 5.6.0-2parrot1-amd64      | 10        | 1.79%   |
| 5.9.0-2parrot1-amd64      | 9         | 1.61%   |
| 5.8.0-2parrot1-amd64      | 6         | 1.07%   |
| 5.4.0-2parrot1-amd64      | 5         | 0.89%   |
| 5.10.0-3parrot1-amd64     | 5         | 0.89%   |
| 5.8.0-1parrot1-amd64      | 4         | 0.72%   |
| 5.10.0-5parrot1-amd64     | 4         | 0.72%   |
| 5.4.0-3parrot1-amd64      | 3         | 0.54%   |
| 5.3.0-3parrot3-amd64      | 3         | 0.54%   |
| 5.2.0-2parrot1-amd64      | 3         | 0.54%   |
| 4.19.0-parrot4-28t-amd64  | 3         | 0.54%   |
| 6.0.5-x64v1-xanmod1       | 2         | 0.36%   |
| 5.10.92-v8+               | 2         | 0.36%   |
| 4.18.0-parrot10-amd64     | 2         | 0.36%   |
| 6.1.27chrultrabook-fixups | 1         | 0.18%   |
| 6.1.0-0.deb11.5-amd64     | 1         | 0.18%   |
| 5.7.0-rc6-galliumos       | 1         | 0.18%   |
| 5.4.0-2parrot1-686-pae    | 1         | 0.18%   |
| 5.4.0-1parrot1-amd64      | 1         | 0.18%   |
| 5.3.0-3parrot3-686-pae    | 1         | 0.18%   |
| 5.3.0-1parrot1-amd64      | 1         | 0.18%   |
| 5.16.0-12parrot1-686-pae  | 1         | 0.18%   |
| 5.15.0-5parrot1-amd64     | 1         | 0.18%   |
| 5.10.0-kali6-amd64        | 1         | 0.18%   |
| 5.10.0-6parrot1-rt-amd64  | 1         | 0.18%   |
| 5.1.0-parrot1-3t-amd64    | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 97        | 17.48%  |
| 6.0.0   | 78        | 14.05%  |
| 5.10.0  | 64        | 11.53%  |
| 5.14.0  | 62        | 11.17%  |
| 5.16.0  | 57        | 10.27%  |
| 5.18.0  | 50        | 9.01%   |
| 5.7.0   | 34        | 6.13%   |
| 5.4.0   | 26        | 4.68%   |
| 5.5.0   | 24        | 4.32%   |
| 5.15.0  | 12        | 2.16%   |
| 5.8.0   | 10        | 1.8%    |
| 5.6.0   | 10        | 1.8%    |
| 5.9.0   | 9         | 1.62%   |
| 5.3.0   | 5         | 0.9%    |
| 4.19.0  | 4         | 0.72%   |
| 5.2.0   | 3         | 0.54%   |
| 6.0.5   | 2         | 0.36%   |
| 5.10.92 | 2         | 0.36%   |
| 4.18.0  | 2         | 0.36%   |
| 6.1.27  | 1         | 0.18%   |
| 5.1.0   | 1         | 0.18%   |
| 4.14.0  | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 98        | 17.66%  |
| 6.0     | 80        | 14.41%  |
| 5.10    | 66        | 11.89%  |
| 5.14    | 62        | 11.17%  |
| 5.16    | 57        | 10.27%  |
| 5.18    | 50        | 9.01%   |
| 5.7     | 34        | 6.13%   |
| 5.4     | 26        | 4.68%   |
| 5.5     | 24        | 4.32%   |
| 5.15    | 12        | 2.16%   |
| 5.8     | 10        | 1.8%    |
| 5.6     | 10        | 1.8%    |
| 5.9     | 9         | 1.62%   |
| 5.3     | 5         | 0.9%    |
| 4.19    | 4         | 0.72%   |
| 5.2     | 3         | 0.54%   |
| 4.18    | 2         | 0.36%   |
| 5.1     | 1         | 0.18%   |
| 4.14    | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 522       | 99.24%  |
| i686    | 2         | 0.38%   |
| aarch64 | 2         | 0.38%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| MATE            | 396       | 73.33%  |
| KDE5            | 76        | 14.07%  |
| Unknown         | 23        | 4.26%   |
| KDE             | 20        | 3.7%    |
| XFCE            | 14        | 2.59%   |
| GNOME           | 4         | 0.74%   |
| X-Cinnamon      | 2         | 0.37%   |
| LXDE            | 1         | 0.19%   |
| GNOME Flashback | 1         | 0.19%   |
| GNOME Classic   | 1         | 0.19%   |
| Cinnamon        | 1         | 0.19%   |
| bspwm           | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 516       | 98.1%   |
| Wayland | 4         | 0.76%   |
| Tty     | 4         | 0.76%   |
| Unknown | 2         | 0.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 284       | 52.69%  |
| Unknown | 161       | 29.87%  |
| TDM     | 71        | 13.17%  |
| SDDM    | 14        | 2.6%    |
| GDM     | 9         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 293       | 55.49%  |
| en_GB   | 33        | 6.25%   |
| fr_FR   | 21        | 3.98%   |
| ru_RU   | 16        | 3.03%   |
| es_ES   | 16        | 3.03%   |
| de_DE   | 16        | 3.03%   |
| en_AU   | 15        | 2.84%   |
| Unknown | 15        | 2.84%   |
| en_IN   | 14        | 2.65%   |
| pt_BR   | 11        | 2.08%   |
| pl_PL   | 11        | 2.08%   |
| it_IT   | 10        | 1.89%   |
| en_CA   | 6         | 1.14%   |
| es_MX   | 4         | 0.76%   |
| cs_CZ   | 4         | 0.76%   |
| tr_TR   | 3         | 0.57%   |
| es_CO   | 3         | 0.57%   |
| es_AR   | 3         | 0.57%   |
| id_ID   | 2         | 0.38%   |
| es_PE   | 2         | 0.38%   |
| es_CL   | 2         | 0.38%   |
| en_ZA   | 2         | 0.38%   |
| en_NZ   | 2         | 0.38%   |
| en_IE   | 2         | 0.38%   |
| en_HK   | 2         | 0.38%   |
| en_DK   | 2         | 0.38%   |
| C       | 2         | 0.38%   |
| sk_SK   | 1         | 0.19%   |
| ru_UA   | 1         | 0.19%   |
| pt_PT   | 1         | 0.19%   |
| nl_BE   | 1         | 0.19%   |
| nb_NO   | 1         | 0.19%   |
| mk_MK   | 1         | 0.19%   |
| fr_CH   | 1         | 0.19%   |
| fr_CA   | 1         | 0.19%   |
| fi_FI   | 1         | 0.19%   |
| en_ZW   | 1         | 0.19%   |
| en_ZM   | 1         | 0.19%   |
| en_NG   | 1         | 0.19%   |
| de_CH   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 297       | 55.51%  |
| EFI  | 238       | 44.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 413       | 77.63%  |
| Ext4    | 69        | 12.97%  |
| Overlay | 19        | 3.57%   |
| Xfs     | 14        | 2.63%   |
| Tmpfs   | 10        | 1.88%   |
| Unknown | 7         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 255       | 47.4%   |
| Unknown | 194       | 36.06%  |
| MBR     | 89        | 16.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 461       | 86.49%  |
| Yes       | 72        | 13.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 338       | 63.65%  |
| Yes       | 193       | 36.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 92        | 17.49%  |
| Lenovo                               | 86        | 16.35%  |
| Dell                                 | 76        | 14.45%  |
| ASUSTek Computer                     | 76        | 14.45%  |
| MSI                                  | 32        | 6.08%   |
| Acer                                 | 31        | 5.89%   |
| Gigabyte Technology                  | 19        | 3.61%   |
| Apple                                | 15        | 2.85%   |
| Toshiba                              | 9         | 1.71%   |
| Samsung Electronics                  | 8         | 1.52%   |
| Unknown                              | 6         | 1.14%   |
| HUAWEI                               | 5         | 0.95%   |
| Alienware                            | 5         | 0.95%   |
| Microsoft                            | 4         | 0.76%   |
| ASRock                               | 4         | 0.76%   |
| Sony                                 | 3         | 0.57%   |
| Google                               | 3         | 0.57%   |
| Gateway                              | 3         | 0.57%   |
| Fujitsu                              | 3         | 0.57%   |
| Foxconn                              | 3         | 0.57%   |
| Razer                                | 2         | 0.38%   |
| Raspberry Pi Foundation              | 2         | 0.38%   |
| Quanta                               | 2         | 0.38%   |
| Positivo                             | 2         | 0.38%   |
| Pegatron                             | 2         | 0.38%   |
| Notebook                             | 2         | 0.38%   |
| ECS                                  | 2         | 0.38%   |
| Biostar                              | 2         | 0.38%   |
| ZOTAC                                | 1         | 0.19%   |
| Wortmann AG                          | 1         | 0.19%   |
| Wistron                              | 1         | 0.19%   |
| Toxic                                | 1         | 0.19%   |
| Timi                                 | 1         | 0.19%   |
| System76                             | 1         | 0.19%   |
| Standard                             | 1         | 0.19%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.19%   |
| Radxa                                | 1         | 0.19%   |
| Positivo Bahia - VAIO                | 1         | 0.19%   |
| Panasonic                            | 1         | 0.19%   |
| Onda TLC                             | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 9         | 1.71%   |
| HP Notebook                          | 4         | 0.76%   |
| HP Laptop 15-dy2xxx                  | 4         | 0.76%   |
| MSI Modern 15 A5M                    | 3         | 0.57%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 3         | 0.57%   |
| HP Pavilion 15                       | 3         | 0.57%   |
| HP ENVY x360 Convertible 13-bd0xxx   | 3         | 0.57%   |
| HP EliteBook 8470p                   | 3         | 0.57%   |
| Dell Latitude E6420                  | 3         | 0.57%   |
| Dell Inspiron MM061                  | 3         | 0.57%   |
| ASUS M5A78L-M/USB3                   | 3         | 0.57%   |
| Toshiba Satellite L775D              | 2         | 0.38%   |
| RPi Raspberry Pi 4 Model B Rev 1.5   | 2         | 0.38%   |
| Quanta TW9/SW9                       | 2         | 0.38%   |
| MSI Katana GF66 12UC                 | 2         | 0.38%   |
| Microsoft Surface Pro 3              | 2         | 0.38%   |
| HP ProDesk 600 G1 SFF                | 2         | 0.38%   |
| HP ProBook 650 G1                    | 2         | 0.38%   |
| HP Pavilion dv6                      | 2         | 0.38%   |
| HP ENVY x360 2-in-1 Laptop 15-ew0xxx | 2         | 0.38%   |
| HP Compaq 8200 Elite SFF PC          | 2         | 0.38%   |
| Gigabyte AX370-Gaming                | 2         | 0.38%   |
| Foxconn s5710t                       | 2         | 0.38%   |
| Dell OptiPlex 7010                   | 2         | 0.38%   |
| Dell OptiPlex 3020                   | 2         | 0.38%   |
| Dell Latitude E7440                  | 2         | 0.38%   |
| Dell Latitude E6410                  | 2         | 0.38%   |
| Dell Latitude 7280                   | 2         | 0.38%   |
| Dell Inspiron N5110                  | 2         | 0.38%   |
| Dell Inspiron 5676                   | 2         | 0.38%   |
| ASUS Q524UQ                          | 2         | 0.38%   |
| ASUS PRIME X399-A                    | 2         | 0.38%   |
| ASUS M5A99X EVO                      | 2         | 0.38%   |
| ASUS H110I-PLUS                      | 2         | 0.38%   |
| ASUS Basic 3221BM                    | 2         | 0.38%   |
| Apple MacBookPro8,1                  | 2         | 0.38%   |
| Apple MacBookAir7,2                  | 2         | 0.38%   |
| Apple iMac9,1                        | 2         | 0.38%   |
| Acer Nitro AN515-57                  | 2         | 0.38%   |
| Acer Nitro AN515-54                  | 2         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 44        | 8.37%   |
| Dell Latitude     | 25        | 4.75%   |
| Dell Inspiron     | 24        | 4.56%   |
| Lenovo IdeaPad    | 19        | 3.61%   |
| HP Pavilion       | 17        | 3.23%   |
| Acer Aspire       | 16        | 3.04%   |
| HP Laptop         | 14        | 2.66%   |
| HP EliteBook      | 13        | 2.47%   |
| HP ENVY           | 11        | 2.09%   |
| Dell OptiPlex     | 9         | 1.71%   |
| Unknown           | 9         | 1.71%   |
| Toshiba Satellite | 8         | 1.52%   |
| HP Compaq         | 8         | 1.52%   |
| ASUS PRIME        | 8         | 1.52%   |
| HP ProBook        | 7         | 1.33%   |
| MSI Katana        | 6         | 1.14%   |
| Dell XPS          | 6         | 1.14%   |
| ASUS VivoBook     | 6         | 1.14%   |
| ASUS ROG          | 6         | 1.14%   |
| Acer Nitro        | 6         | 1.14%   |
| ASUS ASUS         | 5         | 0.95%   |
| Microsoft Surface | 4         | 0.76%   |
| Lenovo Legion     | 4         | 0.76%   |
| HP ZBook          | 4         | 0.76%   |
| HP Notebook       | 4         | 0.76%   |
| Dell Vostro       | 4         | 0.76%   |
| Dell Precision    | 4         | 0.76%   |
| MSI Modern        | 3         | 0.57%   |
| Lenovo Yoga       | 3         | 0.57%   |
| HP Victus         | 3         | 0.57%   |
| HP ProDesk        | 3         | 0.57%   |
| Fujitsu LIFEBOOK  | 3         | 0.57%   |
| ASUS Zenbook      | 3         | 0.57%   |
| ASUS TUF          | 3         | 0.57%   |
| ASUS M5A78L-M     | 3         | 0.57%   |
| Acer Swift        | 3         | 0.57%   |
| Acer Predator     | 3         | 0.57%   |
| Razer Blade       | 2         | 0.38%   |
| RPi Raspberry     | 2         | 0.38%   |
| Quanta TW9        | 2         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 63        | 11.98%  |
| 2019    | 54        | 10.27%  |
| 2011    | 51        | 9.7%    |
| 2020    | 43        | 8.17%   |
| 2018    | 42        | 7.98%   |
| 2012    | 39        | 7.41%   |
| 2013    | 37        | 7.03%   |
| 2016    | 35        | 6.65%   |
| 2022    | 33        | 6.27%   |
| 2017    | 28        | 5.32%   |
| 2014    | 21        | 3.99%   |
| 2015    | 20        | 3.8%    |
| 2010    | 20        | 3.8%    |
| 2009    | 10        | 1.9%    |
| 2007    | 9         | 1.71%   |
| 2008    | 8         | 1.52%   |
| 2023    | 7         | 1.33%   |
| 2006    | 4         | 0.76%   |
| Unknown | 2         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 368       | 69.96%  |
| Desktop        | 123       | 23.38%  |
| Convertible    | 19        | 3.61%   |
| Tablet         | 5         | 0.95%   |
| All in one     | 5         | 0.95%   |
| System on chip | 3         | 0.57%   |
| Mini pc        | 3         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 526       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 523       | 99.43%  |
| Yes  | 3         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 139       | 26.08%  |
| 16.01-24.0  | 123       | 23.08%  |
| 8.01-16.0   | 112       | 21.01%  |
| 3.01-4.0    | 80        | 15.01%  |
| 32.01-64.0  | 46        | 8.63%   |
| 1.01-2.0    | 13        | 2.44%   |
| 64.01-256.0 | 10        | 1.88%   |
| 24.01-32.0  | 7         | 1.31%   |
| 2.01-3.0    | 3         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 190       | 34.17%  |
| 1.01-2.0   | 175       | 31.47%  |
| 3.01-4.0   | 81        | 14.57%  |
| 4.01-8.0   | 71        | 12.77%  |
| 0.51-1.0   | 23        | 4.14%   |
| 8.01-16.0  | 11        | 1.98%   |
| 0.01-0.5   | 3         | 0.54%   |
| 16.01-24.0 | 2         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 328       | 60.97%  |
| 2      | 160       | 29.74%  |
| 3      | 29        | 5.39%   |
| 4      | 12        | 2.23%   |
| 5      | 5         | 0.93%   |
| 6      | 2         | 0.37%   |
| 0      | 2         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 384       | 72.32%  |
| Yes       | 147       | 27.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 433       | 82.16%  |
| No        | 94        | 17.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 481       | 90.93%  |
| No        | 48        | 9.07%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 371       | 69.74%  |
| No        | 161       | 30.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 167       | 31.45%  |
| Germany      | 33        | 6.21%   |
| Spain        | 21        | 3.95%   |
| France       | 21        | 3.95%   |
| UK           | 19        | 3.58%   |
| Russia       | 19        | 3.58%   |
| India        | 18        | 3.39%   |
| Italy        | 17        | 3.2%    |
| Brazil       | 17        | 3.2%    |
| Netherlands  | 16        | 3.01%   |
| Australia    | 13        | 2.45%   |
| Canada       | 12        | 2.26%   |
| Mexico       | 10        | 1.88%   |
| Kenya        | 8         | 1.51%   |
| Sweden       | 6         | 1.13%   |
| Poland       | 6         | 1.13%   |
| Indonesia    | 6         | 1.13%   |
| Czechia      | 6         | 1.13%   |
| Turkey       | 5         | 0.94%   |
| Denmark      | 5         | 0.94%   |
| Bangladesh   | 5         | 0.94%   |
| Algeria      | 5         | 0.94%   |
| Switzerland  | 4         | 0.75%   |
| South Africa | 4         | 0.75%   |
| Austria      | 4         | 0.75%   |
| Portugal     | 3         | 0.56%   |
| Pakistan     | 3         | 0.56%   |
| Nepal        | 3         | 0.56%   |
| Mongolia     | 3         | 0.56%   |
| Luxembourg   | 3         | 0.56%   |
| Iraq         | 3         | 0.56%   |
| Finland      | 3         | 0.56%   |
| Egypt        | 3         | 0.56%   |
| Colombia     | 3         | 0.56%   |
| Chile        | 3         | 0.56%   |
| Bulgaria     | 3         | 0.56%   |
| Argentina    | 3         | 0.56%   |
| Vietnam      | 2         | 0.38%   |
| Puerto Rico  | 2         | 0.38%   |
| Peru         | 2         | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 8         | 1.45%   |
| Nairobi             | 7         | 1.27%   |
| Dallas              | 6         | 1.09%   |
| Saint Paul          | 5         | 0.91%   |
| Moscow              | 5         | 0.91%   |
| Melbourne           | 5         | 0.91%   |
| Berlin              | 5         | 0.91%   |
| Sydney              | 4         | 0.72%   |
| Seattle             | 4         | 0.72%   |
| Madrid              | 4         | 0.72%   |
| Lyon                | 4         | 0.72%   |
| Los Angeles         | 4         | 0.72%   |
| London              | 4         | 0.72%   |
| Houston             | 4         | 0.72%   |
| Dublin              | 4         | 0.72%   |
| Dhaka               | 4         | 0.72%   |
| Chicago             | 4         | 0.72%   |
| Barcelona           | 4         | 0.72%   |
| Atlanta             | 4         | 0.72%   |
| Warsaw              | 3         | 0.54%   |
| Vienna              | 3         | 0.54%   |
| Ulan Bator          | 3         | 0.54%   |
| Stockholm           | 3         | 0.54%   |
| Rome                | 3         | 0.54%   |
| Prague              | 3         | 0.54%   |
| Pensacola           | 3         | 0.54%   |
| Paris               | 3         | 0.54%   |
| Luxembourg          | 3         | 0.54%   |
| Indianapolis        | 3         | 0.54%   |
| Eugene              | 3         | 0.54%   |
| Chennai             | 3         | 0.54%   |
| Zurich              | 2         | 0.36%   |
| Visalia             | 2         | 0.36%   |
| Villa del Rio       | 2         | 0.36%   |
| Uherské Hradiště | 2         | 0.36%   |
| Toronto             | 2         | 0.36%   |
| Tokyo               | 2         | 0.36%   |
| Tangier             | 2         | 0.36%   |
| St Petersburg       | 2         | 0.36%   |
| Sao Paulo           | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 113       | 145    | 15.35%  |
| WDC                         | 106       | 137    | 14.4%   |
| Seagate                     | 83        | 105    | 11.28%  |
| Toshiba                     | 74        | 81     | 10.05%  |
| Unknown                     | 41        | 43     | 5.57%   |
| Kingston                    | 41        | 43     | 5.57%   |
| SanDisk                     | 32        | 41     | 4.35%   |
| SK hynix                    | 25        | 30     | 3.4%    |
| Hitachi                     | 25        | 31     | 3.4%    |
| Micron Technology           | 21        | 21     | 2.85%   |
| Crucial                     | 20        | 25     | 2.72%   |
| HGST                        | 17        | 20     | 2.31%   |
| Intel                       | 14        | 29     | 1.9%    |
| A-DATA Technology           | 12        | 12     | 1.63%   |
| China                       | 8         | 11     | 1.09%   |
| Apple                       | 8         | 8      | 1.09%   |
| KIOXIA                      | 7         | 8      | 0.95%   |
| Team                        | 5         | 6      | 0.68%   |
| SPCC                        | 5         | 5      | 0.68%   |
| Phison                      | 4         | 4      | 0.54%   |
| LITEON                      | 4         | 4      | 0.54%   |
| YMTC                        | 3         | 3      | 0.41%   |
| Silicon Motion              | 3         | 3      | 0.41%   |
| PNY                         | 3         | 3      | 0.41%   |
| LITEONIT                    | 3         | 3      | 0.41%   |
| Kingston Technology Company | 3         | 4      | 0.41%   |
| KingFast                    | 3         | 4      | 0.41%   |
| JMicron Technology          | 3         | 3      | 0.41%   |
| Intenso                     | 3         | 4      | 0.41%   |
| Fujitsu                     | 3         | 3      | 0.41%   |
| Unknown                     | 3         | 3      | 0.41%   |
| Lexar                       | 2         | 2      | 0.27%   |
| HUAWEI                      | 2         | 2      | 0.27%   |
| Corsair                     | 2         | 3      | 0.27%   |
| BR                          | 2         | 2      | 0.27%   |
| Apacer                      | 2         | 3      | 0.27%   |
| Zheino                      | 1         | 1      | 0.14%   |
| Wdxsky                      | 1         | 1      | 0.14%   |
| W800SH                      | 1         | 1      | 0.14%   |
| Unknown (583)               | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 10        | 1.25%   |
| Samsung SSD 860 EVO 500GB            | 9         | 1.12%   |
| Unknown SD/MMC/MS PRO 16GB           | 7         | 0.87%   |
| Toshiba MQ01ABF050 500GB             | 7         | 0.87%   |
| Toshiba MQ01ABD100 1TB               | 7         | 0.87%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 0.87%   |
| Toshiba DT01ACA200 2TB               | 6         | 0.75%   |
| Unknown MMC Card  32GB               | 5         | 0.62%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 5         | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.62%   |
| Samsung SSD 850 EVO 250GB            | 5         | 0.62%   |
| Kingston NVMe SSD Drive 512GB        | 5         | 0.62%   |
| HGST HTS721010A9E630 1TB             | 5         | 0.62%   |
| HGST HTS541010A9E680 1TB             | 5         | 0.62%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 0.5%    |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 0.5%    |
| Seagate ST31000528AS 1TB             | 4         | 0.5%    |
| SanDisk SSD PLUS 1000GB              | 4         | 0.5%    |
| Samsung SSD 980 1TB                  | 4         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.5%    |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.5%    |
| Intel HBRPEKNX0202AH 512GB           | 4         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB          | 3         | 0.37%   |
| WDC WD10SPZX-75Z10T2 1TB             | 3         | 0.37%   |
| Toshiba MQ01ABD075 752GB             | 3         | 0.37%   |
| Toshiba KXG6AZNV256G 256GB           | 3         | 0.37%   |
| Toshiba DT01ACA050 500GB             | 3         | 0.37%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 3         | 0.37%   |
| Seagate ST9250315AS 250GB            | 3         | 0.37%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.37%   |
| Seagate ST250DM000-1BD141 250GB      | 3         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.37%   |
| Seagate Expansion 1TB                | 3         | 0.37%   |
| SanDisk NVMe SSD Drive 1TB           | 3         | 0.37%   |
| Samsung SSD 980 PRO 1TB              | 3         | 0.37%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.37%   |
| Samsung HM500JI 500GB                | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 104    | 29.29%  |
| WDC                 | 75        | 99     | 26.79%  |
| Toshiba             | 60        | 65     | 21.43%  |
| Hitachi             | 25        | 31     | 8.93%   |
| HGST                | 17        | 20     | 6.07%   |
| Samsung Electronics | 11        | 13     | 3.93%   |
| Unknown             | 7         | 8      | 2.5%    |
| Fujitsu             | 1         | 1      | 0.36%   |
| CLOVER              | 1         | 1      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 61     | 21.05%  |
| Kingston            | 24        | 26     | 11.48%  |
| SanDisk             | 17        | 19     | 8.13%   |
| Crucial             | 16        | 21     | 7.66%   |
| WDC                 | 15        | 16     | 7.18%   |
| China               | 8         | 11     | 3.83%   |
| Micron Technology   | 5         | 5      | 2.39%   |
| Apple               | 5         | 5      | 2.39%   |
| A-DATA Technology   | 5         | 5      | 2.39%   |
| Toshiba             | 4         | 5      | 1.91%   |
| Team                | 4         | 5      | 1.91%   |
| LITEON              | 4         | 4      | 1.91%   |
| SPCC                | 3         | 3      | 1.44%   |
| SK hynix            | 3         | 3      | 1.44%   |
| PNY                 | 3         | 3      | 1.44%   |
| LITEONIT            | 3         | 3      | 1.44%   |
| KingFast            | 3         | 3      | 1.44%   |
| Intenso             | 3         | 4      | 1.44%   |
| Unknown             | 2         | 2      | 0.96%   |
| Intel               | 2         | 2      | 0.96%   |
| Fujitsu             | 2         | 2      | 0.96%   |
| Corsair             | 2         | 3      | 0.96%   |
| BR                  | 2         | 2      | 0.96%   |
| Apacer              | 2         | 3      | 0.96%   |
| Unknown             | 2         | 2      | 0.96%   |
| Zheino              | 1         | 1      | 0.48%   |
| Wdxsky              | 1         | 1      | 0.48%   |
| W800SH              | 1         | 1      | 0.48%   |
| Transcend           | 1         | 1      | 0.48%   |
| Teclast             | 1         | 1      | 0.48%   |
| Seagate             | 1         | 1      | 0.48%   |
| SCY                 | 1         | 1      | 0.48%   |
| S3+                 | 1         | 1      | 0.48%   |
| RZX                 | 1         | 1      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| OCZ                 | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Lexar               | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 2      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 239       | 343    | 36.1%   |
| NVMe    | 199       | 258    | 30.06%  |
| SSD     | 187       | 245    | 28.25%  |
| MMC     | 31        | 35     | 4.68%   |
| Unknown | 6         | 6      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 356       | 563    | 57.89%  |
| NVMe | 196       | 254    | 31.87%  |
| SAS  | 32        | 35     | 5.2%    |
| MMC  | 31        | 35     | 5.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 257       | 368    | 58.41%  |
| 0.51-1.0   | 144       | 172    | 32.73%  |
| 1.01-2.0   | 27        | 33     | 6.14%   |
| 3.01-4.0   | 5         | 6      | 1.14%   |
| 2.01-3.0   | 4         | 6      | 0.91%   |
| 4.01-10.0  | 2         | 2      | 0.45%   |
| 10.01-20.0 | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 131       | 24.21%  |
| 101-250        | 107       | 19.78%  |
| 501-1000       | 101       | 18.67%  |
| 1001-2000      | 62        | 11.46%  |
| Unknown        | 51        | 9.43%   |
| 51-100         | 30        | 5.55%   |
| 21-50          | 19        | 3.51%   |
| 1-20           | 17        | 3.14%   |
| More than 3000 | 13        | 2.4%    |
| 2001-3000      | 10        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 170       | 30.74%  |
| 51-100         | 95        | 17.18%  |
| 1-20           | 84        | 15.19%  |
| 101-250        | 76        | 13.74%  |
| Unknown        | 51        | 9.22%   |
| 251-500        | 44        | 7.96%   |
| 501-1000       | 20        | 3.62%   |
| 1001-2000      | 7         | 1.27%   |
| More than 3000 | 3         | 0.54%   |
| 0              | 2         | 0.36%   |
| 2001-3000      | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB    | 3         | 3      | 4%      |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 2.67%   |
| SanDisk SD6SF1M128G1022I 128GB SSD   | 2         | 3      | 2.67%   |
| LITEON CV8-8E128-HP 128GB SSD        | 2         | 2      | 2.67%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1      | 1.33%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 1      | 1.33%   |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 1      | 1.33%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1      | 1.33%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 1      | 1.33%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 1      | 1.33%   |
| WDC WD10JUCX-63WPNY0 1TB             | 1         | 1      | 1.33%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1      | 1.33%   |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 1.33%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.33%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 1.33%   |
| Toshiba MK5059GSXP 500GB             | 1         | 1      | 1.33%   |
| Toshiba MK3265GSXF 320GB             | 1         | 1      | 1.33%   |
| Toshiba DT01ACA050 500GB             | 1         | 1      | 1.33%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1      | 1.33%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.33%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.33%   |
| Seagate ST9250410AS 250GB            | 1         | 1      | 1.33%   |
| Seagate ST500NM0011 500GB            | 1         | 1      | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 1.33%   |
| Seagate ST380215AS 80GB              | 1         | 1      | 1.33%   |
| Seagate ST3802110A 80GB              | 1         | 1      | 1.33%   |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.33%   |
| Seagate ST3320418AS 320GB            | 1         | 1      | 1.33%   |
| Seagate ST3250824AS 250GB            | 1         | 1      | 1.33%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 1      | 1.33%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 1      | 1.33%   |
| Seagate ST3160215AS 160GB            | 1         | 1      | 1.33%   |
| Seagate ST31000528AS 1TB             | 1         | 1      | 1.33%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 1      | 1.33%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1      | 1.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 2      | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 1.33%   |
| Seagate ST1000DM010-2EP102 1TB       | 1         | 1      | 1.33%   |
| SanDisk SSD U100 24GB                | 1         | 1      | 1.33%   |
| SanDisk SSD PLUS 480GB               | 1         | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 19     | 20.83%  |
| WDC                 | 9         | 9      | 12.5%   |
| Samsung Electronics | 8         | 9      | 11.11%  |
| Toshiba             | 7         | 7      | 9.72%   |
| Hitachi             | 7         | 7      | 9.72%   |
| SanDisk             | 6         | 7      | 8.33%   |
| HGST                | 3         | 3      | 4.17%   |
| A-DATA Technology   | 3         | 3      | 4.17%   |
| LITEON              | 2         | 2      | 2.78%   |
| SPCC                | 1         | 1      | 1.39%   |
| SK hynix            | 1         | 1      | 1.39%   |
| Plextor             | 1         | 1      | 1.39%   |
| Micron Technology   | 1         | 1      | 1.39%   |
| Kingston            | 1         | 1      | 1.39%   |
| Intenso             | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |
| Crucial             | 1         | 1      | 1.39%   |
| CLOVER              | 1         | 1      | 1.39%   |
| Unknown             | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 19     | 30.61%  |
| WDC                 | 9         | 9      | 18.37%  |
| Toshiba             | 7         | 7      | 14.29%  |
| Hitachi             | 7         | 7      | 14.29%  |
| Samsung Electronics | 6         | 6      | 12.24%  |
| HGST                | 3         | 3      | 6.12%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| CLOVER              | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 53     | 65.15%  |
| SSD  | 18        | 20     | 27.27%  |
| NVMe | 5         | 5      | 7.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 50%     |
| Intenso SSD SATAIII 512GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Intenso | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 287       | 387    | 47.99%  |
| Detected | 248       | 420    | 41.47%  |
| Malfunc  | 61        | 78     | 10.2%   |
| Failed   | 2         | 2      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 357       | 54.42%  |
| AMD                            | 80        | 12.2%   |
| Samsung Electronics            | 65        | 9.91%   |
| SanDisk                        | 33        | 5.03%   |
| SK hynix                       | 22        | 3.35%   |
| Kingston Technology Company    | 19        | 2.9%    |
| Micron Technology              | 16        | 2.44%   |
| Toshiba America Info Systems   | 10        | 1.52%   |
| Nvidia                         | 8         | 1.22%   |
| KIOXIA                         | 7         | 1.07%   |
| ASMedia Technology             | 6         | 0.91%   |
| Silicon Motion                 | 5         | 0.76%   |
| Phison Electronics             | 5         | 0.76%   |
| Micron/Crucial Technology      | 5         | 0.76%   |
| ADATA Technology               | 5         | 0.76%   |
| Yangtze Memory Technologies    | 3         | 0.46%   |
| Realtek Semiconductor          | 3         | 0.46%   |
| JMicron Technology             | 3         | 0.46%   |
| VIA Technologies               | 1         | 0.15%   |
| Solid State Storage Technology | 1         | 0.15%   |
| Marvell Technology Group       | 1         | 0.15%   |
| Apple                          | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 58        | 7.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 37        | 4.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 35        | 4.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26        | 3.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 26        | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 22        | 2.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 16        | 2.15%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 13        | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 1.75%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 12        | 1.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 12        | 1.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 1.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11        | 1.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9         | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 7         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 7         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7         | 0.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 0.94%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 6         | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 0.81%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                      | 6         | 0.81%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6         | 0.81%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 6         | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 0.81%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 6         | 0.81%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 6         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 6         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 0.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 0.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 5         | 0.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 5         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 352       | 52.46%  |
| NVMe | 196       | 29.21%  |
| RAID | 66        | 9.84%   |
| IDE  | 57        | 8.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 424       | 80.61%  |
| AMD    | 100       | 19.01%  |
| ARM    | 2         | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 2.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 2.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 1.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.14%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.95%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 0.95%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.95%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.95%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.76%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.76%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.76%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.76%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.76%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.57%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.57%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.57%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.57%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 0.57%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 3         | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 123       | 23.38%  |
| Intel Core i7           | 104       | 19.77%  |
| Other                   | 83        | 15.78%  |
| Intel Core i3           | 45        | 8.56%   |
| AMD Ryzen 7             | 24        | 4.56%   |
| Intel Celeron           | 22        | 4.18%   |
| AMD Ryzen 5             | 22        | 4.18%   |
| Intel Core 2 Duo        | 15        | 2.85%   |
| AMD A6                  | 9         | 1.71%   |
| AMD FX                  | 8         | 1.52%   |
| Intel Pentium           | 7         | 1.33%   |
| Intel Pentium Dual-Core | 6         | 1.14%   |
| Intel Xeon              | 5         | 0.95%   |
| AMD Ryzen 3             | 5         | 0.95%   |
| Intel Core 2            | 4         | 0.76%   |
| AMD A4                  | 4         | 0.76%   |
| Intel Pentium Silver    | 3         | 0.57%   |
| Intel Atom              | 3         | 0.57%   |
| AMD Ryzen 9             | 3         | 0.57%   |
| AMD E1                  | 3         | 0.57%   |
| Intel Core i9           | 2         | 0.38%   |
| Intel Core 2 Quad       | 2         | 0.38%   |
| AMD Ryzen Threadripper  | 2         | 0.38%   |
| AMD Phenom II X4        | 2         | 0.38%   |
| AMD Athlon II X2        | 2         | 0.38%   |
| AMD A8                  | 2         | 0.38%   |
| AMD A10                 | 2         | 0.38%   |
| Intel Pentium Dual      | 1         | 0.19%   |
| Intel Genuine           | 1         | 0.19%   |
| Intel Core m5           | 1         | 0.19%   |
| Intel Core M            | 1         | 0.19%   |
| Intel Core 2 Extreme    | 1         | 0.19%   |
| AMD Sempron             | 1         | 0.19%   |
| AMD Ryzen 5 PRO         | 1         | 0.19%   |
| AMD Phenom              | 1         | 0.19%   |
| AMD E2                  | 1         | 0.19%   |
| AMD E                   | 1         | 0.19%   |
| AMD C-50                | 1         | 0.19%   |
| AMD Athlon X2           | 1         | 0.19%   |
| AMD Athlon 64 X2        | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 220       | 41.83%  |
| 4      | 178       | 33.84%  |
| 6      | 47        | 8.94%   |
| 8      | 31        | 5.89%   |
| 12     | 14        | 2.66%   |
| 10     | 14        | 2.66%   |
| 14     | 9         | 1.71%   |
| 1      | 7         | 1.33%   |
| 3      | 3         | 0.57%   |
| 16     | 2         | 0.38%   |
| 24     | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 525       | 99.81%  |
| 2      | 1         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 359       | 68.25%  |
| 1      | 166       | 31.56%  |
| 8      | 1         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 521       | 99.05%  |
| Unknown        | 5         | 0.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 228       | 42.3%   |
| 0x206a7    | 28        | 5.19%   |
| 0x806c1    | 22        | 4.08%   |
| 0x306a9    | 20        | 3.71%   |
| 0x906a3    | 17        | 3.15%   |
| 0x806ec    | 15        | 2.78%   |
| 0x406e3    | 14        | 2.6%    |
| 0xa0652    | 11        | 2.04%   |
| 0x906ea    | 10        | 1.86%   |
| 0x806e9    | 10        | 1.86%   |
| 0x906a4    | 9         | 1.67%   |
| 0x806ea    | 9         | 1.67%   |
| 0x306c3    | 9         | 1.67%   |
| 0x906e9    | 8         | 1.48%   |
| 0x706a8    | 7         | 1.3%    |
| 0x40651    | 7         | 1.3%    |
| 0x1067a    | 7         | 1.3%    |
| 0x0a50000c | 7         | 1.3%    |
| 0x806d1    | 6         | 1.11%   |
| 0x08108109 | 6         | 1.11%   |
| 0x706e5    | 5         | 0.93%   |
| 0x6f6      | 4         | 0.74%   |
| 0x406c4    | 4         | 0.74%   |
| 0x306d4    | 4         | 0.74%   |
| 0x08608103 | 4         | 0.74%   |
| 0x08600106 | 4         | 0.74%   |
| 0x06006705 | 4         | 0.74%   |
| 0x90672    | 3         | 0.56%   |
| 0x07030105 | 3         | 0.56%   |
| 0x06000852 | 3         | 0.56%   |
| 0x03000027 | 3         | 0.56%   |
| 0x010000c8 | 3         | 0.56%   |
| 0xb06a2    | 2         | 0.37%   |
| 0xb0671    | 2         | 0.37%   |
| 0x906ed    | 2         | 0.37%   |
| 0x806eb    | 2         | 0.37%   |
| 0x806c2    | 2         | 0.37%   |
| 0x706a1    | 2         | 0.37%   |
| 0x6fd      | 2         | 0.37%   |
| 0x506c9    | 2         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 90        | 17.11%  |
| SandyBridge      | 48        | 9.13%   |
| Haswell          | 37        | 7.03%   |
| IvyBridge        | 35        | 6.65%   |
| TigerLake        | 33        | 6.27%   |
| Alderlake Hybrid | 33        | 6.27%   |
| Skylake          | 29        | 5.51%   |
| Penryn           | 22        | 4.18%   |
| Unknown          | 18        | 3.42%   |
| CometLake        | 16        | 3.04%   |
| Zen 3            | 15        | 2.85%   |
| Broadwell        | 15        | 2.85%   |
| Zen+             | 14        | 2.66%   |
| Silvermont       | 12        | 2.28%   |
| Piledriver       | 12        | 2.28%   |
| Icelake          | 12        | 2.28%   |
| Zen 2            | 11        | 2.09%   |
| Goldmont plus    | 11        | 2.09%   |
| Core             | 11        | 2.09%   |
| Zen              | 8         | 1.52%   |
| Excavator        | 8         | 1.52%   |
| Westmere         | 7         | 1.33%   |
| K10              | 7         | 1.33%   |
| K10 Llano        | 4         | 0.76%   |
| Puma             | 3         | 0.57%   |
| Nehalem          | 3         | 0.57%   |
| Jaguar           | 3         | 0.57%   |
| Goldmont         | 3         | 0.57%   |
| K8 Hammer        | 2         | 0.38%   |
| Bobcat           | 2         | 0.38%   |
| Steamroller      | 1         | 0.19%   |
| K8 & K10 hybrid  | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 369       | 55.24%  |
| Nvidia | 173       | 25.9%   |
| AMD    | 126       | 18.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 40        | 5.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 4.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 2.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.37%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 2.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 14        | 2.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.92%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.78%   |
| Intel HD Graphics 620                                                                    | 11        | 1.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 1.33%   |
| Intel HD Graphics 630                                                                    | 9         | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.18%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 8         | 1.18%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 1.18%   |
| AMD Lucienne                                                                             | 8         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 0.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 0.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 5         | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.74%   |
| Intel HD Graphics 530                                                                    | 5         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.59%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 238       | 45.08%  |
| Intel + Nvidia | 99        | 18.75%  |
| 1 x AMD        | 91        | 17.23%  |
| 1 x Nvidia     | 62        | 11.74%  |
| Intel + AMD    | 20        | 3.79%   |
| AMD + Nvidia   | 12        | 2.27%   |
| 2 x AMD        | 3         | 0.57%   |
| Other          | 2         | 0.38%   |
| 2 x Nvidia     | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 459       | 86.93%  |
| Proprietary | 54        | 10.23%  |
| Unknown     | 15        | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 391       | 73.36%  |
| 1.01-2.0   | 34        | 6.38%   |
| 0.01-0.5   | 28        | 5.25%   |
| 3.01-4.0   | 27        | 5.07%   |
| 0.51-1.0   | 26        | 4.88%   |
| 7.01-8.0   | 13        | 2.44%   |
| 5.01-6.0   | 10        | 1.88%   |
| 2.01-3.0   | 2         | 0.38%   |
| 8.01-16.0  | 2         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 92        | 15.81%  |
| BOE                     | 74        | 12.71%  |
| LG Display              | 71        | 12.2%   |
| Samsung Electronics     | 63        | 10.82%  |
| Chimei Innolux          | 55        | 9.45%   |
| Dell                    | 24        | 4.12%   |
| Acer                    | 15        | 2.58%   |
| Apple                   | 14        | 2.41%   |
| Sharp                   | 13        | 2.23%   |
| Hewlett-Packard         | 13        | 2.23%   |
| Chi Mei Optoelectronics | 11        | 1.89%   |
| BenQ                    | 11        | 1.89%   |
| Ancor Communications    | 10        | 1.72%   |
| Goldstar                | 9         | 1.55%   |
| Unknown                 | 7         | 1.2%    |
| Philips                 | 7         | 1.2%    |
| PANDA                   | 7         | 1.2%    |
| InfoVision              | 7         | 1.2%    |
| AOC                     | 7         | 1.2%    |
| Lenovo                  | 5         | 0.86%   |
| ViewSonic               | 4         | 0.69%   |
| Sony                    | 4         | 0.69%   |
| Panasonic               | 4         | 0.69%   |
| Vizio                   | 3         | 0.52%   |
| Toshiba                 | 3         | 0.52%   |
| NEC Computers           | 3         | 0.52%   |
| Iiyama                  | 3         | 0.52%   |
| Eizo                    | 3         | 0.52%   |
| AUS                     | 3         | 0.52%   |
| ___                     | 2         | 0.34%   |
| STD                     | 2         | 0.34%   |
| Sceptre Tech            | 2         | 0.34%   |
| Insignia                | 2         | 0.34%   |
| CSO                     | 2         | 0.34%   |
| VOR                     | 1         | 0.17%   |
| VIZ                     | 1         | 0.17%   |
| Unknown (AAA)           | 1         | 0.17%   |
| STA                     | 1         | 0.17%   |
| SGT                     | 1         | 0.17%   |
| Sceptre                 | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.84%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.68%   |
| Sony TV SNYF301 1920x1080                                             | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 3         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.51%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.51%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.51%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 0.51%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.51%   |
| ___ LCD TV ___9000 1360x768                                           | 2         | 0.34%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.34%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.34%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.34%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2         | 0.34%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.34%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 0.34%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.34%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.34%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 257       | 46.56%  |
| 1366x768 (WXGA)    | 128       | 23.19%  |
| 3840x2160 (4K)     | 23        | 4.17%   |
| 1600x900 (HD+)     | 22        | 3.99%   |
| 1680x1050 (WSXGA+) | 16        | 2.9%    |
| 1920x1200 (WUXGA)  | 14        | 2.54%   |
| 1440x900 (WXGA+)   | 12        | 2.17%   |
| 1280x800 (WXGA)    | 12        | 2.17%   |
| 1280x1024 (SXGA)   | 11        | 1.99%   |
| 2560x1440 (QHD)    | 9         | 1.63%   |
| 1360x768           | 7         | 1.27%   |
| 2880x1800          | 4         | 0.72%   |
| 2560x1080          | 4         | 0.72%   |
| 2160x1440          | 4         | 0.72%   |
| Unknown            | 4         | 0.72%   |
| 3440x1440          | 3         | 0.54%   |
| 2560x1600          | 3         | 0.54%   |
| 1920x540           | 3         | 0.54%   |
| 3840x2400          | 2         | 0.36%   |
| 3840x1080          | 2         | 0.36%   |
| 3200x1080          | 2         | 0.36%   |
| 1280x720 (HD)      | 2         | 0.36%   |
| 1024x768 (XGA)     | 2         | 0.36%   |
| 5200x1080          | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 2496x1664          | 1         | 0.18%   |
| 2240x1400          | 1         | 0.18%   |
| 1920x515           | 1         | 0.18%   |
| 1600x1200          | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 192       | 33.16%  |
| 14      | 61        | 10.54%  |
| 13      | 56        | 9.67%   |
| 17      | 41        | 7.08%   |
| 24      | 32        | 5.53%   |
| 27      | 26        | 4.49%   |
| Unknown | 24        | 4.15%   |
| 23      | 19        | 3.28%   |
| 12      | 17        | 2.94%   |
| 21      | 14        | 2.42%   |
| 22      | 13        | 2.25%   |
| 31      | 11        | 1.9%    |
| 19      | 9         | 1.55%   |
| 11      | 9         | 1.55%   |
| 16      | 8         | 1.38%   |
| 72      | 6         | 1.04%   |
| 32      | 5         | 0.86%   |
| 18      | 5         | 0.86%   |
| 40      | 4         | 0.69%   |
| 34      | 4         | 0.69%   |
| 20      | 4         | 0.69%   |
| 84      | 3         | 0.52%   |
| 54      | 2         | 0.35%   |
| 48      | 2         | 0.35%   |
| 47      | 2         | 0.35%   |
| 69      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 46      | 1         | 0.17%   |
| 43      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 41      | 1         | 0.17%   |
| 36      | 1         | 0.17%   |
| 29      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 293       | 51.4%   |
| 501-600     | 71        | 12.46%  |
| 201-300     | 50        | 8.77%   |
| 351-400     | 45        | 7.89%   |
| 401-500     | 39        | 6.84%   |
| Unknown     | 24        | 4.21%   |
| 601-700     | 13        | 2.28%   |
| 701-800     | 10        | 1.75%   |
| 1501-2000   | 10        | 1.75%   |
| 1001-1500   | 8         | 1.4%    |
| 801-900     | 4         | 0.7%    |
| 901-1000    | 3         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 420       | 80%     |
| 16/10   | 60        | 11.43%  |
| Unknown | 16        | 3.05%   |
| 5/4     | 8         | 1.52%   |
| 4/3     | 6         | 1.14%   |
| 21/9    | 5         | 0.95%   |
| 32/9    | 4         | 0.76%   |
| 3/2     | 4         | 0.76%   |
| 6/5     | 1         | 0.19%   |
| 3.73    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 194       | 33.56%  |
| 81-90          | 96        | 16.61%  |
| 201-250        | 64        | 11.07%  |
| 121-130        | 32        | 5.54%   |
| 301-350        | 28        | 4.84%   |
| Unknown        | 24        | 4.15%   |
| 71-80          | 22        | 3.81%   |
| 351-500        | 20        | 3.46%   |
| 151-200        | 17        | 2.94%   |
| 61-70          | 16        | 2.77%   |
| More than 1000 | 14        | 2.42%   |
| 251-300        | 11        | 1.9%    |
| 141-150        | 11        | 1.9%    |
| 501-1000       | 11        | 1.9%    |
| 51-60          | 9         | 1.56%   |
| 111-120        | 6         | 1.04%   |
| 131-140        | 3         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 202       | 36.01%  |
| 101-120       | 137       | 24.42%  |
| 51-100        | 133       | 23.71%  |
| 161-240       | 35        | 6.24%   |
| Unknown       | 24        | 4.28%   |
| 1-50          | 17        | 3.03%   |
| More than 240 | 13        | 2.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 430       | 79.93%  |
| 2     | 83        | 15.43%  |
| 0     | 15        | 2.79%   |
| 3     | 10        | 1.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 295       | 33.11%  |
| Intel                                  | 286       | 32.1%   |
| Qualcomm Atheros                       | 87        | 9.76%   |
| Broadcom                               | 40        | 4.49%   |
| Ralink Technology                      | 20        | 2.24%   |
| TP-Link                                | 16        | 1.8%    |
| MediaTek                               | 16        | 1.8%    |
| Samsung Electronics                    | 15        | 1.68%   |
| Broadcom Limited                       | 12        | 1.35%   |
| Qualcomm Atheros Communications        | 9         | 1.01%   |
| Nvidia                                 | 7         | 0.79%   |
| NetGear                                | 7         | 0.79%   |
| Xiaomi                                 | 6         | 0.67%   |
| Ralink                                 | 6         | 0.67%   |
| Huawei Technologies                    | 6         | 0.67%   |
| ASUSTek Computer                       | 5         | 0.56%   |
| Qualcomm                               | 4         | 0.45%   |
| OPPO Electronics                       | 4         | 0.45%   |
| Microsoft                              | 4         | 0.45%   |
| Marvell Technology Group               | 4         | 0.45%   |
| ASIX Electronics                       | 4         | 0.45%   |
| Mercucys                               | 3         | 0.34%   |
| Lenovo                                 | 3         | 0.34%   |
| D-Link System                          | 3         | 0.34%   |
| vivo                                   | 2         | 0.22%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.22%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.22%   |
| Linksys                                | 2         | 0.22%   |
| JMicron Technology                     | 2         | 0.22%   |
| Ericsson Business Mobile Networks      | 2         | 0.22%   |
| D-Link                                 | 2         | 0.22%   |
| Apple                                  | 2         | 0.22%   |
| ZyXEL Communications                   | 1         | 0.11%   |
| STMicroelectronics                     | 1         | 0.11%   |
| Sagem                                  | 1         | 0.11%   |
| Microchip Technology                   | 1         | 0.11%   |
| ICS Advent                             | 1         | 0.11%   |
| Google                                 | 1         | 0.11%   |
| Gemtek                                 | 1         | 0.11%   |
| Fibocom                                | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 172       | 16.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28        | 2.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 26        | 2.47%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.71%   |
| Intel Wireless 8265 / 8275                                        | 16        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.33%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 1.33%   |
| Intel Wireless 7265                                               | 13        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.95%   |
| Intel Wireless 7260                                               | 10        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 9         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 8         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 8         | 0.76%   |
| Intel Wireless 8260                                               | 8         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.66%   |
| Realtek 802.11ac NIC                                              | 7         | 0.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7         | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.66%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 6         | 0.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 6         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 245       | 43.59%  |
| Realtek Semiconductor             | 109       | 19.4%   |
| Qualcomm Atheros                  | 66        | 11.74%  |
| Broadcom                          | 34        | 6.05%   |
| Ralink Technology                 | 20        | 3.56%   |
| TP-Link                           | 16        | 2.85%   |
| MediaTek                          | 13        | 2.31%   |
| Qualcomm Atheros Communications   | 9         | 1.6%    |
| Broadcom Limited                  | 9         | 1.6%    |
| NetGear                           | 7         | 1.25%   |
| Ralink                            | 6         | 1.07%   |
| ASUSTek Computer                  | 5         | 0.89%   |
| Microsoft                         | 4         | 0.71%   |
| Mercucys                          | 3         | 0.53%   |
| Marvell Technology Group          | 3         | 0.53%   |
| Linksys                           | 2         | 0.36%   |
| D-Link                            | 2         | 0.36%   |
| ZyXEL Communications              | 1         | 0.18%   |
| Sagem                             | 1         | 0.18%   |
| Qualcomm                          | 1         | 0.18%   |
| Gemtek                            | 1         | 0.18%   |
| Fibocom                           | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| Dell                              | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| Belkin Components                 | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 25        | 4.42%   |
| Intel Wi-Fi 6 AX201                                            | 23        | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 3.18%   |
| Intel Wireless 8265 / 8275                                     | 16        | 2.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.47%   |
| Intel Wi-Fi 6 AX200                                            | 14        | 2.47%   |
| Intel Wireless 7265                                            | 13        | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 2.12%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.77%   |
| Intel Wireless 7260                                            | 10        | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 9         | 1.59%   |
| Qualcomm Atheros AR9271 802.11n                                | 9         | 1.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 8         | 1.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 1.41%   |
| Intel Wireless 8260                                            | 8         | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7         | 1.24%   |
| Realtek 802.11ac NIC                                           | 7         | 1.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 7         | 1.24%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 6         | 1.06%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 6         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.06%   |
| Intel Wireless-AC 9260                                         | 6         | 1.06%   |
| Intel Wireless 3165                                            | 6         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 0.88%   |
| Intel Wireless 3160                                            | 5         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 248       | 52.99%  |
| Intel                                  | 114       | 24.36%  |
| Qualcomm Atheros                       | 31        | 6.62%   |
| Samsung Electronics                    | 15        | 3.21%   |
| Broadcom                               | 12        | 2.56%   |
| Nvidia                                 | 7         | 1.5%    |
| Xiaomi                                 | 6         | 1.28%   |
| OPPO Electronics                       | 4         | 0.85%   |
| ASIX Electronics                       | 4         | 0.85%   |
| Qualcomm                               | 3         | 0.64%   |
| MediaTek                               | 3         | 0.64%   |
| Lenovo                                 | 3         | 0.64%   |
| Broadcom Limited                       | 3         | 0.64%   |
| JMicron Technology                     | 2         | 0.43%   |
| Huawei Technologies                    | 2         | 0.43%   |
| D-Link System                          | 2         | 0.43%   |
| Apple                                  | 2         | 0.43%   |
| vivo                                   | 1         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.21%   |
| Marvell Technology Group               | 1         | 0.21%   |
| ICS Advent                             | 1         | 0.21%   |
| Google                                 | 1         | 0.21%   |
| DisplayLink                            | 1         | 0.21%   |
| Davicom Semiconductor                  | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 172       | 36.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 8.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28        | 5.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 4.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 1.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.47%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 1.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.26%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.26%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 5         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.84%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.84%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.63%   |
| Intel Ethernet Connection (16) I219-V                             | 3         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.63%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.42%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.42%   |
| OPPO WAIPIO-MTP _SN:AC53F926                                      | 2         | 0.42%   |
| OPPO RMX2027                                                      | 2         | 0.42%   |
| MediaTek Wiko U316AT                                              | 2         | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 482       | 52.11%  |
| Ethernet | 431       | 46.59%  |
| Modem    | 7         | 0.76%   |
| Unknown  | 5         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 366       | 66.91%  |
| Ethernet | 179       | 32.72%  |
| Unknown  | 2         | 0.37%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 303       | 57.28%  |
| 1     | 203       | 38.37%  |
| 0     | 12        | 2.27%   |
| 3     | 9         | 1.7%    |
| 5     | 1         | 0.19%   |
| 4     | 1         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 421       | 78.69%  |
| Yes     | 113       | 21.12%  |
| Unknown | 1         | 0.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 189       | 50.4%   |
| Realtek Semiconductor           | 36        | 9.6%    |
| Qualcomm Atheros Communications | 35        | 9.33%   |
| Broadcom                        | 19        | 5.07%   |
| IMC Networks                    | 15        | 4%      |
| Cambridge Silicon Radio         | 13        | 3.47%   |
| Foxconn / Hon Hai               | 12        | 3.2%    |
| Apple                           | 12        | 3.2%    |
| Lite-On Technology              | 11        | 2.93%   |
| MediaTek                        | 5         | 1.33%   |
| Dell                            | 5         | 1.33%   |
| ASUSTek Computer                | 5         | 1.33%   |
| Toshiba                         | 3         | 0.8%    |
| Marvell Semiconductor           | 3         | 0.8%    |
| TP-Link                         | 2         | 0.53%   |
| Realtek                         | 2         | 0.53%   |
| Ralink                          | 2         | 0.53%   |
| Dynex                           | 2         | 0.53%   |
| Logitech                        | 1         | 0.27%   |
| Hewlett-Packard                 | 1         | 0.27%   |
| Alps Electric                   | 1         | 0.27%   |
| Unknown                         | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 15.47%  |
| Intel AX201 Bluetooth                               | 55        | 14.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 7.73%   |
| Realtek Bluetooth Radio                             | 24        | 6.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 5.07%   |
| Intel Bluetooth Device                              | 17        | 4.53%   |
| Intel AX200 Bluetooth                               | 13        | 3.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 3.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 2.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 1.6%    |
| IMC Networks Bluetooth Radio                        | 6         | 1.6%    |
| MediaTek Wireless_Device                            | 5         | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.33%   |
| IMC Networks Bluetooth Device                       | 5         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.33%   |
| Apple Bluetooth Host Controller                     | 5         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.07%   |
| IMC Networks Wireless_Device                        | 4         | 1.07%   |
| Dell DW375 Bluetooth Module                         | 4         | 1.07%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.07%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.07%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.8%    |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.8%    |
| TP-Link UB500 Adapter                               | 2         | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.53%   |
| Realtek Bluetooth Radio                             | 2         | 0.53%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.53%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.53%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.53%   |
| Lite-On Wireless_Device                             | 2         | 0.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.53%   |
| Intel AX210 Bluetooth                               | 2         | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 414       | 60.09%  |
| Nvidia                   | 122       | 17.71%  |
| AMD                      | 120       | 17.42%  |
| C-Media Electronics      | 7         | 1.02%   |
| JMTek                    | 4         | 0.58%   |
| Logitech                 | 2         | 0.29%   |
| GN Netcom                | 2         | 0.29%   |
| Generalplus Technology   | 2         | 0.29%   |
| Corsair                  | 2         | 0.29%   |
| Yamaha                   | 1         | 0.15%   |
| Tenx Technology          | 1         | 0.15%   |
| SteelSeries ApS          | 1         | 0.15%   |
| Samson Technologies      | 1         | 0.15%   |
| Realtek Semiconductor    | 1         | 0.15%   |
| Razer USA                | 1         | 0.15%   |
| Micro Star International | 1         | 0.15%   |
| Lenovo                   | 1         | 0.15%   |
| Kingston Technology      | 1         | 0.15%   |
| GYROCOM C&C              | 1         | 0.15%   |
| Guillemot                | 1         | 0.15%   |
| FDUCE PRO AUDIO MADE     | 1         | 0.15%   |
| Conexant Systems         | 1         | 0.15%   |
| Apple                    | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 48        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 44        | 5.39%   |
| AMD Family 17h/19h HD Audio Controller                                     | 41        | 5.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 4.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 33        | 4.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 27        | 3.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 2.08%   |
| AMD FCH Azalia Controller                                                  | 17        | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.96%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.84%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 1.47%   |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 1.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.98%   |
| Nvidia Audio device                                                        | 8         | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 0.74%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 108       | 26.54%  |
| SK hynix            | 69        | 16.95%  |
| Micron Technology   | 59        | 14.5%   |
| Kingston            | 30        | 7.37%   |
| Crucial             | 28        | 6.88%   |
| Unknown             | 26        | 6.39%   |
| Corsair             | 15        | 3.69%   |
| Elpida              | 9         | 2.21%   |
| Ramaxel Technology  | 8         | 1.97%   |
| A-DATA Technology   | 8         | 1.97%   |
| Unknown (ABCD)      | 7         | 1.72%   |
| G.Skill             | 7         | 1.72%   |
| Nanya Technology    | 6         | 1.47%   |
| Team                | 5         | 1.23%   |
| Smart               | 3         | 0.74%   |
| Unknown             | 3         | 0.74%   |
| Transcend           | 2         | 0.49%   |
| PNY                 | 2         | 0.49%   |
| Unifosa             | 1         | 0.25%   |
| Timetec             | 1         | 0.25%   |
| Teikon              | 1         | 0.25%   |
| Silicon Power       | 1         | 0.25%   |
| Saikano             | 1         | 0.25%   |
| S                   | 1         | 0.25%   |
| Ramos Technology    | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| fef5                | 1         | 0.25%   |
| ChangXin Memory     | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| AMD                 | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 1.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.17%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.94%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.94%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.94%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.7%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.7%    |
| Unknown                                                          | 3         | 0.7%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.47%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.47%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.47%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.47%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.47%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.47%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 166       | 47.16%  |
| DDR3    | 111       | 31.53%  |
| LPDDR4  | 24        | 6.82%   |
| LPDDR3  | 12        | 3.41%   |
| Unknown | 12        | 3.41%   |
| DDR5    | 10        | 2.84%   |
| DDR2    | 8         | 2.27%   |
| SDRAM   | 4         | 1.14%   |
| LPDDR5  | 4         | 1.14%   |
| DDR     | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 248       | 71.06%  |
| DIMM         | 62        | 17.77%  |
| Row Of Chips | 35        | 10.03%  |
| Unknown      | 3         | 0.86%   |
| Chip         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 164       | 42.82%  |
| 4096  | 104       | 27.15%  |
| 16384 | 54        | 14.1%   |
| 2048  | 35        | 9.14%   |
| 32768 | 13        | 3.39%   |
| 1024  | 13        | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 75        | 19.63%  |
| 1600    | 71        | 18.59%  |
| 2667    | 65        | 17.02%  |
| 2400    | 28        | 7.33%   |
| 1334    | 17        | 4.45%   |
| 1333    | 17        | 4.45%   |
| 2133    | 16        | 4.19%   |
| 4800    | 11        | 2.88%   |
| 1867    | 10        | 2.62%   |
| 3600    | 8         | 2.09%   |
| 4267    | 7         | 1.83%   |
| 1067    | 5         | 1.31%   |
| Unknown | 5         | 1.31%   |
| 6400    | 4         | 1.05%   |
| 3266    | 4         | 1.05%   |
| 1800    | 4         | 1.05%   |
| 1066    | 4         | 1.05%   |
| 667     | 4         | 1.05%   |
| 3733    | 3         | 0.79%   |
| 800     | 3         | 0.79%   |
| 5600    | 2         | 0.52%   |
| 1866    | 2         | 0.52%   |
| 8400    | 1         | 0.26%   |
| 6800    | 1         | 0.26%   |
| 4266    | 1         | 0.26%   |
| 3866    | 1         | 0.26%   |
| 3534    | 1         | 0.26%   |
| 3533    | 1         | 0.26%   |
| 3100    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |
| 2666    | 1         | 0.26%   |
| 2200    | 1         | 0.26%   |
| 2132    | 1         | 0.26%   |
| 2048    | 1         | 0.26%   |
| 1227    | 1         | 0.26%   |
| 975     | 1         | 0.26%   |
| 533     | 1         | 0.26%   |
| 400     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Dymo-CoStar         | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Seiko Epson L120 Series      | 1         | 20%     |
| Samsung ML-2850 Series       | 1         | 20%     |
| HP OfficeJet Pro 7720 series | 1         | 20%     |
| Dymo-CoStar LabelWriter 450  | 1         | 20%     |
| Brother HL-1210W series      | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 89        | 23.92%  |
| IMC Networks                           | 41        | 11.02%  |
| Bison Electronics                      | 32        | 8.6%    |
| Microdia                               | 29        | 7.8%    |
| Realtek Semiconductor                  | 22        | 5.91%   |
| Quanta                                 | 21        | 5.65%   |
| Sunplus Innovation Technology          | 19        | 5.11%   |
| Apple                                  | 17        | 4.57%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.96%   |
| Syntek                                 | 10        | 2.69%   |
| Luxvisions Innotech Limited            | 8         | 2.15%   |
| Logitech                               | 7         | 1.88%   |
| Suyin                                  | 6         | 1.61%   |
| Ricoh                                  | 6         | 1.61%   |
| Silicon Motion                         | 5         | 1.34%   |
| Acer                                   | 5         | 1.34%   |
| Sonix Technology                       | 4         | 1.08%   |
| Samsung Electronics                    | 4         | 1.08%   |
| Lite-On Technology                     | 4         | 1.08%   |
| icSpring                               | 4         | 1.08%   |
| Microsoft                              | 3         | 0.81%   |
| Alcor Micro                            | 3         | 0.81%   |
| Primax Electronics                     | 2         | 0.54%   |
| LG Electronics                         | 2         | 0.54%   |
| Importek                               | 2         | 0.54%   |
| Generalplus Technology                 | 2         | 0.54%   |
| Creative Technology                    | 2         | 0.54%   |
| USB Camera CS                          | 1         | 0.27%   |
| Tobii Technology AB                    | 1         | 0.27%   |
| Teslong Camera                         | 1         | 0.27%   |
| SunplusIT                              | 1         | 0.27%   |
| Razer USA                              | 1         | 0.27%   |
| Jieli Technology                       | 1         | 0.27%   |
| Goertek Electronics                    | 1         | 0.27%   |
| Genesys Logic                          | 1         | 0.27%   |
| DLTDC0A9II090N                         | 1         | 0.27%   |
| ARC International                      | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |
| 8SSC21D67422V1SR28902JL                | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 18        | 4.8%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 3.2%    |
| IMC Networks Integrated Camera                      | 11        | 2.93%   |
| Realtek Integrated_Webcam_HD                        | 10        | 2.67%   |
| Bison HD Webcam                                     | 10        | 2.67%   |
| Syntek Integrated Camera                            | 8         | 2.13%   |
| Microdia Integrated_Webcam_HD                       | 8         | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 7         | 1.87%   |
| Quanta HD User Facing                               | 6         | 1.6%    |
| Chicony HP Truevision HD                            | 6         | 1.6%    |
| Chicony HD Webcam                                   | 6         | 1.6%    |
| Chicony HD User Facing                              | 6         | 1.6%    |
| Bison Integrated Camera                             | 6         | 1.6%    |
| Sunplus Integrated_Webcam_HD                        | 5         | 1.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 1.33%   |
| Chicony USB2.0 Camera                               | 5         | 1.33%   |
| Bison SunplusIT Integrated Camera                   | 5         | 1.33%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 1.07%   |
| Realtek Integrated Webcam HD                        | 4         | 1.07%   |
| Microdia Webcam Vitade AF                           | 4         | 1.07%   |
| icSpring camera                                     | 4         | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                        | 4         | 1.07%   |
| Chicony HP HD Camera                                | 4         | 1.07%   |
| Chicony EasyCamera                                  | 4         | 1.07%   |
| Bison EasyCamera                                    | 4         | 1.07%   |
| Apple Built-in iSight                               | 4         | 1.07%   |
| Quanta VGA WebCam                                   | 3         | 0.8%    |
| Quanta HP TrueVision HD Camera                      | 3         | 0.8%    |
| Microdia PC Microscope camera                       | 3         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_HD                | 3         | 0.8%    |
| Microdia Integrated Webcam                          | 3         | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.8%    |
| IMC Networks HD Camera                              | 3         | 0.8%    |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.8%    |
| Apple FaceTime HD Camera                            | 3         | 0.8%    |
| Alcor Micro USB 2.0 Camera                          | 3         | 0.8%    |
| Syntek Lenovo EasyCamera                            | 2         | 0.53%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 0.53%   |
| Sunplus Laptop Integrated Webcam FHD                | 2         | 0.53%   |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 29        | 39.19%  |
| Validity Sensors           | 23        | 31.08%  |
| Shenzhen Goodix Technology | 9         | 12.16%  |
| Elan Microelectronics      | 5         | 6.76%   |
| Upek                       | 3         | 4.05%   |
| LighTuning Technology      | 2         | 2.7%    |
| AuthenTec                  | 2         | 2.7%    |
| Samsung Electronics        | 1         | 1.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 9.46%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 8.11%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 6.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.05%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 4.05%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 4.05%   |
| Synaptics UWP WBDI Device                                                  | 3         | 4.05%   |
| Synaptics UWP WBDI                                                         | 3         | 4.05%   |
| Elan ELAN:Fingerprint                                                      | 3         | 4.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.7%    |
| Validity Sensors VFS491                                                    | 2         | 2.7%    |
| Synaptics WBDI                                                             | 2         | 2.7%    |
| Synaptics  WBDI                                                            | 2         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.7%    |
| Elan ELAN:ARM-M4                                                           | 2         | 2.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.35%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.35%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.35%   |
| Samsung Fingerprint Device                                                 | 1         | 1.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.35%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.35%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 14        | 56%     |
| Alcor Micro      | 7         | 28%     |
| Upek             | 1         | 4%      |
| SCM Microsystems | 1         | 4%      |
| OmniKey          | 1         | 4%      |
| O2 Micro         | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 28%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 28%     |
| Broadcom 5880                                                                | 4         | 16%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 4%      |
| OmniKey CardMan Smart@Link                                                   | 1         | 4%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 336       | 62.69%  |
| 1     | 161       | 30.04%  |
| 2     | 37        | 6.9%    |
| 3     | 2         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 75        | 32.47%  |
| Graphics card            | 45        | 19.48%  |
| Net/wireless             | 35        | 15.15%  |
| Chipcard                 | 23        | 9.96%   |
| Multimedia controller    | 17        | 7.36%   |
| Camera                   | 9         | 3.9%    |
| Storage                  | 6         | 2.6%    |
| Net/ethernet             | 5         | 2.16%   |
| Sound                    | 3         | 1.3%    |
| Network                  | 3         | 1.3%    |
| Bluetooth                | 3         | 1.3%    |
| Dvb card                 | 2         | 0.87%   |
| Communication controller | 2         | 0.87%   |
| Storage/raid             | 1         | 0.43%   |
| Modem                    | 1         | 0.43%   |
| Card reader              | 1         | 0.43%   |

